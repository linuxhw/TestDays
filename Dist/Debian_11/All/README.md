Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 630                         | Notebook    | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | Notebook    | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | Notebook    | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Dell          | Latitude E7240              | Notebook    | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Lenovo        | Board                       | Desktop     | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | Notebook    | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | Notebook    | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| Unknown       | Intel X79                   | Desktop     | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4882999fd5](https://linux-hardware.org/?probe=4882999fd5) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | Notebook    | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | Notebook    | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| HP            | 3047h                       | Desktop     | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | Notebook    | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | Notebook    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| Lenovo        | Reno                        | Server      | [91a367ab6d](https://linux-hardware.org/?probe=91a367ab6d) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| SimpliVity    | 04N3DF A03                  | Server      | [c5705e6436](https://linux-hardware.org/?probe=c5705e6436) | Aug 02, 2021 |
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 229       | 51.81%  |
| 5.10.0-7-amd64                 | 108       | 24.43%  |
| 5.10.0-6-amd64                 | 37        | 8.37%   |
| 5.11.22-1-pve                  | 5         | 1.13%   |
| 5.10.0-8-686-pae               | 5         | 1.13%   |
| 5.10.0-8-686                   | 3         | 0.68%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.45%   |
| 5.11.22-2-pve                  | 2         | 0.45%   |
| 5.10.42+truenas                | 2         | 0.45%   |
| 5.10.0-8-rt-amd64              | 2         | 0.45%   |
| 5.10-sunxi64                   | 2         | 0.45%   |
| 4.19.0-14-amd64                | 2         | 0.45%   |
| 5.9.0-arm-64                   | 1         | 0.23%   |
| 5.8.0-3-amd64                  | 1         | 0.23%   |
| 5.4.18-sunxi64                 | 1         | 0.23%   |
| 5.4.0-73-generic               | 1         | 0.23%   |
| 5.14.0-rc3-prygun              | 1         | 0.23%   |
| 5.13.8-xanmod1                 | 1         | 0.23%   |
| 5.13.5-xanmod1                 | 1         | 0.23%   |
| 5.13.4-e5520                   | 1         | 0.23%   |
| 5.13.4                         | 1         | 0.23%   |
| 5.13.1a                        | 1         | 0.23%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.23%   |
| 5.12.4                         | 1         | 0.23%   |
| 5.12.10                        | 1         | 0.23%   |
| 5.12.1                         | 1         | 0.23%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.23%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.23%   |
| 5.11.9+                        | 1         | 0.23%   |
| 5.11.22-3-pve                  | 1         | 0.23%   |
| 5.11.15-terranz                | 1         | 0.23%   |
| 5.11.15-051115-generic         | 1         | 0.23%   |
| 5.11.14                        | 1         | 0.23%   |
| 5.11.0-rc6                     | 1         | 0.23%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.23%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.23%   |
| 5.10.46custom                  | 1         | 0.23%   |
| 5.10.40-ismynik                | 1         | 0.23%   |
| 5.10.38-falcot                 | 1         | 0.23%   |
| 5.10.35-rockchip64             | 1         | 0.23%   |
| 5.10.21-sunxi                  | 1         | 0.23%   |
| 5.10.12-sunxi                  | 1         | 0.23%   |
| 5.10.10-64                     | 1         | 0.23%   |
| 5.10.0-io7-amd64               | 1         | 0.23%   |
| 5.10.0-8-armmp                 | 1         | 0.23%   |
| 5.10.0-7-686-pae               | 1         | 0.23%   |
| 5.10.0-6-rt-amd64              | 1         | 0.23%   |
| 5.10.0-6-686                   | 1         | 0.23%   |
| 5.10.0-5-amd64                 | 1         | 0.23%   |
| 5.10.0-4-amd64                 | 1         | 0.23%   |
| 5.10.0-3-amd64                 | 1         | 0.23%   |
| 5.10.0-2-amd64                 | 1         | 0.23%   |
| 4.19.181-z580322               | 1         | 0.23%   |
| 4.19.0-16-amd64                | 1         | 0.23%   |
| 4.19.0-16-686-pae              | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 384       | 88.89%  |
| 5.11.22  | 8         | 1.85%   |
| 4.19.0   | 4         | 0.93%   |
| 5.12.0   | 3         | 0.69%   |
| 5.11.0   | 3         | 0.69%   |
| 5.13.4   | 2         | 0.46%   |
| 5.11.15  | 2         | 0.46%   |
| 5.10.42  | 2         | 0.46%   |
| 5.10     | 2         | 0.46%   |
| 5.9.0    | 1         | 0.23%   |
| 5.8.0    | 1         | 0.23%   |
| 5.4.18   | 1         | 0.23%   |
| 5.4.0    | 1         | 0.23%   |
| 5.14.0   | 1         | 0.23%   |
| 5.13.8   | 1         | 0.23%   |
| 5.13.5   | 1         | 0.23%   |
| 5.13.1   | 1         | 0.23%   |
| 5.13.0   | 1         | 0.23%   |
| 5.12.4   | 1         | 0.23%   |
| 5.12.10  | 1         | 0.23%   |
| 5.12.1   | 1         | 0.23%   |
| 5.11.9   | 1         | 0.23%   |
| 5.11.14  | 1         | 0.23%   |
| 5.10.46  | 1         | 0.23%   |
| 5.10.40  | 1         | 0.23%   |
| 5.10.38  | 1         | 0.23%   |
| 5.10.35  | 1         | 0.23%   |
| 5.10.21  | 1         | 0.23%   |
| 5.10.12  | 1         | 0.23%   |
| 5.10.10  | 1         | 0.23%   |
| 4.19.181 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 392       | 90.95%  |
| 5.11    | 15        | 3.48%   |
| 5.13    | 6         | 1.39%   |
| 5.12    | 6         | 1.39%   |
| 4.19    | 5         | 1.16%   |
| 5.4     | 2         | 0.46%   |
| 5       | 2         | 0.46%   |
| 5.9     | 1         | 0.23%   |
| 5.8     | 1         | 0.23%   |
| 5.14    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 413       | 95.82%  |
| i686    | 11        | 2.55%   |
| aarch64 | 5         | 1.16%   |
| armv7l  | 2         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 114       | 26.27%  |
| KDE5             | 82        | 18.89%  |
| Unknown          | 78        | 17.97%  |
| XFCE             | 40        | 9.22%   |
| MATE             | 29        | 6.68%   |
| Cinnamon         | 15        | 3.46%   |
| LXQt             | 13        | 3%      |
| i3               | 12        | 2.76%   |
| LXDE             | 10        | 2.3%    |
| KDE              | 10        | 2.3%    |
| X-Cinnamon       | 8         | 1.84%   |
| Trinity          | 5         | 1.15%   |
| lightdm-xsession | 4         | 0.92%   |
| GNOME Flashback  | 4         | 0.92%   |
| sway             | 2         | 0.46%   |
| openbox          | 2         | 0.46%   |
| ICEWM            | 1         | 0.23%   |
| GNUstep          | 1         | 0.23%   |
| Enlightenment    | 1         | 0.23%   |
| default          | 1         | 0.23%   |
| Budgie           | 1         | 0.23%   |
| awesome          | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 254       | 58.66%  |
| Wayland | 91        | 21.02%  |
| Unknown | 51        | 11.78%  |
| Tty     | 37        | 8.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 117       | 27.02%  |
| Unknown | 110       | 25.4%   |
| GDM     | 108       | 24.94%  |
| SDDM    | 85        | 19.63%  |
| LightDM | 8         | 1.85%   |
| XDM     | 2         | 0.46%   |
| SLiM    | 2         | 0.46%   |
| KDM     | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 176       | 40.74%  |
| Unknown | 34        | 7.87%   |
| ru_RU   | 32        | 7.41%   |
| en_GB   | 32        | 7.41%   |
| fr_FR   | 25        | 5.79%   |
| de_DE   | 24        | 5.56%   |
| es_ES   | 12        | 2.78%   |
| pt_BR   | 9         | 2.08%   |
| pl_PL   | 9         | 2.08%   |
| en_IN   | 8         | 1.85%   |
| C       | 7         | 1.62%   |
| it_IT   | 5         | 1.16%   |
| en_AU   | 5         | 1.16%   |
| en_CA   | 4         | 0.93%   |
| tr_TR   | 3         | 0.69%   |
| nl_BE   | 3         | 0.69%   |
| ja_JP   | 3         | 0.69%   |
| hu_HU   | 3         | 0.69%   |
| de_CH   | 3         | 0.69%   |
| cs_CZ   | 3         | 0.69%   |
| uk_UA   | 2         | 0.46%   |
| ru_UA   | 2         | 0.46%   |
| ro_RO   | 2         | 0.46%   |
| pt_PT   | 2         | 0.46%   |
| hr_HR   | 2         | 0.46%   |
| es_AR   | 2         | 0.46%   |
| en_SG   | 2         | 0.46%   |
| en_IE   | 2         | 0.46%   |
| en_HK   | 2         | 0.46%   |
| sv_SE   | 1         | 0.23%   |
| sr_RS   | 1         | 0.23%   |
| sk_SK   | 1         | 0.23%   |
| gl_ES   | 1         | 0.23%   |
| fi_FI   | 1         | 0.23%   |
| es_VE   | 1         | 0.23%   |
| es_UY   | 1         | 0.23%   |
| es_US   | 1         | 0.23%   |
| es_MX   | 1         | 0.23%   |
| es_EC   | 1         | 0.23%   |
| es_CO   | 1         | 0.23%   |
| en_SI   | 1         | 0.23%   |
| en_PH   | 1         | 0.23%   |
| ca_ES   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 268       | 61.89%  |
| BIOS | 165       | 38.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 319       | 74.01%  |
| Overlay | 58        | 13.46%  |
| Btrfs   | 29        | 6.73%   |
| Zfs     | 10        | 2.32%   |
| Xfs     | 5         | 1.16%   |
| Ext3    | 5         | 1.16%   |
| Unknown | 4         | 0.93%   |
| Rootfs  | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 298       | 68.82%  |
| MBR     | 96        | 22.17%  |
| Unknown | 39        | 9.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 347       | 80.32%  |
| Yes       | 85        | 19.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 317       | 73.38%  |
| Yes       | 115       | 26.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 88        | 20.42%  |
| ASUSTek Computer        | 60        | 13.92%  |
| Hewlett-Packard         | 56        | 12.99%  |
| Dell                    | 54        | 12.53%  |
| Gigabyte Technology     | 36        | 8.35%   |
| MSI                     | 23        | 5.34%   |
| ASRock                  | 23        | 5.34%   |
| Apple                   | 18        | 4.18%   |
| Acer                    | 16        | 3.71%   |
| Intel                   | 6         | 1.39%   |
| Toshiba                 | 3         | 0.7%    |
| Supermicro              | 3         | 0.7%    |
| sunxi                   | 3         | 0.7%    |
| HUAWEI                  | 3         | 0.7%    |
| Google                  | 3         | 0.7%    |
| Fujitsu                 | 3         | 0.7%    |
| Unknown                 | 3         | 0.7%    |
| Huanan                  | 2         | 0.46%   |
| Foxconn                 | 2         | 0.46%   |
| ZOTAC                   | 1         | 0.23%   |
| UNOWHY                  | 1         | 0.23%   |
| TUXEDO                  | 1         | 0.23%   |
| SLIMBOOK                | 1         | 0.23%   |
| SimpliVity              | 1         | 0.23%   |
| Shuttle                 | 1         | 0.23%   |
| Samsung Electronics     | 1         | 0.23%   |
| Raspberry Pi Foundation | 1         | 0.23%   |
| Quanta                  | 1         | 0.23%   |
| Protectli               | 1         | 0.23%   |
| Pine Microsystems       | 1         | 0.23%   |
| Pegatron                | 1         | 0.23%   |
| PC Specialist           | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| Notebook                | 1         | 0.23%   |
| Monster                 | 1         | 0.23%   |
| Itautec                 | 1         | 0.23%   |
| IBM                     | 1         | 0.23%   |
| HARDKERNEL              | 1         | 0.23%   |
| ECS                     | 1         | 0.23%   |
| Compulab                | 1         | 0.23%   |
| Clevo                   | 1         | 0.23%   |
| Chuwi                   | 1         | 0.23%   |
| Casper                  | 1         | 0.23%   |
| Biostar                 | 1         | 0.23%   |
| ASRockRack              | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                           | 5         | 1.16%   |
| Unknown                                       | 5         | 1.16%   |
| ASUS All Series                               | 4         | 0.93%   |
| Apple MacBookAir7,1                           | 4         | 0.93%   |
| Gigabyte B550I AORUS PRO AX                   | 3         | 0.7%    |
| ASRock B450M Pro4                             | 3         | 0.7%    |
| Lenovo ThinkPad T490 20N2CTO1WW               | 2         | 0.46%   |
| Lenovo ThinkPad E475 20H40006US               | 2         | 0.46%   |
| Lenovo G50-80 80E5                            | 2         | 0.46%   |
| HUAWEI NBLK-WAX9X                             | 2         | 0.46%   |
| HP Z620 Workstation                           | 2         | 0.46%   |
| HP EliteBook 8460p                            | 2         | 0.46%   |
| HP Compaq nx6125 (PZ849UA#ABA)                | 2         | 0.46%   |
| HP Compaq nx6110 (PZ065UA#ABA)                | 2         | 0.46%   |
| Google Enguarde                               | 2         | 0.46%   |
| Gigabyte Z77-D3H                              | 2         | 0.46%   |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.46%   |
| Dell XPS 13 9310                              | 2         | 0.46%   |
| Dell XPS 13 7390                              | 2         | 0.46%   |
| Dell Precision 3540                           | 2         | 0.46%   |
| Dell OptiPlex 760                             | 2         | 0.46%   |
| Dell Latitude 7480                            | 2         | 0.46%   |
| Dell Inspiron 5570                            | 2         | 0.46%   |
| Dell Inspiron 3793                            | 2         | 0.46%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.46%   |
| ASUS PRIME B550-PLUS                          | 2         | 0.46%   |
| ASUS PRIME B450M-A                            | 2         | 0.46%   |
| Apple MacBook5,2                              | 2         | 0.46%   |
| Acer Aspire 5315                              | 2         | 0.46%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K          | 1         | 0.23%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.23%   |
| TUXEDO Pulse 15 Gen1                          | 1         | 0.23%   |
| Toshiba Satellite U800W                       | 1         | 0.23%   |
| Toshiba Satellite S55-A                       | 1         | 0.23%   |
| Toshiba Satellite C45-A                       | 1         | 0.23%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.23%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.23%   |
| Supermicro SYS-5019S-MR                       | 1         | 0.23%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.23%   |
| SLIMBOOK PROX14-AMD                           | 1         | 0.23%   |
| SimpliVity OmniCube CN-3400-1                 | 1         | 0.23%   |
| Shuttle SX79R                                 | 1         | 0.23%   |
| Samsung 370E4K                                | 1         | 0.23%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.23%   |
| Quanta TWC                                    | 1         | 0.23%   |
| Protectli FW6                                 | 1         | 0.23%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.23%   |
| Pegatron A15                                  | 1         | 0.23%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.23%   |
| Panasonic CF-AX2LDCZMF                        | 1         | 0.23%   |
| Notebook NJ50_70CU                            | 1         | 0.23%   |
| MSI U90/U100                                  | 1         | 0.23%   |
| MSI MS-7C94                                   | 1         | 0.23%   |
| MSI MS-7C84                                   | 1         | 0.23%   |
| MSI MS-7C75                                   | 1         | 0.23%   |
| MSI MS-7C56                                   | 1         | 0.23%   |
| MSI MS-7C35                                   | 1         | 0.23%   |
| MSI MS-7B89                                   | 1         | 0.23%   |
| MSI MS-7B46                                   | 1         | 0.23%   |
| MSI MS-7B09                                   | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 63        | 14.62%  |
| ASUS PRIME                   | 15        | 3.48%   |
| Lenovo IdeaPad               | 14        | 3.25%   |
| Dell Inspiron                | 14        | 3.25%   |
| Acer Aspire                  | 13        | 3.02%   |
| HP ProBook                   | 10        | 2.32%   |
| HP EliteBook                 | 9         | 2.09%   |
| HP Compaq                    | 9         | 2.09%   |
| Dell XPS                     | 9         | 2.09%   |
| Dell OptiPlex                | 9         | 2.09%   |
| Dell Latitude                | 9         | 2.09%   |
| Apple MacBookAir7            | 9         | 2.09%   |
| Dell Precision               | 7         | 1.62%   |
| ASUS ROG                     | 7         | 1.62%   |
| HP Laptop                    | 5         | 1.16%   |
| ASUS ZenBook                 | 5         | 1.16%   |
| ASUS VivoBook                | 5         | 1.16%   |
| Unknown                      | 5         | 1.16%   |
| Lenovo Yoga                  | 4         | 0.93%   |
| Lenovo ThinkCentre           | 4         | 0.93%   |
| ASUS All                     | 4         | 0.93%   |
| Toshiba Satellite            | 3         | 0.7%    |
| HP ProLiant                  | 3         | 0.7%    |
| Gigabyte B550I               | 3         | 0.7%    |
| Fujitsu LIFEBOOK             | 3         | 0.7%    |
| ASRock B450M                 | 3         | 0.7%    |
| Lenovo G50-80                | 2         | 0.46%   |
| HUAWEI NBLK-WAX9X            | 2         | 0.46%   |
| HP ZBook                     | 2         | 0.46%   |
| HP Z620                      | 2         | 0.46%   |
| HP Pavilion                  | 2         | 0.46%   |
| HP OMEN                      | 2         | 0.46%   |
| HP 250                       | 2         | 0.46%   |
| Google Enguarde              | 2         | 0.46%   |
| Gigabyte Z77-D3H             | 2         | 0.46%   |
| Gigabyte Z370                | 2         | 0.46%   |
| Gigabyte AERO                | 2         | 0.46%   |
| Dell Vostro                  | 2         | 0.46%   |
| Dell PowerEdge               | 2         | 0.46%   |
| ASRock Z97                   | 2         | 0.46%   |
| Apple MacBook5               | 2         | 0.46%   |
| Acer Nitro                   | 2         | 0.46%   |
| ZOTAC ZBOX-EN1070            | 1         | 0.23%   |
| UNOWHY Y13G002S4EI           | 1         | 0.23%   |
| TUXEDO Pulse                 | 1         | 0.23%   |
| Supermicro SYS-6019P-WT      | 1         | 0.23%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.23%   |
| Supermicro SYS-5019S-MR      | 1         | 0.23%   |
| sunxi Banana                 | 1         | 0.23%   |
| SLIMBOOK PROX14-AMD          | 1         | 0.23%   |
| SimpliVity OmniCube          | 1         | 0.23%   |
| Shuttle SX79R                | 1         | 0.23%   |
| Samsung 370E4K               | 1         | 0.23%   |
| RPi Raspberry                | 1         | 0.23%   |
| Quanta TWC                   | 1         | 0.23%   |
| Protectli FW6                | 1         | 0.23%   |
| Pine Microsystems Pine64     | 1         | 0.23%   |
| Pegatron A15                 | 1         | 0.23%   |
| PC Specialist NV4XMB         | 1         | 0.23%   |
| Panasonic CF-AX2LDCZMF       | 1         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 91        | 21.11%  |
| 2021    | 74        | 17.17%  |
| 2019    | 59        | 13.69%  |
| 2018    | 39        | 9.05%   |
| 2016    | 21        | 4.87%   |
| 2013    | 20        | 4.64%   |
| 2012    | 20        | 4.64%   |
| 2014    | 17        | 3.94%   |
| 2015    | 15        | 3.48%   |
| 2011    | 14        | 3.25%   |
| 2009    | 12        | 2.78%   |
| 2008    | 11        | 2.55%   |
| 2010    | 10        | 2.32%   |
| 2017    | 8         | 1.86%   |
| Unknown | 7         | 1.62%   |
| 2007    | 5         | 1.16%   |
| 2006    | 3         | 0.7%    |
| 2005    | 2         | 0.46%   |
| 2004    | 2         | 0.46%   |
| 2001    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 243       | 56.38%  |
| Desktop        | 156       | 36.19%  |
| Convertible    | 9         | 2.09%   |
| Server         | 7         | 1.62%   |
| System on chip | 6         | 1.39%   |
| Mini pc        | 5         | 1.16%   |
| Tablet         | 2         | 0.46%   |
| All in one     | 2         | 0.46%   |
| Phone          | 1         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 393       | 90.76%  |
| Enabled  | 40        | 9.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 427       | 99.07%  |
| Yes  | 4         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 118       | 27.38%  |
| 4.01-8.0        | 86        | 19.95%  |
| 8.01-16.0       | 68        | 15.78%  |
| 3.01-4.0        | 49        | 11.37%  |
| 32.01-64.0      | 43        | 9.98%   |
| 64.01-256.0     | 25        | 5.8%    |
| 1.01-2.0        | 19        | 4.41%   |
| 2.01-3.0        | 8         | 1.86%   |
| 0.51-1.0        | 6         | 1.39%   |
| 0.01-0.5        | 4         | 0.93%   |
| 24.01-32.0      | 3         | 0.7%    |
| More than 256.0 | 2         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 105       | 24.03%  |
| 2.01-3.0    | 93        | 21.28%  |
| 4.01-8.0    | 71        | 16.25%  |
| 3.01-4.0    | 59        | 13.5%   |
| 0.51-1.0    | 39        | 8.92%   |
| 8.01-16.0   | 35        | 8.01%   |
| 0.01-0.5    | 23        | 5.26%   |
| 24.01-32.0  | 4         | 0.92%   |
| 16.01-24.0  | 4         | 0.92%   |
| 32.01-64.0  | 3         | 0.69%   |
| 64.01-256.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 225       | 52.2%   |
| 2      | 129       | 29.93%  |
| 3      | 32        | 7.42%   |
| 4      | 18        | 4.18%   |
| 5      | 12        | 2.78%   |
| 8      | 5         | 1.16%   |
| 9      | 3         | 0.7%    |
| 6      | 3         | 0.7%    |
| 0      | 2         | 0.46%   |
| 28     | 1         | 0.23%   |
| 10     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 289       | 67.05%  |
| Yes       | 142       | 32.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 84.92%  |
| No        | 65        | 15.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 301       | 69.84%  |
| No        | 130       | 30.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 57.08%  |
| No        | 185       | 42.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 102       | 23.67%  |
| Russia                 | 37        | 8.58%   |
| France                 | 37        | 8.58%   |
| Germany                | 36        | 8.35%   |
| UK                     | 20        | 4.64%   |
| Spain                  | 17        | 3.94%   |
| Poland                 | 16        | 3.71%   |
| Ukraine                | 14        | 3.25%   |
| Brazil                 | 11        | 2.55%   |
| Netherlands            | 9         | 2.09%   |
| India                  | 8         | 1.86%   |
| Canada                 | 7         | 1.62%   |
| Italy                  | 6         | 1.39%   |
| Greece                 | 6         | 1.39%   |
| Czechia                | 6         | 1.39%   |
| Australia              | 6         | 1.39%   |
| Turkey                 | 5         | 1.16%   |
| Switzerland            | 5         | 1.16%   |
| Portugal               | 5         | 1.16%   |
| Mexico                 | 5         | 1.16%   |
| Hungary                | 5         | 1.16%   |
| Thailand               | 4         | 0.93%   |
| Norway                 | 4         | 0.93%   |
| Kazakhstan             | 4         | 0.93%   |
| Bulgaria               | 4         | 0.93%   |
| Belarus                | 4         | 0.93%   |
| Argentina              | 4         | 0.93%   |
| Japan                  | 3         | 0.7%    |
| Finland                | 3         | 0.7%    |
| Ecuador                | 3         | 0.7%    |
| Croatia                | 3         | 0.7%    |
| Belgium                | 3         | 0.7%    |
| Austria                | 3         | 0.7%    |
| Venezuela              | 2         | 0.46%   |
| Sweden                 | 2         | 0.46%   |
| Slovenia               | 2         | 0.46%   |
| Indonesia              | 2         | 0.46%   |
| Vietnam                | 1         | 0.23%   |
| Uruguay                | 1         | 0.23%   |
| Syria                  | 1         | 0.23%   |
| Singapore              | 1         | 0.23%   |
| Serbia                 | 1         | 0.23%   |
| Romania                | 1         | 0.23%   |
| Philippines            | 1         | 0.23%   |
| New Caledonia          | 1         | 0.23%   |
| Mongolia               | 1         | 0.23%   |
| Malaysia               | 1         | 0.23%   |
| Madagascar             | 1         | 0.23%   |
| Ireland                | 1         | 0.23%   |
| Hong Kong              | 1         | 0.23%   |
| Denmark                | 1         | 0.23%   |
| Colombia               | 1         | 0.23%   |
| China                  | 1         | 0.23%   |
| Bosnia and Herzegovina | 1         | 0.23%   |
| Bangladesh             | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 39        | 9.03%   |
| St Petersburg  | 9         | 2.08%   |
| Paris          | 9         | 2.08%   |
| Lyon           | 7         | 1.62%   |
| Ocala          | 5         | 1.16%   |
| Kalamazoo      | 5         | 1.16%   |
| Athens         | 5         | 1.16%   |
| Warsaw         | 4         | 0.93%   |
| Sofia          | 4         | 0.93%   |
| Moscow         | 4         | 0.93%   |
| London         | 4         | 0.93%   |
| Kyiv           | 4         | 0.93%   |
| Ensenada       | 4         | 0.93%   |
| Berlin         | 4         | 0.93%   |
| Bengaluru      | 4         | 0.93%   |
| Bangkok        | 4         | 0.93%   |
| Vienna         | 3         | 0.69%   |
| Sunnyvale      | 3         | 0.69%   |
| Perm           | 3         | 0.69%   |
| Mesa           | 3         | 0.69%   |
| Madrid         | 3         | 0.69%   |
| Gloucester     | 3         | 0.69%   |
| Clitheroe      | 3         | 0.69%   |
| Zagreb         | 2         | 0.46%   |
| Waregem        | 2         | 0.46%   |
| Sydney         | 2         | 0.46%   |
| Springfield    | 2         | 0.46%   |
| Shizuoka       | 2         | 0.46%   |
| Saratov        | 2         | 0.46%   |
| Saint-Denis    | 2         | 0.46%   |
| Rio de Janeiro | 2         | 0.46%   |
| Prague         | 2         | 0.46%   |
| Oleksandrivka  | 2         | 0.46%   |
| Noblesville    | 2         | 0.46%   |
| New York       | 2         | 0.46%   |
| Munich         | 2         | 0.46%   |
| Mainz          | 2         | 0.46%   |
| Lublin         | 2         | 0.46%   |
| Las Vegas      | 2         | 0.46%   |
| Kharkiv        | 2         | 0.46%   |
| Istanbul       | 2         | 0.46%   |
| Hanover        | 2         | 0.46%   |
| Hakadal        | 2         | 0.46%   |
| Gorinchem      | 2         | 0.46%   |
| Fryazino       | 2         | 0.46%   |
| Donetsk        | 2         | 0.46%   |
| Denpasar       | 2         | 0.46%   |
| Cuenca         | 2         | 0.46%   |
| Burnaby        | 2         | 0.46%   |
| Ankara         | 2         | 0.46%   |
| Amsterdam      | 2         | 0.46%   |
| Ajdov????ina   | 2         | 0.46%   |
| Érd           | 1         | 0.23%   |
| Zurich         | 1         | 0.23%   |
| Zaragoza       | 1         | 0.23%   |
| Yevpatoriya    | 1         | 0.23%   |
| Yekaterinburg  | 1         | 0.23%   |
| Wroclaw        | 1         | 0.23%   |
| Woolloongabba  | 1         | 0.23%   |
| Woodstock      | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 110       | 146    | 17.16%  |
| WDC                 | 98        | 169    | 15.29%  |
| Seagate             | 89        | 126    | 13.88%  |
| Toshiba             | 43        | 60     | 6.71%   |
| Kingston            | 41        | 48     | 6.4%    |
| Crucial             | 30        | 33     | 4.68%   |
| Unknown             | 27        | 37     | 4.21%   |
| Intel               | 21        | 28     | 3.28%   |
| Sandisk             | 19        | 24     | 2.96%   |
| Hitachi             | 18        | 19     | 2.81%   |
| SABRENT             | 16        | 16     | 2.5%    |
| SK Hynix            | 13        | 15     | 2.03%   |
| Apple               | 12        | 12     | 1.87%   |
| A-DATA Technology   | 11        | 15     | 1.72%   |
| HGST                | 9         | 12     | 1.4%    |
| Micron Technology   | 6         | 6      | 0.94%   |
| China               | 6         | 6      | 0.94%   |
| PNY                 | 5         | 5      | 0.78%   |
| KIOXIA              | 5         | 5      | 0.78%   |
| Fujitsu             | 5         | 5      | 0.78%   |
| Transcend           | 4         | 5      | 0.62%   |
| SPCC                | 4         | 4      | 0.62%   |
| Union Memory        | 3         | 3      | 0.47%   |
| Phison              | 3         | 6      | 0.47%   |
| Patriot             | 3         | 3      | 0.47%   |
| LITEONIT            | 3         | 3      | 0.47%   |
| JMicron             | 3         | 3      | 0.47%   |
| Intenso             | 3         | 4      | 0.47%   |
| Gigabyte Technology | 3         | 3      | 0.47%   |
| Phison Electronics  | 2         | 2      | 0.31%   |
| LITEON              | 2         | 2      | 0.31%   |
| Lenovo              | 2         | 2      | 0.31%   |
| Corsair             | 2         | 2      | 0.31%   |
| ZTC                 | 1         | 1      | 0.16%   |
| XPG                 | 1         | 1      | 0.16%   |
| TrueNAS             | 1         | 1      | 0.16%   |
| Team                | 1         | 1      | 0.16%   |
| T-FORCE             | 1         | 1      | 0.16%   |
| SILICONMOTION       | 1         | 1      | 0.16%   |
| Silicon Motion      | 1         | 2      | 0.16%   |
| OCZ                 | 1         | 1      | 0.16%   |
| Maxtor              | 1         | 2      | 0.16%   |
| Maximus             | 1         | 1      | 0.16%   |
| MaxDigital          | 1         | 2      | 0.16%   |
| Lexar               | 1         | 1      | 0.16%   |
| LDLC                | 1         | 1      | 0.16%   |
| KingDian            | 1         | 1      | 0.16%   |
| IBM-ESXS            | 1         | 2      | 0.16%   |
| GOODRAM             | 1         | 1      | 0.16%   |
| DOGFISH             | 1         | 1      | 0.16%   |
| ASUS-PHISON         | 1         | 1      | 0.16%   |
| Apacer              | 1         | 1      | 0.16%   |
| AMD                 | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| SABRENT Disk 160GB                 | 16        | 2.19%   |
| Samsung SSD 860 EVO 1TB            | 12        | 1.64%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 1.37%   |
| Samsung SSD 970 EVO Plus 500GB     | 7         | 0.96%   |
| Samsung SSD 860 EVO 500GB          | 7         | 0.96%   |
| Samsung SSD 850 EVO 500GB          | 7         | 0.96%   |
| Samsung SSD 850 EVO 250GB          | 7         | 0.96%   |
| Kingston SA400S37120G 120GB SSD    | 7         | 0.96%   |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.68%   |
| Crucial CT500MX500SSD1 500GB       | 5         | 0.68%   |
| Apple SSD SM0128G 121GB            | 5         | 0.68%   |
| Toshiba HDWD110 1TB                | 4         | 0.55%   |
| Toshiba DT01ACA300 3TB             | 4         | 0.55%   |
| Toshiba DT01ACA200 2TB             | 4         | 0.55%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB     | 4         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 4         | 0.55%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.55%   |
| Kingston SV300S37A240G 240GB SSD   | 4         | 0.55%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.55%   |
| Crucial CT500P1SSD8 500GB          | 4         | 0.55%   |
| Crucial CT1000P1SSD8 1TB           | 4         | 0.55%   |
| Crucial CT1000MX500SSD1 1TB        | 4         | 0.55%   |
| Apple SSD AP0128H 121GB            | 4         | 0.55%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 3         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 3         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB           | 3         | 0.41%   |
| Unknown DA4064  64GB               | 3         | 0.41%   |
| Toshiba MQ04ABF100 1TB             | 3         | 0.41%   |
| Seagate ST2000LX001-1RG174 2TB     | 3         | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 0.41%   |
| Seagate Backup+ Hub BK 4TB         | 3         | 0.41%   |
| SanDisk SSD PLUS 240GB             | 3         | 0.41%   |
| Samsung SSD 860 EVO M.2 1TB        | 3         | 0.41%   |
| Samsung SSD 840 PRO Series 256GB   | 3         | 0.41%   |
| Samsung MZALQ256HAJD-000L1 256GB   | 3         | 0.41%   |
| Kingston SUV400S37120G 120GB SSD   | 3         | 0.41%   |
| Hitachi HUS724040ALE641 4TB        | 3         | 0.41%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.41%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.27%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 2         | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2         | 0.27%   |
| WDC WD40EFRX-68N32N0 4TB           | 2         | 0.27%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 2         | 0.27%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.27%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.27%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.27%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.27%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2         | 0.27%   |
| WDC WD10EFRX-68FYTN0 1TB           | 2         | 0.27%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 2         | 0.27%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB | 2         | 0.27%   |
| Unknown SL16G  16GB                | 2         | 0.27%   |
| Unknown SD/MMC/MS PRO 32GB         | 2         | 0.27%   |
| Unknown MMC Card  64GB             | 2         | 0.27%   |
| Unknown MMC Card  32GB             | 2         | 0.27%   |
| Unknown HAG2e  16GB                | 2         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 109    | 36.94%  |
| WDC                 | 68        | 126    | 30.63%  |
| Toshiba             | 29        | 44     | 13.06%  |
| Hitachi             | 18        | 19     | 8.11%   |
| HGST                | 9         | 12     | 4.05%   |
| Samsung Electronics | 8         | 9      | 3.6%    |
| Fujitsu             | 5         | 5      | 2.25%   |
| SILICONMOTION       | 1         | 1      | 0.45%   |
| MaxDigital          | 1         | 2      | 0.45%   |
| IBM-ESXS            | 1         | 2      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 63        | 83     | 26.58%  |
| Kingston            | 32        | 39     | 13.5%   |
| Crucial             | 20        | 21     | 8.44%   |
| SABRENT             | 16        | 16     | 6.75%   |
| SanDisk             | 14        | 18     | 5.91%   |
| WDC                 | 13        | 16     | 5.49%   |
| Intel               | 7         | 7      | 2.95%   |
| Apple               | 7         | 7      | 2.95%   |
| A-DATA Technology   | 7         | 8      | 2.95%   |
| China               | 6         | 6      | 2.53%   |
| Transcend           | 4         | 5      | 1.69%   |
| Toshiba             | 4         | 5      | 1.69%   |
| PNY                 | 4         | 4      | 1.69%   |
| SPCC                | 3         | 3      | 1.27%   |
| SK Hynix            | 3         | 3      | 1.27%   |
| Seagate             | 3         | 3      | 1.27%   |
| Patriot             | 3         | 3      | 1.27%   |
| LITEONIT            | 3         | 3      | 1.27%   |
| Micron Technology   | 2         | 2      | 0.84%   |
| JMicron             | 2         | 2      | 0.84%   |
| Intenso             | 2         | 2      | 0.84%   |
| ZTC                 | 1         | 1      | 0.42%   |
| Unknown             | 1         | 1      | 0.42%   |
| Union Memory        | 1         | 1      | 0.42%   |
| TrueNAS             | 1         | 1      | 0.42%   |
| Team                | 1         | 1      | 0.42%   |
| T-FORCE             | 1         | 1      | 0.42%   |
| OCZ                 | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 2      | 0.42%   |
| Maximus             | 1         | 1      | 0.42%   |
| LITEON              | 1         | 1      | 0.42%   |
| Lexar               | 1         | 1      | 0.42%   |
| LDLC                | 1         | 1      | 0.42%   |
| KingDian            | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| Gigabyte Technology | 1         | 1      | 0.42%   |
| DOGFISH             | 1         | 1      | 0.42%   |
| ASUS-PHISON         | 1         | 1      | 0.42%   |
| Apacer              | 1         | 1      | 0.42%   |
| AMD                 | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 218       | 276    | 36.21%  |
| HDD     | 191       | 329    | 31.73%  |
| NVMe    | 158       | 194    | 26.25%  |
| MMC     | 24        | 35     | 3.99%   |
| Unknown | 11        | 19     | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 312       | 570    | 58.54%  |
| NVMe | 158       | 194    | 29.64%  |
| SAS  | 39        | 54     | 7.32%   |
| MMC  | 24        | 35     | 4.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 229       | 337    | 54.78%  |
| 0.51-1.0   | 113       | 140    | 27.03%  |
| 1.01-2.0   | 41        | 49     | 9.81%   |
| 3.01-4.0   | 15        | 38     | 3.59%   |
| 2.01-3.0   | 10        | 15     | 2.39%   |
| 4.01-10.0  | 7         | 18     | 1.67%   |
| 10.01-20.0 | 3         | 8      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 23.33%  |
| 251-500        | 83        | 19.17%  |
| 501-1000       | 55        | 12.7%   |
| 1001-2000      | 43        | 9.93%   |
| More than 3000 | 36        | 8.31%   |
| 1-20           | 36        | 8.31%   |
| 51-100         | 28        | 6.47%   |
| Unknown        | 25        | 5.77%   |
| 21-50          | 15        | 3.46%   |
| 2001-3000      | 11        | 2.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 139       | 31.81%  |
| 21-50          | 54        | 12.36%  |
| 101-250        | 54        | 12.36%  |
| 51-100         | 44        | 10.07%  |
| 251-500        | 42        | 9.61%   |
| 501-1000       | 34        | 7.78%   |
| Unknown        | 25        | 5.72%   |
| 1001-2000      | 21        | 4.81%   |
| More than 3000 | 13        | 2.97%   |
| 2001-3000      | 8         | 1.83%   |
| 0              | 3         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2         | 2      | 2.82%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 2      | 2.82%   |
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 1.41%   |
| WDC WD5000AAKX-00U6AA0 500GB                 | 1         | 1      | 1.41%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.41%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 1.41%   |
| WDC WD5000AAJS-22A8B0 500GB                  | 1         | 1      | 1.41%   |
| WDC WD40EFZX-68AWUN0 4TB                     | 1         | 6      | 1.41%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 1.41%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 1.41%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.41%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 1.41%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 1.41%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 1.41%   |
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 1.41%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 1      | 1.41%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.41%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 1.41%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.41%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.41%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.41%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.41%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1      | 1.41%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 2      | 1.41%   |
| Seagate ST960822A 64GB                       | 1         | 1      | 1.41%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.41%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 1.41%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.41%   |
| Seagate ST3320620A 320GB                     | 1         | 1      | 1.41%   |
| Seagate ST3200827AS 200GB                    | 1         | 1      | 1.41%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 1.41%   |
| Seagate ST3160813AS 160GB                    | 1         | 1      | 1.41%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 1.41%   |
| Seagate ST3120827AS 120GB                    | 1         | 1      | 1.41%   |
| Seagate ST31000333AS 1TB                     | 1         | 1      | 1.41%   |
| Seagate ST3000DM001-9YN166 320GB             | 1         | 1      | 1.41%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.41%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 1.41%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 1.41%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1      | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 1.41%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.41%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 1.41%   |
| SanDisk SSD PLUS 120 GB                      | 1         | 1      | 1.41%   |
| Samsung Electronics SSD 970 EVO 250GB        | 1         | 1      | 1.41%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 1      | 1.41%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 1.41%   |
| Samsung Electronics HM321HI 320GB            | 1         | 1      | 1.41%   |
| Samsung Electronics HD161GJ 160GB            | 1         | 1      | 1.41%   |
| PNY SSD2SC240G3LC709B121-460P 240GB          | 1         | 1      | 1.41%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 1.41%   |
| Kingston SE100S3100G 100GB SSD               | 1         | 1      | 1.41%   |
| KingDian S280 240GB SSD                      | 1         | 1      | 1.41%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 1.41%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 1.41%   |
| Intel SSDSA2M160G2HP 160GB                   | 1         | 1      | 1.41%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 1.41%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 28.99%  |
| WDC                 | 17        | 24     | 24.64%  |
| Hitachi             | 6         | 6      | 8.7%    |
| Toshiba             | 5         | 5      | 7.25%   |
| Samsung Electronics | 5         | 6      | 7.25%   |
| Intel               | 4         | 5      | 5.8%    |
| Kingston            | 3         | 3      | 4.35%   |
| A-DATA Technology   | 3         | 4      | 4.35%   |
| SK Hynix            | 1         | 2      | 1.45%   |
| SanDisk             | 1         | 1      | 1.45%   |
| PNY                 | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| KingDian            | 1         | 1      | 1.45%   |
| HGST                | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 39.22%  |
| WDC                 | 17        | 24     | 33.33%  |
| Hitachi             | 6         | 6      | 11.76%  |
| Toshiba             | 5         | 5      | 9.8%    |
| Samsung Electronics | 2         | 2      | 3.92%   |
| HGST                | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 60     | 73.53%  |
| SSD  | 15        | 17     | 22.06%  |
| NVMe | 3         | 5      | 4.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 354       | 618    | 69.82%  |
| Detected | 86        | 151    | 16.96%  |
| Malfunc  | 65        | 82     | 12.82%  |
| Failed   | 2         | 2      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 258       | 48.04%  |
| AMD                          | 89        | 16.57%  |
| Samsung Electronics          | 59        | 10.99%  |
| Sandisk                      | 26        | 4.84%   |
| Micron/Crucial Technology    | 11        | 2.05%   |
| SK Hynix                     | 10        | 1.86%   |
| Phison Electronics           | 10        | 1.86%   |
| Kingston Technology Company  | 9         | 1.68%   |
| Toshiba America Info Systems | 8         | 1.49%   |
| ASMedia Technology           | 7         | 1.3%    |
| KIOXIA                       | 6         | 1.12%   |
| Nvidia                       | 5         | 0.93%   |
| Marvell Technology Group     | 5         | 0.93%   |
| ADATA Technology             | 5         | 0.93%   |
| Micron Technology            | 4         | 0.74%   |
| JMicron Technology           | 4         | 0.74%   |
| Broadcom / LSI               | 4         | 0.74%   |
| Apple                        | 4         | 0.74%   |
| Union Memory (Shenzhen)      | 2         | 0.37%   |
| Lenovo                       | 2         | 0.37%   |
| VIA Technologies             | 1         | 0.19%   |
| Silicon Motion               | 1         | 0.19%   |
| Silicon Image                | 1         | 0.19%   |
| Seagate Technology           | 1         | 0.19%   |
| OCZ Technology Group         | 1         | 0.19%   |
| LSI Logic / Symbios Logic    | 1         | 0.19%   |
| Lite-On Technology           | 1         | 0.19%   |
| Hewlett-Packard              | 1         | 0.19%   |
| Adaptec                      | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 60        | 9.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 35        | 5.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 18        | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17        | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 2.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 2.09%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 1.45%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9         | 1.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8         | 1.29%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 8         | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.29%   |
| Samsung NVMe Controller                                                                 | 7         | 1.13%   |
| Phison E12 NVMe Controller                                                              | 7         | 1.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 6         | 0.97%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.97%   |
| Samsung Electronics SATA controller                                                     | 6         | 0.97%   |
| KIOXIA Non-Volatile memory controller                                                   | 6         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 0.97%   |
| Intel SSD 660P Series                                                                   | 5         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5         | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.81%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5         | 0.81%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.64%   |
| Micron Non-Volatile memory controller                                                   | 4         | 0.64%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 4         | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.64%   |
| Apple S1X NVMe Controller                                                               | 4         | 0.64%   |
| SK Hynix NVMe SSD Controller                                                            | 3         | 0.48%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.48%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.48%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.48%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 0.48%   |
| Intel SSD 600P Series                                                                   | 3         | 0.48%   |
| Intel NVMe Optane Memory Series                                                         | 3         | 0.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.48%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.48%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 3         | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 299       | 53.97%  |
| NVMe | 158       | 28.52%  |
| IDE  | 52        | 9.39%   |
| RAID | 39        | 7.04%   |
| SAS  | 6         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 319       | 74.01%  |
| AMD    | 105       | 24.36%  |
| ARM    | 7         | 1.62%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 9         | 2.09%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 2.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 1.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.16%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 1.16%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.93%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.93%   |
| ARM Processor                                 | 4         | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.93%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 0.7%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.7%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.7%    |
| AMD FX-8350 Eight-Core Processor              | 3         | 0.7%    |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz           | 2         | 0.46%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.46%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 2         | 0.46%   |
| Intel Genuine CPU T1400 @ 1.73GHz             | 2         | 0.46%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.46%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.46%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.46%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.46%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.46%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.46%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.46%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.46%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 0.46%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2         | 0.46%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.46%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.46%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.46%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 113       | 26.22%  |
| Intel Core i7          | 85        | 19.72%  |
| AMD Ryzen 5            | 29        | 6.73%   |
| Other                  | 24        | 5.57%   |
| AMD Ryzen 7            | 21        | 4.87%   |
| Intel Celeron          | 20        | 4.64%   |
| Intel Xeon             | 17        | 3.94%   |
| Intel Core i3          | 16        | 3.71%   |
| Intel Core 2 Duo       | 15        | 3.48%   |
| Intel Pentium          | 10        | 2.32%   |
| AMD Ryzen 7 PRO        | 7         | 1.62%   |
| AMD FX                 | 7         | 1.62%   |
| AMD Ryzen 9            | 5         | 1.16%   |
| AMD Ryzen 3            | 5         | 1.16%   |
| Intel Pentium M        | 4         | 0.93%   |
| Intel Core 2           | 4         | 0.93%   |
| Intel Atom             | 4         | 0.93%   |
| AMD Ryzen Threadripper | 4         | 0.93%   |
| AMD Phenom II X4       | 4         | 0.93%   |
| Intel Core 2 Quad      | 3         | 0.7%    |
| Intel Pentium Gold     | 2         | 0.46%   |
| Intel Genuine          | 2         | 0.46%   |
| Intel Celeron M        | 2         | 0.46%   |
| AMD Turion 64 Mobile   | 2         | 0.46%   |
| AMD Athlon X4          | 2         | 0.46%   |
| AMD A8                 | 2         | 0.46%   |
| AMD A10                | 2         | 0.46%   |
| Intel Xeon Silver      | 1         | 0.23%   |
| Intel Pentium Dual     | 1         | 0.23%   |
| Intel Pentium 4        | 1         | 0.23%   |
| Intel Core m7          | 1         | 0.23%   |
| Intel Core i9          | 1         | 0.23%   |
| ARM BCM                | 1         | 0.23%   |
| ARM Allwinner          | 1         | 0.23%   |
| ARM AArch64            | 1         | 0.23%   |
| AMD Sempron            | 1         | 0.23%   |
| AMD PRO A8             | 1         | 0.23%   |
| AMD Phenom II X3       | 1         | 0.23%   |
| AMD GX                 | 1         | 0.23%   |
| AMD C-30               | 1         | 0.23%   |
| AMD Athlon XP          | 1         | 0.23%   |
| AMD Athlon II X2       | 1         | 0.23%   |
| AMD Athlon II Neo      | 1         | 0.23%   |
| AMD Athlon Dual Core   | 1         | 0.23%   |
| AMD Athlon 64          | 1         | 0.23%   |
| AMD A6                 | 1         | 0.23%   |
| AMD A12                | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 156       | 36.19%  |
| 2      | 155       | 35.96%  |
| 6      | 47        | 10.9%   |
| 8      | 37        | 8.58%   |
| 1      | 20        | 4.64%   |
| 16     | 6         | 1.39%   |
| 12     | 6         | 1.39%   |
| 44     | 1         | 0.23%   |
| 32     | 1         | 0.23%   |
| 28     | 1         | 0.23%   |
| 3      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 422       | 97.91%  |
| 2      | 9         | 2.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 301       | 69.84%  |
| 1      | 130       | 30.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 417       | 96.75%  |
| 32-bit         | 10        | 2.32%   |
| 64-bit         | 2         | 0.46%   |
| Unknown        | 2         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 17.74%  |
| 0x306a9    | 28        | 6.45%   |
| 0x206a7    | 22        | 5.07%   |
| 0x306d4    | 17        | 3.92%   |
| 0x306c3    | 16        | 3.69%   |
| 0x806c1    | 14        | 3.23%   |
| 0x08701021 | 14        | 3.23%   |
| 0x906ea    | 13        | 3%      |
| 0x806ec    | 13        | 3%      |
| 0x806e9    | 11        | 2.53%   |
| 0x806ea    | 10        | 2.3%    |
| 0x406e3    | 9         | 2.07%   |
| 0x1067a    | 9         | 2.07%   |
| 0x906e9    | 8         | 1.84%   |
| 0x706e5    | 8         | 1.84%   |
| 0x08600106 | 8         | 1.84%   |
| 0xa0652    | 7         | 1.61%   |
| 0x206d7    | 7         | 1.61%   |
| 0x08108109 | 7         | 1.61%   |
| 0x506e3    | 6         | 1.38%   |
| 0x40651    | 6         | 1.38%   |
| 0x06003106 | 6         | 1.38%   |
| 0x806eb    | 5         | 1.15%   |
| 0x506c9    | 5         | 1.15%   |
| 0x20655    | 5         | 1.15%   |
| 0x6fd      | 4         | 0.92%   |
| 0x6d8      | 4         | 0.92%   |
| 0x306f2    | 4         | 0.92%   |
| 0x0a201009 | 4         | 0.92%   |
| 0x0800820d | 4         | 0.92%   |
| 0x6f6      | 3         | 0.69%   |
| 0x30678    | 3         | 0.69%   |
| 0x08001138 | 3         | 0.69%   |
| 0x0600611a | 3         | 0.69%   |
| 0x06000852 | 3         | 0.69%   |
| 0x010000c8 | 3         | 0.69%   |
| 0x010000b6 | 3         | 0.69%   |
| 0xa0660    | 2         | 0.46%   |
| 0xa0655    | 2         | 0.46%   |
| 0x706a8    | 2         | 0.46%   |
| 0x6fb      | 2         | 0.46%   |
| 0x695      | 2         | 0.46%   |
| 0x406c4    | 2         | 0.46%   |
| 0x406c3    | 2         | 0.46%   |
| 0x106c2    | 2         | 0.46%   |
| 0x0a201016 | 2         | 0.46%   |
| 0x08701013 | 2         | 0.46%   |
| 0x08600104 | 2         | 0.46%   |
| 0x08600103 | 2         | 0.46%   |
| 0x08108102 | 2         | 0.46%   |
| 0xf41      | 1         | 0.23%   |
| 0xf29      | 1         | 0.23%   |
| 0xa0671    | 1         | 0.23%   |
| 0xa0653    | 1         | 0.23%   |
| 0x906ed    | 1         | 0.23%   |
| 0x906ec    | 1         | 0.23%   |
| 0x906eb    | 1         | 0.23%   |
| 0x706a1    | 1         | 0.23%   |
| 0x6fa      | 1         | 0.23%   |
| 0x6f2      | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 78        | 18.1%   |
| Zen 2         | 36        | 8.35%   |
| IvyBridge     | 34        | 7.89%   |
| Haswell       | 34        | 7.89%   |
| SandyBridge   | 29        | 6.73%   |
| Skylake       | 23        | 5.34%   |
| Zen+          | 19        | 4.41%   |
| Broadwell     | 18        | 4.18%   |
| TigerLake     | 16        | 3.71%   |
| Core          | 14        | 3.25%   |
| CometLake     | 13        | 3.02%   |
| Penryn        | 12        | 2.78%   |
| Westmere      | 10        | 2.32%   |
| Zen 3         | 9         | 2.09%   |
| Silvermont    | 9         | 2.09%   |
| Unknown       | 9         | 2.09%   |
| K10           | 8         | 1.86%   |
| IceLake       | 8         | 1.86%   |
| Steamroller   | 7         | 1.62%   |
| Zen           | 6         | 1.39%   |
| P6            | 6         | 1.39%   |
| Piledriver    | 5         | 1.16%   |
| Goldmont      | 5         | 1.16%   |
| K8 Hammer     | 4         | 0.93%   |
| Excavator     | 4         | 0.93%   |
| Goldmont plus | 3         | 0.7%    |
| NetBurst      | 2         | 0.46%   |
| Nehalem       | 2         | 0.46%   |
| Bulldozer     | 2         | 0.46%   |
| Bonnell       | 2         | 0.46%   |
| K6            | 1         | 0.23%   |
| K10 Llano     | 1         | 0.23%   |
| Jaguar        | 1         | 0.23%   |
| Bobcat        | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 251       | 51.02%  |
| Nvidia                     | 122       | 24.8%   |
| AMD                        | 108       | 21.95%  |
| ASPEED Technology          | 7         | 1.42%   |
| Matrox Electronics Systems | 4         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 3.75%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 2.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 2.77%   |
| AMD Renoir                                                                               | 14        | 2.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2.37%   |
| AMD Picasso                                                                              | 11        | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.98%   |
| Intel HD Graphics 620                                                                    | 10        | 1.98%   |
| Intel HD Graphics 6000                                                                   | 9         | 1.78%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.58%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.38%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 1.38%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 1.38%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.19%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 0.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.79%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.79%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 0.79%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.79%   |
| Intel HD Graphics 630                                                                    | 4         | 0.79%   |
| Intel HD Graphics 530                                                                    | 4         | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.79%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.59%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.59%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.59%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.59%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.4%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.4%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.4%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.4%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.4%    |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.4%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.4%    |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2         | 0.4%    |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 189       | 43.65%  |
| 1 x AMD         | 87        | 20.09%  |
| 1 x Nvidia      | 70        | 16.17%  |
| Intel + Nvidia  | 48        | 11.09%  |
| Intel + AMD     | 12        | 2.77%   |
| Other           | 8         | 1.85%   |
| 1 x ASPEED      | 6         | 1.39%   |
| 2 x AMD         | 4         | 0.92%   |
| AMD + Nvidia    | 4         | 0.92%   |
| 1 x Matrox      | 3         | 0.69%   |
| Nvidia + Matrox | 1         | 0.23%   |
| AMD + ASPEED    | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 374       | 86.57%  |
| Proprietary | 44        | 10.19%  |
| Unknown     | 14        | 3.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 273       | 62.76%  |
| 0.01-0.5   | 42        | 9.66%   |
| 1.01-2.0   | 34        | 7.82%   |
| 0.51-1.0   | 26        | 5.98%   |
| 3.01-4.0   | 24        | 5.52%   |
| 7.01-8.0   | 23        | 5.29%   |
| 5.01-6.0   | 7         | 1.61%   |
| 2.01-3.0   | 2         | 0.46%   |
| 8.01-16.0  | 2         | 0.46%   |
| 24.01-32.0 | 1         | 0.23%   |
| 16.01-24.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 11.53%  |
| Samsung Electronics     | 48        | 10.06%  |
| BOE                     | 42        | 8.81%   |
| Chimei Innolux          | 40        | 8.39%   |
| LG Display              | 37        | 7.76%   |
| Dell                    | 31        | 6.5%    |
| Goldstar                | 27        | 5.66%   |
| Apple                   | 18        | 3.77%   |
| Ancor Communications    | 18        | 3.77%   |
| Acer                    | 18        | 3.77%   |
| Hewlett-Packard         | 16        | 3.35%   |
| BenQ                    | 14        | 2.94%   |
| Sharp                   | 11        | 2.31%   |
| Lenovo                  | 11        | 2.31%   |
| Philips                 | 10        | 2.1%    |
| AOC                     | 10        | 2.1%    |
| ViewSonic               | 8         | 1.68%   |
| NEC Computers           | 5         | 1.05%   |
| ASUSTek Computer        | 5         | 1.05%   |
| InfoVision              | 4         | 0.84%   |
| Unknown                 | 3         | 0.63%   |
| Iiyama                  | 3         | 0.63%   |
| Chi Mei Optoelectronics | 3         | 0.63%   |
| Vestel Elektronik       | 2         | 0.42%   |
| Sony                    | 2         | 0.42%   |
| PANDA                   | 2         | 0.42%   |
| LG Philips              | 2         | 0.42%   |
| LG Electronics          | 2         | 0.42%   |
| HannStar                | 2         | 0.42%   |
| Eizo                    | 2         | 0.42%   |
| CPT                     | 2         | 0.42%   |
| ___                     | 1         | 0.21%   |
| Vizio                   | 1         | 0.21%   |
| TEO                     | 1         | 0.21%   |
| Prestigio               | 1         | 0.21%   |
| ODH                     | 1         | 0.21%   |
| NCS                     | 1         | 0.21%   |
| MSI                     | 1         | 0.21%   |
| MIT                     | 1         | 0.21%   |
| Mi                      | 1         | 0.21%   |
| Medion                  | 1         | 0.21%   |
| LPL                     | 1         | 0.21%   |
| JXG                     | 1         | 0.21%   |
| JVC                     | 1         | 0.21%   |
| JRY                     | 1         | 0.21%   |
| IOD                     | 1         | 0.21%   |
| INFOTRONIC              | 1         | 0.21%   |
| Idek Iiyama             | 1         | 0.21%   |
| HKC                     | 1         | 0.21%   |
| Hitachi                 | 1         | 0.21%   |
| HannStar Display        | 1         | 0.21%   |
| CSO                     | 1         | 0.21%   |
| COBY                    | 1         | 0.21%   |
| CMN                     | 1         | 0.21%   |
| Belinea                 | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 4         | 0.82%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 4         | 0.82%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 0.82%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 3         | 0.61%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch            | 3         | 0.61%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.61%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 0.61%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3         | 0.61%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                   | 3         | 0.61%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 3         | 0.61%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 2         | 0.41%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2         | 0.41%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.41%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.41%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 2         | 0.41%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.41%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 0.41%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch            | 2         | 0.41%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 2         | 0.41%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 2         | 0.41%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 2         | 0.41%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2         | 0.41%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.41%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 2         | 0.41%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.41%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2         | 0.41%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.41%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2         | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.41%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 2         | 0.41%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.41%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.41%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                   | 2         | 0.41%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch          | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 195       | 42.12%  |
| 1366x768 (WXGA)    | 72        | 15.55%  |
| 3840x2160 (4K)     | 31        | 6.7%    |
| 2560x1440 (QHD)    | 28        | 6.05%   |
| 1600x900 (HD+)     | 20        | 4.32%   |
| 1280x1024 (SXGA)   | 18        | 3.89%   |
| 1920x1200 (WUXGA)  | 16        | 3.46%   |
| 1280x800 (WXGA)    | 14        | 3.02%   |
| 1680x1050 (WSXGA+) | 13        | 2.81%   |
| 1440x900 (WXGA+)   | 13        | 2.81%   |
| 1024x768 (XGA)     | 10        | 2.16%   |
| Unknown            | 5         | 1.08%   |
| 2560x1080          | 4         | 0.86%   |
| 3440x1440          | 3         | 0.65%   |
| 2560x1600          | 3         | 0.65%   |
| 1600x1200          | 3         | 0.65%   |
| 2288x1287          | 2         | 0.43%   |
| 1024x600           | 2         | 0.43%   |
| 7680x4320          | 1         | 0.22%   |
| 5760x1080          | 1         | 0.22%   |
| 4480x1440          | 1         | 0.22%   |
| 3840x2400          | 1         | 0.22%   |
| 3840x1080          | 1         | 0.22%   |
| 3360x1080          | 1         | 0.22%   |
| 2880x1800          | 1         | 0.22%   |
| 2256x1504          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 1920x540           | 1         | 0.22%   |
| 1792x768           | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 92        | 19.41%  |
| 13      | 64        | 13.5%   |
| 14      | 44        | 9.28%   |
| 24      | 42        | 8.86%   |
| 27      | 33        | 6.96%   |
| 23      | 33        | 6.96%   |
| 17      | 28        | 5.91%   |
| 21      | 21        | 4.43%   |
| 12      | 15        | 3.16%   |
| Unknown | 15        | 3.16%   |
| 11      | 14        | 2.95%   |
| 31      | 11        | 2.32%   |
| 19      | 9         | 1.9%    |
| 18      | 8         | 1.69%   |
| 34      | 6         | 1.27%   |
| 22      | 6         | 1.27%   |
| 20      | 6         | 1.27%   |
| 25      | 4         | 0.84%   |
| 84      | 3         | 0.63%   |
| 28      | 3         | 0.63%   |
| 142     | 2         | 0.42%   |
| 72      | 2         | 0.42%   |
| 47      | 2         | 0.42%   |
| 29      | 2         | 0.42%   |
| 10      | 2         | 0.42%   |
| 55      | 1         | 0.21%   |
| 48      | 1         | 0.21%   |
| 40      | 1         | 0.21%   |
| 38      | 1         | 0.21%   |
| 33      | 1         | 0.21%   |
| 32      | 1         | 0.21%   |
| 16      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 175       | 37.55%  |
| 501-600        | 97        | 20.82%  |
| 201-300        | 65        | 13.95%  |
| 401-500        | 47        | 10.09%  |
| 351-400        | 24        | 5.15%   |
| 601-700        | 22        | 4.72%   |
| Unknown        | 15        | 3.22%   |
| 701-800        | 8         | 1.72%   |
| 1501-2000      | 5         | 1.07%   |
| 1001-1500      | 4         | 0.86%   |
| More than 2000 | 2         | 0.43%   |
| 801-900        | 2         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 316       | 72.48%  |
| 16/10   | 55        | 12.61%  |
| 5/4     | 16        | 3.67%   |
| 4/3     | 16        | 3.67%   |
| Unknown | 14        | 3.21%   |
| 21/9    | 8         | 1.83%   |
| 3/2     | 7         | 1.61%   |
| 1.00    | 2         | 0.46%   |
| 6/5     | 1         | 0.23%   |
| 1.96    | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 19.62%  |
| 81-90          | 83        | 17.7%   |
| 201-250        | 78        | 16.63%  |
| 301-350        | 33        | 7.04%   |
| 71-80          | 26        | 5.54%   |
| 351-500        | 23        | 4.9%    |
| 151-200        | 22        | 4.69%   |
| 251-300        | 19        | 4.05%   |
| 141-150        | 17        | 3.62%   |
| 121-130        | 15        | 3.2%    |
| Unknown        | 15        | 3.2%    |
| 61-70          | 14        | 2.99%   |
| 51-60          | 14        | 2.99%   |
| More than 1000 | 8         | 1.71%   |
| 501-1000       | 5         | 1.07%   |
| 131-140        | 3         | 0.64%   |
| 41-50          | 2         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 155       | 34.14%  |
| 51-100        | 152       | 33.48%  |
| 101-120       | 86        | 18.94%  |
| 161-240       | 30        | 6.61%   |
| Unknown       | 15        | 3.3%    |
| More than 240 | 8         | 1.76%   |
| 1-50          | 8         | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 329       | 75.98%  |
| 2     | 71        | 16.4%   |
| 0     | 23        | 5.31%   |
| 3     | 9         | 2.08%   |
| 4     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 237       | 39.43%  |
| Realtek Semiconductor             | 199       | 33.11%  |
| Qualcomm Atheros                  | 59        | 9.82%   |
| Broadcom                          | 36        | 5.99%   |
| Broadcom Limited                  | 16        | 2.66%   |
| Marvell Technology Group          | 6         | 1%      |
| Nvidia                            | 5         | 0.83%   |
| Ralink Technology                 | 3         | 0.5%    |
| Ralink                            | 3         | 0.5%    |
| Ericsson Business Mobile Networks | 3         | 0.5%    |
| AMD                               | 3         | 0.5%    |
| Xiaomi                            | 2         | 0.33%   |
| Sierra Wireless                   | 2         | 0.33%   |
| Microsoft                         | 2         | 0.33%   |
| Microchip Technology              | 2         | 0.33%   |
| Edimax Technology                 | 2         | 0.33%   |
| DisplayLink                       | 2         | 0.33%   |
| Dell                              | 2         | 0.33%   |
| D-Link                            | 2         | 0.33%   |
| Cypress Semiconductor             | 2         | 0.33%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.17%   |
| TP-Link                           | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| Mellanox Technologies             | 1         | 0.17%   |
| MEDIATEK                          | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| IBM                               | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Attansic Technology               | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |
| American Megatrends               | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 141       | 19.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 3.73%   |
| Intel Wi-Fi 6 AX200                                               | 24        | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.93%   |
| Intel Wireless 8265 / 8275                                        | 14        | 1.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 1.8%    |
| Intel Wireless 8260                                               | 13        | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 13        | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.38%   |
| Intel Wireless 7260                                               | 10        | 1.38%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 1.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 9         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.83%   |
| Intel Wireless 3165                                               | 6         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.69%   |
| Intel Wireless 7265                                               | 5         | 0.69%   |
| Intel Wireless 3160                                               | 5         | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.55%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.41%   |
| Intel Wireless-AC 9260                                            | 3         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.41%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.41%   |
| AMD IXP SB400 AC'97 Modem Controller                              | 3         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.28%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 2         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 178       | 57.61%  |
| Qualcomm Atheros                  | 45        | 14.56%  |
| Realtek Semiconductor             | 38        | 12.3%   |
| Broadcom                          | 16        | 5.18%   |
| Broadcom Limited                  | 14        | 4.53%   |
| Ralink Technology                 | 3         | 0.97%   |
| Ralink                            | 3         | 0.97%   |
| Sierra Wireless                   | 2         | 0.65%   |
| Microsoft                         | 2         | 0.65%   |
| Edimax Technology                 | 2         | 0.65%   |
| TP-Link                           | 1         | 0.32%   |
| Qualcomm                          | 1         | 0.32%   |
| MEDIATEK                          | 1         | 0.32%   |
| Fibocom                           | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 24        | 7.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 14        | 4.52%   |
| Intel Wireless 8265 / 8275                                                  | 14        | 4.52%   |
| Intel Wireless 8260                                                         | 13        | 4.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 12        | 3.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 11        | 3.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 10        | 3.23%   |
| Intel Wireless 7260                                                         | 10        | 3.23%   |
| Intel Wi-Fi 6 AX201                                                         | 10        | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 9         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 8         | 2.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 7         | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 7         | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 7         | 2.26%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 7         | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 7         | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 1.94%   |
| Intel Wireless 3165                                                         | 6         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 5         | 1.61%   |
| Intel Wireless 7265                                                         | 5         | 1.61%   |
| Intel Wireless 3160                                                         | 5         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 5         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                              | 5         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 4         | 1.29%   |
| Intel Centrino Wireless-N 2230                                              | 4         | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 3         | 0.97%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 3         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 3         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 3         | 0.97%   |
| Intel Wireless-AC 9260                                                      | 3         | 0.97%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.97%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                         | 2         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 2         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2         | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                                         | 2         | 0.65%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.65%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 2         | 0.65%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver | 2         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                              | 2         | 0.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 2         | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 0.65%   |
| TP-Link Archer T4U ver.3                                                    | 1         | 0.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 1         | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.32%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 0.32%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                    | 1         | 0.32%   |
| Realtek 802.11ac NIC                                                        | 1         | 0.32%   |
| Ralink RT5372 Wireless Adapter                                              | 1         | 0.32%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 0.32%   |
| Ralink MT7601U Wireless Adapter                                             | 1         | 0.32%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                 | 1         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.32%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 180       | 46.27%  |
| Intel                    | 134       | 34.45%  |
| Broadcom                 | 24        | 6.17%   |
| Qualcomm Atheros         | 21        | 5.4%    |
| Marvell Technology Group | 6         | 1.54%   |
| Nvidia                   | 5         | 1.29%   |
| Broadcom Limited         | 3         | 0.77%   |
| Xiaomi                   | 2         | 0.51%   |
| Microchip Technology     | 2         | 0.51%   |
| DisplayLink              | 2         | 0.51%   |
| Cypress Semiconductor    | 2         | 0.51%   |
| Mellanox Technologies    | 1         | 0.26%   |
| JMicron Technology       | 1         | 0.26%   |
| IBM                      | 1         | 0.26%   |
| Huawei Technologies      | 1         | 0.26%   |
| D-Link                   | 1         | 0.26%   |
| Attansic Technology      | 1         | 0.26%   |
| Aquantia                 | 1         | 0.26%   |
| American Megatrends      | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 141       | 35.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 6.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.24%   |
| Intel I211 Gigabit Network Connection                             | 13        | 3.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.49%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.75%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 6         | 1.5%    |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1%      |
| Intel Ethernet Connection I218-LM                                 | 4         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1%      |
| Intel 82574L Gigabit Network Connection                           | 4         | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 2         | 0.5%    |
| Intel I350 Gigabit Network Connection                             | 2         | 0.5%    |
| Intel Ethernet Controller 10G X550T                               | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.5%    |
| Cypress K38231_03                                                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.5%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.25%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.25%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.25%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.25%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.25%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.25%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 366       | 53.9%   |
| WiFi     | 300       | 44.18%  |
| Modem    | 13        | 1.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 289       | 51.98%  |
| WiFi     | 266       | 47.84%  |
| Modem    | 1         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 232       | 53.83%  |
| 1     | 168       | 38.98%  |
| 3     | 14        | 3.25%   |
| 0     | 9         | 2.09%   |
| 4     | 5         | 1.16%   |
| 13    | 1         | 0.23%   |
| 6     | 1         | 0.23%   |
| 5     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 343       | 79.4%   |
| Yes  | 89        | 20.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 53.63%  |
| Qualcomm Atheros Communications | 21        | 8.47%   |
| Realtek Semiconductor           | 17        | 6.85%   |
| Broadcom                        | 16        | 6.45%   |
| Apple                           | 16        | 6.45%   |
| Cambridge Silicon Radio         | 12        | 4.84%   |
| Lite-On Technology              | 8         | 3.23%   |
| IMC Networks                    | 5         | 2.02%   |
| Hewlett-Packard                 | 4         | 1.61%   |
| ASUSTek Computer                | 4         | 1.61%   |
| Realtek                         | 3         | 1.21%   |
| Foxconn / Hon Hai               | 3         | 1.21%   |
| Toshiba                         | 2         | 0.81%   |
| Dell                            | 2         | 0.81%   |
| Taiyo Yuden                     | 1         | 0.4%    |
| Ralink                          | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 19.35%  |
| Intel Bluetooth Device                              | 46        | 18.55%  |
| Intel AX200 Bluetooth                               | 25        | 10.08%  |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 5.24%   |
| Realtek Bluetooth Radio                             | 12        | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 4.84%   |
| Apple Bluetooth USB Host Controller                 | 9         | 3.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 2.42%   |
| Lite-On Bluetooth Device                            | 5         | 2.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 2.02%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.61%   |
| Realtek Bluetooth Radio                             | 3         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.21%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.21%   |
| Apple Bluetooth Host Controller                     | 3         | 1.21%   |
| Toshiba Bluetooth Device                            | 2         | 0.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.81%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 0.81%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.4%    |
| Realtek CSR BS8510                                  | 1         | 0.4%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.4%    |
| Lite-On Wireless_Device                             | 1         | 0.4%    |
| Lite-On BCM43142A0                                  | 1         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.4%    |
| IMC Networks Bluetooth Device                       | 1         | 0.4%    |
| IMC Networks Bluetooth                              | 1         | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.4%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.4%    |
| Dell DW375 Bluetooth Module                         | 1         | 0.4%    |
| Dell BCM20702A0                                     | 1         | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 1         | 0.4%    |
| Broadcom Bluetooth 3.0 Device                       | 1         | 0.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.4%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.4%    |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.4%    |
| ASUS Bluetooth Radio                                | 1         | 0.4%    |
| ASUS Bluetooth Adapter                              | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 300       | 52.08%  |
| AMD                        | 118       | 20.49%  |
| Nvidia                     | 91        | 15.8%   |
| C-Media Electronics        | 14        | 2.43%   |
| Generalplus Technology     | 7         | 1.22%   |
| Logitech                   | 5         | 0.87%   |
| GYROCOM C&C                | 4         | 0.69%   |
| GN Netcom                  | 4         | 0.69%   |
| Creative Labs              | 4         | 0.69%   |
| Texas Instruments          | 3         | 0.52%   |
| Plantronics                | 3         | 0.52%   |
| Samson Technologies        | 2         | 0.35%   |
| BEHRINGER International    | 2         | 0.35%   |
| XMOS                       | 1         | 0.17%   |
| VIA Technologies           | 1         | 0.17%   |
| TEAC                       | 1         | 0.17%   |
| SteelSeries ApS            | 1         | 0.17%   |
| RODE Microphones           | 1         | 0.17%   |
| ROCCAT                     | 1         | 0.17%   |
| Razer USA                  | 1         | 0.17%   |
| PreSonus Audio Electronics | 1         | 0.17%   |
| JMTek                      | 1         | 0.17%   |
| Hewlett-Packard            | 1         | 0.17%   |
| Hangzhou Worlde            | 1         | 0.17%   |
| Dell                       | 1         | 0.17%   |
| Creative Technology        | 1         | 0.17%   |
| Blue Microphones           | 1         | 0.17%   |
| AXELVOX                    | 1         | 0.17%   |
| AVID Technology            | 1         | 0.17%   |
| Audioengine                | 1         | 0.17%   |
| ASUSTek Computer           | 1         | 0.17%   |
| Alesis                     | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 5.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 4.71%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 30        | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 3.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 2.5%    |
| Intel Broadwell-U Audio Controller                                                                | 17        | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15        | 2.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 2.06%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.32%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.18%   |
| Generalplus Technology USB Audio Device                                                           | 7         | 1.03%   |
| AMD Navi 10 HDMI Audio                                                                            | 7         | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5         | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 0.74%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 5         | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.44%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.44%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.44%   |
| GYROCOM C&C Fiio E10                                                                              | 3         | 0.44%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.44%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.44%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.29%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 93        | 20.35%  |
| SK Hynix            | 88        | 19.26%  |
| Kingston            | 62        | 13.57%  |
| Unknown             | 46        | 10.07%  |
| Crucial             | 35        | 7.66%   |
| Micron Technology   | 33        | 7.22%   |
| Corsair             | 30        | 6.56%   |
| G.Skill             | 15        | 3.28%   |
| A-DATA Technology   | 12        | 2.63%   |
| Ramaxel Technology  | 8         | 1.75%   |
| Nanya Technology    | 6         | 1.31%   |
| ELPIDA              | 6         | 1.31%   |
| Team                | 4         | 0.88%   |
| Patriot             | 3         | 0.66%   |
| Kllisre             | 3         | 0.66%   |
| Unknown (ABCD)      | 2         | 0.44%   |
| GOODRAM             | 2         | 0.44%   |
| V-Color             | 1         | 0.22%   |
| Unifosa             | 1         | 0.22%   |
| SMART Brazil        | 1         | 0.22%   |
| Smart               | 1         | 0.22%   |
| PNY                 | 1         | 0.22%   |
| Kingmax             | 1         | 0.22%   |
| KETECH              | 1         | 0.22%   |
| Infineon            | 1         | 0.22%   |
| GeIL                | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 1.01%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.01%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s         | 4         | 0.8%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 4         | 0.8%    |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.6%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.6%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 0.6%    |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 3         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.6%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 3         | 0.6%    |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 3         | 0.6%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.6%    |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.6%    |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 3         | 0.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.4%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 2         | 0.4%    |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 2         | 0.4%    |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s             | 2         | 0.4%    |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 2         | 0.4%    |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 2         | 0.4%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.4%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.4%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.4%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.4%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.4%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.4%    |
| Samsung RAM M4 70L6524CU0-CB3 512MB SODIMM DDR 333MT/s           | 2         | 0.4%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.4%    |
| Nanya RAM NT512D64SH8B0GN-6K 512MB SODIMM DDR 333MT/s            | 2         | 0.4%    |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.4%    |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 2         | 0.4%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 2         | 0.4%    |
| Kingston RAM KHX2400C14S4/16G 16384MB SODIMM DDR4 2667MT/s       | 2         | 0.4%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.4%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 0.4%    |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 0.4%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 189       | 47.85%  |
| DDR3    | 141       | 35.7%   |
| DDR2    | 22        | 5.57%   |
| LPDDR3  | 11        | 2.78%   |
| SDRAM   | 9         | 2.28%   |
| Unknown | 9         | 2.28%   |
| LPDDR4  | 8         | 2.03%   |
| DDR     | 5         | 1.27%   |
| DRAM    | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 224       | 56.85%  |
| DIMM         | 145       | 36.8%   |
| Row Of Chips | 21        | 5.33%   |
| Chip         | 2         | 0.51%   |
| RIMM         | 1         | 0.25%   |
| Unknown      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 153       | 35.83%  |
| 4096  | 112       | 26.23%  |
| 16384 | 65        | 15.22%  |
| 2048  | 42        | 9.84%   |
| 1024  | 24        | 5.62%   |
| 32768 | 18        | 4.22%   |
| 512   | 9         | 2.11%   |
| 256   | 3         | 0.7%    |
| 65536 | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 99        | 22.86%  |
| 2667    | 72        | 16.63%  |
| 3200    | 58        | 13.39%  |
| 1333    | 39        | 9.01%   |
| 2400    | 34        | 7.85%   |
| 2133    | 23        | 5.31%   |
| 1334    | 15        | 3.46%   |
| 3600    | 10        | 2.31%   |
| 800     | 8         | 1.85%   |
| 667     | 8         | 1.85%   |
| 1867    | 7         | 1.62%   |
| 400     | 6         | 1.39%   |
| Unknown | 6         | 1.39%   |
| 2933    | 5         | 1.15%   |
| 533     | 5         | 1.15%   |
| 1866    | 4         | 0.92%   |
| 1067    | 4         | 0.92%   |
| 333     | 4         | 0.92%   |
| 4267    | 3         | 0.69%   |
| 3466    | 3         | 0.69%   |
| 2666    | 3         | 0.69%   |
| 3400    | 2         | 0.46%   |
| 3000    | 2         | 0.46%   |
| 1066    | 2         | 0.46%   |
| 4266    | 1         | 0.23%   |
| 4199    | 1         | 0.23%   |
| 3533    | 1         | 0.23%   |
| 3500    | 1         | 0.23%   |
| 3100    | 1         | 0.23%   |
| 3066    | 1         | 0.23%   |
| 2465    | 1         | 0.23%   |
| 2000    | 1         | 0.23%   |
| 1800    | 1         | 0.23%   |
| 1367    | 1         | 0.23%   |
| 975     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Konica Minolta      | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 11.11%  |
| Samsung ML-1660 Series              | 1         | 11.11%  |
| Konica Minolta bizhub 4402P         | 1         | 11.11%  |
| HP LaserJet P1006                   | 1         | 11.11%  |
| HP LaserJet M101-M106               | 1         | 11.11%  |
| HP LaserJet 1200                    | 1         | 11.11%  |
| HP ENVY 4520 series                 | 1         | 11.11%  |
| Canon LiDE 400                      | 1         | 11.11%  |
| Canon iP2700 series                 | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 50%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 25%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 18.52%  |
| IMC Networks                           | 35        | 14.4%   |
| Acer                                   | 24        | 9.88%   |
| Microdia                               | 23        | 9.47%   |
| Realtek Semiconductor                  | 18        | 7.41%   |
| Logitech                               | 17        | 7%      |
| Lite-On Technology                     | 11        | 4.53%   |
| Quanta                                 | 10        | 4.12%   |
| Sunplus Innovation Technology          | 9         | 3.7%    |
| Suyin                                  | 6         | 2.47%   |
| Apple                                  | 6         | 2.47%   |
| Luxvisions Innotech Limited            | 5         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.06%   |
| Syntek                                 | 4         | 1.65%   |
| Samsung Electronics                    | 3         | 1.23%   |
| Z-Star Microelectronics                | 2         | 0.82%   |
| Genesys Logic                          | 2         | 0.82%   |
| Generalplus Technology                 | 2         | 0.82%   |
| eMPIA Technology                       | 2         | 0.82%   |
| Xiongmai                               | 1         | 0.41%   |
| SiGma Micro                            | 1         | 0.41%   |
| Razer USA                              | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| Pixart Imaging                         | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| Jieli Technology                       | 1         | 0.41%   |
| Huawei Technologies                    | 1         | 0.41%   |
| Hewlett-Packard                        | 1         | 0.41%   |
| AVerMedia Technologies                 | 1         | 0.41%   |
| ARC International                      | 1         | 0.41%   |
| ALi                                    | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |
| A4Tech                                 | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 15        | 6.15%   |
| IMC Networks Integrated Camera                | 13        | 5.33%   |
| Microdia Integrated_Webcam_HD                 | 10        | 4.1%    |
| Acer Integrated Camera                        | 9         | 3.69%   |
| Realtek Integrated_Webcam_HD                  | 8         | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam             | 8         | 3.28%   |
| Chicony HD Webcam                             | 6         | 2.46%   |
| Chicony HP HD Camera                          | 5         | 2.05%   |
| Acer SunplusIT Integrated Camera              | 5         | 2.05%   |
| Lite-On Integrated Camera                     | 4         | 1.64%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 1.23%   |
| Samsung Galaxy A5 (MTP)                       | 3         | 1.23%   |
| Realtek Integrated Webcam                     | 3         | 1.23%   |
| Microdia Webcam Vitade AF                     | 3         | 1.23%   |
| Logitech Webcam C270                          | 3         | 1.23%   |
| Logitech HD Pro Webcam C920                   | 3         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 1.23%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 3         | 1.23%   |
| Syntek Integrated Camera                      | 2         | 0.82%   |
| Realtek EasyCamera                            | 2         | 0.82%   |
| Quanta HD Webcam                              | 2         | 0.82%   |
| Microdia USB 2.0 Camera                       | 2         | 0.82%   |
| Microdia Integrated Webcam HD                 | 2         | 0.82%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.82%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 0.82%   |
| Logitech HD Webcam C910                       | 2         | 0.82%   |
| Logitech HD Webcam C615                       | 2         | 0.82%   |
| Logitech C505 HD Webcam                       | 2         | 0.82%   |
| Lite-On HP Webcam                             | 2         | 0.82%   |
| Lite-On HP HD Camera                          | 2         | 0.82%   |
| IMC Networks ov9734_azurewave_camera          | 2         | 0.82%   |
| IMC Networks Lenovo EasyCamera                | 2         | 0.82%   |
| Chicony USB2.0 Camera                         | 2         | 0.82%   |
| Chicony ThinkPad T490 Webcam                  | 2         | 0.82%   |
| Chicony Lenovo EasyCamera                     | 2         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 0.82%   |
| Chicony HP HD Webcam                          | 2         | 0.82%   |
| Apple FaceTime HD Camera                      | 2         | 0.82%   |
| Acer ThinkPad Integrated Camera               | 2         | 0.82%   |
| Acer Lenovo Integrated Webcam                 | 2         | 0.82%   |
| Acer EasyCamera                               | 2         | 0.82%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 0.41%   |
| Z-Star Sirius USB2.0 Camera                   | 1         | 0.41%   |
| Xiongmai web camera                           | 1         | 0.41%   |
| Syntek USB 2.0 UVC PC Camera                  | 1         | 0.41%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.41%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.41%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.41%   |
| Suyin HP TrueVision Full HD                   | 1         | 0.41%   |
| Suyin HD WebCam                               | 1         | 0.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 0.41%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 0.41%   |
| Sunplus Laptop Integrated Webcam FHD          | 1         | 0.41%   |
| Sunplus HP Universal Camera                   | 1         | 0.41%   |
| Sunplus HD USB Camaer 4K                      | 1         | 0.41%   |
| Sunplus 1.3M HD WebCam                        | 1         | 0.41%   |
| SiGma Micro WebCam SiGma Micro                | 1         | 0.41%   |
| Realtek USB2.0-Camera                         | 1         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 20        | 37.04%  |
| Validity Sensors           | 12        | 22.22%  |
| Shenzhen Goodix Technology | 9         | 16.67%  |
| Upek                       | 5         | 9.26%   |
| AuthenTec                  | 4         | 7.41%   |
| Elan Microelectronics      | 3         | 5.56%   |
| LighTuning Technology      | 1         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 9.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 9.26%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 9.26%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 7.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.85%   |
| Synaptics  WBDI                                                            | 1         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.85%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.85%   |
| Unknown                                                                    | 1         | 1.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 11        | 36.67%  |
| Broadcom              | 8         | 26.67%  |
| Lenovo                | 5         | 16.67%  |
| Upek                  | 3         | 10%     |
| Yubico.com            | 1         | 3.33%   |
| O2 Micro              | 1         | 3.33%   |
| Gemalto (was Gemplus) | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 36.67%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 10%     |
| Broadcom 58200                                                               | 3         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 6.67%   |
| Broadcom 5880                                                                | 2         | 6.67%   |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 318       | 73.27%  |
| 1     | 82        | 18.89%  |
| 2     | 29        | 6.68%   |
| 5     | 2         | 0.46%   |
| 3     | 2         | 0.46%   |
| 4     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 54        | 36.49%  |
| Chipcard                 | 24        | 16.22%  |
| Graphics card            | 23        | 15.54%  |
| Multimedia controller    | 16        | 10.81%  |
| Communication controller | 8         | 5.41%   |
| Net/wireless             | 7         | 4.73%   |
| Unassigned class         | 5         | 3.38%   |
| Storage                  | 3         | 2.03%   |
| Network                  | 3         | 2.03%   |
| Sound                    | 1         | 0.68%   |
| Modem                    | 1         | 0.68%   |
| Firewire controller      | 1         | 0.68%   |
| Card reader              | 1         | 0.68%   |
| Bluetooth                | 1         | 0.68%   |

