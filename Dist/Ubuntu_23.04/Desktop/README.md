Ubuntu 23.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 558

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| NZXT          | N7 B550                     | [53a99b69e6](https://linux-hardware.org/?probe=53a99b69e6) | Sep 30, 2023 |
| Foxconn       | 2ADA                        | [da117a4e6a](https://linux-hardware.org/?probe=da117a4e6a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | [68f162bf42](https://linux-hardware.org/?probe=68f162bf42) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Apple         | Mac-F221BEC8                | [7b4a0099a9](https://linux-hardware.org/?probe=7b4a0099a9) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Foxconn       | 2ADA                        | [0c29af254c](https://linux-hardware.org/?probe=0c29af254c) | Sep 29, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [26580dc672](https://linux-hardware.org/?probe=26580dc672) | Sep 29, 2023 |
| MSI           | A520M-A PRO                 | [27d7959e57](https://linux-hardware.org/?probe=27d7959e57) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| HP            | 8594                        | [374067df48](https://linux-hardware.org/?probe=374067df48) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| Intel         | X79F1 V2.0                  | [919b208284](https://linux-hardware.org/?probe=919b208284) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [fc79d63b87](https://linux-hardware.org/?probe=fc79d63b87) | Sep 26, 2023 |
| ASUSTek       | M51AC                       | [b4bd7fad24](https://linux-hardware.org/?probe=b4bd7fad24) | Sep 25, 2023 |
| HP            | 3047h                       | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Foxconn       | 2ADA                        | [8a1af94640](https://linux-hardware.org/?probe=8a1af94640) | Sep 24, 2023 |
| MSI           | B450M MORTAR MAX            | [da277c4d5a](https://linux-hardware.org/?probe=da277c4d5a) | Sep 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| Pegatron      | 2AB6                        | [9b814d0254](https://linux-hardware.org/?probe=9b814d0254) | Sep 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | [41ac03cc3a](https://linux-hardware.org/?probe=41ac03cc3a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [898219c64a](https://linux-hardware.org/?probe=898219c64a) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a0c1d15f9](https://linux-hardware.org/?probe=2a0c1d15f9) | Sep 23, 2023 |
| ASUSTek       | F1A75-V PRO                 | [ce054bb837](https://linux-hardware.org/?probe=ce054bb837) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | [a204305d1e](https://linux-hardware.org/?probe=a204305d1e) | Sep 22, 2023 |
| AZW           | GTR V21                     | [c3da1f2fd5](https://linux-hardware.org/?probe=c3da1f2fd5) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | [d43d654621](https://linux-hardware.org/?probe=d43d654621) | Sep 22, 2023 |
| Gigabyte      | P55-UD4                     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f65b051dc9](https://linux-hardware.org/?probe=f65b051dc9) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| Huanan        | X99-F8 V2.0                 | [f832424d90](https://linux-hardware.org/?probe=f832424d90) | Sep 19, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [35cbc95f9e](https://linux-hardware.org/?probe=35cbc95f9e) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [bb285c7da5](https://linux-hardware.org/?probe=bb285c7da5) | Sep 18, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [bc9d2f6691](https://linux-hardware.org/?probe=bc9d2f6691) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| ASRock        | Z77 Pro4                    | [13f3de6336](https://linux-hardware.org/?probe=13f3de6336) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [88a398f990](https://linux-hardware.org/?probe=88a398f990) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0c7cb04f38](https://linux-hardware.org/?probe=0c7cb04f38) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [c47a157971](https://linux-hardware.org/?probe=c47a157971) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [27d7589428](https://linux-hardware.org/?probe=27d7589428) | Sep 15, 2023 |
| Dell          | 0XJ8C4 A00                  | [35d0557ca0](https://linux-hardware.org/?probe=35d0557ca0) | Sep 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [14874e9d32](https://linux-hardware.org/?probe=14874e9d32) | Sep 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [3c09b49188](https://linux-hardware.org/?probe=3c09b49188) | Sep 14, 2023 |
| Dell          | 0XJ8C4 A00                  | [4f9a4f7031](https://linux-hardware.org/?probe=4f9a4f7031) | Sep 14, 2023 |
| ASRock        | H97 Anniversary             | [37014ea895](https://linux-hardware.org/?probe=37014ea895) | Sep 13, 2023 |
| Intel         | X99H                        | [e38e67a30c](https://linux-hardware.org/?probe=e38e67a30c) | Sep 13, 2023 |
| Biostar       | TB360-BTC Expert            | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| ASUSTek       | Z170-P                      | [4070a28418](https://linux-hardware.org/?probe=4070a28418) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | [3abcd33b9c](https://linux-hardware.org/?probe=3abcd33b9c) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Dell          | 0HY9JP A00                  | [3b642be7da](https://linux-hardware.org/?probe=3b642be7da) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| ASRock        | H81 Pro BTC                 | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| ONDA          | H61V Ver:4.01               | [7423e0ce99](https://linux-hardware.org/?probe=7423e0ce99) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [625b62078a](https://linux-hardware.org/?probe=625b62078a) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [440c9854ff](https://linux-hardware.org/?probe=440c9854ff) | Sep 09, 2023 |
| Biostar       | TB360-BTC Expert            | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| HP            | 82B4                        | [e702194024](https://linux-hardware.org/?probe=e702194024) | Sep 08, 2023 |
| HP            | 82B4                        | [5c85d3bf3c](https://linux-hardware.org/?probe=5c85d3bf3c) | Sep 08, 2023 |
| Intel         | H61                         | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| ASUSTek       | M51AC                       | [2cd8d3959a](https://linux-hardware.org/?probe=2cd8d3959a) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| HP            | 844C                        | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7fa390fcc4](https://linux-hardware.org/?probe=7fa390fcc4) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | FM2A68M-HD+                 | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| ASUSTek       | A88XM-E                     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| ASRock        | Z790 PG SONIC               | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| ASUSTek       | M2N68-AM SE2                | [78cb25f581](https://linux-hardware.org/?probe=78cb25f581) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [8c1eeceddd](https://linux-hardware.org/?probe=8c1eeceddd) | Aug 31, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| HP            | 843C                        | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Dell          | 0T7D40 A00                  | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| Biostar       | B450MH                      | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| ASUSTek       | X99-DELUXE II               | [d59b79adfe](https://linux-hardware.org/?probe=d59b79adfe) | Aug 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| ASRock        | Q1900M                      | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| Acer          | Veriton M2611G v1.0         | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| Dell          | 0X8582                      | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
| Gigabyte      | H81M-D2V                    | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASRock        | FM2A68M-DG3+                | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| AK3V          | 1.0                         | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| Unknown       | Unknown                     | [e52e8ee5df](https://linux-hardware.org/?probe=e52e8ee5df) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M LE                 | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [7fb2d45505](https://linux-hardware.org/?probe=7fb2d45505) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Dell          | 0HD5W2 A01                  | [be4514c366](https://linux-hardware.org/?probe=be4514c366) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [f278787ab5](https://linux-hardware.org/?probe=f278787ab5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [76078461ae](https://linux-hardware.org/?probe=76078461ae) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [ab3503021a](https://linux-hardware.org/?probe=ab3503021a) | Aug 10, 2023 |
| MSI           | Z590-A PRO                  | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| MSI           | 2AE0                        | [9d3b59de32](https://linux-hardware.org/?probe=9d3b59de32) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [9c9e999e7f](https://linux-hardware.org/?probe=9c9e999e7f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [54f0bde318](https://linux-hardware.org/?probe=54f0bde318) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| GMKtec        | NucBox K4                   | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| MSI           | A320M-A PRO MAX             | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66000207b0](https://linux-hardware.org/?probe=66000207b0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [45405639f5](https://linux-hardware.org/?probe=45405639f5) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Gigabyte      | Z490 UD                     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [87bb7b0b79](https://linux-hardware.org/?probe=87bb7b0b79) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| HP            | 3646h                       | [fbc7ac7c08](https://linux-hardware.org/?probe=fbc7ac7c08) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2fe1d4509a](https://linux-hardware.org/?probe=2fe1d4509a) | Jul 26, 2023 |
| ASRock        | B560M Pro4                  | [d96478ff29](https://linux-hardware.org/?probe=d96478ff29) | Jul 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | [32707549f9](https://linux-hardware.org/?probe=32707549f9) | Jul 25, 2023 |
| Unknown       | 1.2                         | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| Intel         | Unknown                     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e35d64a41b](https://linux-hardware.org/?probe=e35d64a41b) | Jul 21, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a07f95cdcc](https://linux-hardware.org/?probe=a07f95cdcc) | Jul 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | A520M DS3H                  | [3bd7501f03](https://linux-hardware.org/?probe=3bd7501f03) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [f99a99e95e](https://linux-hardware.org/?probe=f99a99e95e) | Jul 19, 2023 |
| Unknown       | G41 Series                  | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60280e0708](https://linux-hardware.org/?probe=60280e0708) | Jul 17, 2023 |
| MSI           | FM2-A85XA-G65               | [8e6741f497](https://linux-hardware.org/?probe=8e6741f497) | Jul 17, 2023 |
| ASRock        | FM2A68M-HD+                 | [5abf5fb1c3](https://linux-hardware.org/?probe=5abf5fb1c3) | Jul 16, 2023 |
| Gigabyte      | H61M-DS2                    | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| MSI           | G41M4                       | [b7bda60261](https://linux-hardware.org/?probe=b7bda60261) | Jul 16, 2023 |
| MSI           | G41M4                       | [a3e5e23a49](https://linux-hardware.org/?probe=a3e5e23a49) | Jul 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [79af0f54f4](https://linux-hardware.org/?probe=79af0f54f4) | Jul 15, 2023 |
| ASUSTek       | PRIME B650M-A II            | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | FM2-A85XA-G65               | [00b4b2f7b0](https://linux-hardware.org/?probe=00b4b2f7b0) | Jul 13, 2023 |
| MSI           | Z87-G43                     | [86d9a28ae8](https://linux-hardware.org/?probe=86d9a28ae8) | Jul 13, 2023 |
| HP            | 83EE                        | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| ASRock        | X79 Extreme9                | [bfd488feb9](https://linux-hardware.org/?probe=bfd488feb9) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| Gigabyte      | MZAPLBP-00                  | [8f57c74864](https://linux-hardware.org/?probe=8f57c74864) | Jul 09, 2023 |
| Dell          | 0GXM1W A00                  | [b320d70c27](https://linux-hardware.org/?probe=b320d70c27) | Jul 09, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [d7f7dc2ef3](https://linux-hardware.org/?probe=d7f7dc2ef3) | Jul 08, 2023 |
| Lenovo        | IdeaCentre K330A            | [8d98ff8f86](https://linux-hardware.org/?probe=8d98ff8f86) | Jul 08, 2023 |
| Dell          | 0GXM1W A00                  | [91cab30323](https://linux-hardware.org/?probe=91cab30323) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | [89a1894d2a](https://linux-hardware.org/?probe=89a1894d2a) | Jul 08, 2023 |
| MSI           | Z97S SLI Krait Edition      | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e3f6aabfb](https://linux-hardware.org/?probe=7e3f6aabfb) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| MSI           | 760GM-E51                   | [757eefb29d](https://linux-hardware.org/?probe=757eefb29d) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [12e2330b5a](https://linux-hardware.org/?probe=12e2330b5a) | Jul 05, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| ASUSTek       | PRIME A520M-K               | [9b1631574e](https://linux-hardware.org/?probe=9b1631574e) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| ASRock        | P67 Performance             | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Biostar       | A10N-8800E                  | [261bb38239](https://linux-hardware.org/?probe=261bb38239) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| ASUSTek       | H170-PRO                    | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Dell          | 0KJCC5 A00                  | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| HP            | 805D                        | [d55246de23](https://linux-hardware.org/?probe=d55246de23) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| System76      | Desktop leox5               | [210eb3f1e8](https://linux-hardware.org/?probe=210eb3f1e8) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [45575cf0cc](https://linux-hardware.org/?probe=45575cf0cc) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [77d2d05995](https://linux-hardware.org/?probe=77d2d05995) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| MSI           | H270-A PRO                  | [169bbe5f04](https://linux-hardware.org/?probe=169bbe5f04) | Jun 23, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| Gigabyte      | H77-D3H                     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Dell          | 0YXG0N A00                  | [546af4a5d6](https://linux-hardware.org/?probe=546af4a5d6) | Jun 22, 2023 |
| HP            | 339A                        | [420903b9cc](https://linux-hardware.org/?probe=420903b9cc) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| HP            | 84FD                        | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| HP            | 1496                        | [ccc9943e2d](https://linux-hardware.org/?probe=ccc9943e2d) | Jun 16, 2023 |
| Unknown       | G41 Series                  | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| ASUSTek       | Rev                         | [6c5d91db68](https://linux-hardware.org/?probe=6c5d91db68) | Jun 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7df89b77f2](https://linux-hardware.org/?probe=7df89b77f2) | Jun 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5cbee4094a](https://linux-hardware.org/?probe=5cbee4094a) | Jun 14, 2023 |
| ASUSTek       | M5A97 PRO                   | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | B360M D2V                   | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| AAEON         | UP-CHCR1 V0.4               | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| Dell          | 0RY007                      | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Dell          | 03KWTV A02                  | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Unknown       | DT138IB                     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| MSI           | MS-B9311                    | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| HP            | 3397                        | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| Intel         | DG43GT AAE62768-303         | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Acer          | Aspire TC-1760              | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Dell          | 0RY007                      | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Dell          | 0RY007                      | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| HP            | 1905                        | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Dell          | 0JP3NX A01                  | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| BESSTAR Te... | UM700                       | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| HP            | 18E5                        | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Gigabyte      | GA-880GM-USB3               | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Gigabyte      | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.0-20-generic        | 181      | 41.23%  |
| 6.2.0-27-generic        | 37       | 8.43%   |
| 6.2.0-26-generic        | 32       | 7.29%   |
| 6.2.0-24-generic        | 31       | 7.06%   |
| 6.2.0-25-generic        | 30       | 6.83%   |
| 6.2.0-32-generic        | 27       | 6.15%   |
| 6.2.0-23-generic        | 27       | 6.15%   |
| 6.2.0-33-generic        | 24       | 5.47%   |
| 6.2.0-31-generic        | 16       | 3.64%   |
| 5.19.0-21-generic       | 5        | 1.14%   |
| 6.3.6-060306-generic    | 2        | 0.46%   |
| 6.3.4-060304-generic    | 2        | 0.46%   |
| 6.3.2-060302-generic    | 2        | 0.46%   |
| 6.2.0-18-generic        | 2        | 0.46%   |
| 6.5.4-060504-generic    | 1        | 0.23%   |
| 6.5.2-tkg-bore-llvm     | 1        | 0.23%   |
| 6.5.0-060500rc5-generic | 1        | 0.23%   |
| 6.5.0-060500-generic    | 1        | 0.23%   |
| 6.4.6-060406-generic    | 1        | 0.23%   |
| 6.4.0-060400-generic    | 1        | 0.23%   |
| 6.2.16-060216-generic   | 1        | 0.23%   |
| 6.2.11-060211-generic   | 1        | 0.23%   |
| 6.2.0-19-generic        | 1        | 0.23%   |
| 6.2.0-1010-lowlatency   | 1        | 0.23%   |
| 6.2.0-1009-lowlatency   | 1        | 0.23%   |
| 6.2.0-1007-lowlatency   | 1        | 0.23%   |
| 6.2.0-1007-gcp          | 1        | 0.23%   |
| 6.2.0-1003-oracle       | 1        | 0.23%   |
| 6.2.0-1003-lowlatency   | 1        | 0.23%   |
| 6.2.0-060200-generic    | 1        | 0.23%   |
| 6.1.0-16-generic        | 1        | 0.23%   |
| 5.19.0-45-generic       | 1        | 0.23%   |
| 5.19.0-42-generic       | 1        | 0.23%   |
| 5.19.0-38-generic       | 1        | 0.23%   |
| 5.19.0-28-generic       | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 389      | 94.42%  |
| 5.19.0  | 9        | 2.18%   |
| 6.3.6   | 2        | 0.49%   |
| 6.3.4   | 2        | 0.49%   |
| 6.3.2   | 2        | 0.49%   |
| 6.5.4   | 1        | 0.24%   |
| 6.5.2   | 1        | 0.24%   |
| 6.5.0   | 1        | 0.24%   |
| 6.4.6   | 1        | 0.24%   |
| 6.4.0   | 1        | 0.24%   |
| 6.2.16  | 1        | 0.24%   |
| 6.2.11  | 1        | 0.24%   |
| 6.1.0   | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 390      | 94.89%  |
| 5.19    | 9        | 2.19%   |
| 6.3     | 6        | 1.46%   |
| 6.5     | 3        | 0.73%   |
| 6.4     | 2        | 0.49%   |
| 6.1     | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 411      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 395      | 96.11%  |
| X-Cinnamon      | 7        | 1.7%    |
| Unknown         | 7        | 1.7%    |
| GNOME Flashback | 2        | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 243      | 58.27%  |
| X11     | 159      | 38.13%  |
| Tty     | 9        | 2.16%   |
| Unknown | 6        | 1.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 359      | 86.92%  |
| Unknown | 41       | 9.93%   |
| LightDM | 10       | 2.42%   |
| GDM     | 3        | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_US            | 187      | 45.28%  |
| de_DE            | 58       | 14.04%  |
| fr_FR            | 24       | 5.81%   |
| C                | 20       | 4.84%   |
| pt_BR            | 19       | 4.6%    |
| en_GB            | 13       | 3.15%   |
| es_ES            | 10       | 2.42%   |
| en_CA            | 9        | 2.18%   |
| ru_RU            | 8        | 1.94%   |
| it_IT            | 7        | 1.69%   |
| pl_PL            | 5        | 1.21%   |
| nl_NL            | 4        | 0.97%   |
| fi_FI            | 4        | 0.97%   |
| en_AU            | 4        | 0.97%   |
| de_AT            | 4        | 0.97%   |
| zh_CN            | 3        | 0.73%   |
| pt_PT            | 3        | 0.73%   |
| cs_CZ            | 3        | 0.73%   |
| zh_TW            | 2        | 0.48%   |
| sv_SE            | 2        | 0.48%   |
| en_NZ            | 2        | 0.48%   |
| en_IL            | 2        | 0.48%   |
| el_GR            | 2        | 0.48%   |
| bg_BG            | 2        | 0.48%   |
| Unknown          | 2        | 0.48%   |
| tr_TR            | 1        | 0.24%   |
| sk_SK            | 1        | 0.24%   |
| nl_BE            | 1        | 0.24%   |
| nb_NO            | 1        | 0.24%   |
| lt_LT            | 1        | 0.24%   |
| ko_KR            | 1        | 0.24%   |
| hu_HU            | 1        | 0.24%   |
| fr_CH            | 1        | 0.24%   |
| fr_CA            | 1        | 0.24%   |
| es_CL            | 1        | 0.24%   |
| es_AR            | 1        | 0.24%   |
| en_US.ISO-8859-1 | 1        | 0.24%   |
| en_SG            | 1        | 0.24%   |
| de_CH            | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 298      | 71.98%  |
| EFI  | 116      | 28.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Tmpfs   | 250      | 60.24%  |
| Ext4    | 150      | 36.14%  |
| Overlay | 5        | 1.2%    |
| Btrfs   | 5        | 1.2%    |
| Zfs     | 4        | 0.96%   |
| Xfs     | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 345      | 83.33%  |
| MBR     | 35       | 8.45%   |
| Unknown | 34       | 8.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 78.23%  |
| Yes       | 91       | 21.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 250      | 60.1%   |
| Yes       | 166      | 39.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 123      | 29.93%  |
| MSI                                  | 53       | 12.9%   |
| Gigabyte Technology                  | 53       | 12.9%   |
| ASRock                               | 33       | 8.03%   |
| Dell                                 | 32       | 7.79%   |
| Hewlett-Packard                      | 25       | 6.08%   |
| Lenovo                               | 18       | 4.38%   |
| Intel                                | 16       | 3.89%   |
| Fujitsu                              | 8        | 1.95%   |
| Unknown                              | 8        | 1.95%   |
| Biostar                              | 4        | 0.97%   |
| Apple                                | 4        | 0.97%   |
| Acer                                 | 3        | 0.73%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.49%   |
| Pegatron                             | 2        | 0.49%   |
| MACHINIST                            | 2        | 0.49%   |
| Huanan                               | 2        | 0.49%   |
| Foxconn                              | 2        | 0.49%   |
| AZW                                  | 2        | 0.49%   |
| ZOTAC                                | 1        | 0.24%   |
| System76                             | 1        | 0.24%   |
| Shuttle                              | 1        | 0.24%   |
| Packard Bell                         | 1        | 0.24%   |
| ONDA                                 | 1        | 0.24%   |
| NZXT                                 | 1        | 0.24%   |
| Login Informatica                    | 1        | 0.24%   |
| Itautec                              | 1        | 0.24%   |
| Google                               | 1        | 0.24%   |
| GMKtec                               | 1        | 0.24%   |
| GEEKOM                               | 1        | 0.24%   |
| Gateway                              | 1        | 0.24%   |
| Fujitsu Siemens                      | 1        | 0.24%   |
| Entroware                            | 1        | 0.24%   |
| ECS                                  | 1        | 0.24%   |
| Colorful Technology                  | 1        | 0.24%   |
| BESSTAR Tech                         | 1        | 0.24%   |
| AK3V                                 | 1        | 0.24%   |
| AAEON                                | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 10       | 2.43%   |
| ASUS All Series                    | 8        | 1.95%   |
| MSI MS-7C95                        | 3        | 0.73%   |
| Gigabyte B450M DS3H                | 3        | 0.73%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 3        | 0.73%   |
| Apple MacPro5,1                    | 3        | 0.73%   |
| MSI MS-7C96                        | 2        | 0.49%   |
| MSI MS-7C02                        | 2        | 0.49%   |
| MSI MS-7B86                        | 2        | 0.49%   |
| MSI MS-7721                        | 2        | 0.49%   |
| MSI MS-7596                        | 2        | 0.49%   |
| Intel H61                          | 2        | 0.49%   |
| HP ProLiant ML10 v2                | 2        | 0.49%   |
| HP EliteDesk 800 G2 DM 35W         | 2        | 0.49%   |
| Gigabyte X670 AORUS ELITE AX       | 2        | 0.49%   |
| Fujitsu ESPRIMO Q920               | 2        | 0.49%   |
| Dell Precision Tower 7810          | 2        | 0.49%   |
| Dell OptiPlex 790                  | 2        | 0.49%   |
| Dell OptiPlex 3050                 | 2        | 0.49%   |
| Dell OptiPlex 3040                 | 2        | 0.49%   |
| Dell OptiPlex 3010                 | 2        | 0.49%   |
| ASUS TUF Gaming Z590-PLUS WIFI     | 2        | 0.49%   |
| ASUS TUF Gaming X570-PLUS          | 2        | 0.49%   |
| ASUS TUF Gaming B650-PLUS WIFI     | 2        | 0.49%   |
| ASUS TUF Gaming B550M-PLUS         | 2        | 0.49%   |
| ASUS TUF Gaming B550-PLUS WIFI II  | 2        | 0.49%   |
| ASUS PRIME Z790-A WIFI             | 2        | 0.49%   |
| ASUS PRIME X670-P WIFI             | 2        | 0.49%   |
| ASUS PRIME X570-P                  | 2        | 0.49%   |
| ASUS PRIME B660M-A D4              | 2        | 0.49%   |
| ASUS PRIME B650M-A II              | 2        | 0.49%   |
| ASUS PRIME B550-PLUS               | 2        | 0.49%   |
| ASUS PRIME B450M-K II              | 2        | 0.49%   |
| ASUS PRIME B450-PLUS               | 2        | 0.49%   |
| ASUS PRIME A320M-K                 | 2        | 0.49%   |
| ASUS M5A97 R2.0                    | 2        | 0.49%   |
| ASUS M5A78L-M LE                   | 2        | 0.49%   |
| ASUS KomplettPC                    | 2        | 0.49%   |
| ASUS H170-PRO                      | 2        | 0.49%   |
| ASUS A88XM-E                       | 2        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 35       | 8.52%   |
| ASUS ROG            | 19       | 4.62%   |
| Dell OptiPlex       | 18       | 4.38%   |
| ASUS TUF            | 17       | 4.14%   |
| Lenovo ThinkCentre  | 10       | 2.43%   |
| Unknown             | 10       | 2.43%   |
| ASUS All            | 8        | 1.95%   |
| HP ProDesk          | 5        | 1.22%   |
| HP EliteDesk        | 5        | 1.22%   |
| HP Compaq           | 5        | 1.22%   |
| Fujitsu ESPRIMO     | 5        | 1.22%   |
| Lenovo IdeaCentre   | 4        | 0.97%   |
| Gigabyte X570       | 4        | 0.97%   |
| Dell Precision      | 4        | 0.97%   |
| Dell Inspiron       | 4        | 0.97%   |
| ASUS M5A78L-M       | 4        | 0.97%   |
| MSI MS-7C95         | 3        | 0.73%   |
| Gigabyte H61M-DS2   | 3        | 0.73%   |
| Gigabyte B450M      | 3        | 0.73%   |
| Dell XPS            | 3        | 0.73%   |
| ASUS P8Z77-V        | 3        | 0.73%   |
| ASUS P8H61-M        | 3        | 0.73%   |
| ASUS M5A97          | 3        | 0.73%   |
| ASRock A320M-HDV    | 3        | 0.73%   |
| Apple MacPro5       | 3        | 0.73%   |
| MSI MS-7C96         | 2        | 0.49%   |
| MSI MS-7C02         | 2        | 0.49%   |
| MSI MS-7B86         | 2        | 0.49%   |
| MSI MS-7721         | 2        | 0.49%   |
| MSI MS-7596         | 2        | 0.49%   |
| Lenovo ThinkStation | 2        | 0.49%   |
| Intel X99           | 2        | 0.49%   |
| Intel H61           | 2        | 0.49%   |
| Huanan X99-F8       | 2        | 0.49%   |
| HP ProLiant         | 2        | 0.49%   |
| Gigabyte Z690       | 2        | 0.49%   |
| Gigabyte X670       | 2        | 0.49%   |
| Gigabyte A520M      | 2        | 0.49%   |
| Gigabyte A320M-S2H  | 2        | 0.49%   |
| Dell Vostro         | 2        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 47       | 11.44%  |
| 2018 | 37       | 9%      |
| 2021 | 36       | 8.76%   |
| 2014 | 34       | 8.27%   |
| 2012 | 33       | 8.03%   |
| 2020 | 32       | 7.79%   |
| 2019 | 29       | 7.06%   |
| 2013 | 28       | 6.81%   |
| 2017 | 22       | 5.35%   |
| 2015 | 22       | 5.35%   |
| 2011 | 19       | 4.62%   |
| 2010 | 19       | 4.62%   |
| 2023 | 16       | 3.89%   |
| 2016 | 16       | 3.89%   |
| 2009 | 12       | 2.92%   |
| 2008 | 5        | 1.22%   |
| 2006 | 3        | 0.73%   |
| 2007 | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 411      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 398      | 96.6%   |
| Enabled  | 14       | 3.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 410      | 99.76%  |
| Yes  | 1        | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 104      | 25.18%  |
| 32.01-64.0      | 75       | 18.16%  |
| 4.01-8.0        | 71       | 17.19%  |
| 64.01-256.0     | 47       | 11.38%  |
| 8.01-16.0       | 46       | 11.14%  |
| 3.01-4.0        | 39       | 9.44%   |
| 24.01-32.0      | 22       | 5.33%   |
| 1.01-2.0        | 4        | 0.97%   |
| 2.01-3.0        | 3        | 0.73%   |
| More than 256.0 | 2        | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 129      | 30.35%  |
| 1.01-2.0   | 110      | 25.88%  |
| 4.01-8.0   | 93       | 21.88%  |
| 3.01-4.0   | 62       | 14.59%  |
| 8.01-16.0  | 22       | 5.18%   |
| 24.01-32.0 | 3        | 0.71%   |
| 0.51-1.0   | 3        | 0.71%   |
| 32.01-64.0 | 2        | 0.47%   |
| 16.01-24.0 | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 173      | 41.29%  |
| 2      | 100      | 23.87%  |
| 3      | 69       | 16.47%  |
| 4      | 38       | 9.07%   |
| 5      | 18       | 4.3%    |
| 6      | 13       | 3.1%    |
| 8      | 3        | 0.72%   |
| 7      | 3        | 0.72%   |
| 9      | 1        | 0.24%   |
| 0      | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 63.53%  |
| Yes       | 151      | 36.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 406      | 98.54%  |
| No        | 6        | 1.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 226      | 54.85%  |
| No        | 186      | 45.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 240      | 57.97%  |
| Yes       | 174      | 42.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 76       | 18.49%  |
| Germany     | 65       | 15.82%  |
| Canada      | 27       | 6.57%   |
| France      | 26       | 6.33%   |
| Brazil      | 24       | 5.84%   |
| UK          | 20       | 4.87%   |
| Italy       | 15       | 3.65%   |
| Russia      | 12       | 2.92%   |
| Australia   | 11       | 2.68%   |
| Netherlands | 9        | 2.19%   |
| Sweden      | 8        | 1.95%   |
| Spain       | 8        | 1.95%   |
| Switzerland | 7        | 1.7%    |
| Finland     | 7        | 1.7%    |
| Czechia     | 7        | 1.7%    |
| Portugal    | 6        | 1.46%   |
| Poland      | 6        | 1.46%   |
| India       | 6        | 1.46%   |
| Austria     | 6        | 1.46%   |
| Turkey      | 4        | 0.97%   |
| Philippines | 4        | 0.97%   |
| New Zealand | 4        | 0.97%   |
| Greece      | 4        | 0.97%   |
| Belgium     | 4        | 0.97%   |
| Norway      | 3        | 0.73%   |
| Israel      | 3        | 0.73%   |
| Iran        | 3        | 0.73%   |
| China       | 3        | 0.73%   |
| Taiwan      | 2        | 0.49%   |
| South Korea | 2        | 0.49%   |
| Serbia      | 2        | 0.49%   |
| Peru        | 2        | 0.49%   |
| Malaysia    | 2        | 0.49%   |
| Lithuania   | 2        | 0.49%   |
| Hungary     | 2        | 0.49%   |
| Hong Kong   | 2        | 0.49%   |
| Chile       | 2        | 0.49%   |
| Bulgaria    | 2        | 0.49%   |
| Argentina   | 2        | 0.49%   |
| Ukraine     | 1        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 7        | 1.67%   |
| Moscow         | 5        | 1.2%    |
| Helsinki       | 5        | 1.2%    |
| Prague         | 4        | 0.96%   |
| Hamburg        | 4        | 0.96%   |
| Brisbane       | 4        | 0.96%   |
| Winnipeg       | 3        | 0.72%   |
| Warsaw         | 3        | 0.72%   |
| Valencia       | 3        | 0.72%   |
| Tourcoing      | 3        | 0.72%   |
| Tehran         | 3        | 0.72%   |
| Sydney         | 3        | 0.72%   |
| Montreal       | 3        | 0.72%   |
| Melbourne      | 3        | 0.72%   |
| Hanover        | 3        | 0.72%   |
| Gothenburg     | 3        | 0.72%   |
| Edmonton       | 3        | 0.72%   |
| Berlin         | 3        | 0.72%   |
| Auckland       | 3        | 0.72%   |
| Vienna         | 2        | 0.48%   |
| Toronto        | 2        | 0.48%   |
| Surat          | 2        | 0.48%   |
| St Petersburg  | 2        | 0.48%   |
| Sorocaba       | 2        | 0.48%   |
| Seattle        | 2        | 0.48%   |
| Sacramento     | 2        | 0.48%   |
| Rome           | 2        | 0.48%   |
| Petah Tikva    | 2        | 0.48%   |
| Oshawa         | 2        | 0.48%   |
| Munich         | 2        | 0.48%   |
| Minneapolis    | 2        | 0.48%   |
| Marcon         | 2        | 0.48%   |
| Makati City    | 2        | 0.48%   |
| Krasnoyarsk    | 2        | 0.48%   |
| Kaohsiung City | 2        | 0.48%   |
| Heilbronn      | 2        | 0.48%   |
| Halle          | 2        | 0.48%   |
| Florence       | 2        | 0.48%   |
| Düsseldorf    | 2        | 0.48%   |
| Dresden        | 2        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 134      | 193    | 17.4%   |
| Seagate                     | 131      | 181    | 17.01%  |
| WDC                         | 117      | 168    | 15.19%  |
| SanDisk                     | 47       | 67     | 6.1%    |
| Kingston                    | 43       | 49     | 5.58%   |
| Crucial                     | 30       | 35     | 3.9%    |
| Toshiba                     | 28       | 35     | 3.64%   |
| Hitachi                     | 20       | 27     | 2.6%    |
| Intel                       | 15       | 16     | 1.95%   |
| Phison Electronics          | 12       | 14     | 1.56%   |
| Micron/Crucial Technology   | 12       | 15     | 1.56%   |
| SK hynix                    | 9        | 9      | 1.17%   |
| Kingston Technology Company | 9        | 13     | 1.17%   |
| HGST                        | 7        | 7      | 0.91%   |
| China                       | 7        | 9      | 0.91%   |
| Unknown                     | 6        | 7      | 0.78%   |
| Intenso                     | 6        | 8      | 0.78%   |
| A-DATA Technology           | 6        | 10     | 0.78%   |
| Patriot                     | 5        | 5      | 0.65%   |
| OCZ                         | 5        | 5      | 0.65%   |
| Micron Technology           | 5        | 7      | 0.65%   |
| MAXIO Technology (Hangzhou) | 5        | 5      | 0.65%   |
| Corsair                     | 5        | 6      | 0.65%   |
| SABRENT                     | 4        | 7      | 0.52%   |
| PNY                         | 4        | 6      | 0.52%   |
| Phison                      | 4        | 5      | 0.52%   |
| KIOXIA                      | 4        | 4      | 0.52%   |
| Apacer                      | 4        | 5      | 0.52%   |
| SPCC                        | 3        | 3      | 0.39%   |
| Silicon Motion              | 3        | 3      | 0.39%   |
| KingSpec                    | 3        | 4      | 0.39%   |
| Hewlett-Packard             | 3        | 3      | 0.39%   |
| Gigabyte Technology         | 3        | 3      | 0.39%   |
| ASMT                        | 3        | 5      | 0.39%   |
| Vaseky                      | 2        | 2      | 0.26%   |
| Team                        | 2        | 2      | 0.26%   |
| Seagate Technology          | 2        | 3      | 0.26%   |
| Realtek                     | 2        | 2      | 0.26%   |
| OWC                         | 2        | 6      | 0.26%   |
| Netac                       | 2        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 21       | 2.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 14       | 1.59%   |
| Seagate ST1000DM010-2EP102 1TB                      | 13       | 1.48%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 11       | 1.25%   |
| Samsung SSD 980 1TB                                 | 9        | 1.03%   |
| Samsung SSD 850 EVO 250GB                           | 9        | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB                      | 8        | 0.91%   |
| Samsung SSD 860 EVO 500GB                           | 8        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                     | 7        | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB                     | 6        | 0.68%   |
| Seagate ST3500418AS 500GB                           | 6        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 6        | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 5        | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                      | 5        | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB                      | 5        | 0.57%   |
| Seagate ST1000DM003-1SB102 1TB                      | 5        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB                      | 5        | 0.57%   |
| SanDisk SSD PLUS 1000GB                             | 5        | 0.57%   |
| Samsung SSD 990 PRO 1TB                             | 5        | 0.57%   |
| Samsung SSD 870 EVO 500GB                           | 5        | 0.57%   |
| Samsung SSD 870 EVO 1TB                             | 5        | 0.57%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.57%   |
| Phison E12 NVMe Controller 2TB                      | 5        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                    | 5        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 0.57%   |
| Toshiba DT01ACA100 1TB                              | 4        | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB                      | 4        | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4        | 0.46%   |
| Samsung SSD 860 QVO 1TB                             | 4        | 0.46%   |
| Samsung PSSD T7 1TB                                 | 4        | 0.46%   |
| SABRENT Disk 752GB                                  | 4        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                         | 4        | 0.46%   |
| Apacer AS350 512GB SSD                              | 4        | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 3        | 0.34%   |
| WDC WD5000AAKX-001CA0 500GB                         | 3        | 0.34%   |
| WDC WD20EZAZ-00L9GB0 2TB                            | 3        | 0.34%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.34%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 3        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 125      | 173    | 40.32%  |
| WDC                 | 106      | 149    | 34.19%  |
| Toshiba             | 23       | 28     | 7.42%   |
| Hitachi             | 20       | 27     | 6.45%   |
| Samsung Electronics | 16       | 19     | 5.16%   |
| HGST                | 7        | 7      | 2.26%   |
| SABRENT             | 4        | 7      | 1.29%   |
| Unknown             | 2        | 2      | 0.65%   |
| Maxtor              | 2        | 3      | 0.65%   |
| USB3.0              | 1        | 1      | 0.32%   |
| Intenso             | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| ASMT                | 1        | 3      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 63       | 86     | 24.71%  |
| Kingston            | 29       | 35     | 11.37%  |
| SanDisk             | 26       | 35     | 10.2%   |
| Crucial             | 24       | 26     | 9.41%   |
| WDC                 | 15       | 16     | 5.88%   |
| Intel               | 8        | 9      | 3.14%   |
| China               | 7        | 9      | 2.75%   |
| Patriot             | 5        | 5      | 1.96%   |
| OCZ                 | 5        | 5      | 1.96%   |
| A-DATA Technology   | 5        | 9      | 1.96%   |
| Intenso             | 4        | 6      | 1.57%   |
| Apacer              | 4        | 5      | 1.57%   |
| Toshiba             | 3        | 4      | 1.18%   |
| PNY                 | 3        | 4      | 1.18%   |
| KingSpec            | 3        | 4      | 1.18%   |
| Vaseky              | 2        | 2      | 0.78%   |
| Team                | 2        | 2      | 0.78%   |
| SPCC                | 2        | 2      | 0.78%   |
| OWC                 | 2        | 6      | 0.78%   |
| Micron Technology   | 2        | 3      | 0.78%   |
| INNOVATION IT       | 2        | 2      | 0.78%   |
| Hewlett-Packard     | 2        | 2      | 0.78%   |
| GOODRAM             | 2        | 3      | 0.78%   |
| Gigastone           | 2        | 2      | 0.78%   |
| Emtec               | 2        | 2      | 0.78%   |
| ASMT                | 2        | 2      | 0.78%   |
| WALRAM              | 1        | 1      | 0.39%   |
| Verbatim            | 1        | 6      | 0.39%   |
| V7                  | 1        | 1      | 0.39%   |
| TO Exter            | 1        | 1      | 0.39%   |
| TEXTORM             | 1        | 1      | 0.39%   |
| T-FORCE             | 1        | 1      | 0.39%   |
| Smartbuy            | 1        | 2      | 0.39%   |
| Seagate             | 1        | 1      | 0.39%   |
| Rogueware           | 1        | 1      | 0.39%   |
| Phison              | 1        | 1      | 0.39%   |
| NN                  | 1        | 1      | 0.39%   |
| Neo                 | 1        | 2      | 0.39%   |
| MSI                 | 1        | 1      | 0.39%   |
| MicroFrom           | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 250      | 422    | 38.4%   |
| SSD     | 213      | 323    | 32.72%  |
| NVMe    | 175      | 264    | 26.88%  |
| Unknown | 11       | 12     | 1.69%   |
| MMC     | 2        | 2      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 337      | 712    | 61.61%  |
| NVMe | 175      | 262    | 31.99%  |
| SAS  | 33       | 47     | 6.03%   |
| MMC  | 2        | 2      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 223      | 347    | 44.78%  |
| 0.51-1.0   | 155      | 236    | 31.12%  |
| 1.01-2.0   | 63       | 80     | 12.65%  |
| 3.01-4.0   | 23       | 34     | 4.62%   |
| 4.01-10.0  | 18       | 28     | 3.61%   |
| 2.01-3.0   | 13       | 16     | 2.61%   |
| 10.01-20.0 | 3        | 4      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 97       | 22.99%  |
| 101-250        | 88       | 20.85%  |
| 251-500        | 84       | 19.91%  |
| 1001-2000      | 53       | 12.56%  |
| More than 3000 | 42       | 9.95%   |
| 2001-3000      | 23       | 5.45%   |
| 1-20           | 15       | 3.55%   |
| 51-100         | 12       | 2.84%   |
| 21-50          | 6        | 1.42%   |
| Unknown        | 2        | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 116      | 27.36%  |
| 21-50          | 94       | 22.17%  |
| 101-250        | 56       | 13.21%  |
| 51-100         | 48       | 11.32%  |
| 251-500        | 37       | 8.73%   |
| 501-1000       | 28       | 6.6%    |
| More than 3000 | 19       | 4.48%   |
| 1001-2000      | 13       | 3.07%   |
| 2001-3000      | 11       | 2.59%   |
| Unknown        | 2        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD        | 2        | 2      | 5.26%   |
| WDC WD6400AACS-00G8B1 640GB             | 1        | 1      | 2.63%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1        | 1      | 2.63%   |
| WDC WD5000HHTZ-04N21V0 500GB            | 1        | 1      | 2.63%   |
| WDC WD5000AZLX-22JKKA0 500GB            | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-001CA0 500GB             | 1        | 1      | 2.63%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1        | 1      | 2.63%   |
| WDC WD2500AAKX-753CA1 250GB             | 1        | 1      | 2.63%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1        | 1      | 2.63%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 1      | 2.63%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1        | 2      | 2.63%   |
| WDC WD10EARS-22Y5B1 1TB                 | 1        | 1      | 2.63%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 2.63%   |
| Toshiba MK3261GSYN 320GB                | 1        | 1      | 2.63%   |
| Toshiba MK2555GSXF 250GB                | 1        | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1      | 2.63%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 2.63%   |
| Seagate ST2000LX001-1RG174 2TB          | 1        | 1      | 2.63%   |
| Seagate ST2000LM007-1R8174 2TB          | 1        | 1      | 2.63%   |
| Seagate ST2000DM008-2FR102 2TB          | 1        | 1      | 2.63%   |
| SanDisk SSD PLUS 240GB                  | 1        | 1      | 2.63%   |
| SanDisk SD7SB2Q-512G-1006 512GB SSD     | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 960 EVO 250GB   | 1        | 1      | 2.63%   |
| Samsung Electronics HD502HJ 500GB       | 1        | 1      | 2.63%   |
| Samsung Electronics HD161GJ 160GB       | 1        | 1      | 2.63%   |
| Patriot P210 1TB SSD                    | 1        | 1      | 2.63%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 1        | 2      | 2.63%   |
| Maxtor 6L160M0 160GB                    | 1        | 2      | 2.63%   |
| Kingston SUV400S37240G 240GB SSD        | 1        | 1      | 2.63%   |
| Intel SSDSC2KW240H6 240GB               | 1        | 1      | 2.63%   |
| Intel SSDSC2BF180A5L 180GB              | 1        | 1      | 2.63%   |
| Hitachi HDT721010SLA360 1TB             | 1        | 1      | 2.63%   |
| Hitachi HDS721010CLA332 1TB             | 1        | 1      | 2.63%   |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 2.63%   |
| Crucial CT512MX100SSD1 512GB            | 1        | 1      | 2.63%   |
| Crucial CT240M500SSD1 240GB             | 1        | 1      | 2.63%   |
| Crucial CT1050MX300SSD1 1TB             | 1        | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 31.58%  |
| Seagate             | 5        | 5      | 13.16%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Kingston            | 3        | 3      | 7.89%   |
| Crucial             | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| SanDisk             | 2        | 2      | 5.26%   |
| Intel               | 2        | 2      | 5.26%   |
| Hitachi             | 2        | 2      | 5.26%   |
| Patriot             | 1        | 1      | 2.63%   |
| Neo                 | 1        | 2      | 2.63%   |
| Maxtor              | 1        | 2      | 2.63%   |
| Gigabyte Technology | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 50%     |
| Seagate             | 5        | 5      | 20.83%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Hitachi             | 2        | 2      | 8.33%   |
| Maxtor              | 1        | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 26     | 62.16%  |
| SSD  | 12       | 13     | 32.43%  |
| NVMe | 2        | 2      | 5.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 299      | 724    | 66.15%  |
| Works    | 119      | 257    | 26.33%  |
| Malfunc  | 33       | 41     | 7.3%    |
| Failed   | 1        | 1      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 262      | 40.49%  |
| AMD                          | 142      | 21.95%  |
| Samsung Electronics          | 70       | 10.82%  |
| Sandisk                      | 24       | 3.71%   |
| Kingston Technology Company  | 23       | 3.55%   |
| Phison Electronics           | 21       | 3.25%   |
| Micron/Crucial Technology    | 20       | 3.09%   |
| ASMedia Technology           | 18       | 2.78%   |
| SK hynix                     | 8        | 1.24%   |
| Seagate Technology           | 7        | 1.08%   |
| Marvell Technology Group     | 7        | 1.08%   |
| MAXIO Technology (Hangzhou)  | 6        | 0.93%   |
| JMicron Technology           | 6        | 0.93%   |
| Toshiba America Info Systems | 4        | 0.62%   |
| Silicon Motion               | 4        | 0.62%   |
| KIOXIA                       | 4        | 0.62%   |
| Realtek Semiconductor        | 3        | 0.46%   |
| Micron Technology            | 3        | 0.46%   |
| Shenzhen Longsys Electronics | 2        | 0.31%   |
| Nvidia                       | 2        | 0.31%   |
| Netac Technology             | 2        | 0.31%   |
| Broadcom / LSI               | 2        | 0.31%   |
| Yangtze Memory Technologies  | 1        | 0.15%   |
| VIA Technologies             | 1        | 0.15%   |
| OCZ Technology Group         | 1        | 0.15%   |
| LSI Logic / Symbios Logic    | 1        | 0.15%   |
| INNOGRIT                     | 1        | 0.15%   |
| Apple                        | 1        | 0.15%   |
| ADATA Technology             | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 85       | 11.04%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 28       | 3.64%   |
| AMD 500 Series Chipset SATA Controller                                                  | 26       | 3.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23       | 2.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 22       | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 2.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 19       | 2.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 18       | 2.34%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 16       | 2.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 15       | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15       | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 14       | 1.82%   |
| Samsung NVMe SSD Controller 980                                                         | 13       | 1.69%   |
| Intel SATA Controller [RAID mode]                                                       | 13       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 1.56%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 1.17%   |
| Phison E12 NVMe Controller                                                              | 9        | 1.17%   |
| Kingston Company Company Non-Volatile memory controller                                 | 9        | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.17%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.17%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 8        | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.04%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 7        | 0.91%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.91%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                                        | 5        | 0.65%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 5        | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 0.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.65%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 4        | 0.52%   |
| Seagate FireCuda 530 SSD                                                                | 4        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 353      | 56.48%  |
| NVMe | 175      | 28%     |
| IDE  | 59       | 9.44%   |
| RAID | 36       | 5.76%   |
| SAS  | 2        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 265      | 64.48%  |
| AMD    | 146      | 35.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics     | 9        | 2.18%   |
| AMD Ryzen 5 3600 6-Core Processor          | 9        | 2.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 6        | 1.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 6        | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 6        | 1.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 5        | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 5        | 1.21%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 5        | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 5        | 1.21%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz       | 5        | 1.21%   |
| AMD Ryzen 9 7900X 12-Core Processor        | 5        | 1.21%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 5        | 1.21%   |
| AMD Ryzen 7 5700G with Radeon Graphics     | 5        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 5        | 1.21%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 4        | 0.97%   |
| Intel Core i5-6600 CPU @ 3.30GHz           | 4        | 0.97%   |
| Intel 13th Gen Core i9-13900K              | 4        | 0.97%   |
| Intel 12th Gen Core i7-12700               | 4        | 0.97%   |
| AMD Ryzen 9 7900 12-Core Processor         | 4        | 0.97%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 4        | 0.97%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 4        | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 4        | 0.97%   |
| Intel Core i7-3770K CPU @ 3.50GHz          | 3        | 0.73%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 3        | 0.73%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 3        | 0.73%   |
| Intel Core i5-2500 CPU @ 3.30GHz           | 3        | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 3        | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz           | 3        | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 3        | 0.73%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 3        | 0.73%   |
| Intel 12th Gen Core i5-12600K              | 3        | 0.73%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz    | 3        | 0.73%   |
| AMD Ryzen 9 7950X 16-Core Processor        | 3        | 0.73%   |
| AMD Ryzen 7 7800X3D 8-Core Processor       | 3        | 0.73%   |
| AMD Ryzen 7 7700X 8-Core Processor         | 3        | 0.73%   |
| AMD Ryzen 7 5700X 8-Core Processor         | 3        | 0.73%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 3        | 0.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 3        | 0.73%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics | 3        | 0.73%   |
| AMD Ryzen 5 5500                           | 3        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 83       | 20.15%  |
| Intel Core i7           | 50       | 12.14%  |
| Other                   | 41       | 9.95%   |
| AMD Ryzen 5             | 41       | 9.95%   |
| AMD Ryzen 7             | 30       | 7.28%   |
| Intel Core i3           | 28       | 6.8%    |
| AMD Ryzen 9             | 27       | 6.55%   |
| Intel Xeon              | 24       | 5.83%   |
| Intel Core 2 Duo        | 11       | 2.67%   |
| Intel Celeron           | 10       | 2.43%   |
| AMD FX                  | 7        | 1.7%    |
| AMD A8                  | 5        | 1.21%   |
| Intel Pentium Dual-Core | 4        | 0.97%   |
| Intel Pentium           | 4        | 0.97%   |
| Intel Core 2 Quad       | 4        | 0.97%   |
| AMD Ryzen 3             | 4        | 0.97%   |
| AMD Phenom II X4        | 4        | 0.97%   |
| AMD Athlon II X2        | 4        | 0.97%   |
| AMD A10                 | 4        | 0.97%   |
| Intel Atom              | 3        | 0.73%   |
| AMD Ryzen 5 PRO         | 3        | 0.73%   |
| Intel Core i9           | 2        | 0.49%   |
| AMD Ryzen Threadripper  | 2        | 0.49%   |
| AMD Athlon X4           | 2        | 0.49%   |
| Intel Pentium Silver    | 1        | 0.24%   |
| Intel Pentium 4         | 1        | 0.24%   |
| Intel Celeron D         | 1        | 0.24%   |
| AMD Ryzen 7 PRO         | 1        | 0.24%   |
| AMD Ryzen 3 PRO         | 1        | 0.24%   |
| AMD Phenom II X6        | 1        | 0.24%   |
| AMD Phenom II X2        | 1        | 0.24%   |
| AMD Phenom              | 1        | 0.24%   |
| AMD Athlon II X4        | 1        | 0.24%   |
| AMD Athlon II X3        | 1        | 0.24%   |
| AMD Athlon Dual Core    | 1        | 0.24%   |
| AMD Athlon 64 X2        | 1        | 0.24%   |
| AMD Athlon              | 1        | 0.24%   |
| AMD A6                  | 1        | 0.24%   |
| AMD A4                  | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 148      | 36.01%  |
| 6      | 77       | 18.73%  |
| 2      | 71       | 17.27%  |
| 8      | 44       | 10.71%  |
| 12     | 31       | 7.54%   |
| 16     | 10       | 2.43%   |
| 24     | 6        | 1.46%   |
| 14     | 5        | 1.22%   |
| 10     | 5        | 1.22%   |
| 3      | 5        | 1.22%   |
| 1      | 4        | 0.97%   |
| 20     | 2        | 0.49%   |
| 36     | 1        | 0.24%   |
| 32     | 1        | 0.24%   |
| 7      | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 404      | 98.3%   |
| 2      | 7        | 1.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 254      | 61.65%  |
| 1      | 158      | 38.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 411      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 350      | 84.75%  |
| 0x0a601203 | 17       | 4.12%   |
| 0x0a50000d | 8        | 1.94%   |
| 0x0a20120a | 4        | 0.97%   |
| 0x08701021 | 4        | 0.97%   |
| 0x0800820d | 3        | 0.73%   |
| 0x010000c8 | 3        | 0.73%   |
| 0x0a201025 | 2        | 0.48%   |
| 0x08701030 | 2        | 0.48%   |
| 0x08108109 | 2        | 0.48%   |
| 0xf64      | 1        | 0.24%   |
| 0x306c3    | 1        | 0.24%   |
| 0x0a704103 | 1        | 0.24%   |
| 0x0a50000c | 1        | 0.24%   |
| 0x0a50000b | 1        | 0.24%   |
| 0x0a404102 | 1        | 0.24%   |
| 0x0a201205 | 1        | 0.24%   |
| 0x0a201009 | 1        | 0.24%   |
| 0x08600109 | 1        | 0.24%   |
| 0x08101016 | 1        | 0.24%   |
| 0x0810100b | 1        | 0.24%   |
| 0x06006705 | 1        | 0.24%   |
| 0x06001119 | 1        | 0.24%   |
| 0x06000852 | 1        | 0.24%   |
| 0x0600063e | 1        | 0.24%   |
| 0x03000027 | 1        | 0.24%   |
| 0x010000dc | 1        | 0.24%   |
| 0x00000000 | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 58       | 14.04%  |
| Haswell          | 52       | 12.59%  |
| Zen 3            | 34       | 8.23%   |
| KabyLake         | 34       | 8.23%   |
| IvyBridge        | 31       | 7.51%   |
| Skylake          | 28       | 6.78%   |
| Zen 2            | 26       | 6.3%    |
| SandyBridge      | 21       | 5.08%   |
| Penryn           | 19       | 4.6%    |
| Piledriver       | 14       | 3.39%   |
| Zen+             | 13       | 3.15%   |
| K10              | 13       | 3.15%   |
| Zen              | 9        | 2.18%   |
| CometLake        | 8        | 1.94%   |
| Alderlake Hybrid | 8        | 1.94%   |
| Silvermont       | 6        | 1.45%   |
| Nehalem          | 6        | 1.45%   |
| Westmere         | 5        | 1.21%   |
| Broadwell        | 5        | 1.21%   |
| Icelake          | 3        | 0.73%   |
| Excavator        | 3        | 0.73%   |
| Core             | 3        | 0.73%   |
| NetBurst         | 2        | 0.48%   |
| K8 Hammer        | 2        | 0.48%   |
| Gracemont        | 2        | 0.48%   |
| Goldmont         | 2        | 0.48%   |
| Bulldozer        | 2        | 0.48%   |
| TigerLake        | 1        | 0.24%   |
| Steamroller      | 1        | 0.24%   |
| K10 Llano        | 1        | 0.24%   |
| Bonnell          | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 153      | 33.85%  |
| Nvidia                     | 152      | 33.63%  |
| Intel                      | 145      | 32.08%  |
| Matrox Electronics Systems | 2        | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 4.96%   |
| AMD Raphael                                                                 | 22       | 4.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19       | 4.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 3.88%   |
| Intel HD Graphics 530                                                       | 17       | 3.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14       | 3.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 2.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 2.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.72%   |
| Intel HD Graphics 630                                                       | 8        | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.29%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.29%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 1.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 1.29%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.08%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 5        | 1.08%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 5        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5        | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.86%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 0.86%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 4        | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.86%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.65%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x AMD             | 128      | 30.99%  |
| 1 x Nvidia          | 121      | 29.3%   |
| 1 x Intel           | 119      | 28.81%  |
| AMD + Nvidia        | 15       | 3.63%   |
| Intel + Nvidia      | 13       | 3.15%   |
| 2 x AMD             | 7        | 1.69%   |
| Intel + AMD         | 3        | 0.73%   |
| 1 x Matrox          | 2        | 0.48%   |
| Intel + 2 x Nvidia  | 2        | 0.48%   |
| 2 x Nvidia          | 1        | 0.24%   |
| 2 x Intel + 1 x AMD | 1        | 0.24%   |
| 2 x Intel           | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 300      | 72.29%  |
| Proprietary | 100      | 24.1%   |
| Unknown     | 15       | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 306      | 73.73%  |
| 0.01-0.5   | 22       | 5.3%    |
| 3.01-4.0   | 20       | 4.82%   |
| 1.01-2.0   | 20       | 4.82%   |
| 7.01-8.0   | 19       | 4.58%   |
| 0.51-1.0   | 12       | 2.89%   |
| 16.01-24.0 | 6        | 1.45%   |
| 8.01-16.0  | 6        | 1.45%   |
| 5.01-6.0   | 4        | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 70       | 16.24%  |
| Goldstar             | 51       | 11.83%  |
| Dell                 | 44       | 10.21%  |
| Acer                 | 31       | 7.19%   |
| Hewlett-Packard      | 25       | 5.8%    |
| Ancor Communications | 23       | 5.34%   |
| AOC                  | 22       | 5.1%    |
| Philips              | 20       | 4.64%   |
| Iiyama               | 19       | 4.41%   |
| BenQ                 | 14       | 3.25%   |
| ASUSTek Computer     | 11       | 2.55%   |
| ViewSonic            | 9        | 2.09%   |
| Lenovo               | 7        | 1.62%   |
| MSI                  | 5        | 1.16%   |
| Sony                 | 4        | 0.93%   |
| Fujitsu Siemens      | 4        | 0.93%   |
| Vestel Elektronik    | 3        | 0.7%    |
| NEC Computers        | 3        | 0.7%    |
| MiTAC                | 3        | 0.7%    |
| Medion               | 3        | 0.7%    |
| HKC                  | 3        | 0.7%    |
| Gigabyte Technology  | 3        | 0.7%    |
| Eizo                 | 3        | 0.7%    |
| Unknown              | 3        | 0.7%    |
| Wacom                | 2        | 0.46%   |
| Unknown (XXX)        | 2        | 0.46%   |
| Unknown              | 2        | 0.46%   |
| TCL                  | 2        | 0.46%   |
| SGT                  | 2        | 0.46%   |
| Sceptre Tech         | 2        | 0.46%   |
| Hitachi              | 2        | 0.46%   |
| Gericom              | 2        | 0.46%   |
| ___                  | 1        | 0.23%   |
| Xiaomi               | 1        | 0.23%   |
| Westinghouse         | 1        | 0.23%   |
| Vizio                | 1        | 0.23%   |
| VIE                  | 1        | 0.23%   |
| Unknown (AAA)        | 1        | 0.23%   |
| Toshiba              | 1        | 0.23%   |
| SANYO                | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5        | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.89%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4        | 0.89%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 3        | 0.67%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.67%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 3        | 0.67%   |
| Unknown                                                               | 3        | 0.67%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.45%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 2        | 0.45%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.45%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 480x270mm 21.7-inch | 2        | 0.45%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1190x340mm 48.7-inch   | 2        | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.45%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.45%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 2        | 0.45%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 2        | 0.45%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 2        | 0.45%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 2        | 0.45%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.45%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.45%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 2        | 0.45%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 2        | 0.45%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 2        | 0.45%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.45%   |
| ASUSTek Computer PB278QV AUS278A 2560x1440 597x336mm 27.0-inch        | 2        | 0.45%   |
| AOC AG273QS4R4 AOC2730 2560x1440 597x336mm 27.0-inch                  | 2        | 0.45%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 2        | 0.45%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 2        | 0.45%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 2        | 0.45%   |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 2        | 0.45%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 2        | 0.45%   |
| Acer G236HL ACR02D4 1920x1080 509x286mm 23.0-inch                     | 2        | 0.45%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 0.22%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 0.22%   |
| Westinghouse UW32S3PW WDT1B4E 1366x768 430x250mm 19.6-inch            | 1        | 0.22%   |
| Vizio E422VLE VIZ0092 1920x1080 930x520mm 41.9-inch                   | 1        | 0.22%   |
| ViewSonic XG350R-C VSC4F37 3440x1440 819x346mm 35.0-inch              | 1        | 0.22%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.22%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 202      | 48.91%  |
| 3840x2160 (4K)     | 57       | 13.8%   |
| 2560x1440 (QHD)    | 45       | 10.9%   |
| 1440x900 (WXGA+)   | 15       | 3.63%   |
| 1366x768 (WXGA)    | 15       | 3.63%   |
| 3440x1440          | 11       | 2.66%   |
| 1280x1024 (SXGA)   | 10       | 2.42%   |
| 2560x1080          | 8        | 1.94%   |
| 1680x1050 (WSXGA+) | 7        | 1.69%   |
| 3840x1080          | 6        | 1.45%   |
| 1920x1200 (WUXGA)  | 6        | 1.45%   |
| 1600x900 (HD+)     | 6        | 1.45%   |
| Unknown            | 5        | 1.21%   |
| 1280x720 (HD)      | 4        | 0.97%   |
| 3840x1600          | 3        | 0.73%   |
| 1920x540           | 3        | 0.73%   |
| 2560x1600          | 2        | 0.48%   |
| 1360x768           | 2        | 0.48%   |
| 5760x2160          | 1        | 0.24%   |
| 3600x1080          | 1        | 0.24%   |
| 1600x1200          | 1        | 0.24%   |
| 1280x960           | 1        | 0.24%   |
| 1024x768 (XGA)     | 1        | 0.24%   |
| 1024x600           | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 69       | 16.16%  |
| 24      | 63       | 14.75%  |
| 23      | 52       | 12.18%  |
| 21      | 46       | 10.77%  |
| 31      | 33       | 7.73%   |
| 19      | 20       | 4.68%   |
| Unknown | 17       | 3.98%   |
| 18      | 14       | 3.28%   |
| 34      | 13       | 3.04%   |
| 84      | 10       | 2.34%   |
| 17      | 9        | 2.11%   |
| 22      | 8        | 1.87%   |
| 20      | 7        | 1.64%   |
| 40      | 6        | 1.41%   |
| 65      | 5        | 1.17%   |
| 48      | 5        | 1.17%   |
| 35      | 5        | 1.17%   |
| 32      | 5        | 1.17%   |
| 26      | 4        | 0.94%   |
| 72      | 3        | 0.7%    |
| 52      | 3        | 0.7%    |
| 42      | 3        | 0.7%    |
| 28      | 3        | 0.7%    |
| 16      | 3        | 0.7%    |
| 13      | 3        | 0.7%    |
| 54      | 2        | 0.47%   |
| 46      | 2        | 0.47%   |
| 37      | 2        | 0.47%   |
| 63      | 1        | 0.23%   |
| 61      | 1        | 0.23%   |
| 60      | 1        | 0.23%   |
| 49      | 1        | 0.23%   |
| 43      | 1        | 0.23%   |
| 38      | 1        | 0.23%   |
| 33      | 1        | 0.23%   |
| 29      | 1        | 0.23%   |
| 15      | 1        | 0.23%   |
| 14      | 1        | 0.23%   |
| 10      | 1        | 0.23%   |
| 9       | 1        | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 168      | 40.29%  |
| 401-500     | 87       | 20.86%  |
| 601-700     | 47       | 11.27%  |
| 1001-1500   | 21       | 5.04%   |
| 701-800     | 19       | 4.56%   |
| Unknown     | 17       | 4.08%   |
| 801-900     | 13       | 3.12%   |
| 351-400     | 13       | 3.12%   |
| 1501-2000   | 13       | 3.12%   |
| 301-350     | 8        | 1.92%   |
| 201-300     | 5        | 1.2%    |
| 901-1000    | 5        | 1.2%    |
| 101-200     | 1        | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 288      | 73.47%  |
| 16/10   | 40       | 10.2%   |
| 21/9    | 22       | 5.61%   |
| 5/4     | 14       | 3.57%   |
| Unknown | 14       | 3.57%   |
| 4/3     | 7        | 1.79%   |
| 32/9    | 7        | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 123      | 29.36%  |
| 301-350        | 71       | 16.95%  |
| 351-500        | 60       | 14.32%  |
| 151-200        | 45       | 10.74%  |
| 251-300        | 30       | 7.16%   |
| More than 1000 | 27       | 6.44%   |
| 501-1000       | 18       | 4.3%    |
| 141-150        | 17       | 4.06%   |
| Unknown        | 17       | 4.06%   |
| 71-80          | 3        | 0.72%   |
| 101-110        | 3        | 0.72%   |
| 51-60          | 1        | 0.24%   |
| 41-50          | 1        | 0.24%   |
| 131-140        | 1        | 0.24%   |
| 121-130        | 1        | 0.24%   |
| 111-120        | 1        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 242      | 59.31%  |
| 101-120 | 92       | 22.55%  |
| 121-160 | 25       | 6.13%   |
| 1-50    | 18       | 4.41%   |
| Unknown | 17       | 4.17%   |
| 161-240 | 14       | 3.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 317      | 76.2%   |
| 2     | 67       | 16.11%  |
| 0     | 24       | 5.77%   |
| 3     | 7        | 1.68%   |
| 4     | 1        | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 272      | 44.16%  |
| Intel                           | 171      | 27.76%  |
| Qualcomm Atheros                | 26       | 4.22%   |
| Broadcom                        | 23       | 3.73%   |
| MediaTek                        | 22       | 3.57%   |
| TP-Link                         | 18       | 2.92%   |
| Ralink Technology               | 10       | 1.62%   |
| Microsoft                       | 8        | 1.3%    |
| NetGear                         | 7        | 1.14%   |
| D-Link                          | 6        | 0.97%   |
| Aquantia                        | 5        | 0.81%   |
| Qualcomm Atheros Communications | 4        | 0.65%   |
| Xiaomi                          | 3        | 0.49%   |
| Ralink                          | 3        | 0.49%   |
| Mellanox Technologies           | 3        | 0.49%   |
| Marvell Technology Group        | 3        | 0.49%   |
| Samsung Electronics             | 2        | 0.32%   |
| Huawei Technologies             | 2        | 0.32%   |
| Google                          | 2        | 0.32%   |
| Edimax Technology               | 2        | 0.32%   |
| Dresden Elektronik              | 2        | 0.32%   |
| D-Link System                   | 2        | 0.32%   |
| Broadcom Limited                | 2        | 0.32%   |
| AVM                             | 2        | 0.32%   |
| ASUSTek Computer                | 2        | 0.32%   |
| Apple                           | 2        | 0.32%   |
| ZyXEL Communications            | 1        | 0.16%   |
| ZyDAS                           | 1        | 0.16%   |
| Z-Com                           | 1        | 0.16%   |
| Qualcomm                        | 1        | 0.16%   |
| QinHeng Electronics             | 1        | 0.16%   |
| Philips (or NXP)                | 1        | 0.16%   |
| Nvidia                          | 1        | 0.16%   |
| Motorola PCS                    | 1        | 0.16%   |
| Linksys                         | 1        | 0.16%   |
| Lenovo                          | 1        | 0.16%   |
| Guillemot                       | 1        | 0.16%   |
| 3Com                            | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 204      | 29.27%  |
| Realtek RTL8125 2.5GbE Controller                                 | 39       | 5.6%    |
| Intel Ethernet Controller I225-V                                  | 22       | 3.16%   |
| Intel Wi-Fi 6 AX200                                               | 20       | 2.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16       | 2.3%    |
| Intel I211 Gigabit Network Connection                             | 15       | 2.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 13       | 1.87%   |
| Intel Ethernet Connection (2) I219-V                              | 10       | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 1.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 1.15%   |
| Realtek 802.11ac NIC                                              | 8        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 1.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7        | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 6        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 0.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6        | 0.86%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5        | 0.72%   |
| Intel Ethernet Connection (17) I219-V                             | 5        | 0.72%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 5        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5        | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.57%   |
| D-Link 802.11ac NIC                                               | 4        | 0.57%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.57%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 74       | 30.71%  |
| Realtek Semiconductor           | 49       | 20.33%  |
| MediaTek                        | 22       | 9.13%   |
| TP-Link                         | 18       | 7.47%   |
| Broadcom                        | 13       | 5.39%   |
| Qualcomm Atheros                | 12       | 4.98%   |
| Ralink Technology               | 10       | 4.15%   |
| Microsoft                       | 8        | 3.32%   |
| NetGear                         | 7        | 2.9%    |
| D-Link                          | 6        | 2.49%   |
| Qualcomm Atheros Communications | 4        | 1.66%   |
| Ralink                          | 3        | 1.24%   |
| Edimax Technology               | 2        | 0.83%   |
| Broadcom Limited                | 2        | 0.83%   |
| AVM                             | 2        | 0.83%   |
| ASUSTek Computer                | 2        | 0.83%   |
| ZyXEL Communications            | 1        | 0.41%   |
| ZyDAS                           | 1        | 0.41%   |
| Z-Com                           | 1        | 0.41%   |
| Philips (or NXP)                | 1        | 0.41%   |
| Linksys                         | 1        | 0.41%   |
| Guillemot                       | 1        | 0.41%   |
| D-Link System                   | 1        | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 20       | 8.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 16       | 6.58%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 13       | 5.35%   |
| Realtek 802.11ac NIC                                                                          | 8        | 3.29%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 7        | 2.88%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 6        | 2.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 6        | 2.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 5        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 2.06%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 5        | 2.06%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 5        | 2.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 2.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 4        | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 4        | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 1.65%   |
| D-Link 802.11ac NIC                                                                           | 4        | 1.65%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 4        | 1.65%   |
| TP-Link 802.11ac NIC                                                                          | 3        | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.23%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 3        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 1.23%   |
| Intel Wireless-AC 9260                                                                        | 3        | 1.23%   |
| Intel Wireless 7260                                                                           | 3        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 0.82%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 0.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 2        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2        | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 0.82%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.82%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.82%   |
| NetGear A6210                                                                                 | 2        | 0.82%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 2        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 258      | 58.9%   |
| Intel                    | 129      | 29.45%  |
| Qualcomm Atheros         | 15       | 3.42%   |
| Broadcom                 | 10       | 2.28%   |
| Aquantia                 | 5        | 1.14%   |
| Xiaomi                   | 3        | 0.68%   |
| Mellanox Technologies    | 3        | 0.68%   |
| Marvell Technology Group | 3        | 0.68%   |
| Samsung Electronics      | 2        | 0.46%   |
| Google                   | 2        | 0.46%   |
| Qualcomm                 | 1        | 0.23%   |
| Nvidia                   | 1        | 0.23%   |
| Motorola PCS             | 1        | 0.23%   |
| Lenovo                   | 1        | 0.23%   |
| Huawei Technologies      | 1        | 0.23%   |
| D-Link System            | 1        | 0.23%   |
| Apple                    | 1        | 0.23%   |
| 3Com                     | 1        | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 204      | 45.43%  |
| Realtek RTL8125 2.5GbE Controller                                             | 39       | 8.69%   |
| Intel Ethernet Controller I225-V                                              | 22       | 4.9%    |
| Intel I211 Gigabit Network Connection                                         | 15       | 3.34%   |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 2.23%   |
| Intel Ethernet Connection I217-LM                                             | 9        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 1.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6        | 1.34%   |
| Intel I210 Gigabit Network Connection                                         | 6        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                          | 6        | 1.34%   |
| Intel Ethernet Connection (2) I218-V                                          | 6        | 1.34%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 1.11%   |
| Intel Ethernet Connection (17) I219-V                                         | 5        | 1.11%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 0.89%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 0.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 0.67%   |
| Intel Ethernet Controller I226-V                                              | 3        | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.45%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 2        | 0.45%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 2        | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.45%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 405      | 63.78%  |
| WiFi     | 225      | 35.43%  |
| Modem    | 5        | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 313      | 72.62%  |
| WiFi     | 118      | 27.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 238      | 57.91%  |
| 2     | 142      | 34.55%  |
| 3     | 25       | 6.08%   |
| 0     | 4        | 0.97%   |
| 5     | 1        | 0.24%   |
| 4     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 269      | 64.82%  |
| Yes  | 146      | 35.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 70       | 38.67%  |
| Cambridge Silicon Radio         | 26       | 14.36%  |
| Realtek Semiconductor           | 21       | 11.6%   |
| MediaTek                        | 12       | 6.63%   |
| IMC Networks                    | 11       | 6.08%   |
| ASUSTek Computer                | 9        | 4.97%   |
| TP-Link                         | 5        | 2.76%   |
| Apple                           | 5        | 2.76%   |
| Foxconn / Hon Hai               | 4        | 2.21%   |
| Broadcom                        | 4        | 2.21%   |
| Qualcomm Atheros Communications | 3        | 1.66%   |
| Realtek                         | 2        | 1.1%    |
| Lite-On Technology              | 2        | 1.1%    |
| Logitech                        | 1        | 0.55%   |
| Integrated System Solution      | 1        | 0.55%   |
| HTC (High Tech Computer)        | 1        | 0.55%   |
| Fujitsu                         | 1        | 0.55%   |
| Edimax Technology               | 1        | 0.55%   |
| Dynex                           | 1        | 0.55%   |
| Belkin Components               | 1        | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26       | 14.29%  |
| Realtek Bluetooth Radio                                              | 18       | 9.89%   |
| Intel AX200 Bluetooth                                                | 18       | 9.89%   |
| Intel AX210 Bluetooth                                                | 13       | 7.14%   |
| MediaTek Wireless_Device                                             | 12       | 6.59%   |
| Intel Bluetooth wireless interface                                   | 11       | 6.04%   |
| Intel AX201 Bluetooth                                                | 11       | 6.04%   |
| IMC Networks Bluetooth Radio                                         | 7        | 3.85%   |
| Intel Bluetooth Device                                               | 6        | 3.3%    |
| TP-Link UB5A Adapter                                                 | 5        | 2.75%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5        | 2.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 2.2%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 3        | 1.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 1.65%   |
| IMC Networks Wireless_Device                                         | 3        | 1.65%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 1.65%   |
| Apple Bluetooth Host Controller                                      | 3        | 1.65%   |
| Realtek Bluetooth Radio                                              | 2        | 1.1%    |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.1%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.1%    |
| ASUS ASUS USB-BT500                                                  | 2        | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.55%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1        | 0.55%   |
| Lite-On Bluetooth Device                                             | 1        | 0.55%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.55%   |
| IMC Networks BCM20702A0                                              | 1        | 0.55%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.55%   |
| Fujitsu Bluetooth Device                                             | 1        | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 0.55%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.55%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.55%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.55%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.55%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.55%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.55%   |
| ASUS BCM20702A0                                                      | 1        | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 255      | 36.22%  |
| AMD                                             | 187      | 26.56%  |
| Nvidia                                          | 146      | 20.74%  |
| C-Media Electronics                             | 19       | 2.7%    |
| Logitech                                        | 15       | 2.13%   |
| ASUSTek Computer                                | 13       | 1.85%   |
| Texas Instruments                               | 5        | 0.71%   |
| Razer USA                                       | 4        | 0.57%   |
| Micro Star International                        | 4        | 0.57%   |
| GN Netcom                                       | 4        | 0.57%   |
| VIA Technologies                                | 3        | 0.43%   |
| Sony                                            | 3        | 0.43%   |
| KORG                                            | 3        | 0.43%   |
| Kingston Technology                             | 3        | 0.43%   |
| Creative Labs                                   | 3        | 0.43%   |
| SteelSeries ApS                                 | 2        | 0.28%   |
| Samson Technologies                             | 2        | 0.28%   |
| Lenovo                                          | 2        | 0.28%   |
| JMTek                                           | 2        | 0.28%   |
| Giga-Byte Technology                            | 2        | 0.28%   |
| Focusrite-Novation                              | 2        | 0.28%   |
| Creative Technology                             | 2        | 0.28%   |
| BEHRINGER International                         | 2        | 0.28%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.14%   |
| Yamaha                                          | 1        | 0.14%   |
| USB Audio                                       | 1        | 0.14%   |
| Turtle Beach                                    | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.14%   |
| Tenx Technology                                 | 1        | 0.14%   |
| Realtek Semiconductor                           | 1        | 0.14%   |
| PreSonus Audio Electronics                      | 1        | 0.14%   |
| Plantronics                                     | 1        | 0.14%   |
| Nektar                                          | 1        | 0.14%   |
| Native Instruments                              | 1        | 0.14%   |
| Microdia                                        | 1        | 0.14%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.14%   |
| Jieli Technology                                | 1        | 0.14%   |
| JBL                                             | 1        | 0.14%   |
| Generalplus Technology                          | 1        | 0.14%   |
| ESS Technology                                  | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 52       | 6.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38       | 4.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29       | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26       | 3.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 25       | 2.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24       | 2.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21       | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 2.34%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 19       | 2.22%   |
| Intel Alder Lake-S HD Audio Controller                                     | 18       | 2.11%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 17       | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 1.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13       | 1.52%   |
| AMD FCH Azalia Controller                                                  | 13       | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 12       | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12       | 1.41%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 12       | 1.41%   |
| ASUSTek Computer USB Audio                                                 | 12       | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.17%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 0.94%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 8        | 0.94%   |
| AMD Trinity HDMI Audio Controller                                          | 8        | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 0.94%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 7        | 0.82%   |
| Nvidia Audio device                                                        | 7        | 0.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 7        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.82%   |
| Nvidia High Definition Audio Controller                                    | 6        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 34       | 18.38%  |
| Corsair                              | 25       | 13.51%  |
| G.Skill                              | 19       | 10.27%  |
| Unknown                              | 18       | 9.73%   |
| Samsung Electronics                  | 17       | 9.19%   |
| Crucial                              | 15       | 8.11%   |
| SK hynix                             | 9        | 4.86%   |
| Micron Technology                    | 8        | 4.32%   |
| A-DATA Technology                    | 7        | 3.78%   |
| Team                                 | 4        | 2.16%   |
| Patriot                              | 3        | 1.62%   |
| Transcend                            | 2        | 1.08%   |
| Ramaxel Technology                   | 2        | 1.08%   |
| Patriot Memory                       | 2        | 1.08%   |
| Nanya Technology                     | 2        | 1.08%   |
| GOODRAM                              | 2        | 1.08%   |
| Unknown                              | 2        | 1.08%   |
| Wodposit                             | 1        | 0.54%   |
| Unknown (ABCD)                       | 1        | 0.54%   |
| Unknown (AB)                         | 1        | 0.54%   |
| Unknown (0x9801)                     | 1        | 0.54%   |
| Unknown (0x0C26)                     | 1        | 0.54%   |
| Unknown (0B85)                       | 1        | 0.54%   |
| Unifosa                              | 1        | 0.54%   |
| Lexar                                | 1        | 0.54%   |
| Juhor                                | 1        | 0.54%   |
| Hewlett-Packard                      | 1        | 0.54%   |
| Elpida                               | 1        | 0.54%   |
| Chun Well Technology Holding Limited | 1        | 0.54%   |
| Atermiter                            | 1        | 0.54%   |
| ASint Technology                     | 1        | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 4        | 2.03%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 3        | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2        | 1.02%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 1.02%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                      | 2        | 1.02%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s     | 2        | 1.02%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 2        | 1.02%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s               | 2        | 1.02%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s               | 2        | 1.02%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s           | 2        | 1.02%   |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s          | 2        | 1.02%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s             | 2        | 1.02%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 2        | 1.02%   |
| A-DATA RAM Module 16GB DIMM DDR4 3200MT/s                      | 2        | 1.02%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 1.02%   |
| Unknown                                                        | 2        | 1.02%   |
| Wodposit RAM WPBH26D416SXA-8G 8GB SODIMM DDR4 2667MT/s         | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM SDRAM                              | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM                                    | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.51%   |
| Unknown RAM Module 32GB DIMM DDR4 2400MT/s                     | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                      | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR 533MT/s                        | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.51%   |
| Unknown RAM Module 1GB DIMM SDRAM 800MT/s                      | 1        | 0.51%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1        | 0.51%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.51%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s            | 1        | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1        | 0.51%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 2133MT/s               | 1        | 0.51%   |
| Unknown (0x9801) RAM Module 4GB DIMM DDR3 1334MT/s             | 1        | 0.51%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3600 32GB DIMM DDR4 2667MT/s  | 1        | 0.51%   |
| Unknown (0B85) RAM Module 8GB DIMM DDR3                        | 1        | 0.51%   |
| Unifosa RAM HU524303EP0200 2GB DIMM DDR3 1333MT/s              | 1        | 0.51%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s               | 1        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 86       | 50.59%  |
| DDR3    | 35       | 20.59%  |
| DDR5    | 26       | 15.29%  |
| SDRAM   | 11       | 6.47%   |
| Unknown | 4        | 2.35%   |
| DDR2    | 3        | 1.76%   |
| DDR     | 2        | 1.18%   |
| LPDDR5  | 1        | 0.59%   |
| LPDDR4  | 1        | 0.59%   |
| LPDDR3  | 1        | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 152      | 91.57%  |
| SODIMM       | 13       | 7.83%   |
| Row Of Chips | 1        | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 67       | 37.43%  |
| 16384 | 39       | 21.79%  |
| 32768 | 27       | 15.08%  |
| 4096  | 26       | 14.53%  |
| 2048  | 14       | 7.82%   |
| 1024  | 4        | 2.23%   |
| 49152 | 1        | 0.56%   |
| 512   | 1        | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 23       | 12.85%  |
| 1600    | 22       | 12.29%  |
| 3600    | 14       | 7.82%   |
| 2400    | 14       | 7.82%   |
| 2133    | 9        | 5.03%   |
| 1333    | 7        | 3.91%   |
| 6000    | 6        | 3.35%   |
| 4800    | 6        | 3.35%   |
| 2667    | 6        | 3.35%   |
| Unknown | 5        | 2.79%   |
| 6400    | 4        | 2.23%   |
| 5200    | 4        | 2.23%   |
| 3866    | 4        | 2.23%   |
| 800     | 4        | 2.23%   |
| 5600    | 3        | 1.68%   |
| 3733    | 3        | 1.68%   |
| 3400    | 3        | 1.68%   |
| 2933    | 3        | 1.68%   |
| 2666    | 3        | 1.68%   |
| 1867    | 3        | 1.68%   |
| 5808    | 2        | 1.12%   |
| 3666    | 2        | 1.12%   |
| 3466    | 2        | 1.12%   |
| 3266    | 2        | 1.12%   |
| 2048    | 2        | 1.12%   |
| 1866    | 2        | 1.12%   |
| 1800    | 2        | 1.12%   |
| 667     | 2        | 1.12%   |
| 400     | 2        | 1.12%   |
| 6800    | 1        | 0.56%   |
| 5800    | 1        | 0.56%   |
| 4199    | 1        | 0.56%   |
| 3933    | 1        | 0.56%   |
| 3800    | 1        | 0.56%   |
| 3534    | 1        | 0.56%   |
| 3533    | 1        | 0.56%   |
| 3334    | 1        | 0.56%   |
| 3066    | 1        | 0.56%   |
| 2800    | 1        | 0.56%   |
| 2176    | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 8        | 29.63%  |
| Seiko Epson           | 5        | 18.52%  |
| Hewlett-Packard       | 5        | 18.52%  |
| Samsung Electronics   | 4        | 14.81%  |
| Canon                 | 2        | 7.41%   |
| QinHeng Electronics   | 1        | 3.7%    |
| Pantum                | 1        | 3.7%    |
| Lexmark International | 1        | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson XP-2200 Series                   | 1        | 3.7%    |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 3.7%    |
| Seiko Epson ET-8550 Series                   | 1        | 3.7%    |
| Seiko Epson ET-2820 Series                   | 1        | 3.7%    |
| Seiko Epson ET-2810 Series                   | 1        | 3.7%    |
| Samsung SCX-4623 Series                      | 1        | 3.7%    |
| Samsung SCX-3400 Series                      | 1        | 3.7%    |
| Samsung M2020 Series                         | 1        | 3.7%    |
| Samsung CLX-3170 Series                      | 1        | 3.7%    |
| QinHeng CH340S                               | 1        | 3.7%    |
| Pantum P2200 series                          | 1        | 3.7%    |
| Lexmark International MC3326adwe             | 1        | 3.7%    |
| HP OfficeJet 5200 series                     | 1        | 3.7%    |
| HP LaserJet P2055 series                     | 1        | 3.7%    |
| HP DeskJet 960c                              | 1        | 3.7%    |
| HP ColorLaserJet M253-M254                   | 1        | 3.7%    |
| HP Color LaserJet Pro M453-4                 | 1        | 3.7%    |
| Canon TR4500 series                          | 1        | 3.7%    |
| Canon iP7200 series                          | 1        | 3.7%    |
| Brother MFC-J6530DW                          | 1        | 3.7%    |
| Brother MFC-J1010DW                          | 1        | 3.7%    |
| Brother MFC-9330CDW                          | 1        | 3.7%    |
| Brother HL-L5000D series                     | 1        | 3.7%    |
| Brother HL-52x0 series                       | 1        | 3.7%    |
| Brother HL-2030 Laser Printer                | 1        | 3.7%    |
| Brother DCP-7055W                            | 1        | 3.7%    |
| Brother DCP-1610W                            | 1        | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Canon   | 3        | 75%     |
| Plustek | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan LiDE 100            | 2        | 50%     |
| Plustek 600dpi USB Scanner         | 1        | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                              | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech                            | 34       | 42.5%   |
| Microsoft                           | 5        | 6.25%   |
| Apple                               | 5        | 6.25%   |
| Sunplus Innovation Technology       | 4        | 5%      |
| Samsung Electronics                 | 3        | 3.75%   |
| Razer USA                           | 3        | 3.75%   |
| ARC International                   | 3        | 3.75%   |
| Z-Star Microelectronics             | 2        | 2.5%    |
| Microdia                            | 2        | 2.5%    |
| Generalplus Technology              | 2        | 2.5%    |
| WCM_USB                             | 1        | 1.25%   |
| Trust                               | 1        | 1.25%   |
| SunplusIT                           | 1        | 1.25%   |
| Sonix Technology                    | 1        | 1.25%   |
| SHENZHEN EMEET TECHNOLOGY           | 1        | 1.25%   |
| Pixart Imaging                      | 1        | 1.25%   |
| MacroSilicon                        | 1        | 1.25%   |
| Lite-On Technology                  | 1        | 1.25%   |
| KYE Systems (Mouse Systems)         | 1        | 1.25%   |
| Hauppauge                           | 1        | 1.25%   |
| Genesys Logic                       | 1        | 1.25%   |
| Fuzhou Rockchip Electronics Company | 1        | 1.25%   |
| eMeet                               | 1        | 1.25%   |
| AVerMedia Technologies              | 1        | 1.25%   |
| Arkmicro Technologies               | 1        | 1.25%   |
| Anchor Chips                        | 1        | 1.25%   |
| Unknown                             | 1        | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 9        | 11.11%  |
| Logitech HD Pro Webcam C920             | 5        | 6.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 4        | 4.94%   |
| Samsung Galaxy series, misc. (MTP mode) | 3        | 3.7%    |
| Logitech BRIO                           | 3        | 3.7%    |
| Sunplus Integrated_Webcam_HD            | 2        | 2.47%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 2.47%   |
| Microsoft LifeCam HD-3000               | 2        | 2.47%   |
| Logitech HD Webcam C510                 | 2        | 2.47%   |
| Generalplus CAMERA - UVC                | 2        | 2.47%   |
| ARC International Camera                | 2        | 2.47%   |
| Z-Star USB 2.0 Web Camera               | 1        | 1.23%   |
| Z-Star Lenovo USB 2.0 UVC Camera        | 1        | 1.23%   |
| WCM_USB WEB CAM                         | 1        | 1.23%   |
| Trust Widescreen 3MP Webcam             | 1        | 1.23%   |
| SunplusIT USB 2.0 Camera                | 1        | 1.23%   |
| Sunplus AUKEY PC-LM1E Camera            | 1        | 1.23%   |
| Sunplus 2K FHD camera                   | 1        | 1.23%   |
| Sonix FHD Webcam                        | 1        | 1.23%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova    | 1        | 1.23%   |
| Razer USA Razer Kiyo Pro                | 1        | 1.23%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 1.23%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 1        | 1.23%   |
| Microsoft LifeCam NX-6000               | 1        | 1.23%   |
| Microsoft LifeCam HD-5000               | 1        | 1.23%   |
| Microdia Sonix USB 2.0 Camera           | 1        | 1.23%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1        | 1.23%   |
| MacroSilicon USB3. 0 capture            | 1        | 1.23%   |
| Logitech Webcam Pro 9000                | 1        | 1.23%   |
| Logitech Webcam C930e                   | 1        | 1.23%   |
| Logitech Webcam C300                    | 1        | 1.23%   |
| Logitech Webcam C250                    | 1        | 1.23%   |
| Logitech Webcam C210                    | 1        | 1.23%   |
| Logitech Webcam C200                    | 1        | 1.23%   |
| Logitech Webcam C170                    | 1        | 1.23%   |
| Logitech StreamCam                      | 1        | 1.23%   |
| Logitech QuickCam Vision Pro            | 1        | 1.23%   |
| Logitech QuickCam Pro 9000              | 1        | 1.23%   |
| Logitech QuickCam Communicate MP/S5500  | 1        | 1.23%   |
| Logitech HD Webcam C615                 | 1        | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 349      | 84.3%   |
| 1     | 55       | 13.29%  |
| 2     | 8        | 1.93%   |
| 6     | 1        | 0.24%   |
| 3     | 1        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 25       | 35.71%  |
| Unassigned class         | 13       | 18.57%  |
| Net/wireless             | 11       | 15.71%  |
| Communication controller | 9        | 12.86%  |
| Sound                    | 4        | 5.71%   |
| Multimedia controller    | 2        | 2.86%   |
| Camera                   | 2        | 2.86%   |
| Bluetooth                | 2        | 2.86%   |
| Fingerprint reader       | 1        | 1.43%   |
| Chipcard                 | 1        | 1.43%   |

