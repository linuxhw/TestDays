Parrot 5.0 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_5.0/Desktop/README.md) and [notebooks](/Dist/Parrot_5.0/Notebook/README.md).

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

Total: 114

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cee28f4953](https://linux-hardware.org/?probe=cee28f4953) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64  | 38        | 44.19%  |
| 5.16.0-12parrot1-amd64 | 33        | 38.37%  |
| 5.15.0-15parrot1-amd64 | 7         | 8.14%   |
| 5.14.0-2parrot1-amd64  | 7         | 8.14%   |
| 5.15.0-5parrot1-amd64  | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 43        | 51.19%  |
| 5.16.0  | 33        | 39.29%  |
| 5.15.0  | 8         | 9.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 43        | 51.19%  |
| 5.16    | 33        | 39.29%  |
| 5.15    | 8         | 9.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 51        | 62.2%   |
| KDE5    | 24        | 29.27%  |
| Unknown | 3         | 3.66%   |
| XFCE    | 2         | 2.44%   |
| KDE     | 1         | 1.22%   |
| GNOME   | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 79        | 96.34%  |
| Wayland | 3         | 3.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 45        | 54.88%  |
| Unknown | 34        | 41.46%  |
| SDDM    | 2         | 2.44%   |
| GDM     | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 44        | 53.66%  |
| en_GB | 7         | 8.54%   |
| es_ES | 5         | 6.1%    |
| en_IN | 5         | 6.1%    |
| ru_RU | 3         | 3.66%   |
| pt_BR | 3         | 3.66%   |
| fr_FR | 3         | 3.66%   |
| en_AU | 2         | 2.44%   |
| de_DE | 2         | 2.44%   |
| cs_CZ | 2         | 2.44%   |
| pt_PT | 1         | 1.22%   |
| pl_PL | 1         | 1.22%   |
| es_PE | 1         | 1.22%   |
| es_MX | 1         | 1.22%   |
| en_ZA | 1         | 1.22%   |
| en_DK | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 49        | 59.76%  |
| EFI  | 33        | 40.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 69        | 84.15%  |
| Ext4    | 9         | 10.98%  |
| Overlay | 4         | 4.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 45.12%  |
| GPT     | 35        | 42.68%  |
| MBR     | 10        | 12.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 87.8%   |
| Yes       | 10        | 12.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 67.07%  |
| Yes       | 27        | 32.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 18.29%  |
| Hewlett-Packard     | 14        | 17.07%  |
| Dell                | 12        | 14.63%  |
| ASUSTek Computer    | 8         | 9.76%   |
| MSI                 | 7         | 8.54%   |
| Acer                | 4         | 4.88%   |
| Apple               | 3         | 3.66%   |
| Toshiba             | 2         | 2.44%   |
| Microsoft           | 2         | 2.44%   |
| HUAWEI              | 2         | 2.44%   |
| Gigabyte Technology | 2         | 2.44%   |
| SLIMBOOK            | 1         | 1.22%   |
| Samsung Electronics | 1         | 1.22%   |
| Razer               | 1         | 1.22%   |
| Metabox             | 1         | 1.22%   |
| Jumper              | 1         | 1.22%   |
| ECS                 | 1         | 1.22%   |
| Daewoo Lucoms       | 1         | 1.22%   |
| Chuwi               | 1         | 1.22%   |
| ASRock              | 1         | 1.22%   |
| Alienware           | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 3.66%   |
| HP ProDesk 600 G1 SFF                              | 2         | 2.44%   |
| HP Notebook                                        | 2         | 2.44%   |
| Dell Latitude E6410                                | 2         | 2.44%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 1.22%   |
| Toshiba Satellite C75D-B                           | 1         | 1.22%   |
| SLIMBOOK ONE-AMD-M4                                | 1         | 1.22%   |
| Samsung 550P5C/550P7C                              | 1         | 1.22%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.22%   |
| MSI MS-7A34                                        | 1         | 1.22%   |
| MSI MS-7529                                        | 1         | 1.22%   |
| MSI GE62 6QE                                       | 1         | 1.22%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 1.22%   |
| Microsoft Surface Pro 3                            | 1         | 1.22%   |
| Microsoft Surface Book                             | 1         | 1.22%   |
| Metabox Edge-Pro NS50MU                            | 1         | 1.22%   |
| Lenovo Yoga C930-13IKB 81C4                        | 1         | 1.22%   |
| Lenovo V330-15IKB 81AX                             | 1         | 1.22%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 1.22%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 1.22%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 1.22%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 1.22%   |
| Lenovo IdeaPad Y580                                | 1         | 1.22%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 1.22%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 1.22%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 1         | 1.22%   |
| Lenovo H535 10117                                  | 1         | 1.22%   |
| Lenovo H530 10130                                  | 1         | 1.22%   |
| Lenovo B50-80 80EW                                 | 1         | 1.22%   |
| Jumper EZbook                                      | 1         | 1.22%   |
| HUAWEI HVY-WXX9                                    | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X                                  | 1         | 1.22%   |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 1.22%   |
| HP ProBook 4535s                                   | 1         | 1.22%   |
| HP Pavilion x360 Convertible 14-ba0xx              | 1         | 1.22%   |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 1.22%   |
| HP Pavilion g7                                     | 1         | 1.22%   |
| HP Laptop 15q-dy0xxx                               | 1         | 1.22%   |
| HP ENVY x360 Convertible 13-bd0xxx                 | 1         | 1.22%   |
| HP EliteBook 8470p                                 | 1         | 1.22%   |
| HP EliteBook 840 G3                                | 1         | 1.22%   |
| HP Compaq 8200 Elite SFF PC                        | 1         | 1.22%   |
| Gigabyte B450M DS3H                                | 1         | 1.22%   |
| Gigabyte A320M-S2H                                 | 1         | 1.22%   |
| ECS GV460AA-ABA a6217c                             | 1         | 1.22%   |
| Dell OptiPlex 7010                                 | 1         | 1.22%   |
| Dell OptiPlex 3020                                 | 1         | 1.22%   |
| Dell Latitude XT2                                  | 1         | 1.22%   |
| Dell Latitude E7450                                | 1         | 1.22%   |
| Dell Latitude E6540                                | 1         | 1.22%   |
| Dell Latitude 7480                                 | 1         | 1.22%   |
| Dell Latitude 5400                                 | 1         | 1.22%   |
| Dell Inspiron N5110                                | 1         | 1.22%   |
| Dell Inspiron 5580                                 | 1         | 1.22%   |
| Dell Inspiron 5570                                 | 1         | 1.22%   |
| Daewoo Lucoms OEM                                  | 1         | 1.22%   |
| Chuwi GemiBook                                     | 1         | 1.22%   |
| ASUS X75VC                                         | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 7         | 8.54%   |
| Lenovo ThinkPad     | 5         | 6.1%    |
| Lenovo IdeaPad      | 4         | 4.88%   |
| MSI Modern          | 3         | 3.66%   |
| HP Pavilion         | 3         | 3.66%   |
| Dell Inspiron       | 3         | 3.66%   |
| Toshiba Satellite   | 2         | 2.44%   |
| Microsoft Surface   | 2         | 2.44%   |
| HP ProDesk          | 2         | 2.44%   |
| HP Notebook         | 2         | 2.44%   |
| HP EliteBook        | 2         | 2.44%   |
| Dell OptiPlex       | 2         | 2.44%   |
| ASUS ROG            | 2         | 2.44%   |
| Acer Nitro          | 2         | 2.44%   |
| SLIMBOOK ONE-AMD-M4 | 1         | 1.22%   |
| Samsung 550P5C      | 1         | 1.22%   |
| Razer Blade         | 1         | 1.22%   |
| MSI MS-7A34         | 1         | 1.22%   |
| MSI MS-7529         | 1         | 1.22%   |
| MSI GE62            | 1         | 1.22%   |
| MSI Creator         | 1         | 1.22%   |
| Metabox Edge-Pro    | 1         | 1.22%   |
| Lenovo Yoga         | 1         | 1.22%   |
| Lenovo V330-15IKB   | 1         | 1.22%   |
| Lenovo Legion       | 1         | 1.22%   |
| Lenovo H535         | 1         | 1.22%   |
| Lenovo H530         | 1         | 1.22%   |
| Lenovo B50-80       | 1         | 1.22%   |
| Jumper EZbook       | 1         | 1.22%   |
| HUAWEI HVY-WXX9     | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X   | 1         | 1.22%   |
| HP ZBook            | 1         | 1.22%   |
| HP ProBook          | 1         | 1.22%   |
| HP Laptop           | 1         | 1.22%   |
| HP ENVY             | 1         | 1.22%   |
| HP Compaq           | 1         | 1.22%   |
| Gigabyte B450M      | 1         | 1.22%   |
| Gigabyte A320M-S2H  | 1         | 1.22%   |
| ECS GV460AA-ABA     | 1         | 1.22%   |
| Daewoo Lucoms OEM   | 1         | 1.22%   |
| Chuwi GemiBook      | 1         | 1.22%   |
| ASUS X75VC          | 1         | 1.22%   |
| ASUS X540SAA        | 1         | 1.22%   |
| ASUS VivoBook       | 1         | 1.22%   |
| ASUS PRIME          | 1         | 1.22%   |
| ASUS H170M-E        | 1         | 1.22%   |
| ASUS Basic          | 1         | 1.22%   |
| ASRock Z87M         | 1         | 1.22%   |
| Apple MacBookPro15  | 1         | 1.22%   |
| Apple MacBookAir3   | 1         | 1.22%   |
| Apple MacBook7      | 1         | 1.22%   |
| Alienware M14xR1    | 1         | 1.22%   |
| Acer TravelMate     | 1         | 1.22%   |
| Acer Aspire         | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 14        | 17.07%  |
| 2017 | 9         | 10.98%  |
| 2013 | 8         | 9.76%   |
| 2018 | 7         | 8.54%   |
| 2020 | 6         | 7.32%   |
| 2019 | 6         | 7.32%   |
| 2011 | 6         | 7.32%   |
| 2016 | 5         | 6.1%    |
| 2012 | 5         | 6.1%    |
| 2010 | 5         | 6.1%    |
| 2015 | 3         | 3.66%   |
| 2014 | 3         | 3.66%   |
| 2009 | 2         | 2.44%   |
| 2007 | 2         | 2.44%   |
| 2022 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 57        | 69.51%  |
| Desktop     | 20        | 24.39%  |
| Convertible | 3         | 3.66%   |
| Tablet      | 2         | 2.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 26.51%  |
| 16.01-24.0  | 15        | 18.07%  |
| 32.01-64.0  | 13        | 15.66%  |
| 3.01-4.0    | 13        | 15.66%  |
| 8.01-16.0   | 13        | 15.66%  |
| 64.01-256.0 | 3         | 3.61%   |
| 24.01-32.0  | 2         | 2.41%   |
| 1.01-2.0    | 2         | 2.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 30        | 36.14%  |
| 1.01-2.0   | 23        | 27.71%  |
| 4.01-8.0   | 14        | 16.87%  |
| 3.01-4.0   | 10        | 12.05%  |
| 0.51-1.0   | 3         | 3.61%   |
| 8.01-16.0  | 2         | 2.41%   |
| 16.01-24.0 | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 57.32%  |
| 2      | 31        | 37.8%   |
| 3      | 2         | 2.44%   |
| 6      | 1         | 1.22%   |
| 5      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 74.39%  |
| Yes       | 21        | 25.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 78.05%  |
| No        | 18        | 21.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 93.9%   |
| No        | 5         | 6.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 70.73%  |
| No        | 24        | 29.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 29        | 34.52%  |
| Spain        | 5         | 5.95%   |
| India        | 5         | 5.95%   |
| UK           | 4         | 4.76%   |
| Mexico       | 4         | 4.76%   |
| Germany      | 4         | 4.76%   |
| Brazil       | 4         | 4.76%   |
| Netherlands  | 3         | 3.57%   |
| France       | 3         | 3.57%   |
| Denmark      | 3         | 3.57%   |
| South Africa | 2         | 2.38%   |
| Russia       | 2         | 2.38%   |
| Morocco      | 2         | 2.38%   |
| Czechia      | 2         | 2.38%   |
| Canada       | 2         | 2.38%   |
| Austria      | 2         | 2.38%   |
| Australia    | 2         | 2.38%   |
| Romania      | 1         | 1.19%   |
| Portugal     | 1         | 1.19%   |
| Peru         | 1         | 1.19%   |
| Georgia      | 1         | 1.19%   |
| Egypt        | 1         | 1.19%   |
| Algeria      | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 3.57%   |
| Vienna                 | 2         | 2.38%   |
| Tangier                | 2         | 2.38%   |
| Ruskin                 | 2         | 2.38%   |
| Camden                 | 2         | 2.38%   |
| Amsterdam              | 2         | 2.38%   |
| Viby J                 | 1         | 1.19%   |
| Vapi                   | 1         | 1.19%   |
| Uherské Hradiště    | 1         | 1.19%   |
| Ts'khinvali            | 1         | 1.19%   |
| Trivandrum             | 1         | 1.19%   |
| Sydney                 | 1         | 1.19%   |
| Sumaré                | 1         | 1.19%   |
| St Petersburg          | 1         | 1.19%   |
| Springfield            | 1         | 1.19%   |
| Spotsylvania           | 1         | 1.19%   |
| South Hamilton         | 1         | 1.19%   |
| Skive                  | 1         | 1.19%   |
| Sao Paulo              | 1         | 1.19%   |
| Sao Joao de Meriti     | 1         | 1.19%   |
| Santa Maria            | 1         | 1.19%   |
| Saint Paul             | 1         | 1.19%   |
| Pretoria               | 1         | 1.19%   |
| Prague                 | 1         | 1.19%   |
| Point Pleasant Beach   | 1         | 1.19%   |
| Pittsburgh             | 1         | 1.19%   |
| Phoenix                | 1         | 1.19%   |
| Pensacola              | 1         | 1.19%   |
| Orofino                | 1         | 1.19%   |
| Opelousas              | 1         | 1.19%   |
| Mt. Pleasant           | 1         | 1.19%   |
| Mostoles               | 1         | 1.19%   |
| Montreal               | 1         | 1.19%   |
| Montigny-le-Bretonneux | 1         | 1.19%   |
| Milton                 | 1         | 1.19%   |
| Mexicali               | 1         | 1.19%   |
| Melbourne              | 1         | 1.19%   |
| Mazatlán              | 1         | 1.19%   |
| Mangalagiri            | 1         | 1.19%   |
| Madrid                 | 1         | 1.19%   |
| Los Angeles            | 1         | 1.19%   |
| Lisbon                 | 1         | 1.19%   |
| Lille                  | 1         | 1.19%   |
| Leduc                  | 1         | 1.19%   |
| La Paz                 | 1         | 1.19%   |
| La Magdalena           | 1         | 1.19%   |
| Krasnogorsk            | 1         | 1.19%   |
| Islington              | 1         | 1.19%   |
| Iasi                   | 1         | 1.19%   |
| Houston                | 1         | 1.19%   |
| Herne                  | 1         | 1.19%   |
| Haßfurt               | 1         | 1.19%   |
| Grand Junction         | 1         | 1.19%   |
| Eugene                 | 1         | 1.19%   |
| Esplugues de Llobregat | 1         | 1.19%   |
| East China Township    | 1         | 1.19%   |
| Durban                 | 1         | 1.19%   |
| Dresden                | 1         | 1.19%   |
| Dillon                 | 1         | 1.19%   |
| Dickson                | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 25     | 16.52%  |
| Seagate             | 16        | 18     | 13.91%  |
| WDC                 | 14        | 17     | 12.17%  |
| Toshiba             | 12        | 12     | 10.43%  |
| Kingston            | 8         | 8      | 6.96%   |
| Sandisk             | 6         | 9      | 5.22%   |
| Unknown             | 3         | 4      | 2.61%   |
| Hitachi             | 3         | 4      | 2.61%   |
| China               | 3         | 4      | 2.61%   |
| SK Hynix            | 2         | 2      | 1.74%   |
| PNY                 | 2         | 2      | 1.74%   |
| Micron Technology   | 2         | 2      | 1.74%   |
| Intel               | 2         | 4      | 1.74%   |
| HGST                | 2         | 2      | 1.74%   |
| Crucial             | 2         | 2      | 1.74%   |
| Apple               | 2         | 2      | 1.74%   |
| A-DATA Technology   | 2         | 2      | 1.74%   |
| YMTC                | 1         | 1      | 0.87%   |
| Team                | 1         | 1      | 0.87%   |
| SPCC                | 1         | 1      | 0.87%   |
| Silicon Motion      | 1         | 1      | 0.87%   |
| S3+                 | 1         | 1      | 0.87%   |
| PLEXTOR             | 1         | 1      | 0.87%   |
| Phison              | 1         | 1      | 0.87%   |
| Netac               | 1         | 1      | 0.87%   |
| LITEON              | 1         | 1      | 0.87%   |
| KingSpec            | 1         | 1      | 0.87%   |
| KingFast            | 1         | 2      | 0.87%   |
| Intenso             | 1         | 2      | 0.87%   |
| HUAWEI              | 1         | 1      | 0.87%   |
| BHT                 | 1         | 1      | 0.87%   |
| ASMedia             | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                | 3         | 2.34%   |
| Kingston NVMe SSD Drive 512GB         | 3         | 2.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 2         | 1.56%   |
| Unknown MMC Card  32GB                | 2         | 1.56%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.56%   |
| Toshiba DT01ACA200 2TB                | 2         | 1.56%   |
| Seagate ST250DM000-1BD141 250GB       | 2         | 1.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 2         | 1.56%   |
| Sandisk NVMe SSD Drive 1TB            | 2         | 1.56%   |
| Samsung SSD 970 EVO Plus 1TB          | 2         | 1.56%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.56%   |
| YMTC PC005 512GB                      | 1         | 0.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.78%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.78%   |
| WDC WDBRPG5000ANC-WRSN 500GB          | 1         | 0.78%   |
| WDC WDBNCE2500PNC 250GB SSD           | 1         | 0.78%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.78%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 0.78%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 0.78%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.78%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 0.78%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 0.78%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 0.78%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 0.78%   |
| WDC PC SN720 SDAPNTW-512G-1101 512GB  | 1         | 0.78%   |
| Unknown SD  128GB                     | 1         | 0.78%   |
| Unknown ISOCOM  64GB                  | 1         | 0.78%   |
| Toshiba MQ01ACF050 500GB              | 1         | 0.78%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.78%   |
| Toshiba MK2533GSGF 250GB              | 1         | 0.78%   |
| Toshiba HDWD105 500GB                 | 1         | 0.78%   |
| Toshiba DT01ACA050 500GB              | 1         | 0.78%   |
| Team TM8PS7512G 512GB SSD             | 1         | 0.78%   |
| SPCC Solid State Disk 240GB           | 1         | 0.78%   |
| SK Hynix NVMe SSD Drive 1024GB        | 1         | 0.78%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB SSD | 1         | 0.78%   |
| Silicon Motion NVMe SSD Drive 128GB   | 1         | 0.78%   |
| Seagate ST9500325AS 500GB             | 1         | 0.78%   |
| Seagate ST9250315AS 250GB             | 1         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.78%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.78%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 0.78%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 0.78%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 0.78%   |
| Seagate ST3500312CS 500GB             | 1         | 0.78%   |
| Seagate ST31000528AS 1TB              | 1         | 0.78%   |
| Seagate ST2000NM0011 2TB              | 1         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 0.78%   |
| Seagate ST1000DM003-1SB10C 1TB        | 1         | 0.78%   |
| Seagate BUP Slim SL 1TB               | 1         | 0.78%   |
| Seagate BUP Slim BK 1TB               | 1         | 0.78%   |
| SanDisk SDSSDH3 2T00 2TB              | 1         | 0.78%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1         | 0.78%   |
| Sandisk NVMe SSD Drive 256GB          | 1         | 0.78%   |
| Sandisk NVMe SSD Drive 250GB          | 1         | 0.78%   |
| Sandisk NVMe SSD Drive 1024GB         | 1         | 0.78%   |
| Samsung SSD 980 1TB                   | 1         | 0.78%   |
| Samsung SSD 860 EVO 500GB             | 1         | 0.78%   |
| Samsung SSD 860 EVO 250GB             | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 37.21%  |
| Toshiba             | 12        | 12     | 27.91%  |
| WDC                 | 7         | 9      | 16.28%  |
| Hitachi             | 3         | 4      | 6.98%   |
| Samsung Electronics | 2         | 2      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| ASMedia             | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 18.42%  |
| WDC                 | 6         | 6      | 15.79%  |
| Kingston            | 4         | 4      | 10.53%  |
| China               | 3         | 4      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| PNY                 | 2         | 2      | 5.26%   |
| Crucial             | 2         | 2      | 5.26%   |
| Team                | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| SK Hynix            | 1         | 1      | 2.63%   |
| S3+                 | 1         | 1      | 2.63%   |
| PLEXTOR             | 1         | 1      | 2.63%   |
| Netac               | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| KingFast            | 1         | 1      | 2.63%   |
| Intenso             | 1         | 2      | 2.63%   |
| BHT                 | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 48     | 34.91%  |
| SSD     | 36        | 43     | 33.96%  |
| NVMe    | 28        | 39     | 26.42%  |
| MMC     | 3         | 4      | 2.83%   |
| Unknown | 2         | 2      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 89     | 62.77%  |
| NVMe | 28        | 39     | 29.79%  |
| SAS  | 4         | 4      | 4.26%   |
| MMC  | 3         | 4      | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 58     | 58.9%   |
| 0.51-1.0   | 23        | 25     | 31.51%  |
| 1.01-2.0   | 7         | 8      | 9.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 28.05%  |
| 501-1000   | 16        | 19.51%  |
| 1001-2000  | 13        | 15.85%  |
| 251-500    | 11        | 13.41%  |
| Unknown    | 9         | 10.98%  |
| 2001-3000  | 3         | 3.66%   |
| 1-20       | 3         | 3.66%   |
| 21-50      | 2         | 2.44%   |
| 51-100     | 2         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 29        | 34.52%  |
| 51-100    | 13        | 15.48%  |
| 1-20      | 10        | 11.9%   |
| 101-250   | 9         | 10.71%  |
| Unknown   | 9         | 10.71%  |
| 251-500   | 8         | 9.52%   |
| 501-1000  | 5         | 5.95%   |
| 1001-2000 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD2003FZEX-00Z4SA0 2TB         | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB          | 1         | 1      | 11.11%  |
| Seagate ST250DM000-1BD141 250GB    | 1         | 1      | 11.11%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 11.11%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1         | 1      | 11.11%  |
| Samsung Electronics HM500JI 500GB  | 1         | 1      | 11.11%  |
| PLEXTOR PX-512M6Pro 512GB SSD      | 1         | 1      | 11.11%  |
| A-DATA Technology SX7000NP 128GB   | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 37.5%   |
| WDC                 | 1         | 1      | 12.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| PLEXTOR             | 1         | 1      | 12.5%   |
| A-DATA Technology   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 60%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 46        | 60     | 49.46%  |
| Detected | 42        | 66     | 45.16%  |
| Malfunc  | 4         | 9      | 4.3%    |
| Failed   | 1         | 1      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 53.06%  |
| AMD                         | 14        | 14.29%  |
| Samsung Electronics         | 11        | 11.22%  |
| Sandisk                     | 6         | 6.12%   |
| Kingston Technology Company | 4         | 4.08%   |
| Nvidia                      | 3         | 3.06%   |
| Micron Technology           | 2         | 2.04%   |
| Yangtze Memory Technologies | 1         | 1.02%   |
| SK Hynix                    | 1         | 1.02%   |
| Silicon Motion              | 1         | 1.02%   |
| Phison Electronics          | 1         | 1.02%   |
| Apple                       | 1         | 1.02%   |
| ADATA Technology            | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 12.5%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 4.46%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 4         | 3.57%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 4         | 3.57%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.68%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 2.68%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 2.68%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.79%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.79%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.79%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.89%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.89%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.89%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.89%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.89%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.89%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.89%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.89%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.89%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.89%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.89%   |
| Intel SSD 600P Series                                                            | 1         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.89%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.89%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.89%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.89%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 1         | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 0.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.89%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.89%   |
| AMD FCH SATA Controller D                                                        | 1         | 0.89%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 0.89%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 48.98%  |
| NVMe | 28        | 28.57%  |
| RAID | 11        | 11.22%  |
| IDE  | 11        | 11.22%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 74.39%  |
| AMD    | 21        | 25.61%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 3.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 2.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 2.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.44%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.44%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 1.22%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 1.22%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.22%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 1.22%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 1         | 1.22%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 1.22%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 1.22%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.22%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.22%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.22%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.22%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 1.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-4670S CPU @ 3.10GHz             | 1         | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.22%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 1.22%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1         | 1.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.22%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz          | 1         | 1.22%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.22%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.22%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.22%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.22%   |
| Intel 12th Gen Core i9-12900H                 | 1         | 1.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.22%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.22%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 19        | 23.17%  |
| Intel Core i7      | 17        | 20.73%  |
| Intel Core i3      | 7         | 8.54%   |
| AMD Ryzen 7        | 7         | 8.54%   |
| Other              | 5         | 6.1%    |
| Intel Core 2 Duo   | 5         | 6.1%    |
| AMD Ryzen 5        | 5         | 6.1%    |
| Intel Pentium      | 4         | 4.88%   |
| Intel Celeron      | 3         | 3.66%   |
| AMD A6             | 2         | 2.44%   |
| Intel Xeon         | 1         | 1.22%   |
| Intel Pentium Dual | 1         | 1.22%   |
| AMD Ryzen 9        | 1         | 1.22%   |
| AMD Ryzen 3        | 1         | 1.22%   |
| AMD E2             | 1         | 1.22%   |
| AMD Athlon 64 X2   | 1         | 1.22%   |
| AMD A8             | 1         | 1.22%   |
| AMD A4             | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 45.12%  |
| 4      | 30        | 36.59%  |
| 8      | 7         | 8.54%   |
| 6      | 6         | 7.32%   |
| 14     | 1         | 1.22%   |
| 12     | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 69.51%  |
| 1      | 25        | 30.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 48.78%  |
| 0x806e9    | 6         | 7.32%   |
| 0x206a7    | 3         | 3.66%   |
| 0x1067a    | 3         | 3.66%   |
| 0xa0652    | 2         | 2.44%   |
| 0x806ea    | 2         | 2.44%   |
| 0x406e3    | 2         | 2.44%   |
| 0x306c3    | 2         | 2.44%   |
| 0x306a9    | 2         | 2.44%   |
| 0x08001138 | 2         | 2.44%   |
| 0x07030105 | 2         | 2.44%   |
| 0x906ed    | 1         | 1.22%   |
| 0x906ea    | 1         | 1.22%   |
| 0x906a3    | 1         | 1.22%   |
| 0x806ec    | 1         | 1.22%   |
| 0x806eb    | 1         | 1.22%   |
| 0x806d1    | 1         | 1.22%   |
| 0x806c1    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x706a8    | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x40651    | 1         | 1.22%   |
| 0x08701021 | 1         | 1.22%   |
| 0x08600106 | 1         | 1.22%   |
| 0x08108109 | 1         | 1.22%   |
| 0x06001119 | 1         | 1.22%   |
| 0x03000027 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 23.17%  |
| Haswell          | 8         | 9.76%   |
| SandyBridge      | 5         | 6.1%    |
| Penryn           | 5         | 6.1%    |
| IvyBridge        | 5         | 6.1%    |
| Unknown          | 4         | 4.88%   |
| Zen 2            | 3         | 3.66%   |
| Zen              | 3         | 3.66%   |
| Skylake          | 3         | 3.66%   |
| Zen+             | 2         | 2.44%   |
| Zen 3            | 2         | 2.44%   |
| Westmere         | 2         | 2.44%   |
| TigerLake        | 2         | 2.44%   |
| Silvermont       | 2         | 2.44%   |
| Puma             | 2         | 2.44%   |
| Icelake          | 2         | 2.44%   |
| Excavator        | 2         | 2.44%   |
| CometLake        | 2         | 2.44%   |
| Broadwell        | 2         | 2.44%   |
| Piledriver       | 1         | 1.22%   |
| K8 Hammer        | 1         | 1.22%   |
| K10 Llano        | 1         | 1.22%   |
| Goldmont plus    | 1         | 1.22%   |
| Goldmont         | 1         | 1.22%   |
| Core             | 1         | 1.22%   |
| Alderlake Hybrid | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 56        | 53.33%  |
| AMD    | 27        | 25.71%  |
| Nvidia | 22        | 20.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 5         | 4.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.67%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.74%   |
| AMD Lucienne                                                                             | 4         | 3.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.8%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.87%   |
| AMD Renoir                                                                               | 2         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.87%   |
| AMD Cezanne                                                                              | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.93%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.93%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 0.93%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.93%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.93%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.93%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.93%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 0.93%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 0.93%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 0.93%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.93%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.93%   |
| Intel HD Graphics 630                                                                    | 1         | 0.93%   |
| Intel HD Graphics 530                                                                    | 1         | 0.93%   |
| Intel HD Graphics 500                                                                    | 1         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.93%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 42.68%  |
| 1 x AMD        | 19        | 23.17%  |
| Intel + Nvidia | 12        | 14.63%  |
| 1 x Nvidia     | 8         | 9.76%   |
| Intel + AMD    | 5         | 6.1%    |
| AMD + Nvidia   | 2         | 2.44%   |
| 2 x AMD        | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 75        | 90.36%  |
| Proprietary | 6         | 7.23%   |
| Unknown     | 2         | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 73.49%  |
| 1.01-2.0   | 7         | 8.43%   |
| 3.01-4.0   | 5         | 6.02%   |
| 0.01-0.5   | 5         | 6.02%   |
| 0.51-1.0   | 4         | 4.82%   |
| 7.01-8.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 19.54%  |
| BOE                     | 12        | 13.79%  |
| LG Display              | 11        | 12.64%  |
| Samsung Electronics     | 7         | 8.05%   |
| Chimei Innolux          | 7         | 8.05%   |
| Goldstar                | 3         | 3.45%   |
| Chi Mei Optoelectronics | 3         | 3.45%   |
| Apple                   | 3         | 3.45%   |
| Acer                    | 3         | 3.45%   |
| Lenovo                  | 2         | 2.3%    |
| Dell                    | 2         | 2.3%    |
| AOC                     | 2         | 2.3%    |
| Vizio                   | 1         | 1.15%   |
| Unknown (AAA)           | 1         | 1.15%   |
| Unknown                 | 1         | 1.15%   |
| Toshiba                 | 1         | 1.15%   |
| STD                     | 1         | 1.15%   |
| Philips                 | 1         | 1.15%   |
| PANDA                   | 1         | 1.15%   |
| Panasonic               | 1         | 1.15%   |
| ONN                     | 1         | 1.15%   |
| NEC Computers           | 1         | 1.15%   |
| Kogan                   | 1         | 1.15%   |
| InfoVision              | 1         | 1.15%   |
| CSO                     | 1         | 1.15%   |
| BenQ                    | 1         | 1.15%   |
| Ativa                   | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 3.41%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch                | 1         | 1.14%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                    | 1         | 1.14%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 1.14%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                         | 1         | 1.14%   |
| STD Monitor STD0001 1920x1080                                            | 1         | 1.14%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch     | 1         | 1.14%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch      | 1         | 1.14%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.14%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 1.14%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 1.14%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.14%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 1.14%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 1.14%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD0574 1920x1080 309x175mm 14.0-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 1.14%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.14%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 1.14%   |
| Lenovo L200pwD LEN1156 1680x1050 433x271mm 20.1-inch                     | 1         | 1.14%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 1.14%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 1.14%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch             | 1         | 1.14%   |
| Goldstar TV GSM0002 1920x1080 1150x650mm 52.0-inch                       | 1         | 1.14%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.14%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                     | 1         | 1.14%   |
| Dell P2412H DELA07D 1920x1080 531x299mm 24.0-inch                        | 1         | 1.14%   |
| Dell LCD Monitor P2417H                                                  | 1         | 1.14%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.14%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 1.14%   |
| BOE LCD Monitor BOE0A1C 1920x1080 344x194mm 15.5-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE07E8 1366x768 309x173mm 13.9-inch                     | 1         | 1.14%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 1.14%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.14%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 45.24%  |
| 1366x768 (WXGA)    | 18        | 21.43%  |
| 1600x900 (HD+)     | 6         | 7.14%   |
| 3840x2160 (4K)     | 4         | 4.76%   |
| 1680x1050 (WSXGA+) | 4         | 4.76%   |
| 1280x800 (WXGA)    | 4         | 4.76%   |
| 2160x1440          | 2         | 2.38%   |
| 3840x1080          | 1         | 1.19%   |
| 2880x1800          | 1         | 1.19%   |
| 2560x1600          | 1         | 1.19%   |
| 2560x1440 (QHD)    | 1         | 1.19%   |
| 1920x1200 (WUXGA)  | 1         | 1.19%   |
| 1440x900 (WXGA+)   | 1         | 1.19%   |
| 1280x1024 (SXGA)   | 1         | 1.19%   |
| Unknown            | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 30.23%  |
| 14      | 11        | 12.79%  |
| 13      | 9         | 10.47%  |
| 17      | 8         | 9.3%    |
| 27      | 6         | 6.98%   |
| 24      | 4         | 4.65%   |
| 22      | 3         | 3.49%   |
| 21      | 3         | 3.49%   |
| 12      | 3         | 3.49%   |
| 23      | 2         | 2.33%   |
| 16      | 2         | 2.33%   |
| Unknown | 2         | 2.33%   |
| 52      | 1         | 1.16%   |
| 41      | 1         | 1.16%   |
| 40      | 1         | 1.16%   |
| 32      | 1         | 1.16%   |
| 31      | 1         | 1.16%   |
| 20      | 1         | 1.16%   |
| 11      | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 52.94%  |
| 501-600     | 11        | 12.94%  |
| 351-400     | 8         | 9.41%   |
| 401-500     | 7         | 8.24%   |
| 201-300     | 7         | 8.24%   |
| Unknown     | 2         | 2.35%   |
| 801-900     | 1         | 1.18%   |
| 701-800     | 1         | 1.18%   |
| 601-700     | 1         | 1.18%   |
| 1001-1500   | 1         | 1.18%   |
| 901-1000    | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 63        | 80.77%  |
| 16/10   | 11        | 14.1%   |
| Unknown | 2         | 2.56%   |
| 5/4     | 1         | 1.28%   |
| 3/2     | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 31.4%   |
| 81-90          | 17        | 19.77%  |
| 201-250        | 9         | 10.47%  |
| 301-350        | 6         | 6.98%   |
| 121-130        | 6         | 6.98%   |
| 71-80          | 3         | 3.49%   |
| 61-70          | 3         | 3.49%   |
| 351-500        | 2         | 2.33%   |
| 251-300        | 2         | 2.33%   |
| 151-200        | 2         | 2.33%   |
| 501-1000       | 2         | 2.33%   |
| Unknown        | 2         | 2.33%   |
| More than 1000 | 1         | 1.16%   |
| 51-60          | 1         | 1.16%   |
| 141-150        | 1         | 1.16%   |
| 131-140        | 1         | 1.16%   |
| 111-120        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 33.33%  |
| 101-120       | 26        | 30.95%  |
| 51-100        | 18        | 21.43%  |
| 161-240       | 5         | 5.95%   |
| More than 240 | 3         | 3.57%   |
| 1-50          | 2         | 2.38%   |
| Unknown       | 2         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 68        | 81.93%  |
| 2     | 11        | 13.25%  |
| 0     | 3         | 3.61%   |
| 3     | 1         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 47        | 33.1%   |
| Intel                           | 42        | 29.58%  |
| Qualcomm Atheros                | 13        | 9.15%   |
| Broadcom                        | 7         | 4.93%   |
| MEDIATEK                        | 5         | 3.52%   |
| TP-Link                         | 3         | 2.11%   |
| Samsung Electronics             | 2         | 1.41%   |
| Ralink Technology               | 2         | 1.41%   |
| Qualcomm Atheros Communications | 2         | 1.41%   |
| Nvidia                          | 2         | 1.41%   |
| Marvell Technology Group        | 2         | 1.41%   |
| ASUSTek Computer                | 2         | 1.41%   |
| vivo                            | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| OnePlus Technology (Shenzhen)   | 1         | 0.7%    |
| NetGear                         | 1         | 0.7%    |
| Microsoft                       | 1         | 0.7%    |
| Linksys                         | 1         | 0.7%    |
| ICS Advent                      | 1         | 0.7%    |
| Huawei Technologies             | 1         | 0.7%    |
| Gemtek                          | 1         | 0.7%    |
| D-Link System                   | 1         | 0.7%    |
| Broadcom Limited                | 1         | 0.7%    |
| ASIX Electronics                | 1         | 0.7%    |
| Apple                           | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 23        | 13.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 5.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 5         | 2.96%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 2.37%   |
| Intel Wireless 3165                                                     | 4         | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.78%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.78%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.78%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.78%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.78%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.78%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 1.18%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 1.18%   |
| Intel Wireless 3160                                                     | 2         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.18%   |
| vivo 1806                                                               | 1         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.59%   |
| OnePlus (Shenzhen) EB2103                                               | 1         | 0.59%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 0.59%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.59%   |
| NetGear A6210                                                           | 1         | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.59%   |
| MediaTek SP514                                                          | 1         | 0.59%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.59%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 36.84%  |
| Realtek Semiconductor           | 23        | 24.21%  |
| Qualcomm Atheros                | 9         | 9.47%   |
| Broadcom                        | 6         | 6.32%   |
| MEDIATEK                        | 4         | 4.21%   |
| TP-Link                         | 3         | 3.16%   |
| Ralink Technology               | 2         | 2.11%   |
| Qualcomm Atheros Communications | 2         | 2.11%   |
| Marvell Technology Group        | 2         | 2.11%   |
| ASUSTek Computer                | 2         | 2.11%   |
| Ralink                          | 1         | 1.05%   |
| NetGear                         | 1         | 1.05%   |
| Microsoft                       | 1         | 1.05%   |
| Linksys                         | 1         | 1.05%   |
| Gemtek                          | 1         | 1.05%   |
| D-Link System                   | 1         | 1.05%   |
| Broadcom Limited                | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 5         | 5.26%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 4.21%   |
| Intel Wireless 3165                                                     | 4         | 4.21%   |
| Realtek 802.11ac NIC                                                    | 3         | 3.16%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 3.16%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.16%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.16%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 3.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 2.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.11%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 2.11%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 2.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 2.11%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 2.11%   |
| Intel Wireless 3160                                                     | 2         | 2.11%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.11%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| NetGear A6210                                                           | 1         | 1.05%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.05%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.05%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.05%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.05%   |
| Intel Wireless 8260                                                     | 1         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.05%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.05%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.05%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.05%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 1         | 1.05%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 1.05%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 1.05%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.05%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1         | 1.05%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 52.86%  |
| Intel                 | 18        | 25.71%  |
| Qualcomm Atheros      | 4         | 5.71%   |
| Samsung Electronics   | 2         | 2.86%   |
| Nvidia                | 2         | 2.86%   |
| Broadcom              | 2         | 2.86%   |
| vivo                  | 1         | 1.43%   |
| MediaTek              | 1         | 1.43%   |
| ICS Advent            | 1         | 1.43%   |
| ASIX Electronics      | 1         | 1.43%   |
| Apple                 | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 31.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.78%   |
| vivo 1806                                                         | 1         | 1.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.39%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.39%   |
| MediaTek SP514                                                    | 1         | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.39%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 1.39%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.39%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.39%   |
| Apple T2 Controller                                               | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 54.23%  |
| Ethernet | 63        | 44.37%  |
| Modem    | 1         | 0.7%    |
| Unknown  | 1         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 73.17%  |
| Ethernet | 22        | 26.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 56.1%   |
| 1     | 35        | 42.68%  |
| 3     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 74.39%  |
| Yes  | 21        | 25.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 48.28%  |
| Realtek Semiconductor           | 6         | 10.34%  |
| Qualcomm Atheros Communications | 4         | 6.9%    |
| MediaTek                        | 3         | 5.17%   |
| Toshiba                         | 2         | 3.45%   |
| Marvell Semiconductor           | 2         | 3.45%   |
| Lite-On Technology              | 2         | 3.45%   |
| IMC Networks                    | 2         | 3.45%   |
| Broadcom                        | 2         | 3.45%   |
| Apple                           | 2         | 3.45%   |
| Realtek                         | 1         | 1.72%   |
| Ralink                          | 1         | 1.72%   |
| Foxconn / Hon Hai               | 1         | 1.72%   |
| Dell                            | 1         | 1.72%   |
| Cambridge Silicon Radio         | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 18.97%  |
| Intel AX201 Bluetooth                               | 6         | 10.34%  |
| Realtek Bluetooth Radio                             | 4         | 6.9%    |
| MediaTek Wireless_Device                            | 3         | 5.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.17%   |
| Intel AX200 Bluetooth                               | 3         | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.45%   |
| Toshiba BCM43142A0                                  | 1         | 1.72%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.72%   |
| Realtek Bluetooth Radio                             | 1         | 1.72%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.72%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.72%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.72%   |
| Lite-On Wireless_Device                             | 1         | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.72%   |
| Intel Bluetooth Device                              | 1         | 1.72%   |
| Intel AX210 Bluetooth                               | 1         | 1.72%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.72%   |
| IMC Networks Bluetooth Device                       | 1         | 1.72%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.72%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.72%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.72%   |
| Broadcom BCM20702A0                                 | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |
| Apple Bluetooth Host Controller                     | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 58        | 56.86%  |
| AMD                    | 24        | 23.53%  |
| Nvidia                 | 16        | 15.69%  |
| SteelSeries ApS        | 1         | 0.98%   |
| Generalplus Technology | 1         | 0.98%   |
| C-Media Electronics    | 1         | 0.98%   |
| Apple                  | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 9.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 7.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 5.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.1%    |
| AMD FCH Azalia Controller                                                                         | 4         | 3.1%    |
| Nvidia Audio device                                                                               | 3         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.55%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.55%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.55%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.55%   |
| SteelSeries ApS SteelSeries GameDAC                                                               | 1         | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.78%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.78%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.78%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.78%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.78%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 0.78%   |
| Apple Audio Device                                                                                | 1         | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.78%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 27.12%  |
| SK Hynix            | 9         | 15.25%  |
| Micron Technology   | 9         | 15.25%  |
| Crucial             | 7         | 11.86%  |
| Unknown             | 5         | 8.47%   |
| Kingston            | 4         | 6.78%   |
| Unknown (ABCD)      | 2         | 3.39%   |
| Ramaxel Technology  | 2         | 3.39%   |
| Elpida              | 2         | 3.39%   |
| Silicon Power       | 1         | 1.69%   |
| G.Skill             | 1         | 1.69%   |
| A-DATA Technology   | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 3.28%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2         | 3.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 3.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 3.28%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 3.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 1.64%   |
| Unknown RAM Module 2GB DIMM                                    | 1         | 1.64%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.64%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 1.64%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM                         | 1         | 1.64%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 1.64%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.64%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s     | 1         | 1.64%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s          | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s    | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 1         | 1.64%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s           | 1         | 1.64%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.64%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s      | 1         | 1.64%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s             | 1         | 1.64%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s       | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.64%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 1         | 1.64%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Kingston RAM HP24D4S7S8MB-4 4GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 1         | 1.64%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| Elpida RAM Module 1GB SODIMM DDR3 1067MT/s                     | 1         | 1.64%   |
| Crucial RAM CT8G4SFS8266.M8FD 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.64%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.64%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| Crucial RAM CT16G4SFD832A.M16FRS 16GB SODIMM DDR4 3200MT/s     | 1         | 1.64%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s      | 1         | 1.64%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.64%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s       | 1         | 1.64%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 23        | 46.94%  |
| DDR3    | 16        | 32.65%  |
| LPDDR4  | 4         | 8.16%   |
| SDRAM   | 2         | 4.08%   |
| LPDDR3  | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 65.96%  |
| DIMM         | 11        | 23.4%   |
| Row Of Chips | 5         | 10.64%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 38.18%  |
| 8192  | 13        | 23.64%  |
| 16384 | 10        | 18.18%  |
| 2048  | 7         | 12.73%  |
| 1024  | 3         | 5.45%   |
| 32768 | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 13        | 24.53%  |
| 1600    | 11        | 20.75%  |
| 3200    | 8         | 15.09%  |
| 2400    | 4         | 7.55%   |
| 1334    | 3         | 5.66%   |
| 3600    | 2         | 3.77%   |
| 1867    | 2         | 3.77%   |
| 1067    | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| 4800    | 1         | 1.89%   |
| 3266    | 1         | 1.89%   |
| 2200    | 1         | 1.89%   |
| 2133    | 1         | 1.89%   |
| 1333    | 1         | 1.89%   |
| 800     | 1         | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 18.75%  |
| Acer                                   | 8         | 12.5%   |
| Microdia                               | 7         | 10.94%  |
| IMC Networks                           | 7         | 10.94%  |
| Apple                                  | 5         | 7.81%   |
| Sunplus Innovation Technology          | 3         | 4.69%   |
| Realtek Semiconductor                  | 3         | 4.69%   |
| Quanta                                 | 3         | 4.69%   |
| Logitech                               | 2         | 3.13%   |
| Teslong Camera                         | 1         | 1.56%   |
| Syntek                                 | 1         | 1.56%   |
| Suyin                                  | 1         | 1.56%   |
| Silicon Motion                         | 1         | 1.56%   |
| Ricoh                                  | 1         | 1.56%   |
| Primax Electronics                     | 1         | 1.56%   |
| Microsoft                              | 1         | 1.56%   |
| Luxvisions Innotech Limited            | 1         | 1.56%   |
| Jieli Technology                       | 1         | 1.56%   |
| Importek                               | 1         | 1.56%   |
| Goertek Electronics                    | 1         | 1.56%   |
| Creative Technology                    | 1         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.56%   |
| Alcor Micro                            | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                       | 3         | 4.62%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.08%   |
| Chicony Integrated Camera                            | 2         | 3.08%   |
| Chicony HP TrueVision HD                             | 2         | 3.08%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 3.08%   |
| Acer SunplusIT Integrated Camera                     | 2         | 3.08%   |
| Teslong Camera                                       | 1         | 1.54%   |
| Syntek Integrated Camera                             | 1         | 1.54%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.54%   |
| Sunplus HK 1080P K20Pro                              | 1         | 1.54%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.54%   |
| Ricoh HD Webcam                                      | 1         | 1.54%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.54%   |
| Realtek Integrated Webcam                            | 1         | 1.54%   |
| Realtek HP Wide Vision HD Camera                     | 1         | 1.54%   |
| Quanta VGA WebCam                                    | 1         | 1.54%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.54%   |
| Quanta HD User Facing                                | 1         | 1.54%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.54%   |
| Microsoft LifeCam Rear                               | 1         | 1.54%   |
| Microsoft LifeCam Front                              | 1         | 1.54%   |
| Microdia Webcam Vitade AF                            | 1         | 1.54%   |
| Microdia PC Microscope camera                        | 1         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.54%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.54%   |
| Microdia Integrated Webcam                           | 1         | 1.54%   |
| Microdia HP Webcam-101                               | 1         | 1.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.54%   |
| Logitech HD Webcam C615                              | 1         | 1.54%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.54%   |
| Jieli USB PHY 2.0                                    | 1         | 1.54%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.54%   |
| IMC Networks XHC Camera                              | 1         | 1.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.54%   |
| IMC Networks USB Camera                              | 1         | 1.54%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.54%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.54%   |
| IMC Networks Integrated Camera                       | 1         | 1.54%   |
| IMC Networks HD Camera                               | 1         | 1.54%   |
| Goertek USB2.0 VGA UVC WebCam                        | 1         | 1.54%   |
| Creative Live! Cam Sync HD [VF0770]                  | 1         | 1.54%   |
| Chicony USB2.0 Camera                                | 1         | 1.54%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 1.54%   |
| Chicony Integrated HP HD Webcam                      | 1         | 1.54%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.54%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.54%   |
| Chicony HP HD Camera                                 | 1         | 1.54%   |
| Chicony HD User Facing                               | 1         | 1.54%   |
| Chicony EasyCamera                                   | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 1.54%   |
| Apple FaceTime HD Camera (Built-in)                  | 1         | 1.54%   |
| Apple FaceTime Camera                                | 1         | 1.54%   |
| Apple Built-in iSight                                | 1         | 1.54%   |
| Alcor Micro SHUNCCM2MP                               | 1         | 1.54%   |
| Acer Lenovo EasyCamera                               | 1         | 1.54%   |
| Acer Integrated Camera                               | 1         | 1.54%   |
| Acer HD Camera                                       | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Validity Sensors           | 3         | 25%     |
| Shenzhen Goodix Technology | 3         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  WBDI                                           | 2         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 8.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 8.33%   |
| Unknown                                                   | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 4         | 57.14%  |
| SCM Microsystems | 1         | 14.29%  |
| OmniKey          | 1         | 14.29%  |
| Alcor Micro      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 14.29%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 43        | 51.81%  |
| 1     | 33        | 39.76%  |
| 2     | 7         | 8.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 12        | 27.91%  |
| Fingerprint reader       | 12        | 27.91%  |
| Graphics card            | 8         | 18.6%   |
| Chipcard                 | 5         | 11.63%  |
| Multimedia controller    | 4         | 9.3%    |
| Communication controller | 1         | 2.33%   |
| Bluetooth                | 1         | 2.33%   |

