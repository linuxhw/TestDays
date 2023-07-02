MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 484

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [123d2215a1](https://linux-hardware.org/?probe=123d2215a1) | Jun 25, 2023 |
| Dell          | Latitude E6510              | Notebook    | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | Notebook    | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | Notebook    | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Dell          | Latitude 5540               | Notebook    | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | Notebook    | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | Notebook    | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | Notebook    | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| ASUSTek       | X202E                       | Notebook    | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | Notebook    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | Desktop     | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | Notebook    | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | Notebook    | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| HP            | 18E5                        | Desktop     | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| HP            | 3029h                       | Desktop     | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Samsung       | 950QDB                      | Convertible | [e16175f1c5](https://linux-hardware.org/?probe=e16175f1c5) | Mar 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | Desktop     | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 255 G3                      | Notebook    | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | 8184 X4                     | Desktop     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | Notebook    | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | Notebook    | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | Notebook    | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [700f0ded17](https://linux-hardware.org/?probe=700f0ded17) | Feb 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b4c5f2e2de](https://linux-hardware.org/?probe=b4c5f2e2de) | Feb 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 40        | 11.33%  |
| 6.0.0-6mx-amd64            | 27        | 7.65%   |
| 5.10.0-18-amd64            | 20        | 5.67%   |
| 5.10.0-13-amd64            | 20        | 5.67%   |
| 5.10.0-20-amd64            | 19        | 5.38%   |
| 5.10.0-9-amd64             | 18        | 5.1%    |
| 5.10.0-19-amd64            | 18        | 5.1%    |
| 5.14.0-4mx-amd64           | 16        | 4.53%   |
| 5.10.0-23-amd64            | 15        | 4.25%   |
| 5.16.0-5mx-amd64           | 14        | 3.97%   |
| 5.10.0-16-amd64            | 13        | 3.68%   |
| 5.18.0-4mx-amd64           | 10        | 2.83%   |
| 5.10.0-11-amd64            | 8         | 2.27%   |
| 5.10.0-22-amd64            | 7         | 1.98%   |
| 5.10.0-15-amd64            | 6         | 1.7%    |
| 5.10.0-14-amd64            | 6         | 1.7%    |
| 6.0.0-4mx-amd64            | 5         | 1.42%   |
| 6.0.0-10.1-liquorix-amd64  | 5         | 1.42%   |
| 5.19.0-2mx-amd64           | 4         | 1.13%   |
| 5.10.0-17-amd64            | 4         | 1.13%   |
| 5.10.0-10-amd64            | 4         | 1.13%   |
| 6.0.0-3mx-amd64            | 3         | 0.85%   |
| 5.16.0-6mx-amd64           | 3         | 0.85%   |
| 5.10.0-20-686-pae          | 3         | 0.85%   |
| 6.1.15-2-liquorix-amd64    | 2         | 0.57%   |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.57%   |
| 6.1.0-4mx-amd64            | 2         | 0.57%   |
| 6.1.0-2mx-amd64            | 2         | 0.57%   |
| 5.19.0-17.2-liquorix-amd64 | 2         | 0.57%   |
| 5.17.0-3mx-amd64           | 2         | 0.57%   |
| 5.16.0-4mx-amd64           | 2         | 0.57%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.57%   |
| 5.14.0-3mx-amd64           | 2         | 0.57%   |
| 5.10.0-8-amd64             | 2         | 0.57%   |
| 5.10.0-18-686-pae          | 2         | 0.57%   |
| 5.10.0-13-686-pae          | 2         | 0.57%   |
| 5.10.0-12-amd64            | 2         | 0.57%   |
| 5.10.0-11-686-pae          | 2         | 0.57%   |
| 6.2.7-x64v4-xanmod1        | 1         | 0.28%   |
| 6.2.14-1-liquorix-amd64    | 1         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 202       | 59.41%  |
| 6.0.0    | 43        | 12.65%  |
| 5.16.0   | 22        | 6.47%   |
| 5.14.0   | 19        | 5.59%   |
| 5.18.0   | 12        | 3.53%   |
| 5.19.0   | 10        | 2.94%   |
| 6.1.0    | 9         | 2.65%   |
| 5.17.0   | 6         | 1.76%   |
| 5.15.0   | 3         | 0.88%   |
| 6.1.15   | 2         | 0.59%   |
| 4.19.0   | 2         | 0.59%   |
| 6.2.7    | 1         | 0.29%   |
| 6.2.14   | 1         | 0.29%   |
| 6.1.12   | 1         | 0.29%   |
| 6.0.5    | 1         | 0.29%   |
| 5.10.82  | 1         | 0.29%   |
| 5.10.52  | 1         | 0.29%   |
| 5.10.142 | 1         | 0.29%   |
| 5.10.113 | 1         | 0.29%   |
| 5.10.111 | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 207       | 60.88%  |
| 6.0     | 44        | 12.94%  |
| 5.16    | 22        | 6.47%   |
| 5.14    | 19        | 5.59%   |
| 6.1     | 12        | 3.53%   |
| 5.18    | 12        | 3.53%   |
| 5.19    | 10        | 2.94%   |
| 5.17    | 6         | 1.76%   |
| 5.15    | 3         | 0.88%   |
| 6.2     | 2         | 0.59%   |
| 4.19    | 2         | 0.59%   |
| Unknown | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 316       | 96.34%  |
| i686   | 12        | 3.66%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 242       | 72.67%  |
| KDE5             | 69        | 20.72%  |
| lightdm-xsession | 6         | 1.8%    |
| GNOME            | 4         | 1.2%    |
| Unknown          | 4         | 1.2%    |
| Budgie           | 3         | 0.9%    |
| X-Cinnamon       | 1         | 0.3%    |
| LXQt             | 1         | 0.3%    |
| i3               | 1         | 0.3%    |
| GNOME Classic    | 1         | 0.3%    |
| fluxbox          | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 325       | 99.09%  |
| Tty     | 2         | 0.61%   |
| Wayland | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 256       | 77.58%  |
| SDDM    | 66        | 20%     |
| SLiM    | 6         | 1.82%   |
| GDM     | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 160       | 48.48%  |
| de_DE   | 44        | 13.33%  |
| it_IT   | 17        | 5.15%   |
| en_GB   | 16        | 4.85%   |
| ru_RU   | 10        | 3.03%   |
| fr_FR   | 9         | 2.73%   |
| en_AU   | 8         | 2.42%   |
| pl_PL   | 7         | 2.12%   |
| es_ES   | 6         | 1.82%   |
| es_AR   | 6         | 1.82%   |
| de_CH   | 5         | 1.52%   |
| Unknown | 4         | 1.21%   |
| tr_TR   | 3         | 0.91%   |
| pt_BR   | 3         | 0.91%   |
| es_MX   | 3         | 0.91%   |
| en_NZ   | 3         | 0.91%   |
| sv_SE   | 2         | 0.61%   |
| nl_NL   | 2         | 0.61%   |
| hu_HU   | 2         | 0.61%   |
| fi_FI   | 2         | 0.61%   |
| es_CO   | 2         | 0.61%   |
| en_CA   | 2         | 0.61%   |
| bg_BG   | 2         | 0.61%   |
| sk_SK   | 1         | 0.3%    |
| ro_RO   | 1         | 0.3%    |
| nb_NO   | 1         | 0.3%    |
| id_ID   | 1         | 0.3%    |
| hr_HR   | 1         | 0.3%    |
| fr_CA   | 1         | 0.3%    |
| fr_BE   | 1         | 0.3%    |
| eu_ES   | 1         | 0.3%    |
| es_VE   | 1         | 0.3%    |
| es_UY   | 1         | 0.3%    |
| es_PE   | 1         | 0.3%    |
| da_DK   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 214       | 65.24%  |
| BIOS | 114       | 34.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 280       | 84.59%  |
| Overlay  | 35        | 10.57%  |
| Btrfs    | 11        | 3.32%   |
| Xfs      | 2         | 0.6%    |
| Reiserfs | 1         | 0.3%    |
| F2fs     | 1         | 0.3%    |
| Ext3     | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 234       | 71.34%  |
| MBR     | 92        | 28.05%  |
| Unknown | 2         | 0.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 239       | 72.21%  |
| Yes       | 92        | 27.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 182       | 55.15%  |
| Yes       | 148       | 44.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 50        | 15.24%  |
| Lenovo                               | 47        | 14.33%  |
| ASUSTek Computer                     | 46        | 14.02%  |
| Dell                                 | 30        | 9.15%   |
| Apple                                | 18        | 5.49%   |
| MSI                                  | 16        | 4.88%   |
| Gigabyte Technology                  | 16        | 4.88%   |
| Acer                                 | 16        | 4.88%   |
| ASRock                               | 9         | 2.74%   |
| Sony                                 | 8         | 2.44%   |
| Unknown                              | 6         | 1.83%   |
| Medion                               | 5         | 1.52%   |
| Intel                                | 5         | 1.52%   |
| Toshiba                              | 4         | 1.22%   |
| Samsung Electronics                  | 3         | 0.91%   |
| Alienware                            | 3         | 0.91%   |
| ZOTAC                                | 2         | 0.61%   |
| TUXEDO                               | 2         | 0.61%   |
| Pegatron                             | 2         | 0.61%   |
| Microsoft                            | 2         | 0.61%   |
| Fujitsu Siemens                      | 2         | 0.61%   |
| Fujitsu                              | 2         | 0.61%   |
| Chuwi                                | 2         | 0.61%   |
| Biostar                              | 2         | 0.61%   |
| AZW                                  | 2         | 0.61%   |
| win element                          | 1         | 0.3%    |
| Vulcan Electronics                   | 1         | 0.3%    |
| Sun Microsystems                     | 1         | 0.3%    |
| SIRAGON                              | 1         | 0.3%    |
| Shenzhen Wangang Technology          | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.3%    |
| SANTECH                              | 1         | 0.3%    |
| RTD Embedded Technologies            | 1         | 0.3%    |
| Notebook                             | 1         | 0.3%    |
| MP                                   | 1         | 0.3%    |
| Linx                                 | 1         | 0.3%    |
| HUAWEI                               | 1         | 0.3%    |
| Huanan                               | 1         | 0.3%    |
| Google                               | 1         | 0.3%    |
| GEO                                  | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 8         | 2.44%   |
| ASUS All Series                              | 7         | 2.13%   |
| MSI MS-7C91                                  | 2         | 0.61%   |
| HP ProBook 450 G1                            | 2         | 0.61%   |
| HP Pavilion Laptop 15-eh1xxx                 | 2         | 0.61%   |
| HP Laptop 17-ak0xx                           | 2         | 0.61%   |
| Gigabyte GA-MA785GM-US2H                     | 2         | 0.61%   |
| Dell OptiPlex 9020                           | 2         | 0.61%   |
| Dell OptiPlex 755                            | 2         | 0.61%   |
| Chuwi GemiBook Pro                           | 2         | 0.61%   |
| AZW SER                                      | 2         | 0.61%   |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.61%   |
| Apple Macmini8,1                             | 2         | 0.61%   |
| Apple MacBookAir7,2                          | 2         | 0.61%   |
| Acer Nitro AN515-55                          | 2         | 0.61%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.3%    |
| win element MoreFine S500+                   | 1         | 0.3%    |
| Vulcan Excursion XB                          | 1         | 0.3%    |
| TUXEDO N7x0WU                                | 1         | 0.3%    |
| TUXEDO InfinityBook Pro Gen7 (MK1)           | 1         | 0.3%    |
| Toshiba Satellite M70                        | 1         | 0.3%    |
| Toshiba Satellite L650                       | 1         | 0.3%    |
| Toshiba Satellite C845                       | 1         | 0.3%    |
| Toshiba PORTEGE Z30-C                        | 1         | 0.3%    |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.3%    |
| Sony VPCYB3V1E                               | 1         | 0.3%    |
| Sony VPCSB1V9R                               | 1         | 0.3%    |
| Sony VPCF119FX                               | 1         | 0.3%    |
| Sony VPCEH2N1E                               | 1         | 0.3%    |
| Sony VPCEC3S1E                               | 1         | 0.3%    |
| Sony VPCCB32FD                               | 1         | 0.3%    |
| Sony VGN-TZ3RXN_B                            | 1         | 0.3%    |
| Sony SVE1513Q1ESI                            | 1         | 0.3%    |
| SIRAGON AIO-5150                             | 1         | 0.3%    |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment UM450   | 1         | 0.3%    |
| SANTECH X170KM-G                             | 1         | 0.3%    |
| Samsung NC210/NC110                          | 1         | 0.3%    |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.3%    |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 22        | 6.71%   |
| Acer Aspire              | 9         | 2.74%   |
| Dell OptiPlex            | 8         | 2.44%   |
| Unknown                  | 8         | 2.44%   |
| HP ProBook               | 7         | 2.13%   |
| HP EliteBook             | 7         | 2.13%   |
| Dell Latitude            | 7         | 2.13%   |
| ASUS All                 | 7         | 2.13%   |
| Lenovo IdeaPad           | 6         | 1.83%   |
| HP Compaq                | 6         | 1.83%   |
| Dell Inspiron            | 6         | 1.83%   |
| HP Laptop                | 5         | 1.52%   |
| ASUS VivoBook            | 5         | 1.52%   |
| ASUS ROG                 | 5         | 1.52%   |
| HP Pavilion              | 4         | 1.22%   |
| ASUS TUF                 | 4         | 1.22%   |
| Toshiba Satellite        | 3         | 0.91%   |
| Dell Vostro              | 3         | 0.91%   |
| Dell Precision           | 3         | 0.91%   |
| Acer Nitro               | 3         | 0.91%   |
| MSI MS-7C91              | 2         | 0.61%   |
| Microsoft Surface        | 2         | 0.61%   |
| Lenovo Yoga              | 2         | 0.61%   |
| Lenovo ThinkCentre       | 2         | 0.61%   |
| Lenovo ThinkBook         | 2         | 0.61%   |
| Lenovo IdeaCentre        | 2         | 0.61%   |
| HP ZBook                 | 2         | 0.61%   |
| HP Spectre               | 2         | 0.61%   |
| HP ENVY                  | 2         | 0.61%   |
| HP 250                   | 2         | 0.61%   |
| Gigabyte GA-MA785GM-US2H | 2         | 0.61%   |
| Gigabyte B550M           | 2         | 0.61%   |
| Chuwi GemiBook           | 2         | 0.61%   |
| AZW SER                  | 2         | 0.61%   |
| ASUS P5GC-MX             | 2         | 0.61%   |
| ASUS ASUS                | 2         | 0.61%   |
| Apple Macmini8           | 2         | 0.61%   |
| Apple Macmini6           | 2         | 0.61%   |
| Apple MacBookPro11       | 2         | 0.61%   |
| Apple MacBookAir7        | 2         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 45        | 13.72%  |
| 2020    | 28        | 8.54%   |
| 2022    | 25        | 7.62%   |
| 2011    | 23        | 7.01%   |
| 2018    | 22        | 6.71%   |
| 2016    | 22        | 6.71%   |
| 2013    | 22        | 6.71%   |
| 2019    | 20        | 6.1%    |
| 2015    | 19        | 5.79%   |
| 2010    | 19        | 5.79%   |
| 2012    | 18        | 5.49%   |
| 2014    | 16        | 4.88%   |
| 2009    | 11        | 3.35%   |
| 2007    | 11        | 3.35%   |
| 2017    | 9         | 2.74%   |
| 2008    | 9         | 2.74%   |
| 2006    | 3         | 0.91%   |
| 2023    | 2         | 0.61%   |
| 2005    | 2         | 0.61%   |
| 2004    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 195       | 59.45%  |
| Desktop     | 103       | 31.4%   |
| Mini pc     | 11        | 3.35%   |
| Convertible | 8         | 2.44%   |
| All in one  | 6         | 1.83%   |
| Tablet      | 3         | 0.91%   |
| Server      | 2         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 325       | 99.09%  |
| Enabled  | 3         | 0.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 327       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 90        | 27.44%  |
| 8.01-16.0   | 69        | 21.04%  |
| 16.01-24.0  | 49        | 14.94%  |
| 3.01-4.0    | 41        | 12.5%   |
| 32.01-64.0  | 37        | 11.28%  |
| 1.01-2.0    | 17        | 5.18%   |
| 24.01-32.0  | 8         | 2.44%   |
| 2.01-3.0    | 8         | 2.44%   |
| 64.01-256.0 | 6         | 1.83%   |
| 0.51-1.0    | 3         | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 122       | 35.47%  |
| 2.01-3.0   | 101       | 29.36%  |
| 3.01-4.0   | 52        | 15.12%  |
| 4.01-8.0   | 38        | 11.05%  |
| 0.51-1.0   | 18        | 5.23%   |
| 8.01-16.0  | 10        | 2.91%   |
| 0.01-0.5   | 2         | 0.58%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 59.64%  |
| 2      | 70        | 21.08%  |
| 3      | 39        | 11.75%  |
| 4      | 12        | 3.61%   |
| 5      | 5         | 1.51%   |
| 8      | 4         | 1.2%    |
| 0      | 2         | 0.6%    |
| 9      | 1         | 0.3%    |
| 7      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 64.63%  |
| Yes       | 116       | 35.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 85.67%  |
| No        | 47        | 14.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 81.46%  |
| No        | 61        | 18.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 62.2%   |
| No        | 124       | 37.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 81        | 24.55%  |
| Germany      | 45        | 13.64%  |
| Italy        | 26        | 7.88%   |
| Canada       | 15        | 4.55%   |
| Russia       | 12        | 3.64%   |
| Australia    | 12        | 3.64%   |
| France       | 11        | 3.33%   |
| Poland       | 10        | 3.03%   |
| UK           | 7         | 2.12%   |
| Spain        | 7         | 2.12%   |
| India        | 7         | 2.12%   |
| Netherlands  | 6         | 1.82%   |
| Switzerland  | 5         | 1.52%   |
| Romania      | 5         | 1.52%   |
| Finland      | 5         | 1.52%   |
| Brazil       | 5         | 1.52%   |
| Argentina    | 5         | 1.52%   |
| Sweden       | 4         | 1.21%   |
| New Zealand  | 4         | 1.21%   |
| Indonesia    | 4         | 1.21%   |
| Turkey       | 3         | 0.91%   |
| Serbia       | 3         | 0.91%   |
| Belgium      | 3         | 0.91%   |
| Venezuela    | 2         | 0.61%   |
| South Africa | 2         | 0.61%   |
| Mexico       | 2         | 0.61%   |
| Hungary      | 2         | 0.61%   |
| Greece       | 2         | 0.61%   |
| Egypt        | 2         | 0.61%   |
| Czechia      | 2         | 0.61%   |
| Croatia      | 2         | 0.61%   |
| Colombia     | 2         | 0.61%   |
| Bulgaria     | 2         | 0.61%   |
| Bangladesh   | 2         | 0.61%   |
| Austria      | 2         | 0.61%   |
| Vietnam      | 1         | 0.3%    |
| Uzbekistan   | 1         | 0.3%    |
| Uruguay      | 1         | 0.3%    |
| Tunisia      | 1         | 0.3%    |
| Slovakia     | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 6         | 1.75%   |
| Berlin        | 6         | 1.75%   |
| Sydney        | 5         | 1.46%   |
| St Petersburg | 4         | 1.17%   |
| Rome          | 3         | 0.88%   |
| Milan         | 3         | 0.88%   |
| Mesquite      | 3         | 0.88%   |
| Melbourne     | 3         | 0.88%   |
| Cambridge     | 3         | 0.88%   |
| Amsterdam     | 3         | 0.88%   |
| Warsaw        | 2         | 0.58%   |
| Walled Lake   | 2         | 0.58%   |
| Vienna        | 2         | 0.58%   |
| Vasco da Gama | 2         | 0.58%   |
| Toronto       | 2         | 0.58%   |
| Portland      | 2         | 0.58%   |
| Perth         | 2         | 0.58%   |
| Otwock        | 2         | 0.58%   |
| Orange        | 2         | 0.58%   |
| Oakland       | 2         | 0.58%   |
| New York      | 2         | 0.58%   |
| Montreal      | 2         | 0.58%   |
| Krakow        | 2         | 0.58%   |
| Istanbul      | 2         | 0.58%   |
| Houston       | 2         | 0.58%   |
| Helsinki      | 2         | 0.58%   |
| Florence      | 2         | 0.58%   |
| Ettingen      | 2         | 0.58%   |
| Doesburg      | 2         | 0.58%   |
| Dhaka         | 2         | 0.58%   |
| Córdoba      | 2         | 0.58%   |
| Catania       | 2         | 0.58%   |
| Casale Litta  | 2         | 0.58%   |
| Canberra      | 2         | 0.58%   |
| Cairo         | 2         | 0.58%   |
| Buffalo       | 2         | 0.58%   |
| Budapest      | 2         | 0.58%   |
| Belgrade      | 2         | 0.58%   |
| Alma          | 2         | 0.58%   |
| Zurich        | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 82        | 119    | 16.27%  |
| WDC                 | 67        | 75     | 13.29%  |
| Seagate             | 58        | 82     | 11.51%  |
| Kingston            | 38        | 41     | 7.54%   |
| Unknown             | 24        | 28     | 4.76%   |
| SanDisk             | 24        | 27     | 4.76%   |
| Crucial             | 24        | 42     | 4.76%   |
| Toshiba             | 22        | 23     | 4.37%   |
| SK hynix            | 15        | 16     | 2.98%   |
| Hitachi             | 12        | 15     | 2.38%   |
| China               | 11        | 12     | 2.18%   |
| Intel               | 10        | 12     | 1.98%   |
| Apple               | 10        | 14     | 1.98%   |
| PNY                 | 6         | 7      | 1.19%   |
| Micron Technology   | 6         | 6      | 1.19%   |
| HGST                | 6         | 6      | 1.19%   |
| Transcend           | 5         | 5      | 0.99%   |
| SPCC                | 5         | 5      | 0.99%   |
| LITEON              | 5         | 5      | 0.99%   |
| KIOXIA              | 5         | 7      | 0.99%   |
| Corsair             | 5         | 5      | 0.99%   |
| Netac               | 4         | 4      | 0.79%   |
| Unknown             | 4         | 4      | 0.79%   |
| Team                | 3         | 3      | 0.6%    |
| Silicon Motion      | 3         | 3      | 0.6%    |
| Phison              | 3         | 4      | 0.6%    |
| OCZ                 | 3         | 3      | 0.6%    |
| Dogfish             | 3         | 3      | 0.6%    |
| Apacer              | 3         | 3      | 0.6%    |
| GOODRAM             | 2         | 2      | 0.4%    |
| EYOTA               | 2         | 2      | 0.4%    |
| External            | 2         | 2      | 0.4%    |
| A-DATA Technology   | 2         | 2      | 0.4%    |
| Vaseky              | 1         | 1      | 0.2%    |
| USB                 | 1         | 1      | 0.2%    |
| UMIS                | 1         | 1      | 0.2%    |
| Teclast             | 1         | 1      | 0.2%    |
| SWORDBILL           | 1         | 2      | 0.2%    |
| SABRENT             | 1         | 1      | 0.2%    |
| Rogueware           | 1         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD        | 9         | 1.63%   |
| Samsung SSD 980 PRO 1TB                | 6         | 1.09%   |
| Samsung SSD 970 EVO Plus 1TB           | 6         | 1.09%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.09%   |
| Samsung SSD 850 EVO 250GB              | 6         | 1.09%   |
| Kingston SV300S37A240G 240GB SSD       | 5         | 0.91%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.72%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.72%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.72%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.72%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.72%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.72%   |
| Unknown                                | 4         | 0.72%   |
| Unknown SD32G  32GB                    | 3         | 0.54%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.54%   |
| Seagate ST3500413AS 500GB              | 3         | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB         | 3         | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.54%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.54%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 0.54%   |
| Samsung SSD 970 PRO 512GB              | 3         | 0.54%   |
| Samsung SSD 870 EVO 500GB              | 3         | 0.54%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.54%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.54%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.54%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.54%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.36%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 2         | 0.36%   |
| WDC WD3200AAKS-75B3A0 320GB            | 2         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.36%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.36%   |
| Unknown SDW32G  32GB                   | 2         | 0.36%   |
| Unknown SD/MMC/MS PRO 250GB            | 2         | 0.36%   |
| Unknown SD/MMC 2GB                     | 2         | 0.36%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 2         | 0.36%   |
| Unknown DA4064  64GB                   | 2         | 0.36%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.36%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.36%   |
| Toshiba HDWD110 1TB                    | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 82     | 37.91%  |
| WDC                 | 48        | 55     | 31.37%  |
| Toshiba             | 16        | 17     | 10.46%  |
| Hitachi             | 12        | 15     | 7.84%   |
| Samsung Electronics | 6         | 6      | 3.92%   |
| HGST                | 6         | 6      | 3.92%   |
| Unknown             | 2         | 2      | 1.31%   |
| Maxtor              | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |
| External            | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 60     | 22.55%  |
| Kingston            | 27        | 29     | 13.24%  |
| Crucial             | 20        | 36     | 9.8%    |
| SanDisk             | 16        | 18     | 7.84%   |
| China               | 11        | 12     | 5.39%   |
| Apple               | 7         | 10     | 3.43%   |
| WDC                 | 6         | 6      | 2.94%   |
| Transcend           | 5         | 5      | 2.45%   |
| SPCC                | 5         | 5      | 2.45%   |
| PNY                 | 5         | 5      | 2.45%   |
| Netac               | 4         | 4      | 1.96%   |
| LITEON              | 4         | 4      | 1.96%   |
| SK hynix            | 3         | 3      | 1.47%   |
| OCZ                 | 3         | 3      | 1.47%   |
| Intel               | 3         | 3      | 1.47%   |
| Dogfish             | 3         | 3      | 1.47%   |
| Toshiba             | 2         | 2      | 0.98%   |
| Team                | 2         | 2      | 0.98%   |
| Micron Technology   | 2         | 2      | 0.98%   |
| GOODRAM             | 2         | 2      | 0.98%   |
| EYOTA               | 2         | 2      | 0.98%   |
| Apacer              | 2         | 2      | 0.98%   |
| A-DATA Technology   | 2         | 2      | 0.98%   |
| Unknown             | 2         | 2      | 0.98%   |
| Vaseky              | 1         | 1      | 0.49%   |
| Teclast             | 1         | 1      | 0.49%   |
| SWORDBILL           | 1         | 2      | 0.49%   |
| Rogueware           | 1         | 2      | 0.49%   |
| RENICE              | 1         | 1      | 0.49%   |
| Patriot             | 1         | 1      | 0.49%   |
| Mushkin             | 1         | 1      | 0.49%   |
| MMY                 | 1         | 1      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |
| Indilinx            | 1         | 1      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| Gigabyte Technology | 1         | 1      | 0.49%   |
| GeIL                | 1         | 1      | 0.49%   |
| External            | 1         | 1      | 0.49%   |
| CT500MX5            | 1         | 1      | 0.49%   |
| CT1000P3            | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 169       | 244    | 37.56%  |
| HDD     | 134       | 188    | 29.78%  |
| NVMe    | 120       | 154    | 26.67%  |
| MMC     | 22        | 26     | 4.89%   |
| Unknown | 5         | 7      | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 235       | 413    | 59.64%  |
| NVMe | 120       | 153    | 30.46%  |
| MMC  | 22        | 26     | 5.58%   |
| SAS  | 17        | 27     | 4.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 193       | 273    | 63.07%  |
| 0.51-1.0   | 76        | 103    | 24.84%  |
| 1.01-2.0   | 22        | 28     | 7.19%   |
| 3.01-4.0   | 5         | 5      | 1.63%   |
| 4.01-10.0  | 5         | 17     | 1.63%   |
| 2.01-3.0   | 4         | 5      | 1.31%   |
| 10.01-20.0 | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 26.79%  |
| 251-500        | 74        | 22.02%  |
| 501-1000       | 43        | 12.8%   |
| 21-50          | 32        | 9.52%   |
| 51-100         | 32        | 9.52%   |
| 1001-2000      | 21        | 6.25%   |
| 1-20           | 17        | 5.06%   |
| More than 3000 | 14        | 4.17%   |
| 2001-3000      | 13        | 3.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 137       | 39.94%  |
| 21-50          | 56        | 16.33%  |
| 101-250        | 43        | 12.54%  |
| 51-100         | 43        | 12.54%  |
| 251-500        | 23        | 6.71%   |
| 501-1000       | 17        | 4.96%   |
| 1001-2000      | 14        | 4.08%   |
| More than 3000 | 7         | 2.04%   |
| 2001-3000      | 3         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 3.13%   |
| China SSD 512GB                              | 2         | 2      | 3.13%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 1.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.56%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 1.56%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 1.56%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.56%   |
| WDC WD3200AAKS-00UU3A0 320GB                 | 1         | 1      | 1.56%   |
| WDC WD3200AAJS-00B4A0 320GB                  | 1         | 1      | 1.56%   |
| WDC WD2500AAJS-00B4A0 250GB                  | 1         | 1      | 1.56%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 1.56%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 1.56%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 1.56%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.56%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD        | 1         | 1      | 1.56%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 1.56%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 1.56%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 1.56%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 1.56%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.56%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 1.56%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 1.56%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 1.56%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 1.56%   |
| Seagate ST3320418AS 320GB                    | 1         | 1      | 1.56%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 1.56%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 1.56%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.56%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 1.56%   |
| Seagate ST1000VM002-1CT162 1TB               | 1         | 1      | 1.56%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 2      | 1.56%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 1.56%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 20     | 30.16%  |
| WDC                 | 11        | 11     | 17.46%  |
| Samsung Electronics | 7         | 10     | 11.11%  |
| Hitachi             | 5         | 6      | 7.94%   |
| HGST                | 4         | 4      | 6.35%   |
| Toshiba             | 3         | 3      | 4.76%   |
| SK hynix            | 2         | 2      | 3.17%   |
| Kingston            | 2         | 2      | 3.17%   |
| China               | 2         | 2      | 3.17%   |
| RENICE              | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Maxtor              | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| Intel               | 1         | 2      | 1.59%   |
| Indilinx            | 1         | 1      | 1.59%   |
| GOODRAM             | 1         | 1      | 1.59%   |
| Crucial             | 1         | 6      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 20     | 45.24%  |
| WDC                 | 10        | 10     | 23.81%  |
| Hitachi             | 5         | 6      | 11.9%   |
| HGST                | 4         | 4      | 9.52%   |
| Toshiba             | 2         | 2      | 4.76%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| Maxtor              | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 44     | 67.21%  |
| SSD  | 18        | 27     | 29.51%  |
| NVMe | 2         | 3      | 3.28%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 275       | 480    | 71.43%  |
| Malfunc  | 61        | 74     | 15.84%  |
| Detected | 49        | 65     | 12.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 219       | 51.77%  |
| AMD                          | 50        | 11.82%  |
| Samsung Electronics          | 43        | 10.17%  |
| SanDisk                      | 19        | 4.49%   |
| SK hynix                     | 11        | 2.6%    |
| Phison Electronics           | 11        | 2.6%    |
| Kingston Technology Company  | 11        | 2.6%    |
| ASMedia Technology           | 9         | 2.13%   |
| Nvidia                       | 7         | 1.65%   |
| KIOXIA                       | 7         | 1.65%   |
| Micron/Crucial Technology    | 6         | 1.42%   |
| Marvell Technology Group     | 5         | 1.18%   |
| Silicon Motion               | 4         | 0.95%   |
| Micron Technology            | 4         | 0.95%   |
| VIA Technologies             | 2         | 0.47%   |
| Toshiba America Info Systems | 2         | 0.47%   |
| Silicon Image                | 2         | 0.47%   |
| Broadcom / LSI               | 2         | 0.47%   |
| Apple                        | 2         | 0.47%   |
| Union Memory (Shenzhen)      | 1         | 0.24%   |
| ULi Electronics              | 1         | 0.24%   |
| Shenzhen Longsys Electronics | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.24%   |
| LSI Logic / Symbios Logic    | 1         | 0.24%   |
| Lite-On Technology           | 1         | 0.24%   |
| JMicron Technology           | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 6.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 3.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 3.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 3.15%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 2.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.47%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.05%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.05%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 0.84%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 4         | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 241       | 56.97%  |
| NVMe | 118       | 27.9%   |
| IDE  | 42        | 9.93%   |
| RAID | 20        | 4.73%   |
| SCSI | 2         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 257       | 78.35%  |
| AMD    | 71        | 21.65%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 2.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 1.52%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 1.52%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 1.22%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 4         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 0.91%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 0.91%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3         | 0.91%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 3         | 0.91%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 3         | 0.91%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 0.91%   |
| Intel 12th Gen Core i7-12700H           | 3         | 0.91%   |
| Intel 12th Gen Core i5-1235U            | 3         | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 0.91%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 3         | 0.91%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 3         | 0.91%   |
| Intel Core i7-8700B CPU @ 3.20GHz       | 2         | 0.61%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 0.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 2         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.61%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.61%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.61%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 2         | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 2         | 0.61%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.61%   |
| Intel Core i5-3350P CPU @ 3.10GHz       | 2         | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 18.29%  |
| Intel Core i7           | 56        | 17.07%  |
| Other                   | 33        | 10.06%  |
| Intel Core i3           | 33        | 10.06%  |
| Intel Celeron           | 22        | 6.71%   |
| AMD Ryzen 5             | 22        | 6.71%   |
| AMD Ryzen 7             | 19        | 5.79%   |
| Intel Core 2 Duo        | 16        | 4.88%   |
| Intel Atom              | 10        | 3.05%   |
| Intel Xeon              | 5         | 1.52%   |
| Intel Pentium           | 4         | 1.22%   |
| AMD Ryzen 9             | 4         | 1.22%   |
| AMD Ryzen 3             | 4         | 1.22%   |
| Intel Pentium Dual-Core | 3         | 0.91%   |
| AMD Athlon II X4        | 3         | 0.91%   |
| Intel Pentium Silver    | 2         | 0.61%   |
| Intel Pentium M         | 2         | 0.61%   |
| Intel Pentium Dual      | 2         | 0.61%   |
| Intel Pentium 4         | 2         | 0.61%   |
| Intel Genuine           | 2         | 0.61%   |
| Intel Core i9           | 2         | 0.61%   |
| Intel Core 2            | 2         | 0.61%   |
| AMD Phenom II X4        | 2         | 0.61%   |
| AMD Phenom              | 2         | 0.61%   |
| Intel Pentium Gold      | 1         | 0.3%    |
| Intel Core M            | 1         | 0.3%    |
| AMD Turion 64 X2 Mobile | 1         | 0.3%    |
| AMD Sempron             | 1         | 0.3%    |
| AMD Ryzen Threadripper  | 1         | 0.3%    |
| AMD Ryzen 5 PRO         | 1         | 0.3%    |
| AMD Phenom II           | 1         | 0.3%    |
| AMD FX                  | 1         | 0.3%    |
| AMD E2                  | 1         | 0.3%    |
| AMD E1                  | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |
| AMD Athlon              | 1         | 0.3%    |
| AMD A8                  | 1         | 0.3%    |
| AMD A6                  | 1         | 0.3%    |
| AMD A12                 | 1         | 0.3%    |
| AMD A10                 | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 124       | 37.8%   |
| 4      | 112       | 34.15%  |
| 6      | 33        | 10.06%  |
| 8      | 29        | 8.84%   |
| 1      | 10        | 3.05%   |
| 12     | 8         | 2.44%   |
| 10     | 6         | 1.83%   |
| 14     | 3         | 0.91%   |
| 16     | 1         | 0.3%    |
| 5      | 1         | 0.3%    |
| 3      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 325       | 99.09%  |
| 2      | 3         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 209       | 63.72%  |
| 1      | 119       | 36.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 323       | 98.48%  |
| 32-bit         | 5         | 1.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 8.73%   |
| 0x206a7    | 22        | 6.63%   |
| 0x306a9    | 21        | 6.33%   |
| 0x306c3    | 18        | 5.42%   |
| 0x806c1    | 12        | 3.61%   |
| 0x1067a    | 12        | 3.61%   |
| 0x406e3    | 11        | 3.31%   |
| 0x0a50000c | 11        | 3.31%   |
| 0x506e3    | 9         | 2.71%   |
| 0x20655    | 8         | 2.41%   |
| 0x906ea    | 7         | 2.11%   |
| 0x706a8    | 7         | 2.11%   |
| 0x906a3    | 6         | 1.81%   |
| 0x806ec    | 6         | 1.81%   |
| 0x806e9    | 6         | 1.81%   |
| 0x30678    | 6         | 1.81%   |
| 0x08608103 | 6         | 1.81%   |
| 0x906ed    | 5         | 1.51%   |
| 0x906a4    | 5         | 1.51%   |
| 0x806ea    | 5         | 1.51%   |
| 0x6fd      | 5         | 1.51%   |
| 0x306d4    | 5         | 1.51%   |
| 0xa0652    | 4         | 1.2%    |
| 0x406c4    | 4         | 1.2%    |
| 0x40651    | 4         | 1.2%    |
| 0x106e5    | 4         | 1.2%    |
| 0x08108109 | 4         | 1.2%    |
| 0xa0653    | 3         | 0.9%    |
| 0x906e9    | 3         | 0.9%    |
| 0x906c0    | 3         | 0.9%    |
| 0x706a1    | 3         | 0.9%    |
| 0x0a50000d | 3         | 0.9%    |
| 0x08701021 | 3         | 0.9%    |
| 0x08600106 | 3         | 0.9%    |
| 0x0800820d | 3         | 0.9%    |
| 0x010000db | 3         | 0.9%    |
| 0xa0671    | 2         | 0.6%    |
| 0x806d1    | 2         | 0.6%    |
| 0x506c9    | 2         | 0.6%    |
| 0x306f2    | 2         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 10.64%  |
| Haswell          | 29        | 8.81%   |
| SandyBridge      | 24        | 7.29%   |
| Skylake          | 22        | 6.69%   |
| IvyBridge        | 22        | 6.69%   |
| Zen 3            | 20        | 6.08%   |
| Unknown          | 20        | 6.08%   |
| Penryn           | 16        | 4.86%   |
| TigerLake        | 13        | 3.95%   |
| Zen+             | 11        | 3.34%   |
| Westmere         | 11        | 3.34%   |
| Silvermont       | 11        | 3.34%   |
| Goldmont plus    | 10        | 3.04%   |
| Core             | 9         | 2.74%   |
| Zen 2            | 8         | 2.43%   |
| K10              | 8         | 2.43%   |
| CometLake        | 8         | 2.43%   |
| Nehalem          | 6         | 1.82%   |
| IceLake          | 6         | 1.82%   |
| Broadwell        | 6         | 1.82%   |
| Alderlake Hybrid | 6         | 1.82%   |
| Zen              | 3         | 0.91%   |
| Tremont          | 3         | 0.91%   |
| P6               | 3         | 0.91%   |
| Goldmont         | 3         | 0.91%   |
| Excavator        | 3         | 0.91%   |
| Bonnell          | 3         | 0.91%   |
| Puma             | 2         | 0.61%   |
| Piledriver       | 2         | 0.61%   |
| NetBurst         | 2         | 0.61%   |
| K8 Hammer        | 2         | 0.61%   |
| K8 & K10 hybrid  | 1         | 0.3%    |
| Bobcat           | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 206       | 53.09%  |
| Nvidia                     | 94        | 24.23%  |
| AMD                        | 87        | 22.42%  |
| Matrox Electronics Systems | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 3.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 2.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2%      |
| Intel HD Graphics 530                                                                    | 7         | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.75%   |
| AMD Lucienne                                                                             | 7         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.25%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1%      |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1%      |
| Intel HD Graphics 620                                                                    | 4         | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1%      |
| AMD Renoir                                                                               | 4         | 1%      |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.75%   |
| Intel HD Graphics 500                                                                    | 3         | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 155       | 47.11%  |
| 1 x AMD        | 64        | 19.45%  |
| 1 x Nvidia     | 52        | 15.81%  |
| Intel + Nvidia | 32        | 9.73%   |
| Intel + AMD    | 11        | 3.34%   |
| AMD + Nvidia   | 9         | 2.74%   |
| 2 x AMD        | 4         | 1.22%   |
| 2 x Intel      | 1         | 0.3%    |
| 1 x Matrox     | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 268       | 80.48%  |
| Proprietary | 45        | 13.51%  |
| Unknown     | 20        | 6.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 63.25%  |
| 0.01-0.5   | 36        | 10.84%  |
| 1.01-2.0   | 24        | 7.23%   |
| 3.01-4.0   | 21        | 6.33%   |
| 0.51-1.0   | 17        | 5.12%   |
| 7.01-8.0   | 15        | 4.52%   |
| 8.01-16.0  | 6         | 1.81%   |
| 2.01-3.0   | 3         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 12.07%  |
| Chimei Innolux          | 39        | 11.21%  |
| Samsung Electronics     | 37        | 10.63%  |
| BOE                     | 24        | 6.9%    |
| LG Display              | 20        | 5.75%   |
| Dell                    | 17        | 4.89%   |
| Hewlett-Packard         | 15        | 4.31%   |
| Acer                    | 13        | 3.74%   |
| Goldstar                | 12        | 3.45%   |
| Apple                   | 12        | 3.45%   |
| Sony                    | 9         | 2.59%   |
| Lenovo                  | 9         | 2.59%   |
| Chi Mei Optoelectronics | 9         | 2.59%   |
| Ancor Communications    | 9         | 2.59%   |
| PANDA                   | 8         | 2.3%    |
| AOC                     | 7         | 2.01%   |
| Sharp                   | 4         | 1.15%   |
| Philips                 | 4         | 1.15%   |
| Fujitsu Siemens         | 4         | 1.15%   |
| Eizo                    | 4         | 1.15%   |
| BenQ                    | 4         | 1.15%   |
| Medion                  | 3         | 0.86%   |
| Iiyama                  | 3         | 0.86%   |
| ASUSTek Computer        | 3         | 0.86%   |
| ViewSonic               | 2         | 0.57%   |
| Panasonic               | 2         | 0.57%   |
| NEC Computers           | 2         | 0.57%   |
| MSI                     | 2         | 0.57%   |
| MiTAC                   | 2         | 0.57%   |
| InfoVision              | 2         | 0.57%   |
| HannStar                | 2         | 0.57%   |
| CPT                     | 2         | 0.57%   |
| Xiaomi                  | 1         | 0.29%   |
| Vizio                   | 1         | 0.29%   |
| Vestel Elektronik       | 1         | 0.29%   |
| TMX                     | 1         | 0.29%   |
| Sunplus                 | 1         | 0.29%   |
| STA                     | 1         | 0.29%   |
| Sangyo                  | 1         | 0.29%   |
| SAC                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.13%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.85%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch                | 2         | 0.56%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.56%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.56%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                          | 2         | 0.56%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.56%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 2         | 0.56%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.56%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.56%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.56%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.56%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                       | 1         | 0.28%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.28%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 1         | 0.28%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 1         | 0.28%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.28%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.28%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.28%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                       | 1         | 0.28%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                     | 1         | 0.28%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                       | 1         | 0.28%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.28%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.28%   |
| Sony CPD-200SX SNY0570 1920x1080 698x392mm 31.5-inch                     | 1         | 0.28%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.28%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.28%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 146       | 43.58%  |
| 1366x768 (WXGA)    | 60        | 17.91%  |
| 3840x2160 (4K)     | 26        | 7.76%   |
| 1680x1050 (WSXGA+) | 14        | 4.18%   |
| 2560x1440 (QHD)    | 13        | 3.88%   |
| 1280x1024 (SXGA)   | 12        | 3.58%   |
| 1600x900 (HD+)     | 9         | 2.69%   |
| 1280x800 (WXGA)    | 9         | 2.69%   |
| 1440x900 (WXGA+)   | 7         | 2.09%   |
| 1920x1200 (WUXGA)  | 6         | 1.79%   |
| 2880x1800          | 3         | 0.9%    |
| 2560x1600          | 3         | 0.9%    |
| 2560x1080          | 3         | 0.9%    |
| 2160x1440          | 3         | 0.9%    |
| 1360x768           | 3         | 0.9%    |
| 3440x1440          | 2         | 0.6%    |
| 2256x1504          | 2         | 0.6%    |
| 1280x720 (HD)      | 2         | 0.6%    |
| 1024x768 (XGA)     | 2         | 0.6%    |
| 1024x600           | 2         | 0.6%    |
| Unknown            | 2         | 0.6%    |
| 3840x2400          | 1         | 0.3%    |
| 3840x1080          | 1         | 0.3%    |
| 3200x2000          | 1         | 0.3%    |
| 3200x1800 (QHD+)   | 1         | 0.3%    |
| 2736x1824          | 1         | 0.3%    |
| 1400x1050          | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 93        | 26.96%  |
| 13      | 29        | 8.41%   |
| 23      | 26        | 7.54%   |
| 24      | 24        | 6.96%   |
| 27      | 23        | 6.67%   |
| 17      | 22        | 6.38%   |
| 14      | 19        | 5.51%   |
| 21      | 15        | 4.35%   |
| 11      | 12        | 3.48%   |
| Unknown | 11        | 3.19%   |
| 22      | 10        | 2.9%    |
| 31      | 9         | 2.61%   |
| 19      | 8         | 2.32%   |
| 12      | 6         | 1.74%   |
| 34      | 5         | 1.45%   |
| 18      | 4         | 1.16%   |
| 16      | 4         | 1.16%   |
| 10      | 4         | 1.16%   |
| 84      | 3         | 0.87%   |
| 40      | 3         | 0.87%   |
| 65      | 2         | 0.58%   |
| 26      | 2         | 0.58%   |
| 20      | 2         | 0.58%   |
| 61      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 47      | 1         | 0.29%   |
| 46      | 1         | 0.29%   |
| 43      | 1         | 0.29%   |
| 42      | 1         | 0.29%   |
| 36      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 25      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 38.3%   |
| 501-600     | 71        | 20.76%  |
| 201-300     | 37        | 10.82%  |
| 401-500     | 33        | 9.65%   |
| 351-400     | 28        | 8.19%   |
| Unknown     | 11        | 3.22%   |
| 601-700     | 10        | 2.92%   |
| 701-800     | 7         | 2.05%   |
| 1001-1500   | 6         | 1.75%   |
| 801-900     | 3         | 0.88%   |
| 1501-2000   | 3         | 0.88%   |
| 901-1000    | 2         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 241       | 75.31%  |
| 16/10   | 45        | 14.06%  |
| 5/4     | 12        | 3.75%   |
| Unknown | 7         | 2.19%   |
| 3/2     | 6         | 1.88%   |
| 21/9    | 5         | 1.56%   |
| 4/3     | 4         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 27.03%  |
| 201-250        | 61        | 17.73%  |
| 81-90          | 38        | 11.05%  |
| 301-350        | 24        | 6.98%   |
| 151-200        | 19        | 5.52%   |
| 121-130        | 18        | 5.23%   |
| 351-500        | 15        | 4.36%   |
| 51-60          | 12        | 3.49%   |
| Unknown        | 11        | 3.2%    |
| 71-80          | 10        | 2.91%   |
| 251-300        | 9         | 2.62%   |
| 501-1000       | 8         | 2.33%   |
| More than 1000 | 7         | 2.03%   |
| 141-150        | 6         | 1.74%   |
| 61-70          | 5         | 1.45%   |
| 41-50          | 4         | 1.16%   |
| 111-120        | 2         | 0.58%   |
| 91-100         | 2         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 122       | 36.42%  |
| 121-160       | 100       | 29.85%  |
| 101-120       | 67        | 20%     |
| 161-240       | 18        | 5.37%   |
| Unknown       | 11        | 3.28%   |
| More than 240 | 9         | 2.69%   |
| 1-50          | 8         | 2.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 264       | 79.04%  |
| 2     | 46        | 13.77%  |
| 0     | 19        | 5.69%   |
| 3     | 5         | 1.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 172       | 33.08%  |
| Intel                             | 157       | 30.19%  |
| Qualcomm Atheros                  | 52        | 10%     |
| Broadcom                          | 30        | 5.77%   |
| MediaTek                          | 17        | 3.27%   |
| Broadcom Limited                  | 12        | 2.31%   |
| TP-Link                           | 10        | 1.92%   |
| Ralink Technology                 | 7         | 1.35%   |
| Marvell Technology Group          | 7         | 1.35%   |
| Samsung Electronics               | 5         | 0.96%   |
| Ralink                            | 5         | 0.96%   |
| Nvidia                            | 5         | 0.96%   |
| Microsoft                         | 4         | 0.77%   |
| ASIX Electronics                  | 4         | 0.77%   |
| Qualcomm Atheros Communications   | 3         | 0.58%   |
| Motorola PCS                      | 3         | 0.58%   |
| AVM                               | 3         | 0.58%   |
| Xiaomi                            | 2         | 0.38%   |
| Sierra Wireless                   | 2         | 0.38%   |
| OPPO Electronics                  | 2         | 0.38%   |
| Linksys                           | 2         | 0.38%   |
| D-Link                            | 2         | 0.38%   |
| VIA Technologies                  | 1         | 0.19%   |
| Sweex                             | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| Mercucys                          | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| Foxconn / Hon Hai                 | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Edimax Technology                 | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Aquantia                          | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 18.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 2.48%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.98%   |
| Intel Wireless 8260                                               | 11        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.65%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.65%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.16%   |
| Intel Wireless 3165                                               | 7         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.99%   |
| Intel Wireless 8265 / 8275                                        | 6         | 0.99%   |
| Intel Wireless 7265                                               | 6         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.83%   |
| Intel Wireless 7260                                               | 5         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 0.66%   |
| Intel Wireless-AC 9260                                            | 4         | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 40.88%  |
| Realtek Semiconductor           | 53        | 17.91%  |
| Qualcomm Atheros                | 35        | 11.82%  |
| Broadcom                        | 20        | 6.76%   |
| MediaTek                        | 17        | 5.74%   |
| TP-Link                         | 9         | 3.04%   |
| Broadcom Limited                | 9         | 3.04%   |
| Ralink Technology               | 7         | 2.36%   |
| Ralink                          | 5         | 1.69%   |
| Qualcomm Atheros Communications | 3         | 1.01%   |
| AVM                             | 3         | 1.01%   |
| Sierra Wireless                 | 2         | 0.68%   |
| Microsoft                       | 2         | 0.68%   |
| Linksys                         | 2         | 0.68%   |
| D-Link                          | 2         | 0.68%   |
| Sweex                           | 1         | 0.34%   |
| NetGear                         | 1         | 0.34%   |
| Mercucys                        | 1         | 0.34%   |
| Marvell Technology Group        | 1         | 0.34%   |
| Edimax Technology               | 1         | 0.34%   |
| ASUSTek Computer                | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.39%   |
| Intel Wireless 8260                                                     | 11        | 3.72%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.36%   |
| Intel Wireless 3165                                                     | 7         | 2.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.03%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.03%   |
| Intel Wireless 7265                                                     | 6         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 1.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.69%   |
| Intel Wireless 7260                                                     | 5         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 1.35%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.01%   |
| Intel Wireless 3160                                                     | 3         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.01%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.01%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 147       | 49.66%  |
| Intel                    | 73        | 24.66%  |
| Qualcomm Atheros         | 22        | 7.43%   |
| Broadcom                 | 17        | 5.74%   |
| Marvell Technology Group | 6         | 2.03%   |
| Nvidia                   | 5         | 1.69%   |
| ASIX Electronics         | 4         | 1.35%   |
| Samsung Electronics      | 3         | 1.01%   |
| Broadcom Limited         | 3         | 1.01%   |
| Xiaomi                   | 2         | 0.68%   |
| OPPO Electronics         | 2         | 0.68%   |
| Motorola PCS             | 2         | 0.68%   |
| Microsoft                | 2         | 0.68%   |
| VIA Technologies         | 1         | 0.34%   |
| TP-Link                  | 1         | 0.34%   |
| Lenovo                   | 1         | 0.34%   |
| JMicron Technology       | 1         | 0.34%   |
| Foxconn / Hon Hai        | 1         | 0.34%   |
| Attansic Technology      | 1         | 0.34%   |
| Aquantia                 | 1         | 0.34%   |
| Apple                    | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 36.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 4.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 3.29%   |
| Intel Ethernet Controller I225-V                                  | 9         | 2.96%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.32%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.99%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.99%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.66%   |
| OPPO CPH2411                                                      | 2         | 0.66%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.66%   |
| Motorola PCS moto g(30)                                           | 2         | 0.66%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 2         | 0.66%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.66%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.66%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 280       | 50.54%  |
| WiFi     | 268       | 48.38%  |
| Modem    | 5         | 0.9%    |
| Unknown  | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 208       | 62.46%  |
| Ethernet | 125       | 37.54%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 185       | 56.23%  |
| 1     | 128       | 38.91%  |
| 3     | 8         | 2.43%   |
| 0     | 7         | 2.13%   |
| 4     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 239       | 72.21%  |
| Yes  | 92        | 27.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 42.86%  |
| Realtek Semiconductor           | 20        | 9.52%   |
| Qualcomm Atheros Communications | 16        | 7.62%   |
| Apple                           | 16        | 7.62%   |
| Cambridge Silicon Radio         | 12        | 5.71%   |
| Foxconn / Hon Hai               | 11        | 5.24%   |
| Broadcom                        | 10        | 4.76%   |
| IMC Networks                    | 8         | 3.81%   |
| Lite-On Technology              | 7         | 3.33%   |
| MediaTek                        | 6         | 2.86%   |
| Hewlett-Packard                 | 4         | 1.9%    |
| ASUSTek Computer                | 3         | 1.43%   |
| Ralink                          | 2         | 0.95%   |
| TP-Link                         | 1         | 0.48%   |
| Realtek                         | 1         | 0.48%   |
| Marvell Semiconductor           | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 16.67%  |
| Realtek Bluetooth Radio                                                             | 18        | 8.57%   |
| Intel AX201 Bluetooth                                                               | 16        | 7.62%   |
| Intel AX200 Bluetooth                                                               | 13        | 6.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 3.81%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 3.33%   |
| MediaTek Wireless_Device                                                            | 6         | 2.86%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.9%    |
| Intel Bluetooth Device                                                              | 4         | 1.9%    |
| IMC Networks Wireless_Device                                                        | 4         | 1.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.43%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.95%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.95%   |
| Lite-On Wireless_Device                                                             | 2         | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.95%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.95%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.48%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.48%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.48%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 242       | 53.07%  |
| AMD                        | 84        | 18.42%  |
| Nvidia                     | 76        | 16.67%  |
| C-Media Electronics        | 7         | 1.54%   |
| Creative Labs              | 5         | 1.1%    |
| VIA Technologies           | 3         | 0.66%   |
| Texas Instruments          | 3         | 0.66%   |
| JMTek                      | 3         | 0.66%   |
| ROCCAT                     | 2         | 0.44%   |
| Realtek Semiconductor      | 2         | 0.44%   |
| Generalplus Technology     | 2         | 0.44%   |
| BEHRINGER International    | 2         | 0.44%   |
| Apple                      | 2         | 0.44%   |
| TerraTec Electronic        | 1         | 0.22%   |
| Shenzhen Riitek Technology | 1         | 0.22%   |
| Setek Elektronik           | 1         | 0.22%   |
| Schiit Audio               | 1         | 0.22%   |
| Scarlett                   | 1         | 0.22%   |
| Razer USA                  | 1         | 0.22%   |
| Plantronics                | 1         | 0.22%   |
| Microsoft                  | 1         | 0.22%   |
| Logitech                   | 1         | 0.22%   |
| LG Electronics             | 1         | 0.22%   |
| Lenovo                     | 1         | 0.22%   |
| Kingston Technology        | 1         | 0.22%   |
| GYROCOM C&C                | 1         | 0.22%   |
| Guillemot                  | 1         | 0.22%   |
| GN Netcom                  | 1         | 0.22%   |
| FIFINE 683 Microphone      | 1         | 0.22%   |
| Ensoniq                    | 1         | 0.22%   |
| Digidesign                 | 1         | 0.22%   |
| Dell                       | 1         | 0.22%   |
| Creative Technology        | 1         | 0.22%   |
| Conexant Systems           | 1         | 0.22%   |
| CMX Systems                | 1         | 0.22%   |
| Cambridge Silicon Radio    | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 39        | 7.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 4.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 4.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 24        | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 3.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.93%   |
| Nvidia Audio device                                                        | 5         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.93%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4         | 0.75%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 81        | 20.98%  |
| SK hynix            | 64        | 16.58%  |
| Unknown             | 46        | 11.92%  |
| Kingston            | 37        | 9.59%   |
| Micron Technology   | 32        | 8.29%   |
| Crucial             | 22        | 5.7%    |
| Corsair             | 21        | 5.44%   |
| G.Skill             | 11        | 2.85%   |
| A-DATA Technology   | 11        | 2.85%   |
| Elpida              | 10        | 2.59%   |
| Ramaxel Technology  | 9         | 2.33%   |
| Unknown (ABCD)      | 8         | 2.07%   |
| Transcend           | 5         | 1.3%    |
| Unknown             | 5         | 1.3%    |
| Nanya Technology    | 4         | 1.04%   |
| Smart               | 2         | 0.52%   |
| Patriot             | 2         | 0.52%   |
| Avant               | 2         | 0.52%   |
| Wilk                | 1         | 0.26%   |
| Unknown (AB)        | 1         | 0.26%   |
| Unifosa             | 1         | 0.26%   |
| Team                | 1         | 0.26%   |
| PNY                 | 1         | 0.26%   |
| Lexar Co Limited    | 1         | 0.26%   |
| Innodisk            | 1         | 0.26%   |
| Hewlett-Packard     | 1         | 0.26%   |
| Golden Empire       | 1         | 0.26%   |
| Essencore           | 1         | 0.26%   |
| CSX                 | 1         | 0.26%   |
| ASint Technology    | 1         | 0.26%   |
| Apacer              | 1         | 0.26%   |
| 48spaces            | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 5         | 1.22%   |
| Unknown                                                          | 5         | 1.22%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.98%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.98%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 4         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 3         | 0.73%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.73%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s        | 3         | 0.73%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.49%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 2         | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.49%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.49%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.49%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 142       | 42.64%  |
| DDR3    | 123       | 36.94%  |
| DDR2    | 18        | 5.41%   |
| LPDDR4  | 16        | 4.8%    |
| SDRAM   | 10        | 3%      |
| Unknown | 7         | 2.1%    |
| LPDDR3  | 6         | 1.8%    |
| DDR     | 6         | 1.8%    |
| DDR5    | 4         | 1.2%    |
| DRAM    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 214       | 64.46%  |
| DIMM         | 98        | 29.52%  |
| Row Of Chips | 18        | 5.42%   |
| Chip         | 1         | 0.3%    |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 117       | 32.5%   |
| 4096  | 109       | 30.28%  |
| 2048  | 55        | 15.28%  |
| 16384 | 51        | 14.17%  |
| 1024  | 16        | 4.44%   |
| 32768 | 10        | 2.78%   |
| 512   | 1         | 0.28%   |
| 256   | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 69        | 19.49%  |
| 3200    | 62        | 17.51%  |
| 2667    | 38        | 10.73%  |
| 1333    | 31        | 8.76%   |
| 2400    | 25        | 7.06%   |
| Unknown | 15        | 4.24%   |
| 1334    | 13        | 3.67%   |
| 2133    | 12        | 3.39%   |
| 3600    | 11        | 3.11%   |
| 667     | 11        | 3.11%   |
| 1067    | 8         | 2.26%   |
| 1867    | 5         | 1.41%   |
| 800     | 5         | 1.41%   |
| 533     | 4         | 1.13%   |
| 4267    | 3         | 0.85%   |
| 4199    | 3         | 0.85%   |
| 2933    | 3         | 0.85%   |
| 2666    | 3         | 0.85%   |
| 6000    | 2         | 0.56%   |
| 3733    | 2         | 0.56%   |
| 3400    | 2         | 0.56%   |
| 3266    | 2         | 0.56%   |
| 2048    | 2         | 0.56%   |
| 1866    | 2         | 0.56%   |
| 1800    | 2         | 0.56%   |
| 975     | 2         | 0.56%   |
| 333     | 2         | 0.56%   |
| 8400    | 1         | 0.28%   |
| 5800    | 1         | 0.28%   |
| 4800    | 1         | 0.28%   |
| 4266    | 1         | 0.28%   |
| 4133    | 1         | 0.28%   |
| 3866    | 1         | 0.28%   |
| 3533    | 1         | 0.28%   |
| 3000    | 1         | 0.28%   |
| 2800    | 1         | 0.28%   |
| 2200    | 1         | 0.28%   |
| 2000    | 1         | 0.28%   |
| 1639    | 1         | 0.28%   |
| 1066    | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 4         | 36.36%  |
| Canon              | 4         | 36.36%  |
| Brother Industries | 3         | 27.27%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon MF641C             | 2         | 18.18%  |
| HP LaserJet P2055 series | 1         | 9.09%   |
| HP LaserJet 1022         | 1         | 9.09%   |
| HP ENVY 4500 series      | 1         | 9.09%   |
| HP Deskjet 1510          | 1         | 9.09%   |
| Canon MG5700 series      | 1         | 9.09%   |
| Canon LiDE 400           | 1         | 9.09%   |
| Brother MFC-7340         | 1         | 9.09%   |
| Brother HL-2150N series  | 1         | 9.09%   |
| Brother DCP-L2540DW      | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan LiDE 210       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 22.39%  |
| IMC Networks                           | 19        | 9.45%   |
| Microdia                               | 16        | 7.96%   |
| Realtek Semiconductor                  | 14        | 6.97%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.97%   |
| Quanta                                 | 11        | 5.47%   |
| Apple                                  | 10        | 4.98%   |
| Bison Electronics                      | 9         | 4.48%   |
| Logitech                               | 8         | 3.98%   |
| Acer                                   | 8         | 3.98%   |
| Sunplus Innovation Technology          | 7         | 3.48%   |
| Suyin                                  | 6         | 2.99%   |
| Luxvisions Innotech Limited            | 5         | 2.49%   |
| Lite-On Technology                     | 5         | 2.49%   |
| Ricoh                                  | 4         | 1.99%   |
| Microsoft                              | 3         | 1.49%   |
| Lenovo                                 | 3         | 1.49%   |
| Silicon Motion                         | 2         | 1%      |
| Hewlett-Packard                        | 2         | 1%      |
| Alcor Micro                            | 2         | 1%      |
| Z-Star Microelectronics                | 1         | 0.5%    |
| Y Media                                | 1         | 0.5%    |
| Sonix Technology                       | 1         | 0.5%    |
| Primax Electronics                     | 1         | 0.5%    |
| Novatek Microelectronics               | 1         | 0.5%    |
| LG Electronics                         | 1         | 0.5%    |
| Goodong Industry                       | 1         | 0.5%    |
| Generalplus Technology                 | 1         | 0.5%    |
| GEMBIRD                                | 1         | 0.5%    |
| Arkmicro Technologies                  | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 10        | 4.95%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 6         | 2.97%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.48%   |
| Quanta HD User Facing                                | 4         | 1.98%   |
| Apple Built-in iSight                                | 4         | 1.98%   |
| Realtek Integrated_Webcam_HD                         | 3         | 1.49%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.49%   |
| Logitech Webcam C930e                                | 3         | 1.49%   |
| IMC Networks Integrated Camera                       | 3         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.49%   |
| Chicony HD User Facing                               | 3         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 3         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 3         | 1.49%   |
| Bison Integrated Camera                              | 3         | 1.49%   |
| Apple FaceTime HD Camera (Built-in)                  | 3         | 1.49%   |
| Suyin Acer CrystalEye Webcam                         | 2         | 0.99%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.99%   |
| Sunplus HD 720P webcam                               | 2         | 0.99%   |
| Ricoh USB2.0 Camera                                  | 2         | 0.99%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 0.99%   |
| Realtek USB Camera                                   | 2         | 0.99%   |
| Microsoft LifeCam HD-3000                            | 2         | 0.99%   |
| Microdia Webcam Vitade AF                            | 2         | 0.99%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.99%   |
| Logitech Webcam C270                                 | 2         | 0.99%   |
| Lite-On HP HD Camera                                 | 2         | 0.99%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 0.99%   |
| IMC Networks XHC Camera                              | 2         | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.99%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 0.99%   |
| Chicony HP Wide Vision FHD Camera                    | 2         | 0.99%   |
| Chicony HD WebCam                                    | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 2         | 0.99%   |
| Bison BisonCam,NB Pro                                | 2         | 0.99%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 0.99%   |
| Acer Integrated Camera                               | 2         | 0.99%   |
| Acer HD Webcam                                       | 2         | 0.99%   |
| Z-Star Venus USB2.0 Camera                           | 1         | 0.5%    |
| Y Media USB Camera                                   | 1         | 0.5%    |
| Suyin Sony Visual Communication Camera               | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 11        | 27.5%   |
| Synaptics                          | 7         | 17.5%   |
| Shenzhen Goodix Technology         | 7         | 17.5%   |
| AuthenTec                          | 5         | 12.5%   |
| Elan Microelectronics              | 4         | 10%     |
| Upek                               | 3         | 7.5%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.5%    |
| Microsoft                          | 1         | 2.5%    |
| Focal-systems.Corp                 | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 5         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 10%     |
| AuthenTec AES2810                                               | 3         | 7.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5%      |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 5%      |
| Elan ELAN:Fingerprint                                           | 2         | 5%      |
| Elan ELAN:ARM-M4                                                | 2         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.5%    |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.5%    |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.5%    |
| Upek TCS5B Fingerprint sensor                                   | 1         | 2.5%    |
| Synaptics WBDI Fingerprint Reader USB 102                       | 1         | 2.5%    |
| Synaptics UWP WBDI Device                                       | 1         | 2.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 2.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.5%    |
| Microsoft Fingerprint Reader                                    | 1         | 2.5%    |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 2.5%    |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.5%    |
| Unknown                                                         | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 5         | 38.46%  |
| Advanced Card Systems | 2         | 15.38%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 38.46%  |
| Broadcom 5880                                  | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 7.69%   |
| Broadcom 58200                                 | 1         | 7.69%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 7.69%   |
| Advanced Card Systems ACR122U                  | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 227       | 67.76%  |
| 1     | 79        | 23.58%  |
| 2     | 25        | 7.46%   |
| 3     | 4         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 51        | 38.64%  |
| Fingerprint reader       | 40        | 30.3%   |
| Chipcard                 | 11        | 8.33%   |
| Net/wireless             | 9         | 6.82%   |
| Multimedia controller    | 5         | 3.79%   |
| Communication controller | 4         | 3.03%   |
| Unassigned class         | 3         | 2.27%   |
| Camera                   | 3         | 2.27%   |
| Net/ethernet             | 2         | 1.52%   |
| Sound                    | 1         | 0.76%   |
| Flash memory             | 1         | 0.76%   |
| Dvb card                 | 1         | 0.76%   |
| Bluetooth                | 1         | 0.76%   |

