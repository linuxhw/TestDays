Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 8010

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| eMachines     | EL1352                      | Desktop     | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| Samsung       | 960QFG                      | Convertible | [400b83d634](https://linux-hardware.org/?probe=400b83d634) | Aug 24, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| HP            | 8299                        | Desktop     | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| HP            | Notebook                    | Notebook    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| Dell          | Latitude E5470              | Notebook    | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | Desktop     | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Intel         | X79M-S                      | Desktop     | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| Google        | Coral                       | Notebook    | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | Notebook    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [de9a1cb848](https://linux-hardware.org/?probe=de9a1cb848) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3da24e6a41](https://linux-hardware.org/?probe=3da24e6a41) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| HP            | 09CCh                       | Desktop     | [947fb1edcb](https://linux-hardware.org/?probe=947fb1edcb) | Aug 15, 2023 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [a1dccbbd3f](https://linux-hardware.org/?probe=a1dccbbd3f) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | Notebook    | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | Notebook    | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [17179d26d5](https://linux-hardware.org/?probe=17179d26d5) | Aug 12, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| MSI           | 2AE0                        | Desktop     | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | 09CCh                       | Desktop     | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [6cbd6d691c](https://linux-hardware.org/?probe=6cbd6d691c) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [a2756bd55e](https://linux-hardware.org/?probe=a2756bd55e) | Aug 10, 2023 |
| Intel         | DZ68BC AAG30742-401         | Desktop     | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| HP            | Presario CQ56               | Notebook    | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| HP            | 89B5 A                      | Desktop     | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| Dell          | 0HJ054                      | Desktop     | [85ceb83c22](https://linux-hardware.org/?probe=85ceb83c22) | Jul 31, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| HP            | 530                         | Notebook    | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion dv4                | Notebook    | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [7583695051](https://linux-hardware.org/?probe=7583695051) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [fe7c4fd681](https://linux-hardware.org/?probe=fe7c4fd681) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | Notebook    | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [431abc64d1](https://linux-hardware.org/?probe=431abc64d1) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | Notebook    | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Acer          | AO756                       | Notebook    | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| Medion        | E15301                      | Notebook    | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| HP            | 3047h                       | Desktop     | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | Notebook    | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | Desktop     | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | Notebook    | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | Notebook    | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | 04075X A00                  | All in one  | [46795bfa31](https://linux-hardware.org/?probe=46795bfa31) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [21bef8253a](https://linux-hardware.org/?probe=21bef8253a) | Jul 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4155214585](https://linux-hardware.org/?probe=4155214585) | Jul 14, 2023 |
| Alienware     | M11xR3                      | Notebook    | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [8fdb4e6f42](https://linux-hardware.org/?probe=8fdb4e6f42) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [537e7c9c94](https://linux-hardware.org/?probe=537e7c9c94) | Jul 13, 2023 |
| HP            | 15                          | Notebook    | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [11ab455725](https://linux-hardware.org/?probe=11ab455725) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| HP            | 8299                        | Desktop     | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| HP            | Compaq 2510p                | Notebook    | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| HP            | Compaq 2510p                | Notebook    | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | Notebook    | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| OTVOC         | N1                          | Notebook    | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | 0GFYJR A00                  | Server      | [573c8bd5bd](https://linux-hardware.org/?probe=573c8bd5bd) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Dell          | Precision M4700             | Notebook    | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| Intel         | H55                         | Desktop     | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| HP            | 2B3E                        | All in one  | [bfa310e490](https://linux-hardware.org/?probe=bfa310e490) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| HP            | 2B3E                        | All in one  | [c6f01baa52](https://linux-hardware.org/?probe=c6f01baa52) | Jul 03, 2023 |
| OTVOC         | N1                          | Notebook    | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| HP            | ENVY m6                     | Notebook    | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Unknown       | V00                         | Mini pc     | [ab56e54ced](https://linux-hardware.org/?probe=ab56e54ced) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [36483eddb0](https://linux-hardware.org/?probe=36483eddb0) | Jul 01, 2023 |
| HP            | Compaq 6830s                | Notebook    | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Win Elemen... | M9                          | Desktop     | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [e47898dc3d](https://linux-hardware.org/?probe=e47898dc3d) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | Notebook    | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [85eeeb037b](https://linux-hardware.org/?probe=85eeeb037b) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | Notebook    | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [707e7d9862](https://linux-hardware.org/?probe=707e7d9862) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | Notebook    | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [c503081708](https://linux-hardware.org/?probe=c503081708) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f46f1000c0](https://linux-hardware.org/?probe=f46f1000c0) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [535d3d42b7](https://linux-hardware.org/?probe=535d3d42b7) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | Notebook    | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | Desktop     | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | Desktop     | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [449b742c95](https://linux-hardware.org/?probe=449b742c95) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [48a2156205](https://linux-hardware.org/?probe=48a2156205) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | Desktop     | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| HP            | 81BA                        | All in one  | [d41186191f](https://linux-hardware.org/?probe=d41186191f) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| ASUSTek       | G50VT                       | Notebook    | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| HP            | 18E5                        | Desktop     | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | Desktop     | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| Google        | Lars                        | Notebook    | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | Desktop     | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | Notebook    | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASRock        | H77M                        | Desktop     | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | 18E5                        | Desktop     | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b9de7bf2f3](https://linux-hardware.org/?probe=b9de7bf2f3) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| HP            | 2B02                        | Desktop     | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | Desktop     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Intel         | Tiger Hill                  | Desktop     | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | Desktop     | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | Notebook    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| Dell          | Latitude 3340               | Notebook    | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Dell          | Precision M2800             | Notebook    | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| eMachines     | E620                        | Notebook    | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40b6afc886](https://linux-hardware.org/?probe=40b6afc886) | May 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ba75f23f44](https://linux-hardware.org/?probe=ba75f23f44) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASUSTek       | GL702VI                     | Notebook    | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| HP            | 655                         | Notebook    | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | Notebook    | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | Desktop     | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| Unknown       | X133                        | Notebook    | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | Desktop     | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Unknown       | E450                        | Notebook    | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| ASRock        | G41M-GS                     | Desktop     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Intel         | H55                         | Desktop     | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [83abb6a8e0](https://linux-hardware.org/?probe=83abb6a8e0) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K53U                        | Notebook    | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [99d3eca719](https://linux-hardware.org/?probe=99d3eca719) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6987a21849](https://linux-hardware.org/?probe=6987a21849) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [8b89ffd983](https://linux-hardware.org/?probe=8b89ffd983) | Apr 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | Notebook    | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | Notebook    | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [896574c24a](https://linux-hardware.org/?probe=896574c24a) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [f0ea43f3fd](https://linux-hardware.org/?probe=f0ea43f3fd) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | Notebook    | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | Desktop     | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | Notebook    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [0a5da1a9a0](https://linux-hardware.org/?probe=0a5da1a9a0) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [13c23678aa](https://linux-hardware.org/?probe=13c23678aa) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | Desktop     | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | Desktop     | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | Desktop     | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | Notebook    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | Notebook    | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | Notebook    | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | Desktop     | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [b813f95c6f](https://linux-hardware.org/?probe=b813f95c6f) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [59572d294b](https://linux-hardware.org/?probe=59572d294b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 3404      | 64.96%  |
| Zorin 15 | 1640      | 31.3%   |
| Zorin 12 | 196       | 3.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 5224      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 229       | 3.81%   |
| 5.11.0-38-generic | 180       | 3%      |
| 5.11.0-27-generic | 156       | 2.6%    |
| 5.15.0-46-generic | 152       | 2.53%   |
| 5.15.0-58-generic | 151       | 2.51%   |
| 5.15.0-52-generic | 151       | 2.51%   |
| 5.15.0-67-generic | 142       | 2.36%   |
| 5.15.0-69-generic | 136       | 2.26%   |
| 5.13.0-30-generic | 126       | 2.1%    |
| 5.11.0-40-generic | 124       | 2.06%   |
| 5.13.0-39-generic | 121       | 2.01%   |
| 5.3.0-40-generic  | 110       | 1.83%   |
| 5.15.0-60-generic | 109       | 1.81%   |
| 5.11.0-41-generic | 108       | 1.8%    |
| 5.11.0-37-generic | 107       | 1.78%   |
| 5.15.0-76-generic | 103       | 1.71%   |
| 5.15.0-78-generic | 102       | 1.7%    |
| 5.15.0-71-generic | 101       | 1.68%   |
| 5.11.0-43-generic | 101       | 1.68%   |
| 5.4.0-42-generic  | 99        | 1.65%   |
| 5.15.0-48-generic | 95        | 1.58%   |
| 5.11.0-34-generic | 94        | 1.56%   |
| 5.13.0-40-generic | 90        | 1.5%    |
| 5.15.0-53-generic | 81        | 1.35%   |
| 5.0.0-37-generic  | 79        | 1.32%   |
| 5.15.0-41-generic | 77        | 1.28%   |
| 5.13.0-44-generic | 76        | 1.27%   |
| 5.13.0-35-generic | 74        | 1.23%   |
| 5.3.0-46-generic  | 73        | 1.22%   |
| 5.13.0-28-generic | 73        | 1.22%   |
| 5.15.0-73-generic | 68        | 1.13%   |
| 5.3.0-51-generic  | 65        | 1.08%   |
| 5.4.0-47-generic  | 61        | 1.02%   |
| 5.13.0-52-generic | 59        | 0.98%   |
| 5.13.0-27-generic | 59        | 0.98%   |
| 5.15.0-72-generic | 58        | 0.97%   |
| 5.4.0-58-generic  | 54        | 0.9%    |
| 5.3.0-53-generic  | 54        | 0.9%    |
| 5.13.0-41-generic | 54        | 0.9%    |
| 5.15.0-79-generic | 53        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1731      | 31.78%  |
| 5.4.0   | 965       | 17.72%  |
| 5.11.0  | 951       | 17.46%  |
| 5.13.0  | 768       | 14.1%   |
| 5.3.0   | 487       | 8.94%   |
| 4.15.0  | 189       | 3.47%   |
| 5.0.0   | 153       | 2.81%   |
| 4.18.0  | 76        | 1.4%    |
| 5.8.0   | 54        | 0.99%   |
| 5.14.0  | 10        | 0.18%   |
| 4.4.0   | 6         | 0.11%   |
| 5.7.1   | 3         | 0.06%   |
| 6.3.2   | 2         | 0.04%   |
| 5.7.0   | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.12 | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.5  | 2         | 0.04%   |
| 5.17.1  | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 4.13.0  | 2         | 0.04%   |
| 6.3.1   | 1         | 0.02%   |
| 6.2.7   | 1         | 0.02%   |
| 6.2.16  | 1         | 0.02%   |
| 6.2.14  | 1         | 0.02%   |
| 6.1.8   | 1         | 0.02%   |
| 6.1.7   | 1         | 0.02%   |
| 6.0.9   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.19  | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1734      | 31.84%  |
| 5.4     | 967       | 17.76%  |
| 5.11    | 951       | 17.46%  |
| 5.13    | 769       | 14.12%  |
| 5.3     | 487       | 8.94%   |
| 4.15    | 189       | 3.47%   |
| 5.0     | 153       | 2.81%   |
| 4.18    | 76        | 1.4%    |
| 5.8     | 55        | 1.01%   |
| 5.14    | 10        | 0.18%   |
| 5.19    | 8         | 0.15%   |
| 5.7     | 6         | 0.11%   |
| 4.4     | 6         | 0.11%   |
| 5.17    | 5         | 0.09%   |
| 5.16    | 5         | 0.09%   |
| 6.0     | 4         | 0.07%   |
| 5.18    | 4         | 0.07%   |
| 5.10    | 4         | 0.07%   |
| 6.3     | 3         | 0.06%   |
| 6.2     | 3         | 0.06%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 4.13    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4831      | 92.42%  |
| i686   | 396       | 7.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3859      | 72.99%  |
| XFCE       | 1096      | 20.73%  |
| Unknown    | 300       | 5.67%   |
| X-Cinnamon | 8         | 0.15%   |
| KDE5       | 6         | 0.11%   |
| Unity      | 4         | 0.08%   |
| KDE        | 4         | 0.08%   |
| Cinnamon   | 3         | 0.06%   |
| Budgie     | 3         | 0.06%   |
| i3         | 2         | 0.04%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5001      | 94.91%  |
| Unknown | 183       | 3.47%   |
| Wayland | 83        | 1.58%   |
| Tty     | 2         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4244      | 79.88%  |
| GDM3    | 401       | 7.55%   |
| GDM     | 372       | 7%      |
| LightDM | 281       | 5.29%   |
| TDM     | 11        | 0.21%   |
| SDDM    | 3         | 0.06%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1928      | 36.63%  |
| de_DE   | 408       | 7.75%   |
| pt_BR   | 336       | 6.38%   |
| en_GB   | 324       | 6.16%   |
| Unknown | 231       | 4.39%   |
| it_IT   | 180       | 3.42%   |
| fr_FR   | 158       | 3%      |
| es_ES   | 147       | 2.79%   |
| en_CA   | 145       | 2.76%   |
| en_IN   | 138       | 2.62%   |
| pl_PL   | 119       | 2.26%   |
| en_AU   | 94        | 1.79%   |
| nl_NL   | 82        | 1.56%   |
| es_MX   | 72        | 1.37%   |
| ru_RU   | 67        | 1.27%   |
| es_AR   | 61        | 1.16%   |
| pt_PT   | 57        | 1.08%   |
| en_ZA   | 52        | 0.99%   |
| cs_CZ   | 50        | 0.95%   |
| hu_HU   | 36        | 0.68%   |
| sv_SE   | 34        | 0.65%   |
| tr_TR   | 32        | 0.61%   |
| C       | 30        | 0.57%   |
| es_CL   | 29        | 0.55%   |
| en_NZ   | 28        | 0.53%   |
| fr_CA   | 25        | 0.48%   |
| es_CO   | 23        | 0.44%   |
| nl_BE   | 22        | 0.42%   |
| de_AT   | 21        | 0.4%    |
| ja_JP   | 20        | 0.38%   |
| de_CH   | 20        | 0.38%   |
| fr_BE   | 17        | 0.32%   |
| el_GR   | 17        | 0.32%   |
| en_PH   | 15        | 0.29%   |
| da_DK   | 15        | 0.29%   |
| nb_NO   | 12        | 0.23%   |
| fi_FI   | 12        | 0.23%   |
| es_PE   | 12        | 0.23%   |
| es_VE   | 11        | 0.21%   |
| sk_SK   | 10        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2789      | 52.71%  |
| EFI  | 2502      | 47.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4878      | 92.76%  |
| Overlay  | 107       | 2.03%   |
| Tmpfs    | 86        | 1.64%   |
| Zfs      | 64        | 1.22%   |
| Btrfs    | 42        | 0.8%    |
| Ext2     | 35        | 0.67%   |
| Unknown  | 27        | 0.51%   |
| Xfs      | 9         | 0.17%   |
| Ext3     | 9         | 0.17%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4603      | 87.18%  |
| GPT     | 497       | 9.41%   |
| MBR     | 180       | 3.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4956      | 94.29%  |
| Yes       | 300       | 5.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4349      | 82.62%  |
| Yes       | 915       | 17.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 911       | 17.44%  |
| ASUSTek Computer    | 719       | 13.76%  |
| Dell                | 692       | 13.25%  |
| Lenovo              | 616       | 11.79%  |
| Gigabyte Technology | 286       | 5.47%   |
| Acer                | 284       | 5.44%   |
| MSI                 | 216       | 4.13%   |
| Apple               | 164       | 3.14%   |
| Toshiba             | 162       | 3.1%    |
| ASRock              | 143       | 2.74%   |
| Intel               | 85        | 1.63%   |
| Samsung Electronics | 66        | 1.26%   |
| Unknown             | 65        | 1.24%   |
| Sony                | 52        | 1%      |
| Fujitsu             | 44        | 0.84%   |
| Pegatron            | 36        | 0.69%   |
| Google              | 36        | 0.69%   |
| Packard Bell        | 33        | 0.63%   |
| Positivo            | 32        | 0.61%   |
| Microsoft           | 26        | 0.5%    |
| Biostar             | 26        | 0.5%    |
| Foxconn             | 25        | 0.48%   |
| Medion              | 23        | 0.44%   |
| Fujitsu Siemens     | 21        | 0.4%    |
| HUAWEI              | 20        | 0.38%   |
| ECS                 | 19        | 0.36%   |
| Alienware           | 19        | 0.36%   |
| AMI                 | 16        | 0.31%   |
| Gateway             | 13        | 0.25%   |
| eMachines           | 13        | 0.25%   |
| Notebook            | 12        | 0.23%   |
| AZW                 | 12        | 0.23%   |
| Chuwi               | 11        | 0.21%   |
| Panasonic           | 9         | 0.17%   |
| Multilaser          | 8         | 0.15%   |
| Semp Toshiba        | 7         | 0.13%   |
| NEC Computers       | 7         | 0.13%   |
| IBM                 | 7         | 0.13%   |
| GPU Company         | 7         | 0.13%   |
| Shuttle             | 6         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 98        | 1.88%   |
| ASUS All Series            | 41        | 0.78%   |
| HP Notebook                | 30        | 0.57%   |
| HP Pavilion Notebook       | 17        | 0.33%   |
| HP Pavilion dv6            | 16        | 0.31%   |
| HP 15                      | 16        | 0.31%   |
| Dell OptiPlex 7010         | 16        | 0.31%   |
| HP Pavilion dv7            | 14        | 0.27%   |
| HP Pavilion 15             | 12        | 0.23%   |
| Dell OptiPlex 780          | 11        | 0.21%   |
| Toshiba Satellite C660     | 10        | 0.19%   |
| Lenovo MIIX 320-10ICR 80XF | 10        | 0.19%   |
| Gigabyte A320M-S2H         | 10        | 0.19%   |
| Dell OptiPlex 790          | 10        | 0.19%   |
| Dell Latitude E6400        | 10        | 0.19%   |
| Dell Latitude D630         | 10        | 0.19%   |
| Dell Inspiron 1545         | 10        | 0.19%   |
| MSI MS-7817                | 9         | 0.17%   |
| HP Pavilion g6             | 9         | 0.17%   |
| Dell OptiPlex 380          | 9         | 0.17%   |
| ASUS M5A97 R2.0            | 9         | 0.17%   |
| Apple MacBookPro8,1        | 9         | 0.17%   |
| Apple iMac12,2             | 9         | 0.17%   |
| MSI MS-7C02                | 8         | 0.15%   |
| HP Pavilion g7             | 8         | 0.15%   |
| HP Laptop 15-bw0xx         | 8         | 0.15%   |
| Dell OptiPlex 755          | 8         | 0.15%   |
| Dell Latitude E6540        | 8         | 0.15%   |
| Dell Inspiron 15-3567      | 8         | 0.15%   |
| ASUS M5A78L-M/USB3         | 8         | 0.15%   |
| Apple iMac12,1             | 8         | 0.15%   |
| HP Pavilion dv6700         | 7         | 0.13%   |
| HP EliteBook 8460p         | 7         | 0.13%   |
| HP EliteBook 840 G1        | 7         | 0.13%   |
| Gigabyte GA-78LMT-USB3 6.0 | 7         | 0.13%   |
| Gigabyte B450 AORUS M      | 7         | 0.13%   |
| Gigabyte 970A-DS3P         | 7         | 0.13%   |
| Dell OptiPlex 990          | 7         | 0.13%   |
| Dell Latitude E6410        | 7         | 0.13%   |
| Dell Inspiron 3521         | 7         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 202       | 3.87%   |
| Lenovo ThinkPad       | 199       | 3.81%   |
| Dell Inspiron         | 198       | 3.79%   |
| Acer Aspire           | 184       | 3.52%   |
| Dell Latitude         | 176       | 3.37%   |
| Lenovo IdeaPad        | 150       | 2.87%   |
| Toshiba Satellite     | 137       | 2.62%   |
| Dell OptiPlex         | 128       | 2.45%   |
| HP Compaq             | 115       | 2.2%    |
| Unknown               | 98        | 1.88%   |
| HP EliteBook          | 94        | 1.8%    |
| HP ProBook            | 74        | 1.42%   |
| HP Laptop             | 62        | 1.19%   |
| Lenovo ThinkCentre    | 56        | 1.07%   |
| ASUS ROG              | 54        | 1.03%   |
| ASUS PRIME            | 50        | 0.96%   |
| Dell Vostro           | 45        | 0.86%   |
| Dell Precision        | 45        | 0.86%   |
| ASUS VivoBook         | 41        | 0.78%   |
| ASUS TUF              | 41        | 0.78%   |
| ASUS All              | 41        | 0.78%   |
| HP ENVY               | 37        | 0.71%   |
| Lenovo Yoga           | 36        | 0.69%   |
| Dell XPS              | 36        | 0.69%   |
| HP Notebook           | 30        | 0.57%   |
| Packard Bell EasyNote | 27        | 0.52%   |
| Microsoft Surface     | 26        | 0.5%    |
| HP Stream             | 23        | 0.44%   |
| HP EliteDesk          | 20        | 0.38%   |
| Fujitsu ESPRIMO       | 19        | 0.36%   |
| HP 15                 | 18        | 0.34%   |
| ASUS ZenBook          | 18        | 0.34%   |
| Apple iMac12          | 17        | 0.33%   |
| HP Presario           | 16        | 0.31%   |
| Dell Studio           | 16        | 0.31%   |
| Lenovo MIIX           | 15        | 0.29%   |
| HP ProDesk            | 15        | 0.29%   |
| Gigabyte B450         | 15        | 0.29%   |
| ASUS M5A97            | 15        | 0.29%   |
| HP 255                | 14        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 454       | 8.69%   |
| 2012    | 432       | 8.27%   |
| 2013    | 408       | 7.81%   |
| 2018    | 374       | 7.16%   |
| 2010    | 363       | 6.95%   |
| 2014    | 339       | 6.49%   |
| 2008    | 319       | 6.11%   |
| 2017    | 310       | 5.93%   |
| 2019    | 308       | 5.9%    |
| 2021    | 293       | 5.61%   |
| 2020    | 290       | 5.55%   |
| 2009    | 275       | 5.26%   |
| 2016    | 254       | 4.86%   |
| 2015    | 252       | 4.82%   |
| 2007    | 234       | 4.48%   |
| 2006    | 104       | 1.99%   |
| 2022    | 92        | 1.76%   |
| 2005    | 66        | 1.26%   |
| 2023    | 26        | 0.5%    |
| 2004    | 11        | 0.21%   |
| Unknown | 11        | 0.21%   |
| 2003    | 8         | 0.15%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2981      | 57.06%  |
| Desktop     | 1862      | 35.64%  |
| Convertible | 114       | 2.18%   |
| All in one  | 111       | 2.12%   |
| Tablet      | 74        | 1.42%   |
| Mini pc     | 69        | 1.32%   |
| Server      | 13        | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4727      | 89.9%   |
| Enabled  | 531       | 10.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5183      | 99.22%  |
| Yes  | 41        | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1316      | 24.91%  |
| 4.01-8.0        | 1265      | 23.94%  |
| 8.01-16.0       | 807       | 15.27%  |
| 16.01-24.0      | 735       | 13.91%  |
| 1.01-2.0        | 471       | 8.91%   |
| 32.01-64.0      | 307       | 5.81%   |
| 2.01-3.0        | 161       | 3.05%   |
| 0.51-1.0        | 96        | 1.82%   |
| 64.01-256.0     | 74        | 1.4%    |
| 24.01-32.0      | 51        | 0.97%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2342      | 41.27%  |
| 2.01-3.0   | 1592      | 28.05%  |
| 3.01-4.0   | 661       | 11.65%  |
| 4.01-8.0   | 527       | 9.29%   |
| 0.51-1.0   | 416       | 7.33%   |
| 8.01-16.0  | 79        | 1.39%   |
| 0.01-0.5   | 41        | 0.72%   |
| 16.01-24.0 | 11        | 0.19%   |
| 24.01-32.0 | 4         | 0.07%   |
| 32.01-64.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3527      | 66.07%  |
| 2       | 1235      | 23.14%  |
| 3       | 301       | 5.64%   |
| 4       | 129       | 2.42%   |
| 5       | 61        | 1.14%   |
| 6       | 34        | 0.64%   |
| 0       | 24        | 0.45%   |
| 7       | 13        | 0.24%   |
| 8       | 9         | 0.17%   |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2705      | 51.49%  |
| Yes       | 2548      | 48.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4512      | 86.22%  |
| No        | 721       | 13.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4160      | 79.25%  |
| No        | 1089      | 20.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2792      | 52.9%   |
| No        | 2486      | 47.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1202      | 22.92%  |
| Germany      | 469       | 8.94%   |
| Brazil       | 381       | 7.27%   |
| UK           | 319       | 6.08%   |
| Italy        | 200       | 3.81%   |
| Canada       | 195       | 3.72%   |
| Spain        | 159       | 3.03%   |
| France       | 158       | 3.01%   |
| India        | 148       | 2.82%   |
| Netherlands  | 146       | 2.78%   |
| Poland       | 120       | 2.29%   |
| Australia    | 104       | 1.98%   |
| Mexico       | 100       | 1.91%   |
| Argentina    | 76        | 1.45%   |
| Portugal     | 68        | 1.3%    |
| Russia       | 62        | 1.18%   |
| Sweden       | 61        | 1.16%   |
| South Africa | 60        | 1.14%   |
| Czechia      | 59        | 1.13%   |
| Belgium      | 59        | 1.13%   |
| Romania      | 49        | 0.93%   |
| Switzerland  | 47        | 0.9%    |
| Greece       | 45        | 0.86%   |
| Indonesia    | 44        | 0.84%   |
| Turkey       | 43        | 0.82%   |
| Austria      | 43        | 0.82%   |
| Hungary      | 41        | 0.78%   |
| Norway       | 37        | 0.71%   |
| Colombia     | 37        | 0.71%   |
| New Zealand  | 35        | 0.67%   |
| Chile        | 35        | 0.67%   |
| Japan        | 33        | 0.63%   |
| Denmark      | 33        | 0.63%   |
| Serbia       | 27        | 0.51%   |
| Egypt        | 27        | 0.51%   |
| Bulgaria     | 24        | 0.46%   |
| Philippines  | 22        | 0.42%   |
| Finland      | 21        | 0.4%    |
| Ukraine      | 19        | 0.36%   |
| Slovakia     | 19        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 43        | 0.78%   |
| Sao Paulo      | 40        | 0.73%   |
| Munich         | 32        | 0.58%   |
| Athens         | 32        | 0.58%   |
| Sydney         | 29        | 0.53%   |
| Rome           | 27        | 0.49%   |
| Vienna         | 26        | 0.47%   |
| Rio de Janeiro | 26        | 0.47%   |
| Milan          | 26        | 0.47%   |
| Madrid         | 26        | 0.47%   |
| Montreal       | 22        | 0.4%    |
| Johannesburg   | 21        | 0.38%   |
| Perth          | 19        | 0.35%   |
| New York       | 19        | 0.35%   |
| Denver         | 19        | 0.35%   |
| Dallas         | 19        | 0.35%   |
| Toronto        | 18        | 0.33%   |
| Paris          | 18        | 0.33%   |
| London         | 18        | 0.33%   |
| Bogotá        | 18        | 0.33%   |
| Auckland       | 18        | 0.33%   |
| Istanbul       | 17        | 0.31%   |
| Hamburg        | 17        | 0.31%   |
| Buenos Aires   | 17        | 0.31%   |
| Bengaluru      | 17        | 0.31%   |
| Belgrade       | 17        | 0.31%   |
| Warsaw         | 16        | 0.29%   |
| Mexico City    | 16        | 0.29%   |
| Cape Town      | 16        | 0.29%   |
| Cairo          | 16        | 0.29%   |
| Bucharest      | 16        | 0.29%   |
| Stockholm      | 15        | 0.27%   |
| Prague         | 15        | 0.27%   |
| Moscow         | 15        | 0.27%   |
| Jakarta        | 15        | 0.27%   |
| Houston        | 15        | 0.27%   |
| Melbourne      | 14        | 0.26%   |
| Copenhagen     | 14        | 0.26%   |
| Zurich         | 13        | 0.24%   |
| Seattle        | 13        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1149      | 1591   | 16.19%  |
| WDC                       | 1034      | 1382   | 14.57%  |
| Samsung Electronics       | 867       | 1239   | 12.22%  |
| Toshiba                   | 538       | 672    | 7.58%   |
| Unknown                   | 417       | 584    | 5.88%   |
| SanDisk                   | 379       | 467    | 5.34%   |
| Kingston                  | 360       | 480    | 5.07%   |
| Hitachi                   | 320       | 395    | 4.51%   |
| Crucial                   | 227       | 275    | 3.2%    |
| Intel                     | 134       | 173    | 1.89%   |
| HGST                      | 129       | 158    | 1.82%   |
| SK hynix                  | 110       | 131    | 1.55%   |
| A-DATA Technology         | 88        | 105    | 1.24%   |
| China                     | 87        | 102    | 1.23%   |
| Micron Technology         | 78        | 91     | 1.1%    |
| Apple                     | 72        | 81     | 1.01%   |
| Intenso                   | 52        | 57     | 0.73%   |
| Phison                    | 49        | 62     | 0.69%   |
| PNY                       | 47        | 59     | 0.66%   |
| Maxtor                    | 47        | 65     | 0.66%   |
| Fujitsu                   | 45        | 47     | 0.63%   |
| Silicon Motion            | 39        | 50     | 0.55%   |
| SPCC                      | 37        | 48     | 0.52%   |
| Patriot                   | 35        | 52     | 0.49%   |
| KIOXIA                    | 34        | 39     | 0.48%   |
| OCZ                       | 29        | 33     | 0.41%   |
| Micron/Crucial Technology | 28        | 33     | 0.39%   |
| JMicron Technology        | 27        | 35     | 0.38%   |
| Netac                     | 26        | 29     | 0.37%   |
| GOODRAM                   | 26        | 30     | 0.37%   |
| Unknown                   | 25        | 29     | 0.35%   |
| Transcend                 | 24        | 45     | 0.34%   |
| LITEON                    | 23        | 28     | 0.32%   |
| Team                      | 19        | 22     | 0.27%   |
| LITEONIT                  | 18        | 21     | 0.25%   |
| Hewlett-Packard           | 18        | 22     | 0.25%   |
| SABRENT                   | 17        | 18     | 0.24%   |
| Phison Electronics        | 17        | 20     | 0.24%   |
| Lexar                     | 16        | 16     | 0.23%   |
| Realtek Semiconductor     | 13        | 14     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 139       | 1.81%   |
| Unknown MMC Card  64GB                              | 117       | 1.52%   |
| Kingston SA400S37240G 240GB SSD                     | 91        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB                     | 62        | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                      | 58        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 52        | 0.68%   |
| Toshiba MQ01ABF050 500GB                            | 51        | 0.66%   |
| Crucial CT240BX500SSD1 240GB                        | 49        | 0.64%   |
| Unknown MMC Card  128GB                             | 48        | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 48        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 47        | 0.61%   |
| Samsung SSD 860 EVO 500GB                           | 46        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                     | 45        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 43        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 42        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 39        | 0.51%   |
| Toshiba MQ04ABF100 1TB                              | 37        | 0.48%   |
| Seagate ST9500325AS 500GB                           | 36        | 0.47%   |
| Samsung SSD 850 EVO 250GB                           | 35        | 0.45%   |
| Unknown SD/MMC/MS PRO 1GB                           | 34        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 34        | 0.44%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 34        | 0.44%   |
| Samsung NVMe SSD Drive 512GB                        | 33        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 33        | 0.43%   |
| Seagate ST3500418AS 500GB                           | 32        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 31        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 30        | 0.39%   |
| Toshiba DT01ACA100 1TB                              | 29        | 0.38%   |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.38%   |
| Unknown MMC Card  16GB                              | 28        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                      | 28        | 0.36%   |
| Seagate Expansion 2TB                               | 27        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 25        | 0.32%   |
| Samsung SSD 860 EVO 250GB                           | 25        | 0.32%   |
| Unknown                                             | 25        | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 23        | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB                      | 23        | 0.3%    |
| HGST HTS721010A9E630 1TB                            | 23        | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 22        | 0.29%   |
| Toshiba HDWD110 1TB                                 | 22        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1134      | 1557   | 34.13%  |
| WDC                 | 921       | 1214   | 27.72%  |
| Toshiba             | 450       | 568    | 13.54%  |
| Hitachi             | 320       | 395    | 9.63%   |
| Samsung Electronics | 164       | 209    | 4.94%   |
| HGST                | 129       | 158    | 3.88%   |
| Maxtor              | 45        | 63     | 1.35%   |
| Fujitsu             | 45        | 47     | 1.35%   |
| Unknown             | 35        | 47     | 1.05%   |
| Apple               | 35        | 38     | 1.05%   |
| SABRENT             | 16        | 17     | 0.48%   |
| USB3.0              | 4         | 5      | 0.12%   |
| IBM/Hitachi         | 4         | 5      | 0.12%   |
| Hewlett-Packard     | 4         | 7      | 0.12%   |
| Intenso             | 3         | 3      | 0.09%   |
| SSK                 | 2         | 2      | 0.06%   |
| QUANTUM             | 2         | 2      | 0.06%   |
| JMicron Technology  | 2         | 2      | 0.06%   |
| External            | 2         | 2      | 0.06%   |
| Pioneer             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 2      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 440       | 619    | 19.25%  |
| Kingston            | 312       | 407    | 13.65%  |
| SanDisk             | 223       | 273    | 9.76%   |
| Crucial             | 220       | 266    | 9.62%   |
| WDC                 | 103       | 131    | 4.51%   |
| China               | 85        | 100    | 3.72%   |
| A-DATA Technology   | 81        | 98     | 3.54%   |
| Intel               | 64        | 75     | 2.8%    |
| Toshiba             | 48        | 56     | 2.1%    |
| PNY                 | 47        | 59     | 2.06%   |
| Micron Technology   | 40        | 46     | 1.75%   |
| SK hynix            | 39        | 43     | 1.71%   |
| Intenso             | 36        | 40     | 1.57%   |
| SPCC                | 35        | 46     | 1.53%   |
| Patriot             | 34        | 51     | 1.49%   |
| Apple               | 30        | 34     | 1.31%   |
| OCZ                 | 27        | 31     | 1.18%   |
| Netac               | 26        | 28     | 1.14%   |
| Transcend           | 24        | 45     | 1.05%   |
| GOODRAM             | 24        | 28     | 1.05%   |
| LITEON              | 23        | 28     | 1.01%   |
| Team                | 19        | 22     | 0.83%   |
| LITEONIT            | 18        | 21     | 0.79%   |
| JMicron Technology  | 17        | 22     | 0.74%   |
| Lexar               | 15        | 15     | 0.66%   |
| KingSpec            | 12        | 14     | 0.52%   |
| Hewlett-Packard     | 12        | 13     | 0.52%   |
| Gigabyte Technology | 11        | 18     | 0.48%   |
| Apacer              | 11        | 13     | 0.48%   |
| Unknown             | 11        | 14     | 0.48%   |
| Leven               | 9         | 10     | 0.39%   |
| Corsair             | 9         | 15     | 0.39%   |
| Plextor             | 8         | 9      | 0.35%   |
| ASMT                | 7         | 7      | 0.31%   |
| Verbatim            | 6         | 6      | 0.26%   |
| OWC                 | 6         | 7      | 0.26%   |
| Mushkin             | 6         | 6      | 0.26%   |
| FORESEE             | 5         | 6      | 0.22%   |
| TCSUNBOW            | 4         | 4      | 0.17%   |
| Super Talent        | 4         | 5      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2908      | 4348   | 44.94%  |
| SSD     | 2056      | 2904   | 31.77%  |
| NVMe    | 975       | 1313   | 15.07%  |
| MMC     | 391       | 536    | 6.04%   |
| Unknown | 141       | 177    | 2.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4322      | 7055   | 72.66%  |
| NVMe | 974       | 1311   | 16.38%  |
| MMC  | 391       | 536    | 6.57%   |
| SAS  | 261       | 376    | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3350      | 4736   | 65.8%   |
| 0.51-1.0   | 1278      | 1769   | 25.1%   |
| 1.01-2.0   | 306       | 441    | 6.01%   |
| 3.01-4.0   | 68        | 150    | 1.34%   |
| 4.01-10.0  | 45        | 66     | 0.88%   |
| 2.01-3.0   | 39        | 70     | 0.77%   |
| 10.01-20.0 | 5         | 20     | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1791      | 33.06%  |
| 251-500        | 1304      | 24.07%  |
| 501-1000       | 727       | 13.42%  |
| 51-100         | 539       | 9.95%   |
| 21-50          | 310       | 5.72%   |
| 1001-2000      | 286       | 5.28%   |
| 1-20           | 163       | 3.01%   |
| More than 3000 | 155       | 2.86%   |
| 2001-3000      | 93        | 1.72%   |
| Unknown        | 49        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2591      | 46%     |
| 21-50          | 1319      | 23.42%  |
| 51-100         | 602       | 10.69%  |
| 101-250        | 493       | 8.75%   |
| 251-500        | 263       | 4.67%   |
| 501-1000       | 148       | 2.63%   |
| 1001-2000      | 77        | 1.37%   |
| More than 3000 | 67        | 1.19%   |
| Unknown        | 49        | 0.87%   |
| 2001-3000      | 23        | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 4         | 4      | 3.36%   |
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 2.52%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.52%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.52%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.68%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.68%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.68%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.68%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.68%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.68%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.68%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.84%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.84%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.84%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.84%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1         | 1      | 0.84%   |
| WDC WD3200BPVT-55ZEST0 320GB             | 1         | 1      | 0.84%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.84%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.84%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 0.84%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.84%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.84%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.84%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.84%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.84%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.84%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 0.84%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.84%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.84%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.84%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.84%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.84%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.84%   |
| Toshiba MK5061GSY 500GB                  | 1         | 1      | 0.84%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.84%   |
| Toshiba MK2046GSX 200GB                  | 1         | 1      | 0.84%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.84%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.84%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 0.84%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 42     | 34.75%  |
| WDC                 | 16        | 17     | 13.56%  |
| Toshiba             | 16        | 16     | 13.56%  |
| HGST                | 10        | 11     | 8.47%   |
| Kingston            | 6         | 6      | 5.08%   |
| Samsung Electronics | 5         | 5      | 4.24%   |
| Hitachi             | 5         | 5      | 4.24%   |
| SK hynix            | 2         | 2      | 1.69%   |
| Intel               | 2         | 2      | 1.69%   |
| A-DATA Technology   | 2         | 2      | 1.69%   |
| Teclast             | 1         | 1      | 0.85%   |
| Silicon Motion      | 1         | 1      | 0.85%   |
| POLION              | 1         | 1      | 0.85%   |
| OCZ                 | 1         | 1      | 0.85%   |
| Netac               | 1         | 1      | 0.85%   |
| Micron Technology   | 1         | 1      | 0.85%   |
| Maxtor              | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| LITEON              | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| Drevo               | 1         | 1      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| Unknown             | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 42     | 46.59%  |
| WDC                 | 15        | 16     | 17.05%  |
| Toshiba             | 13        | 13     | 14.77%  |
| HGST                | 10        | 11     | 11.36%  |
| Hitachi             | 5         | 5      | 5.68%   |
| Samsung Electronics | 3         | 3      | 3.41%   |
| Maxtor              | 1         | 1      | 1.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 84        | 91     | 73.68%  |
| SSD  | 26        | 26     | 22.81%  |
| NVMe | 4         | 4      | 3.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4787      | 8464   | 89.73%  |
| Works    | 433       | 690    | 8.12%   |
| Malfunc  | 112       | 121    | 2.1%    |
| Failed   | 2         | 2      | 0.04%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3596      | 60.03%  |
| AMD                              | 956       | 15.96%  |
| Samsung Electronics              | 336       | 5.61%   |
| SanDisk                          | 166       | 2.77%   |
| Nvidia                           | 153       | 2.55%   |
| ASMedia Technology               | 70        | 1.17%   |
| Phison Electronics               | 68        | 1.14%   |
| SK hynix                         | 66        | 1.1%    |
| Kingston Technology Company      | 65        | 1.09%   |
| JMicron Technology               | 63        | 1.05%   |
| Marvell Technology Group         | 49        | 0.82%   |
| Silicon Motion                   | 44        | 0.73%   |
| Toshiba America Info Systems     | 41        | 0.68%   |
| Micron Technology                | 39        | 0.65%   |
| VIA Technologies                 | 38        | 0.63%   |
| Silicon Integrated Systems [SiS] | 37        | 0.62%   |
| KIOXIA                           | 36        | 0.6%    |
| Micron/Crucial Technology        | 35        | 0.58%   |
| ADATA Technology                 | 20        | 0.33%   |
| Silicon Image                    | 14        | 0.23%   |
| Realtek Semiconductor            | 14        | 0.23%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.17%   |
| Union Memory (Shenzhen)          | 8         | 0.13%   |
| Seagate Technology               | 8         | 0.13%   |
| Broadcom / LSI                   | 7         | 0.12%   |
| Solid State Storage Technology   | 6         | 0.1%    |
| LSI Logic / Symbios Logic        | 6         | 0.1%    |
| Lite-On Technology               | 6         | 0.1%    |
| Apple                            | 6         | 0.1%    |
| INNOGRIT                         | 4         | 0.07%   |
| OCZ Technology Group             | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Netac Technology                 | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| TenaFe                           | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 597       | 8.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 256       | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 237       | 3.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 231       | 3.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 205       | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 186       | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 180       | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 163       | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 159       | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 143       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 134       | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 134       | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 133       | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 127       | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 124       | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 106       | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 103       | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 96        | 1.34%   |
| AMD 400 Series Chipset SATA Controller                                                  | 95        | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 88        | 1.23%   |
| Intel SATA Controller [RAID mode]                                                       | 87        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 83        | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 75        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 75        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 71        | 0.99%   |
| Samsung NVMe SSD Controller 980                                                         | 69        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 67        | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 66        | 0.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 63        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 55        | 0.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 55        | 0.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 51        | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 50        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 47        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 46        | 0.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 45        | 0.63%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44        | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 42        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3719      | 59.35%  |
| IDE  | 1143      | 18.24%  |
| NVMe | 976       | 15.58%  |
| RAID | 412       | 6.58%   |
| SAS  | 10        | 0.16%   |
| SCSI | 6         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4082      | 78.14%  |
| AMD          | 1141      | 21.84%  |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 74        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 38        | 0.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 0.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 37        | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 31        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 30        | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 29        | 0.55%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 29        | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 27        | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 27        | 0.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 26        | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 23        | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.42%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 22        | 0.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 20        | 0.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.38%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.38%   |
| Intel Pentium 4 CPU 3.00GHz                   | 19        | 0.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 19        | 0.36%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.36%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.36%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.36%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.36%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.36%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1066      | 20.37%  |
| Intel Core i7           | 668       | 12.77%  |
| Intel Core i3           | 472       | 9.02%   |
| Intel Core 2 Duo        | 354       | 6.77%   |
| Intel Celeron           | 352       | 6.73%   |
| Intel Atom              | 225       | 4.3%    |
| AMD Ryzen 5             | 204       | 3.9%    |
| Other                   | 190       | 3.63%   |
| Intel Pentium           | 156       | 2.98%   |
| AMD Ryzen 7             | 134       | 2.56%   |
| Intel Xeon              | 100       | 1.91%   |
| Intel Pentium Dual-Core | 96        | 1.83%   |
| AMD FX                  | 77        | 1.47%   |
| Intel Pentium Dual      | 75        | 1.43%   |
| AMD A6                  | 71        | 1.36%   |
| Intel Core 2 Quad       | 64        | 1.22%   |
| AMD A4                  | 59        | 1.13%   |
| AMD Ryzen 3             | 54        | 1.03%   |
| AMD Ryzen 9             | 51        | 0.97%   |
| Intel Core 2            | 47        | 0.9%    |
| AMD A8                  | 47        | 0.9%    |
| Intel Genuine           | 46        | 0.88%   |
| Intel Pentium 4         | 43        | 0.82%   |
| AMD Athlon 64 X2        | 42        | 0.8%    |
| AMD A10                 | 42        | 0.8%    |
| AMD Athlon II X2        | 40        | 0.76%   |
| Intel Pentium M         | 26        | 0.5%    |
| AMD E1                  | 26        | 0.5%    |
| Intel Celeron M         | 25        | 0.48%   |
| AMD E                   | 25        | 0.48%   |
| AMD Phenom II X4        | 23        | 0.44%   |
| AMD Athlon              | 22        | 0.42%   |
| AMD Sempron             | 21        | 0.4%    |
| AMD Turion 64 X2 Mobile | 17        | 0.32%   |
| Intel Pentium Silver    | 16        | 0.31%   |
| Intel Core i9           | 16        | 0.31%   |
| Intel Core M            | 13        | 0.25%   |
| Intel Pentium Gold      | 12        | 0.23%   |
| AMD Phenom II X6        | 12        | 0.23%   |
| AMD Athlon II X4        | 12        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2656      | 50.75%  |
| 4      | 1651      | 31.54%  |
| 6      | 302       | 5.77%   |
| 1      | 291       | 5.56%   |
| 8      | 211       | 4.03%   |
| 3      | 37        | 0.71%   |
| 12     | 36        | 0.69%   |
| 16     | 19        | 0.36%   |
| 10     | 19        | 0.36%   |
| 14     | 7         | 0.13%   |
| 20     | 2         | 0.04%   |
| 40     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 24     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 5203      | 99.6%   |
| 2      | 21        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2827      | 54.11%  |
| 1      | 2398      | 45.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5073      | 97.09%  |
| 32-bit         | 149       | 2.85%   |
| Unknown        | 3         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 465       | 8.75%   |
| 0x206a7    | 426       | 8.02%   |
| 0x306a9    | 342       | 6.44%   |
| 0x1067a    | 317       | 5.97%   |
| 0x306c3    | 278       | 5.23%   |
| 0x40651    | 146       | 2.75%   |
| 0x6fd      | 145       | 2.73%   |
| 0x20655    | 133       | 2.5%    |
| 0x406e3    | 116       | 2.18%   |
| 0x806e9    | 111       | 2.09%   |
| 0x406c4    | 107       | 2.01%   |
| 0x306d4    | 107       | 2.01%   |
| 0x30678    | 99        | 1.86%   |
| 0x806c1    | 94        | 1.77%   |
| 0x506e3    | 93        | 1.75%   |
| 0x806ea    | 86        | 1.62%   |
| 0x906ea    | 81        | 1.52%   |
| 0x906e9    | 74        | 1.39%   |
| 0x806ec    | 73        | 1.37%   |
| 0x10676    | 72        | 1.36%   |
| 0x010000c8 | 62        | 1.17%   |
| 0x6fb      | 59        | 1.11%   |
| 0x506c9    | 55        | 1.04%   |
| 0x06000852 | 55        | 1.04%   |
| 0x08701021 | 53        | 1%      |
| 0x06001119 | 53        | 1%      |
| 0x20652    | 52        | 0.98%   |
| 0x706a8    | 51        | 0.96%   |
| 0x406c3    | 50        | 0.94%   |
| 0x08108109 | 50        | 0.94%   |
| 0x706e5    | 43        | 0.81%   |
| 0x06006705 | 41        | 0.77%   |
| 0x6f6      | 39        | 0.73%   |
| 0x106ca    | 38        | 0.72%   |
| 0x0700010f | 35        | 0.66%   |
| 0x05000119 | 32        | 0.6%    |
| 0x6e8      | 31        | 0.58%   |
| 0x6d8      | 31        | 0.58%   |
| 0x03000027 | 31        | 0.58%   |
| 0x0a50000c | 30        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 519       | 9.93%   |
| Haswell          | 464       | 8.88%   |
| SandyBridge      | 453       | 8.67%   |
| Penryn           | 411       | 7.86%   |
| IvyBridge        | 368       | 7.04%   |
| Core             | 306       | 5.85%   |
| Silvermont       | 296       | 5.66%   |
| Skylake          | 221       | 4.23%   |
| Westmere         | 208       | 3.98%   |
| K10              | 134       | 2.56%   |
| Zen 2            | 127       | 2.43%   |
| Zen+             | 120       | 2.3%    |
| Piledriver       | 116       | 2.22%   |
| Broadwell        | 114       | 2.18%   |
| K8 Hammer        | 107       | 2.05%   |
| TigerLake        | 105       | 2.01%   |
| Zen 3            | 101       | 1.93%   |
| P6               | 87        | 1.66%   |
| Goldmont plus    | 81        | 1.55%   |
| Excavator        | 81        | 1.55%   |
| Bonnell          | 79        | 1.51%   |
| CometLake        | 76        | 1.45%   |
| Zen              | 73        | 1.4%    |
| Unknown          | 70        | 1.34%   |
| IceLake          | 68        | 1.3%    |
| NetBurst         | 61        | 1.17%   |
| Goldmont         | 58        | 1.11%   |
| Puma             | 52        | 0.99%   |
| Bobcat           | 50        | 0.96%   |
| Nehalem          | 48        | 0.92%   |
| Jaguar           | 42        | 0.8%    |
| K10 Llano        | 32        | 0.61%   |
| Alderlake Hybrid | 26        | 0.5%    |
| Steamroller      | 20        | 0.38%   |
| Bulldozer        | 19        | 0.36%   |
| K8 & K10 hybrid  | 17        | 0.33%   |
| Tremont          | 14        | 0.27%   |
| K6               | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3100      | 52.53%  |
| Nvidia                           | 1380      | 23.39%  |
| AMD                              | 1359      | 23.03%  |
| Silicon Integrated Systems [SiS] | 30        | 0.51%   |
| VIA Technologies                 | 19        | 0.32%   |
| Matrox Electronics Systems       | 8         | 0.14%   |
| ASPEED Technology                | 3         | 0.05%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 345       | 5.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 229       | 3.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 169       | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 149       | 2.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 139       | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 137       | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 125       | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 103       | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 102       | 1.65%   |
| Intel HD Graphics 620                                                                    | 100       | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 84        | 1.36%   |
| Intel UHD Graphics 620                                                                   | 82        | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 81        | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 81        | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 79        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 78        | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 77        | 1.25%   |
| Intel HD Graphics 5500                                                                   | 73        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 70        | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 66        | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 64        | 1.04%   |
| Intel HD Graphics 630                                                                    | 57        | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 56        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 55        | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 54        | 0.88%   |
| Intel HD Graphics 530                                                                    | 53        | 0.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 52        | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51        | 0.83%   |
| AMD Renoir                                                                               | 49        | 0.79%   |
| Intel HD Graphics 500                                                                    | 48        | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 45        | 0.73%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 39        | 0.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 38        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.58%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 36        | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 33        | 0.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 33        | 0.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 32        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2504      | 47.71%  |
| 1 x AMD                  | 1091      | 20.79%  |
| 1 x Nvidia               | 911       | 17.36%  |
| Intel + Nvidia           | 395       | 7.53%   |
| Intel + AMD              | 136       | 2.59%   |
| 2 x AMD                  | 78        | 1.49%   |
| AMD + Nvidia             | 51        | 0.97%   |
| 1 x SiS                  | 30        | 0.57%   |
| 1 x VIA                  | 19        | 0.36%   |
| 2 x Nvidia               | 10        | 0.19%   |
| Other                    | 8         | 0.15%   |
| 1 x Matrox               | 6         | 0.11%   |
| 1 x ASPEED               | 2         | 0.04%   |
| 2 x Intel                | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + Matrox          | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| AMD + Matrox             | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4273      | 81.14%  |
| Proprietary | 747       | 14.19%  |
| Unknown     | 246       | 4.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3049      | 57.27%  |
| 0.01-0.5   | 810       | 15.21%  |
| 1.01-2.0   | 523       | 9.82%   |
| 0.51-1.0   | 448       | 8.41%   |
| 3.01-4.0   | 222       | 4.17%   |
| 7.01-8.0   | 135       | 2.54%   |
| 5.01-6.0   | 61        | 1.15%   |
| 8.01-16.0  | 40        | 0.75%   |
| 2.01-3.0   | 31        | 0.58%   |
| 16.01-24.0 | 4         | 0.08%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 713       | 13.84%  |
| AU Optronics            | 611       | 11.86%  |
| LG Display              | 451       | 8.75%   |
| Chimei Innolux          | 406       | 7.88%   |
| BOE                     | 388       | 7.53%   |
| Dell                    | 245       | 4.76%   |
| Goldstar                | 230       | 4.46%   |
| Hewlett-Packard         | 185       | 3.59%   |
| Acer                    | 149       | 2.89%   |
| Apple                   | 142       | 2.76%   |
| Chi Mei Optoelectronics | 118       | 2.29%   |
| AOC                     | 110       | 2.14%   |
| Philips                 | 102       | 1.98%   |
| Ancor Communications    | 87        | 1.69%   |
| BenQ                    | 83        | 1.61%   |
| Lenovo                  | 82        | 1.59%   |
| LG Philips              | 77        | 1.49%   |
| Sharp                   | 58        | 1.13%   |
| InfoVision              | 51        | 0.99%   |
| LG Electronics          | 45        | 0.87%   |
| ViewSonic               | 41        | 0.8%    |
| Sony                    | 38        | 0.74%   |
| Unknown                 | 37        | 0.72%   |
| PANDA                   | 31        | 0.6%    |
| Vizio                   | 30        | 0.58%   |
| Toshiba                 | 29        | 0.56%   |
| HannStar                | 27        | 0.52%   |
| Iiyama                  | 25        | 0.49%   |
| Unknown                 | 25        | 0.49%   |
| ASUSTek Computer        | 23        | 0.45%   |
| CPT                     | 21        | 0.41%   |
| Fujitsu Siemens         | 19        | 0.37%   |
| Eizo                    | 19        | 0.37%   |
| Panasonic               | 16        | 0.31%   |
| Sceptre Tech            | 15        | 0.29%   |
| NEC Computers           | 15        | 0.29%   |
| MSI                     | 14        | 0.27%   |
| Quanta Display          | 11        | 0.21%   |
| Gateway                 | 11        | 0.21%   |
| LGD                     | 10        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 34        | 0.64%   |
| Unknown                                                                  | 25        | 0.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 24        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 21        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 19        | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.34%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 17        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 16        | 0.3%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 12        | 0.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 11        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.21%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 10        | 0.19%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 10        | 0.19%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 10        | 0.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 9         | 0.17%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.17%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 9         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 9         | 0.17%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1702      | 33.71%  |
| 1366x768 (WXGA)    | 1359      | 26.92%  |
| 1600x900 (HD+)     | 282       | 5.59%   |
| 1280x800 (WXGA)    | 239       | 4.73%   |
| 3840x2160 (4K)     | 217       | 4.3%    |
| 1440x900 (WXGA+)   | 163       | 3.23%   |
| 1280x1024 (SXGA)   | 159       | 3.15%   |
| 1680x1050 (WSXGA+) | 150       | 2.97%   |
| 2560x1440 (QHD)    | 116       | 2.3%    |
| 1920x1200 (WUXGA)  | 82        | 1.62%   |
| Unknown            | 81        | 1.6%    |
| 1360x768           | 66        | 1.31%   |
| 1024x600           | 47        | 0.93%   |
| 3440x1440          | 39        | 0.77%   |
| 3840x1080          | 34        | 0.67%   |
| 2560x1080          | 32        | 0.63%   |
| 2560x1600          | 29        | 0.57%   |
| 1024x768 (XGA)     | 27        | 0.53%   |
| 1920x540           | 23        | 0.46%   |
| 2736x1824          | 16        | 0.32%   |
| 2880x1800          | 13        | 0.26%   |
| 3200x1800 (QHD+)   | 12        | 0.24%   |
| 2160x1440          | 12        | 0.24%   |
| 2256x1504          | 10        | 0.2%    |
| 1600x1200          | 9         | 0.18%   |
| 1280x768           | 9         | 0.18%   |
| 5760x1080          | 8         | 0.16%   |
| 1280x720 (HD)      | 8         | 0.16%   |
| 3840x2400          | 6         | 0.12%   |
| 3600x1080          | 5         | 0.1%    |
| 5760x2160          | 4         | 0.08%   |
| 4480x1440          | 4         | 0.08%   |
| 3840x1600          | 4         | 0.08%   |
| 1920x1280          | 4         | 0.08%   |
| 1680x945           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 2880x1920          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1920x515           | 3         | 0.06%   |
| 1152x864           | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1390      | 27.18%  |
| 13      | 454       | 8.88%   |
| Unknown | 419       | 8.19%   |
| 14      | 380       | 7.43%   |
| 17      | 323       | 6.32%   |
| 27      | 234       | 4.58%   |
| 24      | 225       | 4.4%    |
| 21      | 225       | 4.4%    |
| 23      | 213       | 4.17%   |
| 19      | 154       | 3.01%   |
| 18      | 130       | 2.54%   |
| 11      | 124       | 2.42%   |
| 20      | 114       | 2.23%   |
| 12      | 103       | 2.01%   |
| 31      | 98        | 1.92%   |
| 22      | 92        | 1.8%    |
| 10      | 61        | 1.19%   |
| 34      | 55        | 1.08%   |
| 40      | 32        | 0.63%   |
| 54      | 29        | 0.57%   |
| 84      | 28        | 0.55%   |
| 72      | 27        | 0.53%   |
| 16      | 24        | 0.47%   |
| 26      | 22        | 0.43%   |
| 32      | 20        | 0.39%   |
| 25      | 12        | 0.23%   |
| 52      | 11        | 0.22%   |
| 65      | 9         | 0.18%   |
| 36      | 9         | 0.18%   |
| 49      | 8         | 0.16%   |
| 42      | 7         | 0.14%   |
| 74      | 6         | 0.12%   |
| 46      | 6         | 0.12%   |
| 29      | 6         | 0.12%   |
| 28      | 6         | 0.12%   |
| 39      | 5         | 0.1%    |
| 37      | 5         | 0.1%    |
| 33      | 5         | 0.1%    |
| 8       | 5         | 0.1%    |
| 58      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2045      | 40.45%  |
| 501-600     | 643       | 12.72%  |
| 401-500     | 630       | 12.46%  |
| 201-300     | 498       | 9.85%   |
| Unknown     | 419       | 8.29%   |
| 351-400     | 385       | 7.62%   |
| 601-700     | 133       | 2.63%   |
| 701-800     | 89        | 1.76%   |
| 1001-1500   | 85        | 1.68%   |
| 1501-2000   | 64        | 1.27%   |
| 801-900     | 46        | 0.91%   |
| 901-1000    | 13        | 0.26%   |
| 101-200     | 5         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3405      | 71.35%  |
| 16/10   | 659       | 13.81%  |
| Unknown | 371       | 7.77%   |
| 5/4     | 142       | 2.98%   |
| 21/9    | 63        | 1.32%   |
| 3/2     | 55        | 1.15%   |
| 4/3     | 52        | 1.09%   |
| 32/9    | 13        | 0.27%   |
| 6/5     | 7         | 0.15%   |
| 3.73    | 3         | 0.06%   |
| 0.62    | 2         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1381      | 27.19%  |
| 81-90          | 679       | 13.37%  |
| 201-250        | 596       | 11.73%  |
| Unknown        | 419       | 8.25%   |
| 151-200        | 358       | 7.05%   |
| 301-350        | 243       | 4.78%   |
| 351-500        | 190       | 3.74%   |
| 121-130        | 189       | 3.72%   |
| 141-150        | 178       | 3.5%    |
| 71-80          | 158       | 3.11%   |
| More than 1000 | 135       | 2.66%   |
| 51-60          | 126       | 2.48%   |
| 251-300        | 94        | 1.85%   |
| 61-70          | 90        | 1.77%   |
| 501-1000       | 78        | 1.54%   |
| 131-140        | 63        | 1.24%   |
| 41-50          | 59        | 1.16%   |
| 111-120        | 24        | 0.47%   |
| 91-100         | 15        | 0.3%    |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1613      | 32.48%  |
| 51-100        | 1566      | 31.53%  |
| 121-160       | 973       | 19.59%  |
| Unknown       | 419       | 8.44%   |
| 161-240       | 197       | 3.97%   |
| 1-50          | 135       | 2.72%   |
| More than 240 | 63        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4453      | 83.78%  |
| 2     | 561       | 10.56%  |
| 0     | 251       | 4.72%   |
| 3     | 45        | 0.85%   |
| 4     | 4         | 0.08%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2751      | 33.85%  |
| Intel                             | 2103      | 25.88%  |
| Qualcomm Atheros                  | 1054      | 12.97%  |
| Broadcom                          | 660       | 8.12%   |
| Broadcom Limited                  | 202       | 2.49%   |
| Marvell Technology Group          | 144       | 1.77%   |
| Ralink Technology                 | 137       | 1.69%   |
| Nvidia                            | 131       | 1.61%   |
| Ralink                            | 106       | 1.3%    |
| TP-Link                           | 96        | 1.18%   |
| MediaTek                          | 68        | 0.84%   |
| Samsung Electronics               | 51        | 0.63%   |
| ASIX Electronics                  | 36        | 0.44%   |
| Silicon Integrated Systems [SiS]  | 34        | 0.42%   |
| Xiaomi                            | 33        | 0.41%   |
| NetGear                           | 33        | 0.41%   |
| VIA Technologies                  | 31        | 0.38%   |
| D-Link                            | 28        | 0.34%   |
| JMicron Technology                | 27        | 0.33%   |
| Dell                              | 27        | 0.33%   |
| Qualcomm Atheros Communications   | 24        | 0.3%    |
| Huawei Technologies               | 23        | 0.28%   |
| D-Link System                     | 23        | 0.28%   |
| Edimax Technology                 | 19        | 0.23%   |
| DisplayLink                       | 19        | 0.23%   |
| Sierra Wireless                   | 18        | 0.22%   |
| ASUSTek Computer                  | 18        | 0.22%   |
| Microsoft                         | 16        | 0.2%    |
| Hewlett-Packard                   | 15        | 0.18%   |
| OPPO Electronics                  | 14        | 0.17%   |
| Motorola PCS                      | 12        | 0.15%   |
| Qualcomm                          | 10        | 0.12%   |
| Belkin Components                 | 10        | 0.12%   |
| Linksys                           | 9         | 0.11%   |
| Ericsson Business Mobile Networks | 9         | 0.11%   |
| Aquantia                          | 8         | 0.1%    |
| AMD                               | 8         | 0.1%    |
| T & A Mobile Phones               | 6         | 0.07%   |
| Google                            | 6         | 0.07%   |
| Attansic Technology               | 6         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1659      | 17.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 497       | 5.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 222       | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 157       | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 146       | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 135       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 130       | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 127       | 1.34%   |
| Intel Wireless 7260                                                     | 123       | 1.3%    |
| Intel Wireless 7265                                                     | 117       | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 105       | 1.11%   |
| Intel Wireless 8265 / 8275                                              | 98        | 1.04%   |
| Intel Ethernet Connection I217-LM                                       | 92        | 0.97%   |
| Intel Wireless 3165                                                     | 82        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 76        | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                       | 75        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 71        | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 71        | 0.75%   |
| Intel Wi-Fi 6 AX201                                                     | 71        | 0.75%   |
| Intel Wireless 8260                                                     | 70        | 0.74%   |
| Intel I211 Gigabit Network Connection                                   | 69        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 68        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 66        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 65        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                         | 64        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 62        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 57        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 56        | 0.59%   |
| Realtek 802.11ac NIC                                                    | 55        | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 52        | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 0.55%   |
| Intel WiFi Link 5100                                                    | 50        | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 49        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 48        | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 47        | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                    | 47        | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 43        | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 42        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1561      | 34.87%  |
| Realtek Semiconductor                 | 839       | 18.74%  |
| Qualcomm Atheros                      | 839       | 18.74%  |
| Broadcom                              | 454       | 10.14%  |
| Ralink Technology                     | 137       | 3.06%   |
| Broadcom Limited                      | 130       | 2.9%    |
| Ralink                                | 106       | 2.37%   |
| TP-Link                               | 84        | 1.88%   |
| MediaTek                              | 55        | 1.23%   |
| NetGear                               | 32        | 0.71%   |
| D-Link                                | 28        | 0.63%   |
| Qualcomm Atheros Communications       | 24        | 0.54%   |
| Marvell Technology Group              | 23        | 0.51%   |
| Edimax Technology                     | 19        | 0.42%   |
| D-Link System                         | 19        | 0.42%   |
| Sierra Wireless                       | 18        | 0.4%    |
| ASUSTek Computer                      | 16        | 0.36%   |
| Microsoft                             | 13        | 0.29%   |
| Dell                                  | 12        | 0.27%   |
| Belkin Components                     | 10        | 0.22%   |
| Linksys                               | 9         | 0.2%    |
| Sitecom Europe                        | 4         | 0.09%   |
| Micro Star International              | 4         | 0.09%   |
| Gemtek                                | 4         | 0.09%   |
| ZyDAS                                 | 3         | 0.07%   |
| TRENDnet                              | 3         | 0.07%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| Xiaomi                                | 2         | 0.04%   |
| Senao                                 | 2         | 0.04%   |
| Philips (or NXP)                      | 2         | 0.04%   |
| IMC Networks                          | 2         | 0.04%   |
| Fibocom                               | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Tenda                                 | 1         | 0.02%   |
| Qualcomm                              | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| Panasonic (Matsushita)                | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 157       | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 146       | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 135       | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 130       | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 127       | 2.81%   |
| Intel Wireless 7260                                                     | 123       | 2.72%   |
| Intel Wireless 7265                                                     | 117       | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 105       | 2.32%   |
| Intel Wireless 8265 / 8275                                              | 98        | 2.17%   |
| Intel Wireless 3165                                                     | 82        | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 76        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 71        | 1.57%   |
| Intel Wi-Fi 6 AX201                                                     | 71        | 1.57%   |
| Intel Wireless 8260                                                     | 70        | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 68        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 66        | 1.46%   |
| Ralink MT7601U Wireless Adapter                                         | 64        | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 62        | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 57        | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 56        | 1.24%   |
| Realtek 802.11ac NIC                                                    | 55        | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 52        | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 1.15%   |
| Intel WiFi Link 5100                                                    | 50        | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 49        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 43        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 42        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 42        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 41        | 0.91%   |
| Intel Wireless 3160                                                     | 37        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 36        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.8%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 35        | 0.77%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 0.73%   |
| Intel Wireless-AC 9260                                                  | 31        | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 30        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2395      | 50.33%  |
| Intel                                  | 1072      | 22.53%  |
| Qualcomm Atheros                       | 307       | 6.45%   |
| Broadcom                               | 291       | 6.11%   |
| Nvidia                                 | 131       | 2.75%   |
| Marvell Technology Group               | 121       | 2.54%   |
| Broadcom Limited                       | 78        | 1.64%   |
| Samsung Electronics                    | 50        | 1.05%   |
| ASIX Electronics                       | 36        | 0.76%   |
| Silicon Integrated Systems [SiS]       | 32        | 0.67%   |
| Xiaomi                                 | 31        | 0.65%   |
| VIA Technologies                       | 31        | 0.65%   |
| JMicron Technology                     | 27        | 0.57%   |
| Huawei Technologies                    | 19        | 0.4%    |
| DisplayLink                            | 19        | 0.4%    |
| OPPO Electronics                       | 14        | 0.29%   |
| MediaTek                               | 13        | 0.27%   |
| TP-Link                                | 12        | 0.25%   |
| Qualcomm                               | 9         | 0.19%   |
| Motorola PCS                           | 8         | 0.17%   |
| Aquantia                               | 8         | 0.17%   |
| Google                                 | 6         | 0.13%   |
| Attansic Technology                    | 6         | 0.13%   |
| D-Link System                          | 4         | 0.08%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| Davicom Semiconductor                  | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| T & A Mobile Phones                    | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| Lenovo                                 | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| ASUSTek Computer                       | 2         | 0.04%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1659      | 34.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 497       | 10.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 222       | 4.61%   |
| Intel Ethernet Connection I217-LM                                 | 92        | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 75        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 69        | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 65        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 48        | 1%      |
| Nvidia MCP61 Ethernet                                             | 47        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 47        | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 41        | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 39        | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.73%   |
| Intel 82567LM Gigabit Network Connection                          | 35        | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 32        | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 31        | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 29        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 28        | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 28        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 28        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 27        | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 25        | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 25        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 25        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 0.44%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 20        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4503      | 51.23%  |
| WiFi     | 4161      | 47.34%  |
| Modem    | 111       | 1.26%   |
| Unknown  | 14        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3265      | 60.26%  |
| Ethernet | 2149      | 39.66%  |
| Modem    | 2         | 0.04%   |
| Unknown  | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2974      | 56.72%  |
| 1     | 2027      | 38.66%  |
| 0     | 160       | 3.05%   |
| 3     | 75        | 1.43%   |
| 5     | 4         | 0.08%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4056      | 76.49%  |
| Yes  | 1247      | 23.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1072      | 37.92%  |
| Realtek Semiconductor           | 321       | 11.35%  |
| Qualcomm Atheros Communications | 277       | 9.8%    |
| Broadcom                        | 196       | 6.93%   |
| Apple                           | 154       | 5.45%   |
| Cambridge Silicon Radio         | 149       | 5.27%   |
| IMC Networks                    | 114       | 4.03%   |
| Lite-On Technology              | 79        | 2.79%   |
| Foxconn / Hon Hai               | 75        | 2.65%   |
| Dell                            | 69        | 2.44%   |
| Hewlett-Packard                 | 67        | 2.37%   |
| ASUSTek Computer                | 42        | 1.49%   |
| Toshiba                         | 40        | 1.41%   |
| Ralink                          | 26        | 0.92%   |
| Marvell Semiconductor           | 19        | 0.67%   |
| MediaTek                        | 17        | 0.6%    |
| Realtek                         | 14        | 0.5%    |
| Alps Electric                   | 14        | 0.5%    |
| Foxconn International           | 12        | 0.42%   |
| Dynex                           | 10        | 0.35%   |
| TP-Link                         | 8         | 0.28%   |
| Integrated System Solution      | 8         | 0.28%   |
| Belkin Components               | 6         | 0.21%   |
| Askey Computer                  | 6         | 0.21%   |
| Ralink Technology               | 5         | 0.18%   |
| Taiyo Yuden                     | 4         | 0.14%   |
| Micro Star International        | 4         | 0.14%   |
| Chicony Electronics             | 3         | 0.11%   |
| Unknown                         | 3         | 0.11%   |
| Qcom                            | 2         | 0.07%   |
| ISSC                            | 2         | 0.07%   |
| Actions                         | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Mobile Action Technology        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 498       | 17.59%  |
| Realtek Bluetooth Radio                             | 218       | 7.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 149       | 5.26%   |
| Intel AX201 Bluetooth                               | 136       | 4.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 126       | 4.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 117       | 4.13%   |
| Intel AX200 Bluetooth                               | 112       | 3.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 86        | 3.04%   |
| Apple Bluetooth Host Controller                     | 68        | 2.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 51        | 1.8%    |
| Intel Bluetooth Device                              | 50        | 1.77%   |
| Intel AX210 Bluetooth                               | 46        | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 45        | 1.59%   |
| IMC Networks Bluetooth Device                       | 42        | 1.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 40        | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 40        | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 39        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 34        | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 32        | 1.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 30        | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 29        | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 0.99%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 26        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 21        | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.71%   |
| Apple Bluetooth HCI                                 | 20        | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.67%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.67%   |
| Marvell Bluetooth and Wireless LAN Composite        | 18        | 0.64%   |
| Lite-On Bluetooth Device                            | 16        | 0.57%   |
| MediaTek Wireless_Device                            | 15        | 0.53%   |
| IMC Networks Wireless_Device                        | 14        | 0.49%   |
| Toshiba Bluetooth Device                            | 13        | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3802      | 56.43%  |
| AMD                                          | 1364      | 20.25%  |
| Nvidia                                       | 1039      | 15.42%  |
| C-Media Electronics                          | 88        | 1.31%   |
| Silicon Integrated Systems [SiS]             | 37        | 0.55%   |
| VIA Technologies                             | 35        | 0.52%   |
| Creative Labs                                | 34        | 0.5%    |
| Logitech                                     | 28        | 0.42%   |
| Generalplus Technology                       | 20        | 0.3%    |
| Texas Instruments                            | 19        | 0.28%   |
| JMTek                                        | 19        | 0.28%   |
| Kingston Technology                          | 16        | 0.24%   |
| ASUSTek Computer                             | 14        | 0.21%   |
| Creative Technology                          | 13        | 0.19%   |
| Tenx Technology                              | 12        | 0.18%   |
| Realtek Semiconductor                        | 12        | 0.18%   |
| Plantronics                                  | 12        | 0.18%   |
| GN Netcom                                    | 12        | 0.18%   |
| Razer USA                                    | 11        | 0.16%   |
| SteelSeries ApS                              | 6         | 0.09%   |
| Lenovo                                       | 6         | 0.09%   |
| Focusrite-Novation                           | 6         | 0.09%   |
| DCMT Technology                              | 5         | 0.07%   |
| Corsair                                      | 5         | 0.07%   |
| Yamaha                                       | 4         | 0.06%   |
| Micro Star International                     | 4         | 0.06%   |
| Astro Gaming                                 | 4         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.04%   |
| Samsung Electronics                          | 3         | 0.04%   |
| RODE Microphones                             | 3         | 0.04%   |
| PreSonus Audio Electronics                   | 3         | 0.04%   |
| KTMicro                                      | 3         | 0.04%   |
| Jieli Technology                             | 3         | 0.04%   |
| DSEA A/S                                     | 3         | 0.04%   |
| BEHRINGER International                      | 3         | 0.04%   |
| Apple                                        | 3         | 0.04%   |
| AKAI Professional M.I.                       | 3         | 0.04%   |
| XMOS                                         | 2         | 0.03%   |
| Turtle Beach                                 | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 417       | 5.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 383       | 4.8%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 333       | 4.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 304       | 3.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 269       | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 268       | 3.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 245       | 3.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 241       | 3.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 222       | 2.79%   |
| AMD FCH Azalia Controller                                                                         | 219       | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 193       | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 152       | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 148       | 1.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 143       | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 120       | 1.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 119       | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 112       | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 109       | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 108       | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 105       | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 105       | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 103       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 99        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 97        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 92        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 87        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 81        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 78        | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 70        | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 68        | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 65        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 65        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 63        | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 60        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 58        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 58        | 0.73%   |
| Intel 200 Series PCH HD Audio                                                                     | 56        | 0.7%    |
| AMD High Definition Audio Controller                                                              | 56        | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 53        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                                                | 49        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 240       | 21.62%  |
| SK hynix               | 215       | 19.37%  |
| Unknown                | 145       | 13.06%  |
| Micron Technology      | 107       | 9.64%   |
| Kingston               | 92        | 8.29%   |
| Crucial                | 50        | 4.5%    |
| Corsair                | 31        | 2.79%   |
| G.Skill                | 27        | 2.43%   |
| Unknown (ABCD)         | 23        | 2.07%   |
| Elpida                 | 23        | 2.07%   |
| Ramaxel Technology     | 20        | 1.8%    |
| Nanya Technology       | 19        | 1.71%   |
| A-DATA Technology      | 17        | 1.53%   |
| Team                   | 11        | 0.99%   |
| Smart                  | 9         | 0.81%   |
| Unknown                | 8         | 0.72%   |
| Qimonda                | 6         | 0.54%   |
| Patriot                | 6         | 0.54%   |
| Transcend              | 3         | 0.27%   |
| Timetec                | 3         | 0.27%   |
| Avant                  | 3         | 0.27%   |
| Wilk                   | 2         | 0.18%   |
| Unifosa                | 2         | 0.18%   |
| Teikon                 | 2         | 0.18%   |
| Smart Brazil           | 2         | 0.18%   |
| SHARETRONIC            | 2         | 0.18%   |
| PNY                    | 2         | 0.18%   |
| High Bridge            | 2         | 0.18%   |
| ff                     | 2         | 0.18%   |
| fef5                   | 2         | 0.18%   |
| CSX                    | 2         | 0.18%   |
| Apacer                 | 2         | 0.18%   |
| 4ea5                   | 2         | 0.18%   |
| Walton Chaintech       | 1         | 0.09%   |
| Unknown (08B5)         | 1         | 0.09%   |
| Unknown (07F7)         | 1         | 0.09%   |
| Unknown (000080B30080) | 1         | 0.09%   |
| Toshiba                | 1         | 0.09%   |
| SUPER KINGSTEK         | 1         | 0.09%   |
| Strontium              | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 21        | 1.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.76%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 8         | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.67%   |
| Unknown                                                          | 8         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.51%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.42%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.42%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.34%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.34%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 4         | 0.34%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.34%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.34%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 365       | 37.86%  |
| DDR4    | 328       | 34.02%  |
| DDR2    | 91        | 9.44%   |
| LPDDR4  | 52        | 5.39%   |
| SDRAM   | 42        | 4.36%   |
| Unknown | 33        | 3.42%   |
| LPDDR3  | 30        | 3.11%   |
| DDR     | 10        | 1.04%   |
| DRAM    | 6         | 0.62%   |
| DDR5    | 5         | 0.52%   |
| LPDDR5  | 2         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 603       | 63.61%  |
| DIMM         | 263       | 27.74%  |
| Row Of Chips | 68        | 7.17%   |
| Unknown      | 8         | 0.84%   |
| Chip         | 5         | 0.53%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 339       | 31.45%  |
| 4096  | 329       | 30.52%  |
| 2048  | 214       | 19.85%  |
| 16384 | 83        | 7.7%    |
| 1024  | 77        | 7.14%   |
| 32768 | 20        | 1.86%   |
| 512   | 14        | 1.3%    |
| 256   | 2         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 233       | 22.38%  |
| 3200    | 114       | 10.95%  |
| 2667    | 113       | 10.85%  |
| 1333    | 72        | 6.92%   |
| 2400    | 71        | 6.82%   |
| 667     | 47        | 4.51%   |
| Unknown | 43        | 4.13%   |
| 1334    | 41        | 3.94%   |
| 2133    | 40        | 3.84%   |
| 800     | 30        | 2.88%   |
| 1066    | 22        | 2.11%   |
| 1867    | 19        | 1.83%   |
| 4267    | 17        | 1.63%   |
| 3600    | 17        | 1.63%   |
| 3266    | 15        | 1.44%   |
| 2048    | 12        | 1.15%   |
| 975     | 11        | 1.06%   |
| 533     | 11        | 1.06%   |
| 4199    | 9         | 0.86%   |
| 1866    | 8         | 0.77%   |
| 1067    | 8         | 0.77%   |
| 3000    | 7         | 0.67%   |
| 400     | 7         | 0.67%   |
| 1800    | 6         | 0.58%   |
| 2933    | 5         | 0.48%   |
| 4800    | 4         | 0.38%   |
| 3733    | 4         | 0.38%   |
| 333     | 4         | 0.38%   |
| 8400    | 3         | 0.29%   |
| 6400    | 3         | 0.29%   |
| 4266    | 3         | 0.29%   |
| 3866    | 3         | 0.29%   |
| 3400    | 3         | 0.29%   |
| 2800    | 3         | 0.29%   |
| 2666    | 3         | 0.29%   |
| 3800    | 2         | 0.19%   |
| 3666    | 2         | 0.19%   |
| 3500    | 2         | 0.19%   |
| 3466    | 2         | 0.19%   |
| 3333    | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 44        | 29.93%  |
| Canon                 | 32        | 21.77%  |
| Brother Industries    | 24        | 16.33%  |
| Seiko Epson           | 20        | 13.61%  |
| Samsung Electronics   | 15        | 10.2%   |
| Lexmark International | 3         | 2.04%   |
| STMicroelectronics    | 2         | 1.36%   |
| Ricoh                 | 2         | 1.36%   |
| Zebra                 | 1         | 0.68%   |
| Toshiba TEC           | 1         | 0.68%   |
| QinHeng Electronics   | 1         | 0.68%   |
| Pantum                | 1         | 0.68%   |
| Konica Minolta        | 1         | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 2.72%   |
| Seiko Epson L3110 Series                                  | 3         | 2.04%   |
| HP DeskJet 2700 series                                    | 3         | 2.04%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.04%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.36%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2         | 1.36%   |
| Samsung SCX-3400 Series                                   | 2         | 1.36%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.36%   |
| Samsung CLX-3300 Series                                   | 2         | 1.36%   |
| Samsung C460 Series                                       | 2         | 1.36%   |
| HP OfficeJet 6950                                         | 2         | 1.36%   |
| HP LaserJet Professional P1102w                           | 2         | 1.36%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.36%   |
| HP LaserJet P1102                                         | 2         | 1.36%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.36%   |
| HP ENVY 5000 series                                       | 2         | 1.36%   |
| HP ENVY 4520 series                                       | 2         | 1.36%   |
| HP DeskJet 2130 series                                    | 2         | 1.36%   |
| HP DeskJet 1110 series                                    | 2         | 1.36%   |
| Canon PIXMA MX340                                         | 2         | 1.36%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.36%   |
| Canon MF4010 series                                       | 2         | 1.36%   |
| Canon LiDE 400                                            | 2         | 1.36%   |
| Brother HL-52x0 series                                    | 2         | 1.36%   |
| Brother HL-2140 series                                    | 2         | 1.36%   |
| Brother HL-2130 series                                    | 2         | 1.36%   |
| Zebra ZP 450 Printer                                      | 1         | 0.68%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.68%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.68%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.68%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.68%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.68%   |
| Seiko Epson Printer                                       | 1         | 0.68%   |
| Seiko Epson L805 Series                                   | 1         | 0.68%   |
| Seiko Epson L365 Series                                   | 1         | 0.68%   |
| Seiko Epson L360 Series                                   | 1         | 0.68%   |
| Seiko Epson L355 Series                                   | 1         | 0.68%   |
| Seiko Epson L120 Series                                   | 1         | 0.68%   |
| Seiko Epson ET-3850 Series                                | 1         | 0.68%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 72.22%  |
| Seiko Epson     | 3         | 16.67%  |
| Hewlett-Packard | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 3         | 15.79%  |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 10.53%  |
| Canon CanoScan LIDE 25                      | 2         | 10.53%  |
| Canon CanoScan LiDE 100                     | 2         | 10.53%  |
| Seiko Epson Scanner                         | 1         | 5.26%   |
| HP ScanJet 2400c                            | 1         | 5.26%   |
| HP PSC 1200                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 90                      | 1         | 5.26%   |
| Canon CanoScan LiDE 60                      | 1         | 5.26%   |
| Canon CanoScan LiDE 220                     | 1         | 5.26%   |
| Canon CanoScan LiDE 200                     | 1         | 5.26%   |
| Canon CanoScan LiDE 110                     | 1         | 5.26%   |
| Canon CanoScan D660U                        | 1         | 5.26%   |
| Canon CanoScan 8800F                        | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 651       | 22.32%  |
| Microdia                               | 268       | 9.19%   |
| Realtek Semiconductor                  | 220       | 7.54%   |
| IMC Networks                           | 195       | 6.68%   |
| Sunplus Innovation Technology          | 154       | 5.28%   |
| Bison Electronics                      | 148       | 5.07%   |
| Apple                                  | 144       | 4.94%   |
| Suyin                                  | 130       | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 127       | 4.35%   |
| Quanta                                 | 104       | 3.57%   |
| Logitech                               | 102       | 3.5%    |
| Syntek                                 | 71        | 2.43%   |
| Silicon Motion                         | 57        | 1.95%   |
| Lite-On Technology                     | 54        | 1.85%   |
| Alcor Micro                            | 51        | 1.75%   |
| Acer                                   | 41        | 1.41%   |
| Ricoh                                  | 32        | 1.1%    |
| Samsung Electronics                    | 31        | 1.06%   |
| Microsoft                              | 28        | 0.96%   |
| Luxvisions Innotech Limited            | 23        | 0.79%   |
| Z-Star Microelectronics                | 20        | 0.69%   |
| ALi                                    | 19        | 0.65%   |
| Importek                               | 17        | 0.58%   |
| Primax Electronics                     | 15        | 0.51%   |
| GEMBIRD                                | 15        | 0.51%   |
| Sonix Technology                       | 14        | 0.48%   |
| icSpring                               | 14        | 0.48%   |
| Generalplus Technology                 | 13        | 0.45%   |
| Lenovo                                 | 12        | 0.41%   |
| OmniVision Technologies                | 10        | 0.34%   |
| ARC International                      | 10        | 0.34%   |
| Genesys Logic                          | 8         | 0.27%   |
| SunplusIT                              | 7         | 0.24%   |
| Cubeternet                             | 7         | 0.24%   |
| Jieli Technology                       | 6         | 0.21%   |
| Sunplus Technology                     | 5         | 0.17%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.17%   |
| Intel                                  | 5         | 0.17%   |
| Y Media                                | 4         | 0.14%   |
| Razer USA                              | 4         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 84        | 2.86%   |
| Microdia Integrated_Webcam_HD                    | 50        | 1.7%    |
| Apple FaceTime HD Camera (Built-in)              | 47        | 1.6%    |
| IMC Networks USB2.0 HD UVC WebCam                | 46        | 1.57%   |
| Realtek Integrated_Webcam_HD                     | 44        | 1.5%    |
| Bison Integrated Camera                          | 41        | 1.4%    |
| Chicony HD WebCam                                | 39        | 1.33%   |
| Microdia Integrated Webcam                       | 36        | 1.23%   |
| Chicony HP Truevision HD                         | 36        | 1.23%   |
| Syntek Integrated Camera                         | 35        | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 34        | 1.16%   |
| Apple Built-in iSight                            | 34        | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)          | 31        | 1.06%   |
| IMC Networks Integrated Camera                   | 30        | 1.02%   |
| Chicony TOSHIBA Web Camera - HD                  | 30        | 1.02%   |
| Sunplus Integrated_Webcam_HD                     | 28        | 0.95%   |
| Chicony USB 2.0 Camera                           | 27        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 26        | 0.89%   |
| Chicony EasyCamera                               | 25        | 0.85%   |
| Logitech Webcam C270                             | 24        | 0.82%   |
| Chicony HP TrueVision HD Camera                  | 24        | 0.82%   |
| Sunplus HD WebCam                                | 23        | 0.78%   |
| Bison Lenovo EasyCamera                          | 23        | 0.78%   |
| Realtek Integrated Webcam                        | 22        | 0.75%   |
| Logitech HD Pro Webcam C920                      | 22        | 0.75%   |
| Chicony Lenovo EasyCamera                        | 21        | 0.72%   |
| Alcor Micro USB 2.0 PC cam                       | 21        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 20        | 0.68%   |
| Chicony VGA WebCam                               | 19        | 0.65%   |
| Apple FaceTime HD Camera                         | 19        | 0.65%   |
| Realtek USB Camera                               | 18        | 0.61%   |
| Microdia Webcam Vitade AF                        | 18        | 0.61%   |
| Chicony HP Wide Vision HD Camera                 | 18        | 0.61%   |
| Chicony HP HD Webcam                             | 18        | 0.61%   |
| Suyin HP Truevision HD                           | 17        | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 17        | 0.58%   |
| Lite-On HP HD Camera                             | 17        | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam                    | 17        | 0.58%   |
| Realtek HP Truevision HD                         | 16        | 0.55%   |
| Quanta HP TrueVision HD Camera                   | 16        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 206       | 43.37%  |
| AuthenTec                          | 63        | 13.26%  |
| Synaptics                          | 59        | 12.42%  |
| Shenzhen Goodix Technology         | 49        | 10.32%  |
| Upek                               | 34        | 7.16%   |
| Elan Microelectronics              | 26        | 5.47%   |
| STMicroelectronics                 | 18        | 3.79%   |
| LighTuning Technology              | 13        | 2.74%   |
| Samsung Electronics                | 2         | 0.42%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.42%   |
| Next Biometrics                    | 1         | 0.21%   |
| HOLTEK                             | 1         | 0.21%   |
| Focal-systems.Corp                 | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 8.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 32        | 6.74%   |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 5.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 22        | 4.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 4%      |
| Validity Sensors VFS491                                                    | 19        | 4%      |
| Validity Sensors Fingerprint scanner                                       | 18        | 3.79%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 3.79%   |
| AuthenTec AES2810                                                          | 18        | 3.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 3.58%   |
| Elan ELAN:ARM-M4                                                           | 15        | 3.16%   |
| Synaptics  WBDI                                                            | 13        | 2.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 2.11%   |
| AuthenTec AES1600                                                          | 10        | 2.11%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.89%   |
| Synaptics UWP WBDI                                                         | 8         | 1.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.47%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.26%   |
| Synaptics WBDI                                                             | 6         | 1.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.26%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.26%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.05%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.84%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.84%   |
| LighTuning Fingerprint Sensor                                              | 4         | 0.84%   |
| Elan WBF Fingerprint Sensor                                                | 4         | 0.84%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 101       | 50.75%  |
| Alcor Micro                       | 34        | 17.09%  |
| O2 Micro                          | 28        | 14.07%  |
| Lenovo                            | 9         | 4.52%   |
| Upek                              | 7         | 3.52%   |
| Realtek Semiconductor             | 4         | 2.01%   |
| SCM Microsystems                  | 3         | 1.51%   |
| Yubico.com                        | 2         | 1.01%   |
| VASCO Data Security International | 2         | 1.01%   |
| Fujitsu Siemens Computers         | 2         | 1.01%   |
| Advanced Card Systems             | 2         | 1.01%   |
| Reiner SCT Kartensysteme          | 1         | 0.5%    |
| OmniKey                           | 1         | 0.5%    |
| Kobil Systems                     | 1         | 0.5%    |
| Jing-Mold Enterprise              | 1         | 0.5%    |
| Chicony Electronics               | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 23.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 16.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 12%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 11.5%   |
| Broadcom 5880                                                                | 23        | 11.5%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.5%    |
| Broadcom 58200                                                               | 6         | 3%      |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.5%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1%      |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1%      |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.5%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.5%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.5%    |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.5%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.5%    |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.5%    |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.5%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.5%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.5%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.5%    |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3690      | 69.41%  |
| 1     | 1304      | 24.53%  |
| 2     | 286       | 5.38%   |
| 3     | 30        | 0.56%   |
| 4     | 4         | 0.08%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 484       | 25.27%  |
| Fingerprint reader       | 468       | 24.44%  |
| Net/wireless             | 324       | 16.92%  |
| Chipcard                 | 186       | 9.71%   |
| Multimedia controller    | 163       | 8.51%   |
| Communication controller | 50        | 2.61%   |
| Modem                    | 47        | 2.45%   |
| Storage                  | 45        | 2.35%   |
| Bluetooth                | 37        | 1.93%   |
| Sound                    | 22        | 1.15%   |
| Camera                   | 16        | 0.84%   |
| Unassigned class         | 15        | 0.78%   |
| Flash memory             | 13        | 0.68%   |
| Net/ethernet             | 11        | 0.57%   |
| Network                  | 7         | 0.37%   |
| Card reader              | 7         | 0.37%   |
| Storage/raid             | 6         | 0.31%   |
| Dvb card                 | 5         | 0.26%   |
| Storage/ide              | 4         | 0.21%   |
| Storage/nvme             | 3         | 0.16%   |
| Unclassified device      | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

