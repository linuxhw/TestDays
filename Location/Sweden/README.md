Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 2456

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f8f53c15b](https://linux-hardware.org/?probe=8f8f53c15b) | Nov 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ac8f0475f1](https://linux-hardware.org/?probe=ac8f0475f1) | Nov 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [669f6eaf1c](https://linux-hardware.org/?probe=669f6eaf1c) | Nov 26, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [b59180988d](https://linux-hardware.org/?probe=b59180988d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| AZW           | GTR V01                     | Mini pc     | [2042d4c2c0](https://linux-hardware.org/?probe=2042d4c2c0) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4c5a2a2f55](https://linux-hardware.org/?probe=4c5a2a2f55) | Nov 16, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [091c048c2a](https://linux-hardware.org/?probe=091c048c2a) | Nov 12, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [8dee2ceeb0](https://linux-hardware.org/?probe=8dee2ceeb0) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fae66184f2](https://linux-hardware.org/?probe=fae66184f2) | Nov 10, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2765ed4857](https://linux-hardware.org/?probe=2765ed4857) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Acer          | Predator G3610              | Desktop     | [783c053a62](https://linux-hardware.org/?probe=783c053a62) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e51ca052ec](https://linux-hardware.org/?probe=e51ca052ec) | Oct 28, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [cd6e5e2095](https://linux-hardware.org/?probe=cd6e5e2095) | Oct 27, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3c67c8efb7](https://linux-hardware.org/?probe=3c67c8efb7) | Oct 27, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [51cf8b4f9d](https://linux-hardware.org/?probe=51cf8b4f9d) | Oct 25, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f3ac5bf3df](https://linux-hardware.org/?probe=f3ac5bf3df) | Oct 20, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [4138cb5064](https://linux-hardware.org/?probe=4138cb5064) | Oct 17, 2022 |
| HP            | 2AE2                        | Desktop     | [a1a8fcfe49](https://linux-hardware.org/?probe=a1a8fcfe49) | Oct 17, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [10a3014c1a](https://linux-hardware.org/?probe=10a3014c1a) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [4f52cb1040](https://linux-hardware.org/?probe=4f52cb1040) | Oct 15, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | Notebook    | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [92704e062f](https://linux-hardware.org/?probe=92704e062f) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [16a6152e10](https://linux-hardware.org/?probe=16a6152e10) | Oct 02, 2022 |
| Dell          | Latitude E6320              | Notebook    | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9d5f38913b](https://linux-hardware.org/?probe=9d5f38913b) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| HP            | 18E5                        | Desktop     | [bcc9927d20](https://linux-hardware.org/?probe=bcc9927d20) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [52fd47ee14](https://linux-hardware.org/?probe=52fd47ee14) | Sep 15, 2022 |
| Dell          | Latitude 7300               | Notebook    | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| HP            | 1497                        | Desktop     | [7d44fed5d5](https://linux-hardware.org/?probe=7d44fed5d5) | Sep 13, 2022 |
| HP            | 1497                        | Desktop     | [3afd83b18b](https://linux-hardware.org/?probe=3afd83b18b) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e77359618c](https://linux-hardware.org/?probe=e77359618c) | Sep 09, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [cf5955c3e1](https://linux-hardware.org/?probe=cf5955c3e1) | Sep 09, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a8d726946f](https://linux-hardware.org/?probe=a8d726946f) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4080f853b6](https://linux-hardware.org/?probe=4080f853b6) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d54fe6c0ea](https://linux-hardware.org/?probe=d54fe6c0ea) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| HP            | Pavilion 15                 | Notebook    | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Foxconn       | P35A01                      | Desktop     | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2a8c815e](https://linux-hardware.org/?probe=1e2a8c815e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [0b62c9a78f](https://linux-hardware.org/?probe=0b62c9a78f) | Aug 12, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [2487f351d2](https://linux-hardware.org/?probe=2487f351d2) | Aug 12, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [3fbc687842](https://linux-hardware.org/?probe=3fbc687842) | Aug 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f91ebc68e8](https://linux-hardware.org/?probe=f91ebc68e8) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a0f4d75db6](https://linux-hardware.org/?probe=a0f4d75db6) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | 18E7                        | Desktop     | [3d7c1549eb](https://linux-hardware.org/?probe=3d7c1549eb) | Jul 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [32c295bae1](https://linux-hardware.org/?probe=32c295bae1) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f34f2c91](https://linux-hardware.org/?probe=c3f34f2c91) | Jul 28, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | Notebook    | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [960fefaee7](https://linux-hardware.org/?probe=960fefaee7) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [ae2926d93e](https://linux-hardware.org/?probe=ae2926d93e) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | Notebook    | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | Notebook    | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [ba6f405592](https://linux-hardware.org/?probe=ba6f405592) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9da64b4efa](https://linux-hardware.org/?probe=9da64b4efa) | Jul 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | Precision 5570              | Notebook    | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [dcbdde4fdf](https://linux-hardware.org/?probe=dcbdde4fdf) | Jul 06, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [36aca635a8](https://linux-hardware.org/?probe=36aca635a8) | Jul 06, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [a366983f6a](https://linux-hardware.org/?probe=a366983f6a) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [78e233e42f](https://linux-hardware.org/?probe=78e233e42f) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [848a8591de](https://linux-hardware.org/?probe=848a8591de) | Jul 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [af5bb55ac5](https://linux-hardware.org/?probe=af5bb55ac5) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [5448ad3e33](https://linux-hardware.org/?probe=5448ad3e33) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [1c8dd20713](https://linux-hardware.org/?probe=1c8dd20713) | Jun 16, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [bec506a849](https://linux-hardware.org/?probe=bec506a849) | Jun 16, 2022 |
| Acer          | Predator G3610              | Desktop     | [ff347cdb53](https://linux-hardware.org/?probe=ff347cdb53) | Jun 15, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| congatec      | conga-PA7 A.0               | Mini pc     | [e0c6234f77](https://linux-hardware.org/?probe=e0c6234f77) | Jun 13, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | Notebook    | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d9cffc5cc6](https://linux-hardware.org/?probe=d9cffc5cc6) | Jun 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [4b972d5b22](https://linux-hardware.org/?probe=4b972d5b22) | Jun 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [b414c22d34](https://linux-hardware.org/?probe=b414c22d34) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 6450b               | Notebook    | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | Notebook    | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e64dfe3f6f](https://linux-hardware.org/?probe=e64dfe3f6f) | May 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8f40318937](https://linux-hardware.org/?probe=8f40318937) | May 27, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| ASUSTek       | U31Jg                       | Notebook    | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c00f6e1b2a](https://linux-hardware.org/?probe=c00f6e1b2a) | May 24, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [594e42160c](https://linux-hardware.org/?probe=594e42160c) | May 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | Notebook    | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f02fa869ff](https://linux-hardware.org/?probe=f02fa869ff) | May 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [bdc2dbdba3](https://linux-hardware.org/?probe=bdc2dbdba3) | May 19, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | Notebook    | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [efd77955ef](https://linux-hardware.org/?probe=efd77955ef) | May 15, 2022 |
| MSI           | GS73VR 7RG                  | Notebook    | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a9c9d7da8d](https://linux-hardware.org/?probe=a9c9d7da8d) | May 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bfcd03ba86](https://linux-hardware.org/?probe=bfcd03ba86) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [235beb3d5f](https://linux-hardware.org/?probe=235beb3d5f) | May 13, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [6f09e11de7](https://linux-hardware.org/?probe=6f09e11de7) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6165bc68](https://linux-hardware.org/?probe=5b6165bc68) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | Notebook    | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e2dfdb6af2](https://linux-hardware.org/?probe=e2dfdb6af2) | May 03, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [1c3645cb67](https://linux-hardware.org/?probe=1c3645cb67) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adc0bdd7f8](https://linux-hardware.org/?probe=adc0bdd7f8) | May 01, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [7defbcb7bb](https://linux-hardware.org/?probe=7defbcb7bb) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [8cba4892be](https://linux-hardware.org/?probe=8cba4892be) | Apr 25, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [57bbbf3023](https://linux-hardware.org/?probe=57bbbf3023) | Apr 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | Notebook    | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | 18E9                        | Desktop     | [36ff483a2f](https://linux-hardware.org/?probe=36ff483a2f) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [757b005814](https://linux-hardware.org/?probe=757b005814) | Apr 21, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [94e43177eb](https://linux-hardware.org/?probe=94e43177eb) | Apr 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4c46fa8a5b](https://linux-hardware.org/?probe=4c46fa8a5b) | Apr 19, 2022 |
| ASUSTek       | G551JW                      | Notebook    | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [391705d3c1](https://linux-hardware.org/?probe=391705d3c1) | Apr 15, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8994d0ea9f](https://linux-hardware.org/?probe=8994d0ea9f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [dba38dc289](https://linux-hardware.org/?probe=dba38dc289) | Apr 13, 2022 |
| HP            | 18E5                        | Desktop     | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [68aa564b9f](https://linux-hardware.org/?probe=68aa564b9f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [70e4d389af](https://linux-hardware.org/?probe=70e4d389af) | Apr 10, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | Desktop     | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [53e59cf805](https://linux-hardware.org/?probe=53e59cf805) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [f3bc34e630](https://linux-hardware.org/?probe=f3bc34e630) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [4361e01e42](https://linux-hardware.org/?probe=4361e01e42) | Apr 04, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2af47af588](https://linux-hardware.org/?probe=2af47af588) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [bcff3a3aef](https://linux-hardware.org/?probe=bcff3a3aef) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [893945236a](https://linux-hardware.org/?probe=893945236a) | Apr 03, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [137477b9ef](https://linux-hardware.org/?probe=137477b9ef) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [f625382909](https://linux-hardware.org/?probe=f625382909) | Mar 26, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | Notebook    | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | Notebook    | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | Notebook    | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f9345bd168](https://linux-hardware.org/?probe=f9345bd168) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [84e80f8c56](https://linux-hardware.org/?probe=84e80f8c56) | Mar 12, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [f3347643b0](https://linux-hardware.org/?probe=f3347643b0) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [8b499a7b72](https://linux-hardware.org/?probe=8b499a7b72) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | Notebook    | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | Notebook    | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [db85b45bf6](https://linux-hardware.org/?probe=db85b45bf6) | Mar 05, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [c04f6c7365](https://linux-hardware.org/?probe=c04f6c7365) | Mar 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [3ff867b4e2](https://linux-hardware.org/?probe=3ff867b4e2) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [d1c5534f6d](https://linux-hardware.org/?probe=d1c5534f6d) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2b2338382c](https://linux-hardware.org/?probe=2b2338382c) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [4ae8fd98cc](https://linux-hardware.org/?probe=4ae8fd98cc) | Feb 26, 2022 |
| Sony          | VPCEB36FG                   | Notebook    | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1cc7d4542a](https://linux-hardware.org/?probe=1cc7d4542a) | Feb 23, 2022 |
| Elo Touch ... | Geminilake Continental Z... | Desktop     | [6d9bcef1c7](https://linux-hardware.org/?probe=6d9bcef1c7) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| HP            | 86C7                        | All in one  | [efb6906a46](https://linux-hardware.org/?probe=efb6906a46) | Feb 21, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [1c3e6a4af1](https://linux-hardware.org/?probe=1c3e6a4af1) | Feb 21, 2022 |
| Dell          | Precision 3510              | Notebook    | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [34117f82de](https://linux-hardware.org/?probe=34117f82de) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | Notebook    | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [ed1a78c5a6](https://linux-hardware.org/?probe=ed1a78c5a6) | Feb 20, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [6b8b0ec7f9](https://linux-hardware.org/?probe=6b8b0ec7f9) | Feb 19, 2022 |
| HP            | 3032h                       | Desktop     | [df23e573ba](https://linux-hardware.org/?probe=df23e573ba) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| HP            | 829A                        | Mini pc     | [dfd0cb667c](https://linux-hardware.org/?probe=dfd0cb667c) | Feb 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [0600ea1165](https://linux-hardware.org/?probe=0600ea1165) | Feb 11, 2022 |
| Dell          | Latitude D620               | Notebook    | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [db7f189b71](https://linux-hardware.org/?probe=db7f189b71) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3a8c47094b](https://linux-hardware.org/?probe=3a8c47094b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [ae06eadc57](https://linux-hardware.org/?probe=ae06eadc57) | Feb 05, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a8cc9c8481](https://linux-hardware.org/?probe=a8cc9c8481) | Feb 03, 2022 |
| Packard Be... | IMEDIA S2985                | Desktop     | [661d923ce2](https://linux-hardware.org/?probe=661d923ce2) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [c51e8a279f](https://linux-hardware.org/?probe=c51e8a279f) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [19cb128817](https://linux-hardware.org/?probe=19cb128817) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| Acer          | Predator G3610              | Desktop     | [126f12bd14](https://linux-hardware.org/?probe=126f12bd14) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [bbe17ee442](https://linux-hardware.org/?probe=bbe17ee442) | Jan 31, 2022 |
| ASUSTek       | GR8                         | Notebook    | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [6350a05df4](https://linux-hardware.org/?probe=6350a05df4) | Jan 29, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [fa389062e6](https://linux-hardware.org/?probe=fa389062e6) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [fdf21ecdef](https://linux-hardware.org/?probe=fdf21ecdef) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [a0aecb00c0](https://linux-hardware.org/?probe=a0aecb00c0) | Jan 26, 2022 |
| AAEON         | GENE-BT05 V1.1              | Desktop     | [385d6a7c2e](https://linux-hardware.org/?probe=385d6a7c2e) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [5751d3e736](https://linux-hardware.org/?probe=5751d3e736) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [034f7c3687](https://linux-hardware.org/?probe=034f7c3687) | Jan 25, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | Notebook    | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [e5aea099ea](https://linux-hardware.org/?probe=e5aea099ea) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [f82cb83a85](https://linux-hardware.org/?probe=f82cb83a85) | Jan 23, 2022 |
| Notebook      | N13xWU                      | Notebook    | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [2aa2fc8ed9](https://linux-hardware.org/?probe=2aa2fc8ed9) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [e5b1e0c400](https://linux-hardware.org/?probe=e5b1e0c400) | Jan 20, 2022 |
| Dell          | Inspiron 5721               | Notebook    | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [2b7802edc0](https://linux-hardware.org/?probe=2b7802edc0) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | Notebook    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Seco          | C40 C                       | Desktop     | [4243badc3f](https://linux-hardware.org/?probe=4243badc3f) | Jan 14, 2022 |
| Dell          | Latitude 5290               | Notebook    | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [4899dd71f5](https://linux-hardware.org/?probe=4899dd71f5) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [9fa194bf62](https://linux-hardware.org/?probe=9fa194bf62) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [19857c8f84](https://linux-hardware.org/?probe=19857c8f84) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Sony          | VPCEB3S1E                   | Notebook    | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | Notebook    | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [14a4cdc223](https://linux-hardware.org/?probe=14a4cdc223) | Jan 06, 2022 |
| Samsung       | 935XDB                      | Notebook    | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Supermicro    | X9DRW                       | Server      | [31684ad7e4](https://linux-hardware.org/?probe=31684ad7e4) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [81efe23b11](https://linux-hardware.org/?probe=81efe23b11) | Jan 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [446ac9b29a](https://linux-hardware.org/?probe=446ac9b29a) | Jan 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef297a39aa](https://linux-hardware.org/?probe=ef297a39aa) | Jan 04, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [226a67696a](https://linux-hardware.org/?probe=226a67696a) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| MSI           | H67MA-E45                   | Desktop     | [d15eaff050](https://linux-hardware.org/?probe=d15eaff050) | Jan 01, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| MSI           | MS-7211                     | Desktop     | [f8d1e7a88c](https://linux-hardware.org/?probe=f8d1e7a88c) | Dec 31, 2021 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | Notebook    | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | Notebook    | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| Pegatron      | Narra6                      | Desktop     | [da3be9b31b](https://linux-hardware.org/?probe=da3be9b31b) | Dec 29, 2021 |
| MSI           | MS-7211                     | Desktop     | [3524bec1c8](https://linux-hardware.org/?probe=3524bec1c8) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [02f8579bf3](https://linux-hardware.org/?probe=02f8579bf3) | Dec 29, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | Notebook    | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | Notebook    | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | Notebook    | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | Notebook    | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [64e387d031](https://linux-hardware.org/?probe=64e387d031) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1713d01a4](https://linux-hardware.org/?probe=e1713d01a4) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [0a1cd1d1af](https://linux-hardware.org/?probe=0a1cd1d1af) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | Desktop     | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [42d4ee98ce](https://linux-hardware.org/?probe=42d4ee98ce) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | Notebook    | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [75b2d1484e](https://linux-hardware.org/?probe=75b2d1484e) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d66a9996f](https://linux-hardware.org/?probe=7d66a9996f) | Dec 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [44378ec4a5](https://linux-hardware.org/?probe=44378ec4a5) | Dec 14, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [dff25b4704](https://linux-hardware.org/?probe=dff25b4704) | Dec 11, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| ASUSTek       | CM6650                      | Desktop     | [ef34d60843](https://linux-hardware.org/?probe=ef34d60843) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | Notebook    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad04822d41](https://linux-hardware.org/?probe=ad04822d41) | Dec 07, 2021 |
| Dell          | Precision 5560              | Notebook    | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | Notebook    | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [1c3a187ec6](https://linux-hardware.org/?probe=1c3a187ec6) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9609fb65be](https://linux-hardware.org/?probe=9609fb65be) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [a2e2eceb54](https://linux-hardware.org/?probe=a2e2eceb54) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | Notebook    | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4dce6fbb79](https://linux-hardware.org/?probe=4dce6fbb79) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [fcd0ef9f0e](https://linux-hardware.org/?probe=fcd0ef9f0e) | Nov 29, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [5b0f7ffe69](https://linux-hardware.org/?probe=5b0f7ffe69) | Nov 29, 2021 |
| Acer          | Predator PT315-51           | Notebook    | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56f55d6a20](https://linux-hardware.org/?probe=56f55d6a20) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | 212B                        | Desktop     | [0377d5dc76](https://linux-hardware.org/?probe=0377d5dc76) | Nov 23, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | Notebook    | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | Notebook    | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [532584c064](https://linux-hardware.org/?probe=532584c064) | Nov 20, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [fcfcf6c49b](https://linux-hardware.org/?probe=fcfcf6c49b) | Nov 20, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [981f4d57e5](https://linux-hardware.org/?probe=981f4d57e5) | Nov 19, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | Notebook    | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | Notebook    | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | Notebook    | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Acer          | TravelMate Spin B118-R      | Convertible | [7cb747306c](https://linux-hardware.org/?probe=7cb747306c) | Nov 14, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [47982e4a71](https://linux-hardware.org/?probe=47982e4a71) | Nov 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [420684393a](https://linux-hardware.org/?probe=420684393a) | Nov 14, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [28a80f5aa9](https://linux-hardware.org/?probe=28a80f5aa9) | Nov 10, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [8fce727047](https://linux-hardware.org/?probe=8fce727047) | Nov 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | Notebook    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [01629df193](https://linux-hardware.org/?probe=01629df193) | Nov 08, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d3f60c7a58](https://linux-hardware.org/?probe=d3f60c7a58) | Nov 06, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | Notebook    | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | Notebook    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | Notebook    | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | Notebook    | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [23a62cdb4b](https://linux-hardware.org/?probe=23a62cdb4b) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| Gigabyte      | G1.Assassin                 | Desktop     | [40c84c9637](https://linux-hardware.org/?probe=40c84c9637) | Oct 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [82e27c0415](https://linux-hardware.org/?probe=82e27c0415) | Oct 31, 2021 |
| HP            | ZBook 14 G2                 | Notebook    | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| MSI           | H87M-G43                    | Desktop     | [aecd71ac63](https://linux-hardware.org/?probe=aecd71ac63) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | Notebook    | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [9c608040d6](https://linux-hardware.org/?probe=9c608040d6) | Oct 30, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [5a5d3a54c3](https://linux-hardware.org/?probe=5a5d3a54c3) | Oct 29, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [e766bcbb62](https://linux-hardware.org/?probe=e766bcbb62) | Oct 29, 2021 |
| HP            | 212B                        | Desktop     | [9d2a807f08](https://linux-hardware.org/?probe=9d2a807f08) | Oct 29, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [4e4391f329](https://linux-hardware.org/?probe=4e4391f329) | Oct 28, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [5d0901fd2c](https://linux-hardware.org/?probe=5d0901fd2c) | Oct 28, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3054d7b1b](https://linux-hardware.org/?probe=e3054d7b1b) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f67b298ab](https://linux-hardware.org/?probe=5f67b298ab) | Oct 27, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [a9c87c6c9c](https://linux-hardware.org/?probe=a9c87c6c9c) | Oct 27, 2021 |
| HP            | 212B                        | Desktop     | [b72e4a7240](https://linux-hardware.org/?probe=b72e4a7240) | Oct 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b47e0921b6](https://linux-hardware.org/?probe=b47e0921b6) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [780e40d828](https://linux-hardware.org/?probe=780e40d828) | Oct 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [57ba944640](https://linux-hardware.org/?probe=57ba944640) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [2591b8710e](https://linux-hardware.org/?probe=2591b8710e) | Oct 22, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [6e64d3ca9b](https://linux-hardware.org/?probe=6e64d3ca9b) | Oct 22, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [082f743459](https://linux-hardware.org/?probe=082f743459) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [eb31edbd6c](https://linux-hardware.org/?probe=eb31edbd6c) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [1c2c7bda55](https://linux-hardware.org/?probe=1c2c7bda55) | Oct 22, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [f11c125224](https://linux-hardware.org/?probe=f11c125224) | Oct 20, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a7d8d3cf71](https://linux-hardware.org/?probe=a7d8d3cf71) | Oct 19, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [1b7f4401be](https://linux-hardware.org/?probe=1b7f4401be) | Oct 17, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d39f2875f9](https://linux-hardware.org/?probe=d39f2875f9) | Oct 17, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [7f36e83485](https://linux-hardware.org/?probe=7f36e83485) | Oct 17, 2021 |
| HP            | 82F1                        | Desktop     | [8aadc7e548](https://linux-hardware.org/?probe=8aadc7e548) | Oct 16, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [6a36c68267](https://linux-hardware.org/?probe=6a36c68267) | Oct 15, 2021 |
| HP            | 86C7                        | All in one  | [57c1da4955](https://linux-hardware.org/?probe=57c1da4955) | Oct 15, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [a8d60d04b0](https://linux-hardware.org/?probe=a8d60d04b0) | Oct 14, 2021 |
| Dell          | Latitude E5250              | Notebook    | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | Notebook    | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [2bf61f2ec6](https://linux-hardware.org/?probe=2bf61f2ec6) | Oct 14, 2021 |
| Google        | Treeya                      | Notebook    | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| Supermicro    | X8DTH                       | Server      | [ad4abe60cd](https://linux-hardware.org/?probe=ad4abe60cd) | Oct 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [331d7231b0](https://linux-hardware.org/?probe=331d7231b0) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | Notebook    | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | Notebook    | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | Notebook    | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| MSI           | B150M Night Elf             | Desktop     | [ed3f4e9937](https://linux-hardware.org/?probe=ed3f4e9937) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [9587d6e0dd](https://linux-hardware.org/?probe=9587d6e0dd) | Oct 08, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [7e74deaa8e](https://linux-hardware.org/?probe=7e74deaa8e) | Oct 08, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [73f07430e4](https://linux-hardware.org/?probe=73f07430e4) | Oct 07, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Gigabyte      | 970A-UD3                    | Desktop     | [60a820dd34](https://linux-hardware.org/?probe=60a820dd34) | Oct 05, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | Notebook    | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | Notebook    | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | Notebook    | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| ASRock        | G41M-GS3                    | Desktop     | [b0ae6e12c3](https://linux-hardware.org/?probe=b0ae6e12c3) | Oct 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [a1ffad5b6d](https://linux-hardware.org/?probe=a1ffad5b6d) | Oct 02, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [0cb09f59a9](https://linux-hardware.org/?probe=0cb09f59a9) | Oct 01, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b3f1afc64b](https://linux-hardware.org/?probe=b3f1afc64b) | Oct 01, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [bd0f1e95ef](https://linux-hardware.org/?probe=bd0f1e95ef) | Sep 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f5c02601d0](https://linux-hardware.org/?probe=f5c02601d0) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| Acer          | WG43M                       | Desktop     | [f269cb6987](https://linux-hardware.org/?probe=f269cb6987) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [f56bf148bf](https://linux-hardware.org/?probe=f56bf148bf) | Sep 24, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e001ec9d57](https://linux-hardware.org/?probe=e001ec9d57) | Sep 23, 2021 |
| HP            | Presario CQ62               | Notebook    | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [13d080e9d6](https://linux-hardware.org/?probe=13d080e9d6) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bd2cfcf1ee](https://linux-hardware.org/?probe=bd2cfcf1ee) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [3a0e961b45](https://linux-hardware.org/?probe=3a0e961b45) | Sep 18, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | Notebook    | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [8750af4b33](https://linux-hardware.org/?probe=8750af4b33) | Sep 16, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [a9fc1d1222](https://linux-hardware.org/?probe=a9fc1d1222) | Sep 16, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Dell          | Latitude 5290               | Notebook    | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Gigabyte      | H77-D3H                     | Desktop     | [0c9d11ec80](https://linux-hardware.org/?probe=0c9d11ec80) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| HP            | 3032h                       | Desktop     | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Acer          | Swift SF314-511             | Notebook    | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| ASRock        | HM55-MXM                    | Desktop     | [0d500a3661](https://linux-hardware.org/?probe=0d500a3661) | Sep 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [6d3a30d1a7](https://linux-hardware.org/?probe=6d3a30d1a7) | Sep 11, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [fad193ae06](https://linux-hardware.org/?probe=fad193ae06) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [c58154679e](https://linux-hardware.org/?probe=c58154679e) | Sep 10, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [417104e2f2](https://linux-hardware.org/?probe=417104e2f2) | Sep 09, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [7f29f46363](https://linux-hardware.org/?probe=7f29f46363) | Sep 09, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [9a77062729](https://linux-hardware.org/?probe=9a77062729) | Sep 09, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| HP            | ZBook 17 G3                 | Notebook    | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d644d366b2](https://linux-hardware.org/?probe=d644d366b2) | Sep 06, 2021 |
| HP            | ProBook 4540s               | Notebook    | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | Desktop     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| PC Special... | N150CU                      | Notebook    | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| HP            | 3031h                       | Desktop     | [9fc8c93cd1](https://linux-hardware.org/?probe=9fc8c93cd1) | Sep 01, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [9fd555a4ea](https://linux-hardware.org/?probe=9fd555a4ea) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [f4e788dce6](https://linux-hardware.org/?probe=f4e788dce6) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [8f5b776bcb](https://linux-hardware.org/?probe=8f5b776bcb) | Aug 30, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [645425c060](https://linux-hardware.org/?probe=645425c060) | Aug 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | Notebook    | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [8dc5048a39](https://linux-hardware.org/?probe=8dc5048a39) | Aug 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [86c5a4a3dd](https://linux-hardware.org/?probe=86c5a4a3dd) | Aug 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [01b1cadf52](https://linux-hardware.org/?probe=01b1cadf52) | Aug 25, 2021 |
| Acer          | TravelMate Spin B118-R      | Convertible | [a49c104eda](https://linux-hardware.org/?probe=a49c104eda) | Aug 24, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [35f6fc9592](https://linux-hardware.org/?probe=35f6fc9592) | Aug 23, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [32593919a0](https://linux-hardware.org/?probe=32593919a0) | Aug 23, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES0... | Convertible | [4300a083b1](https://linux-hardware.org/?probe=4300a083b1) | Aug 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7406e49c18](https://linux-hardware.org/?probe=7406e49c18) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [cdf90072fd](https://linux-hardware.org/?probe=cdf90072fd) | Aug 21, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [f32d5484b5](https://linux-hardware.org/?probe=f32d5484b5) | Aug 20, 2021 |
| ASRock        | G41M-LE                     | Desktop     | [b6d9b74951](https://linux-hardware.org/?probe=b6d9b74951) | Aug 20, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | Desktop     | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |
| PC Special... | Standard                    | Notebook    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [9482e2b574](https://linux-hardware.org/?probe=9482e2b574) | Aug 17, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [272f3deca9](https://linux-hardware.org/?probe=272f3deca9) | Aug 17, 2021 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [40a8ec3a95](https://linux-hardware.org/?probe=40a8ec3a95) | Aug 16, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [e26b353478](https://linux-hardware.org/?probe=e26b353478) | Aug 16, 2021 |
| Razer         | Blade                       | Notebook    | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | Notebook    | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [347638818a](https://linux-hardware.org/?probe=347638818a) | Aug 15, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [9e8c53410a](https://linux-hardware.org/?probe=9e8c53410a) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [38abfc60a9](https://linux-hardware.org/?probe=38abfc60a9) | Aug 14, 2021 |
| Lenovo        | 1031 SDK0J40697 WIN 3305... | Desktop     | [a06764af07](https://linux-hardware.org/?probe=a06764af07) | Aug 14, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6775259732](https://linux-hardware.org/?probe=6775259732) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [adde6ef882](https://linux-hardware.org/?probe=adde6ef882) | Aug 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [164bbac83c](https://linux-hardware.org/?probe=164bbac83c) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | Notebook    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [a78580fb6b](https://linux-hardware.org/?probe=a78580fb6b) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [c1209f4d40](https://linux-hardware.org/?probe=c1209f4d40) | Aug 09, 2021 |
| Dell          | Precision M4500             | Notebook    | [d7b650fecf](https://linux-hardware.org/?probe=d7b650fecf) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [7bc23070c4](https://linux-hardware.org/?probe=7bc23070c4) | Aug 08, 2021 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [d3e0286f2f](https://linux-hardware.org/?probe=d3e0286f2f) | Aug 08, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [9e08265168](https://linux-hardware.org/?probe=9e08265168) | Aug 08, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ffe68561cd](https://linux-hardware.org/?probe=ffe68561cd) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [b143c1bc24](https://linux-hardware.org/?probe=b143c1bc24) | Aug 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [dea83da57d](https://linux-hardware.org/?probe=dea83da57d) | Aug 04, 2021 |
| Packard Be... | EasyNote TS11SB             | Notebook    | [aa9468a3de](https://linux-hardware.org/?probe=aa9468a3de) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1bcb4e3744](https://linux-hardware.org/?probe=1bcb4e3744) | Aug 03, 2021 |
| Packard Be... | EasyNote TS11SB             | Notebook    | [57fbaedb1e](https://linux-hardware.org/?probe=57fbaedb1e) | Aug 03, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| HP            | Pavilion 15                 | Notebook    | [08bd4b9549](https://linux-hardware.org/?probe=08bd4b9549) | Aug 02, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [23399ffe42](https://linux-hardware.org/?probe=23399ffe42) | Jul 30, 2021 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [9d1b679c39](https://linux-hardware.org/?probe=9d1b679c39) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [822adc34c6](https://linux-hardware.org/?probe=822adc34c6) | Jul 28, 2021 |
| MSI           | Z97-G55 SLI                 | Desktop     | [e473068ae1](https://linux-hardware.org/?probe=e473068ae1) | Jul 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [ad2986d747](https://linux-hardware.org/?probe=ad2986d747) | Jul 26, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [8f6e1f1929](https://linux-hardware.org/?probe=8f6e1f1929) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [896e1bc2a0](https://linux-hardware.org/?probe=896e1bc2a0) | Jul 25, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 263       | 14.75%  |
| Ubuntu 18.04                 | 131       | 7.35%   |
| Ubuntu 22.04                 | 74        | 4.15%   |
| Pop!_OS 21.04                | 49        | 2.75%   |
| Arch Rolling                 | 41        | 2.3%    |
| Manjaro                      | 40        | 2.24%   |
| Arch                         | 40        | 2.24%   |
| OpenMandriva 4.2             | 39        | 2.19%   |
| Debian 11                    | 39        | 2.19%   |
| KDE neon 20.04               | 38        | 2.13%   |
| OpenMandriva 4.3             | 37        | 2.08%   |
| Pop!_OS 20.04                | 30        | 1.68%   |
| Ubuntu 21.10                 | 29        | 1.63%   |
| Ubuntu 21.04                 | 29        | 1.63%   |
| Pop!_OS 20.10                | 29        | 1.63%   |
| Ubuntu 19.04                 | 27        | 1.51%   |
| Fedora 35                    | 27        | 1.51%   |
| Linux Mint 20.3              | 26        | 1.46%   |
| Zorin 16                     | 25        | 1.4%    |
| Fedora 34                    | 25        | 1.4%    |
| Ubuntu 19.10                 | 24        | 1.35%   |
| Pop!_OS 22.04                | 23        | 1.29%   |
| Fedora 32                    | 23        | 1.29%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 1.23%   |
| Fedora 36                    | 22        | 1.23%   |
| Zorin 15                     | 21        | 1.18%   |
| Xubuntu 20.04                | 19        | 1.07%   |
| Ubuntu 20.10                 | 19        | 1.07%   |
| Linux Mint 20.2              | 19        | 1.07%   |
| Linux Mint 20                | 19        | 1.07%   |
| Fedora 33                    | 18        | 1.01%   |
| ArcoLinux Rolling            | 18        | 1.01%   |
| Linux Mint 20.1              | 17        | 0.95%   |
| Fedora 31                    | 15        | 0.84%   |
| Pop!_OS 21.10                | 14        | 0.79%   |
| Debian 10                    | 14        | 0.79%   |
| Gentoo 2.6                   | 13        | 0.73%   |
| Ubuntu 18.10                 | 12        | 0.67%   |
| Linux Mint 19.1              | 12        | 0.67%   |
| Gentoo 2.7                   | 12        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 592       | 34.68%  |
| Pop!_OS       | 138       | 8.08%   |
| Fedora        | 134       | 7.85%   |
| Linux Mint    | 115       | 6.74%   |
| OpenMandriva  | 85        | 4.98%   |
| Manjaro       | 81        | 4.75%   |
| Arch          | 80        | 4.69%   |
| Debian        | 68        | 3.98%   |
| Zorin         | 46        | 2.69%   |
| KDE neon      | 44        | 2.58%   |
| Xubuntu       | 36        | 2.11%   |
| Gentoo        | 28        | 1.64%   |
| openSUSE      | 26        | 1.52%   |
| ArcoLinux     | 23        | 1.35%   |
| ROSA          | 20        | 1.17%   |
| Kubuntu       | 19        | 1.11%   |
| CentOS        | 13        | 0.76%   |
| Elementary    | 11        | 0.64%   |
| EndeavourOS   | 10        | 0.59%   |
| Clear Linux   | 10        | 0.59%   |
| Ubuntu MATE   | 9         | 0.53%   |
| Endless       | 9         | 0.53%   |
| Kali          | 8         | 0.47%   |
| Ubuntu Unity  | 7         | 0.41%   |
| Peppermint    | 6         | 0.35%   |
| LMDE          | 6         | 0.35%   |
| Ubuntu Budgie | 5         | 0.29%   |
| Solus         | 5         | 0.29%   |
| Lubuntu       | 5         | 0.29%   |
| Garuda Linux  | 5         | 0.29%   |
| Slackware     | 4         | 0.23%   |
| Parrot        | 4         | 0.23%   |
| MX            | 4         | 0.23%   |
| BlackPanther  | 4         | 0.23%   |
| Alpine        | 4         | 0.23%   |
| SteamOS       | 3         | 0.18%   |
| Raspbian      | 3         | 0.18%   |
| BunsenLabs    | 3         | 0.18%   |
| Siduction     | 2         | 0.12%   |
| Rocky Linux   | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 39        | 2.01%   |
| 5.16.7-desktop-1omv4003  | 36        | 1.86%   |
| 5.4.0-42-generic         | 33        | 1.7%    |
| 5.4.0-58-generic         | 21        | 1.08%   |
| 5.4.0-48-generic         | 20        | 1.03%   |
| 5.11.0-7620-generic      | 19        | 0.98%   |
| 5.15.0-52-generic        | 18        | 0.93%   |
| 5.3.0-40-generic         | 17        | 0.88%   |
| 5.13.0-7614-generic      | 17        | 0.88%   |
| 5.4.0-52-generic         | 16        | 0.83%   |
| 5.15.0-46-generic        | 15        | 0.77%   |
| 5.13.0-30-generic        | 15        | 0.77%   |
| 5.4.0-40-generic         | 14        | 0.72%   |
| 5.13.0-39-generic        | 14        | 0.72%   |
| 5.4.0-7634-generic       | 13        | 0.67%   |
| 5.15.0-48-generic        | 13        | 0.67%   |
| 5.4.0-54-generic         | 12        | 0.62%   |
| 5.4.0-33-generic         | 12        | 0.62%   |
| 5.11.0-37-generic        | 12        | 0.62%   |
| 5.8.0-48-generic         | 11        | 0.57%   |
| 5.4.0-70-generic         | 11        | 0.57%   |
| 5.15.0-50-generic        | 11        | 0.57%   |
| 5.11.0-7614-generic      | 11        | 0.57%   |
| 5.10.0-8-amd64           | 11        | 0.57%   |
| 5.8.0-43-generic         | 10        | 0.52%   |
| 5.4.0-65-generic         | 10        | 0.52%   |
| 5.4.0-29-generic         | 10        | 0.52%   |
| 5.11.0-41-generic        | 10        | 0.52%   |
| 5.8.0-50-generic         | 9         | 0.46%   |
| 5.4.0-81-generic         | 9         | 0.46%   |
| 5.4.0-67-generic         | 9         | 0.46%   |
| 5.15.0-53-generic        | 9         | 0.46%   |
| 5.15.0-41-generic        | 9         | 0.46%   |
| 4.15.0-47-generic        | 9         | 0.46%   |
| 5.8.0-7642-generic       | 8         | 0.41%   |
| 5.8.0-7630-generic       | 8         | 0.41%   |
| 5.4.0-26-generic         | 8         | 0.41%   |
| 5.11.0-40-generic        | 8         | 0.41%   |
| 5.11.0-38-generic        | 8         | 0.41%   |
| 5.11.0-27-generic        | 8         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 331       | 18%     |
| 5.11.0  | 128       | 6.96%   |
| 5.13.0  | 113       | 6.14%   |
| 5.15.0  | 110       | 5.98%   |
| 5.8.0   | 97        | 5.27%   |
| 4.15.0  | 81        | 4.4%    |
| 5.3.0   | 76        | 4.13%   |
| 5.0.0   | 59        | 3.21%   |
| 5.10.0  | 54        | 2.94%   |
| 4.18.0  | 47        | 2.56%   |
| 5.10.14 | 40        | 2.18%   |
| 5.16.7  | 37        | 2.01%   |
| 5.17.5  | 12        | 0.65%   |
| 5.19.0  | 10        | 0.54%   |
| 5.14.0  | 10        | 0.54%   |
| 5.12.4  | 10        | 0.54%   |
| 4.19.0  | 10        | 0.54%   |
| 5.17.1  | 9         | 0.49%   |
| 5.18.0  | 8         | 0.44%   |
| 5.16.0  | 8         | 0.44%   |
| 5.7.0   | 7         | 0.38%   |
| 5.19.16 | 7         | 0.38%   |
| 5.15.7  | 7         | 0.38%   |
| 5.9.0   | 6         | 0.33%   |
| 5.8.1   | 6         | 0.33%   |
| 4.9.20  | 6         | 0.33%   |
| 5.9.8   | 5         | 0.27%   |
| 5.9.14  | 5         | 0.27%   |
| 5.5.8   | 5         | 0.27%   |
| 5.18.14 | 5         | 0.27%   |
| 5.17.15 | 5         | 0.27%   |
| 5.16.15 | 5         | 0.27%   |
| 5.15.5  | 5         | 0.27%   |
| 5.15.15 | 5         | 0.27%   |
| 5.14.11 | 5         | 0.27%   |
| 5.9.16  | 4         | 0.22%   |
| 5.8.11  | 4         | 0.22%   |
| 5.6.0   | 4         | 0.22%   |
| 5.18.10 | 4         | 0.22%   |
| 5.17.9  | 4         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 360       | 19.89%  |
| 5.15    | 167       | 9.23%   |
| 5.11    | 157       | 8.67%   |
| 5.10    | 139       | 7.68%   |
| 5.8     | 134       | 7.4%    |
| 5.13    | 133       | 7.35%   |
| 5.3     | 88        | 4.86%   |
| 4.15    | 81        | 4.48%   |
| 5.16    | 76        | 4.2%    |
| 5.0     | 62        | 3.43%   |
| 4.18    | 54        | 2.98%   |
| 5.17    | 46        | 2.54%   |
| 5.12    | 36        | 1.99%   |
| 5.18    | 34        | 1.88%   |
| 5.9     | 33        | 1.82%   |
| 5.6     | 28        | 1.55%   |
| 5.14    | 28        | 1.55%   |
| 5.19    | 27        | 1.49%   |
| 5.7     | 24        | 1.33%   |
| 4.19    | 22        | 1.22%   |
| 4.9     | 16        | 0.88%   |
| 6.0     | 15        | 0.83%   |
| 5.5     | 15        | 0.83%   |
| 5.1     | 7         | 0.39%   |
| 5.2     | 6         | 0.33%   |
| 4.4     | 6         | 0.33%   |
| 4.14    | 3         | 0.17%   |
| 4.1     | 3         | 0.17%   |
| 4.20    | 2         | 0.11%   |
| 4.12    | 2         | 0.11%   |
| 3.10    | 2         | 0.11%   |
| 5       | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 3.2     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1598      | 97.62%  |
| i686    | 22        | 1.34%   |
| aarch64 | 10        | 0.61%   |
| armv7l  | 5         | 0.31%   |
| i586    | 1         | 0.06%   |
| armv8l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 802       | 46.57%  |
| Unknown         | 259       | 15.04%  |
| KDE5            | 222       | 12.89%  |
| XFCE            | 125       | 7.26%   |
| X-Cinnamon      | 88        | 5.11%   |
| KDE             | 70        | 4.07%   |
| MATE            | 31        | 1.8%    |
| Cinnamon        | 17        | 0.99%   |
| i3              | 12        | 0.7%    |
| LXDE            | 11        | 0.64%   |
| KDE4            | 11        | 0.64%   |
| Pantheon        | 10        | 0.58%   |
| LXQt            | 10        | 0.58%   |
| Budgie          | 9         | 0.52%   |
| Unity           | 8         | 0.46%   |
| Deepin          | 7         | 0.41%   |
| awesome         | 5         | 0.29%   |
| sway            | 4         | 0.23%   |
| Openbox         | 4         | 0.23%   |
| GNOME Classic   | 4         | 0.23%   |
| GNOME Flashback | 3         | 0.17%   |
| qtile           | 2         | 0.12%   |
| DWM             | 2         | 0.12%   |
| xmonad          | 1         | 0.06%   |
| Trinity         | 1         | 0.06%   |
| spectrwm        | 1         | 0.06%   |
| LeftWM          | 1         | 0.06%   |
| GNOME-Flashback | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1252      | 74.26%  |
| Wayland     | 238       | 14.12%  |
| Unknown     | 132       | 7.83%   |
| Tty         | 63        | 3.74%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 965       | 56.6%   |
| SDDM    | 200       | 11.73%  |
| GDM     | 196       | 11.5%   |
| GDM3    | 141       | 8.27%   |
| LightDM | 119       | 6.98%   |
| TDM     | 63        | 3.7%    |
| KDM     | 11        | 0.65%   |
| XDM     | 6         | 0.35%   |
| Ly      | 3         | 0.18%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 779       | 46.26%  |
| sv_SE       | 457       | 27.14%  |
| Unknown     | 224       | 13.3%   |
| en_GB       | 101       | 6%      |
| C           | 39        | 2.32%   |
| de_DE       | 14        | 0.83%   |
| ru_RU       | 12        | 0.71%   |
| en_SE       | 8         | 0.48%   |
| pl_PL       | 6         | 0.36%   |
| en_DK       | 6         | 0.36%   |
| fr_FR       | 4         | 0.24%   |
| en_CA       | 3         | 0.18%   |
| bg_BG       | 3         | 0.18%   |
| uk_UA       | 2         | 0.12%   |
| POSIX       | 2         | 0.12%   |
| nb_NO       | 2         | 0.12%   |
| lt_LT       | 2         | 0.12%   |
| en_IE       | 2         | 0.12%   |
| en_AG       | 2         | 0.12%   |
| C.UTF8      | 2         | 0.12%   |
| sv_SE.UTF8  | 1         | 0.06%   |
| sv_FI       | 1         | 0.06%   |
| sma_SE      | 1         | 0.06%   |
| nn_NO       | 1         | 0.06%   |
| hu_HU       | 1         | 0.06%   |
| fi_FI       | 1         | 0.06%   |
| es_VE       | 1         | 0.06%   |
| es_ES       | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_IN       | 1         | 0.06%   |
| en_GB.UTF8  | 1         | 0.06%   |
| en_GB.utf-8 | 1         | 0.06%   |
| en_AU       | 1         | 0.06%   |
| bs_BA       | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 840       | 50%     |
| EFI  | 840       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1293      | 77.01%  |
| Btrfs   | 156       | 9.29%   |
| Overlay | 114       | 6.79%   |
| Unknown | 58        | 3.45%   |
| Xfs     | 27        | 1.61%   |
| Zfs     | 16        | 0.95%   |
| Ext2    | 7         | 0.42%   |
| F2fs    | 4         | 0.24%   |
| Tmpfs   | 2         | 0.12%   |
| XXXXXXX | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 987       | 58.51%  |
| GPT     | 562       | 33.31%  |
| MBR     | 138       | 8.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1445      | 86.58%  |
| Yes       | 224       | 13.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1261      | 75.64%  |
| Yes       | 406       | 24.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 364       | 22.24%  |
| Hewlett-Packard         | 240       | 14.66%  |
| Lenovo                  | 231       | 14.11%  |
| Dell                    | 178       | 10.87%  |
| MSI                     | 116       | 7.09%   |
| Gigabyte Technology     | 111       | 6.78%   |
| Acer                    | 80        | 4.89%   |
| Apple                   | 52        | 3.18%   |
| ASRock                  | 43        | 2.63%   |
| Intel                   | 24        | 1.47%   |
| Toshiba                 | 14        | 0.86%   |
| Sony                    | 14        | 0.86%   |
| Raspberry Pi Foundation | 13        | 0.79%   |
| Fujitsu                 | 13        | 0.79%   |
| Packard Bell            | 12        | 0.73%   |
| Samsung Electronics     | 9         | 0.55%   |
| Unknown                 | 9         | 0.55%   |
| Supermicro              | 8         | 0.49%   |
| Notebook                | 7         | 0.43%   |
| Foxconn                 | 7         | 0.43%   |
| Pegatron                | 6         | 0.37%   |
| Google                  | 6         | 0.37%   |
| Microsoft               | 5         | 0.31%   |
| Fujitsu Siemens         | 5         | 0.31%   |
| AAEON                   | 5         | 0.31%   |
| Maxtang                 | 4         | 0.24%   |
| HUAWEI                  | 4         | 0.24%   |
| Valve                   | 3         | 0.18%   |
| TUXEDO                  | 3         | 0.18%   |
| Star Labs               | 2         | 0.12%   |
| Razer                   | 2         | 0.12%   |
| PC Specialist           | 2         | 0.12%   |
| Linx                    | 2         | 0.12%   |
| eMachines               | 2         | 0.12%   |
| AZW                     | 2         | 0.12%   |
| AMD                     | 2         | 0.12%   |
| Alienware               | 2         | 0.12%   |
| ZEPTO                   | 1         | 0.06%   |
| YJKC                    | 1         | 0.06%   |
| XDO.AI                  | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 21        | 1.28%   |
| Unknown                            | 12        | 0.73%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.61%   |
| MSI MS-7C37                        | 7         | 0.43%   |
| ASUS ROG STRIX X570-F GAMING       | 7         | 0.43%   |
| ASUS ROG STRIX B550-F GAMING       | 7         | 0.43%   |
| ASUS PRIME X470-PRO                | 7         | 0.43%   |
| Dell Precision 5540                | 6         | 0.37%   |
| MSI MS-7C52                        | 5         | 0.31%   |
| MSI MS-7817                        | 5         | 0.31%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.31%   |
| HP Pavilion dv7                    | 5         | 0.31%   |
| HP Pavilion 15                     | 5         | 0.31%   |
| HP EliteBook Folio 9470m           | 5         | 0.31%   |
| Gigabyte B450M DS3H                | 5         | 0.31%   |
| Dell XPS 13 9310                   | 5         | 0.31%   |
| ASUS Z170 PRO GAMING               | 5         | 0.31%   |
| ASUS PRIME X370-PRO                | 5         | 0.31%   |
| Apple MacBookPro11,3               | 5         | 0.31%   |
| Acer Aspire V3-571                 | 5         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.24%   |
| MSI MS-7C02                        | 4         | 0.24%   |
| Maxtang FP30                       | 4         | 0.24%   |
| Lenovo MIIX 310-10ICR 80SG         | 4         | 0.24%   |
| HP EliteBook 840 G2                | 4         | 0.24%   |
| Dell XPS 15 9570                   | 4         | 0.24%   |
| Dell XPS 15 9500                   | 4         | 0.24%   |
| Dell XPS 13 9370                   | 4         | 0.24%   |
| Dell OptiPlex 7010                 | 4         | 0.24%   |
| ASUS SABERTOOTH 990FX R2.0         | 4         | 0.24%   |
| ASUS ROG STRIX B550-I GAMING       | 4         | 0.24%   |
| ASUS ROG STRIX B450-F GAMING II    | 4         | 0.24%   |
| ASUS ROG STRIX B350-F GAMING       | 4         | 0.24%   |
| ASUS P8Z77-V LX                    | 4         | 0.24%   |
| ASUS M5A97 R2.0                    | 4         | 0.24%   |
| Apple MacBookAir7,2                | 4         | 0.24%   |
| Valve Jupiter                      | 3         | 0.18%   |
| MSI MS-7C91                        | 3         | 0.18%   |
| MSI MS-7C84                        | 3         | 0.18%   |
| MSI MS-7B98                        | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 127       | 7.76%   |
| ASUS ROG              | 74        | 4.52%   |
| HP EliteBook          | 65        | 3.97%   |
| Acer Aspire           | 52        | 3.18%   |
| Dell Latitude         | 49        | 2.99%   |
| Dell Precision        | 44        | 2.69%   |
| ASUS PRIME            | 42        | 2.57%   |
| Dell XPS              | 39        | 2.38%   |
| HP Pavilion           | 35        | 2.14%   |
| HP ProBook            | 28        | 1.71%   |
| HP Compaq             | 27        | 1.65%   |
| Lenovo IdeaPad        | 26        | 1.59%   |
| Dell OptiPlex         | 23        | 1.41%   |
| ASUS All              | 21        | 1.28%   |
| Lenovo Yoga           | 17        | 1.04%   |
| HP ZBook              | 15        | 0.92%   |
| HP ENVY               | 15        | 0.92%   |
| ASUS VivoBook         | 15        | 0.92%   |
| ASUS TUF              | 15        | 0.92%   |
| RPi Raspberry         | 13        | 0.79%   |
| Toshiba Satellite     | 12        | 0.73%   |
| HP Laptop             | 12        | 0.73%   |
| Unknown               | 12        | 0.73%   |
| Lenovo Legion         | 11        | 0.67%   |
| Dell Inspiron         | 11        | 0.67%   |
| ASUS ZenBook          | 10        | 0.61%   |
| Gigabyte X570         | 9         | 0.55%   |
| ASUS P8Z77-V          | 9         | 0.55%   |
| Packard Bell EasyNote | 8         | 0.49%   |
| HP EliteDesk          | 8         | 0.49%   |
| MSI MS-7C37           | 7         | 0.43%   |
| Dell Vostro           | 7         | 0.43%   |
| ASUS SABERTOOTH       | 7         | 0.43%   |
| Acer Swift            | 7         | 0.43%   |
| Acer Predator         | 7         | 0.43%   |
| Lenovo IdeaPadFlex    | 6         | 0.37%   |
| Gigabyte B450M        | 6         | 0.37%   |
| Apple MacBookPro11    | 6         | 0.37%   |
| MSI MS-7C52           | 5         | 0.31%   |
| MSI MS-7817           | 5         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 175       | 10.69%  |
| 2019    | 173       | 10.57%  |
| 2020    | 145       | 8.86%   |
| 2013    | 123       | 7.51%   |
| 2011    | 123       | 7.51%   |
| 2017    | 121       | 7.39%   |
| 2012    | 119       | 7.27%   |
| 2015    | 104       | 6.35%   |
| 2021    | 101       | 6.17%   |
| 2014    | 100       | 6.11%   |
| 2016    | 91        | 5.56%   |
| 2010    | 82        | 5.01%   |
| 2008    | 46        | 2.81%   |
| 2009    | 45        | 2.75%   |
| 2007    | 37        | 2.26%   |
| 2022    | 23        | 1.41%   |
| 2006    | 10        | 0.61%   |
| Unknown | 10        | 0.61%   |
| 2005    | 7         | 0.43%   |
| 2004    | 1         | 0.06%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 832       | 50.82%  |
| Desktop        | 678       | 41.42%  |
| Convertible    | 40        | 2.44%   |
| Mini pc        | 32        | 1.95%   |
| System on chip | 14        | 0.86%   |
| Tablet         | 14        | 0.86%   |
| All in one     | 14        | 0.86%   |
| Server         | 11        | 0.67%   |
| Phone          | 2         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1503      | 91.31%  |
| Enabled  | 143       | 8.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1628      | 99.45%  |
| Yes  | 9         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 401       | 24.19%  |
| 4.01-8.0        | 349       | 21.05%  |
| 8.01-16.0       | 282       | 17.01%  |
| 32.01-64.0      | 246       | 14.84%  |
| 3.01-4.0        | 221       | 13.33%  |
| 64.01-256.0     | 53        | 3.2%    |
| 1.01-2.0        | 48        | 2.9%    |
| 24.01-32.0      | 26        | 1.57%   |
| 2.01-3.0        | 15        | 0.9%    |
| 0.51-1.0        | 14        | 0.84%   |
| More than 256.0 | 2         | 0.12%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 594       | 32.87%  |
| 2.01-3.0   | 438       | 24.24%  |
| 4.01-8.0   | 320       | 17.71%  |
| 3.01-4.0   | 227       | 12.56%  |
| 8.01-16.0  | 92        | 5.09%   |
| 0.51-1.0   | 88        | 4.87%   |
| 16.01-24.0 | 23        | 1.27%   |
| 0.01-0.5   | 20        | 1.11%   |
| 24.01-32.0 | 4         | 0.22%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 990       | 58.61%  |
| 2      | 366       | 21.67%  |
| 3      | 145       | 8.58%   |
| 4      | 85        | 5.03%   |
| 5      | 39        | 2.31%   |
| 6      | 25        | 1.48%   |
| 0      | 16        | 0.95%   |
| 7      | 14        | 0.83%   |
| 8      | 5         | 0.3%    |
| 10     | 2         | 0.12%   |
| 11     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1095      | 66.52%  |
| Yes       | 551       | 33.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1430      | 87.14%  |
| No        | 211       | 12.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1170      | 70.91%  |
| No        | 480       | 29.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 973       | 58.69%  |
| No        | 685       | 41.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 1637      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Stockholm         | 293       | 16.8%   |
| Gothenburg        | 170       | 9.75%   |
| Malmo             | 81        | 4.64%   |
| Uppsala           | 51        | 2.92%   |
| Lund              | 40        | 2.29%   |
| Linköping        | 37        | 2.12%   |
| Västerås        | 26        | 1.49%   |
| Norrköping       | 24        | 1.38%   |
| Bromma            | 24        | 1.38%   |
| Sollentuna        | 23        | 1.32%   |
| Vaxjo             | 21        | 1.2%    |
| Haegersten        | 19        | 1.09%   |
| Vaestra Froelunda | 18        | 1.03%   |
| Umeå             | 18        | 1.03%   |
| Solna             | 18        | 1.03%   |
| Örebro           | 18        | 1.03%   |
| Karlstad          | 18        | 1.03%   |
| Sundsvall         | 17        | 0.97%   |
| Huddinge          | 16        | 0.92%   |
| Södertälje      | 15        | 0.86%   |
| Helsingborg       | 14        | 0.8%    |
| Kista             | 13        | 0.75%   |
| Bandhagen         | 13        | 0.75%   |
| Taby              | 12        | 0.69%   |
| Moelndal          | 11        | 0.63%   |
| Karlskrona        | 11        | 0.63%   |
| Halmstad          | 11        | 0.63%   |
| Upplands Vasby    | 10        | 0.57%   |
| Sundbyberg        | 10        | 0.57%   |
| Staffanstorp      | 10        | 0.57%   |
| Landskrona        | 10        | 0.57%   |
| Gävle            | 10        | 0.57%   |
| Spanga            | 9         | 0.52%   |
| Nyköping         | 9         | 0.52%   |
| Norsborg          | 9         | 0.52%   |
| Mjoelby           | 9         | 0.52%   |
| Alvsjo            | 9         | 0.52%   |
| Skövde           | 8         | 0.46%   |
| Katrineholm       | 8         | 0.46%   |
| Johanneshov       | 8         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 533       | 861    | 21.75%  |
| WDC                         | 345       | 559    | 14.08%  |
| Seagate                     | 307       | 493    | 12.53%  |
| Kingston                    | 185       | 262    | 7.55%   |
| Intel                       | 138       | 180    | 5.63%   |
| Toshiba                     | 124       | 164    | 5.06%   |
| SanDisk                     | 119       | 154    | 4.86%   |
| Unknown                     | 88        | 114    | 3.59%   |
| Hitachi                     | 76        | 101    | 3.1%    |
| SK hynix                    | 63        | 71     | 2.57%   |
| Crucial                     | 57        | 84     | 2.33%   |
| Micron Technology           | 48        | 62     | 1.96%   |
| HGST                        | 42        | 49     | 1.71%   |
| Apple                       | 27        | 32     | 1.1%    |
| Phison                      | 21        | 25     | 0.86%   |
| OCZ                         | 21        | 24     | 0.86%   |
| Corsair                     | 20        | 27     | 0.82%   |
| A-DATA Technology           | 17        | 17     | 0.69%   |
| LITEON                      | 16        | 21     | 0.65%   |
| KIOXIA                      | 13        | 13     | 0.53%   |
| Transcend                   | 11        | 12     | 0.45%   |
| LITEONIT                    | 10        | 17     | 0.41%   |
| Intenso                     | 10        | 13     | 0.41%   |
| Fujitsu                     | 10        | 15     | 0.41%   |
| Silicon Motion              | 8         | 22     | 0.33%   |
| China                       | 8         | 8      | 0.33%   |
| PNY                         | 7         | 9      | 0.29%   |
| Kingston Technology Company | 7         | 7      | 0.29%   |
| Phison Electronics          | 6         | 7      | 0.24%   |
| Maxtor                      | 6         | 6      | 0.24%   |
| LaCie                       | 6         | 7      | 0.24%   |
| Unknown                     | 6         | 6      | 0.24%   |
| JMicron Technology          | 5         | 5      | 0.2%    |
| ASMT                        | 5         | 5      | 0.2%    |
| Micron/Crucial Technology   | 4         | 6      | 0.16%   |
| Lenovo                      | 4         | 4      | 0.16%   |
| Hewlett-Packard             | 4         | 6      | 0.16%   |
| XPG                         | 3         | 3      | 0.12%   |
| Union Memory                | 3         | 3      | 0.12%   |
| SPCC                        | 3         | 4      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                         | 45        | 1.6%    |
| Samsung SSD 850 EVO 500GB                         | 37        | 1.31%   |
| Kingston SV300S37A120G 120GB SSD                  | 27        | 0.96%   |
| Kingston SA400S37120G 120GB SSD                   | 27        | 0.96%   |
| Samsung NVMe SSD Drive 500GB                      | 25        | 0.89%   |
| Kingston SA400S37240G 240GB SSD                   | 25        | 0.89%   |
| Samsung SSD 860 EVO 250GB                         | 23        | 0.82%   |
| Samsung SSD 840 EVO 250GB                         | 23        | 0.82%   |
| Seagate ST4000DM004-2CV104 4TB                    | 20        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                      | 20        | 0.71%   |
| Samsung SSD 860 EVO 500GB                         | 18        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB                        | 17        | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                    | 17        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                    | 16        | 0.57%   |
| Samsung NVMe SSD Drive 1TB                        | 16        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                   | 16        | 0.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB            | 15        | 0.53%   |
| Samsung SSD 860 EVO 1TB                           | 14        | 0.5%    |
| Unknown MMC Card  32GB                            | 13        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                   | 13        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                      | 13        | 0.46%   |
| Samsung NVMe SSD Drive 250GB                      | 13        | 0.46%   |
| HGST HTS721010A9E630 1TB                          | 13        | 0.46%   |
| WDC WD30EFRX-68EUZN0 3TB                          | 12        | 0.43%   |
| Toshiba NVMe SSD Drive 512GB                      | 12        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                    | 12        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                      | 12        | 0.43%   |
| Samsung NVMe SSD Drive 1024GB                     | 12        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                     | 11        | 0.39%   |
| Seagate ST4000VN008-2DR166 4TB                    | 11        | 0.39%   |
| Samsung SSD 840 EVO 500GB                         | 11        | 0.39%   |
| Intel NVMe SSD Drive 1024GB                       | 11        | 0.39%   |
| Unknown MMC Card  16GB                            | 10        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                    | 10        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                      | 10        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 10        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 9         | 0.32%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 9         | 0.32%   |
| Unknown SD/MMC/MS PRO 8GB                         | 9         | 0.32%   |
| Seagate ST9500325AS 500GB                         | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 304       | 482    | 35.56%  |
| WDC                 | 270       | 447    | 31.58%  |
| Hitachi             | 76        | 101    | 8.89%   |
| Toshiba             | 70        | 95     | 8.19%   |
| Samsung Electronics | 49        | 83     | 5.73%   |
| HGST                | 42        | 49     | 4.91%   |
| Unknown             | 10        | 12     | 1.17%   |
| Fujitsu             | 10        | 15     | 1.17%   |
| Apple               | 6         | 6      | 0.7%    |
| Maxtor              | 5         | 5      | 0.58%   |
| ASMT                | 4         | 4      | 0.47%   |
| Intenso             | 2         | 2      | 0.23%   |
| Hewlett-Packard     | 2         | 4      | 0.23%   |
| USB3.0              | 1         | 1      | 0.12%   |
| MARVELL             | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| IB                  | 1         | 2      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 313       | 459    | 33.33%  |
| Kingston            | 142       | 198    | 15.12%  |
| Intel               | 83        | 104    | 8.84%   |
| SanDisk             | 61        | 77     | 6.5%    |
| Crucial             | 55        | 81     | 5.86%   |
| WDC                 | 48        | 68     | 5.11%   |
| Micron Technology   | 35        | 47     | 3.73%   |
| OCZ                 | 21        | 24     | 2.24%   |
| SK hynix            | 20        | 23     | 2.13%   |
| Apple               | 18        | 22     | 1.92%   |
| Toshiba             | 17        | 24     | 1.81%   |
| LITEON              | 15        | 20     | 1.6%    |
| Corsair             | 12        | 14     | 1.28%   |
| Transcend           | 11        | 12     | 1.17%   |
| A-DATA Technology   | 11        | 11     | 1.17%   |
| LITEONIT            | 10        | 17     | 1.06%   |
| China               | 8         | 8      | 0.85%   |
| Intenso             | 7         | 7      | 0.75%   |
| PNY                 | 5         | 7      | 0.53%   |
| SPCC                | 3         | 4      | 0.32%   |
| JMicron Technology  | 3         | 3      | 0.32%   |
| Verbatim            | 2         | 3      | 0.21%   |
| Seagate             | 2         | 4      | 0.21%   |
| Patriot             | 2         | 3      | 0.21%   |
| M4-CT128            | 2         | 2      | 0.21%   |
| GOODRAM             | 2         | 3      | 0.21%   |
| XSTAR               | 1         | 1      | 0.11%   |
| WDC WDS2            | 1         | 1      | 0.11%   |
| WDC WDS1            | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| tigo                | 1         | 1      | 0.11%   |
| StoreJet            | 1         | 1      | 0.11%   |
| Star                | 1         | 1      | 0.11%   |
| SSSTC               | 1         | 1      | 0.11%   |
| SATAFIRM            | 1         | 1      | 0.11%   |
| ROG                 | 1         | 1      | 0.11%   |
| Radeon              | 1         | 1      | 0.11%   |
| Phison              | 1         | 1      | 0.11%   |
| OWC                 | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 802       | 1277   | 36.72%  |
| HDD     | 690       | 1311   | 31.59%  |
| NVMe    | 580       | 823    | 26.56%  |
| MMC     | 81        | 97     | 3.71%   |
| Unknown | 31        | 40     | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1201      | 2492   | 61.18%  |
| NVMe | 578       | 816    | 29.44%  |
| SAS  | 103       | 143    | 5.25%   |
| MMC  | 81        | 97     | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 984       | 1612   | 60.48%  |
| 0.51-1.0   | 356       | 530    | 21.88%  |
| 1.01-2.0   | 134       | 197    | 8.24%   |
| 3.01-4.0   | 62        | 106    | 3.81%   |
| 2.01-3.0   | 54        | 84     | 3.32%   |
| 4.01-10.0  | 33        | 54     | 2.03%   |
| 10.01-20.0 | 4         | 5      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 482       | 27.72%  |
| 251-500        | 381       | 21.91%  |
| 501-1000       | 225       | 12.94%  |
| 1-20           | 147       | 8.45%   |
| 1001-2000      | 136       | 7.82%   |
| More than 3000 | 116       | 6.67%   |
| 51-100         | 83        | 4.77%   |
| Unknown        | 66        | 3.8%    |
| 2001-3000      | 55        | 3.16%   |
| 21-50          | 48        | 2.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 695       | 38.98%  |
| 21-50          | 250       | 14.02%  |
| 101-250        | 226       | 12.68%  |
| 51-100         | 183       | 10.26%  |
| 251-500        | 128       | 7.18%   |
| 501-1000       | 98        | 5.5%    |
| Unknown        | 66        | 3.7%    |
| 1001-2000      | 58        | 3.25%   |
| More than 3000 | 43        | 2.41%   |
| 2001-3000      | 34        | 1.91%   |
| 0              | 2         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 3.88%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 2.33%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.55%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.55%   |
| Seagate ST9250410AS 250GB                      | 2         | 3      | 1.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.55%   |
| Samsung Electronics SSD 870 EVO 1TB            | 2         | 2      | 1.55%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.55%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.55%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 3      | 1.55%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.55%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.55%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.78%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.78%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.78%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.78%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.78%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.78%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.78%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 1      | 0.78%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.78%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.78%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.78%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 3      | 0.78%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.78%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.78%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.78%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.78%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 1         | 2      | 0.78%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.78%   |
| WDC WD10EFRX-68FYTN0 1TB                       | 1         | 1      | 0.78%   |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.78%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 0.78%   |
| WDC WD10EALX-009BA0 1TB                        | 1         | 3      | 0.78%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 0.78%   |
| WDC WD10EADS-00L5B1 1TB                        | 1         | 1      | 0.78%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB        | 1         | 1      | 0.78%   |
| Transcend TS240GMTS420S 240GB SSD              | 1         | 1      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 22.58%  |
| WDC                 | 24        | 43     | 19.35%  |
| Samsung Electronics | 15        | 15     | 12.1%   |
| Intel               | 12        | 15     | 9.68%   |
| Hitachi             | 11        | 13     | 8.87%   |
| HGST                | 5         | 5      | 4.03%   |
| Kingston            | 4         | 4      | 3.23%   |
| OCZ                 | 3         | 5      | 2.42%   |
| Micron Technology   | 3         | 4      | 2.42%   |
| Crucial             | 3         | 3      | 2.42%   |
| Corsair             | 3         | 3      | 2.42%   |
| Toshiba             | 2         | 3      | 1.61%   |
| LITEONIT            | 2         | 2      | 1.61%   |
| Fujitsu             | 2         | 2      | 1.61%   |
| Union Memory        | 1         | 1      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| SK hynix            | 1         | 1      | 0.81%   |
| SanDisk             | 1         | 1      | 0.81%   |
| PNY                 | 1         | 2      | 0.81%   |
| Hewlett-Packard     | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 34.15%  |
| WDC                 | 23        | 42     | 28.05%  |
| Hitachi             | 11        | 13     | 13.41%  |
| Samsung Electronics | 9         | 9      | 10.98%  |
| HGST                | 5         | 5      | 6.1%    |
| Toshiba             | 2         | 3      | 2.44%   |
| Fujitsu             | 2         | 2      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 1.22%   |
| Apple               | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 79        | 110    | 66.39%  |
| SSD  | 35        | 44     | 29.41%  |
| NVMe | 5         | 5      | 4.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1091      | 2282   | 60.88%  |
| Works    | 586       | 1106   | 32.7%   |
| Malfunc  | 114       | 159    | 6.36%   |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1044      | 49.25%  |
| AMD                              | 357       | 16.84%  |
| Samsung Electronics              | 258       | 12.17%  |
| SanDisk                          | 87        | 4.1%    |
| Kingston Technology Company      | 51        | 2.41%   |
| Toshiba America Info Systems     | 42        | 1.98%   |
| SK hynix                         | 42        | 1.98%   |
| ASMedia Technology               | 37        | 1.75%   |
| Phison Electronics               | 34        | 1.6%    |
| JMicron Technology               | 31        | 1.46%   |
| Marvell Technology Group         | 28        | 1.32%   |
| Nvidia                           | 18        | 0.85%   |
| Micron Technology                | 14        | 0.66%   |
| KIOXIA                           | 11        | 0.52%   |
| Silicon Motion                   | 9         | 0.42%   |
| ADATA Technology                 | 7         | 0.33%   |
| Silicon Image                    | 6         | 0.28%   |
| Union Memory (Shenzhen)          | 5         | 0.24%   |
| Micron/Crucial Technology        | 5         | 0.24%   |
| Lite-On Technology               | 5         | 0.24%   |
| VIA Technologies                 | 4         | 0.19%   |
| Lenovo                           | 4         | 0.19%   |
| Apple                            | 4         | 0.19%   |
| Solid State Storage Technology   | 3         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |
| Broadcom / LSI                   | 3         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.09%   |
| LSI Logic / Symbios Logic        | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| Seagate Technology               | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 240       | 9.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 149       | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 80        | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 75        | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 64        | 2.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 60        | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 53        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 48        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 47        | 1.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 44        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 41        | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 38        | 1.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 36        | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 33        | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 1.3%    |
| Intel SATA Controller [RAID mode]                                              | 31        | 1.26%   |
| Intel SSD 660P Series                                                          | 30        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 30        | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 28        | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 28        | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 28        | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                | 27        | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 27        | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 26        | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 20        | 0.81%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 0.77%   |
| Phison E12 NVMe Controller                                                     | 18        | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 17        | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                             | 16        | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 16        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1194      | 56.27%  |
| NVMe | 586       | 27.62%  |
| IDE  | 209       | 9.85%   |
| RAID | 125       | 5.89%   |
| SAS  | 6         | 0.28%   |
| SCSI | 2         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1202      | 73.43%  |
| AMD      | 419       | 25.6%   |
| ARM      | 15        | 0.92%   |
| QUALCOMM | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 23        | 1.4%    |
| AMD Ryzen 5 3600 6-Core Processor       | 23        | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 22        | 1.34%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 18        | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 15        | 0.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 15        | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 14        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 12        | 0.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 12        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 11        | 0.67%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 11        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 10        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 0.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 10        | 0.61%   |
| ARM Processor                           | 10        | 0.61%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 10        | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 9         | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 9         | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 9         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 8         | 0.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 8         | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 8         | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 8         | 0.49%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 8         | 0.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 8         | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 7         | 0.43%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.43%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 396       | 24.19%  |
| Intel Core i7           | 393       | 24.01%  |
| AMD Ryzen 5             | 109       | 6.66%   |
| Other                   | 85        | 5.19%   |
| AMD Ryzen 7             | 81        | 4.95%   |
| Intel Core i3           | 69        | 4.22%   |
| Intel Core 2 Duo        | 55        | 3.36%   |
| Intel Celeron           | 53        | 3.24%   |
| Intel Xeon              | 37        | 2.26%   |
| AMD Ryzen 9             | 35        | 2.14%   |
| AMD FX                  | 31        | 1.89%   |
| Intel Pentium           | 30        | 1.83%   |
| Intel Atom              | 23        | 1.41%   |
| AMD Ryzen 3             | 19        | 1.16%   |
| Intel Core 2 Quad       | 15        | 0.92%   |
| Intel Core i9           | 14        | 0.86%   |
| AMD A8                  | 13        | 0.79%   |
| Intel Core 2            | 12        | 0.73%   |
| AMD Ryzen Threadripper  | 11        | 0.67%   |
| AMD A6                  | 10        | 0.61%   |
| Intel Pentium Dual-Core | 9         | 0.55%   |
| Intel Genuine           | 9         | 0.55%   |
| AMD A4                  | 9         | 0.55%   |
| AMD Phenom II X4        | 8         | 0.49%   |
| AMD E1                  | 7         | 0.43%   |
| AMD E                   | 7         | 0.43%   |
| AMD Athlon II X2        | 6         | 0.37%   |
| AMD Athlon 64 X2        | 6         | 0.37%   |
| AMD A10                 | 6         | 0.37%   |
| Intel Pentium Dual      | 5         | 0.31%   |
| ARM BCM                 | 5         | 0.31%   |
| AMD Ryzen Embedded      | 5         | 0.31%   |
| AMD Ryzen 7 PRO         | 5         | 0.31%   |
| AMD Phenom II X6        | 5         | 0.31%   |
| AMD Ryzen 5 PRO         | 4         | 0.24%   |
| Intel Pentium Silver    | 3         | 0.18%   |
| AMD Athlon II X3        | 3         | 0.18%   |
| Intel Pentium M         | 2         | 0.12%   |
| Intel Pentium Gold      | 2         | 0.12%   |
| Intel Core m3           | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 649       | 39.57%  |
| 2       | 549       | 33.48%  |
| 6       | 202       | 12.32%  |
| 8       | 125       | 7.62%   |
| 12      | 32        | 1.95%   |
| 1       | 26        | 1.59%   |
| 16      | 25        | 1.52%   |
| 3       | 15        | 0.91%   |
| 18      | 3         | 0.18%   |
| 14      | 3         | 0.18%   |
| 10      | 3         | 0.18%   |
| Unknown | 3         | 0.18%   |
| 32      | 2         | 0.12%   |
| 64      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1615      | 98.66%  |
| 2       | 19        | 1.16%   |
| Unknown | 2         | 0.12%   |
| 3       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1110      | 67.68%  |
| 1       | 527       | 32.13%  |
| Unknown | 3         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1589      | 96.83%  |
| Unknown        | 41        | 2.5%    |
| 32-bit         | 10        | 0.61%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 420       | 24.68%  |
| 0x306c3    | 90        | 5.29%   |
| 0x206a7    | 82        | 4.82%   |
| 0x306a9    | 79        | 4.64%   |
| 0x1067a    | 47        | 2.76%   |
| 0x906ea    | 46        | 2.7%    |
| 0x40651    | 45        | 2.64%   |
| 0x806ec    | 42        | 2.47%   |
| 0x906e9    | 40        | 2.35%   |
| 0x406e3    | 38        | 2.23%   |
| 0x806ea    | 37        | 2.17%   |
| 0x506e3    | 37        | 2.17%   |
| 0x806e9    | 33        | 1.94%   |
| 0x306d4    | 32        | 1.88%   |
| 0x08701021 | 32        | 1.88%   |
| 0x806c1    | 30        | 1.76%   |
| 0x20655    | 26        | 1.53%   |
| 0x0800820d | 19        | 1.12%   |
| 0x08701013 | 18        | 1.06%   |
| 0x08108109 | 17        | 1%      |
| 0x906ed    | 14        | 0.82%   |
| 0x406c4    | 14        | 0.82%   |
| 0x0810100b | 14        | 0.82%   |
| 0x6fd      | 13        | 0.76%   |
| 0x0a50000c | 13        | 0.76%   |
| 0x06000852 | 13        | 0.76%   |
| 0x010000c8 | 13        | 0.76%   |
| 0x106e5    | 12        | 0.71%   |
| 0x0a201009 | 12        | 0.71%   |
| 0x6f6      | 11        | 0.65%   |
| 0x306f2    | 11        | 0.65%   |
| 0x30678    | 11        | 0.65%   |
| 0x10676    | 11        | 0.65%   |
| 0x08600106 | 11        | 0.65%   |
| 0xa0652    | 10        | 0.59%   |
| 0x806eb    | 10        | 0.59%   |
| 0x08108102 | 10        | 0.59%   |
| 0x06001119 | 10        | 0.59%   |
| 0x08001138 | 9         | 0.53%   |
| 0x0700010f | 9         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 298       | 18.19%  |
| Haswell          | 183       | 11.17%  |
| SandyBridge      | 116       | 7.08%   |
| IvyBridge        | 104       | 6.35%   |
| Skylake          | 103       | 6.29%   |
| Zen 2            | 94        | 5.74%   |
| Penryn           | 67        | 4.09%   |
| Zen+             | 63        | 3.85%   |
| Zen 3            | 51        | 3.11%   |
| Zen              | 47        | 2.87%   |
| Core             | 45        | 2.75%   |
| Westmere         | 44        | 2.69%   |
| Broadwell        | 44        | 2.69%   |
| Unknown          | 44        | 2.69%   |
| Silvermont       | 42        | 2.56%   |
| TigerLake        | 41        | 2.5%    |
| K10              | 36        | 2.2%    |
| Piledriver       | 32        | 1.95%   |
| CometLake        | 26        | 1.59%   |
| Nehalem          | 18        | 1.1%    |
| Goldmont plus    | 16        | 0.98%   |
| Excavator        | 14        | 0.85%   |
| IceLake          | 13        | 0.79%   |
| K8 Hammer        | 12        | 0.73%   |
| Alderlake Hybrid | 12        | 0.73%   |
| K10 Llano        | 11        | 0.67%   |
| Jaguar           | 10        | 0.61%   |
| Bulldozer        | 10        | 0.61%   |
| Bobcat           | 9         | 0.55%   |
| Goldmont         | 7         | 0.43%   |
| Puma             | 6         | 0.37%   |
| Bonnell          | 6         | 0.37%   |
| P6               | 4         | 0.24%   |
| NetBurst         | 3         | 0.18%   |
| Steamroller      | 2         | 0.12%   |
| K8 & K10 hybrid  | 2         | 0.12%   |
| Tremont          | 1         | 0.06%   |
| K6               | 1         | 0.06%   |
| Geode            | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 841       | 44.24%  |
| Nvidia                           | 614       | 32.3%   |
| AMD                              | 429       | 22.57%  |
| Matrox Electronics Systems       | 7         | 0.37%   |
| ASPEED Technology                | 7         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 76        | 3.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 53        | 2.7%    |
| Intel UHD Graphics 620                                                                   | 43        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 2.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 41        | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 37        | 1.88%   |
| Intel HD Graphics 620                                                                    | 34        | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 1.73%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.42%   |
| Intel HD Graphics 630                                                                    | 28        | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 1.22%   |
| AMD Renoir                                                                               | 24        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 24        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 21        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 19        | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 16        | 0.81%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 16        | 0.81%   |
| Intel HD Graphics 530                                                                    | 16        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14        | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 14        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.71%   |
| AMD Lucienne                                                                             | 14        | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 13        | 0.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.66%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 13        | 0.66%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 13        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 596       | 36.1%   |
| 1 x Nvidia               | 395       | 23.92%  |
| 1 x AMD                  | 350       | 21.2%   |
| Intel + Nvidia           | 190       | 11.51%  |
| Intel + AMD              | 30        | 1.82%   |
| 2 x AMD                  | 28        | 1.7%    |
| AMD + Nvidia             | 22        | 1.33%   |
| Other                    | 16        | 0.97%   |
| 1 x ASPEED               | 7         | 0.42%   |
| 1 x Matrox               | 5         | 0.3%    |
| 2 x Nvidia               | 4         | 0.24%   |
| 1 x SiS                  | 3         | 0.18%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.06%   |
| 2 x Intel                | 1         | 0.06%   |
| Nvidia + Matrox          | 1         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1221      | 73.29%  |
| Proprietary | 371       | 22.27%  |
| Unknown     | 74        | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 877       | 51.99%  |
| 1.01-2.0   | 199       | 11.8%   |
| 0.01-0.5   | 169       | 10.02%  |
| 0.51-1.0   | 118       | 6.99%   |
| 3.01-4.0   | 114       | 6.76%   |
| 7.01-8.0   | 103       | 6.11%   |
| 5.01-6.0   | 55        | 3.26%   |
| 8.01-16.0  | 29        | 1.72%   |
| 2.01-3.0   | 20        | 1.19%   |
| 16.01-24.0 | 3         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 236       | 12.68%  |
| Samsung Electronics     | 220       | 11.82%  |
| LG Display              | 134       | 7.2%    |
| Chimei Innolux          | 126       | 6.77%   |
| Dell                    | 111       | 5.96%   |
| BenQ                    | 97        | 5.21%   |
| Philips                 | 95        | 5.1%    |
| Ancor Communications    | 85        | 4.57%   |
| BOE                     | 75        | 4.03%   |
| AOC                     | 75        | 4.03%   |
| Hewlett-Packard         | 74        | 3.98%   |
| Acer                    | 66        | 3.55%   |
| Sharp                   | 49        | 2.63%   |
| Goldstar                | 48        | 2.58%   |
| Apple                   | 42        | 2.26%   |
| Lenovo                  | 38        | 2.04%   |
| ASUSTek Computer        | 29        | 1.56%   |
| Eizo                    | 20        | 1.07%   |
| Chi Mei Optoelectronics | 20        | 1.07%   |
| LG Philips              | 16        | 0.86%   |
| InfoVision              | 16        | 0.86%   |
| MSI                     | 13        | 0.7%    |
| Vestel Elektronik       | 12        | 0.64%   |
| Sony                    | 12        | 0.64%   |
| Unknown                 | 11        | 0.59%   |
| LG Electronics          | 10        | 0.54%   |
| Panasonic               | 9         | 0.48%   |
| CSO                     | 9         | 0.48%   |
| ViewSonic               | 8         | 0.43%   |
| PANDA                   | 6         | 0.32%   |
| VOXICON                 | 5         | 0.27%   |
| Toshiba                 | 5         | 0.27%   |
| Fujitsu Siemens         | 5         | 0.27%   |
| BOE Technology Group    | 5         | 0.27%   |
| Quanta Display          | 4         | 0.21%   |
| OEM                     | 4         | 0.21%   |
| Microstep               | 4         | 0.21%   |
| LGD                     | 4         | 0.21%   |
| AUS                     | 4         | 0.21%   |
| Packard Bell            | 3         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 12        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 11        | 0.57%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 10        | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8         | 0.41%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                   | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 8         | 0.41%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8         | 0.41%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 7         | 0.36%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 7         | 0.36%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 6         | 0.31%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 6         | 0.31%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 6         | 0.31%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 6         | 0.31%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 6         | 0.31%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch              | 5         | 0.26%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 5         | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 5         | 0.26%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 5         | 0.26%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 5         | 0.26%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 4         | 0.21%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 4         | 0.21%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 4         | 0.21%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch            | 4         | 0.21%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                        | 4         | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 4         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 4         | 0.21%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch           | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 790       | 44.06%  |
| 1366x768 (WXGA)    | 210       | 11.71%  |
| 2560x1440 (QHD)    | 150       | 8.37%   |
| 3840x2160 (4K)     | 145       | 8.09%   |
| 1680x1050 (WSXGA+) | 65        | 3.63%   |
| 1920x1200 (WUXGA)  | 60        | 3.35%   |
| 3440x1440          | 42        | 2.34%   |
| 1600x900 (HD+)     | 39        | 2.18%   |
| 1280x1024 (SXGA)   | 39        | 2.18%   |
| 1280x800 (WXGA)    | 37        | 2.06%   |
| Unknown            | 34        | 1.9%    |
| 1440x900 (WXGA+)   | 24        | 1.34%   |
| 3840x1080          | 18        | 1%      |
| 2560x1600          | 18        | 1%      |
| 3840x2400          | 15        | 0.84%   |
| 2880x1800          | 15        | 0.84%   |
| 1024x768 (XGA)     | 11        | 0.61%   |
| 1360x768           | 9         | 0.5%    |
| 1920x540           | 7         | 0.39%   |
| 1280x720 (HD)      | 7         | 0.39%   |
| 3200x1800 (QHD+)   | 5         | 0.28%   |
| 2736x1824          | 5         | 0.28%   |
| 2560x1080          | 5         | 0.28%   |
| 1024x600           | 5         | 0.28%   |
| 800x1280           | 3         | 0.17%   |
| 6400x2160          | 3         | 0.17%   |
| 5760x1080          | 3         | 0.17%   |
| 2288x1287          | 3         | 0.17%   |
| 2160x1440          | 3         | 0.17%   |
| 5760x2160          | 2         | 0.11%   |
| 3840x1600          | 2         | 0.11%   |
| 3840x1200          | 2         | 0.11%   |
| 3200x1200          | 2         | 0.11%   |
| 1280x768           | 2         | 0.11%   |
| 7280x2160          | 1         | 0.06%   |
| 5520x2160          | 1         | 0.06%   |
| 4864x1080          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 4240x1440          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 346       | 18.68%  |
| 27      | 204       | 11.02%  |
| 24      | 199       | 10.75%  |
| 13      | 197       | 10.64%  |
| Unknown | 134       | 7.24%   |
| 14      | 131       | 7.07%   |
| 23      | 122       | 6.59%   |
| 17      | 71        | 3.83%   |
| 12      | 52        | 2.81%   |
| 22      | 48        | 2.59%   |
| 21      | 46        | 2.48%   |
| 31      | 42        | 2.27%   |
| 34      | 39        | 2.11%   |
| 19      | 38        | 2.05%   |
| 84      | 25        | 1.35%   |
| 11      | 24        | 1.3%    |
| 32      | 16        | 0.86%   |
| 54      | 10        | 0.54%   |
| 20      | 10        | 0.54%   |
| 72      | 9         | 0.49%   |
| 65      | 8         | 0.43%   |
| 25      | 8         | 0.43%   |
| 18      | 7         | 0.38%   |
| 42      | 6         | 0.32%   |
| 16      | 6         | 0.32%   |
| 39      | 5         | 0.27%   |
| 35      | 5         | 0.27%   |
| 29      | 5         | 0.27%   |
| 10      | 5         | 0.27%   |
| 49      | 4         | 0.22%   |
| 48      | 4         | 0.22%   |
| 50      | 3         | 0.16%   |
| 46      | 3         | 0.16%   |
| 37      | 3         | 0.16%   |
| 55      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 26      | 2         | 0.11%   |
| 142     | 1         | 0.05%   |
| 75      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 570       | 31.49%  |
| 501-600        | 479       | 26.46%  |
| 201-300        | 189       | 10.44%  |
| Unknown        | 134       | 7.4%    |
| 401-500        | 121       | 6.69%   |
| 351-400        | 99        | 5.47%   |
| 601-700        | 65        | 3.59%   |
| 701-800        | 57        | 3.15%   |
| 1001-1500      | 38        | 2.1%    |
| 1501-2000      | 36        | 1.99%   |
| 801-900        | 12        | 0.66%   |
| 901-1000       | 9         | 0.5%    |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1167      | 70.22%  |
| 16/10   | 245       | 14.74%  |
| Unknown | 122       | 7.34%   |
| 21/9    | 46        | 2.77%   |
| 5/4     | 40        | 2.41%   |
| 3/2     | 16        | 0.96%   |
| 4/3     | 14        | 0.84%   |
| 32/9    | 7         | 0.42%   |
| 0.62    | 3         | 0.18%   |
| 1.00    | 1         | 0.06%   |
| 0.45    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 344       | 18.9%   |
| 201-250        | 307       | 16.87%  |
| 81-90          | 237       | 13.02%  |
| 301-350        | 206       | 11.32%  |
| Unknown        | 134       | 7.36%   |
| 351-500        | 105       | 5.77%   |
| 71-80          | 91        | 5%      |
| 251-300        | 81        | 4.45%   |
| More than 1000 | 63        | 3.46%   |
| 151-200        | 57        | 3.13%   |
| 121-130        | 55        | 3.02%   |
| 61-70          | 49        | 2.69%   |
| 501-1000       | 29        | 1.59%   |
| 51-60          | 24        | 1.32%   |
| 141-150        | 14        | 0.77%   |
| 131-140        | 9         | 0.49%   |
| 111-120        | 6         | 0.33%   |
| 41-50          | 5         | 0.27%   |
| 91-100         | 4         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 574       | 32.5%   |
| 121-160       | 447       | 25.31%  |
| 101-120       | 368       | 20.84%  |
| Unknown       | 134       | 7.59%   |
| 161-240       | 128       | 7.25%   |
| More than 240 | 65        | 3.68%   |
| 1-50          | 50        | 2.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1243      | 73.94%  |
| 2     | 315       | 18.74%  |
| 0     | 86        | 5.12%   |
| 3     | 33        | 1.96%   |
| 4     | 4         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 916       | 38.76%  |
| Realtek Semiconductor                  | 710       | 30.05%  |
| Qualcomm Atheros                       | 241       | 10.2%   |
| Broadcom                               | 148       | 6.26%   |
| Broadcom Limited                       | 37        | 1.57%   |
| Marvell Technology Group               | 25        | 1.06%   |
| Ralink                                 | 20        | 0.85%   |
| MediaTek                               | 20        | 0.85%   |
| Hewlett-Packard                        | 15        | 0.63%   |
| Nvidia                                 | 14        | 0.59%   |
| D-Link System                          | 14        | 0.59%   |
| ASUSTek Computer                       | 13        | 0.55%   |
| ASIX Electronics                       | 13        | 0.55%   |
| NetGear                                | 12        | 0.51%   |
| Microsoft                              | 12        | 0.51%   |
| Lenovo                                 | 11        | 0.47%   |
| Dell                                   | 11        | 0.47%   |
| D-Link                                 | 11        | 0.47%   |
| TP-Link                                | 10        | 0.42%   |
| Ralink Technology                      | 10        | 0.42%   |
| Huawei Technologies                    | 9         | 0.38%   |
| Sierra Wireless                        | 8         | 0.34%   |
| DisplayLink                            | 7         | 0.3%    |
| Ericsson Business Mobile Networks      | 6         | 0.25%   |
| Qualcomm Atheros Communications        | 5         | 0.21%   |
| Qualcomm                               | 4         | 0.17%   |
| Fibocom                                | 4         | 0.17%   |
| Aquantia                               | 4         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.13%   |
| Samsung Electronics                    | 3         | 0.13%   |
| Belkin Components                      | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.08%   |
| Texas Instruments                      | 2         | 0.08%   |
| Standard Microsystems                  | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| Microchip Technology                   | 2         | 0.08%   |
| Linksys                                | 2         | 0.08%   |
| ICS Advent                             | 2         | 0.08%   |
| Edimax Technology                      | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 512       | 18.1%   |
| Intel I211 Gigabit Network Connection                             | 88        | 3.11%   |
| Intel Wi-Fi 6 AX200                                               | 76        | 2.69%   |
| Intel Wireless 8265 / 8275                                        | 72        | 2.55%   |
| Intel Wireless 7260                                               | 59        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 1.66%   |
| Intel Wireless 8260                                               | 44        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.41%   |
| Intel Wireless 7265                                               | 38        | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 35        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 33        | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 29        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 22        | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 21        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 21        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.6%    |
| Intel Wireless-AC 9260                                            | 17        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 16        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 638       | 51.45%  |
| Qualcomm Atheros                | 182       | 14.68%  |
| Realtek Semiconductor           | 145       | 11.69%  |
| Broadcom                        | 96        | 7.74%   |
| Ralink                          | 20        | 1.61%   |
| MediaTek                        | 20        | 1.61%   |
| Broadcom Limited                | 20        | 1.61%   |
| ASUSTek Computer                | 13        | 1.05%   |
| NetGear                         | 12        | 0.97%   |
| Ralink Technology               | 10        | 0.81%   |
| D-Link System                   | 10        | 0.81%   |
| D-Link                          | 10        | 0.81%   |
| Sierra Wireless                 | 8         | 0.65%   |
| Microsoft                       | 8         | 0.65%   |
| Hewlett-Packard                 | 8         | 0.65%   |
| TP-Link                         | 7         | 0.56%   |
| Qualcomm Atheros Communications | 5         | 0.4%    |
| Dell                            | 5         | 0.4%    |
| Marvell Technology Group        | 4         | 0.32%   |
| Fibocom                         | 4         | 0.32%   |
| Belkin Components               | 3         | 0.24%   |
| Qualcomm                        | 2         | 0.16%   |
| Linksys                         | 2         | 0.16%   |
| Edimax Technology               | 2         | 0.16%   |
| Wilocity                        | 1         | 0.08%   |
| Wacom                           | 1         | 0.08%   |
| Sitecom Europe                  | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| IMC Networks                    | 1         | 0.08%   |
| Chu Yuen Enterprise             | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 76        | 6.1%    |
| Intel Wireless 8265 / 8275                                     | 72        | 5.78%   |
| Intel Wireless 7260                                            | 59        | 4.74%   |
| Intel Wireless 8260                                            | 44        | 3.53%   |
| Intel Wireless 7265                                            | 38        | 3.05%   |
| Intel Wi-Fi 6 AX201                                            | 35        | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 29        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 25        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 21        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.37%   |
| Intel Wireless-AC 9260                                         | 17        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 1.29%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 16        | 1.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 15        | 1.2%    |
| Intel Wireless 3160                                            | 14        | 1.12%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 1.04%   |
| Intel Wireless 3165                                            | 13        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 1.04%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 0.96%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 12        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 10        | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.64%   |
| Intel Centrino Wireless-N 2230                                 | 8         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 656       | 43.59%  |
| Intel                                  | 558       | 37.08%  |
| Qualcomm Atheros                       | 88        | 5.85%   |
| Broadcom                               | 71        | 4.72%   |
| Marvell Technology Group               | 21        | 1.4%    |
| Broadcom Limited                       | 18        | 1.2%    |
| Nvidia                                 | 14        | 0.93%   |
| ASIX Electronics                       | 13        | 0.86%   |
| Lenovo                                 | 10        | 0.66%   |
| Huawei Technologies                    | 7         | 0.47%   |
| DisplayLink                            | 7         | 0.47%   |
| Microsoft                              | 4         | 0.27%   |
| D-Link System                          | 4         | 0.27%   |
| Aquantia                               | 4         | 0.27%   |
| TP-Link                                | 3         | 0.2%    |
| Samsung Electronics                    | 3         | 0.2%    |
| ZTE WCDMA Technologies MSM             | 2         | 0.13%   |
| Standard Microsystems                  | 2         | 0.13%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.13%   |
| Qualcomm                               | 2         | 0.13%   |
| Microchip Technology                   | 2         | 0.13%   |
| ICS Advent                             | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.07%   |
| VIA Technologies                       | 1         | 0.07%   |
| Unknown                                | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| JMicron Technology                     | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| Gemtek                                 | 1         | 0.07%   |
| D-Link                                 | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 512       | 33.23%  |
| Intel I211 Gigabit Network Connection                             | 88        | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 3.05%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 22        | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 21        | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 19        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 1.17%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.91%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.45%   |
| Intel 82566MM Gigabit Network Connection                          | 7         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1425      | 54.04%  |
| WiFi     | 1170      | 44.37%  |
| Modem    | 35        | 1.33%   |
| Unknown  | 7         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 875       | 51.5%   |
| Ethernet | 822       | 48.38%  |
| Unknown  | 2         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 847       | 51.58%  |
| 1     | 701       | 42.69%  |
| 3     | 45        | 2.74%   |
| 0     | 34        | 2.07%   |
| 4     | 8         | 0.49%   |
| 5     | 5         | 0.3%    |
| 9     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1599      | 97.2%   |
| Yes  | 46        | 2.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 507       | 51.58%  |
| Realtek Semiconductor           | 62        | 6.31%   |
| Qualcomm Atheros Communications | 60        | 6.1%    |
| ASUSTek Computer                | 53        | 5.39%   |
| Cambridge Silicon Radio         | 50        | 5.09%   |
| Apple                           | 46        | 4.68%   |
| IMC Networks                    | 43        | 4.37%   |
| Broadcom                        | 41        | 4.17%   |
| Foxconn / Hon Hai               | 29        | 2.95%   |
| Lite-On Technology              | 26        | 2.64%   |
| Hewlett-Packard                 | 16        | 1.63%   |
| Dell                            | 15        | 1.53%   |
| Ralink                          | 7         | 0.71%   |
| Toshiba                         | 4         | 0.41%   |
| MediaTek                        | 4         | 0.41%   |
| Marvell Semiconductor           | 4         | 0.41%   |
| Realtek                         | 3         | 0.31%   |
| Ralink Technology               | 2         | 0.2%    |
| Micro Star International        | 2         | 0.2%    |
| HTC (High Tech Computer)        | 2         | 0.2%    |
| Chicony Electronics             | 2         | 0.2%    |
| USI                             | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Creative Technology             | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |
| Unknown                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 224       | 22.67%  |
| Intel AX201 Bluetooth                               | 80        | 8.1%    |
| Intel AX200 Bluetooth                               | 73        | 7.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 53        | 5.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 5.06%   |
| Realtek Bluetooth Radio                             | 46        | 4.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 24        | 2.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.92%   |
| Apple Bluetooth Host Controller                     | 19        | 1.92%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.52%   |
| Apple Bluetooth USB Host Controller                 | 14        | 1.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 1.32%   |
| Intel AX210 Bluetooth                               | 13        | 1.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 1.21%   |
| IMC Networks Bluetooth Device                       | 12        | 1.21%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 1.01%   |
| Lite-On Bluetooth Device                            | 9         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.61%   |
| Intel Bluetooth Device                              | 6         | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.61%   |
| ASUS Bluetooth Radio                                | 6         | 0.61%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.51%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.51%   |
| IMC Networks Wireless_Device                        | 4         | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 4         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1136      | 46.77%  |
| AMD                                             | 500       | 20.58%  |
| Nvidia                                          | 457       | 18.81%  |
| C-Media Electronics                             | 45        | 1.85%   |
| Logitech                                        | 29        | 1.19%   |
| Kingston Technology                             | 16        | 0.66%   |
| Creative Labs                                   | 16        | 0.66%   |
| Realtek Semiconductor                           | 15        | 0.62%   |
| Plantronics                                     | 13        | 0.54%   |
| Texas Instruments                               | 12        | 0.49%   |
| Focusrite-Novation                              | 11        | 0.45%   |
| Creative Technology                             | 11        | 0.45%   |
| SteelSeries ApS                                 | 10        | 0.41%   |
| Lenovo                                          | 9         | 0.37%   |
| Razer USA                                       | 8         | 0.33%   |
| Corsair                                         | 8         | 0.33%   |
| SAVITECH                                        | 7         | 0.29%   |
| RODE Microphones                                | 7         | 0.29%   |
| GN Netcom                                       | 5         | 0.21%   |
| ASUSTek Computer                                | 5         | 0.21%   |
| Yamaha                                          | 4         | 0.16%   |
| Sennheiser Communications                       | 4         | 0.16%   |
| Micro Star International                        | 4         | 0.16%   |
| JMTek                                           | 4         | 0.16%   |
| GYROCOM C&C                                     | 4         | 0.16%   |
| Blue Microphones                                | 4         | 0.16%   |
| VIA Technologies                                | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]                | 3         | 0.12%   |
| Samson Technologies                             | 3         | 0.12%   |
| PreSonus Audio Electronics                      | 3         | 0.12%   |
| Apple                                           | 3         | 0.12%   |
| Antlion Audio                                   | 3         | 0.12%   |
| Valve Software                                  | 2         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.08%   |
| Sony                                            | 2         | 0.08%   |
| Schiit Audio                                    | 2         | 0.08%   |
| Samsung Electronics                             | 2         | 0.08%   |
| RME                                             | 2         | 0.08%   |
| M-Audio                                         | 2         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 129       | 4.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 113       | 3.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 106       | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 104       | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 92        | 3.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 86        | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 76        | 2.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 70        | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 58        | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 58        | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 54        | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 53        | 1.86%   |
| Intel 8 Series HD Audio Controller                                         | 53        | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 50        | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 44        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 43        | 1.51%   |
| AMD FCH Azalia Controller                                                  | 43        | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 41        | 1.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 40        | 1.4%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 40        | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 37        | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 35        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 35        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 33        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 27        | 0.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                              | 25        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 24        | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 24        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 23        | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 22        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 22        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                     | 21        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 200       | 21.69%  |
| SK hynix                     | 164       | 17.79%  |
| Corsair                      | 133       | 14.43%  |
| Kingston                     | 114       | 12.36%  |
| Micron Technology            | 88        | 9.54%   |
| Unknown                      | 75        | 8.13%   |
| Crucial                      | 47        | 5.1%    |
| G.Skill                      | 30        | 3.25%   |
| Ramaxel Technology           | 11        | 1.19%   |
| Elpida                       | 10        | 1.08%   |
| A-DATA Technology            | 10        | 1.08%   |
| Unknown (ABCD)               | 7         | 0.76%   |
| Nanya Technology             | 7         | 0.76%   |
| Unknown                      | 4         | 0.43%   |
| Transcend                    | 2         | 0.22%   |
| Team                         | 2         | 0.22%   |
| Qimonda                      | 2         | 0.22%   |
| Patriot                      | 2         | 0.22%   |
| G-Alantic                    | 2         | 0.22%   |
| Avant                        | 2         | 0.22%   |
| Unknown (AB)                 | 1         | 0.11%   |
| Unknown (836D)               | 1         | 0.11%   |
| SHARETRONIC                  | 1         | 0.11%   |
| Patriot Memory (PDP Systems) | 1         | 0.11%   |
| Netlist                      | 1         | 0.11%   |
| GSkill                       | 1         | 0.11%   |
| GOODRAM                      | 1         | 0.11%   |
| ASint Technology             | 1         | 0.11%   |
| Apacer                       | 1         | 0.11%   |
| Ankowall                     | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 2.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.01%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 10        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 9         | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 7         | 0.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 6         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 4         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.4%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.4%    |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 4         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.4%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.4%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 4         | 0.4%    |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 4         | 0.4%    |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s             | 4         | 0.4%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 4         | 0.4%    |
| Corsair RAM CMK16GX4M2Z3600C18 8GB DIMM DDR4 3600MT/s            | 4         | 0.4%    |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s            | 4         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 402       | 48.43%  |
| DDR3    | 274       | 33.01%  |
| LPDDR4  | 43        | 5.18%   |
| DDR2    | 34        | 4.1%    |
| LPDDR3  | 25        | 3.01%   |
| SDRAM   | 21        | 2.53%   |
| Unknown | 15        | 1.81%   |
| DDR     | 8         | 0.96%   |
| DDR5    | 4         | 0.48%   |
| DRAM    | 3         | 0.36%   |
| LPDDR5  | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 438       | 52.77%  |
| DIMM         | 317       | 38.19%  |
| Row Of Chips | 61        | 7.35%   |
| Chip         | 10        | 1.2%    |
| Unknown      | 3         | 0.36%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 344       | 38.7%   |
| 4096    | 216       | 24.3%   |
| 16384   | 159       | 17.89%  |
| 2048    | 115       | 12.94%  |
| 1024    | 27        | 3.04%   |
| 32768   | 22        | 2.47%   |
| 512     | 5         | 0.56%   |
| Unknown | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 175       | 19.75%  |
| 2667    | 109       | 12.3%   |
| 3200    | 103       | 11.63%  |
| 2400    | 67        | 7.56%   |
| 2133    | 61        | 6.88%   |
| 1333    | 47        | 5.3%    |
| 3600    | 46        | 5.19%   |
| 667     | 26        | 2.93%   |
| 1334    | 24        | 2.71%   |
| 4267    | 23        | 2.6%    |
| 1867    | 19        | 2.14%   |
| 800     | 17        | 1.92%   |
| Unknown | 17        | 1.92%   |
| 3466    | 15        | 1.69%   |
| 3400    | 10        | 1.13%   |
| 3000    | 9         | 1.02%   |
| 1067    | 9         | 1.02%   |
| 1066    | 9         | 1.02%   |
| 4266    | 8         | 0.9%    |
| 3733    | 7         | 0.79%   |
| 2666    | 7         | 0.79%   |
| 3266    | 6         | 0.68%   |
| 1800    | 6         | 0.68%   |
| 2933    | 5         | 0.56%   |
| 1866    | 5         | 0.56%   |
| 4800    | 4         | 0.45%   |
| 4199    | 4         | 0.45%   |
| 3866    | 4         | 0.45%   |
| 3800    | 4         | 0.45%   |
| 2747    | 4         | 0.45%   |
| 8400    | 3         | 0.34%   |
| 49926   | 2         | 0.23%   |
| 6400    | 2         | 0.23%   |
| 3151    | 2         | 0.23%   |
| 3100    | 2         | 0.23%   |
| 2048    | 2         | 0.23%   |
| 2000    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 5200    | 1         | 0.11%   |
| 4333    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 38.46%  |
| Samsung Electronics | 5         | 19.23%  |
| Brother Industries  | 5         | 19.23%  |
| Canon               | 3         | 11.54%  |
| Seiko Epson         | 2         | 7.69%   |
| Oki Data            | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 7.69%   |
| HP LaserJet 1020                     | 2         | 7.69%   |
| Seiko Epson XP-4100 Series           | 1         | 3.85%   |
| Seiko Epson Printer                  | 1         | 3.85%   |
| Samsung SCX-3200 Series              | 1         | 3.85%   |
| Samsung M2070 Series                 | 1         | 3.85%   |
| Samsung Color Laser Printer          | 1         | 3.85%   |
| Oki Data USB Device                  | 1         | 3.85%   |
| HP OfficeJet Pro 8730                | 1         | 3.85%   |
| HP OfficeJet G55                     | 1         | 3.85%   |
| HP LaserJet P2035                    | 1         | 3.85%   |
| HP LaserJet 1320                     | 1         | 3.85%   |
| HP ENVY 4520 series                  | 1         | 3.85%   |
| HP DeskJet 5650c                     | 1         | 3.85%   |
| HP Deskjet 3050 J610 series          | 1         | 3.85%   |
| HP DeskJet 2130 series               | 1         | 3.85%   |
| Canon LBP7010C/7018C                 | 1         | 3.85%   |
| Canon LBP6200                        | 1         | 3.85%   |
| Canon CanoScan LiDE 300              | 1         | 3.85%   |
| Brother QL-500 label printer         | 1         | 3.85%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.85%   |
| Brother HL-2130 series               | 1         | 3.85%   |
| Brother DCP-7055W                    | 1         | 3.85%   |
| Brother DCP-7040                     | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 83.33%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ScanJet 2200c                       | 1         | 16.67%  |
| Canon CanoScan LiDE 700F               | 1         | 16.67%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 16.67%  |
| Canon CanoScan LiDE 210                | 1         | 16.67%  |
| Canon CanoScan LiDE 120                | 1         | 16.67%  |
| Canon CanoScan LiDE 100                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 210       | 23.6%   |
| Microdia                               | 89        | 10%     |
| IMC Networks                           | 72        | 8.09%   |
| Logitech                               | 70        | 7.87%   |
| Acer                                   | 69        | 7.75%   |
| Realtek Semiconductor                  | 56        | 6.29%   |
| Sunplus Innovation Technology          | 41        | 4.61%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 4.04%   |
| Apple                                  | 36        | 4.04%   |
| Lite-On Technology                     | 31        | 3.48%   |
| Quanta                                 | 28        | 3.15%   |
| Suyin                                  | 22        | 2.47%   |
| Syntek                                 | 21        | 2.36%   |
| Samsung Electronics                    | 11        | 1.24%   |
| Ricoh                                  | 10        | 1.12%   |
| Microsoft                              | 8         | 0.9%    |
| Lenovo                                 | 8         | 0.9%    |
| Luxvisions Innotech Limited            | 6         | 0.67%   |
| ALi                                    | 6         | 0.67%   |
| Alcor Micro                            | 6         | 0.67%   |
| Z-Star Microelectronics                | 5         | 0.56%   |
| Silicon Motion                         | 5         | 0.56%   |
| Creative Technology                    | 5         | 0.56%   |
| Primax Electronics                     | 4         | 0.45%   |
| Unknown                                | 3         | 0.34%   |
| Generalplus Technology                 | 3         | 0.34%   |
| ARC International                      | 3         | 0.34%   |
| Trust                                  | 2         | 0.22%   |
| Sunplus Technology                     | 2         | 0.22%   |
| LG Electronics                         | 2         | 0.22%   |
| Importek                               | 2         | 0.22%   |
| DigiTech                               | 2         | 0.22%   |
| Valve Software                         | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Sony                                   | 1         | 0.11%   |
| Polycom                                | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| Philips (or NXP)                       | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |
| Linux Foundation                       | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 45        | 4.99%   |
| Microdia Integrated_Webcam_HD                                            | 42        | 4.66%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 24        | 2.66%   |
| IMC Networks Integrated Camera                                           | 22        | 2.44%   |
| Realtek Integrated_Webcam_HD                                             | 21        | 2.33%   |
| Acer Integrated Camera                                                   | 21        | 2.33%   |
| Chicony HD Webcam                                                        | 20        | 2.22%   |
| Syntek Integrated Camera                                                 | 15        | 1.66%   |
| Logitech Webcam C270                                                     | 14        | 1.55%   |
| Chicony HP HD Camera                                                     | 14        | 1.55%   |
| Logitech HD Pro Webcam C920                                              | 12        | 1.33%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 12        | 1.33%   |
| Acer Lenovo EasyCamera                                                   | 12        | 1.33%   |
| Sunplus HD WebCam                                                        | 11        | 1.22%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 11        | 1.22%   |
| Logitech C922 Pro Stream Webcam                                          | 10        | 1.11%   |
| Lite-On HP HD Camera                                                     | 10        | 1.11%   |
| Sunplus Integrated_Webcam_HD                                             | 9         | 1%      |
| Quanta HP HD Camera                                                      | 9         | 1%      |
| Lite-On Integrated Camera                                                | 9         | 1%      |
| Lite-On HP HD Webcam                                                     | 9         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 9         | 1%      |
| Apple Built-in iSight                                                    | 9         | 1%      |
| Acer SunplusIT Integrated Camera                                         | 9         | 1%      |
| Chicony HP HD Webcam                                                     | 8         | 0.89%   |
| Chicony HP Wide Vision HD Camera                                         | 7         | 0.78%   |
| Chicony HP Truevision HD                                                 | 7         | 0.78%   |
| Chicony HP HD Webcam [Fixed]                                             | 7         | 0.78%   |
| Apple FaceTime HD Camera (Built-in)                                      | 7         | 0.78%   |
| Acer EasyCamera                                                          | 7         | 0.78%   |
| Syntek Lenovo EasyCamera                                                 | 6         | 0.67%   |
| Realtek USB Camera                                                       | 6         | 0.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 6         | 0.67%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.67%   |
| Chicony USB2.0 Camera                                                    | 6         | 0.67%   |
| Chicony HD User Facing                                                   | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 6         | 0.67%   |
| Apple FaceTime HD Camera                                                 | 6         | 0.67%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 5         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 102       | 44.35%  |
| Synaptics                  | 60        | 26.09%  |
| Shenzhen Goodix Technology | 25        | 10.87%  |
| AuthenTec                  | 11        | 4.78%   |
| Upek                       | 10        | 4.35%   |
| Elan Microelectronics      | 10        | 4.35%   |
| STMicroelectronics         | 6         | 2.61%   |
| LighTuning Technology      | 6         | 2.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 14.78%  |
| Unknown                                                                    | 18        | 7.83%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 6.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 6.09%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 5.22%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 3.91%   |
| Validity Sensors VFS491                                                    | 8         | 3.48%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 3.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.48%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 3.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 3.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.61%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.61%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.17%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 2.17%   |
| AuthenTec AES2810                                                          | 5         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.3%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.3%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.87%   |
| Synaptics  WBDI                                                            | 2         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.87%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.43%   |
| Synaptics WBDI Device                                                      | 1         | 0.43%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.43%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.43%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.43%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.43%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 49        | 42.24%  |
| Alcor Micro           | 47        | 40.52%  |
| O2 Micro              | 8         | 6.9%    |
| Upek                  | 4         | 3.45%   |
| Lenovo                | 4         | 3.45%   |
| Yubico.com            | 1         | 0.86%   |
| Hewlett-Packard       | 1         | 0.86%   |
| Gemalto (was Gemplus) | 1         | 0.86%   |
| Cherry                | 1         | 0.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 38.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 14.66%  |
| Broadcom 58200                                                               | 12        | 10.34%  |
| Broadcom 5880                                                                | 11        | 9.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 6.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.45%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.72%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.86%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.86%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.86%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1110      | 66.19%  |
| 1     | 439       | 26.18%  |
| 2     | 109       | 6.5%    |
| 3     | 13        | 0.78%   |
| 4     | 5         | 0.3%    |
| 7     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 229       | 32.76%  |
| Graphics card            | 121       | 17.31%  |
| Chipcard                 | 103       | 14.74%  |
| Net/wireless             | 60        | 8.58%   |
| Multimedia controller    | 43        | 6.15%   |
| Communication controller | 37        | 5.29%   |
| Unassigned class         | 22        | 3.15%   |
| Camera                   | 20        | 2.86%   |
| Bluetooth                | 18        | 2.58%   |
| Sound                    | 14        | 2%      |
| Card reader              | 10        | 1.43%   |
| Net/ethernet             | 7         | 1%      |
| Storage/ata              | 2         | 0.29%   |
| Storage                  | 2         | 0.29%   |
| Network                  | 2         | 0.29%   |
| Modem                    | 2         | 0.29%   |
| Flash memory             | 2         | 0.29%   |
| Storage/raid             | 1         | 0.14%   |
| Storage/nvme             | 1         | 0.14%   |
| Storage/ide              | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |
| Dvb card                 | 1         | 0.14%   |

