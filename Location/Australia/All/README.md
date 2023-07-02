Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 5289

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | P67A-UD5-B3                 | Desktop     | [b763c860fa](https://linux-hardware.org/?probe=b763c860fa) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [593512053f](https://linux-hardware.org/?probe=593512053f) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac084eba06](https://linux-hardware.org/?probe=ac084eba06) | Jun 24, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | Notebook    | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [16a5102512](https://linux-hardware.org/?probe=16a5102512) | Jun 23, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [efc582d761](https://linux-hardware.org/?probe=efc582d761) | Jun 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d3a63bb6aa](https://linux-hardware.org/?probe=d3a63bb6aa) | Jun 22, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [8c4bd347a7](https://linux-hardware.org/?probe=8c4bd347a7) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [4131c0a5bb](https://linux-hardware.org/?probe=4131c0a5bb) | Jun 20, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [401cb6a1f1](https://linux-hardware.org/?probe=401cb6a1f1) | Jun 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c1aac2f0a4](https://linux-hardware.org/?probe=c1aac2f0a4) | Jun 19, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [daa3df0f31](https://linux-hardware.org/?probe=daa3df0f31) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [f266551c9d](https://linux-hardware.org/?probe=f266551c9d) | Jun 18, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [5e065b17cf](https://linux-hardware.org/?probe=5e065b17cf) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [79c0cd0257](https://linux-hardware.org/?probe=79c0cd0257) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [613aa12940](https://linux-hardware.org/?probe=613aa12940) | Jun 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [993f00eca6](https://linux-hardware.org/?probe=993f00eca6) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [7689518326](https://linux-hardware.org/?probe=7689518326) | Jun 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | Desktop     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| Seco          | C40 C                       | Desktop     | [37b8e950d0](https://linux-hardware.org/?probe=37b8e950d0) | Jun 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [e68b78c037](https://linux-hardware.org/?probe=e68b78c037) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8e46a969c7](https://linux-hardware.org/?probe=8e46a969c7) | Jun 03, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| HP            | 8648                        | Desktop     | [11e777087a](https://linux-hardware.org/?probe=11e777087a) | May 31, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | Notebook    | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| HP            | 83E2                        | Desktop     | [6eea8879ca](https://linux-hardware.org/?probe=6eea8879ca) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [0ff9159d89](https://linux-hardware.org/?probe=0ff9159d89) | May 27, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| HP            | 81B9 1000                   | All in one  | [55380f30ca](https://linux-hardware.org/?probe=55380f30ca) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [a3456d6048](https://linux-hardware.org/?probe=a3456d6048) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| Intel         | NUC11DBBi9 M17026-403       | Mini pc     | [61970448fa](https://linux-hardware.org/?probe=61970448fa) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [83e639f8e7](https://linux-hardware.org/?probe=83e639f8e7) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [749e013179](https://linux-hardware.org/?probe=749e013179) | May 21, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8dcb326301](https://linux-hardware.org/?probe=8dcb326301) | May 21, 2023 |
| ASUSTek       | P5B                         | Desktop     | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| Dell          | Inspiron 7586               | Convertible | [f4aaec3fda](https://linux-hardware.org/?probe=f4aaec3fda) | May 19, 2023 |
| MSI           | VR601                       | Notebook    | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| HP            | Notebook                    | Notebook    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | Notebook    | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [fe80771d2e](https://linux-hardware.org/?probe=fe80771d2e) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [393b2da4bc](https://linux-hardware.org/?probe=393b2da4bc) | May 11, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3dc1af6df9](https://linux-hardware.org/?probe=3dc1af6df9) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| AOpen         | aA70Mx-VW R1.01 55DE8100... | Desktop     | [400b616f1c](https://linux-hardware.org/?probe=400b616f1c) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [36f1aa431d](https://linux-hardware.org/?probe=36f1aa431d) | May 08, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [94ab5e431c](https://linux-hardware.org/?probe=94ab5e431c) | May 07, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [db1ad69341](https://linux-hardware.org/?probe=db1ad69341) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [8c41580881](https://linux-hardware.org/?probe=8c41580881) | May 06, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f743e9293e](https://linux-hardware.org/?probe=f743e9293e) | May 06, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | Notebook    | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [47ff74d363](https://linux-hardware.org/?probe=47ff74d363) | May 03, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a23cace014](https://linux-hardware.org/?probe=a23cace014) | May 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3742def878](https://linux-hardware.org/?probe=3742def878) | May 02, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [fa4e32fe2c](https://linux-hardware.org/?probe=fa4e32fe2c) | May 01, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [a137e6ab62](https://linux-hardware.org/?probe=a137e6ab62) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | Notebook    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [01311e320c](https://linux-hardware.org/?probe=01311e320c) | Apr 30, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [eda4874295](https://linux-hardware.org/?probe=eda4874295) | Apr 30, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [081551c776](https://linux-hardware.org/?probe=081551c776) | Apr 29, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [ee288626f4](https://linux-hardware.org/?probe=ee288626f4) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [048fda2c60](https://linux-hardware.org/?probe=048fda2c60) | Apr 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [d472fb0a32](https://linux-hardware.org/?probe=d472fb0a32) | Apr 28, 2023 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [b3323dcc11](https://linux-hardware.org/?probe=b3323dcc11) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [c01483e50f](https://linux-hardware.org/?probe=c01483e50f) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X99-A                       | Desktop     | [6788eea8d2](https://linux-hardware.org/?probe=6788eea8d2) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | Notebook    | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Dell          | 08WXMX A02                  | Desktop     | [5f68c6a285](https://linux-hardware.org/?probe=5f68c6a285) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| HP            | 0AA8h                       | Desktop     | [071191ddf3](https://linux-hardware.org/?probe=071191ddf3) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5da3166132](https://linux-hardware.org/?probe=5da3166132) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| Shuttle       | DS10U                       | Desktop     | [ffcce61d82](https://linux-hardware.org/?probe=ffcce61d82) | Apr 22, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [1dd1bcd00e](https://linux-hardware.org/?probe=1dd1bcd00e) | Apr 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [e688e656cd](https://linux-hardware.org/?probe=e688e656cd) | Apr 21, 2023 |
| Shuttle       | FS81                        | Desktop     | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Shuttle       | DS10U                       | Desktop     | [b25013d04f](https://linux-hardware.org/?probe=b25013d04f) | Apr 18, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| HP            | 212B                        | Desktop     | [343f1f5eba](https://linux-hardware.org/?probe=343f1f5eba) | Apr 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Gigabyte      | X79-UD5                     | Desktop     | [369c3cfdb2](https://linux-hardware.org/?probe=369c3cfdb2) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [fe75c98b15](https://linux-hardware.org/?probe=fe75c98b15) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | Notebook    | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [5a3fbafb75](https://linux-hardware.org/?probe=5a3fbafb75) | Apr 12, 2023 |
| HP            | 843B                        | Desktop     | [90de5c4ff1](https://linux-hardware.org/?probe=90de5c4ff1) | Apr 12, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [8f9b60caf3](https://linux-hardware.org/?probe=8f9b60caf3) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| Acer          | TM6495T                     | Notebook    | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [8ca7e7c5ad](https://linux-hardware.org/?probe=8ca7e7c5ad) | Apr 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f9382ece8e](https://linux-hardware.org/?probe=f9382ece8e) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [6dd2d460aa](https://linux-hardware.org/?probe=6dd2d460aa) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7d5fb1a311](https://linux-hardware.org/?probe=7d5fb1a311) | Apr 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| SYWZ          | S210H Series                | Desktop     | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [d866c03132](https://linux-hardware.org/?probe=d866c03132) | Apr 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| MSI           | MS-B1831                    | Desktop     | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [aa679005d3](https://linux-hardware.org/?probe=aa679005d3) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [ba686ac542](https://linux-hardware.org/?probe=ba686ac542) | Apr 04, 2023 |
| Shuttle       | DS10U                       | Desktop     | [a35fd102f2](https://linux-hardware.org/?probe=a35fd102f2) | Apr 04, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a87280f55](https://linux-hardware.org/?probe=3a87280f55) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1cb5977d82](https://linux-hardware.org/?probe=1cb5977d82) | Apr 03, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [250384a794](https://linux-hardware.org/?probe=250384a794) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Acer          | EQ45LM                      | Desktop     | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [17d5390549](https://linux-hardware.org/?probe=17d5390549) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [8357ff8cf5](https://linux-hardware.org/?probe=8357ff8cf5) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2be0fa6524](https://linux-hardware.org/?probe=2be0fa6524) | Apr 01, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f64d2db28](https://linux-hardware.org/?probe=1f64d2db28) | Mar 31, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [3ab2e2c720](https://linux-hardware.org/?probe=3ab2e2c720) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [92981c741d](https://linux-hardware.org/?probe=92981c741d) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| Dell          | Precision 5550              | Notebook    | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [de6a63685a](https://linux-hardware.org/?probe=de6a63685a) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [540caaf04c](https://linux-hardware.org/?probe=540caaf04c) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5312ec3cc9](https://linux-hardware.org/?probe=5312ec3cc9) | Mar 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [696a898cd2](https://linux-hardware.org/?probe=696a898cd2) | Mar 24, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e7b21c227](https://linux-hardware.org/?probe=5e7b21c227) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [10269c811b](https://linux-hardware.org/?probe=10269c811b) | Mar 22, 2023 |
| MSI           | MS-7142                     | Desktop     | [1cb67ac1ca](https://linux-hardware.org/?probe=1cb67ac1ca) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8c50d5ae87](https://linux-hardware.org/?probe=8c50d5ae87) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASUSTek       | Maximus Extreme             | Desktop     | [c6215ec2f3](https://linux-hardware.org/?probe=c6215ec2f3) | Mar 20, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [99cb000a4e](https://linux-hardware.org/?probe=99cb000a4e) | Mar 19, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [cd75bab781](https://linux-hardware.org/?probe=cd75bab781) | Mar 13, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [4ac1bccada](https://linux-hardware.org/?probe=4ac1bccada) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [46c1d399ac](https://linux-hardware.org/?probe=46c1d399ac) | Mar 11, 2023 |
| Gigabyte      | Z590 AORUS ELITE            | Desktop     | [790a51e99f](https://linux-hardware.org/?probe=790a51e99f) | Mar 11, 2023 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7413353e38](https://linux-hardware.org/?probe=7413353e38) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89647ee142](https://linux-hardware.org/?probe=89647ee142) | Mar 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | Notebook    | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| Google        | Ultima                      | Notebook    | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [e0b2fdc347](https://linux-hardware.org/?probe=e0b2fdc347) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3be3c8d79d](https://linux-hardware.org/?probe=3be3c8d79d) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8ecbea06f8](https://linux-hardware.org/?probe=8ecbea06f8) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [25c46b6f70](https://linux-hardware.org/?probe=25c46b6f70) | Mar 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [08346526f3](https://linux-hardware.org/?probe=08346526f3) | Mar 01, 2023 |
| Biostar       | B450MH                      | Desktop     | [aa05ee87d1](https://linux-hardware.org/?probe=aa05ee87d1) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [75249be116](https://linux-hardware.org/?probe=75249be116) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [ce67684fdf](https://linux-hardware.org/?probe=ce67684fdf) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| HP            | 0AECh D                     | Desktop     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Medion        | MAG Z390M MORTAR            | Desktop     | [e2445cf24c](https://linux-hardware.org/?probe=e2445cf24c) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d65a9c975d](https://linux-hardware.org/?probe=d65a9c975d) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [e293e73518](https://linux-hardware.org/?probe=e293e73518) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [2cc51656a5](https://linux-hardware.org/?probe=2cc51656a5) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| AZW           | GTi                         | Desktop     | [17bb698441](https://linux-hardware.org/?probe=17bb698441) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [aa49c18960](https://linux-hardware.org/?probe=aa49c18960) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0365a40dd4](https://linux-hardware.org/?probe=0365a40dd4) | Feb 18, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [65c778e356](https://linux-hardware.org/?probe=65c778e356) | Feb 16, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f12f20217b](https://linux-hardware.org/?probe=f12f20217b) | Feb 15, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [27ddce20a1](https://linux-hardware.org/?probe=27ddce20a1) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f298c1fc7e](https://linux-hardware.org/?probe=f298c1fc7e) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [45cfd72091](https://linux-hardware.org/?probe=45cfd72091) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [0ad0fe310f](https://linux-hardware.org/?probe=0ad0fe310f) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b563d8f052](https://linux-hardware.org/?probe=b563d8f052) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | Notebook    | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | Notebook    | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [99dda6c06c](https://linux-hardware.org/?probe=99dda6c06c) | Feb 09, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [30363b3a5d](https://linux-hardware.org/?probe=30363b3a5d) | Feb 09, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [fff70a8d2c](https://linux-hardware.org/?probe=fff70a8d2c) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [16c72d3532](https://linux-hardware.org/?probe=16c72d3532) | Feb 08, 2023 |
| Alienware     | m15 R7                      | Notebook    | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0f4be18646](https://linux-hardware.org/?probe=0f4be18646) | Feb 07, 2023 |
| HP            | 0AA0h                       | Desktop     | [921b7f0d0c](https://linux-hardware.org/?probe=921b7f0d0c) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2f0810d441](https://linux-hardware.org/?probe=2f0810d441) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2b9cb5eea6](https://linux-hardware.org/?probe=2b9cb5eea6) | Feb 05, 2023 |
| Intel         | X99                         | Desktop     | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [38625b9f02](https://linux-hardware.org/?probe=38625b9f02) | Feb 03, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6ffe048ee2](https://linux-hardware.org/?probe=6ffe048ee2) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [fff64928e8](https://linux-hardware.org/?probe=fff64928e8) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [2cd1d2f51f](https://linux-hardware.org/?probe=2cd1d2f51f) | Feb 03, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | Notebook    | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [cb1e6fa666](https://linux-hardware.org/?probe=cb1e6fa666) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [e3e8d72420](https://linux-hardware.org/?probe=e3e8d72420) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [7560429d05](https://linux-hardware.org/?probe=7560429d05) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [b0697611f6](https://linux-hardware.org/?probe=b0697611f6) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [840102fa91](https://linux-hardware.org/?probe=840102fa91) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [2c34aba28a](https://linux-hardware.org/?probe=2c34aba28a) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [d9508d5b22](https://linux-hardware.org/?probe=d9508d5b22) | Jan 27, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [06086e6112](https://linux-hardware.org/?probe=06086e6112) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [fab7cead8c](https://linux-hardware.org/?probe=fab7cead8c) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Pegatron      | 2AEE                        | Desktop     | [1c59133176](https://linux-hardware.org/?probe=1c59133176) | Jan 24, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ea5c2d01c2](https://linux-hardware.org/?probe=ea5c2d01c2) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| HP            | 8860 A                      | Desktop     | [ffb17b2c42](https://linux-hardware.org/?probe=ffb17b2c42) | Jan 23, 2023 |
| Alienware     | 15 R4                       | Notebook    | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [447e624609](https://linux-hardware.org/?probe=447e624609) | Jan 22, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [852add0d4b](https://linux-hardware.org/?probe=852add0d4b) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | Notebook    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [74d7964357](https://linux-hardware.org/?probe=74d7964357) | Jan 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [46a3691da9](https://linux-hardware.org/?probe=46a3691da9) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [1b41330a7e](https://linux-hardware.org/?probe=1b41330a7e) | Jan 20, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [ff72c387c7](https://linux-hardware.org/?probe=ff72c387c7) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [1a80b30106](https://linux-hardware.org/?probe=1a80b30106) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [91a963e420](https://linux-hardware.org/?probe=91a963e420) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ed9e94399a](https://linux-hardware.org/?probe=ed9e94399a) | Jan 18, 2023 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [8d4e5b4499](https://linux-hardware.org/?probe=8d4e5b4499) | Jan 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c7f31be903](https://linux-hardware.org/?probe=c7f31be903) | Jan 18, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [fb01eafa41](https://linux-hardware.org/?probe=fb01eafa41) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0d7c3e0009](https://linux-hardware.org/?probe=0d7c3e0009) | Jan 17, 2023 |
| Dell          | 075CGM A00                  | Mini pc     | [5df3707c20](https://linux-hardware.org/?probe=5df3707c20) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| HP            | ProLiant DL380 G6           | Server      | [73b5a8c763](https://linux-hardware.org/?probe=73b5a8c763) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [dc3317fe82](https://linux-hardware.org/?probe=dc3317fe82) | Jan 14, 2023 |
| ASUSTek       | GL10DH                      | Desktop     | [c1f3c3b1c4](https://linux-hardware.org/?probe=c1f3c3b1c4) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [79753b9bcd](https://linux-hardware.org/?probe=79753b9bcd) | Jan 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [6a129c6fde](https://linux-hardware.org/?probe=6a129c6fde) | Jan 13, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [433bc4fddd](https://linux-hardware.org/?probe=433bc4fddd) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | Notebook    | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [7c8a02d00a](https://linux-hardware.org/?probe=7c8a02d00a) | Jan 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [252041601b](https://linux-hardware.org/?probe=252041601b) | Jan 12, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [1859af08ff](https://linux-hardware.org/?probe=1859af08ff) | Jan 11, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [22ee51c3f8](https://linux-hardware.org/?probe=22ee51c3f8) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [06eee6367f](https://linux-hardware.org/?probe=06eee6367f) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [f03ae5d905](https://linux-hardware.org/?probe=f03ae5d905) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [9645ad91cc](https://linux-hardware.org/?probe=9645ad91cc) | Jan 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [5656924057](https://linux-hardware.org/?probe=5656924057) | Jan 10, 2023 |
| SYWZ          | S210HA Series               | Desktop     | [0cabf3b51e](https://linux-hardware.org/?probe=0cabf3b51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | Notebook    | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [29ac3deef8](https://linux-hardware.org/?probe=29ac3deef8) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [3b4f027444](https://linux-hardware.org/?probe=3b4f027444) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [5b62f9f024](https://linux-hardware.org/?probe=5b62f9f024) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| Dell          | Latitude 7280               | Notebook    | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | Notebook    | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [8df8f7c51f](https://linux-hardware.org/?probe=8df8f7c51f) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Acer          | Predator G9-793             | Notebook    | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [e6190d3469](https://linux-hardware.org/?probe=e6190d3469) | Jan 07, 2023 |
| HP            | 212A                        | Desktop     | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| HP            | 1905                        | Desktop     | [01fb70526d](https://linux-hardware.org/?probe=01fb70526d) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | 821D                        | Desktop     | [d859c928b8](https://linux-hardware.org/?probe=d859c928b8) | Jan 05, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [cf98b88234](https://linux-hardware.org/?probe=cf98b88234) | Jan 05, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [88ea27e220](https://linux-hardware.org/?probe=88ea27e220) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0RRXFP A00                  | All in one  | [38be4b535f](https://linux-hardware.org/?probe=38be4b535f) | Jan 04, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [f30031a156](https://linux-hardware.org/?probe=f30031a156) | Jan 04, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [5b07c849cc](https://linux-hardware.org/?probe=5b07c849cc) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | Notebook    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Intel         | NUC6i7KYB H90766-404        | Mini pc     | [961f0cc73a](https://linux-hardware.org/?probe=961f0cc73a) | Jan 02, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [1de40c1ae3](https://linux-hardware.org/?probe=1de40c1ae3) | Jan 02, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [1e4997593d](https://linux-hardware.org/?probe=1e4997593d) | Jan 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [99d2f193c4](https://linux-hardware.org/?probe=99d2f193c4) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | Notebook    | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| HP            | 1905                        | Desktop     | [5c576316f8](https://linux-hardware.org/?probe=5c576316f8) | Dec 28, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | Notebook    | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [10b9f48473](https://linux-hardware.org/?probe=10b9f48473) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [d88bd74acf](https://linux-hardware.org/?probe=d88bd74acf) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3073d2d4e1](https://linux-hardware.org/?probe=3073d2d4e1) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29e02a10bf](https://linux-hardware.org/?probe=29e02a10bf) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [36fbefc790](https://linux-hardware.org/?probe=36fbefc790) | Dec 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [b8b3b4f2bd](https://linux-hardware.org/?probe=b8b3b4f2bd) | Dec 19, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| MSI           | Boston                      | Desktop     | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d54bfbf8ff](https://linux-hardware.org/?probe=d54bfbf8ff) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [310076ab4f](https://linux-hardware.org/?probe=310076ab4f) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [de15eb8246](https://linux-hardware.org/?probe=de15eb8246) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [aad215d28c](https://linux-hardware.org/?probe=aad215d28c) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [0f506ff34d](https://linux-hardware.org/?probe=0f506ff34d) | Dec 15, 2022 |
| HP            | 212A                        | Desktop     | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [259f85d65b](https://linux-hardware.org/?probe=259f85d65b) | Dec 12, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [6c3fcfbb13](https://linux-hardware.org/?probe=6c3fcfbb13) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Dell          | XPS L521X                   | Notebook    | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| Gigabyte      | EP45-DS4P                   | Desktop     | [5acdccf7c0](https://linux-hardware.org/?probe=5acdccf7c0) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [3a67010b28](https://linux-hardware.org/?probe=3a67010b28) | Dec 08, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | Desktop     | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| HP            | 3395                        | All in one  | [daedb871f5](https://linux-hardware.org/?probe=daedb871f5) | Dec 08, 2022 |
| HP            | ProLiant DL380 Gen9         | Server      | [d368f224c8](https://linux-hardware.org/?probe=d368f224c8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d1e2a097a9](https://linux-hardware.org/?probe=d1e2a097a9) | Dec 07, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| Dell          | G15 5511                    | Notebook    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [32594286ae](https://linux-hardware.org/?probe=32594286ae) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [e3d7eb48ec](https://linux-hardware.org/?probe=e3d7eb48ec) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c2a68eb192](https://linux-hardware.org/?probe=c2a68eb192) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [7e188d7537](https://linux-hardware.org/?probe=7e188d7537) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| IBM           | 90Y4784                     | Server      | [a9289ca04c](https://linux-hardware.org/?probe=a9289ca04c) | Dec 02, 2022 |
| Dell          | 01V648 A02                  | Server      | [b8747a97b7](https://linux-hardware.org/?probe=b8747a97b7) | Dec 02, 2022 |
| Intel         | S1200RP G62251-405          | Server      | [28f4ceb8ee](https://linux-hardware.org/?probe=28f4ceb8ee) | Dec 02, 2022 |
| IBM           | 00MV214                     | Server      | [f2d1382390](https://linux-hardware.org/?probe=f2d1382390) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [85f6854ce5](https://linux-hardware.org/?probe=85f6854ce5) | Dec 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [919c5d80c8](https://linux-hardware.org/?probe=919c5d80c8) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0949d0916c](https://linux-hardware.org/?probe=0949d0916c) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [6352050887](https://linux-hardware.org/?probe=6352050887) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [e902390c9c](https://linux-hardware.org/?probe=e902390c9c) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f9ff6b9e31](https://linux-hardware.org/?probe=f9ff6b9e31) | Dec 02, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [717d165f0e](https://linux-hardware.org/?probe=717d165f0e) | Dec 02, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [da83c87218](https://linux-hardware.org/?probe=da83c87218) | Dec 01, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c14e2149eb](https://linux-hardware.org/?probe=c14e2149eb) | Dec 01, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [ba1e414d62](https://linux-hardware.org/?probe=ba1e414d62) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| AMI           | Intel                       | Notebook    | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | Notebook    | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | Notebook    | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Razer         | Blade Pro                   | Notebook    | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| HP            | 18E9                        | Desktop     | [dab5e242fd](https://linux-hardware.org/?probe=dab5e242fd) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1d224863f2](https://linux-hardware.org/?probe=1d224863f2) | Nov 24, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [db4e4c9c5b](https://linux-hardware.org/?probe=db4e4c9c5b) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [39bcd0f2d8](https://linux-hardware.org/?probe=39bcd0f2d8) | Nov 22, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Acer          | TravelMate Spin B118-R      | Convertible | [16dc5dd369](https://linux-hardware.org/?probe=16dc5dd369) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cb18ed6ab1](https://linux-hardware.org/?probe=cb18ed6ab1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| HP            | 1495                        | Desktop     | [3ac774a6d6](https://linux-hardware.org/?probe=3ac774a6d6) | Nov 19, 2022 |
| HP            | 1495                        | Desktop     | [659062ad1d](https://linux-hardware.org/?probe=659062ad1d) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [4bba69ecd9](https://linux-hardware.org/?probe=4bba69ecd9) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbbfcd826c](https://linux-hardware.org/?probe=dbbfcd826c) | Nov 18, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| Dell          | 0D6H9T A01                  | Desktop     | [a50bca5670](https://linux-hardware.org/?probe=a50bca5670) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [769e7a63d1](https://linux-hardware.org/?probe=769e7a63d1) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5e42accb39](https://linux-hardware.org/?probe=5e42accb39) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | Notebook    | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Notebook    | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| Acer          | Aspire XC-840               | Desktop     | [fe8db55aac](https://linux-hardware.org/?probe=fe8db55aac) | Nov 14, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [acce4cc1af](https://linux-hardware.org/?probe=acce4cc1af) | Nov 13, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [67c110e0a7](https://linux-hardware.org/?probe=67c110e0a7) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [ea94d443c9](https://linux-hardware.org/?probe=ea94d443c9) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | Notebook    | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [dbf32417df](https://linux-hardware.org/?probe=dbf32417df) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8c775416b9](https://linux-hardware.org/?probe=8c775416b9) | Nov 08, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [43bf170205](https://linux-hardware.org/?probe=43bf170205) | Nov 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [638b6a52ff](https://linux-hardware.org/?probe=638b6a52ff) | Nov 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ee895bde1f](https://linux-hardware.org/?probe=ee895bde1f) | Nov 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0e2747c7ab](https://linux-hardware.org/?probe=0e2747c7ab) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [67928f8921](https://linux-hardware.org/?probe=67928f8921) | Nov 07, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [27acb96a8f](https://linux-hardware.org/?probe=27acb96a8f) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a38da64b4f](https://linux-hardware.org/?probe=a38da64b4f) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7ea9f2df61](https://linux-hardware.org/?probe=7ea9f2df61) | Nov 06, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [dd757fb650](https://linux-hardware.org/?probe=dd757fb650) | Nov 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| HP            | 3396                        | Desktop     | [d6867789ca](https://linux-hardware.org/?probe=d6867789ca) | Nov 04, 2022 |
| MSI           | Katana GF76 12UC            | Notebook    | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c4b2b4072b](https://linux-hardware.org/?probe=c4b2b4072b) | Nov 04, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [80e0ccbf42](https://linux-hardware.org/?probe=80e0ccbf42) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | Notebook    | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | Notebook    | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | Desktop     | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| HP            | 8653 A                      | Desktop     | [9c19089f51](https://linux-hardware.org/?probe=9c19089f51) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 433       | 12.24%  |
| Ubuntu 18.04       | 173       | 4.89%   |
| Ubuntu 22.04       | 142       | 4.01%   |
| Debian 11          | 101       | 2.85%   |
| Pop!_OS 22.04      | 90        | 2.54%   |
| OpenMandriva 4.3   | 74        | 2.09%   |
| Linux Mint 20.3    | 74        | 2.09%   |
| KDE neon 20.04     | 71        | 2.01%   |
| Zorin 16           | 66        | 1.86%   |
| Arch Rolling       | 66        | 1.86%   |
| Fedora 36          | 65        | 1.84%   |
| Pop!_OS 21.04      | 64        | 1.81%   |
| OpenMandriva 4.2   | 56        | 1.58%   |
| Pop!_OS 20.04      | 51        | 1.44%   |
| Fedora 37          | 50        | 1.41%   |
| Linux Mint 20.2    | 49        | 1.38%   |
| Pop!_OS 20.10      | 48        | 1.36%   |
| Ubuntu 21.10       | 46        | 1.3%    |
| Manjaro            | 45        | 1.27%   |
| Arch               | 44        | 1.24%   |
| Linux Mint 21.1    | 42        | 1.19%   |
| Linux Mint 20.1    | 42        | 1.19%   |
| Fedora 35          | 42        | 1.19%   |
| Ubuntu 19.04       | 41        | 1.16%   |
| Fedora 33          | 41        | 1.16%   |
| Ubuntu 20.10       | 39        | 1.1%    |
| ArcoLinux Rolling  | 39        | 1.1%    |
| Fedora 34          | 38        | 1.07%   |
| Ubuntu 21.04       | 37        | 1.05%   |
| Ubuntu 19.10       | 37        | 1.05%   |
| Linux Mint 19.3    | 36        | 1.02%   |
| Linux Mint 20      | 33        | 0.93%   |
| Fedora 38          | 32        | 0.9%    |
| OpenMandriva 23.01 | 31        | 0.88%   |
| Xubuntu 18.04      | 30        | 0.85%   |
| Pop!_OS 21.10      | 30        | 0.85%   |
| Xubuntu 20.04      | 29        | 0.82%   |
| Ubuntu 22.10       | 29        | 0.82%   |
| OpenMandriva 23.03 | 29        | 0.82%   |
| Fedora 32          | 29        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 974       | 29.51%  |
| Linux Mint    | 311       | 9.42%   |
| Pop!_OS       | 270       | 8.18%   |
| Fedora        | 255       | 7.72%   |
| OpenMandriva  | 207       | 6.27%   |
| Debian        | 159       | 4.82%   |
| Arch          | 109       | 3.3%    |
| Zorin         | 100       | 3.03%   |
| Manjaro       | 99        | 3%      |
| KDE neon      | 98        | 2.97%   |
| Xubuntu       | 82        | 2.48%   |
| Kubuntu       | 72        | 2.18%   |
| ArcoLinux     | 40        | 1.21%   |
| Elementary    | 36        | 1.09%   |
| Gentoo        | 34        | 1.03%   |
| openSUSE      | 30        | 0.91%   |
| ROSA          | 29        | 0.88%   |
| Kali          | 28        | 0.85%   |
| Ubuntu MATE   | 26        | 0.79%   |
| Clear Linux   | 25        | 0.76%   |
| ClearOS       | 23        | 0.7%    |
| Lubuntu       | 21        | 0.64%   |
| EndeavourOS   | 19        | 0.58%   |
| Endless       | 18        | 0.55%   |
| BlackPanther  | 18        | 0.55%   |
| MX            | 17        | 0.51%   |
| LMDE          | 15        | 0.45%   |
| Ubuntu Unity  | 14        | 0.42%   |
| Parrot        | 13        | 0.39%   |
| SteamOS       | 12        | 0.36%   |
| CentOS        | 11        | 0.33%   |
| Raspbian      | 10        | 0.3%    |
| Ubuntu Budgie | 9         | 0.27%   |
| Feren OS      | 8         | 0.24%   |
| Nobara        | 7         | 0.21%   |
| LinuxFX       | 7         | 0.21%   |
| Rocky Linux   | 6         | 0.18%   |
| Reborn OS     | 6         | 0.18%   |
| Solus         | 5         | 0.15%   |
| Manjaro-ARM   | 5         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 71        | 1.73%   |
| 5.4.0-42-generic         | 64        | 1.56%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.27%   |
| 5.4.0-40-generic         | 30        | 0.73%   |
| 5.15.0-56-generic        | 30        | 0.73%   |
| 5.11.0-7620-generic      | 30        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 29        | 0.71%   |
| 5.4.0-58-generic         | 29        | 0.71%   |
| 6.2.6-desktop-1omv2390   | 27        | 0.66%   |
| 5.4.0-48-generic         | 27        | 0.66%   |
| 5.15.0-52-generic        | 25        | 0.61%   |
| 5.4.0-26-generic         | 24        | 0.59%   |
| 5.3.0-46-generic         | 24        | 0.59%   |
| 5.4.0-52-generic         | 23        | 0.56%   |
| 5.15.0-58-generic        | 23        | 0.56%   |
| 5.11.0-37-generic        | 23        | 0.56%   |
| 5.4.0-29-generic         | 22        | 0.54%   |
| 5.3.0-40-generic         | 22        | 0.54%   |
| 5.3.0-28-generic         | 22        | 0.54%   |
| 5.17.5-76051705-generic  | 21        | 0.51%   |
| 5.15.0-48-generic        | 21        | 0.51%   |
| 5.11.0-27-generic        | 20        | 0.49%   |
| 5.4.0-7634-generic       | 19        | 0.46%   |
| 5.15.0-46-generic        | 19        | 0.46%   |
| 6.2.0-20-generic         | 18        | 0.44%   |
| 5.4.0-74-generic         | 18        | 0.44%   |
| 5.4.0-47-generic         | 18        | 0.44%   |
| 5.13.0-7620-generic      | 17        | 0.41%   |
| 6.2.6-76060206-generic   | 16        | 0.39%   |
| 6.0.12-76060006-generic  | 16        | 0.39%   |
| 5.8.0-7630-generic       | 16        | 0.39%   |
| 5.8.0-44-generic         | 16        | 0.39%   |
| 5.4.0-91-generic         | 16        | 0.39%   |
| 5.4.0-65-generic         | 16        | 0.39%   |
| 5.19.0-38-generic        | 16        | 0.39%   |
| 5.15.0-41-generic        | 16        | 0.39%   |
| 5.13.0-40-generic        | 16        | 0.39%   |
| 4.15.0-99-generic        | 16        | 0.39%   |
| 5.8.0-7642-generic       | 15        | 0.37%   |
| 5.8.0-63-generic         | 15        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 570       | 15.06%  |
| 5.15.0  | 274       | 7.24%   |
| 5.11.0  | 228       | 6.02%   |
| 5.13.0  | 191       | 5.05%   |
| 5.8.0   | 181       | 4.78%   |
| 4.15.0  | 161       | 4.25%   |
| 5.3.0   | 128       | 3.38%   |
| 5.19.0  | 111       | 2.93%   |
| 5.10.0  | 105       | 2.77%   |
| 5.0.0   | 86        | 2.27%   |
| 5.16.7  | 72        | 1.9%    |
| 4.18.0  | 65        | 1.72%   |
| 5.10.14 | 52        | 1.37%   |
| 6.2.6   | 45        | 1.19%   |
| 6.1.1   | 36        | 0.95%   |
| 4.19.0  | 36        | 0.95%   |
| 5.17.5  | 31        | 0.82%   |
| 3.10.0  | 30        | 0.79%   |
| 6.2.0   | 27        | 0.71%   |
| 6.0.12  | 22        | 0.58%   |
| 6.0.0   | 19        | 0.5%    |
| 6.1.0   | 17        | 0.45%   |
| 5.18.0  | 15        | 0.4%    |
| 5.16.11 | 14        | 0.37%   |
| 5.14.0  | 14        | 0.37%   |
| 6.0.7   | 13        | 0.34%   |
| 5.18.10 | 13        | 0.34%   |
| 5.16.0  | 13        | 0.34%   |
| 4.4.0   | 13        | 0.34%   |
| 5.17.0  | 11        | 0.29%   |
| 4.18.16 | 11        | 0.29%   |
| 6.0.6   | 10        | 0.26%   |
| 5.9.16  | 10        | 0.26%   |
| 5.6.14  | 10        | 0.26%   |
| 5.18.12 | 10        | 0.26%   |
| 5.15.11 | 10        | 0.26%   |
| 5.13.13 | 10        | 0.26%   |
| 5.11.12 | 10        | 0.26%   |
| 4.9.60  | 10        | 0.26%   |
| 6.0.9   | 9         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 621       | 16.91%  |
| 5.15    | 381       | 10.38%  |
| 5.11    | 267       | 7.27%   |
| 5.13    | 237       | 6.45%   |
| 5.8     | 228       | 6.21%   |
| 5.10    | 219       | 5.96%   |
| 4.15    | 161       | 4.38%   |
| 5.19    | 159       | 4.33%   |
| 5.16    | 154       | 4.19%   |
| 5.3     | 143       | 3.89%   |
| 6.2     | 117       | 3.19%   |
| 6.1     | 116       | 3.16%   |
| 6.0     | 106       | 2.89%   |
| 5.0     | 95        | 2.59%   |
| 5.17    | 83        | 2.26%   |
| 5.18    | 80        | 2.18%   |
| 4.18    | 78        | 2.12%   |
| 5.14    | 46        | 1.25%   |
| 5.12    | 46        | 1.25%   |
| 4.19    | 46        | 1.25%   |
| 5.6     | 45        | 1.23%   |
| 5.9     | 38        | 1.03%   |
| 6.3     | 32        | 0.87%   |
| 4.9     | 30        | 0.82%   |
| 3.10    | 30        | 0.82%   |
| 5.5     | 26        | 0.71%   |
| 5.7     | 25        | 0.68%   |
| 5.2     | 17        | 0.46%   |
| 4.4     | 14        | 0.38%   |
| 5.1     | 9         | 0.25%   |
| 4.1     | 4         | 0.11%   |
| 4.20    | 3         | 0.08%   |
| 4.14    | 3         | 0.08%   |
| 4.13    | 3         | 0.08%   |
| 3.16    | 2         | 0.05%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3040      | 96.94%  |
| i686    | 49        | 1.56%   |
| aarch64 | 28        | 0.89%   |
| armv7l  | 13        | 0.41%   |
| riscv64 | 2         | 0.06%   |
| i586    | 2         | 0.06%   |
| armv6l  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1440      | 43.4%   |
| KDE5             | 531       | 16%     |
| Unknown          | 392       | 11.81%  |
| X-Cinnamon       | 264       | 7.96%   |
| XFCE             | 229       | 6.9%    |
| KDE              | 100       | 3.01%   |
| MATE             | 98        | 2.95%   |
| Cinnamon         | 60        | 1.81%   |
| Pantheon         | 34        | 1.02%   |
| LXQt             | 24        | 0.72%   |
| Unity            | 19        | 0.57%   |
| LXDE             | 19        | 0.57%   |
| KDE4             | 18        | 0.54%   |
| i3               | 17        | 0.51%   |
| Budgie           | 17        | 0.51%   |
| awesome          | 8         | 0.24%   |
| GNOME Classic    | 7         | 0.21%   |
| Deepin           | 7         | 0.21%   |
| openbox          | 6         | 0.18%   |
| GNOME Flashback  | 4         | 0.12%   |
| xmonad           | 3         | 0.09%   |
| BunsenLabs       | 3         | 0.09%   |
| qtile            | 2         | 0.06%   |
| Hyprland         | 2         | 0.06%   |
| dwm              | 2         | 0.06%   |
| bspwm            | 2         | 0.06%   |
| Trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| pop              | 1         | 0.03%   |
| Phosh:GNOME      | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2492      | 76.68%  |
| Wayland | 460       | 14.15%  |
| Unknown | 178       | 5.48%   |
| Tty     | 119       | 3.66%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1745      | 53.28%  |
| SDDM    | 455       | 13.89%  |
| GDM     | 341       | 10.41%  |
| LightDM | 326       | 9.95%   |
| GDM3    | 288       | 8.79%   |
| TDM     | 85        | 2.6%    |
| KDM     | 17        | 0.52%   |
| SLiM    | 6         | 0.18%   |
| LXDM    | 5         | 0.15%   |
| XDM     | 4         | 0.12%   |
| Ly      | 2         | 0.06%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 2286      | 70.4%   |
| en_US        | 489       | 15.06%  |
| Unknown      | 324       | 9.98%   |
| C            | 72        | 2.22%   |
| en_GB        | 52        | 1.6%    |
| C.UTF8       | 6         | 0.18%   |
| de_DE        | 3         | 0.09%   |
| zh_CN        | 2         | 0.06%   |
| POSIX        | 2         | 0.06%   |
| en_CA        | 2         | 0.06%   |
| ru_RU        | 1         | 0.03%   |
| it_IT        | 1         | 0.03%   |
| fr_FR        | 1         | 0.03%   |
| es_ES        | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_GB.UTF-12 | 1         | 0.03%   |
| en_BW        | 1         | 0.03%   |
| en_AU.UFT-8  | 1         | 0.03%   |
| en-AU        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1652      | 51.37%  |
| EFI  | 1564      | 48.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2397      | 74.39%  |
| Btrfs   | 306       | 9.5%    |
| Overlay | 230       | 7.14%   |
| Unknown | 100       | 3.1%    |
| Xfs     | 84        | 2.61%   |
| Zfs     | 48        | 1.49%   |
| Tmpfs   | 32        | 0.99%   |
| Ext2    | 10        | 0.31%   |
| Ext3    | 5         | 0.16%   |
| XXXXXXX | 4         | 0.12%   |
| F2fs    | 4         | 0.12%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1796      | 55.66%  |
| GPT     | 1115      | 34.55%  |
| MBR     | 316       | 9.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2706      | 84.3%   |
| Yes       | 504       | 15.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2370      | 73.88%  |
| Yes       | 838       | 26.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 453       | 14.47%  |
| Hewlett-Packard         | 407       | 13%     |
| Dell                    | 401       | 12.81%  |
| Gigabyte Technology     | 374       | 11.95%  |
| Lenovo                  | 330       | 10.54%  |
| MSI                     | 203       | 6.49%   |
| Acer                    | 157       | 5.02%   |
| Apple                   | 144       | 4.6%    |
| ASRock                  | 123       | 3.93%   |
| Toshiba                 | 104       | 3.32%   |
| Intel                   | 89        | 2.84%   |
| Microsoft               | 34        | 1.09%   |
| Raspberry Pi Foundation | 29        | 0.93%   |
| Alienware               | 21        | 0.67%   |
| Unknown                 | 21        | 0.67%   |
| Samsung Electronics     | 15        | 0.48%   |
| AMI                     | 11        | 0.35%   |
| Sony                    | 10        | 0.32%   |
| Pegatron                | 10        | 0.32%   |
| Notebook                | 10        | 0.32%   |
| Timi                    | 8         | 0.26%   |
| Medion                  | 8         | 0.26%   |
| Google                  | 8         | 0.26%   |
| Panasonic               | 7         | 0.22%   |
| IT Channel Pty          | 7         | 0.22%   |
| IBM                     | 7         | 0.22%   |
| HUAWEI                  | 7         | 0.22%   |
| Supermicro              | 6         | 0.19%   |
| Razer                   | 6         | 0.19%   |
| Metabox                 | 6         | 0.19%   |
| ECS                     | 6         | 0.19%   |
| Valve                   | 5         | 0.16%   |
| System76                | 5         | 0.16%   |
| Shuttle                 | 5         | 0.16%   |
| Pine Microsystems       | 5         | 0.16%   |
| Kogan                   | 5         | 0.16%   |
| Intel Client Systems    | 5         | 0.16%   |
| Fanless Mini PC         | 5         | 0.16%   |
| Hardkernel              | 4         | 0.13%   |
| ReachingTech            | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 33        | 1.05%   |
| Dell OptiPlex 9020                     | 26        | 0.83%   |
| Unknown                                | 25        | 0.8%    |
| HP Pavilion dv6                        | 17        | 0.54%   |
| HP Notebook                            | 12        | 0.38%   |
| MSI MS-7B89                            | 11        | 0.35%   |
| HP Pavilion g6                         | 11        | 0.35%   |
| RPi Raspberry Pi                       | 10        | 0.32%   |
| Gigabyte 970A-D3P                      | 10        | 0.32%   |
| Dell OptiPlex 780                      | 10        | 0.32%   |
| MSI MS-7817                            | 9         | 0.29%   |
| HP Pavilion 15                         | 9         | 0.29%   |
| Apple iMac12,2                         | 9         | 0.29%   |
| MSI MS-7C37                            | 8         | 0.26%   |
| Apple MacBookPro10,1                   | 8         | 0.26%   |
| Apple MacBookAir7,2                    | 8         | 0.26%   |
| Gigabyte X58A-UD3R                     | 7         | 0.22%   |
| Gigabyte B75M-D3H                      | 7         | 0.22%   |
| Dell XPS 15 9570                       | 7         | 0.22%   |
| Apple MacBookPro9,2                    | 7         | 0.22%   |
| Apple MacBookPro8,1                    | 7         | 0.22%   |
| MSI MS-7C94                            | 6         | 0.19%   |
| MSI MS-7C84                            | 6         | 0.19%   |
| MSI MS-7C02                            | 6         | 0.19%   |
| Microsoft Surface Laptop 3             | 6         | 0.19%   |
| Dell XPS 13 9360                       | 6         | 0.19%   |
| Dell OptiPlex 990                      | 6         | 0.19%   |
| Dell OptiPlex 9010                     | 6         | 0.19%   |
| Acer ConceptD CN315-71P                | 6         | 0.19%   |
| Valve Jupiter                          | 5         | 0.16%   |
| Toshiba Satellite P750                 | 5         | 0.16%   |
| Toshiba Satellite L850                 | 5         | 0.16%   |
| MSI MS-7B86                            | 5         | 0.16%   |
| MSI MS-7A38                            | 5         | 0.16%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 5         | 0.16%   |
| HP Compaq 8200 Elite SFF PC            | 5         | 0.16%   |
| Gigabyte Z77MX-D3H                     | 5         | 0.16%   |
| Gigabyte X570 AORUS PRO WIFI           | 5         | 0.16%   |
| Gigabyte GA-870A-UD3                   | 5         | 0.16%   |
| Gigabyte B85M-HD3                      | 5         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 153       | 4.89%   |
| Acer Aspire         | 105       | 3.35%   |
| Dell OptiPlex       | 95        | 3.04%   |
| HP Pavilion         | 83        | 2.65%   |
| Toshiba Satellite   | 82        | 2.62%   |
| Dell Latitude       | 80        | 2.56%   |
| Dell Inspiron       | 78        | 2.49%   |
| ASUS PRIME          | 67        | 2.14%   |
| Dell XPS            | 63        | 2.01%   |
| ASUS ROG            | 59        | 1.88%   |
| HP EliteBook        | 53        | 1.69%   |
| Lenovo IdeaPad      | 45        | 1.44%   |
| HP Compaq           | 42        | 1.34%   |
| Dell Precision      | 41        | 1.31%   |
| Microsoft Surface   | 34        | 1.09%   |
| Lenovo ThinkCentre  | 34        | 1.09%   |
| Lenovo Yoga         | 33        | 1.05%   |
| ASUS TUF            | 33        | 1.05%   |
| ASUS All            | 33        | 1.05%   |
| HP ProBook          | 31        | 0.99%   |
| RPi Raspberry       | 29        | 0.93%   |
| HP Laptop           | 25        | 0.8%    |
| Unknown             | 25        | 0.8%    |
| Gigabyte X570       | 22        | 0.7%    |
| HP ENVY             | 20        | 0.64%   |
| Gigabyte B450       | 18        | 0.58%   |
| Dell Vostro         | 16        | 0.51%   |
| ASUS Zenbook        | 15        | 0.48%   |
| Gigabyte B450M      | 13        | 0.42%   |
| HP Spectre          | 12        | 0.38%   |
| HP Notebook         | 12        | 0.38%   |
| ASUS VivoBook       | 12        | 0.38%   |
| Apple MacBookPro10  | 12        | 0.38%   |
| Toshiba PORTEGE     | 11        | 0.35%   |
| MSI MS-7B89         | 11        | 0.35%   |
| Lenovo ThinkStation | 11        | 0.35%   |
| HP ProDesk          | 11        | 0.35%   |
| Apple iMac12        | 11        | 0.35%   |
| Acer Swift          | 11        | 0.35%   |
| Lenovo IdeaPadFlex  | 10        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 304       | 9.71%   |
| 2018    | 291       | 9.3%    |
| 2020    | 271       | 8.66%   |
| 2012    | 253       | 8.08%   |
| 2013    | 233       | 7.44%   |
| 2011    | 228       | 7.28%   |
| 2017    | 210       | 6.71%   |
| 2021    | 188       | 6.01%   |
| 2016    | 186       | 5.94%   |
| 2014    | 184       | 5.88%   |
| 2015    | 162       | 5.18%   |
| 2010    | 155       | 4.95%   |
| 2008    | 117       | 3.74%   |
| 2009    | 116       | 3.71%   |
| 2022    | 93        | 2.97%   |
| 2007    | 55        | 1.76%   |
| Unknown | 42        | 1.34%   |
| 2006    | 20        | 0.64%   |
| 2005    | 12        | 0.38%   |
| 2023    | 6         | 0.19%   |
| 2004    | 2         | 0.06%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1405      | 44.89%  |
| Notebook       | 1342      | 42.88%  |
| Convertible    | 105       | 3.35%   |
| Mini pc        | 80        | 2.56%   |
| All in one     | 77        | 2.46%   |
| Tablet         | 52        | 1.66%   |
| System on chip | 36        | 1.15%   |
| Server         | 27        | 0.86%   |
| Phone          | 3         | 0.1%    |
| Stick pc       | 3         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2904      | 92.13%  |
| Enabled  | 248       | 7.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3116      | 99.55%  |
| Yes  | 14        | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 788       | 24.57%  |
| 4.01-8.0        | 661       | 20.61%  |
| 8.01-16.0       | 533       | 16.62%  |
| 3.01-4.0        | 496       | 15.47%  |
| 32.01-64.0      | 403       | 12.57%  |
| 64.01-256.0     | 121       | 3.77%   |
| 1.01-2.0        | 102       | 3.18%   |
| 24.01-32.0      | 57        | 1.78%   |
| 2.01-3.0        | 20        | 0.62%   |
| 0.51-1.0        | 14        | 0.44%   |
| 0.01-0.5        | 7         | 0.22%   |
| More than 256.0 | 4         | 0.12%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1197      | 33.19%  |
| 2.01-3.0    | 909       | 25.21%  |
| 4.01-8.0    | 523       | 14.5%   |
| 3.01-4.0    | 472       | 13.09%  |
| 0.51-1.0    | 224       | 6.21%   |
| 8.01-16.0   | 181       | 5.02%   |
| 0.01-0.5    | 49        | 1.36%   |
| 16.01-24.0  | 28        | 0.78%   |
| 24.01-32.0  | 12        | 0.33%   |
| 32.01-64.0  | 4         | 0.11%   |
| 64.01-256.0 | 3         | 0.08%   |
| 0           | 2         | 0.06%   |
| Unknown     | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1760      | 53.37%  |
| 2       | 802       | 24.32%  |
| 3       | 320       | 9.7%    |
| 4       | 188       | 5.7%    |
| 5       | 84        | 2.55%   |
| 6       | 47        | 1.43%   |
| 0       | 34        | 1.03%   |
| 7       | 24        | 0.73%   |
| 8       | 18        | 0.55%   |
| 9       | 9         | 0.27%   |
| 10      | 5         | 0.15%   |
| 13      | 3         | 0.09%   |
| 36      | 1         | 0.03%   |
| 14      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1909      | 60.24%  |
| Yes       | 1260      | 39.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2721      | 86.71%  |
| No        | 417       | 13.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2330      | 73.57%  |
| No        | 837       | 26.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1824      | 57.32%  |
| No        | 1358      | 42.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 3130      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 865       | 25.68%  |
| Melbourne      | 671       | 19.92%  |
| Brisbane       | 484       | 14.37%  |
| Perth          | 287       | 8.52%   |
| Adelaide       | 203       | 6.03%   |
| Canberra       | 74        | 2.2%    |
| Wahroonga      | 39        | 1.16%   |
| Hobart         | 32        | 0.95%   |
| Launceston     | 25        | 0.74%   |
| Alexandria     | 20        | 0.59%   |
| Gold Coast     | 18        | 0.53%   |
| Surry Hills    | 17        | 0.5%    |
| Geelong        | 13        | 0.39%   |
| Lane Cove      | 12        | 0.36%   |
| Central Coast  | 12        | 0.36%   |
| Woolloongabba  | 11        | 0.33%   |
| Richmond       | 11        | 0.33%   |
| Newcastle      | 11        | 0.33%   |
| Mitcham        | 11        | 0.33%   |
| Southport      | 10        | 0.3%    |
| Brighton       | 9         | 0.27%   |
| Wollongong     | 8         | 0.24%   |
| Traralgon      | 8         | 0.24%   |
| Townsville     | 7         | 0.21%   |
| Parramatta     | 7         | 0.21%   |
| North Sydney   | 7         | 0.21%   |
| Mandurah       | 7         | 0.21%   |
| Macquarie Park | 7         | 0.21%   |
| Artarmon       | 7         | 0.21%   |
| West End       | 6         | 0.18%   |
| Point Cook     | 6         | 0.18%   |
| Mount Waverley | 6         | 0.18%   |
| Spring Field   | 5         | 0.15%   |
| Ringwood East  | 5         | 0.15%   |
| Northcote      | 5         | 0.15%   |
| Mascot         | 5         | 0.15%   |
| Hawthorn       | 5         | 0.15%   |
| Geraldton      | 5         | 0.15%   |
| Doncaster      | 5         | 0.15%   |
| Clifton Hill   | 5         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 902       | 1625   | 18.56%  |
| Seagate                     | 804       | 1527   | 16.55%  |
| WDC                         | 734       | 1408   | 15.11%  |
| Crucial                     | 260       | 394    | 5.35%   |
| Toshiba                     | 255       | 358    | 5.25%   |
| Kingston                    | 221       | 285    | 4.55%   |
| SanDisk                     | 191       | 252    | 3.93%   |
| Unknown                     | 188       | 276    | 3.87%   |
| Intel                       | 179       | 324    | 3.68%   |
| Hitachi                     | 151       | 241    | 3.11%   |
| SK hynix                    | 97        | 120    | 2%      |
| Apple                       | 84        | 114    | 1.73%   |
| HGST                        | 73        | 110    | 1.5%    |
| Micron Technology           | 66        | 85     | 1.36%   |
| Micron/Crucial Technology   | 53        | 73     | 1.09%   |
| Phison                      | 37        | 56     | 0.76%   |
| SPCC                        | 34        | 42     | 0.7%    |
| OCZ                         | 34        | 51     | 0.7%    |
| KIOXIA                      | 32        | 34     | 0.66%   |
| A-DATA Technology           | 31        | 42     | 0.64%   |
| Phison Electronics          | 20        | 26     | 0.41%   |
| LITEON                      | 20        | 33     | 0.41%   |
| Corsair                     | 20        | 34     | 0.41%   |
| JMicron Technology          | 19        | 23     | 0.39%   |
| LITEONIT                    | 18        | 25     | 0.37%   |
| KingSpec                    | 16        | 36     | 0.33%   |
| Fujitsu                     | 16        | 20     | 0.33%   |
| Unknown                     | 15        | 16     | 0.31%   |
| Transcend                   | 14        | 21     | 0.29%   |
| Patriot                     | 14        | 21     | 0.29%   |
| LaCie                       | 13        | 20     | 0.27%   |
| Gigabyte Technology         | 13        | 16     | 0.27%   |
| Kingston Technology Company | 12        | 15     | 0.25%   |
| China                       | 12        | 14     | 0.25%   |
| ASMT                        | 12        | 19     | 0.25%   |
| Silicon Motion              | 9         | 20     | 0.19%   |
| Maxtor                      | 9         | 12     | 0.19%   |
| Realtek Semiconductor       | 8         | 11     | 0.16%   |
| Hewlett-Packard             | 8         | 12     | 0.16%   |
| XPG                         | 7         | 8      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 59        | 1.05%   |
| Samsung SSD 850 EVO 250GB                           | 47        | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 43        | 0.77%   |
| Unknown MMC Card  32GB                              | 37        | 0.66%   |
| Crucial CT240BX500SSD1 240GB                        | 35        | 0.63%   |
| Unknown MMC Card  64GB                              | 34        | 0.61%   |
| Seagate ST500DM002-1BD142 500GB                     | 34        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 34        | 0.61%   |
| Seagate Expansion Desk 5TB                          | 34        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                        | 34        | 0.61%   |
| Seagate Expansion 1TB                               | 33        | 0.59%   |
| Samsung SSD 850 EVO 500GB                           | 33        | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB                      | 32        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                      | 32        | 0.57%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.57%   |
| Samsung SSD 860 EVO 1TB                             | 31        | 0.55%   |
| Kingston SA400S37240G 240GB SSD                     | 30        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB                      | 29        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.5%    |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB                      | 26        | 0.46%   |
| Seagate ST3500418AS 500GB                           | 25        | 0.45%   |
| Crucial CT480BX500SSD1 480GB                        | 25        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.45%   |
| Toshiba MQ01ABD100 1TB                              | 23        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 23        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.41%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.39%   |
| Seagate ST31000528AS 1TB                            | 21        | 0.38%   |
| Seagate ST2000DL003-9VT166 2TB                      | 21        | 0.38%   |
| Samsung SSD 860 QVO 1TB                             | 21        | 0.38%   |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB                            | 20        | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                      | 20        | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 0.36%   |
| Crucial CT1000BX500SSD1 1TB                         | 20        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 19        | 0.34%   |
| Unknown SD/MMC/MS PRO 250GB                         | 19        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                      | 19        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 789       | 1483   | 39.77%  |
| WDC                 | 601       | 1174   | 30.29%  |
| Toshiba             | 173       | 256    | 8.72%   |
| Hitachi             | 151       | 241    | 7.61%   |
| Samsung Electronics | 93        | 230    | 4.69%   |
| HGST                | 71        | 108    | 3.58%   |
| Apple               | 23        | 29     | 1.16%   |
| Unknown             | 21        | 32     | 1.06%   |
| Fujitsu             | 15        | 19     | 0.76%   |
| LaCie               | 10        | 16     | 0.5%    |
| Maxtor              | 9         | 12     | 0.45%   |
| ASMT                | 8         | 15     | 0.4%    |
| USB                 | 4         | 5      | 0.2%    |
| Hewlett-Packard     | 3         | 4      | 0.15%   |
| KESU                | 2         | 2      | 0.1%    |
| HGST HUS            | 2         | 2      | 0.1%    |
| USB3.0              | 1         | 2      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| MaxDigital          | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| IBM/Hitachi         | 1         | 1      | 0.05%   |
| HPE                 | 1         | 1      | 0.05%   |
| Hajaan              | 1         | 1      | 0.05%   |
| DAS                 | 1         | 1      | 0.05%   |
| AAPL                | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 506       | 837    | 30.97%  |
| Crucial             | 223       | 347    | 13.65%  |
| Kingston            | 160       | 206    | 9.79%   |
| SanDisk             | 125       | 156    | 7.65%   |
| WDC                 | 121       | 161    | 7.41%   |
| Intel               | 88        | 184    | 5.39%   |
| Apple               | 44        | 49     | 2.69%   |
| SK hynix            | 34        | 40     | 2.08%   |
| OCZ                 | 34        | 51     | 2.08%   |
| SPCC                | 30        | 36     | 1.84%   |
| Toshiba             | 27        | 36     | 1.65%   |
| Micron Technology   | 26        | 30     | 1.59%   |
| LITEONIT            | 18        | 25     | 1.1%    |
| LITEON              | 18        | 31     | 1.1%    |
| A-DATA Technology   | 18        | 24     | 1.1%    |
| KingSpec            | 15        | 35     | 0.92%   |
| Transcend           | 14        | 21     | 0.86%   |
| Patriot             | 14        | 21     | 0.86%   |
| Corsair             | 13        | 27     | 0.8%    |
| Seagate             | 12        | 19     | 0.73%   |
| China               | 12        | 14     | 0.73%   |
| TO Exter            | 7         | 7      | 0.43%   |
| Gigabyte Technology | 7         | 7      | 0.43%   |
| OWC                 | 6         | 16     | 0.37%   |
| Plextor             | 5         | 17     | 0.31%   |
| Lexar               | 4         | 4      | 0.24%   |
| KingFast            | 4         | 4      | 0.24%   |
| Team                | 3         | 4      | 0.18%   |
| ASMT                | 3         | 3      | 0.18%   |
| Vaseky              | 2         | 6      | 0.12%   |
| T-CREATE            | 2         | 2      | 0.12%   |
| PNY                 | 2         | 2      | 0.12%   |
| NGFF                | 2         | 2      | 0.12%   |
| Hajaan              | 2         | 2      | 0.12%   |
| FORESEE             | 2         | 2      | 0.12%   |
| External            | 2         | 2      | 0.12%   |
| XPG                 | 1         | 1      | 0.06%   |
| WDC WDS2            | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |
| T-FORCE             | 1         | 1      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1608      | 3639   | 37.54%  |
| SSD     | 1416      | 2467   | 33.05%  |
| NVMe    | 1028      | 1606   | 24%     |
| MMC     | 165       | 232    | 3.85%   |
| Unknown | 67        | 95     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2361      | 5781   | 61.94%  |
| NVMe | 1022      | 1585   | 26.81%  |
| SAS  | 264       | 441    | 6.93%   |
| MMC  | 165       | 232    | 4.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1703      | 3222   | 51.7%   |
| 0.51-1.0   | 880       | 1560   | 26.72%  |
| 1.01-2.0   | 381       | 677    | 11.57%  |
| 4.01-10.0  | 125       | 250    | 3.79%   |
| 3.01-4.0   | 119       | 253    | 3.61%   |
| 2.01-3.0   | 79        | 135    | 2.4%    |
| 10.01-20.0 | 6         | 8      | 0.18%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 764       | 22.54%  |
| 251-500        | 693       | 20.44%  |
| 501-1000       | 519       | 15.31%  |
| 1001-2000      | 312       | 9.2%    |
| More than 3000 | 274       | 8.08%   |
| 1-20           | 271       | 7.99%   |
| 51-100         | 230       | 6.78%   |
| 2001-3000      | 128       | 3.78%   |
| Unknown        | 101       | 2.98%   |
| 21-50          | 98        | 2.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1341      | 37.73%  |
| 21-50          | 578       | 16.26%  |
| 101-250        | 392       | 11.03%  |
| 51-100         | 365       | 10.27%  |
| 251-500        | 294       | 8.27%   |
| 501-1000       | 193       | 5.43%   |
| 1001-2000      | 130       | 3.66%   |
| More than 3000 | 108       | 3.04%   |
| Unknown        | 101       | 2.84%   |
| 2001-3000      | 50        | 1.41%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 7         | 35     | 2.41%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 18     | 1.72%   |
| Seagate ST3500418AS 500GB               | 5         | 14     | 1.72%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 1.72%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.38%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 1.03%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.03%   |
| Seagate ST2000DM001-9YN164 2TB          | 3         | 3      | 1.03%   |
| Seagate ST2000DM001-1CH164 2TB          | 3         | 3      | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 1.03%   |
| Maxtor 6Y080L0 82GB                     | 3         | 5      | 1.03%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 1.03%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 3         | 3      | 1.03%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 1.03%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 1.03%   |
| Crucial CT525MX300SSD1 528GB            | 3         | 5      | 1.03%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.69%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.69%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 3      | 0.69%   |
| WDC WD20EARS-00J2GB0 2TB                | 2         | 2      | 0.69%   |
| WDC WD2002FAEX-007BA0 2TB               | 2         | 3      | 0.69%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.69%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 2         | 2      | 0.69%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.69%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.69%   |
| WDC WD10EADS-11M2B1 1TB                 | 2         | 2      | 0.69%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 3      | 0.69%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.69%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 0.69%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.69%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.69%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.69%   |
| Seagate ST3500413AS 500GB               | 2         | 2      | 0.69%   |
| Seagate ST31000528AS 1TB                | 2         | 2      | 0.69%   |
| Seagate ST31000333AS 1TB                | 2         | 4      | 0.69%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 2      | 0.69%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 2      | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 2      | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 6      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 72        | 119    | 26.28%  |
| WDC                      | 54        | 92     | 19.71%  |
| Samsung Electronics      | 27        | 72     | 9.85%   |
| Hitachi                  | 23        | 26     | 8.39%   |
| Intel                    | 19        | 60     | 6.93%   |
| Toshiba                  | 13        | 17     | 4.74%   |
| Kingston                 | 12        | 12     | 4.38%   |
| HGST                     | 9         | 10     | 3.28%   |
| SanDisk                  | 6         | 6      | 2.19%   |
| Maxtor                   | 6         | 9      | 2.19%   |
| Crucial                  | 6         | 8      | 2.19%   |
| Fujitsu                  | 4         | 4      | 1.46%   |
| Corsair                  | 4         | 5      | 1.46%   |
| SK hynix                 | 3         | 3      | 1.09%   |
| Apple                    | 2         | 2      | 0.73%   |
| Transcend                | 1         | 1      | 0.36%   |
| SPCC                     | 1         | 1      | 0.36%   |
| Realtek Semiconductor    | 1         | 2      | 0.36%   |
| OCZ                      | 1         | 1      | 0.36%   |
| Netac                    | 1         | 1      | 0.36%   |
| MaxDigital               | 1         | 1      | 0.36%   |
| KingSpec                 | 1         | 3      | 0.36%   |
| KingFast                 | 1         | 1      | 0.36%   |
| HPE                      | 1         | 1      | 0.36%   |
| Hewlett-Packard          | 1         | 2      | 0.36%   |
| Gigabyte Technology      | 1         | 1      | 0.36%   |
| Biwin Storage Technology | 1         | 1      | 0.36%   |
| ASMT                     | 1         | 1      | 0.36%   |
| A-DATA Technology        | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 119    | 36.73%  |
| WDC                 | 53        | 89     | 27.04%  |
| Hitachi             | 23        | 26     | 11.73%  |
| Samsung Electronics | 13        | 57     | 6.63%   |
| Toshiba             | 11        | 15     | 5.61%   |
| HGST                | 9         | 10     | 4.59%   |
| Maxtor              | 6         | 9      | 3.06%   |
| Fujitsu             | 4         | 4      | 2.04%   |
| MaxDigital          | 1         | 1      | 0.51%   |
| HPE                 | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 2      | 0.51%   |
| ASMT                | 1         | 1      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 176       | 335    | 69.29%  |
| SSD  | 65        | 111    | 25.59%  |
| NVMe | 13        | 17     | 5.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2017      | 4657   | 59.03%  |
| Works    | 1152      | 2912   | 33.71%  |
| Malfunc  | 246       | 463    | 7.2%    |
| Failed   | 2         | 7      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2079      | 50.51%  |
| AMD                              | 621       | 15.09%  |
| Samsung Electronics              | 423       | 10.28%  |
| SanDisk                          | 108       | 2.62%   |
| Marvell Technology Group         | 93        | 2.26%   |
| Micron/Crucial Technology        | 91        | 2.21%   |
| ASMedia Technology               | 82        | 1.99%   |
| Kingston Technology Company      | 76        | 1.85%   |
| JMicron Technology               | 72        | 1.75%   |
| Phison Electronics               | 69        | 1.68%   |
| SK hynix                         | 64        | 1.55%   |
| Toshiba America Info Systems     | 56        | 1.36%   |
| Micron Technology                | 41        | 1%      |
| KIOXIA                           | 31        | 0.75%   |
| Nvidia                           | 28        | 0.68%   |
| ADATA Technology                 | 22        | 0.53%   |
| Silicon Motion                   | 19        | 0.46%   |
| LSI Logic / Symbios Logic        | 19        | 0.46%   |
| Apple                            | 17        | 0.41%   |
| VIA Technologies                 | 11        | 0.27%   |
| Realtek Semiconductor            | 11        | 0.27%   |
| Broadcom / LSI                   | 11        | 0.27%   |
| Seagate Technology               | 9         | 0.22%   |
| Integrated Technology Express    | 8         | 0.19%   |
| Solid State Storage Technology   | 7         | 0.17%   |
| Silicon Image                    | 6         | 0.15%   |
| Hewlett-Packard                  | 6         | 0.15%   |
| Lite-On Technology               | 5         | 0.12%   |
| Union Memory (Shenzhen)          | 4         | 0.1%    |
| Adaptec                          | 4         | 0.1%    |
| ULi Electronics                  | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| 3ware                            | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| Biwin Storage Technology         | 2         | 0.05%   |
| Promise Technology               | 1         | 0.02%   |
| PMC-Sierra                       | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 434       | 9.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 218       | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 159       | 3.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 129       | 2.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 112       | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 103       | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 103       | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 91        | 1.9%    |
| Intel SATA Controller [RAID mode]                                                       | 86        | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 86        | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 73        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 72        | 1.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 69        | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 68        | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 63        | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 63        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 62        | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                                  | 60        | 1.25%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 56        | 1.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 56        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 56        | 1.17%   |
| Samsung NVMe SSD Controller 980                                                         | 55        | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 55        | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 50        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 47        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 43        | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 40        | 0.83%   |
| Micron/Crucial NVMe Storage Controller                                                  | 36        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36        | 0.75%   |
| Intel SSD 660P Series                                                                   | 35        | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 35        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 35        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 33        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 32        | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 32        | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 29        | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 29        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2243      | 55.45%  |
| NVMe | 1028      | 25.41%  |
| IDE  | 450       | 11.12%  |
| RAID | 294       | 7.27%   |
| SAS  | 21        | 0.52%   |
| SCSI | 9         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2375      | 75.88%  |
| AMD           | 710       | 22.68%  |
| ARM           | 42        | 1.34%   |
| sifive,u74-mc | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |
| Unknown       | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 41        | 1.31%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 35        | 1.12%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 35        | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 30        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 0.92%   |
| ARM Processor                           | 28        | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 28        | 0.89%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 27        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 26        | 0.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 26        | 0.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 25        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 25        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 24        | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 24        | 0.76%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 24        | 0.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 23        | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 23        | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 22        | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 20        | 0.64%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 20        | 0.64%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 20        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 19        | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 19        | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 18        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 17        | 0.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 17        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 17        | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 16        | 0.51%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 14        | 0.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 14        | 0.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 14        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 14        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 14        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 13        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 831       | 26.52%  |
| Intel Core i5           | 683       | 21.79%  |
| Other                   | 209       | 6.67%   |
| AMD Ryzen 5             | 184       | 5.87%   |
| AMD Ryzen 7             | 137       | 4.37%   |
| Intel Core i3           | 134       | 4.28%   |
| Intel Core 2 Duo        | 131       | 4.18%   |
| Intel Celeron           | 116       | 3.7%    |
| Intel Xeon              | 84        | 2.68%   |
| AMD Ryzen 9             | 75        | 2.39%   |
| Intel Pentium           | 50        | 1.6%    |
| AMD FX                  | 47        | 1.5%    |
| Intel Atom              | 32        | 1.02%   |
| AMD A6                  | 31        | 0.99%   |
| AMD A4                  | 27        | 0.86%   |
| AMD Ryzen 3             | 25        | 0.8%    |
| Intel Core 2 Quad       | 23        | 0.73%   |
| Intel Core 2            | 23        | 0.73%   |
| AMD A8                  | 22        | 0.7%    |
| Intel Core i9           | 20        | 0.64%   |
| Intel Pentium Dual-Core | 18        | 0.57%   |
| AMD Phenom II X4        | 15        | 0.48%   |
| AMD E2                  | 15        | 0.48%   |
| AMD A10                 | 15        | 0.48%   |
| ARM BCM                 | 12        | 0.38%   |
| AMD Ryzen Threadripper  | 12        | 0.38%   |
| AMD Phenom II X6        | 10        | 0.32%   |
| Intel Core m3           | 9         | 0.29%   |
| AMD Ryzen 7 PRO         | 9         | 0.29%   |
| AMD Athlon              | 9         | 0.29%   |
| Intel Pentium Dual      | 8         | 0.26%   |
| Intel Genuine           | 8         | 0.26%   |
| AMD E1                  | 8         | 0.26%   |
| Intel Pentium D         | 7         | 0.22%   |
| Intel Core M            | 6         | 0.19%   |
| Intel Pentium Silver    | 5         | 0.16%   |
| Intel Pentium 4         | 5         | 0.16%   |
| AMD Phenom II X2        | 5         | 0.16%   |
| AMD E                   | 5         | 0.16%   |
| AMD Athlon II X4        | 5         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1227      | 39.1%   |
| 2       | 1049      | 33.43%  |
| 6       | 382       | 12.17%  |
| 8       | 233       | 7.43%   |
| 12      | 74        | 2.36%   |
| 1       | 58        | 1.85%   |
| 16      | 43        | 1.37%   |
| 10      | 20        | 0.64%   |
| 3       | 19        | 0.61%   |
| 14      | 13        | 0.41%   |
| 24      | 8         | 0.25%   |
| 32      | 4         | 0.13%   |
| Unknown | 4         | 0.13%   |
| 40      | 2         | 0.06%   |
| 128     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3082      | 98.44%  |
| 2       | 44        | 1.41%   |
| Unknown | 4         | 0.13%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2156      | 68.77%  |
| 1       | 971       | 30.97%  |
| Unknown | 4         | 0.13%   |
| 8       | 2         | 0.06%   |
| 4       | 2         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3040      | 96.78%  |
| Unknown        | 72        | 2.29%   |
| 32-bit         | 23        | 0.73%   |
| 64-bit         | 6         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 924       | 28.27%  |
| 0x206a7    | 176       | 5.38%   |
| 0x306a9    | 162       | 4.96%   |
| 0x306c3    | 142       | 4.34%   |
| 0x1067a    | 95        | 2.91%   |
| 0x906ea    | 86        | 2.63%   |
| 0x906e9    | 69        | 2.11%   |
| 0x506e3    | 69        | 2.11%   |
| 0x806e9    | 63        | 1.93%   |
| 0x406e3    | 60        | 1.84%   |
| 0x08701021 | 57        | 1.74%   |
| 0x40651    | 56        | 1.71%   |
| 0x806ea    | 55        | 1.68%   |
| 0x806ec    | 54        | 1.65%   |
| 0x806c1    | 53        | 1.62%   |
| 0x306d4    | 45        | 1.38%   |
| 0x20655    | 45        | 1.38%   |
| 0x08701013 | 34        | 1.04%   |
| 0x0800820d | 32        | 0.98%   |
| 0x106e5    | 31        | 0.95%   |
| 0x10676    | 28        | 0.86%   |
| 0x30678    | 26        | 0.8%    |
| 0x0a50000c | 26        | 0.8%    |
| 0x20652    | 24        | 0.73%   |
| 0xa0652    | 22        | 0.67%   |
| 0x706e5    | 22        | 0.67%   |
| 0x06000852 | 22        | 0.67%   |
| 0x906ed    | 21        | 0.64%   |
| 0x106a5    | 21        | 0.64%   |
| 0x06006705 | 21        | 0.64%   |
| 0x806eb    | 19        | 0.58%   |
| 0x0a201016 | 19        | 0.58%   |
| 0x08108109 | 19        | 0.58%   |
| 0x010000c8 | 19        | 0.58%   |
| 0x6fb      | 18        | 0.55%   |
| 0x06001119 | 18        | 0.55%   |
| 0x206c2    | 17        | 0.52%   |
| 0x08001138 | 17        | 0.52%   |
| 0x07030105 | 17        | 0.52%   |
| 0x6fd      | 16        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 505       | 16.1%   |
| Haswell          | 310       | 9.88%   |
| IvyBridge        | 239       | 7.62%   |
| SandyBridge      | 238       | 7.59%   |
| Skylake          | 188       | 5.99%   |
| Zen 2            | 163       | 5.2%    |
| Penryn           | 149       | 4.75%   |
| Zen 3            | 115       | 3.67%   |
| Unknown          | 115       | 3.67%   |
| Westmere         | 111       | 3.54%   |
| Zen+             | 81        | 2.58%   |
| Core             | 71        | 2.26%   |
| CometLake        | 71        | 2.26%   |
| Zen              | 69        | 2.2%    |
| TigerLake        | 67        | 2.14%   |
| Silvermont       | 66        | 2.1%    |
| Broadwell        | 66        | 2.1%    |
| Nehalem          | 63        | 2.01%   |
| Piledriver       | 58        | 1.85%   |
| K10              | 52        | 1.66%   |
| Icelake          | 52        | 1.66%   |
| Excavator        | 41        | 1.31%   |
| Alderlake Hybrid | 40        | 1.28%   |
| Goldmont plus    | 35        | 1.12%   |
| Puma             | 23        | 0.73%   |
| Goldmont         | 21        | 0.67%   |
| Steamroller      | 16        | 0.51%   |
| Bonnell          | 16        | 0.51%   |
| NetBurst         | 14        | 0.45%   |
| P6               | 13        | 0.41%   |
| Jaguar           | 13        | 0.41%   |
| Bulldozer        | 13        | 0.41%   |
| K8 Hammer        | 12        | 0.38%   |
| K10 Llano        | 12        | 0.38%   |
| Bobcat           | 9         | 0.29%   |
| Tremont          | 7         | 0.22%   |
| K8 & K10 hybrid  | 2         | 0.06%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1671      | 45.62%  |
| Nvidia                           | 1130      | 30.85%  |
| AMD                              | 831       | 22.69%  |
| Matrox Electronics Systems       | 19        | 0.52%   |
| VIA Technologies                 | 4         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| ASPEED Technology                | 3         | 0.08%   |
| Neomagic                         | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 158       | 4.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 109       | 2.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 88        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 78        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 76        | 2.01%   |
| Intel UHD Graphics 620                                                                   | 72        | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 71        | 1.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 63        | 1.67%   |
| Intel HD Graphics 620                                                                    | 62        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 1.48%   |
| Intel HD Graphics 530                                                                    | 55        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 1.27%   |
| Intel HD Graphics 630                                                                    | 47        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 44        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 43        | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 1.08%   |
| Intel HD Graphics 5500                                                                   | 37        | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 0.93%   |
| AMD Renoir                                                                               | 34        | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 32        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 31        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 29        | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 29        | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 0.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 25        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 25        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 24        | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 22        | 0.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 21        | 0.56%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 20        | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 0.53%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 19        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1166      | 36.76%  |
| 1 x Nvidia               | 708       | 22.32%  |
| 1 x AMD                  | 655       | 20.65%  |
| Intel + Nvidia           | 369       | 11.63%  |
| Intel + AMD              | 77        | 2.43%   |
| 2 x AMD                  | 58        | 1.83%   |
| AMD + Nvidia             | 45        | 1.42%   |
| Other                    | 44        | 1.39%   |
| 1 x Matrox               | 16        | 0.5%    |
| 2 x Nvidia               | 10        | 0.32%   |
| 2 x Intel                | 4         | 0.13%   |
| 1 x VIA                  | 4         | 0.13%   |
| 1 x SiS                  | 3         | 0.09%   |
| Nvidia + Matrox          | 3         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.09%   |
| Nvidia + ASPEED          | 2         | 0.06%   |
| 1 x Neomagic             | 2         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |
| 1 x ASPEED               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2415      | 75.21%  |
| Proprietary | 637       | 19.84%  |
| Unknown     | 159       | 4.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1725      | 53.14%  |
| 1.01-2.0   | 397       | 12.23%  |
| 0.01-0.5   | 285       | 8.78%   |
| 0.51-1.0   | 249       | 7.67%   |
| 3.01-4.0   | 233       | 7.18%   |
| 7.01-8.0   | 187       | 5.76%   |
| 5.01-6.0   | 79        | 2.43%   |
| 8.01-16.0  | 49        | 1.51%   |
| 2.01-3.0   | 28        | 0.86%   |
| 16.01-24.0 | 11        | 0.34%   |
| 4.01-5.0   | 2         | 0.06%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 428       | 12.13%  |
| AU Optronics            | 344       | 9.75%   |
| Dell                    | 269       | 7.62%   |
| LG Display              | 249       | 7.06%   |
| Chimei Innolux          | 196       | 5.55%   |
| Acer                    | 176       | 4.99%   |
| BOE                     | 166       | 4.7%    |
| Goldstar                | 149       | 4.22%   |
| Hewlett-Packard         | 141       | 4%      |
| BenQ                    | 135       | 3.83%   |
| Apple                   | 129       | 3.66%   |
| Philips                 | 116       | 3.29%   |
| Ancor Communications    | 99        | 2.81%   |
| AOC                     | 96        | 2.72%   |
| Sharp                   | 85        | 2.41%   |
| ViewSonic               | 76        | 2.15%   |
| Lenovo                  | 69        | 1.96%   |
| Unknown                 | 59        | 1.67%   |
| Chi Mei Optoelectronics | 46        | 1.3%    |
| ASUSTek Computer        | 37        | 1.05%   |
| Sony                    | 34        | 0.96%   |
| ___                     | 29        | 0.82%   |
| Panasonic               | 26        | 0.74%   |
| LG Electronics          | 26        | 0.74%   |
| Kogan                   | 24        | 0.68%   |
| PANDA                   | 20        | 0.57%   |
| GKK                     | 17        | 0.48%   |
| Toshiba                 | 16        | 0.45%   |
| MSI                     | 14        | 0.4%    |
| Hitachi                 | 13        | 0.37%   |
| Gigabyte Technology     | 12        | 0.34%   |
| Unknown (XXX)           | 11        | 0.31%   |
| SAC                     | 11        | 0.31%   |
| MiTAC                   | 9         | 0.26%   |
| InfoVision              | 9         | 0.26%   |
| TCL                     | 8         | 0.23%   |
| Eizo                    | 8         | 0.23%   |
| CVT                     | 8         | 0.23%   |
| MStar                   | 7         | 0.2%    |
| eMachines               | 7         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 21        | 0.56%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 19        | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 18        | 0.48%   |
| ___ LCDTV16 ___9000 1360x768                                         | 12        | 0.32%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch            | 12        | 0.32%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 12        | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 11        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 11        | 0.3%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                  | 10        | 0.27%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 10        | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                    | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 10        | 0.27%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                   | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 9         | 0.24%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 8         | 0.21%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 8         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 8         | 0.21%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 8         | 0.21%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                     | 8         | 0.21%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 8         | 0.21%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                | 7         | 0.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 7         | 0.19%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch         | 7         | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 7         | 0.19%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                  | 7         | 0.19%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                    | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch     | 7         | 0.19%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.19%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 7         | 0.19%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 7         | 0.19%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch     | 7         | 0.19%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 6         | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1426      | 42.34%  |
| 1366x768 (WXGA)    | 488       | 14.49%  |
| 3840x2160 (4K)     | 296       | 8.79%   |
| 2560x1440 (QHD)    | 190       | 5.64%   |
| 1680x1050 (WSXGA+) | 121       | 3.59%   |
| 1280x1024 (SXGA)   | 108       | 3.21%   |
| 1440x900 (WXGA+)   | 98        | 2.91%   |
| 1920x1200 (WUXGA)  | 93        | 2.76%   |
| 1600x900 (HD+)     | 74        | 2.2%    |
| 1280x800 (WXGA)    | 62        | 1.84%   |
| Unknown            | 57        | 1.69%   |
| 3440x1440          | 53        | 1.57%   |
| 2560x1600          | 29        | 0.86%   |
| 3840x1080          | 26        | 0.77%   |
| 2560x1080          | 22        | 0.65%   |
| 1360x768           | 22        | 0.65%   |
| 2880x1800          | 20        | 0.59%   |
| 3840x2400          | 15        | 0.45%   |
| 2736x1824          | 10        | 0.3%    |
| 1920x540           | 10        | 0.3%    |
| 3200x1800 (QHD+)   | 9         | 0.27%   |
| 1280x768           | 9         | 0.27%   |
| 1920x1280          | 8         | 0.24%   |
| 2160x1440          | 7         | 0.21%   |
| 1280x720 (HD)      | 7         | 0.21%   |
| 3840x1600          | 6         | 0.18%   |
| 2256x1504          | 6         | 0.18%   |
| 1024x768 (XGA)     | 6         | 0.18%   |
| 1024x600           | 6         | 0.18%   |
| 800x1280           | 5         | 0.15%   |
| 5760x2160          | 4         | 0.12%   |
| 5120x1440          | 4         | 0.12%   |
| 4480x1440          | 4         | 0.12%   |
| 3600x1080          | 4         | 0.12%   |
| 3072x1920          | 4         | 0.12%   |
| 2288x1287          | 4         | 0.12%   |
| 2240x1400          | 4         | 0.12%   |
| 1600x1200          | 4         | 0.12%   |
| 3200x1080          | 3         | 0.09%   |
| 2496x1664          | 3         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 656       | 18.67%  |
| 27      | 357       | 10.16%  |
| 24      | 294       | 8.37%   |
| 13      | 294       | 8.37%   |
| 23      | 257       | 7.31%   |
| Unknown | 223       | 6.35%   |
| 21      | 194       | 5.52%   |
| 14      | 193       | 5.49%   |
| 17      | 138       | 3.93%   |
| 19      | 129       | 3.67%   |
| 31      | 112       | 3.19%   |
| 22      | 88        | 2.5%    |
| 34      | 65        | 1.85%   |
| 12      | 63        | 1.79%   |
| 72      | 51        | 1.45%   |
| 11      | 51        | 1.45%   |
| 20      | 49        | 1.39%   |
| 18      | 36        | 1.02%   |
| 84      | 27        | 0.77%   |
| 54      | 20        | 0.57%   |
| 32      | 20        | 0.57%   |
| 26      | 20        | 0.57%   |
| 52      | 16        | 0.46%   |
| 16      | 15        | 0.43%   |
| 48      | 14        | 0.4%    |
| 42      | 13        | 0.37%   |
| 40      | 13        | 0.37%   |
| 37      | 11        | 0.31%   |
| 10      | 10        | 0.28%   |
| 35      | 9         | 0.26%   |
| 25      | 9         | 0.26%   |
| 29      | 8         | 0.23%   |
| 55      | 6         | 0.17%   |
| 46      | 6         | 0.17%   |
| 36      | 5         | 0.14%   |
| 7       | 5         | 0.14%   |
| 63      | 4         | 0.11%   |
| 142     | 3         | 0.09%   |
| 65      | 3         | 0.09%   |
| 49      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 968       | 28.2%   |
| 501-600        | 816       | 23.77%  |
| 401-500        | 406       | 11.83%  |
| 201-300        | 316       | 9.2%    |
| Unknown        | 223       | 6.5%    |
| 351-400        | 214       | 6.23%   |
| 601-700        | 180       | 5.24%   |
| 701-800        | 88        | 2.56%   |
| 1501-2000      | 82        | 2.39%   |
| 1001-1500      | 79        | 2.3%    |
| 801-900        | 36        | 1.05%   |
| 901-1000       | 15        | 0.44%   |
| 1-100          | 5         | 0.15%   |
| More than 2000 | 3         | 0.09%   |
| 101-200        | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2235      | 71.47%  |
| 16/10   | 425       | 13.59%  |
| Unknown | 187       | 5.98%   |
| 5/4     | 94        | 3.01%   |
| 21/9    | 79        | 2.53%   |
| 3/2     | 46        | 1.47%   |
| 4/3     | 27        | 0.86%   |
| 32/9    | 14        | 0.45%   |
| 6/5     | 10        | 0.32%   |
| 0.67    | 5         | 0.16%   |
| 1.00    | 3         | 0.1%    |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 678       | 19.57%  |
| 101-110        | 650       | 18.76%  |
| 301-350        | 370       | 10.68%  |
| 81-90          | 340       | 9.82%   |
| 151-200        | 225       | 6.5%    |
| Unknown        | 223       | 6.44%   |
| 351-500        | 211       | 6.09%   |
| 71-80          | 149       | 4.3%    |
| More than 1000 | 141       | 4.07%   |
| 251-300        | 101       | 2.92%   |
| 121-130        | 95        | 2.74%   |
| 501-1000       | 66        | 1.91%   |
| 51-60          | 54        | 1.56%   |
| 61-70          | 52        | 1.5%    |
| 141-150        | 47        | 1.36%   |
| 111-120        | 20        | 0.58%   |
| 131-140        | 16        | 0.46%   |
| 91-100         | 10        | 0.29%   |
| 41-50          | 9         | 0.26%   |
| 1-40           | 7         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1206      | 36.16%  |
| 101-120       | 784       | 23.51%  |
| 121-160       | 674       | 20.21%  |
| Unknown       | 223       | 6.69%   |
| 161-240       | 219       | 6.57%   |
| More than 240 | 115       | 3.45%   |
| 1-50          | 114       | 3.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2472      | 75.67%  |
| 2     | 554       | 16.96%  |
| 0     | 163       | 4.99%   |
| 3     | 68        | 2.08%   |
| 4     | 9         | 0.28%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1638      | 33.91%  |
| Realtek Semiconductor           | 1588      | 32.88%  |
| Qualcomm Atheros                | 500       | 10.35%  |
| Broadcom                        | 323       | 6.69%   |
| Broadcom Limited                | 73        | 1.51%   |
| Ralink                          | 59        | 1.22%   |
| Marvell Technology Group        | 59        | 1.22%   |
| Ralink Technology               | 47        | 0.97%   |
| TP-Link                         | 44        | 0.91%   |
| MediaTek                        | 37        | 0.77%   |
| Samsung Electronics             | 35        | 0.72%   |
| DisplayLink                     | 25        | 0.52%   |
| Sierra Wireless                 | 24        | 0.5%    |
| NetGear                         | 24        | 0.5%    |
| Huawei Technologies             | 20        | 0.41%   |
| Nvidia                          | 19        | 0.39%   |
| D-Link                          | 19        | 0.39%   |
| Aquantia                        | 19        | 0.39%   |
| Edimax Technology               | 17        | 0.35%   |
| D-Link System                   | 17        | 0.35%   |
| Microsoft                       | 16        | 0.33%   |
| Dell                            | 16        | 0.33%   |
| ASIX Electronics                | 16        | 0.33%   |
| ZTE WCDMA Technologies MSM      | 13        | 0.27%   |
| Lenovo                          | 12        | 0.25%   |
| ASUSTek Computer                | 12        | 0.25%   |
| Apple                           | 12        | 0.25%   |
| Motorola PCS                    | 10        | 0.21%   |
| Hewlett-Packard                 | 10        | 0.21%   |
| OPPO Electronics                | 9         | 0.19%   |
| Google                          | 8         | 0.17%   |
| VIA Technologies                | 7         | 0.14%   |
| Qualcomm Atheros Communications | 7         | 0.14%   |
| ICS Advent                      | 6         | 0.12%   |
| Standard Microsystems           | 5         | 0.1%    |
| Qualcomm                        | 5         | 0.1%    |
| Mellanox Technologies           | 5         | 0.1%    |
| Arduino SA                      | 5         | 0.1%    |
| Xiaomi                          | 4         | 0.08%   |
| Microchip Technology            | 4         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1070      | 18.86%  |
| Intel Wi-Fi 6 AX200                                               | 160       | 2.82%   |
| Intel I211 Gigabit Network Connection                             | 128       | 2.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 127       | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 127       | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 87        | 1.53%   |
| Intel Wireless 8265 / 8275                                        | 85        | 1.5%    |
| Intel Wireless 8260                                               | 75        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 66        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 61        | 1.08%   |
| Intel Wireless 7260                                               | 60        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.02%   |
| Intel Wireless 7265                                               | 58        | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 54        | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 51        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 51        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 48        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 48        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 47        | 0.83%   |
| Intel Wireless 3165                                               | 47        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 45        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 42        | 0.74%   |
| Intel Wireless-AC 9260                                            | 41        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 40        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 39        | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 38        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 37        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 37        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 37        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 32        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 31        | 0.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 30        | 0.53%   |
| Realtek 802.11ac NIC                                              | 29        | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1146      | 46.01%  |
| Qualcomm Atheros                | 372       | 14.93%  |
| Realtek Semiconductor           | 355       | 14.25%  |
| Broadcom                        | 217       | 8.71%   |
| Ralink                          | 59        | 2.37%   |
| Broadcom Limited                | 52        | 2.09%   |
| Ralink Technology               | 47        | 1.89%   |
| TP-Link                         | 42        | 1.69%   |
| MediaTek                        | 33        | 1.32%   |
| Sierra Wireless                 | 24        | 0.96%   |
| NetGear                         | 23        | 0.92%   |
| Marvell Technology Group        | 20        | 0.8%    |
| Edimax Technology               | 17        | 0.68%   |
| D-Link System                   | 12        | 0.48%   |
| ASUSTek Computer                | 12        | 0.48%   |
| Microsoft                       | 11        | 0.44%   |
| D-Link                          | 11        | 0.44%   |
| Dell                            | 9         | 0.36%   |
| Qualcomm Atheros Communications | 7         | 0.28%   |
| Belkin Components               | 4         | 0.16%   |
| BUFFALO                         | 3         | 0.12%   |
| Wacom                           | 2         | 0.08%   |
| Qualcomm                        | 2         | 0.08%   |
| Linksys                         | 2         | 0.08%   |
| Hewlett-Packard                 | 2         | 0.08%   |
| AVM                             | 2         | 0.08%   |
| Xiaomi                          | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Toshiba                         | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 160       | 6.39%   |
| Intel Wireless 8265 / 8275                                     | 85        | 3.39%   |
| Intel Wireless 8260                                            | 75        | 3%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 66        | 2.64%   |
| Intel Wireless 7260                                            | 60        | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 2.32%   |
| Intel Wireless 7265                                            | 58        | 2.32%   |
| Intel Wi-Fi 6 AX201                                            | 54        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 51        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 51        | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 48        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 47        | 1.88%   |
| Intel Wireless 3165                                            | 47        | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 45        | 1.8%    |
| Intel Wireless-AC 9260                                         | 41        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 40        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 39        | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 39        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 38        | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 37        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 37        | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 37        | 1.48%   |
| Intel Centrino Ultimate-N 6300                                 | 32        | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 30        | 1.2%    |
| Realtek 802.11ac NIC                                           | 29        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 27        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 25        | 1%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 25        | 1%      |
| Intel Wireless 3160                                            | 25        | 1%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 23        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 22        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 21        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 20        | 0.8%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 19        | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 19        | 0.76%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 19        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 17        | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 16        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1411      | 47.16%  |
| Intel                            | 928       | 31.02%  |
| Qualcomm Atheros                 | 181       | 6.05%   |
| Broadcom                         | 163       | 5.45%   |
| Marvell Technology Group         | 39        | 1.3%    |
| Samsung Electronics              | 26        | 0.87%   |
| DisplayLink                      | 25        | 0.84%   |
| Broadcom Limited                 | 21        | 0.7%    |
| Nvidia                           | 19        | 0.64%   |
| Aquantia                         | 19        | 0.64%   |
| ASIX Electronics                 | 16        | 0.53%   |
| Huawei Technologies              | 15        | 0.5%    |
| Lenovo                           | 12        | 0.4%    |
| Apple                            | 12        | 0.4%    |
| OPPO Electronics                 | 9         | 0.3%    |
| ZTE WCDMA Technologies MSM       | 8         | 0.27%   |
| Google                           | 8         | 0.27%   |
| D-Link                           | 8         | 0.27%   |
| VIA Technologies                 | 7         | 0.23%   |
| Motorola PCS                     | 6         | 0.2%    |
| ICS Advent                       | 6         | 0.2%    |
| Standard Microsystems            | 5         | 0.17%   |
| D-Link System                    | 5         | 0.17%   |
| Microsoft                        | 4         | 0.13%   |
| Microchip Technology             | 4         | 0.13%   |
| JMicron Technology               | 4         | 0.13%   |
| Xiaomi                           | 3         | 0.1%    |
| MediaTek                         | 3         | 0.1%    |
| IBM                              | 3         | 0.1%    |
| Hewlett-Packard                  | 3         | 0.1%    |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| Qualcomm                         | 2         | 0.07%   |
| QLogic                           | 2         | 0.07%   |
| NetGear                          | 2         | 0.07%   |
| Mellanox Technologies            | 2         | 0.07%   |
| Dell                             | 2         | 0.07%   |
| vivo                             | 1         | 0.03%   |
| TP-Link                          | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1070      | 34.64%  |
| Intel I211 Gigabit Network Connection                             | 128       | 4.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 127       | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 127       | 4.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 87        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 61        | 1.97%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 48        | 1.55%   |
| Intel Ethernet Connection (7) I219-V                              | 42        | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 1.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 1.07%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 31        | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 29        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.91%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27        | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 26        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 21        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.58%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 18        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 13        | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.39%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.36%   |
| Intel 82578DM Gigabit Network Connection                          | 11        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2711      | 53.04%  |
| WiFi     | 2323      | 45.45%  |
| Modem    | 63        | 1.23%   |
| Unknown  | 14        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1745      | 53.74%  |
| Ethernet | 1501      | 46.23%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1646      | 52.06%  |
| 1     | 1285      | 40.64%  |
| 3     | 120       | 3.8%    |
| 0     | 75        | 2.37%   |
| 4     | 22        | 0.7%    |
| 5     | 9         | 0.28%   |
| 6     | 4         | 0.13%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2783      | 87.27%  |
| Yes  | 406       | 12.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 934       | 50.32%  |
| Apple                           | 129       | 6.95%   |
| Broadcom                        | 126       | 6.79%   |
| Realtek Semiconductor           | 119       | 6.41%   |
| Cambridge Silicon Radio         | 115       | 6.2%    |
| Qualcomm Atheros Communications | 114       | 6.14%   |
| Lite-On Technology              | 49        | 2.64%   |
| IMC Networks                    | 48        | 2.59%   |
| Foxconn / Hon Hai               | 41        | 2.21%   |
| Toshiba                         | 39        | 2.1%    |
| ASUSTek Computer                | 26        | 1.4%    |
| Marvell Semiconductor           | 18        | 0.97%   |
| Hewlett-Packard                 | 18        | 0.97%   |
| Dell                            | 17        | 0.92%   |
| Ralink                          | 16        | 0.86%   |
| MediaTek                        | 10        | 0.54%   |
| TP-Link                         | 6         | 0.32%   |
| Alps Electric                   | 6         | 0.32%   |
| Realtek                         | 5         | 0.27%   |
| Edimax Technology               | 5         | 0.27%   |
| Ralink Technology               | 4         | 0.22%   |
| USI                             | 3         | 0.16%   |
| Integrated System Solution      | 2         | 0.11%   |
| Belkin Components               | 2         | 0.11%   |
| Opticis                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 330       | 17.75%  |
| Intel AX201 Bluetooth                               | 163       | 8.77%   |
| Intel AX200 Bluetooth                               | 154       | 8.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 115       | 6.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 102       | 5.49%   |
| Realtek Bluetooth Radio                             | 67        | 3.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 49        | 2.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 48        | 2.58%   |
| Apple Bluetooth Host Controller                     | 48        | 2.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 45        | 2.42%   |
| Apple Bluetooth USB Host Controller                 | 45        | 2.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 1.99%   |
| Intel Bluetooth Device                              | 34        | 1.83%   |
| Intel AX210 Bluetooth                               | 33        | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 1.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 1.08%   |
| IMC Networks Bluetooth Radio                        | 20        | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 1.02%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.86%   |
| Marvell Bluetooth and Wireless LAN Composite        | 15        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.75%   |
| Toshiba Bluetooth Device                            | 13        | 0.7%    |
| Lite-On Bluetooth Device                            | 13        | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.7%    |
| Apple Bluetooth HCI                                 | 13        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.54%   |
| MediaTek Wireless_Device                            | 10        | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.54%   |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.48%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 7         | 0.38%   |
| IMC Networks Bluetooth Device                       | 7         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2269      | 49.08%  |
| AMD                                  | 940       | 20.33%  |
| Nvidia                               | 857       | 18.54%  |
| C-Media Electronics                  | 62        | 1.34%   |
| Logitech                             | 54        | 1.17%   |
| Creative Labs                        | 30        | 0.65%   |
| Realtek Semiconductor                | 26        | 0.56%   |
| Texas Instruments                    | 20        | 0.43%   |
| Kingston Technology                  | 20        | 0.43%   |
| GN Netcom                            | 18        | 0.39%   |
| Razer USA                            | 17        | 0.37%   |
| Creative Technology                  | 16        | 0.35%   |
| Plantronics                          | 15        | 0.32%   |
| Generalplus Technology               | 15        | 0.32%   |
| Apple                                | 14        | 0.3%    |
| RODE Microphones                     | 12        | 0.26%   |
| Corsair                              | 11        | 0.24%   |
| Micro Star International             | 9         | 0.19%   |
| Lenovo                               | 9         | 0.19%   |
| SteelSeries ApS                      | 8         | 0.17%   |
| JMTek                                | 8         | 0.17%   |
| Blue Microphones                     | 8         | 0.17%   |
| Astro Gaming                         | 8         | 0.17%   |
| VIA Technologies                     | 7         | 0.15%   |
| Hewlett-Packard                      | 7         | 0.15%   |
| Dell                                 | 7         | 0.15%   |
| M-Audio                              | 6         | 0.13%   |
| Cambridge Silicon Radio              | 6         | 0.13%   |
| Audio-Technica                       | 6         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.11%   |
| Sennheiser Communications            | 5         | 0.11%   |
| OPPO Electronics                     | 5         | 0.11%   |
| Microsoft                            | 5         | 0.11%   |
| Giga-Byte Technology                 | 5         | 0.11%   |
| Focusrite-Novation                   | 5         | 0.11%   |
| ASUSTek Computer                     | 5         | 0.11%   |
| Sony                                 | 4         | 0.09%   |
| Samson Technologies                  | 4         | 0.09%   |
| PreSonus Audio Electronics           | 4         | 0.09%   |
| Native Instruments                   | 4         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 242       | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 229       | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 215       | 3.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 193       | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 182       | 3.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 173       | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 132       | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 129       | 2.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 123       | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 104       | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 92        | 1.71%   |
| AMD FCH Azalia Controller                                                  | 90        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 89        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 84        | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 80        | 1.49%   |
| Intel 8 Series HD Audio Controller                                         | 79        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 78        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 1.36%   |
| Intel 200 Series PCH HD Audio                                              | 73        | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 66        | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 64        | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 58        | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 57        | 1.06%   |
| Intel Broadwell-U Audio Controller                                         | 57        | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 56        | 1.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 56        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 55        | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                              | 52        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 50        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 50        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 49        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 49        | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 49        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 46        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 44        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 44        | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 43        | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 42        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 41        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 41        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 359       | 20.68%  |
| SK hynix                                | 298       | 17.17%  |
| Kingston                                | 196       | 11.29%  |
| Micron Technology                       | 176       | 10.14%  |
| Corsair                                 | 160       | 9.22%   |
| Unknown                                 | 137       | 7.89%   |
| Crucial                                 | 110       | 6.34%   |
| G.Skill                                 | 95        | 5.47%   |
| Team                                    | 31        | 1.79%   |
| Elpida                                  | 25        | 1.44%   |
| Nanya Technology                        | 24        | 1.38%   |
| Ramaxel Technology                      | 15        | 0.86%   |
| Patriot                                 | 15        | 0.86%   |
| A-DATA Technology                       | 15        | 0.86%   |
| Apacer                                  | 12        | 0.69%   |
| Transcend                               | 10        | 0.58%   |
| Unknown                                 | 8         | 0.46%   |
| Unknown (ABCD)                          | 6         | 0.35%   |
| Strontium                               | 4         | 0.23%   |
| Silicon Power                           | 4         | 0.23%   |
| Neo Forza                               | 4         | 0.23%   |
| GeIL                                    | 4         | 0.23%   |
| Toshiba                                 | 2         | 0.12%   |
| Smart                                   | 2         | 0.12%   |
| pqi                                     | 2         | 0.12%   |
| Hewlett-Packard                         | 2         | 0.12%   |
| Avant                                   | 2         | 0.12%   |
| ASint Technology                        | 2         | 0.12%   |
| Unknown (0x89AD)                        | 1         | 0.06%   |
| Unknown (0x873E)                        | 1         | 0.06%   |
| Unknown (0x0562)                        | 1         | 0.06%   |
| Undefi                                  | 1         | 0.06%   |
| Silicon Power Computer & Communications | 1         | 0.06%   |
| Qimonda                                 | 1         | 0.06%   |
| Princeton                               | 1         | 0.06%   |
| PNY                                     | 1         | 0.06%   |
| Netlist                                 | 1         | 0.06%   |
| Innodisk                                | 1         | 0.06%   |
| GSkill                                  | 1         | 0.06%   |
| Goldenmars                              | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 18        | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s      | 15        | 0.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s         | 14        | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 13        | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 12        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 12        | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 11        | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 11        | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 10        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 10        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 10        | 0.53%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 10        | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 9         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 9         | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 8         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 8         | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 8         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 8         | 0.43%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.43%   |
| Unknown                                                       | 8         | 0.43%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 7         | 0.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 7         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.37%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 7         | 0.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s       | 6         | 0.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 6         | 0.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 6         | 0.32%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s      | 6         | 0.32%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 5         | 0.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 5         | 0.27%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                          | 5         | 0.27%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s            | 5         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 717       | 46.95%  |
| DDR3    | 509       | 33.33%  |
| LPDDR3  | 71        | 4.65%   |
| Unknown | 67        | 4.39%   |
| DDR2    | 56        | 3.67%   |
| LPDDR4  | 47        | 3.08%   |
| SDRAM   | 19        | 1.24%   |
| DDR5    | 17        | 1.11%   |
| LPDDR5  | 11        | 0.72%   |
| DDR     | 11        | 0.72%   |
| DRAM    | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 744       | 48.95%  |
| DIMM         | 638       | 41.97%  |
| Row Of Chips | 124       | 8.16%   |
| Chip         | 10        | 0.66%   |
| FB-DIMM      | 2         | 0.13%   |
| Unknown      | 2         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 640       | 39.56%  |
| 4096  | 414       | 25.59%  |
| 16384 | 267       | 16.5%   |
| 2048  | 186       | 11.5%   |
| 32768 | 66        | 4.08%   |
| 1024  | 33        | 2.04%   |
| 512   | 8         | 0.49%   |
| 65536 | 2         | 0.12%   |
| 1536  | 1         | 0.06%   |
| 256   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 341       | 20.53%  |
| 2667    | 232       | 13.97%  |
| 3200    | 194       | 11.68%  |
| 1333    | 126       | 7.59%   |
| 2133    | 106       | 6.38%   |
| 2400    | 102       | 6.14%   |
| 3600    | 61        | 3.67%   |
| 1334    | 48        | 2.89%   |
| 800     | 44        | 2.65%   |
| 1867    | 41        | 2.47%   |
| 667     | 36        | 2.17%   |
| 4267    | 25        | 1.51%   |
| 3400    | 23        | 1.38%   |
| 3000    | 22        | 1.32%   |
| 1067    | 22        | 1.32%   |
| 4800    | 20        | 1.2%    |
| Unknown | 19        | 1.14%   |
| 3533    | 14        | 0.84%   |
| 1866    | 14        | 0.84%   |
| 1066    | 14        | 0.84%   |
| 6400    | 11        | 0.66%   |
| 3266    | 11        | 0.66%   |
| 3733    | 10        | 0.6%    |
| 2933    | 10        | 0.6%    |
| 2800    | 8         | 0.48%   |
| 8400    | 7         | 0.42%   |
| 3866    | 7         | 0.42%   |
| 2666    | 7         | 0.42%   |
| 3800    | 6         | 0.36%   |
| 4000    | 5         | 0.3%    |
| 3100    | 5         | 0.3%    |
| 2048    | 5         | 0.3%    |
| 1800    | 5         | 0.3%    |
| 400     | 5         | 0.3%    |
| 5200    | 4         | 0.24%   |
| 4266    | 4         | 0.24%   |
| 3500    | 4         | 0.24%   |
| 533     | 4         | 0.24%   |
| 4199    | 3         | 0.18%   |
| 4133    | 3         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 35        | 28%     |
| Hewlett-Packard        | 30        | 24%     |
| Canon                  | 21        | 16.8%   |
| Fuji Xerox             | 8         | 6.4%    |
| Seiko Epson            | 7         | 5.6%    |
| Samsung Electronics    | 6         | 4.8%    |
| Prolific Technology    | 6         | 4.8%    |
| Dymo-CoStar            | 3         | 2.4%    |
| Lexmark International  | 2         | 1.6%    |
| Kyocera                | 2         | 1.6%    |
| Zebra                  | 1         | 0.8%    |
| Xerox                  | 1         | 0.8%    |
| Ricoh                  | 1         | 0.8%    |
| Custom Engineering SPA | 1         | 0.8%    |
| BIXOLON                | 1         | 0.8%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer           | 8         | 6.25%   |
| Prolific PL2305 Parallel Port                | 6         | 4.69%   |
| Brother HL-2130 series                       | 5         | 3.91%   |
| HP DeskJet 2130 series                       | 4         | 3.13%   |
| Brother HL-1110 series                       | 4         | 3.13%   |
| HP ENVY 5000 series                          | 3         | 2.34%   |
| HP DeskJet F2100 Printer series              | 3         | 2.34%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.34%   |
| Canon TS3100 series                          | 3         | 2.34%   |
| Brother HL-1210W series                      | 3         | 2.34%   |
| HP OfficeJet 5200 series                     | 2         | 1.56%   |
| HP DeskJet 3630 series                       | 2         | 1.56%   |
| Fuji Xerox DocuPrint P205 b                  | 2         | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2         | 1.56%   |
| Canon TR8500 series                          | 2         | 1.56%   |
| Canon PIXMA MX920 Series                     | 2         | 1.56%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.56%   |
| Canon MG5600 series                          | 2         | 1.56%   |
| Brother QL-570 Label Printer                 | 2         | 1.56%   |
| Brother MFC-L8690CDW series                  | 2         | 1.56%   |
| Brother MFC-1810                             | 2         | 1.56%   |
| Brother HL-L3230CDW series                   | 2         | 1.56%   |
| Brother HL-L2305 series                      | 2         | 1.56%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.78%   |
| Xerox Phaser 8400N                           | 1         | 0.78%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.78%   |
| Seiko Epson XP-240 Series                    | 1         | 0.78%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.78%   |
| Seiko Epson WF-4830 Series                   | 1         | 0.78%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 0.78%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.78%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.78%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.78%   |
| Samsung ML-1865                              | 1         | 0.78%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.78%   |
| Samsung ML-1450                              | 1         | 0.78%   |
| Samsung M267x 287x Series                    | 1         | 0.78%   |
| Samsung M2020 Series                         | 1         | 0.78%   |
| Ricoh Printer                                | 1         | 0.78%   |
| Lexmark International E260dn                 | 1         | 0.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Canon            | 10        | 58.82%  |
| Seiko Epson      | 4         | 23.53%  |
| Syscan           | 1         | 5.88%   |
| Salix Technology | 1         | 5.88%   |
| Mustek Systems   | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                 | 2         | 11.76%  |
| Syscan TravelScan 460/464                               | 1         | 5.88%   |
| Seiko Epson Scanner                                     | 1         | 5.88%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.88%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 5.88%   |
| Salix USB Scanner.                                      | 1         | 5.88%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.88%   |
| Canon CanoScan LiDE 220                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 200                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.88%   |
| Canon CanoScan 1220U                                    | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 374       | 21.61%  |
| Logitech                               | 170       | 9.82%   |
| Microdia                               | 140       | 8.09%   |
| Realtek Semiconductor                  | 130       | 7.51%   |
| Apple                                  | 123       | 7.11%   |
| IMC Networks                           | 114       | 6.59%   |
| Sunplus Innovation Technology          | 108       | 6.24%   |
| Quanta                                 | 64        | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 58        | 3.35%   |
| Bison Electronics                      | 57        | 3.29%   |
| Suyin                                  | 54        | 3.12%   |
| Microsoft                              | 49        | 2.83%   |
| Acer                                   | 36        | 2.08%   |
| Lite-On Technology                     | 28        | 1.62%   |
| Syntek                                 | 25        | 1.44%   |
| Samsung Electronics                    | 24        | 1.39%   |
| Luxvisions Innotech Limited            | 17        | 0.98%   |
| Importek                               | 12        | 0.69%   |
| Silicon Motion                         | 11        | 0.64%   |
| Alcor Micro                            | 10        | 0.58%   |
| Ricoh                                  | 9         | 0.52%   |
| Razer USA                              | 9         | 0.52%   |
| Lenovo                                 | 9         | 0.52%   |
| Primax Electronics                     | 7         | 0.4%    |
| GEMBIRD                                | 7         | 0.4%    |
| Generalplus Technology                 | 6         | 0.35%   |
| OPPO Electronics                       | 5         | 0.29%   |
| OmniVision Technologies                | 5         | 0.29%   |
| LG Electronics                         | 5         | 0.29%   |
| Z-Star Microelectronics                | 4         | 0.23%   |
| Magic Control Technology               | 4         | 0.23%   |
| Genesys Logic                          | 4         | 0.23%   |
| DigiTech                               | 4         | 0.23%   |
| Cubeternet                             | 4         | 0.23%   |
| ALi                                    | 4         | 0.23%   |
| USB Camera                             | 3         | 0.17%   |
| Sonix Technology                       | 3         | 0.17%   |
| SunplusIT                              | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |
| Asuscom Network                        | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 68        | 3.86%   |
| Chicony Integrated Camera                               | 64        | 3.63%   |
| Apple FaceTime HD Camera (Built-in)                     | 42        | 2.38%   |
| Realtek Integrated_Webcam_HD                            | 38        | 2.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 32        | 1.82%   |
| Chicony HD Webcam                                       | 30        | 1.7%    |
| IMC Networks Integrated Camera                          | 29        | 1.64%   |
| Apple Built-in iSight                                   | 29        | 1.64%   |
| Sunplus Integrated_Webcam_HD                            | 28        | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 28        | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                         | 27        | 1.53%   |
| Logitech Webcam C270                                    | 25        | 1.42%   |
| Samsung Galaxy A5 (MTP)                                 | 24        | 1.36%   |
| Bison Integrated Camera                                 | 24        | 1.36%   |
| Logitech HD Pro Webcam C920                             | 22        | 1.25%   |
| Chicony HP TrueVision HD Camera                         | 18        | 1.02%   |
| Syntek Integrated Camera                                | 17        | 0.96%   |
| Logitech C922 Pro Stream Webcam                         | 16        | 0.91%   |
| Chicony HP HD Camera                                    | 15        | 0.85%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.79%   |
| Chicony HP Truevision HD                                | 14        | 0.79%   |
| Chicony HD User Facing                                  | 14        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.79%   |
| Sunplus HD WebCam                                       | 13        | 0.74%   |
| Quanta HD User Facing                                   | 13        | 0.74%   |
| Apple FaceTime HD Camera                                | 13        | 0.74%   |
| Realtek USB Camera                                      | 12        | 0.68%   |
| Microsoft LifeCam HD-3000                               | 12        | 0.68%   |
| Logitech Webcam C930e                                   | 12        | 0.68%   |
| Lite-On Integrated Camera                               | 11        | 0.62%   |
| Chicony USB2.0 Camera                                   | 11        | 0.62%   |
| Suyin HP Truevision HD                                  | 10        | 0.57%   |
| Microdia Integrated Webcam                              | 10        | 0.57%   |
| Logitech Webcam C170                                    | 10        | 0.57%   |
| Logitech StreamCam                                      | 10        | 0.57%   |
| Logitech HD Webcam C615                                 | 10        | 0.57%   |
| Chicony EasyCamera                                      | 10        | 0.57%   |
| Chicony CNF9055 Toshiba Webcam                          | 10        | 0.57%   |
| Realtek Integrated Webcam HD                            | 9         | 0.51%   |
| Quanta HP TrueVision HD Camera                          | 9         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 134       | 41.61%  |
| Synaptics                  | 77        | 23.91%  |
| Shenzhen Goodix Technology | 39        | 12.11%  |
| LighTuning Technology      | 21        | 6.52%   |
| Elan Microelectronics      | 15        | 4.66%   |
| AuthenTec                  | 15        | 4.66%   |
| Upek                       | 14        | 4.35%   |
| STMicroelectronics         | 6         | 1.86%   |
| Focal-systems.Corp         | 1         | 0.31%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 6.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 5.28%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.73%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 3.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 3.73%   |
| Validity Sensors VFS491                                                    | 10        | 3.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.11%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 3.11%   |
| Synaptics  WBDI                                                            | 10        | 3.11%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 3.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 2.8%    |
| Synaptics WBDI                                                             | 9         | 2.8%    |
| Synaptics UWP WBDI                                                         | 8         | 2.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.48%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.17%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.86%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.86%   |
| Synaptics WBDI Device                                                      | 5         | 1.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.24%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.24%   |
| AuthenTec AES1600                                                          | 4         | 1.24%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.93%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.93%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.93%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.62%   |
| AuthenTec AES2810                                                          | 2         | 0.62%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.31%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 34        | 59.65%  |
| Alcor Micro           | 13        | 22.81%  |
| Upek                  | 4         | 7.02%   |
| Lenovo                | 3         | 5.26%   |
| O2 Micro              | 2         | 3.51%   |
| Advanced Card Systems | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 28.07%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 22.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.53%  |
| Broadcom 5880                                                                | 6         | 10.53%  |
| Broadcom 58200                                                               | 6         | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.02%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.51%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2269      | 69.82%  |
| 1     | 804       | 24.74%  |
| 2     | 136       | 4.18%   |
| 3     | 29        | 0.89%   |
| 4     | 10        | 0.31%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 320       | 28.12%  |
| Graphics card            | 253       | 22.23%  |
| Net/wireless             | 172       | 15.11%  |
| Multimedia controller    | 76        | 6.68%   |
| Chipcard                 | 52        | 4.57%   |
| Communication controller | 51        | 4.48%   |
| Camera                   | 36        | 3.16%   |
| Bluetooth                | 35        | 3.08%   |
| Unassigned class         | 33        | 2.9%    |
| Net/ethernet             | 24        | 2.11%   |
| Sound                    | 20        | 1.76%   |
| Storage                  | 14        | 1.23%   |
| Modem                    | 11        | 0.97%   |
| Network                  | 9         | 0.79%   |
| Card reader              | 9         | 0.79%   |
| Dvb card                 | 8         | 0.7%    |
| Video                    | 3         | 0.26%   |
| Storage/raid             | 3         | 0.26%   |
| Storage/ata              | 2         | 0.18%   |
| Firewire controller      | 2         | 0.18%   |
| Unclassified device      | 1         | 0.09%   |
| Tv card                  | 1         | 0.09%   |
| Storage/nvme             | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Flash memory             | 1         | 0.09%   |

