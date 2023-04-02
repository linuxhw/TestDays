Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 8436

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0MGK50 A02                  | Desktop     | [3a042b5160](https://linux-hardware.org/?probe=3a042b5160) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | Notebook    | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| MSI           | P43T-C51                    | Desktop     | [d16b44b442](https://linux-hardware.org/?probe=d16b44b442) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [8326806aa6](https://linux-hardware.org/?probe=8326806aa6) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| ASRock        | B550M-C                     | Desktop     | [c0fcfbc0ed](https://linux-hardware.org/?probe=c0fcfbc0ed) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [b62f0eaa0e](https://linux-hardware.org/?probe=b62f0eaa0e) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [29ec74ac8b](https://linux-hardware.org/?probe=29ec74ac8b) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cba16003d7](https://linux-hardware.org/?probe=cba16003d7) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [93b35b776a](https://linux-hardware.org/?probe=93b35b776a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [99da9866a9](https://linux-hardware.org/?probe=99da9866a9) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [be6e8f17cc](https://linux-hardware.org/?probe=be6e8f17cc) | Mar 25, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [d1eea40764](https://linux-hardware.org/?probe=d1eea40764) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [29fce46770](https://linux-hardware.org/?probe=29fce46770) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [a36464850a](https://linux-hardware.org/?probe=a36464850a) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| HP            | Spectre                     | Convertible | [c9181ab4f2](https://linux-hardware.org/?probe=c9181ab4f2) | Mar 22, 2023 |
| HP            | Spectre                     | Convertible | [5e07c68683](https://linux-hardware.org/?probe=5e07c68683) | Mar 22, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [7336ce9057](https://linux-hardware.org/?probe=7336ce9057) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [01e06fb483](https://linux-hardware.org/?probe=01e06fb483) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [7fb5a2f07e](https://linux-hardware.org/?probe=7fb5a2f07e) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [f320bc5964](https://linux-hardware.org/?probe=f320bc5964) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [21de7ff6d5](https://linux-hardware.org/?probe=21de7ff6d5) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f9c84aa26c](https://linux-hardware.org/?probe=f9c84aa26c) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [1854e9efde](https://linux-hardware.org/?probe=1854e9efde) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | Notebook    | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ed76176dfa](https://linux-hardware.org/?probe=ed76176dfa) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [4b484ab326](https://linux-hardware.org/?probe=4b484ab326) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [a721b1b9d6](https://linux-hardware.org/?probe=a721b1b9d6) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | Notebook    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b21fb664f8](https://linux-hardware.org/?probe=b21fb664f8) | Mar 17, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [fff0c55980](https://linux-hardware.org/?probe=fff0c55980) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [538477684f](https://linux-hardware.org/?probe=538477684f) | Mar 17, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1b43670875](https://linux-hardware.org/?probe=1b43670875) | Mar 16, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [062ba6c2b9](https://linux-hardware.org/?probe=062ba6c2b9) | Mar 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [53c02c1bb8](https://linux-hardware.org/?probe=53c02c1bb8) | Mar 16, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [623a5ed92b](https://linux-hardware.org/?probe=623a5ed92b) | Mar 15, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [42baaa40b9](https://linux-hardware.org/?probe=42baaa40b9) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2662a08251](https://linux-hardware.org/?probe=2662a08251) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | Notebook    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| HP            | ProLiant DL380 G4           | Server      | [403a18bfff](https://linux-hardware.org/?probe=403a18bfff) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [aa74d34d26](https://linux-hardware.org/?probe=aa74d34d26) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [12423f96f6](https://linux-hardware.org/?probe=12423f96f6) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [25c6ceb9e8](https://linux-hardware.org/?probe=25c6ceb9e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1e2dd83baa](https://linux-hardware.org/?probe=1e2dd83baa) | Mar 13, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [a7e24ac4b6](https://linux-hardware.org/?probe=a7e24ac4b6) | Mar 13, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7c00691824](https://linux-hardware.org/?probe=7c00691824) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | Notebook    | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| HP            | G61                         | Notebook    | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [f1e983c2dc](https://linux-hardware.org/?probe=f1e983c2dc) | Mar 10, 2023 |
| HP            | 8754                        | Mini pc     | [4913915d6f](https://linux-hardware.org/?probe=4913915d6f) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [9552c8c0ab](https://linux-hardware.org/?probe=9552c8c0ab) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | Notebook    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ceb2734b56](https://linux-hardware.org/?probe=ceb2734b56) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [d45b4c63fa](https://linux-hardware.org/?probe=d45b4c63fa) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [f4e6d8e7a0](https://linux-hardware.org/?probe=f4e6d8e7a0) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [9c59079b1f](https://linux-hardware.org/?probe=9c59079b1f) | Mar 09, 2023 |
| Acer          | Veriton M480                | Desktop     | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| ASUSTek       | H81T                        | Desktop     | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7b405f2925](https://linux-hardware.org/?probe=7b405f2925) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Dell          | Latitude 5590               | Notebook    | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | Notebook    | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [0047dd8b2a](https://linux-hardware.org/?probe=0047dd8b2a) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ca073d764f](https://linux-hardware.org/?probe=ca073d764f) | Mar 06, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [6a7ad331f8](https://linux-hardware.org/?probe=6a7ad331f8) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [6a6864f933](https://linux-hardware.org/?probe=6a6864f933) | Mar 05, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [ea211d74ee](https://linux-hardware.org/?probe=ea211d74ee) | Mar 05, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6f3850aa74](https://linux-hardware.org/?probe=6f3850aa74) | Mar 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [24d58ff4fc](https://linux-hardware.org/?probe=24d58ff4fc) | Mar 05, 2023 |
| HP            | 3397                        | Desktop     | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| MSI           | 970A-G46                    | Desktop     | [804b0fa4da](https://linux-hardware.org/?probe=804b0fa4da) | Mar 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [6181549e93](https://linux-hardware.org/?probe=6181549e93) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| HP            | Spectre                     | Convertible | [8e2fdf7f6b](https://linux-hardware.org/?probe=8e2fdf7f6b) | Mar 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5823762138](https://linux-hardware.org/?probe=5823762138) | Mar 03, 2023 |
| HP            | ENVY dv6                    | Notebook    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e08a9cdac6](https://linux-hardware.org/?probe=e08a9cdac6) | Mar 03, 2023 |
| HP            | 82F2 A01                    | Desktop     | [305779159c](https://linux-hardware.org/?probe=305779159c) | Mar 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [13f585159e](https://linux-hardware.org/?probe=13f585159e) | Mar 02, 2023 |
| DTRI          | DT317CR                     | Notebook    | [b78d90835c](https://linux-hardware.org/?probe=b78d90835c) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [8ac11055c8](https://linux-hardware.org/?probe=8ac11055c8) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [f61c295d09](https://linux-hardware.org/?probe=f61c295d09) | Mar 01, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [0ffe1f9541](https://linux-hardware.org/?probe=0ffe1f9541) | Feb 28, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [5a32d2e162](https://linux-hardware.org/?probe=5a32d2e162) | Feb 28, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [9707436005](https://linux-hardware.org/?probe=9707436005) | Feb 28, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [def987e32c](https://linux-hardware.org/?probe=def987e32c) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec1f27de09](https://linux-hardware.org/?probe=ec1f27de09) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | Notebook    | [1643b96eae](https://linux-hardware.org/?probe=1643b96eae) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | Notebook    | [b48cc99ce3](https://linux-hardware.org/?probe=b48cc99ce3) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [62a7d7ef5c](https://linux-hardware.org/?probe=62a7d7ef5c) | Feb 28, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [2465135444](https://linux-hardware.org/?probe=2465135444) | Feb 28, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [05542207ee](https://linux-hardware.org/?probe=05542207ee) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [d4bcf9b7a2](https://linux-hardware.org/?probe=d4bcf9b7a2) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b5a08d19e9](https://linux-hardware.org/?probe=b5a08d19e9) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ac3b5424a](https://linux-hardware.org/?probe=3ac3b5424a) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [83c075f5c5](https://linux-hardware.org/?probe=83c075f5c5) | Feb 26, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [20bd9411d9](https://linux-hardware.org/?probe=20bd9411d9) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e07445a583](https://linux-hardware.org/?probe=e07445a583) | Feb 25, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [9c1dad9bdc](https://linux-hardware.org/?probe=9c1dad9bdc) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Star Labs     | StarBook                    | Notebook    | [fbd529b953](https://linux-hardware.org/?probe=fbd529b953) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [efdc981614](https://linux-hardware.org/?probe=efdc981614) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [51e3518d50](https://linux-hardware.org/?probe=51e3518d50) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7780f02f45](https://linux-hardware.org/?probe=7780f02f45) | Feb 23, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [82889a28a0](https://linux-hardware.org/?probe=82889a28a0) | Feb 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [c69ac67426](https://linux-hardware.org/?probe=c69ac67426) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [14cf9e07e0](https://linux-hardware.org/?probe=14cf9e07e0) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [388f34d16e](https://linux-hardware.org/?probe=388f34d16e) | Feb 23, 2023 |
| Dell          | Latitude 7300               | Notebook    | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [beb6e53cb7](https://linux-hardware.org/?probe=beb6e53cb7) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [640957cabe](https://linux-hardware.org/?probe=640957cabe) | Feb 23, 2023 |
| HP            | Spectre                     | Convertible | [2366c11489](https://linux-hardware.org/?probe=2366c11489) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [53e8b0db7d](https://linux-hardware.org/?probe=53e8b0db7d) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Compaq        | 430                         | Notebook    | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [dd12dc45d7](https://linux-hardware.org/?probe=dd12dc45d7) | Feb 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f36328511d](https://linux-hardware.org/?probe=f36328511d) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [defde684a0](https://linux-hardware.org/?probe=defde684a0) | Feb 20, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [08d8865fcf](https://linux-hardware.org/?probe=08d8865fcf) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [1832e70d83](https://linux-hardware.org/?probe=1832e70d83) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [9adf6b834b](https://linux-hardware.org/?probe=9adf6b834b) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| AZW           | GK55                        | Desktop     | [e8376dbc54](https://linux-hardware.org/?probe=e8376dbc54) | Feb 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [0f1365d8d8](https://linux-hardware.org/?probe=0f1365d8d8) | Feb 19, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82fd276e35](https://linux-hardware.org/?probe=82fd276e35) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f8f6e2baea](https://linux-hardware.org/?probe=f8f6e2baea) | Feb 19, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6aae20aa14](https://linux-hardware.org/?probe=6aae20aa14) | Feb 18, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [61befa2690](https://linux-hardware.org/?probe=61befa2690) | Feb 18, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [be751c4a5b](https://linux-hardware.org/?probe=be751c4a5b) | Feb 18, 2023 |
| Google        | Celes                       | Notebook    | [3004fce0ed](https://linux-hardware.org/?probe=3004fce0ed) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d0bb58e003](https://linux-hardware.org/?probe=d0bb58e003) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [322588bc4e](https://linux-hardware.org/?probe=322588bc4e) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d770ba8b7b](https://linux-hardware.org/?probe=d770ba8b7b) | Feb 17, 2023 |
| Gateway       | SX2803                      | Desktop     | [a1b20489b4](https://linux-hardware.org/?probe=a1b20489b4) | Feb 17, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4948ea8836](https://linux-hardware.org/?probe=4948ea8836) | Feb 17, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [a9d6ae7b72](https://linux-hardware.org/?probe=a9d6ae7b72) | Feb 17, 2023 |
| HP            | 18E7                        | Desktop     | [821ea2c921](https://linux-hardware.org/?probe=821ea2c921) | Feb 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [065827a397](https://linux-hardware.org/?probe=065827a397) | Feb 16, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [fd678baa9f](https://linux-hardware.org/?probe=fd678baa9f) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| ASRock        | Z390M Pro4                  | Desktop     | [cf96b55907](https://linux-hardware.org/?probe=cf96b55907) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e1d323e96f](https://linux-hardware.org/?probe=e1d323e96f) | Feb 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [987c9b1854](https://linux-hardware.org/?probe=987c9b1854) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [77e13c5748](https://linux-hardware.org/?probe=77e13c5748) | Feb 14, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [dd2017324e](https://linux-hardware.org/?probe=dd2017324e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [dc352cd9dc](https://linux-hardware.org/?probe=dc352cd9dc) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [6e5eacb53a](https://linux-hardware.org/?probe=6e5eacb53a) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d1171fb67b](https://linux-hardware.org/?probe=d1171fb67b) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E6530              | Notebook    | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [cd29998b19](https://linux-hardware.org/?probe=cd29998b19) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [b3ab77c355](https://linux-hardware.org/?probe=b3ab77c355) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [37c223623f](https://linux-hardware.org/?probe=37c223623f) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [8ac5b193cb](https://linux-hardware.org/?probe=8ac5b193cb) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [156fae6b82](https://linux-hardware.org/?probe=156fae6b82) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f5ef3d92cb](https://linux-hardware.org/?probe=f5ef3d92cb) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [27411524db](https://linux-hardware.org/?probe=27411524db) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [afb25c8733](https://linux-hardware.org/?probe=afb25c8733) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [35d68b3769](https://linux-hardware.org/?probe=35d68b3769) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [5335da53d0](https://linux-hardware.org/?probe=5335da53d0) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| Samsung       | 767XCL                      | Notebook    | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f2deee99d1](https://linux-hardware.org/?probe=f2deee99d1) | Feb 11, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [ca7e69040a](https://linux-hardware.org/?probe=ca7e69040a) | Feb 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [30965e948d](https://linux-hardware.org/?probe=30965e948d) | Feb 10, 2023 |
| Dell          | 04YJ19 A00                  | Desktop     | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [cb3ab0bbf5](https://linux-hardware.org/?probe=cb3ab0bbf5) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [132d55b2ed](https://linux-hardware.org/?probe=132d55b2ed) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | Notebook    | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [fc292cd441](https://linux-hardware.org/?probe=fc292cd441) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [af3d5cd04c](https://linux-hardware.org/?probe=af3d5cd04c) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [02b69364a6](https://linux-hardware.org/?probe=02b69364a6) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [83efc68bd7](https://linux-hardware.org/?probe=83efc68bd7) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cdfbd3e72a](https://linux-hardware.org/?probe=cdfbd3e72a) | Feb 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [58346a45de](https://linux-hardware.org/?probe=58346a45de) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [e533f4d15f](https://linux-hardware.org/?probe=e533f4d15f) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e0634fdc6e](https://linux-hardware.org/?probe=e0634fdc6e) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [577d1f97d8](https://linux-hardware.org/?probe=577d1f97d8) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [2b7b643f2e](https://linux-hardware.org/?probe=2b7b643f2e) | Feb 08, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [0e174666ba](https://linux-hardware.org/?probe=0e174666ba) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [a127a79277](https://linux-hardware.org/?probe=a127a79277) | Feb 07, 2023 |
| Dell          | Precision M4800             | Notebook    | [2572c61169](https://linux-hardware.org/?probe=2572c61169) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [6e7434a708](https://linux-hardware.org/?probe=6e7434a708) | Feb 07, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [3be676928d](https://linux-hardware.org/?probe=3be676928d) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01872da4ea](https://linux-hardware.org/?probe=01872da4ea) | Feb 07, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b666459988](https://linux-hardware.org/?probe=b666459988) | Feb 06, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [dee03d9aff](https://linux-hardware.org/?probe=dee03d9aff) | Feb 06, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [149a2716a8](https://linux-hardware.org/?probe=149a2716a8) | Feb 06, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [3e487446eb](https://linux-hardware.org/?probe=3e487446eb) | Feb 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [31e2c2f5e1](https://linux-hardware.org/?probe=31e2c2f5e1) | Feb 06, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [a0b1f2a7b4](https://linux-hardware.org/?probe=a0b1f2a7b4) | Feb 06, 2023 |
| Toshiba       | Satellite Pro L510          | Notebook    | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [f91035a72a](https://linux-hardware.org/?probe=f91035a72a) | Feb 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [bdd3224e6c](https://linux-hardware.org/?probe=bdd3224e6c) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | Notebook    | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [44c671bfa6](https://linux-hardware.org/?probe=44c671bfa6) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [79548473df](https://linux-hardware.org/?probe=79548473df) | Feb 05, 2023 |
| Unknown       | X79A                        | Desktop     | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [42d855f568](https://linux-hardware.org/?probe=42d855f568) | Feb 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [a3b4edbfd9](https://linux-hardware.org/?probe=a3b4edbfd9) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [b9b0a6cccb](https://linux-hardware.org/?probe=b9b0a6cccb) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [d82820c304](https://linux-hardware.org/?probe=d82820c304) | Feb 04, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [2594dddd54](https://linux-hardware.org/?probe=2594dddd54) | Feb 04, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| Medion        | S17405                      | Notebook    | [85cdfa1290](https://linux-hardware.org/?probe=85cdfa1290) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| MSI           | GE63 Raider RGB 9SE         | Notebook    | [b7ec016843](https://linux-hardware.org/?probe=b7ec016843) | Feb 02, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [7c6794cc63](https://linux-hardware.org/?probe=7c6794cc63) | Feb 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [82845bb849](https://linux-hardware.org/?probe=82845bb849) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [1fddf279a5](https://linux-hardware.org/?probe=1fddf279a5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | Notebook    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [981bcc29a7](https://linux-hardware.org/?probe=981bcc29a7) | Feb 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [1dbacce612](https://linux-hardware.org/?probe=1dbacce612) | Feb 01, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [caa1c9e23a](https://linux-hardware.org/?probe=caa1c9e23a) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Dell          | 0J1C3P A00                  | Desktop     | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | Desktop     | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [7893a67a4b](https://linux-hardware.org/?probe=7893a67a4b) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [b88f08d400](https://linux-hardware.org/?probe=b88f08d400) | Jan 29, 2023 |
| Dell          | G15 5520                    | Notebook    | [ae4bf1777e](https://linux-hardware.org/?probe=ae4bf1777e) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [77c9cc065f](https://linux-hardware.org/?probe=77c9cc065f) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [1ddc17833b](https://linux-hardware.org/?probe=1ddc17833b) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8727d22cba](https://linux-hardware.org/?probe=8727d22cba) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [97aa61aba5](https://linux-hardware.org/?probe=97aa61aba5) | Jan 29, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [4603f92b18](https://linux-hardware.org/?probe=4603f92b18) | Jan 29, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [b9a38b7494](https://linux-hardware.org/?probe=b9a38b7494) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [608c0b8c88](https://linux-hardware.org/?probe=608c0b8c88) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| Dell          | G15 5520                    | Notebook    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [bf09bd7413](https://linux-hardware.org/?probe=bf09bd7413) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [85e23fef85](https://linux-hardware.org/?probe=85e23fef85) | Jan 28, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7961073f5f](https://linux-hardware.org/?probe=7961073f5f) | Jan 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [ece518ec34](https://linux-hardware.org/?probe=ece518ec34) | Jan 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [40672aba71](https://linux-hardware.org/?probe=40672aba71) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [ff67a5eb33](https://linux-hardware.org/?probe=ff67a5eb33) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [9912417dc3](https://linux-hardware.org/?probe=9912417dc3) | Jan 27, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [3eb9131ab1](https://linux-hardware.org/?probe=3eb9131ab1) | Jan 27, 2023 |
| HP            | 8054                        | Desktop     | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4109360c56](https://linux-hardware.org/?probe=4109360c56) | Jan 26, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Dell          | G3 3500                     | Notebook    | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [4ad0b3594f](https://linux-hardware.org/?probe=4ad0b3594f) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [4a3c63f3f0](https://linux-hardware.org/?probe=4a3c63f3f0) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2026175299](https://linux-hardware.org/?probe=2026175299) | Jan 26, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3fbe56012b](https://linux-hardware.org/?probe=3fbe56012b) | Jan 25, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [702b3c77fc](https://linux-hardware.org/?probe=702b3c77fc) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [5258f49771](https://linux-hardware.org/?probe=5258f49771) | Jan 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [270a9bf553](https://linux-hardware.org/?probe=270a9bf553) | Jan 24, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [647c279ad4](https://linux-hardware.org/?probe=647c279ad4) | Jan 24, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [f3fb4632c2](https://linux-hardware.org/?probe=f3fb4632c2) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| HP            | ZBook x2 G4                 | Tablet      | [f2799f616c](https://linux-hardware.org/?probe=f2799f616c) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| HP            | 2B2C                        | Desktop     | [01cb4bc77f](https://linux-hardware.org/?probe=01cb4bc77f) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Lenovo        | ThinkPad L430 2466DS2       | Notebook    | [8be9a889b7](https://linux-hardware.org/?probe=8be9a889b7) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [15b2f3fc5e](https://linux-hardware.org/?probe=15b2f3fc5e) | Jan 22, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [77a744c052](https://linux-hardware.org/?probe=77a744c052) | Jan 22, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cd1f6d8306](https://linux-hardware.org/?probe=cd1f6d8306) | Jan 21, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [45bc9c5f3f](https://linux-hardware.org/?probe=45bc9c5f3f) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4591be73d](https://linux-hardware.org/?probe=b4591be73d) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f33b08f626](https://linux-hardware.org/?probe=f33b08f626) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [0f0f1ed390](https://linux-hardware.org/?probe=0f0f1ed390) | Jan 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b6b4b01344](https://linux-hardware.org/?probe=b6b4b01344) | Jan 20, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [cf6837bb85](https://linux-hardware.org/?probe=cf6837bb85) | Jan 20, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [1de254a697](https://linux-hardware.org/?probe=1de254a697) | Jan 20, 2023 |
| Dell          | G3 3579                     | Notebook    | [d418b797c8](https://linux-hardware.org/?probe=d418b797c8) | Jan 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| HP            | 1000                        | Notebook    | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [065167a01c](https://linux-hardware.org/?probe=065167a01c) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [3eb4809e32](https://linux-hardware.org/?probe=3eb4809e32) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0c77a64f45](https://linux-hardware.org/?probe=0c77a64f45) | Jan 18, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [457c3d4d50](https://linux-hardware.org/?probe=457c3d4d50) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [cda19bda99](https://linux-hardware.org/?probe=cda19bda99) | Jan 18, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c0667c5ea5](https://linux-hardware.org/?probe=c0667c5ea5) | Jan 18, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [095355c9fc](https://linux-hardware.org/?probe=095355c9fc) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [987dcf118c](https://linux-hardware.org/?probe=987dcf118c) | Jan 17, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [269015d6a4](https://linux-hardware.org/?probe=269015d6a4) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [a5ddfa16b9](https://linux-hardware.org/?probe=a5ddfa16b9) | Jan 17, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [4c9bb70ea2](https://linux-hardware.org/?probe=4c9bb70ea2) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Foxconn       | nT-i2000 Series PCB         | Desktop     | [a879fdd461](https://linux-hardware.org/?probe=a879fdd461) | Jan 15, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [bd3c9aa4fd](https://linux-hardware.org/?probe=bd3c9aa4fd) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | Notebook    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f5246578fe](https://linux-hardware.org/?probe=f5246578fe) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [77adbc7487](https://linux-hardware.org/?probe=77adbc7487) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [e430030b47](https://linux-hardware.org/?probe=e430030b47) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8fbf586d24](https://linux-hardware.org/?probe=8fbf586d24) | Jan 14, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3365f7d56f](https://linux-hardware.org/?probe=3365f7d56f) | Jan 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [5de8333ea3](https://linux-hardware.org/?probe=5de8333ea3) | Jan 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5fb8523c7](https://linux-hardware.org/?probe=d5fb8523c7) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Dell          | Latitude E6430              | Notebook    | [5951bc10ca](https://linux-hardware.org/?probe=5951bc10ca) | Jan 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [32479ec724](https://linux-hardware.org/?probe=32479ec724) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [25a1763f73](https://linux-hardware.org/?probe=25a1763f73) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8322c3202b](https://linux-hardware.org/?probe=8322c3202b) | Jan 12, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [855dfb5e62](https://linux-hardware.org/?probe=855dfb5e62) | Jan 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [998a408a04](https://linux-hardware.org/?probe=998a408a04) | Jan 12, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Nvidia        | AN-M2                       | Desktop     | [8a7aad3266](https://linux-hardware.org/?probe=8a7aad3266) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | Desktop     | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [bbcffca1e1](https://linux-hardware.org/?probe=bbcffca1e1) | Jan 11, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [54711252e5](https://linux-hardware.org/?probe=54711252e5) | Jan 11, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [2c317eaef8](https://linux-hardware.org/?probe=2c317eaef8) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a1e541c1b3](https://linux-hardware.org/?probe=a1e541c1b3) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [b5d071346b](https://linux-hardware.org/?probe=b5d071346b) | Jan 11, 2023 |
| HP            | 8767 A                      | Desktop     | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a57b3e3df6](https://linux-hardware.org/?probe=a57b3e3df6) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [694c5c31f9](https://linux-hardware.org/?probe=694c5c31f9) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [47ac5c5ee1](https://linux-hardware.org/?probe=47ac5c5ee1) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8e857e93de](https://linux-hardware.org/?probe=8e857e93de) | Jan 10, 2023 |
| Dell          | Latitude 3570               | Notebook    | [2748121a05](https://linux-hardware.org/?probe=2748121a05) | Jan 10, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [1ec26d7d15](https://linux-hardware.org/?probe=1ec26d7d15) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [7193f85a8c](https://linux-hardware.org/?probe=7193f85a8c) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8f9cd3c097](https://linux-hardware.org/?probe=8f9cd3c097) | Jan 09, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [0db2c1a27c](https://linux-hardware.org/?probe=0db2c1a27c) | Jan 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9bf425bc2d](https://linux-hardware.org/?probe=9bf425bc2d) | Jan 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [153884836e](https://linux-hardware.org/?probe=153884836e) | Jan 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [06f9209282](https://linux-hardware.org/?probe=06f9209282) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b6e56e8d87](https://linux-hardware.org/?probe=b6e56e8d87) | Jan 08, 2023 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [66ba6bf6d3](https://linux-hardware.org/?probe=66ba6bf6d3) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7a02a3b48b](https://linux-hardware.org/?probe=7a02a3b48b) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [faf4eff378](https://linux-hardware.org/?probe=faf4eff378) | Jan 08, 2023 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [e7b268e7e5](https://linux-hardware.org/?probe=e7b268e7e5) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a885b118ab](https://linux-hardware.org/?probe=a885b118ab) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27c42e99db](https://linux-hardware.org/?probe=27c42e99db) | Jan 08, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [4d780d6bf9](https://linux-hardware.org/?probe=4d780d6bf9) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [cfabe67812](https://linux-hardware.org/?probe=cfabe67812) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ddae48cdbb](https://linux-hardware.org/?probe=ddae48cdbb) | Jan 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8b38f9336f](https://linux-hardware.org/?probe=8b38f9336f) | Jan 07, 2023 |
| HP            | ZBook 15                    | Notebook    | [3e2f33f6c1](https://linux-hardware.org/?probe=3e2f33f6c1) | Jan 07, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [3b8a41b7af](https://linux-hardware.org/?probe=3b8a41b7af) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7a2744ca03](https://linux-hardware.org/?probe=7a2744ca03) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6cd2288696](https://linux-hardware.org/?probe=6cd2288696) | Jan 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ed168f4e29](https://linux-hardware.org/?probe=ed168f4e29) | Jan 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a2a0663674](https://linux-hardware.org/?probe=a2a0663674) | Jan 05, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| Acer          | IPMBW-BR                    | All in one  | [1485ad36a9](https://linux-hardware.org/?probe=1485ad36a9) | Jan 05, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [cf98b88234](https://linux-hardware.org/?probe=cf98b88234) | Jan 05, 2023 |
| Gigabyte      | AERO 16 XE4                 | Notebook    | [e05dd3f797](https://linux-hardware.org/?probe=e05dd3f797) | Jan 05, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [584234b202](https://linux-hardware.org/?probe=584234b202) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [63f0536a21](https://linux-hardware.org/?probe=63f0536a21) | Jan 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [e7e5475978](https://linux-hardware.org/?probe=e7e5475978) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Lenovo        | ThinkPad X230 2320LFG       | Notebook    | [e8e510f4e6](https://linux-hardware.org/?probe=e8e510f4e6) | Jan 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [5b13eb0dad](https://linux-hardware.org/?probe=5b13eb0dad) | Jan 04, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5b2857e18b](https://linux-hardware.org/?probe=5b2857e18b) | Jan 04, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [f30031a156](https://linux-hardware.org/?probe=f30031a156) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [9012a42d6e](https://linux-hardware.org/?probe=9012a42d6e) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | Notebook    | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [25d993017e](https://linux-hardware.org/?probe=25d993017e) | Jan 02, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| HP            | ProBook 635 Aero G8         | Notebook    | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [a795f33f7a](https://linux-hardware.org/?probe=a795f33f7a) | Jan 02, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [1296e73b50](https://linux-hardware.org/?probe=1296e73b50) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [acdb8c643e](https://linux-hardware.org/?probe=acdb8c643e) | Jan 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [18d10ee7ac](https://linux-hardware.org/?probe=18d10ee7ac) | Jan 01, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [30abdaa93b](https://linux-hardware.org/?probe=30abdaa93b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a6540a8761](https://linux-hardware.org/?probe=a6540a8761) | Jan 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [0db2db0d47](https://linux-hardware.org/?probe=0db2db0d47) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [162ad451eb](https://linux-hardware.org/?probe=162ad451eb) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea3b140a7f](https://linux-hardware.org/?probe=ea3b140a7f) | Dec 31, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Dell          | Latitude 3420               | Notebook    | [05095533cd](https://linux-hardware.org/?probe=05095533cd) | Dec 31, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [fc2f55c02e](https://linux-hardware.org/?probe=fc2f55c02e) | Dec 31, 2022 |
| Dell          | G3 3579                     | Notebook    | [cad48f0160](https://linux-hardware.org/?probe=cad48f0160) | Dec 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [83810bf0a9](https://linux-hardware.org/?probe=83810bf0a9) | Dec 30, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [eab8778810](https://linux-hardware.org/?probe=eab8778810) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4409746122](https://linux-hardware.org/?probe=4409746122) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [da9b785d2a](https://linux-hardware.org/?probe=da9b785d2a) | Dec 30, 2022 |
| ASRock        | B650M PG Riptide            | Desktop     | [614e6307eb](https://linux-hardware.org/?probe=614e6307eb) | Dec 29, 2022 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e6ac6cac6c](https://linux-hardware.org/?probe=e6ac6cac6c) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | Notebook    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1219225d5d](https://linux-hardware.org/?probe=1219225d5d) | Dec 28, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0382c36a9d](https://linux-hardware.org/?probe=0382c36a9d) | Dec 28, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a42da327a2](https://linux-hardware.org/?probe=a42da327a2) | Dec 28, 2022 |
| System76      | Darter Pro                  | Notebook    | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | Notebook    | [a86fddc0b9](https://linux-hardware.org/?probe=a86fddc0b9) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b9fd8381a4](https://linux-hardware.org/?probe=b9fd8381a4) | Dec 27, 2022 |
| MouseCompu... | BC-MB1485UD11A-191          | Convertible | [b24a434561](https://linux-hardware.org/?probe=b24a434561) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | Desktop     | [8658fa0fa3](https://linux-hardware.org/?probe=8658fa0fa3) | Dec 27, 2022 |
| Dell          | 0YDJK3 A02                  | Server      | [83c3b04914](https://linux-hardware.org/?probe=83c3b04914) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [bef58a2317](https://linux-hardware.org/?probe=bef58a2317) | Dec 26, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | 2B29                        | Desktop     | [b83d4fafa0](https://linux-hardware.org/?probe=b83d4fafa0) | Dec 26, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [9fb13764cc](https://linux-hardware.org/?probe=9fb13764cc) | Dec 26, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8ca73d6b87](https://linux-hardware.org/?probe=8ca73d6b87) | Dec 26, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [6e3d39b4ae](https://linux-hardware.org/?probe=6e3d39b4ae) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| Biostar       | AM1MHP                      | Desktop     | [a4c61d5381](https://linux-hardware.org/?probe=a4c61d5381) | Dec 25, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8a1cb3f5e7](https://linux-hardware.org/?probe=8a1cb3f5e7) | Dec 25, 2022 |
| MSI           | 970A-G46                    | Desktop     | [4b2435b250](https://linux-hardware.org/?probe=4b2435b250) | Dec 25, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8bfc8d2560](https://linux-hardware.org/?probe=8bfc8d2560) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [457612540c](https://linux-hardware.org/?probe=457612540c) | Dec 24, 2022 |
| Gigabyte      | AX370-Gaming-CF             | Desktop     | [4770daed30](https://linux-hardware.org/?probe=4770daed30) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1ae154433a](https://linux-hardware.org/?probe=1ae154433a) | Dec 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [52edc0816c](https://linux-hardware.org/?probe=52edc0816c) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| Google        | Babytiger                   | Notebook    | [352d1a547b](https://linux-hardware.org/?probe=352d1a547b) | Dec 23, 2022 |
| Google        | Babytiger                   | Notebook    | [4b2ae6579f](https://linux-hardware.org/?probe=4b2ae6579f) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0246231a61](https://linux-hardware.org/?probe=0246231a61) | Dec 22, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [83436ff428](https://linux-hardware.org/?probe=83436ff428) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [0ee0790d0a](https://linux-hardware.org/?probe=0ee0790d0a) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c2dd6d0281](https://linux-hardware.org/?probe=c2dd6d0281) | Dec 22, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [90f9fb28f8](https://linux-hardware.org/?probe=90f9fb28f8) | Dec 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [74f0c818d6](https://linux-hardware.org/?probe=74f0c818d6) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [768834619c](https://linux-hardware.org/?probe=768834619c) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [95b8e650ce](https://linux-hardware.org/?probe=95b8e650ce) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [5262e622da](https://linux-hardware.org/?probe=5262e622da) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3f3d7ab961](https://linux-hardware.org/?probe=3f3d7ab961) | Dec 21, 2022 |
| Dell          | 0YDJK3 A02                  | Server      | [8b7f633e4c](https://linux-hardware.org/?probe=8b7f633e4c) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | Notebook    | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [487d7751d8](https://linux-hardware.org/?probe=487d7751d8) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | Notebook    | [cd16c6fb41](https://linux-hardware.org/?probe=cd16c6fb41) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [593cdd8cf6](https://linux-hardware.org/?probe=593cdd8cf6) | Dec 19, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [70b20b876e](https://linux-hardware.org/?probe=70b20b876e) | Dec 19, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| Alienware     | x14                         | Notebook    | [d965b3510e](https://linux-hardware.org/?probe=d965b3510e) | Dec 19, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [afcae667f0](https://linux-hardware.org/?probe=afcae667f0) | Dec 19, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [17618a8281](https://linux-hardware.org/?probe=17618a8281) | Dec 18, 2022 |
| HP            | 85BA 00100                  | All in one  | [a67c97653f](https://linux-hardware.org/?probe=a67c97653f) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8d21cb0063](https://linux-hardware.org/?probe=8d21cb0063) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [4760b50d21](https://linux-hardware.org/?probe=4760b50d21) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7964862f29](https://linux-hardware.org/?probe=7964862f29) | Dec 18, 2022 |
| Intel         | H55                         | Desktop     | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43d229d12e](https://linux-hardware.org/?probe=43d229d12e) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a8936bc5e3](https://linux-hardware.org/?probe=a8936bc5e3) | Dec 17, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [b0f674ae6f](https://linux-hardware.org/?probe=b0f674ae6f) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f9f06d0bcb](https://linux-hardware.org/?probe=f9f06d0bcb) | Dec 17, 2022 |
| Gigabyte      | G5 KE                       | Notebook    | [9ff3d65e35](https://linux-hardware.org/?probe=9ff3d65e35) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5f8287cae9](https://linux-hardware.org/?probe=5f8287cae9) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [d37c2f05fd](https://linux-hardware.org/?probe=d37c2f05fd) | Dec 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [87b21382ec](https://linux-hardware.org/?probe=87b21382ec) | Dec 17, 2022 |
| HP            | 83EE                        | Desktop     | [a008cde5ae](https://linux-hardware.org/?probe=a008cde5ae) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [9768b1fe82](https://linux-hardware.org/?probe=9768b1fe82) | Dec 16, 2022 |
| Dell          | Precision 5570              | Notebook    | [9468beba51](https://linux-hardware.org/?probe=9468beba51) | Dec 16, 2022 |
| HP            | Laptop 15-dw4xxx            | Notebook    | [ac9c6384ca](https://linux-hardware.org/?probe=ac9c6384ca) | Dec 16, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [6d51ea5c76](https://linux-hardware.org/?probe=6d51ea5c76) | Dec 16, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [bf511c3913](https://linux-hardware.org/?probe=bf511c3913) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [de15eb8246](https://linux-hardware.org/?probe=de15eb8246) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [302dc680df](https://linux-hardware.org/?probe=302dc680df) | Dec 16, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [18b9f94390](https://linux-hardware.org/?probe=18b9f94390) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [d289646ec3](https://linux-hardware.org/?probe=d289646ec3) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | Notebook    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [62395615bf](https://linux-hardware.org/?probe=62395615bf) | Dec 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2495c6742d](https://linux-hardware.org/?probe=2495c6742d) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7ea1bad26b](https://linux-hardware.org/?probe=7ea1bad26b) | Dec 15, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [82d5ee3bbe](https://linux-hardware.org/?probe=82d5ee3bbe) | Dec 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [eace53ab64](https://linux-hardware.org/?probe=eace53ab64) | Dec 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Dell          | Latitude 5490               | Notebook    | [d05d57e241](https://linux-hardware.org/?probe=d05d57e241) | Dec 14, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a2fc1288f1](https://linux-hardware.org/?probe=a2fc1288f1) | Dec 14, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [baa0f26af0](https://linux-hardware.org/?probe=baa0f26af0) | Dec 13, 2022 |
| Samsung       | 730QED                      | Convertible | [b2c224e73a](https://linux-hardware.org/?probe=b2c224e73a) | Dec 13, 2022 |
| Samsung       | 730QAA                      | Convertible | [3c97d3d801](https://linux-hardware.org/?probe=3c97d3d801) | Dec 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [869c239d63](https://linux-hardware.org/?probe=869c239d63) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [40cf8dd049](https://linux-hardware.org/?probe=40cf8dd049) | Dec 12, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [304bad9c19](https://linux-hardware.org/?probe=304bad9c19) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [1461a09931](https://linux-hardware.org/?probe=1461a09931) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | Notebook    | [f8dae62b0c](https://linux-hardware.org/?probe=f8dae62b0c) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| Sony          | VPCEB3D4R                   | Notebook    | [5f85b7c516](https://linux-hardware.org/?probe=5f85b7c516) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| ZOTAC         | ZBOX-ID42-BE                | Mini pc     | [98600510bf](https://linux-hardware.org/?probe=98600510bf) | Dec 11, 2022 |
| MSI           | Modern 14 B11MOU            | Notebook    | [ec8ac9bbd7](https://linux-hardware.org/?probe=ec8ac9bbd7) | Dec 11, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [811092647b](https://linux-hardware.org/?probe=811092647b) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [3ba8e00e00](https://linux-hardware.org/?probe=3ba8e00e00) | Dec 11, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [eb171830a5](https://linux-hardware.org/?probe=eb171830a5) | Dec 11, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [b73060ce38](https://linux-hardware.org/?probe=b73060ce38) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5073afb493](https://linux-hardware.org/?probe=5073afb493) | Dec 10, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [92d1403bdf](https://linux-hardware.org/?probe=92d1403bdf) | Dec 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [a933e298c7](https://linux-hardware.org/?probe=a933e298c7) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [0e7dd9fbdb](https://linux-hardware.org/?probe=0e7dd9fbdb) | Dec 10, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Acer          | Swift SFX16-52G             | Notebook    | [02a7a5e487](https://linux-hardware.org/?probe=02a7a5e487) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [93934b74f5](https://linux-hardware.org/?probe=93934b74f5) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a6f72ec4e3](https://linux-hardware.org/?probe=a6f72ec4e3) | Dec 09, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [b9e3c45caa](https://linux-hardware.org/?probe=b9e3c45caa) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [6af7fadd72](https://linux-hardware.org/?probe=6af7fadd72) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [7e1510d6c6](https://linux-hardware.org/?probe=7e1510d6c6) | Dec 09, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b822420d6d](https://linux-hardware.org/?probe=b822420d6d) | Dec 09, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [82fdec2637](https://linux-hardware.org/?probe=82fdec2637) | Dec 09, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5e58e0fc36](https://linux-hardware.org/?probe=5e58e0fc36) | Dec 08, 2022 |
| Dell          | Latitude 3400               | Notebook    | [d01726a4d0](https://linux-hardware.org/?probe=d01726a4d0) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8924598f09](https://linux-hardware.org/?probe=8924598f09) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | Notebook    | [426e23829e](https://linux-hardware.org/?probe=426e23829e) | Dec 08, 2022 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [cb45484bb6](https://linux-hardware.org/?probe=cb45484bb6) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | Notebook    | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| MSI           | Modern 14 B11MOU            | Notebook    | [49e70cf65f](https://linux-hardware.org/?probe=49e70cf65f) | Dec 07, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [8575adb47e](https://linux-hardware.org/?probe=8575adb47e) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [7ac17baea3](https://linux-hardware.org/?probe=7ac17baea3) | Dec 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [383bc11a0d](https://linux-hardware.org/?probe=383bc11a0d) | Dec 07, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5b4cf72d01](https://linux-hardware.org/?probe=5b4cf72d01) | Dec 07, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [def749869a](https://linux-hardware.org/?probe=def749869a) | Dec 07, 2022 |
| Acer          | Aspire R5-571T              | Convertible | [1530922d4f](https://linux-hardware.org/?probe=1530922d4f) | Dec 06, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [1ca8a161fd](https://linux-hardware.org/?probe=1ca8a161fd) | Dec 06, 2022 |
| Acer          | Aspire R5-571T              | Convertible | [12160f0234](https://linux-hardware.org/?probe=12160f0234) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [db1a2c7a74](https://linux-hardware.org/?probe=db1a2c7a74) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6ae5470891](https://linux-hardware.org/?probe=6ae5470891) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| HP            | ProBook 6560b               | Notebook    | [a73750fc79](https://linux-hardware.org/?probe=a73750fc79) | Dec 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2ddb168532](https://linux-hardware.org/?probe=2ddb168532) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [76ce7610ea](https://linux-hardware.org/?probe=76ce7610ea) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [0574aeace9](https://linux-hardware.org/?probe=0574aeace9) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | Notebook    | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| Dell          | 0NNFGG A00                  | Desktop     | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d081f85083](https://linux-hardware.org/?probe=d081f85083) | Dec 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch Rolling     | 3019      | 50.1%   |
| Arch             | 2983      | 49.5%   |
| Arch V20.4.11    | 3         | 0.05%   |
| Arch V19.11.3    | 3         | 0.05%   |
| Arch V20.5.7     | 2         | 0.03%   |
| Arch V20.3.4     | 2         | 0.03%   |
| Arch V19.04.4    | 2         | 0.03%   |
| Arch Workstation | 1         | 0.02%   |
| Arch V6.9.2      | 1         | 0.02%   |
| Arch V19.09.1    | 1         | 0.02%   |
| Arch V19.07.9    | 1         | 0.02%   |
| Arch V19.07.11   | 1         | 0.02%   |
| Arch V19.06.1    | 1         | 0.02%   |
| Arch V19.05.2    | 1         | 0.02%   |
| Arch V19.01.4    | 1         | 0.02%   |
| Arch Breaking    | 1         | 0.02%   |
| Arch 2020.09.05  | 1         | 0.02%   |
| Arch 20.08.3     | 1         | 0.02%   |
| Arch 2.7         | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 5859      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.22%   |
| 6.0.2-arch1-1   | 71        | 1.02%   |
| 5.8.5-arch1-1   | 70        | 1.01%   |
| 5.9.14-arch1-1  | 61        | 0.88%   |
| 5.9.1-arch1-1   | 60        | 0.86%   |
| 5.17.5-arch1-1  | 53        | 0.76%   |
| 5.17.9-arch1-1  | 51        | 0.73%   |
| 5.8.12-arch1-1  | 48        | 0.69%   |
| 5.8.10-arch1-1  | 48        | 0.69%   |
| 5.8.14-arch1-1  | 47        | 0.68%   |
| 5.7.12-arch1-1  | 46        | 0.66%   |
| 5.13.13-arch1-1 | 45        | 0.65%   |
| 6.1.1-arch1-1   | 44        | 0.63%   |
| 5.8.1-arch1-1   | 43        | 0.62%   |
| 6.0.9-arch1-1   | 42        | 0.61%   |
| 5.11.16-arch1-1 | 42        | 0.61%   |
| 6.0.12-arch1-1  | 41        | 0.59%   |
| 6.1.12-arch1-1  | 37        | 0.53%   |
| 5.6.15-arch1-1  | 37        | 0.53%   |
| 5.18.16-arch1-1 | 34        | 0.49%   |
| 5.11.6-arch1-1  | 34        | 0.49%   |
| 5.11.11-arch1-1 | 34        | 0.49%   |
| 6.2.8-arch1-1   | 33        | 0.48%   |
| 5.12.15-arch1-1 | 33        | 0.48%   |
| 5.10.16-arch1-1 | 33        | 0.48%   |
| 6.1.8-arch1-1   | 32        | 0.46%   |
| 6.0.10-arch2-1  | 32        | 0.46%   |
| 5.19.13-arch1-1 | 32        | 0.46%   |
| 5.18.1-arch1-1  | 32        | 0.46%   |
| 6.0.7-arch1-1   | 31        | 0.45%   |
| 5.8.3-arch1-1   | 31        | 0.45%   |
| 5.19.7-arch1-1  | 31        | 0.45%   |
| 5.15.7-arch1-1  | 31        | 0.45%   |
| 5.14.14-arch1-1 | 31        | 0.45%   |
| 6.1.9-arch1-1   | 30        | 0.43%   |
| 6.0.8-arch1-1   | 30        | 0.43%   |
| 5.9.11-arch2-1  | 30        | 0.43%   |
| 5.9.10-arch1-1  | 30        | 0.43%   |
| 5.13.12-arch1-1 | 30        | 0.43%   |
| 6.2.2-arch1-1   | 29        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.51%   |
| 5.8.5   | 92        | 1.33%   |
| 6.0.2   | 90        | 1.3%    |
| 5.9.1   | 77        | 1.11%   |
| 5.8.12  | 73        | 1.05%   |
| 5.9.14  | 72        | 1.04%   |
| 5.17.5  | 70        | 1.01%   |
| 5.8.14  | 63        | 0.91%   |
| 5.8.10  | 62        | 0.89%   |
| 5.17.9  | 61        | 0.88%   |
| 5.13.13 | 56        | 0.81%   |
| 6.1.1   | 55        | 0.79%   |
| 6.1.12  | 53        | 0.76%   |
| 5.8.1   | 53        | 0.76%   |
| 5.7.12  | 53        | 0.76%   |
| 6.0.9   | 52        | 0.75%   |
| 5.11.6  | 52        | 0.75%   |
| 6.2.2   | 51        | 0.73%   |
| 6.1.9   | 51        | 0.73%   |
| 5.11.16 | 51        | 0.73%   |
| 6.0.12  | 50        | 0.72%   |
| 5.11.2  | 43        | 0.62%   |
| 6.0.8   | 42        | 0.61%   |
| 5.12.15 | 42        | 0.61%   |
| 5.10.16 | 42        | 0.61%   |
| 6.1.8   | 41        | 0.59%   |
| 6.0.11  | 41        | 0.59%   |
| 5.19.7  | 41        | 0.59%   |
| 5.18.16 | 41        | 0.59%   |
| 5.11.11 | 41        | 0.59%   |
| 6.2.8   | 40        | 0.58%   |
| 6.0.10  | 40        | 0.58%   |
| 5.19.13 | 40        | 0.58%   |
| 5.7.6   | 38        | 0.55%   |
| 5.6.15  | 38        | 0.55%   |
| 5.18.1  | 38        | 0.55%   |
| 5.15.7  | 38        | 0.55%   |
| 5.14.14 | 38        | 0.55%   |
| 5.12.14 | 38        | 0.55%   |
| 6.0.7   | 37        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 7.81%   |
| 5.15    | 477       | 7.14%   |
| 6.0     | 411       | 6.15%   |
| 6.1     | 390       | 5.84%   |
| 5.9     | 384       | 5.75%   |
| 5.18    | 366       | 5.48%   |
| 5.10    | 355       | 5.31%   |
| 5.4     | 353       | 5.28%   |
| 5.11    | 350       | 5.24%   |
| 5.19    | 343       | 5.13%   |
| 5.17    | 341       | 5.1%    |
| 5.12    | 309       | 4.62%   |
| 5.16    | 305       | 4.56%   |
| 5.6     | 263       | 3.94%   |
| 5.7     | 260       | 3.89%   |
| 5.14    | 237       | 3.55%   |
| 5.13    | 234       | 3.5%    |
| 6.2     | 196       | 2.93%   |
| 5.5     | 148       | 2.21%   |
| 5.3     | 114       | 1.71%   |
| 4.19    | 56        | 0.84%   |
| 5.2     | 54        | 0.81%   |
| 5.0     | 41        | 0.61%   |
| 4.18    | 37        | 0.55%   |
| 5.1     | 32        | 0.48%   |
| 4.20    | 22        | 0.33%   |
| 4.17    | 19        | 0.28%   |
| 4.15    | 14        | 0.21%   |
| 4.14    | 10        | 0.15%   |
| 4.16    | 9         | 0.13%   |
| 4.9     | 5         | 0.07%   |
| 4.7     | 4         | 0.06%   |
| 4.6     | 4         | 0.06%   |
| 4.11    | 4         | 0.06%   |
| 4.8     | 3         | 0.04%   |
| 4.4     | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |
| 4.10    | 2         | 0.03%   |
| 6.3     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 5854      | 99.91%  |
| i686   | 5         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1980      | 32.4%   |
| KDE5                     | 1492      | 24.41%  |
| Unknown                  | 783       | 12.81%  |
| XFCE                     | 478       | 7.82%   |
| i3                       | 306       | 5.01%   |
| KDE                      | 289       | 4.73%   |
| X-Cinnamon               | 83        | 1.36%   |
| MATE                     | 82        | 1.34%   |
| Budgie                   | 82        | 1.34%   |
| sway                     | 79        | 1.29%   |
| Cinnamon                 | 79        | 1.29%   |
| Deepin                   | 66        | 1.08%   |
| LXQt                     | 51        | 0.83%   |
| LXDE                     | 37        | 0.61%   |
| bspwm                    | 31        | 0.51%   |
| Awesome                  | 31        | 0.51%   |
| Hyprland                 | 27        | 0.44%   |
| qtile                    | 19        | 0.31%   |
| openbox                  | 19        | 0.31%   |
| GNOME Flashback          | 15        | 0.25%   |
| xmonad                   | 13        | 0.21%   |
| Unity                    | 11        | 0.18%   |
| DWM                      | 11        | 0.18%   |
| GNOME Classic            | 7         | 0.11%   |
| LeftWM                   | 5         | 0.08%   |
| i3-with-shmlog           | 5         | 0.08%   |
| Enlightenment            | 4         | 0.07%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| chadwm                   | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| X-Generic                | 1         | 0.02%   |
| Wayfire                  | 1         | 0.02%   |
| sway:Unity               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3658      | 60.3%   |
| Wayland | 1413      | 23.29%  |
| Tty     | 565       | 9.31%   |
| Unknown | 429       | 7.07%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2527      | 41.76%  |
| SDDM    | 1389      | 22.95%  |
| GDM     | 860       | 14.21%  |
| LightDM | 648       | 10.71%  |
| TDM     | 398       | 6.58%   |
| Ly      | 70        | 1.16%   |
| XDM     | 56        | 0.93%   |
| LXDM    | 50        | 0.83%   |
| SLiM    | 25        | 0.41%   |
| GREETD  | 17        | 0.28%   |
| NODM    | 4         | 0.07%   |
| EMPTTY  | 4         | 0.07%   |
| XINIT   | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 2894      | 48.28%  |
| Unknown    | 614       | 10.24%  |
| en_GB      | 350       | 5.84%   |
| C          | 294       | 4.9%    |
| de_DE      | 249       | 4.15%   |
| it_IT      | 186       | 3.1%    |
| ru_RU      | 182       | 3.04%   |
| pt_BR      | 162       | 2.7%    |
| fr_FR      | 136       | 2.27%   |
| pl_PL      | 83        | 1.38%   |
| es_ES      | 63        | 1.05%   |
| en_IN      | 63        | 1.05%   |
| en_CA      | 63        | 1.05%   |
| en_AU      | 62        | 1.03%   |
| zh_CN      | 58        | 0.97%   |
| en_IE      | 34        | 0.57%   |
| en_DK      | 28        | 0.47%   |
| es_MX      | 22        | 0.37%   |
| de_AT      | 21        | 0.35%   |
| hu_HU      | 20        | 0.33%   |
| es_AR      | 18        | 0.3%    |
| en_NZ      | 17        | 0.28%   |
| ja_JP      | 16        | 0.27%   |
| nl_NL      | 15        | 0.25%   |
| tr_TR      | 14        | 0.23%   |
| es_CO      | 14        | 0.23%   |
| es_CL      | 14        | 0.23%   |
| ru_UA      | 13        | 0.22%   |
| cs_CZ      | 13        | 0.22%   |
| pt_PT      | 12        | 0.2%    |
| en_US.UTF8 | 10        | 0.17%   |
| en_SG      | 10        | 0.17%   |
| sv_SE      | 9         | 0.15%   |
| lv_LV      | 9         | 0.15%   |
| en_ZA      | 9         | 0.15%   |
| en_DE      | 9         | 0.15%   |
| fi_FI      | 8         | 0.13%   |
| de_CH      | 8         | 0.13%   |
| uk_UA      | 7         | 0.12%   |
| ko_KR      | 7         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3683      | 61.54%  |
| BIOS | 2302      | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4250      | 71.58%  |
| Btrfs    | 1194      | 20.11%  |
| Unknown  | 180       | 3.03%   |
| Xfs      | 145       | 2.44%   |
| F2fs     | 82        | 1.38%   |
| Zfs      | 36        | 0.61%   |
| Overlay  | 32        | 0.54%   |
| Ext2     | 8         | 0.13%   |
| XXXXX    | 4         | 0.07%   |
| Ext3     | 2         | 0.03%   |
| XXX4     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3736      | 62.84%  |
| Unknown | 1700      | 28.6%   |
| MBR     | 509       | 8.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5122      | 86.21%  |
| Yes       | 819       | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4105      | 68.9%   |
| Yes       | 1853      | 31.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1124      | 19.18%  |
| Lenovo                 | 1054      | 17.99%  |
| Dell                   | 631       | 10.77%  |
| Hewlett-Packard        | 611       | 10.43%  |
| MSI                    | 495       | 8.45%   |
| Gigabyte Technology    | 486       | 8.29%   |
| ASRock                 | 302       | 5.15%   |
| Acer                   | 283       | 4.83%   |
| Apple                  | 92        | 1.57%   |
| Intel                  | 75        | 1.28%   |
| HUAWEI                 | 58        | 0.99%   |
| Samsung Electronics    | 56        | 0.96%   |
| Toshiba                | 44        | 0.75%   |
| Unknown                | 32        | 0.55%   |
| Microsoft              | 31        | 0.53%   |
| Notebook               | 29        | 0.49%   |
| Sony                   | 23        | 0.39%   |
| Google                 | 23        | 0.39%   |
| Timi                   | 22        | 0.38%   |
| TUXEDO                 | 18        | 0.31%   |
| Fujitsu                | 18        | 0.31%   |
| Framework              | 17        | 0.29%   |
| Alienware              | 17        | 0.29%   |
| Biostar                | 14        | 0.24%   |
| Razer                  | 13        | 0.22%   |
| LG Electronics         | 11        | 0.19%   |
| Pegatron               | 10        | 0.17%   |
| Medion                 | 10        | 0.17%   |
| ECS                    | 10        | 0.17%   |
| Avell High Performance | 10        | 0.17%   |
| System76               | 9         | 0.15%   |
| Supermicro             | 8         | 0.14%   |
| Schenker               | 8         | 0.14%   |
| Positivo               | 8         | 0.14%   |
| Packard Bell           | 8         | 0.14%   |
| MECHREVO               | 7         | 0.12%   |
| Huanan                 | 6         | 0.1%    |
| Chuwi                  | 6         | 0.1%    |
| ZOTAC                  | 5         | 0.09%   |
| Teclast                | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 58        | 0.99%   |
| Unknown                          | 55        | 0.94%   |
| MSI MS-7C37                      | 28        | 0.48%   |
| MSI MS-7C02                      | 28        | 0.48%   |
| ASUS TUF Gaming X570-PLUS        | 27        | 0.46%   |
| MSI MS-7B86                      | 22        | 0.38%   |
| Gigabyte B450M DS3H              | 22        | 0.38%   |
| Dell XPS 15 9570                 | 18        | 0.31%   |
| MSI MS-7A34                      | 17        | 0.29%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.29%   |
| Gigabyte X570 AORUS ELITE        | 16        | 0.27%   |
| Framework Laptop                 | 16        | 0.27%   |
| ASUS ROG STRIX B550-F GAMING     | 16        | 0.27%   |
| ASUS PRIME B450M-A               | 16        | 0.27%   |
| MSI MS-7C91                      | 15        | 0.26%   |
| MSI MS-7B89                      | 15        | 0.26%   |
| MSI MS-7B79                      | 15        | 0.26%   |
| MSI MS-7A38                      | 15        | 0.26%   |
| HP Notebook                      | 15        | 0.26%   |
| ASUS PRIME X470-PRO              | 15        | 0.26%   |
| ASUS PRIME X370-PRO              | 15        | 0.26%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14        | 0.24%   |
| Dell XPS 15 9500                 | 14        | 0.24%   |
| Dell XPS 13 9360                 | 13        | 0.22%   |
| Gigabyte 970A-DS3P               | 11        | 0.19%   |
| Dell XPS 13 9380                 | 11        | 0.19%   |
| ASUS TUF Gaming B550-PLUS        | 11        | 0.19%   |
| ASUS PRIME A320M-K               | 11        | 0.19%   |
| ASRock X570 Taichi               | 11        | 0.19%   |
| MSI MS-7C56                      | 10        | 0.17%   |
| Gigabyte B450 AORUS ELITE        | 10        | 0.17%   |
| Dell Latitude E6430              | 10        | 0.17%   |
| Dell Inspiron 15 7000 Gaming     | 10        | 0.17%   |
| ASUS ROG STRIX X570-E GAMING     | 10        | 0.17%   |
| ASUS ROG STRIX X470-F GAMING     | 10        | 0.17%   |
| ASUS ROG STRIX B550-I GAMING     | 10        | 0.17%   |
| HUAWEI NBLK-WAX9X                | 9         | 0.15%   |
| HP EliteBook 840 G6              | 9         | 0.15%   |
| Gigabyte X570 I AORUS PRO WIFI   | 9         | 0.15%   |
| Gigabyte B450 AORUS M            | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 572       | 9.76%   |
| ASUS ROG           | 212       | 3.62%   |
| ASUS PRIME         | 190       | 3.24%   |
| Lenovo IdeaPad     | 187       | 3.19%   |
| Acer Aspire        | 168       | 2.87%   |
| Dell Inspiron      | 156       | 2.66%   |
| Dell XPS           | 151       | 2.58%   |
| Dell Latitude      | 137       | 2.34%   |
| ASUS TUF           | 128       | 2.18%   |
| HP Pavilion        | 112       | 1.91%   |
| HP EliteBook       | 99        | 1.69%   |
| HP ENVY            | 61        | 1.04%   |
| HP Laptop          | 59        | 1.01%   |
| Lenovo Legion      | 58        | 0.99%   |
| ASUS All           | 58        | 0.99%   |
| Lenovo Yoga        | 56        | 0.96%   |
| HP ProBook         | 55        | 0.94%   |
| Gigabyte X570      | 55        | 0.94%   |
| ASUS VivoBook      | 55        | 0.94%   |
| Unknown            | 55        | 0.94%   |
| Dell Precision     | 54        | 0.92%   |
| Dell OptiPlex      | 50        | 0.85%   |
| Acer Nitro         | 39        | 0.67%   |
| Toshiba Satellite  | 35        | 0.6%    |
| Gigabyte B450M     | 34        | 0.58%   |
| Microsoft Surface  | 31        | 0.53%   |
| Dell Vostro        | 30        | 0.51%   |
| ASRock X570        | 30        | 0.51%   |
| Acer Swift         | 30        | 0.51%   |
| MSI MS-7C37        | 28        | 0.48%   |
| MSI MS-7C02        | 28        | 0.48%   |
| Lenovo ThinkBook   | 28        | 0.48%   |
| Gigabyte B450      | 28        | 0.48%   |
| ASUS Zenbook       | 28        | 0.48%   |
| ASUS ASUS          | 27        | 0.46%   |
| HP Spectre         | 26        | 0.44%   |
| HP OMEN            | 23        | 0.39%   |
| HP Compaq          | 23        | 0.39%   |
| MSI MS-7B86        | 22        | 0.38%   |
| Lenovo ThinkCentre | 22        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 881       | 15.04%  |
| 2019    | 838       | 14.3%   |
| 2020    | 764       | 13.04%  |
| 2017    | 509       | 8.69%   |
| 2021    | 484       | 8.26%   |
| 2016    | 346       | 5.91%   |
| 2012    | 331       | 5.65%   |
| 2015    | 302       | 5.15%   |
| 2013    | 298       | 5.09%   |
| 2014    | 293       | 5%      |
| 2011    | 248       | 4.23%   |
| 2022    | 198       | 3.38%   |
| 2010    | 149       | 2.54%   |
| 2008    | 87        | 1.48%   |
| 2009    | 78        | 1.33%   |
| 2007    | 30        | 0.51%   |
| 2006    | 11        | 0.19%   |
| 2023    | 5         | 0.09%   |
| 2005    | 3         | 0.05%   |
| Unknown | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3171      | 54.12%  |
| Desktop     | 2304      | 39.32%  |
| Convertible | 206       | 3.52%   |
| Tablet      | 59        | 1.01%   |
| Mini pc     | 52        | 0.89%   |
| All in one  | 40        | 0.68%   |
| Server      | 26        | 0.44%   |
| Stick pc    | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5804      | 98.86%  |
| Enabled  | 67        | 1.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5816      | 99.27%  |
| Yes  | 43        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1723      | 28.97%  |
| 8.01-16.0       | 1150      | 19.34%  |
| 4.01-8.0        | 1115      | 18.75%  |
| 32.01-64.0      | 958       | 16.11%  |
| 3.01-4.0        | 499       | 8.39%   |
| 64.01-256.0     | 228       | 3.83%   |
| 24.01-32.0      | 147       | 2.47%   |
| 1.01-2.0        | 72        | 1.21%   |
| 2.01-3.0        | 34        | 0.57%   |
| 0.51-1.0        | 11        | 0.18%   |
| More than 256.0 | 8         | 0.13%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1540      | 23.8%   |
| 4.01-8.0    | 1514      | 23.4%   |
| 1.01-2.0    | 1411      | 21.81%  |
| 3.01-4.0    | 1037      | 16.03%  |
| 8.01-16.0   | 539       | 8.33%   |
| 0.51-1.0    | 226       | 3.49%   |
| 16.01-24.0  | 91        | 1.41%   |
| 0.01-0.5    | 55        | 0.85%   |
| 24.01-32.0  | 35        | 0.54%   |
| 32.01-64.0  | 18        | 0.28%   |
| 64.01-256.0 | 2         | 0.03%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2985      | 49.49%  |
| 2      | 1649      | 27.34%  |
| 3      | 684       | 11.34%  |
| 4      | 326       | 5.4%    |
| 5      | 186       | 3.08%   |
| 6      | 82        | 1.36%   |
| 7      | 44        | 0.73%   |
| 8      | 20        | 0.33%   |
| 0      | 19        | 0.31%   |
| 9      | 16        | 0.27%   |
| 11     | 5         | 0.08%   |
| 12     | 4         | 0.07%   |
| 10     | 4         | 0.07%   |
| 13     | 3         | 0.05%   |
| 14     | 2         | 0.03%   |
| 22     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4609      | 78.15%  |
| Yes       | 1289      | 21.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4928      | 83.77%  |
| No        | 955       | 16.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4549      | 77.15%  |
| No        | 1347      | 22.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4092      | 69.01%  |
| No        | 1838      | 30.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1128      | 19.11%  |
| Germany     | 574       | 9.73%   |
| Russia      | 382       | 6.47%   |
| Brazil      | 312       | 5.29%   |
| Italy       | 310       | 5.25%   |
| France      | 257       | 4.35%   |
| UK          | 223       | 3.78%   |
| India       | 185       | 3.13%   |
| Poland      | 178       | 3.02%   |
| Canada      | 152       | 2.58%   |
| Spain       | 126       | 2.13%   |
| Netherlands | 118       | 2%      |
| Australia   | 102       | 1.73%   |
| China       | 92        | 1.56%   |
| Ukraine     | 89        | 1.51%   |
| Sweden      | 89        | 1.51%   |
| Austria     | 87        | 1.47%   |
| Turkey      | 72        | 1.22%   |
| Finland     | 64        | 1.08%   |
| Switzerland | 55        | 0.93%   |
| Czechia     | 53        | 0.9%    |
| Hungary     | 49        | 0.83%   |
| Mexico      | 48        | 0.81%   |
| Indonesia   | 47        | 0.8%    |
| Romania     | 45        | 0.76%   |
| Belgium     | 45        | 0.76%   |
| Argentina   | 44        | 0.75%   |
| Japan       | 40        | 0.68%   |
| Greece      | 40        | 0.68%   |
| Denmark     | 40        | 0.68%   |
| Norway      | 38        | 0.64%   |
| Portugal    | 36        | 0.61%   |
| Vietnam     | 34        | 0.58%   |
| Chile       | 34        | 0.58%   |
| New Zealand | 32        | 0.54%   |
| Iran        | 32        | 0.54%   |
| Colombia    | 30        | 0.51%   |
| Hong Kong   | 25        | 0.42%   |
| Bulgaria    | 25        | 0.42%   |
| Serbia      | 24        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 113       | 1.81%   |
| Paris             | 65        | 1.04%   |
| St Petersburg     | 56        | 0.9%    |
| Berlin            | 54        | 0.86%   |
| Sao Paulo         | 50        | 0.8%    |
| Warsaw            | 47        | 0.75%   |
| Vienna            | 47        | 0.75%   |
| Milan             | 47        | 0.75%   |
| Munich            | 39        | 0.62%   |
| Melbourne         | 39        | 0.62%   |
| Helsinki          | 35        | 0.56%   |
| Amsterdam         | 32        | 0.51%   |
| Frankfurt am Main | 31        | 0.5%    |
| Sydney            | 30        | 0.48%   |
| Los Angeles       | 27        | 0.43%   |
| New York          | 26        | 0.42%   |
| Hamburg           | 26        | 0.42%   |
| Valencia          | 25        | 0.4%    |
| Kyiv              | 25        | 0.4%    |
| Rome              | 24        | 0.38%   |
| Prague            | 24        | 0.38%   |
| Istanbul          | 24        | 0.38%   |
| London            | 22        | 0.35%   |
| Athens            | 22        | 0.35%   |
| Bengaluru         | 21        | 0.34%   |
| Seattle           | 20        | 0.32%   |
| Madrid            | 20        | 0.32%   |
| Cologne           | 20        | 0.32%   |
| Budapest          | 20        | 0.32%   |
| Montreal          | 19        | 0.3%    |
| Krakow            | 19        | 0.3%    |
| Singapore         | 18        | 0.29%   |
| Phoenix           | 18        | 0.29%   |
| Zurich            | 17        | 0.27%   |
| Stockholm         | 17        | 0.27%   |
| Beijing           | 17        | 0.27%   |
| Stuttgart         | 16        | 0.26%   |
| Mexico City       | 16        | 0.26%   |
| Dublin            | 16        | 0.26%   |
| Dallas            | 16        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1971      | 3131   | 20.19%  |
| WDC                         | 1403      | 2174   | 14.37%  |
| Seagate                     | 1190      | 1779   | 12.19%  |
| SanDisk                     | 654       | 860    | 6.7%    |
| Toshiba                     | 629       | 837    | 6.44%   |
| Kingston                    | 518       | 676    | 5.31%   |
| Crucial                     | 430       | 613    | 4.4%    |
| SK hynix                    | 297       | 358    | 3.04%   |
| Intel                       | 272       | 362    | 2.79%   |
| Unknown                     | 247       | 299    | 2.53%   |
| HGST                        | 169       | 212    | 1.73%   |
| Micron Technology           | 162       | 197    | 1.66%   |
| Hitachi                     | 161       | 200    | 1.65%   |
| A-DATA Technology           | 147       | 206    | 1.51%   |
| Phison                      | 114       | 147    | 1.17%   |
| Micron/Crucial Technology   | 67        | 79     | 0.69%   |
| China                       | 65        | 80     | 0.67%   |
| Silicon Motion              | 64        | 77     | 0.66%   |
| Apple                       | 62        | 74     | 0.64%   |
| Phison Electronics          | 58        | 69     | 0.59%   |
| KIOXIA                      | 54        | 65     | 0.55%   |
| SPCC                        | 50        | 55     | 0.51%   |
| OCZ                         | 50        | 68     | 0.51%   |
| Corsair                     | 47        | 60     | 0.48%   |
| Transcend                   | 43        | 57     | 0.44%   |
| PNY                         | 40        | 49     | 0.41%   |
| LITEON                      | 40        | 43     | 0.41%   |
| Patriot                     | 38        | 47     | 0.39%   |
| ADATA Technology            | 31        | 37     | 0.32%   |
| GOODRAM                     | 28        | 32     | 0.29%   |
| XPG                         | 27        | 38     | 0.28%   |
| Kingston Technology Company | 27        | 29     | 0.28%   |
| Realtek Semiconductor       | 25        | 31     | 0.26%   |
| JMicron Technology          | 22        | 30     | 0.23%   |
| Hewlett-Packard             | 22        | 23     | 0.23%   |
| Plextor                     | 20        | 29     | 0.2%    |
| Lenovo                      | 20        | 24     | 0.2%    |
| Team                        | 18        | 26     | 0.18%   |
| Intenso                     | 18        | 19     | 0.18%   |
| Lexar                       | 17        | 22     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 149       | 1.34%   |
| Samsung SSD 850 EVO 500GB                           | 112       | 1.01%   |
| Samsung SSD 860 EVO 500GB                           | 111       | 1%      |
| Kingston SA400S37240G 240GB SSD                     | 98        | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB                      | 92        | 0.83%   |
| Samsung SSD 850 EVO 250GB                           | 82        | 0.74%   |
| Samsung NVMe SSD Drive 512GB                        | 82        | 0.74%   |
| Samsung SSD 860 EVO 1TB                             | 79        | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB                        | 76        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                      | 71        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 69        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 69        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 68        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                          | 67        | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                      | 65        | 0.58%   |
| Samsung NVMe SSD Drive 500GB                        | 64        | 0.58%   |
| Kingston SA400S37120G 120GB SSD                     | 61        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 56        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                      | 55        | 0.49%   |
| HGST HTS721010A9E630 1TB                            | 55        | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 53        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 53        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                     | 53        | 0.48%   |
| SanDisk NVMe SSD Drive 1TB                          | 50        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 49        | 0.44%   |
| Toshiba DT01ACA100 1TB                              | 48        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 48        | 0.43%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 48        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                     | 44        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB                      | 44        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                       | 43        | 0.39%   |
| Samsung SSD 860 QVO 1TB                             | 43        | 0.39%   |
| Toshiba MQ04ABF100 1TB                              | 42        | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                      | 42        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                    | 40        | 0.36%   |
| Samsung SSD 970 EVO 500GB                           | 37        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 37        | 0.33%   |
| Unknown MMC Card  64GB                              | 36        | 0.32%   |
| Seagate ST1000LM048-2E7172 1TB                      | 36        | 0.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 36        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1161      | 1732   | 35.91%  |
| WDC                 | 1071      | 1641   | 33.13%  |
| Toshiba             | 435       | 569    | 13.45%  |
| HGST                | 167       | 210    | 5.17%   |
| Hitachi             | 161       | 200    | 4.98%   |
| Samsung Electronics | 110       | 145    | 3.4%    |
| Unknown             | 27        | 33     | 0.84%   |
| Apple               | 25        | 25     | 0.77%   |
| SABRENT             | 12        | 13     | 0.37%   |
| ASMT                | 11        | 13     | 0.34%   |
| Fujitsu             | 10        | 10     | 0.31%   |
| Maxtor              | 5         | 5      | 0.15%   |
| HGST HTS            | 4         | 4      | 0.12%   |
| USB3.0              | 3         | 4      | 0.09%   |
| LaCie               | 2         | 2      | 0.06%   |
| KESU                | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| Generic-            | 2         | 3      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 11     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 6      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 932       | 1337   | 28.22%  |
| Kingston            | 411       | 524    | 12.44%  |
| Crucial             | 389       | 554    | 11.78%  |
| SanDisk             | 331       | 451    | 10.02%  |
| WDC                 | 225       | 293    | 6.81%   |
| A-DATA Technology   | 95        | 139    | 2.88%   |
| Intel               | 77        | 90     | 2.33%   |
| China               | 65        | 80     | 1.97%   |
| Toshiba             | 54        | 90     | 1.63%   |
| OCZ                 | 50        | 68     | 1.51%   |
| SK hynix            | 48        | 56     | 1.45%   |
| SPCC                | 41        | 44     | 1.24%   |
| Transcend           | 40        | 54     | 1.21%   |
| Micron Technology   | 40        | 49     | 1.21%   |
| Patriot             | 38        | 47     | 1.15%   |
| PNY                 | 35        | 44     | 1.06%   |
| LITEON              | 35        | 37     | 1.06%   |
| Apple               | 28        | 29     | 0.85%   |
| GOODRAM             | 26        | 30     | 0.79%   |
| Corsair             | 20        | 25     | 0.61%   |
| Plextor             | 17        | 18     | 0.51%   |
| Intenso             | 17        | 18     | 0.51%   |
| LITEONIT            | 16        | 16     | 0.48%   |
| Lexar               | 15        | 19     | 0.45%   |
| KingSpec            | 14        | 15     | 0.42%   |
| JMicron Technology  | 14        | 16     | 0.42%   |
| Team                | 12        | 13     | 0.36%   |
| Hewlett-Packard     | 11        | 11     | 0.33%   |
| TO Exter            | 9         | 13     | 0.27%   |
| Mushkin             | 9         | 14     | 0.27%   |
| Unknown             | 8         | 9      | 0.24%   |
| Seagate             | 7         | 7      | 0.21%   |
| Netac               | 7         | 7      | 0.21%   |
| Gigabyte Technology | 7         | 7      | 0.21%   |
| FORESEE             | 6         | 8      | 0.18%   |
| KingDian            | 5         | 6      | 0.15%   |
| AMD                 | 5         | 6      | 0.15%   |
| Unknown             | 4         | 4      | 0.12%   |
| HS-SSD-C100         | 4         | 4      | 0.12%   |
| Apacer              | 4         | 5      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2920      | 4317   | 33.86%  |
| SSD     | 2756      | 4423   | 31.96%  |
| HDD     | 2652      | 4652   | 30.75%  |
| MMC     | 207       | 251    | 2.4%    |
| Unknown | 88        | 108    | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3964      | 8777   | 53.6%   |
| NVMe | 2916      | 4302   | 39.43%  |
| SAS  | 308       | 421    | 4.16%   |
| MMC  | 207       | 251    | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2834      | 4536   | 48.78%  |
| 0.51-1.0        | 1844      | 2685   | 31.74%  |
| 1.01-2.0        | 619       | 952    | 10.65%  |
| 3.01-4.0        | 201       | 344    | 3.46%   |
| 4.01-10.0       | 153       | 291    | 2.63%   |
| 2.01-3.0        | 136       | 212    | 2.34%   |
| 10.01-20.0      | 22        | 53     | 0.38%   |
| More than 100.0 | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1319      | 21.55%  |
| 101-250        | 1312      | 21.43%  |
| 501-1000       | 1133      | 18.51%  |
| 1001-2000      | 838       | 13.69%  |
| More than 3000 | 607       | 9.92%   |
| 2001-3000      | 350       | 5.72%   |
| 51-100         | 229       | 3.74%   |
| Unknown        | 159       | 2.6%    |
| 21-50          | 92        | 1.5%    |
| 1-20           | 83        | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1170      | 18.37%  |
| 101-250        | 1111      | 17.44%  |
| 21-50          | 896       | 14.07%  |
| 251-500        | 803       | 12.61%  |
| 51-100         | 770       | 12.09%  |
| 501-1000       | 674       | 10.58%  |
| 1001-2000      | 397       | 6.23%   |
| More than 3000 | 229       | 3.59%   |
| 2001-3000      | 160       | 2.51%   |
| Unknown        | 159       | 2.5%    |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 13        | 15     | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 11        | 11     | 1.6%    |
| HGST HTS721010A9E630 1TB                                        | 9         | 9      | 1.31%   |
| HGST HTS541010A9E680 1TB                                        | 8         | 8      | 1.16%   |
| Kingston SV300S37A120G 120GB SSD                                | 7         | 7      | 1.02%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 6         | 6      | 0.87%   |
| Seagate ST9500325AS 500GB                                       | 6         | 6      | 0.87%   |
| Seagate ST500LT012-1DG142 500GB                                 | 6         | 6      | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 6         | 9      | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 6         | 9      | 0.87%   |
| OCZ VERTEX4 256GB SSD                                           | 6         | 9      | 0.87%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 5         | 6      | 0.73%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 5         | 7      | 0.73%   |
| Toshiba MQ01ABD100 1TB                                          | 5         | 8      | 0.73%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 0.73%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 5         | 6      | 0.73%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 5         | 5      | 0.73%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.73%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 5         | 11     | 0.73%   |
| HGST HTS725050A7E630 500GB                                      | 5         | 5      | 0.73%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 0.73%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 4      | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 4         | 4      | 0.58%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 0.58%   |
| Seagate ST9250315AS 250GB                                       | 4         | 4      | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 4         | 4      | 0.58%   |
| Seagate ST3320620AS 320GB                                       | 4         | 4      | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 4         | 4      | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 4      | 0.58%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 4         | 5      | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 4         | 4      | 0.58%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 5      | 0.58%   |
| Samsung Electronics HD103SJ 1TB                                 | 4         | 6      | 0.58%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 4         | 4      | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 3         | 3      | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB                                        | 3         | 7      | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 3         | 3      | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB                                        | 3         | 3      | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 3      | 0.44%   |
| WDC WD10EZEX-08M2NA0 1TB                                        | 3         | 3      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 184       | 221    | 27.92%  |
| WDC                   | 146       | 196    | 22.15%  |
| Samsung Electronics   | 58        | 78     | 8.8%    |
| Toshiba               | 47        | 59     | 7.13%   |
| Hitachi               | 42        | 45     | 6.37%   |
| HGST                  | 32        | 33     | 4.86%   |
| Kingston              | 22        | 25     | 3.34%   |
| SanDisk               | 18        | 19     | 2.73%   |
| Intel                 | 18        | 21     | 2.73%   |
| Crucial               | 16        | 19     | 2.43%   |
| SK hynix              | 12        | 13     | 1.82%   |
| OCZ                   | 10        | 17     | 1.52%   |
| A-DATA Technology     | 9         | 10     | 1.37%   |
| LITEON                | 5         | 5      | 0.76%   |
| Transcend             | 3         | 9      | 0.46%   |
| Micron Technology     | 3         | 4      | 0.46%   |
| Hewlett-Packard       | 3         | 3      | 0.46%   |
| Drevo                 | 3         | 4      | 0.46%   |
| Corsair               | 3         | 3      | 0.46%   |
| XrayDisk              | 2         | 2      | 0.3%    |
| SPCC                  | 2         | 3      | 0.3%    |
| Realtek Semiconductor | 2         | 3      | 0.3%    |
| PNY                   | 2         | 3      | 0.3%    |
| Plextor               | 2         | 9      | 0.3%    |
| Patriot               | 2         | 2      | 0.3%    |
| ASMT                  | 2         | 2      | 0.3%    |
| Apple                 | 2         | 2      | 0.3%    |
| SSSTC                 | 1         | 1      | 0.15%   |
| KingSpec              | 1         | 1      | 0.15%   |
| Kingrich              | 1         | 1      | 0.15%   |
| JMicron Technology    | 1         | 1      | 0.15%   |
| INNOVATION IT         | 1         | 1      | 0.15%   |
| GLOWAY                | 1         | 1      | 0.15%   |
| Gigabyte Technology   | 1         | 1      | 0.15%   |
| China                 | 1         | 1      | 0.15%   |
| BAITITON              | 1         | 4      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 184       | 221    | 39.66%  |
| WDC                 | 140       | 188    | 30.17%  |
| Hitachi             | 42        | 45     | 9.05%   |
| Toshiba             | 41        | 53     | 8.84%   |
| HGST                | 32        | 33     | 6.9%    |
| Samsung Electronics | 21        | 25     | 4.53%   |
| Apple               | 2         | 2      | 0.43%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 429       | 569    | 69.19%  |
| SSD  | 150       | 189    | 24.19%  |
| NVMe | 41        | 64     | 6.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 16.67%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 8.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 8.33%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 8.33%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 8.33%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 8.33%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 33.33%  |
| WDC                 | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| Transcend           | 1         | 1      | 8.33%   |
| Phison              | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3099      | 6891   | 46.69%  |
| Detected | 2931      | 6024   | 44.15%  |
| Malfunc  | 595       | 822    | 8.96%   |
| Failed   | 12        | 13     | 0.18%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3278      | 39.61%  |
| AMD                              | 1600      | 19.34%  |
| Samsung Electronics              | 1181      | 14.27%  |
| SanDisk                          | 480       | 5.8%    |
| SK hynix                         | 246       | 2.97%   |
| Phison Electronics               | 218       | 2.63%   |
| ASMedia Technology               | 169       | 2.04%   |
| Toshiba America Info Systems     | 140       | 1.69%   |
| Kingston Technology Company      | 140       | 1.69%   |
| Micron Technology                | 128       | 1.55%   |
| Micron/Crucial Technology        | 104       | 1.26%   |
| ADATA Technology                 | 93        | 1.12%   |
| Silicon Motion                   | 85        | 1.03%   |
| Marvell Technology Group         | 67        | 0.81%   |
| KIOXIA                           | 57        | 0.69%   |
| JMicron Technology               | 38        | 0.46%   |
| Realtek Semiconductor            | 36        | 0.44%   |
| Union Memory (Shenzhen)          | 23        | 0.28%   |
| Broadcom / LSI                   | 19        | 0.23%   |
| Lite-On Technology               | 18        | 0.22%   |
| Lenovo                           | 18        | 0.22%   |
| Nvidia                           | 15        | 0.18%   |
| Solid State Storage Technology   | 14        | 0.17%   |
| Seagate Technology               | 13        | 0.16%   |
| Apple                            | 13        | 0.16%   |
| LSI Logic / Symbios Logic        | 11        | 0.13%   |
| Adaptec                          | 10        | 0.12%   |
| Yangtze Memory Technologies      | 8         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 8         | 0.1%    |
| Silicon Image                    | 7         | 0.08%   |
| VIA Technologies                 | 6         | 0.07%   |
| Hewlett-Packard                  | 6         | 0.07%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| Shenzhen Longsys Electronics     | 4         | 0.05%   |
| OCZ Technology Group             | 4         | 0.05%   |
| INNOGRIT                         | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| Netac Technology                 | 2         | 0.02%   |
| Integrated Technology Express    | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1211      | 13.06%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 710       | 7.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 386       | 4.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 321       | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 212       | 2.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 197       | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 190       | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 181       | 1.95%   |
| AMD 500 Series Chipset SATA Controller                                         | 167       | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 165       | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 162       | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 162       | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 154       | 1.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 146       | 1.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 132       | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 132       | 1.42%   |
| Micron NVMe Storage Controller                                                 | 125       | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 122       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 119       | 1.28%   |
| Phison E12 NVMe Controller                                                     | 115       | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 112       | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 111       | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 107       | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 102       | 1.1%    |
| Intel SSD 660P Series                                                          | 99        | 1.07%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 96        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 95        | 1.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 94        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 79        | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 75        | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 71        | 0.77%   |
| Intel SATA Controller [RAID mode]                                              | 70        | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                         | 70        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 67        | 0.72%   |
| AMD X370 Series Chipset SATA Controller                                        | 62        | 0.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 60        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 60        | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 59        | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 58        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 57        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4305      | 53.78%  |
| NVMe | 2931      | 36.61%  |
| RAID | 439       | 5.48%   |
| IDE  | 299       | 3.74%   |
| SAS  | 23        | 0.29%   |
| SCSI | 8         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3907      | 66.68%  |
| AMD    | 1952      | 33.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 107       | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 105       | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 94        | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 84        | 1.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 77        | 1.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 75        | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 74        | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 71        | 1.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 69        | 1.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 68        | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 66        | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 64        | 1.09%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 62        | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 50        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 49        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 49        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 49        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 48        | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 47        | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 47        | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 0.77%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 43        | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 42        | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 41        | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 40        | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 39        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 38        | 0.65%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 38        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 38        | 0.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 37        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 36        | 0.61%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 36        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 36        | 0.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 34        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.56%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 32        | 0.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 31        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1351      | 23.03%  |
| Intel Core i5           | 1250      | 21.31%  |
| AMD Ryzen 5             | 643       | 10.96%  |
| AMD Ryzen 7             | 587       | 10.01%  |
| Other                   | 374       | 6.38%   |
| Intel Core i3           | 279       | 4.76%   |
| AMD Ryzen 9             | 210       | 3.58%   |
| Intel Celeron           | 147       | 2.51%   |
| Intel Xeon              | 116       | 1.98%   |
| Intel Core 2 Duo        | 99        | 1.69%   |
| AMD Ryzen 3             | 91        | 1.55%   |
| Intel Pentium           | 87        | 1.48%   |
| AMD FX                  | 83        | 1.41%   |
| AMD Ryzen 7 PRO         | 65        | 1.11%   |
| Intel Core i9           | 64        | 1.09%   |
| Intel Atom              | 48        | 0.82%   |
| AMD A8                  | 31        | 0.53%   |
| AMD Ryzen Threadripper  | 29        | 0.49%   |
| Intel Core 2 Quad       | 25        | 0.43%   |
| AMD Ryzen 5 PRO         | 24        | 0.41%   |
| AMD A6                  | 24        | 0.41%   |
| AMD A10                 | 24        | 0.41%   |
| Intel Pentium Dual-Core | 17        | 0.29%   |
| AMD Athlon              | 17        | 0.29%   |
| AMD A4                  | 16        | 0.27%   |
| Intel Pentium Silver    | 14        | 0.24%   |
| AMD Phenom II X4        | 13        | 0.22%   |
| Intel Genuine           | 9         | 0.15%   |
| Intel Core m3           | 9         | 0.15%   |
| AMD Athlon II X4        | 8         | 0.14%   |
| Intel Core 2            | 7         | 0.12%   |
| AMD E2                  | 7         | 0.12%   |
| AMD E                   | 7         | 0.12%   |
| AMD Athlon II X2        | 7         | 0.12%   |
| Intel Pentium Dual      | 6         | 0.1%    |
| AMD Phenom II X6        | 6         | 0.1%    |
| AMD E1                  | 6         | 0.1%    |
| AMD Athlon 64 X2        | 6         | 0.1%    |
| Intel Core m5           | 5         | 0.09%   |
| AMD Athlon X4           | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2230      | 37.98%  |
| 2       | 1504      | 25.62%  |
| 6       | 918       | 15.64%  |
| 8       | 830       | 14.14%  |
| 12      | 154       | 2.62%   |
| 16      | 86        | 1.46%   |
| 1       | 35        | 0.6%    |
| 10      | 32        | 0.55%   |
| 14      | 28        | 0.48%   |
| 3       | 25        | 0.43%   |
| 24      | 10        | 0.17%   |
| 32      | 7         | 0.12%   |
| 64      | 4         | 0.07%   |
| 18      | 2         | 0.03%   |
| Unknown | 2         | 0.03%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 5824      | 99.4%   |
| 2      | 35        | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4649      | 79.24%  |
| 1       | 1216      | 20.73%  |
| Unknown | 2         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5751      | 97.99%  |
| Unknown        | 114       | 1.94%   |
| 32-bit         | 4         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1861      | 30.51%  |
| 0x306a9    | 203       | 3.33%   |
| 0x906ea    | 199       | 3.26%   |
| 0x306c3    | 199       | 3.26%   |
| 0x08701021 | 195       | 3.2%    |
| 0x206a7    | 178       | 2.92%   |
| 0x906e9    | 172       | 2.82%   |
| 0x806ea    | 167       | 2.74%   |
| 0x0800820d | 144       | 2.36%   |
| 0x806ec    | 136       | 2.23%   |
| 0x806c1    | 134       | 2.2%    |
| 0x506e3    | 121       | 1.98%   |
| 0x406e3    | 110       | 1.8%    |
| 0x806e9    | 103       | 1.69%   |
| 0x08701013 | 95        | 1.56%   |
| 0x0a50000c | 93        | 1.52%   |
| 0x306d4    | 90        | 1.48%   |
| 0x40651    | 86        | 1.41%   |
| 0x08108102 | 84        | 1.38%   |
| 0x08600106 | 76        | 1.25%   |
| 0x08108109 | 70        | 1.15%   |
| 0x1067a    | 68        | 1.11%   |
| 0xa0652    | 61        | 1%      |
| 0x08001138 | 57        | 0.93%   |
| 0x20655    | 50        | 0.82%   |
| 0x0a201016 | 50        | 0.82%   |
| 0x0a201009 | 50        | 0.82%   |
| 0x08600104 | 50        | 0.82%   |
| 0x806eb    | 46        | 0.75%   |
| 0x08600103 | 42        | 0.69%   |
| 0x706e5    | 37        | 0.61%   |
| 0x08608103 | 37        | 0.61%   |
| 0x906ed    | 36        | 0.59%   |
| 0x0810100b | 35        | 0.57%   |
| 0x906a3    | 27        | 0.44%   |
| 0x406c4    | 27        | 0.44%   |
| 0x08001137 | 26        | 0.43%   |
| 0x06000852 | 26        | 0.43%   |
| 0x506c9    | 24        | 0.39%   |
| 0x08101016 | 24        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1294      | 22.03%  |
| Zen 2            | 595       | 10.13%  |
| Haswell          | 444       | 7.56%   |
| Zen+             | 392       | 6.67%   |
| Skylake          | 361       | 6.14%   |
| Zen 3            | 332       | 5.65%   |
| IvyBridge        | 302       | 5.14%   |
| SandyBridge      | 269       | 4.58%   |
| Unknown          | 221       | 3.76%   |
| Zen              | 215       | 3.66%   |
| TigerLake        | 202       | 3.44%   |
| CometLake        | 159       | 2.71%   |
| Broadwell        | 138       | 2.35%   |
| Penryn           | 136       | 2.31%   |
| Piledriver       | 102       | 1.74%   |
| Westmere         | 99        | 1.69%   |
| Silvermont       | 96        | 1.63%   |
| IceLake          | 91        | 1.55%   |
| Alderlake Hybrid | 56        | 0.95%   |
| Goldmont plus    | 49        | 0.83%   |
| K10              | 47        | 0.8%    |
| Excavator        | 40        | 0.68%   |
| Nehalem          | 39        | 0.66%   |
| Core             | 38        | 0.65%   |
| Goldmont         | 30        | 0.51%   |
| K10 Llano        | 18        | 0.31%   |
| Steamroller      | 17        | 0.29%   |
| Bonnell          | 17        | 0.29%   |
| Bobcat           | 17        | 0.29%   |
| Jaguar           | 13        | 0.22%   |
| Puma             | 12        | 0.2%    |
| K8 Hammer        | 10        | 0.17%   |
| Tremont          | 8         | 0.14%   |
| NetBurst         | 7         | 0.12%   |
| Bulldozer        | 5         | 0.09%   |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3012      | 41.55%  |
| Nvidia                           | 2272      | 31.34%  |
| AMD                              | 1931      | 26.64%  |
| Matrox Electronics Systems       | 17        | 0.23%   |
| ASPEED Technology                | 9         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.06%   |
| ATI Technologies                 | 3         | 0.04%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 283       | 3.82%   |
| Intel UHD Graphics 620                                                                   | 231       | 3.12%   |
| AMD Renoir                                                                               | 210       | 2.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 202       | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 183       | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 182       | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 181       | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 175       | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 158       | 2.13%   |
| Intel HD Graphics 630                                                                    | 146       | 1.97%   |
| Intel HD Graphics 620                                                                    | 137       | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 135       | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 135       | 1.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 128       | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 123       | 1.66%   |
| Intel HD Graphics 5500                                                                   | 103       | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 1.26%   |
| Intel HD Graphics 530                                                                    | 92        | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 91        | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 90        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 84        | 1.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 79        | 1.07%   |
| AMD Lucienne                                                                             | 79        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 76        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 75        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 74        | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 72        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 67        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 59        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 57        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 56        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 55        | 0.74%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 54        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 51        | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 0.66%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 49        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 45        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 45        | 0.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 43        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1848      | 31.26%  |
| 1 x AMD                  | 1495      | 25.29%  |
| 1 x Nvidia               | 1110      | 18.78%  |
| Intel + Nvidia           | 937       | 15.85%  |
| AMD + Nvidia             | 194       | 3.28%   |
| Intel + AMD              | 155       | 2.62%   |
| 2 x AMD                  | 91        | 1.54%   |
| 2 x Nvidia               | 30        | 0.51%   |
| 1 x Matrox               | 13        | 0.22%   |
| 2 x Intel                | 8         | 0.14%   |
| Other                    | 6         | 0.1%    |
| 1 x ASPEED               | 5         | 0.08%   |
| 1 x SiS                  | 4         | 0.07%   |
| AMD + ASPEED             | 3         | 0.05%   |
| Nvidia + Matrox          | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x VIA                  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4272      | 72.17%  |
| Proprietary | 1595      | 26.95%  |
| Unknown     | 52        | 0.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3247      | 53.78%  |
| 7.01-8.0   | 601       | 9.95%   |
| 1.01-2.0   | 562       | 9.31%   |
| 3.01-4.0   | 474       | 7.85%   |
| 0.01-0.5   | 439       | 7.27%   |
| 0.51-1.0   | 250       | 4.14%   |
| 5.01-6.0   | 233       | 3.86%   |
| 8.01-16.0  | 165       | 2.73%   |
| 2.01-3.0   | 53        | 0.88%   |
| 16.01-24.0 | 11        | 0.18%   |
| 4.01-5.0   | 3         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 787       | 11.06%  |
| AU Optronics            | 775       | 10.89%  |
| BOE                     | 623       | 8.75%   |
| LG Display              | 551       | 7.74%   |
| Chimei Innolux          | 545       | 7.66%   |
| Dell                    | 507       | 7.12%   |
| Goldstar                | 431       | 6.06%   |
| Acer                    | 289       | 4.06%   |
| AOC                     | 234       | 3.29%   |
| BenQ                    | 218       | 3.06%   |
| Hewlett-Packard         | 207       | 2.91%   |
| Sharp                   | 197       | 2.77%   |
| Ancor Communications    | 187       | 2.63%   |
| Philips                 | 136       | 1.91%   |
| Lenovo                  | 120       | 1.69%   |
| ViewSonic               | 98        | 1.38%   |
| PANDA                   | 97        | 1.36%   |
| Apple                   | 85        | 1.19%   |
| Iiyama                  | 80        | 1.12%   |
| ASUSTek Computer        | 76        | 1.07%   |
| InfoVision              | 54        | 0.76%   |
| LG Electronics          | 52        | 0.73%   |
| Sony                    | 41        | 0.58%   |
| MSI                     | 39        | 0.55%   |
| Unknown                 | 36        | 0.51%   |
| NEC Computers           | 36        | 0.51%   |
| CSO                     | 34        | 0.48%   |
| Chi Mei Optoelectronics | 29        | 0.41%   |
| Eizo                    | 27        | 0.38%   |
| Gigabyte Technology     | 25        | 0.35%   |
| Fujitsu Siemens         | 19        | 0.27%   |
| Panasonic               | 18        | 0.25%   |
| Sceptre Tech            | 17        | 0.24%   |
| Toshiba                 | 16        | 0.22%   |
| Vizio                   | 14        | 0.2%    |
| HannStar                | 14        | 0.2%    |
| Pixio                   | 13        | 0.18%   |
| Unknown                 | 11        | 0.15%   |
| Valve                   | 10        | 0.14%   |
| Hitachi                 | 10        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 46        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 33        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 32        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 29        | 0.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 27        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 25        | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 24        | 0.32%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 24        | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 23        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 22        | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 22        | 0.3%    |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 22        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 21        | 0.28%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 19        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 17        | 0.23%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 17        | 0.23%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 17        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 16        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 16        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 15        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 15        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 14        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 13        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 13        | 0.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 13        | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 13        | 0.17%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 13        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 12        | 0.16%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.16%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 11        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3268      | 48.81%  |
| 1366x768 (WXGA)    | 783       | 11.7%   |
| 3840x2160 (4K)     | 525       | 7.84%   |
| 2560x1440 (QHD)    | 503       | 7.51%   |
| 1920x1200 (WUXGA)  | 189       | 2.82%   |
| 1600x900 (HD+)     | 186       | 2.78%   |
| 1680x1050 (WSXGA+) | 136       | 2.03%   |
| 3440x1440          | 126       | 1.88%   |
| 1280x1024 (SXGA)   | 118       | 1.76%   |
| Unknown            | 109       | 1.63%   |
| 1440x900 (WXGA+)   | 94        | 1.4%    |
| 2560x1080          | 83        | 1.24%   |
| 1280x800 (WXGA)    | 55        | 0.82%   |
| 2560x1600          | 53        | 0.79%   |
| 3840x1080          | 47        | 0.7%    |
| 1360x768           | 42        | 0.63%   |
| 2880x1800          | 40        | 0.6%    |
| 3840x2400          | 31        | 0.46%   |
| 3840x1600          | 20        | 0.3%    |
| 3200x1800 (QHD+)   | 20        | 0.3%    |
| 2256x1504          | 20        | 0.3%    |
| 2160x1440          | 20        | 0.3%    |
| 1920x540           | 16        | 0.24%   |
| 2736x1824          | 14        | 0.21%   |
| 3000x2000          | 12        | 0.18%   |
| 7680x2160          | 9         | 0.13%   |
| 3072x1920          | 9         | 0.13%   |
| 1920x1280          | 9         | 0.13%   |
| 5120x1440          | 8         | 0.12%   |
| 1600x1200          | 8         | 0.12%   |
| 5760x1080          | 7         | 0.1%    |
| 4480x1440          | 7         | 0.1%    |
| 2240x1400          | 7         | 0.1%    |
| 1024x768 (XGA)     | 7         | 0.1%    |
| 1280x720 (HD)      | 6         | 0.09%   |
| 1024x600           | 6         | 0.09%   |
| 6400x2160          | 4         | 0.06%   |
| 6400x1440          | 4         | 0.06%   |
| 3840x1200          | 4         | 0.06%   |
| 3286x1080          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1574      | 22.25%  |
| 13      | 714       | 10.09%  |
| 27      | 698       | 9.87%   |
| 24      | 680       | 9.61%   |
| 14      | 593       | 8.38%   |
| 23      | 496       | 7.01%   |
| 21      | 394       | 5.57%   |
| Unknown | 347       | 4.91%   |
| 17      | 243       | 3.44%   |
| 34      | 171       | 2.42%   |
| 31      | 146       | 2.06%   |
| 19      | 142       | 2.01%   |
| 12      | 124       | 1.75%   |
| 18      | 97        | 1.37%   |
| 22      | 96        | 1.36%   |
| 20      | 68        | 0.96%   |
| 16      | 54        | 0.76%   |
| 11      | 49        | 0.69%   |
| 72      | 40        | 0.57%   |
| 84      | 38        | 0.54%   |
| 25      | 36        | 0.51%   |
| 40      | 26        | 0.37%   |
| 48      | 22        | 0.31%   |
| 54      | 21        | 0.3%    |
| 32      | 21        | 0.3%    |
| 28      | 19        | 0.27%   |
| 26      | 18        | 0.25%   |
| 10      | 18        | 0.25%   |
| 37      | 17        | 0.24%   |
| 29      | 17        | 0.24%   |
| 46      | 11        | 0.16%   |
| 35      | 9         | 0.13%   |
| 49      | 7         | 0.1%    |
| 33      | 7         | 0.1%    |
| 65      | 6         | 0.08%   |
| 42      | 6         | 0.08%   |
| 74      | 5         | 0.07%   |
| 43      | 5         | 0.07%   |
| 39      | 5         | 0.07%   |
| 38      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2529      | 36.97%  |
| 501-600        | 1672      | 24.44%  |
| 401-500        | 703       | 10.28%  |
| 201-300        | 590       | 8.63%   |
| Unknown        | 347       | 5.07%   |
| 351-400        | 303       | 4.43%   |
| 601-700        | 250       | 3.65%   |
| 701-800        | 202       | 2.95%   |
| 1501-2000      | 84        | 1.23%   |
| 1001-1500      | 83        | 1.21%   |
| 801-900        | 61        | 0.89%   |
| 901-1000       | 13        | 0.19%   |
| 101-200        | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4689      | 76.08%  |
| 16/10   | 668       | 10.84%  |
| Unknown | 298       | 4.84%   |
| 21/9    | 211       | 3.42%   |
| 5/4     | 120       | 1.95%   |
| 3/2     | 104       | 1.69%   |
| 4/3     | 31        | 0.5%    |
| 32/9    | 29        | 0.47%   |
| 2.65    | 4         | 0.06%   |
| 0.62    | 3         | 0.05%   |
| 1.96    | 2         | 0.03%   |
| 3.40    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.57    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1571      | 22.57%  |
| 201-250        | 1307      | 18.78%  |
| 81-90          | 975       | 14.01%  |
| 301-350        | 717       | 10.3%   |
| 351-500        | 368       | 5.29%   |
| Unknown        | 347       | 4.99%   |
| 71-80          | 334       | 4.8%    |
| 151-200        | 289       | 4.15%   |
| 251-300        | 249       | 3.58%   |
| 121-130        | 167       | 2.4%    |
| 141-150        | 133       | 1.91%   |
| More than 1000 | 130       | 1.87%   |
| 61-70          | 111       | 1.59%   |
| 501-1000       | 105       | 1.51%   |
| 51-60          | 52        | 0.75%   |
| 111-120        | 43        | 0.62%   |
| 131-140        | 23        | 0.33%   |
| 91-100         | 22        | 0.32%   |
| 41-50          | 16        | 0.23%   |
| 1-40           | 1         | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2017      | 30.07%  |
| 51-100        | 2015      | 30.04%  |
| 101-120       | 1443      | 21.51%  |
| 161-240       | 545       | 8.13%   |
| Unknown       | 347       | 5.17%   |
| More than 240 | 235       | 3.5%    |
| 1-50          | 105       | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4354      | 72.51%  |
| 2     | 1299      | 21.63%  |
| 3     | 219       | 3.65%   |
| 0     | 113       | 1.88%   |
| 4     | 17        | 0.28%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3319      | 37.93%  |
| Realtek Semiconductor             | 3164      | 36.16%  |
| Qualcomm Atheros                  | 838       | 9.58%   |
| Broadcom                          | 312       | 3.57%   |
| MediaTek                          | 130       | 1.49%   |
| TP-Link                           | 91        | 1.04%   |
| Ralink Technology                 | 75        | 0.86%   |
| Microsoft                         | 63        | 0.72%   |
| Broadcom Limited                  | 61        | 0.7%    |
| Marvell Technology Group          | 54        | 0.62%   |
| Ralink                            | 45        | 0.51%   |
| ASIX Electronics                  | 44        | 0.5%    |
| Lenovo                            | 43        | 0.49%   |
| Samsung Electronics               | 30        | 0.34%   |
| Qualcomm                          | 30        | 0.34%   |
| Sierra Wireless                   | 29        | 0.33%   |
| Xiaomi                            | 26        | 0.3%    |
| DisplayLink                       | 26        | 0.3%    |
| Ericsson Business Mobile Networks | 25        | 0.29%   |
| Aquantia                          | 24        | 0.27%   |
| D-Link                            | 21        | 0.24%   |
| NetGear                           | 19        | 0.22%   |
| Qualcomm Atheros Communications   | 18        | 0.21%   |
| Dell                              | 16        | 0.18%   |
| Hewlett-Packard                   | 15        | 0.17%   |
| Apple                             | 15        | 0.17%   |
| Google                            | 14        | 0.16%   |
| Nvidia                            | 13        | 0.15%   |
| Huawei Technologies               | 13        | 0.15%   |
| Microchip Technology              | 11        | 0.13%   |
| Mellanox Technologies             | 11        | 0.13%   |
| ASUSTek Computer                  | 9         | 0.1%    |
| Linksys                           | 8         | 0.09%   |
| Cypress Semiconductor             | 8         | 0.09%   |
| Fibocom                           | 7         | 0.08%   |
| D-Link System                     | 7         | 0.08%   |
| JMicron Technology                | 6         | 0.07%   |
| Edimax Technology                 | 6         | 0.07%   |
| Oculus VR                         | 5         | 0.06%   |
| Motorola PCS                      | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2260      | 21.93%  |
| Intel Wi-Fi 6 AX200                                               | 513       | 4.98%   |
| Intel I211 Gigabit Network Connection                             | 360       | 3.49%   |
| Intel Wireless 8265 / 8275                                        | 254       | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 233       | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 186       | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179       | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 168       | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 165       | 1.6%    |
| Intel Ethernet Connection (2) I219-V                              | 152       | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 152       | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 150       | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 145       | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 135       | 1.31%   |
| Intel Wireless 8260                                               | 131       | 1.27%   |
| Intel Wireless 7265                                               | 130       | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 121       | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 106       | 1.03%   |
| Intel Wireless 7260                                               | 102       | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 99        | 0.96%   |
| Intel Wireless-AC 9260                                            | 98        | 0.95%   |
| Intel Wireless 3165                                               | 91        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 91        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 87        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 86        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 83        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 81        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 81        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 79        | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 78        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 78        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 72        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 67        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 63        | 0.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 58        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 56        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 55        | 0.53%   |
| Intel Wireless 3160                                               | 49        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 47        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2581      | 54.14%  |
| Realtek Semiconductor           | 668       | 14.01%  |
| Qualcomm Atheros                | 657       | 13.78%  |
| Broadcom                        | 238       | 4.99%   |
| MediaTek                        | 126       | 2.64%   |
| TP-Link                         | 77        | 1.62%   |
| Ralink Technology               | 75        | 1.57%   |
| Microsoft                       | 56        | 1.17%   |
| Broadcom Limited                | 47        | 0.99%   |
| Ralink                          | 45        | 0.94%   |
| Sierra Wireless                 | 29        | 0.61%   |
| Qualcomm                        | 26        | 0.55%   |
| Qualcomm Atheros Communications | 18        | 0.38%   |
| D-Link                          | 18        | 0.38%   |
| NetGear                         | 17        | 0.36%   |
| Marvell Technology Group        | 16        | 0.34%   |
| Dell                            | 9         | 0.19%   |
| ASUSTek Computer                | 9         | 0.19%   |
| Linksys                         | 8         | 0.17%   |
| Fibocom                         | 7         | 0.15%   |
| Hewlett-Packard                 | 6         | 0.13%   |
| Edimax Technology               | 6         | 0.13%   |
| AVM                             | 4         | 0.08%   |
| Wilocity                        | 3         | 0.06%   |
| Mercucys                        | 3         | 0.06%   |
| D-Link System                   | 3         | 0.06%   |
| Belkin Components               | 3         | 0.06%   |
| Xiaomi                          | 2         | 0.04%   |
| Tenda                           | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| IMC Networks                    | 2         | 0.04%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Sagem                           | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 513       | 10.71%  |
| Intel Wireless 8265 / 8275                                     | 254       | 5.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 165       | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 152       | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 150       | 3.13%   |
| Intel Wi-Fi 6 AX201                                            | 145       | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 135       | 2.82%   |
| Intel Wireless 8260                                            | 131       | 2.74%   |
| Intel Wireless 7265                                            | 130       | 2.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 121       | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 106       | 2.21%   |
| Intel Wireless 7260                                            | 102       | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 99        | 2.07%   |
| Intel Wireless-AC 9260                                         | 98        | 2.05%   |
| Intel Wireless 3165                                            | 91        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 91        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 87        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 86        | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 83        | 1.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 81        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 79        | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 78        | 1.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 72        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 63        | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 58        | 1.21%   |
| Intel Wireless 3160                                            | 49        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 43        | 0.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 42        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 37        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 34        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                            | 30        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29        | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 28        | 0.58%   |
| Realtek 802.11ac NIC                                           | 27        | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 26        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                | 26        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2869      | 54.38%  |
| Intel                                  | 1659      | 31.44%  |
| Qualcomm Atheros                       | 239       | 4.53%   |
| Broadcom                               | 116       | 2.2%    |
| ASIX Electronics                       | 44        | 0.83%   |
| Lenovo                                 | 41        | 0.78%   |
| Marvell Technology Group               | 38        | 0.72%   |
| Samsung Electronics                    | 30        | 0.57%   |
| DisplayLink                            | 26        | 0.49%   |
| Xiaomi                                 | 24        | 0.45%   |
| Aquantia                               | 24        | 0.45%   |
| Apple                                  | 15        | 0.28%   |
| TP-Link                                | 14        | 0.27%   |
| Broadcom Limited                       | 14        | 0.27%   |
| Nvidia                                 | 13        | 0.25%   |
| Google                                 | 12        | 0.23%   |
| Mellanox Technologies                  | 11        | 0.21%   |
| Cypress Semiconductor                  | 8         | 0.15%   |
| Microsoft                              | 6         | 0.11%   |
| JMicron Technology                     | 6         | 0.11%   |
| Huawei Technologies                    | 6         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.08%   |
| Qualcomm                               | 4         | 0.08%   |
| Motorola PCS                           | 4         | 0.08%   |
| MediaTek                               | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| D-Link System                          | 4         | 0.08%   |
| QLogic                                 | 3         | 0.06%   |
| OPPO Electronics                       | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| D-Link                                 | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| NetGear                                | 2         | 0.04%   |
| IBM                                    | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| VIA Technologies                       | 1         | 0.02%   |
| Standard Microsystems [SMC]            | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| QNAP System                            | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2260      | 41.77%  |
| Intel I211 Gigabit Network Connection                             | 360       | 6.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 233       | 4.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 186       | 3.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179       | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 168       | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 152       | 2.81%   |
| Intel Ethernet Connection (7) I219-V                              | 81        | 1.5%    |
| Intel Ethernet Controller I225-V                                  | 78        | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 67        | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 56        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 55        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 47        | 0.87%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 41        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 39        | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 38        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 37        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 35        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 32        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 28        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 26        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 26        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                             | 22        | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 21        | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 21        | 0.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 15        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4919      | 51.42%  |
| WiFi     | 4545      | 47.51%  |
| Modem    | 92        | 0.96%   |
| Unknown  | 10        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3469      | 56.11%  |
| Ethernet | 2712      | 43.86%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3115      | 52.94%  |
| 1     | 2520      | 42.83%  |
| 3     | 169       | 2.87%   |
| 0     | 48        | 0.82%   |
| 4     | 19        | 0.32%   |
| 5     | 7         | 0.12%   |
| 6     | 5         | 0.08%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4997      | 84.03%  |
| Yes  | 950       | 15.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2257      | 54.37%  |
| Realtek Semiconductor           | 364       | 8.77%   |
| Cambridge Silicon Radio         | 297       | 7.15%   |
| Qualcomm Atheros Communications | 257       | 6.19%   |
| Broadcom                        | 162       | 3.9%    |
| IMC Networks                    | 140       | 3.37%   |
| Lite-On Technology              | 130       | 3.13%   |
| Foxconn / Hon Hai               | 113       | 2.72%   |
| ASUSTek Computer                | 100       | 2.41%   |
| Apple                           | 88        | 2.12%   |
| Realtek                         | 42        | 1.01%   |
| Dell                            | 32        | 0.77%   |
| MediaTek                        | 27        | 0.65%   |
| Hewlett-Packard                 | 18        | 0.43%   |
| TP-Link                         | 15        | 0.36%   |
| Marvell Semiconductor           | 15        | 0.36%   |
| Toshiba                         | 13        | 0.31%   |
| HTC (High Tech Computer)        | 13        | 0.31%   |
| Ralink                          | 11        | 0.26%   |
| USI                             | 9         | 0.22%   |
| Edimax Technology               | 8         | 0.19%   |
| Foxconn International           | 6         | 0.14%   |
| Integrated System Solution      | 4         | 0.1%    |
| Dynex                           | 4         | 0.1%    |
| Micro Star International        | 3         | 0.07%   |
| Chicony Electronics             | 3         | 0.07%   |
| Askey Computer                  | 3         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.05%   |
| Ralink Technology               | 2         | 0.05%   |
| Opticis                         | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |
| Alps Electric                   | 2         | 0.05%   |
| Syntek                          | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 730       | 17.55%  |
| Intel AX200 Bluetooth                                                | 489       | 11.76%  |
| Intel AX201 Bluetooth                                                | 331       | 7.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 297       | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 296       | 7.12%   |
| Realtek Bluetooth Radio                                              | 230       | 5.53%   |
| Qualcomm Atheros  Bluetooth Device                                   | 134       | 3.22%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 118       | 2.84%   |
| Intel AX210 Bluetooth                                                | 100       | 2.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 92        | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 82        | 1.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 57        | 1.37%   |
| Intel Bluetooth Device                                               | 54        | 1.3%    |
| IMC Networks Bluetooth Radio                                         | 48        | 1.15%   |
| Lite-On Bluetooth Device                                             | 47        | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 45        | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 44        | 1.06%   |
| Apple Bluetooth Host Controller                                      | 44        | 1.06%   |
| Realtek Bluetooth Radio                                              | 42        | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                                    | 42        | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 41        | 0.99%   |
| IMC Networks Wireless_Device                                         | 40        | 0.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 39        | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 37        | 0.89%   |
| IMC Networks Bluetooth Device                                        | 34        | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 31        | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 27        | 0.65%   |
| Apple Bluetooth USB Host Controller                                  | 27        | 0.65%   |
| MediaTek Wireless_Device                                             | 26        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 23        | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 21        | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 19        | 0.46%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 17        | 0.41%   |
| TP-Link UB500 Adapter                                                | 15        | 0.36%   |
| Realtek RTL8821A Bluetooth                                           | 15        | 0.36%   |
| Lite-On Wireless_Device                                              | 14        | 0.34%   |
| ASUS Bluetooth Radio                                                 | 14        | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 13        | 0.31%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 13        | 0.31%   |
| Realtek RTL8723B Bluetooth                                           | 12        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3783      | 40.9%   |
| AMD                                  | 2252      | 24.35%  |
| Nvidia                               | 1697      | 18.35%  |
| C-Media Electronics                  | 216       | 2.34%   |
| Logitech                             | 102       | 1.1%    |
| Kingston Technology                  | 76        | 0.82%   |
| Focusrite-Novation                   | 66        | 0.71%   |
| Texas Instruments                    | 60        | 0.65%   |
| JMTek                                | 57        | 0.62%   |
| SteelSeries ApS                      | 55        | 0.59%   |
| Realtek Semiconductor                | 49        | 0.53%   |
| Razer USA                            | 49        | 0.53%   |
| Lenovo                               | 43        | 0.46%   |
| Creative Labs                        | 43        | 0.46%   |
| Creative Technology                  | 39        | 0.42%   |
| Corsair                              | 39        | 0.42%   |
| Blue Microphones                     | 34        | 0.37%   |
| Samson Technologies                  | 26        | 0.28%   |
| GN Netcom                            | 24        | 0.26%   |
| ASUSTek Computer                     | 23        | 0.25%   |
| Valve Software                       | 20        | 0.22%   |
| GYROCOM C&C                          | 19        | 0.21%   |
| Yamaha                               | 18        | 0.19%   |
| Sony                                 | 18        | 0.19%   |
| Generalplus Technology               | 18        | 0.19%   |
| Apple                                | 18        | 0.19%   |
| BEHRINGER International              | 17        | 0.18%   |
| Plantronics                          | 14        | 0.15%   |
| Audio-Technica                       | 14        | 0.15%   |
| SAVITECH                             | 13        | 0.14%   |
| FiiO Electronics Technology          | 13        | 0.14%   |
| XMOS                                 | 12        | 0.13%   |
| M-Audio                              | 11        | 0.12%   |
| RODE Microphones                     | 10        | 0.11%   |
| Dell                                 | 10        | 0.11%   |
| Cambridge Silicon Radio              | 9         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 8         | 0.09%   |
| Microsoft                            | 8         | 0.09%   |
| Giga-Byte Technology                 | 8         | 0.09%   |
| DSEA A/S                             | 8         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 767       | 6.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 551       | 4.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 524       | 4.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 385       | 3.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 320       | 2.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 314       | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 293       | 2.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 283       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 243       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 236       | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 224       | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 220       | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 202       | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 190       | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 171       | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 165       | 1.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 163       | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 160       | 1.44%   |
| AMD Navi 10 HDMI Audio                                                     | 160       | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 136       | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                              | 130       | 1.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 130       | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 124       | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 124       | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 124       | 1.12%   |
| Intel Broadwell-U Audio Controller                                         | 123       | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 118       | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 117       | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 115       | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 113       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 108       | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 103       | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 101       | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 97        | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 93        | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 93        | 0.84%   |
| AMD FCH Azalia Controller                                                  | 86        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 78        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 74        | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 73        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1038      | 20.88%  |
| SK hynix                     | 772       | 15.53%  |
| Kingston                     | 627       | 12.61%  |
| Corsair                      | 487       | 9.8%    |
| Micron Technology            | 474       | 9.54%   |
| Crucial                      | 398       | 8.01%   |
| G.Skill                      | 320       | 6.44%   |
| Unknown                      | 271       | 5.45%   |
| A-DATA Technology            | 99        | 1.99%   |
| Ramaxel Technology           | 77        | 1.55%   |
| Elpida                       | 47        | 0.95%   |
| Team                         | 45        | 0.91%   |
| Patriot                      | 42        | 0.84%   |
| GOODRAM                      | 28        | 0.56%   |
| Nanya Technology             | 23        | 0.46%   |
| Unknown (ABCD)               | 20        | 0.4%    |
| Smart                        | 18        | 0.36%   |
| Transcend                    | 17        | 0.34%   |
| Unknown                      | 15        | 0.3%    |
| PNY                          | 12        | 0.24%   |
| AMD                          | 11        | 0.22%   |
| Goldkey                      | 9         | 0.18%   |
| Apacer                       | 8         | 0.16%   |
| Smart Brazil                 | 6         | 0.12%   |
| Teikon                       | 5         | 0.1%    |
| Golden Empire                | 5         | 0.1%    |
| GeIL                         | 5         | 0.1%    |
| Wilk Elektronik              | 4         | 0.08%   |
| Silicon Power                | 4         | 0.08%   |
| Neo Forza                    | 4         | 0.08%   |
| V-GeN                        | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| KLEVV                        | 3         | 0.06%   |
| Kingmax                      | 3         | 0.06%   |
| GSkill                       | 3         | 0.06%   |
| Avant                        | 3         | 0.06%   |
| ASint Technology             | 3         | 0.06%   |
| 48spaces                     | 3         | 0.06%   |
| Wilk                         | 2         | 0.04%   |
| Thermaltake                  | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 65        | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 59        | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 57        | 1.07%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 53        | 1%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 52        | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 32        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 31        | 0.58%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 29        | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 25        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 24        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 23        | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.41%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 22        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 21        | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.38%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 20        | 0.38%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.36%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 18        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.32%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.32%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 17        | 0.32%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 17        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 16        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2674      | 62.58%  |
| DDR3    | 1037      | 24.27%  |
| LPDDR4  | 155       | 3.63%   |
| LPDDR3  | 128       | 3%      |
| Unknown | 64        | 1.5%    |
| SDRAM   | 56        | 1.31%   |
| DDR2    | 56        | 1.31%   |
| DDR5    | 46        | 1.08%   |
| LPDDR5  | 42        | 0.98%   |
| DDR     | 14        | 0.33%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2219      | 51.97%  |
| DIMM         | 1661      | 38.9%   |
| Row Of Chips | 346       | 8.1%    |
| Chip         | 31        | 0.73%   |
| Unknown      | 10        | 0.23%   |
| RIMM         | 2         | 0.05%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2121      | 45.89%  |
| 4096  | 1064      | 23.02%  |
| 16384 | 846       | 18.3%   |
| 2048  | 325       | 7.03%   |
| 32768 | 204       | 4.41%   |
| 1024  | 55        | 1.19%   |
| 512   | 6         | 0.13%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 784       | 16.72%  |
| 2667    | 768       | 16.38%  |
| 1600    | 678       | 14.46%  |
| 2400    | 411       | 8.76%   |
| 2133    | 258       | 5.5%    |
| 3600    | 241       | 5.14%   |
| 1333    | 201       | 4.29%   |
| 1867    | 112       | 2.39%   |
| 1334    | 87        | 1.86%   |
| 3266    | 82        | 1.75%   |
| 4267    | 80        | 1.71%   |
| 3400    | 79        | 1.68%   |
| 3466    | 78        | 1.66%   |
| 3000    | 59        | 1.26%   |
| 3733    | 55        | 1.17%   |
| 2933    | 46        | 0.98%   |
| 667     | 46        | 0.98%   |
| 6400    | 45        | 0.96%   |
| 3800    | 41        | 0.87%   |
| 4800    | 38        | 0.81%   |
| 1067    | 36        | 0.77%   |
| 1866    | 33        | 0.7%    |
| Unknown | 31        | 0.66%   |
| 3866    | 30        | 0.64%   |
| 2800    | 30        | 0.64%   |
| 1066    | 28        | 0.6%    |
| 800     | 26        | 0.55%   |
| 3666    | 24        | 0.51%   |
| 2666    | 24        | 0.51%   |
| 4266    | 20        | 0.43%   |
| 4199    | 18        | 0.38%   |
| 8400    | 17        | 0.36%   |
| 400     | 12        | 0.26%   |
| 3333    | 11        | 0.23%   |
| 2048    | 10        | 0.21%   |
| 1800    | 10        | 0.21%   |
| 4000    | 9         | 0.19%   |
| 3066    | 9         | 0.19%   |
| 2733    | 9         | 0.19%   |
| 3151    | 8         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 32        | 36.78%  |
| Brother Industries       | 15        | 17.24%  |
| Samsung Electronics      | 13        | 14.94%  |
| Canon                    | 11        | 12.64%  |
| Seiko Epson              | 4         | 4.6%    |
| Prolific Technology      | 3         | 3.45%   |
| Dymo-CoStar              | 3         | 3.45%   |
| Zebra                    | 1         | 1.15%   |
| STMicroelectronics       | 1         | 1.15%   |
| Ricoh                    | 1         | 1.15%   |
| QinHeng Electronics      | 1         | 1.15%   |
| Magic Control Technology | 1         | 1.15%   |
| Fuji Xerox               | 1         | 1.15%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 3         | 3.45%   |
| Prolific PL2305 Parallel Port                             | 3         | 3.45%   |
| HP DeskJet 2130 series                                    | 3         | 3.45%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.3%    |
| HP Officejet Pro 8100                                     | 2         | 2.3%    |
| HP LaserJet P2015 series                                  | 2         | 2.3%    |
| HP LaserJet 1022                                          | 2         | 2.3%    |
| HP LaserJet 1012                                          | 2         | 2.3%    |
| HP DeskJet 840c                                           | 2         | 2.3%    |
| HP Deskjet 3050 J610 series                               | 2         | 2.3%    |
| HP DeskJet 2600 series                                    | 2         | 2.3%    |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.3%    |
| Brother Printer                                           | 2         | 2.3%    |
| Brother HL-5370DW series                                  | 2         | 2.3%    |
| Zebra LP2844 Printer                                      | 1         | 1.15%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.15%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.15%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.15%   |
| Seiko Epson Printer                                       | 1         | 1.15%   |
| Seiko Epson L3110 Series                                  | 1         | 1.15%   |
| Samsung SCX-4200 series                                   | 1         | 1.15%   |
| Samsung SCX-3200 Series                                   | 1         | 1.15%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.15%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.15%   |
| Samsung M267x 287x Series                                 | 1         | 1.15%   |
| Samsung M2020 Series                                      | 1         | 1.15%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.15%   |
| Samsung C1860 Series                                      | 1         | 1.15%   |
| Ricoh SP 150SU                                            | 1         | 1.15%   |
| QinHeng CH340S                                            | 1         | 1.15%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.15%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.15%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.15%   |
| HP LaserJet P1005                                         | 1         | 1.15%   |
| HP LaserJet M14-M17                                       | 1         | 1.15%   |
| HP LaserJet 1320                                          | 1         | 1.15%   |
| HP LaserJet 1200                                          | 1         | 1.15%   |
| HP LaserJet 1020                                          | 1         | 1.15%   |
| HP LaserJet 1018                                          | 1         | 1.15%   |
| HP Ink Tank 310 series                                    | 1         | 1.15%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 747       | 19.97%  |
| IMC Networks                           | 391       | 10.45%  |
| Logitech                               | 334       | 8.93%   |
| Microdia                               | 325       | 8.69%   |
| Acer                                   | 283       | 7.56%   |
| Realtek Semiconductor                  | 250       | 6.68%   |
| Quanta                                 | 198       | 5.29%   |
| Sunplus Innovation Technology          | 158       | 4.22%   |
| Cheng Uei Precision Industry (Foxlink) | 123       | 3.29%   |
| Syntek                                 | 103       | 2.75%   |
| Lite-On Technology                     | 95        | 2.54%   |
| Apple                                  | 82        | 2.19%   |
| Suyin                                  | 60        | 1.6%    |
| Luxvisions Innotech Limited            | 57        | 1.52%   |
| Microsoft                              | 48        | 1.28%   |
| Bison Electronics                      | 46        | 1.23%   |
| Samsung Electronics                    | 44        | 1.18%   |
| Silicon Motion                         | 40        | 1.07%   |
| Alcor Micro                            | 38        | 1.02%   |
| Lenovo                                 | 26        | 0.7%    |
| Z-Star Microelectronics                | 22        | 0.59%   |
| Valve Software                         | 17        | 0.45%   |
| MacroSilicon                           | 16        | 0.43%   |
| Sonix Technology                       | 14        | 0.37%   |
| ARC International                      | 13        | 0.35%   |
| SunplusIT                              | 11        | 0.29%   |
| Razer USA                              | 11        | 0.29%   |
| KYE Systems (Mouse Systems)            | 11        | 0.29%   |
| Importek                               | 11        | 0.29%   |
| ALi                                    | 11        | 0.29%   |
| Ricoh                                  | 10        | 0.27%   |
| Primax Electronics                     | 9         | 0.24%   |
| Generalplus Technology                 | 9         | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.19%   |
| LG Electronics                         | 7         | 0.19%   |
| Creative Technology                    | 7         | 0.19%   |
| Jieli Technology                       | 6         | 0.16%   |
| Google                                 | 6         | 0.16%   |
| Trust                                  | 5         | 0.13%   |
| Hewlett-Packard                        | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 231       | 6.1%    |
| Microdia Integrated_Webcam_HD                                              | 162       | 4.28%   |
| IMC Networks Integrated Camera                                             | 140       | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 113       | 2.98%   |
| Acer Integrated Camera                                                     | 92        | 2.43%   |
| Realtek Integrated_Webcam_HD                                               | 86        | 2.27%   |
| Chicony HD Webcam                                                          | 83        | 2.19%   |
| Logitech HD Pro Webcam C920                                                | 70        | 1.85%   |
| Syntek Integrated Camera                                                   | 66        | 1.74%   |
| Sunplus Integrated_Webcam_HD                                               | 64        | 1.69%   |
| Logitech Webcam C270                                                       | 55        | 1.45%   |
| Quanta HD User Facing                                                      | 45        | 1.19%   |
| Lite-On Integrated Camera                                                  | 45        | 1.19%   |
| Samsung Galaxy A5 (MTP)                                                    | 44        | 1.16%   |
| Acer HD Webcam                                                             | 42        | 1.11%   |
| Acer SunplusIT Integrated Camera                                           | 39        | 1.03%   |
| Apple FaceTime HD Camera (Built-in)                                        | 32        | 0.85%   |
| Chicony USB2.0 Camera                                                      | 31        | 0.82%   |
| Chicony Integrated Camera (1280x720@30)                                    | 31        | 0.82%   |
| Chicony HP Wide Vision HD Camera                                           | 31        | 0.82%   |
| Chicony HP HD Camera                                                       | 30        | 0.79%   |
| Logitech C922 Pro Stream Webcam                                            | 29        | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 29        | 0.77%   |
| Microdia Integrated Webcam                                                 | 28        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 26        | 0.69%   |
| Chicony HD User Facing                                                     | 25        | 0.66%   |
| Realtek USB Camera                                                         | 24        | 0.63%   |
| Microdia USB 2.0 Camera                                                    | 24        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 24        | 0.63%   |
| Chicony EasyCamera                                                         | 23        | 0.61%   |
| Quanta HP Wide Vision HD Camera                                            | 22        | 0.58%   |
| Acer EasyCamera                                                            | 22        | 0.58%   |
| Realtek Integrated Webcam                                                  | 21        | 0.55%   |
| Microdia Webcam Vitade AF                                                  | 21        | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                                               | 21        | 0.55%   |
| Acer Lenovo EasyCamera                                                     | 21        | 0.55%   |
| Quanta VGA WebCam                                                          | 19        | 0.5%    |
| Logitech Webcam C310                                                       | 19        | 0.5%    |
| Logitech BRIO Ultra HD Webcam                                              | 19        | 0.5%    |
| Lite-On HP HD Camera                                                       | 19        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 315       | 39.03%  |
| Validity Sensors                   | 202       | 25.03%  |
| Shenzhen Goodix Technology         | 147       | 18.22%  |
| Elan Microelectronics              | 49        | 6.07%   |
| LighTuning Technology              | 27        | 3.35%   |
| Upek                               | 26        | 3.22%   |
| AuthenTec                          | 21        | 2.6%    |
| STMicroelectronics                 | 9         | 1.12%   |
| Samsung Electronics                | 4         | 0.5%    |
| Microsoft                          | 3         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.25%   |
| Focal-systems.Corp                 | 1         | 0.12%   |
| DigitalPersona                     | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 111       | 13.75%  |
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 9.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 49        | 6.07%   |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 5.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 4.58%   |
| Synaptics UWP WBDI                                                         | 31        | 3.84%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 3.72%   |
| Elan ELAN:Fingerprint                                                      | 30        | 3.72%   |
| Shenzhen Goodix FingerPrint                                                | 27        | 3.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 2.85%   |
| Synaptics  WBDI                                                            | 22        | 2.73%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.48%   |
| Synaptics WBDI                                                             | 19        | 2.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 19        | 2.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.23%   |
| Elan ELAN:ARM-M4                                                           | 17        | 2.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.98%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 1.86%   |
| Validity Sensors VFS491                                                    | 13        | 1.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.36%   |
| AuthenTec AES2810                                                          | 11        | 1.36%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.24%   |
| Synaptics UWP WBDI Device                                                  | 9         | 1.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.12%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 0.87%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.62%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.62%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.5%    |
| Synaptics WBDI Device                                                      | 4         | 0.5%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.37%   |
| Samsung Fingerprint Device                                                 | 3         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 128       | 41.29%  |
| Broadcom                          | 106       | 34.19%  |
| Upek                              | 18        | 5.81%   |
| Lenovo                            | 10        | 3.23%   |
| Clay Logic                        | 8         | 2.58%   |
| Advanced Card Systems             | 6         | 1.94%   |
| Yubico.com                        | 5         | 1.61%   |
| O2 Micro                          | 5         | 1.61%   |
| SCM Microsystems                  | 4         | 1.29%   |
| Reiner SCT Kartensysteme          | 4         | 1.29%   |
| Gemalto (was Gemplus)             | 4         | 1.29%   |
| Aladdin Knowledge Systems         | 3         | 0.97%   |
| OmniKey                           | 2         | 0.65%   |
| VASCO Data Security International | 1         | 0.32%   |
| Realtek Semiconductor             | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Fujitsu Siemens Computers         | 1         | 0.32%   |
| Chicony Electronics               | 1         | 0.32%   |
| Aladdin R.D.                      | 1         | 0.32%   |
| Aktiv                             | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 126       | 40.65%  |
| Broadcom 5880                                                                | 31        | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 9.03%   |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 7.74%   |
| Broadcom 58200                                                               | 21        | 6.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 5.81%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 3.23%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 1.61%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 1.29%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.97%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.97%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.97%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.65%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.65%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.65%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.32%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.32%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.32%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.32%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.32%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.32%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.32%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.32%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.32%   |
| Aktiv Rutoken lite                                                           | 1         | 0.32%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.32%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4178      | 69.75%  |
| 1     | 1440      | 24.04%  |
| 2     | 297       | 4.96%   |
| 3     | 62        | 1.04%   |
| 4     | 10        | 0.17%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 789       | 35.95%  |
| Graphics card            | 413       | 18.82%  |
| Chipcard                 | 263       | 11.98%  |
| Net/wireless             | 193       | 8.79%   |
| Multimedia controller    | 146       | 6.65%   |
| Camera                   | 118       | 5.38%   |
| Unassigned class         | 51        | 2.32%   |
| Bluetooth                | 45        | 2.05%   |
| Communication controller | 44        | 2%      |
| Sound                    | 35        | 1.59%   |
| Net/ethernet             | 22        | 1%      |
| Network                  | 20        | 0.91%   |
| Storage                  | 17        | 0.77%   |
| Card reader              | 12        | 0.55%   |
| Modem                    | 9         | 0.41%   |
| Dvb card                 | 6         | 0.27%   |
| Wireless                 | 2         | 0.09%   |
| Storage/raid             | 2         | 0.09%   |
| Storage/nvme             | 2         | 0.09%   |
| Storage/ide              | 2         | 0.09%   |
| Tv card                  | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

