Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 7209

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Dev One Notebook PC         | Notebook    | [095bc08ae2](https://linux-hardware.org/?probe=095bc08ae2) | May 09, 2024 |
| Intel         | X99                         | Desktop     | [a02c0050f2](https://linux-hardware.org/?probe=a02c0050f2) | May 08, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [07f83fc6c0](https://linux-hardware.org/?probe=07f83fc6c0) | May 08, 2024 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [b67da2effc](https://linux-hardware.org/?probe=b67da2effc) | May 08, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [54f40400ed](https://linux-hardware.org/?probe=54f40400ed) | May 08, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f0bc418296](https://linux-hardware.org/?probe=f0bc418296) | May 08, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9b4c39c111](https://linux-hardware.org/?probe=9b4c39c111) | May 07, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [9236e5d92d](https://linux-hardware.org/?probe=9236e5d92d) | May 07, 2024 |
| Toshiba       | TECRA R850                  | Notebook    | [a4fae83513](https://linux-hardware.org/?probe=a4fae83513) | May 07, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [051c9db94b](https://linux-hardware.org/?probe=051c9db94b) | May 07, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [a81f44c8b4](https://linux-hardware.org/?probe=a81f44c8b4) | May 07, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [e061b752c8](https://linux-hardware.org/?probe=e061b752c8) | May 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [d7c1c96567](https://linux-hardware.org/?probe=d7c1c96567) | May 07, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60ef8abb02](https://linux-hardware.org/?probe=60ef8abb02) | May 07, 2024 |
| Dell          | Latitude E6540              | Notebook    | [634735e1da](https://linux-hardware.org/?probe=634735e1da) | May 06, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [cd07d15de0](https://linux-hardware.org/?probe=cd07d15de0) | May 06, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [5af3396f04](https://linux-hardware.org/?probe=5af3396f04) | May 05, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [ca15c39fa7](https://linux-hardware.org/?probe=ca15c39fa7) | May 05, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [9c6cf56bbb](https://linux-hardware.org/?probe=9c6cf56bbb) | May 05, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [5aaf9f4609](https://linux-hardware.org/?probe=5aaf9f4609) | May 05, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [bab451ff6f](https://linux-hardware.org/?probe=bab451ff6f) | May 05, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [31db777b68](https://linux-hardware.org/?probe=31db777b68) | May 04, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [3fbbffc4e8](https://linux-hardware.org/?probe=3fbbffc4e8) | May 04, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [bec2f2a916](https://linux-hardware.org/?probe=bec2f2a916) | May 04, 2024 |
| HP            | 8054                        | Desktop     | [bc7d8e8b56](https://linux-hardware.org/?probe=bc7d8e8b56) | May 04, 2024 |
| MSI           | GF75 Thin 10SCSXR           | Notebook    | [588a1bf985](https://linux-hardware.org/?probe=588a1bf985) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [7dfe52f49a](https://linux-hardware.org/?probe=7dfe52f49a) | May 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [40f4c2e910](https://linux-hardware.org/?probe=40f4c2e910) | May 03, 2024 |
| Dell          | 0D881F A05                  | Desktop     | [9dfc8fb5b7](https://linux-hardware.org/?probe=9dfc8fb5b7) | May 03, 2024 |
| Acer          | Swift SF314-41              | Notebook    | [7c627dfe92](https://linux-hardware.org/?probe=7c627dfe92) | May 02, 2024 |
| Acer          | Swift SF314-41              | Notebook    | [c6c8d9ef33](https://linux-hardware.org/?probe=c6c8d9ef33) | May 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [750eaa16c3](https://linux-hardware.org/?probe=750eaa16c3) | May 02, 2024 |
| ASRock        | Z270 Extreme4               | Desktop     | [7e548f1855](https://linux-hardware.org/?probe=7e548f1855) | May 02, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [0386514a20](https://linux-hardware.org/?probe=0386514a20) | May 01, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e759e41a51](https://linux-hardware.org/?probe=e759e41a51) | May 01, 2024 |
| HP            | 2AF7                        | Desktop     | [6e5ea827da](https://linux-hardware.org/?probe=6e5ea827da) | May 01, 2024 |
| Dell          | Latitude E7250              | Notebook    | [e674f5e264](https://linux-hardware.org/?probe=e674f5e264) | May 01, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [ea3b78a648](https://linux-hardware.org/?probe=ea3b78a648) | May 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6486b4f435](https://linux-hardware.org/?probe=6486b4f435) | May 01, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [13549c3c7b](https://linux-hardware.org/?probe=13549c3c7b) | May 01, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [e9f80cea34](https://linux-hardware.org/?probe=e9f80cea34) | Apr 30, 2024 |
| Lenovo        | ThinkPad T570 20H9CTO1WW    | Notebook    | [433a701205](https://linux-hardware.org/?probe=433a701205) | Apr 30, 2024 |
| HP            | G42                         | Notebook    | [6c3591bf85](https://linux-hardware.org/?probe=6c3591bf85) | Apr 30, 2024 |
| HP            | G42                         | Notebook    | [577968802f](https://linux-hardware.org/?probe=577968802f) | Apr 30, 2024 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [85b180a3db](https://linux-hardware.org/?probe=85b180a3db) | Apr 30, 2024 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4a07e72bf5](https://linux-hardware.org/?probe=4a07e72bf5) | Apr 30, 2024 |
| Dell          | Latitude 5510               | Notebook    | [1dcf4bdf1f](https://linux-hardware.org/?probe=1dcf4bdf1f) | Apr 30, 2024 |
| ASUSTek       | KGPE-D16                    | Desktop     | [f199ccf950](https://linux-hardware.org/?probe=f199ccf950) | Apr 30, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [cd98023b83](https://linux-hardware.org/?probe=cd98023b83) | Apr 30, 2024 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [616294b6b2](https://linux-hardware.org/?probe=616294b6b2) | Apr 29, 2024 |
| HP            | 18E7                        | Desktop     | [c4e6067edb](https://linux-hardware.org/?probe=c4e6067edb) | Apr 29, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [c16a488664](https://linux-hardware.org/?probe=c16a488664) | Apr 29, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [b9693bfaa8](https://linux-hardware.org/?probe=b9693bfaa8) | Apr 28, 2024 |
| MSI           | MS-7D46                     | Notebook    | [135fa9337a](https://linux-hardware.org/?probe=135fa9337a) | Apr 28, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [f6c6a3c2cb](https://linux-hardware.org/?probe=f6c6a3c2cb) | Apr 28, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [f9c0aa7676](https://linux-hardware.org/?probe=f9c0aa7676) | Apr 28, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [3a742038ec](https://linux-hardware.org/?probe=3a742038ec) | Apr 28, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [8459f9ea9a](https://linux-hardware.org/?probe=8459f9ea9a) | Apr 28, 2024 |
| Dell          | 04GJJT A00                  | Desktop     | [b336911f53](https://linux-hardware.org/?probe=b336911f53) | Apr 28, 2024 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [a330c6b15e](https://linux-hardware.org/?probe=a330c6b15e) | Apr 28, 2024 |
| ASUSTek       | K55VJ                       | Notebook    | [dee27f64b0](https://linux-hardware.org/?probe=dee27f64b0) | Apr 28, 2024 |
| ASUSTek       | K55VJ                       | Notebook    | [ade9763073](https://linux-hardware.org/?probe=ade9763073) | Apr 28, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [12a735e282](https://linux-hardware.org/?probe=12a735e282) | Apr 27, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [cd0ed468fc](https://linux-hardware.org/?probe=cd0ed468fc) | Apr 27, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [c7fee93564](https://linux-hardware.org/?probe=c7fee93564) | Apr 27, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [1cad57b859](https://linux-hardware.org/?probe=1cad57b859) | Apr 27, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [99f1c965f4](https://linux-hardware.org/?probe=99f1c965f4) | Apr 27, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [0056e3f773](https://linux-hardware.org/?probe=0056e3f773) | Apr 27, 2024 |
| Alienware     | 17 R5                       | Notebook    | [519ea8e910](https://linux-hardware.org/?probe=519ea8e910) | Apr 27, 2024 |
| HP            | 8704                        | Desktop     | [9637e112ef](https://linux-hardware.org/?probe=9637e112ef) | Apr 27, 2024 |
| HP            | 8704                        | Desktop     | [bc67b63fb1](https://linux-hardware.org/?probe=bc67b63fb1) | Apr 27, 2024 |
| HP            | Compaq 8710w (GT649PA#AB... | Notebook    | [aa6e9b5ba6](https://linux-hardware.org/?probe=aa6e9b5ba6) | Apr 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [86089f64dc](https://linux-hardware.org/?probe=86089f64dc) | Apr 26, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [c609a3560c](https://linux-hardware.org/?probe=c609a3560c) | Apr 26, 2024 |
| HP            | EliteBook 8730w             | Notebook    | [da4db94e97](https://linux-hardware.org/?probe=da4db94e97) | Apr 26, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [c1242570d2](https://linux-hardware.org/?probe=c1242570d2) | Apr 25, 2024 |
| Gigabyte      | B75M-D2V                    | Desktop     | [21c055a907](https://linux-hardware.org/?probe=21c055a907) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [e89543357b](https://linux-hardware.org/?probe=e89543357b) | Apr 25, 2024 |
| Gigabyte      | G5 MD                       | Notebook    | [09c723ce43](https://linux-hardware.org/?probe=09c723ce43) | Apr 25, 2024 |
| Gigabyte      | G5 MD                       | Notebook    | [4529b157ae](https://linux-hardware.org/?probe=4529b157ae) | Apr 25, 2024 |
| ECS           | Nettle                      | Desktop     | [ca8eb0919a](https://linux-hardware.org/?probe=ca8eb0919a) | Apr 25, 2024 |
| ECS           | Nettle                      | Desktop     | [47a4f75a79](https://linux-hardware.org/?probe=47a4f75a79) | Apr 25, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [56b059f9ef](https://linux-hardware.org/?probe=56b059f9ef) | Apr 25, 2024 |
| HP            | 829A                        | Mini pc     | [b8f9282a11](https://linux-hardware.org/?probe=b8f9282a11) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [91dc4d43de](https://linux-hardware.org/?probe=91dc4d43de) | Apr 25, 2024 |
| ASUSTek       | P5K Premium                 | Desktop     | [9b09b4d8bd](https://linux-hardware.org/?probe=9b09b4d8bd) | Apr 24, 2024 |
| Intel Clie... | LAPBC710                    | Notebook    | [8a2e6ee6ff](https://linux-hardware.org/?probe=8a2e6ee6ff) | Apr 24, 2024 |
| Intel Clie... | LAPBC710                    | Notebook    | [1853edd88a](https://linux-hardware.org/?probe=1853edd88a) | Apr 24, 2024 |
| Carbon Sys... | Iridium 16 Pro              | Notebook    | [b35260710f](https://linux-hardware.org/?probe=b35260710f) | Apr 24, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [71acf13c6c](https://linux-hardware.org/?probe=71acf13c6c) | Apr 24, 2024 |
| Dell          | G15 5511                    | Notebook    | [82f96ae6f0](https://linux-hardware.org/?probe=82f96ae6f0) | Apr 23, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [aa99325f06](https://linux-hardware.org/?probe=aa99325f06) | Apr 23, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1cc02514fd](https://linux-hardware.org/?probe=1cc02514fd) | Apr 23, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a42417ee6b](https://linux-hardware.org/?probe=a42417ee6b) | Apr 23, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [11d418a07c](https://linux-hardware.org/?probe=11d418a07c) | Apr 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [41d6261b80](https://linux-hardware.org/?probe=41d6261b80) | Apr 22, 2024 |
| JWIPC         | A320I S1                    | Desktop     | [eea8091ffa](https://linux-hardware.org/?probe=eea8091ffa) | Apr 22, 2024 |
| Gigabyte      | H310M S2P                   | Desktop     | [80fc55e632](https://linux-hardware.org/?probe=80fc55e632) | Apr 22, 2024 |
| Samsung       | 950XED                      | Notebook    | [20c945fb12](https://linux-hardware.org/?probe=20c945fb12) | Apr 22, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [cb411ef765](https://linux-hardware.org/?probe=cb411ef765) | Apr 22, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [89c9b39716](https://linux-hardware.org/?probe=89c9b39716) | Apr 22, 2024 |
| HP            | Pavilion g7                 | Notebook    | [b700499e3c](https://linux-hardware.org/?probe=b700499e3c) | Apr 21, 2024 |
| JWIPC         | A320I S1                    | Desktop     | [c8bb6cd872](https://linux-hardware.org/?probe=c8bb6cd872) | Apr 21, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6808539c26](https://linux-hardware.org/?probe=6808539c26) | Apr 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [96c7946b39](https://linux-hardware.org/?probe=96c7946b39) | Apr 20, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b3d6bd419d](https://linux-hardware.org/?probe=b3d6bd419d) | Apr 20, 2024 |
| DERE          | Unknown                     | Tablet      | [7780e6cd50](https://linux-hardware.org/?probe=7780e6cd50) | Apr 20, 2024 |
| Acer          | Aspire XC-705               | Desktop     | [da91a97808](https://linux-hardware.org/?probe=da91a97808) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [f48c5f02d8](https://linux-hardware.org/?probe=f48c5f02d8) | Apr 20, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [d99c576d13](https://linux-hardware.org/?probe=d99c576d13) | Apr 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [4f61acab6e](https://linux-hardware.org/?probe=4f61acab6e) | Apr 19, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [06f11dee2c](https://linux-hardware.org/?probe=06f11dee2c) | Apr 19, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [c55294e976](https://linux-hardware.org/?probe=c55294e976) | Apr 19, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [47d879fa41](https://linux-hardware.org/?probe=47d879fa41) | Apr 19, 2024 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ebc9dd41f4](https://linux-hardware.org/?probe=ebc9dd41f4) | Apr 19, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [88f29dbdc6](https://linux-hardware.org/?probe=88f29dbdc6) | Apr 19, 2024 |
| ASUSTek       | X756UXK                     | Notebook    | [c529e5199d](https://linux-hardware.org/?probe=c529e5199d) | Apr 18, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | Desktop     | [020aa8904b](https://linux-hardware.org/?probe=020aa8904b) | Apr 18, 2024 |
| Pegatron      | 2AC3                        | Desktop     | [db5312ea90](https://linux-hardware.org/?probe=db5312ea90) | Apr 18, 2024 |
| Clevo         | P170EM                      | Notebook    | [62fe8276aa](https://linux-hardware.org/?probe=62fe8276aa) | Apr 18, 2024 |
| Clevo         | P170EM                      | Notebook    | [46daa154fe](https://linux-hardware.org/?probe=46daa154fe) | Apr 18, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [6074f97307](https://linux-hardware.org/?probe=6074f97307) | Apr 18, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [52efce758f](https://linux-hardware.org/?probe=52efce758f) | Apr 18, 2024 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [6b14b793c5](https://linux-hardware.org/?probe=6b14b793c5) | Apr 17, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78cd7a86b3](https://linux-hardware.org/?probe=78cd7a86b3) | Apr 17, 2024 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | Notebook    | [f56632a8e0](https://linux-hardware.org/?probe=f56632a8e0) | Apr 16, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [2dc0b12567](https://linux-hardware.org/?probe=2dc0b12567) | Apr 16, 2024 |
| Fujitsu       | D3642-B1 S26361-D3642-B1    | Desktop     | [eb94119a94](https://linux-hardware.org/?probe=eb94119a94) | Apr 16, 2024 |
| Lenovo        | G480 20149                  | Notebook    | [4acc655121](https://linux-hardware.org/?probe=4acc655121) | Apr 16, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [31a598cb35](https://linux-hardware.org/?probe=31a598cb35) | Apr 16, 2024 |
| ASUSTek       | P7H55-M                     | Desktop     | [f4c4f689d2](https://linux-hardware.org/?probe=f4c4f689d2) | Apr 16, 2024 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [2f76e25729](https://linux-hardware.org/?probe=2f76e25729) | Apr 16, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [9bf28eb5b5](https://linux-hardware.org/?probe=9bf28eb5b5) | Apr 15, 2024 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | Notebook    | [2628bdee23](https://linux-hardware.org/?probe=2628bdee23) | Apr 15, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f51e425901](https://linux-hardware.org/?probe=f51e425901) | Apr 15, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [7674249513](https://linux-hardware.org/?probe=7674249513) | Apr 15, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [bca932a740](https://linux-hardware.org/?probe=bca932a740) | Apr 15, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2060f0dcd](https://linux-hardware.org/?probe=d2060f0dcd) | Apr 14, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b202e3f78e](https://linux-hardware.org/?probe=b202e3f78e) | Apr 14, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [aa7ac835c0](https://linux-hardware.org/?probe=aa7ac835c0) | Apr 14, 2024 |
| AMI           | Intel                       | Desktop     | [d8aa9b61b5](https://linux-hardware.org/?probe=d8aa9b61b5) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [2b471c5586](https://linux-hardware.org/?probe=2b471c5586) | Apr 14, 2024 |
| Intel         | B250                        | Desktop     | [197e339bcf](https://linux-hardware.org/?probe=197e339bcf) | Apr 14, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [2d02eae5ec](https://linux-hardware.org/?probe=2d02eae5ec) | Apr 13, 2024 |
| Toshiba       | TECRA R850                  | Notebook    | [8e11067c28](https://linux-hardware.org/?probe=8e11067c28) | Apr 13, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [22b0bf7e14](https://linux-hardware.org/?probe=22b0bf7e14) | Apr 13, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [416a662c16](https://linux-hardware.org/?probe=416a662c16) | Apr 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [21882b12a8](https://linux-hardware.org/?probe=21882b12a8) | Apr 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [f239d3dcb1](https://linux-hardware.org/?probe=f239d3dcb1) | Apr 12, 2024 |
| Samsung       | 550XDA                      | Notebook    | [2679015030](https://linux-hardware.org/?probe=2679015030) | Apr 12, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a678b9a33b](https://linux-hardware.org/?probe=a678b9a33b) | Apr 12, 2024 |
| Samsung       | 550XDA                      | Notebook    | [ac02b37e1d](https://linux-hardware.org/?probe=ac02b37e1d) | Apr 12, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [44a31677ab](https://linux-hardware.org/?probe=44a31677ab) | Apr 12, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [36bf325205](https://linux-hardware.org/?probe=36bf325205) | Apr 12, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [3173fd0ebe](https://linux-hardware.org/?probe=3173fd0ebe) | Apr 12, 2024 |
| Dell          | XPS 9320                    | Notebook    | [bcd7c6346c](https://linux-hardware.org/?probe=bcd7c6346c) | Apr 11, 2024 |
| TECNO         | MEGABOOK T1                 | Notebook    | [d19f36b422](https://linux-hardware.org/?probe=d19f36b422) | Apr 10, 2024 |
| Intel         | X99                         | Desktop     | [45b537d1cf](https://linux-hardware.org/?probe=45b537d1cf) | Apr 10, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [3fcaa3cf98](https://linux-hardware.org/?probe=3fcaa3cf98) | Apr 10, 2024 |
| Dell          | Inspiron 14 5425            | Notebook    | [65702761a8](https://linux-hardware.org/?probe=65702761a8) | Apr 10, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c12fc6f65e](https://linux-hardware.org/?probe=c12fc6f65e) | Apr 10, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [87501e63cd](https://linux-hardware.org/?probe=87501e63cd) | Apr 10, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [1bf9c1a3a1](https://linux-hardware.org/?probe=1bf9c1a3a1) | Apr 10, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [9b826b95dc](https://linux-hardware.org/?probe=9b826b95dc) | Apr 10, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [d62d670bd4](https://linux-hardware.org/?probe=d62d670bd4) | Apr 09, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [37733a1209](https://linux-hardware.org/?probe=37733a1209) | Apr 09, 2024 |
| HP            | ProBook 4520s               | Notebook    | [b29f0bab6b](https://linux-hardware.org/?probe=b29f0bab6b) | Apr 09, 2024 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [2bc54fcf85](https://linux-hardware.org/?probe=2bc54fcf85) | Apr 09, 2024 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [268dc837cb](https://linux-hardware.org/?probe=268dc837cb) | Apr 09, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [6e23ce4681](https://linux-hardware.org/?probe=6e23ce4681) | Apr 09, 2024 |
| Fujitsu       | FARQ01024                   | Notebook    | [11340c8636](https://linux-hardware.org/?probe=11340c8636) | Apr 09, 2024 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [465cbec10e](https://linux-hardware.org/?probe=465cbec10e) | Apr 09, 2024 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [14aae5a31c](https://linux-hardware.org/?probe=14aae5a31c) | Apr 08, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [fa773129c2](https://linux-hardware.org/?probe=fa773129c2) | Apr 08, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [937a23fec5](https://linux-hardware.org/?probe=937a23fec5) | Apr 08, 2024 |
| HP            | 15                          | Notebook    | [8e4dc27da3](https://linux-hardware.org/?probe=8e4dc27da3) | Apr 08, 2024 |
| MSI           | A55M-P33                    | Desktop     | [4116940d72](https://linux-hardware.org/?probe=4116940d72) | Apr 08, 2024 |
| MSI           | A55M-P33                    | Desktop     | [0697630ce1](https://linux-hardware.org/?probe=0697630ce1) | Apr 08, 2024 |
| Acer          | Aspire XC-705               | Desktop     | [867eb764b1](https://linux-hardware.org/?probe=867eb764b1) | Apr 08, 2024 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [3fb9602631](https://linux-hardware.org/?probe=3fb9602631) | Apr 08, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [33dd11bc5b](https://linux-hardware.org/?probe=33dd11bc5b) | Apr 07, 2024 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [74499eab00](https://linux-hardware.org/?probe=74499eab00) | Apr 07, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [daeb8bc353](https://linux-hardware.org/?probe=daeb8bc353) | Apr 07, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [e6d6bf8f56](https://linux-hardware.org/?probe=e6d6bf8f56) | Apr 06, 2024 |
| ASUSTek       | N551JX                      | Notebook    | [e7f0a7b86d](https://linux-hardware.org/?probe=e7f0a7b86d) | Apr 06, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [f436469297](https://linux-hardware.org/?probe=f436469297) | Apr 06, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9207cd6c9a](https://linux-hardware.org/?probe=9207cd6c9a) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [edbaa46cbe](https://linux-hardware.org/?probe=edbaa46cbe) | Apr 05, 2024 |
| MSI           | MS-B9241                    | Desktop     | [f0b74d9e54](https://linux-hardware.org/?probe=f0b74d9e54) | Apr 05, 2024 |
| Unknown       | V00                         | Mini pc     | [65a304e1cd](https://linux-hardware.org/?probe=65a304e1cd) | Apr 05, 2024 |
| Avell High... | B.ON                        | Notebook    | [9070104d8b](https://linux-hardware.org/?probe=9070104d8b) | Apr 05, 2024 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [62fb7b6781](https://linux-hardware.org/?probe=62fb7b6781) | Apr 05, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [8f37d9426f](https://linux-hardware.org/?probe=8f37d9426f) | Apr 05, 2024 |
| HP            | Laptop 15q-ds0xxx           | Notebook    | [64e20f99d6](https://linux-hardware.org/?probe=64e20f99d6) | Apr 05, 2024 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [35844b49db](https://linux-hardware.org/?probe=35844b49db) | Apr 04, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [b453824271](https://linux-hardware.org/?probe=b453824271) | Apr 04, 2024 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [00654fb268](https://linux-hardware.org/?probe=00654fb268) | Apr 04, 2024 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [aaec2396a7](https://linux-hardware.org/?probe=aaec2396a7) | Apr 03, 2024 |
| EXTRA Comp... | MS-1758                     | Notebook    | [2035bb619e](https://linux-hardware.org/?probe=2035bb619e) | Apr 03, 2024 |
| EXTRA Comp... | MS-1758                     | Notebook    | [eb223535ec](https://linux-hardware.org/?probe=eb223535ec) | Apr 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3afa8d09c7](https://linux-hardware.org/?probe=3afa8d09c7) | Apr 02, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [54060d2e31](https://linux-hardware.org/?probe=54060d2e31) | Apr 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bba7520a79](https://linux-hardware.org/?probe=bba7520a79) | Apr 01, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [10b376d6b8](https://linux-hardware.org/?probe=10b376d6b8) | Apr 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d82daf5b14](https://linux-hardware.org/?probe=d82daf5b14) | Apr 01, 2024 |
| Lenovo        | ThinkPad E520 1143R77       | Notebook    | [5aa9f4eb4b](https://linux-hardware.org/?probe=5aa9f4eb4b) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8b7a171522](https://linux-hardware.org/?probe=8b7a171522) | Mar 31, 2024 |
| Lenovo        | IdeaCentre K430             | Desktop     | [b72fcce004](https://linux-hardware.org/?probe=b72fcce004) | Mar 31, 2024 |
| Lenovo        | IdeaCentre K430             | Desktop     | [a2c9b21fb9](https://linux-hardware.org/?probe=a2c9b21fb9) | Mar 31, 2024 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [84b0e3e2af](https://linux-hardware.org/?probe=84b0e3e2af) | Mar 31, 2024 |
| Unknown       | EZpad                       | Tablet      | [0001634658](https://linux-hardware.org/?probe=0001634658) | Mar 30, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [175015e349](https://linux-hardware.org/?probe=175015e349) | Mar 30, 2024 |
| Wortmann      | 1220571_1470066             | Notebook    | [702441f1cb](https://linux-hardware.org/?probe=702441f1cb) | Mar 30, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [ec84be5fad](https://linux-hardware.org/?probe=ec84be5fad) | Mar 30, 2024 |
| Avell High... | B.ON                        | Notebook    | [577f3c12bf](https://linux-hardware.org/?probe=577f3c12bf) | Mar 30, 2024 |
| Dell          | G3 3590                     | Notebook    | [5d1da882a1](https://linux-hardware.org/?probe=5d1da882a1) | Mar 30, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ab1cbc61a9](https://linux-hardware.org/?probe=ab1cbc61a9) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [8a49203e45](https://linux-hardware.org/?probe=8a49203e45) | Mar 30, 2024 |
| Dell          | Latitude 5580               | Notebook    | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [75c0051304](https://linux-hardware.org/?probe=75c0051304) | Mar 28, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [54e2230e47](https://linux-hardware.org/?probe=54e2230e47) | Mar 28, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [fe3bb27b46](https://linux-hardware.org/?probe=fe3bb27b46) | Mar 28, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [ff78c23f0b](https://linux-hardware.org/?probe=ff78c23f0b) | Mar 28, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [df7168fb55](https://linux-hardware.org/?probe=df7168fb55) | Mar 28, 2024 |
| HP            | 1998                        | Desktop     | [4c2971ed76](https://linux-hardware.org/?probe=4c2971ed76) | Mar 27, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [b36db98ee9](https://linux-hardware.org/?probe=b36db98ee9) | Mar 27, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [d73ccce6fc](https://linux-hardware.org/?probe=d73ccce6fc) | Mar 27, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [80ad3b2985](https://linux-hardware.org/?probe=80ad3b2985) | Mar 27, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [44a28c885e](https://linux-hardware.org/?probe=44a28c885e) | Mar 27, 2024 |
| HP            | Notebook                    | Notebook    | [1b9763e964](https://linux-hardware.org/?probe=1b9763e964) | Mar 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [96680ae64f](https://linux-hardware.org/?probe=96680ae64f) | Mar 26, 2024 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [9bcf8d91cc](https://linux-hardware.org/?probe=9bcf8d91cc) | Mar 26, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [8f85bd11a7](https://linux-hardware.org/?probe=8f85bd11a7) | Mar 26, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [f4df9e06b2](https://linux-hardware.org/?probe=f4df9e06b2) | Mar 26, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [baff8cb9b8](https://linux-hardware.org/?probe=baff8cb9b8) | Mar 25, 2024 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [d71f48c168](https://linux-hardware.org/?probe=d71f48c168) | Mar 25, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [2e8543e629](https://linux-hardware.org/?probe=2e8543e629) | Mar 25, 2024 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [29a1e96961](https://linux-hardware.org/?probe=29a1e96961) | Mar 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [21cb087ae2](https://linux-hardware.org/?probe=21cb087ae2) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [97a323caf9](https://linux-hardware.org/?probe=97a323caf9) | Mar 25, 2024 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [fdc15386b1](https://linux-hardware.org/?probe=fdc15386b1) | Mar 24, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [401ed2252e](https://linux-hardware.org/?probe=401ed2252e) | Mar 24, 2024 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [2709ea9b5c](https://linux-hardware.org/?probe=2709ea9b5c) | Mar 24, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [9afa8e9c42](https://linux-hardware.org/?probe=9afa8e9c42) | Mar 24, 2024 |
| Star Labs     | StarBook                    | Notebook    | [93976aeded](https://linux-hardware.org/?probe=93976aeded) | Mar 24, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [2cea54d4d5](https://linux-hardware.org/?probe=2cea54d4d5) | Mar 24, 2024 |
| HP            | 1998                        | Desktop     | [d8865ee940](https://linux-hardware.org/?probe=d8865ee940) | Mar 24, 2024 |
| Dell          | Inspiron 7580               | Notebook    | [8175d8b6de](https://linux-hardware.org/?probe=8175d8b6de) | Mar 24, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [be3135994e](https://linux-hardware.org/?probe=be3135994e) | Mar 23, 2024 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [a94b3b4bd4](https://linux-hardware.org/?probe=a94b3b4bd4) | Mar 23, 2024 |
| ASRock        | Z390 Phantom Gaming 4-CB    | Desktop     | [b57290ea52](https://linux-hardware.org/?probe=b57290ea52) | Mar 23, 2024 |
| Unknown       | Cherry Trail CR             | Notebook    | [efb2513f33](https://linux-hardware.org/?probe=efb2513f33) | Mar 22, 2024 |
| HP            | ENVY 17 Notebook PC         | Notebook    | [7add9d6d29](https://linux-hardware.org/?probe=7add9d6d29) | Mar 22, 2024 |
| Lenovo        | B590 20208                  | Notebook    | [22c0d1ef85](https://linux-hardware.org/?probe=22c0d1ef85) | Mar 22, 2024 |
| HONOR         | HYM-WXX                     | Notebook    | [2d11f15773](https://linux-hardware.org/?probe=2d11f15773) | Mar 22, 2024 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [5efc983ef2](https://linux-hardware.org/?probe=5efc983ef2) | Mar 21, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [cfac3d0451](https://linux-hardware.org/?probe=cfac3d0451) | Mar 21, 2024 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [af9f7dda55](https://linux-hardware.org/?probe=af9f7dda55) | Mar 20, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [928d1b1d84](https://linux-hardware.org/?probe=928d1b1d84) | Mar 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dddc8e40c7](https://linux-hardware.org/?probe=dddc8e40c7) | Mar 20, 2024 |
| HP            | Pavilion 15                 | Notebook    | [6901a5764b](https://linux-hardware.org/?probe=6901a5764b) | Mar 20, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [c2a845d2ed](https://linux-hardware.org/?probe=c2a845d2ed) | Mar 19, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dfc5f12487](https://linux-hardware.org/?probe=dfc5f12487) | Mar 19, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [891d67a053](https://linux-hardware.org/?probe=891d67a053) | Mar 19, 2024 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS2... | Notebook    | [87bd273b48](https://linux-hardware.org/?probe=87bd273b48) | Mar 19, 2024 |
| Lenovo        | 102F                        | Desktop     | [e4e070f4df](https://linux-hardware.org/?probe=e4e070f4df) | Mar 19, 2024 |
| Acer          | Aspire A515-55              | Notebook    | [42252ad0cc](https://linux-hardware.org/?probe=42252ad0cc) | Mar 19, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [04c8384abd](https://linux-hardware.org/?probe=04c8384abd) | Mar 19, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [3dd98d315b](https://linux-hardware.org/?probe=3dd98d315b) | Mar 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C11... | Notebook    | [043dcda6e9](https://linux-hardware.org/?probe=043dcda6e9) | Mar 18, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2d7fd89873](https://linux-hardware.org/?probe=2d7fd89873) | Mar 18, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [86614957f2](https://linux-hardware.org/?probe=86614957f2) | Mar 17, 2024 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [d24e51a631](https://linux-hardware.org/?probe=d24e51a631) | Mar 17, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | Desktop     | [27baad85ff](https://linux-hardware.org/?probe=27baad85ff) | Mar 17, 2024 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [427e8024f2](https://linux-hardware.org/?probe=427e8024f2) | Mar 17, 2024 |
| ASRock        | A780GM-LE                   | Desktop     | [cfc1958990](https://linux-hardware.org/?probe=cfc1958990) | Mar 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a98bd8065a](https://linux-hardware.org/?probe=a98bd8065a) | Mar 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dff6166e47](https://linux-hardware.org/?probe=dff6166e47) | Mar 16, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [6130454352](https://linux-hardware.org/?probe=6130454352) | Mar 16, 2024 |
| ASUSTek       | E1600WKA                    | All in one  | [c96a90df46](https://linux-hardware.org/?probe=c96a90df46) | Mar 16, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9170e8c21f](https://linux-hardware.org/?probe=9170e8c21f) | Mar 16, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [494ed5303a](https://linux-hardware.org/?probe=494ed5303a) | Mar 16, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [0f3b430878](https://linux-hardware.org/?probe=0f3b430878) | Mar 15, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [582d3628d3](https://linux-hardware.org/?probe=582d3628d3) | Mar 15, 2024 |
| GPU Compan... | GWTN141-10                  | Notebook    | [a9ab30227d](https://linux-hardware.org/?probe=a9ab30227d) | Mar 15, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [bd231eead5](https://linux-hardware.org/?probe=bd231eead5) | Mar 15, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c63d09f5fa](https://linux-hardware.org/?probe=c63d09f5fa) | Mar 15, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [3f7ac15be0](https://linux-hardware.org/?probe=3f7ac15be0) | Mar 15, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cdcb2eddcf](https://linux-hardware.org/?probe=cdcb2eddcf) | Mar 15, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [8a576ef6a9](https://linux-hardware.org/?probe=8a576ef6a9) | Mar 15, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a80e2be7ab](https://linux-hardware.org/?probe=a80e2be7ab) | Mar 14, 2024 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [bd35285f2c](https://linux-hardware.org/?probe=bd35285f2c) | Mar 14, 2024 |
| Dell          | Unidentified System         | Notebook    | [bab85b187d](https://linux-hardware.org/?probe=bab85b187d) | Mar 14, 2024 |
| Alienware     | 07HV66 A01                  | Desktop     | [b94fccbefa](https://linux-hardware.org/?probe=b94fccbefa) | Mar 13, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [56218fcc37](https://linux-hardware.org/?probe=56218fcc37) | Mar 13, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [9fd3e4a19d](https://linux-hardware.org/?probe=9fd3e4a19d) | Mar 13, 2024 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [297e0ad092](https://linux-hardware.org/?probe=297e0ad092) | Mar 13, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c4fe7430eb](https://linux-hardware.org/?probe=c4fe7430eb) | Mar 13, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [5bd971f4fe](https://linux-hardware.org/?probe=5bd971f4fe) | Mar 12, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [7cefc8c569](https://linux-hardware.org/?probe=7cefc8c569) | Mar 12, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [fed8a21f01](https://linux-hardware.org/?probe=fed8a21f01) | Mar 12, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [f3a4539b51](https://linux-hardware.org/?probe=f3a4539b51) | Mar 12, 2024 |
| Sony          | SVF1521Q1EW                 | Notebook    | [a8c6dba463](https://linux-hardware.org/?probe=a8c6dba463) | Mar 12, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [35a7d6e7ed](https://linux-hardware.org/?probe=35a7d6e7ed) | Mar 11, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ea8dd3c585](https://linux-hardware.org/?probe=ea8dd3c585) | Mar 11, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | Desktop     | [e922cff9f6](https://linux-hardware.org/?probe=e922cff9f6) | Mar 11, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [23ac7afe02](https://linux-hardware.org/?probe=23ac7afe02) | Mar 11, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [d1eb9c18ad](https://linux-hardware.org/?probe=d1eb9c18ad) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [4c224edb1a](https://linux-hardware.org/?probe=4c224edb1a) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f18cdf7cd0](https://linux-hardware.org/?probe=f18cdf7cd0) | Mar 11, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [5035a532a3](https://linux-hardware.org/?probe=5035a532a3) | Mar 11, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [0c55a3dc95](https://linux-hardware.org/?probe=0c55a3dc95) | Mar 10, 2024 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [44866c275d](https://linux-hardware.org/?probe=44866c275d) | Mar 10, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [78ab08dee5](https://linux-hardware.org/?probe=78ab08dee5) | Mar 09, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [4832f2d4f3](https://linux-hardware.org/?probe=4832f2d4f3) | Mar 09, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [bb366ca4ff](https://linux-hardware.org/?probe=bb366ca4ff) | Mar 09, 2024 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [8747621558](https://linux-hardware.org/?probe=8747621558) | Mar 09, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [da327f64f7](https://linux-hardware.org/?probe=da327f64f7) | Mar 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [afa0de9aa3](https://linux-hardware.org/?probe=afa0de9aa3) | Mar 09, 2024 |
| Dell          | Latitude 7280               | Notebook    | [1149975fb9](https://linux-hardware.org/?probe=1149975fb9) | Mar 08, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [3908a94356](https://linux-hardware.org/?probe=3908a94356) | Mar 08, 2024 |
| Google        | Voxel                       | Notebook    | [9990aee89e](https://linux-hardware.org/?probe=9990aee89e) | Mar 08, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [1b2e1ca711](https://linux-hardware.org/?probe=1b2e1ca711) | Mar 08, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [6e8fa415b9](https://linux-hardware.org/?probe=6e8fa415b9) | Mar 08, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [504620c576](https://linux-hardware.org/?probe=504620c576) | Mar 08, 2024 |
| Dell          | Inspiron 7537               | Notebook    | [197adab8a5](https://linux-hardware.org/?probe=197adab8a5) | Mar 07, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [7e89a95523](https://linux-hardware.org/?probe=7e89a95523) | Mar 06, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [8bf6517d80](https://linux-hardware.org/?probe=8bf6517d80) | Mar 06, 2024 |
| HP            | 8704                        | Desktop     | [a9a02c9d98](https://linux-hardware.org/?probe=a9a02c9d98) | Mar 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [299b810e81](https://linux-hardware.org/?probe=299b810e81) | Mar 06, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ab417c3289](https://linux-hardware.org/?probe=ab417c3289) | Mar 06, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5602abb8e5](https://linux-hardware.org/?probe=5602abb8e5) | Mar 05, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e3503e808b](https://linux-hardware.org/?probe=e3503e808b) | Mar 05, 2024 |
| MSI           | 970 GAMING                  | Desktop     | [7ec06861ba](https://linux-hardware.org/?probe=7ec06861ba) | Mar 05, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [f46cf35368](https://linux-hardware.org/?probe=f46cf35368) | Mar 05, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [7165f80198](https://linux-hardware.org/?probe=7165f80198) | Mar 04, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [34133ba182](https://linux-hardware.org/?probe=34133ba182) | Mar 04, 2024 |
| Lenovo        | ThinkPad T470 20HD000EHV    | Notebook    | [b2d96be2dd](https://linux-hardware.org/?probe=b2d96be2dd) | Mar 04, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [e8081f5809](https://linux-hardware.org/?probe=e8081f5809) | Mar 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1d8f8e4d0f](https://linux-hardware.org/?probe=1d8f8e4d0f) | Mar 04, 2024 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [65080da98c](https://linux-hardware.org/?probe=65080da98c) | Mar 04, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [0304104a60](https://linux-hardware.org/?probe=0304104a60) | Mar 03, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [b6012299f3](https://linux-hardware.org/?probe=b6012299f3) | Mar 03, 2024 |
| ASRock        | Z390 Phantom Gaming 4S-I... | Desktop     | [b323dd518d](https://linux-hardware.org/?probe=b323dd518d) | Mar 02, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [e8f7a7959b](https://linux-hardware.org/?probe=e8f7a7959b) | Mar 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [336cabac77](https://linux-hardware.org/?probe=336cabac77) | Mar 02, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [8797322d65](https://linux-hardware.org/?probe=8797322d65) | Mar 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [59d562ccb2](https://linux-hardware.org/?probe=59d562ccb2) | Mar 02, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [49325a9c62](https://linux-hardware.org/?probe=49325a9c62) | Mar 01, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX ICE     | Desktop     | [4a327fd904](https://linux-hardware.org/?probe=4a327fd904) | Mar 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b58bb65fff](https://linux-hardware.org/?probe=b58bb65fff) | Mar 01, 2024 |
| Acer          | Aspire Z3-615               | All in one  | [fd9c0e6b48](https://linux-hardware.org/?probe=fd9c0e6b48) | Feb 29, 2024 |
| Dell          | XPS 17 9700                 | Notebook    | [b4e8c94b56](https://linux-hardware.org/?probe=b4e8c94b56) | Feb 29, 2024 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [e0277e4684](https://linux-hardware.org/?probe=e0277e4684) | Feb 29, 2024 |
| AZW           | LZX TBD                     | Desktop     | [2036ce8e24](https://linux-hardware.org/?probe=2036ce8e24) | Feb 29, 2024 |
| Fujitsu       | LIFEBOOK T725               | Notebook    | [4f3102fa7d](https://linux-hardware.org/?probe=4f3102fa7d) | Feb 29, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [1043b72dee](https://linux-hardware.org/?probe=1043b72dee) | Feb 29, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [15c3307e88](https://linux-hardware.org/?probe=15c3307e88) | Feb 28, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [62b6009aaa](https://linux-hardware.org/?probe=62b6009aaa) | Feb 28, 2024 |
| Acer          | Swift SF114-34              | Notebook    | [75d2193098](https://linux-hardware.org/?probe=75d2193098) | Feb 28, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3022d85c07](https://linux-hardware.org/?probe=3022d85c07) | Feb 28, 2024 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [49640f04ca](https://linux-hardware.org/?probe=49640f04ca) | Feb 28, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [e947cc88f8](https://linux-hardware.org/?probe=e947cc88f8) | Feb 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [d549a1c39d](https://linux-hardware.org/?probe=d549a1c39d) | Feb 27, 2024 |
| Dell          | 03NVJ6 A00                  | Desktop     | [18e6ec9743](https://linux-hardware.org/?probe=18e6ec9743) | Feb 27, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8f3bba3e55](https://linux-hardware.org/?probe=8f3bba3e55) | Feb 27, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [57bd86e0d4](https://linux-hardware.org/?probe=57bd86e0d4) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [4635af4aa0](https://linux-hardware.org/?probe=4635af4aa0) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [ead35b6d5c](https://linux-hardware.org/?probe=ead35b6d5c) | Feb 26, 2024 |
| Acer          | Veriton M4660G V:1.0        | Desktop     | [f4d17adcc4](https://linux-hardware.org/?probe=f4d17adcc4) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [2c00c513d3](https://linux-hardware.org/?probe=2c00c513d3) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60b6b91372](https://linux-hardware.org/?probe=60b6b91372) | Feb 26, 2024 |
| MSI           | GF63 8RD                    | Notebook    | [b933a88005](https://linux-hardware.org/?probe=b933a88005) | Feb 26, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [98eac26d47](https://linux-hardware.org/?probe=98eac26d47) | Feb 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4c07576f6](https://linux-hardware.org/?probe=e4c07576f6) | Feb 26, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [039a83b180](https://linux-hardware.org/?probe=039a83b180) | Feb 25, 2024 |
| ASUSTek       | P7P55-M                     | Desktop     | [3ea869d864](https://linux-hardware.org/?probe=3ea869d864) | Feb 24, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | Notebook    | [73250b5f33](https://linux-hardware.org/?probe=73250b5f33) | Feb 24, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [84300cc9c1](https://linux-hardware.org/?probe=84300cc9c1) | Feb 24, 2024 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [ec1d2f8b0d](https://linux-hardware.org/?probe=ec1d2f8b0d) | Feb 24, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [2b1f681fd3](https://linux-hardware.org/?probe=2b1f681fd3) | Feb 24, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [b8f9baa1db](https://linux-hardware.org/?probe=b8f9baa1db) | Feb 24, 2024 |
| Dell          | Latitude 5179               | Tablet      | [b3f168923b](https://linux-hardware.org/?probe=b3f168923b) | Feb 24, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [8173a2268e](https://linux-hardware.org/?probe=8173a2268e) | Feb 24, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [9e7c47300c](https://linux-hardware.org/?probe=9e7c47300c) | Feb 24, 2024 |
| Apple         | MacBookPro16,3              | Notebook    | [4921eebd7d](https://linux-hardware.org/?probe=4921eebd7d) | Feb 23, 2024 |
| HP            | 255 G1                      | Notebook    | [ff401d3204](https://linux-hardware.org/?probe=ff401d3204) | Feb 23, 2024 |
| HP            | 1496                        | Desktop     | [1cc3bd19db](https://linux-hardware.org/?probe=1cc3bd19db) | Feb 23, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [63323ac7cf](https://linux-hardware.org/?probe=63323ac7cf) | Feb 23, 2024 |
| Gigabyte      | B760M DS3H                  | Desktop     | [7e6352f1af](https://linux-hardware.org/?probe=7e6352f1af) | Feb 23, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [55a9d1f030](https://linux-hardware.org/?probe=55a9d1f030) | Feb 22, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [682708c8fc](https://linux-hardware.org/?probe=682708c8fc) | Feb 22, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [7b6aebf503](https://linux-hardware.org/?probe=7b6aebf503) | Feb 22, 2024 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [bc6b844872](https://linux-hardware.org/?probe=bc6b844872) | Feb 22, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [5f363c641f](https://linux-hardware.org/?probe=5f363c641f) | Feb 22, 2024 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6511d32b6d](https://linux-hardware.org/?probe=6511d32b6d) | Feb 22, 2024 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [daeb6385eb](https://linux-hardware.org/?probe=daeb6385eb) | Feb 22, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f317a83d41](https://linux-hardware.org/?probe=f317a83d41) | Feb 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [dbfe2d4d52](https://linux-hardware.org/?probe=dbfe2d4d52) | Feb 22, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [af9bba507c](https://linux-hardware.org/?probe=af9bba507c) | Feb 22, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [857257c8f8](https://linux-hardware.org/?probe=857257c8f8) | Feb 21, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [6ca9a09551](https://linux-hardware.org/?probe=6ca9a09551) | Feb 21, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [1e64feccdb](https://linux-hardware.org/?probe=1e64feccdb) | Feb 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6b768aaf97](https://linux-hardware.org/?probe=6b768aaf97) | Feb 21, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [b22962f486](https://linux-hardware.org/?probe=b22962f486) | Feb 20, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [eacc26c850](https://linux-hardware.org/?probe=eacc26c850) | Feb 20, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [76b5749b02](https://linux-hardware.org/?probe=76b5749b02) | Feb 20, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [844cae8943](https://linux-hardware.org/?probe=844cae8943) | Feb 20, 2024 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [034c817132](https://linux-hardware.org/?probe=034c817132) | Feb 20, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX ICE     | Desktop     | [bcd7e37ea6](https://linux-hardware.org/?probe=bcd7e37ea6) | Feb 19, 2024 |
| Dell          | Latitude E6530              | Notebook    | [cd8cb1807f](https://linux-hardware.org/?probe=cd8cb1807f) | Feb 19, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [7ce601e458](https://linux-hardware.org/?probe=7ce601e458) | Feb 19, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX ICE     | Desktop     | [917ab93492](https://linux-hardware.org/?probe=917ab93492) | Feb 19, 2024 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [862807dfbb](https://linux-hardware.org/?probe=862807dfbb) | Feb 19, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [061476515d](https://linux-hardware.org/?probe=061476515d) | Feb 18, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [e7b2834297](https://linux-hardware.org/?probe=e7b2834297) | Feb 18, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [129f9eb367](https://linux-hardware.org/?probe=129f9eb367) | Feb 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [81acc04317](https://linux-hardware.org/?probe=81acc04317) | Feb 17, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9ba5899cee](https://linux-hardware.org/?probe=9ba5899cee) | Feb 17, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8d4e7679e](https://linux-hardware.org/?probe=f8d4e7679e) | Feb 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78267b0204](https://linux-hardware.org/?probe=78267b0204) | Feb 17, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [288572728a](https://linux-hardware.org/?probe=288572728a) | Feb 17, 2024 |
| Dell          | 047FGK A00                  | Mini pc     | [fdee6678fc](https://linux-hardware.org/?probe=fdee6678fc) | Feb 17, 2024 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [c220d545b2](https://linux-hardware.org/?probe=c220d545b2) | Feb 17, 2024 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [4886dcfde6](https://linux-hardware.org/?probe=4886dcfde6) | Feb 17, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [ecfbf20c60](https://linux-hardware.org/?probe=ecfbf20c60) | Feb 16, 2024 |
| Sony          | VPCEE37FL                   | Notebook    | [611371a88b](https://linux-hardware.org/?probe=611371a88b) | Feb 16, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [9e0a3e5b40](https://linux-hardware.org/?probe=9e0a3e5b40) | Feb 16, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [106c5b5cdb](https://linux-hardware.org/?probe=106c5b5cdb) | Feb 15, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [96a731aa8d](https://linux-hardware.org/?probe=96a731aa8d) | Feb 15, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [2b9bdf9093](https://linux-hardware.org/?probe=2b9bdf9093) | Feb 15, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [3ea0c302a4](https://linux-hardware.org/?probe=3ea0c302a4) | Feb 15, 2024 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [5f6e7affee](https://linux-hardware.org/?probe=5f6e7affee) | Feb 14, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [f6ae281d7d](https://linux-hardware.org/?probe=f6ae281d7d) | Feb 14, 2024 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [93a81f85e2](https://linux-hardware.org/?probe=93a81f85e2) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [0df8d427ea](https://linux-hardware.org/?probe=0df8d427ea) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [a1010c1dc5](https://linux-hardware.org/?probe=a1010c1dc5) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [5be4fcf8fd](https://linux-hardware.org/?probe=5be4fcf8fd) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [4d5af450c4](https://linux-hardware.org/?probe=4d5af450c4) | Feb 14, 2024 |
| Lenovo        | G470 20078                  | Notebook    | [03e084a881](https://linux-hardware.org/?probe=03e084a881) | Feb 14, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [385a58367a](https://linux-hardware.org/?probe=385a58367a) | Feb 14, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | Desktop     | [d0a9f3664e](https://linux-hardware.org/?probe=d0a9f3664e) | Feb 13, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c5a7934836](https://linux-hardware.org/?probe=c5a7934836) | Feb 13, 2024 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [6a09917f6f](https://linux-hardware.org/?probe=6a09917f6f) | Feb 13, 2024 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [c82778e496](https://linux-hardware.org/?probe=c82778e496) | Feb 13, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [0b68327f4f](https://linux-hardware.org/?probe=0b68327f4f) | Feb 13, 2024 |
| HP            | 843B                        | Desktop     | [aa6fd9964e](https://linux-hardware.org/?probe=aa6fd9964e) | Feb 13, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [7d0d42af14](https://linux-hardware.org/?probe=7d0d42af14) | Feb 13, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [1111f10cce](https://linux-hardware.org/?probe=1111f10cce) | Feb 13, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f8f33cacdf](https://linux-hardware.org/?probe=f8f33cacdf) | Feb 13, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [d271f4b0ca](https://linux-hardware.org/?probe=d271f4b0ca) | Feb 12, 2024 |
| Dell          | Latitude E5420              | Notebook    | [e5f8d8fab7](https://linux-hardware.org/?probe=e5f8d8fab7) | Feb 12, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [25f4ea22cd](https://linux-hardware.org/?probe=25f4ea22cd) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [7465298e19](https://linux-hardware.org/?probe=7465298e19) | Feb 12, 2024 |
| HP            | G62                         | Notebook    | [b6daa4e6b1](https://linux-hardware.org/?probe=b6daa4e6b1) | Feb 12, 2024 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6f6d39cf77](https://linux-hardware.org/?probe=6f6d39cf77) | Feb 12, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [00a2a68eef](https://linux-hardware.org/?probe=00a2a68eef) | Feb 12, 2024 |
| AMD           | 990FXA-UD3                  | Desktop     | [a8866aee9c](https://linux-hardware.org/?probe=a8866aee9c) | Feb 12, 2024 |
| Lenovo        | ThinkPad P51 20HJS3Q700     | Notebook    | [2de6ff345e](https://linux-hardware.org/?probe=2de6ff345e) | Feb 12, 2024 |
| Samsung       | 750QFG                      | Convertible | [a3e518ea21](https://linux-hardware.org/?probe=a3e518ea21) | Feb 11, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [27505f5d96](https://linux-hardware.org/?probe=27505f5d96) | Feb 11, 2024 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [d232086b57](https://linux-hardware.org/?probe=d232086b57) | Feb 11, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [4ee3aae45e](https://linux-hardware.org/?probe=4ee3aae45e) | Feb 11, 2024 |
| Acer          | Aspire E5-476G              | Notebook    | [dbdd6adbd1](https://linux-hardware.org/?probe=dbdd6adbd1) | Feb 11, 2024 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [1c8831a84d](https://linux-hardware.org/?probe=1c8831a84d) | Feb 11, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fd93dfb574](https://linux-hardware.org/?probe=fd93dfb574) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [0a197d31ec](https://linux-hardware.org/?probe=0a197d31ec) | Feb 10, 2024 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [918a5487fe](https://linux-hardware.org/?probe=918a5487fe) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [bc1e6e90c1](https://linux-hardware.org/?probe=bc1e6e90c1) | Feb 10, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [166c275408](https://linux-hardware.org/?probe=166c275408) | Feb 10, 2024 |
| HP            | 1998                        | Desktop     | [de3c15346c](https://linux-hardware.org/?probe=de3c15346c) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0c1b63b275](https://linux-hardware.org/?probe=0c1b63b275) | Feb 10, 2024 |
| MSI           | X99A SLI PLUS               | Desktop     | [4681488249](https://linux-hardware.org/?probe=4681488249) | Feb 10, 2024 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [9fee66c070](https://linux-hardware.org/?probe=9fee66c070) | Feb 10, 2024 |
| AAEON         | S500 V1.0                   | Desktop     | [e4d8723e6f](https://linux-hardware.org/?probe=e4d8723e6f) | Feb 09, 2024 |
| Intel         | NUC13SBBi7 M89885-303       | Mini pc     | [f096c5fea7](https://linux-hardware.org/?probe=f096c5fea7) | Feb 09, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [5e72988c18](https://linux-hardware.org/?probe=5e72988c18) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [88e8815be3](https://linux-hardware.org/?probe=88e8815be3) | Feb 08, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8a9bf9c2bc](https://linux-hardware.org/?probe=8a9bf9c2bc) | Feb 08, 2024 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [b38610da22](https://linux-hardware.org/?probe=b38610da22) | Feb 07, 2024 |
| Dell          | Inspiron 5593               | Notebook    | [2a2f735595](https://linux-hardware.org/?probe=2a2f735595) | Feb 07, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | Desktop     | [df029c3635](https://linux-hardware.org/?probe=df029c3635) | Feb 07, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [ff633ac02f](https://linux-hardware.org/?probe=ff633ac02f) | Feb 07, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [bb080b509b](https://linux-hardware.org/?probe=bb080b509b) | Feb 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [85c4dfa0f4](https://linux-hardware.org/?probe=85c4dfa0f4) | Feb 07, 2024 |
| ASRock        | Z790 PG-ITX/TB4             | Desktop     | [df4c402e7d](https://linux-hardware.org/?probe=df4c402e7d) | Feb 07, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [790b3a7124](https://linux-hardware.org/?probe=790b3a7124) | Feb 07, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [22cd39d25b](https://linux-hardware.org/?probe=22cd39d25b) | Feb 06, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2bdeaafbb9](https://linux-hardware.org/?probe=2bdeaafbb9) | Feb 06, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [751b66639b](https://linux-hardware.org/?probe=751b66639b) | Feb 05, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7373f73199](https://linux-hardware.org/?probe=7373f73199) | Feb 05, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [429b3c3517](https://linux-hardware.org/?probe=429b3c3517) | Feb 05, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4b6f872d8b](https://linux-hardware.org/?probe=4b6f872d8b) | Feb 05, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9af8c5b8ed](https://linux-hardware.org/?probe=9af8c5b8ed) | Feb 05, 2024 |
| HP            | 1998                        | Desktop     | [5e85b19897](https://linux-hardware.org/?probe=5e85b19897) | Feb 05, 2024 |
| AZW           | EQ MINI 10                  | Desktop     | [17aec34e47](https://linux-hardware.org/?probe=17aec34e47) | Feb 05, 2024 |
| Toshiba       | QOSMIO X505                 | Notebook    | [109be22d5f](https://linux-hardware.org/?probe=109be22d5f) | Feb 05, 2024 |
| HP            | Pavilion 15                 | Notebook    | [066b0cf774](https://linux-hardware.org/?probe=066b0cf774) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d731c8db9a](https://linux-hardware.org/?probe=d731c8db9a) | Feb 04, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [732db9f3b4](https://linux-hardware.org/?probe=732db9f3b4) | Feb 04, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [24bf3674dc](https://linux-hardware.org/?probe=24bf3674dc) | Feb 04, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [7d98e0f393](https://linux-hardware.org/?probe=7d98e0f393) | Feb 04, 2024 |
| Lenovo        | ThinkPad E520 1143R77       | Notebook    | [b36ea31ed6](https://linux-hardware.org/?probe=b36ea31ed6) | Feb 04, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [984cacb97a](https://linux-hardware.org/?probe=984cacb97a) | Feb 04, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [489a0859f2](https://linux-hardware.org/?probe=489a0859f2) | Feb 03, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [6719f31d16](https://linux-hardware.org/?probe=6719f31d16) | Feb 03, 2024 |
| Dell          | Inspiron 5593               | Notebook    | [99994880b0](https://linux-hardware.org/?probe=99994880b0) | Feb 03, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [f57c7238f4](https://linux-hardware.org/?probe=f57c7238f4) | Feb 03, 2024 |
| Biostar       | G41-M7                      | Desktop     | [eea33a47ac](https://linux-hardware.org/?probe=eea33a47ac) | Feb 03, 2024 |
| Dell          | Latitude 5591               | Notebook    | [4d40381f13](https://linux-hardware.org/?probe=4d40381f13) | Feb 03, 2024 |
| Dell          | Latitude 5591               | Notebook    | [cd7d3e9257](https://linux-hardware.org/?probe=cd7d3e9257) | Feb 03, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [58d150eef2](https://linux-hardware.org/?probe=58d150eef2) | Feb 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [8c03bd946c](https://linux-hardware.org/?probe=8c03bd946c) | Feb 02, 2024 |
| Notebook      | V15x_V17xRNx                | Notebook    | [901e71289e](https://linux-hardware.org/?probe=901e71289e) | Feb 02, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [ce1ff05aed](https://linux-hardware.org/?probe=ce1ff05aed) | Feb 02, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [63522c9a09](https://linux-hardware.org/?probe=63522c9a09) | Feb 02, 2024 |
| GX55          | Unknown                     | Tablet      | [99db62ac14](https://linux-hardware.org/?probe=99db62ac14) | Feb 02, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [507fad3c00](https://linux-hardware.org/?probe=507fad3c00) | Feb 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [c2514048e9](https://linux-hardware.org/?probe=c2514048e9) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8e3680cd5d](https://linux-hardware.org/?probe=8e3680cd5d) | Feb 01, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6c75053ee6](https://linux-hardware.org/?probe=6c75053ee6) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f1b0b8716f](https://linux-hardware.org/?probe=f1b0b8716f) | Feb 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [9d2088ace3](https://linux-hardware.org/?probe=9d2088ace3) | Feb 01, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [8f630da527](https://linux-hardware.org/?probe=8f630da527) | Jan 31, 2024 |
| Dell          | 0YJPT1 A00                  | Desktop     | [014e8534ab](https://linux-hardware.org/?probe=014e8534ab) | Jan 31, 2024 |
| MSI           | Creator M16 A12UC           | Notebook    | [804a70b7f5](https://linux-hardware.org/?probe=804a70b7f5) | Jan 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [02d7b129fc](https://linux-hardware.org/?probe=02d7b129fc) | Jan 31, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [fd4b4dd902](https://linux-hardware.org/?probe=fd4b4dd902) | Jan 31, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [a477ec4fe1](https://linux-hardware.org/?probe=a477ec4fe1) | Jan 31, 2024 |
| HP            | 1998                        | Desktop     | [8ab7c171c3](https://linux-hardware.org/?probe=8ab7c171c3) | Jan 31, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [aabd02c85c](https://linux-hardware.org/?probe=aabd02c85c) | Jan 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [c52cbab2e3](https://linux-hardware.org/?probe=c52cbab2e3) | Jan 30, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| HP            | 1998                        | Desktop     | [92ff4b3ecd](https://linux-hardware.org/?probe=92ff4b3ecd) | Jan 30, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4cfb847d84](https://linux-hardware.org/?probe=4cfb847d84) | Jan 29, 2024 |
| Dell          | Latitude 3300               | Notebook    | [9d76144e60](https://linux-hardware.org/?probe=9d76144e60) | Jan 29, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [14da91750f](https://linux-hardware.org/?probe=14da91750f) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [66d62ae7ed](https://linux-hardware.org/?probe=66d62ae7ed) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [9684aca764](https://linux-hardware.org/?probe=9684aca764) | Jan 29, 2024 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [9cfcec4d2d](https://linux-hardware.org/?probe=9cfcec4d2d) | Jan 29, 2024 |
| MSI           | MAG B560M MORTAR            | Desktop     | [709499c177](https://linux-hardware.org/?probe=709499c177) | Jan 28, 2024 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [0500733b2d](https://linux-hardware.org/?probe=0500733b2d) | Jan 28, 2024 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [ea399c19ca](https://linux-hardware.org/?probe=ea399c19ca) | Jan 28, 2024 |
| Dell          | Latitude 7530               | Notebook    | [ff36f2cfcc](https://linux-hardware.org/?probe=ff36f2cfcc) | Jan 28, 2024 |
| HP            | EliteBook 8470w             | Notebook    | [a92904a970](https://linux-hardware.org/?probe=a92904a970) | Jan 28, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | Desktop     | [fe3286f6e5](https://linux-hardware.org/?probe=fe3286f6e5) | Jan 28, 2024 |
| MSI           | A320M BAZOOKA               | Desktop     | [db3234d7aa](https://linux-hardware.org/?probe=db3234d7aa) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [aa19c735f2](https://linux-hardware.org/?probe=aa19c735f2) | Jan 28, 2024 |
| Acer          | Aspire A715-42G             | Notebook    | [6e3e887615](https://linux-hardware.org/?probe=6e3e887615) | Jan 27, 2024 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [e53ca59dec](https://linux-hardware.org/?probe=e53ca59dec) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [f2ed690a39](https://linux-hardware.org/?probe=f2ed690a39) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [4644130b45](https://linux-hardware.org/?probe=4644130b45) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f3243845d3](https://linux-hardware.org/?probe=f3243845d3) | Jan 27, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [41fc5cca96](https://linux-hardware.org/?probe=41fc5cca96) | Jan 27, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [08d3d9b75e](https://linux-hardware.org/?probe=08d3d9b75e) | Jan 26, 2024 |
| Dell          | Latitude 7530               | Notebook    | [e1cd3d26e8](https://linux-hardware.org/?probe=e1cd3d26e8) | Jan 26, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3524a7d564](https://linux-hardware.org/?probe=3524a7d564) | Jan 26, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [23faf0c03e](https://linux-hardware.org/?probe=23faf0c03e) | Jan 25, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [b6507e7469](https://linux-hardware.org/?probe=b6507e7469) | Jan 25, 2024 |
| Lenovo        | ThinkPad Twist 334729G      | Notebook    | [0a17051b66](https://linux-hardware.org/?probe=0a17051b66) | Jan 25, 2024 |
| Acer          | Aspire Z5600                | All in one  | [3735067105](https://linux-hardware.org/?probe=3735067105) | Jan 25, 2024 |
| Google        | Taeko                       | Notebook    | [e52e2ff787](https://linux-hardware.org/?probe=e52e2ff787) | Jan 25, 2024 |
| Medion        | S14409                      | Notebook    | [8e8339905a](https://linux-hardware.org/?probe=8e8339905a) | Jan 25, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [1c3a86b39c](https://linux-hardware.org/?probe=1c3a86b39c) | Jan 25, 2024 |
| MSI           | B560M PRO-VDH               | Desktop     | [e64338286f](https://linux-hardware.org/?probe=e64338286f) | Jan 24, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [0bc85e1b60](https://linux-hardware.org/?probe=0bc85e1b60) | Jan 24, 2024 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [94b425089f](https://linux-hardware.org/?probe=94b425089f) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [5a3dba74d6](https://linux-hardware.org/?probe=5a3dba74d6) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [a0e1db7908](https://linux-hardware.org/?probe=a0e1db7908) | Jan 24, 2024 |
| AZW           | MINI S 10                   | Desktop     | [d549e8a8a6](https://linux-hardware.org/?probe=d549e8a8a6) | Jan 24, 2024 |
| AZW           | MINI S 10                   | Desktop     | [b1a0a41e9e](https://linux-hardware.org/?probe=b1a0a41e9e) | Jan 24, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7c94952653](https://linux-hardware.org/?probe=7c94952653) | Jan 23, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [18a98466b2](https://linux-hardware.org/?probe=18a98466b2) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [f9da9c2d2e](https://linux-hardware.org/?probe=f9da9c2d2e) | Jan 23, 2024 |
| MSI           | MAG B560M MORTAR            | Desktop     | [2637ed4a7c](https://linux-hardware.org/?probe=2637ed4a7c) | Jan 23, 2024 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [af9215d3a5](https://linux-hardware.org/?probe=af9215d3a5) | Jan 23, 2024 |
| HP            | ProBook 4540s               | Notebook    | [84367073dd](https://linux-hardware.org/?probe=84367073dd) | Jan 22, 2024 |
| HP            | ProBook 4540s               | Notebook    | [f72cd2d1a0](https://linux-hardware.org/?probe=f72cd2d1a0) | Jan 22, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [b619b984b6](https://linux-hardware.org/?probe=b619b984b6) | Jan 22, 2024 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [e8d7aba4fe](https://linux-hardware.org/?probe=e8d7aba4fe) | Jan 22, 2024 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [1cfa83e1fc](https://linux-hardware.org/?probe=1cfa83e1fc) | Jan 22, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [31a4f6e57f](https://linux-hardware.org/?probe=31a4f6e57f) | Jan 22, 2024 |
| ASUSTek       | UX410UAK                    | Notebook    | [1155ca8c5c](https://linux-hardware.org/?probe=1155ca8c5c) | Jan 22, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [db7e0a0c8a](https://linux-hardware.org/?probe=db7e0a0c8a) | Jan 22, 2024 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [7eea5af3e6](https://linux-hardware.org/?probe=7eea5af3e6) | Jan 22, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e568089bad](https://linux-hardware.org/?probe=e568089bad) | Jan 21, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [428442a3ab](https://linux-hardware.org/?probe=428442a3ab) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a43bd4926](https://linux-hardware.org/?probe=6a43bd4926) | Jan 21, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [aaf1d1d0de](https://linux-hardware.org/?probe=aaf1d1d0de) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [71136f647b](https://linux-hardware.org/?probe=71136f647b) | Jan 20, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2d9680d782](https://linux-hardware.org/?probe=2d9680d782) | Jan 20, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ea63bb1d97](https://linux-hardware.org/?probe=ea63bb1d97) | Jan 20, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [36e3b9f35a](https://linux-hardware.org/?probe=36e3b9f35a) | Jan 19, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [494d0af2e5](https://linux-hardware.org/?probe=494d0af2e5) | Jan 19, 2024 |
| Dell          | Latitude 7330               | Notebook    | [d8b532bbee](https://linux-hardware.org/?probe=d8b532bbee) | Jan 19, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [bd52f86baa](https://linux-hardware.org/?probe=bd52f86baa) | Jan 18, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [5c18e1a4bc](https://linux-hardware.org/?probe=5c18e1a4bc) | Jan 18, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [c6bd12e53b](https://linux-hardware.org/?probe=c6bd12e53b) | Jan 18, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [7af8bc4215](https://linux-hardware.org/?probe=7af8bc4215) | Jan 18, 2024 |
| Great Wall    | MBX-Z60AR110 TBD            | Desktop     | [fdfa81d344](https://linux-hardware.org/?probe=fdfa81d344) | Jan 18, 2024 |
| Dell          | Latitude 5530               | Notebook    | [df5d5becd7](https://linux-hardware.org/?probe=df5d5becd7) | Jan 17, 2024 |
| Medion        | MS-7800                     | Desktop     | [8af71869fc](https://linux-hardware.org/?probe=8af71869fc) | Jan 17, 2024 |
| Medion        | H110H4-EM                   | Desktop     | [ea736cf314](https://linux-hardware.org/?probe=ea736cf314) | Jan 17, 2024 |
| MSI           | B560M PRO-VDH               | Desktop     | [cc460a0905](https://linux-hardware.org/?probe=cc460a0905) | Jan 16, 2024 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [0d81012aa0](https://linux-hardware.org/?probe=0d81012aa0) | Jan 16, 2024 |
| Dell          | Inspiron N311z              | Notebook    | [e4163cacc4](https://linux-hardware.org/?probe=e4163cacc4) | Jan 16, 2024 |
| Intel         | B75 V124                    | Desktop     | [4548b73c01](https://linux-hardware.org/?probe=4548b73c01) | Jan 16, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [c69281db28](https://linux-hardware.org/?probe=c69281db28) | Jan 15, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ca627d3c3e](https://linux-hardware.org/?probe=ca627d3c3e) | Jan 15, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [9ae250d8a6](https://linux-hardware.org/?probe=9ae250d8a6) | Jan 15, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [cdfc29ad66](https://linux-hardware.org/?probe=cdfc29ad66) | Jan 15, 2024 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [efb852e7fb](https://linux-hardware.org/?probe=efb852e7fb) | Jan 15, 2024 |
| MSI           | P67A-G43                    | Desktop     | [30b1edf89c](https://linux-hardware.org/?probe=30b1edf89c) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3aab9743d9](https://linux-hardware.org/?probe=3aab9743d9) | Jan 14, 2024 |
| Google        | Fleex                       | Notebook    | [46f5b6af86](https://linux-hardware.org/?probe=46f5b6af86) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [32021c35d3](https://linux-hardware.org/?probe=32021c35d3) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [0d2db2e184](https://linux-hardware.org/?probe=0d2db2e184) | Jan 14, 2024 |
| HP            | x2 210 G2                   | Tablet      | [e1baf3e443](https://linux-hardware.org/?probe=e1baf3e443) | Jan 14, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9c43a79143](https://linux-hardware.org/?probe=9c43a79143) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [bda32c8468](https://linux-hardware.org/?probe=bda32c8468) | Jan 14, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [37f2fc1ee2](https://linux-hardware.org/?probe=37f2fc1ee2) | Jan 14, 2024 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [2663e39ea0](https://linux-hardware.org/?probe=2663e39ea0) | Jan 14, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [35dd663593](https://linux-hardware.org/?probe=35dd663593) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [398927cd45](https://linux-hardware.org/?probe=398927cd45) | Jan 13, 2024 |
| Unknown       | AY07J                       | Desktop     | [1cb5749c2b](https://linux-hardware.org/?probe=1cb5749c2b) | Jan 13, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [04c5daf912](https://linux-hardware.org/?probe=04c5daf912) | Jan 13, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | Notebook    | [be204b17d2](https://linux-hardware.org/?probe=be204b17d2) | Jan 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [587226a745](https://linux-hardware.org/?probe=587226a745) | Jan 13, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [38ad1122d1](https://linux-hardware.org/?probe=38ad1122d1) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [25341b5586](https://linux-hardware.org/?probe=25341b5586) | Jan 13, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [80bd0982b9](https://linux-hardware.org/?probe=80bd0982b9) | Jan 13, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3c339a3645](https://linux-hardware.org/?probe=3c339a3645) | Jan 13, 2024 |
| Dell          | Precision 7720              | Notebook    | [adec0c91d9](https://linux-hardware.org/?probe=adec0c91d9) | Jan 13, 2024 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [700470a7f6](https://linux-hardware.org/?probe=700470a7f6) | Jan 12, 2024 |
| MSI           | H410M PRO                   | Desktop     | [76a24b5fa3](https://linux-hardware.org/?probe=76a24b5fa3) | Jan 12, 2024 |
| Lenovo        | ThinkPad E450 20DC003WUS    | Notebook    | [817c17d60e](https://linux-hardware.org/?probe=817c17d60e) | Jan 12, 2024 |
| HP            | ProBook 6450b               | Notebook    | [ddae4148a2](https://linux-hardware.org/?probe=ddae4148a2) | Jan 12, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a188d14c50](https://linux-hardware.org/?probe=a188d14c50) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f1814dff2e](https://linux-hardware.org/?probe=f1814dff2e) | Jan 11, 2024 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [e8b3f439b3](https://linux-hardware.org/?probe=e8b3f439b3) | Jan 10, 2024 |
| HP            | 8767 A                      | Desktop     | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| ASUSTek       | H81T R2.0                   | Desktop     | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [7101d9332b](https://linux-hardware.org/?probe=7101d9332b) | Jan 10, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [0cd91acdff](https://linux-hardware.org/?probe=0cd91acdff) | Jan 10, 2024 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [a089502ce1](https://linux-hardware.org/?probe=a089502ce1) | Jan 10, 2024 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [7caaae153c](https://linux-hardware.org/?probe=7caaae153c) | Jan 09, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [a3c73eb2fd](https://linux-hardware.org/?probe=a3c73eb2fd) | Jan 09, 2024 |
| Sony          | VGN-CS190N                  | Notebook    | [2ac26516a6](https://linux-hardware.org/?probe=2ac26516a6) | Jan 09, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Micro Comp... | Venus series                | Notebook    | [7680fc8cfc](https://linux-hardware.org/?probe=7680fc8cfc) | Jan 09, 2024 |
| Micro Comp... | Venus series                | Notebook    | [4413b07a3b](https://linux-hardware.org/?probe=4413b07a3b) | Jan 09, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [8a0e17b484](https://linux-hardware.org/?probe=8a0e17b484) | Jan 09, 2024 |
| Unknown       | V00                         | Mini pc     | [9f59e7926f](https://linux-hardware.org/?probe=9f59e7926f) | Jan 09, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [a092034ebf](https://linux-hardware.org/?probe=a092034ebf) | Jan 09, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7194fe43ed](https://linux-hardware.org/?probe=7194fe43ed) | Jan 09, 2024 |
| Biostar       | B550MX/E PRO                | Desktop     | [8c12a7197e](https://linux-hardware.org/?probe=8c12a7197e) | Jan 08, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [565c995910](https://linux-hardware.org/?probe=565c995910) | Jan 08, 2024 |
| Dell          | 0F96C8 A00                  | All in one  | [f7d20028f6](https://linux-hardware.org/?probe=f7d20028f6) | Jan 08, 2024 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [f43717fa8e](https://linux-hardware.org/?probe=f43717fa8e) | Jan 08, 2024 |
| MSI           | Creator Z17 A12UGST         | Notebook    | [b9357d76fc](https://linux-hardware.org/?probe=b9357d76fc) | Jan 08, 2024 |
| Dell          | Latitude E7450              | Notebook    | [a60667c993](https://linux-hardware.org/?probe=a60667c993) | Jan 08, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | Desktop     | [e19857a2a6](https://linux-hardware.org/?probe=e19857a2a6) | Jan 08, 2024 |
| MSI           | Creator Z17 A12UGST         | Notebook    | [6027d9f940](https://linux-hardware.org/?probe=6027d9f940) | Jan 08, 2024 |
| Apple         | MacBookAir9,1               | Notebook    | [6af0a29be6](https://linux-hardware.org/?probe=6af0a29be6) | Jan 07, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ee9fb5898f](https://linux-hardware.org/?probe=ee9fb5898f) | Jan 07, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [fccab2dc4a](https://linux-hardware.org/?probe=fccab2dc4a) | Jan 07, 2024 |
| Intel         | VALLEYVIEW C0 PLATFORM      | Tablet      | [c3d56fa36c](https://linux-hardware.org/?probe=c3d56fa36c) | Jan 07, 2024 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [e23adc98db](https://linux-hardware.org/?probe=e23adc98db) | Jan 06, 2024 |
| HP            | 3397                        | Desktop     | [0ba7322ded](https://linux-hardware.org/?probe=0ba7322ded) | Jan 05, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [5feecec8b2](https://linux-hardware.org/?probe=5feecec8b2) | Jan 05, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [c58bf7eae4](https://linux-hardware.org/?probe=c58bf7eae4) | Jan 05, 2024 |
| HP            | ZBook 14u G5                | Notebook    | [33c5c3bf2c](https://linux-hardware.org/?probe=33c5c3bf2c) | Jan 05, 2024 |
| HP            | ZBook 14u G5                | Notebook    | [7774c1745d](https://linux-hardware.org/?probe=7774c1745d) | Jan 05, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [431379ef73](https://linux-hardware.org/?probe=431379ef73) | Jan 05, 2024 |
| Biostar       | B365MHC                     | Desktop     | [0936a451ce](https://linux-hardware.org/?probe=0936a451ce) | Jan 04, 2024 |
| HP            | ENVY m6                     | Notebook    | [d63a06fb89](https://linux-hardware.org/?probe=d63a06fb89) | Jan 04, 2024 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [5ca009faf3](https://linux-hardware.org/?probe=5ca009faf3) | Jan 04, 2024 |
| Dell          | Latitude E6420              | Notebook    | [c9538d7328](https://linux-hardware.org/?probe=c9538d7328) | Jan 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cf1f935e69](https://linux-hardware.org/?probe=cf1f935e69) | Jan 03, 2024 |
| Dell          | Latitude E6420              | Notebook    | [45dcfa5d2c](https://linux-hardware.org/?probe=45dcfa5d2c) | Jan 03, 2024 |
| Dell          | Latitude 7490               | Notebook    | [80751dfc22](https://linux-hardware.org/?probe=80751dfc22) | Jan 03, 2024 |
| Dell          | Latitude 7490               | Notebook    | [0765d95d82](https://linux-hardware.org/?probe=0765d95d82) | Jan 03, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [69f291e4be](https://linux-hardware.org/?probe=69f291e4be) | Jan 03, 2024 |
| Dell          | Inspiron 5502               | Notebook    | [3486d53d60](https://linux-hardware.org/?probe=3486d53d60) | Jan 03, 2024 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [83106ca0a8](https://linux-hardware.org/?probe=83106ca0a8) | Jan 03, 2024 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [c1d7df8730](https://linux-hardware.org/?probe=c1d7df8730) | Jan 02, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4c7efd21fe](https://linux-hardware.org/?probe=4c7efd21fe) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [a948fd2006](https://linux-hardware.org/?probe=a948fd2006) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [a435ff1bd6](https://linux-hardware.org/?probe=a435ff1bd6) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [4db4a265b6](https://linux-hardware.org/?probe=4db4a265b6) | Jan 02, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [acc47dae75](https://linux-hardware.org/?probe=acc47dae75) | Jan 02, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [2ca86aaf30](https://linux-hardware.org/?probe=2ca86aaf30) | Jan 02, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fb59929b28](https://linux-hardware.org/?probe=fb59929b28) | Jan 02, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3de5d6e06c](https://linux-hardware.org/?probe=3de5d6e06c) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [21c267752a](https://linux-hardware.org/?probe=21c267752a) | Jan 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [435dc251c1](https://linux-hardware.org/?probe=435dc251c1) | Jan 02, 2024 |
| System76      | Pangolin                    | Notebook    | [58876a3573](https://linux-hardware.org/?probe=58876a3573) | Jan 01, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [750a1d90dd](https://linux-hardware.org/?probe=750a1d90dd) | Jan 01, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [b4f1a69ca3](https://linux-hardware.org/?probe=b4f1a69ca3) | Jan 01, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [b5efb44fe4](https://linux-hardware.org/?probe=b5efb44fe4) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [e8e24c9091](https://linux-hardware.org/?probe=e8e24c9091) | Jan 01, 2024 |
| MSI           | 2AE0                        | Desktop     | [00b5d15112](https://linux-hardware.org/?probe=00b5d15112) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c6a3df522b](https://linux-hardware.org/?probe=c6a3df522b) | Dec 31, 2023 |
| ASRock        | Z170A-X1                    | Desktop     | [faba481c2b](https://linux-hardware.org/?probe=faba481c2b) | Dec 31, 2023 |
| HP            | 8704                        | Desktop     | [49843bcacc](https://linux-hardware.org/?probe=49843bcacc) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [c8488906f2](https://linux-hardware.org/?probe=c8488906f2) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [ed56d2dcb5](https://linux-hardware.org/?probe=ed56d2dcb5) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [71c755966f](https://linux-hardware.org/?probe=71c755966f) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b13ec8c4fe](https://linux-hardware.org/?probe=b13ec8c4fe) | Dec 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d0b71859f2](https://linux-hardware.org/?probe=d0b71859f2) | Dec 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Notebook    | [42b25d8ac5](https://linux-hardware.org/?probe=42b25d8ac5) | Dec 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bf4f14e416](https://linux-hardware.org/?probe=bf4f14e416) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6SE6900    | Notebook    | [f9e5fe1156](https://linux-hardware.org/?probe=f9e5fe1156) | Dec 29, 2023 |
| Lenovo        | ThinkPad T450 20BUS05V00    | Notebook    | [3334aeb4e1](https://linux-hardware.org/?probe=3334aeb4e1) | Dec 29, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [4f74bf57df](https://linux-hardware.org/?probe=4f74bf57df) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [59ae3d3d52](https://linux-hardware.org/?probe=59ae3d3d52) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c68ea76b65](https://linux-hardware.org/?probe=c68ea76b65) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [48d04b219b](https://linux-hardware.org/?probe=48d04b219b) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | Notebook    | [3110584890](https://linux-hardware.org/?probe=3110584890) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | Notebook    | [3a9461e870](https://linux-hardware.org/?probe=3a9461e870) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [1042d42263](https://linux-hardware.org/?probe=1042d42263) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [d68aa800c6](https://linux-hardware.org/?probe=d68aa800c6) | Dec 28, 2023 |
| Packard Be... | MCP73T-AD                   | Desktop     | [c7d9006760](https://linux-hardware.org/?probe=c7d9006760) | Dec 27, 2023 |
| HP            | 339A                        | Desktop     | [49cb574539](https://linux-hardware.org/?probe=49cb574539) | Dec 27, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [6a0970bd24](https://linux-hardware.org/?probe=6a0970bd24) | Dec 27, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [10fa4fd32b](https://linux-hardware.org/?probe=10fa4fd32b) | Dec 27, 2023 |
| Dell          | Vostro 3446                 | Notebook    | [ed9d04a3d2](https://linux-hardware.org/?probe=ed9d04a3d2) | Dec 27, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [2d0962bbfa](https://linux-hardware.org/?probe=2d0962bbfa) | Dec 27, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [b1b00dd0b5](https://linux-hardware.org/?probe=b1b00dd0b5) | Dec 27, 2023 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [7979b3518c](https://linux-hardware.org/?probe=7979b3518c) | Dec 27, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| Lenovo        | ThinkPad T520 4243ED3       | Notebook    | [6fd4832f12](https://linux-hardware.org/?probe=6fd4832f12) | Dec 26, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [5902199f52](https://linux-hardware.org/?probe=5902199f52) | Dec 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0714d5920a](https://linux-hardware.org/?probe=0714d5920a) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [cf1f0e7284](https://linux-hardware.org/?probe=cf1f0e7284) | Dec 26, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6f41d95dc](https://linux-hardware.org/?probe=f6f41d95dc) | Dec 25, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [46a795ef16](https://linux-hardware.org/?probe=46a795ef16) | Dec 25, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [5972225791](https://linux-hardware.org/?probe=5972225791) | Dec 25, 2023 |
| PC Special... | 14 Fusion Pro               | Notebook    | [76bf311c34](https://linux-hardware.org/?probe=76bf311c34) | Dec 25, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [988e9fc65c](https://linux-hardware.org/?probe=988e9fc65c) | Dec 25, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [8b6cbdd646](https://linux-hardware.org/?probe=8b6cbdd646) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [74c274a303](https://linux-hardware.org/?probe=74c274a303) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [123aa39382](https://linux-hardware.org/?probe=123aa39382) | Dec 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1297c97e04](https://linux-hardware.org/?probe=1297c97e04) | Dec 24, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9549fcd83e](https://linux-hardware.org/?probe=9549fcd83e) | Dec 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [6d8c495e90](https://linux-hardware.org/?probe=6d8c495e90) | Dec 23, 2023 |
| HP            | 340S G7 Notebook PC         | Notebook    | [097603b65a](https://linux-hardware.org/?probe=097603b65a) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | Notebook    | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| Dell          | Latitude 7280               | Notebook    | [5397e7633e](https://linux-hardware.org/?probe=5397e7633e) | Dec 22, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| Eluktronic... | MECH-17                     | Notebook    | [0a69b2e084](https://linux-hardware.org/?probe=0a69b2e084) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [cdcc0b8368](https://linux-hardware.org/?probe=cdcc0b8368) | Dec 22, 2023 |
| Dell          | Precision 5480              | Notebook    | [382626cfb5](https://linux-hardware.org/?probe=382626cfb5) | Dec 21, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [81855c7ee8](https://linux-hardware.org/?probe=81855c7ee8) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [98eee633b1](https://linux-hardware.org/?probe=98eee633b1) | Dec 20, 2023 |
| Micro Comp... | Venus series                | Notebook    | [e01ac2dc02](https://linux-hardware.org/?probe=e01ac2dc02) | Dec 20, 2023 |
| Google        | Cave                        | Notebook    | [ec9d49335f](https://linux-hardware.org/?probe=ec9d49335f) | Dec 20, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [c41952876f](https://linux-hardware.org/?probe=c41952876f) | Dec 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [449c36ff1c](https://linux-hardware.org/?probe=449c36ff1c) | Dec 19, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [031f8b45bd](https://linux-hardware.org/?probe=031f8b45bd) | Dec 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWA16R0... | Notebook    | [4f1e1945a7](https://linux-hardware.org/?probe=4f1e1945a7) | Dec 19, 2023 |
| MSI           | H97M-P35                    | Desktop     | [759943cd15](https://linux-hardware.org/?probe=759943cd15) | Dec 19, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [0fe8df6dfe](https://linux-hardware.org/?probe=0fe8df6dfe) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| HP            | 81B3                        | Desktop     | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| HP            | 828A                        | Desktop     | [94483ed23a](https://linux-hardware.org/?probe=94483ed23a) | Dec 19, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d8f95bfd45](https://linux-hardware.org/?probe=d8f95bfd45) | Dec 18, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [f9a70833ee](https://linux-hardware.org/?probe=f9a70833ee) | Dec 18, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d56dcc35b9](https://linux-hardware.org/?probe=d56dcc35b9) | Dec 18, 2023 |
| Gateway       | NV54 Series                 | Notebook    | [1bd87c77d2](https://linux-hardware.org/?probe=1bd87c77d2) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [16550580d3](https://linux-hardware.org/?probe=16550580d3) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [50ef2b12e3](https://linux-hardware.org/?probe=50ef2b12e3) | Dec 17, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [8f970e8d4c](https://linux-hardware.org/?probe=8f970e8d4c) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [c88b531754](https://linux-hardware.org/?probe=c88b531754) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [e3d9d4d8a7](https://linux-hardware.org/?probe=e3d9d4d8a7) | Dec 17, 2023 |
| HP            | Notebook                    | Notebook    | [88e0b592ea](https://linux-hardware.org/?probe=88e0b592ea) | Dec 17, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [fe9179b1fb](https://linux-hardware.org/?probe=fe9179b1fb) | Dec 16, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [32af19e996](https://linux-hardware.org/?probe=32af19e996) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f1f6a55f9c](https://linux-hardware.org/?probe=f1f6a55f9c) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [8b6e7627f9](https://linux-hardware.org/?probe=8b6e7627f9) | Dec 16, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [15c3d23fc9](https://linux-hardware.org/?probe=15c3d23fc9) | Dec 15, 2023 |
| HP            | G62                         | Notebook    | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [ce943a3a49](https://linux-hardware.org/?probe=ce943a3a49) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [a7be5e66cd](https://linux-hardware.org/?probe=a7be5e66cd) | Dec 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [cf35bfbdf4](https://linux-hardware.org/?probe=cf35bfbdf4) | Dec 14, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [0b19e954c5](https://linux-hardware.org/?probe=0b19e954c5) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57cc6cbccf](https://linux-hardware.org/?probe=57cc6cbccf) | Dec 14, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [27c22f0c94](https://linux-hardware.org/?probe=27c22f0c94) | Dec 14, 2023 |
| HP            | 2AA7 H                      | Desktop     | [5e9703dff5](https://linux-hardware.org/?probe=5e9703dff5) | Dec 13, 2023 |
| Unknown       | AM02                        | Mini pc     | [6bd02968e3](https://linux-hardware.org/?probe=6bd02968e3) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c5d4eabc9b](https://linux-hardware.org/?probe=c5d4eabc9b) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [87fa57a3af](https://linux-hardware.org/?probe=87fa57a3af) | Dec 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [39a6569b14](https://linux-hardware.org/?probe=39a6569b14) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [4fd70c36f8](https://linux-hardware.org/?probe=4fd70c36f8) | Dec 12, 2023 |
| Acer          | Predator G3-572             | Notebook    | [7de00d4eab](https://linux-hardware.org/?probe=7de00d4eab) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cea97f4e49](https://linux-hardware.org/?probe=cea97f4e49) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [6e5abc0ea5](https://linux-hardware.org/?probe=6e5abc0ea5) | Dec 10, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [b85850b4c2](https://linux-hardware.org/?probe=b85850b4c2) | Dec 10, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [3a6b7f5ae4](https://linux-hardware.org/?probe=3a6b7f5ae4) | Dec 09, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [215b8bc94a](https://linux-hardware.org/?probe=215b8bc94a) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a0919a7fc](https://linux-hardware.org/?probe=7a0919a7fc) | Dec 09, 2023 |
| Lenovo        | ThinkPad X220 4290B19       | Notebook    | [1515bfc49e](https://linux-hardware.org/?probe=1515bfc49e) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | Notebook    | [f463c790b4](https://linux-hardware.org/?probe=f463c790b4) | Dec 08, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0fb56c3b77](https://linux-hardware.org/?probe=0fb56c3b77) | Dec 08, 2023 |
| HP            | 843B                        | Desktop     | [27527dbb19](https://linux-hardware.org/?probe=27527dbb19) | Dec 07, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [21847052d3](https://linux-hardware.org/?probe=21847052d3) | Dec 07, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7317dc8b5c](https://linux-hardware.org/?probe=7317dc8b5c) | Dec 06, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [65530f33de](https://linux-hardware.org/?probe=65530f33de) | Dec 06, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1f68b6b7c7](https://linux-hardware.org/?probe=1f68b6b7c7) | Dec 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [1bf269cb9e](https://linux-hardware.org/?probe=1bf269cb9e) | Dec 05, 2023 |
| eMachines     | eME732G                     | Notebook    | [d94dd62bf1](https://linux-hardware.org/?probe=d94dd62bf1) | Dec 05, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [0d7f21475d](https://linux-hardware.org/?probe=0d7f21475d) | Dec 05, 2023 |
| Micro Comp... | Venus series                | Notebook    | [fab7ae9a17](https://linux-hardware.org/?probe=fab7ae9a17) | Dec 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6e58d5148](https://linux-hardware.org/?probe=e6e58d5148) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [31b3b0fd94](https://linux-hardware.org/?probe=31b3b0fd94) | Dec 05, 2023 |
| Samsung       | 730QED                      | Convertible | [e7b8057036](https://linux-hardware.org/?probe=e7b8057036) | Dec 04, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| eMachines     | eME732G                     | Notebook    | [931569e396](https://linux-hardware.org/?probe=931569e396) | Dec 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [7a78497797](https://linux-hardware.org/?probe=7a78497797) | Dec 03, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [d12c9b1f20](https://linux-hardware.org/?probe=d12c9b1f20) | Dec 03, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [166b024a63](https://linux-hardware.org/?probe=166b024a63) | Dec 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [427b578e83](https://linux-hardware.org/?probe=427b578e83) | Dec 02, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [d923b4bdf8](https://linux-hardware.org/?probe=d923b4bdf8) | Dec 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f9629d4399](https://linux-hardware.org/?probe=f9629d4399) | Dec 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [26d7ac2396](https://linux-hardware.org/?probe=26d7ac2396) | Dec 02, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9516f4d644](https://linux-hardware.org/?probe=9516f4d644) | Dec 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [abb3c226ed](https://linux-hardware.org/?probe=abb3c226ed) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [2fcc002511](https://linux-hardware.org/?probe=2fcc002511) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [0b156341f6](https://linux-hardware.org/?probe=0b156341f6) | Dec 01, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [997c41ef61](https://linux-hardware.org/?probe=997c41ef61) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [cafac3babc](https://linux-hardware.org/?probe=cafac3babc) | Dec 01, 2023 |
| Blue Bird     | Bluebird PC                 | Tablet      | [efcf788f14](https://linux-hardware.org/?probe=efcf788f14) | Nov 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [86519a17c4](https://linux-hardware.org/?probe=86519a17c4) | Nov 30, 2023 |
| AZW           | LZX TBD                     | Desktop     | [11f35f4369](https://linux-hardware.org/?probe=11f35f4369) | Nov 30, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [6fe23dd80e](https://linux-hardware.org/?probe=6fe23dd80e) | Nov 28, 2023 |
| HP            | 355 G2                      | Notebook    | [bb79df3643](https://linux-hardware.org/?probe=bb79df3643) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a35b8ef607](https://linux-hardware.org/?probe=a35b8ef607) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [fc19161855](https://linux-hardware.org/?probe=fc19161855) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| Micro Comp... | Venus series                | Notebook    | [fd9dbf149e](https://linux-hardware.org/?probe=fd9dbf149e) | Nov 27, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4b4737d484](https://linux-hardware.org/?probe=4b4737d484) | Nov 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [16761c9d57](https://linux-hardware.org/?probe=16761c9d57) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [12a76ad0cd](https://linux-hardware.org/?probe=12a76ad0cd) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1878fa087a](https://linux-hardware.org/?probe=1878fa087a) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| DERE          | Unknown                     | Tablet      | [0b81551c86](https://linux-hardware.org/?probe=0b81551c86) | Nov 24, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [106d0f0bff](https://linux-hardware.org/?probe=106d0f0bff) | Nov 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [16e9af1d1a](https://linux-hardware.org/?probe=16e9af1d1a) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [c60e251b40](https://linux-hardware.org/?probe=c60e251b40) | Nov 23, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [7b466d7f56](https://linux-hardware.org/?probe=7b466d7f56) | Nov 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [8c6fd80245](https://linux-hardware.org/?probe=8c6fd80245) | Nov 22, 2023 |
| Lenovo        | ThinkCentre M91p 4518A31    | Desktop     | [9031421465](https://linux-hardware.org/?probe=9031421465) | Nov 22, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [30d6da52fa](https://linux-hardware.org/?probe=30d6da52fa) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [47105264f8](https://linux-hardware.org/?probe=47105264f8) | Nov 22, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [cd86a8c45b](https://linux-hardware.org/?probe=cd86a8c45b) | Nov 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| HP            | 2AA7 H                      | Desktop     | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [44dab561a1](https://linux-hardware.org/?probe=44dab561a1) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [e696c3dd13](https://linux-hardware.org/?probe=e696c3dd13) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07e18044ae](https://linux-hardware.org/?probe=07e18044ae) | Nov 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a6763208d](https://linux-hardware.org/?probe=7a6763208d) | Nov 21, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6066ce2199](https://linux-hardware.org/?probe=6066ce2199) | Nov 20, 2023 |
| PC Special... | Lafite Pro II 15            | Notebook    | [b7b85ab8ce](https://linux-hardware.org/?probe=b7b85ab8ce) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [6175f06df9](https://linux-hardware.org/?probe=6175f06df9) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4c78fb767](https://linux-hardware.org/?probe=f4c78fb767) | Nov 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [2f5e048964](https://linux-hardware.org/?probe=2f5e048964) | Nov 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [1aed7bfcb8](https://linux-hardware.org/?probe=1aed7bfcb8) | Nov 19, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [0de89fd40b](https://linux-hardware.org/?probe=0de89fd40b) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [8c24f72ac9](https://linux-hardware.org/?probe=8c24f72ac9) | Nov 19, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8049743efd](https://linux-hardware.org/?probe=8049743efd) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [883da32584](https://linux-hardware.org/?probe=883da32584) | Nov 18, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c845b4f25f](https://linux-hardware.org/?probe=c845b4f25f) | Nov 18, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8b7c376d](https://linux-hardware.org/?probe=4a8b7c376d) | Nov 18, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [43e84fe856](https://linux-hardware.org/?probe=43e84fe856) | Nov 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0c9b59ab03](https://linux-hardware.org/?probe=0c9b59ab03) | Nov 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [391e71ffae](https://linux-hardware.org/?probe=391e71ffae) | Nov 17, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [69d85e6c31](https://linux-hardware.org/?probe=69d85e6c31) | Nov 16, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [dc260fc224](https://linux-hardware.org/?probe=dc260fc224) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [adab9bb3b4](https://linux-hardware.org/?probe=adab9bb3b4) | Nov 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2902bc3e9f](https://linux-hardware.org/?probe=2902bc3e9f) | Nov 15, 2023 |
| Dell          | Latitude 5521               | Notebook    | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1f783e1865](https://linux-hardware.org/?probe=1f783e1865) | Nov 14, 2023 |
| Dell          | Latitude E7450              | Notebook    | [500f23ef78](https://linux-hardware.org/?probe=500f23ef78) | Nov 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [edf0d74b51](https://linux-hardware.org/?probe=edf0d74b51) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [585ce3241c](https://linux-hardware.org/?probe=585ce3241c) | Nov 13, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0874caf8a9](https://linux-hardware.org/?probe=0874caf8a9) | Nov 13, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [8fd2ed0ba7](https://linux-hardware.org/?probe=8fd2ed0ba7) | Nov 13, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [2166a882d2](https://linux-hardware.org/?probe=2166a882d2) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d1d512f69](https://linux-hardware.org/?probe=6d1d512f69) | Nov 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| Jumper        | EZbook                      | Notebook    | [682c154cdb](https://linux-hardware.org/?probe=682c154cdb) | Nov 12, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [5ef7be7906](https://linux-hardware.org/?probe=5ef7be7906) | Nov 12, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [0afc087be6](https://linux-hardware.org/?probe=0afc087be6) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [8762b09fbd](https://linux-hardware.org/?probe=8762b09fbd) | Nov 12, 2023 |
| ASUSTek       | Q524UQ                      | Notebook    | [0fe339b29a](https://linux-hardware.org/?probe=0fe339b29a) | Nov 11, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [951f01b614](https://linux-hardware.org/?probe=951f01b614) | Nov 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [9d1efed149](https://linux-hardware.org/?probe=9d1efed149) | Nov 11, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [d9a8e46b60](https://linux-hardware.org/?probe=d9a8e46b60) | Nov 11, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [f34d67b79a](https://linux-hardware.org/?probe=f34d67b79a) | Nov 11, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [9fde81d361](https://linux-hardware.org/?probe=9fde81d361) | Nov 10, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [3442cd2670](https://linux-hardware.org/?probe=3442cd2670) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [d91c0b4b6f](https://linux-hardware.org/?probe=d91c0b4b6f) | Nov 10, 2023 |
| Lenovo        | ThinkPad T480s 20L7001MH... | Notebook    | [f5c3846dce](https://linux-hardware.org/?probe=f5c3846dce) | Nov 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [0ec19aab02](https://linux-hardware.org/?probe=0ec19aab02) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3f1d1d36ef](https://linux-hardware.org/?probe=3f1d1d36ef) | Nov 10, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [8775266ad7](https://linux-hardware.org/?probe=8775266ad7) | Nov 10, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [85e2b37a15](https://linux-hardware.org/?probe=85e2b37a15) | Nov 10, 2023 |
| HP            | 86F3 00100                  | All in one  | [5ac5555396](https://linux-hardware.org/?probe=5ac5555396) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecb49b0454](https://linux-hardware.org/?probe=ecb49b0454) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5b67ed0642](https://linux-hardware.org/?probe=5b67ed0642) | Nov 09, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [faf465319b](https://linux-hardware.org/?probe=faf465319b) | Nov 09, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [76926e3f2c](https://linux-hardware.org/?probe=76926e3f2c) | Nov 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [f5a16ecf27](https://linux-hardware.org/?probe=f5a16ecf27) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [a26aceca7f](https://linux-hardware.org/?probe=a26aceca7f) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [ab1a7393ef](https://linux-hardware.org/?probe=ab1a7393ef) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [6badd92c4f](https://linux-hardware.org/?probe=6badd92c4f) | Nov 08, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [dbfe362cd8](https://linux-hardware.org/?probe=dbfe362cd8) | Nov 08, 2023 |
| MSI           | MAG B660M MORTAR            | Desktop     | [a8c3434f4e](https://linux-hardware.org/?probe=a8c3434f4e) | Nov 07, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [34c0a2ec4c](https://linux-hardware.org/?probe=34c0a2ec4c) | Nov 07, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a599d9b486](https://linux-hardware.org/?probe=a599d9b486) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8ef23bbac8](https://linux-hardware.org/?probe=8ef23bbac8) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [003be2f197](https://linux-hardware.org/?probe=003be2f197) | Nov 07, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [9b3ffcb3d5](https://linux-hardware.org/?probe=9b3ffcb3d5) | Nov 07, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [fecc1b7dff](https://linux-hardware.org/?probe=fecc1b7dff) | Nov 07, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [530b650093](https://linux-hardware.org/?probe=530b650093) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [01884ea8de](https://linux-hardware.org/?probe=01884ea8de) | Nov 07, 2023 |
| Dell          | Precision 3561              | Notebook    | [8fd1f7d515](https://linux-hardware.org/?probe=8fd1f7d515) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6f9ee3fea0](https://linux-hardware.org/?probe=6f9ee3fea0) | Nov 06, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [f72df0be76](https://linux-hardware.org/?probe=f72df0be76) | Nov 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [fef5a2e8ae](https://linux-hardware.org/?probe=fef5a2e8ae) | Nov 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1427      | 27.59%  |
| Kubuntu 22.04   | 1421      | 27.47%  |
| Kubuntu 23.10   | 378       | 7.31%   |
| Kubuntu 23.04   | 317       | 6.13%   |
| Kubuntu 22.10   | 298       | 5.76%   |
| Kubuntu 20.10   | 258       | 4.99%   |
| Kubuntu 21.10   | 243       | 4.7%    |
| Kubuntu 21.04   | 214       | 4.14%   |
| Kubuntu 18.04   | 208       | 4.02%   |
| Kubuntu 19.10   | 178       | 3.44%   |
| Kubuntu 11      | 97        | 1.88%   |
| Kubuntu 24.04   | 41        | 0.79%   |
| Kubuntu 11.1    | 26        | 0.5%    |
| Kubuntu 19.04   | 22        | 0.43%   |
| Kubuntu 16.04   | 13        | 0.25%   |
| Kubuntu         | 8         | 0.15%   |
| Kubuntu 18.10   | 7         | 0.14%   |
| Kubuntu 2.0     | 6         | 0.12%   |
| Kubuntu 17.10   | 3         | 0.06%   |
| Kubuntu 14.04   | 3         | 0.06%   |
| Kubuntu 17.04   | 2         | 0.04%   |
| Kubuntu 20.08.3 | 1         | 0.02%   |
| Kubuntu 2.1     | 1         | 0.02%   |
| Kubuntu 12.04   | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 4911      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 1.8%    |
| 6.5.0-14-generic  | 93        | 1.63%   |
| 5.15.0-52-generic | 84        | 1.47%   |
| 6.2.0-20-generic  | 81        | 1.42%   |
| 5.15.0-56-generic | 80        | 1.4%    |
| 5.19.0-35-generic | 70        | 1.23%   |
| 5.4.0-52-generic  | 68        | 1.19%   |
| 6.2.0-26-generic  | 62        | 1.09%   |
| 5.4.0-58-generic  | 59        | 1.03%   |
| 5.4.0-48-generic  | 59        | 1.03%   |
| 5.15.0-48-generic | 58        | 1.02%   |
| 5.15.0-46-generic | 53        | 0.93%   |
| 5.13.0-39-generic | 53        | 0.93%   |
| 5.19.0-23-generic | 52        | 0.91%   |
| 6.5.0-10-generic  | 48        | 0.84%   |
| 6.5.0-26-generic  | 47        | 0.82%   |
| 6.2.0-34-generic  | 47        | 0.82%   |
| 5.4.0-40-generic  | 47        | 0.82%   |
| 5.19.0-38-generic | 47        | 0.82%   |
| 6.5.0-15-generic  | 45        | 0.79%   |
| 5.15.0-43-generic | 44        | 0.77%   |
| 5.13.0-28-generic | 44        | 0.77%   |
| 5.19.0-31-generic | 43        | 0.75%   |
| 6.5.0-28-generic  | 42        | 0.74%   |
| 5.19.0-26-generic | 42        | 0.74%   |
| 5.15.0-58-generic | 42        | 0.74%   |
| 5.15.0-91-generic | 41        | 0.72%   |
| 5.15.0-47-generic | 40        | 0.7%    |
| 6.5.0-9-generic   | 39        | 0.68%   |
| 5.15.0-41-generic | 39        | 0.68%   |
| 5.11.0-37-generic | 39        | 0.68%   |
| 5.15.0-53-generic | 37        | 0.65%   |
| 5.13.0-30-generic | 37        | 0.65%   |
| 5.11.0-25-generic | 37        | 0.65%   |
| 6.5.0-17-generic  | 36        | 0.63%   |
| 5.4.0-47-generic  | 36        | 0.63%   |
| 6.5.0-21-generic  | 34        | 0.6%    |
| 6.2.0-39-generic  | 34        | 0.6%    |
| 6.2.0-33-generic  | 34        | 0.6%    |
| 6.2.0-32-generic  | 34        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 998       | 18.89%  |
| 5.4.0   | 954       | 18.05%  |
| 6.5.0   | 497       | 9.41%   |
| 6.2.0   | 464       | 8.78%   |
| 5.19.0  | 450       | 8.52%   |
| 5.13.0  | 410       | 7.76%   |
| 5.8.0   | 409       | 7.74%   |
| 5.11.0  | 325       | 6.15%   |
| 5.3.0   | 224       | 4.24%   |
| 4.15.0  | 72        | 1.36%   |
| 5.0.0   | 36        | 0.68%   |
| 6.8.0   | 30        | 0.57%   |
| 5.17.0  | 21        | 0.4%    |
| 5.10.0  | 18        | 0.34%   |
| 5.6.0   | 15        | 0.28%   |
| 6.6.0   | 10        | 0.19%   |
| 6.1.0   | 10        | 0.19%   |
| 4.4.0   | 10        | 0.19%   |
| 6.0.0   | 9         | 0.17%   |
| 5.14.0  | 9         | 0.17%   |
| 4.18.0  | 8         | 0.15%   |
| 6.0.9   | 6         | 0.11%   |
| 6.3.0   | 5         | 0.09%   |
| 5.9.0   | 5         | 0.09%   |
| 6.4.8   | 4         | 0.08%   |
| 6.4.0   | 4         | 0.08%   |
| 6.3.8   | 4         | 0.08%   |
| 5.7.0   | 4         | 0.08%   |
| 6.8.1   | 3         | 0.06%   |
| 6.7.4   | 3         | 0.06%   |
| 6.7.0   | 3         | 0.06%   |
| 6.6.1   | 3         | 0.06%   |
| 6.4.10  | 3         | 0.06%   |
| 6.3.6   | 3         | 0.06%   |
| 6.3.1   | 3         | 0.06%   |
| 6.1.5   | 3         | 0.06%   |
| 5.8.18  | 3         | 0.06%   |
| 5.18.4  | 3         | 0.06%   |
| 5.18.10 | 3         | 0.06%   |
| 5.16.0  | 3         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1014      | 19.22%  |
| 5.4     | 961       | 18.22%  |
| 6.5     | 504       | 9.55%   |
| 6.2     | 475       | 9%      |
| 5.19    | 457       | 8.66%   |
| 5.8     | 425       | 8.06%   |
| 5.13    | 421       | 7.98%   |
| 5.11    | 331       | 6.27%   |
| 5.3     | 227       | 4.3%    |
| 4.15    | 73        | 1.38%   |
| 5.0     | 37        | 0.7%    |
| 6.8     | 34        | 0.64%   |
| 5.10    | 31        | 0.59%   |
| 6.1     | 30        | 0.57%   |
| 5.17    | 28        | 0.53%   |
| 6.3     | 23        | 0.44%   |
| 6.6     | 21        | 0.4%    |
| 6.0     | 21        | 0.4%    |
| 5.6     | 20        | 0.38%   |
| 5.14    | 18        | 0.34%   |
| 6.4     | 16        | 0.3%    |
| 5.9     | 13        | 0.25%   |
| 5.12    | 13        | 0.25%   |
| 6.7     | 12        | 0.23%   |
| 5.18    | 12        | 0.23%   |
| 5.7     | 11        | 0.21%   |
| 5.16    | 10        | 0.19%   |
| 4.4     | 10        | 0.19%   |
| 4.18    | 10        | 0.19%   |
| 5.5     | 5         | 0.09%   |
| 4.13    | 3         | 0.06%   |
| 4.10    | 3         | 0.06%   |
| 5.1     | 2         | 0.04%   |
| 4.17    | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4883      | 99.43%  |
| i686    | 13        | 0.26%   |
| aarch64 | 11        | 0.22%   |
| riscv64 | 4         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 3986      | 79.94%  |
| KDE        | 929       | 18.63%  |
| GNOME      | 27        | 0.54%   |
| Cinnamon   | 11        | 0.22%   |
| Budgie     | 8         | 0.16%   |
| MATE       | 7         | 0.14%   |
| XFCE       | 4         | 0.08%   |
| KDE4       | 4         | 0.08%   |
| LXQt       | 3         | 0.06%   |
| Unity      | 2         | 0.04%   |
| X-Cinnamon | 1         | 0.02%   |
| KDE6       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |
| GNUstep    | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4648      | 93.77%  |
| Wayland | 250       | 5.04%   |
| Tty     | 58        | 1.17%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 3028      | 60.56%  |
| Unknown | 1650      | 33%     |
| GDM     | 115       | 2.3%    |
| GDM3    | 100       | 2%      |
| LightDM | 82        | 1.64%   |
| TDM     | 21        | 0.42%   |
| SLiM    | 2         | 0.04%   |
| LXDM    | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2160      | 43.64%  |
| de_DE   | 410       | 8.28%   |
| en_GB   | 247       | 4.99%   |
| ru_RU   | 239       | 4.83%   |
| fr_FR   | 222       | 4.48%   |
| it_IT   | 214       | 4.32%   |
| pt_BR   | 191       | 3.86%   |
| en_CA   | 109       | 2.2%    |
| es_ES   | 106       | 2.14%   |
| en_AU   | 92        | 1.86%   |
| en_IN   | 83        | 1.68%   |
| pl_PL   | 81        | 1.64%   |
| Unknown | 77        | 1.56%   |
| C       | 58        | 1.17%   |
| hu_HU   | 33        | 0.67%   |
| es_MX   | 33        | 0.67%   |
| cs_CZ   | 31        | 0.63%   |
| en_ZA   | 28        | 0.57%   |
| nl_NL   | 27        | 0.55%   |
| es_AR   | 27        | 0.55%   |
| de_AT   | 25        | 0.51%   |
| ru_UA   | 24        | 0.48%   |
| en_NZ   | 22        | 0.44%   |
| zh_CN   | 20        | 0.4%    |
| de_CH   | 19        | 0.38%   |
| tr_TR   | 16        | 0.32%   |
| sv_SE   | 16        | 0.32%   |
| pt_PT   | 15        | 0.3%    |
| es_CO   | 15        | 0.3%    |
| es_CL   | 14        | 0.28%   |
| en_PH   | 13        | 0.26%   |
| en_IL   | 13        | 0.26%   |
| en_IE   | 13        | 0.26%   |
| el_GR   | 13        | 0.26%   |
| nl_BE   | 11        | 0.22%   |
| fr_BE   | 11        | 0.22%   |
| fi_FI   | 11        | 0.22%   |
| es_VE   | 10        | 0.2%    |
| uk_UA   | 9         | 0.18%   |
| en_SG   | 9         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2666      | 53.44%  |
| BIOS | 2323      | 46.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4232      | 85.32%  |
| Tmpfs    | 316       | 6.37%   |
| Btrfs    | 193       | 3.89%   |
| Overlay  | 117       | 2.36%   |
| Xfs      | 48        | 0.97%   |
| Zfs      | 26        | 0.52%   |
| Unknown  | 12        | 0.24%   |
| Ext3     | 5         | 0.1%    |
| Ext2     | 5         | 0.1%    |
| F2fs     | 2         | 0.04%   |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2691      | 53.86%  |
| Unknown | 1889      | 37.81%  |
| MBR     | 416       | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4307      | 86.71%  |
| Yes       | 660       | 13.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3138      | 63.1%   |
| Yes       | 1835      | 36.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 824       | 16.78%  |
| Lenovo              | 744       | 15.15%  |
| Hewlett-Packard     | 671       | 13.66%  |
| Dell                | 643       | 13.09%  |
| Gigabyte Technology | 370       | 7.53%   |
| MSI                 | 332       | 6.76%   |
| Acer                | 230       | 4.68%   |
| ASRock              | 167       | 3.4%    |
| Apple               | 90        | 1.83%   |
| Intel               | 59        | 1.2%    |
| Samsung Electronics | 57        | 1.16%   |
| HUAWEI              | 54        | 1.1%    |
| Unknown             | 47        | 0.96%   |
| Toshiba             | 32        | 0.65%   |
| Google              | 32        | 0.65%   |
| Notebook            | 30        | 0.61%   |
| Fujitsu             | 30        | 0.61%   |
| Sony                | 26        | 0.53%   |
| AZW                 | 24        | 0.49%   |
| TUXEDO              | 21        | 0.43%   |
| Alienware           | 21        | 0.43%   |
| Medion              | 19        | 0.39%   |
| Timi                | 17        | 0.35%   |
| Pegatron            | 16        | 0.33%   |
| Biostar             | 16        | 0.33%   |
| Positivo            | 13        | 0.26%   |
| Packard Bell        | 12        | 0.24%   |
| Foxconn             | 12        | 0.24%   |
| Microsoft           | 11        | 0.22%   |
| PC Specialist       | 10        | 0.2%    |
| ECS                 | 10        | 0.2%    |
| System76            | 9         | 0.18%   |
| Supermicro          | 9         | 0.18%   |
| ZOTAC               | 8         | 0.16%   |
| GPU Company         | 8         | 0.16%   |
| Chuwi               | 8         | 0.16%   |
| LG Electronics      | 7         | 0.14%   |
| Gateway             | 7         | 0.14%   |
| Framework           | 7         | 0.14%   |
| Shuttle             | 6         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 63        | 1.28%   |
| ASUS All Series                    | 54        | 1.1%    |
| ASUS ROG STRIX B550-F GAMING       | 14        | 0.29%   |
| HP Notebook                        | 13        | 0.26%   |
| MSI MS-7C37                        | 12        | 0.24%   |
| Gigabyte B450M DS3H                | 11        | 0.22%   |
| MSI MS-7B79                        | 10        | 0.2%    |
| HP Pavilion g6                     | 10        | 0.2%    |
| Dell OptiPlex 9020                 | 10        | 0.2%    |
| Dell OptiPlex 7010                 | 10        | 0.2%    |
| AZW SER                            | 10        | 0.2%    |
| MSI MS-7C91                        | 9         | 0.18%   |
| HP Pavilion dv6                    | 9         | 0.18%   |
| HP Pavilion 15                     | 9         | 0.18%   |
| HP EliteBook 840 G5                | 9         | 0.18%   |
| Dell XPS 15 9560                   | 9         | 0.18%   |
| ASUS TUF Gaming X570-PLUS          | 9         | 0.18%   |
| ASUS ROG STRIX X570-E GAMING       | 9         | 0.18%   |
| MSI MS-7C56                        | 8         | 0.16%   |
| MSI MS-7817                        | 8         | 0.16%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.16%   |
| HP EliteBook 840 G6                | 8         | 0.16%   |
| Gigabyte X570 AORUS MASTER         | 8         | 0.16%   |
| Gigabyte A320M-S2H                 | 8         | 0.16%   |
| Gigabyte 970A-DS3P                 | 8         | 0.16%   |
| Dell XPS 15 9570                   | 8         | 0.16%   |
| ASUS TUF Gaming B550-PLUS          | 8         | 0.16%   |
| ASUS PRIME B450M-A                 | 8         | 0.16%   |
| ASUS PRIME B350-PLUS               | 8         | 0.16%   |
| ASUS PRIME A320M-K                 | 8         | 0.16%   |
| MSI MS-7B86                        | 7         | 0.14%   |
| MSI MS-7693                        | 7         | 0.14%   |
| HP Pavilion dv7                    | 7         | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx | 7         | 0.14%   |
| Dell XPS 15 7590                   | 7         | 0.14%   |
| MSI MS-7C95                        | 6         | 0.12%   |
| MSI MS-7C02                        | 6         | 0.12%   |
| MSI MS-7A34                        | 6         | 0.12%   |
| HUAWEI HVY-WXX9                    | 6         | 0.12%   |
| HP Pavilion Notebook               | 6         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 335       | 6.82%   |
| Dell Latitude      | 176       | 3.58%   |
| Dell Inspiron      | 157       | 3.2%    |
| Acer Aspire        | 146       | 2.97%   |
| Lenovo IdeaPad     | 141       | 2.87%   |
| HP Pavilion        | 128       | 2.61%   |
| ASUS ROG           | 124       | 2.52%   |
| ASUS PRIME         | 118       | 2.4%    |
| Dell XPS           | 92        | 1.87%   |
| HP EliteBook       | 85        | 1.73%   |
| HP ProBook         | 83        | 1.69%   |
| ASUS VivoBook      | 79        | 1.61%   |
| Dell Precision     | 71        | 1.45%   |
| HP Laptop          | 70        | 1.43%   |
| Dell OptiPlex      | 64        | 1.3%    |
| Unknown            | 63        | 1.28%   |
| ASUS TUF           | 59        | 1.2%    |
| ASUS All           | 54        | 1.1%    |
| HP ENVY            | 45        | 0.92%   |
| Lenovo ThinkCentre | 42        | 0.86%   |
| Lenovo Legion      | 40        | 0.81%   |
| Lenovo Yoga        | 39        | 0.79%   |
| HP Compaq          | 39        | 0.79%   |
| Dell Vostro        | 37        | 0.75%   |
| ASUS ASUS          | 33        | 0.67%   |
| Acer Nitro         | 33        | 0.67%   |
| Lenovo ThinkBook   | 30        | 0.61%   |
| Toshiba Satellite  | 26        | 0.53%   |
| ASUS ZenBook       | 24        | 0.49%   |
| HP ZBook           | 22        | 0.45%   |
| Gigabyte X570      | 22        | 0.45%   |
| Acer Swift         | 22        | 0.45%   |
| Gigabyte B450M     | 19        | 0.39%   |
| HP EliteDesk       | 17        | 0.35%   |
| HP Spectre         | 16        | 0.33%   |
| Gigabyte B550      | 15        | 0.31%   |
| HP OMEN            | 14        | 0.29%   |
| HP Notebook        | 13        | 0.26%   |
| Fujitsu ESPRIMO    | 13        | 0.26%   |
| Dell G3            | 13        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 595       | 12.12%  |
| 2019    | 539       | 10.98%  |
| 2018    | 488       | 9.94%   |
| 2021    | 450       | 9.16%   |
| 2017    | 346       | 7.05%   |
| 2012    | 346       | 7.05%   |
| 2013    | 315       | 6.41%   |
| 2014    | 277       | 5.64%   |
| 2022    | 275       | 5.6%    |
| 2011    | 269       | 5.48%   |
| 2016    | 224       | 4.56%   |
| 2015    | 207       | 4.22%   |
| 2010    | 150       | 3.05%   |
| 2023    | 117       | 2.38%   |
| 2008    | 117       | 2.38%   |
| 2009    | 112       | 2.28%   |
| 2007    | 51        | 1.04%   |
| Unknown | 13        | 0.26%   |
| 2006    | 9         | 0.18%   |
| 2024    | 7         | 0.14%   |
| 2005    | 3         | 0.06%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2706      | 55.1%   |
| Desktop        | 1823      | 37.12%  |
| Convertible    | 172       | 3.5%    |
| Mini pc        | 81        | 1.65%   |
| All in one     | 56        | 1.14%   |
| Tablet         | 43        | 0.88%   |
| Server         | 20        | 0.41%   |
| System on chip | 9         | 0.18%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4511      | 91.28%  |
| Enabled  | 431       | 8.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4870      | 99.17%  |
| Yes  | 41        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1254      | 25.28%  |
| 4.01-8.0        | 1068      | 21.53%  |
| 8.01-16.0       | 923       | 18.61%  |
| 32.01-64.0      | 744       | 15%     |
| 3.01-4.0        | 533       | 10.74%  |
| 64.01-256.0     | 188       | 3.79%   |
| 24.01-32.0      | 154       | 3.1%    |
| 1.01-2.0        | 61        | 1.23%   |
| 2.01-3.0        | 29        | 0.58%   |
| More than 256.0 | 6         | 0.12%   |
| 0.51-1.0        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1364      | 25.5%   |
| 4.01-8.0    | 1338      | 25.02%  |
| 1.01-2.0    | 1123      | 21%     |
| 3.01-4.0    | 939       | 17.56%  |
| 8.01-16.0   | 383       | 7.16%   |
| 0.51-1.0    | 91        | 1.7%    |
| 16.01-24.0  | 70        | 1.31%   |
| 24.01-32.0  | 20        | 0.37%   |
| 32.01-64.0  | 11        | 0.21%   |
| 0.01-0.5    | 7         | 0.13%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2690      | 53.27%  |
| 2      | 1368      | 27.09%  |
| 3      | 467       | 9.25%   |
| 4      | 263       | 5.21%   |
| 5      | 124       | 2.46%   |
| 6      | 57        | 1.13%   |
| 7      | 38        | 0.75%   |
| 0      | 15        | 0.3%    |
| 8      | 11        | 0.22%   |
| 9      | 6         | 0.12%   |
| 11     | 4         | 0.08%   |
| 12     | 3         | 0.06%   |
| 10     | 3         | 0.06%   |
| 13     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3425      | 69.26%  |
| Yes       | 1520      | 30.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4115      | 83.62%  |
| No        | 806       | 16.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3870      | 78.4%   |
| No        | 1066      | 21.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3360      | 67.81%  |
| No        | 1595      | 32.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 980       | 19.9%   |
| Germany      | 555       | 11.27%  |
| Russia       | 327       | 6.64%   |
| France       | 273       | 5.54%   |
| Italy        | 271       | 5.5%    |
| Brazil       | 253       | 5.14%   |
| UK           | 231       | 4.69%   |
| Spain        | 151       | 3.07%   |
| Canada       | 136       | 2.76%   |
| Poland       | 122       | 2.48%   |
| Netherlands  | 106       | 2.15%   |
| Australia    | 92        | 1.87%   |
| India        | 90        | 1.83%   |
| Ukraine      | 64        | 1.3%    |
| Switzerland  | 62        | 1.26%   |
| Mexico       | 60        | 1.22%   |
| Hungary      | 57        | 1.16%   |
| Czechia      | 54        | 1.1%    |
| Belgium      | 48        | 0.97%   |
| Argentina    | 46        | 0.93%   |
| Austria      | 43        | 0.87%   |
| Turkey       | 40        | 0.81%   |
| Sweden       | 39        | 0.79%   |
| Indonesia    | 34        | 0.69%   |
| Finland      | 34        | 0.69%   |
| South Africa | 32        | 0.65%   |
| Greece       | 30        | 0.61%   |
| China        | 30        | 0.61%   |
| Bulgaria     | 30        | 0.61%   |
| Portugal     | 28        | 0.57%   |
| Romania      | 27        | 0.55%   |
| Norway       | 26        | 0.53%   |
| Denmark      | 26        | 0.53%   |
| Slovenia     | 24        | 0.49%   |
| Serbia       | 23        | 0.47%   |
| Colombia     | 23        | 0.47%   |
| New Zealand  | 21        | 0.43%   |
| Chile        | 20        | 0.41%   |
| Slovakia     | 19        | 0.39%   |
| Israel       | 18        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 87        | 1.69%   |
| Berlin            | 55        | 1.07%   |
| Paris             | 44        | 0.85%   |
| Milan             | 39        | 0.76%   |
| St Petersburg     | 38        | 0.74%   |
| Hamburg           | 38        | 0.74%   |
| Warsaw            | 34        | 0.66%   |
| Rome              | 33        | 0.64%   |
| Sao Paulo         | 31        | 0.6%    |
| Budapest          | 29        | 0.56%   |
| Madrid            | 28        | 0.54%   |
| Sydney            | 26        | 0.5%    |
| Frankfurt am Main | 26        | 0.5%    |
| Vienna            | 25        | 0.48%   |
| Munich            | 25        | 0.48%   |
| Cologne           | 24        | 0.46%   |
| Amsterdam         | 23        | 0.45%   |
| London            | 22        | 0.43%   |
| Zurich            | 20        | 0.39%   |
| Rio de Janeiro    | 20        | 0.39%   |
| Melbourne         | 20        | 0.39%   |
| Kyiv              | 19        | 0.37%   |
| Montreal          | 18        | 0.35%   |
| Prague            | 17        | 0.33%   |
| Dallas            | 17        | 0.33%   |
| Sofia             | 16        | 0.31%   |
| Belgrade          | 16        | 0.31%   |
| Istanbul          | 15        | 0.29%   |
| Krakow            | 14        | 0.27%   |
| Johannesburg      | 14        | 0.27%   |
| Athens            | 14        | 0.27%   |
| Seattle           | 13        | 0.25%   |
| San Francisco     | 13        | 0.25%   |
| Minsk             | 13        | 0.25%   |
| Jakarta           | 13        | 0.25%   |
| Dublin            | 13        | 0.25%   |
| Phoenix           | 12        | 0.23%   |
| Novosibirsk       | 12        | 0.23%   |
| Los Angeles       | 12        | 0.23%   |
| Leipzig           | 12        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1384      | 2199   | 17.73%  |
| WDC                         | 1076      | 1714   | 13.78%  |
| Seagate                     | 948       | 1509   | 12.14%  |
| SanDisk                     | 458       | 593    | 5.87%   |
| Kingston                    | 443       | 542    | 5.67%   |
| Toshiba                     | 422       | 590    | 5.41%   |
| Crucial                     | 322       | 409    | 4.12%   |
| Unknown                     | 258       | 329    | 3.3%    |
| Intel                       | 239       | 320    | 3.06%   |
| SK hynix                    | 222       | 262    | 2.84%   |
| Hitachi                     | 182       | 228    | 2.33%   |
| Micron Technology           | 150       | 173    | 1.92%   |
| HGST                        | 138       | 183    | 1.77%   |
| A-DATA Technology           | 115       | 135    | 1.47%   |
| KIOXIA                      | 83        | 93     | 1.06%   |
| China                       | 69        | 89     | 0.88%   |
| Phison                      | 60        | 75     | 0.77%   |
| Silicon Motion              | 59        | 72     | 0.76%   |
| Apple                       | 55        | 68     | 0.7%    |
| SPCC                        | 53        | 74     | 0.68%   |
| PNY                         | 44        | 68     | 0.56%   |
| Phison Electronics          | 44        | 46     | 0.56%   |
| Patriot                     | 42        | 54     | 0.54%   |
| Micron/Crucial Technology   | 41        | 53     | 0.53%   |
| Intenso                     | 37        | 47     | 0.47%   |
| Corsair                     | 36        | 52     | 0.46%   |
| Transcend                   | 35        | 37     | 0.45%   |
| Unknown                     | 34        | 41     | 0.44%   |
| OCZ                         | 29        | 36     | 0.37%   |
| Maxtor                      | 28        | 33     | 0.36%   |
| LITEON                      | 28        | 30     | 0.36%   |
| Kingston Technology Company | 27        | 38     | 0.35%   |
| JMicron Technology          | 27        | 29     | 0.35%   |
| Team                        | 21        | 22     | 0.27%   |
| SABRENT                     | 21        | 26     | 0.27%   |
| GOODRAM                     | 21        | 37     | 0.27%   |
| XPG                         | 17        | 18     | 0.22%   |
| LITEONIT                    | 17        | 19     | 0.22%   |
| Lexar                       | 17        | 18     | 0.22%   |
| KingSpec                    | 16        | 19     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                          | 73        | 0.83%   |
| Kingston SA400S37240G 240GB SSD                    | 72        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 64        | 0.73%   |
| Samsung SSD 850 EVO 250GB                          | 59        | 0.67%   |
| Samsung SSD 850 EVO 500GB                          | 58        | 0.66%   |
| Kingston SA400S37480G 480GB SSD                    | 56        | 0.64%   |
| Samsung SSD 860 EVO 1TB                            | 52        | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                     | 45        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                        | 44        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 41        | 0.47%   |
| Unknown MMC Card  32GB                             | 40        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                     | 40        | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 40        | 0.46%   |
| Unknown MMC Card  64GB                             | 37        | 0.42%   |
| Toshiba MQ01ABD100 1TB                             | 37        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 36        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                       | 36        | 0.41%   |
| Toshiba MQ04ABF100 1TB                             | 35        | 0.4%    |
| HGST HTS721010A9E630 1TB                           | 35        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                     | 34        | 0.39%   |
| Unknown                                            | 34        | 0.39%   |
| Toshiba DT01ACA100 1TB                             | 33        | 0.38%   |
| Samsung NVMe SSD Drive 500GB                       | 33        | 0.38%   |
| Samsung SSD 860 EVO 250GB                          | 32        | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                     | 30        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                     | 30        | 0.34%   |
| Samsung NVMe SSD Drive 1TB                         | 30        | 0.34%   |
| Crucial CT500MX500SSD1 500GB                       | 29        | 0.33%   |
| Seagate ST4000DM004-2CV104 4TB                     | 28        | 0.32%   |
| SanDisk NVMe SSD Drive 1TB                         | 28        | 0.32%   |
| Samsung NVMe SSD Drive 512GB                       | 28        | 0.32%   |
| Toshiba HDWD110 1TB                                | 27        | 0.31%   |
| Seagate ST500DM002-1BD142 500GB                    | 26        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB                     | 26        | 0.3%    |
| SanDisk SSD PLUS 240GB                             | 26        | 0.3%    |
| Samsung SSD 980 1TB                                | 26        | 0.3%    |
| Kingston SA400S37120G 120GB SSD                    | 26        | 0.3%    |
| Unknown SD/MMC/MS PRO 128GB                        | 25        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB                     | 25        | 0.29%   |
| Samsung SSD 870 QVO 1TB                            | 24        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 918       | 1458   | 35.11%  |
| WDC                 | 804       | 1315   | 30.75%  |
| Toshiba             | 300       | 426    | 11.47%  |
| Hitachi             | 182       | 228    | 6.96%   |
| HGST                | 137       | 182    | 5.24%   |
| Samsung Electronics | 119       | 191    | 4.55%   |
| Unknown             | 30        | 35     | 1.15%   |
| Maxtor              | 27        | 32     | 1.03%   |
| SABRENT             | 21        | 26     | 0.8%    |
| Apple               | 19        | 19     | 0.73%   |
| JMicron Technology  | 16        | 17     | 0.61%   |
| Fujitsu             | 12        | 15     | 0.46%   |
| TO Exter            | 4         | 4      | 0.15%   |
| Hewlett-Packard     | 4         | 6      | 0.15%   |
| SAGE                | 3         | 3      | 0.11%   |
| USB                 | 2         | 3      | 0.08%   |
| LaCie               | 2         | 3      | 0.08%   |
| KESU                | 2         | 2      | 0.08%   |
| ASMT                | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SSI                 | 1         | 1      | 0.04%   |
| Shenzhen            | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 2      | 0.04%   |
| LIO-ORG             | 1         | 1      | 0.04%   |
| ipTIME              | 1         | 1      | 0.04%   |
| IET                 | 1         | 1      | 0.04%   |
| HPE                 | 1         | 6      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 667       | 983    | 25.36%  |
| Kingston            | 321       | 384    | 12.21%  |
| Crucial             | 266       | 345    | 10.11%  |
| SanDisk             | 249       | 316    | 9.47%   |
| WDC                 | 147       | 206    | 5.59%   |
| A-DATA Technology   | 85        | 99     | 3.23%   |
| Intel               | 72        | 96     | 2.74%   |
| China               | 68        | 88     | 2.59%   |
| Micron Technology   | 47        | 52     | 1.79%   |
| SPCC                | 44        | 61     | 1.67%   |
| PNY                 | 40        | 64     | 1.52%   |
| Patriot             | 40        | 52     | 1.52%   |
| Toshiba             | 38        | 55     | 1.44%   |
| SK hynix            | 36        | 38     | 1.37%   |
| Intenso             | 30        | 36     | 1.14%   |
| Transcend           | 29        | 29     | 1.1%    |
| OCZ                 | 29        | 36     | 1.1%    |
| LITEON              | 23        | 24     | 0.87%   |
| GOODRAM             | 21        | 37     | 0.8%    |
| Apple               | 21        | 22     | 0.8%    |
| Team                | 18        | 18     | 0.68%   |
| Corsair             | 18        | 31     | 0.68%   |
| LITEONIT            | 17        | 19     | 0.65%   |
| KingSpec            | 16        | 19     | 0.61%   |
| Lexar               | 14        | 15     | 0.53%   |
| Unknown             | 13        | 17     | 0.49%   |
| Apacer              | 11        | 16     | 0.42%   |
| Verbatim            | 10        | 12     | 0.38%   |
| Mushkin             | 10        | 11     | 0.38%   |
| Hewlett-Packard     | 9         | 10     | 0.34%   |
| Seagate             | 8         | 14     | 0.3%    |
| Plextor             | 8         | 9      | 0.3%    |
| Netac               | 8         | 9      | 0.3%    |
| External            | 8         | 14     | 0.3%    |
| Emtec               | 8         | 9      | 0.3%    |
| Gigabyte Technology | 7         | 7      | 0.27%   |
| ASMT                | 7         | 8      | 0.27%   |
| Dogfish             | 6         | 6      | 0.23%   |
| FORESEE             | 5         | 5      | 0.19%   |
| Unknown             | 4         | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2248      | 3468   | 32.49%  |
| NVMe    | 2208      | 3079   | 31.92%  |
| HDD     | 2114      | 3984   | 30.56%  |
| MMC     | 222       | 273    | 3.21%   |
| Unknown | 126       | 183    | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3336      | 7136   | 54.69%  |
| NVMe | 2202      | 3059   | 36.1%   |
| SAS  | 340       | 519    | 5.57%   |
| MMC  | 222       | 273    | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2330      | 3714   | 49.64%  |
| 0.51-1.0   | 1453      | 2196   | 30.95%  |
| 1.01-2.0   | 519       | 851    | 11.06%  |
| 3.01-4.0   | 184       | 359    | 3.92%   |
| 2.01-3.0   | 98        | 143    | 2.09%   |
| 4.01-10.0  | 88        | 150    | 1.87%   |
| 10.01-20.0 | 22        | 39     | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1200      | 23.53%  |
| 101-250        | 1200      | 23.53%  |
| 501-1000       | 962       | 18.86%  |
| 1001-2000      | 584       | 11.45%  |
| More than 3000 | 401       | 7.86%   |
| 2001-3000      | 240       | 4.71%   |
| 51-100         | 239       | 4.69%   |
| 1-20           | 145       | 2.84%   |
| 21-50          | 107       | 2.1%    |
| Unknown        | 22        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1153      | 21.87%  |
| 101-250        | 917       | 17.4%   |
| 21-50          | 836       | 15.86%  |
| 51-100         | 689       | 13.07%  |
| 251-500        | 606       | 11.5%   |
| 501-1000       | 500       | 9.49%   |
| 1001-2000      | 279       | 5.29%   |
| More than 3000 | 182       | 3.45%   |
| 2001-3000      | 87        | 1.65%   |
| Unknown        | 22        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 7         | 13     | 1.39%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 6      | 1.2%    |
| HGST HTS721010A9E630 1TB                | 6         | 7      | 1.2%    |
| Seagate ST31000524AS 1TB                | 5         | 6      | 1%      |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 5      | 1%      |
| HGST HTS545050A7E680 500GB              | 5         | 5      | 1%      |
| WDC WD5000AAKS-00V1A0 500GB             | 4         | 5      | 0.8%    |
| Toshiba MQ04ABF100 1TB                  | 4         | 4      | 0.8%    |
| Toshiba MQ01ABD100 1TB                  | 4         | 6      | 0.8%    |
| Seagate ST9500325AS 500GB               | 4         | 9      | 0.8%    |
| Seagate ST500LT012-9WS142 500GB         | 4         | 4      | 0.8%    |
| Seagate ST3500418AS 500GB               | 4         | 4      | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB          | 4         | 11     | 0.8%    |
| Samsung Electronics SSD 870 EVO 500GB   | 4         | 4      | 0.8%    |
| HGST HTS541010A9E680 1TB                | 4         | 9      | 0.8%    |
| Crucial CT1050MX300SSD1 1050GB          | 4         | 4      | 0.8%    |
| WDC WD30EZRX-00MMMB0 3TB                | 3         | 3      | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB                | 3         | 6      | 0.6%    |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB                | 3         | 4      | 0.6%    |
| Seagate ST9250315AS 250GB               | 3         | 4      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB         | 3         | 3      | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 3      | 0.6%    |
| Seagate ST31000528AS 1TB                | 3         | 3      | 0.6%    |
| Seagate ST1000LM048-2E7172 1TB          | 3         | 3      | 0.6%    |
| SanDisk SSD PLUS 240GB                  | 3         | 3      | 0.6%    |
| Samsung Electronics SSD 870 EVO 1TB     | 3         | 3      | 0.6%    |
| Neo Forza NFS121SA312-6007000 120GB SSD | 3         | 3      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD        | 3         | 3      | 0.6%    |
| Hitachi HTS547564A9E384 640GB           | 3         | 3      | 0.6%    |
| Crucial CT525MX300SSD1 528GB            | 3         | 3      | 0.6%    |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 2      | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB                | 2         | 2      | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB                | 2         | 4      | 0.4%    |
| WDC WD3200JD-22KLB0 320GB               | 2         | 3      | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 2      | 0.4%    |
| WDC WD15EARS-00Z5B1 1TB                 | 2         | 2      | 0.4%    |
| WDC WD10JPVX-60JC3T0 1TB                | 2         | 2      | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 2      | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB                | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 108       | 144    | 22.22%  |
| Seagate             | 105       | 139    | 21.6%   |
| Samsung Electronics | 51        | 77     | 10.49%  |
| Toshiba             | 38        | 45     | 7.82%   |
| Hitachi             | 31        | 32     | 6.38%   |
| Crucial             | 20        | 24     | 4.12%   |
| HGST                | 18        | 24     | 3.7%    |
| SanDisk             | 17        | 18     | 3.5%    |
| Intel               | 15        | 21     | 3.09%   |
| SK hynix            | 13        | 13     | 2.67%   |
| Kingston            | 11        | 12     | 2.26%   |
| Maxtor              | 7         | 9      | 1.44%   |
| A-DATA Technology   | 7         | 7      | 1.44%   |
| Micron Technology   | 5         | 5      | 1.03%   |
| Apple               | 5         | 5      | 1.03%   |
| OCZ                 | 4         | 4      | 0.82%   |
| Neo                 | 3         | 3      | 0.62%   |
| SSSTC               | 2         | 2      | 0.41%   |
| LITEONIT            | 2         | 2      | 0.41%   |
| Intenso             | 2         | 2      | 0.41%   |
| Fujitsu             | 2         | 2      | 0.41%   |
| Zheino              | 1         | 2      | 0.21%   |
| XPG                 | 1         | 1      | 0.21%   |
| VISIPRO             | 1         | 2      | 0.21%   |
| VENO                | 1         | 1      | 0.21%   |
| tecmiyo             | 1         | 3      | 0.21%   |
| Team                | 1         | 1      | 0.21%   |
| T-FORCE             | 1         | 1      | 0.21%   |
| SPCC                | 1         | 1      | 0.21%   |
| SABRENT             | 1         | 1      | 0.21%   |
| R580                | 1         | 1      | 0.21%   |
| Phison Electronics  | 1         | 1      | 0.21%   |
| ORTIAL              | 1         | 1      | 0.21%   |
| Mushkin             | 1         | 1      | 0.21%   |
| LITEON              | 1         | 1      | 0.21%   |
| Drevo               | 1         | 1      | 0.21%   |
| Corsair             | 1         | 1      | 0.21%   |
| China               | 1         | 1      | 0.21%   |
| BAITITON            | 1         | 3      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 105       | 141    | 32.11%  |
| Seagate             | 105       | 139    | 32.11%  |
| Toshiba             | 33        | 40     | 10.09%  |
| Hitachi             | 31        | 32     | 9.48%   |
| Samsung Electronics | 19        | 41     | 5.81%   |
| HGST                | 18        | 24     | 5.5%    |
| Maxtor              | 7         | 9      | 2.14%   |
| Apple               | 5         | 5      | 1.53%   |
| Fujitsu             | 2         | 2      | 0.61%   |
| SABRENT             | 1         | 1      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 298       | 435    | 65.78%  |
| SSD  | 126       | 151    | 27.81%  |
| NVMe | 29        | 31     | 6.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2603      | 5859   | 47.22%  |
| Works    | 2465      | 4503   | 44.72%  |
| Malfunc  | 438       | 617    | 7.95%   |
| Failed   | 6         | 8      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3026      | 45.17%  |
| AMD                              | 1111      | 16.58%  |
| Samsung Electronics              | 726       | 10.84%  |
| SanDisk                          | 370       | 5.52%   |
| SK hynix                         | 185       | 2.76%   |
| Kingston Technology Company      | 153       | 2.28%   |
| Phison Electronics               | 131       | 1.96%   |
| ASMedia Technology               | 111       | 1.66%   |
| Micron Technology                | 103       | 1.54%   |
| Toshiba America Info Systems     | 99        | 1.48%   |
| Micron/Crucial Technology        | 95        | 1.42%   |
| Silicon Motion                   | 78        | 1.16%   |
| KIOXIA                           | 76        | 1.13%   |
| JMicron Technology               | 63        | 0.94%   |
| Marvell Technology Group         | 60        | 0.9%    |
| ADATA Technology                 | 51        | 0.76%   |
| Nvidia                           | 47        | 0.7%    |
| Realtek Semiconductor            | 32        | 0.48%   |
| Solid State Storage Technology   | 20        | 0.3%    |
| Union Memory (Shenzhen)          | 17        | 0.25%   |
| Broadcom / LSI                   | 16        | 0.24%   |
| LSI Logic / Symbios Logic        | 14        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 13        | 0.19%   |
| Lite-On Technology               | 12        | 0.18%   |
| Apple                            | 12        | 0.18%   |
| Silicon Image                    | 11        | 0.16%   |
| VIA Technologies                 | 8         | 0.12%   |
| Shenzhen Longsys Electronics     | 8         | 0.12%   |
| Seagate Technology               | 8         | 0.12%   |
| Lenovo                           | 5         | 0.07%   |
| Zhaoxin                          | 4         | 0.06%   |
| Yangtze Memory Technologies      | 4         | 0.06%   |
| Solidigm                         | 4         | 0.06%   |
| INNOGRIT                         | 4         | 0.06%   |
| Netac Technology                 | 3         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| Promise Technology               | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 751       | 9.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 360       | 4.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 245       | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 228       | 3.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 190       | 2.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 189       | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 164       | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 150       | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 136       | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 130       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 116       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 115       | 1.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 114       | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 112       | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 106       | 1.4%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 103       | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 100       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 94        | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 94        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 91        | 1.2%    |
| Intel SATA Controller [RAID Mode]                                              | 86        | 1.14%   |
| Intel SSD 660P Series                                                          | 82        | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 80        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 78        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 75        | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 74        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 71        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 69        | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 65        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 63        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 63        | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 60        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 57        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 55        | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                            | 52        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 51        | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 51        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 51        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 50        | 0.66%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 49        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3565      | 53.38%  |
| NVMe | 2192      | 32.82%  |
| RAID | 499       | 7.47%   |
| IDE  | 396       | 5.93%   |
| SAS  | 18        | 0.27%   |
| SCSI | 8         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 3493      | 71.13%  |
| AMD           | 1399      | 28.49%  |
| ARM           | 8         | 0.16%   |
| sifive,u74-mc | 4         | 0.08%   |
| CentaurHauls  | 4         | 0.08%   |
| QUALCOMM      | 1         | 0.02%   |
| Phytium       | 1         | 0.02%   |
| Unknown       | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 75        | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 62        | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 58        | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 52        | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 50        | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 46        | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 46        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 43        | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 41        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 41        | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 41        | 0.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 37        | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 35        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 35        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 30        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 30        | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 29        | 0.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 29        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 29        | 0.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 28        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 27        | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 27        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 26        | 0.53%   |
| Intel 12th Gen Core i7-12700H                 | 25        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.45%   |
| AMD FX-8350 Eight-Core Processor              | 22        | 0.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 21        | 0.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 21        | 0.43%   |
| Intel 12th Gen Core i7-1260P                  | 21        | 0.43%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 21        | 0.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 20        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1080      | 21.95%  |
| Intel Core i5           | 1027      | 20.87%  |
| Other                   | 508       | 10.33%  |
| AMD Ryzen 5             | 403       | 8.19%   |
| AMD Ryzen 7             | 357       | 7.26%   |
| Intel Core i3           | 245       | 4.98%   |
| Intel Celeron           | 171       | 3.48%   |
| AMD Ryzen 9             | 125       | 2.54%   |
| Intel Core 2 Duo        | 108       | 2.2%    |
| Intel Xeon              | 97        | 1.97%   |
| Intel Pentium           | 82        | 1.67%   |
| AMD FX                  | 80        | 1.63%   |
| AMD Ryzen 3             | 56        | 1.14%   |
| Intel Core i9           | 43        | 0.87%   |
| AMD Ryzen 7 PRO         | 38        | 0.77%   |
| AMD A10                 | 37        | 0.75%   |
| AMD A6                  | 36        | 0.73%   |
| Intel Atom              | 35        | 0.71%   |
| AMD A8                  | 34        | 0.69%   |
| Intel Pentium Dual-Core | 30        | 0.61%   |
| Intel Core 2 Quad       | 28        | 0.57%   |
| AMD Phenom II X4        | 28        | 0.57%   |
| AMD Ryzen 5 PRO         | 20        | 0.41%   |
| Intel Pentium Silver    | 19        | 0.39%   |
| AMD A4                  | 18        | 0.37%   |
| AMD Athlon              | 15        | 0.3%    |
| AMD Athlon II X4        | 14        | 0.28%   |
| AMD Ryzen Threadripper  | 13        | 0.26%   |
| AMD Athlon II X2        | 11        | 0.22%   |
| AMD Athlon 64 X2        | 11        | 0.22%   |
| Intel Genuine           | 9         | 0.18%   |
| AMD Phenom II X6        | 9         | 0.18%   |
| AMD E1                  | 9         | 0.18%   |
| AMD E                   | 9         | 0.18%   |
| Intel Pentium Dual      | 8         | 0.16%   |
| Intel Core m3           | 8         | 0.16%   |
| AMD E2                  | 7         | 0.14%   |
| Intel Pentium Gold      | 6         | 0.12%   |
| AMD Opteron             | 6         | 0.12%   |
| Intel Core 2            | 5         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1902      | 38.67%  |
| 2       | 1442      | 29.31%  |
| 6       | 649       | 13.19%  |
| 8       | 519       | 10.55%  |
| 12      | 130       | 2.64%   |
| 16      | 67        | 1.36%   |
| 10      | 57        | 1.16%   |
| 14      | 55        | 1.12%   |
| 1       | 40        | 0.81%   |
| 24      | 19        | 0.39%   |
| 3       | 13        | 0.26%   |
| Unknown | 8         | 0.16%   |
| 20      | 6         | 0.12%   |
| 32      | 5         | 0.1%    |
| 64      | 2         | 0.04%   |
| 18      | 2         | 0.04%   |
| 44      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4867      | 99.1%   |
| 2       | 33        | 0.67%   |
| Unknown | 8         | 0.16%   |
| 4       | 2         | 0.04%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3706      | 75.28%  |
| 1       | 1209      | 24.56%  |
| Unknown | 8         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4898      | 99.74%  |
| Unknown        | 6         | 0.12%   |
| 64-bit         | 5         | 0.1%    |
| 32-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1949      | 38.49%  |
| 0x306a9    | 185       | 3.65%   |
| 0x306c3    | 176       | 3.48%   |
| 0x206a7    | 163       | 3.22%   |
| 0x906ea    | 132       | 2.61%   |
| 0x806ec    | 113       | 2.23%   |
| 0x806c1    | 109       | 2.15%   |
| 0x806ea    | 104       | 2.05%   |
| 0x40651    | 83        | 1.64%   |
| 0x08701021 | 83        | 1.64%   |
| 0x906e9    | 80        | 1.58%   |
| 0x1067a    | 80        | 1.58%   |
| 0x806e9    | 76        | 1.5%    |
| 0x506e3    | 75        | 1.48%   |
| 0x0a50000c | 70        | 1.38%   |
| 0x406e3    | 62        | 1.22%   |
| 0x08108109 | 59        | 1.17%   |
| 0x08600106 | 51        | 1.01%   |
| 0x0800820d | 50        | 0.99%   |
| 0x306d4    | 47        | 0.93%   |
| 0x906a3    | 44        | 0.87%   |
| 0x06000852 | 44        | 0.87%   |
| 0x08108102 | 40        | 0.79%   |
| 0x706e5    | 39        | 0.77%   |
| 0x08701013 | 39        | 0.77%   |
| 0xa0652    | 37        | 0.73%   |
| 0x08608103 | 37        | 0.73%   |
| 0x906ed    | 34        | 0.67%   |
| 0x806eb    | 33        | 0.65%   |
| 0x010000c8 | 32        | 0.63%   |
| 0x20655    | 29        | 0.57%   |
| 0x706a1    | 28        | 0.55%   |
| 0x0a50000d | 28        | 0.55%   |
| 0x706a8    | 25        | 0.49%   |
| 0x08600104 | 25        | 0.49%   |
| 0x406c4    | 23        | 0.45%   |
| 0x30678    | 22        | 0.43%   |
| 0x06001119 | 22        | 0.43%   |
| 0xa0653    | 20        | 0.4%    |
| 0x806d1    | 20        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 878       | 17.82%  |
| Haswell          | 444       | 9.01%   |
| IvyBridge        | 325       | 6.6%    |
| Zen 2            | 312       | 6.33%   |
| Unknown          | 304       | 6.17%   |
| SandyBridge      | 269       | 5.46%   |
| Skylake          | 238       | 4.83%   |
| Zen 3            | 228       | 4.63%   |
| Zen+             | 226       | 4.59%   |
| TigerLake        | 204       | 4.14%   |
| Penryn           | 150       | 3.05%   |
| Alderlake Hybrid | 135       | 2.74%   |
| CometLake        | 127       | 2.58%   |
| Icelake          | 113       | 2.29%   |
| Zen              | 106       | 2.15%   |
| Piledriver       | 103       | 2.09%   |
| Broadwell        | 92        | 1.87%   |
| Goldmont plus    | 85        | 1.73%   |
| Westmere         | 83        | 1.68%   |
| K10              | 83        | 1.68%   |
| Silvermont       | 73        | 1.48%   |
| Core             | 59        | 1.2%    |
| Excavator        | 53        | 1.08%   |
| Nehalem          | 49        | 0.99%   |
| Goldmont         | 35        | 0.71%   |
| Puma             | 24        | 0.49%   |
| Steamroller      | 20        | 0.41%   |
| K10 Llano        | 20        | 0.41%   |
| K8 Hammer        | 18        | 0.37%   |
| Bobcat           | 18        | 0.37%   |
| Jaguar           | 17        | 0.35%   |
| Bulldozer        | 10        | 0.2%    |
| NetBurst         | 8         | 0.16%   |
| Tremont          | 7         | 0.14%   |
| Bonnell          | 7         | 0.14%   |
| K8 & K10 hybrid  | 2         | 0.04%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2725      | 45.81%  |
| Nvidia                           | 1766      | 29.69%  |
| AMD                              | 1433      | 24.09%  |
| Matrox Electronics Systems       | 9         | 0.15%   |
| ASPEED Technology                | 9         | 0.15%   |
| Zhaoxin                          | 4         | 0.07%   |
| ATI Technologies                 | 2         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 191       | 3.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 184       | 3.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 180       | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 149       | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 146       | 2.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 137       | 2.25%   |
| Intel UHD Graphics 620                                                                   | 132       | 2.17%   |
| Intel HD Graphics 620                                                                    | 117       | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 107       | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 106       | 1.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 106       | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 101       | 1.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 100       | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 95        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 86        | 1.41%   |
| Intel HD Graphics 530                                                                    | 78        | 1.28%   |
| Intel HD Graphics 630                                                                    | 75        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 72        | 1.18%   |
| Intel HD Graphics 5500                                                                   | 71        | 1.17%   |
| AMD Lucienne                                                                             | 70        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 66        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 63        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 52        | 0.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 45        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 44        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42        | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 38        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 38        | 0.62%   |
| AMD Rembrandt [Radeon 680M]                                                              | 38        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 37        | 0.61%   |
| Intel Iris Plus Graphics G7                                                              | 35        | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 35        | 0.57%   |
| AMD Raphael                                                                              | 34        | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.54%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 33        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1807      | 36.61%  |
| 1 x AMD                  | 1103      | 22.35%  |
| 1 x Nvidia               | 904       | 18.31%  |
| Intel + Nvidia           | 717       | 14.53%  |
| Intel + AMD              | 134       | 2.71%   |
| AMD + Nvidia             | 116       | 2.35%   |
| 2 x AMD                  | 84        | 1.7%    |
| 2 x Nvidia               | 20        | 0.41%   |
| Other                    | 19        | 0.38%   |
| 1 x ASPEED               | 5         | 0.1%    |
| 1 x Zhaoxin              | 4         | 0.08%   |
| Nvidia + ASPEED          | 4         | 0.08%   |
| 1 x Matrox               | 4         | 0.08%   |
| 3 x Nvidia               | 3         | 0.06%   |
| 2 x Intel                | 3         | 0.06%   |
| Nvidia + Matrox          | 3         | 0.06%   |
| AMD + Matrox             | 2         | 0.04%   |
| 3 x AMD                  | 1         | 0.02%   |
| 1 x SiS                  | 1         | 0.02%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3600      | 72.39%  |
| Proprietary | 1256      | 25.26%  |
| Unknown     | 117       | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2880      | 57.21%  |
| 1.01-2.0   | 527       | 10.47%  |
| 0.01-0.5   | 427       | 8.48%   |
| 3.01-4.0   | 358       | 7.11%   |
| 0.51-1.0   | 310       | 6.16%   |
| 7.01-8.0   | 245       | 4.87%   |
| 5.01-6.0   | 145       | 2.88%   |
| 8.01-16.0  | 81        | 1.61%   |
| 2.01-3.0   | 40        | 0.79%   |
| 16.01-24.0 | 16        | 0.32%   |
| 4.01-5.0   | 4         | 0.08%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 723       | 12.5%   |
| AU Optronics            | 609       | 10.53%  |
| BOE                     | 541       | 9.35%   |
| LG Display              | 480       | 8.3%    |
| Chimei Innolux          | 474       | 8.2%    |
| Dell                    | 387       | 6.69%   |
| Goldstar                | 323       | 5.58%   |
| Hewlett-Packard         | 201       | 3.48%   |
| Acer                    | 197       | 3.41%   |
| BenQ                    | 144       | 2.49%   |
| AOC                     | 140       | 2.42%   |
| Philips                 | 136       | 2.35%   |
| Ancor Communications    | 127       | 2.2%    |
| Sharp                   | 122       | 2.11%   |
| Iiyama                  | 83        | 1.43%   |
| ASUSTek Computer        | 83        | 1.43%   |
| Lenovo                  | 80        | 1.38%   |
| Apple                   | 75        | 1.3%    |
| ViewSonic               | 65        | 1.12%   |
| PANDA                   | 60        | 1.04%   |
| Chi Mei Optoelectronics | 53        | 0.92%   |
| InfoVision              | 46        | 0.8%    |
| Sony                    | 32        | 0.55%   |
| LG Electronics          | 31        | 0.54%   |
| Unknown                 | 25        | 0.43%   |
| Panasonic               | 23        | 0.4%    |
| NEC Computers           | 22        | 0.38%   |
| Eizo                    | 22        | 0.38%   |
| CSO                     | 22        | 0.38%   |
| MSI                     | 19        | 0.33%   |
| Sceptre Tech            | 18        | 0.31%   |
| Gigabyte Technology     | 16        | 0.28%   |
| HannStar                | 15        | 0.26%   |
| Vizio                   | 14        | 0.24%   |
| Toshiba                 | 13        | 0.22%   |
| Medion                  | 13        | 0.22%   |
| Vestel Elektronik       | 9         | 0.16%   |
| Idek Iiyama             | 9         | 0.16%   |
| Fujitsu Siemens         | 9         | 0.16%   |
| RTK                     | 8         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 29        | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 26        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 25        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 24        | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 23        | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 23        | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 21        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 20        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 19        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 18        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 18        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 16        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 15        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 15        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 15        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 13        | 0.22%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 13        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 12        | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch              | 12        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 12        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 11        | 0.18%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 11        | 0.18%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                          | 11        | 0.18%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 10        | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 10        | 0.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 10        | 0.17%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 10        | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 9         | 0.15%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 9         | 0.15%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                       | 9         | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 9         | 0.15%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                             | 8         | 0.13%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 8         | 0.13%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 8         | 0.13%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 8         | 0.13%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch     | 8         | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2630      | 48.24%  |
| 1366x768 (WXGA)    | 745       | 13.66%  |
| 3840x2160 (4K)     | 401       | 7.36%   |
| 2560x1440 (QHD)    | 307       | 5.63%   |
| 1920x1200 (WUXGA)  | 191       | 3.5%    |
| 1600x900 (HD+)     | 186       | 3.41%   |
| 1680x1050 (WSXGA+) | 122       | 2.24%   |
| 1280x1024 (SXGA)   | 95        | 1.74%   |
| 3440x1440          | 79        | 1.45%   |
| Unknown            | 79        | 1.45%   |
| 1440x900 (WXGA+)   | 75        | 1.38%   |
| 2560x1600          | 67        | 1.23%   |
| 2560x1080          | 63        | 1.16%   |
| 1280x800 (WXGA)    | 48        | 0.88%   |
| 2880x1800          | 40        | 0.73%   |
| 3840x1080          | 38        | 0.7%    |
| 1360x768           | 37        | 0.68%   |
| 3840x2400          | 23        | 0.42%   |
| 2160x1440          | 23        | 0.42%   |
| 1920x540           | 16        | 0.29%   |
| 1600x1200          | 13        | 0.24%   |
| 2240x1400          | 12        | 0.22%   |
| 1024x768 (XGA)     | 12        | 0.22%   |
| 3840x1200          | 9         | 0.17%   |
| 2256x1504          | 9         | 0.17%   |
| 1920x1280          | 9         | 0.17%   |
| 3200x1800 (QHD+)   | 8         | 0.15%   |
| 3840x1600          | 7         | 0.13%   |
| 4480x1440          | 6         | 0.11%   |
| 1280x720 (HD)      | 6         | 0.11%   |
| 3456x2160          | 5         | 0.09%   |
| 3200x2000          | 5         | 0.09%   |
| 2736x1824          | 5         | 0.09%   |
| 2288x1287          | 5         | 0.09%   |
| 5760x1080          | 4         | 0.07%   |
| 3600x1080          | 4         | 0.07%   |
| 3072x1920          | 4         | 0.07%   |
| 2520x1680          | 4         | 0.07%   |
| 5760x2160          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1362      | 23.61%  |
| 27      | 504       | 8.74%   |
| 24      | 500       | 8.67%   |
| 13      | 465       | 8.06%   |
| 14      | 454       | 7.87%   |
| 23      | 404       | 7%      |
| 17      | 329       | 5.7%    |
| 21      | 314       | 5.44%   |
| Unknown | 252       | 4.37%   |
| 31      | 149       | 2.58%   |
| 34      | 125       | 2.17%   |
| 19      | 106       | 1.84%   |
| 16      | 80        | 1.39%   |
| 20      | 76        | 1.32%   |
| 22      | 75        | 1.3%    |
| 12      | 73        | 1.27%   |
| 18      | 66        | 1.14%   |
| 11      | 62        | 1.07%   |
| 54      | 37        | 0.64%   |
| 32      | 37        | 0.64%   |
| 72      | 35        | 0.61%   |
| 84      | 33        | 0.57%   |
| 40      | 29        | 0.5%    |
| 25      | 26        | 0.45%   |
| 28      | 17        | 0.29%   |
| 26      | 17        | 0.29%   |
| 46      | 13        | 0.23%   |
| 48      | 11        | 0.19%   |
| 42      | 9         | 0.16%   |
| 37      | 9         | 0.16%   |
| 52      | 8         | 0.14%   |
| 10      | 8         | 0.14%   |
| 65      | 6         | 0.1%    |
| 36      | 6         | 0.1%    |
| 29      | 6         | 0.1%    |
| 49      | 5         | 0.09%   |
| 142     | 4         | 0.07%   |
| 69      | 4         | 0.07%   |
| 60      | 4         | 0.07%   |
| 43      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2104      | 37.46%  |
| 501-600        | 1284      | 22.86%  |
| 401-500        | 568       | 10.11%  |
| 351-400        | 384       | 6.84%   |
| 201-300        | 380       | 6.77%   |
| Unknown        | 252       | 4.49%   |
| 601-700        | 226       | 4.02%   |
| 701-800        | 170       | 3.03%   |
| 1001-1500      | 101       | 1.8%    |
| 1501-2000      | 76        | 1.35%   |
| 801-900        | 48        | 0.85%   |
| 901-1000       | 14        | 0.25%   |
| More than 2000 | 4         | 0.07%   |
| 101-200        | 3         | 0.05%   |
| 1-100          | 3         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3848      | 76.27%  |
| 16/10   | 614       | 12.17%  |
| Unknown | 215       | 4.26%   |
| 21/9    | 143       | 2.83%   |
| 5/4     | 88        | 1.74%   |
| 3/2     | 66        | 1.31%   |
| 4/3     | 31        | 0.61%   |
| 32/9    | 17        | 0.34%   |
| 6/5     | 6         | 0.12%   |
| 1.00    | 4         | 0.08%   |
| 0.56    | 4         | 0.08%   |
| 3.40    | 2         | 0.04%   |
| 1.96    | 2         | 0.04%   |
| 0.25    | 2         | 0.04%   |
| 0.67    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.31    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1362      | 23.98%  |
| 201-250        | 973       | 17.13%  |
| 81-90          | 726       | 12.78%  |
| 301-350        | 520       | 9.16%   |
| 351-500        | 330       | 5.81%   |
| 151-200        | 260       | 4.58%   |
| 121-130        | 256       | 4.51%   |
| Unknown        | 252       | 4.44%   |
| 251-300        | 206       | 3.63%   |
| 71-80          | 200       | 3.52%   |
| More than 1000 | 153       | 2.69%   |
| 141-150        | 95        | 1.67%   |
| 501-1000       | 90        | 1.58%   |
| 111-120        | 71        | 1.25%   |
| 51-60          | 64        | 1.13%   |
| 61-70          | 59        | 1.04%   |
| 131-140        | 34        | 0.6%    |
| 91-100         | 14        | 0.25%   |
| 41-50          | 8         | 0.14%   |
| 1-40           | 6         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1719      | 31.25%  |
| 121-160       | 1623      | 29.5%   |
| 101-120       | 1205      | 21.91%  |
| 161-240       | 403       | 7.33%   |
| Unknown       | 252       | 4.58%   |
| More than 240 | 160       | 2.91%   |
| 1-50          | 139       | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3704      | 73.8%   |
| 2     | 1051      | 20.94%  |
| 3     | 133       | 2.65%   |
| 0     | 112       | 2.23%   |
| 4     | 19        | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2783      | 37.32%  |
| Intel                             | 2556      | 34.27%  |
| Qualcomm Atheros                  | 674       | 9.04%   |
| Broadcom                          | 314       | 4.21%   |
| MediaTek                          | 198       | 2.65%   |
| TP-Link                           | 91        | 1.22%   |
| Ralink Technology                 | 75        | 1.01%   |
| Ralink                            | 67        | 0.9%    |
| Broadcom Limited                  | 54        | 0.72%   |
| ASIX Electronics                  | 49        | 0.66%   |
| Nvidia                            | 39        | 0.52%   |
| Samsung Electronics               | 37        | 0.5%    |
| Marvell Technology Group          | 36        | 0.48%   |
| DisplayLink                       | 31        | 0.42%   |
| Aquantia                          | 28        | 0.38%   |
| Xiaomi                            | 25        | 0.34%   |
| Qualcomm                          | 24        | 0.32%   |
| Qualcomm Atheros Communications   | 23        | 0.31%   |
| NetGear                           | 23        | 0.31%   |
| Microsoft                         | 23        | 0.31%   |
| Lenovo                            | 21        | 0.28%   |
| Huawei Technologies               | 19        | 0.25%   |
| Dell                              | 18        | 0.24%   |
| Sierra Wireless                   | 17        | 0.23%   |
| D-Link                            | 16        | 0.21%   |
| ASUSTek Computer                  | 16        | 0.21%   |
| Edimax Technology                 | 13        | 0.17%   |
| Ericsson Business Mobile Networks | 12        | 0.16%   |
| Hewlett-Packard                   | 11        | 0.15%   |
| Apple                             | 10        | 0.13%   |
| Google                            | 9         | 0.12%   |
| JMicron Technology                | 8         | 0.11%   |
| D-Link System                     | 8         | 0.11%   |
| Linksys                           | 7         | 0.09%   |
| Belkin Components                 | 7         | 0.09%   |
| AVM                               | 6         | 0.08%   |
| FIBOCOM                           | 5         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.05%   |
| VIA Technologies                  | 4         | 0.05%   |
| U-Blox                            | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1860      | 21.32%  |
| Intel Wi-Fi 6 AX200                                                    | 281       | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 242       | 2.77%   |
| Realtek RTL8125 2.5GbE Controller                                      | 182       | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 177       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 163       | 1.87%   |
| Intel Wireless 8265 / 8275                                             | 162       | 1.86%   |
| Intel I211 Gigabit Network Connection                                  | 147       | 1.69%   |
| Intel Wi-Fi 6 AX201                                                    | 144       | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 129       | 1.48%   |
| Intel Wireless 7265                                                    | 122       | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 115       | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 110       | 1.26%   |
| Intel Wireless 7260                                                    | 106       | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 103       | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 95        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 94        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 94        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 89        | 1.02%   |
| Intel Ethernet Controller I225-V                                       | 85        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 84        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 82        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 74        | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 74        | 0.85%   |
| Intel Wireless 3165                                                    | 73        | 0.84%   |
| Intel Wireless 8260                                                    | 69        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 69        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 65        | 0.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 63        | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 62        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 55        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 54        | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 54        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                   | 50        | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 49        | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 48        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 45        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 45        | 0.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 41        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                  | 41        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1978      | 48.55%  |
| Realtek Semiconductor                 | 669       | 16.42%  |
| Qualcomm Atheros                      | 529       | 12.98%  |
| Broadcom                              | 217       | 5.33%   |
| MediaTek                              | 191       | 4.69%   |
| TP-Link                               | 80        | 1.96%   |
| Ralink Technology                     | 75        | 1.84%   |
| Ralink                                | 67        | 1.64%   |
| Broadcom Limited                      | 41        | 1.01%   |
| Qualcomm Atheros Communications       | 23        | 0.56%   |
| NetGear                               | 23        | 0.56%   |
| Microsoft                             | 22        | 0.54%   |
| Sierra Wireless                       | 17        | 0.42%   |
| Qualcomm                              | 17        | 0.42%   |
| D-Link                                | 16        | 0.39%   |
| ASUSTek Computer                      | 16        | 0.39%   |
| Edimax Technology                     | 13        | 0.32%   |
| Dell                                  | 12        | 0.29%   |
| Marvell Technology Group              | 7         | 0.17%   |
| Belkin Components                     | 7         | 0.17%   |
| Linksys                               | 6         | 0.15%   |
| AVM                                   | 6         | 0.15%   |
| FIBOCOM                               | 5         | 0.12%   |
| D-Link System                         | 5         | 0.12%   |
| Hewlett-Packard                       | 4         | 0.1%    |
| Wacom                                 | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| ZyDAS                                 | 2         | 0.05%   |
| Wilocity                              | 2         | 0.05%   |
| Mercucys                              | 2         | 0.05%   |
| IMC Networks                          | 2         | 0.05%   |
| Texas Instruments                     | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| LG Electronics                        | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 281       | 6.84%   |
| Intel Wireless 8265 / 8275                                     | 162       | 3.94%   |
| Intel Wi-Fi 6 AX201                                            | 144       | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 129       | 3.14%   |
| Intel Wireless 7265                                            | 122       | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 115       | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 110       | 2.68%   |
| Intel Wireless 7260                                            | 106       | 2.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 103       | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 95        | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 94        | 2.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 94        | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 89        | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 84        | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 74        | 1.8%    |
| Intel Wireless 3165                                            | 73        | 1.78%   |
| Intel Wireless 8260                                            | 69        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 69        | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 65        | 1.58%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 63        | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 62        | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 55        | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 54        | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 49        | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 48        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 41        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 40        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 38        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 38        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                | 35        | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 33        | 0.8%    |
| Intel Wireless 3160                                            | 33        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 33        | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                  | 32        | 0.78%   |
| Realtek 802.11ac NIC                                           | 31        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 31        | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 31        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 29        | 0.71%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 25        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2478      | 55.94%  |
| Intel                            | 1240      | 27.99%  |
| Qualcomm Atheros                 | 188       | 4.24%   |
| Broadcom                         | 132       | 2.98%   |
| ASIX Electronics                 | 49        | 1.11%   |
| Nvidia                           | 39        | 0.88%   |
| Samsung Electronics              | 37        | 0.84%   |
| DisplayLink                      | 31        | 0.7%    |
| Marvell Technology Group         | 29        | 0.65%   |
| Aquantia                         | 28        | 0.63%   |
| Xiaomi                           | 25        | 0.56%   |
| Lenovo                           | 21        | 0.47%   |
| Huawei Technologies              | 16        | 0.36%   |
| Broadcom Limited                 | 14        | 0.32%   |
| TP-Link                          | 11        | 0.25%   |
| Apple                            | 10        | 0.23%   |
| Google                           | 9         | 0.2%    |
| JMicron Technology               | 8         | 0.18%   |
| Qualcomm                         | 7         | 0.16%   |
| MediaTek                         | 7         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.09%   |
| VIA Technologies                 | 4         | 0.09%   |
| OPPO Electronics                 | 4         | 0.09%   |
| T & A Mobile Phones              | 3         | 0.07%   |
| Motorola PCS                     | 3         | 0.07%   |
| Mellanox Technologies            | 3         | 0.07%   |
| D-Link System                    | 3         | 0.07%   |
| Solarflare Communications        | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Raspberry Pi                     | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| IBM                              | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| American Megatrends              | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Tehuti Networks                  | 1         | 0.02%   |
| Spreadtrum Communications        | 1         | 0.02%   |
| QNAP System                      | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| Motorola BCS                     | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1860      | 40.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 242       | 5.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 182       | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 177       | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 163       | 3.58%   |
| Intel I211 Gigabit Network Connection                                          | 147       | 3.23%   |
| Intel Ethernet Controller I225-V                                               | 85        | 1.87%   |
| Intel Ethernet Connection (2) I219-V                                           | 82        | 1.8%    |
| Intel Ethernet Connection I217-LM                                              | 74        | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 54        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                           | 50        | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 45        | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                                          | 41        | 0.9%    |
| Intel 82579V Gigabit Network Connection                                        | 35        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                           | 31        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 29        | 0.64%   |
| Intel I210 Gigabit Network Connection                                          | 28        | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 28        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 28        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 27        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 26        | 0.57%   |
| Intel Ethernet Connection I218-LM                                              | 26        | 0.57%   |
| Realtek Killer E2600 GbE Controller                                            | 24        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 24        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 23        | 0.51%   |
| Intel Ethernet Connection I217-V                                               | 23        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 22        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                           | 22        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                           | 22        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 21        | 0.46%   |
| Intel 82574L Gigabit Network Connection                                        | 21        | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 20        | 0.44%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 20        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 19        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 18        | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 18        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                          | 17        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 17        | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 16        | 0.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 16        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4105      | 51.1%   |
| WiFi     | 3867      | 48.14%  |
| Modem    | 53        | 0.66%   |
| Unknown  | 8         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3020      | 58.08%  |
| Ethernet | 2179      | 41.9%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2608      | 53.01%  |
| 1     | 2089      | 42.46%  |
| 3     | 121       | 2.46%   |
| 0     | 77        | 1.57%   |
| 4     | 18        | 0.37%   |
| 6     | 4         | 0.08%   |
| 5     | 3         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3876      | 77.77%  |
| Yes     | 1107      | 22.21%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1724      | 50.51%  |
| Realtek Semiconductor           | 346       | 10.14%  |
| Qualcomm Atheros Communications | 235       | 6.89%   |
| Cambridge Silicon Radio         | 221       | 6.48%   |
| IMC Networks                    | 153       | 4.48%   |
| Broadcom                        | 149       | 4.37%   |
| Foxconn / Hon Hai               | 110       | 3.22%   |
| Lite-On Technology              | 105       | 3.08%   |
| Apple                           | 77        | 2.26%   |
| ASUSTek Computer                | 56        | 1.64%   |
| MediaTek                        | 37        | 1.08%   |
| Dell                            | 36        | 1.05%   |
| Realtek                         | 32        | 0.94%   |
| Ralink                          | 22        | 0.64%   |
| Hewlett-Packard                 | 15        | 0.44%   |
| TP-Link                         | 14        | 0.41%   |
| Toshiba                         | 12        | 0.35%   |
| Foxconn International           | 9         | 0.26%   |
| Marvell Semiconductor           | 8         | 0.23%   |
| Ralink Technology               | 6         | 0.18%   |
| SiW                             | 5         | 0.15%   |
| Dynex                           | 5         | 0.15%   |
| Alps Electric                   | 5         | 0.15%   |
| USI                             | 4         | 0.12%   |
| Edimax Technology               | 4         | 0.12%   |
| Integrated System Solution      | 3         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| Smart Modular Technologies      | 2         | 0.06%   |
| Micro Star International        | 2         | 0.06%   |
| D-Link                          | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| GN Netcom                       | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 342       | 10.01%  |
| Intel Bluetooth wireless interface                  | 339       | 9.92%   |
| Intel AX200 Bluetooth                               | 273       | 7.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 228       | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 221       | 6.47%   |
| Realtek Bluetooth Radio                             | 208       | 6.09%   |
| Intel Bluetooth Device                              | 204       | 5.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 122       | 3.57%   |
| Intel AX211 Bluetooth                               | 115       | 3.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 66        | 1.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 60        | 1.76%   |
| Intel AX210 Bluetooth                               | 59        | 1.73%   |
| IMC Networks Wireless_Device                        | 56        | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 52        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 49        | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 42        | 1.23%   |
| MediaTek Wireless_Device                            | 37        | 1.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 36        | 1.05%   |
| Apple Bluetooth Host Controller                     | 35        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 0.97%   |
| Lite-On Bluetooth Device                            | 33        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 33        | 0.97%   |
| Realtek Bluetooth Radio                             | 32        | 0.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 29        | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 29        | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 27        | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 0.73%   |
| Lite-On Wireless_Device                             | 24        | 0.7%    |
| Apple Bluetooth USB Host Controller                 | 24        | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 23        | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 23        | 0.67%   |
| Ralink RT3290 Bluetooth                             | 22        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 0.61%   |
| IMC Networks Bluetooth Device                       | 20        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.56%   |
| ASUS ASUS USB-BT500                                 | 18        | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 17        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 17        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3399      | 46.84%  |
| AMD                        | 1625      | 22.4%   |
| Nvidia                     | 1305      | 17.99%  |
| C-Media Electronics        | 128       | 1.76%   |
| Logitech                   | 63        | 0.87%   |
| GN Netcom                  | 45        | 0.62%   |
| Creative Labs              | 45        | 0.62%   |
| Realtek Semiconductor      | 41        | 0.57%   |
| JMTek                      | 40        | 0.55%   |
| ASUSTek Computer           | 32        | 0.44%   |
| Texas Instruments          | 30        | 0.41%   |
| Generalplus Technology     | 28        | 0.39%   |
| Razer USA                  | 23        | 0.32%   |
| Hewlett-Packard            | 23        | 0.32%   |
| Corsair                    | 23        | 0.32%   |
| Creative Technology        | 22        | 0.3%    |
| Lenovo                     | 19        | 0.26%   |
| Focusrite-Novation         | 19        | 0.26%   |
| Plantronics                | 18        | 0.25%   |
| SteelSeries ApS            | 17        | 0.23%   |
| Kingston Technology        | 16        | 0.22%   |
| Micro Star International   | 12        | 0.17%   |
| VIA Technologies           | 11        | 0.15%   |
| Tenx Technology            | 10        | 0.14%   |
| DSEA A/S                   | 9         | 0.12%   |
| Dell                       | 9         | 0.12%   |
| Blue Microphones           | 9         | 0.12%   |
| Sony                       | 8         | 0.11%   |
| PreSonus Audio Electronics | 7         | 0.1%    |
| SAVITECH                   | 6         | 0.08%   |
| Apple                      | 6         | 0.08%   |
| AKAI Professional M.I.     | 6         | 0.08%   |
| Trust                      | 5         | 0.07%   |
| TEAC                       | 5         | 0.07%   |
| RODE Microphones           | 5         | 0.07%   |
| BEHRINGER International    | 5         | 0.07%   |
| Arturia                    | 5         | 0.07%   |
| ZOOM                       | 4         | 0.06%   |
| Zhaoxin                    | 4         | 0.06%   |
| Yamaha                     | 4         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 612       | 7.03%   |
| Intel Sunrise Point-LP HD Audio                                            | 365       | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 312       | 3.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 301       | 3.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 259       | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 256       | 2.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 248       | 2.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 235       | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 204       | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 201       | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 176       | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 157       | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 143       | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 133       | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 128       | 1.47%   |
| AMD FCH Azalia Controller                                                  | 120       | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 114       | 1.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 112       | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 109       | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 108       | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 107       | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 102       | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 97        | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 96        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 91        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 90        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 85        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 84        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 83        | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 82        | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 81        | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 81        | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78        | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 78        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 72        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 70        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 68        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 65        | 0.75%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 65        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 64        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 779       | 21.62%  |
| SK hynix            | 579       | 16.07%  |
| Kingston            | 459       | 12.74%  |
| Micron Technology   | 383       | 10.63%  |
| Crucial             | 264       | 7.33%   |
| Corsair             | 225       | 6.24%   |
| Unknown             | 219       | 6.08%   |
| G.Skill             | 163       | 4.52%   |
| A-DATA Technology   | 79        | 2.19%   |
| Ramaxel Technology  | 56        | 1.55%   |
| Unknown (ABCD)      | 51        | 1.42%   |
| Nanya Technology    | 39        | 1.08%   |
| Elpida              | 36        | 1%      |
| Unknown             | 36        | 1%      |
| Team                | 27        | 0.75%   |
| Patriot             | 23        | 0.64%   |
| Transcend           | 19        | 0.53%   |
| Smart               | 19        | 0.53%   |
| Goodram             | 9         | 0.25%   |
| Silicon Power       | 8         | 0.22%   |
| Apacer              | 8         | 0.22%   |
| AMD                 | 8         | 0.22%   |
| Avant               | 6         | 0.17%   |
| Wilk                | 5         | 0.14%   |
| Teikon              | 5         | 0.14%   |
| Smart Brazil        | 5         | 0.14%   |
| ASint Technology    | 5         | 0.14%   |
| PNY                 | 4         | 0.11%   |
| Lexar               | 4         | 0.11%   |
| 4ea5                | 4         | 0.11%   |
| SHARETRONIC         | 3         | 0.08%   |
| Kllisre             | 3         | 0.08%   |
| KINGBANK            | 3         | 0.08%   |
| Goldkey             | 3         | 0.08%   |
| GeIL                | 3         | 0.08%   |
| ff                  | 3         | 0.08%   |
| CSX                 | 3         | 0.08%   |
| V-GeN               | 2         | 0.06%   |
| V-Color             | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 39        | 1.01%   |
| Unknown                                                          | 36        | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 34        | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 31        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 29        | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 21        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 21        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 19        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 15        | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.36%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 12        | 0.31%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.31%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.29%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 11        | 0.29%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.29%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 11        | 0.29%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.26%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.26%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1727      | 56.04%  |
| DDR3    | 805       | 26.12%  |
| LPDDR4  | 157       | 5.09%   |
| DDR5    | 94        | 3.05%   |
| Unknown | 67        | 2.17%   |
| LPDDR3  | 65        | 2.11%   |
| DDR2    | 56        | 1.82%   |
| LPDDR5  | 51        | 1.65%   |
| SDRAM   | 46        | 1.49%   |
| DDR     | 11        | 0.36%   |
| DRAM    | 3         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1742      | 56.41%  |
| DIMM         | 1032      | 33.42%  |
| Row Of Chips | 279       | 9.03%   |
| Chip         | 15        | 0.49%   |
| Unknown      | 13        | 0.42%   |
| RIMM         | 3         | 0.1%    |
| FB-DIMM      | 3         | 0.1%    |
| DIP          | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1437      | 42.46%  |
| 4096  | 798       | 23.58%  |
| 16384 | 695       | 20.54%  |
| 2048  | 269       | 7.95%   |
| 32768 | 146       | 4.31%   |
| 1024  | 35        | 1.03%   |
| 12288 | 1         | 0.03%   |
| 512   | 1         | 0.03%   |
| 256   | 1         | 0.03%   |
| 128   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 629       | 18.79%  |
| 2667    | 553       | 16.52%  |
| 1600    | 542       | 16.19%  |
| 2400    | 287       | 8.57%   |
| 1333    | 191       | 5.7%    |
| 2133    | 153       | 4.57%   |
| 3600    | 115       | 3.43%   |
| 4267    | 70        | 2.09%   |
| 1334    | 69        | 2.06%   |
| 6400    | 50        | 1.49%   |
| 4800    | 50        | 1.49%   |
| 1867    | 49        | 1.46%   |
| 2666    | 38        | 1.14%   |
| 800     | 37        | 1.11%   |
| 3733    | 33        | 0.99%   |
| 667     | 32        | 0.96%   |
| 3800    | 30        | 0.9%    |
| 3266    | 29        | 0.87%   |
| Unknown | 28        | 0.84%   |
| 3000    | 21        | 0.63%   |
| 2933    | 20        | 0.6%    |
| 1066    | 20        | 0.6%    |
| 5600    | 19        | 0.57%   |
| 3400    | 19        | 0.57%   |
| 1866    | 19        | 0.57%   |
| 3866    | 18        | 0.54%   |
| 1067    | 18        | 0.54%   |
| 6000    | 15        | 0.45%   |
| 8400    | 14        | 0.42%   |
| 1800    | 14        | 0.42%   |
| 4199    | 12        | 0.36%   |
| 4266    | 10        | 0.3%    |
| 3666    | 10        | 0.3%    |
| 3534    | 10        | 0.3%    |
| 3066    | 10        | 0.3%    |
| 400     | 9         | 0.27%   |
| 3333    | 8         | 0.24%   |
| 2800    | 8         | 0.24%   |
| 3466    | 7         | 0.21%   |
| 2048    | 7         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 52        | 37.14%  |
| Brother Industries     | 31        | 22.14%  |
| Seiko Epson            | 15        | 10.71%  |
| Samsung Electronics    | 11        | 7.86%   |
| Canon                  | 11        | 7.86%   |
| Dymo-CoStar            | 3         | 2.14%   |
| Zebra                  | 2         | 1.43%   |
| Xerox                  | 2         | 1.43%   |
| Prolific Technology    | 2         | 1.43%   |
| Pantum                 | 2         | 1.43%   |
| SAT                    | 1         | 0.71%   |
| Ricoh                  | 1         | 0.71%   |
| QinHeng Electronics    | 1         | 0.71%   |
| Panasonic (Matsushita) | 1         | 0.71%   |
| Lexmark International  | 1         | 0.71%   |
| Kyocera                | 1         | 0.71%   |
| ICS Advent             | 1         | 0.71%   |
| Datamax-O'Neil         | 1         | 0.71%   |
| Apple                  | 1         | 0.71%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.11%   |
| Seiko Epson L360 Series                                | 2         | 1.41%   |
| Seiko Epson L3110 Series                               | 2         | 1.41%   |
| Samsung M2070 Series                                   | 2         | 1.41%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.41%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.41%   |
| HP LaserJet P2015 series                               | 2         | 1.41%   |
| HP LaserJet 1020                                       | 2         | 1.41%   |
| HP LaserJet 1018                                       | 2         | 1.41%   |
| HP ENVY 4500 series                                    | 2         | 1.41%   |
| HP DeskJet 2700 series                                 | 2         | 1.41%   |
| HP DeskJet 2600 series                                 | 2         | 1.41%   |
| Brother MFC-J460DW                                     | 2         | 1.41%   |
| Brother HL-L2320D series                               | 2         | 1.41%   |
| Brother HL-2230 series                                 | 2         | 1.41%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.7%    |
| Zebra Thrmal 2844                                      | 1         | 0.7%    |
| Xerox Phaser 6500N                                     | 1         | 0.7%    |
| Xerox Phaser 3140 and 3155                             | 1         | 0.7%    |
| Seiko Epson XP-7100 Series                             | 1         | 0.7%    |
| Seiko Epson XP-3100 Series                             | 1         | 0.7%    |
| Seiko Epson XP-2200 Series                             | 1         | 0.7%    |
| Seiko Epson XP-2100 Series                             | 1         | 0.7%    |
| Seiko Epson WF-2530 Series                             | 1         | 0.7%    |
| Seiko Epson Printer                                    | 1         | 0.7%    |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.7%    |
| Seiko Epson L120 Series                                | 1         | 0.7%    |
| Seiko Epson ET-3830 Series                             | 1         | 0.7%    |
| Seiko Epson ET-2710 Series                             | 1         | 0.7%    |
| Seiko Epson ET-2700 Series                             | 1         | 0.7%    |
| SAT SAT38TUSE                                          | 1         | 0.7%    |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.7%    |
| Samsung SCX-3200 Series                                | 1         | 0.7%    |
| Samsung ML-2250 Series                                 | 1         | 0.7%    |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.7%    |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.7%    |
| Samsung M2020 Series                                   | 1         | 0.7%    |
| Samsung CLX-3180 Series                                | 1         | 0.7%    |
| Samsung CLX-3170 Series                                | 1         | 0.7%    |
| Samsung CLP-360 Series                                 | 1         | 0.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 16        | 51.61%  |
| Seiko Epson     | 9         | 29.03%  |
| Mustek Systems  | 3         | 9.68%   |
| Hewlett-Packard | 3         | 9.68%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 9.68%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 9.68%   |
| Canon CanoScan LiDE 110                                 | 3         | 9.68%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 6.45%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 6.45%   |
| Canon CanoScan LIDE 25                                  | 2         | 6.45%   |
| Canon CanoScan LiDE 220                                 | 2         | 6.45%   |
| Canon CanoScan LiDE 210                                 | 2         | 6.45%   |
| Seiko Epson Perfection 660                              | 1         | 3.23%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.23%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.23%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.23%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.23%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.23%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.23%   |
| HP ScanJet G4010                                        | 1         | 3.23%   |
| HP ScanJet 82x0C                                        | 1         | 3.23%   |
| HP ScanJet 3770                                         | 1         | 3.23%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.23%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 600       | 18.48%  |
| IMC Networks                           | 312       | 9.61%   |
| Microdia                               | 286       | 8.81%   |
| Logitech                               | 246       | 7.58%   |
| Realtek Semiconductor                  | 234       | 7.21%   |
| Quanta                                 | 182       | 5.61%   |
| Bison Electronics                      | 178       | 5.48%   |
| Sunplus Innovation Technology          | 177       | 5.45%   |
| Cheng Uei Precision Industry (Foxlink) | 132       | 4.07%   |
| Acer                                   | 87        | 2.68%   |
| Apple                                  | 76        | 2.34%   |
| Syntek                                 | 67        | 2.06%   |
| Luxvisions Innotech Limited            | 64        | 1.97%   |
| Suyin                                  | 60        | 1.85%   |
| Lite-On Technology                     | 54        | 1.66%   |
| Silicon Motion                         | 47        | 1.45%   |
| Microsoft                              | 41        | 1.26%   |
| Alcor Micro                            | 34        | 1.05%   |
| Samsung Electronics                    | 33        | 1.02%   |
| Sonix Technology                       | 25        | 0.77%   |
| Generalplus Technology                 | 19        | 0.59%   |
| Ricoh                                  | 18        | 0.55%   |
| SunplusIT                              | 16        | 0.49%   |
| Z-Star Microelectronics                | 15        | 0.46%   |
| Lenovo                                 | 14        | 0.43%   |
| MacroSilicon                           | 10        | 0.31%   |
| KYE Systems (Mouse Systems)            | 10        | 0.31%   |
| icSpring                               | 10        | 0.31%   |
| ARC International                      | 9         | 0.28%   |
| Y Media                                | 8         | 0.25%   |
| ShineTech                              | 8         | 0.25%   |
| Razer USA                              | 8         | 0.25%   |
| Genesys Logic                          | 8         | 0.25%   |
| Huawei Technologies                    | 7         | 0.22%   |
| GEMBIRD                                | 7         | 0.22%   |
| Cubeternet                             | 7         | 0.22%   |
| Sunplus Technology                     | 6         | 0.18%   |
| Primax Electronics                     | 6         | 0.18%   |
| Importek                               | 6         | 0.18%   |
| Trust                                  | 5         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 143       | 4.36%   |
| Microdia Integrated_Webcam_HD                                              | 122       | 3.72%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 97        | 2.96%   |
| Realtek Integrated_Webcam_HD                                               | 92        | 2.81%   |
| IMC Networks Integrated Camera                                             | 92        | 2.81%   |
| Sunplus Integrated_Webcam_HD                                               | 69        | 2.11%   |
| Bison Integrated Camera                                                    | 60        | 1.83%   |
| Logitech HD Pro Webcam C920                                                | 52        | 1.59%   |
| Chicony HD WebCam                                                          | 51        | 1.56%   |
| Syntek Integrated Camera                                                   | 49        | 1.5%    |
| Logitech Webcam C270                                                       | 48        | 1.46%   |
| Quanta HD User Facing                                                      | 36        | 1.1%    |
| Chicony HD User Facing                                                     | 35        | 1.07%   |
| Chicony USB2.0 Camera                                                      | 33        | 1.01%   |
| Chicony HP HD Camera                                                       | 33        | 1.01%   |
| Acer Integrated Camera                                                     | 32        | 0.98%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 31        | 0.95%   |
| Bison HD Webcam                                                            | 31        | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 26        | 0.79%   |
| Quanta HP TrueVision HD Camera                                             | 25        | 0.76%   |
| Quanta HP HD Camera                                                        | 25        | 0.76%   |
| Microdia Webcam Vitade AF                                                  | 24        | 0.73%   |
| Microdia Integrated Webcam                                                 | 24        | 0.73%   |
| Realtek USB Camera                                                         | 23        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)                                    | 23        | 0.7%    |
| Microdia USB 2.0 Camera                                                    | 21        | 0.64%   |
| Microdia Integrated_Webcam_FHD                                             | 21        | 0.64%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.61%   |
| Apple FaceTime HD Camera (Built-in)                                        | 20        | 0.61%   |
| Lite-On Integrated Camera                                                  | 19        | 0.58%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 19        | 0.58%   |
| Chicony HP TrueVision HD Camera                                            | 19        | 0.58%   |
| Bison BisonCam,NB Pro                                                      | 19        | 0.58%   |
| IMC Networks HD Camera                                                     | 18        | 0.55%   |
| Chicony HP TrueVision HD                                                   | 18        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 18        | 0.55%   |
| Luxvisions Innotech Limited Integrated Camera                              | 17        | 0.52%   |
| Microsoft LifeCam HD-3000                                                  | 16        | 0.49%   |
| Logitech C922 Pro Stream Webcam                                            | 16        | 0.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 16        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 207       | 32.14%  |
| Validity Sensors                   | 171       | 26.55%  |
| Shenzhen Goodix Technology         | 127       | 19.72%  |
| Elan Microelectronics              | 47        | 7.3%    |
| AuthenTec                          | 27        | 4.19%   |
| Upek                               | 24        | 3.73%   |
| LighTuning Technology              | 23        | 3.57%   |
| STMicroelectronics                 | 6         | 0.93%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.78%   |
| Samsung Electronics                | 2         | 0.31%   |
| Focal-systems.Corp                 | 2         | 0.31%   |
| FocalTech                          | 1         | 0.16%   |
| DigitalPersona                     | 1         | 0.16%   |
| Dell                               | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 75        | 11.65%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 9.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 5.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 34        | 5.28%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.73%   |
| Elan ELAN:Fingerprint                                                      | 24        | 3.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 3.42%   |
| Elan ELAN:ARM-M4                                                           | 21        | 3.26%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 2.95%   |
| Synaptics UWP WBDI                                                         | 19        | 2.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 2.8%    |
| Shenzhen Goodix FingerPrint                                                | 18        | 2.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 15        | 2.33%   |
| Synaptics WBDI                                                             | 14        | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 13        | 2.02%   |
| Synaptics  WBDI                                                            | 12        | 1.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.86%   |
| Validity Sensors VFS491                                                    | 11        | 1.71%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.71%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 1.71%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.4%    |
| AuthenTec AES2810                                                          | 9         | 1.4%    |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.09%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 0.93%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.93%   |
| Synaptics TouchPad                                                         | 6         | 0.93%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.93%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.93%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 5         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 0.78%   |
| Unknown                                                                    | 5         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.62%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 120       | 43.01%  |
| Alcor Micro               | 85        | 30.47%  |
| Upek                      | 14        | 5.02%   |
| O2 Micro                  | 11        | 3.94%   |
| Lenovo                    | 9         | 3.23%   |
| Advanced Card Systems     | 7         | 2.51%   |
| SCM Microsystems          | 4         | 1.43%   |
| Gemalto (was Gemplus)     | 4         | 1.43%   |
| Yubico.com                | 3         | 1.08%   |
| OmniKey                   | 3         | 1.08%   |
| Reiner SCT Kartensysteme  | 2         | 0.72%   |
| Realtek Semiconductor     | 2         | 0.72%   |
| Fujitsu Siemens Computers | 2         | 0.72%   |
| Clay Logic                | 2         | 0.72%   |
| Bit4id                    | 2         | 0.72%   |
| Aladdin R.D.              | 2         | 0.72%   |
| Aladdin Knowledge Systems | 2         | 0.72%   |
| Watchdata                 | 1         | 0.36%   |
| In Focus Systems          | 1         | 0.36%   |
| Giesecke & Devrient       | 1         | 0.36%   |
| Chicony Electronics       | 1         | 0.36%   |
| Aktiv                     | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 29.39%  |
| Broadcom 5880                                                                | 39        | 13.98%  |
| Broadcom 58200                                                               | 33        | 11.83%  |
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 10.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 6.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 5.02%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 3.94%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 3.23%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.43%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.08%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.08%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.08%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.72%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.72%   |
| OmniKey CardMan 1021                                                         | 2         | 0.72%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.72%   |
| Bit4id miniLector EVO                                                        | 2         | 0.72%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.72%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.72%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.72%   |
| Watchdata USB Key                                                            | 1         | 0.36%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.36%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.36%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.36%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.36%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.36%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.36%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.36%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.36%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.36%   |
| Aktiv Rutoken lite                                                           | 1         | 0.36%   |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3440      | 68.57%  |
| 1     | 1279      | 25.49%  |
| 2     | 248       | 4.94%   |
| 3     | 28        | 0.56%   |
| 4     | 10        | 0.2%    |
| 7     | 4         | 0.08%   |
| 6     | 4         | 0.08%   |
| 5     | 3         | 0.06%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 631       | 33.65%  |
| Graphics card            | 310       | 16.53%  |
| Chipcard                 | 243       | 12.96%  |
| Net/wireless             | 221       | 11.79%  |
| Multimedia controller    | 97        | 5.17%   |
| Camera                   | 84        | 4.48%   |
| Bluetooth                | 56        | 2.99%   |
| Sound                    | 55        | 2.93%   |
| Unassigned class         | 43        | 2.29%   |
| Communication controller | 40        | 2.13%   |
| Storage                  | 24        | 1.28%   |
| Card reader              | 23        | 1.23%   |
| Net/ethernet             | 12        | 0.64%   |
| Network                  | 10        | 0.53%   |
| Storage/ide              | 8         | 0.43%   |
| Modem                    | 7         | 0.37%   |
| Firewire controller      | 4         | 0.21%   |
| Storage/raid             | 3         | 0.16%   |
| Dvb card                 | 3         | 0.16%   |
| Storage/nvme             | 1         | 0.05%   |

