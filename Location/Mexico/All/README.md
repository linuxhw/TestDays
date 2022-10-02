Linux in Mexico - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Mexico/Desktop/README.md) and [notebooks](/Location/Mexico/Notebook/README.md).

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

Total: 2702

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion                    | Notebook    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [570ff509ac](https://linux-hardware.org/?probe=570ff509ac) | Sep 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [afe1282d38](https://linux-hardware.org/?probe=afe1282d38) | Sep 29, 2022 |
| GHIA          | LFI3H                       | Notebook    | [4233e4e6c5](https://linux-hardware.org/?probe=4233e4e6c5) | Sep 29, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [3e8f63475d](https://linux-hardware.org/?probe=3e8f63475d) | Sep 29, 2022 |
| GHIA          | LFI3H                       | Notebook    | [482e78460a](https://linux-hardware.org/?probe=482e78460a) | Sep 29, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4f2655de78](https://linux-hardware.org/?probe=4f2655de78) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | Notebook    | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Dell          | Latitude E5450              | Notebook    | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Intel         | NUC5i3MYBE H47781-211       | Mini pc     | [ec2541f624](https://linux-hardware.org/?probe=ec2541f624) | Sep 26, 2022 |
| HP            | Unknown                     | Notebook    | [63af86aa38](https://linux-hardware.org/?probe=63af86aa38) | Sep 25, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [68f3d2bdba](https://linux-hardware.org/?probe=68f3d2bdba) | Sep 25, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [f7e1dc7c9d](https://linux-hardware.org/?probe=f7e1dc7c9d) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [63d494787f](https://linux-hardware.org/?probe=63d494787f) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0170bcbb42](https://linux-hardware.org/?probe=0170bcbb42) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Chuwi         | CoreBook XPro               | Notebook    | [5ace2b3ea5](https://linux-hardware.org/?probe=5ace2b3ea5) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| ASUSTek       | G750JM                      | Notebook    | [2e53c11312](https://linux-hardware.org/?probe=2e53c11312) | Sep 22, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [c6a0b0d987](https://linux-hardware.org/?probe=c6a0b0d987) | Sep 22, 2022 |
| Lenovo        | G40-80 80E4                 | Notebook    | [575b85b038](https://linux-hardware.org/?probe=575b85b038) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | Notebook    | [18a0a2158c](https://linux-hardware.org/?probe=18a0a2158c) | Sep 21, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| American M... | XA133PR110                  | Notebook    | [b79d35c0bd](https://linux-hardware.org/?probe=b79d35c0bd) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [841474a64b](https://linux-hardware.org/?probe=841474a64b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | Notebook    | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d35104af13](https://linux-hardware.org/?probe=d35104af13) | Sep 19, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [c986542d56](https://linux-hardware.org/?probe=c986542d56) | Sep 18, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [a17cc62b40](https://linux-hardware.org/?probe=a17cc62b40) | Sep 18, 2022 |
| HP            | EliteBook 2740p             | Notebook    | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| HP            | Notebook                    | Notebook    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | 0CYTN6 A00                  | All in one  | [e0bddcbf09](https://linux-hardware.org/?probe=e0bddcbf09) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| Dell          | Latitude E6400              | Notebook    | [0c6b0c35e6](https://linux-hardware.org/?probe=0c6b0c35e6) | Sep 14, 2022 |
| Dell          | Latitude E6400              | Notebook    | [b4c9fcf4c3](https://linux-hardware.org/?probe=b4c9fcf4c3) | Sep 14, 2022 |
| Lanix         | AL V9                       | Notebook    | [03e7c7ece5](https://linux-hardware.org/?probe=03e7c7ece5) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [5b62dddb37](https://linux-hardware.org/?probe=5b62dddb37) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| Lanix         | AL V9                       | Notebook    | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| ECS           | G31T-M9                     | Desktop     | [547762d8bf](https://linux-hardware.org/?probe=547762d8bf) | Sep 11, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [32c5b56788](https://linux-hardware.org/?probe=32c5b56788) | Sep 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Gateway       | NE56R                       | Notebook    | [c928861fb0](https://linux-hardware.org/?probe=c928861fb0) | Sep 09, 2022 |
| Gateway       | NE56R                       | Notebook    | [3167a59b9b](https://linux-hardware.org/?probe=3167a59b9b) | Sep 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c008fc6206](https://linux-hardware.org/?probe=c008fc6206) | Sep 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [32edc5cfad](https://linux-hardware.org/?probe=32edc5cfad) | Sep 08, 2022 |
| Biostar       | H310MHP                     | Desktop     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Dell          | Latitude D410               | Notebook    | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [a5f7ef09b8](https://linux-hardware.org/?probe=a5f7ef09b8) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [a138be9eb6](https://linux-hardware.org/?probe=a138be9eb6) | Sep 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [de66677d3d](https://linux-hardware.org/?probe=de66677d3d) | Sep 03, 2022 |
| HP            | Pavilion 14                 | Notebook    | [7a2b6c5f4b](https://linux-hardware.org/?probe=7a2b6c5f4b) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [7da5af06fb](https://linux-hardware.org/?probe=7da5af06fb) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c7b43caa52](https://linux-hardware.org/?probe=c7b43caa52) | Sep 01, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| HP            | Pavilion 14                 | Notebook    | [b35151af0c](https://linux-hardware.org/?probe=b35151af0c) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| HP            | 871A                        | Mini pc     | [d6261d6fb1](https://linux-hardware.org/?probe=d6261d6fb1) | Sep 01, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Dell          | 0WG864                      | Desktop     | [234e8953bc](https://linux-hardware.org/?probe=234e8953bc) | Aug 30, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [47049b9a6a](https://linux-hardware.org/?probe=47049b9a6a) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [e3e8a26940](https://linux-hardware.org/?probe=e3e8a26940) | Aug 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [dd47181665](https://linux-hardware.org/?probe=dd47181665) | Aug 28, 2022 |
| Chuwi         | UBook X                     | Tablet      | [27c118eaf1](https://linux-hardware.org/?probe=27c118eaf1) | Aug 28, 2022 |
| GHIA          | 2 en 1                      | Tablet      | [5ed07e6854](https://linux-hardware.org/?probe=5ed07e6854) | Aug 27, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [43fdfb3cf8](https://linux-hardware.org/?probe=43fdfb3cf8) | Aug 27, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [a1f434a97c](https://linux-hardware.org/?probe=a1f434a97c) | Aug 27, 2022 |
| ECS           | A320AM4-M3D                 | Desktop     | [685960846a](https://linux-hardware.org/?probe=685960846a) | Aug 26, 2022 |
| Dell          | 0WG864                      | Desktop     | [7cbb2239ba](https://linux-hardware.org/?probe=7cbb2239ba) | Aug 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| HP            | 8245 001                    | All in one  | [d8ed4c408d](https://linux-hardware.org/?probe=d8ed4c408d) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| Pegatron      | E60                         | Desktop     | [c1aba90f51](https://linux-hardware.org/?probe=c1aba90f51) | Aug 23, 2022 |
| Dell          | 0WG864                      | Desktop     | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| HP            | ENVY m6 Notebook            | Notebook    | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [81b7ddb4e9](https://linux-hardware.org/?probe=81b7ddb4e9) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [aa44fba5de](https://linux-hardware.org/?probe=aa44fba5de) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [21d9982f20](https://linux-hardware.org/?probe=21d9982f20) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | Notebook    | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | Notebook    | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Dell          | 0WG864                      | Desktop     | [c4aee967b4](https://linux-hardware.org/?probe=c4aee967b4) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| HP            | Pavilion TS 14              | Notebook    | [145fc8369f](https://linux-hardware.org/?probe=145fc8369f) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [da2935226c](https://linux-hardware.org/?probe=da2935226c) | Aug 14, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [9e59d35488](https://linux-hardware.org/?probe=9e59d35488) | Aug 12, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Dell          | 0WG864                      | Desktop     | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [4a9c41e3fd](https://linux-hardware.org/?probe=4a9c41e3fd) | Aug 12, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [6e1650d26d](https://linux-hardware.org/?probe=6e1650d26d) | Aug 11, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [f886e2ff98](https://linux-hardware.org/?probe=f886e2ff98) | Aug 10, 2022 |
| Lenovo        | L340-15API 81LW             | Notebook    | [50eca7fa1e](https://linux-hardware.org/?probe=50eca7fa1e) | Aug 10, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [f9c85afff2](https://linux-hardware.org/?probe=f9c85afff2) | Aug 10, 2022 |
| Lenovo        | 36ED SDK0M26027 WIN 3273... | All in one  | [6481787b51](https://linux-hardware.org/?probe=6481787b51) | Aug 09, 2022 |
| ECS           | A55F-M4                     | Desktop     | [9c032723ab](https://linux-hardware.org/?probe=9c032723ab) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [726b790d1a](https://linux-hardware.org/?probe=726b790d1a) | Aug 09, 2022 |
| Intel         | D975XBX2 AAD53350-503       | Desktop     | [67f56805b0](https://linux-hardware.org/?probe=67f56805b0) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| Google        | Blorb                       | Notebook    | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Acer          | AO756                       | Notebook    | [4bc715a31c](https://linux-hardware.org/?probe=4bc715a31c) | Aug 05, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [3e02305524](https://linux-hardware.org/?probe=3e02305524) | Aug 04, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e962ba603d](https://linux-hardware.org/?probe=e962ba603d) | Jul 31, 2022 |
| HP            | ProBook 4520s               | Notebook    | [8e03860e5f](https://linux-hardware.org/?probe=8e03860e5f) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| Alienware     | 17 R4                       | Notebook    | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [7cb85f4322](https://linux-hardware.org/?probe=7cb85f4322) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d85cd905fd](https://linux-hardware.org/?probe=d85cd905fd) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | Notebook    | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| HP            | 0AACh                       | Desktop     | [d7df31df8c](https://linux-hardware.org/?probe=d7df31df8c) | Jul 26, 2022 |
| HP            | 0AACh                       | Desktop     | [357aa343ec](https://linux-hardware.org/?probe=357aa343ec) | Jul 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [80024f9b67](https://linux-hardware.org/?probe=80024f9b67) | Jul 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [85d557665e](https://linux-hardware.org/?probe=85d557665e) | Jul 25, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| Alienware     | M11xR3                      | Notebook    | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [5bec1168d0](https://linux-hardware.org/?probe=5bec1168d0) | Jul 22, 2022 |
| Gigabyte      | M68M-S2P                    | Desktop     | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| HP            | 240 G4                      | Notebook    | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [afb076562c](https://linux-hardware.org/?probe=afb076562c) | Jul 21, 2022 |
| Unknown       | W1415A                      | Notebook    | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [5fdb8cad05](https://linux-hardware.org/?probe=5fdb8cad05) | Jul 21, 2022 |
| GHIA          | Notebook                    | Notebook    | [2193ab1cd3](https://linux-hardware.org/?probe=2193ab1cd3) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| HP            | 3397                        | Desktop     | [81b550875a](https://linux-hardware.org/?probe=81b550875a) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [129009177c](https://linux-hardware.org/?probe=129009177c) | Jul 18, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [3a633633a2](https://linux-hardware.org/?probe=3a633633a2) | Jul 18, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| Dell          | Precision M4600             | Notebook    | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3feffc8f41](https://linux-hardware.org/?probe=3feffc8f41) | Jul 14, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [639c8172d1](https://linux-hardware.org/?probe=639c8172d1) | Jul 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [1cf6844d33](https://linux-hardware.org/?probe=1cf6844d33) | Jul 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [0e0ba8274b](https://linux-hardware.org/?probe=0e0ba8274b) | Jul 13, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [a7bebd622f](https://linux-hardware.org/?probe=a7bebd622f) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [0ab6a30f98](https://linux-hardware.org/?probe=0ab6a30f98) | Jul 12, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [c9645d6952](https://linux-hardware.org/?probe=c9645d6952) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | Notebook    | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ecfb5f39c5](https://linux-hardware.org/?probe=ecfb5f39c5) | Jul 09, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [e1d3204cf2](https://linux-hardware.org/?probe=e1d3204cf2) | Jul 09, 2022 |
| HP            | 18E4                        | Desktop     | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [0b57ab5b5b](https://linux-hardware.org/?probe=0b57ab5b5b) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [28b43e6c1f](https://linux-hardware.org/?probe=28b43e6c1f) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7e53f712c5](https://linux-hardware.org/?probe=7e53f712c5) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| HP            | Pavilion dv4                | Notebook    | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | Notebook    | [a5ad48eeb5](https://linux-hardware.org/?probe=a5ad48eeb5) | Jul 03, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [c364b347a5](https://linux-hardware.org/?probe=c364b347a5) | Jul 02, 2022 |
| Dell          | Precision M4600             | Notebook    | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | Notebook    | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [6ed674f77e](https://linux-hardware.org/?probe=6ed674f77e) | Jul 01, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d3fab53889](https://linux-hardware.org/?probe=d3fab53889) | Jul 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7eeeee6c93](https://linux-hardware.org/?probe=7eeeee6c93) | Jun 30, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [53dac35f18](https://linux-hardware.org/?probe=53dac35f18) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Biostar       | H510MH/E                    | Desktop     | [7b28198a82](https://linux-hardware.org/?probe=7b28198a82) | Jun 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| HP            | 18E9                        | Desktop     | [67a4877415](https://linux-hardware.org/?probe=67a4877415) | Jun 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5873a7a8dd](https://linux-hardware.org/?probe=5873a7a8dd) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [3730ffb739](https://linux-hardware.org/?probe=3730ffb739) | Jun 27, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f20fc8c349](https://linux-hardware.org/?probe=f20fc8c349) | Jun 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e457a60dd4](https://linux-hardware.org/?probe=e457a60dd4) | Jun 26, 2022 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [4d48252e22](https://linux-hardware.org/?probe=4d48252e22) | Jun 26, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Google        | Kip                         | Notebook    | [d21adde488](https://linux-hardware.org/?probe=d21adde488) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| Dell          | Latitude E6400              | Notebook    | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Alienware     | 17 R4                       | Notebook    | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [c52b07844d](https://linux-hardware.org/?probe=c52b07844d) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [31f786c1ff](https://linux-hardware.org/?probe=31f786c1ff) | Jun 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R5CT... | Convertible | [79c59719f7](https://linux-hardware.org/?probe=79c59719f7) | Jun 21, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [665cfa446b](https://linux-hardware.org/?probe=665cfa446b) | Jun 18, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [aa89682b09](https://linux-hardware.org/?probe=aa89682b09) | Jun 18, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [570c3b2345](https://linux-hardware.org/?probe=570c3b2345) | Jun 17, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkPad T540p 20BE003NU... | Notebook    | [e05c2e42c2](https://linux-hardware.org/?probe=e05c2e42c2) | Jun 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [384aa1f6c2](https://linux-hardware.org/?probe=384aa1f6c2) | Jun 17, 2022 |
| Gateway       | NE513                       | Notebook    | [c33ad72253](https://linux-hardware.org/?probe=c33ad72253) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ded75509fb](https://linux-hardware.org/?probe=ded75509fb) | Jun 15, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6194911b41](https://linux-hardware.org/?probe=6194911b41) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [f0e0fc8360](https://linux-hardware.org/?probe=f0e0fc8360) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| Dell          | Latitude E6410              | Notebook    | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [36f61b29b5](https://linux-hardware.org/?probe=36f61b29b5) | Jun 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [c8e7eea8fc](https://linux-hardware.org/?probe=c8e7eea8fc) | Jun 11, 2022 |
| Foxconn       | 2AB7                        | Desktop     | [339721d187](https://linux-hardware.org/?probe=339721d187) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | Notebook    | [84ed262694](https://linux-hardware.org/?probe=84ed262694) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | Notebook    | [ad265d5197](https://linux-hardware.org/?probe=ad265d5197) | Jun 10, 2022 |
| HP            | 2AF9                        | Desktop     | [005b85e6bb](https://linux-hardware.org/?probe=005b85e6bb) | Jun 10, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [479a01b8d8](https://linux-hardware.org/?probe=479a01b8d8) | Jun 10, 2022 |
| ASUSTek       | K43E                        | Notebook    | [cd9e7dab5e](https://linux-hardware.org/?probe=cd9e7dab5e) | Jun 09, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | Notebook    | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [38c0d1cebc](https://linux-hardware.org/?probe=38c0d1cebc) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| INET          | Z12B                        | Mini pc     | [c6362e368b](https://linux-hardware.org/?probe=c6362e368b) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| TPV-INVENT... | 2AD6 A01                    | Desktop     | [f2a54a7cc4](https://linux-hardware.org/?probe=f2a54a7cc4) | Jun 03, 2022 |
| TPV-INVENT... | 2AD6 A01                    | Desktop     | [deed95f1d2](https://linux-hardware.org/?probe=deed95f1d2) | Jun 03, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [1955955afc](https://linux-hardware.org/?probe=1955955afc) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [295c085967](https://linux-hardware.org/?probe=295c085967) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| Dell          | G7 7588                     | Notebook    | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| Lenovo        | IdeaPad S300 20197          | Notebook    | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| HP            | Presario CQ62               | Notebook    | [fe3cac8868](https://linux-hardware.org/?probe=fe3cac8868) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| MSI           | Boston                      | Desktop     | [7e3c443fb1](https://linux-hardware.org/?probe=7e3c443fb1) | May 27, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [2bdba73cfa](https://linux-hardware.org/?probe=2bdba73cfa) | May 26, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ee4d26d407](https://linux-hardware.org/?probe=ee4d26d407) | May 23, 2022 |
| Dell          | 0KRC95 A00                  | Desktop     | [8b45e8387c](https://linux-hardware.org/?probe=8b45e8387c) | May 23, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [93bb32d1b2](https://linux-hardware.org/?probe=93bb32d1b2) | May 21, 2022 |
| Acer          | Aspire 5332                 | Notebook    | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [75100b20cc](https://linux-hardware.org/?probe=75100b20cc) | May 19, 2022 |
| HP            | 158A                        | Desktop     | [befd0b5756](https://linux-hardware.org/?probe=befd0b5756) | May 18, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [679cd1e540](https://linux-hardware.org/?probe=679cd1e540) | May 18, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | Notebook    | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | Notebook    | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | S10-3                       | Notebook    | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| HP            | 2129                        | Desktop     | [d0babde387](https://linux-hardware.org/?probe=d0babde387) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| HP            | 158A                        | Desktop     | [a6bbb73cc3](https://linux-hardware.org/?probe=a6bbb73cc3) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2bd7babedc](https://linux-hardware.org/?probe=2bd7babedc) | May 13, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [d3151cce7a](https://linux-hardware.org/?probe=d3151cce7a) | May 12, 2022 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [985d5869bf](https://linux-hardware.org/?probe=985d5869bf) | May 12, 2022 |
| Intel         | D946GZIS AAD66165-501       | Desktop     | [4eb1cdd501](https://linux-hardware.org/?probe=4eb1cdd501) | May 11, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [9b6892ebed](https://linux-hardware.org/?probe=9b6892ebed) | May 09, 2022 |
| Google        | Blooglet                    | Notebook    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| Google        | Blooglet                    | Notebook    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| HP            | Laptop 17z-ca300            | Notebook    | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| Dell          | 0Y958C A00                  | Desktop     | [5ae3c49fcd](https://linux-hardware.org/?probe=5ae3c49fcd) | May 08, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| HP            | Notebook                    | Notebook    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [46d0c349d6](https://linux-hardware.org/?probe=46d0c349d6) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| Dell          | 008R9M A02                  | Server      | [02f8e21fa8](https://linux-hardware.org/?probe=02f8e21fa8) | May 06, 2022 |
| Dell          | 072T6D A01                  | Server      | [4b88759a98](https://linux-hardware.org/?probe=4b88759a98) | May 06, 2022 |
| HP            | Pavilion 14                 | Notebook    | [2bd48eeb41](https://linux-hardware.org/?probe=2bd48eeb41) | May 06, 2022 |
| HP            | 158A                        | Desktop     | [842aab71bd](https://linux-hardware.org/?probe=842aab71bd) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Dell          | 072T6D A01                  | Server      | [1c1e47824e](https://linux-hardware.org/?probe=1c1e47824e) | May 06, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [23c1cdc921](https://linux-hardware.org/?probe=23c1cdc921) | May 05, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [fc3604980a](https://linux-hardware.org/?probe=fc3604980a) | May 04, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | Notebook    | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| Dell          | 072T6D A01                  | Server      | [4fe1d33c99](https://linux-hardware.org/?probe=4fe1d33c99) | May 04, 2022 |
| ASUSTek       | VM65N-K                     | Desktop     | [9df63c1d99](https://linux-hardware.org/?probe=9df63c1d99) | May 04, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| HP            | 3047h                       | Desktop     | [bc2b3d4c04](https://linux-hardware.org/?probe=bc2b3d4c04) | May 04, 2022 |
| Dell          | Latitude 7420               | Notebook    | [a0bd1ee0f4](https://linux-hardware.org/?probe=a0bd1ee0f4) | May 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d943b0302e](https://linux-hardware.org/?probe=d943b0302e) | May 02, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| Acer          | Aspire V5-561               | Notebook    | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| Dell          | Latitude E5550              | Notebook    | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [fbb6d3b97e](https://linux-hardware.org/?probe=fbb6d3b97e) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [d594f3335c](https://linux-hardware.org/?probe=d594f3335c) | May 01, 2022 |
| ASUSTek       | X202E                       | Notebook    | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| ASUSTek       | Lancaster8                  | Desktop     | [912f9bb3f9](https://linux-hardware.org/?probe=912f9bb3f9) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| HP            | 1497                        | Desktop     | [559a844943](https://linux-hardware.org/?probe=559a844943) | Apr 30, 2022 |
| Lenovo        | S10-3                       | Notebook    | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [88c6676e7b](https://linux-hardware.org/?probe=88c6676e7b) | Apr 29, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f2bdbd2a4a](https://linux-hardware.org/?probe=f2bdbd2a4a) | Apr 29, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| Lanix         | EQ45M-S2 LNXACT             | Desktop     | [485f464d12](https://linux-hardware.org/?probe=485f464d12) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Toshiba       | Satellite L735D             | Notebook    | [4bd23809e6](https://linux-hardware.org/?probe=4bd23809e6) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [0925d92173](https://linux-hardware.org/?probe=0925d92173) | Apr 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [0cbc3290f0](https://linux-hardware.org/?probe=0cbc3290f0) | Apr 25, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | Notebook    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [2bcb31328e](https://linux-hardware.org/?probe=2bcb31328e) | Apr 23, 2022 |
| Chuwi         | Unknown                     | Notebook    | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [61ca629904](https://linux-hardware.org/?probe=61ca629904) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [c722e417a1](https://linux-hardware.org/?probe=c722e417a1) | Apr 20, 2022 |
| HP            | 3047h                       | Desktop     | [36a3e2ab98](https://linux-hardware.org/?probe=36a3e2ab98) | Apr 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b720cd5fc5](https://linux-hardware.org/?probe=b720cd5fc5) | Apr 20, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | Notebook    | [55186a3c2e](https://linux-hardware.org/?probe=55186a3c2e) | Apr 18, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | Notebook    | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | Notebook    | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [5971999c12](https://linux-hardware.org/?probe=5971999c12) | Apr 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bdc8f9b39e](https://linux-hardware.org/?probe=bdc8f9b39e) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | Notebook    | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d113301081](https://linux-hardware.org/?probe=d113301081) | Apr 14, 2022 |
| HP            | 0A54h                       | Desktop     | [11c5e77be7](https://linux-hardware.org/?probe=11c5e77be7) | Apr 14, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [25c2200e11](https://linux-hardware.org/?probe=25c2200e11) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Dell          | 0C2XKD A00                  | Desktop     | [4ece5fe0b7](https://linux-hardware.org/?probe=4ece5fe0b7) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | Notebook    | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [5d153a1030](https://linux-hardware.org/?probe=5d153a1030) | Apr 12, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [934e06ad74](https://linux-hardware.org/?probe=934e06ad74) | Apr 12, 2022 |
| HP            | ZBook 15                    | Notebook    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| Toshiba       | Satellite L735D             | Notebook    | [47f0119635](https://linux-hardware.org/?probe=47f0119635) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9d37acefa0](https://linux-hardware.org/?probe=9d37acefa0) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| Toshiba       | Satellite P775              | Notebook    | [3acd0b8861](https://linux-hardware.org/?probe=3acd0b8861) | Apr 08, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [801e4fdab1](https://linux-hardware.org/?probe=801e4fdab1) | Apr 07, 2022 |
| Dell          | Latitude E5440              | Notebook    | [18a9d37c02](https://linux-hardware.org/?probe=18a9d37c02) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| Biostar       | H110MHC                     | Desktop     | [09715fbaf2](https://linux-hardware.org/?probe=09715fbaf2) | Apr 05, 2022 |
| HP            | ProLiant DL380 Gen9         | Server      | [b183986866](https://linux-hardware.org/?probe=b183986866) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| HP            | 0B48h                       | Desktop     | [7cd0cbb7b7](https://linux-hardware.org/?probe=7cd0cbb7b7) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [9d26a79ca6](https://linux-hardware.org/?probe=9d26a79ca6) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [54db9ac27f](https://linux-hardware.org/?probe=54db9ac27f) | Apr 05, 2022 |
| HP            | Pavilion 14                 | Notebook    | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| HP            | Presario CQ56               | Notebook    | [7233c29381](https://linux-hardware.org/?probe=7233c29381) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | Notebook    | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Dell          | 0K240Y A03                  | Desktop     | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| Intel         | S2600CP G50768-505          | Server      | [cdfba65630](https://linux-hardware.org/?probe=cdfba65630) | Apr 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | Desktop     | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ECS           | A55F-M4                     | Desktop     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5af7df2c2a](https://linux-hardware.org/?probe=5af7df2c2a) | Mar 30, 2022 |
| HP            | 2B3B                        | All in one  | [032bb3134f](https://linux-hardware.org/?probe=032bb3134f) | Mar 30, 2022 |
| Acer          | Aspire one                  | Notebook    | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [67475db5e9](https://linux-hardware.org/?probe=67475db5e9) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2c7227662f](https://linux-hardware.org/?probe=2c7227662f) | Mar 29, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [4feee8c983](https://linux-hardware.org/?probe=4feee8c983) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b625abc938](https://linux-hardware.org/?probe=b625abc938) | Mar 26, 2022 |
| Lanix         | EQ45M-S2 LNXACT             | Desktop     | [ab78b9c7a6](https://linux-hardware.org/?probe=ab78b9c7a6) | Mar 25, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [0eb6fdc31d](https://linux-hardware.org/?probe=0eb6fdc31d) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | Notebook    | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [08e8cd5735](https://linux-hardware.org/?probe=08e8cd5735) | Mar 24, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| Biostar       | G31D-M7                     | Desktop     | [9882f292ea](https://linux-hardware.org/?probe=9882f292ea) | Mar 24, 2022 |
| System76      | Gazelle                     | Notebook    | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HP            | 1589                        | Desktop     | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Lenovo        | Unknown                     | Notebook    | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e1f3c645b5](https://linux-hardware.org/?probe=e1f3c645b5) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | Notebook    | [ed01dc4465](https://linux-hardware.org/?probe=ed01dc4465) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6c0caa0de4](https://linux-hardware.org/?probe=6c0caa0de4) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | Notebook    | [dbed1562e8](https://linux-hardware.org/?probe=dbed1562e8) | Mar 17, 2022 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [7e23b31c1b](https://linux-hardware.org/?probe=7e23b31c1b) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [68aaea88ba](https://linux-hardware.org/?probe=68aaea88ba) | Mar 16, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [a77a1ff925](https://linux-hardware.org/?probe=a77a1ff925) | Mar 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9e61aac69e](https://linux-hardware.org/?probe=9e61aac69e) | Mar 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [41fec60404](https://linux-hardware.org/?probe=41fec60404) | Mar 14, 2022 |
| Dell          | Latitude E6220              | Notebook    | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [065495a18e](https://linux-hardware.org/?probe=065495a18e) | Mar 13, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [9cad95edc1](https://linux-hardware.org/?probe=9cad95edc1) | Mar 12, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c8474e89b8](https://linux-hardware.org/?probe=c8474e89b8) | Mar 11, 2022 |
| HP            | 1497                        | Desktop     | [7965a1ed31](https://linux-hardware.org/?probe=7965a1ed31) | Mar 11, 2022 |
| Dell          | G5 5505                     | Notebook    | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| Pegatron      | Benicia                     | Desktop     | [00bcb5f530](https://linux-hardware.org/?probe=00bcb5f530) | Mar 10, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [046572a251](https://linux-hardware.org/?probe=046572a251) | Mar 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [db7727accf](https://linux-hardware.org/?probe=db7727accf) | Mar 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [b8038bbdc8](https://linux-hardware.org/?probe=b8038bbdc8) | Mar 09, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [1935867fe2](https://linux-hardware.org/?probe=1935867fe2) | Mar 09, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [fe2249c404](https://linux-hardware.org/?probe=fe2249c404) | Mar 08, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [515e875bbd](https://linux-hardware.org/?probe=515e875bbd) | Mar 07, 2022 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [673c6bd0db](https://linux-hardware.org/?probe=673c6bd0db) | Mar 07, 2022 |
| HP            | 0A64h                       | Desktop     | [75e39b1761](https://linux-hardware.org/?probe=75e39b1761) | Mar 07, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c3a014ca22](https://linux-hardware.org/?probe=c3a014ca22) | Mar 07, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [60146fd918](https://linux-hardware.org/?probe=60146fd918) | Mar 07, 2022 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [36979f5dde](https://linux-hardware.org/?probe=36979f5dde) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | Notebook    | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| Unknown       | KN12A                       | Notebook    | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | Notebook    | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Lenovo        | G40-70 20369                | Notebook    | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0ba7ca16b8](https://linux-hardware.org/?probe=0ba7ca16b8) | Mar 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [91a666ba20](https://linux-hardware.org/?probe=91a666ba20) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [af28b0f0d8](https://linux-hardware.org/?probe=af28b0f0d8) | Mar 02, 2022 |
| Timi          | TM1612                      | Notebook    | [dc1c26b3a9](https://linux-hardware.org/?probe=dc1c26b3a9) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | Notebook    | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| ASUSTek       | X401A                       | Notebook    | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| GHIA          | GB3B V1.1                   | Mini pc     | [b11e8e0ad2](https://linux-hardware.org/?probe=b11e8e0ad2) | Feb 28, 2022 |
| Biostar       | N68S3+                      | Desktop     | [d27fca4784](https://linux-hardware.org/?probe=d27fca4784) | Feb 28, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [fb0403c8b8](https://linux-hardware.org/?probe=fb0403c8b8) | Feb 26, 2022 |
| Timi          | RedmiBook 13 R              | Notebook    | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | Notebook    | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [6a14728490](https://linux-hardware.org/?probe=6a14728490) | Feb 24, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [aebbda3f2d](https://linux-hardware.org/?probe=aebbda3f2d) | Feb 23, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [302836f9d3](https://linux-hardware.org/?probe=302836f9d3) | Feb 23, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fe042017e6](https://linux-hardware.org/?probe=fe042017e6) | Feb 23, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| ASUSTek       | X45U                        | Notebook    | [41f11e9487](https://linux-hardware.org/?probe=41f11e9487) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [346c976e4b](https://linux-hardware.org/?probe=346c976e4b) | Feb 19, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [26d9aa49e7](https://linux-hardware.org/?probe=26d9aa49e7) | Feb 19, 2022 |
| HP            | ProBook 4530s               | Notebook    | [26a60b46d2](https://linux-hardware.org/?probe=26a60b46d2) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e5d5d5afe](https://linux-hardware.org/?probe=3e5d5d5afe) | Feb 18, 2022 |
| Hyundai Te... | Thinnote 13                 | Notebook    | [16d5bcb194](https://linux-hardware.org/?probe=16d5bcb194) | Feb 17, 2022 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [4054007b41](https://linux-hardware.org/?probe=4054007b41) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| HP            | 2B31                        | All in one  | [f9526f3928](https://linux-hardware.org/?probe=f9526f3928) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [38fe80e2a8](https://linux-hardware.org/?probe=38fe80e2a8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [cf4c296719](https://linux-hardware.org/?probe=cf4c296719) | Feb 17, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f7c7bd4baf](https://linux-hardware.org/?probe=f7c7bd4baf) | Feb 17, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [78b50a2601](https://linux-hardware.org/?probe=78b50a2601) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [f181193143](https://linux-hardware.org/?probe=f181193143) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Dell          | Latitude E7440              | Notebook    | [1efc982c71](https://linux-hardware.org/?probe=1efc982c71) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [0bba38da27](https://linux-hardware.org/?probe=0bba38da27) | Feb 16, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [34fff5bf39](https://linux-hardware.org/?probe=34fff5bf39) | Feb 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [85d4a8278e](https://linux-hardware.org/?probe=85d4a8278e) | Feb 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| HP            | 655                         | Notebook    | [b0189b16b1](https://linux-hardware.org/?probe=b0189b16b1) | Feb 14, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [64dd67ba95](https://linux-hardware.org/?probe=64dd67ba95) | Feb 14, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [51dfcad0d4](https://linux-hardware.org/?probe=51dfcad0d4) | Feb 14, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [429d06ed33](https://linux-hardware.org/?probe=429d06ed33) | Feb 13, 2022 |
| HP            | 245 G1                      | Notebook    | [30c3eb937a](https://linux-hardware.org/?probe=30c3eb937a) | Feb 13, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [3ef228db80](https://linux-hardware.org/?probe=3ef228db80) | Feb 11, 2022 |
| Dell          | Latitude 7420               | Notebook    | [2547d7836e](https://linux-hardware.org/?probe=2547d7836e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| Sony          | VGN-Z575FN                  | Notebook    | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [cc5c3cd3d0](https://linux-hardware.org/?probe=cc5c3cd3d0) | Feb 11, 2022 |
| ASRock        | B250 Gaming K4              | Desktop     | [226e1abd06](https://linux-hardware.org/?probe=226e1abd06) | Feb 11, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [99d7e82df9](https://linux-hardware.org/?probe=99d7e82df9) | Feb 11, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 2349L38       | Notebook    | [85d1c3705e](https://linux-hardware.org/?probe=85d1c3705e) | Feb 09, 2022 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [9c02ccf9fb](https://linux-hardware.org/?probe=9c02ccf9fb) | Feb 09, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [eec17e2cdc](https://linux-hardware.org/?probe=eec17e2cdc) | Feb 09, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [98bdb87a7c](https://linux-hardware.org/?probe=98bdb87a7c) | Feb 08, 2022 |
| Lanix         | A V16                       | Notebook    | [2cbb463004](https://linux-hardware.org/?probe=2cbb463004) | Feb 08, 2022 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | Notebook    | [78011da841](https://linux-hardware.org/?probe=78011da841) | Feb 07, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [9e2a093ef4](https://linux-hardware.org/?probe=9e2a093ef4) | Feb 07, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | Notebook    | [7196de2b08](https://linux-hardware.org/?probe=7196de2b08) | Feb 06, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Lanix         | NEURON_FLEX                 | Notebook    | [566f9282eb](https://linux-hardware.org/?probe=566f9282eb) | Feb 05, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [cfdee7d88e](https://linux-hardware.org/?probe=cfdee7d88e) | Feb 05, 2022 |
| Lanix         | NEURON_FLEX                 | Notebook    | [90d39053df](https://linux-hardware.org/?probe=90d39053df) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | 2B3B                        | All in one  | [b3dccf594c](https://linux-hardware.org/?probe=b3dccf594c) | Feb 03, 2022 |
| Dell          | Latitude 3420               | Notebook    | [98d388a60d](https://linux-hardware.org/?probe=98d388a60d) | Feb 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [32586355fe](https://linux-hardware.org/?probe=32586355fe) | Feb 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Lenovo        | Rev B 20YM                  | Notebook    | [83c63da100](https://linux-hardware.org/?probe=83c63da100) | Feb 01, 2022 |
| Dell          | Latitude 3330               | Notebook    | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| Dell          | Latitude 3330               | Notebook    | [61a24473d4](https://linux-hardware.org/?probe=61a24473d4) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Microsoft     | Surface Book                | Tablet      | [627c9a74be](https://linux-hardware.org/?probe=627c9a74be) | Jan 30, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [3bab4dd576](https://linux-hardware.org/?probe=3bab4dd576) | Jan 28, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0c23524659](https://linux-hardware.org/?probe=0c23524659) | Jan 28, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [e21f938f27](https://linux-hardware.org/?probe=e21f938f27) | Jan 28, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [097ee1d69a](https://linux-hardware.org/?probe=097ee1d69a) | Jan 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f25c578f5a](https://linux-hardware.org/?probe=f25c578f5a) | Jan 28, 2022 |
| Timi          | TM1701                      | Notebook    | [c4387537b3](https://linux-hardware.org/?probe=c4387537b3) | Jan 28, 2022 |
| Dell          | Latitude E6410              | Notebook    | [8f9cad1934](https://linux-hardware.org/?probe=8f9cad1934) | Jan 28, 2022 |
| Microsoft     | Surface Book                | Tablet      | [86c4883034](https://linux-hardware.org/?probe=86c4883034) | Jan 28, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d45c6ba963](https://linux-hardware.org/?probe=d45c6ba963) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWA15L0... | Notebook    | [6e1153bb21](https://linux-hardware.org/?probe=6e1153bb21) | Jan 28, 2022 |
| Timi          | TM1701                      | Notebook    | [90877c2a8a](https://linux-hardware.org/?probe=90877c2a8a) | Jan 28, 2022 |
| HP            | 2B3B                        | All in one  | [35e4a2dffb](https://linux-hardware.org/?probe=35e4a2dffb) | Jan 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [49ab3da4e2](https://linux-hardware.org/?probe=49ab3da4e2) | Jan 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e96d993823](https://linux-hardware.org/?probe=e96d993823) | Jan 26, 2022 |
| Foxconn       | 2A92                        | Desktop     | [affed2d377](https://linux-hardware.org/?probe=affed2d377) | Jan 26, 2022 |
| HP            | 8245 001                    | All in one  | [bfdc2533bb](https://linux-hardware.org/?probe=bfdc2533bb) | Jan 25, 2022 |
| System76      | Gazelle                     | Notebook    | [4066e8f06a](https://linux-hardware.org/?probe=4066e8f06a) | Jan 24, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [1b2ef9d1dc](https://linux-hardware.org/?probe=1b2ef9d1dc) | Jan 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e0197b9fdc](https://linux-hardware.org/?probe=e0197b9fdc) | Jan 23, 2022 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [100cf973bf](https://linux-hardware.org/?probe=100cf973bf) | Jan 21, 2022 |
| ASUSTek       | B551LG                      | Notebook    | [4df03afb9f](https://linux-hardware.org/?probe=4df03afb9f) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Alienware     | x15 R1                      | Notebook    | [5f9dce49b3](https://linux-hardware.org/?probe=5f9dce49b3) | Jan 20, 2022 |
| HP            | 8381 1000                   | All in one  | [acba4af69a](https://linux-hardware.org/?probe=acba4af69a) | Jan 20, 2022 |
| Dell          | 0PU052                      | Desktop     | [0b1d31cda2](https://linux-hardware.org/?probe=0b1d31cda2) | Jan 20, 2022 |
| Dell          | 0PU052                      | Desktop     | [36323786b9](https://linux-hardware.org/?probe=36323786b9) | Jan 20, 2022 |
| Acer          | Predator G9-591             | Notebook    | [187b246949](https://linux-hardware.org/?probe=187b246949) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3d19d1297](https://linux-hardware.org/?probe=c3d19d1297) | Jan 18, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [5052313cdf](https://linux-hardware.org/?probe=5052313cdf) | Jan 17, 2022 |
| Dell          | Latitude E6400              | Notebook    | [05d5d5de96](https://linux-hardware.org/?probe=05d5d5de96) | Jan 17, 2022 |
| Google        | Ultima                      | Notebook    | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HC            | HCAR357-MI V1.0             | Desktop     | [a610cc37dc](https://linux-hardware.org/?probe=a610cc37dc) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [eb68d3d4dd](https://linux-hardware.org/?probe=eb68d3d4dd) | Jan 15, 2022 |
| Pegatron      | EVE                         | Desktop     | [d21708f0ed](https://linux-hardware.org/?probe=d21708f0ed) | Jan 14, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [286a7e58fd](https://linux-hardware.org/?probe=286a7e58fd) | Jan 14, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [981a9aff50](https://linux-hardware.org/?probe=981a9aff50) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2d83a27067](https://linux-hardware.org/?probe=2d83a27067) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [85c2838614](https://linux-hardware.org/?probe=85c2838614) | Jan 11, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [2bf3f44e95](https://linux-hardware.org/?probe=2bf3f44e95) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [4f99e4803d](https://linux-hardware.org/?probe=4f99e4803d) | Jan 09, 2022 |
| Acer          | WG43M                       | Desktop     | [8c9d16de68](https://linux-hardware.org/?probe=8c9d16de68) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [a2ca29b82e](https://linux-hardware.org/?probe=a2ca29b82e) | Jan 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [b92a220707](https://linux-hardware.org/?probe=b92a220707) | Jan 07, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [b384dcb200](https://linux-hardware.org/?probe=b384dcb200) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1660421dd9](https://linux-hardware.org/?probe=1660421dd9) | Jan 05, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [d9aa580e5f](https://linux-hardware.org/?probe=d9aa580e5f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | Notebook    | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [3718c8a46f](https://linux-hardware.org/?probe=3718c8a46f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | Notebook    | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [466004173b](https://linux-hardware.org/?probe=466004173b) | Jan 04, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [df695a7747](https://linux-hardware.org/?probe=df695a7747) | Jan 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2436d612db](https://linux-hardware.org/?probe=2436d612db) | Jan 02, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [275d5a762b](https://linux-hardware.org/?probe=275d5a762b) | Jan 02, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | Notebook    | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [ffda51867b](https://linux-hardware.org/?probe=ffda51867b) | Jan 01, 2022 |
| eMachines     | E525                        | Notebook    | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Alienware     | 17 R3                       | Notebook    | [d5f4157f56](https://linux-hardware.org/?probe=d5f4157f56) | Dec 30, 2021 |
| Alienware     | 17 R3                       | Notebook    | [6c4813d3fd](https://linux-hardware.org/?probe=6c4813d3fd) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | Notebook    | [de9115a89c](https://linux-hardware.org/?probe=de9115a89c) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | Notebook    | [bf4fd6e13c](https://linux-hardware.org/?probe=bf4fd6e13c) | Dec 30, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| ASUSTek       | K43E                        | Notebook    | [38e1c3f86f](https://linux-hardware.org/?probe=38e1c3f86f) | Dec 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9d2017b698](https://linux-hardware.org/?probe=9d2017b698) | Dec 29, 2021 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [0184868fb6](https://linux-hardware.org/?probe=0184868fb6) | Dec 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Sony          | VPCEA35FL                   | Notebook    | [6c2b68633d](https://linux-hardware.org/?probe=6c2b68633d) | Dec 27, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [bb08100c63](https://linux-hardware.org/?probe=bb08100c63) | Dec 24, 2021 |
| Dell          | 0GC080                      | Desktop     | [7ab7f1da0e](https://linux-hardware.org/?probe=7ab7f1da0e) | Dec 23, 2021 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [729cb86592](https://linux-hardware.org/?probe=729cb86592) | Dec 21, 2021 |
| HP            | 2B3B                        | All in one  | [583460f9ab](https://linux-hardware.org/?probe=583460f9ab) | Dec 20, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | Notebook    | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| HP            | 2B3B                        | All in one  | [4c39b178ad](https://linux-hardware.org/?probe=4c39b178ad) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HP            | 14                          | Notebook    | [921783a9be](https://linux-hardware.org/?probe=921783a9be) | Dec 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b7b779b709](https://linux-hardware.org/?probe=b7b779b709) | Dec 16, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [66c985876e](https://linux-hardware.org/?probe=66c985876e) | Dec 16, 2021 |
| Dell          | 0GM819                      | Desktop     | [809fc591dd](https://linux-hardware.org/?probe=809fc591dd) | Dec 16, 2021 |
| Biostar       | H110MHC                     | Desktop     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [ca0c96e24b](https://linux-hardware.org/?probe=ca0c96e24b) | Dec 15, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [c17076e55c](https://linux-hardware.org/?probe=c17076e55c) | Dec 15, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [603a6f5087](https://linux-hardware.org/?probe=603a6f5087) | Dec 15, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [0119ac4373](https://linux-hardware.org/?probe=0119ac4373) | Dec 15, 2021 |
| Supermicro    | X10DRH-iT                   | Server      | [50aebe4b28](https://linux-hardware.org/?probe=50aebe4b28) | Dec 14, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | Notebook    | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [f87ff266d6](https://linux-hardware.org/?probe=f87ff266d6) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [38f2bc6cc7](https://linux-hardware.org/?probe=38f2bc6cc7) | Dec 13, 2021 |
| HP            | 09F8h                       | Desktop     | [c70b669376](https://linux-hardware.org/?probe=c70b669376) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| Timi          | TM1612                      | Notebook    | [1179aed154](https://linux-hardware.org/?probe=1179aed154) | Dec 12, 2021 |
| ASUSTek       | Bantry CRB SDK0E50510 WI... | Desktop     | [5dfc7cb81a](https://linux-hardware.org/?probe=5dfc7cb81a) | Dec 11, 2021 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [9cc5505029](https://linux-hardware.org/?probe=9cc5505029) | Dec 11, 2021 |
| HP            | 158A                        | Desktop     | [db518613b6](https://linux-hardware.org/?probe=db518613b6) | Dec 10, 2021 |
| Dell          | Latitude E5400              | Notebook    | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Gateway       | NE511                       | Notebook    | [ca37375600](https://linux-hardware.org/?probe=ca37375600) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| HP            | 3397                        | Desktop     | [9c1590635c](https://linux-hardware.org/?probe=9c1590635c) | Dec 09, 2021 |
| HONOR         | NBR-WAX9                    | Notebook    | [e4edda2131](https://linux-hardware.org/?probe=e4edda2131) | Dec 08, 2021 |
| Dell          | 0WG864                      | Desktop     | [59d9c69b35](https://linux-hardware.org/?probe=59d9c69b35) | Dec 08, 2021 |
| HP            | 09F8h                       | Desktop     | [fe41d0247b](https://linux-hardware.org/?probe=fe41d0247b) | Dec 08, 2021 |
| Acer          | Aspire XC-704G              | Desktop     | [961534f79d](https://linux-hardware.org/?probe=961534f79d) | Dec 08, 2021 |
| Acer          | Aspire XC-704G              | Desktop     | [5b69f445ad](https://linux-hardware.org/?probe=5b69f445ad) | Dec 08, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | Notebook    | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| HP            | 0A54h                       | Desktop     | [e445d6aa51](https://linux-hardware.org/?probe=e445d6aa51) | Dec 07, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [89330570db](https://linux-hardware.org/?probe=89330570db) | Dec 07, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7ff7601d59](https://linux-hardware.org/?probe=7ff7601d59) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Dell          | Vostro 3405                 | Notebook    | [b2dc2ac6b8](https://linux-hardware.org/?probe=b2dc2ac6b8) | Dec 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7a511dda3d](https://linux-hardware.org/?probe=7a511dda3d) | Dec 04, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60e7267ddb](https://linux-hardware.org/?probe=60e7267ddb) | Dec 04, 2021 |
| Acer          | Aspire X1930                | Desktop     | [68d51a9af5](https://linux-hardware.org/?probe=68d51a9af5) | Dec 03, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cf43f05660](https://linux-hardware.org/?probe=cf43f05660) | Dec 03, 2021 |
| HP            | 2B07                        | All in one  | [b6cf0a1651](https://linux-hardware.org/?probe=b6cf0a1651) | Dec 03, 2021 |
| Gigabyte      | GA-E350N                    | Desktop     | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| HP            | 829A                        | Mini pc     | [a790174646](https://linux-hardware.org/?probe=a790174646) | Dec 02, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4993feea8f](https://linux-hardware.org/?probe=4993feea8f) | Dec 02, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [0105f991c1](https://linux-hardware.org/?probe=0105f991c1) | Dec 01, 2021 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [13325b986f](https://linux-hardware.org/?probe=13325b986f) | Dec 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4855fe75cb](https://linux-hardware.org/?probe=4855fe75cb) | Dec 01, 2021 |
| HP            | Pavilion dv5                | Notebook    | [71ea9a6485](https://linux-hardware.org/?probe=71ea9a6485) | Nov 30, 2021 |
| Biostar       | TH55XE                      | Desktop     | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [f886714ec5](https://linux-hardware.org/?probe=f886714ec5) | Nov 28, 2021 |
| HP            | 1497                        | Desktop     | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0cb5ca7e51](https://linux-hardware.org/?probe=0cb5ca7e51) | Nov 28, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [8b2be4927b](https://linux-hardware.org/?probe=8b2be4927b) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| ECS           | 945GCT-M3                   | Desktop     | [a81a27ac47](https://linux-hardware.org/?probe=a81a27ac47) | Nov 25, 2021 |
| Dell          | Latitude 3520               | Notebook    | [dfb19a422e](https://linux-hardware.org/?probe=dfb19a422e) | Nov 25, 2021 |
| Dell          | Latitude 3520               | Notebook    | [a0271563a5](https://linux-hardware.org/?probe=a0271563a5) | Nov 25, 2021 |
| Lenovo        | [Lenovo SR950 4TiB] SB27... | Server      | [05228da4b0](https://linux-hardware.org/?probe=05228da4b0) | Nov 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [9d28cad38c](https://linux-hardware.org/?probe=9d28cad38c) | Nov 24, 2021 |
| Alienware     | m15 R6                      | Notebook    | [7a71325757](https://linux-hardware.org/?probe=7a71325757) | Nov 24, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [eade5e3428](https://linux-hardware.org/?probe=eade5e3428) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [81a6212074](https://linux-hardware.org/?probe=81a6212074) | Nov 23, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [ecc3ddf24a](https://linux-hardware.org/?probe=ecc3ddf24a) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| ECS           | Nettle3                     | Desktop     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [de0c208dd4](https://linux-hardware.org/?probe=de0c208dd4) | Nov 20, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [55e4412774](https://linux-hardware.org/?probe=55e4412774) | Nov 20, 2021 |
| HP            | 829A                        | Mini pc     | [a906b7c0d4](https://linux-hardware.org/?probe=a906b7c0d4) | Nov 20, 2021 |
| HP            | 829A                        | Mini pc     | [0eabb0317b](https://linux-hardware.org/?probe=0eabb0317b) | Nov 20, 2021 |
| AMD           | AOPW-PLUS                   | Server      | [4a83a85932](https://linux-hardware.org/?probe=4a83a85932) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| Lenovo        | G475 20080                  | Notebook    | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Dell          | Latitude E6400              | Notebook    | [e86a11de03](https://linux-hardware.org/?probe=e86a11de03) | Nov 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [5df470b888](https://linux-hardware.org/?probe=5df470b888) | Nov 15, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [a3cd1a283b](https://linux-hardware.org/?probe=a3cd1a283b) | Nov 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [e82daa0aba](https://linux-hardware.org/?probe=e82daa0aba) | Nov 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [ec71ab6f0c](https://linux-hardware.org/?probe=ec71ab6f0c) | Nov 12, 2021 |
| Dell          | Inspiron 1501               | Notebook    | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| HP            | ProBook 645 G2              | Notebook    | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | Notebook    | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| Dell          | 0CYTN6 A00                  | All in one  | [a70fc41793](https://linux-hardware.org/?probe=a70fc41793) | Nov 09, 2021 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [e019dfb216](https://linux-hardware.org/?probe=e019dfb216) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [a990ce7acd](https://linux-hardware.org/?probe=a990ce7acd) | Nov 08, 2021 |
| Dell          | 0HY9JP A00                  | Desktop     | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| IP3 Tech      | AB3                         | Mini pc     | [25cbd96c5f](https://linux-hardware.org/?probe=25cbd96c5f) | Nov 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [38d3058206](https://linux-hardware.org/?probe=38d3058206) | Nov 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | Notebook    | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [7ac20ab25f](https://linux-hardware.org/?probe=7ac20ab25f) | Nov 03, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [d7d0a0b507](https://linux-hardware.org/?probe=d7d0a0b507) | Nov 03, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [6b0d6d003d](https://linux-hardware.org/?probe=6b0d6d003d) | Nov 03, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [9fd4c9e3a2](https://linux-hardware.org/?probe=9fd4c9e3a2) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | Notebook    | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| System76      | Gazelle                     | Notebook    | [09a256c5ae](https://linux-hardware.org/?probe=09a256c5ae) | Nov 02, 2021 |
| System76      | Gazelle                     | Notebook    | [09da0264ca](https://linux-hardware.org/?probe=09da0264ca) | Nov 01, 2021 |
| Gateway       | NV42                        | Notebook    | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| Toshiba       | Satellite P105              | Notebook    | [1b17b5c927](https://linux-hardware.org/?probe=1b17b5c927) | Oct 31, 2021 |
| Toshiba       | Satellite P105              | Notebook    | [8f6268031e](https://linux-hardware.org/?probe=8f6268031e) | Oct 31, 2021 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [2fca11cf26](https://linux-hardware.org/?probe=2fca11cf26) | Oct 31, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [393213dee8](https://linux-hardware.org/?probe=393213dee8) | Oct 31, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [ffb75356ef](https://linux-hardware.org/?probe=ffb75356ef) | Oct 30, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | Notebook    | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [db2a7eba35](https://linux-hardware.org/?probe=db2a7eba35) | Oct 29, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [54f331c0ec](https://linux-hardware.org/?probe=54f331c0ec) | Oct 29, 2021 |
| HP            | Notebook                    | Notebook    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Dell          | Studio 1535                 | Notebook    | [69dc8fefa7](https://linux-hardware.org/?probe=69dc8fefa7) | Oct 27, 2021 |
| Dell          | Studio 1535                 | Notebook    | [3779b20704](https://linux-hardware.org/?probe=3779b20704) | Oct 27, 2021 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [47a0de503d](https://linux-hardware.org/?probe=47a0de503d) | Oct 27, 2021 |
| Dell          | 0GC080                      | Desktop     | [cb7602a2bd](https://linux-hardware.org/?probe=cb7602a2bd) | Oct 26, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [a391445664](https://linux-hardware.org/?probe=a391445664) | Oct 25, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [9fed362dde](https://linux-hardware.org/?probe=9fed362dde) | Oct 25, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [7414a480f8](https://linux-hardware.org/?probe=7414a480f8) | Oct 25, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [57be86b920](https://linux-hardware.org/?probe=57be86b920) | Oct 24, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [e8e9a85406](https://linux-hardware.org/?probe=e8e9a85406) | Oct 23, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [b4cd0bde35](https://linux-hardware.org/?probe=b4cd0bde35) | Oct 23, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [20123f6b2f](https://linux-hardware.org/?probe=20123f6b2f) | Oct 23, 2021 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [f3c4f73cb2](https://linux-hardware.org/?probe=f3c4f73cb2) | Oct 23, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [172b30ebe0](https://linux-hardware.org/?probe=172b30ebe0) | Oct 23, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [5fea6b8b9a](https://linux-hardware.org/?probe=5fea6b8b9a) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [eb508ab31e](https://linux-hardware.org/?probe=eb508ab31e) | Oct 22, 2021 |
| Google        | Guado                       | Desktop     | [5aba3d29f4](https://linux-hardware.org/?probe=5aba3d29f4) | Oct 21, 2021 |
| Google        | Guado                       | Desktop     | [2393c52b33](https://linux-hardware.org/?probe=2393c52b33) | Oct 21, 2021 |
| Dell          | Latitude 5400               | Notebook    | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| HP            | Pavilion dv5                | Notebook    | [74cee5b7a8](https://linux-hardware.org/?probe=74cee5b7a8) | Oct 20, 2021 |
| Foxconn       | 2AB7                        | Desktop     | [de1be07e5a](https://linux-hardware.org/?probe=de1be07e5a) | Oct 20, 2021 |
| Foxconn       | 2AB7                        | Desktop     | [4e260fe9f3](https://linux-hardware.org/?probe=4e260fe9f3) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [14086a6760](https://linux-hardware.org/?probe=14086a6760) | Oct 19, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90aa462368](https://linux-hardware.org/?probe=90aa462368) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | 0RF705                      | Desktop     | [07965413db](https://linux-hardware.org/?probe=07965413db) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | Notebook    | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [6522d9dc18](https://linux-hardware.org/?probe=6522d9dc18) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [b4c6139d09](https://linux-hardware.org/?probe=b4c6139d09) | Oct 17, 2021 |
| ASUSTek       | P6T                         | Desktop     | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Biostar       | N61PB-M2S                   | Desktop     | [e16a5113ba](https://linux-hardware.org/?probe=e16a5113ba) | Oct 17, 2021 |
| Biostar       | N61PB-M2S                   | Desktop     | [d17b2a3da0](https://linux-hardware.org/?probe=d17b2a3da0) | Oct 16, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [57eaf5a3e0](https://linux-hardware.org/?probe=57eaf5a3e0) | Oct 15, 2021 |
| Intel         | B75                         | Desktop     | [9374d023b7](https://linux-hardware.org/?probe=9374d023b7) | Oct 15, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [ecda4970d8](https://linux-hardware.org/?probe=ecda4970d8) | Oct 15, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [54b9ff49e4](https://linux-hardware.org/?probe=54b9ff49e4) | Oct 14, 2021 |
| Sony          | SVE14A15FLB                 | Notebook    | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [ef16468238](https://linux-hardware.org/?probe=ef16468238) | Oct 13, 2021 |
| Sony          | SVE14A15FLB                 | Notebook    | [51170d9250](https://linux-hardware.org/?probe=51170d9250) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Biostar       | A10N-9630E                  | Desktop     | [d8ce068d3a](https://linux-hardware.org/?probe=d8ce068d3a) | Oct 12, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [d74fd1a5d9](https://linux-hardware.org/?probe=d74fd1a5d9) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [bdc66de1e6](https://linux-hardware.org/?probe=bdc66de1e6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [90dd918da6](https://linux-hardware.org/?probe=90dd918da6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [0562199997](https://linux-hardware.org/?probe=0562199997) | Oct 11, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [96da43b986](https://linux-hardware.org/?probe=96da43b986) | Oct 11, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [06c3b56836](https://linux-hardware.org/?probe=06c3b56836) | Oct 11, 2021 |
| ASUSTek       | N61Jq                       | Notebook    | [2307cb57c4](https://linux-hardware.org/?probe=2307cb57c4) | Oct 11, 2021 |
| ASRock        | N73V-S                      | Desktop     | [01e398a327](https://linux-hardware.org/?probe=01e398a327) | Oct 11, 2021 |
| ASRock        | N73V-S                      | Desktop     | [8ae578e81d](https://linux-hardware.org/?probe=8ae578e81d) | Oct 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f8a55a2c62](https://linux-hardware.org/?probe=f8a55a2c62) | Oct 08, 2021 |
| Intel         | B75                         | Desktop     | [3a8b2a06b0](https://linux-hardware.org/?probe=3a8b2a06b0) | Oct 08, 2021 |
| Intel         | B75                         | Desktop     | [a694ca546a](https://linux-hardware.org/?probe=a694ca546a) | Oct 08, 2021 |
| Pegatron      | 2A99                        | Desktop     | [10f364b4ef](https://linux-hardware.org/?probe=10f364b4ef) | Oct 07, 2021 |
| Dell          | 0HD5K4 A00                  | All in one  | [75ce72a959](https://linux-hardware.org/?probe=75ce72a959) | Oct 06, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Alienware     | 17 R4                       | Notebook    | [564dd05308](https://linux-hardware.org/?probe=564dd05308) | Oct 04, 2021 |
| Alienware     | 17 R4                       | Notebook    | [01f8341213](https://linux-hardware.org/?probe=01f8341213) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4291T5Q       | Notebook    | [d31646221c](https://linux-hardware.org/?probe=d31646221c) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [0a301456dc](https://linux-hardware.org/?probe=0a301456dc) | Oct 03, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [16e83f5564](https://linux-hardware.org/?probe=16e83f5564) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [67b629d7f9](https://linux-hardware.org/?probe=67b629d7f9) | Oct 02, 2021 |
| MSI           | GE72 6QD                    | Notebook    | [a8713aca99](https://linux-hardware.org/?probe=a8713aca99) | Oct 01, 2021 |
| Eluktronic... | RP-15                       | Notebook    | [c147de5b16](https://linux-hardware.org/?probe=c147de5b16) | Sep 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2692ea7a93](https://linux-hardware.org/?probe=2692ea7a93) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Dell          | Latitude 5491               | Notebook    | [197b1a5c35](https://linux-hardware.org/?probe=197b1a5c35) | Sep 29, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [d92879de9a](https://linux-hardware.org/?probe=d92879de9a) | Sep 28, 2021 |
| Sony          | VGN-NR330FE                 | Notebook    | [9222a5b0bf](https://linux-hardware.org/?probe=9222a5b0bf) | Sep 26, 2021 |
| Sony          | VGN-NR330FE                 | Notebook    | [4e7013363c](https://linux-hardware.org/?probe=4e7013363c) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [72bee59f14](https://linux-hardware.org/?probe=72bee59f14) | Sep 26, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [c91a5b0d8d](https://linux-hardware.org/?probe=c91a5b0d8d) | Sep 25, 2021 |
| HP            | 09E0h                       | Desktop     | [35fd460ea9](https://linux-hardware.org/?probe=35fd460ea9) | Sep 25, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b9c8253944](https://linux-hardware.org/?probe=b9c8253944) | Sep 25, 2021 |
| Dell          | Latitude E6440              | Notebook    | [940e015781](https://linux-hardware.org/?probe=940e015781) | Sep 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3b8c430d4d](https://linux-hardware.org/?probe=3b8c430d4d) | Sep 24, 2021 |
| Google        | Ekko                        | Notebook    | [8760e0b36c](https://linux-hardware.org/?probe=8760e0b36c) | Sep 24, 2021 |
| Google        | Ekko                        | Notebook    | [0d6d5cc44a](https://linux-hardware.org/?probe=0d6d5cc44a) | Sep 23, 2021 |
| Dell          | 0478VN A00                  | Desktop     | [89db3ccae7](https://linux-hardware.org/?probe=89db3ccae7) | Sep 22, 2021 |
| EVOO          | EG-LP10                     | Notebook    | [e6ab927226](https://linux-hardware.org/?probe=e6ab927226) | Sep 22, 2021 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [c75d05568f](https://linux-hardware.org/?probe=c75d05568f) | Sep 22, 2021 |
| Dell          | Latitude E6440              | Notebook    | [45f88af089](https://linux-hardware.org/?probe=45f88af089) | Sep 22, 2021 |
| Dell          | Latitude E6440              | Notebook    | [28a8dacd93](https://linux-hardware.org/?probe=28a8dacd93) | Sep 22, 2021 |
| Dell          | 0GC080                      | Desktop     | [0297b84b90](https://linux-hardware.org/?probe=0297b84b90) | Sep 22, 2021 |
| Dell          | 0GC080                      | Desktop     | [d66102b7f1](https://linux-hardware.org/?probe=d66102b7f1) | Sep 22, 2021 |
| Sony          | VGN-CR360FE                 | Notebook    | [db32680a97](https://linux-hardware.org/?probe=db32680a97) | Sep 22, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0beca82e69](https://linux-hardware.org/?probe=0beca82e69) | Sep 20, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2d0d73c751](https://linux-hardware.org/?probe=2d0d73c751) | Sep 19, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [a2bbae72c0](https://linux-hardware.org/?probe=a2bbae72c0) | Sep 18, 2021 |
| Dell          | 0HD5K4 A00                  | All in one  | [b8ac53850d](https://linux-hardware.org/?probe=b8ac53850d) | Sep 18, 2021 |
| Toshiba       | Satellite L15W-B            | Notebook    | [3871a3c4fc](https://linux-hardware.org/?probe=3871a3c4fc) | Sep 18, 2021 |
| Acer          | AO751h                      | Notebook    | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [3c89bcae88](https://linux-hardware.org/?probe=3c89bcae88) | Sep 18, 2021 |
| Acer          | Aspire E5-551               | Notebook    | [223b8d9942](https://linux-hardware.org/?probe=223b8d9942) | Sep 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [5f6d259dce](https://linux-hardware.org/?probe=5f6d259dce) | Sep 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [cc48078a68](https://linux-hardware.org/?probe=cc48078a68) | Sep 16, 2021 |
| Sony          | VGN-CS140F                  | Notebook    | [a7e19c8a44](https://linux-hardware.org/?probe=a7e19c8a44) | Sep 16, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| ECS           | G41T-M7                     | Desktop     | [42e72694fc](https://linux-hardware.org/?probe=42e72694fc) | Sep 15, 2021 |
| Dell          | 0GC080                      | Desktop     | [e7be152af1](https://linux-hardware.org/?probe=e7be152af1) | Sep 15, 2021 |
| HP            | Notebook                    | Notebook    | [c3bcf38e50](https://linux-hardware.org/?probe=c3bcf38e50) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e1f454ca9a](https://linux-hardware.org/?probe=e1f454ca9a) | Sep 13, 2021 |
| HP            | Mini 110-3500               | Notebook    | [a4dd2b26bf](https://linux-hardware.org/?probe=a4dd2b26bf) | Sep 13, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [5dcb7c25ca](https://linux-hardware.org/?probe=5dcb7c25ca) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | Notebook    | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [69338ada32](https://linux-hardware.org/?probe=69338ada32) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [57f772fc9f](https://linux-hardware.org/?probe=57f772fc9f) | Sep 12, 2021 |
| Sony          | VPCCW25FL                   | Notebook    | [5dcd7a6c93](https://linux-hardware.org/?probe=5dcd7a6c93) | Sep 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [267c72cca2](https://linux-hardware.org/?probe=267c72cca2) | Sep 11, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [4e86625634](https://linux-hardware.org/?probe=4e86625634) | Sep 10, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [e0e7daf6f8](https://linux-hardware.org/?probe=e0e7daf6f8) | Sep 10, 2021 |
| Lenovo        | ThinkCentre M58e 7303AS6    | Desktop     | [467b83765f](https://linux-hardware.org/?probe=467b83765f) | Sep 10, 2021 |
| ASUSTek       | U56E                        | Notebook    | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [f11003a698](https://linux-hardware.org/?probe=f11003a698) | Sep 08, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [cb8ee015c6](https://linux-hardware.org/?probe=cb8ee015c6) | Sep 08, 2021 |
| MSI           | MS-7228                     | Desktop     | [30e50bf019](https://linux-hardware.org/?probe=30e50bf019) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| ASRock        | G41M-VS                     | Desktop     | [4895fb4c21](https://linux-hardware.org/?probe=4895fb4c21) | Sep 07, 2021 |
| Gateway       | NV55C                       | Notebook    | [1515d7dfbf](https://linux-hardware.org/?probe=1515d7dfbf) | Sep 06, 2021 |
| HP            | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Acer          | One S1003                   | Tablet      | [879a8ee9da](https://linux-hardware.org/?probe=879a8ee9da) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [e5d901c7a5](https://linux-hardware.org/?probe=e5d901c7a5) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [78f1531e54](https://linux-hardware.org/?probe=78f1531e54) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [d306a73462](https://linux-hardware.org/?probe=d306a73462) | Sep 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fcdcfe317f](https://linux-hardware.org/?probe=fcdcfe317f) | Sep 05, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [b3c5e46b4d](https://linux-hardware.org/?probe=b3c5e46b4d) | Sep 04, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [c9fd460c11](https://linux-hardware.org/?probe=c9fd460c11) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [4115bc0195](https://linux-hardware.org/?probe=4115bc0195) | Sep 03, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [2891fe25e6](https://linux-hardware.org/?probe=2891fe25e6) | Sep 03, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [08ede2b115](https://linux-hardware.org/?probe=08ede2b115) | Sep 01, 2021 |
| Sony          | SVE14A15FLB                 | Notebook    | [b49abbf4c8](https://linux-hardware.org/?probe=b49abbf4c8) | Sep 01, 2021 |
| Dell          | 094MXG A00                  | All in one  | [7fe3c46d72](https://linux-hardware.org/?probe=7fe3c46d72) | Sep 01, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [f1a0e351a2](https://linux-hardware.org/?probe=f1a0e351a2) | Aug 31, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [3140742cd5](https://linux-hardware.org/?probe=3140742cd5) | Aug 31, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e134361dc2](https://linux-hardware.org/?probe=e134361dc2) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b409334e94](https://linux-hardware.org/?probe=b409334e94) | Aug 30, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [f1eec80b6a](https://linux-hardware.org/?probe=f1eec80b6a) | Aug 30, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [c4b5fdc75f](https://linux-hardware.org/?probe=c4b5fdc75f) | Aug 30, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f185dd7230](https://linux-hardware.org/?probe=f185dd7230) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| ASRock        | G31M-S                      | Desktop     | [00579ca792](https://linux-hardware.org/?probe=00579ca792) | Aug 30, 2021 |
| HP            | 2000                        | Notebook    | [c1d490dc62](https://linux-hardware.org/?probe=c1d490dc62) | Aug 29, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [d8daca96d1](https://linux-hardware.org/?probe=d8daca96d1) | Aug 28, 2021 |
| Chuwi         | UBook                       | Tablet      | [5d34718515](https://linux-hardware.org/?probe=5d34718515) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [5716a5328f](https://linux-hardware.org/?probe=5716a5328f) | Aug 28, 2021 |
| ASRock        | G41M-VS                     | Desktop     | [6d2338d42c](https://linux-hardware.org/?probe=6d2338d42c) | Aug 26, 2021 |
| MSI           | MS-7228                     | Desktop     | [ee7056f565](https://linux-hardware.org/?probe=ee7056f565) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [5899e10002](https://linux-hardware.org/?probe=5899e10002) | Aug 25, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [27ba1b6422](https://linux-hardware.org/?probe=27ba1b6422) | Aug 25, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 264       | 13.95%  |
| Ubuntu 18.04                 | 172       | 9.09%   |
| OpenMandriva 4.2             | 88        | 4.65%   |
| OpenMandriva 4.3             | 53        | 2.8%    |
| KDE neon 20.04               | 49        | 2.59%   |
| Debian 11                    | 47        | 2.48%   |
| Ubuntu 22.04                 | 40        | 2.11%   |
| Zorin 16                     | 39        | 2.06%   |
| Manjaro                      | 38        | 2.01%   |
| Linux Mint 20.3              | 36        | 1.9%    |
| Fedora 36                    | 36        | 1.9%    |
| Arch                         | 34        | 1.8%    |
| Pop!_OS 20.04                | 33        | 1.74%   |
| Zorin 15                     | 28        | 1.48%   |
| Ubuntu 19.10                 | 26        | 1.37%   |
| Linux Mint 20                | 25        | 1.32%   |
| Fedora 35                    | 25        | 1.32%   |
| Ubuntu 21.10                 | 24        | 1.27%   |
| Linux Mint 19.3              | 24        | 1.27%   |
| Ubuntu 19.04                 | 23        | 1.22%   |
| Ubuntu 20.10                 | 22        | 1.16%   |
| Pop!_OS 21.04                | 22        | 1.16%   |
| Debian 10                    | 21        | 1.11%   |
| Kubuntu 20.04                | 20        | 1.06%   |
| Linux Mint 20.1              | 19        | 1%      |
| Fedora 34                    | 19        | 1%      |
| Xubuntu 20.04                | 17        | 0.9%    |
| Xubuntu 18.04                | 17        | 0.9%    |
| Linux Mint 20.2              | 17        | 0.9%    |
| Fedora 33                    | 16        | 0.85%   |
| Ubuntu 18.10                 | 15        | 0.79%   |
| Fedora 32                    | 15        | 0.79%   |
| Pop!_OS 22.04                | 14        | 0.74%   |
| Ubuntu 21.04                 | 12        | 0.63%   |
| Fedora 31                    | 12        | 0.63%   |
| Elementary 6.1               | 12        | 0.63%   |
| ROSA R10                     | 11        | 0.58%   |
| Pop!_OS 20.10                | 11        | 0.58%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 0.58%   |
| Elementary 5.1.7             | 11        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 595       | 32.62%  |
| OpenMandriva  | 147       | 8.06%   |
| Linux Mint    | 142       | 7.79%   |
| Fedora        | 121       | 6.63%   |
| Pop!_OS       | 85        | 4.66%   |
| Manjaro       | 80        | 4.39%   |
| Zorin         | 73        | 4%      |
| Debian        | 73        | 4%      |
| KDE neon      | 54        | 2.96%   |
| Endless       | 46        | 2.52%   |
| Arch          | 45        | 2.47%   |
| ROSA          | 42        | 2.3%    |
| Xubuntu       | 40        | 2.19%   |
| Kubuntu       | 39        | 2.14%   |
| Elementary    | 32        | 1.75%   |
| openSUSE      | 21        | 1.15%   |
| Kali          | 16        | 0.88%   |
| Lubuntu       | 13        | 0.71%   |
| Ubuntu Budgie | 12        | 0.66%   |
| Clear Linux   | 12        | 0.66%   |
| LMDE          | 11        | 0.6%    |
| Ubuntu Unity  | 9         | 0.49%   |
| Gentoo        | 9         | 0.49%   |
| EndeavourOS   | 9         | 0.49%   |
| ArcoLinux     | 9         | 0.49%   |
| Ubuntu MATE   | 8         | 0.44%   |
| CentOS        | 8         | 0.44%   |
| Parrot        | 7         | 0.38%   |
| Garuda Linux  | 6         | 0.33%   |
| Peppermint    | 5         | 0.27%   |
| MX            | 5         | 0.27%   |
| RHEL          | 4         | 0.22%   |
| Linux Lite    | 4         | 0.22%   |
| BlackPanther  | 4         | 0.22%   |
| Reborn OS     | 3         | 0.16%   |
| LinuxFX       | 3         | 0.16%   |
| Deepin        | 3         | 0.16%   |
| UbuntuDDE     | 2         | 0.11%   |
| Ubuntu Studio | 2         | 0.11%   |
| Solus         | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 87        | 4.24%   |
| 5.16.7-desktop-1omv4003  | 49        | 2.39%   |
| 5.4.0-42-generic         | 44        | 2.14%   |
| 5.4.0-58-generic         | 26        | 1.27%   |
| 5.8.0-14-generic         | 21        | 1.02%   |
| 5.3.0-40-generic         | 20        | 0.97%   |
| 5.11.0-27-generic        | 19        | 0.93%   |
| 5.4.0-91-generic         | 18        | 0.88%   |
| 5.4.0-52-generic         | 18        | 0.88%   |
| 5.4.0-48-generic         | 18        | 0.88%   |
| 5.4.0-40-generic         | 17        | 0.83%   |
| 5.3.0-46-generic         | 16        | 0.78%   |
| 5.11.0-37-generic        | 16        | 0.78%   |
| 5.4.0-65-generic         | 15        | 0.73%   |
| 5.4.0-54-generic         | 14        | 0.68%   |
| 5.4.0-37-generic         | 14        | 0.68%   |
| 5.3.0-42-generic         | 14        | 0.68%   |
| 5.3.0-28-generic         | 14        | 0.68%   |
| 5.13.0-40-generic        | 14        | 0.68%   |
| 5.15.0-47-generic        | 13        | 0.63%   |
| 5.13.0-39-generic        | 13        | 0.63%   |
| 5.11.0-7620-generic      | 13        | 0.63%   |
| 5.4.0-7642-generic       | 12        | 0.58%   |
| 5.4.0-33-generic         | 12        | 0.58%   |
| 5.13.0-28-generic        | 12        | 0.58%   |
| 5.11.0-43-generic        | 12        | 0.58%   |
| 5.0.0-37-generic         | 12        | 0.58%   |
| 5.4.0-77-generic         | 11        | 0.54%   |
| 5.4.0-74-generic         | 11        | 0.54%   |
| 5.4.0-45-generic         | 11        | 0.54%   |
| 5.15.0-46-generic        | 11        | 0.54%   |
| 5.15.0-41-generic        | 11        | 0.54%   |
| 5.10.0-8-amd64           | 11        | 0.54%   |
| 4.18.0-15-generic        | 11        | 0.54%   |
| 5.8.0-53-generic         | 10        | 0.49%   |
| 5.4.0-72-generic         | 10        | 0.49%   |
| 5.4.0-26-generic         | 10        | 0.49%   |
| 5.11.0-41-generic        | 10        | 0.49%   |
| 5.11.0-40-generic        | 10        | 0.49%   |
| 5.11.0-38-generic        | 10        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 378       | 19.54%  |
| 5.11.0  | 134       | 6.93%   |
| 5.8.0   | 119       | 6.15%   |
| 5.13.0  | 113       | 5.84%   |
| 5.3.0   | 111       | 5.74%   |
| 4.15.0  | 108       | 5.58%   |
| 5.10.14 | 87        | 4.5%    |
| 5.15.0  | 78        | 4.03%   |
| 4.18.0  | 73        | 3.77%   |
| 5.0.0   | 72        | 3.72%   |
| 5.10.0  | 56        | 2.9%    |
| 5.16.7  | 50        | 2.59%   |
| 4.19.0  | 33        | 1.71%   |
| 5.17.5  | 10        | 0.52%   |
| 4.9.20  | 9         | 0.47%   |
| 5.14.0  | 8         | 0.41%   |
| 5.9.16  | 6         | 0.31%   |
| 5.3.18  | 6         | 0.31%   |
| 5.12.4  | 6         | 0.31%   |
| 5.11.12 | 6         | 0.31%   |
| 4.9.60  | 6         | 0.31%   |
| 4.4.0   | 6         | 0.31%   |
| 5.9.1   | 5         | 0.26%   |
| 5.4.32  | 5         | 0.26%   |
| 5.19.11 | 5         | 0.26%   |
| 5.19.0  | 5         | 0.26%   |
| 5.18.6  | 5         | 0.26%   |
| 5.17.15 | 5         | 0.26%   |
| 5.17.0  | 5         | 0.26%   |
| 5.16.16 | 5         | 0.26%   |
| 5.16.13 | 5         | 0.26%   |
| 5.16.11 | 5         | 0.26%   |
| 5.16.0  | 5         | 0.26%   |
| 5.15.8  | 5         | 0.26%   |
| 5.15.15 | 5         | 0.26%   |
| 5.15.13 | 5         | 0.26%   |
| 5.12.9  | 5         | 0.26%   |
| 5.7.0   | 4         | 0.21%   |
| 5.6.0   | 4         | 0.21%   |
| 5.3.11  | 4         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 407       | 21.31%  |
| 5.10    | 178       | 9.32%   |
| 5.11    | 151       | 7.91%   |
| 5.8     | 134       | 7.02%   |
| 5.15    | 134       | 7.02%   |
| 5.13    | 131       | 6.86%   |
| 5.3     | 128       | 6.7%    |
| 4.15    | 108       | 5.65%   |
| 5.16    | 89        | 4.66%   |
| 4.18    | 75        | 3.93%   |
| 5.0     | 73        | 3.82%   |
| 4.19    | 38        | 1.99%   |
| 5.17    | 33        | 1.73%   |
| 5.18    | 32        | 1.68%   |
| 5.19    | 27        | 1.41%   |
| 5.14    | 26        | 1.36%   |
| 5.9     | 25        | 1.31%   |
| 4.9     | 25        | 1.31%   |
| 5.7     | 22        | 1.15%   |
| 5.12    | 20        | 1.05%   |
| 5.6     | 19        | 0.99%   |
| 5.5     | 9         | 0.47%   |
| 4.4     | 6         | 0.31%   |
| 5.2     | 4         | 0.21%   |
| 4.12    | 4         | 0.21%   |
| 4.13    | 3         | 0.16%   |
| 4.1     | 3         | 0.16%   |
| 4.10    | 2         | 0.1%    |
| 5.1     | 1         | 0.05%   |
| 4.20    | 1         | 0.05%   |
| 3.2     | 1         | 0.05%   |
| 3.10    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1693      | 95.92%  |
| i686    | 68        | 3.85%   |
| aarch64 | 3         | 0.17%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 815       | 44.39%  |
| KDE5              | 285       | 15.52%  |
| Unknown           | 220       | 11.98%  |
| XFCE              | 131       | 7.14%   |
| X-Cinnamon        | 103       | 5.61%   |
| KDE               | 70        | 3.81%   |
| MATE              | 54        | 2.94%   |
| Pantheon          | 30        | 1.63%   |
| Cinnamon          | 25        | 1.36%   |
| KDE4              | 22        | 1.2%    |
| LXQt              | 15        | 0.82%   |
| Budgie            | 15        | 0.82%   |
| LXDE              | 14        | 0.76%   |
| Unity             | 9         | 0.49%   |
| Deepin            | 7         | 0.38%   |
| GNOME Classic     | 4         | 0.22%   |
| Openbox           | 3         | 0.16%   |
| trinity           | 2         | 0.11%   |
| qtile             | 2         | 0.11%   |
| i3                | 2         | 0.11%   |
| Enlightenment     | 2         | 0.11%   |
| Yaru:ubuntu:GNOME | 1         | 0.05%   |
| xmonad            | 1         | 0.05%   |
| lightdm-xsession  | 1         | 0.05%   |
| GNOME Flashback   | 1         | 0.05%   |
| bspwm             | 1         | 0.05%   |
| awesome           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1435      | 79.28%  |
| Wayland | 232       | 12.82%  |
| Unknown | 133       | 7.35%   |
| Tty     | 10        | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1030      | 56.69%  |
| SDDM    | 253       | 13.92%  |
| GDM     | 205       | 11.28%  |
| LightDM | 133       | 7.32%   |
| GDM3    | 111       | 6.11%   |
| TDM     | 53        | 2.92%   |
| KDM     | 23        | 1.27%   |
| XDM     | 4         | 0.22%   |
| SLiM    | 3         | 0.17%   |
| MDM     | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_MX      | 861       | 47.75%  |
| en_US      | 528       | 29.28%  |
| Unknown    | 221       | 12.26%  |
| es_ES      | 125       | 6.93%   |
| C          | 32        | 1.77%   |
| en_GB      | 11        | 0.61%   |
| es_US      | 5         | 0.28%   |
| en_CA      | 4         | 0.22%   |
| POSIX      | 2         | 0.11%   |
| es_MX.UTF8 | 2         | 0.11%   |
| es_AR      | 2         | 0.11%   |
| en_MX      | 2         | 0.11%   |
| uk_UA      | 1         | 0.06%   |
| nhn_MX     | 1         | 0.06%   |
| it_IT      | 1         | 0.06%   |
| es_CO      | 1         | 0.06%   |
| en_US.UTF8 | 1         | 0.06%   |
| de_DE      | 1         | 0.06%   |
| Default    | 1         | 0.06%   |
| C.UTF8     | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 980       | 54.6%   |
| EFI  | 815       | 45.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1391      | 77.84%  |
| Overlay | 169       | 9.46%   |
| Btrfs   | 110       | 6.16%   |
| Unknown | 68        | 3.81%   |
| Xfs     | 27        | 1.51%   |
| Zfs     | 8         | 0.45%   |
| Ext2    | 8         | 0.45%   |
| Ext3    | 2         | 0.11%   |
| XXXXXXX | 1         | 0.06%   |
| Tmpfs   | 1         | 0.06%   |
| F2fs    | 1         | 0.06%   |
| Aufs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1149      | 64.05%  |
| GPT     | 454       | 25.31%  |
| MBR     | 191       | 10.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1577      | 88.2%   |
| Yes       | 211       | 11.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1210      | 67.37%  |
| Yes       | 586       | 32.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 366       | 20.75%  |
| Lenovo                  | 250       | 14.17%  |
| Dell                    | 231       | 13.1%   |
| ASUSTek Computer        | 184       | 10.43%  |
| Gigabyte Technology     | 130       | 7.37%   |
| Acer                    | 102       | 5.78%   |
| Toshiba                 | 58        | 3.29%   |
| Apple                   | 47        | 2.66%   |
| Sony                    | 36        | 2.04%   |
| MSI                     | 36        | 2.04%   |
| HUAWEI                  | 35        | 1.98%   |
| Intel                   | 29        | 1.64%   |
| ECS                     | 29        | 1.64%   |
| ASRock                  | 27        | 1.53%   |
| Biostar                 | 20        | 1.13%   |
| Samsung Electronics     | 18        | 1.02%   |
| Gateway                 | 17        | 0.96%   |
| Pegatron                | 14        | 0.79%   |
| Lanix                   | 14        | 0.79%   |
| Alienware               | 13        | 0.74%   |
| Google                  | 11        | 0.62%   |
| Foxconn                 | 7         | 0.4%    |
| AMI                     | 7         | 0.4%    |
| Unknown                 | 7         | 0.4%    |
| Microsoft               | 6         | 0.34%   |
| Chuwi                   | 6         | 0.34%   |
| PCChips                 | 5         | 0.28%   |
| GHIA                    | 5         | 0.28%   |
| System76                | 4         | 0.23%   |
| Raspberry Pi Foundation | 4         | 0.23%   |
| eMachines               | 4         | 0.23%   |
| Timi                    | 3         | 0.17%   |
| EVOO                    | 3         | 0.17%   |
| Wistron                 | 2         | 0.11%   |
| TPV-INVENTA             | 2         | 0.11%   |
| Supermicro              | 2         | 0.11%   |
| Panasonic               | 2         | 0.11%   |
| Insyde                  | 2         | 0.11%   |
| IBM                     | 2         | 0.11%   |
| Corporativo Lanix       | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP Notebook                           | 26        | 1.47%   |
| Unknown                               | 18        | 1.02%   |
| HP Pavilion Laptop 15-cw0xxx          | 16        | 0.91%   |
| ASUS PRIME A320M-K                    | 14        | 0.79%   |
| HP Pavilion g4                        | 11        | 0.62%   |
| HUAWEI HVY-WXX9                       | 10        | 0.57%   |
| HP Pavilion Notebook                  | 9         | 0.51%   |
| HP Laptop 15-da0xxx                   | 9         | 0.51%   |
| Lenovo IdeaPad 330-14AST 81D5         | 8         | 0.45%   |
| HP Laptop 15-bw0xx                    | 7         | 0.4%    |
| HP EliteBook 8460p                    | 7         | 0.4%    |
| Gigabyte B450M DS3H                   | 7         | 0.4%    |
| ECS A320AM4-M3D                       | 7         | 0.4%    |
| Dell Latitude E6430                   | 7         | 0.4%    |
| HP Pavilion Laptop 15-cw1xxx          | 6         | 0.34%   |
| HP Pavilion dv4                       | 6         | 0.34%   |
| Dell Inspiron 5559                    | 6         | 0.34%   |
| Dell Inspiron 3421                    | 6         | 0.34%   |
| ASUS PRIME B450M-A II                 | 6         | 0.34%   |
| ASUS All Series                       | 6         | 0.34%   |
| HP Pavilion x360 Convertible 14-ba0xx | 5         | 0.28%   |
| HP Pavilion dv5                       | 5         | 0.28%   |
| HP Compaq 6200 Pro SFF PC             | 5         | 0.28%   |
| Gigabyte GA-880GM-USB3                | 5         | 0.28%   |
| Dell OptiPlex 9020                    | 5         | 0.28%   |
| Dell OptiPlex 755                     | 5         | 0.28%   |
| Dell OptiPlex 7010                    | 5         | 0.28%   |
| ASUS ROG STRIX B450-F GAMING          | 5         | 0.28%   |
| Apple MacBookPro9,2                   | 5         | 0.28%   |
| Acer Aspire E5-573                    | 5         | 0.28%   |
| Acer Aspire E3-112M                   | 5         | 0.28%   |
| Toshiba Satellite L855                | 4         | 0.23%   |
| Lenovo G50-30 80G0                    | 4         | 0.23%   |
| Lenovo G40-45 80E1                    | 4         | 0.23%   |
| HP Pavilion 14                        | 4         | 0.23%   |
| HP Laptop 15-bs0xx                    | 4         | 0.23%   |
| HP Laptop 14-cm0xxx                   | 4         | 0.23%   |
| HP G42                                | 4         | 0.23%   |
| HP 14                                 | 4         | 0.23%   |
| Gigabyte A320M-S2H V2                 | 4         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 99        | 5.61%   |
| Lenovo ThinkPad    | 90        | 5.1%    |
| Dell Inspiron      | 78        | 4.42%   |
| Lenovo IdeaPad     | 77        | 4.37%   |
| Acer Aspire        | 73        | 4.14%   |
| Dell Latitude      | 62        | 3.51%   |
| Toshiba Satellite  | 54        | 3.06%   |
| HP Laptop          | 45        | 2.55%   |
| Dell OptiPlex      | 40        | 2.27%   |
| ASUS PRIME         | 40        | 2.27%   |
| HP Compaq          | 36        | 2.04%   |
| HP Notebook        | 26        | 1.47%   |
| HP EliteBook       | 21        | 1.19%   |
| HP ProBook         | 20        | 1.13%   |
| Unknown            | 18        | 1.02%   |
| ASUS VivoBook      | 15        | 0.85%   |
| ASUS ROG           | 15        | 0.85%   |
| Lenovo ThinkCentre | 12        | 0.68%   |
| HP ENVY            | 12        | 0.68%   |
| HUAWEI HVY-WXX9    | 10        | 0.57%   |
| HP 240             | 9         | 0.51%   |
| Gigabyte B450M     | 9         | 0.51%   |
| Dell XPS           | 9         | 0.51%   |
| Dell Vostro        | 9         | 0.51%   |
| Lenovo Yoga        | 8         | 0.45%   |
| Gigabyte A320M-S2H | 8         | 0.45%   |
| Dell Studio        | 8         | 0.45%   |
| Dell Precision     | 8         | 0.45%   |
| Lenovo Legion      | 7         | 0.4%    |
| HP ProDesk         | 7         | 0.4%    |
| Gigabyte B450      | 7         | 0.4%    |
| ECS A320AM4-M3D    | 7         | 0.4%    |
| ASUS TUF           | 7         | 0.4%    |
| ASUS M5A97         | 7         | 0.4%    |
| Microsoft Surface  | 6         | 0.34%   |
| HP ZBook           | 6         | 0.34%   |
| HP OMEN            | 6         | 0.34%   |
| ASUS All           | 6         | 0.34%   |
| Apple MacBookPro9  | 6         | 0.34%   |
| MSI GF63           | 5         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 183       | 10.37%  |
| 2011    | 162       | 9.18%   |
| 2017    | 146       | 8.28%   |
| 2012    | 144       | 8.16%   |
| 2019    | 134       | 7.6%    |
| 2014    | 126       | 7.14%   |
| 2015    | 125       | 7.09%   |
| 2020    | 114       | 6.46%   |
| 2013    | 111       | 6.29%   |
| 2010    | 110       | 6.24%   |
| 2016    | 86        | 4.88%   |
| 2008    | 83        | 4.71%   |
| 2009    | 78        | 4.42%   |
| 2021    | 66        | 3.74%   |
| 2007    | 48        | 2.72%   |
| 2006    | 22        | 1.25%   |
| 2005    | 11        | 0.62%   |
| 2022    | 7         | 0.4%    |
| Unknown | 5         | 0.28%   |
| 2004    | 2         | 0.11%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1095      | 62.07%  |
| Desktop        | 547       | 31.01%  |
| All in one     | 38        | 2.15%   |
| Convertible    | 31        | 1.76%   |
| Tablet         | 20        | 1.13%   |
| Mini pc        | 17        | 0.96%   |
| Server         | 12        | 0.68%   |
| System on chip | 4         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1618      | 90.9%   |
| Enabled  | 162       | 9.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1752      | 99.32%  |
| Yes  | 12        | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 472       | 26.44%  |
| 3.01-4.0        | 438       | 24.54%  |
| 8.01-16.0       | 340       | 19.05%  |
| 16.01-24.0      | 211       | 11.82%  |
| 1.01-2.0        | 135       | 7.56%   |
| 32.01-64.0      | 78        | 4.37%   |
| 2.01-3.0        | 36        | 2.02%   |
| 24.01-32.0      | 27        | 1.51%   |
| 64.01-256.0     | 23        | 1.29%   |
| 0.51-1.0        | 22        | 1.23%   |
| More than 256.0 | 2         | 0.11%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 768       | 39.85%  |
| 2.01-3.0    | 497       | 25.79%  |
| 3.01-4.0    | 222       | 11.52%  |
| 4.01-8.0    | 201       | 10.43%  |
| 0.51-1.0    | 149       | 7.73%   |
| 8.01-16.0   | 57        | 2.96%   |
| 0.01-0.5    | 19        | 0.99%   |
| 16.01-24.0  | 9         | 0.47%   |
| 24.01-32.0  | 2         | 0.1%    |
| 32.01-64.0  | 1         | 0.05%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1215      | 67.13%  |
| 2       | 415       | 22.93%  |
| 3       | 91        | 5.03%   |
| 4       | 39        | 2.15%   |
| 0       | 26        | 1.44%   |
| 5       | 11        | 0.61%   |
| 6       | 7         | 0.39%   |
| 7       | 2         | 0.11%   |
| 37      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1059      | 59.59%  |
| Yes       | 718       | 40.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1546      | 87.59%  |
| No        | 219       | 12.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1430      | 80.93%  |
| No        | 337       | 19.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1025      | 57.17%  |
| No        | 768       | 42.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Mexico  | 1764      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 379       | 20.33%  |
| Guadalajara           | 100       | 5.36%   |
| Monterrey             | 64        | 3.43%   |
| Zapopan               | 50        | 2.68%   |
| Queretaro             | 49        | 2.63%   |
| Tijuana               | 46        | 2.47%   |
| Puebla City           | 40        | 2.15%   |
| Mérida               | 34        | 1.82%   |
| Cancún               | 29        | 1.56%   |
| Ciudad Juárez        | 28        | 1.5%    |
| Hermosillo            | 27        | 1.45%   |
| Toluca                | 26        | 1.39%   |
| Morelia               | 24        | 1.29%   |
| Ciudad Lopez Mateos   | 24        | 1.29%   |
| Naucalpan             | 22        | 1.18%   |
| Mexico                | 22        | 1.18%   |
| Apodaca               | 22        | 1.18%   |
| Tlalnepantla          | 21        | 1.13%   |
| León                 | 21        | 1.13%   |
| Chihuahua City        | 20        | 1.07%   |
| Oaxaca City           | 19        | 1.02%   |
| Ecatepec              | 19        | 1.02%   |
| Ciudad Nezahualcoyotl | 17        | 0.91%   |
| Villahermosa          | 16        | 0.86%   |
| Mexicali              | 16        | 0.86%   |
| Ensenada              | 16        | 0.86%   |
| Xalapa                | 15        | 0.8%    |
| Veracruz              | 15        | 0.8%    |
| Cuernavaca            | 15        | 0.8%    |
| San Luis Potosí City | 14        | 0.75%   |
| Culiacán             | 14        | 0.75%   |
| Celaya                | 14        | 0.75%   |
| Zacatecas City        | 13        | 0.7%    |
| Iztapalapa            | 13        | 0.7%    |
| Guadalupe             | 13        | 0.7%    |
| Puerto Vallarta       | 12        | 0.64%   |
| Saltillo              | 11        | 0.59%   |
| Pachuca               | 10        | 0.54%   |
| Durango               | 10        | 0.54%   |
| Azcapotzalco          | 10        | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 457       | 670    | 19.41%  |
| WDC                     | 403       | 523    | 17.12%  |
| Toshiba                 | 230       | 273    | 9.77%   |
| Kingston                | 219       | 265    | 9.3%    |
| A-DATA Technology       | 155       | 192    | 6.58%   |
| Samsung Electronics     | 147       | 177    | 6.24%   |
| Hitachi                 | 127       | 162    | 5.4%    |
| Unknown                 | 111       | 140    | 4.72%   |
| HGST                    | 74        | 84     | 3.14%   |
| SanDisk                 | 61        | 76     | 2.59%   |
| Intel                   | 33        | 53     | 1.4%    |
| Crucial                 | 31        | 38     | 1.32%   |
| SK hynix                | 30        | 37     | 1.27%   |
| Apple                   | 24        | 30     | 1.02%   |
| XPG                     | 21        | 31     | 0.89%   |
| Fujitsu                 | 21        | 23     | 0.89%   |
| Realtek Semiconductor   | 17        | 22     | 0.72%   |
| Micron Technology       | 15        | 18     | 0.64%   |
| PNY                     | 14        | 16     | 0.59%   |
| Phison                  | 11        | 12     | 0.47%   |
| LITEON                  | 11        | 16     | 0.47%   |
| Maxtor                  | 8         | 10     | 0.34%   |
| YMTC                    | 7         | 8      | 0.3%    |
| JMicron Technology      | 7         | 7      | 0.3%    |
| Unknown                 | 7         | 7      | 0.3%    |
| Netac                   | 6         | 7      | 0.25%   |
| KIOXIA                  | 6         | 8      | 0.25%   |
| Gigabyte Technology     | 6         | 7      | 0.25%   |
| Silicon Motion          | 5         | 6      | 0.21%   |
| China                   | 5         | 5      | 0.21%   |
| Hewlett-Packard         | 4         | 4      | 0.17%   |
| Yeyian                  | 3         | 4      | 0.13%   |
| Union Memory (Shenzhen) | 3         | 3      | 0.13%   |
| Transcend               | 3         | 3      | 0.13%   |
| SPCC                    | 3         | 3      | 0.13%   |
| SABRENT                 | 3         | 3      | 0.13%   |
| Phison Electronics      | 3         | 3      | 0.13%   |
| Patriot                 | 3         | 5      | 0.13%   |
| AS201                   | 3         | 3      | 0.13%   |
| Team                    | 2         | 2      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 56        | 2.23%   |
| Seagate ST1000LM035-1RK172 1TB     | 52        | 2.07%   |
| Toshiba MQ04ABF100 1TB             | 36        | 1.43%   |
| Kingston SA400S37480G 480GB SSD    | 36        | 1.43%   |
| Toshiba MQ01ABD100 1TB             | 33        | 1.31%   |
| A-DATA SU650 120GB SSD             | 33        | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 30        | 1.19%   |
| Seagate ST500DM002-1BD142 500GB    | 26        | 1.03%   |
| Kingston SA400S37120G 120GB SSD    | 25        | 0.99%   |
| Seagate ST500LT012-1DG142 500GB    | 24        | 0.95%   |
| Toshiba MQ01ABF050 500GB           | 23        | 0.91%   |
| A-DATA SU630 240GB SSD             | 21        | 0.83%   |
| Unknown MMC Card  32GB             | 19        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB     | 16        | 0.64%   |
| A-DATA SU650 240GB SSD             | 16        | 0.64%   |
| HGST HTS541010A9E680 1TB           | 15        | 0.6%    |
| Unknown SD/MMC/MS PRO 2GB          | 13        | 0.52%   |
| Toshiba DT01ACA050 500GB           | 13        | 0.52%   |
| Samsung NVMe SSD Drive 512GB       | 13        | 0.52%   |
| XPG GAMMIX S11 Pro 512GB           | 12        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 12        | 0.48%   |
| Unknown MMC Card  64GB             | 12        | 0.48%   |
| Unknown MMC Card  16GB             | 12        | 0.48%   |
| Seagate ST3500418AS 500GB          | 12        | 0.48%   |
| HGST HTS725050A7E630 500GB         | 12        | 0.48%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 11        | 0.44%   |
| Toshiba DT01ACA200 2TB             | 11        | 0.44%   |
| Seagate ST9500325AS 500GB          | 11        | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB    | 11        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 0.44%   |
| Kingston SA400S37960G 960GB SSD    | 11        | 0.44%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 10        | 0.4%    |
| Seagate ST2000LM007-1R8174 2TB     | 9         | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB     | 9         | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB     | 9         | 0.36%   |
| Seagate Expansion 1TB              | 9         | 0.36%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.36%   |
| HGST HTS541075A9E680 752GB         | 9         | 0.36%   |
| WDC WD10JPVX-60JC3T1 1TB           | 8         | 0.32%   |
| WDC WD10JPCX-24UE4T0 1TB           | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 455       | 666    | 34.97%  |
| WDC                 | 351       | 443    | 26.98%  |
| Toshiba             | 206       | 246    | 15.83%  |
| Hitachi             | 127       | 162    | 9.76%   |
| HGST                | 74        | 84     | 5.69%   |
| Samsung Electronics | 27        | 29     | 2.08%   |
| Fujitsu             | 21        | 23     | 1.61%   |
| Unknown             | 13        | 14     | 1%      |
| Maxtor              | 8         | 10     | 0.61%   |
| Apple               | 7         | 8      | 0.54%   |
| Hewlett-Packard     | 3         | 3      | 0.23%   |
| USB3.0              | 1         | 1      | 0.08%   |
| SAGE                | 1         | 1      | 0.08%   |
| Quantum             | 1         | 1      | 0.08%   |
| MaxDigital          | 1         | 4      | 0.08%   |
| LaCie               | 1         | 2      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| HPE                 | 1         | 1      | 0.08%   |
| DELLBOSS            | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 203       | 243    | 31.82%  |
| A-DATA Technology   | 149       | 185    | 23.35%  |
| Samsung Electronics | 49        | 56     | 7.68%   |
| WDC                 | 42        | 57     | 6.58%   |
| SanDisk             | 30        | 35     | 4.7%    |
| Crucial             | 27        | 29     | 4.23%   |
| PNY                 | 14        | 16     | 2.19%   |
| Apple               | 13        | 14     | 2.04%   |
| Intel               | 12        | 16     | 1.88%   |
| LITEON              | 11        | 16     | 1.72%   |
| Micron Technology   | 10        | 13     | 1.57%   |
| SK hynix            | 9         | 10     | 1.41%   |
| Netac               | 6         | 7      | 0.94%   |
| Gigabyte Technology | 5         | 6      | 0.78%   |
| China               | 5         | 5      | 0.78%   |
| Yeyian              | 3         | 4      | 0.47%   |
| Unknown             | 3         | 3      | 0.47%   |
| Transcend           | 3         | 3      | 0.47%   |
| Toshiba             | 3         | 3      | 0.47%   |
| SPCC                | 3         | 3      | 0.47%   |
| Patriot             | 3         | 5      | 0.47%   |
| AS201               | 3         | 3      | 0.47%   |
| Team                | 2         | 2      | 0.31%   |
| Pioneer             | 2         | 3      | 0.31%   |
| OCZ                 | 2         | 4      | 0.31%   |
| LITEONIT            | 2         | 2      | 0.31%   |
| KingSpec            | 2         | 3      | 0.31%   |
| Unknown             | 2         | 2      | 0.31%   |
| ZTC                 | 1         | 1      | 0.16%   |
| Zheino              | 1         | 1      | 0.16%   |
| WDC WDS4            | 1         | 1      | 0.16%   |
| VALK                | 1         | 1      | 0.16%   |
| StoreJet            | 1         | 1      | 0.16%   |
| ShanDianZhe         | 1         | 2      | 0.16%   |
| Morebeck-N100       | 1         | 1      | 0.16%   |
| Londisk             | 1         | 1      | 0.16%   |
| Lite-On             | 1         | 3      | 0.16%   |
| Lexar               | 1         | 1      | 0.16%   |
| Hikvision           | 1         | 1      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1156      | 1701   | 53.64%  |
| SSD     | 585       | 774    | 27.15%  |
| NVMe    | 298       | 404    | 13.83%  |
| MMC     | 96        | 124    | 4.45%   |
| Unknown | 20        | 24     | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1504      | 2415   | 76.5%   |
| NVMe | 292       | 398    | 14.85%  |
| MMC  | 96        | 124    | 4.88%   |
| SAS  | 74        | 90     | 3.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1102      | 1536   | 61.88%  |
| 0.51-1.0   | 524       | 678    | 29.42%  |
| 1.01-2.0   | 106       | 148    | 5.95%   |
| 3.01-4.0   | 22        | 45     | 1.24%   |
| 2.01-3.0   | 19        | 26     | 1.07%   |
| 4.01-10.0  | 7         | 28     | 0.39%   |
| 10.01-20.0 | 1         | 14     | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 470       | 25.43%  |
| 251-500        | 416       | 22.51%  |
| 501-1000       | 290       | 15.69%  |
| 1-20           | 168       | 9.09%   |
| 51-100         | 156       | 8.44%   |
| 1001-2000      | 126       | 6.82%   |
| 21-50          | 100       | 5.41%   |
| More than 3000 | 51        | 2.76%   |
| Unknown        | 36        | 1.95%   |
| 2001-3000      | 35        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 823       | 43.09%  |
| 21-50          | 362       | 18.95%  |
| 101-250        | 212       | 11.1%   |
| 51-100         | 202       | 10.58%  |
| 251-500        | 119       | 6.23%   |
| 501-1000       | 85        | 4.45%   |
| 1001-2000      | 44        | 2.3%    |
| Unknown        | 36        | 1.88%   |
| More than 3000 | 18        | 0.94%   |
| 2001-3000      | 9         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 6         | 7      | 3.21%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 5      | 2.67%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 2.67%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 2.14%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 2.14%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 1.6%    |
| Seagate ST3160815AS 160GB           | 3         | 3      | 1.6%    |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 3      | 1.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 1.6%    |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 3      | 1.6%    |
| HGST HTS541010A7E630 1TB            | 3         | 3      | 1.6%    |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 1.07%   |
| Toshiba MQ04ABF100 1TB              | 2         | 2      | 1.07%   |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.07%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 1.07%   |
| Seagate ST3500418AS 500GB           | 2         | 2      | 1.07%   |
| Seagate ST31000524AS 1TB            | 2         | 4      | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 1.07%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 1.07%   |
| Maxtor 6Y080M0 81GB                 | 2         | 2      | 1.07%   |
| Kingston SUV400S37480G 480GB SSD    | 2         | 2      | 1.07%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 1.07%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 2      | 1.07%   |
| Hitachi HTS545016B9A300 160GB       | 2         | 2      | 1.07%   |
| HGST HTS545050A7E380 500GB          | 2         | 2      | 1.07%   |
| WDC WD800JD-00MSA1 80GB             | 1         | 1      | 0.53%   |
| WDC WD6400BEVT-60A0RT0 640GB        | 1         | 1      | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 2      | 0.53%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-603CA0 500GB         | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000AAKS-402AA0 500GB         | 1         | 1      | 0.53%   |
| WDC WD5000AADS-56S9B1 500GB         | 1         | 1      | 0.53%   |
| WDC WD5000AACS-61M6B2 500GB         | 1         | 1      | 0.53%   |
| WDC WD50 00BEVT-11ZAT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD3200KS-75PFB0 320GB           | 1         | 1      | 0.53%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 0.53%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1         | 1      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 75     | 30.39%  |
| WDC                 | 30        | 34     | 16.57%  |
| Toshiba             | 25        | 35     | 13.81%  |
| Hitachi             | 24        | 26     | 13.26%  |
| HGST                | 16        | 16     | 8.84%   |
| Kingston            | 9         | 9      | 4.97%   |
| Samsung Electronics | 5         | 5      | 2.76%   |
| SanDisk             | 4         | 4      | 2.21%   |
| LITEON              | 3         | 3      | 1.66%   |
| Fujitsu             | 3         | 3      | 1.66%   |
| Maxtor              | 2         | 2      | 1.1%    |
| A-DATA Technology   | 2         | 2      | 1.1%    |
| Micron Technology   | 1         | 1      | 0.55%   |
| Crucial             | 1         | 1      | 0.55%   |
| China               | 1         | 1      | 0.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 75     | 34.59%  |
| WDC                 | 30        | 34     | 18.87%  |
| Toshiba             | 25        | 35     | 15.72%  |
| Hitachi             | 24        | 26     | 15.09%  |
| HGST                | 16        | 16     | 10.06%  |
| Samsung Electronics | 4         | 4      | 2.52%   |
| Fujitsu             | 3         | 3      | 1.89%   |
| Maxtor              | 2         | 2      | 1.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 153       | 195    | 87.43%  |
| SSD  | 19        | 19     | 10.86%  |
| NVMe | 3         | 3      | 1.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1191      | 1994   | 63.93%  |
| Works    | 499       | 815    | 26.78%  |
| Malfunc  | 172       | 217    | 9.23%   |
| Failed   | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1122      | 57.1%   |
| AMD                              | 445       | 22.65%  |
| Samsung Electronics              | 76        | 3.87%   |
| Nvidia                           | 53        | 2.7%    |
| SanDisk                          | 45        | 2.29%   |
| Realtek Semiconductor            | 25        | 1.27%   |
| ADATA Technology                 | 22        | 1.12%   |
| Toshiba America Info Systems     | 21        | 1.07%   |
| SK hynix                         | 21        | 1.07%   |
| Marvell Technology Group         | 20        | 1.02%   |
| Kingston Technology Company      | 17        | 0.87%   |
| Phison Electronics               | 15        | 0.76%   |
| KIOXIA                           | 8         | 0.41%   |
| Yangtze Memory Technologies      | 7         | 0.36%   |
| Union Memory (Shenzhen)          | 7         | 0.36%   |
| Micron/Crucial Technology        | 7         | 0.36%   |
| JMicron Technology               | 7         | 0.36%   |
| LSI Logic / Symbios Logic        | 6         | 0.31%   |
| ASMedia Technology               | 6         | 0.31%   |
| Silicon Motion                   | 5         | 0.25%   |
| Micron Technology                | 5         | 0.25%   |
| VIA Technologies                 | 4         | 0.2%    |
| Apple                            | 4         | 0.2%    |
| Silicon Image                    | 3         | 0.15%   |
| Hewlett-Packard                  | 3         | 0.15%   |
| Broadcom / LSI                   | 2         | 0.1%    |
| Unknown                          | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Broadcom                         | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 314       | 13.37%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 92        | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 83        | 3.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 78        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 67        | 2.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 59        | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46        | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 44        | 1.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 42        | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42        | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 40        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 40        | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 38        | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 37        | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 37        | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 36        | 1.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 34        | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 34        | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 30        | 1.28%   |
| AMD FCH SATA Controller D                                                               | 29        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 26        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 26        | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 25        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 24        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 23        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22        | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 21        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 21        | 0.89%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 21        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 20        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18        | 0.77%   |
| Samsung NVMe SSD Controller 980                                                         | 17        | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 0.72%   |
| Realtek Realtek Non-Volatile memory controller                                          | 16        | 0.68%   |
| Nvidia MCP61 IDE                                                                        | 16        | 0.68%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 16        | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                                  | 16        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1312      | 63.54%  |
| IDE  | 295       | 14.29%  |
| NVMe | 294       | 14.24%  |
| RAID | 153       | 7.41%   |
| SAS  | 10        | 0.48%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1240      | 70.29%  |
| AMD    | 520       | 29.48%  |
| ARM    | 4         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 0.91%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 16        | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.79%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 14        | 0.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 12        | 0.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 12        | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.62%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 11        | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 10        | 0.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.57%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 10        | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 9         | 0.51%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 9         | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.51%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.51%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 9         | 0.51%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.45%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 8         | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 8         | 0.45%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 8         | 0.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.45%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 8         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 314       | 17.8%   |
| Intel Core i7           | 269       | 15.25%  |
| Intel Celeron           | 163       | 9.24%   |
| Intel Core i3           | 149       | 8.45%   |
| AMD Ryzen 5             | 93        | 5.27%   |
| Intel Core 2 Duo        | 81        | 4.59%   |
| Intel Atom              | 55        | 3.12%   |
| Other                   | 51        | 2.89%   |
| AMD Ryzen 7             | 45        | 2.55%   |
| AMD A6                  | 43        | 2.44%   |
| Intel Pentium           | 40        | 2.27%   |
| AMD A8                  | 36        | 2.04%   |
| Intel Xeon              | 35        | 1.98%   |
| AMD Ryzen 3             | 34        | 1.93%   |
| AMD A4                  | 28        | 1.59%   |
| AMD FX                  | 25        | 1.42%   |
| AMD A10                 | 24        | 1.36%   |
| Intel Pentium Dual      | 21        | 1.19%   |
| AMD E                   | 20        | 1.13%   |
| AMD Athlon              | 20        | 1.13%   |
| Intel Pentium Dual-Core | 17        | 0.96%   |
| AMD Athlon II X2        | 16        | 0.91%   |
| AMD E1                  | 12        | 0.68%   |
| AMD Athlon 64 X2        | 12        | 0.68%   |
| Intel Pentium 4         | 10        | 0.57%   |
| Intel Core 2 Quad       | 10        | 0.57%   |
| Intel Core 2            | 10        | 0.57%   |
| Intel Genuine           | 9         | 0.51%   |
| AMD Sempron             | 9         | 0.51%   |
| AMD Turion 64 X2 Mobile | 8         | 0.45%   |
| AMD Ryzen 9             | 8         | 0.45%   |
| AMD Athlon II           | 8         | 0.45%   |
| AMD Phenom II X4        | 7         | 0.4%    |
| AMD Ryzen 5 PRO         | 6         | 0.34%   |
| Intel Core i9           | 5         | 0.28%   |
| AMD E2                  | 5         | 0.28%   |
| AMD Ryzen 3 PRO         | 4         | 0.23%   |
| AMD A12                 | 4         | 0.23%   |
| Intel Pentium Silver    | 3         | 0.17%   |
| Intel Core m3           | 3         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 935       | 52.97%  |
| 4       | 520       | 29.46%  |
| 6       | 120       | 6.8%    |
| 1       | 104       | 5.89%   |
| 8       | 59        | 3.34%   |
| 3       | 10        | 0.57%   |
| 12      | 6         | 0.34%   |
| 16      | 5         | 0.28%   |
| 28      | 3         | 0.17%   |
| 32      | 1         | 0.06%   |
| 10      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1751      | 99.26%  |
| 2      | 13        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1022      | 57.9%   |
| 1       | 742       | 42.04%  |
| Unknown | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1704      | 96.38%  |
| Unknown        | 33        | 1.87%   |
| 32-bit         | 20        | 1.13%   |
| 64-bit         | 11        | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 335       | 18.42%  |
| 0x206a7    | 125       | 6.87%   |
| 0x306a9    | 92        | 5.06%   |
| 0x1067a    | 58        | 3.19%   |
| 0x306c3    | 50        | 2.75%   |
| 0x40651    | 47        | 2.58%   |
| 0x30678    | 42        | 2.31%   |
| 0x806ec    | 39        | 2.14%   |
| 0x806e9    | 39        | 2.14%   |
| 0x306d4    | 34        | 1.87%   |
| 0x806ea    | 32        | 1.76%   |
| 0x506e3    | 32        | 1.76%   |
| 0x010000c8 | 31        | 1.7%    |
| 0x6fd      | 30        | 1.65%   |
| 0x08108109 | 30        | 1.65%   |
| 0x906ea    | 28        | 1.54%   |
| 0x406e3    | 28        | 1.54%   |
| 0x406c4    | 28        | 1.54%   |
| 0x20655    | 27        | 1.48%   |
| 0x06001119 | 27        | 1.48%   |
| 0x06006705 | 25        | 1.37%   |
| 0x906e9    | 24        | 1.32%   |
| 0x0810100b | 24        | 1.32%   |
| 0x406c3    | 22        | 1.21%   |
| 0x10676    | 22        | 1.21%   |
| 0x106ca    | 21        | 1.15%   |
| 0x07030105 | 21        | 1.15%   |
| 0x806c1    | 18        | 0.99%   |
| 0x20652    | 18        | 0.99%   |
| 0x0800820d | 18        | 0.99%   |
| 0x08101016 | 17        | 0.93%   |
| 0x706a1    | 16        | 0.88%   |
| 0x506c9    | 16        | 0.88%   |
| 0x08108102 | 16        | 0.88%   |
| 0x0600611a | 16        | 0.88%   |
| 0x05000119 | 16        | 0.88%   |
| 0x08600106 | 15        | 0.82%   |
| 0x6fb      | 14        | 0.77%   |
| 0x706e5    | 12        | 0.66%   |
| 0x106c2    | 12        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 214       | 12.13%  |
| SandyBridge      | 153       | 8.67%   |
| Haswell          | 122       | 6.92%   |
| IvyBridge        | 118       | 6.69%   |
| Silvermont       | 104       | 5.9%    |
| Penryn           | 93        | 5.27%   |
| Skylake          | 81        | 4.59%   |
| Zen+             | 76        | 4.31%   |
| Excavator        | 73        | 4.14%   |
| Core             | 65        | 3.68%   |
| Zen              | 54        | 3.06%   |
| K10              | 52        | 2.95%   |
| Westmere         | 50        | 2.83%   |
| Zen 2            | 47        | 2.66%   |
| Broadwell        | 47        | 2.66%   |
| Piledriver       | 45        | 2.55%   |
| Bonnell          | 36        | 2.04%   |
| K8 Hammer        | 35        | 1.98%   |
| Bobcat           | 30        | 1.7%    |
| Puma             | 28        | 1.59%   |
| Goldmont plus    | 28        | 1.59%   |
| CometLake        | 25        | 1.42%   |
| TigerLake        | 23        | 1.3%    |
| Goldmont         | 20        | 1.13%   |
| Zen 3            | 19        | 1.08%   |
| IceLake          | 19        | 1.08%   |
| Unknown          | 17        | 0.96%   |
| Nehalem          | 14        | 0.79%   |
| Steamroller      | 13        | 0.74%   |
| NetBurst         | 13        | 0.74%   |
| Jaguar           | 13        | 0.74%   |
| K10 Llano        | 10        | 0.57%   |
| P6               | 9         | 0.51%   |
| K8 & K10 hybrid  | 9         | 0.51%   |
| Bulldozer        | 8         | 0.45%   |
| Alderlake Hybrid | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1049      | 53.14%  |
| AMD                              | 547       | 27.71%  |
| Nvidia                           | 362       | 18.34%  |
| Matrox Electronics Systems       | 9         | 0.46%   |
| VIA Technologies                 | 2         | 0.1%    |
| ATI Technologies                 | 2         | 0.1%    |
| ASPEED Technology                | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 127       | 6.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 55        | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 52        | 2.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 52        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 2.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 44        | 2.14%   |
| Intel HD Graphics 5500                                                                   | 41        | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 1.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 37        | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 1.75%   |
| Intel HD Graphics 620                                                                    | 36        | 1.75%   |
| Intel UHD Graphics 620                                                                   | 35        | 1.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 34        | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 31        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 1.41%   |
| Intel HD Graphics 530                                                                    | 29        | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 1.41%   |
| AMD Renoir                                                                               | 26        | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 25        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 22        | 1.07%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 22        | 1.07%   |
| Intel HD Graphics 630                                                                    | 21        | 1.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 0.92%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 0.88%   |
| Intel HD Graphics 500                                                                    | 17        | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 0.83%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 16        | 0.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 15        | 0.73%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 13        | 0.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 13        | 0.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 12        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 860       | 48.51%  |
| 1 x AMD         | 459       | 25.89%  |
| 1 x Nvidia      | 202       | 11.39%  |
| Intel + Nvidia  | 134       | 7.56%   |
| Intel + AMD     | 37        | 2.09%   |
| 2 x AMD         | 36        | 2.03%   |
| AMD + Nvidia    | 16        | 0.9%    |
| 1 x Matrox      | 8         | 0.45%   |
| Other           | 7         | 0.39%   |
| 2 x Nvidia      | 6         | 0.34%   |
| 1 x ASPEED      | 2         | 0.11%   |
| 3 x AMD         | 1         | 0.06%   |
| 2 x Intel       | 1         | 0.06%   |
| 1 x VIA         | 1         | 0.06%   |
| 1 x SiS         | 1         | 0.06%   |
| Nvidia + VIA    | 1         | 0.06%   |
| Nvidia + Matrox | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1562      | 87.65%  |
| Proprietary | 180       | 10.1%   |
| Unknown     | 40        | 2.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1006      | 55.92%  |
| 0.01-0.5   | 289       | 16.06%  |
| 1.01-2.0   | 189       | 10.51%  |
| 0.51-1.0   | 166       | 9.23%   |
| 3.01-4.0   | 60        | 3.34%   |
| 7.01-8.0   | 42        | 2.33%   |
| 5.01-6.0   | 31        | 1.72%   |
| 2.01-3.0   | 12        | 0.67%   |
| 16.01-24.0 | 2         | 0.11%   |
| 8.01-16.0  | 2         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 232       | 12.19%  |
| Samsung Electronics     | 222       | 11.67%  |
| BOE                     | 194       | 10.19%  |
| LG Display              | 189       | 9.93%   |
| Chimei Innolux          | 186       | 9.77%   |
| Hewlett-Packard         | 146       | 7.67%   |
| Dell                    | 102       | 5.36%   |
| Goldstar                | 64        | 3.36%   |
| Acer                    | 54        | 2.84%   |
| BenQ                    | 48        | 2.52%   |
| Apple                   | 48        | 2.52%   |
| Chi Mei Optoelectronics | 35        | 1.84%   |
| AOC                     | 34        | 1.79%   |
| Lenovo                  | 31        | 1.63%   |
| Unknown                 | 29        | 1.52%   |
| Gateway                 | 18        | 0.95%   |
| ViewSonic               | 17        | 0.89%   |
| Ancor Communications    | 17        | 0.89%   |
| Sharp                   | 16        | 0.84%   |
| LG Philips              | 16        | 0.84%   |
| Sony                    | 15        | 0.79%   |
| ASUSTek Computer        | 13        | 0.68%   |
| HannStar                | 9         | 0.47%   |
| PANDA                   | 8         | 0.42%   |
| InfoVision              | 8         | 0.42%   |
| VOR                     | 7         | 0.37%   |
| SAC                     | 6         | 0.32%   |
| ___                     | 5         | 0.26%   |
| Philips                 | 5         | 0.26%   |
| Panasonic               | 5         | 0.26%   |
| NEC Computers           | 5         | 0.26%   |
| Insignia                | 5         | 0.26%   |
| InnoLux Display         | 5         | 0.26%   |
| Toshiba                 | 4         | 0.21%   |
| RTK                     | 4         | 0.21%   |
| Plain Tree Systems      | 4         | 0.21%   |
| LG Electronics          | 4         | 0.21%   |
| JDI                     | 4         | 0.21%   |
| FOX                     | 4         | 0.21%   |
| eMachines               | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 16        | 0.83%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                     | 13        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 12        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 12        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 11        | 0.57%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 11        | 0.57%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 11        | 0.57%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 10        | 0.52%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 10        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 10        | 0.52%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 10        | 0.52%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 9         | 0.46%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 9         | 0.46%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 9         | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 9         | 0.46%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 8         | 0.41%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.41%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 7         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 7         | 0.36%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 6         | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 6         | 0.31%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 6         | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 6         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 6         | 0.31%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                     | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 6         | 0.31%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch    | 6         | 0.31%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                     | 5         | 0.26%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 5         | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 696       | 37.99%  |
| 1920x1080 (FHD)    | 566       | 30.9%   |
| 1600x900 (HD+)     | 86        | 4.69%   |
| 1440x900 (WXGA+)   | 73        | 3.98%   |
| 1280x800 (WXGA)    | 68        | 3.71%   |
| 1280x1024 (SXGA)   | 55        | 3%      |
| 3840x2160 (4K)     | 44        | 2.4%    |
| 1360x768           | 26        | 1.42%   |
| 1680x1050 (WSXGA+) | 25        | 1.36%   |
| 1024x600           | 25        | 1.36%   |
| 1024x768 (XGA)     | 22        | 1.2%    |
| 2560x1440 (QHD)    | 19        | 1.04%   |
| Unknown            | 18        | 0.98%   |
| 2560x1080          | 15        | 0.82%   |
| 3440x1440          | 12        | 0.66%   |
| 2160x1440          | 11        | 0.6%    |
| 3840x1080          | 8         | 0.44%   |
| 1920x1200 (WUXGA)  | 6         | 0.33%   |
| 3000x2000          | 5         | 0.27%   |
| 2880x1800          | 5         | 0.27%   |
| 2560x1600          | 5         | 0.27%   |
| 1600x1200          | 5         | 0.27%   |
| 2288x1287          | 4         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.16%   |
| 2736x1824          | 3         | 0.16%   |
| 3360x1080          | 2         | 0.11%   |
| 2520x1680          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 1280x768           | 2         | 0.11%   |
| 1152x864           | 2         | 0.11%   |
| 6720x1440          | 1         | 0.05%   |
| 4721x1050          | 1         | 0.05%   |
| 4310x1080          | 1         | 0.05%   |
| 3840x2400          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3286x1080          | 1         | 0.05%   |
| 3280x1200          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 484       | 25.65%  |
| 13      | 261       | 13.83%  |
| 14      | 211       | 11.18%  |
| 21      | 113       | 5.99%   |
| 23      | 92        | 4.88%   |
| 19      | 76        | 4.03%   |
| 18      | 75        | 3.97%   |
| 17      | 73        | 3.87%   |
| Unknown | 67        | 3.55%   |
| 24      | 60        | 3.18%   |
| 27      | 56        | 2.97%   |
| 11      | 51        | 2.7%    |
| 20      | 50        | 2.65%   |
| 12      | 31        | 1.64%   |
| 31      | 26        | 1.38%   |
| 10      | 25        | 1.32%   |
| 34      | 22        | 1.17%   |
| 22      | 19        | 1.01%   |
| 16      | 13        | 0.69%   |
| 72      | 12        | 0.64%   |
| 84      | 9         | 0.48%   |
| 54      | 9         | 0.48%   |
| 32      | 7         | 0.37%   |
| 40      | 6         | 0.32%   |
| 29      | 5         | 0.26%   |
| 46      | 4         | 0.21%   |
| 26      | 4         | 0.21%   |
| 142     | 3         | 0.16%   |
| 39      | 3         | 0.16%   |
| 25      | 3         | 0.16%   |
| 49      | 2         | 0.11%   |
| 48      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 8       | 2         | 0.11%   |
| 74      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 50      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 883       | 47.45%  |
| 401-500        | 308       | 16.55%  |
| 501-600        | 202       | 10.85%  |
| 201-300        | 194       | 10.42%  |
| 351-400        | 80        | 4.3%    |
| Unknown        | 67        | 3.6%    |
| 601-700        | 35        | 1.88%   |
| 701-800        | 30        | 1.61%   |
| 1501-2000      | 22        | 1.18%   |
| 1001-1500      | 22        | 1.18%   |
| 801-900        | 12        | 0.64%   |
| More than 2000 | 3         | 0.16%   |
| 101-200        | 2         | 0.11%   |
| 901-1000       | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1341      | 78.01%  |
| 16/10   | 181       | 10.53%  |
| Unknown | 56        | 3.26%   |
| 5/4     | 49        | 2.85%   |
| 4/3     | 36        | 2.09%   |
| 3/2     | 25        | 1.45%   |
| 21/9    | 24        | 1.4%    |
| 1.00    | 4         | 0.23%   |
| 32/9    | 3         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 490       | 26.2%   |
| 81-90          | 417       | 22.3%   |
| 201-250        | 231       | 12.35%  |
| 151-200        | 164       | 8.77%   |
| 141-150        | 98        | 5.24%   |
| Unknown        | 67        | 3.58%   |
| 301-350        | 59        | 3.16%   |
| 71-80          | 57        | 3.05%   |
| 351-500        | 55        | 2.94%   |
| 51-60          | 51        | 2.73%   |
| More than 1000 | 39        | 2.09%   |
| 121-130        | 28        | 1.5%    |
| 61-70          | 26        | 1.39%   |
| 41-50          | 25        | 1.34%   |
| 501-1000       | 21        | 1.12%   |
| 251-300        | 16        | 0.86%   |
| 131-140        | 12        | 0.64%   |
| 111-120        | 8         | 0.43%   |
| 91-100         | 4         | 0.21%   |
| 1-40           | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 750       | 40.96%  |
| 51-100        | 537       | 29.33%  |
| 121-160       | 341       | 18.62%  |
| Unknown       | 67        | 3.66%   |
| 1-50          | 60        | 3.28%   |
| 161-240       | 52        | 2.84%   |
| More than 240 | 24        | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1472      | 81.55%  |
| 2     | 258       | 14.29%  |
| 0     | 49        | 2.71%   |
| 3     | 25        | 1.39%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1049      | 39.32%  |
| Intel                                  | 624       | 23.39%  |
| Qualcomm Atheros                       | 365       | 13.68%  |
| Broadcom                               | 203       | 7.61%   |
| Ralink Technology                      | 55        | 2.06%   |
| Ralink                                 | 52        | 1.95%   |
| Broadcom Limited                       | 49        | 1.84%   |
| Nvidia                                 | 45        | 1.69%   |
| Marvell Technology Group               | 38        | 1.42%   |
| TP-Link                                | 33        | 1.24%   |
| Qualcomm Atheros Communications        | 20        | 0.75%   |
| Huawei Technologies                    | 16        | 0.6%    |
| Motorola PCS                           | 11        | 0.41%   |
| MediaTek                               | 9         | 0.34%   |
| Xiaomi                                 | 7         | 0.26%   |
| Samsung Electronics                    | 7         | 0.26%   |
| DisplayLink                            | 7         | 0.26%   |
| ASIX Electronics                       | 7         | 0.26%   |
| Mercucys                               | 6         | 0.22%   |
| VIA Technologies                       | 4         | 0.15%   |
| Dell                                   | 4         | 0.15%   |
| D-Link System                          | 4         | 0.15%   |
| D-Link                                 | 4         | 0.15%   |
| Qualcomm                               | 3         | 0.11%   |
| NetGear                                | 3         | 0.11%   |
| Microchip Technology                   | 3         | 0.11%   |
| Linksys                                | 3         | 0.11%   |
| Lenovo                                 | 3         | 0.11%   |
| ICS Advent                             | 3         | 0.11%   |
| IBM                                    | 3         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3         | 0.11%   |
| Wacom                                  | 2         | 0.07%   |
| Spreadtrum Communications              | 2         | 0.07%   |
| JMicron Technology                     | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Tenda                                  | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Sangoma Technologies                   | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 628       | 19.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 255       | 7.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 72        | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 56        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 54        | 1.69%   |
| Intel Wi-Fi 6 AX200                                               | 50        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 48        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 47        | 1.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 45        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 44        | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                     | 38        | 1.19%   |
| Intel Wireless 7265                                               | 30        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29        | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 28        | 0.88%   |
| Intel Wireless 7260                                               | 27        | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 25        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 25        | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 24        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                   | 23        | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 0.72%   |
| Intel Wireless 8260                                               | 23        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 0.69%   |
| Intel Wireless 3165                                               | 22        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 22        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.63%   |
| Intel Wireless 3160                                               | 18        | 0.56%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 17        | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 17        | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                   | 17        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 17        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.5%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 16        | 0.5%    |
| Realtek 802.11ac NIC                                              | 15        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 454       | 29.97%  |
| Realtek Semiconductor                 | 376       | 24.82%  |
| Qualcomm Atheros                      | 303       | 20%     |
| Broadcom                              | 147       | 9.7%    |
| Ralink Technology                     | 55        | 3.63%   |
| Ralink                                | 52        | 3.43%   |
| Broadcom Limited                      | 35        | 2.31%   |
| TP-Link                               | 31        | 2.05%   |
| Qualcomm Atheros Communications       | 20        | 1.32%   |
| Mercucys                              | 6         | 0.4%    |
| MediaTek                              | 6         | 0.4%    |
| Marvell Technology Group              | 6         | 0.4%    |
| D-Link                                | 4         | 0.26%   |
| NetGear                               | 3         | 0.2%    |
| Dell                                  | 3         | 0.2%    |
| D-Link System                         | 3         | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.2%    |
| Wacom                                 | 2         | 0.13%   |
| Linksys                               | 2         | 0.13%   |
| Tenda                                 | 1         | 0.07%   |
| Qualcomm                              | 1         | 0.07%   |
| Micro Star International              | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 72        | 4.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 56        | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 54        | 3.51%   |
| Intel Wi-Fi 6 AX200                                                     | 50        | 3.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 48        | 3.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 47        | 3.06%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 45        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 2.47%   |
| Intel Wireless 7265                                                     | 30        | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 29        | 1.89%   |
| Intel Wireless 8265 / 8275                                              | 28        | 1.82%   |
| Intel Wireless 7260                                                     | 27        | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 25        | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 1.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 24        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 24        | 1.56%   |
| Ralink MT7601U Wireless Adapter                                         | 23        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 1.5%    |
| Intel Wireless 8260                                                     | 23        | 1.5%    |
| Intel Wireless 3165                                                     | 22        | 1.43%   |
| Intel Wireless 3160                                                     | 18        | 1.17%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 17        | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 17        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 17        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.04%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 1.04%   |
| Realtek 802.11ac NIC                                                    | 15        | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 15        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 13        | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 13        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 919       | 56.66%  |
| Intel                                  | 334       | 20.59%  |
| Qualcomm Atheros                       | 109       | 6.72%   |
| Broadcom                               | 79        | 4.87%   |
| Nvidia                                 | 45        | 2.77%   |
| Marvell Technology Group               | 32        | 1.97%   |
| Huawei Technologies                    | 15        | 0.92%   |
| Broadcom Limited                       | 14        | 0.86%   |
| Xiaomi                                 | 7         | 0.43%   |
| Samsung Electronics                    | 7         | 0.43%   |
| Motorola PCS                           | 7         | 0.43%   |
| DisplayLink                            | 7         | 0.43%   |
| ASIX Electronics                       | 7         | 0.43%   |
| VIA Technologies                       | 4         | 0.25%   |
| MediaTek                               | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| IBM                                    | 3         | 0.18%   |
| TP-Link                                | 2         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.12%   |
| Qualcomm                               | 2         | 0.12%   |
| Microchip Technology                   | 2         | 0.12%   |
| Lenovo                                 | 2         | 0.12%   |
| JMicron Technology                     | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| Lab126                                 | 1         | 0.06%   |
| Hisense                                | 1         | 0.06%   |
| Google                                 | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| D-Link System                          | 1         | 0.06%   |
| ADMtek                                 | 1         | 0.06%   |
| Accton Technology                      | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 628       | 38.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 255       | 15.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 4.62%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.34%   |
| Intel I211 Gigabit Network Connection                             | 22        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.22%   |
| Nvidia MCP61 Ethernet                                             | 17        | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13        | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 0.79%   |
| Huawei YAL-L21                                                    | 13        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 10        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 9         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.49%   |
| Nvidia MCP67 Ethernet                                             | 8         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.43%   |
| Motorola PCS Moto G (5) Plus                                      | 7         | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1544      | 51.62%  |
| WiFi     | 1430      | 47.81%  |
| Modem    | 9         | 0.3%    |
| Unknown  | 8         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1124      | 60.89%  |
| Ethernet | 720       | 39%     |
| Unknown  | 2         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1065      | 60.31%  |
| 1     | 649       | 36.75%  |
| 0     | 29        | 1.64%   |
| 3     | 14        | 0.79%   |
| 4     | 5         | 0.28%   |
| 8     | 3         | 0.17%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1379      | 76.31%  |
| Yes  | 428       | 23.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 334       | 32.4%   |
| Realtek Semiconductor           | 195       | 18.91%  |
| Qualcomm Atheros Communications | 95        | 9.21%   |
| Cambridge Silicon Radio         | 76        | 7.37%   |
| Broadcom                        | 75        | 7.27%   |
| Apple                           | 42        | 4.07%   |
| Lite-On Technology              | 39        | 3.78%   |
| Foxconn / Hon Hai               | 31        | 3.01%   |
| IMC Networks                    | 25        | 2.42%   |
| Dell                            | 25        | 2.42%   |
| Toshiba                         | 16        | 1.55%   |
| Hewlett-Packard                 | 16        | 1.55%   |
| Ralink                          | 15        | 1.45%   |
| Realtek                         | 11        | 1.07%   |
| ASUSTek Computer                | 10        | 0.97%   |
| Marvell Semiconductor           | 6         | 0.58%   |
| Ralink Technology               | 5         | 0.48%   |
| Alps Electric                   | 4         | 0.39%   |
| Foxconn International           | 3         | 0.29%   |
| TP-Link                         | 2         | 0.19%   |
| Roper                           | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| MediaTek                        | 1         | 0.1%    |
| Integrated System Solution      | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 147       | 14.24%  |
| Realtek Bluetooth Radio                                                             | 91        | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 84        | 8.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 76        | 7.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 61        | 5.91%   |
| Intel AX200 Bluetooth                                                               | 49        | 4.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 46        | 4.46%   |
| Intel AX201 Bluetooth                                                               | 41        | 3.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 23        | 2.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 16        | 1.55%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 1.55%   |
| Ralink RT3290 Bluetooth                                                             | 15        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 14        | 1.36%   |
| Realtek RTL8723B Bluetooth                                                          | 13        | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.26%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 12        | 1.16%   |
| Realtek Bluetooth Radio                                                             | 11        | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 11        | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 1.07%   |
| Lite-On Bluetooth Device                                                            | 11        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.07%   |
| Apple Bluetooth Host Controller                                                     | 11        | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.97%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 10        | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 0.78%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.78%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.58%   |
| IMC Networks Bluetooth Device                                                       | 6         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 5         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 0.48%   |
| Dell Wireless 355 Bluetooth                                                         | 5         | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.48%   |
| Broadcom HP Portable Bumble Bee                                                     | 5         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.48%   |
| Apple Bluetooth HCI                                                                 | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1184      | 55.48%  |
| AMD                                             | 547       | 25.63%  |
| Nvidia                                          | 269       | 12.61%  |
| C-Media Electronics                             | 21        | 0.98%   |
| Texas Instruments                               | 13        | 0.61%   |
| Logitech                                        | 13        | 0.61%   |
| Generalplus Technology                          | 9         | 0.42%   |
| Creative Labs                                   | 6         | 0.28%   |
| VIA Technologies                                | 5         | 0.23%   |
| Realtek Semiconductor                           | 5         | 0.23%   |
| Plantronics                                     | 5         | 0.23%   |
| Tenx Technology                                 | 4         | 0.19%   |
| Syntek                                          | 4         | 0.19%   |
| GN Netcom                                       | 4         | 0.19%   |
| Creative Technology                             | 4         | 0.19%   |
| Corsair                                         | 4         | 0.19%   |
| Lenovo                                          | 3         | 0.14%   |
| Kingston Technology                             | 3         | 0.14%   |
| Samson Technologies                             | 2         | 0.09%   |
| Razer USA                                       | 2         | 0.09%   |
| M-Audio                                         | 2         | 0.09%   |
| Focusrite-Novation                              | 2         | 0.09%   |
| ATI Technologies                                | 2         | 0.09%   |
| USB-MIC                                         | 1         | 0.05%   |
| Synaptics                                       | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.05%   |
| Shure                                           | 1         | 0.05%   |
| Sennheiser Communications                       | 1         | 0.05%   |
| SAVITECH                                        | 1         | 0.05%   |
| Microsoft                                       | 1         | 0.05%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.05%   |
| JMTek                                           | 1         | 0.05%   |
| Giga-Byte Technology                            | 1         | 0.05%   |
| FiiO Electronics Technology                     | 1         | 0.05%   |
| DisplayLink                                     | 1         | 0.05%   |
| Dell                                            | 1         | 0.05%   |
| Conexant Systems                                | 1         | 0.05%   |
| Cirrus Logic                                    | 1         | 0.05%   |
| Cambridge Audio                                 | 1         | 0.05%   |
| BR25                                            | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 133       | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 130       | 4.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 125       | 4.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 116       | 4.33%   |
| AMD FCH Azalia Controller                                                                         | 109       | 4.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 93        | 3.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 91        | 3.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 77        | 2.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 73        | 2.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 72        | 2.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 60        | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 60        | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 55        | 2.06%   |
| Intel 8 Series HD Audio Controller                                                                | 55        | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 51        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 49        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 45        | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 43        | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 43        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 40        | 1.49%   |
| AMD High Definition Audio Controller                                                              | 37        | 1.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 36        | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 33        | 1.23%   |
| AMD Trinity HDMI Audio Controller                                                                 | 31        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 1.05%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 24        | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 0.86%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 22        | 0.82%   |
| Nvidia MCP61 High Definition Audio                                                                | 21        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 18        | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 17        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 226       | 23.25%  |
| SK hynix                       | 169       | 17.39%  |
| Kingston                       | 161       | 16.56%  |
| Micron Technology              | 106       | 10.91%  |
| Unknown                        | 85        | 8.74%   |
| A-DATA Technology              | 70        | 7.2%    |
| Corsair                        | 27        | 2.78%   |
| Ramaxel Technology             | 22        | 2.26%   |
| Elpida                         | 15        | 1.54%   |
| Nanya Technology               | 14        | 1.44%   |
| Crucial                        | 12        | 1.23%   |
| Unknown (ABCD)                 | 11        | 1.13%   |
| Patriot                        | 9         | 0.93%   |
| Team                           | 6         | 0.62%   |
| Qimonda                        | 6         | 0.62%   |
| PNY                            | 4         | 0.41%   |
| Transcend                      | 3         | 0.31%   |
| G.Skill                        | 3         | 0.31%   |
| Timetec                        | 2         | 0.21%   |
| Hewlett-Packard                | 2         | 0.21%   |
| ChangXin Memory                | 2         | 0.21%   |
| Avant                          | 2         | 0.21%   |
| Unknown (0x29E)                | 1         | 0.1%    |
| Silicon Power                  | 1         | 0.1%    |
| SHARETRONIC                    | 1         | 0.1%    |
| SGS/Thomson                    | 1         | 0.1%    |
| S                              | 1         | 0.1%    |
| Patriot Memory                 | 1         | 0.1%    |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.1%    |
| Goldkey                        | 1         | 0.1%    |
| Gigabyte Technology            | 1         | 0.1%    |
| CSX                            | 1         | 0.1%    |
| Apacer                         | 1         | 0.1%    |
| Aeneon                         | 1         | 0.1%    |
| 3235CB0010E4                   | 1         | 0.1%    |
| 0161000080AD                   | 1         | 0.1%    |
| Unknown                        | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 2.06%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 1.03%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 10        | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 8         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 7         | 0.66%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s                     | 7         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.56%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 6         | 0.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.56%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 6         | 0.56%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 6         | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.47%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 5         | 0.47%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 0.38%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 4         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 4         | 0.38%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 339       | 41.8%   |
| DDR4    | 317       | 39.09%  |
| DDR2    | 54        | 6.66%   |
| SDRAM   | 24        | 2.96%   |
| LPDDR4  | 23        | 2.84%   |
| Unknown | 23        | 2.84%   |
| LPDDR3  | 22        | 2.71%   |
| DDR     | 8         | 0.99%   |
| RAM     | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 507       | 63.14%  |
| DIMM         | 236       | 29.39%  |
| Row Of Chips | 53        | 6.6%    |
| Chip         | 4         | 0.5%    |
| Unknown      | 2         | 0.25%   |
| RIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 320       | 34.37%  |
| 8192  | 310       | 33.3%   |
| 2048  | 153       | 16.43%  |
| 16384 | 70        | 7.52%   |
| 1024  | 47        | 5.05%   |
| 32768 | 20        | 2.15%   |
| 512   | 7         | 0.75%   |
| 256   | 2         | 0.21%   |
| 32767 | 1         | 0.11%   |
| 128   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 223       | 24.86%  |
| 2667    | 127       | 14.16%  |
| 1333    | 77        | 8.58%   |
| 3200    | 68        | 7.58%   |
| 2400    | 62        | 6.91%   |
| 2133    | 49        | 5.46%   |
| 1334    | 36        | 4.01%   |
| 667     | 34        | 3.79%   |
| 800     | 25        | 2.79%   |
| 3266    | 24        | 2.68%   |
| Unknown | 24        | 2.68%   |
| 3600    | 14        | 1.56%   |
| 1867    | 12        | 1.34%   |
| 1067    | 12        | 1.34%   |
| 1066    | 10        | 1.11%   |
| 3400    | 9         | 1%      |
| 533     | 8         | 0.89%   |
| 4267    | 7         | 0.78%   |
| 3466    | 7         | 0.78%   |
| 3000    | 7         | 0.78%   |
| 2666    | 7         | 0.78%   |
| 2800    | 6         | 0.67%   |
| 2048    | 6         | 0.67%   |
| 1866    | 6         | 0.67%   |
| 975     | 5         | 0.56%   |
| 2933    | 4         | 0.45%   |
| 49926   | 3         | 0.33%   |
| 4199    | 3         | 0.33%   |
| 3733    | 3         | 0.33%   |
| 8400    | 2         | 0.22%   |
| 1332    | 2         | 0.22%   |
| 400     | 2         | 0.22%   |
| 333     | 2         | 0.22%   |
| 4000    | 1         | 0.11%   |
| 3800    | 1         | 0.11%   |
| 3334    | 1         | 0.11%   |
| 3333    | 1         | 0.11%   |
| 2187    | 1         | 0.11%   |
| 2134    | 1         | 0.11%   |
| 2000    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 14        | 33.33%  |
| Brother Industries     | 10        | 23.81%  |
| Hewlett-Packard        | 8         | 19.05%  |
| Canon                  | 4         | 9.52%   |
| Samsung Electronics    | 3         | 7.14%   |
| TSC Auto ID Technology | 1         | 2.38%   |
| Kyocera                | 1         | 2.38%   |
| BIXOLON                | 1         | 2.38%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 13.95%  |
| HP LaserJet Professional P 1102w        | 2         | 4.65%   |
| HP DeskJet 1110 series                  | 2         | 4.65%   |
| Canon G3000 series                      | 2         | 4.65%   |
| Brother MFC-J470DW                      | 2         | 4.65%   |
| Brother HL-1110 series                  | 2         | 4.65%   |
| TSC Auto ID Printer                     | 1         | 2.33%   |
| Seiko Epson XP-230 Series               | 1         | 2.33%   |
| Seiko Epson Printer                     | 1         | 2.33%   |
| Seiko Epson L555 Series                 | 1         | 2.33%   |
| Seiko Epson L4150 Series                | 1         | 2.33%   |
| Seiko Epson L300 Series                 | 1         | 2.33%   |
| Seiko Epson L210 Series                 | 1         | 2.33%   |
| Seiko Epson L200 Series                 | 1         | 2.33%   |
| Seiko Epson L1300 Series                | 1         | 2.33%   |
| Seiko Epson ET-3750 Series              | 1         | 2.33%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.33%   |
| Samsung ML-1660 Series                  | 1         | 2.33%   |
| Samsung M283x Series                    | 1         | 2.33%   |
| Kyocera FS-1030D printer                | 1         | 2.33%   |
| HP OfficeJet Pro 7740 series            | 1         | 2.33%   |
| HP DeskJet F4200 series                 | 1         | 2.33%   |
| HP DeskJet 2620 All-in-One Printer      | 1         | 2.33%   |
| HP Deskjet 2540 series                  | 1         | 2.33%   |
| Canon PIXMA MG3500 Series               | 1         | 2.33%   |
| Canon PIXMA iP3000x Printer             | 1         | 2.33%   |
| Brother MFC-T910DW                      | 1         | 2.33%   |
| Brother MFC-L3770CDW series             | 1         | 2.33%   |
| Brother DCP-T710W                       | 1         | 2.33%   |
| Brother DCP-L2540DW                     | 1         | 2.33%   |
| Brother DCP-1510                        | 1         | 2.33%   |
| Brother Composite Device                | 1         | 2.33%   |
| BIXOLON SRP-350plusIII                  | 1         | 2.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 4         | 80%     |
| Seiko Epson     | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                    | 2         | 40%     |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1         | 20%     |
| HP ScanJet 4500C/5550C                             | 1         | 20%     |
| HP ScanJet 3300c                                   | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 273       | 22.67%  |
| Microdia                               | 105       | 8.72%   |
| IMC Networks                           | 98        | 8.14%   |
| Realtek Semiconductor                  | 85        | 7.06%   |
| Cheng Uei Precision Industry (Foxlink) | 69        | 5.73%   |
| Acer                                   | 66        | 5.48%   |
| Suyin                                  | 60        | 4.98%   |
| Sunplus Innovation Technology          | 57        | 4.73%   |
| Logitech                               | 44        | 3.65%   |
| Quanta                                 | 43        | 3.57%   |
| Apple                                  | 40        | 3.32%   |
| Syntek                                 | 39        | 3.24%   |
| Lite-On Technology                     | 32        | 2.66%   |
| Ricoh                                  | 19        | 1.58%   |
| Silicon Motion                         | 18        | 1.5%    |
| Generalplus Technology                 | 16        | 1.33%   |
| Importek                               | 14        | 1.16%   |
| Alcor Micro                            | 14        | 1.16%   |
| Microsoft                              | 9         | 0.75%   |
| GEMBIRD                                | 8         | 0.66%   |
| Jieli Technology                       | 7         | 0.58%   |
| ALi                                    | 7         | 0.58%   |
| Samsung Electronics                    | 6         | 0.5%    |
| OmniVision Technologies                | 6         | 0.5%    |
| Z-Star Microelectronics                | 5         | 0.42%   |
| Genesys Logic                          | 5         | 0.42%   |
| Y Media                                | 4         | 0.33%   |
| Primax Electronics                     | 4         | 0.33%   |
| MacroSilicon                           | 4         | 0.33%   |
| KYE Systems (Mouse Systems)            | 4         | 0.33%   |
| Sunplus Technology                     | 3         | 0.25%   |
| Luxvisions Innotech Limited            | 3         | 0.25%   |
| LG Electronics                         | 3         | 0.25%   |
| Lenovo                                 | 3         | 0.25%   |
| Cubeternet                             | 3         | 0.25%   |
| Tobii Technology AB                    | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| DigiTech                               | 2         | 0.17%   |
| YGTek                                  | 1         | 0.08%   |
| Xiongmai                               | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 38        | 3.13%   |
| Microdia Integrated_Webcam_HD                                              | 35        | 2.88%   |
| Chicony HD WebCam                                                          | 27        | 2.22%   |
| Acer Integrated Camera                                                     | 24        | 1.98%   |
| IMC Networks Integrated Camera                                             | 22        | 1.81%   |
| Chicony HP Webcam                                                          | 20        | 1.65%   |
| Realtek Integrated_Webcam_HD                                               | 19        | 1.56%   |
| Logitech HD Pro Webcam C920                                                | 16        | 1.32%   |
| Sunplus Integrated_Webcam_HD                                               | 15        | 1.23%   |
| Quanta HP Webcam                                                           | 14        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 1.15%   |
| IMC Networks HD Camera                                                     | 14        | 1.15%   |
| Syntek Integrated Camera                                                   | 13        | 1.07%   |
| Generalplus GENERAL WEBCAM                                                 | 13        | 1.07%   |
| Chicony HP Truevision HD camera                                            | 13        | 1.07%   |
| Chicony HP TrueVision HD                                                   | 13        | 1.07%   |
| Sunplus HD WebCam                                                          | 12        | 0.99%   |
| Lite-On HP Wide Vision HD Camera                                           | 12        | 0.99%   |
| IMC Networks EasyCamera                                                    | 12        | 0.99%   |
| Chicony USB 2.0 Camera                                                     | 12        | 0.99%   |
| Syntek Lenovo EasyCamera                                                   | 11        | 0.91%   |
| Microdia Integrated Webcam                                                 | 10        | 0.82%   |
| Chicony HP Wide Vision HD Camera                                           | 10        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 10        | 0.82%   |
| Apple FaceTime HD Camera                                                   | 10        | 0.82%   |
| Suyin HP Truevision HD                                                     | 9         | 0.74%   |
| Logitech Webcam C270                                                       | 9         | 0.74%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 0.74%   |
| Chicony HP HD Camera                                                       | 9         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 9         | 0.74%   |
| Acer Lenovo EasyCamera                                                     | 9         | 0.74%   |
| Acer EasyCamera                                                            | 9         | 0.74%   |
| Realtek USB Camera                                                         | 8         | 0.66%   |
| Microdia Sonix USB 2.0 Camera                                              | 8         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 8         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 8         | 0.66%   |
| Apple iPhone5/5C/5S/6                                                      | 8         | 0.66%   |
| Apple Built-in iSight                                                      | 8         | 0.66%   |
| Realtek HP Truevision HD                                                   | 7         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 70        | 38.04%  |
| Shenzhen Goodix Technology | 37        | 20.11%  |
| Synaptics                  | 32        | 17.39%  |
| Upek                       | 14        | 7.61%   |
| AuthenTec                  | 14        | 7.61%   |
| Elan Microelectronics      | 6         | 3.26%   |
| STMicroelectronics         | 5         | 2.72%   |
| LighTuning Technology      | 3         | 1.63%   |
| Suprema                    | 1         | 0.54%   |
| Samsung Electronics        | 1         | 0.54%   |
| Focal-systems.Corp         | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 29        | 15.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 8.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 6.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 6.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 4.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 3.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 3.8%    |
| Unknown                                                                    | 7         | 3.8%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.72%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.72%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.72%   |
| AuthenTec AES2810                                                          | 5         | 2.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.17%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.17%   |
| Validity Sensors VFS491                                                    | 3         | 1.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.09%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.09%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.09%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.54%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.54%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.54%   |
| Samsung Fingerprint Device                                                 | 1         | 0.54%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.54%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.54%   |
| AuthenTec AES1600                                                          | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 53.7%   |
| Alcor Micro           | 12        | 22.22%  |
| Upek                  | 7         | 12.96%  |
| Lenovo                | 5         | 9.26%   |
| Gemalto (was Gemplus) | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 24.07%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 20.37%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 12.96%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 9.26%   |
| Broadcom 58200                                                               | 3         | 5.56%   |
| Broadcom 5880                                                                | 2         | 3.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1273      | 70.72%  |
| 1     | 441       | 24.5%   |
| 2     | 73        | 4.06%   |
| 3     | 11        | 0.61%   |
| 7     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 182       | 29.64%  |
| Net/wireless             | 111       | 18.08%  |
| Graphics card            | 104       | 16.94%  |
| Chipcard                 | 52        | 8.47%   |
| Multimedia controller    | 41        | 6.68%   |
| Communication controller | 33        | 5.37%   |
| Bluetooth                | 21        | 3.42%   |
| Camera                   | 14        | 2.28%   |
| Unassigned class         | 10        | 1.63%   |
| Storage                  | 10        | 1.63%   |
| Net/ethernet             | 9         | 1.47%   |
| Sound                    | 7         | 1.14%   |
| Modem                    | 5         | 0.81%   |
| Card reader              | 5         | 0.81%   |
| Network                  | 4         | 0.65%   |
| Storage/raid             | 2         | 0.33%   |
| Video                    | 1         | 0.16%   |
| Storage/ide              | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

