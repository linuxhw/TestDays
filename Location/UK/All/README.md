Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 9904

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0VHWTR A01                  | Desktop     | [7544868958](https://linux-hardware.org/?probe=7544868958) | Feb 01, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [d7a5b537d9](https://linux-hardware.org/?probe=d7a5b537d9) | Feb 01, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [b13dd2d455](https://linux-hardware.org/?probe=b13dd2d455) | Feb 01, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [162e744903](https://linux-hardware.org/?probe=162e744903) | Feb 01, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3f9519f358](https://linux-hardware.org/?probe=3f9519f358) | Jan 31, 2023 |
| HP            | Sona                        | Notebook    | [36a3d72172](https://linux-hardware.org/?probe=36a3d72172) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [b029e941fb](https://linux-hardware.org/?probe=b029e941fb) | Jan 30, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [6c66b66a78](https://linux-hardware.org/?probe=6c66b66a78) | Jan 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [9568a6f43d](https://linux-hardware.org/?probe=9568a6f43d) | Jan 30, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8d62c84240](https://linux-hardware.org/?probe=8d62c84240) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7743588036](https://linux-hardware.org/?probe=7743588036) | Jan 30, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a05f6f2f6c](https://linux-hardware.org/?probe=a05f6f2f6c) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0082cca600](https://linux-hardware.org/?probe=0082cca600) | Jan 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [6d867d07e1](https://linux-hardware.org/?probe=6d867d07e1) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [bb0384d993](https://linux-hardware.org/?probe=bb0384d993) | Jan 30, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [380088c986](https://linux-hardware.org/?probe=380088c986) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [04ed0bd8b1](https://linux-hardware.org/?probe=04ed0bd8b1) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [873725bb74](https://linux-hardware.org/?probe=873725bb74) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f489fe4f5d](https://linux-hardware.org/?probe=f489fe4f5d) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [91ef57c9e5](https://linux-hardware.org/?probe=91ef57c9e5) | Jan 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a7b54907f](https://linux-hardware.org/?probe=5a7b54907f) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [845b3c6990](https://linux-hardware.org/?probe=845b3c6990) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d7469767f6](https://linux-hardware.org/?probe=d7469767f6) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [baf61affa2](https://linux-hardware.org/?probe=baf61affa2) | Jan 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c4877a8bc3](https://linux-hardware.org/?probe=c4877a8bc3) | Jan 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f447127e74](https://linux-hardware.org/?probe=f447127e74) | Jan 28, 2023 |
| HP            | 2B17                        | Desktop     | [8746c148c7](https://linux-hardware.org/?probe=8746c148c7) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [6d4ecb5a00](https://linux-hardware.org/?probe=6d4ecb5a00) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [f395c475c9](https://linux-hardware.org/?probe=f395c475c9) | Jan 27, 2023 |
| Dell          | 0CU409                      | Desktop     | [5da09834b4](https://linux-hardware.org/?probe=5da09834b4) | Jan 27, 2023 |
| Dell          | 0CU409                      | Desktop     | [06b8ea0f8e](https://linux-hardware.org/?probe=06b8ea0f8e) | Jan 27, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [4611591cc9](https://linux-hardware.org/?probe=4611591cc9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [e171a529b9](https://linux-hardware.org/?probe=e171a529b9) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [a0b14899a8](https://linux-hardware.org/?probe=a0b14899a8) | Jan 27, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [3963660171](https://linux-hardware.org/?probe=3963660171) | Jan 27, 2023 |
| HP            | 212A                        | Desktop     | [5b9c217d02](https://linux-hardware.org/?probe=5b9c217d02) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | Notebook    | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | 1497                        | Desktop     | [21a3e07346](https://linux-hardware.org/?probe=21a3e07346) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [de8222900d](https://linux-hardware.org/?probe=de8222900d) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | Notebook    | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [7fb86baa0e](https://linux-hardware.org/?probe=7fb86baa0e) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [fb83192f84](https://linux-hardware.org/?probe=fb83192f84) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [6faa58b4a1](https://linux-hardware.org/?probe=6faa58b4a1) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [f437e45107](https://linux-hardware.org/?probe=f437e45107) | Jan 26, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [3386aa1dce](https://linux-hardware.org/?probe=3386aa1dce) | Jan 25, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9dfb8ac7b0](https://linux-hardware.org/?probe=9dfb8ac7b0) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [64ccdd32f5](https://linux-hardware.org/?probe=64ccdd32f5) | Jan 25, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [68c58308b8](https://linux-hardware.org/?probe=68c58308b8) | Jan 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [0d073c35f4](https://linux-hardware.org/?probe=0d073c35f4) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c8c9f53754](https://linux-hardware.org/?probe=c8c9f53754) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [3ffb5ed458](https://linux-hardware.org/?probe=3ffb5ed458) | Jan 24, 2023 |
| ASUSTek       | Z87-WS                      | Desktop     | [da3028df45](https://linux-hardware.org/?probe=da3028df45) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [97ca64cad1](https://linux-hardware.org/?probe=97ca64cad1) | Jan 23, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e9124adb70](https://linux-hardware.org/?probe=e9124adb70) | Jan 23, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [e1eeca8eab](https://linux-hardware.org/?probe=e1eeca8eab) | Jan 23, 2023 |
| Dell          | 0TP406                      | Desktop     | [e169f52d32](https://linux-hardware.org/?probe=e169f52d32) | Jan 23, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [4a6f5a78f9](https://linux-hardware.org/?probe=4a6f5a78f9) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f0cce92dd4](https://linux-hardware.org/?probe=f0cce92dd4) | Jan 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ac375e0fa7](https://linux-hardware.org/?probe=ac375e0fa7) | Jan 23, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [e4a2f02d89](https://linux-hardware.org/?probe=e4a2f02d89) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| HP            | 1905                        | Desktop     | [aaa3a9557c](https://linux-hardware.org/?probe=aaa3a9557c) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6419184e6e](https://linux-hardware.org/?probe=6419184e6e) | Jan 21, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [cf65d9f981](https://linux-hardware.org/?probe=cf65d9f981) | Jan 21, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d971cd0912](https://linux-hardware.org/?probe=d971cd0912) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fe4b24bf26](https://linux-hardware.org/?probe=fe4b24bf26) | Jan 21, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [db131543b4](https://linux-hardware.org/?probe=db131543b4) | Jan 21, 2023 |
| Lenovo        | 31900058 STD                | All in one  | [a079d28341](https://linux-hardware.org/?probe=a079d28341) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [97b14c6835](https://linux-hardware.org/?probe=97b14c6835) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | Notebook    | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [4269f0e624](https://linux-hardware.org/?probe=4269f0e624) | Jan 20, 2023 |
| HP            | Unknown                     | Notebook    | [b82faadc9d](https://linux-hardware.org/?probe=b82faadc9d) | Jan 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9301fd6936](https://linux-hardware.org/?probe=9301fd6936) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [17e254a9ec](https://linux-hardware.org/?probe=17e254a9ec) | Jan 19, 2023 |
| HP            | 2AF3                        | Desktop     | [ac7c491076](https://linux-hardware.org/?probe=ac7c491076) | Jan 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [958e372993](https://linux-hardware.org/?probe=958e372993) | Jan 19, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [72e46e7bad](https://linux-hardware.org/?probe=72e46e7bad) | Jan 18, 2023 |
| Toshiba       | Satellite L70-C-12H         | Notebook    | [aa6340dd48](https://linux-hardware.org/?probe=aa6340dd48) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | 3396                        | Desktop     | [456080afe8](https://linux-hardware.org/?probe=456080afe8) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4545e31cd2](https://linux-hardware.org/?probe=4545e31cd2) | Jan 18, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0ccab4b1e3](https://linux-hardware.org/?probe=0ccab4b1e3) | Jan 18, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ff6ad7bf11](https://linux-hardware.org/?probe=ff6ad7bf11) | Jan 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [4b8096c4d2](https://linux-hardware.org/?probe=4b8096c4d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [6d93895cac](https://linux-hardware.org/?probe=6d93895cac) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [be9f4d6758](https://linux-hardware.org/?probe=be9f4d6758) | Jan 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [03c7a9b8a1](https://linux-hardware.org/?probe=03c7a9b8a1) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | Latitude E5440              | Notebook    | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [658ed38b10](https://linux-hardware.org/?probe=658ed38b10) | Jan 17, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [44f839ccbd](https://linux-hardware.org/?probe=44f839ccbd) | Jan 17, 2023 |
| Dell          | 07PXPY A02                  | Server      | [d56ca4a374](https://linux-hardware.org/?probe=d56ca4a374) | Jan 17, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [5012a7ccfc](https://linux-hardware.org/?probe=5012a7ccfc) | Jan 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [3dbc34a913](https://linux-hardware.org/?probe=3dbc34a913) | Jan 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d05225350d](https://linux-hardware.org/?probe=d05225350d) | Jan 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [aea2d1af0a](https://linux-hardware.org/?probe=aea2d1af0a) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [6445b08ce9](https://linux-hardware.org/?probe=6445b08ce9) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5ff11074e0](https://linux-hardware.org/?probe=5ff11074e0) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1c05ac2e28](https://linux-hardware.org/?probe=1c05ac2e28) | Jan 17, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ccce363b13](https://linux-hardware.org/?probe=ccce363b13) | Jan 17, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [83b98e5580](https://linux-hardware.org/?probe=83b98e5580) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [a75cdaa463](https://linux-hardware.org/?probe=a75cdaa463) | Jan 16, 2023 |
| Dell          | 0KRC95 A01                  | Desktop     | [4d39406938](https://linux-hardware.org/?probe=4d39406938) | Jan 16, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [64b395004f](https://linux-hardware.org/?probe=64b395004f) | Jan 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [5928caba96](https://linux-hardware.org/?probe=5928caba96) | Jan 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [798a9f2d30](https://linux-hardware.org/?probe=798a9f2d30) | Jan 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1644be7e2e](https://linux-hardware.org/?probe=1644be7e2e) | Jan 16, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [b1581dd523](https://linux-hardware.org/?probe=b1581dd523) | Jan 16, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [39b18604bf](https://linux-hardware.org/?probe=39b18604bf) | Jan 16, 2023 |
| Biostar       | H310MHP                     | Desktop     | [6495c0927b](https://linux-hardware.org/?probe=6495c0927b) | Jan 16, 2023 |
| Gigabyte      | EP45-DS4                    | Desktop     | [ef63262326](https://linux-hardware.org/?probe=ef63262326) | Jan 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [b73dacceb7](https://linux-hardware.org/?probe=b73dacceb7) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [31cf03aadd](https://linux-hardware.org/?probe=31cf03aadd) | Jan 15, 2023 |
| Gigabyte      | EP45-DS4                    | Desktop     | [9feae23438](https://linux-hardware.org/?probe=9feae23438) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | Notebook    | [3660b874bc](https://linux-hardware.org/?probe=3660b874bc) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | Notebook    | [5b62bf0146](https://linux-hardware.org/?probe=5b62bf0146) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [dca583bf2e](https://linux-hardware.org/?probe=dca583bf2e) | Jan 15, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [9ec7c970da](https://linux-hardware.org/?probe=9ec7c970da) | Jan 15, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0b80c9ddfb](https://linux-hardware.org/?probe=0b80c9ddfb) | Jan 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ba3e47247a](https://linux-hardware.org/?probe=ba3e47247a) | Jan 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [38d732c237](https://linux-hardware.org/?probe=38d732c237) | Jan 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [85048ce95d](https://linux-hardware.org/?probe=85048ce95d) | Jan 15, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [ca73cb526c](https://linux-hardware.org/?probe=ca73cb526c) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [0579b343cb](https://linux-hardware.org/?probe=0579b343cb) | Jan 15, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [2c4864375c](https://linux-hardware.org/?probe=2c4864375c) | Jan 14, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [d113da489f](https://linux-hardware.org/?probe=d113da489f) | Jan 14, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [6b0992e510](https://linux-hardware.org/?probe=6b0992e510) | Jan 14, 2023 |
| Dell          | Inspiron 15 7510            | Notebook    | [67f4d14824](https://linux-hardware.org/?probe=67f4d14824) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [4d74819919](https://linux-hardware.org/?probe=4d74819919) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| HP            | 805A                        | Desktop     | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [da829cbbc7](https://linux-hardware.org/?probe=da829cbbc7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [e4e7a1d245](https://linux-hardware.org/?probe=e4e7a1d245) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [c7baf1a126](https://linux-hardware.org/?probe=c7baf1a126) | Jan 14, 2023 |
| Alienware     | 17 R3                       | Notebook    | [d4cf3c4f4d](https://linux-hardware.org/?probe=d4cf3c4f4d) | Jan 14, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [0d1982257b](https://linux-hardware.org/?probe=0d1982257b) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [4e45aef7b0](https://linux-hardware.org/?probe=4e45aef7b0) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| Gigabyte      | B650E AORUS MASTER          | Desktop     | [7a9514375b](https://linux-hardware.org/?probe=7a9514375b) | Jan 13, 2023 |
| Dell          | Vostro 3549                 | Notebook    | [b6970533c4](https://linux-hardware.org/?probe=b6970533c4) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [bb92fab8d3](https://linux-hardware.org/?probe=bb92fab8d3) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [41e26fa7a1](https://linux-hardware.org/?probe=41e26fa7a1) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| AZW           | Green G3                    | Desktop     | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [15129f4c39](https://linux-hardware.org/?probe=15129f4c39) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | Notebook    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [8309c81fdf](https://linux-hardware.org/?probe=8309c81fdf) | Jan 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [508efb9c99](https://linux-hardware.org/?probe=508efb9c99) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | Notebook    | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [76d5a2b12b](https://linux-hardware.org/?probe=76d5a2b12b) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ee7b0c337b](https://linux-hardware.org/?probe=ee7b0c337b) | Jan 12, 2023 |
| Google        | Link                        | Notebook    | [f73704d47a](https://linux-hardware.org/?probe=f73704d47a) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c3b6b8b400](https://linux-hardware.org/?probe=c3b6b8b400) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [606cb1231b](https://linux-hardware.org/?probe=606cb1231b) | Jan 12, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [c10a0ccff5](https://linux-hardware.org/?probe=c10a0ccff5) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [2dadad3f74](https://linux-hardware.org/?probe=2dadad3f74) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [566725e667](https://linux-hardware.org/?probe=566725e667) | Jan 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [0001dd4164](https://linux-hardware.org/?probe=0001dd4164) | Jan 12, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a1f2661396](https://linux-hardware.org/?probe=a1f2661396) | Jan 11, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [96d07a0f9d](https://linux-hardware.org/?probe=96d07a0f9d) | Jan 11, 2023 |
| Lenovo        | ThinkPad W510 439123G       | Notebook    | [4fd1a4a217](https://linux-hardware.org/?probe=4fd1a4a217) | Jan 11, 2023 |
| Toshiba       | Satellite P50-C             | Notebook    | [1da161195b](https://linux-hardware.org/?probe=1da161195b) | Jan 11, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [680b0adb7b](https://linux-hardware.org/?probe=680b0adb7b) | Jan 11, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f0ba373485](https://linux-hardware.org/?probe=f0ba373485) | Jan 11, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [a25c10f2dd](https://linux-hardware.org/?probe=a25c10f2dd) | Jan 11, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [d079d53d80](https://linux-hardware.org/?probe=d079d53d80) | Jan 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [f91cb1b0e7](https://linux-hardware.org/?probe=f91cb1b0e7) | Jan 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [74cafb7a17](https://linux-hardware.org/?probe=74cafb7a17) | Jan 10, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [2dc4c5a4d8](https://linux-hardware.org/?probe=2dc4c5a4d8) | Jan 10, 2023 |
| HP            | ProBook 645 G2              | Notebook    | [1298e3efb0](https://linux-hardware.org/?probe=1298e3efb0) | Jan 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d1c53542d8](https://linux-hardware.org/?probe=d1c53542d8) | Jan 10, 2023 |
| Google        | Sparky360                   | Notebook    | [68e8848fba](https://linux-hardware.org/?probe=68e8848fba) | Jan 10, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Gigabyte      | H61N-USB3                   | Desktop     | [fd5a06c33f](https://linux-hardware.org/?probe=fd5a06c33f) | Jan 09, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [cae316a9ad](https://linux-hardware.org/?probe=cae316a9ad) | Jan 09, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [c434b0e62f](https://linux-hardware.org/?probe=c434b0e62f) | Jan 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f1edf0ce01](https://linux-hardware.org/?probe=f1edf0ce01) | Jan 09, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d903601066](https://linux-hardware.org/?probe=d903601066) | Jan 09, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [e86a06caea](https://linux-hardware.org/?probe=e86a06caea) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [22df883df4](https://linux-hardware.org/?probe=22df883df4) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [0e705ced6f](https://linux-hardware.org/?probe=0e705ced6f) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [46ae333889](https://linux-hardware.org/?probe=46ae333889) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ab227bc376](https://linux-hardware.org/?probe=ab227bc376) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ff6d324723](https://linux-hardware.org/?probe=ff6d324723) | Jan 08, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [652db107e8](https://linux-hardware.org/?probe=652db107e8) | Jan 08, 2023 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a2a9c2e730](https://linux-hardware.org/?probe=a2a9c2e730) | Jan 08, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [c343ff064d](https://linux-hardware.org/?probe=c343ff064d) | Jan 08, 2023 |
| Gateway       | MX8716B                     | Notebook    | [b8b9890719](https://linux-hardware.org/?probe=b8b9890719) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [c7fc660dd7](https://linux-hardware.org/?probe=c7fc660dd7) | Jan 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9f15bde3f6](https://linux-hardware.org/?probe=9f15bde3f6) | Jan 08, 2023 |
| Dell          | Latitude 5290               | Notebook    | [1cd20e22fc](https://linux-hardware.org/?probe=1cd20e22fc) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [24b5e0ba8e](https://linux-hardware.org/?probe=24b5e0ba8e) | Jan 07, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f70583b34b](https://linux-hardware.org/?probe=f70583b34b) | Jan 07, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [57433162a0](https://linux-hardware.org/?probe=57433162a0) | Jan 07, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [9a59c21db0](https://linux-hardware.org/?probe=9a59c21db0) | Jan 07, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [e7ee03968d](https://linux-hardware.org/?probe=e7ee03968d) | Jan 07, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f6d81f424d](https://linux-hardware.org/?probe=f6d81f424d) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f9fe18f923](https://linux-hardware.org/?probe=f9fe18f923) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [ae3de33f00](https://linux-hardware.org/?probe=ae3de33f00) | Jan 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1239be31f9](https://linux-hardware.org/?probe=1239be31f9) | Jan 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [17c9c6288e](https://linux-hardware.org/?probe=17c9c6288e) | Jan 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e2304eaaf2](https://linux-hardware.org/?probe=e2304eaaf2) | Jan 07, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [f489c93a99](https://linux-hardware.org/?probe=f489c93a99) | Jan 06, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a456485950](https://linux-hardware.org/?probe=a456485950) | Jan 06, 2023 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ad64106497](https://linux-hardware.org/?probe=ad64106497) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [ae45dfd30e](https://linux-hardware.org/?probe=ae45dfd30e) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cf94b53a8b](https://linux-hardware.org/?probe=cf94b53a8b) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b063be9f2e](https://linux-hardware.org/?probe=b063be9f2e) | Jan 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [4c54844f40](https://linux-hardware.org/?probe=4c54844f40) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [19a3a4f1c3](https://linux-hardware.org/?probe=19a3a4f1c3) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c1a3bf015a](https://linux-hardware.org/?probe=c1a3bf015a) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [abbff7d42a](https://linux-hardware.org/?probe=abbff7d42a) | Jan 04, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [5253826cac](https://linux-hardware.org/?probe=5253826cac) | Jan 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [671b852e29](https://linux-hardware.org/?probe=671b852e29) | Jan 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [73de62ce79](https://linux-hardware.org/?probe=73de62ce79) | Jan 03, 2023 |
| HP            | 83F3                        | Desktop     | [d53e207581](https://linux-hardware.org/?probe=d53e207581) | Jan 03, 2023 |
| MSI           | 2A9C                        | Desktop     | [48fc400420](https://linux-hardware.org/?probe=48fc400420) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [5ccb37c1d7](https://linux-hardware.org/?probe=5ccb37c1d7) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [bd49b43116](https://linux-hardware.org/?probe=bd49b43116) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [aa875f1083](https://linux-hardware.org/?probe=aa875f1083) | Jan 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ed57548b6](https://linux-hardware.org/?probe=9ed57548b6) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [a3d030fdc2](https://linux-hardware.org/?probe=a3d030fdc2) | Jan 02, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [6a90fa6693](https://linux-hardware.org/?probe=6a90fa6693) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [ae42b505d4](https://linux-hardware.org/?probe=ae42b505d4) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [6326869c9e](https://linux-hardware.org/?probe=6326869c9e) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [72a2446cd3](https://linux-hardware.org/?probe=72a2446cd3) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [03ca911bb7](https://linux-hardware.org/?probe=03ca911bb7) | Jan 01, 2023 |
| Advent        | Modena M201 Blue            | Notebook    | [abaae97a6f](https://linux-hardware.org/?probe=abaae97a6f) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [8e5b57a9f8](https://linux-hardware.org/?probe=8e5b57a9f8) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | Notebook    | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [10366e2627](https://linux-hardware.org/?probe=10366e2627) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [0749146323](https://linux-hardware.org/?probe=0749146323) | Dec 31, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [7c96c6776e](https://linux-hardware.org/?probe=7c96c6776e) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | 840A                        | Desktop     | [ad51866fe9](https://linux-hardware.org/?probe=ad51866fe9) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [294144217a](https://linux-hardware.org/?probe=294144217a) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [74b3157c61](https://linux-hardware.org/?probe=74b3157c61) | Dec 30, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [858fd62d74](https://linux-hardware.org/?probe=858fd62d74) | Dec 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [465d2da36b](https://linux-hardware.org/?probe=465d2da36b) | Dec 30, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [6aa950201f](https://linux-hardware.org/?probe=6aa950201f) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7a685e175c](https://linux-hardware.org/?probe=7a685e175c) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [f6f61f1841](https://linux-hardware.org/?probe=f6f61f1841) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [796edd73f6](https://linux-hardware.org/?probe=796edd73f6) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [e7a5c8704b](https://linux-hardware.org/?probe=e7a5c8704b) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [fa210be351](https://linux-hardware.org/?probe=fa210be351) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [d560c94d76](https://linux-hardware.org/?probe=d560c94d76) | Dec 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [08682d735c](https://linux-hardware.org/?probe=08682d735c) | Dec 30, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [9d71d087d8](https://linux-hardware.org/?probe=9d71d087d8) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [23d1e04f4c](https://linux-hardware.org/?probe=23d1e04f4c) | Dec 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [7b8f5e4379](https://linux-hardware.org/?probe=7b8f5e4379) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c7bea2d0f](https://linux-hardware.org/?probe=0c7bea2d0f) | Dec 29, 2022 |
| PC Special... | PCX0DX                      | Notebook    | [0a33ad889c](https://linux-hardware.org/?probe=0a33ad889c) | Dec 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e9a313bb81](https://linux-hardware.org/?probe=e9a313bb81) | Dec 28, 2022 |
| HP            | 840A                        | Desktop     | [85b8b7f9b1](https://linux-hardware.org/?probe=85b8b7f9b1) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Alienware     | M11x R2                     | Notebook    | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [23c5689182](https://linux-hardware.org/?probe=23c5689182) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [8e9e780028](https://linux-hardware.org/?probe=8e9e780028) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | 0AE4h                       | Desktop     | [c44d06efa6](https://linux-hardware.org/?probe=c44d06efa6) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c62ee60963](https://linux-hardware.org/?probe=c62ee60963) | Dec 27, 2022 |
| Acer          | Swift SFX14-51G             | Notebook    | [16c5f2a610](https://linux-hardware.org/?probe=16c5f2a610) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [db0586ef7b](https://linux-hardware.org/?probe=db0586ef7b) | Dec 27, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [b74460d91c](https://linux-hardware.org/?probe=b74460d91c) | Dec 27, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1ab930dc6](https://linux-hardware.org/?probe=a1ab930dc6) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [92825b79ee](https://linux-hardware.org/?probe=92825b79ee) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | Desktop     | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Alienware     | 07JNH0 A00                  | Desktop     | [41c418873b](https://linux-hardware.org/?probe=41c418873b) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c516dc209](https://linux-hardware.org/?probe=1c516dc209) | Dec 26, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Teclast       | X4                          | Tablet      | [d0b2244f5e](https://linux-hardware.org/?probe=d0b2244f5e) | Dec 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [cb4b71069c](https://linux-hardware.org/?probe=cb4b71069c) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c44d3c60da](https://linux-hardware.org/?probe=c44d3c60da) | Dec 25, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a46d6a7706](https://linux-hardware.org/?probe=a46d6a7706) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| Lenovo        | ThinkPad T450 20BUS3GN01    | Notebook    | [e88a11d2bb](https://linux-hardware.org/?probe=e88a11d2bb) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [778c642778](https://linux-hardware.org/?probe=778c642778) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [ef62b12cdb](https://linux-hardware.org/?probe=ef62b12cdb) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [91fb8b9a21](https://linux-hardware.org/?probe=91fb8b9a21) | Dec 24, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [ad65fe187a](https://linux-hardware.org/?probe=ad65fe187a) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [85a74e99ff](https://linux-hardware.org/?probe=85a74e99ff) | Dec 23, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [0ca6dca505](https://linux-hardware.org/?probe=0ca6dca505) | Dec 23, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [7123056cea](https://linux-hardware.org/?probe=7123056cea) | Dec 23, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [a9e701a27a](https://linux-hardware.org/?probe=a9e701a27a) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | Notebook    | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [53678dec76](https://linux-hardware.org/?probe=53678dec76) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | Notebook    | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [877545dd5c](https://linux-hardware.org/?probe=877545dd5c) | Dec 22, 2022 |
| System76      | Lemur Pro                   | Notebook    | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [74f0c818d6](https://linux-hardware.org/?probe=74f0c818d6) | Dec 21, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [d63c07df34](https://linux-hardware.org/?probe=d63c07df34) | Dec 21, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [51b3c3725e](https://linux-hardware.org/?probe=51b3c3725e) | Dec 21, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [d565332e52](https://linux-hardware.org/?probe=d565332e52) | Dec 21, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [dbb80c6a3c](https://linux-hardware.org/?probe=dbb80c6a3c) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [422faa5041](https://linux-hardware.org/?probe=422faa5041) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [5ab7ccb4cc](https://linux-hardware.org/?probe=5ab7ccb4cc) | Dec 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [870c784f85](https://linux-hardware.org/?probe=870c784f85) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [fdf00892eb](https://linux-hardware.org/?probe=fdf00892eb) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [0690e94fd6](https://linux-hardware.org/?probe=0690e94fd6) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [0644973fc3](https://linux-hardware.org/?probe=0644973fc3) | Dec 19, 2022 |
| HP            | 620                         | Notebook    | [c5ed6ae3bf](https://linux-hardware.org/?probe=c5ed6ae3bf) | Dec 19, 2022 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [86cedc585c](https://linux-hardware.org/?probe=86cedc585c) | Dec 19, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [6c6dcce3d8](https://linux-hardware.org/?probe=6c6dcce3d8) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [e8b08e9f68](https://linux-hardware.org/?probe=e8b08e9f68) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [03db07e80d](https://linux-hardware.org/?probe=03db07e80d) | Dec 18, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [28dc03a1bc](https://linux-hardware.org/?probe=28dc03a1bc) | Dec 18, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5fee494e26](https://linux-hardware.org/?probe=5fee494e26) | Dec 17, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [d2076f2a7a](https://linux-hardware.org/?probe=d2076f2a7a) | Dec 17, 2022 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [b882d3e249](https://linux-hardware.org/?probe=b882d3e249) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [ec4188fb59](https://linux-hardware.org/?probe=ec4188fb59) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [d47eae36fe](https://linux-hardware.org/?probe=d47eae36fe) | Dec 17, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [2f27a6ddd3](https://linux-hardware.org/?probe=2f27a6ddd3) | Dec 16, 2022 |
| Intel         | X79M-S                      | Desktop     | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3a9c3088c9](https://linux-hardware.org/?probe=3a9c3088c9) | Dec 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [7c5cc51ed4](https://linux-hardware.org/?probe=7c5cc51ed4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0fe564693b](https://linux-hardware.org/?probe=0fe564693b) | Dec 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [bb07a9abda](https://linux-hardware.org/?probe=bb07a9abda) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [302ea6f1dd](https://linux-hardware.org/?probe=302ea6f1dd) | Dec 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [aac750d7d1](https://linux-hardware.org/?probe=aac750d7d1) | Dec 14, 2022 |
| HP            | 355 G2                      | Notebook    | [c826d17369](https://linux-hardware.org/?probe=c826d17369) | Dec 14, 2022 |
| HP            | 355 G2                      | Notebook    | [f785946641](https://linux-hardware.org/?probe=f785946641) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [9330717977](https://linux-hardware.org/?probe=9330717977) | Dec 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [719a73ae26](https://linux-hardware.org/?probe=719a73ae26) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [47d6df705b](https://linux-hardware.org/?probe=47d6df705b) | Dec 13, 2022 |
| ECS           | GeForce7050M-M              | Desktop     | [118a28442e](https://linux-hardware.org/?probe=118a28442e) | Dec 13, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [16d5f27d87](https://linux-hardware.org/?probe=16d5f27d87) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [221e900b1c](https://linux-hardware.org/?probe=221e900b1c) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4be6aa4b7a](https://linux-hardware.org/?probe=4be6aa4b7a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T400 647419G       | Notebook    | [a73b681605](https://linux-hardware.org/?probe=a73b681605) | Dec 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [bc4a9d103c](https://linux-hardware.org/?probe=bc4a9d103c) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [5357e778aa](https://linux-hardware.org/?probe=5357e778aa) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d198c7fc5e](https://linux-hardware.org/?probe=d198c7fc5e) | Dec 11, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [eb171830a5](https://linux-hardware.org/?probe=eb171830a5) | Dec 11, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5073afb493](https://linux-hardware.org/?probe=5073afb493) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Intel         | Los Lunas 2 FAB             | Desktop     | [a6b8e30388](https://linux-hardware.org/?probe=a6b8e30388) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| Star Labs     | StarLite                    | Notebook    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| Toshiba       | Satellite C855-1W4          | Notebook    | [19149f22c5](https://linux-hardware.org/?probe=19149f22c5) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | Desktop     | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [9c4d6a19fe](https://linux-hardware.org/?probe=9c4d6a19fe) | Dec 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [79812ceedd](https://linux-hardware.org/?probe=79812ceedd) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3832c3e444](https://linux-hardware.org/?probe=3832c3e444) | Dec 09, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1280df2c5d](https://linux-hardware.org/?probe=1280df2c5d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [e11fca23e8](https://linux-hardware.org/?probe=e11fca23e8) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [172c6c1300](https://linux-hardware.org/?probe=172c6c1300) | Dec 08, 2022 |
| Google        | Nami                        | Notebook    | [9861d341a7](https://linux-hardware.org/?probe=9861d341a7) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | Desktop     | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | Notebook    | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4158e5b80f](https://linux-hardware.org/?probe=4158e5b80f) | Dec 07, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [cfb7b0f7ad](https://linux-hardware.org/?probe=cfb7b0f7ad) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [9fc6ea26bb](https://linux-hardware.org/?probe=9fc6ea26bb) | Dec 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [70cd36710e](https://linux-hardware.org/?probe=70cd36710e) | Dec 06, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [06cc238c83](https://linux-hardware.org/?probe=06cc238c83) | Dec 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [eb1b8bc98a](https://linux-hardware.org/?probe=eb1b8bc98a) | Dec 06, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [54fffddad1](https://linux-hardware.org/?probe=54fffddad1) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [02130c9bbb](https://linux-hardware.org/?probe=02130c9bbb) | Dec 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [bbe22c0ea7](https://linux-hardware.org/?probe=bbe22c0ea7) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [da0d74a201](https://linux-hardware.org/?probe=da0d74a201) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [69e8f9815d](https://linux-hardware.org/?probe=69e8f9815d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Google        | Chell                       | Notebook    | [3ffe532315](https://linux-hardware.org/?probe=3ffe532315) | Dec 05, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [21462d212f](https://linux-hardware.org/?probe=21462d212f) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| HP            | 8350                        | Desktop     | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [d9009fc1f5](https://linux-hardware.org/?probe=d9009fc1f5) | Dec 05, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [9b7999b50d](https://linux-hardware.org/?probe=9b7999b50d) | Dec 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [53ae0e1b6c](https://linux-hardware.org/?probe=53ae0e1b6c) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [13c990586f](https://linux-hardware.org/?probe=13c990586f) | Dec 05, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a0ff47f000](https://linux-hardware.org/?probe=a0ff47f000) | Dec 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS00700    | Notebook    | [141e7e9992](https://linux-hardware.org/?probe=141e7e9992) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4d38cbb41a](https://linux-hardware.org/?probe=4d38cbb41a) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7428311d73](https://linux-hardware.org/?probe=7428311d73) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [343b4488cc](https://linux-hardware.org/?probe=343b4488cc) | Dec 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c09783ccde](https://linux-hardware.org/?probe=c09783ccde) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| HP            | Notebook                    | Notebook    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [6c694b8c98](https://linux-hardware.org/?probe=6c694b8c98) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [61e955b5a6](https://linux-hardware.org/?probe=61e955b5a6) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [dc9c0686e7](https://linux-hardware.org/?probe=dc9c0686e7) | Dec 03, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f477b8f059](https://linux-hardware.org/?probe=f477b8f059) | Dec 03, 2022 |
| Star Labs     | StarLite                    | Notebook    | [d4cf1b0cd0](https://linux-hardware.org/?probe=d4cf1b0cd0) | Dec 03, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [69a716f389](https://linux-hardware.org/?probe=69a716f389) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [eb9887d9d4](https://linux-hardware.org/?probe=eb9887d9d4) | Dec 02, 2022 |
| ASUSTek       | A8N-E                       | Desktop     | [a1020380dd](https://linux-hardware.org/?probe=a1020380dd) | Dec 02, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [93c4564635](https://linux-hardware.org/?probe=93c4564635) | Dec 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [8e317647dc](https://linux-hardware.org/?probe=8e317647dc) | Dec 02, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a4ed7efef9](https://linux-hardware.org/?probe=a4ed7efef9) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5eebfea632](https://linux-hardware.org/?probe=5eebfea632) | Dec 01, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [b385e11c00](https://linux-hardware.org/?probe=b385e11c00) | Dec 01, 2022 |
| Dell          | 0G254H A00                  | Desktop     | [473fb8a09a](https://linux-hardware.org/?probe=473fb8a09a) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| Dell          | Latitude E5570              | Notebook    | [4db5cd2ef4](https://linux-hardware.org/?probe=4db5cd2ef4) | Dec 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [2f59960e11](https://linux-hardware.org/?probe=2f59960e11) | Dec 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [c155b94a47](https://linux-hardware.org/?probe=c155b94a47) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Dell          | Latitude E5520              | Notebook    | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [0b05465735](https://linux-hardware.org/?probe=0b05465735) | Nov 30, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [687aa83749](https://linux-hardware.org/?probe=687aa83749) | Nov 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f9215967d3](https://linux-hardware.org/?probe=f9215967d3) | Nov 30, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [4af0b7dc59](https://linux-hardware.org/?probe=4af0b7dc59) | Nov 30, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [bc8c993489](https://linux-hardware.org/?probe=bc8c993489) | Nov 30, 2022 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [c01129a199](https://linux-hardware.org/?probe=c01129a199) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [9e4bdbc81d](https://linux-hardware.org/?probe=9e4bdbc81d) | Nov 29, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [399346217e](https://linux-hardware.org/?probe=399346217e) | Nov 29, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [3e34521c45](https://linux-hardware.org/?probe=3e34521c45) | Nov 29, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [e43c4c3053](https://linux-hardware.org/?probe=e43c4c3053) | Nov 29, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [481a664e0a](https://linux-hardware.org/?probe=481a664e0a) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [e71c023456](https://linux-hardware.org/?probe=e71c023456) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f2c8b52293](https://linux-hardware.org/?probe=f2c8b52293) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [3ba81fa674](https://linux-hardware.org/?probe=3ba81fa674) | Nov 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [341bca1753](https://linux-hardware.org/?probe=341bca1753) | Nov 28, 2022 |
| Timi          | TM1613                      | Notebook    | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8072eb50aa](https://linux-hardware.org/?probe=8072eb50aa) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | Notebook    | [6816e8f5ca](https://linux-hardware.org/?probe=6816e8f5ca) | Nov 27, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | Notebook    | [06c690a0e1](https://linux-hardware.org/?probe=06c690a0e1) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [c924457e4b](https://linux-hardware.org/?probe=c924457e4b) | Nov 27, 2022 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| HP            | 86EE                        | All in one  | [8533afb703](https://linux-hardware.org/?probe=8533afb703) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [677279419f](https://linux-hardware.org/?probe=677279419f) | Nov 27, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [18b1ecf4fd](https://linux-hardware.org/?probe=18b1ecf4fd) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | Notebook    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [79cce0ef33](https://linux-hardware.org/?probe=79cce0ef33) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [c9feb7eed2](https://linux-hardware.org/?probe=c9feb7eed2) | Nov 26, 2022 |
| HP            | 0AA8h                       | Desktop     | [dba59690d7](https://linux-hardware.org/?probe=dba59690d7) | Nov 26, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [759ad3eb43](https://linux-hardware.org/?probe=759ad3eb43) | Nov 26, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [ba7b5c7748](https://linux-hardware.org/?probe=ba7b5c7748) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e7d8fb64e4](https://linux-hardware.org/?probe=e7d8fb64e4) | Nov 26, 2022 |
| Lenovo        | ThinkPad L13 20R3000FUK     | Notebook    | [c3ff5b014d](https://linux-hardware.org/?probe=c3ff5b014d) | Nov 26, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [85c0936ee0](https://linux-hardware.org/?probe=85c0936ee0) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [165626e7d0](https://linux-hardware.org/?probe=165626e7d0) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0a9d327f59](https://linux-hardware.org/?probe=0a9d327f59) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [869a5a808f](https://linux-hardware.org/?probe=869a5a808f) | Nov 25, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b70689b098](https://linux-hardware.org/?probe=b70689b098) | Nov 24, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [62c027aa0e](https://linux-hardware.org/?probe=62c027aa0e) | Nov 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5ea9d52f04](https://linux-hardware.org/?probe=5ea9d52f04) | Nov 24, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [4408f2ceff](https://linux-hardware.org/?probe=4408f2ceff) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| HP            | Pavilion x2 Detachable      | Tablet      | [3a3ff8db5e](https://linux-hardware.org/?probe=3a3ff8db5e) | Nov 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c0ce9a3ff3](https://linux-hardware.org/?probe=c0ce9a3ff3) | Nov 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57ddd940](https://linux-hardware.org/?probe=1e57ddd940) | Nov 23, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [470e942150](https://linux-hardware.org/?probe=470e942150) | Nov 23, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4c27c5511f](https://linux-hardware.org/?probe=4c27c5511f) | Nov 23, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0168e30f4f](https://linux-hardware.org/?probe=0168e30f4f) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [ce01aee504](https://linux-hardware.org/?probe=ce01aee504) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [12aac56052](https://linux-hardware.org/?probe=12aac56052) | Nov 22, 2022 |
| HP            | EliteBook 8530w             | Notebook    | [0c1d6d2201](https://linux-hardware.org/?probe=0c1d6d2201) | Nov 22, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d300e0c9cf](https://linux-hardware.org/?probe=d300e0c9cf) | Nov 21, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [b2e96ee4b2](https://linux-hardware.org/?probe=b2e96ee4b2) | Nov 21, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [16859cf0ca](https://linux-hardware.org/?probe=16859cf0ca) | Nov 21, 2022 |
| Radxa         | ROCK 5B                     | Soc         | [769a23d6d3](https://linux-hardware.org/?probe=769a23d6d3) | Nov 21, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [24fb42db2b](https://linux-hardware.org/?probe=24fb42db2b) | Nov 21, 2022 |
| HP            | 822A                        | Desktop     | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ac1533973e](https://linux-hardware.org/?probe=ac1533973e) | Nov 20, 2022 |
| Alienware     | M17xR3                      | Notebook    | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8e65fdc84b](https://linux-hardware.org/?probe=8e65fdc84b) | Nov 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [74187a44ae](https://linux-hardware.org/?probe=74187a44ae) | Nov 20, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [4a270e871f](https://linux-hardware.org/?probe=4a270e871f) | Nov 20, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [9f7a4537bf](https://linux-hardware.org/?probe=9f7a4537bf) | Nov 20, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [237b1cf2af](https://linux-hardware.org/?probe=237b1cf2af) | Nov 20, 2022 |
| TYAN Compu... | S7012                       | Server      | [5b5d81b1a8](https://linux-hardware.org/?probe=5b5d81b1a8) | Nov 19, 2022 |
| Medion        | BEAST X25                   | Notebook    | [fddb326ca2](https://linux-hardware.org/?probe=fddb326ca2) | Nov 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [61738f6d8a](https://linux-hardware.org/?probe=61738f6d8a) | Nov 19, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [68d1c8a80a](https://linux-hardware.org/?probe=68d1c8a80a) | Nov 19, 2022 |
| HP            | 8626                        | Desktop     | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP            | 8626                        | Desktop     | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [24518f7bf0](https://linux-hardware.org/?probe=24518f7bf0) | Nov 19, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [5c51c13f84](https://linux-hardware.org/?probe=5c51c13f84) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| ASUSTek       | K55A                        | Notebook    | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [89b7e22011](https://linux-hardware.org/?probe=89b7e22011) | Nov 19, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c9cee6c5e5](https://linux-hardware.org/?probe=c9cee6c5e5) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1faf8e38b4](https://linux-hardware.org/?probe=1faf8e38b4) | Nov 18, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e6c324007b](https://linux-hardware.org/?probe=e6c324007b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [882e91c53a](https://linux-hardware.org/?probe=882e91c53a) | Nov 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [83c0e1f2a1](https://linux-hardware.org/?probe=83c0e1f2a1) | Nov 16, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Dell          | Latitude 5410               | Notebook    | [dd9eb324db](https://linux-hardware.org/?probe=dd9eb324db) | Nov 16, 2022 |
| Dell          | Vostro 3590                 | Notebook    | [67ffc3ab77](https://linux-hardware.org/?probe=67ffc3ab77) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | Notebook    | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| HP            | 0AA4h                       | Desktop     | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [feeb9c7afd](https://linux-hardware.org/?probe=feeb9c7afd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dixonsxp      | F71IX1                      | Notebook    | [816c618ae7](https://linux-hardware.org/?probe=816c618ae7) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | Notebook    | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [15cd1d588f](https://linux-hardware.org/?probe=15cd1d588f) | Nov 15, 2022 |
| Dell          | Latitude E6320              | Notebook    | [a4767dfe35](https://linux-hardware.org/?probe=a4767dfe35) | Nov 14, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6c53b0c32d](https://linux-hardware.org/?probe=6c53b0c32d) | Nov 14, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [92a9bbc9a0](https://linux-hardware.org/?probe=92a9bbc9a0) | Nov 14, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fe166a1906](https://linux-hardware.org/?probe=fe166a1906) | Nov 14, 2022 |
| Acer          | Extensa 2530                | Notebook    | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [2853121816](https://linux-hardware.org/?probe=2853121816) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [d31168230f](https://linux-hardware.org/?probe=d31168230f) | Nov 13, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [4b6c28bf91](https://linux-hardware.org/?probe=4b6c28bf91) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [62cbc0b03d](https://linux-hardware.org/?probe=62cbc0b03d) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [305242c389](https://linux-hardware.org/?probe=305242c389) | Nov 13, 2022 |
| Colorful T... | I-H110-SI1                  | Desktop     | [50c44868e2](https://linux-hardware.org/?probe=50c44868e2) | Nov 13, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [78220bf9c5](https://linux-hardware.org/?probe=78220bf9c5) | Nov 13, 2022 |
| HP            | Presario CQ58               | Notebook    | [7a2e365b72](https://linux-hardware.org/?probe=7a2e365b72) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f84f4f8173](https://linux-hardware.org/?probe=f84f4f8173) | Nov 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [04a42845bf](https://linux-hardware.org/?probe=04a42845bf) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b2dbd8f602](https://linux-hardware.org/?probe=b2dbd8f602) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59a0a26e78](https://linux-hardware.org/?probe=59a0a26e78) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59d3c93814](https://linux-hardware.org/?probe=59d3c93814) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | Notebook    | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dc0e46c7b3](https://linux-hardware.org/?probe=dc0e46c7b3) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [75f7a51f9e](https://linux-hardware.org/?probe=75f7a51f9e) | Nov 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5439d56b25](https://linux-hardware.org/?probe=5439d56b25) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | Desktop     | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | Notebook    | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Silicom       | MinnowBoard Turbot          | Desktop     | [8fd6be3ee5](https://linux-hardware.org/?probe=8fd6be3ee5) | Nov 11, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [d05d4d5371](https://linux-hardware.org/?probe=d05d4d5371) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| HP            | 840A                        | Desktop     | [96a97a230e](https://linux-hardware.org/?probe=96a97a230e) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [53dff9d6c0](https://linux-hardware.org/?probe=53dff9d6c0) | Nov 08, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [c1b96e2040](https://linux-hardware.org/?probe=c1b96e2040) | Nov 08, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [10f1d89d4a](https://linux-hardware.org/?probe=10f1d89d4a) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| Linx          | LINX1010B                   | Notebook    | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4cf4bffd62](https://linux-hardware.org/?probe=4cf4bffd62) | Nov 07, 2022 |
| Entroware     | Hybris                      | Notebook    | [bf5c8bcbaf](https://linux-hardware.org/?probe=bf5c8bcbaf) | Nov 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [873668d836](https://linux-hardware.org/?probe=873668d836) | Nov 07, 2022 |
| Notebook      | PA70ES                      | Notebook    | [7254b24693](https://linux-hardware.org/?probe=7254b24693) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [0c0bde7c74](https://linux-hardware.org/?probe=0c0bde7c74) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4c292cff97](https://linux-hardware.org/?probe=4c292cff97) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c5e823980](https://linux-hardware.org/?probe=8c5e823980) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Dell          | G7 7700                     | Notebook    | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [e5721cdfbb](https://linux-hardware.org/?probe=e5721cdfbb) | Nov 06, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [340f509c6b](https://linux-hardware.org/?probe=340f509c6b) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| HP            | Pavilion g7                 | Notebook    | [4ad4ed4c47](https://linux-hardware.org/?probe=4ad4ed4c47) | Nov 05, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [654585bbaf](https://linux-hardware.org/?probe=654585bbaf) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [b74e119c7e](https://linux-hardware.org/?probe=b74e119c7e) | Nov 05, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [8b7e60aef0](https://linux-hardware.org/?probe=8b7e60aef0) | Nov 05, 2022 |
| Samsung       | 700T1C                      | Notebook    | [c561c328b3](https://linux-hardware.org/?probe=c561c328b3) | Nov 05, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [7a4477cf7b](https://linux-hardware.org/?probe=7a4477cf7b) | Nov 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c7dc8f4eb6](https://linux-hardware.org/?probe=c7dc8f4eb6) | Nov 05, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c177c82021](https://linux-hardware.org/?probe=c177c82021) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | Notebook    | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d2a6ea0b28](https://linux-hardware.org/?probe=d2a6ea0b28) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bb9a674a45](https://linux-hardware.org/?probe=bb9a674a45) | Nov 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ad5ff05f8e](https://linux-hardware.org/?probe=ad5ff05f8e) | Nov 04, 2022 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [96e0465554](https://linux-hardware.org/?probe=96e0465554) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3b8c01f3d5](https://linux-hardware.org/?probe=3b8c01f3d5) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | Notebook    | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| Acer          | H57M01                      | Desktop     | [bfbf74ff75](https://linux-hardware.org/?probe=bfbf74ff75) | Nov 03, 2022 |
| Star Labs     | StarBook                    | Notebook    | [1cfe5c0920](https://linux-hardware.org/?probe=1cfe5c0920) | Nov 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [db83c146a6](https://linux-hardware.org/?probe=db83c146a6) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c693004e08](https://linux-hardware.org/?probe=c693004e08) | Nov 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e4a7690a77](https://linux-hardware.org/?probe=e4a7690a77) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [1421a5a4e9](https://linux-hardware.org/?probe=1421a5a4e9) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | Notebook    | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [0092b0ddaf](https://linux-hardware.org/?probe=0092b0ddaf) | Nov 01, 2022 |
| Phoenix       | POULSBO                     | Desktop     | [177f05205b](https://linux-hardware.org/?probe=177f05205b) | Nov 01, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [caffb9ebd7](https://linux-hardware.org/?probe=caffb9ebd7) | Nov 01, 2022 |
| ASUSTek       | P52F                        | Notebook    | [a83cb4c35d](https://linux-hardware.org/?probe=a83cb4c35d) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a233571587](https://linux-hardware.org/?probe=a233571587) | Oct 31, 2022 |
| Acer          | Aspire TC-280               | Desktop     | [68679c6495](https://linux-hardware.org/?probe=68679c6495) | Oct 31, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [8769289ea5](https://linux-hardware.org/?probe=8769289ea5) | Oct 31, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [92e9764aa0](https://linux-hardware.org/?probe=92e9764aa0) | Oct 31, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [d6bf187cc9](https://linux-hardware.org/?probe=d6bf187cc9) | Oct 31, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [4fa081a282](https://linux-hardware.org/?probe=4fa081a282) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [38d0d0e32a](https://linux-hardware.org/?probe=38d0d0e32a) | Oct 31, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [d84f634b59](https://linux-hardware.org/?probe=d84f634b59) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| Acer          | Swift SFX14-51G             | Notebook    | [6812d7cf22](https://linux-hardware.org/?probe=6812d7cf22) | Oct 30, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f1eac2c0c3](https://linux-hardware.org/?probe=f1eac2c0c3) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | Notebook    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [03d14141e4](https://linux-hardware.org/?probe=03d14141e4) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [b7760774ca](https://linux-hardware.org/?probe=b7760774ca) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [23ad30db1a](https://linux-hardware.org/?probe=23ad30db1a) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| GEO           | GeoBook3                    | Notebook    | [133a4460f6](https://linux-hardware.org/?probe=133a4460f6) | Oct 29, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [957fc9af86](https://linux-hardware.org/?probe=957fc9af86) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| Dell          | Latitude E6530              | Notebook    | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7d5d2ec0ba](https://linux-hardware.org/?probe=7d5d2ec0ba) | Oct 28, 2022 |
| MSI           | MS-AE3111 10                | Other       | [b21e69db4d](https://linux-hardware.org/?probe=b21e69db4d) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| MSI           | MS-AE3111 10                | Other       | [ad5c043471](https://linux-hardware.org/?probe=ad5c043471) | Oct 28, 2022 |
| Tactus        | GeoBook 110                 | Notebook    | [aad56b27f0](https://linux-hardware.org/?probe=aad56b27f0) | Oct 28, 2022 |
| HP            | 82A5                        | Mini pc     | [c0be7985c0](https://linux-hardware.org/?probe=c0be7985c0) | Oct 28, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [20bf043d6f](https://linux-hardware.org/?probe=20bf043d6f) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| Alienware     | 046MHW A00                  | Desktop     | [5a5511a68b](https://linux-hardware.org/?probe=5a5511a68b) | Oct 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [920b0eaa44](https://linux-hardware.org/?probe=920b0eaa44) | Oct 27, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | Notebook    | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Gigabyte      | H61N-USB3                   | Desktop     | [ff94581714](https://linux-hardware.org/?probe=ff94581714) | Oct 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d8343e2db5](https://linux-hardware.org/?probe=d8343e2db5) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| HP            | Setzer                      | Notebook    | [a1039409cd](https://linux-hardware.org/?probe=a1039409cd) | Oct 26, 2022 |
| HP            | Setzer                      | Notebook    | [3945fea013](https://linux-hardware.org/?probe=3945fea013) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | Desktop     | [592883e78e](https://linux-hardware.org/?probe=592883e78e) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | Desktop     | [734fb9ac8c](https://linux-hardware.org/?probe=734fb9ac8c) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [dee13eac1d](https://linux-hardware.org/?probe=dee13eac1d) | Oct 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [1bc80461df](https://linux-hardware.org/?probe=1bc80461df) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3a10949e83](https://linux-hardware.org/?probe=3a10949e83) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b4d5421b09](https://linux-hardware.org/?probe=b4d5421b09) | Oct 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [e3a6983caf](https://linux-hardware.org/?probe=e3a6983caf) | Oct 25, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [a56ad41b2f](https://linux-hardware.org/?probe=a56ad41b2f) | Oct 25, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [2692d8c0cd](https://linux-hardware.org/?probe=2692d8c0cd) | Oct 24, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [bff16c4d6c](https://linux-hardware.org/?probe=bff16c4d6c) | Oct 24, 2022 |
| Acer          | Aspire C24-865              | All in one  | [31b61c3ce9](https://linux-hardware.org/?probe=31b61c3ce9) | Oct 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dd05575bb4](https://linux-hardware.org/?probe=dd05575bb4) | Oct 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2cb5dc9c7](https://linux-hardware.org/?probe=d2cb5dc9c7) | Oct 24, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [8b6263dc68](https://linux-hardware.org/?probe=8b6263dc68) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | Notebook    | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Acer          | Aspire C24-865              | All in one  | [257d3a9124](https://linux-hardware.org/?probe=257d3a9124) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| AMI           | Unknown                     | Notebook    | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [34f4204ae8](https://linux-hardware.org/?probe=34f4204ae8) | Oct 23, 2022 |
| GEO           | GeoBook 140                 | Notebook    | [e97f8024f4](https://linux-hardware.org/?probe=e97f8024f4) | Oct 22, 2022 |
| HP            | 86EE                        | All in one  | [4c631cdc18](https://linux-hardware.org/?probe=4c631cdc18) | Oct 22, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| GEO           | GeoBook 140                 | Notebook    | [bbbe5e0fca](https://linux-hardware.org/?probe=bbbe5e0fca) | Oct 22, 2022 |
| Dell          | 07PR60 A00                  | Desktop     | [a1cb6d4862](https://linux-hardware.org/?probe=a1cb6d4862) | Oct 22, 2022 |
| Samsung       | R519/R719                   | Notebook    | [da6668197e](https://linux-hardware.org/?probe=da6668197e) | Oct 22, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [0ec4fb54a6](https://linux-hardware.org/?probe=0ec4fb54a6) | Oct 21, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [1f659498a2](https://linux-hardware.org/?probe=1f659498a2) | Oct 21, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [2f6d59ec8b](https://linux-hardware.org/?probe=2f6d59ec8b) | Oct 21, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [0ed2f15c34](https://linux-hardware.org/?probe=0ed2f15c34) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| Acer          | Aspire S3                   | Notebook    | [a24603a142](https://linux-hardware.org/?probe=a24603a142) | Oct 20, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [3632c8a48d](https://linux-hardware.org/?probe=3632c8a48d) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [fef9e26716](https://linux-hardware.org/?probe=fef9e26716) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | Desktop     | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [c30eaa0009](https://linux-hardware.org/?probe=c30eaa0009) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire V5-132P              | Notebook    | [420ad7ac8c](https://linux-hardware.org/?probe=420ad7ac8c) | Oct 19, 2022 |
| Lenovo        | G580 2689H2G                | Notebook    | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1223730da0](https://linux-hardware.org/?probe=1223730da0) | Oct 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [d65e0cfe7a](https://linux-hardware.org/?probe=d65e0cfe7a) | Oct 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [04bef71f33](https://linux-hardware.org/?probe=04bef71f33) | Oct 18, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [d5d3ad3491](https://linux-hardware.org/?probe=d5d3ad3491) | Oct 18, 2022 |
| GEO           | GeoBook 120                 | Notebook    | [fe063a61a7](https://linux-hardware.org/?probe=fe063a61a7) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| HP            | ZBook 15                    | Notebook    | [6926e1a3c0](https://linux-hardware.org/?probe=6926e1a3c0) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [d6a23d7f6d](https://linux-hardware.org/?probe=d6a23d7f6d) | Oct 17, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [61aeb93e12](https://linux-hardware.org/?probe=61aeb93e12) | Oct 16, 2022 |
| ASRock        | N68-S                       | Desktop     | [356bdaf8d8](https://linux-hardware.org/?probe=356bdaf8d8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Dell          | 0XGMD0 A00                  | All in one  | [e38169d409](https://linux-hardware.org/?probe=e38169d409) | Oct 16, 2022 |
| Samsung       | 700T1C                      | Notebook    | [b0b2e6712c](https://linux-hardware.org/?probe=b0b2e6712c) | Oct 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d2b5d08432](https://linux-hardware.org/?probe=d2b5d08432) | Oct 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ee67e90b5f](https://linux-hardware.org/?probe=ee67e90b5f) | Oct 15, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ef118e61f2](https://linux-hardware.org/?probe=ef118e61f2) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| Dell          | 0J3C2F A01                  | Desktop     | [b30840548a](https://linux-hardware.org/?probe=b30840548a) | Oct 15, 2022 |
| HP            | Presario C300 (RM500EA#A... | Notebook    | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4545a01dbb](https://linux-hardware.org/?probe=4545a01dbb) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [82a7e620f0](https://linux-hardware.org/?probe=82a7e620f0) | Oct 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [34fcf52c18](https://linux-hardware.org/?probe=34fcf52c18) | Oct 14, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [78b6f676b0](https://linux-hardware.org/?probe=78b6f676b0) | Oct 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2830449515](https://linux-hardware.org/?probe=2830449515) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a3f2f1dcc7](https://linux-hardware.org/?probe=a3f2f1dcc7) | Oct 13, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [3e38f64c1c](https://linux-hardware.org/?probe=3e38f64c1c) | Oct 13, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [e1bdf49dbf](https://linux-hardware.org/?probe=e1bdf49dbf) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [3ffa813244](https://linux-hardware.org/?probe=3ffa813244) | Oct 13, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [63731688d0](https://linux-hardware.org/?probe=63731688d0) | Oct 13, 2022 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [977ba540ba](https://linux-hardware.org/?probe=977ba540ba) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7dbdbc1de9](https://linux-hardware.org/?probe=7dbdbc1de9) | Oct 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0bc0b385c3](https://linux-hardware.org/?probe=0bc0b385c3) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| ASUSTek       | P6T SE                      | Desktop     | [4ba4bc909d](https://linux-hardware.org/?probe=4ba4bc909d) | Oct 12, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [1c508c2425](https://linux-hardware.org/?probe=1c508c2425) | Oct 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e67263e24c](https://linux-hardware.org/?probe=e67263e24c) | Oct 11, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c213445487](https://linux-hardware.org/?probe=c213445487) | Oct 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f263785a18](https://linux-hardware.org/?probe=f263785a18) | Oct 11, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | Notebook    | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2b7e826ffe](https://linux-hardware.org/?probe=2b7e826ffe) | Oct 10, 2022 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5e65bc0e8a](https://linux-hardware.org/?probe=5e65bc0e8a) | Oct 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [c33c96e412](https://linux-hardware.org/?probe=c33c96e412) | Oct 09, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [2fcef4ba1a](https://linux-hardware.org/?probe=2fcef4ba1a) | Oct 09, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7bed9aed61](https://linux-hardware.org/?probe=7bed9aed61) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | Notebook    | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [e51edac602](https://linux-hardware.org/?probe=e51edac602) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [d19b3b23b5](https://linux-hardware.org/?probe=d19b3b23b5) | Oct 08, 2022 |
| ASRock        | N68-S                       | Desktop     | [6483604e68](https://linux-hardware.org/?probe=6483604e68) | Oct 08, 2022 |
| ASRock        | N68-S                       | Desktop     | [49c45b72cf](https://linux-hardware.org/?probe=49c45b72cf) | Oct 08, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [7f59512d7b](https://linux-hardware.org/?probe=7f59512d7b) | Oct 08, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [9cdc747659](https://linux-hardware.org/?probe=9cdc747659) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [2920ed8076](https://linux-hardware.org/?probe=2920ed8076) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4bea37497e](https://linux-hardware.org/?probe=4bea37497e) | Oct 07, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [84875d4a55](https://linux-hardware.org/?probe=84875d4a55) | Oct 07, 2022 |
| HP            | 822A                        | Desktop     | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [08c66f26fe](https://linux-hardware.org/?probe=08c66f26fe) | Oct 07, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [2f0b4a72b3](https://linux-hardware.org/?probe=2f0b4a72b3) | Oct 06, 2022 |
| Dell          | Latitude 7480               | Notebook    | [ad29ce89eb](https://linux-hardware.org/?probe=ad29ce89eb) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [bb71e0e8c3](https://linux-hardware.org/?probe=bb71e0e8c3) | Oct 05, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [56cf39c1dd](https://linux-hardware.org/?probe=56cf39c1dd) | Oct 05, 2022 |
| HP            | 2B60 MVB                    | Desktop     | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [8bef2621c5](https://linux-hardware.org/?probe=8bef2621c5) | Oct 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [700e1adbbb](https://linux-hardware.org/?probe=700e1adbbb) | Oct 05, 2022 |
| Lenovo        | N23 80UR                    | Convertible | [f6bf19c41a](https://linux-hardware.org/?probe=f6bf19c41a) | Oct 05, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [b63bfc9b4c](https://linux-hardware.org/?probe=b63bfc9b4c) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | Notebook    | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Microsoft     | Surface Book                | Tablet      | [85c4f341f3](https://linux-hardware.org/?probe=85c4f341f3) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [a80da55e0c](https://linux-hardware.org/?probe=a80da55e0c) | Oct 04, 2022 |
| Acer          | Extensa 2530                | Notebook    | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [8ccfb39433](https://linux-hardware.org/?probe=8ccfb39433) | Oct 03, 2022 |
| HP            | 8105                        | Desktop     | [50aaff9f71](https://linux-hardware.org/?probe=50aaff9f71) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [15ed095440](https://linux-hardware.org/?probe=15ed095440) | Oct 02, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [cdcd2cf0e6](https://linux-hardware.org/?probe=cdcd2cf0e6) | Oct 02, 2022 |
| eMachines     | E525                        | Notebook    | [1467bc71f7](https://linux-hardware.org/?probe=1467bc71f7) | Oct 02, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [8eaded9cb5](https://linux-hardware.org/?probe=8eaded9cb5) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [f6e2c51367](https://linux-hardware.org/?probe=f6e2c51367) | Sep 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ab0a3e1a94](https://linux-hardware.org/?probe=ab0a3e1a94) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [f0eae50061](https://linux-hardware.org/?probe=f0eae50061) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Dell          | Latitude 7430               | Notebook    | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Supermicro    | X10SRA-F                    | Server      | [a9aa07ef24](https://linux-hardware.org/?probe=a9aa07ef24) | Sep 28, 2022 |
| Supermicro    | X10SRA-F                    | Server      | [2f41a520ed](https://linux-hardware.org/?probe=2f41a520ed) | Sep 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1116      | 15.93%  |
| Ubuntu 18.04       | 596       | 8.51%   |
| Ubuntu 22.04       | 280       | 4%      |
| Zorin 16           | 162       | 2.31%   |
| Debian 11          | 137       | 1.96%   |
| OpenMandriva 4.3   | 134       | 1.91%   |
| OpenMandriva 4.2   | 132       | 1.88%   |
| Arch Rolling       | 115       | 1.64%   |
| Linux Mint 20.2    | 112       | 1.6%    |
| Linux Mint 20.3    | 111       | 1.58%   |
| Linux Mint 19.3    | 111       | 1.58%   |
| KDE neon 20.04     | 111       | 1.58%   |
| Pop!_OS 20.04      | 108       | 1.54%   |
| Ubuntu 19.04       | 105       | 1.5%    |
| Manjaro            | 101       | 1.44%   |
| Ubuntu 20.10       | 100       | 1.43%   |
| Pop!_OS 21.04      | 100       | 1.43%   |
| Arch               | 97        | 1.38%   |
| Ubuntu 21.10       | 94        | 1.34%   |
| Zorin 15           | 91        | 1.3%    |
| Pop!_OS 22.04      | 91        | 1.3%    |
| Ubuntu 19.10       | 89        | 1.27%   |
| Pop!_OS 20.10      | 86        | 1.23%   |
| Linux Mint 20.1    | 84        | 1.2%    |
| ArcoLinux Rolling  | 84        | 1.2%    |
| Ubuntu 21.04       | 81        | 1.16%   |
| Xubuntu 20.04      | 76        | 1.09%   |
| Linux Mint 20      | 67        | 0.96%   |
| Fedora 36          | 65        | 0.93%   |
| Fedora 34          | 60        | 0.86%   |
| Pop!_OS 21.10      | 57        | 0.81%   |
| Fedora 35          | 57        | 0.81%   |
| Ubuntu 18.10       | 56        | 0.8%    |
| Kubuntu 20.04      | 56        | 0.8%    |
| OpenMandriva 23.01 | 51        | 0.73%   |
| Fedora 33          | 48        | 0.69%   |
| Fedora 31          | 48        | 0.69%   |
| Debian 10          | 47        | 0.67%   |
| Linux Mint 21      | 44        | 0.63%   |
| Fedora 32          | 43        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2473      | 37.01%  |
| Linux Mint    | 581       | 8.7%    |
| Pop!_OS       | 419       | 6.27%   |
| OpenMandriva  | 371       | 5.55%   |
| Fedora        | 353       | 5.28%   |
| Zorin         | 263       | 3.94%   |
| Debian        | 234       | 3.5%    |
| Manjaro       | 215       | 3.22%   |
| Arch          | 210       | 3.14%   |
| Kubuntu       | 141       | 2.11%   |
| Xubuntu       | 139       | 2.08%   |
| KDE neon      | 139       | 2.08%   |
| ArcoLinux     | 88        | 1.32%   |
| ROSA          | 75        | 1.12%   |
| SteamOS       | 69        | 1.03%   |
| Elementary    | 68        | 1.02%   |
| Ubuntu MATE   | 63        | 0.94%   |
| Gentoo        | 62        | 0.93%   |
| openSUSE      | 59        | 0.88%   |
| Endless       | 53        | 0.79%   |
| Lubuntu       | 50        | 0.75%   |
| Ubuntu Unity  | 49        | 0.73%   |
| Clear Linux   | 44        | 0.66%   |
| Kali          | 41        | 0.61%   |
| BlackPanther  | 40        | 0.6%    |
| CentOS        | 26        | 0.39%   |
| LMDE          | 25        | 0.37%   |
| MX            | 22        | 0.33%   |
| Ubuntu Budgie | 21        | 0.31%   |
| Garuda Linux  | 21        | 0.31%   |
| EndeavourOS   | 21        | 0.31%   |
| Raspbian      | 18        | 0.27%   |
| Peppermint    | 16        | 0.24%   |
| RHEL          | 15        | 0.22%   |
| Parrot        | 13        | 0.19%   |
| Slackware     | 11        | 0.16%   |
| Nobara        | 10        | 0.15%   |
| Alpine        | 9         | 0.13%   |
| NixOS         | 8         | 0.12%   |
| Mageia        | 7         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.95%   |
| 5.16.7-desktop-1omv4003  | 130       | 1.66%   |
| 5.10.14-desktop-1omv4002 | 129       | 1.65%   |
| 5.4.0-48-generic         | 81        | 1.04%   |
| 5.4.0-52-generic         | 76        | 0.97%   |
| 5.4.0-29-generic         | 73        | 0.93%   |
| 5.15.0-56-generic        | 71        | 0.91%   |
| 5.4.0-26-generic         | 70        | 0.9%    |
| 5.3.0-28-generic         | 65        | 0.83%   |
| 5.15.0-52-generic        | 65        | 0.83%   |
| 5.15.0-46-generic        | 63        | 0.81%   |
| 5.3.0-40-generic         | 60        | 0.77%   |
| 5.4.0-40-generic         | 53        | 0.68%   |
| 5.4.0-37-generic         | 51        | 0.65%   |
| 5.11.0-27-generic        | 51        | 0.65%   |
| 5.4.0-58-generic         | 50        | 0.64%   |
| 6.1.1-desktop-1omv2290   | 49        | 0.63%   |
| 5.4.0-65-generic         | 45        | 0.58%   |
| 5.4.0-33-generic         | 45        | 0.58%   |
| 5.11.0-38-generic        | 45        | 0.58%   |
| 5.0.0-32-generic         | 45        | 0.58%   |
| 5.4.0-91-generic         | 43        | 0.55%   |
| 5.13.0-7614-generic      | 43        | 0.55%   |
| 5.11.0-25-generic        | 43        | 0.55%   |
| 5.4.0-7634-generic       | 41        | 0.52%   |
| 5.4.0-54-generic         | 41        | 0.52%   |
| 5.3.0-46-generic         | 41        | 0.52%   |
| 5.4.0-74-generic         | 40        | 0.51%   |
| 5.4.0-66-generic         | 40        | 0.51%   |
| 5.15.0-58-generic        | 40        | 0.51%   |
| 5.8.0-7630-generic       | 39        | 0.5%    |
| 5.8.0-43-generic         | 39        | 0.5%    |
| 5.11.0-7620-generic      | 39        | 0.5%    |
| 5.0.0-37-generic         | 39        | 0.5%    |
| 5.15.0-48-generic        | 38        | 0.49%   |
| 5.11.0-40-generic        | 38        | 0.49%   |
| 5.3.0-42-generic         | 37        | 0.47%   |
| 5.13.0-28-generic        | 37        | 0.47%   |
| 5.11.0-37-generic        | 37        | 0.47%   |
| 5.8.0-50-generic         | 36        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1488      | 20.53%  |
| 5.15.0  | 529       | 7.3%    |
| 5.11.0  | 454       | 6.26%   |
| 5.8.0   | 448       | 6.18%   |
| 5.13.0  | 432       | 5.96%   |
| 4.15.0  | 417       | 5.75%   |
| 5.3.0   | 374       | 5.16%   |
| 5.0.0   | 244       | 3.37%   |
| 4.18.0  | 180       | 2.48%   |
| 5.10.0  | 162       | 2.24%   |
| 5.16.7  | 131       | 1.81%   |
| 5.10.14 | 129       | 1.78%   |
| 5.19.0  | 71        | 0.98%   |
| 4.19.0  | 57        | 0.79%   |
| 6.1.1   | 54        | 0.75%   |
| 5.17.5  | 34        | 0.47%   |
| 4.18.16 | 32        | 0.44%   |
| 5.14.0  | 30        | 0.41%   |
| 4.9.60  | 26        | 0.36%   |
| 6.0.6   | 25        | 0.34%   |
| 6.0.0   | 25        | 0.34%   |
| 5.9.16  | 25        | 0.34%   |
| 5.18.0  | 22        | 0.3%    |
| 4.4.0   | 21        | 0.29%   |
| 6.0.12  | 19        | 0.26%   |
| 5.17.1  | 19        | 0.26%   |
| 5.18.12 | 18        | 0.25%   |
| 5.16.11 | 18        | 0.25%   |
| 5.15.12 | 17        | 0.23%   |
| 5.13.12 | 17        | 0.23%   |
| 5.7.0   | 16        | 0.22%   |
| 5.16.0  | 16        | 0.22%   |
| 4.9.20  | 16        | 0.22%   |
| 5.17.0  | 15        | 0.21%   |
| 5.15.15 | 15        | 0.21%   |
| 5.12.4  | 15        | 0.21%   |
| 5.12.13 | 15        | 0.21%   |
| 5.6.14  | 14        | 0.19%   |
| 5.6.0   | 14        | 0.19%   |
| 5.3.18  | 14        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1579      | 22.08%  |
| 5.15    | 708       | 9.9%    |
| 5.8     | 535       | 7.48%   |
| 5.13    | 518       | 7.24%   |
| 5.11    | 512       | 7.16%   |
| 5.3     | 424       | 5.93%   |
| 5.10    | 422       | 5.9%    |
| 4.15    | 419       | 5.86%   |
| 5.0     | 254       | 3.55%   |
| 5.16    | 238       | 3.33%   |
| 4.18    | 215       | 3.01%   |
| 5.19    | 159       | 2.22%   |
| 6.0     | 135       | 1.89%   |
| 5.17    | 105       | 1.47%   |
| 5.14    | 99        | 1.38%   |
| 5.9     | 95        | 1.33%   |
| 5.18    | 93        | 1.3%    |
| 4.19    | 89        | 1.24%   |
| 6.1     | 88        | 1.23%   |
| 5.12    | 88        | 1.23%   |
| 5.6     | 75        | 1.05%   |
| 4.9     | 72        | 1.01%   |
| 5.7     | 68        | 0.95%   |
| 5.5     | 42        | 0.59%   |
| 4.4     | 25        | 0.35%   |
| 5.2     | 23        | 0.32%   |
| 5.1     | 16        | 0.22%   |
| 4.14    | 10        | 0.14%   |
| 4.1     | 9         | 0.13%   |
| 3.10    | 8         | 0.11%   |
| 4.20    | 5         | 0.07%   |
| 4.13    | 5         | 0.07%   |
| 3.13    | 4         | 0.06%   |
| 4.16    | 3         | 0.04%   |
| 4.12    | 3         | 0.04%   |
| 4.8     | 2         | 0.03%   |
| 5       | 1         | 0.01%   |
| 4.6     | 1         | 0.01%   |
| 4.17    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6157      | 95.95%  |
| i686    | 173       | 2.7%    |
| aarch64 | 64        | 1%      |
| armv7l  | 23        | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3060      | 45.45%  |
| KDE5             | 1002      | 14.88%  |
| Unknown          | 911       | 13.53%  |
| X-Cinnamon       | 467       | 6.94%   |
| XFCE             | 449       | 6.67%   |
| KDE              | 175       | 2.6%    |
| MATE             | 173       | 2.57%   |
| Cinnamon         | 85        | 1.26%   |
| Pantheon         | 64        | 0.95%   |
| Unity            | 51        | 0.76%   |
| LXQt             | 46        | 0.68%   |
| LXDE             | 44        | 0.65%   |
| KDE4             | 36        | 0.53%   |
| Budgie           | 29        | 0.43%   |
| i3               | 26        | 0.39%   |
| GNOME Flashback  | 24        | 0.36%   |
| Deepin           | 13        | 0.19%   |
| Openbox          | 11        | 0.16%   |
| sway             | 10        | 0.15%   |
| GNOME Classic    | 9         | 0.13%   |
| awesome          | 8         | 0.12%   |
| qtile            | 7         | 0.1%    |
| lightdm-xsession | 7         | 0.1%    |
| xmonad           | 4         | 0.06%   |
| DWM              | 3         | 0.04%   |
| bspwm            | 3         | 0.04%   |
| trinity          | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| enlightenment    | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |
| icewm            | 1         | 0.01%   |
| Hyprland         | 1         | 0.01%   |
| GNUstep          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5210      | 79.08%  |
| Wayland | 776       | 11.78%  |
| Unknown | 452       | 6.86%   |
| Tty     | 149       | 2.26%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3838      | 57.35%  |
| SDDM    | 851       | 12.72%  |
| GDM     | 664       | 9.92%   |
| GDM3    | 554       | 8.28%   |
| LightDM | 517       | 7.73%   |
| TDM     | 196       | 2.93%   |
| KDM     | 35        | 0.52%   |
| XDM     | 14        | 0.21%   |
| LXDM    | 7         | 0.1%    |
| Ly      | 6         | 0.09%   |
| SLiM    | 4         | 0.06%   |
| GREETD  | 2         | 0.03%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 4703      | 71.56%  |
| Unknown        | 805       | 12.25%  |
| en_US          | 767       | 11.67%  |
| C              | 98        | 1.49%   |
| pl_PL          | 56        | 0.85%   |
| POSIX          | 13        | 0.2%    |
| ru_RU          | 11        | 0.17%   |
| en_IE          | 10        | 0.15%   |
| en_CA          | 10        | 0.15%   |
| de_DE          | 10        | 0.15%   |
| it_IT          | 9         | 0.14%   |
| fr_FR          | 7         | 0.11%   |
| ro_RO          | 6         | 0.09%   |
| en_IN          | 6         | 0.09%   |
| cs_CZ          | 6         | 0.09%   |
| hu_HU          | 5         | 0.08%   |
| es_ES          | 5         | 0.08%   |
| en_AU          | 5         | 0.08%   |
| pt_PT          | 4         | 0.06%   |
| zh_CN          | 3         | 0.05%   |
| sk_SK          | 3         | 0.05%   |
| pt_BR          | 3         | 0.05%   |
| C.UTF8         | 3         | 0.05%   |
| uk_UA          | 2         | 0.03%   |
| nl_NL          | 2         | 0.03%   |
| lt_LT          | 2         | 0.03%   |
| en_GB.iso88591 | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.02%   |
| tr_TR          | 1         | 0.02%   |
| ru_UA          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| fi_FI          | 1         | 0.02%   |
| en_ZA          | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GG          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3504      | 53.42%  |
| EFI  | 3055      | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5178      | 78.88%  |
| Btrfs    | 503       | 7.66%   |
| Overlay  | 450       | 6.86%   |
| Unknown  | 233       | 3.55%   |
| Xfs      | 90        | 1.37%   |
| Zfs      | 52        | 0.79%   |
| Ext2     | 20        | 0.3%    |
| Tmpfs    | 14        | 0.21%   |
| Ext3     | 11        | 0.17%   |
| F2fs     | 8         | 0.12%   |
| Aufs     | 2         | 0.03%   |
| Reiserfs | 1         | 0.02%   |
| Lvm      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4014      | 61.03%  |
| GPT     | 1974      | 30.01%  |
| MBR     | 589       | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5556      | 84.85%  |
| Yes       | 992       | 15.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4734      | 72.53%  |
| Yes       | 1793      | 27.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1022      | 15.94%  |
| ASUSTek Computer        | 933       | 14.55%  |
| Hewlett-Packard         | 811       | 12.65%  |
| Lenovo                  | 773       | 12.05%  |
| Gigabyte Technology     | 472       | 7.36%   |
| MSI                     | 352       | 5.49%   |
| Acer                    | 307       | 4.79%   |
| ASRock                  | 198       | 3.09%   |
| Apple                   | 185       | 2.88%   |
| Toshiba                 | 153       | 2.39%   |
| Intel                   | 116       | 1.81%   |
| Samsung Electronics     | 79        | 1.23%   |
| Raspberry Pi Foundation | 68        | 1.06%   |
| Valve                   | 62        | 0.97%   |
| Sony                    | 57        | 0.89%   |
| Fujitsu                 | 43        | 0.67%   |
| Unknown                 | 42        | 0.65%   |
| PC Specialist           | 41        | 0.64%   |
| Microsoft               | 39        | 0.61%   |
| HUAWEI                  | 36        | 0.56%   |
| Packard Bell            | 35        | 0.55%   |
| Google                  | 29        | 0.45%   |
| Foxconn                 | 29        | 0.45%   |
| Notebook                | 28        | 0.44%   |
| Alienware               | 24        | 0.37%   |
| Pegatron                | 21        | 0.33%   |
| Fujitsu Siemens         | 19        | 0.3%    |
| Star Labs               | 18        | 0.28%   |
| Razer                   | 18        | 0.28%   |
| Medion                  | 17        | 0.27%   |
| Biostar                 | 16        | 0.25%   |
| Dixonsxp                | 14        | 0.22%   |
| Linx                    | 13        | 0.2%    |
| GEO                     | 13        | 0.2%    |
| Entroware               | 13        | 0.2%    |
| AMI                     | 13        | 0.2%    |
| AZW                     | 11        | 0.17%   |
| Clevo                   | 10        | 0.16%   |
| Chuwi                   | 10        | 0.16%   |
| Advent                  | 10        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 66        | 1.03%   |
| Unknown                            | 65        | 1.01%   |
| Valve Jupiter                      | 62        | 0.97%   |
| Dell OptiPlex 7010                 | 27        | 0.42%   |
| MSI MS-7C02                        | 25        | 0.39%   |
| RPi Raspberry Pi                   | 22        | 0.34%   |
| HP Pavilion g6                     | 22        | 0.34%   |
| Dell OptiPlex 755                  | 20        | 0.31%   |
| MSI MS-7C37                        | 19        | 0.3%    |
| ASUS M5A78L-M/USB3                 | 19        | 0.3%    |
| Dell OptiPlex 780                  | 18        | 0.28%   |
| ASUS ROG STRIX B450-F GAMING       | 18        | 0.28%   |
| HP Pavilion 15                     | 17        | 0.27%   |
| ASUS TUF Gaming X570-PLUS          | 17        | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 16        | 0.25%   |
| Dell OptiPlex 790                  | 16        | 0.25%   |
| HP Pavilion Notebook               | 15        | 0.23%   |
| HP Notebook                        | 15        | 0.23%   |
| Dell XPS 15 7590                   | 15        | 0.23%   |
| Dell Inspiron 1545                 | 15        | 0.23%   |
| Dell XPS 15 9560                   | 13        | 0.2%    |
| Dell XPS 13 9370                   | 13        | 0.2%    |
| ASUS PRIME A320M-K                 | 13        | 0.2%    |
| Gigabyte X570 AORUS ELITE          | 12        | 0.19%   |
| Gigabyte 970A-DS3P                 | 12        | 0.19%   |
| Dell XPS 15 9570                   | 12        | 0.19%   |
| Dell XPS 13 9360                   | 12        | 0.19%   |
| Dell Latitude E6400                | 12        | 0.19%   |
| Lenovo V145-15AST 81MT             | 11        | 0.17%   |
| Gigabyte GA-78LMT-USB3             | 11        | 0.17%   |
| Dell XPS 13 9380                   | 11        | 0.17%   |
| Dell Latitude E6410                | 11        | 0.17%   |
| Toshiba Satellite C660             | 10        | 0.16%   |
| MSI MS-7C91                        | 10        | 0.16%   |
| Microsoft Surface Pro 4            | 10        | 0.16%   |
| HP ProLiant MicroServer            | 10        | 0.16%   |
| Gigabyte GA-78LMT-USB3 6.0         | 10        | 0.16%   |
| Dell XPS 15 9510                   | 10        | 0.16%   |
| Dell XPS 13 7390                   | 10        | 0.16%   |
| Dell Vostro 200                    | 10        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 362       | 5.64%   |
| Dell Latitude          | 229       | 3.57%   |
| Acer Aspire            | 225       | 3.51%   |
| Dell Inspiron          | 216       | 3.37%   |
| Dell OptiPlex          | 181       | 2.82%   |
| Dell XPS               | 171       | 2.67%   |
| HP Pavilion            | 140       | 2.18%   |
| ASUS ROG               | 136       | 2.12%   |
| Toshiba Satellite      | 134       | 2.09%   |
| Lenovo IdeaPad         | 119       | 1.86%   |
| ASUS PRIME             | 113       | 1.76%   |
| HP EliteBook           | 97        | 1.51%   |
| Dell Precision         | 93        | 1.45%   |
| HP Compaq              | 89        | 1.39%   |
| RPi Raspberry          | 68        | 1.06%   |
| ASUS All               | 66        | 1.03%   |
| Unknown                | 65        | 1.01%   |
| Valve Jupiter          | 62        | 0.97%   |
| Lenovo ThinkCentre     | 60        | 0.94%   |
| HP ProBook             | 55        | 0.86%   |
| HP Laptop              | 52        | 0.81%   |
| ASUS VivoBook          | 50        | 0.78%   |
| ASUS TUF               | 50        | 0.78%   |
| HP ENVY                | 48        | 0.75%   |
| Dell Vostro            | 45        | 0.7%    |
| Microsoft Surface      | 39        | 0.61%   |
| Lenovo Yoga            | 39        | 0.61%   |
| HP ProLiant            | 32        | 0.5%    |
| Gigabyte X570          | 32        | 0.5%    |
| ASUS M5A78L-M          | 27        | 0.42%   |
| Gigabyte GA-78LMT-USB3 | 26        | 0.41%   |
| MSI MS-7C02            | 25        | 0.39%   |
| HP EliteDesk           | 25        | 0.39%   |
| ASUS Zenbook           | 25        | 0.39%   |
| HP Stream              | 24        | 0.37%   |
| HP Spectre             | 23        | 0.36%   |
| Acer Swift             | 23        | 0.36%   |
| MSI MS-7C37            | 19        | 0.3%    |
| Lenovo Legion          | 19        | 0.3%    |
| Razer Blade            | 18        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 640       | 9.98%   |
| 2019    | 578       | 9.01%   |
| 2012    | 523       | 8.16%   |
| 2020    | 510       | 7.95%   |
| 2013    | 459       | 7.16%   |
| 2011    | 441       | 6.88%   |
| 2017    | 431       | 6.72%   |
| 2014    | 403       | 6.28%   |
| 2010    | 361       | 5.63%   |
| 2015    | 344       | 5.36%   |
| 2021    | 336       | 5.24%   |
| 2016    | 326       | 5.08%   |
| 2009    | 275       | 4.29%   |
| 2008    | 265       | 4.13%   |
| 2007    | 184       | 2.87%   |
| 2022    | 153       | 2.39%   |
| 2006    | 78        | 1.22%   |
| Unknown | 67        | 1.04%   |
| 2005    | 26        | 0.41%   |
| 2004    | 6         | 0.09%   |
| 2003    | 3         | 0.05%   |
| 2002    | 3         | 0.05%   |
| 2023    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3255      | 50.76%  |
| Desktop        | 2588      | 40.36%  |
| Convertible    | 122       | 1.9%    |
| Mini pc        | 116       | 1.81%   |
| All in one     | 108       | 1.68%   |
| Tablet         | 88        | 1.37%   |
| System on chip | 79        | 1.23%   |
| Server         | 51        | 0.8%    |
| Phone          | 4         | 0.06%   |
| Other          | 1         | 0.02%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5950      | 92.01%  |
| Enabled  | 517       | 7.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6365      | 99.25%  |
| Yes  | 48        | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1431      | 21.94%  |
| 16.01-24.0      | 1394      | 21.38%  |
| 3.01-4.0        | 1157      | 17.74%  |
| 8.01-16.0       | 1141      | 17.5%   |
| 32.01-64.0      | 656       | 10.06%  |
| 1.01-2.0        | 293       | 4.49%   |
| 64.01-256.0     | 172       | 2.64%   |
| 2.01-3.0        | 120       | 1.84%   |
| 24.01-32.0      | 90        | 1.38%   |
| 0.51-1.0        | 56        | 0.86%   |
| More than 256.0 | 7         | 0.11%   |
| 0.01-0.5        | 4         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2722      | 37.91%  |
| 2.01-3.0    | 1759      | 24.5%   |
| 4.01-8.0    | 928       | 12.92%  |
| 3.01-4.0    | 844       | 11.75%  |
| 0.51-1.0    | 485       | 6.75%   |
| 8.01-16.0   | 263       | 3.66%   |
| 0.01-0.5    | 102       | 1.42%   |
| 16.01-24.0  | 38        | 0.53%   |
| 24.01-32.0  | 18        | 0.25%   |
| 32.01-64.0  | 14        | 0.19%   |
| Unknown     | 4         | 0.06%   |
| 64.01-256.0 | 3         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3747      | 56.4%   |
| 2       | 1653      | 24.88%  |
| 3       | 541       | 8.14%   |
| 4       | 299       | 4.5%    |
| 5       | 163       | 2.45%   |
| 6       | 82        | 1.23%   |
| 0       | 67        | 1.01%   |
| 7       | 35        | 0.53%   |
| 9       | 14        | 0.21%   |
| 8       | 14        | 0.21%   |
| Unknown | 8         | 0.12%   |
| 11      | 6         | 0.09%   |
| 12      | 5         | 0.08%   |
| 10      | 4         | 0.06%   |
| 13      | 3         | 0.05%   |
| 21      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 14      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3776      | 58.22%  |
| Yes       | 2710      | 41.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5431      | 84.57%  |
| No        | 991       | 15.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4879      | 75.43%  |
| No        | 1589      | 24.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3706      | 57.08%  |
| No        | 2787      | 42.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 6413      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 419       | 5.95%   |
| Manchester          | 149       | 2.12%   |
| Birmingham          | 116       | 1.65%   |
| Bristol             | 112       | 1.59%   |
| Glasgow             | 101       | 1.44%   |
| Edinburgh           | 95        | 1.35%   |
| Sheffield           | 90        | 1.28%   |
| Nottingham          | 88        | 1.25%   |
| Liverpool           | 80        | 1.14%   |
| Leeds               | 76        | 1.08%   |
| Reading             | 63        | 0.9%    |
| Norwich             | 59        | 0.84%   |
| Islington           | 59        | 0.84%   |
| Cambridge           | 59        | 0.84%   |
| Southampton         | 49        | 0.7%    |
| Milton Keynes       | 48        | 0.68%   |
| Derby               | 47        | 0.67%   |
| Croydon             | 46        | 0.65%   |
| Coventry            | 45        | 0.64%   |
| Leicester           | 39        | 0.55%   |
| Cardiff             | 39        | 0.55%   |
| Aberdeen            | 38        | 0.54%   |
| Bradford            | 37        | 0.53%   |
| Wolverhampton       | 36        | 0.51%   |
| Swindon             | 36        | 0.51%   |
| Oxford              | 36        | 0.51%   |
| Gloucester          | 36        | 0.51%   |
| Hackney             | 35        | 0.5%    |
| York                | 34        | 0.48%   |
| Newcastle upon Tyne | 34        | 0.48%   |
| Brighton            | 34        | 0.48%   |
| Bolton              | 33        | 0.47%   |
| Wigan               | 32        | 0.45%   |
| Plymouth            | 32        | 0.45%   |
| Kensington          | 31        | 0.44%   |
| Clapham             | 30        | 0.43%   |
| Walsall             | 29        | 0.41%   |
| Harrow              | 29        | 0.41%   |
| Sunderland          | 28        | 0.4%    |
| Bromley             | 28        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1481      | 2442   | 15.31%  |
| Samsung Electronics       | 1465      | 2277   | 15.15%  |
| WDC                       | 1375      | 2258   | 14.21%  |
| Toshiba                   | 665       | 901    | 6.87%   |
| SanDisk                   | 564       | 742    | 5.83%   |
| Unknown                   | 521       | 717    | 5.39%   |
| Crucial                   | 502       | 721    | 5.19%   |
| Kingston                  | 411       | 564    | 4.25%   |
| Hitachi                   | 376       | 514    | 3.89%   |
| SK hynix                  | 197       | 233    | 2.04%   |
| Intel                     | 197       | 264    | 2.04%   |
| HGST                      | 156       | 226    | 1.61%   |
| Phison                    | 148       | 199    | 1.53%   |
| Micron Technology         | 97        | 116    | 1%      |
| Apple                     | 97        | 133    | 1%      |
| China                     | 95        | 131    | 0.98%   |
| A-DATA Technology         | 92        | 119    | 0.95%   |
| OCZ                       | 60        | 69     | 0.62%   |
| PNY                       | 58        | 72     | 0.6%    |
| KIOXIA                    | 58        | 77     | 0.6%    |
| Maxtor                    | 57        | 86     | 0.59%   |
| LITEON                    | 52        | 62     | 0.54%   |
| Silicon Motion            | 49        | 62     | 0.51%   |
| Transcend                 | 46        | 56     | 0.48%   |
| Corsair                   | 46        | 64     | 0.48%   |
| Fujitsu                   | 42        | 59     | 0.43%   |
| Phison Electronics        | 35        | 47     | 0.36%   |
| Unknown                   | 32        | 41     | 0.33%   |
| LITEONIT                  | 30        | 37     | 0.31%   |
| Micron/Crucial Technology | 29        | 40     | 0.3%    |
| JMicron Technology        | 25        | 37     | 0.26%   |
| Integral                  | 24        | 29     | 0.25%   |
| Patriot                   | 22        | 34     | 0.23%   |
| ASMT                      | 22        | 52     | 0.23%   |
| SABRENT                   | 20        | 22     | 0.21%   |
| Netac                     | 20        | 25     | 0.21%   |
| Gigabyte Technology       | 17        | 24     | 0.18%   |
| Drevo                     | 16        | 24     | 0.17%   |
| SPCC                      | 15        | 25     | 0.16%   |
| Hewlett-Packard           | 15        | 47     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 111       | 1.02%   |
| Seagate ST3500312CS 500GB              | 82        | 0.75%   |
| Samsung SSD 850 EVO 250GB              | 80        | 0.73%   |
| Kingston SA400S37240G 240GB SSD        | 78        | 0.72%   |
| Samsung SSD 850 EVO 500GB              | 73        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB         | 71        | 0.65%   |
| Crucial CT1000MX500SSD1 1TB            | 67        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 66        | 0.61%   |
| Crucial CT500MX500SSD1 500GB           | 66        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB         | 64        | 0.59%   |
| Unknown MMC Card  64GB                 | 63        | 0.58%   |
| Samsung NVMe SSD Drive 500GB           | 63        | 0.58%   |
| Kingston SA400S37120G 120GB SSD        | 63        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB         | 61        | 0.56%   |
| Samsung SSD 860 EVO 500GB              | 61        | 0.56%   |
| Samsung SSD 860 EVO 1TB                | 56        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB           | 55        | 0.51%   |
| Seagate ST500DM002-1BD142 500GB        | 54        | 0.5%    |
| Samsung NVMe SSD Drive 512GB           | 54        | 0.5%    |
| Unknown MMC Card  128GB                | 53        | 0.49%   |
| Toshiba MQ01ABD100 1TB                 | 50        | 0.46%   |
| Samsung NVMe SSD Drive 1TB             | 50        | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 49        | 0.45%   |
| Crucial CT240BX500SSD1 240GB           | 45        | 0.41%   |
| Crucial CT250MX500SSD1 250GB           | 41        | 0.38%   |
| Unknown SD/MMC/MS PRO 2GB              | 39        | 0.36%   |
| Samsung SSD 840 EVO 250GB              | 39        | 0.36%   |
| Seagate Expansion 240GB                | 38        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD       | 38        | 0.35%   |
| HGST HTS721010A9E630 1TB               | 36        | 0.33%   |
| Toshiba DT01ACA100 1TB                 | 35        | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB         | 34        | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB         | 34        | 0.31%   |
| Toshiba NVMe SSD Drive 256GB           | 33        | 0.3%    |
| Toshiba MQ01ABF050 500GB               | 33        | 0.3%    |
| SanDisk NVMe SSD Drive 1TB             | 33        | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB         | 32        | 0.29%   |
| SanDisk SSD PLUS 480GB                 | 32        | 0.29%   |
| Unknown                                | 32        | 0.29%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 31        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1435      | 2343   | 35.61%  |
| WDC                 | 1085      | 1830   | 26.92%  |
| Toshiba             | 488       | 669    | 12.11%  |
| Hitachi             | 375       | 512    | 9.31%   |
| Samsung Electronics | 206       | 290    | 5.11%   |
| HGST                | 156       | 226    | 3.87%   |
| Maxtor              | 47        | 75     | 1.17%   |
| Unknown             | 46        | 61     | 1.14%   |
| Apple               | 45        | 55     | 1.12%   |
| Fujitsu             | 42        | 59     | 1.04%   |
| ASMT                | 22        | 52     | 0.55%   |
| SABRENT             | 19        | 21     | 0.47%   |
| Hewlett-Packard     | 14        | 46     | 0.35%   |
| USB3.0              | 8         | 13     | 0.2%    |
| ASMedia             | 6         | 12     | 0.15%   |
| WD MediaMax         | 3         | 3      | 0.07%   |
| USB                 | 3         | 3      | 0.07%   |
| HPE                 | 3         | 5      | 0.07%   |
| ASMT109x            | 3         | 5      | 0.07%   |
| LaCie               | 2         | 2      | 0.05%   |
| KESU                | 2         | 6      | 0.05%   |
| JMicron Technology  | 2         | 4      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 4      | 0.05%   |
| TrueNAS             | 1         | 3      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| Advantech           | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 749       | 1100   | 22.98%  |
| Crucial             | 464       | 677    | 14.24%  |
| SanDisk             | 393       | 493    | 12.06%  |
| Kingston            | 353       | 479    | 10.83%  |
| WDC                 | 176       | 244    | 5.4%    |
| China               | 91        | 127    | 2.79%   |
| Intel               | 81        | 92     | 2.49%   |
| A-DATA Technology   | 72        | 91     | 2.21%   |
| OCZ                 | 60        | 69     | 1.84%   |
| Toshiba             | 57        | 69     | 1.75%   |
| PNY                 | 55        | 65     | 1.69%   |
| Micron Technology   | 52        | 63     | 1.6%    |
| LITEON              | 51        | 61     | 1.56%   |
| SK hynix            | 50        | 62     | 1.53%   |
| Apple               | 45        | 59     | 1.38%   |
| Transcend           | 42        | 52     | 1.29%   |
| LITEONIT            | 30        | 37     | 0.92%   |
| Corsair             | 27        | 39     | 0.83%   |
| Integral            | 24        | 29     | 0.74%   |
| Patriot             | 22        | 34     | 0.68%   |
| Seagate             | 19        | 22     | 0.58%   |
| Netac               | 19        | 22     | 0.58%   |
| Drevo               | 16        | 24     | 0.49%   |
| Unknown             | 14        | 19     | 0.43%   |
| Team                | 13        | 14     | 0.4%    |
| Lexar               | 13        | 15     | 0.4%    |
| SPCC                | 12        | 22     | 0.37%   |
| JMicron Technology  | 12        | 18     | 0.37%   |
| Gigabyte Technology | 12        | 17     | 0.37%   |
| Vaseky              | 11        | 15     | 0.34%   |
| TO Exter            | 11        | 13     | 0.34%   |
| TCSUNBOW            | 11        | 16     | 0.34%   |
| Maxtor              | 10        | 11     | 0.31%   |
| KIOXIA-EXCERIA      | 10        | 14     | 0.31%   |
| ORTIAL              | 7         | 7      | 0.21%   |
| KingDian            | 7         | 10     | 0.21%   |
| Star                | 6         | 7      | 0.18%   |
| Plextor             | 6         | 9      | 0.18%   |
| NGFF                | 6         | 6      | 0.18%   |
| KingSpec            | 6         | 8      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3262      | 6324   | 38.57%  |
| SSD     | 2758      | 4415   | 32.61%  |
| NVMe    | 1830      | 2634   | 21.64%  |
| MMC     | 470       | 633    | 5.56%   |
| Unknown | 138       | 205    | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4877      | 10235  | 64.18%  |
| NVMe | 1826      | 2622   | 24.03%  |
| MMC  | 470       | 633    | 6.19%   |
| SAS  | 426       | 721    | 5.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3659      | 6041   | 56.34%  |
| 0.51-1.0   | 1724      | 2644   | 26.55%  |
| 1.01-2.0   | 587       | 1017   | 9.04%   |
| 3.01-4.0   | 189       | 343    | 2.91%   |
| 4.01-10.0  | 163       | 361    | 2.51%   |
| 2.01-3.0   | 151       | 280    | 2.33%   |
| 10.01-20.0 | 20        | 52     | 0.31%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1856      | 27.28%  |
| 251-500        | 1325      | 19.48%  |
| 501-1000       | 1016      | 14.93%  |
| 1001-2000      | 530       | 7.79%   |
| 1-20           | 471       | 6.92%   |
| 51-100         | 448       | 6.59%   |
| More than 3000 | 406       | 5.97%   |
| 21-50          | 324       | 4.76%   |
| 2001-3000      | 217       | 3.19%   |
| Unknown        | 210       | 3.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2841      | 40.15%  |
| 21-50          | 1136      | 16.05%  |
| 101-250        | 834       | 11.79%  |
| 51-100         | 734       | 10.37%  |
| 251-500        | 507       | 7.17%   |
| 501-1000       | 348       | 4.92%   |
| 1001-2000      | 231       | 3.26%   |
| Unknown        | 210       | 2.97%   |
| More than 3000 | 151       | 2.13%   |
| 2001-3000      | 83        | 1.17%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 6         | 10     | 1.24%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.24%   |
| Seagate ST9500325AS 500GB                | 5         | 7      | 1.03%   |
| Seagate ST500DM002-1BD142 500GB          | 5         | 5      | 1.03%   |
| Seagate ST3500418AS 500GB                | 5         | 5      | 1.03%   |
| Seagate ST3500312CS 500GB                | 5         | 7      | 1.03%   |
| Samsung Electronics HD103UJ 1TB          | 5         | 7      | 1.03%   |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.83%   |
| Hitachi HTS547575A9E384 752GB            | 4         | 6      | 0.83%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.83%   |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.83%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 0.83%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.62%   |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.62%   |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.62%   |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.62%   |
| SanDisk SSD PLUS 480GB                   | 3         | 3      | 0.62%   |
| Samsung Electronics SSD 960 EVO 250GB    | 3         | 4      | 0.62%   |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.62%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 0.62%   |
| Hitachi HUA723030ALA640 3TB              | 3         | 4      | 0.62%   |
| Hitachi HTS542512K9SA00 120GB            | 3         | 3      | 0.62%   |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.62%   |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.62%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.62%   |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.62%   |
| WDC WD800JD-00HKA0 80GB                  | 2         | 2      | 0.41%   |
| WDC WD6400AAKS-22A7B2 640GB              | 2         | 2      | 0.41%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2         | 2      | 0.41%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 2         | 3      | 0.41%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2         | 2      | 0.41%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.41%   |
| WDC WD2500BEVT-80A23T0 250GB             | 2         | 4      | 0.41%   |
| WDC WD2002FYPS-02W3B0 2TB                | 2         | 9      | 0.41%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 2         | 2      | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB                  | 2         | 3      | 0.41%   |
| WDC WD10EADS-00L5B1 1TB                  | 2         | 2      | 0.41%   |
| Unknown MM0500EBKAE 500GB                | 2         | 2      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 145    | 25.59%  |
| WDC                 | 96        | 149    | 20.47%  |
| Hitachi             | 60        | 83     | 12.79%  |
| Samsung Electronics | 41        | 53     | 8.74%   |
| Toshiba             | 29        | 35     | 6.18%   |
| Crucial             | 22        | 28     | 4.69%   |
| HGST                | 17        | 20     | 3.62%   |
| SanDisk             | 12        | 16     | 2.56%   |
| Intel               | 12        | 16     | 2.56%   |
| Kingston            | 8         | 10     | 1.71%   |
| SK hynix            | 5         | 5      | 1.07%   |
| Micron Technology   | 5         | 5      | 1.07%   |
| LITEON              | 5         | 5      | 1.07%   |
| A-DATA Technology   | 5         | 5      | 1.07%   |
| Maxtor              | 4         | 4      | 0.85%   |
| Fujitsu             | 4         | 4      | 0.85%   |
| Hewlett-Packard     | 3         | 3      | 0.64%   |
| Corsair             | 3         | 7      | 0.64%   |
| Unknown             | 2         | 2      | 0.43%   |
| Drevo               | 2         | 5      | 0.43%   |
| Zheino              | 1         | 2      | 0.21%   |
| WD MediaMax         | 1         | 1      | 0.21%   |
| VENO                | 1         | 1      | 0.21%   |
| Team                | 1         | 1      | 0.21%   |
| OCZ                 | 1         | 1      | 0.21%   |
| Faspeed             | 1         | 1      | 0.21%   |
| China               | 1         | 1      | 0.21%   |
| BIWIN               | 1         | 1      | 0.21%   |
| BAITITON            | 1         | 4      | 0.21%   |
| Apple               | 1         | 2      | 0.21%   |
| Apacer              | 1         | 1      | 0.21%   |
| AGI                 | 1         | 1      | 0.21%   |
| 2-Power             | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 145    | 34.09%  |
| WDC                 | 94        | 147    | 26.7%   |
| Hitachi             | 60        | 83     | 17.05%  |
| Toshiba             | 28        | 34     | 7.95%   |
| Samsung Electronics | 18        | 25     | 5.11%   |
| HGST                | 17        | 20     | 4.83%   |
| Maxtor              | 4         | 4      | 1.14%   |
| Fujitsu             | 4         | 4      | 1.14%   |
| Hewlett-Packard     | 3         | 3      | 0.85%   |
| Unknown             | 2         | 2      | 0.57%   |
| WD MediaMax         | 1         | 1      | 0.28%   |
| Apple               | 1         | 2      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 319       | 470    | 73.17%  |
| SSD  | 99        | 126    | 22.71%  |
| NVMe | 18        | 23     | 4.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB  | 2         | 3      | 25%     |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 12.5%   |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 12.5%   |
| Seagate ST3160815AS 160GB         | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 12.5%   |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 5      | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| Seagate             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4354      | 9455   | 63.17%  |
| Works    | 2107      | 4128   | 30.57%  |
| Malfunc  | 424       | 619    | 6.15%   |
| Failed   | 7         | 9      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4068      | 50.84%  |
| AMD                              | 1386      | 17.32%  |
| Samsung Electronics              | 707       | 8.84%   |
| SanDisk                          | 299       | 3.74%   |
| Phison Electronics               | 206       | 2.57%   |
| ASMedia Technology               | 162       | 2.02%   |
| Nvidia                           | 145       | 1.81%   |
| SK hynix                         | 143       | 1.79%   |
| Toshiba America Info Systems     | 137       | 1.71%   |
| Marvell Technology Group         | 109       | 1.36%   |
| JMicron Technology               | 83        | 1.04%   |
| Kingston Technology Company      | 70        | 0.87%   |
| Micron/Crucial Technology        | 66        | 0.82%   |
| Silicon Motion                   | 56        | 0.7%    |
| KIOXIA                           | 53        | 0.66%   |
| Micron Technology                | 48        | 0.6%    |
| ADATA Technology                 | 34        | 0.42%   |
| LSI Logic / Symbios Logic        | 31        | 0.39%   |
| VIA Technologies                 | 21        | 0.26%   |
| Broadcom / LSI                   | 21        | 0.26%   |
| Silicon Image                    | 19        | 0.24%   |
| Seagate Technology               | 19        | 0.24%   |
| Silicon Integrated Systems [SiS] | 15        | 0.19%   |
| Hewlett-Packard                  | 13        | 0.16%   |
| Apple                            | 12        | 0.15%   |
| O2 Micro                         | 10        | 0.12%   |
| Adaptec                          | 10        | 0.12%   |
| Realtek Semiconductor            | 8         | 0.1%    |
| Lenovo                           | 8         | 0.1%    |
| Solid State Storage Technology   | 7         | 0.09%   |
| Union Memory (Shenzhen)          | 6         | 0.07%   |
| Shenzhen Longsys Electronics     | 5         | 0.06%   |
| Lite-On Technology               | 4         | 0.05%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Solidigm                         | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 925       | 9.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 384       | 4.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 271       | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 262       | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 245       | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 221       | 2.35%   |
| AMD 400 Series Chipset SATA Controller                                         | 196       | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 173       | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 166       | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 164       | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 155       | 1.65%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 155       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 153       | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 134       | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 119       | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 119       | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 118       | 1.25%   |
| Intel SATA Controller [RAID mode]                                              | 117       | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 114       | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 107       | 1.14%   |
| Phison E12 NVMe Controller                                                     | 105       | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 105       | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 104       | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 102       | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 101       | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 97        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                | 88        | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 88        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 85        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 85        | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 75        | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 74        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 73        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 73        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 72        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 68        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 68        | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 64        | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 59        | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 59        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4586      | 56.8%   |
| NVMe | 1847      | 22.88%  |
| IDE  | 1045      | 12.94%  |
| RAID | 537       | 6.65%   |
| SAS  | 34        | 0.42%   |
| SCSI | 25        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4673      | 72.87%  |
| AMD          | 1654      | 25.79%  |
| ARM          | 84        | 1.31%   |
| QUALCOMM     | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 75        | 1.17%   |
| ARM Processor                           | 62        | 0.96%   |
| AMD Custom APU 0405                     | 62        | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 60        | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 59        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 49        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 46        | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 45        | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 44        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 42        | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 40        | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 39        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 39        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 39        | 0.61%   |
| AMD FX-8350 Eight-Core Processor        | 39        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 38        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 38        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 38        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 37        | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 36        | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 36        | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 36        | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 35        | 0.54%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 35        | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 34        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 34        | 0.53%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 34        | 0.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 33        | 0.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 32        | 0.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 31        | 0.48%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 31        | 0.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 29        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 29        | 0.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 29        | 0.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 28        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 28        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 27        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 0.4%    |
| Intel Celeron N4000 CPU @ 1.10GHz       | 26        | 0.4%    |
| Intel Celeron CPU N3350 @ 1.10GHz       | 26        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1288      | 20.05%  |
| Intel Core i7           | 1227      | 19.1%   |
| Intel Core i3           | 403       | 6.27%   |
| Other                   | 386       | 6.01%   |
| AMD Ryzen 5             | 326       | 5.07%   |
| Intel Celeron           | 315       | 4.9%    |
| Intel Core 2 Duo        | 299       | 4.65%   |
| AMD Ryzen 7             | 272       | 4.23%   |
| Intel Xeon              | 190       | 2.96%   |
| Intel Pentium           | 172       | 2.68%   |
| AMD FX                  | 138       | 2.15%   |
| AMD Ryzen 9             | 119       | 1.85%   |
| Intel Atom              | 117       | 1.82%   |
| AMD A6                  | 75        | 1.17%   |
| AMD Ryzen 3             | 74        | 1.15%   |
| AMD A8                  | 74        | 1.15%   |
| Intel Pentium Dual-Core | 71        | 1.11%   |
| Intel Core 2 Quad       | 63        | 0.98%   |
| AMD A10                 | 55        | 0.86%   |
| Intel Core 2            | 54        | 0.84%   |
| Intel Core i9           | 47        | 0.73%   |
| Intel Pentium Dual      | 42        | 0.65%   |
| AMD A4                  | 39        | 0.61%   |
| AMD Athlon II X2        | 38        | 0.59%   |
| AMD Phenom II X4        | 31        | 0.48%   |
| Intel Genuine           | 26        | 0.4%    |
| Intel Pentium 4         | 23        | 0.36%   |
| AMD Athlon 64 X2        | 23        | 0.36%   |
| AMD Ryzen Threadripper  | 22        | 0.34%   |
| AMD E1                  | 22        | 0.34%   |
| AMD Athlon              | 22        | 0.34%   |
| ARM BCM                 | 21        | 0.33%   |
| AMD E                   | 21        | 0.33%   |
| Intel Celeron Dual-Core | 19        | 0.3%    |
| Intel Pentium Silver    | 16        | 0.25%   |
| AMD Athlon II X4        | 16        | 0.25%   |
| Intel Pentium D         | 15        | 0.23%   |
| Intel Celeron M         | 14        | 0.22%   |
| AMD Phenom              | 14        | 0.22%   |
| AMD Phenom II X6        | 13        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2649      | 41.24%  |
| 4       | 2261      | 35.2%   |
| 6       | 592       | 9.22%   |
| 8       | 452       | 7.04%   |
| 1       | 177       | 2.76%   |
| 12      | 102       | 1.59%   |
| 16      | 63        | 0.98%   |
| 3       | 57        | 0.89%   |
| 14      | 23        | 0.36%   |
| 10      | 18        | 0.28%   |
| 24      | 12        | 0.19%   |
| 32      | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 64      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6322      | 98.58%  |
| 2       | 84        | 1.31%   |
| Unknown | 3         | 0.05%   |
| 4       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4072      | 63.44%  |
| 1       | 2344      | 36.52%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6191      | 96.13%  |
| Unknown        | 171       | 2.66%   |
| 32-bit         | 73        | 1.13%   |
| 64-bit         | 5         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1538      | 23.13%  |
| 0x306a9    | 352       | 5.29%   |
| 0x206a7    | 350       | 5.26%   |
| 0x306c3    | 290       | 4.36%   |
| 0x1067a    | 259       | 3.9%    |
| 0x906ea    | 156       | 2.35%   |
| 0x806ea    | 136       | 2.05%   |
| 0x506e3    | 132       | 1.99%   |
| 0x08701021 | 127       | 1.91%   |
| 0x806ec    | 120       | 1.8%    |
| 0x406e3    | 119       | 1.79%   |
| 0x806e9    | 116       | 1.74%   |
| 0x40651    | 116       | 1.74%   |
| 0x20655    | 114       | 1.71%   |
| 0x906e9    | 104       | 1.56%   |
| 0x306d4    | 100       | 1.5%    |
| 0x806c1    | 97        | 1.46%   |
| 0x6fd      | 92        | 1.38%   |
| 0x406c4    | 84        | 1.26%   |
| 0x010000c8 | 76        | 1.14%   |
| 0x06000852 | 73        | 1.1%    |
| 0x30678    | 70        | 1.05%   |
| 0x06001119 | 65        | 0.98%   |
| 0x10676    | 60        | 0.9%    |
| 0x0800820d | 60        | 0.9%    |
| 0x08108109 | 54        | 0.81%   |
| 0x08701013 | 53        | 0.8%    |
| 0xa0652    | 49        | 0.74%   |
| 0x6fb      | 49        | 0.74%   |
| 0x506c9    | 47        | 0.71%   |
| 0x906ed    | 45        | 0.68%   |
| 0x20652    | 45        | 0.68%   |
| 0x706e5    | 43        | 0.65%   |
| 0x06006705 | 43        | 0.65%   |
| 0x406c3    | 39        | 0.59%   |
| 0x706a1    | 38        | 0.57%   |
| 0x08108102 | 38        | 0.57%   |
| 0x206c2    | 36        | 0.54%   |
| 0x06003106 | 36        | 0.54%   |
| 0x6f6      | 35        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 929       | 14.46%  |
| Haswell          | 535       | 8.33%   |
| SandyBridge      | 458       | 7.13%   |
| IvyBridge        | 450       | 7%      |
| Penryn           | 372       | 5.79%   |
| Skylake          | 324       | 5.04%   |
| Zen 2            | 322       | 5.01%   |
| Core             | 250       | 3.89%   |
| Silvermont       | 238       | 3.7%    |
| Westmere         | 236       | 3.67%   |
| Unknown          | 232       | 3.61%   |
| Zen+             | 211       | 3.28%   |
| Piledriver       | 186       | 2.89%   |
| K10              | 168       | 2.61%   |
| Zen              | 141       | 2.19%   |
| Broadwell        | 139       | 2.16%   |
| Zen 3            | 135       | 2.1%    |
| TigerLake        | 126       | 1.96%   |
| CometLake        | 112       | 1.74%   |
| Excavator        | 106       | 1.65%   |
| IceLake          | 85        | 1.32%   |
| Goldmont plus    | 80        | 1.25%   |
| Nehalem          | 77        | 1.2%    |
| Goldmont         | 57        | 0.89%   |
| K8 Hammer        | 56        | 0.87%   |
| Steamroller      | 52        | 0.81%   |
| Puma             | 52        | 0.81%   |
| Bobcat           | 45        | 0.7%    |
| NetBurst         | 43        | 0.67%   |
| Bonnell          | 43        | 0.67%   |
| P6               | 39        | 0.61%   |
| Alderlake Hybrid | 36        | 0.56%   |
| Jaguar           | 27        | 0.42%   |
| Bulldozer        | 26        | 0.4%    |
| K8 & K10 hybrid  | 12        | 0.19%   |
| K10 Llano        | 11        | 0.17%   |
| Tremont          | 10        | 0.16%   |
| K6               | 4         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3509      | 48.53%  |
| Nvidia                                       | 2012      | 27.83%  |
| AMD                                          | 1633      | 22.59%  |
| Matrox Electronics Systems                   | 35        | 0.48%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.21%   |
| ASPEED Technology                            | 10        | 0.14%   |
| ATI Technologies                             | 8         | 0.11%   |
| VIA Technologies                             | 5         | 0.07%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 335       | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 247       | 3.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 156       | 2.09%   |
| Intel UHD Graphics 620                                                                   | 149       | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 145       | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 143       | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 141       | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 140       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 139       | 1.86%   |
| Intel HD Graphics 620                                                                    | 123       | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 122       | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 121       | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 115       | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 114       | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 102       | 1.36%   |
| Intel HD Graphics 5500                                                                   | 98        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 98        | 1.31%   |
| Intel HD Graphics 630                                                                    | 96        | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 95        | 1.27%   |
| Intel HD Graphics 530                                                                    | 88        | 1.18%   |
| AMD Renoir                                                                               | 84        | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 82        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 80        | 1.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 77        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 62        | 0.83%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 62        | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 57        | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 56        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 56        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 54        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 51        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 0.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 48        | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 48        | 0.64%   |
| Intel HD Graphics 500                                                                    | 46        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 45        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 42        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 2728      | 42.16%  |
| 1 x AMD                              | 1394      | 21.55%  |
| 1 x Nvidia                           | 1302      | 20.12%  |
| Intel + Nvidia                       | 602       | 9.3%    |
| Intel + AMD                          | 95        | 1.47%   |
| Other                                | 93        | 1.44%   |
| 2 x AMD                              | 73        | 1.13%   |
| AMD + Nvidia                         | 68        | 1.05%   |
| 1 x Matrox                           | 31        | 0.48%   |
| 2 x Nvidia                           | 29        | 0.45%   |
| 1 x SiS                              | 14        | 0.22%   |
| 2 x Intel                            | 9         | 0.14%   |
| Nvidia + ASPEED                      | 6         | 0.09%   |
| 1 x VIA                              | 5         | 0.08%   |
| 1 x ASPEED                           | 4         | 0.06%   |
| Nvidia + Matrox                      | 3         | 0.05%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.03%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia             | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x XGI                              | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.02%   |
| 1 x Huawei Technologies              | 1         | 0.02%   |
| AMD + SiS                            | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5061      | 77.47%  |
| Proprietary | 1150      | 17.6%   |
| Unknown     | 322       | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3656      | 55.18%  |
| 0.01-0.5   | 769       | 11.61%  |
| 1.01-2.0   | 724       | 10.93%  |
| 0.51-1.0   | 478       | 7.21%   |
| 3.01-4.0   | 400       | 6.04%   |
| 7.01-8.0   | 304       | 4.59%   |
| 5.01-6.0   | 154       | 2.32%   |
| 8.01-16.0  | 89        | 1.34%   |
| 2.01-3.0   | 46        | 0.69%   |
| 16.01-24.0 | 3         | 0.05%   |
| 4.01-5.0   | 1         | 0.02%   |
| 24.01-32.0 | 1         | 0.02%   |
| 0          | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 802       | 11.79%  |
| AU Optronics            | 756       | 11.11%  |
| LG Display              | 584       | 8.58%   |
| Dell                    | 481       | 7.07%   |
| Chimei Innolux          | 430       | 6.32%   |
| BOE                     | 402       | 5.91%   |
| Acer                    | 299       | 4.4%    |
| Goldstar                | 240       | 3.53%   |
| Hewlett-Packard         | 226       | 3.32%   |
| BenQ                    | 209       | 3.07%   |
| AOC                     | 209       | 3.07%   |
| Sharp                   | 205       | 3.01%   |
| Apple                   | 147       | 2.16%   |
| Iiyama                  | 139       | 2.04%   |
| Ancor Communications    | 128       | 1.88%   |
| Lenovo                  | 124       | 1.82%   |
| Philips                 | 108       | 1.59%   |
| ViewSonic               | 78        | 1.15%   |
| Chi Mei Optoelectronics | 75        | 1.1%    |
| Sony                    | 74        | 1.09%   |
| Unknown                 | 64        | 0.94%   |
| HannStar                | 56        | 0.82%   |
| ASUSTek Computer        | 56        | 0.82%   |
| PANDA                   | 54        | 0.79%   |
| Panasonic               | 50        | 0.73%   |
| LG Philips              | 45        | 0.66%   |
| Toshiba                 | 42        | 0.62%   |
| LG Electronics          | 39        | 0.57%   |
| Vestel Elektronik       | 37        | 0.54%   |
| InfoVision              | 37        | 0.54%   |
| MSI                     | 30        | 0.44%   |
| NEC Computers           | 29        | 0.43%   |
| Analogix                | 26        | 0.38%   |
| ANX                     | 21        | 0.31%   |
| Gigabyte Technology     | 18        | 0.26%   |
| Valve                   | 17        | 0.25%   |
| Hitachi                 | 17        | 0.25%   |
| OEM                     | 16        | 0.24%   |
| MiTAC                   | 14        | 0.21%   |
| Fujitsu Siemens         | 14        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 40        | 0.57%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 37        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 31        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 30        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 29        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 27        | 0.38%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 25        | 0.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 24        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 24        | 0.34%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 21        | 0.3%    |
| ANX ANX7530 U ANX7539 800x1280                                        | 21        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 19        | 0.27%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 19        | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 17        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 17        | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 16        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 15        | 0.21%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 15        | 0.21%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 15        | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 15        | 0.21%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 14        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 14        | 0.2%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 14        | 0.2%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 14        | 0.2%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 13        | 0.18%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 13        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 13        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 13        | 0.18%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 13        | 0.18%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 13        | 0.18%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 12        | 0.17%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.17%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 12        | 0.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 12        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2687      | 40.87%  |
| 1366x768 (WXGA)    | 1119      | 17.02%  |
| 3840x2160 (4K)     | 496       | 7.54%   |
| 2560x1440 (QHD)    | 346       | 5.26%   |
| 1280x1024 (SXGA)   | 228       | 3.47%   |
| 1280x800 (WXGA)    | 193       | 2.94%   |
| 1600x900 (HD+)     | 182       | 2.77%   |
| 1440x900 (WXGA+)   | 177       | 2.69%   |
| 1680x1050 (WSXGA+) | 174       | 2.65%   |
| 1920x1200 (WUXGA)  | 147       | 2.24%   |
| Unknown            | 101       | 1.54%   |
| 3440x1440          | 82        | 1.25%   |
| 800x1280           | 62        | 0.94%   |
| 1360x768           | 57        | 0.87%   |
| 2560x1080          | 49        | 0.75%   |
| 3840x1080          | 46        | 0.7%    |
| 1920x540           | 42        | 0.64%   |
| 2560x1600          | 39        | 0.59%   |
| 3840x2400          | 29        | 0.44%   |
| 1024x768 (XGA)     | 29        | 0.44%   |
| 3200x1800 (QHD+)   | 24        | 0.37%   |
| 2736x1824          | 22        | 0.33%   |
| 1600x1200          | 22        | 0.33%   |
| 2880x1800          | 19        | 0.29%   |
| 1280x720 (HD)      | 18        | 0.27%   |
| 1024x600           | 18        | 0.27%   |
| 2160x1440          | 16        | 0.24%   |
| 2288x1287          | 10        | 0.15%   |
| 1920x1280          | 9         | 0.14%   |
| 5760x1080          | 7         | 0.11%   |
| 5120x1440          | 7         | 0.11%   |
| 7680x2160          | 5         | 0.08%   |
| 3840x1200          | 5         | 0.08%   |
| 3072x1920          | 5         | 0.08%   |
| 2256x1504          | 5         | 0.08%   |
| 1680x945           | 5         | 0.08%   |
| 3200x1080          | 4         | 0.06%   |
| 2880x1920          | 4         | 0.06%   |
| 5760x2160          | 3         | 0.05%   |
| 4480x1440          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1544      | 22.8%   |
| 13      | 632       | 9.33%   |
| 27      | 530       | 7.83%   |
| Unknown | 507       | 7.49%   |
| 24      | 477       | 7.04%   |
| 23      | 427       | 6.3%    |
| 21      | 377       | 5.57%   |
| 14      | 369       | 5.45%   |
| 17      | 348       | 5.14%   |
| 12      | 199       | 2.94%   |
| 19      | 179       | 2.64%   |
| 31      | 137       | 2.02%   |
| 22      | 107       | 1.58%   |
| 11      | 104       | 1.54%   |
| 84      | 101       | 1.49%   |
| 34      | 99        | 1.46%   |
| 18      | 84        | 1.24%   |
| 20      | 71        | 1.05%   |
| 72      | 54        | 0.8%    |
| 26      | 40        | 0.59%   |
| 25      | 38        | 0.56%   |
| 10      | 35        | 0.52%   |
| 32      | 32        | 0.47%   |
| 54      | 29        | 0.43%   |
| 16      | 28        | 0.41%   |
| 40      | 18        | 0.27%   |
| 33      | 18        | 0.27%   |
| 48      | 16        | 0.24%   |
| 7       | 16        | 0.24%   |
| 65      | 13        | 0.19%   |
| 39      | 13        | 0.19%   |
| 28      | 13        | 0.19%   |
| 46      | 11        | 0.16%   |
| 60      | 10        | 0.15%   |
| 55      | 10        | 0.15%   |
| 52      | 10        | 0.15%   |
| 43      | 8         | 0.12%   |
| 35      | 8         | 0.12%   |
| 142     | 7         | 0.1%    |
| 8       | 7         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2237      | 33.51%  |
| 501-600        | 1343      | 20.12%  |
| 201-300        | 727       | 10.89%  |
| 401-500        | 715       | 10.71%  |
| Unknown        | 507       | 7.6%    |
| 351-400        | 401       | 6.01%   |
| 601-700        | 232       | 3.48%   |
| 1501-2000      | 157       | 2.35%   |
| 701-800        | 148       | 2.22%   |
| 1001-1500      | 122       | 1.83%   |
| 801-900        | 42        | 0.63%   |
| 1-100          | 16        | 0.24%   |
| 901-1000       | 12        | 0.18%   |
| More than 2000 | 9         | 0.13%   |
| 101-200        | 7         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4475      | 72%     |
| 16/10   | 761       | 12.24%  |
| Unknown | 401       | 6.45%   |
| 5/4     | 211       | 3.4%    |
| 21/9    | 114       | 1.83%   |
| 3/2     | 84        | 1.35%   |
| 4/3     | 62        | 1%      |
| 0.62    | 48        | 0.77%   |
| 32/9    | 19        | 0.31%   |
| 0.67    | 16        | 0.26%   |
| 6/5     | 10        | 0.16%   |
| 1.00    | 10        | 0.16%   |
| 3.20    | 2         | 0.03%   |
| 3.40    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1539      | 22.94%  |
| 201-250        | 1104      | 16.46%  |
| 81-90          | 666       | 9.93%   |
| 301-350        | 559       | 8.33%   |
| Unknown        | 507       | 7.56%   |
| 151-200        | 384       | 5.72%   |
| 71-80          | 348       | 5.19%   |
| 351-500        | 304       | 4.53%   |
| More than 1000 | 252       | 3.76%   |
| 121-130        | 197       | 2.94%   |
| 251-300        | 188       | 2.8%    |
| 61-70          | 175       | 2.61%   |
| 141-150        | 161       | 2.4%    |
| 51-60          | 109       | 1.62%   |
| 501-1000       | 80        | 1.19%   |
| 131-140        | 42        | 0.63%   |
| 41-50          | 31        | 0.46%   |
| 111-120        | 27        | 0.4%    |
| 1-40           | 23        | 0.34%   |
| 91-100         | 12        | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2075      | 31.72%  |
| 101-120       | 1635      | 25%     |
| 121-160       | 1516      | 23.18%  |
| Unknown       | 507       | 7.75%   |
| 161-240       | 431       | 6.59%   |
| More than 240 | 195       | 2.98%   |
| 1-50          | 182       | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5281      | 80.34%  |
| 2     | 873       | 13.28%  |
| 0     | 317       | 4.82%   |
| 3     | 93        | 1.41%   |
| 4     | 8         | 0.12%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3184      | 33.31%  |
| Intel                             | 3157      | 33.03%  |
| Qualcomm Atheros                  | 1003      | 10.49%  |
| Broadcom                          | 674       | 7.05%   |
| Ralink Technology                 | 190       | 1.99%   |
| Marvell Technology Group          | 153       | 1.6%    |
| Broadcom Limited                  | 142       | 1.49%   |
| Nvidia                            | 118       | 1.23%   |
| Ralink                            | 105       | 1.1%    |
| TP-Link                           | 101       | 1.06%   |
| MediaTek                          | 62        | 0.65%   |
| DisplayLink                       | 38        | 0.4%    |
| Microsoft                         | 36        | 0.38%   |
| Ericsson Business Mobile Networks | 36        | 0.38%   |
| ASIX Electronics                  | 36        | 0.38%   |
| Dell                              | 35        | 0.37%   |
| Samsung Electronics               | 33        | 0.35%   |
| Belkin Components                 | 28        | 0.29%   |
| NetGear                           | 26        | 0.27%   |
| Qualcomm Atheros Communications   | 25        | 0.26%   |
| Edimax Technology                 | 24        | 0.25%   |
| Lenovo                            | 22        | 0.23%   |
| Huawei Technologies               | 22        | 0.23%   |
| Hewlett-Packard                   | 18        | 0.19%   |
| Aquantia                          | 17        | 0.18%   |
| Qualcomm                          | 16        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.16%   |
| Sierra Wireless                   | 11        | 0.12%   |
| JMicron Technology                | 11        | 0.12%   |
| ASUSTek Computer                  | 11        | 0.12%   |
| VIA Technologies                  | 10        | 0.1%    |
| Microchip Technology              | 10        | 0.1%    |
| Mellanox Technologies             | 10        | 0.1%    |
| Xiaomi                            | 9         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 8         | 0.08%   |
| D-Link                            | 8         | 0.08%   |
| Apple                             | 8         | 0.08%   |
| Google                            | 7         | 0.07%   |
| D-Link System                     | 7         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2067      | 18.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 385       | 3.41%   |
| Intel Wi-Fi 6 AX200                                               | 315       | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 270       | 2.39%   |
| Intel I211 Gigabit Network Connection                             | 218       | 1.93%   |
| Intel Wireless 8265 / 8275                                        | 182       | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 1.4%    |
| Intel Wireless 7260                                               | 149       | 1.32%   |
| Intel Wireless 7265                                               | 144       | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 141       | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 131       | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 122       | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 120       | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 119       | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 116       | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 115       | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 113       | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 106       | 0.94%   |
| Intel Wireless 8260                                               | 106       | 0.94%   |
| Intel Wireless 3165                                               | 100       | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 90        | 0.8%    |
| Intel Wireless-AC 9260                                            | 85        | 0.75%   |
| Intel Wi-Fi 6 AX201                                               | 84        | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 83        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 81        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 73        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 69        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 69        | 0.61%   |
| Realtek 802.11ac NIC                                              | 68        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                   | 66        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 65        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 65        | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 64        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 63        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 61        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 61        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 60        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 55        | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 54        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2259      | 43.28%  |
| Realtek Semiconductor             | 899       | 17.22%  |
| Qualcomm Atheros                  | 814       | 15.59%  |
| Broadcom                          | 422       | 8.08%   |
| Ralink Technology                 | 190       | 3.64%   |
| Ralink                            | 104       | 1.99%   |
| Broadcom Limited                  | 103       | 1.97%   |
| TP-Link                           | 95        | 1.82%   |
| MediaTek                          | 52        | 1%      |
| Microsoft                         | 34        | 0.65%   |
| Marvell Technology Group          | 30        | 0.57%   |
| Belkin Components                 | 28        | 0.54%   |
| NetGear                           | 26        | 0.5%    |
| Qualcomm Atheros Communications   | 25        | 0.48%   |
| Edimax Technology                 | 24        | 0.46%   |
| Dell                              | 20        | 0.38%   |
| Sierra Wireless                   | 11        | 0.21%   |
| ASUSTek Computer                  | 10        | 0.19%   |
| D-Link                            | 8         | 0.15%   |
| Qualcomm                          | 7         | 0.13%   |
| Micro Star International          | 6         | 0.11%   |
| D-Link System                     | 6         | 0.11%   |
| IMC Networks                      | 5         | 0.1%    |
| Ericsson Business Mobile Networks | 5         | 0.1%    |
| ZyDAS                             | 4         | 0.08%   |
| TRENDnet                          | 3         | 0.06%   |
| Sitecom Europe                    | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Gemtek                            | 3         | 0.06%   |
| Fibocom                           | 3         | 0.06%   |
| Wilocity                          | 2         | 0.04%   |
| Wacom                             | 2         | 0.04%   |
| Hewlett-Packard                   | 2         | 0.04%   |
| Texas Instruments                 | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Samsung Electronics               | 1         | 0.02%   |
| Philips (or NXP)                  | 1         | 0.02%   |
| InProComm                         | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| CyberTAN Technology               | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 315       | 5.98%   |
| Intel Wireless 8265 / 8275                                              | 182       | 3.46%   |
| Intel Wireless 7260                                                     | 149       | 2.83%   |
| Intel Wireless 7265                                                     | 144       | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 141       | 2.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 131       | 2.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 122       | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 120       | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 119       | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 106       | 2.01%   |
| Intel Wireless 8260                                                     | 106       | 2.01%   |
| Intel Wireless 3165                                                     | 100       | 1.9%    |
| Intel Wireless-AC 9260                                                  | 85        | 1.61%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 83        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 81        | 1.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 73        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 69        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 69        | 1.31%   |
| Realtek 802.11ac NIC                                                    | 68        | 1.29%   |
| Ralink MT7601U Wireless Adapter                                         | 66        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 65        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 64        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 61        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 55        | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.03%   |
| Intel Wireless 3160                                                     | 53        | 1.01%   |
| Ralink RT5370 Wireless Adapter                                          | 51        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 51        | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 51        | 0.97%   |
| Intel WiFi Link 5100                                                    | 49        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 41        | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 41        | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 40        | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 40        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 40        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2786      | 48.38%  |
| Intel                                  | 1732      | 30.07%  |
| Broadcom                               | 352       | 6.11%   |
| Qualcomm Atheros                       | 279       | 4.84%   |
| Marvell Technology Group               | 123       | 2.14%   |
| Nvidia                                 | 118       | 2.05%   |
| Broadcom Limited                       | 42        | 0.73%   |
| DisplayLink                            | 38        | 0.66%   |
| ASIX Electronics                       | 36        | 0.63%   |
| Samsung Electronics                    | 32        | 0.56%   |
| Lenovo                                 | 22        | 0.38%   |
| Huawei Technologies                    | 18        | 0.31%   |
| Aquantia                               | 17        | 0.3%    |
| Silicon Integrated Systems [SiS]       | 14        | 0.24%   |
| JMicron Technology                     | 11        | 0.19%   |
| VIA Technologies                       | 10        | 0.17%   |
| Xiaomi                                 | 9         | 0.16%   |
| Qualcomm                               | 9         | 0.16%   |
| Microchip Technology                   | 9         | 0.16%   |
| Mellanox Technologies                  | 9         | 0.16%   |
| MediaTek                               | 9         | 0.16%   |
| OnePlus Technology (Shenzhen)          | 7         | 0.12%   |
| Google                                 | 7         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.1%    |
| TP-Link                                | 6         | 0.1%    |
| Motorola PCS                           | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| OPPO Electronics                       | 5         | 0.09%   |
| Attansic Technology                    | 5         | 0.09%   |
| ICS Advent                             | 4         | 0.07%   |
| Hewlett-Packard                        | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| HTC (High Tech Computer)               | 3         | 0.05%   |
| 3Com                                   | 3         | 0.05%   |
| Standard Microsystems                  | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Emulex                                 | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2067      | 35.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 385       | 6.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 270       | 4.58%   |
| Intel I211 Gigabit Network Connection                             | 218       | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 116       | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 115       | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 90        | 1.53%   |
| Intel Ethernet Connection (7) I219-V                              | 65        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 64        | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 63        | 1.07%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 52        | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 50        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 49        | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 49        | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.71%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41        | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 40        | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 39        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 38        | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 38        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 36        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 35        | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 34        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 34        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 33        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 33        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 29        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 28        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 25        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 24        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 24        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5425      | 52.05%  |
| WiFi     | 4872      | 46.74%  |
| Modem    | 111       | 1.06%   |
| Unknown  | 15        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3784      | 57.19%  |
| Ethernet | 2832      | 42.8%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3381      | 52.36%  |
| 1     | 2697      | 41.77%  |
| 0     | 180       | 2.79%   |
| 3     | 139       | 2.15%   |
| 4     | 37        | 0.57%   |
| 5     | 17        | 0.26%   |
| 6     | 4         | 0.06%   |
| 8     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5753      | 88.43%  |
| Yes  | 753       | 11.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1721      | 45.75%  |
| Cambridge Silicon Radio         | 297       | 7.89%   |
| Realtek Semiconductor           | 283       | 7.52%   |
| Qualcomm Atheros Communications | 283       | 7.52%   |
| Broadcom                        | 258       | 6.86%   |
| Apple                           | 174       | 4.63%   |
| IMC Networks                    | 158       | 4.2%    |
| Lite-On Technology              | 95        | 2.53%   |
| Foxconn / Hon Hai               | 90        | 2.39%   |
| Dell                            | 74        | 1.97%   |
| ASUSTek Computer                | 67        | 1.78%   |
| Toshiba                         | 49        | 1.3%    |
| Hewlett-Packard                 | 41        | 1.09%   |
| Marvell Semiconductor           | 28        | 0.74%   |
| Realtek                         | 19        | 0.51%   |
| Alps Electric                   | 18        | 0.48%   |
| Belkin Components               | 17        | 0.45%   |
| Foxconn International           | 14        | 0.37%   |
| TP-Link                         | 10        | 0.27%   |
| MediaTek                        | 10        | 0.27%   |
| Ralink                          | 9         | 0.24%   |
| Integrated System Solution      | 8         | 0.21%   |
| Ralink Technology               | 6         | 0.16%   |
| Askey Computer                  | 6         | 0.16%   |
| Taiyo Yuden                     | 5         | 0.13%   |
| Micro Star International        | 5         | 0.13%   |
| HTC (High Tech Computer)        | 4         | 0.11%   |
| Logitech                        | 3         | 0.08%   |
| Edimax Technology               | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SIN                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Cypress Semiconductor           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 688       | 18.28%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 297       | 7.89%   |
| Intel AX200 Bluetooth                               | 290       | 7.71%   |
| Intel Bluetooth Device                              | 273       | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 190       | 5.05%   |
| Realtek Bluetooth Radio                             | 164       | 4.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 104       | 2.76%   |
| IMC Networks Bluetooth Radio                        | 99        | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 2.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 76        | 2.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 70        | 1.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 67        | 1.78%   |
| Apple Bluetooth USB Host Controller                 | 67        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 65        | 1.73%   |
| Apple Bluetooth Host Controller                     | 63        | 1.67%   |
| Lite-On Bluetooth Device                            | 61        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 59        | 1.57%   |
| Intel AX210 Bluetooth                               | 55        | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 53        | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 1.38%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 27        | 0.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.69%   |
| IMC Networks Bluetooth Device                       | 26        | 0.69%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.69%   |
| Marvell Bluetooth and Wireless LAN Composite        | 25        | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 19        | 0.5%    |
| Realtek Bluetooth Radio                             | 19        | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.48%   |
| Apple Bluetooth HCI                                 | 18        | 0.48%   |
| IMC Networks Wireless_Device                        | 16        | 0.43%   |
| Toshiba Bluetooth Device                            | 15        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 14        | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4415      | 49.79%  |
| AMD                                  | 1874      | 21.13%  |
| Nvidia                               | 1576      | 17.77%  |
| C-Media Electronics                  | 159       | 1.79%   |
| Creative Labs                        | 81        | 0.91%   |
| Logitech                             | 54        | 0.61%   |
| Texas Instruments                    | 50        | 0.56%   |
| JMTek                                | 33        | 0.37%   |
| Realtek Semiconductor                | 31        | 0.35%   |
| Focusrite-Novation                   | 31        | 0.35%   |
| Creative Technology                  | 30        | 0.34%   |
| Razer USA                            | 27        | 0.3%    |
| SteelSeries ApS                      | 25        | 0.28%   |
| Plantronics                          | 25        | 0.28%   |
| GN Netcom                            | 24        | 0.27%   |
| ASUSTek Computer                     | 21        | 0.24%   |
| Corsair                              | 19        | 0.21%   |
| VIA Technologies                     | 18        | 0.2%    |
| Kingston Technology                  | 18        | 0.2%    |
| Blue Microphones                     | 18        | 0.2%    |
| Silicon Integrated Systems [SiS]     | 15        | 0.17%   |
| Lenovo                               | 15        | 0.17%   |
| Generalplus Technology               | 14        | 0.16%   |
| Micro Star International             | 13        | 0.15%   |
| Apple                                | 12        | 0.14%   |
| Tenx Technology                      | 10        | 0.11%   |
| Dell                                 | 10        | 0.11%   |
| Sennheiser Communications            | 9         | 0.1%    |
| ATI Technologies                     | 9         | 0.1%    |
| GYROCOM C&C                          | 8         | 0.09%   |
| AKAI Professional M.I.               | 8         | 0.09%   |
| XMOS                                 | 7         | 0.08%   |
| Sony                                 | 7         | 0.08%   |
| Conexant Systems                     | 7         | 0.08%   |
| BEHRINGER International              | 7         | 0.08%   |
| Microsoft                            | 6         | 0.07%   |
| DSEA A/S                             | 6         | 0.07%   |
| Yamaha                               | 5         | 0.06%   |
| Unknown                              | 5         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 447       | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 435       | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 400       | 3.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 357       | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 304       | 2.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 297       | 2.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 270       | 2.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 270       | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 236       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 234       | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 227       | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 226       | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 163       | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 163       | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 161       | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 160       | 1.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 149       | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 144       | 1.37%   |
| Intel 8 Series HD Audio Controller                                                                | 143       | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 142       | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 141       | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 132       | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 128       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 127       | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 125       | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 124       | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 117       | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 102       | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 101       | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 98        | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 96        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 92        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 91        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 89        | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 89        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 87        | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 80        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 79        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 77        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 75        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 684       | 19.83%  |
| SK hynix            | 606       | 17.57%  |
| Corsair             | 410       | 11.88%  |
| Micron Technology   | 348       | 10.09%  |
| Unknown             | 342       | 9.91%   |
| Crucial             | 331       | 9.59%   |
| Kingston            | 301       | 8.72%   |
| Ramaxel Technology  | 54        | 1.57%   |
| Elpida              | 47        | 1.36%   |
| A-DATA Technology   | 43        | 1.25%   |
| Nanya Technology    | 42        | 1.22%   |
| Unknown (ABCD)      | 31        | 0.9%    |
| G.Skill             | 30        | 0.87%   |
| Team                | 27        | 0.78%   |
| Patriot             | 18        | 0.52%   |
| Unknown             | 13        | 0.38%   |
| Transcend           | 9         | 0.26%   |
| Qimonda             | 8         | 0.23%   |
| Hewlett-Packard     | 8         | 0.23%   |
| ASint Technology    | 7         | 0.2%    |
| Toshiba             | 6         | 0.17%   |
| A Force             | 6         | 0.17%   |
| Timetec             | 5         | 0.14%   |
| GOODRAM             | 5         | 0.14%   |
| Apacer              | 5         | 0.14%   |
| KLEVV               | 3         | 0.09%   |
| GSkill              | 3         | 0.09%   |
| Axiom               | 3         | 0.09%   |
| V-Color             | 2         | 0.06%   |
| Unknown (F301)      | 2         | 0.06%   |
| Unknown (0x0702)    | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| Infineon            | 2         | 0.06%   |
| Essencore           | 2         | 0.06%   |
| CSX                 | 2         | 0.06%   |
| Avant               | 2         | 0.06%   |
| ATP                 | 2         | 0.06%   |
| Wilk Elektronik     | 1         | 0.03%   |
| Uroad               | 1         | 0.03%   |
| Unknown (CB83)      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 40        | 1.07%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 36        | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 29        | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 17        | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 16        | 0.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 16        | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.4%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 15        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 14        | 0.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.38%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 14        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 13        | 0.35%   |
| Unknown                                                          | 13        | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 12        | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 12        | 0.32%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.29%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 11        | 0.29%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 11        | 0.29%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 10        | 0.27%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 10        | 0.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.27%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1338      | 44.51%  |
| DDR3    | 1009      | 33.57%  |
| DDR2    | 177       | 5.89%   |
| LPDDR4  | 118       | 3.93%   |
| LPDDR3  | 105       | 3.49%   |
| Unknown | 103       | 3.43%   |
| SDRAM   | 94        | 3.13%   |
| DDR5    | 25        | 0.83%   |
| DDR     | 23        | 0.77%   |
| DRAM    | 8         | 0.27%   |
| LPDDR5  | 6         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1557      | 52.51%  |
| DIMM         | 1157      | 39.02%  |
| Row Of Chips | 208       | 7.02%   |
| Chip         | 19        | 0.64%   |
| Unknown      | 14        | 0.47%   |
| RIMM         | 6         | 0.2%    |
| FB-DIMM      | 4         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1206      | 37.26%  |
| 4096   | 903       | 27.9%   |
| 16384  | 453       | 13.99%  |
| 2048   | 427       | 13.19%  |
| 1024   | 138       | 4.26%   |
| 32768  | 88        | 2.72%   |
| 512    | 17        | 0.53%   |
| 256    | 2         | 0.06%   |
| 131072 | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 663       | 20.29%  |
| 2667    | 433       | 13.25%  |
| 3200    | 357       | 10.93%  |
| 2400    | 267       | 8.17%   |
| 1333    | 249       | 7.62%   |
| 2133    | 168       | 5.14%   |
| 3600    | 103       | 3.15%   |
| 667     | 99        | 3.03%   |
| 1867    | 89        | 2.72%   |
| 800     | 81        | 2.48%   |
| 1334    | 79        | 2.42%   |
| Unknown | 58        | 1.78%   |
| 4267    | 48        | 1.47%   |
| 1067    | 44        | 1.35%   |
| 3400    | 42        | 1.29%   |
| 1066    | 36        | 1.1%    |
| 3266    | 34        | 1.04%   |
| 3000    | 34        | 1.04%   |
| 2048    | 30        | 0.92%   |
| 3733    | 27        | 0.83%   |
| 1866    | 27        | 0.83%   |
| 2800    | 22        | 0.67%   |
| 4800    | 21        | 0.64%   |
| 4199    | 20        | 0.61%   |
| 2933    | 20        | 0.61%   |
| 3466    | 19        | 0.58%   |
| 533     | 19        | 0.58%   |
| 2666    | 17        | 0.52%   |
| 400     | 16        | 0.49%   |
| 1800    | 14        | 0.43%   |
| 4266    | 13        | 0.4%    |
| 975     | 12        | 0.37%   |
| 3800    | 7         | 0.21%   |
| 1639    | 7         | 0.21%   |
| 49926   | 6         | 0.18%   |
| 8400    | 6         | 0.18%   |
| 3100    | 6         | 0.18%   |
| 2000    | 6         | 0.18%   |
| 6400    | 5         | 0.15%   |
| 3007    | 5         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 63        | 41.18%  |
| Canon                 | 26        | 16.99%  |
| Seiko Epson           | 14        | 9.15%   |
| Samsung Electronics   | 14        | 9.15%   |
| Brother Industries    | 13        | 8.5%    |
| Prolific Technology   | 5         | 3.27%   |
| Lexmark International | 4         | 2.61%   |
| STMicroelectronics    | 2         | 1.31%   |
| QinHeng Electronics   | 2         | 1.31%   |
| Oki Data              | 2         | 1.31%   |
| Kyocera               | 2         | 1.31%   |
| Dymo-CoStar           | 2         | 1.31%   |
| Seiko Instruments     | 1         | 0.65%   |
| Ricoh                 | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |
| Apple                 | 1         | 0.65%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 6         | 3.87%   |
| Prolific PL2305 Parallel Port                             | 5         | 3.23%   |
| HP ENVY 5000 series                                       | 5         | 3.23%   |
| HP ENVY 4520 series                                       | 5         | 3.23%   |
| Canon PIXMA MG2500 Series                                 | 5         | 3.23%   |
| HP DeskJet 2600 series                                    | 4         | 2.58%   |
| HP DeskJet 2130 series                                    | 3         | 1.94%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.29%   |
| Seiko Epson XP-243 245 247 Series                         | 2         | 1.29%   |
| Seiko Epson XP-200 Series                                 | 2         | 1.29%   |
| Samsung ML-2250 Series                                    | 2         | 1.29%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.29%   |
| Samsung C43x Series                                       | 2         | 1.29%   |
| QinHeng CH340S                                            | 2         | 1.29%   |
| Oki Data USB Device                                       | 2         | 1.29%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.29%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.29%   |
| HP Deskjet F2280 series                                   | 2         | 1.29%   |
| HP DeskJet 3630 series                                    | 2         | 1.29%   |
| HP Deskjet 2540 series                                    | 2         | 1.29%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.29%   |
| HP Color LaserJet CP1215                                  | 2         | 1.29%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.29%   |
| Canon PIXMA MP495                                         | 2         | 1.29%   |
| Canon MG5700 series                                       | 2         | 1.29%   |
| Canon iP7200 series                                       | 2         | 1.29%   |
| Canon CanoScan LiDE 300                                   | 2         | 1.29%   |
| Brother HL-3140CW series                                  | 2         | 1.29%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.29%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.65%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.65%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.65%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.65%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.65%   |
| Seiko Epson L355 Series                                   | 1         | 0.65%   |
| Samsung SCX-4300 Series                                   | 1         | 0.65%   |
| Samsung SCX-3400 Series                                   | 1         | 0.65%   |
| Samsung ML-1865                                           | 1         | 0.65%   |
| Samsung ML-1510 Laser Printer                             | 1         | 0.65%   |
| Samsung M2020 Series                                      | 1         | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 23        | 62.16%  |
| Seiko Epson        | 8         | 21.62%  |
| Ultima Electronics | 2         | 5.41%   |
| Hewlett-Packard    | 2         | 5.41%   |
| Mustek Systems     | 1         | 2.7%    |
| AGFA-Gevaert NV    | 1         | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 13.51%  |
| Canon CanoScan LiDE 220                                                               | 4         | 10.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 8.11%   |
| Canon CanoScan LiDE 110                                                               | 3         | 8.11%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5.41%   |
| Seiko Epson Scanner                                                                   | 2         | 5.41%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 5.41%   |
| Canon CanoScan LiDE 200                                                               | 2         | 5.41%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.7%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.7%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.7%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.7%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.7%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.7%    |
| Canon CanoScan LiDE 90                                                                | 1         | 2.7%    |
| Canon CanoScan LiDE 70                                                                | 1         | 2.7%    |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.7%    |
| Canon CanoScan LiDE 210                                                               | 1         | 2.7%    |
| Canon CanoScan LiDE 100                                                               | 1         | 2.7%    |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.7%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 771       | 21.15%  |
| Microdia                               | 386       | 10.59%  |
| Realtek Semiconductor                  | 292       | 8.01%   |
| IMC Networks                           | 256       | 7.02%   |
| Logitech                               | 249       | 6.83%   |
| Acer                                   | 217       | 5.95%   |
| Sunplus Innovation Technology          | 171       | 4.69%   |
| Apple                                  | 142       | 3.89%   |
| Cheng Uei Precision Industry (Foxlink) | 130       | 3.57%   |
| Quanta                                 | 115       | 3.15%   |
| Suyin                                  | 112       | 3.07%   |
| Lite-On Technology                     | 89        | 2.44%   |
| Microsoft                              | 72        | 1.97%   |
| Syntek                                 | 66        | 1.81%   |
| Silicon Motion                         | 58        | 1.59%   |
| Alcor Micro                            | 49        | 1.34%   |
| Samsung Electronics                    | 44        | 1.21%   |
| Ricoh                                  | 43        | 1.18%   |
| Lenovo                                 | 34        | 0.93%   |
| Z-Star Microelectronics                | 28        | 0.77%   |
| ARC International                      | 25        | 0.69%   |
| Generalplus Technology                 | 22        | 0.6%    |
| Luxvisions Innotech Limited            | 21        | 0.58%   |
| GEMBIRD                                | 20        | 0.55%   |
| MacroSilicon                           | 15        | 0.41%   |
| Creative Technology                    | 14        | 0.38%   |
| ALi                                    | 12        | 0.33%   |
| Sonix Technology                       | 11        | 0.3%    |
| Primax Electronics                     | 11        | 0.3%    |
| Razer USA                              | 10        | 0.27%   |
| Aveo Technology                        | 10        | 0.27%   |
| SunplusIT                              | 8         | 0.22%   |
| Huawei Technologies                    | 8         | 0.22%   |
| Hewlett-Packard                        | 8         | 0.22%   |
| Unknown                                | 7         | 0.19%   |
| Genesys Logic                          | 7         | 0.19%   |
| Sunplus Technology                     | 6         | 0.16%   |
| OmniVision Technologies                | 6         | 0.16%   |
| Importek                               | 6         | 0.16%   |
| Intel                                  | 5         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 166       | 4.5%    |
| Chicony Integrated Camera                               | 131       | 3.55%   |
| Realtek Integrated_Webcam_HD                            | 95        | 2.58%   |
| IMC Networks Integrated Camera                          | 74        | 2.01%   |
| Logitech HD Pro Webcam C920                             | 73        | 1.98%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 65        | 1.76%   |
| Chicony HD WebCam                                       | 61        | 1.65%   |
| Sunplus Integrated_Webcam_HD                            | 53        | 1.44%   |
| Logitech Webcam C270                                    | 46        | 1.25%   |
| Samsung Galaxy A5 (MTP)                                 | 44        | 1.19%   |
| Apple Built-in iSight                                   | 42        | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                     | 41        | 1.11%   |
| Acer Integrated Camera                                  | 41        | 1.11%   |
| Realtek USB Camera                                      | 36        | 0.98%   |
| Microdia Integrated Webcam                              | 36        | 0.98%   |
| Chicony USB2.0 Camera                                   | 36        | 0.98%   |
| Apple iPhone 5/5C/5S/6/SE                               | 36        | 0.98%   |
| Microdia Webcam Vitade AF                               | 31        | 0.84%   |
| Lite-On Integrated Camera                               | 31        | 0.84%   |
| Chicony TOSHIBA Web Camera - HD                         | 31        | 0.84%   |
| Microdia USB 2.0 Camera                                 | 30        | 0.81%   |
| Chicony USB 2.0 Camera                                  | 30        | 0.81%   |
| Microsoft LifeCam HD-3000                               | 28        | 0.76%   |
| Chicony HP TrueVision HD Camera                         | 27        | 0.73%   |
| Acer Lenovo EasyCamera                                  | 27        | 0.73%   |
| Acer BisonCam,NB Pro                                    | 27        | 0.73%   |
| Chicony HP Truevision HD                                | 25        | 0.68%   |
| ARC International Camera                                | 25        | 0.68%   |
| Syntek Lenovo EasyCamera                                | 24        | 0.65%   |
| Chicony VGA WebCam                                      | 24        | 0.65%   |
| Chicony EasyCamera                                      | 24        | 0.65%   |
| Microsoft LifeCam Cinema                                | 23        | 0.62%   |
| Chicony HP HD Camera                                    | 22        | 0.6%    |
| Acer SunplusIT Integrated Camera                        | 22        | 0.6%    |
| Chicony HP Wide Vision HD Camera                        | 21        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 21        | 0.57%   |
| Apple FaceTime HD Camera                                | 21        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)                 | 20        | 0.54%   |
| Syntek Integrated Camera                                | 19        | 0.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 191       | 30.46%  |
| Synaptics                  | 173       | 27.59%  |
| Shenzhen Goodix Technology | 94        | 14.99%  |
| AuthenTec                  | 46        | 7.34%   |
| Upek                       | 44        | 7.02%   |
| Elan Microelectronics      | 30        | 4.78%   |
| LighTuning Technology      | 29        | 4.63%   |
| STMicroelectronics         | 15        | 2.39%   |
| Samsung Electronics        | 2         | 0.32%   |
| HOLTEK                     | 2         | 0.32%   |
| Focal-systems.Corp         | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 57        | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                                        | 48        | 7.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 43        | 6.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 5.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 36        | 5.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 4.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 3.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 3.83%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 3.03%   |
| Synaptics  WBDI                                                            | 17        | 2.71%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 2.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.39%   |
| Validity Sensors VFS491                                                    | 14        | 2.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.23%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 2.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.91%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 1.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.91%   |
| AuthenTec AES2810                                                          | 11        | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.59%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.44%   |
| Synaptics WBDI Device                                                      | 8         | 1.28%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.28%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.12%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.12%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.96%   |
| Elan ELAN:ARM-M4                                                           | 6         | 0.96%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.8%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.8%    |
| AuthenTec AES1600                                                          | 5         | 0.8%    |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.64%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.48%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 156       | 52%     |
| Alcor Micro           | 66        | 22%     |
| Upek                  | 23        | 7.67%   |
| O2 Micro              | 21        | 7%      |
| Lenovo                | 21        | 7%      |
| Gemalto (was Gemplus) | 4         | 1.33%   |
| SCM Microsystems      | 3         | 1%      |
| Purism, SPC           | 1         | 0.33%   |
| OmniKey               | 1         | 0.33%   |
| Hewlett-Packard       | 1         | 0.33%   |
| Clay Logic            | 1         | 0.33%   |
| Chicony Electronics   | 1         | 0.33%   |
| BIT4ID                | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 65        | 21.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 62        | 20.67%  |
| Broadcom 5880                                                                | 41        | 13.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 9.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 23        | 7.67%   |
| Broadcom 58200                                                               | 20        | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 19        | 6.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 5.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.67%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.67%   |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.67%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.33%   |
| Purism, SPC Librem Key                                                       | 1         | 0.33%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4637      | 70.43%  |
| 1     | 1527      | 23.19%  |
| 2     | 344       | 5.22%   |
| 3     | 55        | 0.84%   |
| 4     | 12        | 0.18%   |
| 5     | 4         | 0.06%   |
| 7     | 2         | 0.03%   |
| 6     | 2         | 0.03%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 610       | 25.81%  |
| Graphics card            | 521       | 22.05%  |
| Net/wireless             | 375       | 15.87%  |
| Chipcard                 | 274       | 11.6%   |
| Multimedia controller    | 135       | 5.71%   |
| Communication controller | 108       | 4.57%   |
| Unassigned class         | 52        | 2.2%    |
| Sound                    | 52        | 2.2%    |
| Camera                   | 46        | 1.95%   |
| Bluetooth                | 45        | 1.9%    |
| Storage                  | 37        | 1.57%   |
| Net/ethernet             | 21        | 0.89%   |
| Card reader              | 21        | 0.89%   |
| Modem                    | 17        | 0.72%   |
| Network                  | 15        | 0.63%   |
| Storage/raid             | 8         | 0.34%   |
| Flash memory             | 8         | 0.34%   |
| Dvb card                 | 6         | 0.25%   |
| Firewire controller      | 5         | 0.21%   |
| Storage/ide              | 4         | 0.17%   |
| Storage/nvme             | 3         | 0.13%   |

