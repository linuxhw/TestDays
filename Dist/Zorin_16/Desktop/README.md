Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 1768

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | 8750                        | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HP            | 82FE 11                     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Biostar       | TPower X58                  | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| AZW           | U59                         | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Dell          | 0478VN A00                  | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ASUSTek       | H110M-A                     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Acer          | H81H3-M4                    | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | 1790                        | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| HP            | 1790                        | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| ASUSTek       | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| HP            | 1790                        | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Seco          | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gateway       | SX2851                      | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0GTK4K A02                  | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| ASUSTek       | H97-PLUS                    | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| HP            | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| HP            | 2AF3                        | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Unknown       | Unknown                     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| HP            | 304Ah                       | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Unknown       | Unknown                     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Acer          | EM61SM/EM61PM               | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| HP            | 822A                        | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| HP            | 2B60 MVB                    | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| HP            | 3397                        | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| HP            | 8055                        | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Gateway       | FMCP7AM                     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| HP            | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASRock        | B85M Pro4                   | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | 8055                        | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| ASUSTek       | Benicia                     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| HP            | 0AA8h                       | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Gigabyte      | Z77-D3H                     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| ASRock        | B550M/ac                    | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| MSI           | B250M PRO-VD                | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| Dell          | 0T656F A01                  | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| MSI           | Z97 GAMING 5                | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| MP            | MS-7848                     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| LORD ELECT... | GM965 Series                | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| ASUSTek       | P7H55-M LX                  | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Supermicro    | C7Q67 V1.01                 | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| ASRock        | Z170 Pro4                   | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| MSI           | Z97 GAMING 5                | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| MSI           | B75MA-P45                   | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| System76      | Thelio thelio-r2            | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 0J3C2F A00                  | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Pegatron      | Benicia                     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| HP            | 8350                        | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 71       | 5.39%   |
| 5.11.0-38-generic | 62       | 4.71%   |
| 5.15.0-67-generic | 57       | 4.33%   |
| 5.15.0-69-generic | 56       | 4.25%   |
| 5.11.0-27-generic | 56       | 4.25%   |
| 5.15.0-46-generic | 55       | 4.18%   |
| 5.11.0-40-generic | 50       | 3.8%    |
| 5.15.0-52-generic | 49       | 3.72%   |
| 5.13.0-39-generic | 49       | 3.72%   |
| 5.15.0-58-generic | 46       | 3.49%   |
| 5.15.0-60-generic | 45       | 3.42%   |
| 5.15.0-48-generic | 41       | 3.11%   |
| 5.11.0-41-generic | 41       | 3.11%   |
| 5.13.0-30-generic | 40       | 3.04%   |
| 5.13.0-40-generic | 38       | 2.89%   |
| 5.15.0-71-generic | 37       | 2.81%   |
| 5.11.0-43-generic | 36       | 2.73%   |
| 5.15.0-41-generic | 35       | 2.66%   |
| 5.11.0-37-generic | 35       | 2.66%   |
| 5.13.0-28-generic | 31       | 2.35%   |
| 5.11.0-34-generic | 31       | 2.35%   |
| 5.15.0-53-generic | 29       | 2.2%    |
| 5.13.0-35-generic | 28       | 2.13%   |
| 5.13.0-27-generic | 26       | 1.97%   |
| 5.13.0-41-generic | 25       | 1.9%    |
| 5.15.0-73-generic | 24       | 1.82%   |
| 5.13.0-52-generic | 24       | 1.82%   |
| 5.15.0-72-generic | 22       | 1.67%   |
| 5.13.0-44-generic | 21       | 1.59%   |
| 5.13.0-51-generic | 17       | 1.29%   |
| 5.15.0-43-generic | 13       | 0.99%   |
| 5.11.0-44-generic | 13       | 0.99%   |
| 5.11.0-36-generic | 12       | 0.91%   |
| 5.15.0-57-generic | 11       | 0.84%   |
| 5.13.0-37-generic | 11       | 0.84%   |
| 5.15.0-75-generic | 9        | 0.68%   |
| 5.13.0-48-generic | 8        | 0.61%   |
| 5.8.0-53-generic  | 7        | 0.53%   |
| 5.15.0-50-generic | 7        | 0.53%   |
| 5.8.0-50-generic  | 5        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 534      | 44.5%   |
| 5.11.0  | 334      | 27.83%  |
| 5.13.0  | 293      | 24.42%  |
| 5.8.0   | 25       | 2.08%   |
| 6.3.2   | 1        | 0.08%   |
| 6.2.7   | 1        | 0.08%   |
| 6.1.8   | 1        | 0.08%   |
| 6.1.7   | 1        | 0.08%   |
| 6.0.8   | 1        | 0.08%   |
| 5.4.0   | 1        | 0.08%   |
| 5.19.6  | 1        | 0.08%   |
| 5.19.2  | 1        | 0.08%   |
| 5.19.12 | 1        | 0.08%   |
| 5.17.9  | 1        | 0.08%   |
| 5.17.5  | 1        | 0.08%   |
| 5.17.1  | 1        | 0.08%   |
| 5.15.13 | 1        | 0.08%   |
| 5.14.0  | 1        | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 535      | 44.62%  |
| 5.11    | 334      | 27.86%  |
| 5.13    | 293      | 24.44%  |
| 5.8     | 25       | 2.09%   |
| 5.19    | 3        | 0.25%   |
| 5.17    | 3        | 0.25%   |
| 6.3     | 1        | 0.08%   |
| 6.2     | 1        | 0.08%   |
| 6.1     | 1        | 0.08%   |
| 6.0     | 1        | 0.08%   |
| 5.4     | 1        | 0.08%   |
| 5.14    | 1        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1146     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1001     | 86.82%  |
| XFCE       | 143      | 12.4%   |
| Unknown    | 5        | 0.43%   |
| Cinnamon   | 2        | 0.17%   |
| X-Cinnamon | 1        | 0.09%   |
| MATE       | 1        | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1137     | 98.96%  |
| Wayland | 10       | 0.87%   |
| Tty     | 1        | 0.09%   |
| Unknown | 1        | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 965      | 83.12%  |
| GDM3    | 84       | 7.24%   |
| GDM     | 83       | 7.15%   |
| LightDM | 28       | 2.41%   |
| TDM     | 1        | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 463      | 40.3%   |
| de_DE | 115      | 10.01%  |
| en_GB | 84       | 7.31%   |
| pt_BR | 80       | 6.96%   |
| fr_FR | 36       | 3.13%   |
| en_CA | 31       | 2.7%    |
| it_IT | 29       | 2.52%   |
| pl_PL | 26       | 2.26%   |
| en_AU | 26       | 2.26%   |
| es_ES | 24       | 2.09%   |
| en_IN | 23       | 2%      |
| nl_NL | 21       | 1.83%   |
| ru_RU | 17       | 1.48%   |
| es_AR | 16       | 1.39%   |
| hu_HU | 12       | 1.04%   |
| es_MX | 11       | 0.96%   |
| en_ZA | 10       | 0.87%   |
| pt_PT | 9        | 0.78%   |
| cs_CZ | 9        | 0.78%   |
| nl_BE | 7        | 0.61%   |
| fr_CA | 7        | 0.61%   |
| sv_SE | 6        | 0.52%   |
| nb_NO | 5        | 0.44%   |
| tr_TR | 4        | 0.35%   |
| ja_JP | 4        | 0.35%   |
| fi_FI | 4        | 0.35%   |
| es_VE | 4        | 0.35%   |
| es_CL | 4        | 0.35%   |
| en_NZ | 4        | 0.35%   |
| el_GR | 4        | 0.35%   |
| da_DK | 4        | 0.35%   |
| sl_SI | 3        | 0.26%   |
| sk_SK | 3        | 0.26%   |
| en_PH | 3        | 0.26%   |
| zh_CN | 2        | 0.17%   |
| fr_BE | 2        | 0.17%   |
| es_US | 2        | 0.17%   |
| es_GT | 2        | 0.17%   |
| es_EC | 2        | 0.17%   |
| es_CR | 2        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 613      | 52.98%  |
| EFI  | 544      | 47.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1081     | 93.92%  |
| Zfs      | 25       | 2.17%   |
| Overlay  | 15       | 1.3%    |
| Btrfs    | 10       | 0.87%   |
| Tmpfs    | 9        | 0.78%   |
| Xfs      | 5        | 0.43%   |
| Ext2     | 3        | 0.26%   |
| Ext3     | 2        | 0.17%   |
| Reiserfs | 1        | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1017     | 87.82%  |
| GPT     | 91       | 7.86%   |
| MBR     | 50       | 4.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1112     | 96.78%  |
| Yes       | 37       | 3.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1029     | 89.48%  |
| Yes       | 121      | 10.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 269      | 23.47%  |
| Gigabyte Technology                  | 184      | 16.06%  |
| Dell                                 | 123      | 10.73%  |
| MSI                                  | 119      | 10.38%  |
| Hewlett-Packard                      | 111      | 9.69%   |
| ASRock                               | 82       | 7.16%   |
| Lenovo                               | 51       | 4.45%   |
| Intel                                | 30       | 2.62%   |
| Acer                                 | 19       | 1.66%   |
| Biostar                              | 17       | 1.48%   |
| Unknown                              | 16       | 1.4%    |
| Fujitsu                              | 15       | 1.31%   |
| Foxconn                              | 15       | 1.31%   |
| Pegatron                             | 14       | 1.22%   |
| OEM                                  | 4        | 0.35%   |
| Google                               | 4        | 0.35%   |
| ECS                                  | 4        | 0.35%   |
| BESSTAR Tech                         | 4        | 0.35%   |
| Apple                                | 4        | 0.35%   |
| Alienware                            | 4        | 0.35%   |
| Positivo                             | 3        | 0.26%   |
| Medion                               | 3        | 0.26%   |
| Huanan                               | 3        | 0.26%   |
| Gateway                              | 3        | 0.26%   |
| AZW                                  | 3        | 0.26%   |
| Shuttle                              | 2        | 0.17%   |
| QIYIDA                               | 2        | 0.17%   |
| PCWare                               | 2        | 0.17%   |
| Packard Bell                         | 2        | 0.17%   |
| MAXSUN                               | 2        | 0.17%   |
| JGINYUE                              | 2        | 0.17%   |
| eMachines                            | 2        | 0.17%   |
| Wortmann AG                          | 1        | 0.09%   |
| WIPRO                                | 1        | 0.09%   |
| Vorke                                | 1        | 0.09%   |
| TYAN Computer                        | 1        | 0.09%   |
| System76                             | 1        | 0.09%   |
| Supermicro                           | 1        | 0.09%   |
| Soncview                             | 1        | 0.09%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 29       | 2.53%   |
| Unknown                          | 17       | 1.48%   |
| Dell OptiPlex 7010               | 10       | 0.87%   |
| MSI MS-7817                      | 8        | 0.7%    |
| Dell OptiPlex 790                | 8        | 0.7%    |
| Dell OptiPlex 780                | 7        | 0.61%   |
| MSI MS-7C02                      | 6        | 0.52%   |
| Gigabyte A320M-S2H               | 6        | 0.52%   |
| Dell OptiPlex 380                | 6        | 0.52%   |
| ASUS M5A78L-M/USB3               | 6        | 0.52%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.44%   |
| Dell Precision WorkStation T3500 | 5        | 0.44%   |
| Dell OptiPlex 990                | 5        | 0.44%   |
| Dell OptiPlex 3010               | 5        | 0.44%   |
| ASUS M5A97 R2.0                  | 5        | 0.44%   |
| MSI MS-7C37                      | 4        | 0.35%   |
| Intel H61                        | 4        | 0.35%   |
| HP ProDesk 600 G1 SFF            | 4        | 0.35%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.35%   |
| Gigabyte GA-78LMT-USB3 6.0       | 4        | 0.35%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.35%   |
| Gigabyte B450 AORUS M            | 4        | 0.35%   |
| Dell OptiPlex 7040               | 4        | 0.35%   |
| Dell OptiPlex 360                | 4        | 0.35%   |
| Dell OptiPlex 3020               | 4        | 0.35%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.35%   |
| ASUS PRIME X370-PRO              | 4        | 0.35%   |
| ASRock B450 Pro4                 | 4        | 0.35%   |
| OEM G41 775 ICH7 8712            | 3        | 0.26%   |
| MSI MS-7C91                      | 3        | 0.26%   |
| MSI MS-7B89                      | 3        | 0.26%   |
| MSI MS-7B86                      | 3        | 0.26%   |
| Intel X79M-S                     | 3        | 0.26%   |
| Intel H55                        | 3        | 0.26%   |
| HP ProDesk 600 G1 TWR            | 3        | 0.26%   |
| HP EliteDesk 800 G1 USDT         | 3        | 0.26%   |
| HP Compaq Pro 6300 MT            | 3        | 0.26%   |
| HP Compaq Elite 8300 SFF         | 3        | 0.26%   |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.26%   |
| Gigabyte H110M-H                 | 3        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 77       | 6.72%   |
| ASUS PRIME             | 42       | 3.66%   |
| ASUS ROG               | 36       | 3.14%   |
| Lenovo ThinkCentre     | 33       | 2.88%   |
| ASUS All               | 29       | 2.53%   |
| HP Compaq              | 28       | 2.44%   |
| ASUS TUF               | 24       | 2.09%   |
| Unknown                | 17       | 1.48%   |
| HP EliteDesk           | 16       | 1.4%    |
| Dell Precision         | 15       | 1.31%   |
| Gigabyte B450          | 11       | 0.96%   |
| Fujitsu ESPRIMO        | 11       | 0.96%   |
| HP ProDesk             | 10       | 0.87%   |
| HP Pavilion            | 10       | 0.87%   |
| Dell Inspiron          | 10       | 0.87%   |
| Gigabyte X570          | 9        | 0.79%   |
| ASUS M5A78L-M          | 9        | 0.79%   |
| Acer Aspire            | 9        | 0.79%   |
| MSI MS-7817            | 8        | 0.7%    |
| ASUS M5A97             | 8        | 0.7%    |
| Gigabyte GA-78LMT-USB3 | 7        | 0.61%   |
| Gigabyte B450M         | 7        | 0.61%   |
| Gigabyte A320M-S2H     | 7        | 0.61%   |
| ASRock B450M           | 7        | 0.61%   |
| ASRock B450            | 7        | 0.61%   |
| MSI MS-7C02            | 6        | 0.52%   |
| Lenovo IdeaCentre      | 6        | 0.52%   |
| Dell XPS               | 6        | 0.52%   |
| Dell Vostro            | 5        | 0.44%   |
| ASUS P8H61-M           | 5        | 0.44%   |
| MSI MS-7C37            | 4        | 0.35%   |
| Intel H61              | 4        | 0.35%   |
| Gigabyte GA-78LMT-S2   | 4        | 0.35%   |
| Gigabyte B550M         | 4        | 0.35%   |
| Gigabyte B550          | 4        | 0.35%   |
| ASUS P8Z77-V           | 4        | 0.35%   |
| ASUS P5K               | 4        | 0.35%   |
| ASRock 970             | 4        | 0.35%   |
| Acer Veriton           | 4        | 0.35%   |
| OEM G41                | 3        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 113      | 9.86%   |
| 2012    | 111      | 9.69%   |
| 2018    | 106      | 9.25%   |
| 2011    | 94       | 8.2%    |
| 2014    | 86       | 7.5%    |
| 2020    | 79       | 6.89%   |
| 2019    | 77       | 6.72%   |
| 2021    | 71       | 6.2%    |
| 2010    | 67       | 5.85%   |
| 2017    | 62       | 5.41%   |
| 2008    | 54       | 4.71%   |
| 2009    | 53       | 4.62%   |
| 2016    | 48       | 4.19%   |
| 2015    | 37       | 3.23%   |
| 2022    | 31       | 2.71%   |
| 2007    | 30       | 2.62%   |
| 2006    | 12       | 1.05%   |
| 2023    | 6        | 0.52%   |
| 2005    | 6        | 0.52%   |
| Unknown | 3        | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1146     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1073     | 93.22%  |
| Enabled  | 78       | 6.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1142     | 99.65%  |
| Yes  | 4        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 285      | 24.53%  |
| 8.01-16.0       | 255      | 21.94%  |
| 4.01-8.0        | 184      | 15.83%  |
| 3.01-4.0        | 167      | 14.37%  |
| 32.01-64.0      | 164      | 14.11%  |
| 64.01-256.0     | 37       | 3.18%   |
| 24.01-32.0      | 27       | 2.32%   |
| 1.01-2.0        | 26       | 2.24%   |
| 2.01-3.0        | 14       | 1.2%    |
| 0.51-1.0        | 2        | 0.17%   |
| More than 256.0 | 1        | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 462      | 37.2%   |
| 2.01-3.0   | 389      | 31.32%  |
| 3.01-4.0   | 170      | 13.69%  |
| 4.01-8.0   | 167      | 13.45%  |
| 8.01-16.0  | 28       | 2.25%   |
| 0.51-1.0   | 16       | 1.29%   |
| 16.01-24.0 | 6        | 0.48%   |
| 32.01-64.0 | 2        | 0.16%   |
| 24.01-32.0 | 1        | 0.08%   |
| 0.01-0.5   | 1        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 521      | 44.19%  |
| 2      | 330      | 27.99%  |
| 3      | 144      | 12.21%  |
| 4      | 84       | 7.12%   |
| 5      | 47       | 3.99%   |
| 6      | 28       | 2.37%   |
| 7      | 10       | 0.85%   |
| 8      | 7        | 0.59%   |
| 0      | 6        | 0.51%   |
| 51     | 1        | 0.08%   |
| 11     | 1        | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 577      | 50.13%  |
| Yes       | 574      | 49.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1131     | 98.69%  |
| No        | 15       | 1.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 590      | 50.99%  |
| No        | 567      | 49.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 763      | 66%     |
| Yes       | 393      | 34%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 295      | 25.65%  |
| Germany      | 120      | 10.43%  |
| Brazil       | 86       | 7.48%   |
| UK           | 80       | 6.96%   |
| Canada       | 42       | 3.65%   |
| Italy        | 38       | 3.3%    |
| Netherlands  | 35       | 3.04%   |
| France       | 32       | 2.78%   |
| Poland       | 30       | 2.61%   |
| Australia    | 26       | 2.26%   |
| Spain        | 25       | 2.17%   |
| India        | 23       | 2%      |
| Argentina    | 18       | 1.57%   |
| Hungary      | 16       | 1.39%   |
| Russia       | 15       | 1.3%    |
| Mexico       | 14       | 1.22%   |
| Denmark      | 13       | 1.13%   |
| Belgium      | 13       | 1.13%   |
| Sweden       | 12       | 1.04%   |
| Portugal     | 11       | 0.96%   |
| Norway       | 11       | 0.96%   |
| South Africa | 10       | 0.87%   |
| Czechia      | 10       | 0.87%   |
| Greece       | 9        | 0.78%   |
| Switzerland  | 8        | 0.7%    |
| Malaysia     | 8        | 0.7%    |
| Egypt        | 8        | 0.7%    |
| Chile        | 7        | 0.61%   |
| Venezuela    | 6        | 0.52%   |
| Turkey       | 6        | 0.52%   |
| Slovenia     | 6        | 0.52%   |
| Serbia       | 6        | 0.52%   |
| Finland      | 6        | 0.52%   |
| Slovakia     | 5        | 0.43%   |
| Romania      | 5        | 0.43%   |
| New Zealand  | 5        | 0.43%   |
| Japan        | 5        | 0.43%   |
| Indonesia    | 5        | 0.43%   |
| Croatia      | 4        | 0.35%   |
| Colombia     | 4        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 11       | 0.93%   |
| Munich         | 10       | 0.84%   |
| Rio de Janeiro | 7        | 0.59%   |
| Milan          | 7        | 0.59%   |
| Athens         | 7        | 0.59%   |
| Sao Paulo      | 6        | 0.51%   |
| Houston        | 6        | 0.51%   |
| Denver         | 6        | 0.51%   |
| Perth          | 5        | 0.42%   |
| Dallas         | 5        | 0.42%   |
| Copenhagen     | 5        | 0.42%   |
| Cape Town      | 5        | 0.42%   |
| Buenos Aires   | 5        | 0.42%   |
| Sydney         | 4        | 0.34%   |
| Richmond       | 4        | 0.34%   |
| Prague         | 4        | 0.34%   |
| Portland       | 4        | 0.34%   |
| Phoenix        | 4        | 0.34%   |
| Melbourne      | 4        | 0.34%   |
| Hamburg        | 4        | 0.34%   |
| Dayton         | 4        | 0.34%   |
| Calgary        | 4        | 0.34%   |
| Budapest       | 4        | 0.34%   |
| Brasília      | 4        | 0.34%   |
| Bengaluru      | 4        | 0.34%   |
| Atlanta        | 4        | 0.34%   |
| Adelaide       | 4        | 0.34%   |
| Zurich         | 3        | 0.25%   |
| Warsaw         | 3        | 0.25%   |
| Vienna         | 3        | 0.25%   |
| The Hague      | 3        | 0.25%   |
| Stuttgart      | 3        | 0.25%   |
| Santo André   | 3        | 0.25%   |
| Santiago       | 3        | 0.25%   |
| Salt Lake City | 3        | 0.25%   |
| Rome           | 3        | 0.25%   |
| Porto          | 3        | 0.25%   |
| Novosibirsk    | 3        | 0.25%   |
| Montreal       | 3        | 0.25%   |
| Milwaukee      | 3        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 408      | 638    | 19.9%   |
| WDC                       | 330      | 489    | 16.1%   |
| Samsung Electronics       | 270      | 413    | 13.17%  |
| Kingston                  | 126      | 179    | 6.15%   |
| Toshiba                   | 115      | 176    | 5.61%   |
| SanDisk                   | 108      | 134    | 5.27%   |
| Crucial                   | 85       | 103    | 4.15%   |
| Hitachi                   | 81       | 106    | 3.95%   |
| A-DATA Technology         | 31       | 39     | 1.51%   |
| China                     | 27       | 29     | 1.32%   |
| Unknown                   | 25       | 42     | 1.22%   |
| Silicon Motion            | 24       | 32     | 1.17%   |
| Intel                     | 24       | 28     | 1.17%   |
| Phison                    | 19       | 21     | 0.93%   |
| HGST                      | 17       | 25     | 0.83%   |
| SK hynix                  | 15       | 20     | 0.73%   |
| Intenso                   | 15       | 17     | 0.73%   |
| PNY                       | 14       | 19     | 0.68%   |
| Patriot                   | 14       | 18     | 0.68%   |
| Maxtor                    | 12       | 16     | 0.59%   |
| JMicron Technology        | 11       | 13     | 0.54%   |
| OCZ                       | 10       | 12     | 0.49%   |
| Micron/Crucial Technology | 10       | 12     | 0.49%   |
| Micron Technology         | 10       | 10     | 0.49%   |
| Lexar                     | 10       | 10     | 0.49%   |
| GOODRAM                   | 10       | 10     | 0.49%   |
| SPCC                      | 9        | 11     | 0.44%   |
| Gigabyte Technology       | 9        | 11     | 0.44%   |
| Phison Electronics        | 8        | 10     | 0.39%   |
| KingSpec                  | 8        | 10     | 0.39%   |
| Hewlett-Packard           | 8        | 12     | 0.39%   |
| Realtek Semiconductor     | 7        | 7      | 0.34%   |
| HS-SSD-C100               | 7        | 7      | 0.34%   |
| Apple                     | 7        | 7      | 0.34%   |
| XPG                       | 6        | 7      | 0.29%   |
| Netac                     | 6        | 9      | 0.29%   |
| Apacer                    | 6        | 8      | 0.29%   |
| Unknown                   | 6        | 7      | 0.29%   |
| Team                      | 5        | 7      | 0.24%   |
| Leven                     | 5        | 6      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 44       | 1.87%   |
| Kingston SA400S37240G 240GB SSD                     | 30       | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB                      | 25       | 1.06%   |
| Samsung SSD 860 EVO 500GB                           | 22       | 0.93%   |
| Crucial CT240BX500SSD1 240GB                        | 22       | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 18       | 0.76%   |
| Samsung NVMe SSD Drive 1TB                          | 17       | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 17       | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 16       | 0.68%   |
| Toshiba HDWD110 1TB                                 | 16       | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16       | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB                      | 16       | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 16       | 0.68%   |
| Toshiba DT01ACA100 1TB                              | 14       | 0.59%   |
| Seagate ST3500418AS 500GB                           | 14       | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 14       | 0.59%   |
| Kingston SA400S37480G 480GB SSD                     | 14       | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13       | 0.55%   |
| Toshiba DT01ACA050 500GB                            | 12       | 0.51%   |
| Seagate ST3500413AS 500GB                           | 12       | 0.51%   |
| Seagate ST1000DM003-1SB102 1TB                      | 12       | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 12       | 0.51%   |
| Unknown SD/MMC/MS PRO 250GB                         | 11       | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                      | 11       | 0.47%   |
| SanDisk NVMe SSD Drive 500GB                        | 11       | 0.47%   |
| SanDisk NVMe SSD Drive 1TB                          | 11       | 0.47%   |
| Samsung SSD 850 EVO 500GB                           | 11       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 11       | 0.47%   |
| Crucial CT500MX500SSD1 500GB                        | 11       | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10       | 0.42%   |
| Seagate ST3500312CS 500GB                           | 10       | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB                      | 10       | 0.42%   |
| Samsung SSD 870 EVO 1TB                             | 10       | 0.42%   |
| Samsung HD103SJ 1TB                                 | 10       | 0.42%   |
| SanDisk SSD PLUS 240GB                              | 9        | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 9        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 9        | 0.38%   |
| Crucial CT2000MX500SSD1 2TB                         | 9        | 0.38%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 8        | 0.34%   |
| Toshiba MQ01ABD100 1TB                              | 8        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 403      | 620    | 40.3%   |
| WDC                 | 301      | 435    | 30.1%   |
| Toshiba             | 99       | 157    | 9.9%    |
| Hitachi             | 81       | 106    | 8.1%    |
| Samsung Electronics | 61       | 80     | 6.1%    |
| HGST                | 17       | 25     | 1.7%    |
| Maxtor              | 12       | 16     | 1.2%    |
| Unknown             | 11       | 15     | 1.1%    |
| Apple               | 5        | 5      | 0.5%    |
| Super Talent        | 3        | 4      | 0.3%    |
| Hewlett-Packard     | 3        | 6      | 0.3%    |
| USB3.0              | 2        | 3      | 0.2%    |
| QUANTUM             | 1        | 1      | 0.1%    |
| ACASIS              | 1        | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 145      | 206    | 20%     |
| Kingston            | 104      | 139    | 14.34%  |
| Crucial             | 81       | 99     | 11.17%  |
| SanDisk             | 70       | 85     | 9.66%   |
| WDC                 | 35       | 45     | 4.83%   |
| A-DATA Technology   | 29       | 37     | 4%      |
| China               | 27       | 29     | 3.72%   |
| PNY                 | 14       | 19     | 1.93%   |
| Intel               | 14       | 16     | 1.93%   |
| Patriot             | 13       | 17     | 1.79%   |
| Toshiba             | 11       | 13     | 1.52%   |
| Intenso             | 11       | 13     | 1.52%   |
| OCZ                 | 10       | 12     | 1.38%   |
| Lexar               | 10       | 10     | 1.38%   |
| SPCC                | 9        | 11     | 1.24%   |
| GOODRAM             | 9        | 9      | 1.24%   |
| SK hynix            | 7        | 7      | 0.97%   |
| Micron Technology   | 7        | 7      | 0.97%   |
| KingSpec            | 7        | 9      | 0.97%   |
| Gigabyte Technology | 7        | 8      | 0.97%   |
| Netac               | 6        | 8      | 0.83%   |
| Apacer              | 6        | 8      | 0.83%   |
| Team                | 5        | 7      | 0.69%   |
| Leven               | 5        | 6      | 0.69%   |
| Hewlett-Packard     | 5        | 6      | 0.69%   |
| Transcend           | 3        | 3      | 0.41%   |
| Seagate             | 3        | 6      | 0.41%   |
| LITEON              | 3        | 3      | 0.41%   |
| KIOXIA-EXCERIA      | 3        | 7      | 0.41%   |
| Corsair             | 3        | 8      | 0.41%   |
| Acer                | 3        | 5      | 0.41%   |
| Unknown             | 3        | 3      | 0.41%   |
| Verbatim            | 2        | 2      | 0.28%   |
| Plextor             | 2        | 3      | 0.28%   |
| Pioneer             | 2        | 2      | 0.28%   |
| NN                  | 2        | 3      | 0.28%   |
| Kimtigo             | 2        | 2      | 0.28%   |
| FORESEE             | 2        | 3      | 0.28%   |
| Drevo               | 2        | 3      | 0.28%   |
| Dogfish             | 2        | 3      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 778      | 1474   | 45.05%  |
| SSD     | 603      | 931    | 34.92%  |
| NVMe    | 279      | 404    | 16.16%  |
| Unknown | 60       | 80     | 3.47%   |
| MMC     | 7        | 8      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1060     | 2362   | 74.07%  |
| NVMe | 274      | 391    | 19.15%  |
| SAS  | 90       | 136    | 6.29%   |
| MMC  | 7        | 8      | 0.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 792      | 1317   | 53.62%  |
| 0.51-1.0   | 410      | 631    | 27.76%  |
| 1.01-2.0   | 159      | 230    | 10.77%  |
| 3.01-4.0   | 44       | 102    | 2.98%   |
| 4.01-10.0  | 40       | 64     | 2.71%   |
| 2.01-3.0   | 28       | 42     | 1.9%    |
| 10.01-20.0 | 4        | 19     | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 345      | 28.77%  |
| 251-500        | 272      | 22.69%  |
| 501-1000       | 197      | 16.43%  |
| 1001-2000      | 124      | 10.34%  |
| More than 3000 | 84       | 7.01%   |
| 51-100         | 69       | 5.75%   |
| 2001-3000      | 41       | 3.42%   |
| 1-20           | 26       | 2.17%   |
| 21-50          | 25       | 2.09%   |
| Unknown        | 16       | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 414      | 33.12%  |
| 21-50          | 318      | 25.44%  |
| 51-100         | 155      | 12.4%   |
| 101-250        | 121      | 9.68%   |
| 251-500        | 75       | 6%      |
| 501-1000       | 64       | 5.12%   |
| More than 3000 | 43       | 3.44%   |
| 1001-2000      | 32       | 2.56%   |
| Unknown        | 16       | 1.28%   |
| 2001-3000      | 12       | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 5.13%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 2.56%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2.56%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1        | 1      | 2.56%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 2.56%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 2.56%   |
| WDC WD Green 2.5 1000GB SSD              | 1        | 1      | 2.56%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 2.56%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 2.56%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 2.56%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 2.56%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 2.56%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 2.56%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 2.56%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 2.56%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.56%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 2.56%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2.56%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.56%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.56%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.56%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 2.56%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 2.56%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 2.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 2.56%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 2.56%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 2.56%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 2.56%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 2.56%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 2.56%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 2.56%   |
| Maxtor STM3320613AS 320GB                | 1        | 1      | 2.56%   |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 2.56%   |
| Kingston SNS4151S316GD 16GB SSD          | 1        | 1      | 2.56%   |
| Intel SSDSC2CW060A3 64GB                 | 1        | 1      | 2.56%   |
| A-DATA Technology SX8200PNP 256GB        | 1        | 1      | 2.56%   |
| A-DATA Technology SU630 240GB SSD        | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 16     | 39.47%  |
| WDC                 | 6        | 7      | 15.79%  |
| Toshiba             | 6        | 6      | 15.79%  |
| Kingston            | 2        | 2      | 5.26%   |
| HGST                | 2        | 2      | 5.26%   |
| A-DATA Technology   | 2        | 2      | 5.26%   |
| Silicon Motion      | 1        | 1      | 2.63%   |
| Samsung Electronics | 1        | 1      | 2.63%   |
| OCZ                 | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 16     | 51.72%  |
| WDC                 | 5        | 6      | 17.24%  |
| Toshiba             | 5        | 5      | 17.24%  |
| HGST                | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 31     | 73.53%  |
| SSD  | 7        | 7      | 20.59%  |
| NVMe | 2        | 2      | 5.88%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1057     | 2583   | 88.53%  |
| Works    | 103      | 274    | 8.63%   |
| Malfunc  | 34       | 40     | 2.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 746      | 48.19%  |
| AMD                           | 367      | 23.71%  |
| Samsung Electronics           | 92       | 5.94%   |
| SanDisk                       | 46       | 2.97%   |
| ASMedia Technology            | 44       | 2.84%   |
| JMicron Technology            | 31       | 2%      |
| Kingston Technology Company   | 30       | 1.94%   |
| Phison Electronics            | 29       | 1.87%   |
| Nvidia                        | 27       | 1.74%   |
| Silicon Motion                | 26       | 1.68%   |
| Marvell Technology Group      | 23       | 1.49%   |
| Micron/Crucial Technology     | 14       | 0.9%    |
| ADATA Technology              | 11       | 0.71%   |
| SK hynix                      | 7        | 0.45%   |
| Silicon Image                 | 7        | 0.45%   |
| Realtek Semiconductor         | 7        | 0.45%   |
| VIA Technologies              | 6        | 0.39%   |
| Seagate Technology            | 6        | 0.39%   |
| KIOXIA                        | 5        | 0.32%   |
| Toshiba America Info Systems  | 4        | 0.26%   |
| MAXIO Technology (Hangzhou)   | 4        | 0.26%   |
| Micron Technology             | 3        | 0.19%   |
| Broadcom / LSI                | 3        | 0.19%   |
| INNOGRIT                      | 2        | 0.13%   |
| TenaFe                        | 1        | 0.06%   |
| OCZ Technology Group          | 1        | 0.06%   |
| Netac Technology              | 1        | 0.06%   |
| Lite-On Technology            | 1        | 0.06%   |
| Integrated Technology Express | 1        | 0.06%   |
| HighPoint Technologies        | 1        | 0.06%   |
| Beijing Starblaze Technology  | 1        | 0.06%   |
| Apple                         | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 198      | 10.11%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 116      | 5.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 75       | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 70       | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 67       | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 66       | 3.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 58       | 2.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 55       | 2.81%   |
| Intel SATA Controller [RAID mode]                                                       | 51       | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 50       | 2.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 44       | 2.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 44       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 44       | 2.25%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 40       | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 38       | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 36       | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 31       | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 30       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 29       | 1.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 28       | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 24       | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 21       | 1.07%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 21       | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 17       | 0.87%   |
| AMD FCH SATA Controller D                                                               | 17       | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 17       | 0.87%   |
| Phison E12 NVMe Controller                                                              | 15       | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                         | 15       | 0.77%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15       | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 14       | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 14       | 0.71%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 13       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 13       | 0.66%   |
| Samsung NVMe SSD Controller 980                                                         | 12       | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 12       | 0.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 12       | 0.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11       | 0.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 11       | 0.56%   |
| Nvidia MCP61 IDE                                                                        | 10       | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 913      | 57.82%  |
| IDE  | 300      | 19%     |
| NVMe | 273      | 17.29%  |
| RAID | 85       | 5.38%   |
| SAS  | 5        | 0.32%   |
| SCSI | 3        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 755      | 65.88%  |
| AMD    | 391      | 34.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 27       | 2.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 24       | 2.09%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 1.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 16       | 1.39%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 1.31%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 14       | 1.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 13       | 1.13%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 13       | 1.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 13       | 1.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.96%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 11       | 0.96%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 11       | 0.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 10       | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 10       | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 0.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 9        | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 9        | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 9        | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 9        | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 9        | 0.78%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 8        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8        | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 8        | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 8        | 0.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 0.7%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 7        | 0.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 7        | 0.61%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 7        | 0.61%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 7        | 0.61%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 7        | 0.61%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 7        | 0.61%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 7        | 0.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 7        | 0.61%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 0.61%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 7        | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 7        | 0.61%   |
| AMD FX-8350 Eight-Core Processor            | 7        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 228      | 19.86%  |
| Intel Core i7           | 125      | 10.89%  |
| AMD Ryzen 5             | 103      | 8.97%   |
| Intel Core i3           | 100      | 8.71%   |
| Intel Xeon              | 63       | 5.49%   |
| AMD Ryzen 7             | 49       | 4.27%   |
| AMD FX                  | 47       | 4.09%   |
| Intel Core 2 Duo        | 38       | 3.31%   |
| Intel Celeron           | 35       | 3.05%   |
| AMD Ryzen 9             | 35       | 3.05%   |
| Other                   | 31       | 2.7%    |
| Intel Core 2 Quad       | 30       | 2.61%   |
| Intel Pentium Dual-Core | 27       | 2.35%   |
| Intel Pentium           | 23       | 2%      |
| AMD Ryzen 3             | 21       | 1.83%   |
| AMD Athlon II X2        | 17       | 1.48%   |
| Intel Pentium Dual      | 16       | 1.39%   |
| AMD Phenom II X4        | 13       | 1.13%   |
| AMD A10                 | 13       | 1.13%   |
| Intel Core i9           | 12       | 1.05%   |
| AMD A8                  | 11       | 0.96%   |
| AMD Phenom II X6        | 9        | 0.78%   |
| AMD A6                  | 9        | 0.78%   |
| Intel Core 2            | 8        | 0.7%    |
| AMD Athlon 64 X2        | 8        | 0.7%    |
| Intel Pentium 4         | 7        | 0.61%   |
| AMD Athlon II X4        | 7        | 0.61%   |
| Intel Atom              | 6        | 0.52%   |
| AMD Athlon              | 6        | 0.52%   |
| Intel Pentium Gold      | 5        | 0.44%   |
| AMD E1                  | 4        | 0.35%   |
| AMD Athlon II X3        | 4        | 0.35%   |
| AMD A4                  | 4        | 0.35%   |
| AMD Ryzen 5 PRO         | 3        | 0.26%   |
| AMD PRO A10             | 3        | 0.26%   |
| AMD Phenom              | 3        | 0.26%   |
| AMD GX                  | 3        | 0.26%   |
| Intel Pentium D         | 2        | 0.17%   |
| AMD Sempron             | 2        | 0.17%   |
| AMD E2                  | 2        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 472      | 41.08%  |
| 2      | 323      | 28.11%  |
| 6      | 166      | 14.45%  |
| 8      | 91       | 7.92%   |
| 12     | 26       | 2.26%   |
| 1      | 24       | 2.09%   |
| 3      | 19       | 1.65%   |
| 16     | 15       | 1.31%   |
| 10     | 11       | 0.96%   |
| 28     | 1        | 0.09%   |
| 14     | 1        | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1138     | 99.3%   |
| 2      | 8        | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 607      | 52.92%  |
| 1      | 540      | 47.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1146     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 129      | 11.1%   |
| 0x306a9    | 89       | 7.66%   |
| Unknown    | 86       | 7.4%    |
| 0x206a7    | 81       | 6.97%   |
| 0x1067a    | 71       | 6.11%   |
| 0x08701021 | 48       | 4.13%   |
| 0x506e3    | 46       | 3.96%   |
| 0x06000852 | 34       | 2.93%   |
| 0x906ea    | 27       | 2.32%   |
| 0x906e9    | 21       | 1.81%   |
| 0x0800820d | 20       | 1.72%   |
| 0xa0653    | 19       | 1.64%   |
| 0x6fd      | 19       | 1.64%   |
| 0x0a201016 | 18       | 1.55%   |
| 0x010000c8 | 18       | 1.55%   |
| 0xa0655    | 16       | 1.38%   |
| 0x06001119 | 16       | 1.38%   |
| 0x6fb      | 15       | 1.29%   |
| 0x08108109 | 15       | 1.29%   |
| 0x906ed    | 13       | 1.12%   |
| 0x08001138 | 12       | 1.03%   |
| 0x0600063e | 12       | 1.03%   |
| 0xa0671    | 11       | 0.95%   |
| 0x906eb    | 11       | 0.95%   |
| 0x010000dc | 11       | 0.95%   |
| 0x010000db | 11       | 0.95%   |
| 0x206d7    | 10       | 0.86%   |
| 0x106e5    | 10       | 0.86%   |
| 0x08701013 | 10       | 0.86%   |
| 0x106a5    | 9        | 0.77%   |
| 0x90672    | 8        | 0.69%   |
| 0x306f2    | 8        | 0.69%   |
| 0x20655    | 8        | 0.69%   |
| 0x20652    | 8        | 0.69%   |
| 0x10676    | 8        | 0.69%   |
| 0x0a201009 | 8        | 0.69%   |
| 0x0a50000d | 7        | 0.6%    |
| 0x08101016 | 7        | 0.6%    |
| 0x06003106 | 7        | 0.6%    |
| 0x6f6      | 6        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 150      | 13.08%  |
| IvyBridge        | 96       | 8.37%   |
| SandyBridge      | 94       | 8.2%    |
| Penryn           | 84       | 7.32%   |
| KabyLake         | 83       | 7.24%   |
| Zen 2            | 73       | 6.36%   |
| Zen 3            | 59       | 5.14%   |
| K10              | 55       | 4.8%    |
| Piledriver       | 53       | 4.62%   |
| Skylake          | 48       | 4.18%   |
| Core             | 46       | 4.01%   |
| Zen+             | 38       | 3.31%   |
| Zen              | 38       | 3.31%   |
| CometLake        | 37       | 3.23%   |
| Nehalem          | 24       | 2.09%   |
| Westmere         | 22       | 1.92%   |
| Unknown          | 18       | 1.57%   |
| K8 Hammer        | 14       | 1.22%   |
| Silvermont       | 13       | 1.13%   |
| Excavator        | 12       | 1.05%   |
| Bulldozer        | 12       | 1.05%   |
| Icelake          | 11       | 0.96%   |
| NetBurst         | 10       | 0.87%   |
| Alderlake Hybrid | 10       | 0.87%   |
| Steamroller      | 7        | 0.61%   |
| Jaguar           | 7        | 0.61%   |
| Puma             | 6        | 0.52%   |
| Broadwell        | 6        | 0.52%   |
| K10 Llano        | 4        | 0.35%   |
| Goldmont plus    | 4        | 0.35%   |
| Bonnell          | 4        | 0.35%   |
| Bobcat           | 4        | 0.35%   |
| Tremont          | 2        | 0.17%   |
| Goldmont         | 2        | 0.17%   |
| TigerLake        | 1        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 461      | 37.6%   |
| Intel             | 397      | 32.38%  |
| AMD               | 365      | 29.77%  |
| VIA Technologies  | 2        | 0.16%   |
| ASPEED Technology | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 68       | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 49       | 3.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 40       | 3.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 40       | 3.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 30       | 2.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 28       | 2.24%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 27       | 2.16%   |
| Intel HD Graphics 530                                                       | 26       | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 21       | 1.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 20       | 1.6%    |
| Nvidia GK208B [GeForce GT 730]                                              | 19       | 1.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 17       | 1.36%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 17       | 1.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17       | 1.36%   |
| Nvidia GF119 [GeForce GT 610]                                               | 16       | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 16       | 1.28%   |
| Intel HD Graphics 630                                                       | 15       | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 15       | 1.2%    |
| AMD RS780L [Radeon 3000]                                                    | 13       | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 13       | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13       | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 12       | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                         | 12       | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 11       | 0.88%   |
| Nvidia GF108 [GeForce GT 730]                                               | 11       | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 0.88%   |
| Nvidia GF108 [GeForce GT 630]                                               | 10       | 0.8%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 9        | 0.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 9        | 0.72%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 8        | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 8        | 0.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 0.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 7        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 426      | 36.82%  |
| 1 x Intel            | 349      | 30.16%  |
| 1 x AMD              | 336      | 29.04%  |
| Intel + Nvidia       | 11       | 0.95%   |
| AMD + Nvidia         | 11       | 0.95%   |
| 2 x AMD              | 10       | 0.86%   |
| Intel + AMD          | 7        | 0.61%   |
| 2 x Nvidia           | 3        | 0.26%   |
| 1 x VIA              | 2        | 0.17%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.09%   |
| 1 x ASPEED           | 1        | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 797      | 68.71%  |
| Proprietary | 300      | 25.86%  |
| Unknown     | 63       | 5.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 500      | 42.66%  |
| 1.01-2.0   | 145      | 12.37%  |
| 0.51-1.0   | 135      | 11.52%  |
| 0.01-0.5   | 120      | 10.24%  |
| 3.01-4.0   | 101      | 8.62%   |
| 7.01-8.0   | 87       | 7.42%   |
| 8.01-16.0  | 35       | 2.99%   |
| 5.01-6.0   | 31       | 2.65%   |
| 2.01-3.0   | 14       | 1.19%   |
| 16.01-24.0 | 4        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 166      | 14.7%   |
| Dell                 | 107      | 9.48%   |
| Goldstar             | 106      | 9.39%   |
| Hewlett-Packard      | 89       | 7.88%   |
| Acer                 | 76       | 6.73%   |
| AOC                  | 66       | 5.85%   |
| Philips              | 58       | 5.14%   |
| BenQ                 | 44       | 3.9%    |
| Ancor Communications | 41       | 3.63%   |
| LG Electronics       | 27       | 2.39%   |
| ViewSonic            | 21       | 1.86%   |
| Unknown              | 21       | 1.86%   |
| Unknown              | 19       | 1.68%   |
| Lenovo               | 16       | 1.42%   |
| Iiyama               | 15       | 1.33%   |
| Sony                 | 13       | 1.15%   |
| Fujitsu Siemens      | 12       | 1.06%   |
| ASUSTek Computer     | 12       | 1.06%   |
| Sceptre Tech         | 11       | 0.97%   |
| NEC Computers        | 10       | 0.89%   |
| HPN                  | 10       | 0.89%   |
| Eizo                 | 10       | 0.89%   |
| Vizio                | 9        | 0.8%    |
| MSI                  | 8        | 0.71%   |
| Toshiba              | 6        | 0.53%   |
| Microstep            | 6        | 0.53%   |
| FUS                  | 6        | 0.53%   |
| AUS                  | 6        | 0.53%   |
| Panasonic            | 5        | 0.44%   |
| Vestel               | 4        | 0.35%   |
| Medion               | 4        | 0.35%   |
| Lenovo Group Limited | 4        | 0.35%   |
| ITE                  | 4        | 0.35%   |
| ___                  | 3        | 0.27%   |
| Unknown (XXX)        | 3        | 0.27%   |
| Sharp                | 3        | 0.27%   |
| Roku                 | 3        | 0.27%   |
| PKB                  | 3        | 0.27%   |
| Onkyo                | 3        | 0.27%   |
| JRY                  | 3        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 19       | 1.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 7        | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 6        | 0.5%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 6        | 0.5%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 5        | 0.42%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                 | 4        | 0.34%   |
| Philips LCD Monitor FTV 1920x1080                                       | 4        | 0.34%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 4        | 0.34%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 4        | 0.34%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 3        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 3        | 0.25%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 3        | 0.25%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.25%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 3        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 3        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 3        | 0.25%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch                 | 3        | 0.25%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 3        | 0.25%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 3        | 0.25%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch               | 3        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 3        | 0.25%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                       | 3        | 0.25%   |
| Dell LCD Monitor E228WFP                                                | 3        | 0.25%   |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                      | 3        | 0.25%   |
| ___ LCDTV16 ___9000 1360x768                                            | 2        | 0.17%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 2        | 0.17%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 2        | 0.17%   |
| Unknown LCD Monitor SAMSUNG                                             | 2        | 0.17%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch                | 2        | 0.17%   |
| Skyworth MATRIX6*2 SII9575 1920x1080 708x398mm 32.0-inch                | 2        | 0.17%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                   | 2        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 2        | 0.17%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 2        | 0.17%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch    | 2        | 0.17%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch    | 2        | 0.17%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch    | 2        | 0.17%   |
| Samsung Electronics SMT27A550 SAM07B8 1920x1080 598x336mm 27.0-inch     | 2        | 0.17%   |
| Samsung Electronics SMT-1934 SAM04FC 1280x1024 376x301mm 19.0-inch      | 2        | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 466      | 41.76%  |
| 3840x2160 (4K)     | 95       | 8.51%   |
| 1680x1050 (WSXGA+) | 65       | 5.82%   |
| 1280x1024 (SXGA)   | 61       | 5.47%   |
| 1600x900 (HD+)     | 56       | 5.02%   |
| 2560x1440 (QHD)    | 55       | 4.93%   |
| Unknown            | 51       | 4.57%   |
| 1366x768 (WXGA)    | 45       | 4.03%   |
| 1440x900 (WXGA+)   | 39       | 3.49%   |
| 1360x768           | 28       | 2.51%   |
| 1920x1200 (WUXGA)  | 25       | 2.24%   |
| 3440x1440          | 24       | 2.15%   |
| 3840x1080          | 23       | 2.06%   |
| 2560x1080          | 12       | 1.08%   |
| 1920x540           | 11       | 0.99%   |
| 1024x768 (XGA)     | 9        | 0.81%   |
| 1600x1200          | 6        | 0.54%   |
| 3840x1600          | 4        | 0.36%   |
| 4480x1440          | 3        | 0.27%   |
| 1280x720 (HD)      | 3        | 0.27%   |
| 5760x2160          | 2        | 0.18%   |
| 5760x1080          | 2        | 0.18%   |
| 4480x1080          | 2        | 0.18%   |
| 3600x1080          | 2        | 0.18%   |
| 3360x1080          | 2        | 0.18%   |
| 3200x1200          | 2        | 0.18%   |
| 3120x1050          | 2        | 0.18%   |
| 2944x1080          | 2        | 0.18%   |
| 2560x1600          | 2        | 0.18%   |
| 6400x1440          | 1        | 0.09%   |
| 5440x1080          | 1        | 0.09%   |
| 5120x1440          | 1        | 0.09%   |
| 5040x1050          | 1        | 0.09%   |
| 4480x1600          | 1        | 0.09%   |
| 4160x1440          | 1        | 0.09%   |
| 3780x2160          | 1        | 0.09%   |
| 3360x1050          | 1        | 0.09%   |
| 3040x1050          | 1        | 0.09%   |
| 2720x1024          | 1        | 0.09%   |
| 2464x900           | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 218      | 19.71%  |
| 27      | 111      | 10.04%  |
| 24      | 111      | 10.04%  |
| 23      | 98       | 8.86%   |
| 21      | 95       | 8.59%   |
| 19      | 68       | 6.15%   |
| 20      | 59       | 5.33%   |
| 31      | 54       | 4.88%   |
| 22      | 49       | 4.43%   |
| 18      | 45       | 4.07%   |
| 17      | 28       | 2.53%   |
| 34      | 22       | 1.99%   |
| 40      | 16       | 1.45%   |
| 15      | 15       | 1.36%   |
| 84      | 14       | 1.27%   |
| 54      | 11       | 0.99%   |
| 32      | 11       | 0.99%   |
| 72      | 10       | 0.9%    |
| 26      | 9        | 0.81%   |
| 36      | 6        | 0.54%   |
| 25      | 6        | 0.54%   |
| 28      | 5        | 0.45%   |
| 52      | 4        | 0.36%   |
| 35      | 4        | 0.36%   |
| 65      | 3        | 0.27%   |
| 49      | 3        | 0.27%   |
| 48      | 3        | 0.27%   |
| 33      | 3        | 0.27%   |
| 29      | 3        | 0.27%   |
| 57      | 2        | 0.18%   |
| 47      | 2        | 0.18%   |
| 43      | 2        | 0.18%   |
| 42      | 2        | 0.18%   |
| 41      | 2        | 0.18%   |
| 37      | 2        | 0.18%   |
| 86      | 1        | 0.09%   |
| 75      | 1        | 0.09%   |
| 74      | 1        | 0.09%   |
| 69      | 1        | 0.09%   |
| 60      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 299      | 28%     |
| 401-500     | 275      | 25.75%  |
| Unknown     | 218      | 20.41%  |
| 601-700     | 73       | 6.84%   |
| 701-800     | 42       | 3.93%   |
| 301-350     | 41       | 3.84%   |
| 351-400     | 32       | 3%      |
| 1001-1500   | 31       | 2.9%    |
| 1501-2000   | 28       | 2.62%   |
| 801-900     | 23       | 2.15%   |
| 901-1000    | 6        | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 589      | 57.24%  |
| Unknown | 203      | 19.73%  |
| 16/10   | 125      | 12.15%  |
| 5/4     | 54       | 5.25%   |
| 21/9    | 31       | 3.01%   |
| 4/3     | 18       | 1.75%   |
| 32/9    | 6        | 0.58%   |
| 6/5     | 2        | 0.19%   |
| 3/2     | 1        | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 283      | 25.99%  |
| Unknown        | 218      | 20.02%  |
| 151-200        | 162      | 14.88%  |
| 301-350        | 114      | 10.47%  |
| 351-500        | 100      | 9.18%   |
| 141-150        | 60       | 5.51%   |
| More than 1000 | 53       | 4.87%   |
| 251-300        | 46       | 4.22%   |
| 501-1000       | 36       | 3.31%   |
| 101-110        | 11       | 1.01%   |
| 111-120        | 4        | 0.37%   |
| 131-140        | 1        | 0.09%   |
| 121-130        | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 585      | 56.2%   |
| Unknown | 218      | 20.94%  |
| 101-120 | 148      | 14.22%  |
| 1-50    | 49       | 4.71%   |
| 121-160 | 30       | 2.88%   |
| 161-240 | 11       | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 929      | 79.95%  |
| 2     | 151      | 12.99%  |
| 0     | 66       | 5.68%   |
| 3     | 15       | 1.29%   |
| 4     | 1        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 729      | 42.96%  |
| Intel                             | 460      | 27.11%  |
| Qualcomm Atheros                  | 104      | 6.13%   |
| Broadcom                          | 58       | 3.42%   |
| Ralink Technology                 | 55       | 3.24%   |
| TP-Link                           | 44       | 2.59%   |
| MediaTek                          | 25       | 1.47%   |
| Nvidia                            | 23       | 1.36%   |
| Ralink                            | 22       | 1.3%    |
| Samsung Electronics               | 14       | 0.82%   |
| NetGear                           | 14       | 0.82%   |
| Broadcom Limited                  | 12       | 0.71%   |
| Microsoft                         | 11       | 0.65%   |
| Qualcomm Atheros Communications   | 10       | 0.59%   |
| D-Link                            | 10       | 0.59%   |
| Marvell Technology Group          | 9        | 0.53%   |
| Xiaomi                            | 8        | 0.47%   |
| D-Link System                     | 7        | 0.41%   |
| ASIX Electronics                  | 7        | 0.41%   |
| Huawei Technologies               | 6        | 0.35%   |
| ASUSTek Computer                  | 6        | 0.35%   |
| Edimax Technology                 | 5        | 0.29%   |
| Aquantia                          | 5        | 0.29%   |
| OPPO Electronics                  | 4        | 0.24%   |
| Motorola PCS                      | 4        | 0.24%   |
| Linksys                           | 4        | 0.24%   |
| DisplayLink                       | 3        | 0.18%   |
| Belkin Components                 | 3        | 0.18%   |
| VIA Technologies                  | 2        | 0.12%   |
| Sundance Technology Inc / IC Plus | 2        | 0.12%   |
| Motorola                          | 2        | 0.12%   |
| Gemtek                            | 2        | 0.12%   |
| AVM                               | 2        | 0.12%   |
| Arduino SA                        | 2        | 0.12%   |
| ZyDAS                             | 1        | 0.06%   |
| U-Blox                            | 1        | 0.06%   |
| TRENDnet                          | 1        | 0.06%   |
| T & A Mobile Phones               | 1        | 0.06%   |
| Sigma Sport                       | 1        | 0.06%   |
| Research In Motion                | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 556      | 28.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 3.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 3.01%   |
| Intel Wi-Fi 6 AX200                                               | 56       | 2.9%    |
| Intel I211 Gigabit Network Connection                             | 53       | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 2.07%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 2.02%   |
| Intel Ethernet Connection (2) I219-V                              | 33       | 1.71%   |
| Realtek 802.11ac NIC                                              | 28       | 1.45%   |
| Intel Ethernet Controller I225-V                                  | 28       | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 27       | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27       | 1.4%    |
| Ralink MT7601U Wireless Adapter                                   | 25       | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 19       | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18       | 0.93%   |
| Intel Wireless 7265                                               | 17       | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 14       | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13       | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 13       | 0.67%   |
| Nvidia MCP61 Ethernet                                             | 13       | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 0.67%   |
| Ralink RT5370 Wireless Adapter                                    | 12       | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 12       | 0.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 12       | 0.62%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 11       | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 11       | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 11       | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 11       | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11       | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 10       | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.52%   |
| Intel Wireless-AC 9260                                            | 10       | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9        | 0.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9        | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 179      | 27.25%  |
| Realtek Semiconductor                 | 174      | 26.48%  |
| Ralink Technology                     | 55       | 8.37%   |
| Qualcomm Atheros                      | 52       | 7.91%   |
| TP-Link                               | 42       | 6.39%   |
| Broadcom                              | 27       | 4.11%   |
| Ralink                                | 22       | 3.35%   |
| MediaTek                              | 21       | 3.2%    |
| NetGear                               | 14       | 2.13%   |
| Microsoft                             | 11       | 1.67%   |
| Qualcomm Atheros Communications       | 10       | 1.52%   |
| D-Link                                | 10       | 1.52%   |
| ASUSTek Computer                      | 6        | 0.91%   |
| Edimax Technology                     | 5        | 0.76%   |
| D-Link System                         | 5        | 0.76%   |
| Broadcom Limited                      | 5        | 0.76%   |
| Linksys                               | 4        | 0.61%   |
| Belkin Components                     | 3        | 0.46%   |
| Gemtek                                | 2        | 0.3%    |
| AVM                                   | 2        | 0.3%    |
| ZyDAS                                 | 1        | 0.15%   |
| Xiaomi                                | 1        | 0.15%   |
| TRENDnet                              | 1        | 0.15%   |
| Panasonic (Matsushita)                | 1        | 0.15%   |
| Ovislink                              | 1        | 0.15%   |
| Marvell Technology Group              | 1        | 0.15%   |
| ADMtek                                | 1        | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 56       | 8.4%    |
| Realtek 802.11ac NIC                                           | 28       | 4.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 27       | 4.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 27       | 4.05%   |
| Ralink MT7601U Wireless Adapter                                | 25       | 3.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18       | 2.7%    |
| Intel Wireless 7265                                            | 17       | 2.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 14       | 2.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13       | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 13       | 1.95%   |
| Ralink RT5370 Wireless Adapter                                 | 12       | 1.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12       | 1.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 11       | 1.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 11       | 1.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 10       | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10       | 1.5%    |
| Intel Wireless-AC 9260                                         | 10       | 1.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7        | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 7        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                | 7        | 1.05%   |
| Intel Wireless 7260                                            | 7        | 1.05%   |
| Intel Wireless 3165                                            | 7        | 1.05%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 6        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6        | 0.9%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 6        | 0.9%    |
| MediaTek WiFi                                                  | 6        | 0.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6        | 0.9%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5        | 0.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 5        | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5        | 0.75%   |
| NetGear A6210                                                  | 5        | 0.75%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 5        | 0.75%   |
| Microsoft Xbox 360 Wireless Adapter                            | 5        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 670      | 55.23%  |
| Intel                             | 360      | 29.68%  |
| Qualcomm Atheros                  | 54       | 4.45%   |
| Broadcom                          | 31       | 2.56%   |
| Nvidia                            | 23       | 1.9%    |
| Samsung Electronics               | 10       | 0.82%   |
| Marvell Technology Group          | 8        | 0.66%   |
| Xiaomi                            | 7        | 0.58%   |
| Broadcom Limited                  | 7        | 0.58%   |
| ASIX Electronics                  | 7        | 0.58%   |
| Huawei Technologies               | 5        | 0.41%   |
| Aquantia                          | 5        | 0.41%   |
| OPPO Electronics                  | 4        | 0.33%   |
| MediaTek                          | 4        | 0.33%   |
| DisplayLink                       | 3        | 0.25%   |
| VIA Technologies                  | 2        | 0.16%   |
| TP-Link                           | 2        | 0.16%   |
| Sundance Technology Inc / IC Plus | 2        | 0.16%   |
| Motorola PCS                      | 2        | 0.16%   |
| D-Link System                     | 2        | 0.16%   |
| Research In Motion                | 1        | 0.08%   |
| Qualcomm                          | 1        | 0.08%   |
| JMicron Technology                | 1        | 0.08%   |
| HMD Global                        | 1        | 0.08%   |
| Google                            | 1        | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 556      | 44.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 4.68%   |
| Intel I211 Gigabit Network Connection                             | 53       | 4.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 3.15%   |
| Intel Ethernet Connection (2) I219-V                              | 33       | 2.66%   |
| Intel Ethernet Controller I225-V                                  | 28       | 2.26%   |
| Intel Ethernet Connection I217-V                                  | 19       | 1.53%   |
| Nvidia MCP61 Ethernet                                             | 13       | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 12       | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 11       | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11       | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.73%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 5        | 0.4%    |
| Intel Ethernet Connection (14) I219-V                             | 5        | 0.4%    |
| Intel Ethernet Connection (12) I219-V                             | 5        | 0.4%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 4        | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.32%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.32%   |
| Intel 82578DC Gigabit Network Connection                          | 4        | 0.32%   |
| Huawei LLD-L21                                                    | 4        | 0.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1131     | 64.85%  |
| WiFi     | 592      | 33.94%  |
| Modem    | 17       | 0.97%   |
| Unknown  | 4        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 853      | 71.02%  |
| WiFi     | 345      | 28.73%  |
| Modem    | 2        | 0.17%   |
| Unknown  | 1        | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 744      | 64.36%  |
| 2     | 360      | 31.14%  |
| 3     | 37       | 3.2%    |
| 0     | 10       | 0.87%   |
| 5     | 2        | 0.17%   |
| 4     | 2        | 0.17%   |
| 7     | 1        | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 770      | 66.15%  |
| Yes  | 394      | 33.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 149      | 37.06%  |
| Cambridge Silicon Radio         | 81       | 20.15%  |
| Realtek Semiconductor           | 57       | 14.18%  |
| Broadcom                        | 22       | 5.47%   |
| ASUSTek Computer                | 20       | 4.98%   |
| Qualcomm Atheros Communications | 13       | 3.23%   |
| MediaTek                        | 10       | 2.49%   |
| IMC Networks                    | 9        | 2.24%   |
| Apple                           | 7        | 1.74%   |
| TP-Link                         | 6        | 1.49%   |
| Dynex                           | 5        | 1.24%   |
| Lite-On Technology              | 3        | 0.75%   |
| Foxconn / Hon Hai               | 3        | 0.75%   |
| Belkin Components               | 3        | 0.75%   |
| Integrated System Solution      | 2        | 0.5%    |
| Dell                            | 2        | 0.5%    |
| Actions                         | 2        | 0.5%    |
| Unknown                         | 2        | 0.5%    |
| Sitecom Europe                  | 1        | 0.25%   |
| Realtek                         | 1        | 0.25%   |
| National Semiconductor          | 1        | 0.25%   |
| Micro Star International        | 1        | 0.25%   |
| Edimax Technology               | 1        | 0.25%   |
| D-Link System                   | 1        | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 81       | 20.15%  |
| Realtek Bluetooth Radio                                   | 48       | 11.94%  |
| Intel AX200 Bluetooth                                     | 44       | 10.95%  |
| Intel Bluetooth wireless interface                        | 34       | 8.46%   |
| Intel AX210 Bluetooth                                     | 24       | 5.97%   |
| Intel Wireless-AC 3168 Bluetooth                          | 17       | 4.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 11       | 2.74%   |
| MediaTek Wireless_Device                                  | 10       | 2.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 10       | 2.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 8        | 1.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 8        | 1.99%   |
| Intel AX201 Bluetooth                                     | 7        | 1.74%   |
| TP-Link UB500 Adapter                                     | 6        | 1.49%   |
| IMC Networks Bluetooth Radio                              | 6        | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                            | 5        | 1.24%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]  | 5        | 1.24%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 4        | 1%      |
| Realtek RTL8821A Bluetooth                                | 3        | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 3        | 0.75%   |
| Lite-On Bluetooth Device                                  | 3        | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 3        | 0.75%   |
| Broadcom HP Portable Bumble Bee                           | 3        | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 3        | 0.75%   |
| ASUS Qualcomm Bluetooth 4.1                               | 3        | 0.75%   |
| ASUS Bluetooth Radio                                      | 3        | 0.75%   |
| Apple Bluetooth USB Host Controller                       | 3        | 0.75%   |
| Qualcomm Atheros  Bluetooth Device                        | 2        | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 2        | 0.5%    |
| Foxconn / Hon Hai Wireless_Device                         | 2        | 0.5%    |
| Dell BT Mini-Receiver                                     | 2        | 0.5%    |
| Broadcom Bluetooth 2.0+eDR dongle                         | 2        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 2        | 0.5%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 2        | 0.5%    |
| ASUS ASUS USB-BT500                                       | 2        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.5%    |
| Actions general adapter                                   | 2        | 0.5%    |
| Unknown                                                   | 2        | 0.5%    |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.25%   |
| Realtek RTL8723B Bluetooth                                | 1        | 0.25%   |
| Realtek Bluetooth Radio                                   | 1        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 733      | 38.6%   |
| AMD                                          | 488      | 25.7%   |
| Nvidia                                       | 432      | 22.75%  |
| C-Media Electronics                          | 45       | 2.37%   |
| Creative Labs                                | 20       | 1.05%   |
| Logitech                                     | 14       | 0.74%   |
| Kingston Technology                          | 13       | 0.68%   |
| ASUSTek Computer                             | 11       | 0.58%   |
| Texas Instruments                            | 9        | 0.47%   |
| JMTek                                        | 8        | 0.42%   |
| Generalplus Technology                       | 8        | 0.42%   |
| VIA Technologies                             | 7        | 0.37%   |
| Razer USA                                    | 7        | 0.37%   |
| Plantronics                                  | 6        | 0.32%   |
| Creative Technology                          | 6        | 0.32%   |
| GN Netcom                                    | 5        | 0.26%   |
| Realtek Semiconductor                        | 4        | 0.21%   |
| Tenx Technology                              | 3        | 0.16%   |
| SteelSeries ApS                              | 3        | 0.16%   |
| RODE Microphones                             | 3        | 0.16%   |
| Micro Star International                     | 3        | 0.16%   |
| Focusrite-Novation                           | 3        | 0.16%   |
| Astro Gaming                                 | 3        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.11%   |
| Yamaha                                       | 2        | 0.11%   |
| Sennheiser Communications                    | 2        | 0.11%   |
| KTMicro                                      | 2        | 0.11%   |
| Jieli Technology                             | 2        | 0.11%   |
| DCMT Technology                              | 2        | 0.11%   |
| Cambridge Audio                              | 2        | 0.11%   |
| Blue Microphones                             | 2        | 0.11%   |
| BEHRINGER International                      | 2        | 0.11%   |
| Audio-Technica                               | 2        | 0.11%   |
| XMOS                                         | 1        | 0.05%   |
| Valve Software                               | 1        | 0.05%   |
| Universal Audio                              | 1        | 0.05%   |
| Trust                                        | 1        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.05%   |
| Swissonic                                    | 1        | 0.05%   |
| Sony                                         | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 119      | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 106      | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 105      | 4.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 95       | 4.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 80       | 3.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 71       | 3.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 70       | 3.16%   |
| AMD Family 17h/19h HD Audio Controller                                            | 63       | 2.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 51       | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 47       | 2.12%   |
| AMD FCH Azalia Controller                                                         | 43       | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 41       | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 41       | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                        | 39       | 1.76%   |
| Intel 200 Series PCH HD Audio                                                     | 38       | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 32       | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 31       | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 29       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                     | 28       | 1.26%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 27       | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 27       | 1.22%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 27       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                                     | 26       | 1.17%   |
| Nvidia GF119 HDMI Audio Controller                                                | 24       | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 24       | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 23       | 1.04%   |
| AMD Navi 10 HDMI Audio                                                            | 22       | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 21       | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                     | 20       | 0.9%    |
| Nvidia High Definition Audio Controller                                           | 20       | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 20       | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                                     | 18       | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 18       | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 18       | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 18       | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                                     | 17       | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 17       | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                          | 17       | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 16       | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                | 14       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 31       | 17.61%  |
| Kingston            | 26       | 14.77%  |
| Samsung Electronics | 18       | 10.23%  |
| G.Skill             | 17       | 9.66%   |
| Corsair             | 15       | 8.52%   |
| SK hynix            | 14       | 7.95%   |
| Crucial             | 14       | 7.95%   |
| Team                | 8        | 4.55%   |
| Micron Technology   | 5        | 2.84%   |
| Unknown             | 4        | 2.27%   |
| Nanya Technology    | 3        | 1.7%    |
| Wilk                | 2        | 1.14%   |
| Unifosa             | 2        | 1.14%   |
| Ramaxel Technology  | 2        | 1.14%   |
| Patriot             | 2        | 1.14%   |
| Avant               | 2        | 1.14%   |
| A-DATA Technology   | 2        | 1.14%   |
| Transcend           | 1        | 0.57%   |
| SUPER KINGSTEK      | 1        | 0.57%   |
| Qimonda             | 1        | 0.57%   |
| Patriot Memory      | 1        | 0.57%   |
| Goldkey             | 1        | 0.57%   |
| Golden Empire       | 1        | 0.57%   |
| F7852C80            | 1        | 0.57%   |
| Elpida              | 1        | 0.57%   |
| AMD                 | 1        | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 4        | 2.04%   |
| Unknown                                                  | 4        | 2.04%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s       | 3        | 1.53%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 2        | 1.02%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.02%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 1.02%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s   | 2        | 1.02%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 2        | 1.02%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 1.02%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s  | 2        | 1.02%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 2        | 1.02%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 2        | 1.02%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 1.02%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 2        | 1.02%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 1.02%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 1.02%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 1.02%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s    | 2        | 1.02%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s  | 2        | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 2        | 1.02%   |
| Wilk RAM IRX3200D464L16A/16G 16384MB DIMM DDR4 3200MT/s  | 1        | 0.51%   |
| Wilk RAM GX3236D464S/8GSBS1 8192MB DIMM DDR4 3467MT/s    | 1        | 0.51%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s  | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM SDRAM                        | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 0.51%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 0.51%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.51%   |
| Unknown RAM Module 512MB DIMM 667MT/s                    | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s               | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                 | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s              | 1        | 0.51%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 45.22%  |
| DDR3    | 56       | 35.67%  |
| Unknown | 9        | 5.73%   |
| DDR2    | 8        | 5.1%    |
| SDRAM   | 7        | 4.46%   |
| DDR     | 3        | 1.91%   |
| DDR5    | 2        | 1.27%   |
| LPDDR4  | 1        | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 146      | 94.19%  |
| SODIMM       | 7        | 4.52%   |
| Row Of Chips | 1        | 0.65%   |
| FB-DIMM      | 1        | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 36.93%  |
| 4096  | 46       | 26.14%  |
| 2048  | 25       | 14.2%   |
| 16384 | 23       | 13.07%  |
| 32768 | 10       | 5.68%   |
| 1024  | 6        | 3.41%   |
| 512   | 1        | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 17.24%  |
| 1333    | 23       | 13.22%  |
| 3200    | 15       | 8.62%   |
| 3600    | 12       | 6.9%    |
| 2667    | 9        | 5.17%   |
| 2133    | 9        | 5.17%   |
| 2400    | 8        | 4.6%    |
| 3000    | 6        | 3.45%   |
| 800     | 6        | 3.45%   |
| 1800    | 5        | 2.87%   |
| 2933    | 4        | 2.3%    |
| 1866    | 4        | 2.3%    |
| Unknown | 4        | 2.3%    |
| 667     | 3        | 1.72%   |
| 4800    | 2        | 1.15%   |
| 3866    | 2        | 1.15%   |
| 3800    | 2        | 1.15%   |
| 3733    | 2        | 1.15%   |
| 3666    | 2        | 1.15%   |
| 3466    | 2        | 1.15%   |
| 3333    | 2        | 1.15%   |
| 2666    | 2        | 1.15%   |
| 1867    | 2        | 1.15%   |
| 1066    | 2        | 1.15%   |
| 5354    | 1        | 0.57%   |
| 4266    | 1        | 0.57%   |
| 4000    | 1        | 0.57%   |
| 3933    | 1        | 0.57%   |
| 3500    | 1        | 0.57%   |
| 3467    | 1        | 0.57%   |
| 3400    | 1        | 0.57%   |
| 3266    | 1        | 0.57%   |
| 2800    | 1        | 0.57%   |
| 2465    | 1        | 0.57%   |
| 2200    | 1        | 0.57%   |
| 1400    | 1        | 0.57%   |
| 976     | 1        | 0.57%   |
| 400     | 1        | 0.57%   |
| 333     | 1        | 0.57%   |
| 266     | 1        | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 12       | 22.64%  |
| Brother Industries    | 11       | 20.75%  |
| Canon                 | 10       | 18.87%  |
| Seiko Epson           | 8        | 15.09%  |
| Samsung Electronics   | 8        | 15.09%  |
| Lexmark International | 2        | 3.77%   |
| QinHeng Electronics   | 1        | 1.89%   |
| Konica Minolta        | 1        | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L3110 Series                     | 2        | 3.77%   |
| Samsung C460 Series                          | 2        | 3.77%   |
| HP LaserJet Professional P1102w              | 2        | 3.77%   |
| HP DeskJet 2130 series                       | 2        | 3.77%   |
| Canon LiDE 400                               | 2        | 3.77%   |
| Seiko Epson XP-7100 Series                   | 1        | 1.89%   |
| Seiko Epson XP-200 Series                    | 1        | 1.89%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.89%   |
| Seiko Epson L355 Series                      | 1        | 1.89%   |
| Seiko Epson ET-2820 Series                   | 1        | 1.89%   |
| Seiko Epson ET-2710 Series                   | 1        | 1.89%   |
| Samsung SCX-483x 5x3x Series                 | 1        | 1.89%   |
| Samsung SCX-4623 Series                      | 1        | 1.89%   |
| Samsung SCX-4200 series                      | 1        | 1.89%   |
| Samsung SCX-3400 Series                      | 1        | 1.89%   |
| Samsung ML-2950 Series                       | 1        | 1.89%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.89%   |
| QinHeng CH340S                               | 1        | 1.89%   |
| Lexmark International MX317dn                | 1        | 1.89%   |
| Lexmark International Laser Printer E232     | 1        | 1.89%   |
| Konica Minolta PagePro 1380MF                | 1        | 1.89%   |
| HP Smart Tank 510 series                     | 1        | 1.89%   |
| HP PSC 1100 series                           | 1        | 1.89%   |
| HP Officejet 6600                            | 1        | 1.89%   |
| HP OfficeJet 5600 (USBHUB)                   | 1        | 1.89%   |
| HP OfficeJet 4650 series                     | 1        | 1.89%   |
| HP ENVY Photo 7800 series                    | 1        | 1.89%   |
| HP ENVY 4520 series                          | 1        | 1.89%   |
| HP DeskJet 2700 series                       | 1        | 1.89%   |
| Canon TS3100 series                          | 1        | 1.89%   |
| Canon TR4500 series                          | 1        | 1.89%   |
| Canon PIXMA MG3200 Series                    | 1        | 1.89%   |
| Canon PIXMA MG2500 Series                    | 1        | 1.89%   |
| Canon MF240 Series UFRII LT                  | 1        | 1.89%   |
| Canon iP4200                                 | 1        | 1.89%   |
| Canon G3010 series                           | 1        | 1.89%   |
| Canon E410 series                            | 1        | 1.89%   |
| Brother VC-500W                              | 1        | 1.89%   |
| Brother QL-500 label printer                 | 1        | 1.89%   |
| Brother MFC-J1010DW                          | 1        | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 75%     |
| Hewlett-Packard | 2        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP ScanJet 2400c                   | 1        | 12.5%   |
| HP PSC 1200                        | 1        | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 12.5%   |
| Canon CanoScan LiDE 60             | 1        | 12.5%   |
| Canon CanoScan LiDE 110            | 1        | 12.5%   |
| Canon CanoScan LiDE 100            | 1        | 12.5%   |
| Canon CanoScan D660U               | 1        | 12.5%   |
| Canon CanoScan 8800F               | 1        | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 54       | 27.98%  |
| Microdia                      | 17       | 8.81%   |
| Microsoft                     | 15       | 7.77%   |
| Sunplus Innovation Technology | 10       | 5.18%   |
| Generalplus Technology        | 9        | 4.66%   |
| Samsung Electronics           | 8        | 4.15%   |
| Apple                         | 8        | 4.15%   |
| ARC International             | 7        | 3.63%   |
| Chicony Electronics           | 5        | 2.59%   |
| Realtek Semiconductor         | 4        | 2.07%   |
| Razer USA                     | 4        | 2.07%   |
| Jieli Technology              | 4        | 2.07%   |
| Tobii Technology AB           | 3        | 1.55%   |
| GEMBIRD                       | 3        | 1.55%   |
| Creative Technology           | 3        | 1.55%   |
| Z-Star Microelectronics       | 2        | 1.04%   |
| Xiongmai                      | 2        | 1.04%   |
| Suyin                         | 2        | 1.04%   |
| MacroSilicon                  | 2        | 1.04%   |
| lihappe8                      | 2        | 1.04%   |
| Guillemot                     | 2        | 1.04%   |
| Cubeternet                    | 2        | 1.04%   |
| A4Tech                        | 2        | 1.04%   |
| 2M UVC CAMERA                 | 2        | 1.04%   |
| WaveRider Communications      | 1        | 0.52%   |
| Unknown                       | 1        | 0.52%   |
| Trust                         | 1        | 0.52%   |
| Teslong Camera                | 1        | 0.52%   |
| Sunplus Technology            | 1        | 0.52%   |
| Sonix Technology              | 1        | 0.52%   |
| Ruision                       | 1        | 0.52%   |
| Pixart Imaging                | 1        | 0.52%   |
| Lenovo                        | 1        | 0.52%   |
| KYE Systems (Mouse Systems)   | 1        | 0.52%   |
| Intel                         | 1        | 0.52%   |
| INOGENI                       | 1        | 0.52%   |
| IMC Networks                  | 1        | 0.52%   |
| Huawei Technologies           | 1        | 0.52%   |
| Hewlett-Packard               | 1        | 0.52%   |
| Genesys Logic                 | 1        | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 14       | 7.18%   |
| Logitech HD Pro Webcam C920              | 12       | 6.15%   |
| Samsung Galaxy A5 (MTP)                  | 8        | 4.1%    |
| Microsoft LifeCam HD-3000                | 8        | 4.1%    |
| ARC International Camera                 | 7        | 3.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 7        | 3.59%   |
| Sunplus FHD Camera Microphone            | 5        | 2.56%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 2.05%   |
| Logitech HD Webcam C615                  | 4        | 2.05%   |
| Jieli USB PHY 2.0                        | 4        | 2.05%   |
| Generalplus GENERAL WEBCAM               | 4        | 2.05%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 2.05%   |
| Chicony HP High Definition 1MP Webcam    | 4        | 2.05%   |
| Tobii AB EyeChip                         | 3        | 1.54%   |
| Sunplus HD 720P webcam                   | 3        | 1.54%   |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.54%   |
| Microdia Webcam Vitade AF                | 3        | 1.54%   |
| Microdia USB 2.0 Camera                  | 3        | 1.54%   |
| Microdia REDRAGON Live Camera Audio      | 3        | 1.54%   |
| Microdia Integrated Camera               | 3        | 1.54%   |
| Logitech HD Webcam C910                  | 3        | 1.54%   |
| Logitech C920 PRO HD Webcam              | 3        | 1.54%   |
| Xiongmai web camera                      | 2        | 1.03%   |
| Suyin HD WebCam                          | 2        | 1.03%   |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 1.03%   |
| Microdia USB Live camera                 | 2        | 1.03%   |
| Logitech Webcam C925e                    | 2        | 1.03%   |
| Logitech Webcam C310                     | 2        | 1.03%   |
| Logitech QuickCam Pro for Notebooks      | 2        | 1.03%   |
| Logitech HD Webcam C525                  | 2        | 1.03%   |
| Logitech C922 Pro Stream Webcam          | 2        | 1.03%   |
| lihappe8 USB 2.0 Camera                  | 2        | 1.03%   |
| GEMBIRD USB2.0 PC CAMERA                 | 2        | 1.03%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam     | 2        | 1.03%   |
| Z-Star Venus USB2.0 Camera               | 1        | 0.51%   |
| Z-Star Integrated Camera                 | 1        | 0.51%   |
| WaveRider USB 2.0 Camera                 | 1        | 0.51%   |
| Unknown HD camera                        | 1        | 0.51%   |
| Trust Webcam                             | 1        | 0.51%   |
| Teslong Camera Teslong Camera            | 1        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 20%     |
| Advanced Card Systems             | 2        | 20%     |
| VASCO Data Security International | 1        | 10%     |
| SCM Microsystems                  | 1        | 10%     |
| Reiner SCT Kartensysteme          | 1        | 10%     |
| Fujitsu Siemens Computers         | 1        | 10%     |
| Chicony Electronics               | 1        | 10%     |
| Alcor Micro                       | 1        | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface               | 2        | 20%     |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 10%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 1        | 10%     |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                 | 1        | 10%     |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 10%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 1        | 10%     |
| Alcor Micro AU9540 Smartcard Reader                             | 1        | 10%     |
| Advanced Card Systems ACR39U                                    | 1        | 10%     |
| Advanced Card Systems ACR1281 1S Dual Reader                    | 1        | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 942      | 80.51%  |
| 1     | 202      | 17.26%  |
| 2     | 23       | 1.97%   |
| 3     | 2        | 0.17%   |
| 4     | 1        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 99       | 40.24%  |
| Graphics card            | 88       | 35.77%  |
| Communication controller | 12       | 4.88%   |
| Multimedia controller    | 9        | 3.66%   |
| Unassigned class         | 7        | 2.85%   |
| Chipcard                 | 7        | 2.85%   |
| Storage/raid             | 5        | 2.03%   |
| Modem                    | 4        | 1.63%   |
| Sound                    | 3        | 1.22%   |
| Bluetooth                | 3        | 1.22%   |
| Net/ethernet             | 2        | 0.81%   |
| Camera                   | 2        | 0.81%   |
| Storage/ide              | 1        | 0.41%   |
| Network                  | 1        | 0.41%   |
| Fingerprint reader       | 1        | 0.41%   |
| Dvb card                 | 1        | 0.41%   |
| Card reader              | 1        | 0.41%   |

