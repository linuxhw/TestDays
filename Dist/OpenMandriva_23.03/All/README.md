OpenMandriva 23.03 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.03.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_23.03/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_23.03/Notebook/README.md).

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

Total: 1974

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 13-5368            | Notebook    | [811a112c63](https://linux-hardware.org/?probe=811a112c63) | Jan 02, 2024 |
| ASUSTek       | K53SC                       | Notebook    | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [0b5268372a](https://linux-hardware.org/?probe=0b5268372a) | Dec 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [f1c5d0d405](https://linux-hardware.org/?probe=f1c5d0d405) | Dec 24, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [b4333bcaaf](https://linux-hardware.org/?probe=b4333bcaaf) | Dec 22, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [fc2beada0a](https://linux-hardware.org/?probe=fc2beada0a) | Dec 21, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [d38a6ca473](https://linux-hardware.org/?probe=d38a6ca473) | Dec 19, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [d70deaa140](https://linux-hardware.org/?probe=d70deaa140) | Dec 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [60e69d071e](https://linux-hardware.org/?probe=60e69d071e) | Dec 17, 2023 |
| Lenovo        | ThinkPad X260 20F5A0XWJP    | Notebook    | [7aede5c549](https://linux-hardware.org/?probe=7aede5c549) | Dec 16, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [1909f0bbc0](https://linux-hardware.org/?probe=1909f0bbc0) | Dec 16, 2023 |
| HP            | 1494                        | Desktop     | [0c31d410f6](https://linux-hardware.org/?probe=0c31d410f6) | Dec 15, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [5724665c2a](https://linux-hardware.org/?probe=5724665c2a) | Dec 14, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f12298a018](https://linux-hardware.org/?probe=f12298a018) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [5ec5788395](https://linux-hardware.org/?probe=5ec5788395) | Dec 13, 2023 |
| MACHINIST     | X79 Z9-D7 PRO V1.0          | Desktop     | [aaeef17ed2](https://linux-hardware.org/?probe=aaeef17ed2) | Dec 12, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [044e8ae8d6](https://linux-hardware.org/?probe=044e8ae8d6) | Dec 05, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [3658acadc3](https://linux-hardware.org/?probe=3658acadc3) | Dec 04, 2023 |
| Acer          | Aspire X1430                | Desktop     | [e4fa6a217d](https://linux-hardware.org/?probe=e4fa6a217d) | Dec 03, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [136f4b6903](https://linux-hardware.org/?probe=136f4b6903) | Dec 03, 2023 |
| Alienware     | 18                          | Notebook    | [e2dc3b99fc](https://linux-hardware.org/?probe=e2dc3b99fc) | Dec 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f73d3f92cf](https://linux-hardware.org/?probe=f73d3f92cf) | Dec 02, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [0fefa1b40e](https://linux-hardware.org/?probe=0fefa1b40e) | Dec 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [ab8935b499](https://linux-hardware.org/?probe=ab8935b499) | Dec 01, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e61dfbe107](https://linux-hardware.org/?probe=e61dfbe107) | Nov 30, 2023 |
| Dell          | 02YRK5 A01                  | Desktop     | [a59aed6ba5](https://linux-hardware.org/?probe=a59aed6ba5) | Nov 29, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [dd98dacf94](https://linux-hardware.org/?probe=dd98dacf94) | Nov 28, 2023 |
| Dell          | Precision M4500             | Notebook    | [044aca6d38](https://linux-hardware.org/?probe=044aca6d38) | Nov 27, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [557aba57b5](https://linux-hardware.org/?probe=557aba57b5) | Nov 26, 2023 |
| HP            | Laptop 15z-ef3xxx           | Notebook    | [278b62313d](https://linux-hardware.org/?probe=278b62313d) | Nov 25, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | Notebook    | [e93688d366](https://linux-hardware.org/?probe=e93688d366) | Nov 22, 2023 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7a812fcce7](https://linux-hardware.org/?probe=7a812fcce7) | Nov 20, 2023 |
| HP            | 1589                        | Desktop     | [481cc393d1](https://linux-hardware.org/?probe=481cc393d1) | Nov 19, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [87222a31f3](https://linux-hardware.org/?probe=87222a31f3) | Nov 18, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5dfd0d8f38](https://linux-hardware.org/?probe=5dfd0d8f38) | Nov 18, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [84a5759af0](https://linux-hardware.org/?probe=84a5759af0) | Nov 18, 2023 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [e9e9d46316](https://linux-hardware.org/?probe=e9e9d46316) | Nov 17, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6d71a63b67](https://linux-hardware.org/?probe=6d71a63b67) | Nov 16, 2023 |
| Medion        | DN2820FYB-IS BTNUCW08.11... | Desktop     | [def1bf43ff](https://linux-hardware.org/?probe=def1bf43ff) | Nov 15, 2023 |
| Alienware     | 18                          | Notebook    | [129d60c7cc](https://linux-hardware.org/?probe=129d60c7cc) | Nov 15, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [954580f051](https://linux-hardware.org/?probe=954580f051) | Nov 12, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [cd607f9e87](https://linux-hardware.org/?probe=cd607f9e87) | Nov 12, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [d93bb6c2bd](https://linux-hardware.org/?probe=d93bb6c2bd) | Nov 11, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [0c374e0790](https://linux-hardware.org/?probe=0c374e0790) | Nov 11, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [1e2c26c06a](https://linux-hardware.org/?probe=1e2c26c06a) | Nov 09, 2023 |
| Exo           | Intel powered classmate ... | Notebook    | [135b2008b7](https://linux-hardware.org/?probe=135b2008b7) | Nov 09, 2023 |
| HP            | Compaq 6710b                | Notebook    | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [fecdf24435](https://linux-hardware.org/?probe=fecdf24435) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [4b769dbcca](https://linux-hardware.org/?probe=4b769dbcca) | Oct 31, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [763630b66c](https://linux-hardware.org/?probe=763630b66c) | Oct 31, 2023 |
| Acer          | Veriton M480                | Desktop     | [fb5c756319](https://linux-hardware.org/?probe=fb5c756319) | Oct 30, 2023 |
| ASUSTek       | P5B                         | Desktop     | [aa136c9e44](https://linux-hardware.org/?probe=aa136c9e44) | Oct 29, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [bff9909d9b](https://linux-hardware.org/?probe=bff9909d9b) | Oct 24, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [17c7c26cd0](https://linux-hardware.org/?probe=17c7c26cd0) | Oct 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [6f72e3839d](https://linux-hardware.org/?probe=6f72e3839d) | Oct 23, 2023 |
| Acer          | Spin SP314-51               | Convertible | [b8e1c5b1dd](https://linux-hardware.org/?probe=b8e1c5b1dd) | Oct 21, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [5d936f030f](https://linux-hardware.org/?probe=5d936f030f) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [eb657acc28](https://linux-hardware.org/?probe=eb657acc28) | Oct 16, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [78e96592c1](https://linux-hardware.org/?probe=78e96592c1) | Oct 14, 2023 |
| Fujitsu       | FMVNS7HE                    | Notebook    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| Pegatron      | Benicia                     | Desktop     | [895d65cd9b](https://linux-hardware.org/?probe=895d65cd9b) | Oct 08, 2023 |
| HP            | 8433 11                     | Desktop     | [7540fc930b](https://linux-hardware.org/?probe=7540fc930b) | Oct 05, 2023 |
| eMachines     | EL1352                      | Desktop     | [741a66b428](https://linux-hardware.org/?probe=741a66b428) | Oct 05, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [4749aba038](https://linux-hardware.org/?probe=4749aba038) | Oct 04, 2023 |
| HP            | 8433 11                     | Desktop     | [0fcfc69a01](https://linux-hardware.org/?probe=0fcfc69a01) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | Desktop     | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| Intel         | H61                         | Desktop     | [f41171114f](https://linux-hardware.org/?probe=f41171114f) | Sep 28, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [9f17460970](https://linux-hardware.org/?probe=9f17460970) | Sep 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8b562cc39](https://linux-hardware.org/?probe=b8b562cc39) | Sep 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e2dda8ebb1](https://linux-hardware.org/?probe=e2dda8ebb1) | Sep 21, 2023 |
| ASUSTek       | TP550LAB                    | Notebook    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | Notebook    | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| Lenovo        | ThinkPad T420 4236B27       | Notebook    | [8cd0ed072f](https://linux-hardware.org/?probe=8cd0ed072f) | Sep 16, 2023 |
| HP            | 15                          | Notebook    | [636b9a80a1](https://linux-hardware.org/?probe=636b9a80a1) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| Positivo      | C14CR21                     | Notebook    | [9d48466eab](https://linux-hardware.org/?probe=9d48466eab) | Sep 13, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [a1f824e885](https://linux-hardware.org/?probe=a1f824e885) | Sep 12, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [ef6f0ae453](https://linux-hardware.org/?probe=ef6f0ae453) | Sep 11, 2023 |
| Dell          | OptiPlex 3020               | Desktop     | [12428f0a31](https://linux-hardware.org/?probe=12428f0a31) | Sep 11, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [b5b49fefb3](https://linux-hardware.org/?probe=b5b49fefb3) | Sep 09, 2023 |
| Dell          | Latitude E6400              | Notebook    | [e42cf159af](https://linux-hardware.org/?probe=e42cf159af) | Sep 09, 2023 |
| Dell          | 0WK833                      | Desktop     | [5ec8a9e552](https://linux-hardware.org/?probe=5ec8a9e552) | Sep 09, 2023 |
| HP            | Notebook                    | Notebook    | [5a36d2a3bf](https://linux-hardware.org/?probe=5a36d2a3bf) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| MSI           | 760GA-P43                   | Desktop     | [b067d69499](https://linux-hardware.org/?probe=b067d69499) | Sep 08, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c65d5d49b1](https://linux-hardware.org/?probe=c65d5d49b1) | Sep 08, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| Toshiba       | Satellite C850-1DZ          | Notebook    | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [922ff6eddb](https://linux-hardware.org/?probe=922ff6eddb) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| ASRock        | FM2A78M-HD+                 | Desktop     | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| Biostar       | N68S3B                      | Desktop     | [fc063709f7](https://linux-hardware.org/?probe=fc063709f7) | Sep 02, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Intel         | H110                        | Desktop     | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Biostar       | G41D3                       | Desktop     | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [04424409ef](https://linux-hardware.org/?probe=04424409ef) | Aug 29, 2023 |
| Intel         | DG45ID AAE27729-312         | Desktop     | [add370815d](https://linux-hardware.org/?probe=add370815d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | Desktop     | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| Sony          | VPCEB43FG                   | Notebook    | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [ff832aca4a](https://linux-hardware.org/?probe=ff832aca4a) | Aug 26, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| Dell          | G5 5590                     | Notebook    | [c13a60889c](https://linux-hardware.org/?probe=c13a60889c) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [928ea69caf](https://linux-hardware.org/?probe=928ea69caf) | Aug 24, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3f2ff7e9c7](https://linux-hardware.org/?probe=3f2ff7e9c7) | Aug 22, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [33ad1ac951](https://linux-hardware.org/?probe=33ad1ac951) | Aug 21, 2023 |
| Dell          | Latitude E5520              | Notebook    | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| Dell          | Latitude E6500              | Notebook    | [5d1f16198a](https://linux-hardware.org/?probe=5d1f16198a) | Aug 18, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | Notebook    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | Notebook    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | Notebook    | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [61908d704c](https://linux-hardware.org/?probe=61908d704c) | Aug 13, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | Notebook    | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| ZOTAC         | ZBOXNANO-ID67/ID68/ID69     | Mini pc     | [169c6d3b85](https://linux-hardware.org/?probe=169c6d3b85) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [a60b6f6ca2](https://linux-hardware.org/?probe=a60b6f6ca2) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| HP            | 2215                        | Desktop     | [40ace58487](https://linux-hardware.org/?probe=40ace58487) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Acer          | Extensa 5630                | Notebook    | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [e3cf4cec26](https://linux-hardware.org/?probe=e3cf4cec26) | Aug 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d073a53c85](https://linux-hardware.org/?probe=d073a53c85) | Aug 08, 2023 |
| Lenovo        | ThinkPad X220 4290C37       | Notebook    | [125ac0cbd3](https://linux-hardware.org/?probe=125ac0cbd3) | Aug 08, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [84c3eefc94](https://linux-hardware.org/?probe=84c3eefc94) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | Notebook    | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Acer          | AO756                       | Notebook    | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c04ac90ce8](https://linux-hardware.org/?probe=c04ac90ce8) | Aug 07, 2023 |
| Digiboard     | NM70-I                      | Desktop     | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| ASUSTek       | P5GDC                       | Desktop     | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [201844f73e](https://linux-hardware.org/?probe=201844f73e) | Aug 06, 2023 |
| GPD           | G1618-03                    | Notebook    | [070d548515](https://linux-hardware.org/?probe=070d548515) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Dell          | Precision M2800             | Notebook    | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Medion        | B550A4-EM                   | Desktop     | [f1bf2b93c1](https://linux-hardware.org/?probe=f1bf2b93c1) | Aug 05, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [9db6bfdcfa](https://linux-hardware.org/?probe=9db6bfdcfa) | Aug 05, 2023 |
| Intel         | H81                         | Desktop     | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S9R500    | Notebook    | [3624b5e366](https://linux-hardware.org/?probe=3624b5e366) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| ASRock        | G31M-S                      | Desktop     | [02bb341cc9](https://linux-hardware.org/?probe=02bb341cc9) | Aug 04, 2023 |
| GFAST         | N150                        | Notebook    | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | Desktop     | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| HP            | 844C                        | Desktop     | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| HP            | 8767 A                      | Desktop     | [2cf5a8cce4](https://linux-hardware.org/?probe=2cf5a8cce4) | Aug 03, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [c9e70623fc](https://linux-hardware.org/?probe=c9e70623fc) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Dell          | Precision M4500             | Notebook    | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [5cbdefa7c5](https://linux-hardware.org/?probe=5cbdefa7c5) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [70c8bcf589](https://linux-hardware.org/?probe=70c8bcf589) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | Desktop     | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ef89d48d6](https://linux-hardware.org/?probe=7ef89d48d6) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| Dell          | Latitude E6430              | Notebook    | [9dcf92cce9](https://linux-hardware.org/?probe=9dcf92cce9) | Jul 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e11390bc86](https://linux-hardware.org/?probe=e11390bc86) | Jul 31, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| MSI           | MS-B1591                    | Desktop     | [9bdfd87437](https://linux-hardware.org/?probe=9bdfd87437) | Jul 30, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [7d262746c9](https://linux-hardware.org/?probe=7d262746c9) | Jul 30, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [18f28e3fb6](https://linux-hardware.org/?probe=18f28e3fb6) | Jul 29, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | Notebook    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [be08c309d2](https://linux-hardware.org/?probe=be08c309d2) | Jul 29, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | 3111 NOK                    | Desktop     | [bced6fb88a](https://linux-hardware.org/?probe=bced6fb88a) | Jul 29, 2023 |
| HP            | 86F3 00100                  | All in one  | [485fcbfa5d](https://linux-hardware.org/?probe=485fcbfa5d) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| A14CR         | Unknown                     | Notebook    | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Lenovo        | ThinkPad E555 20DH0027UK    | Notebook    | [b7bf821032](https://linux-hardware.org/?probe=b7bf821032) | Jul 26, 2023 |
| ASRock        | B85M                        | Desktop     | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| Positivo      | G800                        | Notebook    | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | P50IJ                       | Notebook    | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Dell          | 0RY206                      | Desktop     | [5f16b7ecda](https://linux-hardware.org/?probe=5f16b7ecda) | Jul 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| HP            | 1495                        | Desktop     | [99072e94e8](https://linux-hardware.org/?probe=99072e94e8) | Jul 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| ZOTAC         | ZBOX-BI322                  | Mini pc     | [f595927b7b](https://linux-hardware.org/?probe=f595927b7b) | Jul 25, 2023 |
| HP            | 8350                        | Desktop     | [51c4120395](https://linux-hardware.org/?probe=51c4120395) | Jul 25, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a68492f27e](https://linux-hardware.org/?probe=a68492f27e) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | Notebook    | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| PCWare        | IPMH61R3 8MB                | Desktop     | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| HP            | 198E                        | Desktop     | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [06e3fae658](https://linux-hardware.org/?probe=06e3fae658) | Jul 24, 2023 |
| HP            | 212B                        | Desktop     | [3e033bf376](https://linux-hardware.org/?probe=3e033bf376) | Jul 24, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [41246e91c0](https://linux-hardware.org/?probe=41246e91c0) | Jul 24, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [e382c4d40c](https://linux-hardware.org/?probe=e382c4d40c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| ASUSTek       | NARRA                       | Desktop     | [2c0dc7397a](https://linux-hardware.org/?probe=2c0dc7397a) | Jul 23, 2023 |
| HP            | Notebook                    | Notebook    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [b5fe1f6fca](https://linux-hardware.org/?probe=b5fe1f6fca) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | Notebook    | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| Chuwi         | M01ALWR310-ADA90A           | Mini pc     | [0274c94523](https://linux-hardware.org/?probe=0274c94523) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [c058e8c58e](https://linux-hardware.org/?probe=c058e8c58e) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [8a8cb2c3e4](https://linux-hardware.org/?probe=8a8cb2c3e4) | Jul 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [3ed4a6a897](https://linux-hardware.org/?probe=3ed4a6a897) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| LG Electro... | P420-G.BE42P1               | Notebook    | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [96f08b7598](https://linux-hardware.org/?probe=96f08b7598) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | Notebook    | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| AZW           | Gemini J45                  | Desktop     | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | G42                         | Notebook    | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [a62fb79aac](https://linux-hardware.org/?probe=a62fb79aac) | Jul 17, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [082165532b](https://linux-hardware.org/?probe=082165532b) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [6d453b900a](https://linux-hardware.org/?probe=6d453b900a) | Jul 17, 2023 |
| HP            | 18E8                        | Desktop     | [606aa1f34d](https://linux-hardware.org/?probe=606aa1f34d) | Jul 16, 2023 |
| Toshiba       | TECRA A10                   | Notebook    | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [f2432a7a2a](https://linux-hardware.org/?probe=f2432a7a2a) | Jul 15, 2023 |
| Dell          | 073MMW A03                  | Desktop     | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| Lenovo        | ThinkPad T400 6474C53       | Notebook    | [e9db1ea8a6](https://linux-hardware.org/?probe=e9db1ea8a6) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| HP            | 83EB                        | All in one  | [9a1012bd0d](https://linux-hardware.org/?probe=9a1012bd0d) | Jul 14, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [3efd87a0d8](https://linux-hardware.org/?probe=3efd87a0d8) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Acer          | Veriton E430G               | Desktop     | [f52d631cce](https://linux-hardware.org/?probe=f52d631cce) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| Dell          | 0WC7KF A00                  | All in one  | [71309341ec](https://linux-hardware.org/?probe=71309341ec) | Jul 13, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [ce55d97846](https://linux-hardware.org/?probe=ce55d97846) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Dell          | Inspiron 5749               | Notebook    | [0421d22945](https://linux-hardware.org/?probe=0421d22945) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [8f1d64206e](https://linux-hardware.org/?probe=8f1d64206e) | Jul 11, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Unknown       | 1.0                         | Desktop     | [dcf11d8f40](https://linux-hardware.org/?probe=dcf11d8f40) | Jul 10, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [9a58539b66](https://linux-hardware.org/?probe=9a58539b66) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [84738fcbb3](https://linux-hardware.org/?probe=84738fcbb3) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| AZW           | U55                         | Mini pc     | [274a292b6d](https://linux-hardware.org/?probe=274a292b6d) | Jul 09, 2023 |
| Alienware     | 17                          | Notebook    | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6a3712ec9](https://linux-hardware.org/?probe=c6a3712ec9) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [26896deb1e](https://linux-hardware.org/?probe=26896deb1e) | Jul 09, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [d6a3964ff7](https://linux-hardware.org/?probe=d6a3964ff7) | Jul 08, 2023 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [f36d062c95](https://linux-hardware.org/?probe=f36d062c95) | Jul 08, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | Notebook    | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [1cc2699f88](https://linux-hardware.org/?probe=1cc2699f88) | Jul 08, 2023 |
| HP            | 158B                        | Desktop     | [aad7455bc5](https://linux-hardware.org/?probe=aad7455bc5) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | Notebook    | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [ac0f0dd893](https://linux-hardware.org/?probe=ac0f0dd893) | Jul 08, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [05d0b7e769](https://linux-hardware.org/?probe=05d0b7e769) | Jul 07, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [de87cf7e95](https://linux-hardware.org/?probe=de87cf7e95) | Jul 07, 2023 |
| Medion        | Unknown                     | Notebook    | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| Dell          | 09D2HH A00                  | Desktop     | [2885be7e12](https://linux-hardware.org/?probe=2885be7e12) | Jul 07, 2023 |
| Google        | Lick                        | Notebook    | [aa3d137fcf](https://linux-hardware.org/?probe=aa3d137fcf) | Jul 07, 2023 |
| HP            | 0A50h                       | Desktop     | [125782672d](https://linux-hardware.org/?probe=125782672d) | Jul 06, 2023 |
| Dell          | Latitude E5450              | Notebook    | [0a1677c02e](https://linux-hardware.org/?probe=0a1677c02e) | Jul 06, 2023 |
| Toshiba       | Satellite P200D             | Notebook    | [609a275664](https://linux-hardware.org/?probe=609a275664) | Jul 06, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e21418b71f](https://linux-hardware.org/?probe=e21418b71f) | Jul 06, 2023 |
| HP            | 212A                        | Desktop     | [7f7a7fa2e1](https://linux-hardware.org/?probe=7f7a7fa2e1) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [d3738bf0c4](https://linux-hardware.org/?probe=d3738bf0c4) | Jul 05, 2023 |
| HP            | 550                         | Notebook    | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [5b561a0e00](https://linux-hardware.org/?probe=5b561a0e00) | Jul 05, 2023 |
| Packard Be... | IPOWER                      | Notebook    | [3c116708b4](https://linux-hardware.org/?probe=3c116708b4) | Jul 05, 2023 |
| Standard      | ECT                         | Notebook    | [42f38309b9](https://linux-hardware.org/?probe=42f38309b9) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | Notebook    | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [464ff62eaf](https://linux-hardware.org/?probe=464ff62eaf) | Jul 04, 2023 |
| eMachines     | Padus                       | Notebook    | [008b3a48cd](https://linux-hardware.org/?probe=008b3a48cd) | Jul 04, 2023 |
| Biostar       | TA970                       | Desktop     | [31aec054d7](https://linux-hardware.org/?probe=31aec054d7) | Jul 04, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [08fb6b76ce](https://linux-hardware.org/?probe=08fb6b76ce) | Jul 03, 2023 |
| Lenovo        | Aptio CRB SDK0J40679 WIN... | Mini pc     | [40f510325d](https://linux-hardware.org/?probe=40f510325d) | Jul 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1b82430294](https://linux-hardware.org/?probe=1b82430294) | Jul 02, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e112fcd006](https://linux-hardware.org/?probe=e112fcd006) | Jul 02, 2023 |
| Alienware     | 18                          | Notebook    | [7898671060](https://linux-hardware.org/?probe=7898671060) | Jul 02, 2023 |
| HP            | 1497                        | Desktop     | [e282eb8fe1](https://linux-hardware.org/?probe=e282eb8fe1) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [fc639c945e](https://linux-hardware.org/?probe=fc639c945e) | Jul 01, 2023 |
| HP            | 550                         | Notebook    | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| Acer          | JM11-MS                     | Notebook    | [ad02c854e0](https://linux-hardware.org/?probe=ad02c854e0) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [af3e6790e4](https://linux-hardware.org/?probe=af3e6790e4) | Jun 30, 2023 |
| HP            | 8056                        | Desktop     | [32d1199c51](https://linux-hardware.org/?probe=32d1199c51) | Jun 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| Lenovo        | ThinkPad L430 246634S       | Notebook    | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [6d3d6e002f](https://linux-hardware.org/?probe=6d3d6e002f) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Dell          | System XPS L321X            | Notebook    | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | Notebook    | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [20f509028b](https://linux-hardware.org/?probe=20f509028b) | Jun 29, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0286d2f5e5](https://linux-hardware.org/?probe=0286d2f5e5) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | Desktop     | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | Notebook    | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| Huanan        | X99-BD4 V1.31               | Desktop     | [fcd9a6b1e2](https://linux-hardware.org/?probe=fcd9a6b1e2) | Jun 28, 2023 |
| Acer          | EG43M                       | Desktop     | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | Desktop     | [1114cf7328](https://linux-hardware.org/?probe=1114cf7328) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Foxconn       | G41MD                       | Desktop     | [926a733402](https://linux-hardware.org/?probe=926a733402) | Jun 27, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [cb47380993](https://linux-hardware.org/?probe=cb47380993) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2ed9f4248c](https://linux-hardware.org/?probe=2ed9f4248c) | Jun 27, 2023 |
| PCsmart       | PCSGOB14p-C                 | Notebook    | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [09f4e0e86a](https://linux-hardware.org/?probe=09f4e0e86a) | Jun 27, 2023 |
| Kennex        | POS-PIG41BA                 | Desktop     | [90addad9e1](https://linux-hardware.org/?probe=90addad9e1) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | Notebook    | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [89858274fd](https://linux-hardware.org/?probe=89858274fd) | Jun 27, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [4557637b8a](https://linux-hardware.org/?probe=4557637b8a) | Jun 26, 2023 |
| HP            | 8430 1000                   | All in one  | [cba036b5d2](https://linux-hardware.org/?probe=cba036b5d2) | Jun 26, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [6aba51f328](https://linux-hardware.org/?probe=6aba51f328) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [713bfcdf62](https://linux-hardware.org/?probe=713bfcdf62) | Jun 26, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [734e60af76](https://linux-hardware.org/?probe=734e60af76) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [8013deae02](https://linux-hardware.org/?probe=8013deae02) | Jun 25, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [f58c462a34](https://linux-hardware.org/?probe=f58c462a34) | Jun 25, 2023 |
| Biostar       | G31M+                       | Desktop     | [d8347c5f07](https://linux-hardware.org/?probe=d8347c5f07) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Dell          | Precision M6400             | Notebook    | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [186a7eedb6](https://linux-hardware.org/?probe=186a7eedb6) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | Notebook    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Medion        | H110H4-CM2                  | Desktop     | [49df9d792a](https://linux-hardware.org/?probe=49df9d792a) | Jun 25, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [6760d73caf](https://linux-hardware.org/?probe=6760d73caf) | Jun 24, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [785d3130e7](https://linux-hardware.org/?probe=785d3130e7) | Jun 24, 2023 |
| HP            | G62                         | Notebook    | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Dell          | Latitude 3180               | Notebook    | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [5d4d2adebe](https://linux-hardware.org/?probe=5d4d2adebe) | Jun 24, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [76dd0fc5f1](https://linux-hardware.org/?probe=76dd0fc5f1) | Jun 24, 2023 |
| HP            | Compaq 610                  | Notebook    | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| HP            | 1495                        | Desktop     | [eab7d15f02](https://linux-hardware.org/?probe=eab7d15f02) | Jun 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [39d5409264](https://linux-hardware.org/?probe=39d5409264) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| Huanan        | X79 V6.11                   | Desktop     | [e94687bb6b](https://linux-hardware.org/?probe=e94687bb6b) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [167de0618f](https://linux-hardware.org/?probe=167de0618f) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| Sony          | VAIO                        | All in one  | [8eda132a31](https://linux-hardware.org/?probe=8eda132a31) | Jun 22, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8454119675](https://linux-hardware.org/?probe=8454119675) | Jun 22, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ba9d7c939a](https://linux-hardware.org/?probe=ba9d7c939a) | Jun 22, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| Acer          | One S1002                   | Notebook    | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [9f5f612aa7](https://linux-hardware.org/?probe=9f5f612aa7) | Jun 21, 2023 |
| HP            | Notebook                    | Notebook    | [3460bcb864](https://linux-hardware.org/?probe=3460bcb864) | Jun 20, 2023 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [abaf6ee67e](https://linux-hardware.org/?probe=abaf6ee67e) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| Acer          | Aspire F5-771G              | Notebook    | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| Gigabyte      | GA-E350N                    | Desktop     | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Dell          | System XPS L502X            | Notebook    | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4bafdb9349](https://linux-hardware.org/?probe=4bafdb9349) | Jun 18, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [7348297d40](https://linux-hardware.org/?probe=7348297d40) | Jun 18, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [fac7a3587a](https://linux-hardware.org/?probe=fac7a3587a) | Jun 18, 2023 |
| GEEKOM        | MiniAir 11                  | Server      | [ac5a7b3810](https://linux-hardware.org/?probe=ac5a7b3810) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [bb3ad00508](https://linux-hardware.org/?probe=bb3ad00508) | Jun 17, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | Notebook    | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3050f49c99](https://linux-hardware.org/?probe=3050f49c99) | Jun 17, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [eebb6ba229](https://linux-hardware.org/?probe=eebb6ba229) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [491797a556](https://linux-hardware.org/?probe=491797a556) | Jun 17, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [2149968671](https://linux-hardware.org/?probe=2149968671) | Jun 16, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [4dae4ff7c6](https://linux-hardware.org/?probe=4dae4ff7c6) | Jun 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ebedbde736](https://linux-hardware.org/?probe=ebedbde736) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [699dd5b23e](https://linux-hardware.org/?probe=699dd5b23e) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [d7689b11ad](https://linux-hardware.org/?probe=d7689b11ad) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [41fa36550a](https://linux-hardware.org/?probe=41fa36550a) | Jun 14, 2023 |
| HP            | 81B3                        | Desktop     | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [b50d647073](https://linux-hardware.org/?probe=b50d647073) | Jun 14, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [83d9a91c16](https://linux-hardware.org/?probe=83d9a91c16) | Jun 13, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c74f83bbea](https://linux-hardware.org/?probe=c74f83bbea) | Jun 13, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| Biostar       | A520MH                      | Desktop     | [70760c5e70](https://linux-hardware.org/?probe=70760c5e70) | Jun 12, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| HP            | 339A                        | Desktop     | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| HP            | G42                         | Notebook    | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Acer          | Predator G3600              | Desktop     | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| HP            | 09E0h                       | Desktop     | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| HP            | 87A4 10100                  | All in one  | [3c67e34a5e](https://linux-hardware.org/?probe=3c67e34a5e) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| HP            | 8169                        | Desktop     | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| Kraftway      | KWH510                      | Desktop     | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| HP            | 822A                        | Desktop     | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | Desktop     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| HP            | 8265                        | Desktop     | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| NEC Comput... | MS-AD611                    | All in one  | [219795e31d](https://linux-hardware.org/?probe=219795e31d) | Jun 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [48d99dbec6](https://linux-hardware.org/?probe=48d99dbec6) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | Desktop     | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | Desktop     | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Foxconn       | G41MD                       | Desktop     | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| ECS           | G31T-M                      | Desktop     | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| Compaq        | 420                         | Notebook    | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| Teclast       | X4                          | Tablet      | [2392aa748a](https://linux-hardware.org/?probe=2392aa748a) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | Desktop     | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Dell          | System Vostro 3450          | Notebook    | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [11bab4bc11](https://linux-hardware.org/?probe=11bab4bc11) | May 30, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | Notebook    | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | P67A-GD65                   | Desktop     | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Google        | Auron_Paine                 | Notebook    | [66fd27934f](https://linux-hardware.org/?probe=66fd27934f) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Lenovo        | ThinkPad W541 20EF000MUS    | Notebook    | [44c1329399](https://linux-hardware.org/?probe=44c1329399) | May 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [42b817db26](https://linux-hardware.org/?probe=42b817db26) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | Notebook    | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Dell          | 0TP412                      | Desktop     | [112fa3015f](https://linux-hardware.org/?probe=112fa3015f) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3e9709dc25](https://linux-hardware.org/?probe=3e9709dc25) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| MSI           | B250M BAZOOKA               | Desktop     | [2bfe50d945](https://linux-hardware.org/?probe=2bfe50d945) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5977804b94](https://linux-hardware.org/?probe=5977804b94) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | Desktop     | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| MSI           | Z590 PLUS                   | Desktop     | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [0df1994f25](https://linux-hardware.org/?probe=0df1994f25) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [b6b7396e06](https://linux-hardware.org/?probe=b6b7396e06) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [701c6c3410](https://linux-hardware.org/?probe=701c6c3410) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | Desktop     | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Intel         | H61                         | Desktop     | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| Dell          | 0H19HD A06                  | Server      | [25975db1c4](https://linux-hardware.org/?probe=25975db1c4) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | Notebook    | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| Foxconn       | G41MD                       | Desktop     | [a3a8a67867](https://linux-hardware.org/?probe=a3a8a67867) | May 23, 2023 |
| Dell          | 0X2YVY A00                  | All in one  | [cf15aa9b1a](https://linux-hardware.org/?probe=cf15aa9b1a) | May 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | Notebook    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| HP            | 2AF3                        | Desktop     | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| Dell          | Latitude E6230              | Notebook    | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [816fffab13](https://linux-hardware.org/?probe=816fffab13) | May 21, 2023 |
| Teclast       | X4                          | Tablet      | [9dc0b8fa7b](https://linux-hardware.org/?probe=9dc0b8fa7b) | May 21, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [0ef682fa85](https://linux-hardware.org/?probe=0ef682fa85) | May 21, 2023 |
| Philco        | 14H                         | Notebook    | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | Notebook    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| ASUSTek       | N53TK                       | Notebook    | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| ASRock        | Q1900M                      | Desktop     | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [0deaff38f5](https://linux-hardware.org/?probe=0deaff38f5) | May 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3af6442c9](https://linux-hardware.org/?probe=c3af6442c9) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [e1939cff8f](https://linux-hardware.org/?probe=e1939cff8f) | May 21, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [f39a134aa1](https://linux-hardware.org/?probe=f39a134aa1) | May 20, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Latitude 5285               | Notebook    | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b563edd887](https://linux-hardware.org/?probe=b563edd887) | May 20, 2023 |
| Foxconn       | G41MD                       | Desktop     | [1a649b0512](https://linux-hardware.org/?probe=1a649b0512) | May 20, 2023 |
| HP            | 250 G2                      | Notebook    | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | Notebook    | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | Notebook    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | Notebook    | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b30dee1244](https://linux-hardware.org/?probe=b30dee1244) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | Notebook    | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | Desktop     | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| NEC Comput... | SK15 3A3B                   | All in one  | [80a4b43ab9](https://linux-hardware.org/?probe=80a4b43ab9) | May 17, 2023 |
| Fujitsu       | LIFEBOOK P728               | Convertible | [55db12e408](https://linux-hardware.org/?probe=55db12e408) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| Maxtang       | FP650 V1.0                  | Desktop     | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| Samsung       | R428/P428                   | Notebook    | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | 8436                        | Desktop     | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| HP            | Pavilion dv8                | Notebook    | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | Desktop     | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | Notebook    | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Intel         | H61                         | Desktop     | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | Desktop     | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [95974d7e97](https://linux-hardware.org/?probe=95974d7e97) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Toshiba       | Satellite C75-A             | Notebook    | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [989d8eef43](https://linux-hardware.org/?probe=989d8eef43) | May 11, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7e1600284a](https://linux-hardware.org/?probe=7e1600284a) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Intel         | X58M                        | Desktop     | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| Samsung       | X420/X520                   | Notebook    | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8f7bcc525d](https://linux-hardware.org/?probe=8f7bcc525d) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| Dell          | Precision M3800             | Notebook    | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| HP            | 304Ah                       | Desktop     | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | Notebook    | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Acer          | EG43M                       | Desktop     | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [53d91dca3c](https://linux-hardware.org/?probe=53d91dca3c) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [acf61a6132](https://linux-hardware.org/?probe=acf61a6132) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| ASUSTek       | X202E                       | Notebook    | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [47388f4553](https://linux-hardware.org/?probe=47388f4553) | May 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [46a87a6448](https://linux-hardware.org/?probe=46a87a6448) | May 07, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [16611a8ed6](https://linux-hardware.org/?probe=16611a8ed6) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [305cc49ac0](https://linux-hardware.org/?probe=305cc49ac0) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [895855ed9a](https://linux-hardware.org/?probe=895855ed9a) | May 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [655bbe4068](https://linux-hardware.org/?probe=655bbe4068) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Dell          | System XPS L702X            | Notebook    | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | Desktop     | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [d5456946bb](https://linux-hardware.org/?probe=d5456946bb) | May 06, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | Desktop     | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| ASUSTek       | X401A1                      | Notebook    | [3fa1a1e9f0](https://linux-hardware.org/?probe=3fa1a1e9f0) | May 05, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [edcdedd65a](https://linux-hardware.org/?probe=edcdedd65a) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6f2b69becc](https://linux-hardware.org/?probe=6f2b69becc) | May 05, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| Dell          | 0PU052                      | Desktop     | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| ASRock        | Z590 Steel Legend           | Desktop     | [d36cec198b](https://linux-hardware.org/?probe=d36cec198b) | May 04, 2023 |
| Medion        | E6232                       | Notebook    | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Gateway       | NE46R                       | Notebook    | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | Notebook    | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | Notebook    | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [d8ec895bea](https://linux-hardware.org/?probe=d8ec895bea) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Acer          | H57M01                      | Desktop     | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e9f23b9574](https://linux-hardware.org/?probe=e9f23b9574) | May 03, 2023 |
| Positivo      | W2150G                      | All in one  | [38c2a94baa](https://linux-hardware.org/?probe=38c2a94baa) | May 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [cb2a0efe72](https://linux-hardware.org/?probe=cb2a0efe72) | May 02, 2023 |
| Unknown       | 1.0                         | Desktop     | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| American M... | IPPBT-RO                    | All in one  | [a2921975cd](https://linux-hardware.org/?probe=a2921975cd) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| HP            | 3031h                       | Desktop     | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | Desktop     | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [ecae18f163](https://linux-hardware.org/?probe=ecae18f163) | May 01, 2023 |
| HP            | 3033h                       | Desktop     | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| HP            | 3648h                       | Desktop     | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| HP            | Compaq 8510w                | Notebook    | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b23b933b5](https://linux-hardware.org/?probe=4b23b933b5) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | Desktop     | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| HP            | Notebook                    | Notebook    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| Intel         | H61                         | Desktop     | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| MSI           | MS-9661 SA                  | Server      | [1888fa6df7](https://linux-hardware.org/?probe=1888fa6df7) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Medion        | X6816                       | Notebook    | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Sony          | SVF15212CXW                 | Notebook    | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| HP            | ProBook 4330s               | Notebook    | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | Notebook    | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [da50afdd1c](https://linux-hardware.org/?probe=da50afdd1c) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | Desktop     | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | Notebook    | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Samsung       | 950QED                      | Convertible | [0135cc3aa4](https://linux-hardware.org/?probe=0135cc3aa4) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Biostar       | H610MH                      | Desktop     | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | Notebook    | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Intel         | H81                         | Desktop     | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | Notebook    | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| HP            | 83E2                        | Desktop     | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Dell          | 0RCGCR A04                  | Server      | [8ef63cb2de](https://linux-hardware.org/?probe=8ef63cb2de) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e2f309bb08](https://linux-hardware.org/?probe=e2f309bb08) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | Notebook    | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | Notebook    | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | Notebook    | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Dell          | Latitude XT2                | Notebook    | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | Notebook    | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | Desktop     | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | Notebook    | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| Acer          | Spin SP315-51               | Convertible | [42da7880dd](https://linux-hardware.org/?probe=42da7880dd) | Apr 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6115e5ccd4](https://linux-hardware.org/?probe=6115e5ccd4) | Apr 22, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9d1c8d691f](https://linux-hardware.org/?probe=9d1c8d691f) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [2ff545a3fc](https://linux-hardware.org/?probe=2ff545a3fc) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| HP            | ProBook 4330s               | Notebook    | [f6608ffee2](https://linux-hardware.org/?probe=f6608ffee2) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | Desktop     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Acer          | Spin SP314-51               | Convertible | [5fd72bcee7](https://linux-hardware.org/?probe=5fd72bcee7) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | Desktop     | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | Desktop     | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| HP            | Compaq 6720s                | Notebook    | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | Desktop     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| ASRock        | P43DE                       | Desktop     | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | Desktop     | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [11ea81f23c](https://linux-hardware.org/?probe=11ea81f23c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | Notebook    | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| HP            | G62                         | Notebook    | [a0096bb254](https://linux-hardware.org/?probe=a0096bb254) | Apr 20, 2023 |
| Gigabyte      | H81N                        | Desktop     | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Toshiba       | dynabook T451/46EW          | Notebook    | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| Intel         | H61S                        | Desktop     | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [14d03d2dd7](https://linux-hardware.org/?probe=14d03d2dd7) | Apr 19, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| HP            | 18E4                        | Desktop     | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | Notebook    | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | Desktop     | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.03/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390      | 1861      | 95.73%  |
| 6.2.2-desktop-1omv2390      | 44        | 2.26%   |
| 6.1.1-desktop-1omv2290      | 13        | 0.67%   |
| 6.2.1-desktop-1omv2390      | 8         | 0.41%   |
| 5.16.13-desktop-1omv4003    | 6         | 0.31%   |
| 6.1.4-desktop-1omv2301      | 4         | 0.21%   |
| 6.3.5-desktop-3omv2390      | 2         | 0.1%    |
| 6.2.8-desktop-1omv2390      | 2         | 0.1%    |
| 6.4.11-desktop-1omv2390     | 1         | 0.05%   |
| 6.2.7-desktop-1omv2390      | 1         | 0.05%   |
| 6.2.10-desktop-2.0omv4.9mjn | 1         | 0.05%   |
| 6.1.22-xanmod1              | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 1861      | 95.73%  |
| 6.2.2   | 44        | 2.26%   |
| 6.1.1   | 13        | 0.67%   |
| 6.2.1   | 8         | 0.41%   |
| 5.16.13 | 6         | 0.31%   |
| 6.1.4   | 4         | 0.21%   |
| 6.3.5   | 2         | 0.1%    |
| 6.2.8   | 2         | 0.1%    |
| 6.4.11  | 1         | 0.05%   |
| 6.2.7   | 1         | 0.05%   |
| 6.2.10  | 1         | 0.05%   |
| 6.1.22  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1917      | 98.61%  |
| 6.1     | 18        | 0.93%   |
| 5.16    | 6         | 0.31%   |
| 6.3     | 2         | 0.1%    |
| 6.4     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1944      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 1649      | 84.83%  |
| GNOME    | 154       | 7.92%   |
| LXQt     | 124       | 6.38%   |
| Cinnamon | 7         | 0.36%   |
| XFCE     | 3         | 0.15%   |
| Budgie   | 3         | 0.15%   |
| Unknown  | 3         | 0.15%   |
| DWM      | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1790      | 92.08%  |
| Wayland | 154       | 7.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1782      | 91.62%  |
| GDM     | 155       | 7.97%   |
| LightDM | 6         | 0.31%   |
| Unknown | 2         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 920       | 47.3%   |
| de_DE | 153       | 7.87%   |
| fr_FR | 116       | 5.96%   |
| ru_RU | 105       | 5.4%    |
| en_GB | 85        | 4.37%   |
| pl_PL | 80        | 4.11%   |
| pt_BR | 77        | 3.96%   |
| it_IT | 73        | 3.75%   |
| es_ES | 41        | 2.11%   |
| es_MX | 36        | 1.85%   |
| en_CA | 29        | 1.49%   |
| en_AU | 23        | 1.18%   |
| cs_CZ | 20        | 1.03%   |
| hu_HU | 18        | 0.93%   |
| en_IN | 14        | 0.72%   |
| nl_NL | 12        | 0.62%   |
| de_AT | 12        | 0.62%   |
| es_AR | 10        | 0.51%   |
| fr_CA | 9         | 0.46%   |
| tr_TR | 8         | 0.41%   |
| ja_JP | 8         | 0.41%   |
| fr_BE | 8         | 0.41%   |
| es_VE | 8         | 0.41%   |
| de_CH | 8         | 0.41%   |
| pt_PT | 7         | 0.36%   |
| da_DK | 7         | 0.36%   |
| nl_BE | 5         | 0.26%   |
| es_CO | 5         | 0.26%   |
| fr_CH | 4         | 0.21%   |
| es_UY | 4         | 0.21%   |
| es_PE | 4         | 0.21%   |
| en_ZA | 4         | 0.21%   |
| en_NZ | 4         | 0.21%   |
| UTF-8 | 3         | 0.15%   |
| es_CL | 3         | 0.15%   |
| en_AG | 3         | 0.15%   |
| es_CR | 2         | 0.1%    |
| en_SG | 2         | 0.1%    |
| en_PH | 2         | 0.1%    |
| en_DK | 2         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1153      | 59.31%  |
| BIOS | 791       | 40.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 954       | 49.05%  |
| Overlay  | 845       | 43.44%  |
| Btrfs    | 105       | 5.4%    |
| Xfs      | 20        | 1.03%   |
| F2fs     | 15        | 0.77%   |
| Ext3     | 3         | 0.15%   |
| Jfs      | 2         | 0.1%    |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1538      | 79.03%  |
| MBR     | 407       | 20.91%  |
| Unknown | 1         | 0.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1005      | 51.67%  |
| Yes       | 940       | 48.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1104      | 56.73%  |
| Yes       | 842       | 43.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 288       | 14.81%  |
| Lenovo              | 259       | 13.32%  |
| Hewlett-Packard     | 251       | 12.91%  |
| Dell                | 221       | 11.37%  |
| Gigabyte Technology | 140       | 7.2%    |
| Acer                | 128       | 6.58%   |
| MSI                 | 115       | 5.92%   |
| ASRock              | 77        | 3.96%   |
| Toshiba             | 44        | 2.26%   |
| Intel               | 35        | 1.8%    |
| Fujitsu             | 34        | 1.75%   |
| Samsung Electronics | 28        | 1.44%   |
| Apple               | 28        | 1.44%   |
| Sony                | 17        | 0.87%   |
| Biostar             | 17        | 0.87%   |
| Unknown             | 17        | 0.87%   |
| Foxconn             | 15        | 0.77%   |
| Fujitsu Siemens     | 12        | 0.62%   |
| Packard Bell        | 11        | 0.57%   |
| Medion              | 11        | 0.57%   |
| Microsoft           | 9         | 0.46%   |
| Chuwi               | 9         | 0.46%   |
| Positivo            | 8         | 0.41%   |
| Pegatron            | 8         | 0.41%   |
| Notebook            | 8         | 0.41%   |
| ECS                 | 8         | 0.41%   |
| AZW                 | 8         | 0.41%   |
| Alienware           | 8         | 0.41%   |
| HUAWEI              | 6         | 0.31%   |
| NEC Computers       | 5         | 0.26%   |
| GPU Company         | 5         | 0.26%   |
| Google              | 5         | 0.26%   |
| ZOTAC               | 4         | 0.21%   |
| TUXEDO              | 4         | 0.21%   |
| LG Electronics      | 4         | 0.21%   |
| eMachines           | 4         | 0.21%   |
| Timi                | 3         | 0.15%   |
| lapbook             | 3         | 0.15%   |
| Kiano               | 3         | 0.15%   |
| Huanan              | 3         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 22        | 1.13%   |
| ASUS All Series                             | 10        | 0.51%   |
| HP Notebook                                 | 9         | 0.46%   |
| Dell OptiPlex 7010                          | 9         | 0.46%   |
| ASUS PRIME A320M-K                          | 7         | 0.36%   |
| Intel H61                                   | 6         | 0.31%   |
| Gigabyte Z77M-D3H                           | 6         | 0.31%   |
| Dell Inspiron 13-5368                       | 6         | 0.31%   |
| ASUS S551LN                                 | 6         | 0.31%   |
| MSI MS-7C02                                 | 5         | 0.26%   |
| MSI MS-7B86                                 | 5         | 0.26%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 5         | 0.26%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 5         | 0.26%   |
| Dell OptiPlex 3020                          | 5         | 0.26%   |
| ASUS P5G41T-M LX                            | 5         | 0.26%   |
| Toshiba Satellite L655                      | 4         | 0.21%   |
| Samsung 950XCJ/951XCJ/950XCR                | 4         | 0.21%   |
| Samsung 950QED                              | 4         | 0.21%   |
| MSI MS-7C56                                 | 4         | 0.21%   |
| MSI MS-7817                                 | 4         | 0.21%   |
| MSI MS-7721                                 | 4         | 0.21%   |
| Lenovo V15-ADA 82C7                         | 4         | 0.21%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 4         | 0.21%   |
| HP Pavilion Notebook                        | 4         | 0.21%   |
| HP EliteDesk 800 G1 SFF                     | 4         | 0.21%   |
| HP 250 G6 Notebook PC                       | 4         | 0.21%   |
| Foxconn G41MD                               | 4         | 0.21%   |
| Dell OptiPlex 9020                          | 4         | 0.21%   |
| Dell Latitude 7490                          | 4         | 0.21%   |
| Dell Inspiron 1720                          | 4         | 0.21%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)          | 3         | 0.15%   |
| MSI MS-7C91                                 | 3         | 0.15%   |
| MSI MS-7C52                                 | 3         | 0.15%   |
| MSI MS-7850                                 | 3         | 0.15%   |
| Lenovo V145-15AST 81MT                      | 3         | 0.15%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 3         | 0.15%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3001LUK        | 3         | 0.15%   |
| Lenovo IdeaPad S145-15AST 81N3              | 3         | 0.15%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2         | 3         | 0.15%   |
| Lenovo G50-70 20351                         | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 96        | 4.94%   |
| Acer Aspire             | 87        | 4.48%   |
| Lenovo IdeaPad          | 58        | 2.98%   |
| Dell OptiPlex           | 55        | 2.83%   |
| Dell Latitude           | 54        | 2.78%   |
| Dell Inspiron           | 54        | 2.78%   |
| ASUS PRIME              | 45        | 2.31%   |
| HP Pavilion             | 42        | 2.16%   |
| HP Compaq               | 41        | 2.11%   |
| Toshiba Satellite       | 36        | 1.85%   |
| Lenovo ThinkCentre      | 26        | 1.34%   |
| HP Laptop               | 26        | 1.34%   |
| HP EliteBook            | 23        | 1.18%   |
| Dell Precision          | 23        | 1.18%   |
| ASUS VivoBook           | 22        | 1.13%   |
| Unknown                 | 22        | 1.13%   |
| ASUS ROG                | 17        | 0.87%   |
| HP EliteDesk            | 15        | 0.77%   |
| ASUS TUF                | 15        | 0.77%   |
| HP ProBook              | 14        | 0.72%   |
| Dell Vostro             | 14        | 0.72%   |
| Fujitsu LIFEBOOK        | 13        | 0.67%   |
| Acer Veriton            | 11        | 0.57%   |
| Lenovo IdeaCentre       | 10        | 0.51%   |
| Fujitsu ESPRIMO         | 10        | 0.51%   |
| Dell XPS                | 10        | 0.51%   |
| ASUS All                | 10        | 0.51%   |
| Microsoft Surface       | 9         | 0.46%   |
| HP ProDesk              | 9         | 0.46%   |
| HP Notebook             | 9         | 0.46%   |
| ASUS M5A78L-M           | 9         | 0.46%   |
| Fujitsu Siemens ESPRIMO | 8         | 0.41%   |
| Packard Bell EasyNote   | 7         | 0.36%   |
| Lenovo Yoga             | 7         | 0.36%   |
| Lenovo Legion           | 7         | 0.36%   |
| Dell System             | 7         | 0.36%   |
| ASUS P5G41T-M           | 7         | 0.36%   |
| Toshiba dynabook        | 6         | 0.31%   |
| Intel H61               | 6         | 0.31%   |
| HP OMEN                 | 6         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 177       | 9.1%    |
| 2012    | 174       | 8.95%   |
| 2011    | 156       | 8.02%   |
| 2018    | 153       | 7.87%   |
| 2020    | 151       | 7.77%   |
| 2019    | 139       | 7.15%   |
| 2013    | 133       | 6.84%   |
| 2014    | 119       | 6.12%   |
| 2017    | 116       | 5.97%   |
| 2010    | 109       | 5.61%   |
| 2015    | 100       | 5.14%   |
| 2016    | 95        | 4.89%   |
| 2008    | 84        | 4.32%   |
| 2022    | 81        | 4.17%   |
| 2009    | 67        | 3.45%   |
| 2007    | 59        | 3.03%   |
| 2006    | 16        | 0.82%   |
| 2023    | 10        | 0.51%   |
| 2005    | 3         | 0.15%   |
| 2004    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 961       | 49.43%  |
| Desktop     | 871       | 44.8%   |
| Mini pc     | 33        | 1.7%    |
| All in one  | 32        | 1.65%   |
| Convertible | 28        | 1.44%   |
| Tablet      | 12        | 0.62%   |
| Server      | 7         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1944      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1938      | 99.69%  |
| Yes  | 6         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 575       | 29.55%  |
| 3.01-4.0        | 399       | 20.5%   |
| 16.01-24.0      | 360       | 18.5%   |
| 8.01-16.0       | 310       | 15.93%  |
| 32.01-64.0      | 133       | 6.83%   |
| 1.01-2.0        | 55        | 2.83%   |
| 2.01-3.0        | 40        | 2.06%   |
| 64.01-256.0     | 35        | 1.8%    |
| 24.01-32.0      | 32        | 1.64%   |
| 0.51-1.0        | 4         | 0.21%   |
| More than 256.0 | 3         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1231      | 63.06%  |
| 2.01-3.0  | 491       | 25.15%  |
| 0.51-1.0  | 115       | 5.89%   |
| 3.01-4.0  | 84        | 4.3%    |
| 4.01-8.0  | 19        | 0.97%   |
| 0.01-0.5  | 11        | 0.56%   |
| 8.01-16.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1116      | 57.32%  |
| 2      | 496       | 25.48%  |
| 3      | 161       | 8.27%   |
| 4      | 82        | 4.21%   |
| 5      | 36        | 1.85%   |
| 0      | 29        | 1.49%   |
| 6      | 14        | 0.72%   |
| 7      | 5         | 0.26%   |
| 8      | 4         | 0.21%   |
| 10     | 2         | 0.1%    |
| 13     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1084      | 55.76%  |
| Yes       | 860       | 44.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1725      | 88.73%  |
| No        | 219       | 11.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1401      | 72.07%  |
| No        | 543       | 27.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1062      | 54.63%  |
| No        | 882       | 45.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 257       | 13.22%  |
| Germany      | 198       | 10.19%  |
| Brazil       | 128       | 6.58%   |
| Russia       | 125       | 6.43%   |
| France       | 114       | 5.86%   |
| Poland       | 106       | 5.45%   |
| Italy        | 103       | 5.3%    |
| UK           | 78        | 4.01%   |
| Canada       | 62        | 3.19%   |
| Japan        | 59        | 3.03%   |
| Spain        | 55        | 2.83%   |
| Mexico       | 34        | 1.75%   |
| India        | 33        | 1.7%    |
| Australia    | 33        | 1.7%    |
| Netherlands  | 29        | 1.49%   |
| Finland      | 26        | 1.34%   |
| Czechia      | 26        | 1.34%   |
| Hungary      | 22        | 1.13%   |
| Argentina    | 21        | 1.08%   |
| Belgium      | 18        | 0.93%   |
| Indonesia    | 17        | 0.87%   |
| Austria      | 17        | 0.87%   |
| Switzerland  | 16        | 0.82%   |
| Denmark      | 14        | 0.72%   |
| Sweden       | 13        | 0.67%   |
| Romania      | 13        | 0.67%   |
| Portugal     | 13        | 0.67%   |
| Colombia     | 13        | 0.67%   |
| Venezuela    | 12        | 0.62%   |
| Greece       | 12        | 0.62%   |
| Bulgaria     | 12        | 0.62%   |
| Slovakia     | 10        | 0.51%   |
| Peru         | 10        | 0.51%   |
| Norway       | 10        | 0.51%   |
| China        | 10        | 0.51%   |
| Turkey       | 9         | 0.46%   |
| South Africa | 9         | 0.46%   |
| Malaysia     | 8         | 0.41%   |
| Chile        | 8         | 0.41%   |
| Belarus      | 8         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 27        | 1.38%   |
| Warsaw         | 19        | 0.97%   |
| Milan          | 18        | 0.92%   |
| St Petersburg  | 15        | 0.77%   |
| Hamburg        | 14        | 0.72%   |
| Berlin         | 14        | 0.72%   |
| Rio de Janeiro | 12        | 0.62%   |
| Montreal       | 12        | 0.62%   |
| Helsinki       | 12        | 0.62%   |
| Vienna         | 10        | 0.51%   |
| Rome           | 10        | 0.51%   |
| Paris          | 10        | 0.51%   |
| Munich         | 10        | 0.51%   |
| Brisbane       | 10        | 0.51%   |
| Mexico City    | 8         | 0.41%   |
| Sydney         | 7         | 0.36%   |
| Seattle        | 7         | 0.36%   |
| Sao Paulo      | 7         | 0.36%   |
| Prague         | 7         | 0.36%   |
| Lima           | 7         | 0.36%   |
| Kuala Lumpur   | 7         | 0.36%   |
| Curitiba       | 7         | 0.36%   |
| Budapest       | 7         | 0.36%   |
| Athens         | 7         | 0.36%   |
| Yokohama       | 6         | 0.31%   |
| Ufa            | 6         | 0.31%   |
| Santiago       | 6         | 0.31%   |
| Montevideo     | 6         | 0.31%   |
| Los Angeles    | 6         | 0.31%   |
| Krakow         | 6         | 0.31%   |
| Hexham         | 6         | 0.31%   |
| Freeport       | 6         | 0.31%   |
| Cologne        | 6         | 0.31%   |
| Bogotá        | 6         | 0.31%   |
| Bengaluru      | 6         | 0.31%   |
| Vantaa         | 5         | 0.26%   |
| Singapore      | 5         | 0.26%   |
| San José      | 5         | 0.26%   |
| Pescara        | 5         | 0.26%   |
| Montpellier    | 5         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 423       | 493    | 14.66%  |
| WDC                 | 415       | 511    | 14.38%  |
| Samsung Electronics | 333       | 409    | 11.54%  |
| Toshiba             | 199       | 208    | 6.9%    |
| Kingston            | 180       | 210    | 6.24%   |
| Crucial             | 148       | 164    | 5.13%   |
| SanDisk             | 107       | 118    | 3.71%   |
| Hitachi             | 107       | 114    | 3.71%   |
| Unknown             | 75        | 84     | 2.6%    |
| A-DATA Technology   | 52        | 56     | 1.8%    |
| HGST                | 51        | 55     | 1.77%   |
| Intel               | 49        | 50     | 1.7%    |
| SPCC                | 48        | 53     | 1.66%   |
| China               | 48        | 50     | 1.66%   |
| SK hynix            | 38        | 38     | 1.32%   |
| Micron Technology   | 35        | 35     | 1.21%   |
| PNY                 | 30        | 31     | 1.04%   |
| JMicron Technology  | 24        | 24     | 0.83%   |
| Patriot             | 23        | 23     | 0.8%    |
| Transcend           | 22        | 22     | 0.76%   |
| Netac               | 20        | 21     | 0.69%   |
| Phison              | 19        | 20     | 0.66%   |
| GOODRAM             | 18        | 19     | 0.62%   |
| Intenso             | 17        | 18     | 0.59%   |
| Maxtor              | 15        | 16     | 0.52%   |
| KIOXIA              | 15        | 15     | 0.52%   |
| KingSpec            | 14        | 14     | 0.49%   |
| Gigabyte Technology | 13        | 13     | 0.45%   |
| Team                | 12        | 12     | 0.42%   |
| Apacer              | 12        | 13     | 0.42%   |
| XPG                 | 11        | 13     | 0.38%   |
| Apple               | 11        | 12     | 0.38%   |
| Unknown             | 11        | 12     | 0.38%   |
| LITEON              | 10        | 10     | 0.35%   |
| Fujitsu             | 10        | 11     | 0.35%   |
| SABRENT             | 9         | 9      | 0.31%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.31%   |
| Silicon Motion      | 8         | 8      | 0.28%   |
| Corsair             | 8         | 8      | 0.28%   |
| Verbatim            | 7         | 7      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 34        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB    | 26        | 0.83%   |
| Toshiba DT01ACA100 1TB             | 25        | 0.8%    |
| Kingston SA400S37480G 480GB SSD    | 25        | 0.8%    |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.7%    |
| Crucial CT240BX500SSD1 240GB       | 21        | 0.67%   |
| Toshiba MQ01ABD100 1TB             | 20        | 0.64%   |
| Toshiba MQ01ABF050 500GB           | 19        | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB     | 19        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB     | 19        | 0.6%    |
| Unknown SD/MMC/MS PRO 512GB        | 16        | 0.51%   |
| Samsung SSD 860 EVO 500GB          | 16        | 0.51%   |
| Crucial CT480BX500SSD1 480GB       | 16        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB    | 15        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB     | 15        | 0.48%   |
| Kingston SA400S37120G 120GB SSD    | 15        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB        | 14        | 0.45%   |
| SPCC Solid State Disk 512GB        | 13        | 0.41%   |
| Samsung SSD 860 EVO 250GB          | 13        | 0.41%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.38%   |
| Toshiba DT01ACA050 500GB           | 12        | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 12        | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB     | 12        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB         | 12        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD   | 12        | 0.38%   |
| JMicron Generic 2TB                | 12        | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 11        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB           | 11        | 0.35%   |
| Seagate ST9500325AS 500GB          | 11        | 0.35%   |
| Seagate ST3500418AS 500GB          | 11        | 0.35%   |
| Unknown                            | 11        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 10        | 0.32%   |
| Toshiba HDWD110 1TB                | 10        | 0.32%   |
| Seagate ST1000LM048-2E7172 1TB     | 10        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 0.32%   |
| Samsung SSD 860 EVO 1TB            | 10        | 0.32%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.32%   |
| Crucial CT1000BX500SSD1 1TB        | 10        | 0.32%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 9         | 0.29%   |
| Seagate ST2000LM007-1R8174 2TB     | 9         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 412       | 478    | 34.86%  |
| WDC                 | 313       | 377    | 26.48%  |
| Toshiba             | 174       | 180    | 14.72%  |
| Hitachi             | 107       | 114    | 9.05%   |
| HGST                | 51        | 55     | 4.31%   |
| Samsung Electronics | 47        | 53     | 3.98%   |
| Unknown             | 16        | 16     | 1.35%   |
| Maxtor              | 14        | 15     | 1.18%   |
| Fujitsu             | 10        | 11     | 0.85%   |
| SABRENT             | 8         | 8      | 0.68%   |
| Apple               | 5         | 5      | 0.42%   |
| StoreJet            | 3         | 3      | 0.25%   |
| WD MediaMax         | 2         | 2      | 0.17%   |
| TO Exter            | 2         | 2      | 0.17%   |
| Intenso             | 2         | 2      | 0.17%   |
| External            | 2         | 2      | 0.17%   |
| ExcelStor           | 2         | 2      | 0.17%   |
| USB3.0              | 1         | 1      | 0.08%   |
| USB                 | 1         | 1      | 0.08%   |
| SSK                 | 1         | 1      | 0.08%   |
| SAGE                | 1         | 1      | 0.08%   |
| RSH-319             | 1         | 1      | 0.08%   |
| QUANTUM             | 1         | 1      | 0.08%   |
| MaxDigital          | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 166       | 192    | 14.86%  |
| Kingston            | 130       | 153    | 11.64%  |
| Crucial             | 121       | 126    | 10.83%  |
| SanDisk             | 81        | 88     | 7.25%   |
| WDC                 | 66        | 74     | 5.91%   |
| China               | 48        | 50     | 4.3%    |
| A-DATA Technology   | 42        | 45     | 3.76%   |
| SPCC                | 39        | 41     | 3.49%   |
| PNY                 | 25        | 26     | 2.24%   |
| Intel               | 23        | 23     | 2.06%   |
| Patriot             | 22        | 22     | 1.97%   |
| Micron Technology   | 19        | 19     | 1.7%    |
| Transcend           | 18        | 18     | 1.61%   |
| Netac               | 18        | 19     | 1.61%   |
| Toshiba             | 16        | 16     | 1.43%   |
| JMicron Technology  | 16        | 16     | 1.43%   |
| GOODRAM             | 16        | 17     | 1.43%   |
| Intenso             | 15        | 15     | 1.34%   |
| KingSpec            | 12        | 12     | 1.07%   |
| SK hynix            | 11        | 11     | 0.98%   |
| LITEON              | 10        | 10     | 0.9%    |
| Gigabyte Technology | 10        | 10     | 0.9%    |
| Apacer              | 9         | 9      | 0.81%   |
| Team                | 8         | 8      | 0.72%   |
| Verbatim            | 7         | 7      | 0.63%   |
| OCZ                 | 7         | 10     | 0.63%   |
| Seagate             | 6         | 6      | 0.54%   |
| Unknown             | 6         | 7      | 0.54%   |
| Teclast             | 5         | 5      | 0.45%   |
| KingFast            | 5         | 5      | 0.45%   |
| KingDian            | 5         | 5      | 0.45%   |
| XrayDisk            | 4         | 4      | 0.36%   |
| Mushkin             | 4         | 4      | 0.36%   |
| Lexar               | 4         | 4      | 0.36%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.36%   |
| Emtec               | 4         | 4      | 0.36%   |
| ASMT                | 4         | 4      | 0.36%   |
| Apple               | 4         | 4      | 0.36%   |
| Wibtek              | 3         | 3      | 0.27%   |
| ShiJi               | 3         | 3      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 989       | 1337   | 39.17%  |
| SSD     | 938       | 1200   | 37.15%  |
| NVMe    | 504       | 603    | 19.96%  |
| MMC     | 63        | 68     | 2.5%    |
| Unknown | 31        | 36     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1590      | 2388   | 68.62%  |
| NVMe | 502       | 599    | 21.67%  |
| SAS  | 162       | 189    | 6.99%   |
| MMC  | 63        | 68     | 2.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1205      | 1568   | 59.98%  |
| 0.51-1.0        | 567       | 679    | 28.22%  |
| 1.01-2.0        | 155       | 185    | 7.72%   |
| 2.01-3.0        | 30        | 33     | 1.49%   |
| 3.01-4.0        | 23        | 31     | 1.14%   |
| 4.01-10.0       | 21        | 32     | 1.05%   |
| 10.01-20.0      | 7         | 8      | 0.35%   |
| More than 100.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 642       | 32.97%  |
| 101-250        | 395       | 20.29%  |
| 251-500        | 318       | 16.33%  |
| 501-1000       | 175       | 8.99%   |
| 51-100         | 119       | 6.11%   |
| 21-50          | 109       | 5.6%    |
| Unknown        | 79        | 4.06%   |
| 1001-2000      | 63        | 3.24%   |
| 2001-3000      | 25        | 1.28%   |
| More than 3000 | 22        | 1.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1522      | 78.13%  |
| 21-50          | 135       | 6.93%   |
| Unknown        | 79        | 4.06%   |
| 101-250        | 59        | 3.03%   |
| 51-100         | 58        | 2.98%   |
| 251-500        | 43        | 2.21%   |
| 501-1000       | 33        | 1.69%   |
| 1001-2000      | 7         | 0.36%   |
| More than 3000 | 6         | 0.31%   |
| 2001-3000      | 6         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 14        | 14     | 2.68%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 7         | 7      | 1.34%   |
| Seagate ST9500325AS 500GB           | 7         | 7      | 1.34%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.15%   |
| Seagate ST3500418AS 500GB           | 6         | 6      | 1.15%   |
| Hitachi HDS721010CLA332 1TB         | 6         | 6      | 1.15%   |
| HGST HTS545050A7E380 500GB          | 6         | 6      | 1.15%   |
| HGST HTS541010A9E680 1TB            | 6         | 6      | 1.15%   |
| WDC WD5000AAKX-001CA0 500GB         | 5         | 5      | 0.96%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 0.96%   |
| Toshiba MQ01ABD050 500GB            | 5         | 5      | 0.96%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 0.96%   |
| Hitachi HTS723232A7A364 320GB       | 5         | 5      | 0.96%   |
| HGST HTS545050A7E680 500GB          | 5         | 6      | 0.96%   |
| Toshiba DT01ACA100 1TB              | 4         | 4      | 0.77%   |
| Seagate ST3320418AS 320GB           | 4         | 4      | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 4      | 0.77%   |
| Hitachi HTS547575A9E384 752GB       | 4         | 4      | 0.77%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.77%   |
| WDC WD10EALX-009BA0 1TB             | 3         | 3      | 0.57%   |
| Toshiba MQ04ABF100 1TB              | 3         | 3      | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 3      | 0.57%   |
| Seagate ST3500413AS 500GB           | 3         | 3      | 0.57%   |
| Seagate ST31000524AS 1TB            | 3         | 3      | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB      | 3         | 4      | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 4      | 0.57%   |
| Samsung Electronics HD103SI 1TB     | 3         | 3      | 0.57%   |
| Netac SSD 120GB                     | 3         | 3      | 0.57%   |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 3      | 0.57%   |
| HGST HTS725050A7E630 500GB          | 3         | 3      | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.38%   |
| WDC WD3200AAKS-61L9A0 320GB         | 2         | 2      | 0.38%   |
| WDC WD20EARX-00PASB0 2TB            | 2         | 2      | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB            | 2         | 2      | 0.38%   |
| WDC WD10EARS-00Y5B1 1TB             | 2         | 2      | 0.38%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 149    | 28.32%  |
| WDC                 | 110       | 122    | 21.48%  |
| Toshiba             | 47        | 47     | 9.18%   |
| Hitachi             | 47        | 48     | 9.18%   |
| Samsung Electronics | 30        | 32     | 5.86%   |
| HGST                | 28        | 30     | 5.47%   |
| Intel               | 14        | 14     | 2.73%   |
| Maxtor              | 9         | 10     | 1.76%   |
| Kingston            | 9         | 10     | 1.76%   |
| China               | 7         | 7      | 1.37%   |
| SK hynix            | 6         | 6      | 1.17%   |
| Fujitsu             | 6         | 7      | 1.17%   |
| SanDisk             | 5         | 5      | 0.98%   |
| Netac               | 4         | 4      | 0.78%   |
| KingSpec            | 4         | 4      | 0.78%   |
| Intenso             | 4         | 4      | 0.78%   |
| Crucial             | 4         | 4      | 0.78%   |
| A-DATA Technology   | 4         | 4      | 0.78%   |
| SPCC                | 3         | 3      | 0.59%   |
| LITEON              | 3         | 3      | 0.59%   |
| ExcelStor           | 2         | 2      | 0.39%   |
| Apple               | 2         | 2      | 0.39%   |
| WD MediaMax         | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| Teclast             | 1         | 1      | 0.2%    |
| Team                | 1         | 1      | 0.2%    |
| SATAFIRM            | 1         | 1      | 0.2%    |
| SAGE                | 1         | 1      | 0.2%    |
| RSH-319             | 1         | 1      | 0.2%    |
| QUANTUM             | 1         | 1      | 0.2%    |
| Plextor             | 1         | 1      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| Micron Technology   | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Indilinx            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fanxiang            | 1         | 1      | 0.2%    |
| BAITITON            | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 149    | 34.69%  |
| WDC                 | 103       | 114    | 24.64%  |
| Hitachi             | 47        | 48     | 11.24%  |
| Toshiba             | 46        | 46     | 11%     |
| HGST                | 28        | 30     | 6.7%    |
| Samsung Electronics | 26        | 27     | 6.22%   |
| Maxtor              | 9         | 10     | 2.15%   |
| Fujitsu             | 6         | 7      | 1.44%   |
| ExcelStor           | 2         | 2      | 0.48%   |
| Apple               | 2         | 2      | 0.48%   |
| WD MediaMax         | 1         | 1      | 0.24%   |
| SAGE                | 1         | 1      | 0.24%   |
| RSH-319             | 1         | 1      | 0.24%   |
| QUANTUM             | 1         | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 389       | 439    | 80.37%  |
| SSD  | 86        | 87     | 17.77%  |
| NVMe | 9         | 10     | 1.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800JD-00MSA1 80GB           | 1         | 1      | 7.69%   |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-00YZCA0 160GB      | 1         | 1      | 7.69%   |
| Toshiba MK3261GSYN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 7.69%   |
| Seagate ST9320423AS 320GB         | 1         | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 7.69%   |
| Samsung Electronics HM250HI 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 7.69%   |
| HGST HTS545050B7E660 500GB        | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 38.46%  |
| WDC                 | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Seagate             | 2         | 2      | 15.38%  |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1593      | 2451   | 69.62%  |
| Malfunc  | 471       | 536    | 20.59%  |
| Detected | 211       | 244    | 9.22%   |
| Failed   | 13        | 13     | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1353      | 56.26%  |
| AMD                                     | 415       | 17.26%  |
| Samsung Electronics                     | 146       | 6.07%   |
| SanDisk                                 | 78        | 3.24%   |
| Kingston Technology Company             | 56        | 2.33%   |
| Phison Electronics                      | 50        | 2.08%   |
| Micron/Crucial Technology               | 33        | 1.37%   |
| ASMedia Technology                      | 33        | 1.37%   |
| Nvidia                                  | 31        | 1.29%   |
| Silicon Motion                          | 30        | 1.25%   |
| SK hynix                                | 25        | 1.04%   |
| KIOXIA                                  | 20        | 0.83%   |
| ADATA Technology                        | 19        | 0.79%   |
| Micron Technology                       | 16        | 0.67%   |
| Marvell Technology Group                | 15        | 0.62%   |
| JMicron Technology                      | 13        | 0.54%   |
| Toshiba America Info Systems            | 11        | 0.46%   |
| VIA Technologies                        | 9         | 0.37%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.37%   |
| Union Memory (Shenzhen)                 | 6         | 0.25%   |
| Realtek Semiconductor                   | 6         | 0.25%   |
| Solid State Storage Technology          | 5         | 0.21%   |
| Shenzhen Longsys Electronics            | 3         | 0.12%   |
| Seagate Technology                      | 3         | 0.12%   |
| Broadcom / LSI                          | 3         | 0.12%   |
| Biwin Storage Technology                | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.08%   |
| Netac Technology                        | 2         | 0.08%   |
| Lenovo                                  | 2         | 0.08%   |
| Transcend                               | 1         | 0.04%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| Promise Technology                      | 1         | 0.04%   |
| LSI Logic / Symbios Logic               | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| Integrated Technology Express           | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 254       | 9.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 107       | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 96        | 3.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 93        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 70        | 2.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 55        | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                                  | 55        | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 54        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 52        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 52        | 1.85%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 51        | 1.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 50        | 1.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 49        | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 48        | 1.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 47        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 45        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 44        | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 42        | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 41        | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 39        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 36        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 33        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 33        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 33        | 1.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 32        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 31        | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 31        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 31        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 30        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 27        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 26        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26        | 0.92%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 25        | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 24        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 23        | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 23        | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 21        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 21        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1520      | 61.81%  |
| NVMe | 500       | 20.33%  |
| IDE  | 303       | 12.32%  |
| RAID | 130       | 5.29%   |
| SAS  | 5         | 0.2%    |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1451      | 74.64%  |
| AMD    | 493       | 25.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 16        | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 14        | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 0.67%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 13        | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.62%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 12        | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 12        | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.62%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 12        | 0.62%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 11        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.57%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 11        | 0.57%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 11        | 0.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 10        | 0.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 10        | 0.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 10        | 0.51%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.51%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 9         | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9         | 0.46%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 9         | 0.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 9         | 0.46%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 9         | 0.46%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 9         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 409       | 21.04%  |
| Intel Core i7           | 244       | 12.55%  |
| Intel Core i3           | 208       | 10.7%   |
| Intel Celeron           | 141       | 7.25%   |
| AMD Ryzen 5             | 132       | 6.79%   |
| Other                   | 119       | 6.12%   |
| Intel Core 2 Duo        | 107       | 5.5%    |
| Intel Pentium           | 68        | 3.5%    |
| AMD Ryzen 7             | 67        | 3.45%   |
| AMD Ryzen 3             | 37        | 1.9%    |
| Intel Pentium Dual-Core | 32        | 1.65%   |
| Intel Xeon              | 31        | 1.59%   |
| AMD FX                  | 28        | 1.44%   |
| AMD A8                  | 23        | 1.18%   |
| Intel Core 2 Quad       | 22        | 1.13%   |
| AMD A4                  | 18        | 0.93%   |
| Intel Pentium Dual      | 17        | 0.87%   |
| AMD Ryzen 9             | 16        | 0.82%   |
| AMD A6                  | 15        | 0.77%   |
| AMD Athlon              | 14        | 0.72%   |
| AMD A10                 | 14        | 0.72%   |
| Intel Core 2            | 13        | 0.67%   |
| AMD Athlon II X2        | 12        | 0.62%   |
| AMD Athlon 64 X2        | 12        | 0.62%   |
| Intel Atom              | 11        | 0.57%   |
| Intel Pentium Silver    | 10        | 0.51%   |
| Intel Genuine           | 8         | 0.41%   |
| Intel Core i9           | 8         | 0.41%   |
| Intel Pentium Gold      | 7         | 0.36%   |
| AMD E                   | 7         | 0.36%   |
| AMD Phenom II X6        | 6         | 0.31%   |
| AMD E1                  | 5         | 0.26%   |
| Intel Celeron Dual-Core | 4         | 0.21%   |
| AMD Turion 64 X2 Mobile | 4         | 0.21%   |
| AMD Ryzen 5 PRO         | 4         | 0.21%   |
| AMD Athlon X4           | 4         | 0.21%   |
| AMD A12                 | 4         | 0.21%   |
| Intel Pentium 4         | 3         | 0.15%   |
| AMD Sempron             | 3         | 0.15%   |
| AMD Ryzen 7 PRO         | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 948       | 48.77%  |
| 4      | 596       | 30.66%  |
| 6      | 178       | 9.16%   |
| 8      | 104       | 5.35%   |
| 1      | 56        | 2.88%   |
| 12     | 16        | 0.82%   |
| 14     | 14        | 0.72%   |
| 3      | 12        | 0.62%   |
| 16     | 9         | 0.46%   |
| 10     | 8         | 0.41%   |
| 24     | 3         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1937      | 99.64%  |
| 2      | 7         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1169      | 60.13%  |
| 1      | 761       | 39.15%  |
| 4      | 10        | 0.51%   |
| 8      | 3         | 0.15%   |
| 16     | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1944      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1464      | 75.27%  |
| 0x08108109 | 49        | 2.52%   |
| 0x0a50000c | 29        | 1.49%   |
| 0x0a50000d | 26        | 1.34%   |
| 0x08701021 | 25        | 1.29%   |
| 0x06001119 | 23        | 1.18%   |
| 0x08608103 | 17        | 0.87%   |
| 0x0800820d | 17        | 0.87%   |
| 0x06006705 | 16        | 0.82%   |
| 0x010000c8 | 16        | 0.82%   |
| 0x06003106 | 15        | 0.77%   |
| 0x08101016 | 14        | 0.72%   |
| 0x06000822 | 11        | 0.57%   |
| 0x08108102 | 10        | 0.51%   |
| 0x0600611a | 10        | 0.51%   |
| 0x0a20120a | 9         | 0.46%   |
| 0x0a201016 | 9         | 0.46%   |
| 0x08200103 | 9         | 0.46%   |
| 0x0500010d | 9         | 0.46%   |
| 0x08600106 | 8         | 0.41%   |
| 0x0700010b | 7         | 0.36%   |
| 0x05000101 | 7         | 0.36%   |
| 0x010000b6 | 7         | 0.36%   |
| 0x0a201025 | 6         | 0.31%   |
| 0x08600103 | 6         | 0.31%   |
| 0x07030105 | 6         | 0.31%   |
| 0x0600081c | 6         | 0.31%   |
| 0x010000bf | 6         | 0.31%   |
| 0x08600104 | 5         | 0.26%   |
| 0x0810100b | 5         | 0.26%   |
| 0x206a7    | 4         | 0.21%   |
| 0x08608102 | 4         | 0.21%   |
| 0x03000027 | 4         | 0.21%   |
| 0x08701030 | 3         | 0.15%   |
| 0x08701013 | 3         | 0.15%   |
| 0x08600109 | 3         | 0.15%   |
| 0x0800820b | 3         | 0.15%   |
| 0x02000057 | 3         | 0.15%   |
| 0x02000032 | 3         | 0.15%   |
| 0x01000095 | 3         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 225       | 11.57%  |
| Haswell          | 161       | 8.28%   |
| SandyBridge      | 157       | 8.08%   |
| IvyBridge        | 156       | 8.02%   |
| Penryn           | 135       | 6.94%   |
| Skylake          | 124       | 6.38%   |
| Zen 3            | 84        | 4.32%   |
| Zen+             | 80        | 4.12%   |
| Core             | 78        | 4.01%   |
| Westmere         | 58        | 2.98%   |
| Zen 2            | 56        | 2.88%   |
| Silvermont       | 56        | 2.88%   |
| Piledriver       | 51        | 2.62%   |
| TigerLake        | 47        | 2.42%   |
| Goldmont plus    | 45        | 2.31%   |
| K10              | 43        | 2.21%   |
| Broadwell        | 42        | 2.16%   |
| Icelake          | 38        | 1.95%   |
| CometLake        | 38        | 1.95%   |
| Zen              | 37        | 1.9%    |
| Alderlake Hybrid | 36        | 1.85%   |
| Excavator        | 30        | 1.54%   |
| Unknown          | 28        | 1.44%   |
| K8 Hammer        | 21        | 1.08%   |
| Goldmont         | 19        | 0.98%   |
| Bobcat           | 17        | 0.87%   |
| Steamroller      | 16        | 0.82%   |
| Nehalem          | 12        | 0.62%   |
| Tremont          | 9         | 0.46%   |
| Jaguar           | 9         | 0.46%   |
| Bonnell          | 8         | 0.41%   |
| Puma             | 7         | 0.36%   |
| K8 & K10 hybrid  | 6         | 0.31%   |
| K10 Llano        | 6         | 0.31%   |
| NetBurst         | 5         | 0.26%   |
| Bulldozer        | 3         | 0.15%   |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1116      | 51.36%  |
| AMD                                          | 532       | 24.48%  |
| Nvidia                                       | 517       | 23.79%  |
| Silicon Integrated Systems [SiS]             | 2         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.05%   |
| S3 Graphics                                  | 1         | 0.05%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.05%   |
| Matrox Electronics Systems                   | 1         | 0.05%   |
| ATI Technologies                             | 1         | 0.05%   |
| ASPEED Technology                            | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 120       | 5.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 79        | 3.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 65        | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 52        | 2.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 2.2%    |
| Intel HD Graphics 530                                                                    | 49        | 2.2%    |
| Intel HD Graphics 620                                                                    | 48        | 2.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 43        | 1.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 40        | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 32        | 1.44%   |
| Intel UHD Graphics 620                                                                   | 32        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 30        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 30        | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 0.99%   |
| AMD Lucienne                                                                             | 21        | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 20        | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 19        | 0.85%   |
| Intel HD Graphics 630                                                                    | 19        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 0.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 16        | 0.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 16        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.63%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 13        | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.58%   |
| Intel HD Graphics 500                                                                    | 12        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 812       | 41.75%  |
| 1 x AMD                                  | 439       | 22.57%  |
| 1 x Nvidia                               | 330       | 16.97%  |
| Intel + Nvidia                           | 156       | 8.02%   |
| 2 x Intel                                | 106       | 5.45%   |
| Intel + AMD                              | 40        | 2.06%   |
| 2 x AMD                                  | 26        | 1.34%   |
| AMD + Nvidia                             | 25        | 1.29%   |
| 2 x Nvidia                               | 2         | 0.1%    |
| 1 x SiS                                  | 2         | 0.1%    |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.1%    |
| 1 x S3 Graphics                          | 1         | 0.05%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.05%   |
| Nvidia + XGI                             | 1         | 0.05%   |
| 1 x ASPEED                               | 1         | 0.05%   |
| AMD + Matrox                             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1855      | 95.32%  |
| Proprietary | 53        | 2.72%   |
| Unknown     | 38        | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 964       | 49.56%  |
| 1.01-2.0   | 280       | 14.4%   |
| 0.01-0.5   | 251       | 12.9%   |
| 0.51-1.0   | 166       | 8.53%   |
| 3.01-4.0   | 129       | 6.63%   |
| 7.01-8.0   | 74        | 3.8%    |
| 5.01-6.0   | 49        | 2.52%   |
| 8.01-16.0  | 21        | 1.08%   |
| 2.01-3.0   | 7         | 0.36%   |
| 16.01-24.0 | 3         | 0.15%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 253       | 12.93%  |
| AU Optronics            | 230       | 11.75%  |
| LG Display              | 165       | 8.43%   |
| BOE                     | 157       | 8.02%   |
| Chimei Innolux          | 145       | 7.41%   |
| Goldstar                | 109       | 5.57%   |
| Hewlett-Packard         | 90        | 4.6%    |
| Dell                    | 83        | 4.24%   |
| Acer                    | 73        | 3.73%   |
| AOC                     | 67        | 3.42%   |
| Philips                 | 50        | 2.55%   |
| BenQ                    | 48        | 2.45%   |
| Lenovo                  | 43        | 2.2%    |
| Ancor Communications    | 29        | 1.48%   |
| Sharp                   | 27        | 1.38%   |
| Apple                   | 26        | 1.33%   |
| ViewSonic               | 25        | 1.28%   |
| LG Philips              | 24        | 1.23%   |
| ASUSTek Computer        | 24        | 1.23%   |
| Chi Mei Optoelectronics | 22        | 1.12%   |
| Iiyama                  | 21        | 1.07%   |
| PANDA                   | 14        | 0.72%   |
| Sony                    | 12        | 0.61%   |
| Unknown                 | 11        | 0.56%   |
| Sceptre Tech            | 10        | 0.51%   |
| InfoVision              | 9         | 0.46%   |
| NEC Computers           | 8         | 0.41%   |
| HannStar                | 8         | 0.41%   |
| Unknown                 | 8         | 0.41%   |
| MSI                     | 7         | 0.36%   |
| Hitachi                 | 7         | 0.36%   |
| Panasonic               | 6         | 0.31%   |
| HKC                     | 6         | 0.31%   |
| Fujitsu Siemens         | 6         | 0.31%   |
| Unknown (XXX)           | 4         | 0.2%    |
| Seiki                   | 4         | 0.2%    |
| LG Electronics          | 4         | 0.2%    |
| Insignia                | 4         | 0.2%    |
| Eizo                    | 4         | 0.2%    |
| CSO                     | 4         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 11        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 10        | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 10        | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 10        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.4%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 8         | 0.4%    |
| Unknown                                                               | 8         | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.35%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 7         | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 6         | 0.3%    |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 6         | 0.3%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.3%    |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 6         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 5         | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 5         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.25%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 5         | 0.25%   |
| Seiki SE20HY SEK0CA8 1360x768 440x250mm 19.9-inch                     | 4         | 0.2%    |
| Samsung Electronics SyncMaster SAM0527 1600x900 443x250mm 20.0-inch   | 4         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 4         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 4         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4         | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.2%    |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 4         | 0.2%    |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 863       | 44.78%  |
| 1366x768 (WXGA)    | 418       | 21.69%  |
| 3840x2160 (4K)     | 93        | 4.83%   |
| 1600x900 (HD+)     | 91        | 4.72%   |
| 2560x1440 (QHD)    | 68        | 3.53%   |
| 1680x1050 (WSXGA+) | 65        | 3.37%   |
| 1280x1024 (SXGA)   | 54        | 2.8%    |
| 1280x800 (WXGA)    | 52        | 2.7%    |
| 1440x900 (WXGA+)   | 48        | 2.49%   |
| 1920x1200 (WUXGA)  | 39        | 2.02%   |
| 1360x768           | 27        | 1.4%    |
| 2560x1600          | 17        | 0.88%   |
| 3440x1440          | 14        | 0.73%   |
| 2560x1080          | 8         | 0.42%   |
| 2288x1287          | 6         | 0.31%   |
| 1920x540           | 6         | 0.31%   |
| 1024x768 (XGA)     | 6         | 0.31%   |
| Unknown            | 5         | 0.26%   |
| 3840x2400          | 4         | 0.21%   |
| 2880x1800          | 4         | 0.21%   |
| 2736x1824          | 4         | 0.21%   |
| 2160x1440          | 4         | 0.21%   |
| 1920x1280          | 4         | 0.21%   |
| 1600x1200          | 3         | 0.16%   |
| 1280x960           | 3         | 0.16%   |
| 3200x1800 (QHD+)   | 2         | 0.1%    |
| 1280x720 (HD)      | 2         | 0.1%    |
| 1024x600           | 2         | 0.1%    |
| 8320x1440          | 1         | 0.05%   |
| 800x1280           | 1         | 0.05%   |
| 6000x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5120x1440          | 1         | 0.05%   |
| 4480x2023          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |
| 2880x1920          | 1         | 0.05%   |
| 2240x1400          | 1         | 0.05%   |
| 2160x1350          | 1         | 0.05%   |
| 1800x1200          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 492       | 25.1%   |
| 13      | 145       | 7.4%    |
| 23      | 143       | 7.3%    |
| 27      | 141       | 7.19%   |
| 21      | 136       | 6.94%   |
| 14      | 129       | 6.58%   |
| 24      | 128       | 6.53%   |
| 17      | 115       | 5.87%   |
| 18      | 57        | 2.91%   |
| 19      | 56        | 2.86%   |
| 22      | 50        | 2.55%   |
| 31      | 48        | 2.45%   |
| Unknown | 48        | 2.45%   |
| 12      | 41        | 2.09%   |
| 20      | 35        | 1.79%   |
| 11      | 28        | 1.43%   |
| 34      | 21        | 1.07%   |
| 16      | 18        | 0.92%   |
| 54      | 17        | 0.87%   |
| 84      | 14        | 0.71%   |
| 72      | 9         | 0.46%   |
| 40      | 9         | 0.46%   |
| 32      | 8         | 0.41%   |
| 26      | 7         | 0.36%   |
| 25      | 7         | 0.36%   |
| 142     | 6         | 0.31%   |
| 10      | 6         | 0.31%   |
| 39      | 5         | 0.26%   |
| 52      | 4         | 0.2%    |
| 48      | 4         | 0.2%    |
| 46      | 4         | 0.2%    |
| 65      | 3         | 0.15%   |
| 37      | 3         | 0.15%   |
| 36      | 3         | 0.15%   |
| 29      | 3         | 0.15%   |
| 60      | 2         | 0.1%    |
| 35      | 2         | 0.1%    |
| 28      | 2         | 0.1%    |
| 74      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 733       | 37.8%   |
| 501-600        | 384       | 19.8%   |
| 401-500        | 305       | 15.73%  |
| 351-400        | 142       | 7.32%   |
| 201-300        | 132       | 6.81%   |
| 601-700        | 69        | 3.56%   |
| Unknown        | 48        | 2.48%   |
| 1001-1500      | 39        | 2.01%   |
| 701-800        | 34        | 1.75%   |
| 1501-2000      | 24        | 1.24%   |
| 801-900        | 19        | 0.98%   |
| More than 2000 | 6         | 0.31%   |
| 901-1000       | 2         | 0.1%    |
| 101-200        | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1468      | 78.76%  |
| 16/10   | 233       | 12.5%   |
| 5/4     | 54        | 2.9%    |
| Unknown | 31        | 1.66%   |
| 3/2     | 26        | 1.39%   |
| 21/9    | 22        | 1.18%   |
| 4/3     | 18        | 0.97%   |
| 1.00    | 6         | 0.32%   |
| 32/9    | 1         | 0.05%   |
| 2.12    | 1         | 0.05%   |
| 2.00    | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |
| 0.63    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 494       | 25.32%  |
| 201-250        | 364       | 18.66%  |
| 81-90          | 224       | 11.48%  |
| 301-350        | 143       | 7.33%   |
| 151-200        | 142       | 7.28%   |
| 351-500        | 81        | 4.15%   |
| 141-150        | 73        | 3.74%   |
| 121-130        | 68        | 3.49%   |
| More than 1000 | 64        | 3.28%   |
| 71-80          | 56        | 2.87%   |
| 251-300        | 53        | 2.72%   |
| Unknown        | 48        | 2.46%   |
| 61-70          | 32        | 1.64%   |
| 51-60          | 31        | 1.59%   |
| 501-1000       | 29        | 1.49%   |
| 131-140        | 27        | 1.38%   |
| 111-120        | 13        | 0.67%   |
| 91-100         | 4         | 0.21%   |
| 41-50          | 3         | 0.15%   |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 719       | 37.45%  |
| 101-120       | 569       | 29.64%  |
| 121-160       | 427       | 22.24%  |
| 161-240       | 77        | 4.01%   |
| 1-50          | 60        | 3.13%   |
| Unknown       | 48        | 2.5%    |
| More than 240 | 20        | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1762      | 90.54%  |
| 2     | 157       | 8.07%   |
| 0     | 17        | 0.87%   |
| 3     | 9         | 0.46%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1140      | 40.63%  |
| Intel                             | 833       | 29.69%  |
| Qualcomm Atheros                  | 345       | 12.3%   |
| Broadcom                          | 133       | 4.74%   |
| MediaTek                          | 40        | 1.43%   |
| Ralink Technology                 | 36        | 1.28%   |
| Broadcom Limited                  | 32        | 1.14%   |
| Ralink                            | 27        | 0.96%   |
| TP-Link                           | 26        | 0.93%   |
| Marvell Technology Group          | 26        | 0.93%   |
| Nvidia                            | 23        | 0.82%   |
| Qualcomm Atheros Communications   | 18        | 0.64%   |
| ASUSTek Computer                  | 10        | 0.36%   |
| NetGear                           | 8         | 0.29%   |
| D-Link                            | 8         | 0.29%   |
| ASIX Electronics                  | 8         | 0.29%   |
| JMicron Technology                | 7         | 0.25%   |
| Dell                              | 7         | 0.25%   |
| Sierra Wireless                   | 6         | 0.21%   |
| Microsoft                         | 6         | 0.21%   |
| Samsung Electronics               | 5         | 0.18%   |
| Huawei Technologies               | 4         | 0.14%   |
| Ericsson Business Mobile Networks | 4         | 0.14%   |
| Aquantia                          | 4         | 0.14%   |
| Xiaomi                            | 3         | 0.11%   |
| T & A Mobile Phones               | 3         | 0.11%   |
| Linksys                           | 3         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| Sigma Sport                       | 2         | 0.07%   |
| Qualcomm                          | 2         | 0.07%   |
| OPPO Electronics                  | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |
| IMC Networks                      | 2         | 0.07%   |
| ICS Advent                        | 2         | 0.07%   |
| Gemtek                            | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Attansic Technology               | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 800       | 24.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 138       | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 2.23%   |
| Intel Wireless 7265                                               | 59        | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 57        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 49        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 47        | 1.43%   |
| Intel Wi-Fi 6 AX200                                               | 43        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 41        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 40        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 39        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 1.19%   |
| Intel Wireless 3165                                               | 38        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 32        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 25        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.76%   |
| Intel Wireless 8260                                               | 24        | 0.73%   |
| Intel Wireless 7260                                               | 23        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 22        | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 21        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 20        | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 19        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 19        | 0.58%   |
| Intel Wireless 3160                                               | 18        | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 18        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 17        | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 17        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 17        | 0.52%   |
| Intel WiFi Link 5100                                              | 16        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 620       | 42.67%  |
| Realtek Semiconductor           | 296       | 20.37%  |
| Qualcomm Atheros                | 257       | 17.69%  |
| Broadcom                        | 77        | 5.3%    |
| Ralink Technology               | 36        | 2.48%   |
| MediaTek                        | 35        | 2.41%   |
| Ralink                          | 27        | 1.86%   |
| Qualcomm Atheros Communications | 18        | 1.24%   |
| TP-Link                         | 17        | 1.17%   |
| Broadcom Limited                | 10        | 0.69%   |
| ASUSTek Computer                | 9         | 0.62%   |
| D-Link                          | 8         | 0.55%   |
| NetGear                         | 7         | 0.48%   |
| Sierra Wireless                 | 6         | 0.41%   |
| Microsoft                       | 5         | 0.34%   |
| Dell                            | 4         | 0.28%   |
| Marvell Technology Group        | 3         | 0.21%   |
| Linksys                         | 3         | 0.21%   |
| IMC Networks                    | 2         | 0.14%   |
| Gemtek                          | 2         | 0.14%   |
| D-Link System                   | 2         | 0.14%   |
| ZyDAS                           | 1         | 0.07%   |
| Wilocity                        | 1         | 0.07%   |
| VIA Technologies                | 1         | 0.07%   |
| Qualcomm                        | 1         | 0.07%   |
| PLANEX                          | 1         | 0.07%   |
| BUFFALO                         | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| AVM                             | 1         | 0.07%   |
| Arduino SA                      | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 59        | 4.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 57        | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 49        | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 47        | 3.22%   |
| Intel Wi-Fi 6 AX200                                                     | 43        | 2.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 39        | 2.67%   |
| Intel Wireless 3165                                                     | 38        | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.33%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 2.26%   |
| Intel Wireless 8265 / 8275                                              | 32        | 2.19%   |
| Intel Wireless 8260                                                     | 24        | 1.64%   |
| Intel Wireless 7260                                                     | 23        | 1.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 22        | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 22        | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 21        | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 21        | 1.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 20        | 1.37%   |
| Intel Wireless 3160                                                     | 18        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 17        | 1.17%   |
| Qualcomm Atheros AR9271 802.11n                                         | 17        | 1.17%   |
| Intel WiFi Link 5100                                                    | 16        | 1.1%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 16        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 15        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 1.03%   |
| Intel Centrino Ultimate-N 6300                                          | 14        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.89%   |
| Realtek 802.11ac NIC                                                    | 13        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 12        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1021      | 57.55%  |
| Intel                            | 417       | 23.51%  |
| Qualcomm Atheros                 | 122       | 6.88%   |
| Broadcom                         | 79        | 4.45%   |
| Nvidia                           | 23        | 1.3%    |
| Marvell Technology Group         | 23        | 1.3%    |
| Broadcom Limited                 | 23        | 1.3%    |
| TP-Link                          | 9         | 0.51%   |
| ASIX Electronics                 | 8         | 0.45%   |
| JMicron Technology               | 7         | 0.39%   |
| MediaTek                         | 5         | 0.28%   |
| Samsung Electronics              | 4         | 0.23%   |
| Aquantia                         | 4         | 0.23%   |
| Xiaomi                           | 3         | 0.17%   |
| Huawei Technologies              | 3         | 0.17%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| OPPO Electronics                 | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| ICS Advent                       | 2         | 0.11%   |
| Attansic Technology              | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.06%   |
| Qualcomm                         | 1         | 0.06%   |
| NetGear                          | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| Microsoft                        | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| Insyde Software                  | 1         | 0.06%   |
| Edimax Technology                | 1         | 0.06%   |
| DisplayLink                      | 1         | 0.06%   |
| ASUSTek Computer                 | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| 3Com                             | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 800       | 44.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 138       | 7.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 4.05%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 2.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1.66%   |
| Intel I211 Gigabit Network Connection                             | 25        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.39%   |
| Intel Ethernet Controller I225-V                                  | 19        | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 19        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1%      |
| Intel 82567LM Gigabit Network Connection                          | 17        | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 8         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 7         | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.39%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.39%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.39%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.39%   |
| Intel 82566MM Gigabit Network Connection                          | 7         | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.39%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 6         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1725      | 54.85%  |
| WiFi     | 1401      | 44.55%  |
| Modem    | 15        | 0.48%   |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 992       | 51.75%  |
| WiFi     | 924       | 48.2%   |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1004      | 51.65%  |
| 1     | 879       | 45.22%  |
| 3     | 29        | 1.49%   |
| 0     | 27        | 1.39%   |
| 4     | 4         | 0.21%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1309      | 67.23%  |
| Yes  | 638       | 32.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 468       | 43.94%  |
| Realtek Semiconductor           | 128       | 12.02%  |
| Qualcomm Atheros Communications | 83        | 7.79%   |
| Cambridge Silicon Radio         | 69        | 6.48%   |
| IMC Networks                    | 57        | 5.35%   |
| Broadcom                        | 56        | 5.26%   |
| Lite-On Technology              | 42        | 3.94%   |
| Apple                           | 27        | 2.54%   |
| Foxconn / Hon Hai               | 26        | 2.44%   |
| ASUSTek Computer                | 21        | 1.97%   |
| Toshiba                         | 18        | 1.69%   |
| Hewlett-Packard                 | 17        | 1.6%    |
| MediaTek                        | 12        | 1.13%   |
| Dell                            | 12        | 1.13%   |
| Realtek                         | 6         | 0.56%   |
| Ralink                          | 5         | 0.47%   |
| TP-Link                         | 3         | 0.28%   |
| Marvell Semiconductor           | 3         | 0.28%   |
| Chicony Electronics             | 2         | 0.19%   |
| Belkin Components               | 2         | 0.19%   |
| Qcom                            | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Actions                         | 1         | 0.09%   |
| Unknown                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 199       | 18.67%  |
| Realtek Bluetooth Radio                             | 85        | 7.97%   |
| Intel Bluetooth Device                              | 80        | 7.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 69        | 6.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 5.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 42        | 3.94%   |
| Intel AX200 Bluetooth                               | 40        | 3.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 3.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 2.81%   |
| Intel AX210 Bluetooth                               | 22        | 2.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 1.78%   |
| IMC Networks Bluetooth Device                       | 16        | 1.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 1.31%   |
| MediaTek Wireless_Device                            | 12        | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.13%   |
| Apple Bluetooth Host Controller                     | 12        | 1.13%   |
| IMC Networks Wireless_Device                        | 11        | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 0.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.94%   |
| ASUS Bluetooth Device                               | 10        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.75%   |
| Lite-On Bluetooth Device                            | 7         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.66%   |
| Realtek Bluetooth Radio                             | 6         | 0.56%   |
| Toshiba Bluetooth Device                            | 5         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.47%   |
| IMC Networks BCM20702A0                             | 5         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.38%   |
| Lite-On Wireless_Device                             | 4         | 0.38%   |
| IMC Networks Bluetooth                              | 4         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1423      | 54.96%  |
| AMD                                          | 572       | 22.09%  |
| Nvidia                                       | 400       | 15.45%  |
| C-Media Electronics                          | 35        | 1.35%   |
| Creative Labs                                | 24        | 0.93%   |
| Generalplus Technology                       | 18        | 0.7%    |
| Logitech                                     | 9         | 0.35%   |
| Texas Instruments                            | 8         | 0.31%   |
| Creative Technology                          | 7         | 0.27%   |
| Micro Star International                     | 5         | 0.19%   |
| JMTek                                        | 5         | 0.19%   |
| Tenx Technology                              | 4         | 0.15%   |
| ASUSTek Computer                             | 4         | 0.15%   |
| VIA Technologies                             | 3         | 0.12%   |
| SteelSeries ApS                              | 3         | 0.12%   |
| KTMicro                                      | 3         | 0.12%   |
| Hewlett-Packard                              | 3         | 0.12%   |
| GN Netcom                                    | 3         | 0.12%   |
| FiiO Electronics Technology                  | 3         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.08%   |
| Schiit Audio                                 | 2         | 0.08%   |
| Samson Technologies                          | 2         | 0.08%   |
| ROCCAT                                       | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| PreSonus Audio Electronics                   | 2         | 0.08%   |
| No brand                                     | 2         | 0.08%   |
| Native Instruments                           | 2         | 0.08%   |
| Kingston Technology                          | 2         | 0.08%   |
| Focusrite-Novation                           | 2         | 0.08%   |
| DSEA A/S                                     | 2         | 0.08%   |
| Dell                                         | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| Yamaha                                       | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Xilinx                                       | 1         | 0.04%   |
| USB-Speaker                                  | 1         | 0.04%   |
| THX                                          | 1         | 0.04%   |
| Tdlasunnic                                   | 1         | 0.04%   |
| Sterling                                     | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 191       | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 156       | 5.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 147       | 4.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 135       | 4.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 106       | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 94        | 3.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 82        | 2.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 80        | 2.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 76        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 73        | 2.36%   |
| AMD FCH Azalia Controller                                                                         | 73        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 68        | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 63        | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 61        | 1.97%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 57        | 1.84%   |
| Intel 200 Series PCH HD Audio                                                                     | 51        | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 46        | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 45        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 43        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 38        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 1.1%    |
| Intel 8 Series HD Audio Controller                                                                | 34        | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33        | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 30        | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 29        | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 29        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 29        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 25        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 23        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 22        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 21        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 447       | 19.18%  |
| SK hynix                                         | 375       | 16.09%  |
| Kingston                                         | 308       | 13.22%  |
| Unknown                                          | 243       | 10.43%  |
| Micron Technology                                | 210       | 9.01%   |
| Crucial                                          | 127       | 5.45%   |
| Corsair                                          | 91        | 3.91%   |
| G.Skill                                          | 63        | 2.7%    |
| Ramaxel Technology                               | 50        | 2.15%   |
| A-DATA Technology                                | 48        | 2.06%   |
| Nanya Technology                                 | 46        | 1.97%   |
| Elpida                                           | 39        | 1.67%   |
| Unknown (ABCD)                                   | 36        | 1.55%   |
| Unknown                                          | 34        | 1.46%   |
| Team                                             | 26        | 1.12%   |
| Patriot                                          | 13        | 0.56%   |
| Transcend                                        | 12        | 0.52%   |
| Smart                                            | 12        | 0.52%   |
| GOODRAM                                          | 11        | 0.47%   |
| Apacer                                           | 9         | 0.39%   |
| Multilaser                                       | 8         | 0.34%   |
| Qimonda                                          | 6         | 0.26%   |
| Avant                                            | 6         | 0.26%   |
| AMD                                              | 6         | 0.26%   |
| Unifosa                                          | 5         | 0.21%   |
| Teikon                                           | 4         | 0.17%   |
| Silicon Power                                    | 4         | 0.17%   |
| Innodisk                                         | 4         | 0.17%   |
| Hikvision                                        | 4         | 0.17%   |
| Wilk                                             | 3         | 0.13%   |
| Toshiba                                          | 3         | 0.13%   |
| Timetec                                          | 3         | 0.13%   |
| Kllisre                                          | 3         | 0.13%   |
| GeIL                                             | 3         | 0.13%   |
| ASint Technology                                 | 3         | 0.13%   |
| 48spaces                                         | 3         | 0.13%   |
| Walton Chaintech                                 | 2         | 0.09%   |
| Unknown (0x48594D503132355336344350382D53362020) | 2         | 0.09%   |
| Sesame                                           | 2         | 0.09%   |
| PUSKILL                                          | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 34        | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 26        | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 20        | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 20        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 16        | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 14        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 12        | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 12        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.47%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 12        | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 10        | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 10        | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 10        | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 10        | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 10        | 0.39%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 10        | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 9         | 0.36%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 9         | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 9         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.36%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 9         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 9         | 0.36%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.36%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 8         | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 8         | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 771       | 38.94%  |
| DDR3    | 761       | 38.43%  |
| DDR2    | 150       | 7.58%   |
| SDRAM   | 108       | 5.45%   |
| LPDDR4  | 69        | 3.48%   |
| Unknown | 66        | 3.33%   |
| DDR5    | 14        | 0.71%   |
| LPDDR3  | 12        | 0.61%   |
| DDR     | 11        | 0.56%   |
| LPDDR5  | 10        | 0.51%   |
| DRAM    | 8         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1031      | 53.03%  |
| DIMM         | 820       | 42.18%  |
| Row Of Chips | 78        | 4.01%   |
| Unknown      | 8         | 0.41%   |
| RIMM         | 4         | 0.21%   |
| Chip         | 3         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 751       | 34.09%  |
| 4096  | 714       | 32.41%  |
| 2048  | 383       | 17.39%  |
| 16384 | 184       | 8.35%   |
| 1024  | 93        | 4.22%   |
| 32768 | 66        | 3%      |
| 512   | 10        | 0.45%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 475       | 21.66%  |
| 3200    | 272       | 12.4%   |
| 2667    | 224       | 10.21%  |
| 1333    | 199       | 9.07%   |
| 2400    | 164       | 7.48%   |
| 1334    | 92        | 4.2%    |
| 667     | 92        | 4.2%    |
| 2133    | 87        | 3.97%   |
| 800     | 72        | 3.28%   |
| Unknown | 56        | 2.55%   |
| 3600    | 43        | 1.96%   |
| 1867    | 34        | 1.55%   |
| 1067    | 26        | 1.19%   |
| 2933    | 24        | 1.09%   |
| 4199    | 22        | 1%      |
| 3266    | 22        | 1%      |
| 2048    | 22        | 1%      |
| 1866    | 21        | 0.96%   |
| 1066    | 19        | 0.87%   |
| 3000    | 17        | 0.78%   |
| 3733    | 16        | 0.73%   |
| 4267    | 15        | 0.68%   |
| 2666    | 14        | 0.64%   |
| 1800    | 14        | 0.64%   |
| 533     | 13        | 0.59%   |
| 6400    | 10        | 0.46%   |
| 3800    | 8         | 0.36%   |
| 3400    | 8         | 0.36%   |
| 4800    | 7         | 0.32%   |
| 3666    | 6         | 0.27%   |
| 975     | 6         | 0.27%   |
| 4266    | 5         | 0.23%   |
| 3533    | 5         | 0.23%   |
| 3466    | 5         | 0.23%   |
| 1639    | 5         | 0.23%   |
| 1648    | 4         | 0.18%   |
| 400     | 4         | 0.18%   |
| 49926   | 3         | 0.14%   |
| 6000    | 3         | 0.14%   |
| 3866    | 3         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 33.33%  |
| Brother Industries  | 15        | 22.73%  |
| Canon               | 13        | 19.7%   |
| Seiko Epson         | 8         | 12.12%  |
| Samsung Electronics | 5         | 7.58%   |
| Xerox               | 1         | 1.52%   |
| Prolific Technology | 1         | 1.52%   |
| Philips (or NXP)    | 1         | 1.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP DeskJet 2600 series              | 3         | 4.48%   |
| Brother HL-L2390DW                  | 3         | 4.48%   |
| HP OfficeJet 3830 series            | 2         | 2.99%   |
| HP Laser 107a                       | 2         | 2.99%   |
| Canon TS5300 series                 | 2         | 2.99%   |
| Canon CanoScan LiDE 300             | 2         | 2.99%   |
| Xerox WorkCentre 6025               | 1         | 1.49%   |
| Seiko Epson XP-7100 Series          | 1         | 1.49%   |
| Seiko Epson Printer                 | 1         | 1.49%   |
| Seiko Epson L6270 Series            | 1         | 1.49%   |
| Seiko Epson L6160 Series            | 1         | 1.49%   |
| Seiko Epson L365 Series             | 1         | 1.49%   |
| Seiko Epson L3150 Series            | 1         | 1.49%   |
| Seiko Epson L3110 Series            | 1         | 1.49%   |
| Seiko Epson L120 Series             | 1         | 1.49%   |
| Samsung SCX-3200 Series             | 1         | 1.49%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 1.49%   |
| Samsung ML-1710 Printer             | 1         | 1.49%   |
| Samsung M267x 287x Series           | 1         | 1.49%   |
| Samsung M2070 Series                | 1         | 1.49%   |
| Prolific PL2305 Parallel Port       | 1         | 1.49%   |
| Philips (or NXP) USB Printer        | 1         | 1.49%   |
| HP OfficeJet 6950                   | 1         | 1.49%   |
| HP Officejet 4500 G510g-m           | 1         | 1.49%   |
| HP LaserJet P1005                   | 1         | 1.49%   |
| HP LaserJet M101-M106               | 1         | 1.49%   |
| HP ENVY 5000 series                 | 1         | 1.49%   |
| HP Deskjet F4500 series             | 1         | 1.49%   |
| HP DeskJet F4200 series             | 1         | 1.49%   |
| HP DeskJet 959c                     | 1         | 1.49%   |
| HP DeskJet 6122                     | 1         | 1.49%   |
| HP DeskJet 5650c                    | 1         | 1.49%   |
| HP DeskJet 3700 series              | 1         | 1.49%   |
| HP Deskjet 3540 series              | 1         | 1.49%   |
| HP Deskjet 2050 J510                | 1         | 1.49%   |
| HP DeskJet 1110 series              | 1         | 1.49%   |
| HP coredump                         | 1         | 1.49%   |
| Canon TS700 series                  | 1         | 1.49%   |
| Canon TS5100 series                 | 1         | 1.49%   |
| Canon TR7500 series                 | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 5         | 62.5%   |
| KYE Systems (Mouse Systems) | 1         | 12.5%   |
| Hewlett-Packard             | 1         | 12.5%   |
| Acer Peripherals (now BenQ) | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1         | 12.5%   |
| HP ScanJet 3670                                     | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1         | 12.5%   |
| Canon CanoScan LiDE 90                              | 1         | 12.5%   |
| Canon CanoScan LIDE 25                              | 1         | 12.5%   |
| Canon CanoScan LiDE 210                             | 1         | 12.5%   |
| Canon CanoScan 1220U                                | 1         | 12.5%   |
| Acer Peripherals (now BenQ) Prisa 1240UT            | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 251       | 25.59%  |
| Realtek Semiconductor                  | 88        | 8.97%   |
| IMC Networks                           | 78        | 7.95%   |
| Microdia                               | 69        | 7.03%   |
| Sunplus Innovation Technology          | 52        | 5.3%    |
| Bison Electronics                      | 48        | 4.89%   |
| Suyin                                  | 40        | 4.08%   |
| Quanta                                 | 37        | 3.77%   |
| Logitech                               | 37        | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 3.67%   |
| Syntek                                 | 32        | 3.26%   |
| Apple                                  | 26        | 2.65%   |
| Lite-On Technology                     | 18        | 1.83%   |
| Silicon Motion                         | 17        | 1.73%   |
| Alcor Micro                            | 13        | 1.33%   |
| Luxvisions Innotech Limited            | 12        | 1.22%   |
| Acer                                   | 12        | 1.22%   |
| Ricoh                                  | 10        | 1.02%   |
| Sonix Technology                       | 7         | 0.71%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.61%   |
| Primax Electronics                     | 6         | 0.61%   |
| Lenovo                                 | 6         | 0.61%   |
| Importek                               | 6         | 0.61%   |
| Generalplus Technology                 | 6         | 0.61%   |
| Microsoft                              | 5         | 0.51%   |
| ALi                                    | 5         | 0.51%   |
| Z-Star Microelectronics                | 4         | 0.41%   |
| Samsung Electronics                    | 4         | 0.41%   |
| OmniVision Technologies                | 4         | 0.41%   |
| icSpring                               | 4         | 0.41%   |
| HRY                                    | 3         | 0.31%   |
| Hewlett-Packard                        | 3         | 0.31%   |
| ARC International                      | 3         | 0.31%   |
| Y Media                                | 2         | 0.2%    |
| WaveRider Communications               | 2         | 0.2%    |
| Unknown                                | 2         | 0.2%    |
| Sunplus Technology                     | 2         | 0.2%    |
| Intel                                  | 2         | 0.2%    |
| Genesys Logic                          | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 35        | 3.55%   |
| Chicony HD WebCam                                   | 28        | 2.84%   |
| Microdia Integrated_Webcam_HD                       | 21        | 2.13%   |
| IMC Networks Integrated Camera                      | 20        | 2.03%   |
| Syntek Integrated Camera                            | 19        | 1.93%   |
| Realtek USB Camera                                  | 18        | 1.83%   |
| Bison Integrated Camera                             | 18        | 1.83%   |
| Realtek Integrated_Webcam_HD                        | 17        | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 16        | 1.62%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 1.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 13        | 1.32%   |
| Logitech Webcam C270                                | 12        | 1.22%   |
| Chicony FJ Camera                                   | 12        | 1.22%   |
| Microdia Integrated Webcam                          | 10        | 1.01%   |
| Apple FaceTime HD Camera (Built-in)                 | 10        | 1.01%   |
| Realtek Integrated Webcam HD                        | 9         | 0.91%   |
| Chicony Lenovo EasyCamera                           | 9         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 9         | 0.91%   |
| Chicony USB2.0 Camera                               | 8         | 0.81%   |
| Chicony HP Truevision HD                            | 8         | 0.81%   |
| Chicony HD User Facing                              | 8         | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 7         | 0.71%   |
| Microdia Webcam Vitade AF                           | 7         | 0.71%   |
| Chicony VGA Webcam                                  | 7         | 0.71%   |
| Chicony USB 2.0 Camera                              | 7         | 0.71%   |
| Chicony HP TrueVision HD Camera                     | 7         | 0.71%   |
| Chicony EasyCamera                                  | 7         | 0.71%   |
| Bison HD Webcam                                     | 7         | 0.71%   |
| Apple FaceTime HD Camera                            | 7         | 0.71%   |
| Syntek EasyCamera                                   | 6         | 0.61%   |
| Suyin 1.3M HD WebCam                                | 6         | 0.61%   |
| Sonix USB2.0 HD UVC WebCam                          | 6         | 0.61%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 6         | 0.61%   |
| Quanta VGA WebCam                                   | 6         | 0.61%   |
| Quanta HP TrueVision HD Camera                      | 6         | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 6         | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 0.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 6         | 0.61%   |
| Chicony HP Wide Vision HD Camera                    | 6         | 0.61%   |
| Alcor Micro USB 2.0 Camera                          | 6         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 45        | 29.03%  |
| Synaptics                  | 25        | 16.13%  |
| AuthenTec                  | 25        | 16.13%  |
| Upek                       | 15        | 9.68%   |
| Shenzhen Goodix Technology | 12        | 7.74%   |
| Elan Microelectronics      | 12        | 7.74%   |
| LighTuning Technology      | 9         | 5.81%   |
| STMicroelectronics         | 4         | 2.58%   |
| Samsung Electronics        | 4         | 2.58%   |
| Focal-systems.Corp         | 4         | 2.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 9.03%   |
| AuthenTec AES2810                                                          | 11        | 7.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 6.45%   |
| Validity Sensors VFS491                                                    | 8         | 5.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.52%   |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 4.52%   |
| Elan ELAN:ARM-M4                                                           | 7         | 4.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 4.52%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.58%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 2.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.58%   |
| Synaptics UWP WBDI Device                                                  | 4         | 2.58%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.58%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.58%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 2.58%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.58%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 2.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.94%   |
| Synaptics  WBDI                                                            | 3         | 1.94%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.94%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.29%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.29%   |
| Synaptics WBDI                                                             | 2         | 1.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.29%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.29%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.29%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.29%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.29%   |
| AuthenTec AES1600                                                          | 2         | 1.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.65%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.65%   |
| Synaptics UWP WBDI                                                         | 1         | 0.65%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 32        | 46.38%  |
| O2 Micro              | 13        | 18.84%  |
| Alcor Micro           | 11        | 15.94%  |
| Upek                  | 4         | 5.8%    |
| Lenovo                | 4         | 5.8%    |
| SCM Microsystems      | 1         | 1.45%   |
| Realtek Semiconductor | 1         | 1.45%   |
| Gemalto (was Gemplus) | 1         | 1.45%   |
| Castles Technology    | 1         | 1.45%   |
| Advanced Card Systems | 1         | 1.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 18.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 17.39%  |
| Broadcom 5880                                                                | 11        | 15.94%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 15.94%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 11.59%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.8%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.8%    |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 1.45%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.45%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 1.45%   |
| Broadcom 58200                                                               | 1         | 1.45%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1583      | 81.39%  |
| 1     | 319       | 16.4%   |
| 2     | 39        | 2.01%   |
| 3     | 4         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 39.04%  |
| Graphics card            | 101       | 25.44%  |
| Chipcard                 | 68        | 17.13%  |
| Net/wireless             | 14        | 3.53%   |
| Unassigned class         | 13        | 3.27%   |
| Communication controller | 11        | 2.77%   |
| Multimedia controller    | 10        | 2.52%   |
| Storage                  | 9         | 2.27%   |
| Camera                   | 8         | 2.02%   |
| Bluetooth                | 5         | 1.26%   |
| Net/ethernet             | 2         | 0.5%    |
| Flash memory             | 1         | 0.25%   |

