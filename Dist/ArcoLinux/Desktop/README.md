ArcoLinux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

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

Total: 2036

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B650 AORUS ELITE AX V2      | [cb100ba8bc](https://linux-hardware.org/?probe=cb100ba8bc) | May 08, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [6b97d23143](https://linux-hardware.org/?probe=6b97d23143) | May 07, 2024 |
| Gigabyte      | H81M-H                      | [5ea3b70747](https://linux-hardware.org/?probe=5ea3b70747) | May 06, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [4c7d6f1e6a](https://linux-hardware.org/?probe=4c7d6f1e6a) | May 05, 2024 |
| Dell          | 03NVJ6 A03                  | [fd0f0fad2d](https://linux-hardware.org/?probe=fd0f0fad2d) | May 04, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [9ca1c7c92f](https://linux-hardware.org/?probe=9ca1c7c92f) | May 04, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [055f5e4645](https://linux-hardware.org/?probe=055f5e4645) | May 04, 2024 |
| Gigabyte      | B365M H                     | [26c29ceb49](https://linux-hardware.org/?probe=26c29ceb49) | May 04, 2024 |
| MSI           | Z97 PC Mate                 | [277b1dc273](https://linux-hardware.org/?probe=277b1dc273) | May 04, 2024 |
| Dell          | 0C2XKD A01                  | [a246668749](https://linux-hardware.org/?probe=a246668749) | May 04, 2024 |
| HP            | 83F0                        | [896e46f757](https://linux-hardware.org/?probe=896e46f757) | May 03, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [82d8781e9b](https://linux-hardware.org/?probe=82d8781e9b) | May 03, 2024 |
| MSI           | MAG B460M MORTAR            | [4c66dab9c1](https://linux-hardware.org/?probe=4c66dab9c1) | May 03, 2024 |
| ASRock        | FM2A88X Extreme4+           | [64005c86c7](https://linux-hardware.org/?probe=64005c86c7) | May 02, 2024 |
| Intel         | H55                         | [b7cf243933](https://linux-hardware.org/?probe=b7cf243933) | May 02, 2024 |
| American M... | E5 Ver:3.2S                 | [748bf7d3e8](https://linux-hardware.org/?probe=748bf7d3e8) | May 01, 2024 |
| Dell          | 00F82W A00                  | [850344d254](https://linux-hardware.org/?probe=850344d254) | Apr 30, 2024 |
| Intel         | H61S                        | [6b425a599b](https://linux-hardware.org/?probe=6b425a599b) | Apr 30, 2024 |
| Acer          | H81-M1                      | [cf0c78b108](https://linux-hardware.org/?probe=cf0c78b108) | Apr 30, 2024 |
| Pegatron      | NARRA3                      | [ca94843c0a](https://linux-hardware.org/?probe=ca94843c0a) | Apr 29, 2024 |
| ASRock        | A320M/ac                    | [aeafdb6795](https://linux-hardware.org/?probe=aeafdb6795) | Apr 29, 2024 |
| HP            | 3029h                       | [1ae766a3ba](https://linux-hardware.org/?probe=1ae766a3ba) | Apr 28, 2024 |
| Dell          | 0WWJRX A01                  | [21af8ccdc8](https://linux-hardware.org/?probe=21af8ccdc8) | Apr 27, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [5004ab8c5b](https://linux-hardware.org/?probe=5004ab8c5b) | Apr 27, 2024 |
| Dell          | 0HD5W2 A01                  | [21e5ae7f3e](https://linux-hardware.org/?probe=21e5ae7f3e) | Apr 27, 2024 |
| Acer          | Aspire XC-605               | [d1ebb51ac8](https://linux-hardware.org/?probe=d1ebb51ac8) | Apr 25, 2024 |
| HP            | 2B36                        | [d52be34009](https://linux-hardware.org/?probe=d52be34009) | Apr 25, 2024 |
| Dell          | 02YYK5 A01                  | [9850b81106](https://linux-hardware.org/?probe=9850b81106) | Apr 25, 2024 |
| MSI           | Z97 PC Mate                 | [1d5f001265](https://linux-hardware.org/?probe=1d5f001265) | Apr 24, 2024 |
| Gigabyte      | A320M-S2H-CF                | [488c5e3d42](https://linux-hardware.org/?probe=488c5e3d42) | Apr 23, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [c2d77decab](https://linux-hardware.org/?probe=c2d77decab) | Apr 22, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [7d3fad530f](https://linux-hardware.org/?probe=7d3fad530f) | Apr 22, 2024 |
| HP            | 802F                        | [8a38f4d001](https://linux-hardware.org/?probe=8a38f4d001) | Apr 21, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [d9d4c8fda0](https://linux-hardware.org/?probe=d9d4c8fda0) | Apr 21, 2024 |
| HP            | 2B36                        | [4b5101fd25](https://linux-hardware.org/?probe=4b5101fd25) | Apr 21, 2024 |
| Dell          | 00F82W A00                  | [8d86d9c0a6](https://linux-hardware.org/?probe=8d86d9c0a6) | Apr 21, 2024 |
| HP            | 802F                        | [cb7a0fabc8](https://linux-hardware.org/?probe=cb7a0fabc8) | Apr 21, 2024 |
| MSI           | A320M PRO-VD/S              | [1c4a853ae2](https://linux-hardware.org/?probe=1c4a853ae2) | Apr 21, 2024 |
| Gigabyte      | Z270X-Gaming 5              | [eb8b3c8970](https://linux-hardware.org/?probe=eb8b3c8970) | Apr 21, 2024 |
| ASRock        | A320M-HDV                   | [5b29bd1ecf](https://linux-hardware.org/?probe=5b29bd1ecf) | Apr 21, 2024 |
| Gigabyte      | B550 GAMING X V2            | [713e7bdc86](https://linux-hardware.org/?probe=713e7bdc86) | Apr 20, 2024 |
| Gigabyte      | B550 GAMING X V2            | [24e31227a4](https://linux-hardware.org/?probe=24e31227a4) | Apr 20, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [4eade3ca4d](https://linux-hardware.org/?probe=4eade3ca4d) | Apr 20, 2024 |
| HP            | 18E7                        | [1d707ddc17](https://linux-hardware.org/?probe=1d707ddc17) | Apr 20, 2024 |
| Gigabyte      | Z390 DESIGNARE-CF           | [19d3a51e2c](https://linux-hardware.org/?probe=19d3a51e2c) | Apr 20, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [f83f880363](https://linux-hardware.org/?probe=f83f880363) | Apr 20, 2024 |
| Unknown       | Unknown                     | [bda99e9656](https://linux-hardware.org/?probe=bda99e9656) | Apr 20, 2024 |
| Unknown       | Unknown                     | [4f687b566d](https://linux-hardware.org/?probe=4f687b566d) | Apr 20, 2024 |
| ASUSTek       | D425MC                      | [7be445a3bf](https://linux-hardware.org/?probe=7be445a3bf) | Apr 19, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [5378e196b0](https://linux-hardware.org/?probe=5378e196b0) | Apr 19, 2024 |
| ASUSTek       | PRIME Z370-A                | [3c0df82050](https://linux-hardware.org/?probe=3c0df82050) | Apr 19, 2024 |
| DFI           | HD101-H81D                  | [a6b195fbc8](https://linux-hardware.org/?probe=a6b195fbc8) | Apr 18, 2024 |
| Acer          | Aspire XC-605               | [d9014cb8e6](https://linux-hardware.org/?probe=d9014cb8e6) | Apr 18, 2024 |
| Unknown       | Unknown                     | [8424abb1e7](https://linux-hardware.org/?probe=8424abb1e7) | Apr 18, 2024 |
| ASRock        | B450 Pro4                   | [78d6c9eb2c](https://linux-hardware.org/?probe=78d6c9eb2c) | Apr 18, 2024 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [05c7db4b10](https://linux-hardware.org/?probe=05c7db4b10) | Apr 18, 2024 |
| Dell          | 0V8F20 A01                  | [5b99cd208d](https://linux-hardware.org/?probe=5b99cd208d) | Apr 17, 2024 |
| Shenzhen M... | F7BFC                       | [f95926a55e](https://linux-hardware.org/?probe=f95926a55e) | Apr 17, 2024 |
| Lenovo        | 36EB NOK                    | [c83418c56a](https://linux-hardware.org/?probe=c83418c56a) | Apr 17, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [86e82df824](https://linux-hardware.org/?probe=86e82df824) | Apr 17, 2024 |
| Biostar       | H61MLC                      | [8f70d8bdb9](https://linux-hardware.org/?probe=8f70d8bdb9) | Apr 16, 2024 |
| Acer          | H81-M1                      | [1c508f5a38](https://linux-hardware.org/?probe=1c508f5a38) | Apr 16, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a9de65b3dc](https://linux-hardware.org/?probe=a9de65b3dc) | Apr 16, 2024 |
| MSI           | PRO B650-S WIFI             | [580df50da1](https://linux-hardware.org/?probe=580df50da1) | Apr 16, 2024 |
| ASUSTek       | PRIME Z370-A                | [a8d2383fa0](https://linux-hardware.org/?probe=a8d2383fa0) | Apr 15, 2024 |
| ASUSTek       | PRIME Z490-A                | [154867d800](https://linux-hardware.org/?probe=154867d800) | Apr 14, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | [20e54ade99](https://linux-hardware.org/?probe=20e54ade99) | Apr 13, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b8f62dc34c](https://linux-hardware.org/?probe=b8f62dc34c) | Apr 13, 2024 |
| MSI           | B450M-A PRO MAX             | [705cf8272f](https://linux-hardware.org/?probe=705cf8272f) | Apr 12, 2024 |
| MSI           | B450M-A PRO MAX             | [94b1f5a4cd](https://linux-hardware.org/?probe=94b1f5a4cd) | Apr 12, 2024 |
| HP            | 3397                        | [31cfb1bfb0](https://linux-hardware.org/?probe=31cfb1bfb0) | Apr 12, 2024 |
| ASUSTek       | PRIME Z490-A                | [bc81c86e6b](https://linux-hardware.org/?probe=bc81c86e6b) | Apr 12, 2024 |
| MSI           | A320M PRO-VD/S              | [fad7dacfc2](https://linux-hardware.org/?probe=fad7dacfc2) | Apr 10, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [4586d481ed](https://linux-hardware.org/?probe=4586d481ed) | Apr 10, 2024 |
| Shenzhen M... | F7BFC                       | [94ccbc78f1](https://linux-hardware.org/?probe=94ccbc78f1) | Apr 10, 2024 |
| ASRock        | Z370 Extreme4               | [89b87e5d2e](https://linux-hardware.org/?probe=89b87e5d2e) | Apr 10, 2024 |
| MSI           | B450M MORTAR MAX            | [2a497ea609](https://linux-hardware.org/?probe=2a497ea609) | Apr 10, 2024 |
| ASRock        | B450M Pro4                  | [c6e809a3fa](https://linux-hardware.org/?probe=c6e809a3fa) | Apr 08, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [75f2fd247a](https://linux-hardware.org/?probe=75f2fd247a) | Apr 08, 2024 |
| Gigabyte      | GA-880GM-UD2H               | [8bd7df2e63](https://linux-hardware.org/?probe=8bd7df2e63) | Apr 07, 2024 |
| AZW           | SER V1                      | [399ba2c254](https://linux-hardware.org/?probe=399ba2c254) | Apr 07, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [0795129140](https://linux-hardware.org/?probe=0795129140) | Apr 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [354d98798a](https://linux-hardware.org/?probe=354d98798a) | Apr 06, 2024 |
| MSI           | B450M PRO-VDH               | [967dca41d6](https://linux-hardware.org/?probe=967dca41d6) | Apr 05, 2024 |
| Shenzhen M... | F7BFC                       | [bbe75de967](https://linux-hardware.org/?probe=bbe75de967) | Apr 04, 2024 |
| MSI           | B450M-A PRO MAX             | [c139fcd8d6](https://linux-hardware.org/?probe=c139fcd8d6) | Apr 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | [97239eebc7](https://linux-hardware.org/?probe=97239eebc7) | Apr 03, 2024 |
| HP            | 21D0                        | [8097b780d4](https://linux-hardware.org/?probe=8097b780d4) | Apr 03, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [a00d3e21e2](https://linux-hardware.org/?probe=a00d3e21e2) | Apr 03, 2024 |
| Intel         | B75                         | [b090c94f7f](https://linux-hardware.org/?probe=b090c94f7f) | Apr 02, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [73bcf62b59](https://linux-hardware.org/?probe=73bcf62b59) | Apr 01, 2024 |
| ECS           | A960M-M3                    | [dce366554b](https://linux-hardware.org/?probe=dce366554b) | Apr 01, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [cf3a89d3d4](https://linux-hardware.org/?probe=cf3a89d3d4) | Apr 01, 2024 |
| MSI           | PRO B550M-P GEN3            | [79c408e0e7](https://linux-hardware.org/?probe=79c408e0e7) | Mar 30, 2024 |
| Gigabyte      | H55M-S2V                    | [b6b0564fdc](https://linux-hardware.org/?probe=b6b0564fdc) | Mar 29, 2024 |
| ASRock        | Z390 Phantom Gaming 4-CB    | [fca7774b11](https://linux-hardware.org/?probe=fca7774b11) | Mar 29, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [fd22085109](https://linux-hardware.org/?probe=fd22085109) | Mar 29, 2024 |
| Foxconn       | 2A8C                        | [7160e6163b](https://linux-hardware.org/?probe=7160e6163b) | Mar 27, 2024 |
| Huanan        | X79 ZHIZUN V7.1             | [f2b2f4d41d](https://linux-hardware.org/?probe=f2b2f4d41d) | Mar 27, 2024 |
| Gigabyte      | Z97P-D3                     | [269ee0ed72](https://linux-hardware.org/?probe=269ee0ed72) | Mar 26, 2024 |
| Gigabyte      | 970A-DS3P                   | [23122d3ad4](https://linux-hardware.org/?probe=23122d3ad4) | Mar 26, 2024 |
| ASUSTek       | PRIME Z490-A                | [da725303e1](https://linux-hardware.org/?probe=da725303e1) | Mar 25, 2024 |
| Gigabyte      | Z390 DESIGNARE-CF           | [8bcc48c4f8](https://linux-hardware.org/?probe=8bcc48c4f8) | Mar 25, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | [302c96a79d](https://linux-hardware.org/?probe=302c96a79d) | Mar 24, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | [633d507169](https://linux-hardware.org/?probe=633d507169) | Mar 24, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [74e95f0015](https://linux-hardware.org/?probe=74e95f0015) | Mar 24, 2024 |
| Lenovo        | 0B98401 PRO                 | [5059aeedf0](https://linux-hardware.org/?probe=5059aeedf0) | Mar 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [e71e7c70d9](https://linux-hardware.org/?probe=e71e7c70d9) | Mar 23, 2024 |
| MSI           | X399 GAMING PRO CARBON A... | [7c0f257328](https://linux-hardware.org/?probe=7c0f257328) | Mar 22, 2024 |
| ASUSTek       | PRIME Z490-A                | [1af97a5f24](https://linux-hardware.org/?probe=1af97a5f24) | Mar 22, 2024 |
| ASUSTek       | P8Z77-V LE                  | [2eef0cba83](https://linux-hardware.org/?probe=2eef0cba83) | Mar 22, 2024 |
| ASUSTek       | H110M-A                     | [fc2fe23179](https://linux-hardware.org/?probe=fc2fe23179) | Mar 22, 2024 |
| ASRock        | FM2A75M Pro4+               | [52f8addde4](https://linux-hardware.org/?probe=52f8addde4) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [0c346bdf70](https://linux-hardware.org/?probe=0c346bdf70) | Mar 21, 2024 |
| Lenovo        | 0B98401 PRO                 | [8b49c50089](https://linux-hardware.org/?probe=8b49c50089) | Mar 21, 2024 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [c47be99616](https://linux-hardware.org/?probe=c47be99616) | Mar 20, 2024 |
| ASRock        | X670E Taichi                | [9478d158a1](https://linux-hardware.org/?probe=9478d158a1) | Mar 20, 2024 |
| ASUSTek       | PRIME X570-P                | [1f7d74bee8](https://linux-hardware.org/?probe=1f7d74bee8) | Mar 20, 2024 |
| ASUSTek       | B85M-E                      | [e3a6512d0c](https://linux-hardware.org/?probe=e3a6512d0c) | Mar 20, 2024 |
| ASRock        | B450M Pro4                  | [bdd0b87420](https://linux-hardware.org/?probe=bdd0b87420) | Mar 19, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [9010c8e968](https://linux-hardware.org/?probe=9010c8e968) | Mar 19, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5fba7feb6c](https://linux-hardware.org/?probe=5fba7feb6c) | Mar 18, 2024 |
| ASUSTek       | PRIME Z370-A                | [c9aab7c5fe](https://linux-hardware.org/?probe=c9aab7c5fe) | Mar 18, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [99e78f54fd](https://linux-hardware.org/?probe=99e78f54fd) | Mar 18, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | [cd6abd6c87](https://linux-hardware.org/?probe=cd6abd6c87) | Mar 17, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [ee3281cbda](https://linux-hardware.org/?probe=ee3281cbda) | Mar 17, 2024 |
| MSI           | MAG B550M BAZOOKA           | [6f59b5bfa1](https://linux-hardware.org/?probe=6f59b5bfa1) | Mar 17, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [2f763edf96](https://linux-hardware.org/?probe=2f763edf96) | Mar 16, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [5912d4041d](https://linux-hardware.org/?probe=5912d4041d) | Mar 16, 2024 |
| Acer          | Predator G3-710             | [81423396ff](https://linux-hardware.org/?probe=81423396ff) | Mar 16, 2024 |
| Gigabyte      | Z390 UD V2                  | [cc72fc2c00](https://linux-hardware.org/?probe=cc72fc2c00) | Mar 16, 2024 |
| Acer          | Predator G3-710             | [4a28c9273f](https://linux-hardware.org/?probe=4a28c9273f) | Mar 16, 2024 |
| ASUSTek       | M5A97 R2.0                  | [75f598474b](https://linux-hardware.org/?probe=75f598474b) | Mar 16, 2024 |
| ASUSTek       | GL10DH                      | [924e2c2170](https://linux-hardware.org/?probe=924e2c2170) | Mar 16, 2024 |
| ASRock        | H310M-HDV                   | [4e2f714f49](https://linux-hardware.org/?probe=4e2f714f49) | Mar 16, 2024 |
| DFI           | HD101-H81D                  | [e8136a2ba9](https://linux-hardware.org/?probe=e8136a2ba9) | Mar 15, 2024 |
| ASRock        | H310M-HDV                   | [8d62cae785](https://linux-hardware.org/?probe=8d62cae785) | Mar 15, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [45edcadc55](https://linux-hardware.org/?probe=45edcadc55) | Mar 15, 2024 |
| Gigabyte      | A320M-S2H-CF                | [ea5a34f828](https://linux-hardware.org/?probe=ea5a34f828) | Mar 15, 2024 |
| Gigabyte      | A320M-S2H-CF                | [b9dc85b113](https://linux-hardware.org/?probe=b9dc85b113) | Mar 14, 2024 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | [9caab49bca](https://linux-hardware.org/?probe=9caab49bca) | Mar 14, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40f761e062](https://linux-hardware.org/?probe=40f761e062) | Mar 14, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [6bea275119](https://linux-hardware.org/?probe=6bea275119) | Mar 12, 2024 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [cb4201e540](https://linux-hardware.org/?probe=cb4201e540) | Mar 11, 2024 |
| MSI           | H310M PRO-VH                | [47509ee75f](https://linux-hardware.org/?probe=47509ee75f) | Mar 11, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [459312f8b8](https://linux-hardware.org/?probe=459312f8b8) | Mar 10, 2024 |
| Gigabyte      | B550 AORUS MASTER           | [706768c42a](https://linux-hardware.org/?probe=706768c42a) | Mar 10, 2024 |
| Gigabyte      | X570 GAMING X               | [2239cf5983](https://linux-hardware.org/?probe=2239cf5983) | Mar 10, 2024 |
| MSI           | B450M-A PRO MAX             | [5c9ff73ab5](https://linux-hardware.org/?probe=5c9ff73ab5) | Mar 09, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [45c9891fb0](https://linux-hardware.org/?probe=45c9891fb0) | Mar 09, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [db5efc9462](https://linux-hardware.org/?probe=db5efc9462) | Mar 09, 2024 |
| ASUSTek       | P8Z77-V LE                  | [c12bbfb9c1](https://linux-hardware.org/?probe=c12bbfb9c1) | Mar 08, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dd3df4cff2](https://linux-hardware.org/?probe=dd3df4cff2) | Mar 07, 2024 |
| ASUSTek       | H81M-E                      | [17ef9e97c9](https://linux-hardware.org/?probe=17ef9e97c9) | Mar 06, 2024 |
| Gigabyte      | H110M-DS2-CF                | [363dfceefd](https://linux-hardware.org/?probe=363dfceefd) | Mar 06, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [544a3548cc](https://linux-hardware.org/?probe=544a3548cc) | Mar 05, 2024 |
| ASUSTek       | PRO A520M-C                 | [394fa5ec3f](https://linux-hardware.org/?probe=394fa5ec3f) | Mar 04, 2024 |
| ASRock        | Z370 Pro4                   | [a234df2002](https://linux-hardware.org/?probe=a234df2002) | Mar 04, 2024 |
| MSI           | H110M PRO-VH PLUS           | [5a814bda6b](https://linux-hardware.org/?probe=5a814bda6b) | Mar 04, 2024 |
| Apple         | Mac-F221BEC8                | [abdf139678](https://linux-hardware.org/?probe=abdf139678) | Mar 04, 2024 |
| ASRock        | B450M Pro4                  | [95f6ca3672](https://linux-hardware.org/?probe=95f6ca3672) | Mar 04, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [c247d9c586](https://linux-hardware.org/?probe=c247d9c586) | Mar 04, 2024 |
| Dell          | 0VTJVC A00                  | [b4cd6d805c](https://linux-hardware.org/?probe=b4cd6d805c) | Mar 04, 2024 |
| MSI           | X399 GAMING PRO CARBON A... | [608e1e507e](https://linux-hardware.org/?probe=608e1e507e) | Mar 04, 2024 |
| ASUSTek       | PRIME B360M-A               | [12cb401e25](https://linux-hardware.org/?probe=12cb401e25) | Mar 03, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [c4d1b90289](https://linux-hardware.org/?probe=c4d1b90289) | Mar 02, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [d674e2f295](https://linux-hardware.org/?probe=d674e2f295) | Mar 02, 2024 |
| ASUSTek       | PRIME B360M-A               | [db88ff40ea](https://linux-hardware.org/?probe=db88ff40ea) | Mar 02, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | [57bd82edb2](https://linux-hardware.org/?probe=57bd82edb2) | Mar 01, 2024 |
| IceWhale T... | ZimaBoard 432 ZMB           | [e901d6e9d1](https://linux-hardware.org/?probe=e901d6e9d1) | Mar 01, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | [695266922d](https://linux-hardware.org/?probe=695266922d) | Feb 29, 2024 |
| Gigabyte      | X670E AORUS XTREME          | [94090f0c82](https://linux-hardware.org/?probe=94090f0c82) | Feb 29, 2024 |
| NZXT          | N7 Z790                     | [983e6338eb](https://linux-hardware.org/?probe=983e6338eb) | Feb 28, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [bd84816ed8](https://linux-hardware.org/?probe=bd84816ed8) | Feb 28, 2024 |
| Shenzhen M... | F7BFC                       | [a3c3fa8741](https://linux-hardware.org/?probe=a3c3fa8741) | Feb 27, 2024 |
| Gigabyte      | H61MS                       | [734eead932](https://linux-hardware.org/?probe=734eead932) | Feb 26, 2024 |
| MSI           | B360 GAMING PLUS            | [40619e4cc4](https://linux-hardware.org/?probe=40619e4cc4) | Feb 26, 2024 |
| MSI           | B360 GAMING PLUS            | [e3fe48b63c](https://linux-hardware.org/?probe=e3fe48b63c) | Feb 26, 2024 |
| Gigabyte      | H61MS                       | [34e5453caa](https://linux-hardware.org/?probe=34e5453caa) | Feb 25, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | [48aeafb576](https://linux-hardware.org/?probe=48aeafb576) | Feb 25, 2024 |
| Gigabyte      | B450M DS3H V2               | [969b42aca3](https://linux-hardware.org/?probe=969b42aca3) | Feb 24, 2024 |
| ASUSTek       | PRIME X670-P                | [02f31414e9](https://linux-hardware.org/?probe=02f31414e9) | Feb 24, 2024 |
| ASUSTek       | Z10PA-D8 Series             | [83933addae](https://linux-hardware.org/?probe=83933addae) | Feb 23, 2024 |
| Gigabyte      | H410M H V3                  | [d5aad61582](https://linux-hardware.org/?probe=d5aad61582) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [322513c6ae](https://linux-hardware.org/?probe=322513c6ae) | Feb 23, 2024 |
| ASUSTek       | PRIME X670-P                | [d5a3258e39](https://linux-hardware.org/?probe=d5a3258e39) | Feb 22, 2024 |
| Gigabyte      | B450M DS3H-CF               | [a7511eee63](https://linux-hardware.org/?probe=a7511eee63) | Feb 21, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [cc638a70e5](https://linux-hardware.org/?probe=cc638a70e5) | Feb 21, 2024 |
| HP            | 1998                        | [ea2b04fb8f](https://linux-hardware.org/?probe=ea2b04fb8f) | Feb 20, 2024 |
| HP            | 18E7                        | [bb8f095490](https://linux-hardware.org/?probe=bb8f095490) | Feb 20, 2024 |
| HP            | 21D0                        | [a19cdbd10a](https://linux-hardware.org/?probe=a19cdbd10a) | Feb 20, 2024 |
| Gigabyte      | B550M DS3H                  | [38bfeafdc6](https://linux-hardware.org/?probe=38bfeafdc6) | Feb 20, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fc618dfd9e](https://linux-hardware.org/?probe=fc618dfd9e) | Feb 20, 2024 |
| ASRock        | B550M-ITX/ac                | [2504d0d667](https://linux-hardware.org/?probe=2504d0d667) | Feb 20, 2024 |
| Gigabyte      | Z270-Gaming K3              | [03e4b54d18](https://linux-hardware.org/?probe=03e4b54d18) | Feb 18, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [4bca7ee01c](https://linux-hardware.org/?probe=4bca7ee01c) | Feb 17, 2024 |
| Gigabyte      | B560 HD3                    | [471e56fa2c](https://linux-hardware.org/?probe=471e56fa2c) | Feb 16, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [1036cc6203](https://linux-hardware.org/?probe=1036cc6203) | Feb 16, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | [ad824cd065](https://linux-hardware.org/?probe=ad824cd065) | Feb 16, 2024 |
| MSI           | B85M-E45                    | [e1ea6178f0](https://linux-hardware.org/?probe=e1ea6178f0) | Feb 14, 2024 |
| HP            | 18E7                        | [b6da2159e6](https://linux-hardware.org/?probe=b6da2159e6) | Feb 14, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [cd8c907b9a](https://linux-hardware.org/?probe=cd8c907b9a) | Feb 14, 2024 |
| MSI           | PRO B650-P WIFI             | [572a664a23](https://linux-hardware.org/?probe=572a664a23) | Feb 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c8f0cd8bd8](https://linux-hardware.org/?probe=c8f0cd8bd8) | Feb 14, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | [60e638856c](https://linux-hardware.org/?probe=60e638856c) | Feb 14, 2024 |
| Intel         | B75                         | [cbd278dc3e](https://linux-hardware.org/?probe=cbd278dc3e) | Feb 13, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd137bafb9](https://linux-hardware.org/?probe=fd137bafb9) | Feb 13, 2024 |
| Lenovo        | 0B98401 PRO                 | [e3ad18986b](https://linux-hardware.org/?probe=e3ad18986b) | Feb 12, 2024 |
| ASRock        | B650 PG Lightning           | [a3c86997db](https://linux-hardware.org/?probe=a3c86997db) | Feb 11, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [ece84ea9af](https://linux-hardware.org/?probe=ece84ea9af) | Feb 11, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a43d95d0c8](https://linux-hardware.org/?probe=a43d95d0c8) | Feb 10, 2024 |
| ASUSTek       | WS X299 SAGE                | [efa41f50a4](https://linux-hardware.org/?probe=efa41f50a4) | Feb 10, 2024 |
| Gigabyte      | B560M AORUS PRO AX          | [cff5a68e2f](https://linux-hardware.org/?probe=cff5a68e2f) | Feb 10, 2024 |
| HP            | 8951                        | [f66c879001](https://linux-hardware.org/?probe=f66c879001) | Feb 08, 2024 |
| MSI           | G41M-P23                    | [4fb4d1fcac](https://linux-hardware.org/?probe=4fb4d1fcac) | Feb 08, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [6600be95fb](https://linux-hardware.org/?probe=6600be95fb) | Feb 08, 2024 |
| Gigabyte      | Z390 UD V2                  | [1538e99333](https://linux-hardware.org/?probe=1538e99333) | Feb 07, 2024 |
| Dell          | 0VFD52 A00                  | [cc2714d2cf](https://linux-hardware.org/?probe=cc2714d2cf) | Feb 07, 2024 |
| Dell          | 0N4YC8 A00                  | [fa06b6e98c](https://linux-hardware.org/?probe=fa06b6e98c) | Feb 06, 2024 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [b34e94536e](https://linux-hardware.org/?probe=b34e94536e) | Feb 05, 2024 |
| ASUSTek       | ROG Maximus X HERO          | [d27ab1996f](https://linux-hardware.org/?probe=d27ab1996f) | Feb 05, 2024 |
| Biostar       | B450NH                      | [79535237f8](https://linux-hardware.org/?probe=79535237f8) | Feb 05, 2024 |
| MSI           | MEG X570 ACE                | [c2fe3b7022](https://linux-hardware.org/?probe=c2fe3b7022) | Feb 04, 2024 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [abdae6d53a](https://linux-hardware.org/?probe=abdae6d53a) | Feb 04, 2024 |
| HP            | 8053                        | [15b30efc20](https://linux-hardware.org/?probe=15b30efc20) | Feb 04, 2024 |
| ASUSTek       | ROG Maximus X HERO          | [17b58ae7c8](https://linux-hardware.org/?probe=17b58ae7c8) | Feb 03, 2024 |
| Huanan        | B85-ITX V2.2                | [dc62daa01b](https://linux-hardware.org/?probe=dc62daa01b) | Feb 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f4791a454c](https://linux-hardware.org/?probe=f4791a454c) | Feb 02, 2024 |
| MSI           | B550 GAMING GEN3            | [e0f8f7bf56](https://linux-hardware.org/?probe=e0f8f7bf56) | Feb 01, 2024 |
| HP            | 8053                        | [d4cc3a7d7d](https://linux-hardware.org/?probe=d4cc3a7d7d) | Jan 31, 2024 |
| HP            | 802F                        | [7d597a977d](https://linux-hardware.org/?probe=7d597a977d) | Jan 30, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [37a5bccc7c](https://linux-hardware.org/?probe=37a5bccc7c) | Jan 30, 2024 |
| HP            | 8053                        | [7cba6dd60f](https://linux-hardware.org/?probe=7cba6dd60f) | Jan 30, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [e88b2c35d9](https://linux-hardware.org/?probe=e88b2c35d9) | Jan 29, 2024 |
| Dell          | 03NVJ6 A03                  | [2ad42e2ce5](https://linux-hardware.org/?probe=2ad42e2ce5) | Jan 29, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [29cc3e58d3](https://linux-hardware.org/?probe=29cc3e58d3) | Jan 26, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [25ca4f9198](https://linux-hardware.org/?probe=25ca4f9198) | Jan 26, 2024 |
| Gigabyte      | Z390 UD V2                  | [43e8fec21d](https://linux-hardware.org/?probe=43e8fec21d) | Jan 25, 2024 |
| MSI           | Z490-A PRO                  | [682c9a3d4b](https://linux-hardware.org/?probe=682c9a3d4b) | Jan 25, 2024 |
| Dell          | 0HD5W2 A01                  | [5c9b7ff711](https://linux-hardware.org/?probe=5c9b7ff711) | Jan 24, 2024 |
| ASRock        | Z370 Extreme4               | [1f8f4bbd8a](https://linux-hardware.org/?probe=1f8f4bbd8a) | Jan 24, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [f19c285018](https://linux-hardware.org/?probe=f19c285018) | Jan 24, 2024 |
| HP            | 21D0                        | [b9cb80ae88](https://linux-hardware.org/?probe=b9cb80ae88) | Jan 23, 2024 |
| Dell          | 0VTJVC A00                  | [634478296d](https://linux-hardware.org/?probe=634478296d) | Jan 23, 2024 |
| ASUSTek       | PRIME Z490-V                | [fe2523751b](https://linux-hardware.org/?probe=fe2523751b) | Jan 23, 2024 |
| Gigabyte      | Z270-Gaming 3               | [3977f0ba53](https://linux-hardware.org/?probe=3977f0ba53) | Jan 23, 2024 |
| Gigabyte      | X570 GAMING X               | [a2f925963a](https://linux-hardware.org/?probe=a2f925963a) | Jan 22, 2024 |
| Dell          | 0VTJVC A00                  | [006ea19b6d](https://linux-hardware.org/?probe=006ea19b6d) | Jan 21, 2024 |
| ASUSTek       | PRIME B550M-A               | [2a8652365f](https://linux-hardware.org/?probe=2a8652365f) | Jan 21, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [5c7cfc2209](https://linux-hardware.org/?probe=5c7cfc2209) | Jan 20, 2024 |
| MSI           | Z270 GAMING M5              | [e8e8d1eac7](https://linux-hardware.org/?probe=e8e8d1eac7) | Jan 20, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [d10d02479b](https://linux-hardware.org/?probe=d10d02479b) | Jan 19, 2024 |
| Gigabyte      | A520M K V2                  | [65409c0132](https://linux-hardware.org/?probe=65409c0132) | Jan 19, 2024 |
| Dell          | 0HD5W2 A01                  | [bca96a52c9](https://linux-hardware.org/?probe=bca96a52c9) | Jan 19, 2024 |
| MSI           | PRO B650M-P                 | [1dbda223dd](https://linux-hardware.org/?probe=1dbda223dd) | Jan 19, 2024 |
| MSI           | Z170A KRAIT GAMING          | [a07bb34929](https://linux-hardware.org/?probe=a07bb34929) | Jan 18, 2024 |
| Gigabyte      | H310M DS2 x.x               | [dcbb993ea5](https://linux-hardware.org/?probe=dcbb993ea5) | Jan 18, 2024 |
| MSI           | A320M-A PRO                 | [f118f7960d](https://linux-hardware.org/?probe=f118f7960d) | Jan 18, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [8c0d4eb1d6](https://linux-hardware.org/?probe=8c0d4eb1d6) | Jan 17, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [53e10082bf](https://linux-hardware.org/?probe=53e10082bf) | Jan 17, 2024 |
| ASRock        | A320M-HDV R3.0              | [de188c28b4](https://linux-hardware.org/?probe=de188c28b4) | Jan 16, 2024 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [d7031bc588](https://linux-hardware.org/?probe=d7031bc588) | Jan 15, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [64034e1d83](https://linux-hardware.org/?probe=64034e1d83) | Jan 15, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [37525c1fc4](https://linux-hardware.org/?probe=37525c1fc4) | Jan 15, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [48662f6676](https://linux-hardware.org/?probe=48662f6676) | Jan 14, 2024 |
| HP            | 802F                        | [c1c2cf68cf](https://linux-hardware.org/?probe=c1c2cf68cf) | Jan 13, 2024 |
| ASUSTek       | PRIME H510M-E               | [8d2d7ea755](https://linux-hardware.org/?probe=8d2d7ea755) | Jan 13, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [eac19e51a1](https://linux-hardware.org/?probe=eac19e51a1) | Jan 12, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ae6f35c2d9](https://linux-hardware.org/?probe=ae6f35c2d9) | Jan 11, 2024 |
| HP            | 886C                        | [2a05d09b63](https://linux-hardware.org/?probe=2a05d09b63) | Jan 11, 2024 |
| ASRock        | B550M Pro4                  | [5a91b2f042](https://linux-hardware.org/?probe=5a91b2f042) | Jan 11, 2024 |
| HP            | 2B2C                        | [6e5219edb5](https://linux-hardware.org/?probe=6e5219edb5) | Jan 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [13954507ba](https://linux-hardware.org/?probe=13954507ba) | Jan 10, 2024 |
| Supermicro    | X10DRL-i                    | [874482c96c](https://linux-hardware.org/?probe=874482c96c) | Jan 10, 2024 |
| Dell          | 0YXT71 A01                  | [e50164b814](https://linux-hardware.org/?probe=e50164b814) | Jan 10, 2024 |
| BESSTAR Te... | DMAF5 V1.0                  | [c34b89590f](https://linux-hardware.org/?probe=c34b89590f) | Jan 10, 2024 |
| Supermicro    | X10DRL-i                    | [d51207de50](https://linux-hardware.org/?probe=d51207de50) | Jan 09, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d7fb6a77ce](https://linux-hardware.org/?probe=d7fb6a77ce) | Jan 09, 2024 |
| Acer          | Aspire XC-605               | [45cfea1b20](https://linux-hardware.org/?probe=45cfea1b20) | Jan 08, 2024 |
| MSI           | 2A78h                       | [dfa343a5d1](https://linux-hardware.org/?probe=dfa343a5d1) | Jan 08, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [fab97aa087](https://linux-hardware.org/?probe=fab97aa087) | Jan 07, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [3d05259dfb](https://linux-hardware.org/?probe=3d05259dfb) | Jan 07, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1db7814b85](https://linux-hardware.org/?probe=1db7814b85) | Jan 07, 2024 |
| MSI           | Z390-A PRO                  | [27f18dc1f7](https://linux-hardware.org/?probe=27f18dc1f7) | Jan 07, 2024 |
| ASRock        | X670E Taichi Carrara        | [f827ab96ab](https://linux-hardware.org/?probe=f827ab96ab) | Jan 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [3d68a9a838](https://linux-hardware.org/?probe=3d68a9a838) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e618c21fe](https://linux-hardware.org/?probe=9e618c21fe) | Jan 05, 2024 |
| ASRock        | Z370 Extreme4               | [0726856482](https://linux-hardware.org/?probe=0726856482) | Jan 05, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [9085f69422](https://linux-hardware.org/?probe=9085f69422) | Jan 04, 2024 |
| ASRock        | B550M Pro4                  | [0009b1d1c0](https://linux-hardware.org/?probe=0009b1d1c0) | Jan 04, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [34a39f9113](https://linux-hardware.org/?probe=34a39f9113) | Jan 04, 2024 |
| HP            | 83E1                        | [9006156354](https://linux-hardware.org/?probe=9006156354) | Jan 04, 2024 |
| HP            | 2B2C                        | [5ac47f9e43](https://linux-hardware.org/?probe=5ac47f9e43) | Jan 04, 2024 |
| MSI           | B250M BAZOOKA               | [f38a6dd3e9](https://linux-hardware.org/?probe=f38a6dd3e9) | Jan 04, 2024 |
| ASUSTek       | TUF Z390-PRO GAMING         | [e44e9a6818](https://linux-hardware.org/?probe=e44e9a6818) | Jan 03, 2024 |
| HP            | 8433 11                     | [7cb531e95b](https://linux-hardware.org/?probe=7cb531e95b) | Jan 02, 2024 |
| HP            | 886C                        | [790d8f5734](https://linux-hardware.org/?probe=790d8f5734) | Jan 02, 2024 |
| HP            | 0A54h                       | [6db4931db4](https://linux-hardware.org/?probe=6db4931db4) | Jan 02, 2024 |
| HP            | 0A54h                       | [cbf6bc2e02](https://linux-hardware.org/?probe=cbf6bc2e02) | Jan 02, 2024 |
| HP            | 886C                        | [d076e5b70a](https://linux-hardware.org/?probe=d076e5b70a) | Jan 01, 2024 |
| HP            | 18E7                        | [cf9a9bbe99](https://linux-hardware.org/?probe=cf9a9bbe99) | Jan 01, 2024 |
| ASRock        | Z690M Phantom Gaming 4      | [9b11da6c92](https://linux-hardware.org/?probe=9b11da6c92) | Jan 01, 2024 |
| ASRock        | B450 Gaming K4              | [082442f033](https://linux-hardware.org/?probe=082442f033) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4b8ffea2ef](https://linux-hardware.org/?probe=4b8ffea2ef) | Jan 01, 2024 |
| Gigabyte      | Z390 UD V2                  | [c7c5239d23](https://linux-hardware.org/?probe=c7c5239d23) | Dec 31, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [cc1f8b0b86](https://linux-hardware.org/?probe=cc1f8b0b86) | Dec 31, 2023 |
| ASUSTek       | PRIME A520M-K               | [7baccc479c](https://linux-hardware.org/?probe=7baccc479c) | Dec 31, 2023 |
| ASRock        | X570 Extreme4               | [13312e6a34](https://linux-hardware.org/?probe=13312e6a34) | Dec 30, 2023 |
| ASRock        | B450 Gaming K4              | [8651fcb2dc](https://linux-hardware.org/?probe=8651fcb2dc) | Dec 30, 2023 |
| ASRock        | H410M/ac                    | [7d74a172c8](https://linux-hardware.org/?probe=7d74a172c8) | Dec 30, 2023 |
| MSI           | MS-B9311                    | [47bab5481d](https://linux-hardware.org/?probe=47bab5481d) | Dec 30, 2023 |
| MSI           | Z590-A PRO                  | [f6eb92aa92](https://linux-hardware.org/?probe=f6eb92aa92) | Dec 30, 2023 |
| Dell          | 03NVJ6 A03                  | [a87a530d24](https://linux-hardware.org/?probe=a87a530d24) | Dec 30, 2023 |
| Acer          | WMCP78M                     | [1384395472](https://linux-hardware.org/?probe=1384395472) | Dec 29, 2023 |
| Dell          | 0HD5W2 A01                  | [91ac22ebca](https://linux-hardware.org/?probe=91ac22ebca) | Dec 29, 2023 |
| ASRock        | Z370 Extreme4               | [97e413d4b8](https://linux-hardware.org/?probe=97e413d4b8) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | [617d953e8f](https://linux-hardware.org/?probe=617d953e8f) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | [587d9f4fcb](https://linux-hardware.org/?probe=587d9f4fcb) | Dec 29, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [656b1b3ae1](https://linux-hardware.org/?probe=656b1b3ae1) | Dec 29, 2023 |
| Gigabyte      | H77-D3H                     | [2fe4c01bc1](https://linux-hardware.org/?probe=2fe4c01bc1) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [adcd184722](https://linux-hardware.org/?probe=adcd184722) | Dec 28, 2023 |
| ASUSTek       | PRIME X570-P                | [29084d784b](https://linux-hardware.org/?probe=29084d784b) | Dec 28, 2023 |
| ASUSTek       | P8Z77-V LE                  | [da06397f0e](https://linux-hardware.org/?probe=da06397f0e) | Dec 27, 2023 |
| MSI           | B450M PRO-M2                | [5b0afba8bf](https://linux-hardware.org/?probe=5b0afba8bf) | Dec 27, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [fccf2df94e](https://linux-hardware.org/?probe=fccf2df94e) | Dec 27, 2023 |
| Gigabyte      | A320M-DS2-CF                | [a0ef6497e0](https://linux-hardware.org/?probe=a0ef6497e0) | Dec 26, 2023 |
| Dell          | 03NVJ6 A03                  | [b6056625fc](https://linux-hardware.org/?probe=b6056625fc) | Dec 26, 2023 |
| Gigabyte      | H310M DS2 x.x               | [47c95a8cc5](https://linux-hardware.org/?probe=47c95a8cc5) | Dec 26, 2023 |
| Unknown       | Unknown                     | [750b06a365](https://linux-hardware.org/?probe=750b06a365) | Dec 24, 2023 |
| Gigabyte      | X670 GAMING X AX            | [4452cd4a25](https://linux-hardware.org/?probe=4452cd4a25) | Dec 24, 2023 |
| Acer          | H81-M1                      | [e9fd2a5dc4](https://linux-hardware.org/?probe=e9fd2a5dc4) | Dec 23, 2023 |
| MSI           | PRO H410M-B                 | [28d6a6092b](https://linux-hardware.org/?probe=28d6a6092b) | Dec 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [851dce0b14](https://linux-hardware.org/?probe=851dce0b14) | Dec 22, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [e0cd6655cb](https://linux-hardware.org/?probe=e0cd6655cb) | Dec 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [119a1632aa](https://linux-hardware.org/?probe=119a1632aa) | Dec 21, 2023 |
| ASUSTek       | Z87-PRO                     | [1c5b8cb7de](https://linux-hardware.org/?probe=1c5b8cb7de) | Dec 21, 2023 |
| Gigabyte      | Z690 AORUS XTREME           | [c721656dbe](https://linux-hardware.org/?probe=c721656dbe) | Dec 20, 2023 |
| MSI           | A78M-E45                    | [6d11f72d41](https://linux-hardware.org/?probe=6d11f72d41) | Dec 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [4ea2f3364d](https://linux-hardware.org/?probe=4ea2f3364d) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [18cb796b47](https://linux-hardware.org/?probe=18cb796b47) | Dec 19, 2023 |
| Win elemen... | M600                        | [0d0f7a6719](https://linux-hardware.org/?probe=0d0f7a6719) | Dec 19, 2023 |
| Unknown       | HX90                        | [2bf61c79c6](https://linux-hardware.org/?probe=2bf61c79c6) | Dec 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [38b0463b4a](https://linux-hardware.org/?probe=38b0463b4a) | Dec 18, 2023 |
| ASUSTek       | WS X299 SAGE                | [cc5a70ea88](https://linux-hardware.org/?probe=cc5a70ea88) | Dec 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ce269919cd](https://linux-hardware.org/?probe=ce269919cd) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bd0bcd2eba](https://linux-hardware.org/?probe=bd0bcd2eba) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [a62323f9e3](https://linux-hardware.org/?probe=a62323f9e3) | Dec 18, 2023 |
| MSI           | MAG B550M BAZOOKA           | [474668dbec](https://linux-hardware.org/?probe=474668dbec) | Dec 18, 2023 |
| ASUSTek       | WS X299 SAGE                | [6e76ff78f6](https://linux-hardware.org/?probe=6e76ff78f6) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO             | [64d4715e81](https://linux-hardware.org/?probe=64d4715e81) | Dec 18, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [d6ddc6fdde](https://linux-hardware.org/?probe=d6ddc6fdde) | Dec 18, 2023 |
| HP            | 18E7                        | [20a3bd6bee](https://linux-hardware.org/?probe=20a3bd6bee) | Dec 17, 2023 |
| ASRock        | X670E Taichi Carrara        | [2d0eb33a7a](https://linux-hardware.org/?probe=2d0eb33a7a) | Dec 17, 2023 |
| ASUSTek       | P8Z77-V LE                  | [1c2f8035bb](https://linux-hardware.org/?probe=1c2f8035bb) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [316b12645c](https://linux-hardware.org/?probe=316b12645c) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [36f9f51f5d](https://linux-hardware.org/?probe=36f9f51f5d) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [ec182b1b52](https://linux-hardware.org/?probe=ec182b1b52) | Dec 16, 2023 |
| HP            | 18E7                        | [5923f47c4b](https://linux-hardware.org/?probe=5923f47c4b) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [39f4b40998](https://linux-hardware.org/?probe=39f4b40998) | Dec 14, 2023 |
| Dell          | 0TTDMJ A00                  | [66477630d7](https://linux-hardware.org/?probe=66477630d7) | Dec 14, 2023 |
| ASUSTek       | Z87-PRO                     | [5ea78096f6](https://linux-hardware.org/?probe=5ea78096f6) | Dec 14, 2023 |
| HP            | 1495                        | [e187132e56](https://linux-hardware.org/?probe=e187132e56) | Dec 14, 2023 |
| ASRock        | A300M-STX                   | [f6f4e86ea3](https://linux-hardware.org/?probe=f6f4e86ea3) | Dec 13, 2023 |
| HP            | 1495                        | [7c74116b39](https://linux-hardware.org/?probe=7c74116b39) | Dec 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [f34c061189](https://linux-hardware.org/?probe=f34c061189) | Dec 12, 2023 |
| Gigabyte      | Z97X-UD5H                   | [b42f33ca53](https://linux-hardware.org/?probe=b42f33ca53) | Dec 12, 2023 |
| Acer          | H81-M1                      | [c6f5b1d841](https://linux-hardware.org/?probe=c6f5b1d841) | Dec 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [fc475e4cd3](https://linux-hardware.org/?probe=fc475e4cd3) | Dec 11, 2023 |
| HP            | 1850                        | [903e4b5eb1](https://linux-hardware.org/?probe=903e4b5eb1) | Dec 11, 2023 |
| ASUSTek       | PRIME B250M-A               | [43516f3ae9](https://linux-hardware.org/?probe=43516f3ae9) | Dec 10, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [66edf53f93](https://linux-hardware.org/?probe=66edf53f93) | Dec 10, 2023 |
| Dell          | 0F373D A00                  | [cf693d5429](https://linux-hardware.org/?probe=cf693d5429) | Dec 09, 2023 |
| MSI           | A520M PRO-VH                | [96475c0e77](https://linux-hardware.org/?probe=96475c0e77) | Dec 08, 2023 |
| ASRock        | X670E Taichi Carrara        | [9050f85bc9](https://linux-hardware.org/?probe=9050f85bc9) | Dec 08, 2023 |
| Acer          | H81-M1                      | [76ff7a29ae](https://linux-hardware.org/?probe=76ff7a29ae) | Dec 07, 2023 |
| MSI           | Z97 PC Mate                 | [23a0828c28](https://linux-hardware.org/?probe=23a0828c28) | Dec 07, 2023 |
| ASUSTek       | PRIME A520M-K               | [a6f429594d](https://linux-hardware.org/?probe=a6f429594d) | Dec 07, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [5183612439](https://linux-hardware.org/?probe=5183612439) | Dec 07, 2023 |
| HP            | 2AFB                        | [a91d9cd265](https://linux-hardware.org/?probe=a91d9cd265) | Dec 06, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [9b36560b08](https://linux-hardware.org/?probe=9b36560b08) | Dec 06, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [d52d7379c3](https://linux-hardware.org/?probe=d52d7379c3) | Dec 06, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [54d3b585e6](https://linux-hardware.org/?probe=54d3b585e6) | Dec 05, 2023 |
| Gigabyte      | Z390 UD V2                  | [2d85fb4799](https://linux-hardware.org/?probe=2d85fb4799) | Dec 05, 2023 |
| Gigabyte      | H370M DS3H-CF               | [332f084cba](https://linux-hardware.org/?probe=332f084cba) | Dec 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [a635fe86e0](https://linux-hardware.org/?probe=a635fe86e0) | Dec 04, 2023 |
| MSI           | Z590-A PRO                  | [4298ef81a3](https://linux-hardware.org/?probe=4298ef81a3) | Dec 04, 2023 |
| ASUSTek       | Z87-PRO                     | [a6cce7762e](https://linux-hardware.org/?probe=a6cce7762e) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [4c8abee905](https://linux-hardware.org/?probe=4c8abee905) | Dec 03, 2023 |
| MSI           | B450M MORTAR                | [5e8bdafa0a](https://linux-hardware.org/?probe=5e8bdafa0a) | Dec 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [931c17aeb7](https://linux-hardware.org/?probe=931c17aeb7) | Dec 02, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [d2ec06fb3c](https://linux-hardware.org/?probe=d2ec06fb3c) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [305a40c9b7](https://linux-hardware.org/?probe=305a40c9b7) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [6d97271c61](https://linux-hardware.org/?probe=6d97271c61) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [0cff3cecd5](https://linux-hardware.org/?probe=0cff3cecd5) | Dec 02, 2023 |
| ASUSTek       | PRIME B450M-A               | [9fee8c35c3](https://linux-hardware.org/?probe=9fee8c35c3) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [a27577cb3a](https://linux-hardware.org/?probe=a27577cb3a) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [fc8b74d0f9](https://linux-hardware.org/?probe=fc8b74d0f9) | Nov 29, 2023 |
| MSI           | X470 GAMING PLUS            | [5030903de4](https://linux-hardware.org/?probe=5030903de4) | Nov 28, 2023 |
| Acer          | Aspire M5400                | [f0e15f3802](https://linux-hardware.org/?probe=f0e15f3802) | Nov 27, 2023 |
| ASUSTek       | X79-DELUXE                  | [b89bce359a](https://linux-hardware.org/?probe=b89bce359a) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [7406ad3cc2](https://linux-hardware.org/?probe=7406ad3cc2) | Nov 26, 2023 |
| ASRock        | B450M Steel Legend          | [b0f55cc692](https://linux-hardware.org/?probe=b0f55cc692) | Nov 26, 2023 |
| Dell          | 0V8WGR A01                  | [b44e627796](https://linux-hardware.org/?probe=b44e627796) | Nov 26, 2023 |
| HP            | 1497                        | [1cbc2dbbc9](https://linux-hardware.org/?probe=1cbc2dbbc9) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-A                | [d1462624ea](https://linux-hardware.org/?probe=d1462624ea) | Nov 24, 2023 |
| NZXT          | N7 B550                     | [eda34615ff](https://linux-hardware.org/?probe=eda34615ff) | Nov 24, 2023 |
| Lenovo        | MAHOBAY NOK                 | [cb6301a778](https://linux-hardware.org/?probe=cb6301a778) | Nov 23, 2023 |
| BESSTAR Te... | UM700                       | [2be2b94342](https://linux-hardware.org/?probe=2be2b94342) | Nov 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [abb0181b70](https://linux-hardware.org/?probe=abb0181b70) | Nov 22, 2023 |
| HP            | 18E7                        | [594059fee8](https://linux-hardware.org/?probe=594059fee8) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [42064a20b4](https://linux-hardware.org/?probe=42064a20b4) | Nov 21, 2023 |
| Shenzhen M... | F7BFC                       | [bd7cd76d26](https://linux-hardware.org/?probe=bd7cd76d26) | Nov 20, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [6e05364421](https://linux-hardware.org/?probe=6e05364421) | Nov 20, 2023 |
| Dell          | 0KV62T A00                  | [72b1a867da](https://linux-hardware.org/?probe=72b1a867da) | Nov 20, 2023 |
| Acer          | Predator PO3-630            | [8919926380](https://linux-hardware.org/?probe=8919926380) | Nov 20, 2023 |
| ASRock        | B450 Pro4                   | [cfc45028e8](https://linux-hardware.org/?probe=cfc45028e8) | Nov 19, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [41a350bfbd](https://linux-hardware.org/?probe=41a350bfbd) | Nov 18, 2023 |
| ASUSTek       | H110M-A                     | [79a1012336](https://linux-hardware.org/?probe=79a1012336) | Nov 18, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [eeef8f244c](https://linux-hardware.org/?probe=eeef8f244c) | Nov 18, 2023 |
| MSI           | B550-A PRO                  | [a7467830d5](https://linux-hardware.org/?probe=a7467830d5) | Nov 17, 2023 |
| Acer          | Nitro N50-610               | [648f624587](https://linux-hardware.org/?probe=648f624587) | Nov 16, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b33b5da196](https://linux-hardware.org/?probe=b33b5da196) | Nov 16, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [adaa2215c6](https://linux-hardware.org/?probe=adaa2215c6) | Nov 15, 2023 |
| Intel         | B75                         | [b05bcd24eb](https://linux-hardware.org/?probe=b05bcd24eb) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Gigabyte      | H410M H V3                  | [6a15b4fb46](https://linux-hardware.org/?probe=6a15b4fb46) | Nov 13, 2023 |
| Shenzhen M... | F7BFC                       | [b375ae991a](https://linux-hardware.org/?probe=b375ae991a) | Nov 12, 2023 |
| Gigabyte      | 970A-DS3P FX                | [269c0ca349](https://linux-hardware.org/?probe=269c0ca349) | Nov 12, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [64b6fe3b3a](https://linux-hardware.org/?probe=64b6fe3b3a) | Nov 11, 2023 |
| Dell          | 09KPNV A00                  | [231b7871d0](https://linux-hardware.org/?probe=231b7871d0) | Nov 11, 2023 |
| ASUSTek       | PRIME A520M-K               | [8e450b21e1](https://linux-hardware.org/?probe=8e450b21e1) | Nov 10, 2023 |
| Gigabyte      | Z390 UD V2                  | [2106c14823](https://linux-hardware.org/?probe=2106c14823) | Nov 10, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [1f65a38863](https://linux-hardware.org/?probe=1f65a38863) | Nov 09, 2023 |
| Gigabyte      | Z390 UD V2                  | [7cdb83cd7a](https://linux-hardware.org/?probe=7cdb83cd7a) | Nov 09, 2023 |
| HP            | 802F                        | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| ASRock        | Z77 Extreme4                | [ebe40897c3](https://linux-hardware.org/?probe=ebe40897c3) | Nov 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [6970492955](https://linux-hardware.org/?probe=6970492955) | Nov 08, 2023 |
| ASRock        | Z690 Extreme                | [6377c6ca79](https://linux-hardware.org/?probe=6377c6ca79) | Nov 08, 2023 |
| ASRock        | B450M-HDV R4.0              | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | [ef9e91fdbf](https://linux-hardware.org/?probe=ef9e91fdbf) | Nov 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [84527b43d1](https://linux-hardware.org/?probe=84527b43d1) | Nov 07, 2023 |
| MSI           | A78M-E45                    | [920763b803](https://linux-hardware.org/?probe=920763b803) | Nov 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | [ce42858c1f](https://linux-hardware.org/?probe=ce42858c1f) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8ee603dbfc](https://linux-hardware.org/?probe=8ee603dbfc) | Nov 05, 2023 |
| Dell          | 048DY8 A01                  | [2ef39546ef](https://linux-hardware.org/?probe=2ef39546ef) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| ASUSTek       | PRIME A520M-K               | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| ASUSTek       | Maximus VII HERO            | [a60f1d4a52](https://linux-hardware.org/?probe=a60f1d4a52) | Nov 01, 2023 |
| ASRock        | B250M Pro4                  | [399fe59760](https://linux-hardware.org/?probe=399fe59760) | Nov 01, 2023 |
| Fujitsu       | D4017-A1 S26361-D4017-A1... | [939aebfa68](https://linux-hardware.org/?probe=939aebfa68) | Nov 01, 2023 |
| HP            | 2B01                        | [a345333330](https://linux-hardware.org/?probe=a345333330) | Oct 31, 2023 |
| Gigabyte      | B450M DS3H WIFI V2-CF       | [ac2f19109e](https://linux-hardware.org/?probe=ac2f19109e) | Oct 31, 2023 |
| HP            | 2B01                        | [b3a75824f5](https://linux-hardware.org/?probe=b3a75824f5) | Oct 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [d735ec288c](https://linux-hardware.org/?probe=d735ec288c) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [4e5ba58b35](https://linux-hardware.org/?probe=4e5ba58b35) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| Dell          | 0T1D10 A01                  | [1b0a34d774](https://linux-hardware.org/?probe=1b0a34d774) | Oct 29, 2023 |
| MSI           | X570-A PRO                  | [b6f56d4f6c](https://linux-hardware.org/?probe=b6f56d4f6c) | Oct 29, 2023 |
| Intel         | B75                         | [7b6b287377](https://linux-hardware.org/?probe=7b6b287377) | Oct 28, 2023 |
| Win elemen... | M600                        | [6a027c490c](https://linux-hardware.org/?probe=6a027c490c) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| Gigabyte      | X570 GAMING X               | [b65f692868](https://linux-hardware.org/?probe=b65f692868) | Oct 26, 2023 |
| Gigabyte      | 990FXA-UD3                  | [f4f26b1c2a](https://linux-hardware.org/?probe=f4f26b1c2a) | Oct 25, 2023 |
| Gigabyte      | B550M DS3H                  | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4e7be30b13](https://linux-hardware.org/?probe=4e7be30b13) | Oct 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [f99b06d89a](https://linux-hardware.org/?probe=f99b06d89a) | Oct 24, 2023 |
| Acer          | Veriton N4640G              | [ccba40d7a9](https://linux-hardware.org/?probe=ccba40d7a9) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [3daca4912e](https://linux-hardware.org/?probe=3daca4912e) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| Intel         | HM570                       | [5dba972342](https://linux-hardware.org/?probe=5dba972342) | Oct 23, 2023 |
| AMI           | Intel                       | [5e579268b6](https://linux-hardware.org/?probe=5e579268b6) | Oct 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [f134292e10](https://linux-hardware.org/?probe=f134292e10) | Oct 23, 2023 |
| Intel         | B75                         | [96f9a95f89](https://linux-hardware.org/?probe=96f9a95f89) | Oct 22, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [38d48bd5b5](https://linux-hardware.org/?probe=38d48bd5b5) | Oct 22, 2023 |
| Acer          | Veriton S2680G              | [da6ff1f2f3](https://linux-hardware.org/?probe=da6ff1f2f3) | Oct 22, 2023 |
| ASRock        | B650M PG Riptide            | [218908299a](https://linux-hardware.org/?probe=218908299a) | Oct 21, 2023 |
| ASUSTek       | PRIME H270-PRO              | [3b1d62c873](https://linux-hardware.org/?probe=3b1d62c873) | Oct 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3216d9052a](https://linux-hardware.org/?probe=3216d9052a) | Oct 21, 2023 |
| Gigabyte      | H410M H V3                  | [0b9affbbb3](https://linux-hardware.org/?probe=0b9affbbb3) | Oct 21, 2023 |
| HP            | 3397                        | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| Acer          | Predator PO3-620            | [db0c739e61](https://linux-hardware.org/?probe=db0c739e61) | Oct 19, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3e5a5380d7](https://linux-hardware.org/?probe=3e5a5380d7) | Oct 18, 2023 |
| ASRock        | B550M-ITX/ac                | [83cb446c19](https://linux-hardware.org/?probe=83cb446c19) | Oct 16, 2023 |
| Dell          | 00F82W A00                  | [410900bf0d](https://linux-hardware.org/?probe=410900bf0d) | Oct 15, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [9065a343c2](https://linux-hardware.org/?probe=9065a343c2) | Oct 15, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [cdd65525cc](https://linux-hardware.org/?probe=cdd65525cc) | Oct 15, 2023 |
| Unknown       | Unknown                     | [23768d9009](https://linux-hardware.org/?probe=23768d9009) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [79a68614cb](https://linux-hardware.org/?probe=79a68614cb) | Oct 15, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [42e5a09fe2](https://linux-hardware.org/?probe=42e5a09fe2) | Oct 14, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e3a01650f1](https://linux-hardware.org/?probe=e3a01650f1) | Oct 14, 2023 |
| HP            | 18E7                        | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8d41cb80bf](https://linux-hardware.org/?probe=8d41cb80bf) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [339d1c4a25](https://linux-hardware.org/?probe=339d1c4a25) | Oct 13, 2023 |
| Dell          | 03NVJ6 A02                  | [0f40b40836](https://linux-hardware.org/?probe=0f40b40836) | Oct 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [89ae9695ef](https://linux-hardware.org/?probe=89ae9695ef) | Oct 11, 2023 |
| Dell          | 00F82W A00                  | [75fd02b856](https://linux-hardware.org/?probe=75fd02b856) | Oct 10, 2023 |
| Dell          | 03NVJ6 A02                  | [8f7a44301e](https://linux-hardware.org/?probe=8f7a44301e) | Oct 10, 2023 |
| Gigabyte      | H87N-WIFI                   | [f010d626da](https://linux-hardware.org/?probe=f010d626da) | Oct 08, 2023 |
| Dell          | 0WWJRX A00                  | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [1deaeb248b](https://linux-hardware.org/?probe=1deaeb248b) | Oct 04, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [8959fc9294](https://linux-hardware.org/?probe=8959fc9294) | Oct 03, 2023 |
| MSI           | Z590-A PRO                  | [373685317f](https://linux-hardware.org/?probe=373685317f) | Oct 03, 2023 |
| HP            | 87D6 SMVB                   | [ac72ba77a1](https://linux-hardware.org/?probe=ac72ba77a1) | Oct 02, 2023 |
| EXPER         | H61H2-MV                    | [5cd287a613](https://linux-hardware.org/?probe=5cd287a613) | Oct 01, 2023 |
| EXPER         | H61H2-MV                    | [7b50b9b997](https://linux-hardware.org/?probe=7b50b9b997) | Oct 01, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [27e61d282f](https://linux-hardware.org/?probe=27e61d282f) | Oct 01, 2023 |
| ASRock        | A320M-DGS                   | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| Dell          | 0YXT71 A02                  | [6bc3385414](https://linux-hardware.org/?probe=6bc3385414) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Medion        | MS-7667                     | [a91527e825](https://linux-hardware.org/?probe=a91527e825) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| ASRock        | Z490 Phantom Gaming 4       | [6fc3fe7a63](https://linux-hardware.org/?probe=6fc3fe7a63) | Sep 29, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [1476ba44bb](https://linux-hardware.org/?probe=1476ba44bb) | Sep 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1f76bcf230](https://linux-hardware.org/?probe=1f76bcf230) | Sep 23, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [0fb4baf82b](https://linux-hardware.org/?probe=0fb4baf82b) | Sep 23, 2023 |
| MSI           | Z270 GAMING M5              | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| ASUSTek       | Q170M2                      | [962ed87784](https://linux-hardware.org/?probe=962ed87784) | Sep 20, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [96a7016b7e](https://linux-hardware.org/?probe=96a7016b7e) | Sep 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [20eef756df](https://linux-hardware.org/?probe=20eef756df) | Sep 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f26ced12d](https://linux-hardware.org/?probe=1f26ced12d) | Sep 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [bf29b07e79](https://linux-hardware.org/?probe=bf29b07e79) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| ASRock        | B450M Pro4                  | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| Gigabyte      | H310M S2                    | [f6a841ea3d](https://linux-hardware.org/?probe=f6a841ea3d) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [9f3bdc24af](https://linux-hardware.org/?probe=9f3bdc24af) | Sep 18, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [1875fb96e5](https://linux-hardware.org/?probe=1875fb96e5) | Sep 17, 2023 |
| Dell          | 0VTJVC A00                  | [8a404c05c2](https://linux-hardware.org/?probe=8a404c05c2) | Sep 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [f15272f431](https://linux-hardware.org/?probe=f15272f431) | Sep 15, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [8c1887fa93](https://linux-hardware.org/?probe=8c1887fa93) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [c3e468a36f](https://linux-hardware.org/?probe=c3e468a36f) | Sep 15, 2023 |
| ASUSTek       | PRIME Z370-A                | [8b7e93cd9d](https://linux-hardware.org/?probe=8b7e93cd9d) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| Gigabyte      | EP45-UD3LR                  | [7dc196091d](https://linux-hardware.org/?probe=7dc196091d) | Sep 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e12c2067df](https://linux-hardware.org/?probe=e12c2067df) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| ASRock        | B450M Pro4                  | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| Gigabyte      | X570 GAMING X               | [8e988d79b7](https://linux-hardware.org/?probe=8e988d79b7) | Sep 09, 2023 |
| BESSTAR Te... | UM700                       | [a93bb80cb8](https://linux-hardware.org/?probe=a93bb80cb8) | Sep 09, 2023 |
| Gigabyte      | H61M-S1                     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [9d0bacfabd](https://linux-hardware.org/?probe=9d0bacfabd) | Sep 09, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6ed0b47516](https://linux-hardware.org/?probe=6ed0b47516) | Sep 08, 2023 |
| BESSTAR Te... | HX90                        | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [6dbe579385](https://linux-hardware.org/?probe=6dbe579385) | Sep 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [8fc5475fd3](https://linux-hardware.org/?probe=8fc5475fd3) | Sep 08, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [721c2adc46](https://linux-hardware.org/?probe=721c2adc46) | Sep 07, 2023 |
| BESSTAR Te... | UM700                       | [d635105967](https://linux-hardware.org/?probe=d635105967) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [e47f10b579](https://linux-hardware.org/?probe=e47f10b579) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [d1cf42c68c](https://linux-hardware.org/?probe=d1cf42c68c) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [4d1ca2eb79](https://linux-hardware.org/?probe=4d1ca2eb79) | Sep 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [995b1f100d](https://linux-hardware.org/?probe=995b1f100d) | Sep 06, 2023 |
| ASRock        | B450M Pro4                  | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| ASUSTek       | P8Z77-V LE                  | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| AZW           | MINI S                      | [331702f893](https://linux-hardware.org/?probe=331702f893) | Sep 04, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [d15e4d0045](https://linux-hardware.org/?probe=d15e4d0045) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [9f8e38af3e](https://linux-hardware.org/?probe=9f8e38af3e) | Sep 02, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [59014a9e20](https://linux-hardware.org/?probe=59014a9e20) | Sep 02, 2023 |
| Shenzhen M... | F6BFC                       | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| HP            | 802F                        | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| Dell          | 0V8WGR A01                  | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| HP            | 8061                        | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [5df3abe62e](https://linux-hardware.org/?probe=5df3abe62e) | Aug 28, 2023 |
| Acer          | Aspire M3470                | [60d18d6d6e](https://linux-hardware.org/?probe=60d18d6d6e) | Aug 28, 2023 |
| Unknown       | Unknown                     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [8ee512db27](https://linux-hardware.org/?probe=8ee512db27) | Aug 27, 2023 |
| Acer          | Aspire M3470                | [7e6d230bf5](https://linux-hardware.org/?probe=7e6d230bf5) | Aug 27, 2023 |
| ASRock        | X570 Phantom Gaming 4S      | [1be18fe99f](https://linux-hardware.org/?probe=1be18fe99f) | Aug 27, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [512429f429](https://linux-hardware.org/?probe=512429f429) | Aug 27, 2023 |
| HP            | 802F                        | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| Gigabyte      | A520M S2H                   | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| ASUSTek       | Q170M2                      | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Dell          | 0D6H9T A00                  | [81b8c378f7](https://linux-hardware.org/?probe=81b8c378f7) | Aug 23, 2023 |
| ASUSTek       | P5Q-E                       | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [dedf0b23a3](https://linux-hardware.org/?probe=dedf0b23a3) | Aug 19, 2023 |
| ASRock        | B250M-HDV                   | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d8de59f346](https://linux-hardware.org/?probe=d8de59f346) | Aug 19, 2023 |
| MSI           | Indio                       | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| MSI           | Z97 PC Mate                 | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| MSI           | Z77A-G45                    | [b72192373b](https://linux-hardware.org/?probe=b72192373b) | Aug 17, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| ASRock        | B360M Pro4                  | [948ab98a6f](https://linux-hardware.org/?probe=948ab98a6f) | Aug 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [b53cba2654](https://linux-hardware.org/?probe=b53cba2654) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| MSI           | Z97 GAMING 7                | [8414f16824](https://linux-hardware.org/?probe=8414f16824) | Aug 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HP            | 158A                        | [96e7fa3b8f](https://linux-hardware.org/?probe=96e7fa3b8f) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| Dell          | 073Y7Y A00                  | [cbf4153713](https://linux-hardware.org/?probe=cbf4153713) | Aug 09, 2023 |
| Gigabyte      | H610M S2H DDR4              | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| HP            | 8876 11                     | [059d4c2db2](https://linux-hardware.org/?probe=059d4c2db2) | Aug 07, 2023 |
| HP            | 158A                        | [657812fbbf](https://linux-hardware.org/?probe=657812fbbf) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [48cf16e31d](https://linux-hardware.org/?probe=48cf16e31d) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [656e917b79](https://linux-hardware.org/?probe=656e917b79) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| HP            | 21D0                        | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [26cca552dd](https://linux-hardware.org/?probe=26cca552dd) | Aug 01, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| Unknown       | HX90                        | [2eba30b5be](https://linux-hardware.org/?probe=2eba30b5be) | Jul 30, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| ASRock        | B450M/ac                    | [51d9b57967](https://linux-hardware.org/?probe=51d9b57967) | Jul 29, 2023 |
| MSI           | B360M BAZOOKA               | [081608e70c](https://linux-hardware.org/?probe=081608e70c) | Jul 28, 2023 |
| Intel         | HM570                       | [c969a88e87](https://linux-hardware.org/?probe=c969a88e87) | Jul 28, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [3c0f7ba188](https://linux-hardware.org/?probe=3c0f7ba188) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Dell          | 00V62H A01                  | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| ASRock        | B360M Pro4                  | [20221ed288](https://linux-hardware.org/?probe=20221ed288) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| Gigabyte      | 970A-D3P                    | [fcb6317c1b](https://linux-hardware.org/?probe=fcb6317c1b) | Jul 25, 2023 |
| SiS Techno... | 760                         | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [df1a812c11](https://linux-hardware.org/?probe=df1a812c11) | Jul 24, 2023 |
| Gigabyte      | 970A-D3P                    | [bd66a96c97](https://linux-hardware.org/?probe=bd66a96c97) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [b844b9a353](https://linux-hardware.org/?probe=b844b9a353) | Jul 23, 2023 |
| Gigabyte      | B450M S2H                   | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| ASUSTek       | X99-DELUXE II               | [afc4d3c307](https://linux-hardware.org/?probe=afc4d3c307) | Jul 22, 2023 |
| HP            | 21D0                        | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| ASUSTek       | Q170M2                      | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| Biostar       | A320MH                      | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [874f8dff98](https://linux-hardware.org/?probe=874f8dff98) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [322db1cde6](https://linux-hardware.org/?probe=322db1cde6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| ASRock        | B450M Steel Legend          | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [61ed023e0c](https://linux-hardware.org/?probe=61ed023e0c) | Jul 16, 2023 |
| HP            | 8053                        | [bcdddcb036](https://linux-hardware.org/?probe=bcdddcb036) | Jul 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [91145d3929](https://linux-hardware.org/?probe=91145d3929) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| ASUSTek       | PRIME Z490-A                | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| ASRock        | B250M-HDV                   | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| MSI           | G41M-P33 Combo              | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| HP            | 21D0                        | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| MSI           | MS-7309                     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | H87-PRO                     | [ef2ca9e804](https://linux-hardware.org/?probe=ef2ca9e804) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Gigabyte      | X79-UD3                     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| ASRock        | B460M-HDV                   | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| Intel         | H61                         | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| Unknown       | Unknown                     | [ee4b75fe8e](https://linux-hardware.org/?probe=ee4b75fe8e) | Jul 09, 2023 |
| HP            | 83E2                        | [7764034dad](https://linux-hardware.org/?probe=7764034dad) | Jul 08, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Acer          | Predator G3600              | [79f515acf1](https://linux-hardware.org/?probe=79f515acf1) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1327d1ff3b](https://linux-hardware.org/?probe=1327d1ff3b) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e7a7107e85](https://linux-hardware.org/?probe=e7a7107e85) | Jul 07, 2023 |
| Dell          | 0K240Y A02                  | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| HP            | 8053                        | [66ee68d1ba](https://linux-hardware.org/?probe=66ee68d1ba) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [cd2c46c45c](https://linux-hardware.org/?probe=cd2c46c45c) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [bba1bf2655](https://linux-hardware.org/?probe=bba1bf2655) | Jul 04, 2023 |
| Foxconn       | H81MXV/H81MXV-D             | [5920f3fec9](https://linux-hardware.org/?probe=5920f3fec9) | Jul 04, 2023 |
| Chuwi         | RZBOX                       | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| HP            | 886C                        | [735b488512](https://linux-hardware.org/?probe=735b488512) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| Dell          | 0HD5W2 A01                  | [e3285ce484](https://linux-hardware.org/?probe=e3285ce484) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5a84f67b67](https://linux-hardware.org/?probe=5a84f67b67) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| Gigabyte      | Z77X-D3H                    | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [eb31590a2c](https://linux-hardware.org/?probe=eb31590a2c) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [b8194aee09](https://linux-hardware.org/?probe=b8194aee09) | Jun 28, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| AZW           | GTR V02                     | [d8a1975328](https://linux-hardware.org/?probe=d8a1975328) | Jun 27, 2023 |
| HP            | 2B2C                        | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| ASRock        | G31M-S                      | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| HP            | 859B                        | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [b598080123](https://linux-hardware.org/?probe=b598080123) | Jun 26, 2023 |
| HP            | 8599                        | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3df76bbd0e](https://linux-hardware.org/?probe=3df76bbd0e) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | [49172baecf](https://linux-hardware.org/?probe=49172baecf) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | 2B2C                        | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Intel         | X99H                        | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [f84d78f3cf](https://linux-hardware.org/?probe=f84d78f3cf) | Jun 24, 2023 |
| Intel         | H61                         | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| HP            | 0A54h                       | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [cafe332307](https://linux-hardware.org/?probe=cafe332307) | Jun 24, 2023 |
| HP            | 0A54h                       | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| ASRock        | B360M Pro4                  | [645a24c7bc](https://linux-hardware.org/?probe=645a24c7bc) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | B360M BAZOOKA               | [2807f81cc7](https://linux-hardware.org/?probe=2807f81cc7) | Jun 22, 2023 |
| Dell          | 0HD5W2 A01                  | [bbdbdd30a9](https://linux-hardware.org/?probe=bbdbdd30a9) | Jun 22, 2023 |
| HP            | 2B2C                        | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| HP            | 802F                        | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Gigabyte      | H87N-WIFI                   | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [5199a5d1f8](https://linux-hardware.org/?probe=5199a5d1f8) | Jun 22, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | [198b248306](https://linux-hardware.org/?probe=198b248306) | Jun 22, 2023 |
| MSI           | X99A SLI Krait Edition      | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| HP            | 802F                        | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| ASUSTek       | PRIME H510M-E               | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| ASRock        | B450 Pro4                   | [3acc831573](https://linux-hardware.org/?probe=3acc831573) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| Dell          | 06JWJY A01                  | [2131eadb5b](https://linux-hardware.org/?probe=2131eadb5b) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Intel         | H55                         | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| HP            | 886C                        | [ef429234c7](https://linux-hardware.org/?probe=ef429234c7) | Jun 16, 2023 |
| Intel         | H55                         | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| MSI           | B360M BAZOOKA               | [4448a99385](https://linux-hardware.org/?probe=4448a99385) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Intel         | H61                         | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| ASRock        | Z97 Extreme6                | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | [bd6a04d15d](https://linux-hardware.org/?probe=bd6a04d15d) | Jun 13, 2023 |
| Gigabyte      | B450M DS3H V2               | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | [58235def6c](https://linux-hardware.org/?probe=58235def6c) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | PRIME A520M-K               | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRock        | B360M Pro4                  | [396e828c07](https://linux-hardware.org/?probe=396e828c07) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| ASRock        | B450 Pro4                   | [49ebfc0459](https://linux-hardware.org/?probe=49ebfc0459) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| MSI           | MS-B9321                    | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| ASRock        | B360M Pro4                  | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| Dell          | 06D7TR A01                  | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| HP            | 8053                        | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Win elemen... | M600                        | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| Dell          | 0HD5W2 A01                  | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| ASUSTek       | Z97-K                       | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| Dell          | 002KVM A01                  | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [9171b7f0f0](https://linux-hardware.org/?probe=9171b7f0f0) | May 29, 2023 |
| ASRock        | H87M Pro4                   | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| ASUSTek       | PRIME Z370-P                | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3392305134](https://linux-hardware.org/?probe=3392305134) | May 26, 2023 |
| HP            | 8437                        | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| Gigabyte      | MFLP5IP-00                  | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| ASUSTek       | PRIME X299-A                | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| ASUSTek       | PRIME Z370-A                | [1387725836](https://linux-hardware.org/?probe=1387725836) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A                | [c309714d15](https://linux-hardware.org/?probe=c309714d15) | May 23, 2023 |
| MSI           | Z590-A PRO                  | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| ASUSTek       | P5Q-PRO                     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| HP            | 8599                        | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | B450M H                     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| MSI           | A320M-HDV R4.0              | [e7a27c7429](https://linux-hardware.org/?probe=e7a27c7429) | May 21, 2023 |
| MSI           | 970 GAMING                  | [222ebac915](https://linux-hardware.org/?probe=222ebac915) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| HP            | 8433 11                     | [5d9e3a1dcc](https://linux-hardware.org/?probe=5d9e3a1dcc) | May 20, 2023 |
| MSI           | MEG X570 UNIFY              | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| MSI           | 970 GAMING                  | [dde73bc060](https://linux-hardware.org/?probe=dde73bc060) | May 18, 2023 |
| MSI           | B450M-A PRO MAX             | [763654d8fc](https://linux-hardware.org/?probe=763654d8fc) | May 18, 2023 |
| HP            | 339A                        | [44a6e1f861](https://linux-hardware.org/?probe=44a6e1f861) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| MSI           | Z590-A PRO                  | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [d9b18c7990](https://linux-hardware.org/?probe=d9b18c7990) | May 16, 2023 |
| ASRock        | A300M-STX                   | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| Google        | Sumo                        | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [9beabf1347](https://linux-hardware.org/?probe=9beabf1347) | May 15, 2023 |
| Unknown       | HX90                        | [85edf2e24e](https://linux-hardware.org/?probe=85edf2e24e) | May 14, 2023 |
| Dell          | 0M017G A00                  | [5bd115a1b4](https://linux-hardware.org/?probe=5bd115a1b4) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| Dell          | 0M017G A00                  | [5e7cf34522](https://linux-hardware.org/?probe=5e7cf34522) | May 14, 2023 |
| MSI           | A320M-HDV R4.0              | [748e0f187f](https://linux-hardware.org/?probe=748e0f187f) | May 14, 2023 |
| MSI           | B450M PRO-VDH MAX           | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| ASUSTek       | PRIME Z490-A                | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | [0b4b06b5fa](https://linux-hardware.org/?probe=0b4b06b5fa) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| Lenovo        | 36EB SDK0K17763 WIN 1801... | [4d68e2912b](https://linux-hardware.org/?probe=4d68e2912b) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [13bace1181](https://linux-hardware.org/?probe=13bace1181) | May 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| ASRock        | B250M-HDV                   | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| ASRock        | B250M-HDV                   | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| ASRock        | H370 Pro4                   | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| ASUSTek       | PRIME X570-P                | [e28a5499a4](https://linux-hardware.org/?probe=e28a5499a4) | May 05, 2023 |
| Gigabyte      | 2AC8                        | [4f5b51c45e](https://linux-hardware.org/?probe=4f5b51c45e) | May 04, 2023 |
| Intel         | DG43GT AAE62768-300         | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Gigabyte      | X570S AERO G                | [cde129cf45](https://linux-hardware.org/?probe=cde129cf45) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9824006277](https://linux-hardware.org/?probe=9824006277) | Apr 26, 2023 |
| HP            | 18E7                        | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| Unknown       | Unknown                     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| ASUSTek       | PRIME Z490-A                | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| ASRock        | Z690 Extreme                | [3767d30290](https://linux-hardware.org/?probe=3767d30290) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H AC               | [d48ffa8191](https://linux-hardware.org/?probe=d48ffa8191) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| ASUSTek       | PRIME X570-P                | [512bad7a33](https://linux-hardware.org/?probe=512bad7a33) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Unknown       | Unknown                     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [fa729987de](https://linux-hardware.org/?probe=fa729987de) | Apr 09, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [cd157a6ebf](https://linux-hardware.org/?probe=cd157a6ebf) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| Biostar       | TZ77B                       | [c5d5603dc4](https://linux-hardware.org/?probe=c5d5603dc4) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [09679af7dc](https://linux-hardware.org/?probe=09679af7dc) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e78d2454c](https://linux-hardware.org/?probe=1e78d2454c) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| HP            | 8399                        | [d8c0ad05f5](https://linux-hardware.org/?probe=d8c0ad05f5) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| ASUSTek       | Q170M2                      | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| Dell          | 0W2F8G A02                  | [511510b501](https://linux-hardware.org/?probe=511510b501) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| Dell          | 0T1D10 A01                  | [6c4d5eee3f](https://linux-hardware.org/?probe=6c4d5eee3f) | Mar 25, 2023 |
| ASRock        | Z370M Pro4                  | [765602e7bf](https://linux-hardware.org/?probe=765602e7bf) | Mar 24, 2023 |
| MSI           | A320M-HDV R4.0              | [a04e0acbcf](https://linux-hardware.org/?probe=a04e0acbcf) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [5b6af55009](https://linux-hardware.org/?probe=5b6af55009) | Mar 23, 2023 |
| HP            | 828A                        | [cce5214801](https://linux-hardware.org/?probe=cce5214801) | Mar 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| HP            | 18E8                        | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| ASUSTek       | PRIME X570-P                | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Unknown       | Unknown                     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASRock        | 970 Extreme4                | [42391e1ac6](https://linux-hardware.org/?probe=42391e1ac6) | Mar 16, 2023 |
| Lenovo        | 36EB NOK                    | [b6d8243d49](https://linux-hardware.org/?probe=b6d8243d49) | Mar 15, 2023 |
| HP            | 828A                        | [9d6df1b56e](https://linux-hardware.org/?probe=9d6df1b56e) | Mar 15, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| Dell          | 08NPPY A00                  | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| Gigabyte      | H61MS                       | [bdf01893f8](https://linux-hardware.org/?probe=bdf01893f8) | Mar 10, 2023 |
| Gigabyte      | H61MS                       | [24444c6d30](https://linux-hardware.org/?probe=24444c6d30) | Mar 08, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [f500d72edd](https://linux-hardware.org/?probe=f500d72edd) | Mar 08, 2023 |
| HP            | 8055                        | [0b9ddd5940](https://linux-hardware.org/?probe=0b9ddd5940) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ArcoLinux Rolling  | 1151     | 93.58%  |
| ArcoLinux          | 54       | 4.39%   |
| ArcoLinux 20.7.5   | 4        | 0.33%   |
| ArcoLinux 20.6.5   | 3        | 0.24%   |
| ArcoLinux 19.12.15 | 3        | 0.24%   |
| ArcoLinux 20.3.4   | 2        | 0.16%   |
| ArcoLinux 20.2.12  | 2        | 0.16%   |
| ArcoLinux 19.07.11 | 2        | 0.16%   |
| ArcoLinux 6.9.1    | 1        | 0.08%   |
| ArcoLinux 20.5.7   | 1        | 0.08%   |
| ArcoLinux 20.5.2   | 1        | 0.08%   |
| ArcoLinux 20.4.11  | 1        | 0.08%   |
| ArcoLinux 20.3.3   | 1        | 0.08%   |
| ArcoLinux 20.2.9   | 1        | 0.08%   |
| ArcoLinux 20.1.4   | 1        | 0.08%   |
| ArcoLinux 19.11.3  | 1        | 0.08%   |
| ArcoLinux 19.02.4  | 1        | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ArcoLinux | 1219     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 6.6.1-arch1-1     | 31       | 1.89%   |
| 5.15.7-arch1-1    | 26       | 1.59%   |
| 6.4.12-arch1-1    | 21       | 1.28%   |
| 6.3.8-arch1-1     | 21       | 1.28%   |
| 5.16.11-arch1-1   | 18       | 1.1%    |
| 5.15.10-arch1-1   | 18       | 1.1%    |
| 5.13.13-arch1-1   | 18       | 1.1%    |
| 6.8.1-arch1-1     | 17       | 1.04%   |
| 6.3.9-arch1-1     | 17       | 1.04%   |
| 6.7.9-arch1-1     | 16       | 0.98%   |
| 6.7.0-arch3-1     | 16       | 0.98%   |
| 6.6.8-arch1-1     | 15       | 0.92%   |
| 6.2.11-arch1-1    | 15       | 0.92%   |
| 5.8.14-arch1-1    | 14       | 0.86%   |
| 6.8.7-arch1-1     | 13       | 0.79%   |
| 6.7.4-arch1-1     | 13       | 0.79%   |
| 6.3.2-arch1-1     | 13       | 0.79%   |
| 6.2.8-arch1-1     | 13       | 0.79%   |
| 6.6.2-arch1-1     | 11       | 0.67%   |
| 6.5.9-arch2-1     | 11       | 0.67%   |
| 6.4.11-arch1-1    | 11       | 0.67%   |
| 6.3.3-arch1-1     | 11       | 0.67%   |
| 5.14.14-arch1-1   | 11       | 0.67%   |
| 6.6.7-arch1-1     | 10       | 0.61%   |
| 6.5.8-arch1-1     | 10       | 0.61%   |
| 6.5.7-arch1-1     | 10       | 0.61%   |
| 6.4.10-arch1-1    | 10       | 0.61%   |
| 5.9.14-arch1-1    | 10       | 0.61%   |
| 6.3.1-arch1-1     | 9        | 0.55%   |
| 6.8.2-arch2-1     | 8        | 0.49%   |
| 6.7.8-arch1-1     | 8        | 0.49%   |
| 6.5.3-arch1-1     | 8        | 0.49%   |
| 6.1.12-arch1-1    | 8        | 0.49%   |
| 6.0.12-arch1-1    | 8        | 0.49%   |
| 5.19.13-arch1-1   | 8        | 0.49%   |
| 5.15.7-zen1-1-zen | 8        | 0.49%   |
| 5.15.4-arch1-1    | 8        | 0.49%   |
| 6.8.5-arch1-1     | 7        | 0.43%   |
| 6.6.9-arch1-1     | 7        | 0.43%   |
| 6.6.3-arch1-1     | 7        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.7  | 34       | 2.08%   |
| 6.6.1   | 32       | 1.96%   |
| 6.3.8   | 28       | 1.71%   |
| 6.4.12  | 27       | 1.65%   |
| 6.8.7   | 21       | 1.28%   |
| 6.7.0   | 21       | 1.28%   |
| 6.3.9   | 21       | 1.28%   |
| 6.8.1   | 20       | 1.22%   |
| 6.7.9   | 20       | 1.22%   |
| 5.16.11 | 20       | 1.22%   |
| 5.15.10 | 20       | 1.22%   |
| 6.6.8   | 18       | 1.1%    |
| 6.3.2   | 18       | 1.1%    |
| 5.13.13 | 18       | 1.1%    |
| 6.7.4   | 17       | 1.04%   |
| 6.4.11  | 17       | 1.04%   |
| 6.2.11  | 17       | 1.04%   |
| 6.3.3   | 16       | 0.98%   |
| 6.3.1   | 16       | 0.98%   |
| 6.6.7   | 15       | 0.92%   |
| 6.5.3   | 14       | 0.86%   |
| 6.2.8   | 14       | 0.86%   |
| 6.1.12  | 14       | 0.86%   |
| 6.0.2   | 14       | 0.86%   |
| 5.8.14  | 14       | 0.86%   |
| 6.5.9   | 13       | 0.8%    |
| 6.5.8   | 12       | 0.73%   |
| 6.5.7   | 12       | 0.73%   |
| 6.4.2   | 12       | 0.73%   |
| 6.4.1   | 12       | 0.73%   |
| 5.15.4  | 12       | 0.73%   |
| 6.8.5   | 11       | 0.67%   |
| 6.8.2   | 11       | 0.67%   |
| 6.7.6   | 11       | 0.67%   |
| 6.6.2   | 11       | 0.67%   |
| 6.5.5   | 11       | 0.67%   |
| 6.3.5   | 11       | 0.67%   |
| 6.2.10  | 11       | 0.67%   |
| 5.14.14 | 11       | 0.67%   |
| 6.4.10  | 10       | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15     | 147      | 9.47%   |
| 6.6      | 129      | 8.31%   |
| 6.3      | 123      | 7.92%   |
| 6.1      | 111      | 7.15%   |
| 6.4      | 108      | 6.95%   |
| 6.7      | 89       | 5.73%   |
| 5.10     | 83       | 5.34%   |
| 6.2      | 77       | 4.96%   |
| 6.8      | 75       | 4.83%   |
| 6.5      | 72       | 4.64%   |
| 5.16     | 62       | 3.99%   |
| 6.0      | 60       | 3.86%   |
| 5.14     | 57       | 3.67%   |
| 5.9      | 49       | 3.16%   |
| 5.12     | 44       | 2.83%   |
| 5.13     | 43       | 2.77%   |
| 5.18     | 41       | 2.64%   |
| 5.11     | 41       | 2.64%   |
| 5.17     | 38       | 2.45%   |
| 5.19     | 34       | 2.19%   |
| 5.8      | 28       | 1.8%    |
| 5.4      | 21       | 1.35%   |
| 5.6      | 5        | 0.32%   |
| 5.3      | 3        | 0.19%   |
| 5.7      | 2        | 0.13%   |
| 5.5      | 2        | 0.13%   |
| 5.15.96  | 2        | 0.13%   |
| 4.19     | 2        | 0.13%   |
| 6.3.3    | 1        | 0.06%   |
| 6.2.0    | 1        | 0.06%   |
| 5.15.107 | 1        | 0.06%   |
| 5.0      | 1        | 0.06%   |
| 4.17     | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1219     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| XFCE           | 463      | 33.82%  |
| KDE5           | 286      | 20.89%  |
| GNOME          | 100      | 7.3%    |
| i3             | 80       | 5.84%   |
| awesome        | 56       | 4.09%   |
| Cinnamon       | 53       | 3.87%   |
| Hyprland       | 37       | 2.7%    |
| X-Cinnamon     | 35       | 2.56%   |
| qtile          | 34       | 2.48%   |
| bspwm          | 26       | 1.9%    |
| Unknown        | 25       | 1.83%   |
| xmonad         | 22       | 1.61%   |
| Deepin         | 20       | 1.46%   |
| KDE6           | 16       | 1.17%   |
| Budgie         | 16       | 1.17%   |
| LXQt           | 15       | 1.1%    |
| LeftWM         | 14       | 1.02%   |
| DWM            | 13       | 0.95%   |
| KDE            | 12       | 0.88%   |
| MATE           | 10       | 0.73%   |
| chadwm         | 10       | 0.73%   |
| herbstluftwm   | 5        | 0.37%   |
| i3-with-shmlog | 4        | 0.29%   |
| Cutefish       | 4        | 0.29%   |
| sway           | 3        | 0.22%   |
| wayfire        | 2        | 0.15%   |
| openbox        | 2        | 0.15%   |
| Unity          | 1        | 0.07%   |
| LXDE           | 1        | 0.07%   |
| ICEWM          | 1        | 0.07%   |
| Hypr           | 1        | 0.07%   |
| GNOME Classic  | 1        | 0.07%   |
| dusk           | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1066     | 84.4%   |
| Wayland | 108      | 8.55%   |
| Tty     | 73       | 5.78%   |
| Unknown | 16       | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 847      | 65.2%   |
| LightDM | 213      | 16.4%   |
| TDM     | 133      | 10.24%  |
| Unknown | 76       | 5.85%   |
| GDM     | 22       | 1.69%   |
| Ly      | 5        | 0.38%   |
| LXDM    | 3        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 644      | 51.89%  |
| en_GB   | 109      | 8.78%   |
| de_DE   | 51       | 4.11%   |
| C       | 48       | 3.87%   |
| en_CA   | 44       | 3.55%   |
| ru_RU   | 36       | 2.9%    |
| fr_FR   | 29       | 2.34%   |
| pt_BR   | 28       | 2.26%   |
| en_AU   | 27       | 2.18%   |
| es_ES   | 24       | 1.93%   |
| en_IN   | 22       | 1.77%   |
| it_IT   | 18       | 1.45%   |
| en_ZA   | 11       | 0.89%   |
| es_AR   | 10       | 0.81%   |
| tr_TR   | 9        | 0.73%   |
| hu_HU   | 9        | 0.73%   |
| es_MX   | 9        | 0.73%   |
| sv_SE   | 8        | 0.64%   |
| pl_PL   | 7        | 0.56%   |
| Unknown | 7        | 0.56%   |
| nl_NL   | 6        | 0.48%   |
| zh_CN   | 5        | 0.4%    |
| pt_PT   | 5        | 0.4%    |
| fi_FI   | 5        | 0.4%    |
| nl_BE   | 4        | 0.32%   |
| fr_CA   | 4        | 0.32%   |
| en_DK   | 4        | 0.32%   |
| da_DK   | 4        | 0.32%   |
| ja_JP   | 3        | 0.24%   |
| es_CO   | 3        | 0.24%   |
| en_IL   | 3        | 0.24%   |
| en_IE   | 3        | 0.24%   |
| de_AT   | 3        | 0.24%   |
| uk_UA   | 2        | 0.16%   |
| ru_UA   | 2        | 0.16%   |
| nb_NO   | 2        | 0.16%   |
| ko_KR   | 2        | 0.16%   |
| es_VE   | 2        | 0.16%   |
| es_UY   | 2        | 0.16%   |
| es_BO   | 2        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 918      | 74.03%  |
| BIOS | 322      | 25.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 852      | 66.72%  |
| Btrfs    | 305      | 23.88%  |
| Overlay  | 78       | 6.11%   |
| F2fs     | 17       | 1.33%   |
| Xfs      | 15       | 1.17%   |
| Unknown  | 7        | 0.55%   |
| Reiserfs | 2        | 0.16%   |
| Jfs      | 1        | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1020     | 82.19%  |
| MBR     | 149      | 12.01%  |
| Unknown | 72       | 5.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 839      | 65.09%  |
| Yes       | 450      | 34.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 649      | 51.55%  |
| No        | 610      | 48.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 352      | 28.88%  |
| Gigabyte Technology                  | 233      | 19.11%  |
| MSI                                  | 189      | 15.5%   |
| ASRock                               | 112      | 9.19%   |
| Dell                                 | 77       | 6.32%   |
| Hewlett-Packard                      | 71       | 5.82%   |
| Lenovo                               | 34       | 2.79%   |
| Acer                                 | 20       | 1.64%   |
| Unknown                              | 18       | 1.48%   |
| Intel                                | 17       | 1.39%   |
| Supermicro                           | 15       | 1.23%   |
| Fujitsu                              | 8        | 0.66%   |
| Biostar                              | 6        | 0.49%   |
| Huanan                               | 5        | 0.41%   |
| Foxconn                              | 5        | 0.41%   |
| BESSTAR Tech                         | 5        | 0.41%   |
| Pegatron                             | 4        | 0.33%   |
| Medion                               | 4        | 0.33%   |
| Apple                                | 4        | 0.33%   |
| AZW                                  | 3        | 0.25%   |
| Alienware                            | 3        | 0.25%   |
| SYWZ                                 | 2        | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.16%   |
| Packard Bell                         | 2        | 0.16%   |
| NZXT                                 | 2        | 0.16%   |
| MACHINIST                            | 2        | 0.16%   |
| ECS                                  | 2        | 0.16%   |
| Win element                          | 1        | 0.08%   |
| VS Company                           | 1        | 0.08%   |
| SZMZ                                 | 1        | 0.08%   |
| System76                             | 1        | 0.08%   |
| SiS Technology                       | 1        | 0.08%   |
| Shuttle                              | 1        | 0.08%   |
| Seeed Studio                         | 1        | 0.08%   |
| Proline                              | 1        | 0.08%   |
| Positivo                             | 1        | 0.08%   |
| PLEXHD                               | 1        | 0.08%   |
| Maibenben                            | 1        | 0.08%   |
| Kllisre                              | 1        | 0.08%   |
| IceWhale Technology                  | 1        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS    | 22       | 1.8%    |
| ASUS All Series              | 21       | 1.72%   |
| Unknown                      | 19       | 1.56%   |
| ASUS ROG STRIX B550-F GAMING | 13       | 1.07%   |
| MSI MS-7C37                  | 12       | 0.98%   |
| ASUS PRIME X570-P            | 12       | 0.98%   |
| Supermicro SYS-5019A-FTN4    | 10       | 0.82%   |
| MSI MS-7C91                  | 10       | 0.82%   |
| MSI MS-7B89                  | 9        | 0.74%   |
| MSI MS-7B79                  | 9        | 0.74%   |
| MSI MS-7C02                  | 8        | 0.66%   |
| MSI MS-7A38                  | 8        | 0.66%   |
| Gigabyte X570 AORUS MASTER   | 8        | 0.66%   |
| Gigabyte X570 AORUS ELITE    | 8        | 0.66%   |
| Dell OptiPlex 7010           | 8        | 0.66%   |
| ASUS PRIME X470-PRO          | 8        | 0.66%   |
| Gigabyte X570 GAMING X       | 7        | 0.57%   |
| Gigabyte B450 AORUS ELITE    | 7        | 0.57%   |
| ASUS PRIME A320M-K           | 7        | 0.57%   |
| MSI MS-7C56                  | 6        | 0.49%   |
| MSI MS-7B86                  | 6        | 0.49%   |
| Gigabyte B450M DS3H V2       | 6        | 0.49%   |
| Dell OptiPlex 9020           | 6        | 0.49%   |
| Dell OptiPlex 9010           | 6        | 0.49%   |
| ASUS Z170 PRO GAMING         | 6        | 0.49%   |
| ASUS ROG CROSSHAIR VIII HERO | 6        | 0.49%   |
| ASUS PRIME B450M-A           | 6        | 0.49%   |
| ASRock B450M Pro4            | 6        | 0.49%   |
| MSI MS-7C95                  | 5        | 0.41%   |
| MSI MS-7971                  | 5        | 0.41%   |
| HP ProDesk 600 G1 SFF        | 5        | 0.41%   |
| Gigabyte X570 AORUS PRO WIFI | 5        | 0.41%   |
| ASUS ROG STRIX X570-E GAMING | 5        | 0.41%   |
| ASUS M5A78L-M/USB3           | 5        | 0.41%   |
| MSI MS-7C35                  | 4        | 0.33%   |
| MSI MS-7B98                  | 4        | 0.33%   |
| MSI MS-7817                  | 4        | 0.33%   |
| Intel H61                    | 4        | 0.33%   |
| HP EliteDesk 800 G1 SFF      | 4        | 0.33%   |
| HP Compaq Elite 8300 SFF     | 4        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 96       | 7.88%   |
| ASUS ROG                  | 78       | 6.4%    |
| ASUS TUF                  | 59       | 4.84%   |
| Dell OptiPlex             | 48       | 3.94%   |
| Gigabyte X570             | 31       | 2.54%   |
| ASUS All                  | 21       | 1.72%   |
| Lenovo ThinkCentre        | 20       | 1.64%   |
| Unknown                   | 19       | 1.56%   |
| Gigabyte B450M            | 17       | 1.39%   |
| Gigabyte B450             | 14       | 1.15%   |
| MSI MS-7C37               | 12       | 0.98%   |
| HP ProDesk                | 12       | 0.98%   |
| HP EliteDesk              | 12       | 0.98%   |
| HP Compaq                 | 12       | 0.98%   |
| Gigabyte B550             | 12       | 0.98%   |
| ASRock B450M              | 12       | 0.98%   |
| Supermicro SYS-5019A-FTN4 | 10       | 0.82%   |
| MSI MS-7C91               | 10       | 0.82%   |
| MSI MS-7B89               | 9        | 0.74%   |
| MSI MS-7B79               | 9        | 0.74%   |
| ASUS P8Z77-V              | 9        | 0.74%   |
| MSI MS-7C02               | 8        | 0.66%   |
| MSI MS-7A38               | 8        | 0.66%   |
| Dell Inspiron             | 8        | 0.66%   |
| Acer Aspire               | 8        | 0.66%   |
| Lenovo IdeaCentre         | 7        | 0.57%   |
| Gigabyte Z390             | 7        | 0.57%   |
| Dell Vostro               | 7        | 0.57%   |
| Dell Precision            | 7        | 0.57%   |
| ASUS Z170                 | 7        | 0.57%   |
| ASUS P8H61-M              | 7        | 0.57%   |
| ASRock B450               | 7        | 0.57%   |
| Acer Predator             | 7        | 0.57%   |
| MSI MS-7C56               | 6        | 0.49%   |
| MSI MS-7B86               | 6        | 0.49%   |
| HP Pavilion               | 6        | 0.49%   |
| Fujitsu ESPRIMO           | 6        | 0.49%   |
| ASUS STRIX                | 6        | 0.49%   |
| ASUS M5A78L-M             | 6        | 0.49%   |
| MSI MS-7C95               | 5        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 194      | 15.91%  |
| 2019    | 178      | 14.6%   |
| 2020    | 160      | 13.13%  |
| 2021    | 95       | 7.79%   |
| 2017    | 77       | 6.32%   |
| 2013    | 76       | 6.23%   |
| 2012    | 66       | 5.41%   |
| 2016    | 62       | 5.09%   |
| 2014    | 60       | 4.92%   |
| 2022    | 57       | 4.68%   |
| 2015    | 55       | 4.51%   |
| 2011    | 47       | 3.86%   |
| 2010    | 29       | 2.38%   |
| 2023    | 21       | 1.72%   |
| 2009    | 14       | 1.15%   |
| 2008    | 13       | 1.07%   |
| 2007    | 7        | 0.57%   |
| 2006    | 5        | 0.41%   |
| 2005    | 1        | 0.08%   |
| 2004    | 1        | 0.08%   |
| Unknown | 1        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1219     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1218     | 99.84%  |
| Enabled  | 2        | 0.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1218     | 99.92%  |
| Yes  | 1        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 372      | 29.81%  |
| 32.01-64.0      | 354      | 28.37%  |
| 8.01-16.0       | 185      | 14.82%  |
| 4.01-8.0        | 118      | 9.46%   |
| 64.01-256.0     | 97       | 7.77%   |
| 3.01-4.0        | 57       | 4.57%   |
| 24.01-32.0      | 56       | 4.49%   |
| 1.01-2.0        | 4        | 0.32%   |
| More than 256.0 | 2        | 0.16%   |
| 2.01-3.0        | 2        | 0.16%   |
| Unknown         | 1        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 384      | 26.7%   |
| 2.01-3.0    | 343      | 23.85%  |
| 4.01-8.0    | 274      | 19.05%  |
| 3.01-4.0    | 223      | 15.51%  |
| 0.51-1.0    | 98       | 6.82%   |
| 8.01-16.0   | 86       | 5.98%   |
| 0.01-0.5    | 17       | 1.18%   |
| 16.01-24.0  | 9        | 0.63%   |
| 32.01-64.0  | 1        | 0.07%   |
| 24.01-32.0  | 1        | 0.07%   |
| 64.01-256.0 | 1        | 0.07%   |
| Unknown     | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 387      | 29.75%  |
| 3      | 286      | 21.98%  |
| 1      | 274      | 21.06%  |
| 4      | 175      | 13.45%  |
| 5      | 93       | 7.15%   |
| 6      | 40       | 3.07%   |
| 7      | 19       | 1.46%   |
| 8      | 7        | 0.54%   |
| 9      | 6        | 0.46%   |
| 0      | 5        | 0.38%   |
| 11     | 3        | 0.23%   |
| 10     | 2        | 0.15%   |
| 21     | 1        | 0.08%   |
| 20     | 1        | 0.08%   |
| 19     | 1        | 0.08%   |
| 13     | 1        | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 899      | 72.73%  |
| Yes       | 337      | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1214     | 99.59%  |
| No        | 5        | 0.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 639      | 51.74%  |
| Yes       | 596      | 48.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 661      | 52.92%  |
| Yes       | 588      | 47.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 294      | 23.98%  |
| Germany      | 92       | 7.5%    |
| UK           | 85       | 6.93%   |
| Canada       | 58       | 4.73%   |
| Brazil       | 51       | 4.16%   |
| Russia       | 41       | 3.34%   |
| France       | 34       | 2.77%   |
| Australia    | 31       | 2.53%   |
| Spain        | 30       | 2.45%   |
| India        | 30       | 2.45%   |
| Sweden       | 26       | 2.12%   |
| Netherlands  | 23       | 1.88%   |
| Belgium      | 23       | 1.88%   |
| Italy        | 22       | 1.79%   |
| Mexico       | 21       | 1.71%   |
| Argentina    | 19       | 1.55%   |
| Poland       | 17       | 1.39%   |
| Turkey       | 15       | 1.22%   |
| Hungary      | 14       | 1.14%   |
| Portugal     | 13       | 1.06%   |
| Austria      | 13       | 1.06%   |
| Romania      | 12       | 0.98%   |
| Norway       | 12       | 0.98%   |
| South Africa | 11       | 0.9%    |
| Finland      | 11       | 0.9%    |
| Bulgaria     | 10       | 0.82%   |
| Ukraine      | 9        | 0.73%   |
| Denmark      | 9        | 0.73%   |
| Switzerland  | 8        | 0.65%   |
| Greece       | 8        | 0.65%   |
| Colombia     | 8        | 0.65%   |
| Uruguay      | 7        | 0.57%   |
| Malaysia     | 7        | 0.57%   |
| Ireland      | 7        | 0.57%   |
| Czechia      | 7        | 0.57%   |
| Vietnam      | 6        | 0.49%   |
| Serbia       | 6        | 0.49%   |
| Japan        | 6        | 0.49%   |
| Indonesia    | 6        | 0.49%   |
| Egypt        | 6        | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sydney           | 14       | 1.06%   |
| Durham           | 14       | 1.06%   |
| Berlin           | 12       | 0.91%   |
| Vienna           | 10       | 0.76%   |
| Sao Paulo        | 10       | 0.76%   |
| Moscow           | 9        | 0.68%   |
| Atlanta          | 9        | 0.68%   |
| Warsaw           | 8        | 0.6%    |
| Istanbul         | 8        | 0.6%    |
| Helsinki         | 8        | 0.6%    |
| Toronto          | 7        | 0.53%   |
| Montevideo       | 7        | 0.53%   |
| Madrid           | 7        | 0.53%   |
| London           | 7        | 0.53%   |
| Lier             | 7        | 0.53%   |
| Chicago          | 7        | 0.53%   |
| Amsterdam        | 7        | 0.53%   |
| Stockholm        | 6        | 0.45%   |
| Sofia            | 6        | 0.45%   |
| New York         | 6        | 0.45%   |
| Wilrijk          | 5        | 0.38%   |
| Portland         | 5        | 0.38%   |
| Perth            | 5        | 0.38%   |
| Oslo             | 5        | 0.38%   |
| Nairobi          | 5        | 0.38%   |
| Montreal         | 5        | 0.38%   |
| Las Vegas        | 5        | 0.38%   |
| Houston          | 5        | 0.38%   |
| Dublin           | 5        | 0.38%   |
| Dallas           | 5        | 0.38%   |
| Columbus         | 5        | 0.38%   |
| Budapest         | 5        | 0.38%   |
| Bucharest        | 5        | 0.38%   |
| Zapopan          | 4        | 0.3%    |
| St Petersburg    | 4        | 0.3%    |
| Singapore        | 4        | 0.3%    |
| Shetland Islands | 4        | 0.3%    |
| San Juan         | 4        | 0.3%    |
| Miami            | 4        | 0.3%    |
| Melbourne        | 4        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 471      | 1012   | 17.17%  |
| WDC                          | 452      | 861    | 16.48%  |
| Seagate                      | 410      | 694    | 14.95%  |
| Kingston                     | 168      | 275    | 6.12%   |
| Sandisk                      | 145      | 211    | 5.29%   |
| Toshiba                      | 132      | 185    | 4.81%   |
| Crucial                      | 119      | 186    | 4.34%   |
| Phison Electronics           | 62       | 102    | 2.26%   |
| Hitachi                      | 61       | 85     | 2.22%   |
| A-DATA Technology            | 54       | 73     | 1.97%   |
| Micron/Crucial Technology    | 41       | 58     | 1.49%   |
| Silicon Motion               | 37       | 53     | 1.35%   |
| Intel                        | 34       | 55     | 1.24%   |
| China                        | 29       | 47     | 1.06%   |
| Kingston Technology Company  | 27       | 36     | 0.98%   |
| SK hynix                     | 25       | 43     | 0.91%   |
| Unknown                      | 24       | 36     | 0.87%   |
| HGST                         | 21       | 35     | 0.77%   |
| SPCC                         | 20       | 26     | 0.73%   |
| PNY                          | 20       | 32     | 0.73%   |
| Phison                       | 20       | 34     | 0.73%   |
| Corsair                      | 17       | 35     | 0.62%   |
| ADATA Technology             | 15       | 17     | 0.55%   |
| Patriot                      | 14       | 21     | 0.51%   |
| JMicron Technology           | 14       | 16     | 0.51%   |
| Realtek Semiconductor        | 13       | 16     | 0.47%   |
| MAXIO Technology (Hangzhou)  | 12       | 17     | 0.44%   |
| Hewlett-Packard              | 12       | 19     | 0.44%   |
| SABRENT                      | 11       | 13     | 0.4%    |
| OCZ                          | 11       | 15     | 0.4%    |
| Gigabyte Technology          | 11       | 14     | 0.4%    |
| XPG                          | 10       | 13     | 0.36%   |
| Transcend                    | 10       | 14     | 0.36%   |
| Plextor                      | 10       | 12     | 0.36%   |
| ASMT                         | 9        | 14     | 0.33%   |
| Maxtor                       | 7        | 10     | 0.26%   |
| Intenso                      | 7        | 11     | 0.26%   |
| Team                         | 5        | 6      | 0.18%   |
| Shenzhen Longsys Electronics | 5        | 10     | 0.18%   |
| Micron Technology            | 5        | 10     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 78       | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 45       | 1.36%   |
| Samsung SSD 860 EVO 500GB                             | 43       | 1.3%    |
| Kingston SA400S37240G 240GB SSD                       | 41       | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB                        | 37       | 1.12%   |
| Samsung SSD 850 EVO 250GB                             | 36       | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB                        | 35       | 1.06%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 33       | 1%      |
| Samsung SSD 860 EVO 1TB                               | 29       | 0.87%   |
| Samsung SSD 850 EVO 500GB                             | 28       | 0.84%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 27       | 0.81%   |
| Samsung SSD 870 EVO 1TB                               | 26       | 0.78%   |
| Phison E12 NVMe Controller 2TB                        | 26       | 0.78%   |
| Crucial CT1000MX500SSD1 1TB                           | 26       | 0.78%   |
| Toshiba DT01ACA100 1TB                                | 24       | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 23       | 0.69%   |
| Kingston SA400S37480G 480GB SSD                       | 23       | 0.69%   |
| Kingston SA400S37120G 120GB SSD                       | 22       | 0.66%   |
| Samsung SSD 860 EVO 250GB                             | 21       | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                        | 20       | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 20       | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB                        | 19       | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                        | 18       | 0.54%   |
| Samsung SSD 980 1TB                                   | 18       | 0.54%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 18       | 0.54%   |
| Toshiba HDWD110 1TB                                   | 17       | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                        | 17       | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                        | 15       | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                          | 15       | 0.45%   |
| Crucial CT500MX500SSD1 500GB                          | 15       | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 14       | 0.42%   |
| Unknown SD/MMC/MS PRO 128GB                           | 14       | 0.42%   |
| Crucial CT240BX500SSD1 240GB                          | 14       | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 13       | 0.39%   |
| Samsung SSD 840 EVO 250GB                             | 13       | 0.39%   |
| Samsung SSD 970 EVO 1TB                               | 12       | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 11       | 0.33%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 11       | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 11       | 0.33%   |
| Toshiba HDWD120 2TB                                   | 11       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 399      | 664    | 36.98%  |
| WDC                 | 368      | 678    | 34.11%  |
| Toshiba             | 106      | 151    | 9.82%   |
| Hitachi             | 61       | 85     | 5.65%   |
| Samsung Electronics | 49       | 71     | 4.54%   |
| HGST                | 19       | 31     | 1.76%   |
| Unknown             | 16       | 23     | 1.48%   |
| JMicron Technology  | 11       | 13     | 1.02%   |
| SABRENT             | 8        | 9      | 0.74%   |
| Maxtor              | 6        | 9      | 0.56%   |
| ASMT                | 5        | 9      | 0.46%   |
| TO Exter            | 4        | 4      | 0.37%   |
| Hewlett-Packard     | 4        | 6      | 0.37%   |
| Fujitsu             | 4        | 5      | 0.37%   |
| ASMedia             | 3        | 4      | 0.28%   |
| Inateck             | 2        | 2      | 0.19%   |
| WD MediaMax         | 1        | 1      | 0.09%   |
| USB3.0              | 1        | 1      | 0.09%   |
| TDAS                | 1        | 4      | 0.09%   |
| RSH-319             | 1        | 1      | 0.09%   |
| Min Yi U            | 1        | 1      | 0.09%   |
| Maxone              | 1        | 1      | 0.09%   |
| Intenso             | 1        | 1      | 0.09%   |
| HGST HUS            | 1        | 1      | 0.09%   |
| HGST HTS            | 1        | 1      | 0.09%   |
| H/W                 | 1        | 12     | 0.09%   |
| External            | 1        | 1      | 0.09%   |
| ExcelStor           | 1        | 2      | 0.09%   |
| CSD                 | 1        | 1      | 0.09%   |
| Unknown             | 1        | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 275      | 518    | 27.09%  |
| Kingston            | 132      | 197    | 13%     |
| Crucial             | 107      | 165    | 10.54%  |
| WDC                 | 87       | 140    | 8.57%   |
| SanDisk             | 72       | 98     | 7.09%   |
| A-DATA Technology   | 43       | 60     | 4.24%   |
| China               | 29       | 47     | 2.86%   |
| PNY                 | 20       | 30     | 1.97%   |
| SPCC                | 16       | 20     | 1.58%   |
| SK hynix            | 14       | 29     | 1.38%   |
| Patriot             | 14       | 21     | 1.38%   |
| Toshiba             | 11       | 16     | 1.08%   |
| OCZ                 | 11       | 15     | 1.08%   |
| Intel               | 11       | 13     | 1.08%   |
| Corsair             | 9        | 19     | 0.89%   |
| Transcend           | 8        | 12     | 0.79%   |
| Plextor             | 8        | 10     | 0.79%   |
| Hewlett-Packard     | 7        | 11     | 0.69%   |
| Gigabyte Technology | 7        | 8      | 0.69%   |
| Intenso             | 6        | 10     | 0.59%   |
| Team                | 5        | 6      | 0.49%   |
| KingSpec            | 5        | 7      | 0.49%   |
| Apacer              | 5        | 5      | 0.49%   |
| LITEON              | 4        | 4      | 0.39%   |
| GOODRAM             | 4        | 4      | 0.39%   |
| Acer                | 4        | 4      | 0.39%   |
| Unknown             | 4        | 4      | 0.39%   |
| T-FORCE             | 3        | 3      | 0.3%    |
| SSK                 | 3        | 3      | 0.3%    |
| Seagate             | 3        | 7      | 0.3%    |
| Mushkin             | 3        | 6      | 0.3%    |
| Micron Technology   | 3        | 7      | 0.3%    |
| LITEONIT            | 3        | 3      | 0.3%    |
| Lexar               | 3        | 3      | 0.3%    |
| Leven               | 3        | 3      | 0.3%    |
| HS-SSD-C100         | 3        | 3      | 0.3%    |
| External            | 3        | 7      | 0.3%    |
| AMD                 | 3        | 4      | 0.3%    |
| XrayDisk            | 2        | 3      | 0.2%    |
| Vaseky              | 2        | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 812      | 1793   | 36.38%  |
| SSD     | 766      | 1603   | 34.32%  |
| NVMe    | 625      | 1212   | 28%     |
| Unknown | 27       | 39     | 1.21%   |
| MMC     | 2        | 2      | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1064     | 3183   | 57.39%  |
| NVMe | 624      | 1203   | 33.66%  |
| SAS  | 164      | 261    | 8.85%   |
| MMC  | 2        | 2      | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 760      | 1596   | 42.06%  |
| 0.51-1.0   | 574      | 969    | 31.77%  |
| 1.01-2.0   | 262      | 461    | 14.5%   |
| 3.01-4.0   | 91       | 149    | 5.04%   |
| 2.01-3.0   | 52       | 81     | 2.88%   |
| 4.01-10.0  | 51       | 114    | 2.82%   |
| 10.01-20.0 | 17       | 26     | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 257      | 19.14%  |
| 501-1000       | 237      | 17.65%  |
| 251-500        | 220      | 16.38%  |
| 101-250        | 199      | 14.82%  |
| 1001-2000      | 195      | 14.52%  |
| 2001-3000      | 93       | 6.92%   |
| 1-20           | 57       | 4.24%   |
| Unknown        | 44       | 3.28%   |
| 51-100         | 30       | 2.23%   |
| 21-50          | 11       | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 294      | 20.6%   |
| 21-50          | 227      | 15.91%  |
| 101-250        | 200      | 14.02%  |
| 251-500        | 152      | 10.65%  |
| 501-1000       | 144      | 10.09%  |
| 51-100         | 141      | 9.88%   |
| 1001-2000      | 108      | 7.57%   |
| More than 3000 | 63       | 4.41%   |
| 2001-3000      | 53       | 3.71%   |
| Unknown        | 44       | 3.08%   |
| 0              | 1        | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB                           | 9        | 12     | 2.33%   |
| Seagate ST1000DM003-9YN162 1TB                                | 7        | 7      | 1.81%   |
| Seagate ST3500413AS 500GB                                     | 6        | 7      | 1.55%   |
| Seagate ST31000528AS 1TB                                      | 6        | 6      | 1.55%   |
| Seagate ST1000DM003-1CH162 1TB                                | 6        | 10     | 1.55%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 5        | 5      | 1.3%    |
| WDC WD20EARS-00MVWB0 2TB                                      | 4        | 8      | 1.04%   |
| Toshiba DT01ACA100 1TB                                        | 4        | 7      | 1.04%   |
| Seagate ST3500312CS 500GB                                     | 4        | 6      | 1.04%   |
| Seagate ST31000524AS 1TB                                      | 4        | 5      | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB                                | 4        | 7      | 1.04%   |
| Seagate ST2000DM001-1ER164 2TB                                | 4        | 10     | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 4        | 4      | 1.04%   |
| Hitachi HDS721010CLA332 1TB                                   | 4        | 6      | 1.04%   |
| WDC WD30EFRX-68EUZN0 3TB                                      | 3        | 5      | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                               | 3        | 4      | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                                | 3        | 4      | 0.78%   |
| SanDisk SSD PLUS 1000GB                                       | 3        | 5      | 0.78%   |
| Samsung Electronics SSD 850 EVO 250GB                         | 3        | 4      | 0.78%   |
| Maxtor STM3250310AS 250GB                                     | 3        | 5      | 0.78%   |
| Kingston SA400S37480G 480GB SSD                               | 3        | 4      | 0.78%   |
| Hitachi HDS721050CLA662 500GB                                 | 3        | 4      | 0.78%   |
| ASMedia AS2115 8TB                                            | 3        | 4      | 0.78%   |
| WDC WDS500G1X0E-00AFY0 500GB                                  | 2        | 2      | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                              | 2        | 2      | 0.52%   |
| WDC WD6400AAKS-22A7B2 640GB                                   | 2        | 4      | 0.52%   |
| WDC WD5000AAKX-75U6AA0 500GB                                  | 2        | 3      | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB                                  | 2        | 2      | 0.52%   |
| WDC WD5000AAKX-603CA0 500GB                                   | 2        | 6      | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                                  | 2        | 2      | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB                                   | 2        | 3      | 0.52%   |
| WDC WD40EFRX-68N32N0 4TB                                      | 2        | 6      | 0.52%   |
| WDC WD3200AVJS-63B6A0 320GB                                   | 2        | 5      | 0.52%   |
| WDC WD3200AAJS-22L7A0 320GB                                   | 2        | 2      | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB                                      | 2        | 4      | 0.52%   |
| WDC WD20EARX-00PASB0 2TB                                      | 2        | 2      | 0.52%   |
| WDC WD2002FAEX-007BA0 2TB                                     | 2        | 3      | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                                      | 2        | 2      | 0.52%   |
| WDC WD10EZEX-00WN4A0 1TB                                      | 2        | 2      | 0.52%   |
| WDC WD10EARS-22Y5B1 1TB                                       | 2        | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 98       | 136    | 26.92%  |
| WDC                         | 97       | 158    | 26.65%  |
| Samsung Electronics         | 43       | 58     | 11.81%  |
| Hitachi                     | 25       | 34     | 6.87%   |
| Toshiba                     | 15       | 22     | 4.12%   |
| Kingston                    | 8        | 11     | 2.2%    |
| SanDisk                     | 7        | 14     | 1.92%   |
| Crucial                     | 7        | 11     | 1.92%   |
| Intel                       | 6        | 9      | 1.65%   |
| A-DATA Technology           | 6        | 9      | 1.65%   |
| Maxtor                      | 5        | 8      | 1.37%   |
| Hewlett-Packard             | 4        | 4      | 1.1%    |
| Corsair                     | 4        | 14     | 1.1%    |
| Transcend                   | 3        | 3      | 0.82%   |
| HGST                        | 3        | 10     | 0.82%   |
| China                       | 3        | 4      | 0.82%   |
| ASMedia                     | 3        | 4      | 0.82%   |
| SK hynix                    | 2        | 2      | 0.55%   |
| Silicon Motion              | 2        | 3      | 0.55%   |
| Inateck                     | 2        | 2      | 0.55%   |
| Fujitsu                     | 2        | 3      | 0.55%   |
| Drevo                       | 2        | 2      | 0.55%   |
| XPG                         | 1        | 1      | 0.27%   |
| USB3.0                      | 1        | 1      | 0.27%   |
| Super Talent                | 1        | 1      | 0.27%   |
| SPCC                        | 1        | 1      | 0.27%   |
| Realtek Semiconductor       | 1        | 1      | 0.27%   |
| Ramsta                      | 1        | 2      | 0.27%   |
| Patriot                     | 1        | 1      | 0.27%   |
| Micron/Crucial Technology   | 1        | 2      | 0.27%   |
| Micron Technology           | 1        | 4      | 0.27%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.27%   |
| KingSpec                    | 1        | 1      | 0.27%   |
| JMicron Technology          | 1        | 1      | 0.27%   |
| HS-SSD-C100                 | 1        | 1      | 0.27%   |
| HGST HTS                    | 1        | 1      | 0.27%   |
| CSD                         | 1        | 1      | 0.27%   |
| Colorful                    | 1        | 1      | 0.27%   |
| Unknown                     | 1        | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 98       | 136    | 36.7%   |
| WDC                 | 93       | 151    | 34.83%  |
| Hitachi             | 25       | 34     | 9.36%   |
| Toshiba             | 15       | 22     | 5.62%   |
| Samsung Electronics | 15       | 19     | 5.62%   |
| Maxtor              | 5        | 8      | 1.87%   |
| HGST                | 3        | 10     | 1.12%   |
| ASMedia             | 3        | 4      | 1.12%   |
| Inateck             | 2        | 2      | 0.75%   |
| Hewlett-Packard     | 2        | 2      | 0.75%   |
| Fujitsu             | 2        | 3      | 0.75%   |
| JMicron Technology  | 1        | 1      | 0.37%   |
| HGST HTS            | 1        | 1      | 0.37%   |
| CSD                 | 1        | 1      | 0.37%   |
| Unknown             | 1        | 1      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 236      | 395    | 70.87%  |
| SSD  | 76       | 116    | 22.82%  |
| NVMe | 21       | 32     | 6.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 2        | 2      | 20%     |
| WDC WD5000AAKX-001CA0 500GB                      | 1        | 1      | 10%     |
| Seagate ST91000430AS 1TB                         | 1        | 1      | 10%     |
| Seagate ST3500410AS 500GB                        | 1        | 1      | 10%     |
| Seagate ST32000641AS 2TB                         | 1        | 2      | 10%     |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1        | 1      | 10%     |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 10%     |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 6      | 44.44%  |
| Samsung Electronics | 4        | 4      | 44.44%  |
| WDC                 | 1        | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1077     | 3569   | 65.99%  |
| Malfunc  | 319      | 543    | 19.55%  |
| Detected | 227      | 526    | 13.91%  |
| Failed   | 9        | 11     | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 672      | 32.17%  |
| AMD                              | 543      | 25.99%  |
| Samsung Electronics              | 249      | 11.92%  |
| SanDisk                          | 103      | 4.93%   |
| Phison Electronics               | 92       | 4.4%    |
| ASMedia Technology               | 72       | 3.45%   |
| Kingston Technology Company      | 69       | 3.3%    |
| Micron/Crucial Technology        | 55       | 2.63%   |
| Silicon Motion                   | 39       | 1.87%   |
| Marvell Technology Group         | 29       | 1.39%   |
| ADATA Technology                 | 28       | 1.34%   |
| Realtek Semiconductor            | 20       | 0.96%   |
| Toshiba America Info Systems     | 15       | 0.72%   |
| SK hynix                         | 12       | 0.57%   |
| Seagate Technology               | 12       | 0.57%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.57%   |
| JMicron Technology               | 11       | 0.53%   |
| Nvidia                           | 9        | 0.43%   |
| Shenzhen Longsys Electronics     | 6        | 0.29%   |
| INNOGRIT                         | 6        | 0.29%   |
| Micron Technology                | 4        | 0.19%   |
| LSI Logic / Symbios Logic        | 4        | 0.19%   |
| Lite-On Technology               | 4        | 0.19%   |
| KIOXIA                           | 4        | 0.19%   |
| VIA Technologies                 | 3        | 0.14%   |
| Silicon Image                    | 2        | 0.1%    |
| Broadcom / LSI                   | 2        | 0.1%    |
| Biwin Storage Technology         | 2        | 0.1%    |
| Adaptec                          | 2        | 0.1%    |
| Union Memory (Shenzhen)          | 1        | 0.05%   |
| Transcend                        | 1        | 0.05%   |
| Solid State Storage Technology   | 1        | 0.05%   |
| Silicon Integrated Systems [SiS] | 1        | 0.05%   |
| Netac Technology                 | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |
| Enmotus                          | 1        | 0.05%   |
| Beijing Starblaze Technology     | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 315      | 12.81%  |
| AMD 400 Series Chipset SATA Controller                                                  | 152      | 6.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 138      | 5.61%   |
| AMD 500 Series Chipset SATA Controller                                                  | 103      | 4.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 84       | 3.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 70       | 2.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 70       | 2.85%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 68       | 2.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 66       | 2.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 55       | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 52       | 2.11%   |
| Phison E12 NVMe Controller                                                              | 46       | 1.87%   |
| Intel SATA Controller [RAID mode]                                                       | 45       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 39       | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 33       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 32       | 1.3%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 31       | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 30       | 1.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 30       | 1.22%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 30       | 1.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 25       | 1.02%   |
| AMD 600 Series Chipset SATA Controller                                                  | 25       | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 24       | 0.98%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 23       | 0.94%   |
| AMD FCH SATA Controller D                                                               | 23       | 0.94%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 22       | 0.89%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 22       | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 21       | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 20       | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20       | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18       | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18       | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                                  | 18       | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 17       | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16       | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 15       | 0.61%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 15       | 0.61%   |
| Intel SSD 660P Series                                                                   | 15       | 0.61%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 14       | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 14       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1093     | 56.81%  |
| NVMe | 625      | 32.48%  |
| IDE  | 120      | 6.24%   |
| RAID | 79       | 4.11%   |
| SAS  | 5        | 0.26%   |
| SCSI | 2        | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 662      | 54.31%  |
| AMD     | 556      | 45.61%  |
| Unknown | 1        | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 49       | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 30       | 2.45%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 28       | 2.28%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 27       | 2.2%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 26       | 2.12%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 25       | 2.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 22       | 1.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 21       | 1.71%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 21       | 1.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 19       | 1.55%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 18       | 1.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 17       | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 17       | 1.39%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 1.22%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 15       | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 14       | 1.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 14       | 1.14%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 13       | 1.06%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 13       | 1.06%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 12       | 0.98%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 12       | 0.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12       | 0.98%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 12       | 0.98%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 0.98%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 12       | 0.98%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 11       | 0.9%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 10       | 0.82%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 10       | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 0.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 10       | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 10       | 0.82%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 10       | 0.82%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 10       | 0.82%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 9        | 0.73%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 9        | 0.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 9        | 0.73%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 9        | 0.73%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 9        | 0.73%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 8        | 0.65%   |
| AMD FX-6300 Six-Core Processor              | 8        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 207      | 16.91%  |
| AMD Ryzen 5             | 194      | 15.85%  |
| Intel Core i7           | 191      | 15.6%   |
| AMD Ryzen 7             | 154      | 12.58%  |
| AMD Ryzen 9             | 91       | 7.43%   |
| Intel Core i3           | 59       | 4.82%   |
| Intel Xeon              | 54       | 4.41%   |
| Other                   | 48       | 3.92%   |
| AMD FX                  | 27       | 2.21%   |
| AMD Ryzen 3             | 26       | 2.12%   |
| Intel Core i9           | 25       | 2.04%   |
| Intel Pentium           | 19       | 1.55%   |
| Intel Celeron           | 16       | 1.31%   |
| Intel Atom              | 12       | 0.98%   |
| Intel Core 2 Duo        | 11       | 0.9%    |
| AMD Ryzen Threadripper  | 9        | 0.74%   |
| AMD A10                 | 8        | 0.65%   |
| AMD Phenom II X4        | 7        | 0.57%   |
| AMD Athlon II X2        | 6        | 0.49%   |
| Intel Pentium Dual-Core | 5        | 0.41%   |
| Intel Core 2 Quad       | 5        | 0.41%   |
| AMD Athlon              | 5        | 0.41%   |
| AMD A8                  | 5        | 0.41%   |
| AMD A6                  | 5        | 0.41%   |
| Intel Pentium Dual      | 4        | 0.33%   |
| AMD Phenom II X6        | 4        | 0.33%   |
| AMD Athlon 64 X2        | 4        | 0.33%   |
| AMD A4                  | 4        | 0.33%   |
| Intel Pentium Gold      | 2        | 0.16%   |
| Intel Genuine           | 2        | 0.16%   |
| Intel Core 2            | 2        | 0.16%   |
| AMD Ryzen 5 PRO         | 2        | 0.16%   |
| AMD Phenom              | 2        | 0.16%   |
| Intel Pentium 4         | 1        | 0.08%   |
| AMD Ryzen 7 PRO         | 1        | 0.08%   |
| AMD Ryzen 3 PRO         | 1        | 0.08%   |
| AMD E2                  | 1        | 0.08%   |
| AMD E1                  | 1        | 0.08%   |
| AMD Athlon X4           | 1        | 0.08%   |
| AMD Athlon II X4        | 1        | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 417      | 34.01%  |
| 6       | 288      | 23.49%  |
| 8       | 222      | 18.11%  |
| 2       | 131      | 10.69%  |
| 12      | 69       | 5.63%   |
| 16      | 41       | 3.34%   |
| 10      | 20       | 1.63%   |
| 3       | 12       | 0.98%   |
| 1       | 9        | 0.73%   |
| 24      | 8        | 0.65%   |
| 40      | 2        | 0.16%   |
| 20      | 2        | 0.16%   |
| 18      | 2        | 0.16%   |
| 32      | 1        | 0.08%   |
| 14      | 1        | 0.08%   |
| Unknown | 1        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1211     | 99.26%  |
| 2       | 8        | 0.66%   |
| Unknown | 1        | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 888      | 72.73%  |
| 1       | 332      | 27.19%  |
| Unknown | 1        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1214     | 99.59%  |
| Unknown        | 5        | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 436      | 33.64%  |
| 0x08701021 | 87       | 6.71%   |
| 0x306c3    | 55       | 4.24%   |
| 0x0800820d | 51       | 3.94%   |
| 0x306a9    | 49       | 3.78%   |
| 0x506e3    | 40       | 3.09%   |
| 0x0a201016 | 39       | 3.01%   |
| 0x906ea    | 38       | 2.93%   |
| 0x906e9    | 36       | 2.78%   |
| 0x08701013 | 26       | 2.01%   |
| 0x206a7    | 25       | 1.93%   |
| 0x0a201009 | 22       | 1.7%    |
| 0x0a50000c | 19       | 1.47%   |
| 0x0a20120a | 19       | 1.47%   |
| 0x0a50000d | 18       | 1.39%   |
| 0x08108109 | 17       | 1.31%   |
| 0x08101016 | 14       | 1.08%   |
| 0xa0655    | 13       | 1%      |
| 0x08701030 | 13       | 1%      |
| 0xa0653    | 12       | 0.93%   |
| 0x0a601203 | 11       | 0.85%   |
| 0x906ec    | 10       | 0.77%   |
| 0x506f1    | 10       | 0.77%   |
| 0x306f2    | 10       | 0.77%   |
| 0x1067a    | 10       | 0.77%   |
| 0x08001138 | 9        | 0.69%   |
| 0x08001137 | 9        | 0.69%   |
| 0x06000852 | 9        | 0.69%   |
| 0x90672    | 8        | 0.62%   |
| 0x06000822 | 8        | 0.62%   |
| 0x906ed    | 7        | 0.54%   |
| 0x0a601206 | 7        | 0.54%   |
| 0x906eb    | 6        | 0.46%   |
| 0x0a201205 | 6        | 0.46%   |
| 0x0a201025 | 6        | 0.46%   |
| 0x08108102 | 6        | 0.46%   |
| 0xa0671    | 5        | 0.39%   |
| 0x6fd      | 5        | 0.39%   |
| 0x106e5    | 5        | 0.39%   |
| 0x0810100b | 5        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 167      | 13.63%  |
| Zen 3            | 163      | 13.31%  |
| Zen 2            | 154      | 12.57%  |
| Haswell          | 115      | 9.39%   |
| Zen+             | 90       | 7.35%   |
| IvyBridge        | 86       | 7.02%   |
| Skylake          | 72       | 5.88%   |
| SandyBridge      | 46       | 3.76%   |
| CometLake        | 46       | 3.76%   |
| Zen              | 45       | 3.67%   |
| Alderlake Hybrid | 33       | 2.69%   |
| Unknown          | 33       | 2.69%   |
| Piledriver       | 31       | 2.53%   |
| Penryn           | 21       | 1.71%   |
| K10              | 21       | 1.71%   |
| Goldmont         | 15       | 1.22%   |
| Icelake          | 13       | 1.06%   |
| Nehalem          | 12       | 0.98%   |
| Steamroller      | 10       | 0.82%   |
| Core             | 9        | 0.73%   |
| Westmere         | 7        | 0.57%   |
| K8 Hammer        | 6        | 0.49%   |
| Silvermont       | 5        | 0.41%   |
| Broadwell        | 5        | 0.41%   |
| Goldmont plus    | 4        | 0.33%   |
| Excavator        | 3        | 0.24%   |
| Bulldozer        | 3        | 0.24%   |
| Tremont          | 2        | 0.16%   |
| K10 Llano        | 2        | 0.16%   |
| Jaguar           | 2        | 0.16%   |
| Gracemont        | 2        | 0.16%   |
| NetBurst         | 1        | 0.08%   |
| Bobcat           | 1        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 564      | 42.63%  |
| AMD               | 447      | 33.79%  |
| Intel             | 296      | 22.37%  |
| ASPEED Technology | 15       | 1.13%   |
| ATI Technologies  | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 94       | 6.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 54       | 3.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 42       | 3.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 36       | 2.62%   |
| Intel HD Graphics 530                                                       | 35       | 2.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 33       | 2.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 32       | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 30       | 2.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 27       | 1.96%   |
| Intel HD Graphics 630                                                       | 25       | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 25       | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 24       | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 23       | 1.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 22       | 1.6%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 21       | 1.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 20       | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 20       | 1.45%   |
| AMD Raphael                                                                 | 20       | 1.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 20       | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 19       | 1.38%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 19       | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 18       | 1.31%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 16       | 1.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 16       | 1.16%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 16       | 1.16%   |
| ASPEED Technology ASPEED Graphics Family                                    | 15       | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 15       | 1.09%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 14       | 1.02%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 14       | 1.02%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 14       | 1.02%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 13       | 0.95%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 13       | 0.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 13       | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 13       | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 13       | 0.95%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 13       | 0.95%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 12       | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 11       | 0.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 11       | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 504      | 40.48%  |
| 1 x AMD        | 397      | 31.89%  |
| 1 x Intel      | 216      | 17.35%  |
| Intel + Nvidia | 46       | 3.69%   |
| 2 x AMD        | 31       | 2.49%   |
| AMD + Nvidia   | 13       | 1.04%   |
| 1 x ASPEED     | 12       | 0.96%   |
| Intel + AMD    | 10       | 0.8%    |
| 2 x Nvidia     | 7        | 0.56%   |
| Other          | 3        | 0.24%   |
| 2 x Intel      | 3        | 0.24%   |
| AMD + ASPEED   | 3        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 732      | 58.98%  |
| Proprietary | 463      | 37.31%  |
| Unknown     | 46       | 3.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 356      | 28.23%  |
| 7.01-8.0   | 268      | 21.25%  |
| 3.01-4.0   | 137      | 10.86%  |
| 1.01-2.0   | 131      | 10.39%  |
| 8.01-16.0  | 123      | 9.75%   |
| 5.01-6.0   | 87       | 6.9%    |
| 0.01-0.5   | 60       | 4.76%   |
| 0.51-1.0   | 56       | 4.44%   |
| 16.01-24.0 | 21       | 1.67%   |
| 2.01-3.0   | 19       | 1.51%   |
| 4.01-5.0   | 3        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 231      | 15.81%  |
| Goldstar             | 180      | 12.32%  |
| Dell                 | 167      | 11.43%  |
| Acer                 | 101      | 6.91%   |
| AOC                  | 88       | 6.02%   |
| Ancor Communications | 79       | 5.41%   |
| Hewlett-Packard      | 73       | 5%      |
| BenQ                 | 73       | 5%      |
| Philips              | 48       | 3.29%   |
| ASUSTek Computer     | 41       | 2.81%   |
| ViewSonic            | 31       | 2.12%   |
| Unknown              | 30       | 2.05%   |
| MSI                  | 24       | 1.64%   |
| Iiyama               | 22       | 1.51%   |
| Sony                 | 21       | 1.44%   |
| Lenovo               | 21       | 1.44%   |
| Gigabyte Technology  | 19       | 1.3%    |
| Vizio                | 15       | 1.03%   |
| LG Electronics       | 15       | 1.03%   |
| Eizo                 | 14       | 0.96%   |
| Sceptre Tech         | 13       | 0.89%   |
| Toshiba              | 11       | 0.75%   |
| Vestel Elektronik    | 7        | 0.48%   |
| HannStar             | 6        | 0.41%   |
| Unknown              | 6        | 0.41%   |
| Panasonic            | 4        | 0.27%   |
| MiTAC                | 4        | 0.27%   |
| Microstep            | 4        | 0.27%   |
| Denver               | 4        | 0.27%   |
| VIE                  | 3        | 0.21%   |
| Unknown (XXX)        | 3        | 0.21%   |
| Sharp                | 3        | 0.21%   |
| Insignia             | 3        | 0.21%   |
| Idek Iiyama          | 3        | 0.21%   |
| HKC                  | 3        | 0.21%   |
| Wacom                | 2        | 0.14%   |
| VIZ                  | 2        | 0.14%   |
| UTV                  | 2        | 0.14%   |
| SKY                  | 2        | 0.14%   |
| SGT                  | 2        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 21       | 1.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 15       | 0.95%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 9        | 0.57%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9        | 0.57%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9        | 0.57%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 7        | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7        | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 7        | 0.44%   |
| AOC 27G2WG3- AOC2702 1920x1080 600x340mm 27.2-inch                    | 7        | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6        | 0.38%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 6        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6        | 0.38%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6        | 0.38%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.38%   |
| Unknown                                                               | 6        | 0.38%   |
| Toshiba TV TSB0206 1920x1080                                          | 5        | 0.32%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 5        | 0.32%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 5        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5        | 0.32%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 4        | 0.25%   |
| MSI Optix MAG24C MSI1462 1920x1080 521x293mm 23.5-inch                | 4        | 0.25%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 4        | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.25%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 4        | 0.25%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 4        | 0.25%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 4        | 0.25%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 4        | 0.25%   |
| AOC Q2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 4        | 0.25%   |
| AOC 24V2W1G5 AOC2402 1920x1080 530x300mm 24.0-inch                    | 4        | 0.25%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 4        | 0.25%   |
| Ancor Communications ASUS VX279 ACI27E4 1920x1080 598x336mm 27.0-inch | 4        | 0.25%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 620x340mm 27.8-inch | 4        | 0.25%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 4        | 0.25%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 3        | 0.19%   |
| Sony TV SNYE903 1920x1080                                             | 3        | 0.19%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 3        | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.19%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3        | 0.19%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 647      | 46.12%  |
| 2560x1440 (QHD)    | 185      | 13.19%  |
| 3840x2160 (4K)     | 166      | 11.83%  |
| 2560x1080          | 48       | 3.42%   |
| 1680x1050 (WSXGA+) | 46       | 3.28%   |
| 1366x768 (WXGA)    | 37       | 2.64%   |
| 3440x1440          | 36       | 2.57%   |
| 1280x1024 (SXGA)   | 36       | 2.57%   |
| 1440x900 (WXGA+)   | 30       | 2.14%   |
| 1920x1200 (WUXGA)  | 27       | 1.92%   |
| Unknown            | 25       | 1.78%   |
| 1600x900 (HD+)     | 23       | 1.64%   |
| 2288x1287          | 22       | 1.57%   |
| 3840x1080          | 20       | 1.43%   |
| 1360x768           | 13       | 0.93%   |
| 1920x540           | 8        | 0.57%   |
| 1600x1200          | 8        | 0.57%   |
| 3840x1600          | 5        | 0.36%   |
| 5760x2160          | 2        | 0.14%   |
| 2944x1080          | 2        | 0.14%   |
| 2048x1152          | 2        | 0.14%   |
| 6400x1440          | 1        | 0.07%   |
| 5520x1080          | 1        | 0.07%   |
| 5360x1440          | 1        | 0.07%   |
| 5120x1440          | 1        | 0.07%   |
| 480x1920           | 1        | 0.07%   |
| 4480x1440          | 1        | 0.07%   |
| 4480x1080          | 1        | 0.07%   |
| 3840x2524          | 1        | 0.07%   |
| 3840x1200          | 1        | 0.07%   |
| 3520x1080          | 1        | 0.07%   |
| 3360x1080          | 1        | 0.07%   |
| 3286x1080          | 1        | 0.07%   |
| 3280x1080          | 1        | 0.07%   |
| 1400x1050          | 1        | 0.07%   |
| 1024x768 (XGA)     | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 266      | 18.21%  |
| 24      | 231      | 15.81%  |
| 21      | 152      | 10.4%   |
| 23      | 142      | 9.72%   |
| 31      | 114      | 7.8%    |
| Unknown | 84       | 5.75%   |
| 34      | 66       | 4.52%   |
| 19      | 46       | 3.15%   |
| 18      | 36       | 2.46%   |
| 22      | 32       | 2.19%   |
| 20      | 31       | 2.12%   |
| 84      | 25       | 1.71%   |
| 40      | 25       | 1.71%   |
| 17      | 23       | 1.57%   |
| 142     | 21       | 1.44%   |
| 72      | 19       | 1.3%    |
| 32      | 17       | 1.16%   |
| 54      | 16       | 1.1%    |
| 28      | 14       | 0.96%   |
| 25      | 12       | 0.82%   |
| 26      | 9        | 0.62%   |
| 49      | 8        | 0.55%   |
| 15      | 8        | 0.55%   |
| 42      | 7        | 0.48%   |
| 74      | 5        | 0.34%   |
| 65      | 5        | 0.34%   |
| 52      | 5        | 0.34%   |
| 48      | 5        | 0.34%   |
| 29      | 5        | 0.34%   |
| 46      | 4        | 0.27%   |
| 39      | 4        | 0.27%   |
| 37      | 4        | 0.27%   |
| 60      | 2        | 0.14%   |
| 41      | 2        | 0.14%   |
| 36      | 2        | 0.14%   |
| 35      | 2        | 0.14%   |
| 33      | 2        | 0.14%   |
| 14      | 2        | 0.14%   |
| 75      | 1        | 0.07%   |
| 69      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 566      | 40.84%  |
| 401-500        | 266      | 19.19%  |
| 601-700        | 165      | 11.9%   |
| 701-800        | 85       | 6.13%   |
| Unknown        | 84       | 6.06%   |
| 1501-2000      | 50       | 3.61%   |
| 1001-1500      | 47       | 3.39%   |
| 801-900        | 38       | 2.74%   |
| 301-350        | 31       | 2.24%   |
| More than 2000 | 21       | 1.52%   |
| 351-400        | 19       | 1.37%   |
| 901-1000       | 10       | 0.72%   |
| 201-300        | 4        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 916      | 71.34%  |
| 16/10   | 118      | 9.19%   |
| 21/9    | 88       | 6.85%   |
| Unknown | 71       | 5.53%   |
| 5/4     | 36       | 2.8%    |
| 1.00    | 21       | 1.64%   |
| 4/3     | 13       | 1.01%   |
| 32/9    | 11       | 0.86%   |
| 3/2     | 4        | 0.31%   |
| 6/5     | 3        | 0.23%   |
| 2.00    | 1        | 0.08%   |
| 0.80    | 1        | 0.08%   |
| 0.25    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 450      | 31.78%  |
| 301-350        | 273      | 19.28%  |
| 351-500        | 202      | 14.27%  |
| 151-200        | 103      | 7.27%   |
| More than 1000 | 98       | 6.92%   |
| 251-300        | 84       | 5.93%   |
| Unknown        | 84       | 5.93%   |
| 501-1000       | 59       | 4.17%   |
| 141-150        | 50       | 3.53%   |
| 101-110        | 8        | 0.56%   |
| 131-140        | 2        | 0.14%   |
| 81-90          | 1        | 0.07%   |
| 71-80          | 1        | 0.07%   |
| 121-130        | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 764      | 58.1%   |
| 101-120 | 301      | 22.89%  |
| Unknown | 84       | 6.39%   |
| 1-50    | 75       | 5.7%    |
| 121-160 | 71       | 5.4%    |
| 161-240 | 20       | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 837      | 66.06%  |
| 2     | 328      | 25.89%  |
| 0     | 53       | 4.18%   |
| 3     | 44       | 3.47%   |
| 4     | 5        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 769      | 44.53%  |
| Intel                                  | 622      | 36.02%  |
| Qualcomm Atheros                       | 81       | 4.69%   |
| Broadcom                               | 40       | 2.32%   |
| MediaTek                               | 34       | 1.97%   |
| Ralink Technology                      | 31       | 1.8%    |
| TP-Link                                | 27       | 1.56%   |
| Aquantia                               | 11       | 0.64%   |
| Microsoft                              | 9        | 0.52%   |
| Nvidia                                 | 8        | 0.46%   |
| Broadcom Limited                       | 8        | 0.46%   |
| D-Link System                          | 7        | 0.41%   |
| Samsung Electronics                    | 6        | 0.35%   |
| Qualcomm Atheros Communications        | 4        | 0.23%   |
| Qualcomm                               | 4        | 0.23%   |
| NetGear                                | 4        | 0.23%   |
| Marvell Technology Group               | 4        | 0.23%   |
| D-Link                                 | 4        | 0.23%   |
| ASUSTek Computer                       | 4        | 0.23%   |
| ASIX Electronics                       | 4        | 0.23%   |
| Ralink                                 | 3        | 0.17%   |
| Huawei Technologies                    | 3        | 0.17%   |
| Edimax Technology                      | 3        | 0.17%   |
| Tenda                                  | 2        | 0.12%   |
| T & A Mobile Phones                    | 2        | 0.12%   |
| Oculus VR                              | 2        | 0.12%   |
| Motorola PCS                           | 2        | 0.12%   |
| Lenovo                                 | 2        | 0.12%   |
| Insyde Software                        | 2        | 0.12%   |
| Emulex                                 | 2        | 0.12%   |
| DisplayLink                            | 2        | 0.12%   |
| Xiaomi                                 | 1        | 0.06%   |
| VIA Technologies                       | 1        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.06%   |
| Solarflare Communications              | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.06%   |
| Seeed Technology                       | 1        | 0.06%   |
| QLogic                                 | 1        | 0.06%   |
| Ovislink                               | 1        | 0.06%   |
| OPPO Electronics                       | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 583      | 28.9%   |
| Intel I211 Gigabit Network Connection                                  | 118      | 5.85%   |
| Intel Wi-Fi 6 AX200                                                    | 114      | 5.65%   |
| Realtek RTL8125 2.5GbE Controller                                      | 103      | 5.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 64       | 3.17%   |
| Intel Ethernet Controller I225-V                                       | 59       | 2.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 40       | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39       | 1.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 38       | 1.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 29       | 1.44%   |
| Intel Ethernet Connection I217-LM                                      | 28       | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24       | 1.19%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 23       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 19       | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 18       | 0.89%   |
| Intel Ethernet Connection I217-V                                       | 18       | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18       | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 16       | 0.79%   |
| Intel 82579V Gigabit Network Connection                                | 16       | 0.79%   |
| Realtek 802.11ac NIC                                                   | 15       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                        | 15       | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 14       | 0.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 14       | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12       | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 12       | 0.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12       | 0.59%   |
| Intel I210 Gigabit Network Connection                                  | 12       | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 11       | 0.55%   |
| Intel Wireless 7265                                                    | 11       | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 10       | 0.5%    |
| Intel Wireless 7260                                                    | 10       | 0.5%    |
| Intel Ethernet Connection X553 1GbE                                    | 10       | 0.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 10       | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 9        | 0.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                   | 9        | 0.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 8        | 0.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8        | 0.4%    |
| Intel Wireless 8265 / 8275                                             | 8        | 0.4%    |
| Intel Wireless 8260                                                    | 8        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 302      | 48.09%  |
| Realtek Semiconductor                 | 121      | 19.27%  |
| Qualcomm Atheros                      | 43       | 6.85%   |
| Ralink Technology                     | 31       | 4.94%   |
| MediaTek                              | 30       | 4.78%   |
| Broadcom                              | 29       | 4.62%   |
| TP-Link                               | 27       | 4.3%    |
| Microsoft                             | 9        | 1.43%   |
| Qualcomm Atheros Communications       | 4        | 0.64%   |
| NetGear                               | 4        | 0.64%   |
| D-Link System                         | 4        | 0.64%   |
| D-Link                                | 4        | 0.64%   |
| ASUSTek Computer                      | 4        | 0.64%   |
| Ralink                                | 3        | 0.48%   |
| Edimax Technology                     | 3        | 0.48%   |
| Broadcom Limited                      | 3        | 0.48%   |
| Tenda                                 | 2        | 0.32%   |
| Xiaomi                                | 1        | 0.16%   |
| Ovislink                              | 1        | 0.16%   |
| IMC Networks                          | 1        | 0.16%   |
| CyberTAN Technology                   | 1        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 114      | 17.92%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 38       | 5.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 29       | 4.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 23       | 3.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 19       | 2.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 18       | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 16       | 2.52%   |
| Realtek 802.11ac NIC                                          | 15       | 2.36%   |
| Ralink MT7601U Wireless Adapter                               | 15       | 2.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 14       | 2.2%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 14       | 2.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 12       | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 11       | 1.73%   |
| Intel Wireless 7265                                           | 11       | 1.73%   |
| Intel Wireless 7260                                           | 10       | 1.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 10       | 1.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 9        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 9        | 1.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 8        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8        | 1.26%   |
| Intel Wireless 8265 / 8275                                    | 8        | 1.26%   |
| Intel Wireless 8260                                           | 8        | 1.26%   |
| Intel Wireless 3165                                           | 8        | 1.26%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 7        | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 7        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                | 7        | 1.1%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 6        | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 6        | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 5        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 5        | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 5        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 5        | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 5        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 5        | 0.79%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter  | 5        | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 5        | 0.79%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 4        | 0.63%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 4        | 0.63%   |
| Ralink RT5370 Wireless Adapter                                | 4        | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 723      | 54.81%  |
| Intel                                  | 471      | 35.71%  |
| Qualcomm Atheros                       | 42       | 3.18%   |
| Broadcom                               | 13       | 0.99%   |
| Aquantia                               | 11       | 0.83%   |
| Nvidia                                 | 8        | 0.61%   |
| Samsung Electronics                    | 6        | 0.45%   |
| Broadcom Limited                       | 5        | 0.38%   |
| Qualcomm                               | 4        | 0.3%    |
| Marvell Technology Group               | 4        | 0.3%    |
| ASIX Electronics                       | 4        | 0.3%    |
| Huawei Technologies                    | 3        | 0.23%   |
| D-Link System                          | 3        | 0.23%   |
| T & A Mobile Phones                    | 2        | 0.15%   |
| Lenovo                                 | 2        | 0.15%   |
| Insyde Software                        | 2        | 0.15%   |
| Emulex                                 | 2        | 0.15%   |
| DisplayLink                            | 2        | 0.15%   |
| VIA Technologies                       | 1        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.08%   |
| Solarflare Communications              | 1        | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.08%   |
| QLogic                                 | 1        | 0.08%   |
| OPPO Electronics                       | 1        | 0.08%   |
| Motorola PCS                           | 1        | 0.08%   |
| Mellanox Technologies                  | 1        | 0.08%   |
| MediaTek                               | 1        | 0.08%   |
| ICS Advent                             | 1        | 0.08%   |
| HTC (High Tech Computer)               | 1        | 0.08%   |
| 3Com                                   | 1        | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 583      | 42.59%  |
| Intel I211 Gigabit Network Connection                                             | 118      | 8.62%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 103      | 7.52%   |
| Intel Ethernet Connection (2) I219-V                                              | 64       | 4.67%   |
| Intel Ethernet Controller I225-V                                                  | 59       | 4.31%   |
| Intel Ethernet Connection (7) I219-V                                              | 40       | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 39       | 2.85%   |
| Intel Ethernet Connection I217-LM                                                 | 28       | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 24       | 1.75%   |
| Intel Ethernet Connection I217-V                                                  | 18       | 1.31%   |
| Intel Ethernet Connection (2) I219-LM                                             | 18       | 1.31%   |
| Intel 82579V Gigabit Network Connection                                           | 16       | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 12       | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 12       | 0.88%   |
| Intel I210 Gigabit Network Connection                                             | 12       | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 10       | 0.73%   |
| Intel Ethernet Connection X553 1GbE                                               | 10       | 0.73%   |
| Intel Ethernet Connection (2) I218-V                                              | 9        | 0.66%   |
| Intel Ethernet Connection (12) I219-V                                             | 7        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 5        | 0.37%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 5        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                         | 5        | 0.37%   |
| Nvidia MCP61 Ethernet                                                             | 5        | 0.37%   |
| Intel Ethernet Controller I226-V                                                  | 5        | 0.37%   |
| Intel 82574L Gigabit Network Connection                                           | 5        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 5        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                            | 4        | 0.29%   |
| Realtek Killer E2600 GbE Controller                                               | 4        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                         | 4        | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 4        | 0.29%   |
| Intel Ethernet Controller X550                                                    | 4        | 0.29%   |
| Intel Ethernet Connection (7) I219-LM                                             | 4        | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                                             | 4        | 0.29%   |
| Intel Ethernet Connection (14) I219-V                                             | 4        | 0.29%   |
| Intel 82576 Gigabit Network Connection                                            | 4        | 0.29%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 4        | 0.29%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 4        | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 3        | 0.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 3        | 0.22%   |
| Intel Ethernet Connection (17) I219-V                                             | 3        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1214     | 66.63%  |
| WiFi     | 596      | 32.71%  |
| Modem    | 8        | 0.44%   |
| Unknown  | 4        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 976      | 76.91%  |
| WiFi     | 293      | 23.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 680      | 55.28%  |
| 2     | 456      | 37.07%  |
| 3     | 67       | 5.45%   |
| 4     | 19       | 1.54%   |
| 5     | 3        | 0.24%   |
| 0     | 3        | 0.24%   |
| 9     | 1        | 0.08%   |
| 6     | 1        | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 914      | 72.77%  |
| Yes  | 342      | 27.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 292      | 48.03%  |
| Cambridge Silicon Radio         | 107      | 17.6%   |
| Realtek Semiconductor           | 46       | 7.57%   |
| ASUSTek Computer                | 43       | 7.07%   |
| MediaTek                        | 24       | 3.95%   |
| Broadcom                        | 18       | 2.96%   |
| TP-Link                         | 17       | 2.8%    |
| Qualcomm Atheros Communications | 15       | 2.47%   |
| IMC Networks                    | 12       | 1.97%   |
| Apple                           | 10       | 1.64%   |
| Foxconn / Hon Hai               | 5        | 0.82%   |
| Belkin Components               | 4        | 0.66%   |
| Edimax Technology               | 3        | 0.49%   |
| Realtek                         | 2        | 0.33%   |
| Lite-On Technology              | 2        | 0.33%   |
| HTC (High Tech Computer)        | 2        | 0.33%   |
| SINO WEALTH                     | 1        | 0.16%   |
| Integrated System Solution      | 1        | 0.16%   |
| Dynex                           | 1        | 0.16%   |
| Creative Technology             | 1        | 0.16%   |
| Actions                         | 1        | 0.16%   |
| Unknown                         | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 111      | 18.2%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 107      | 17.54%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 38       | 6.23%   |
| Realtek Bluetooth Radio                                              | 33       | 5.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 30       | 4.92%   |
| Intel Bluetooth wireless interface                                   | 28       | 4.59%   |
| MediaTek Wireless_Device                                             | 24       | 3.93%   |
| Intel AX210 Bluetooth                                                | 21       | 3.44%   |
| Intel AX201 Bluetooth                                                | 20       | 3.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 19       | 3.11%   |
| TP-Link UB500 Adapter                                                | 17       | 2.79%   |
| Intel Bluetooth Device                                               | 16       | 2.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 15       | 2.46%   |
| ASUS ASUS USB-BT500                                                  | 15       | 2.46%   |
| Qualcomm Atheros  Bluetooth Device                                   | 11       | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 11       | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 1.64%   |
| Intel AX211 Bluetooth                                                | 6        | 0.98%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                                    | 5        | 0.82%   |
| Apple Bluetooth Host Controller                                      | 5        | 0.82%   |
| IMC Networks Wireless_Device                                         | 4        | 0.66%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.66%   |
| ASUS BCM20702A0                                                      | 4        | 0.66%   |
| Edimax Edimax Bluetooth Adapter                                      | 3        | 0.49%   |
| ASUS Bluetooth Radio                                                 | 3        | 0.49%   |
| ASUS Bluetooth Adapter                                               | 3        | 0.49%   |
| Apple Bluetooth USB Host Controller                                  | 3        | 0.49%   |
| Realtek Bluetooth Radio                                              | 2        | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 0.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 0.33%   |
| Broadcom HP Portable Bumble Bee                                      | 2        | 0.33%   |
| Broadcom BCM2045 Bluetooth                                           | 2        | 0.33%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 0.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 2        | 0.33%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 1        | 0.16%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.16%   |
| Realtek Bluetooth 5.3 Radio                                          | 1        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 665      | 28.06%  |
| Intel                                | 636      | 26.84%  |
| Nvidia                               | 556      | 23.46%  |
| C-Media Electronics                  | 78       | 3.29%   |
| Logitech                             | 47       | 1.98%   |
| Texas Instruments                    | 30       | 1.27%   |
| Kingston Technology                  | 26       | 1.1%    |
| Razer USA                            | 23       | 0.97%   |
| JMTek                                | 23       | 0.97%   |
| Focusrite-Novation                   | 19       | 0.8%    |
| Creative Technology                  | 15       | 0.63%   |
| SteelSeries ApS                      | 14       | 0.59%   |
| Creative Labs                        | 14       | 0.59%   |
| Corsair                              | 14       | 0.59%   |
| ASUSTek Computer                     | 14       | 0.59%   |
| Generalplus Technology               | 10       | 0.42%   |
| DSEA A/S                             | 9        | 0.38%   |
| RODE Microphones                     | 8        | 0.34%   |
| Realtek Semiconductor                | 8        | 0.34%   |
| SAVITECH                             | 6        | 0.25%   |
| Blue Microphones                     | 6        | 0.25%   |
| BEHRINGER International              | 6        | 0.25%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.21%   |
| Samson Technologies                  | 5        | 0.21%   |
| PreSonus Audio Electronics           | 5        | 0.21%   |
| Audio-Technica                       | 5        | 0.21%   |
| Astro Gaming                         | 5        | 0.21%   |
| Yamaha                               | 4        | 0.17%   |
| XMOS                                 | 4        | 0.17%   |
| Sony                                 | 4        | 0.17%   |
| M-Audio                              | 4        | 0.17%   |
| Hewlett-Packard                      | 4        | 0.17%   |
| GN Netcom                            | 4        | 0.17%   |
| ASRock                               | 4        | 0.17%   |
| Plantronics                          | 3        | 0.13%   |
| Native Instruments                   | 3        | 0.13%   |
| Giga-Byte Technology                 | 3        | 0.13%   |
| FiiO Electronics Technology          | 3        | 0.13%   |
| FIFINE Microphones                   | 3        | 0.13%   |
| BR25                                 | 3        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 250      | 8.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 130      | 4.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 98       | 3.5%    |
| Intel 200 Series PCH HD Audio                                              | 85       | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 81       | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 80       | 2.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 78       | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 73       | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 70       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 61       | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 59       | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 59       | 2.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 54       | 1.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 52       | 1.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 50       | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 48       | 1.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 46       | 1.64%   |
| AMD Navi 10 HDMI Audio                                                     | 44       | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 42       | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 39       | 1.39%   |
| Nvidia TU106 High Definition Audio Controller                              | 38       | 1.36%   |
| Nvidia TU104 HD Audio Controller                                           | 36       | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34       | 1.21%   |
| Nvidia GA102 High Definition Audio Controller                              | 28       | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 26       | 0.93%   |
| Intel Alder Lake-S HD Audio Controller                                     | 25       | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 25       | 0.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 24       | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 22       | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                         | 22       | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 22       | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 21       | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 21       | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 21       | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 21       | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                      | 20       | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 20       | 0.71%   |
| AMD FCH Azalia Controller                                                  | 20       | 0.71%   |
| JMTek USB PnP Audio Device                                                 | 19       | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                | 18       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 261      | 19.57%  |
| Kingston                     | 200      | 14.99%  |
| G.Skill                      | 171      | 12.82%  |
| Crucial                      | 126      | 9.45%   |
| Samsung Electronics          | 109      | 8.17%   |
| SK hynix                     | 103      | 7.72%   |
| Unknown                      | 89       | 6.67%   |
| Micron Technology            | 53       | 3.97%   |
| A-DATA Technology            | 41       | 3.07%   |
| Team                         | 37       | 2.77%   |
| Patriot                      | 14       | 1.05%   |
| Unknown                      | 13       | 0.97%   |
| Ramaxel Technology           | 12       | 0.9%    |
| Nanya Technology             | 10       | 0.75%   |
| Unknown (ABCD)               | 5        | 0.37%   |
| Silicon Power                | 5        | 0.37%   |
| PNY                          | 4        | 0.3%    |
| Patriot Memory (PDP Systems) | 4        | 0.3%    |
| Neo Forza                    | 4        | 0.3%    |
| Kingmax                      | 4        | 0.3%    |
| GOODRAM                      | 4        | 0.3%    |
| Elpida                       | 4        | 0.3%    |
| Apacer                       | 4        | 0.3%    |
| Transcend                    | 3        | 0.22%   |
| Asgard                       | 3        | 0.22%   |
| Unifosa                      | 2        | 0.15%   |
| Timetec                      | 2        | 0.15%   |
| Sesame                       | 2        | 0.15%   |
| Lexar                        | 2        | 0.15%   |
| Goldkey                      | 2        | 0.15%   |
| Golden Empire                | 2        | 0.15%   |
| GeIL                         | 2        | 0.15%   |
| Avant                        | 2        | 0.15%   |
| AMD                          | 2        | 0.15%   |
| V-Color                      | 1        | 0.07%   |
| Unknown (AB)                 | 1        | 0.07%   |
| Unknown (8AF1)               | 1        | 0.07%   |
| Unknown (89F7)               | 1        | 0.07%   |
| Unknown (0x0DD5)             | 1        | 0.07%   |
| Unknown (0B38)               | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 28       | 1.92%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 18       | 1.23%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s       | 17       | 1.16%   |
| Unknown                                                      | 13       | 0.89%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 11       | 0.75%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s     | 10       | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 10       | 0.68%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 10       | 0.68%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 10       | 0.68%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s        | 10       | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s          | 9        | 0.62%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 9        | 0.62%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 9        | 0.62%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 9        | 0.62%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 9        | 0.62%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 8        | 0.55%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 7        | 0.48%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 7        | 0.48%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s         | 7        | 0.48%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 7        | 0.48%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 7        | 0.48%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 7        | 0.48%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 7        | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 6        | 0.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 6        | 0.41%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s        | 6        | 0.41%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s         | 6        | 0.41%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s       | 6        | 0.41%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 6        | 0.41%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                  | 6        | 0.41%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                  | 6        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 5        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 5        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 5        | 0.34%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s          | 5        | 0.34%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 5        | 0.34%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 5        | 0.34%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s            | 5        | 0.34%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s       | 5        | 0.34%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s        | 5        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 756      | 64.84%  |
| DDR3    | 278      | 23.84%  |
| DDR5    | 46       | 3.95%   |
| Unknown | 35       | 3%      |
| SDRAM   | 20       | 1.72%   |
| DDR2    | 18       | 1.54%   |
| LPDDR4  | 5        | 0.43%   |
| DRAM    | 4        | 0.34%   |
| DDR     | 3        | 0.26%   |
| LPDDR5  | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1084     | 94.1%   |
| SODIMM       | 64       | 5.56%   |
| RIMM         | 3        | 0.26%   |
| Row Of Chips | 1        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 551      | 43.35%  |
| 16384 | 326      | 25.65%  |
| 4096  | 224      | 17.62%  |
| 32768 | 83       | 6.53%   |
| 2048  | 69       | 5.43%   |
| 1024  | 11       | 0.87%   |
| 49152 | 4        | 0.31%   |
| 512   | 2        | 0.16%   |
| 16    | 1        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 194      | 14.63%  |
| 1600    | 169      | 12.75%  |
| 3600    | 145      | 10.94%  |
| 2400    | 100      | 7.54%   |
| 1333    | 85       | 6.41%   |
| 2667    | 82       | 6.18%   |
| 2133    | 50       | 3.77%   |
| 3733    | 48       | 3.62%   |
| 3800    | 37       | 2.79%   |
| 3000    | 33       | 2.49%   |
| 3400    | 30       | 2.26%   |
| 2666    | 22       | 1.66%   |
| 1867    | 21       | 1.58%   |
| 1866    | 21       | 1.58%   |
| 1800    | 21       | 1.58%   |
| 3866    | 20       | 1.51%   |
| 800     | 18       | 1.36%   |
| 3666    | 15       | 1.13%   |
| 4800    | 14       | 1.06%   |
| 3466    | 14       | 1.06%   |
| 2933    | 14       | 1.06%   |
| 2800    | 14       | 1.06%   |
| 6000    | 13       | 0.98%   |
| 667     | 11       | 0.83%   |
| 3534    | 9        | 0.68%   |
| 5200    | 8        | 0.6%    |
| 2000    | 8        | 0.6%    |
| Unknown | 8        | 0.6%    |
| 3334    | 7        | 0.53%   |
| 3266    | 7        | 0.53%   |
| 2465    | 7        | 0.53%   |
| 1648    | 7        | 0.53%   |
| 4000    | 6        | 0.45%   |
| 3066    | 6        | 0.45%   |
| 1066    | 5        | 0.38%   |
| 6400    | 3        | 0.23%   |
| 5800    | 3        | 0.23%   |
| 5600    | 3        | 0.23%   |
| 2733    | 3        | 0.23%   |
| 2048    | 3        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 21       | 40.38%  |
| Brother Industries    | 19       | 36.54%  |
| Seiko Epson           | 3        | 5.77%   |
| Samsung Electronics   | 2        | 3.85%   |
| Ricoh                 | 1        | 1.92%   |
| Prolific Technology   | 1        | 1.92%   |
| Lexmark International | 1        | 1.92%   |
| Kyocera               | 1        | 1.92%   |
| Gprinter              | 1        | 1.92%   |
| Dymo-CoStar           | 1        | 1.92%   |
| Canon                 | 1        | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP DeskJet F4100 Printer series        | 2        | 3.77%   |
| HP DeskJet 2700 series                 | 2        | 3.77%   |
| HP DeskJet 2600 series                 | 2        | 3.77%   |
| Brother Printer                        | 2        | 3.77%   |
| Brother MFC-J6545DW                    | 2        | 3.77%   |
| Seiko Epson XP-240 Series              | 1        | 1.89%   |
| Seiko Epson XP-2100 Series             | 1        | 1.89%   |
| Seiko Epson ET-2710 Series             | 1        | 1.89%   |
| Samsung SCX-3400 Series                | 1        | 1.89%   |
| Samsung SCX-3200 Series                | 1        | 1.89%   |
| Ricoh RICOH SP 211                     | 1        | 1.89%   |
| Prolific PL2305 Parallel Port          | 1        | 1.89%   |
| Lexmark International B2236dw          | 1        | 1.89%   |
| Kyocera UTAX_TA LP 3240_LP 4240        | 1        | 1.89%   |
| HP OfficeJet Pro 6960                  | 1        | 1.89%   |
| HP OfficeJet 5200 series               | 1        | 1.89%   |
| HP OfficeJet 4650 series               | 1        | 1.89%   |
| HP LaserJet Professional P1102w        | 1        | 1.89%   |
| HP LaserJet P1005                      | 1        | 1.89%   |
| HP LaserJet M203-M206                  | 1        | 1.89%   |
| HP LaserJet 3050                       | 1        | 1.89%   |
| HP LaserJet 1020                       | 1        | 1.89%   |
| HP LaserJet 1015                       | 1        | 1.89%   |
| HP Ink Tank 110 series                 | 1        | 1.89%   |
| HP ENVY 6400 series                    | 1        | 1.89%   |
| HP ENVY 4500 series                    | 1        | 1.89%   |
| HP DeskJet F2492 All-in-One            | 1        | 1.89%   |
| HP Deskjet 4640 series                 | 1        | 1.89%   |
| HP DeskJet 3700 series                 | 1        | 1.89%   |
| HP Deskjet 1050 J410                   | 1        | 1.89%   |
| Gprinter GP-58                         | 1        | 1.89%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 1.89%   |
| Canon TS5100 series                    | 1        | 1.89%   |
| Brother MFC-L3750CDW                   | 1        | 1.89%   |
| Brother MFC-J497DW                     | 1        | 1.89%   |
| Brother MFC-J485DW                     | 1        | 1.89%   |
| Brother MFC-J450DW                     | 1        | 1.89%   |
| Brother MFC-9325CW                     | 1        | 1.89%   |
| Brother MFC-7460DN                     | 1        | 1.89%   |
| Brother HL-L2340D series               | 1        | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 33.33%  |
| Hewlett-Packard | 2        | 33.33%  |
| Canon           | 2        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 16.67%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1        | 16.67%  |
| HP ScanJet 2400c                                        | 1        | 16.67%  |
| HP ScanJet 2200c                                        | 1        | 16.67%  |
| Canon CanoScan LIDE 25                                  | 1        | 16.67%  |
| Canon CanoScan LiDE 200                                 | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech                                          | 115      | 40.49%  |
| Microdia                                          | 29       | 10.21%  |
| Sunplus Innovation Technology                     | 16       | 5.63%   |
| Microsoft                                         | 13       | 4.58%   |
| Apple                                             | 9        | 3.17%   |
| Realtek Semiconductor                             | 8        | 2.82%   |
| Samsung Electronics                               | 7        | 2.46%   |
| Generalplus Technology                            | 7        | 2.46%   |
| Razer USA                                         | 6        | 2.11%   |
| KYE Systems (Mouse Systems)                       | 5        | 1.76%   |
| Hewlett-Packard                                   | 5        | 1.76%   |
| GEMBIRD                                           | 5        | 1.76%   |
| ARC International                                 | 5        | 1.76%   |
| Creative Technology                               | 4        | 1.41%   |
| Z-Star Microelectronics                           | 3        | 1.06%   |
| Sunplus IT                                        | 3        | 1.06%   |
| Sonix Technology                                  | 3        | 1.06%   |
| MacroSilicon                                      | 3        | 1.06%   |
| WaveRider Communications                          | 2        | 0.7%    |
| Ruision                                           | 2        | 0.7%    |
| Lenovo                                            | 2        | 0.7%    |
| Jieli Technology                                  | 2        | 0.7%    |
| Cubeternet                                        | 2        | 0.7%    |
| Chicony Electronics                               | 2        | 0.7%    |
| AVerMedia Technologies                            | 2        | 0.7%    |
| ANYKA                                             | 2        | 0.7%    |
| YGTek                                             | 1        | 0.35%   |
| Valve Software                                    | 1        | 0.35%   |
| Unknown                                           | 1        | 0.35%   |
| Suyin                                             | 1        | 0.35%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1        | 0.35%   |
| Silicon Motion                                    | 1        | 0.35%   |
| Owl Labs                                          | 1        | 0.35%   |
| OPPO Electronics                                  | 1        | 0.35%   |
| OmniVision Technologies                           | 1        | 0.35%   |
| Jeilin Technology                                 | 1        | 0.35%   |
| Insta360                                          | 1        | 0.35%   |
| Huawei Technologies                               | 1        | 0.35%   |
| Google                                            | 1        | 0.35%   |
| Genesys Logic                                     | 1        | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920               | 26       | 9.15%   |
| Logitech Webcam C270                      | 25       | 8.8%    |
| Logitech C922 Pro Stream Webcam           | 16       | 5.63%   |
| Microdia USB 2.0 Camera                   | 12       | 4.23%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 9        | 3.17%   |
| Samsung Galaxy series, misc. (MTP mode)   | 7        | 2.46%   |
| Microsoft LifeCam HD-3000                 | 7        | 2.46%   |
| Logitech C920 PRO HD Webcam               | 6        | 2.11%   |
| Logitech Webcam C310                      | 5        | 1.76%   |
| Logitech BRIO Ultra HD Webcam             | 5        | 1.76%   |
| Generalplus CAMERA - UVC                  | 5        | 1.76%   |
| ARC International Camera                  | 5        | 1.76%   |
| Sunplus PC Camera                         | 4        | 1.41%   |
| Razer USA Gaming Webcam [Kiyo]            | 4        | 1.41%   |
| Microsoft LifeCam Cinema                  | 4        | 1.41%   |
| Microdia Integrated Camera                | 4        | 1.41%   |
| Microdia Camera                           | 4        | 1.41%   |
| Logitech Webcam C930e                     | 4        | 1.41%   |
| Logitech Webcam C925e                     | 4        | 1.41%   |
| KYE Systems (Mouse Systems) Genius Webcam | 4        | 1.41%   |
| Sunplus HD 720P webcam                    | 3        | 1.06%   |
| Sunplus Full HD webcam                    | 3        | 1.06%   |
| Realtek FULL HD 1080P Webcam              | 3        | 1.06%   |
| Microdia Webcam Vitade AF                 | 3        | 1.06%   |
| MacroSilicon MiraBox Capture              | 3        | 1.06%   |
| Logitech StreamCam                        | 3        | 1.06%   |
| Logitech HD Webcam C615                   | 3        | 1.06%   |
| HP Webcam HD 2300                         | 3        | 1.06%   |
| GEMBIRD USB2.0 PC CAMERA                  | 3        | 1.06%   |
| Creative Live! Cam Sync HD [VF0770]       | 3        | 1.06%   |
| Z-Star Venus USB2.0 Camera                | 2        | 0.7%    |
| Sunplus IT PC Camera                      | 2        | 0.7%    |
| Ruision UVC Camera                        | 2        | 0.7%    |
| Realtek Thronmax Stream Go Pro Webcam     | 2        | 0.7%    |
| Razer USA Razer Kiyo Pro                  | 2        | 0.7%    |
| Microdia WEBCAM PCYES RAZA FHD-03         | 2        | 0.7%    |
| Logitech Webcam C110                      | 2        | 0.7%    |
| Logitech HD Webcam C910                   | 2        | 0.7%    |
| Logitech HD Webcam C510                   | 2        | 0.7%    |
| Jieli USB PHY 2.0                         | 2        | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| LighTuning Technology | 2        | 28.57%  |
| DigitalPersona        | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 14.29%  |
| DigitalPersona Fingerprint Reader           | 1        | 14.29%  |
| AuthenTec Fingerprint Sensor                | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 2        | 20%     |
| Alcor Micro           | 2        | 20%     |
| Yubico.com            | 1        | 10%     |
| SCM Microsystems      | 1        | 10%     |
| OmniKey               | 1        | 10%     |
| Clay Logic            | 1        | 10%     |
| Cherry                | 1        | 10%     |
| Aladdin R.D.          | 1        | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 20%     |
| Alcor Micro AU9540 Smartcard Reader               | 2        | 20%     |
| Yubico.com Yubikey NEO(-N) OTP+CCID               | 1        | 10%     |
| SCM Microsystems SCR3500 A Contact Reader         | 1        | 10%     |
| OmniKey CardMan 1021                              | 1        | 10%     |
| Clay Logic Nitrokey Pro                           | 1        | 10%     |
| Cherry Smart Card Reader USB                      | 1        | 10%     |
| Aladdin R.D. JaCarta LT                           | 1        | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1079     | 86.67%  |
| 1     | 142      | 11.41%  |
| 2     | 18       | 1.45%   |
| 4     | 3        | 0.24%   |
| 3     | 3        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 77       | 41.62%  |
| Net/wireless             | 30       | 16.22%  |
| Unassigned class         | 18       | 9.73%   |
| Communication controller | 16       | 8.65%   |
| Camera                   | 8        | 4.32%   |
| Fingerprint reader       | 7        | 3.78%   |
| Bluetooth                | 6        | 3.24%   |
| Chipcard                 | 5        | 2.7%    |
| Sound                    | 4        | 2.16%   |
| Storage/raid             | 2        | 1.08%   |
| Network                  | 2        | 1.08%   |
| Net/ethernet             | 2        | 1.08%   |
| Multimedia controller    | 2        | 1.08%   |
| Modem                    | 2        | 1.08%   |
| Card reader              | 2        | 1.08%   |
| Storage/nvme             | 1        | 0.54%   |
| Dvb card                 | 1        | 0.54%   |

