OpenMandriva 23.08 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.08.

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

Total: 910

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3396                        | [5e68a536f2](https://linux-hardware.org/?probe=5e68a536f2) | May 09, 2024 |
| Dell          | 0VNP2H A00                  | [28953f7c6a](https://linux-hardware.org/?probe=28953f7c6a) | May 09, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| ASRock        | B450M-HDV                   | [098e62d52a](https://linux-hardware.org/?probe=098e62d52a) | May 08, 2024 |
| Gigabyte      | H310M S2H x.x               | [97598b9cc3](https://linux-hardware.org/?probe=97598b9cc3) | May 07, 2024 |
| Intel         | DQ45CB AAE30148-207         | [263e934dc2](https://linux-hardware.org/?probe=263e934dc2) | May 07, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [ae1edad2ab](https://linux-hardware.org/?probe=ae1edad2ab) | May 06, 2024 |
| HP            | 8053                        | [06b48e5ec6](https://linux-hardware.org/?probe=06b48e5ec6) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | [780a67ef79](https://linux-hardware.org/?probe=780a67ef79) | May 05, 2024 |
| Lenovo        | 0B98401 WIN                 | [8d1ee988ad](https://linux-hardware.org/?probe=8d1ee988ad) | May 05, 2024 |
| Dell          | 0R6PCT A01                  | [61f596b724](https://linux-hardware.org/?probe=61f596b724) | May 04, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [64b195310b](https://linux-hardware.org/?probe=64b195310b) | May 04, 2024 |
| HP            | 339A                        | [a5f44d3bdb](https://linux-hardware.org/?probe=a5f44d3bdb) | May 04, 2024 |
| Gigabyte      | B550M DS3H AC               | [15375b5d97](https://linux-hardware.org/?probe=15375b5d97) | May 04, 2024 |
| ASUSTek       | K8V-MX                      | [64054e7bf3](https://linux-hardware.org/?probe=64054e7bf3) | May 03, 2024 |
| ASUSTek       | PRIME B460-PLUS             | [dd201d321b](https://linux-hardware.org/?probe=dd201d321b) | May 03, 2024 |
| Dell          | 0WR7PY A04                  | [b48e977e84](https://linux-hardware.org/?probe=b48e977e84) | May 03, 2024 |
| Intel         | B75                         | [4c39b0616d](https://linux-hardware.org/?probe=4c39b0616d) | May 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [d7c901b5d7](https://linux-hardware.org/?probe=d7c901b5d7) | May 02, 2024 |
| Packard Be... | IMEDIA S2185                | [47d64869d6](https://linux-hardware.org/?probe=47d64869d6) | Apr 30, 2024 |
| MSI           | PRO H610M-G DDR4            | [b8ab800603](https://linux-hardware.org/?probe=b8ab800603) | Apr 30, 2024 |
| Biostar       | H310MHP                     | [1faa8b5213](https://linux-hardware.org/?probe=1faa8b5213) | Apr 30, 2024 |
| Biostar       | H310MHP                     | [d5bc5a946f](https://linux-hardware.org/?probe=d5bc5a946f) | Apr 30, 2024 |
| Lenovo        | 30C9 SEK0N11843 IOT 3806... | [517daa7c85](https://linux-hardware.org/?probe=517daa7c85) | Apr 30, 2024 |
| ASUSTek       | PRIME H410M-K               | [9c6f64ecd9](https://linux-hardware.org/?probe=9c6f64ecd9) | Apr 29, 2024 |
| ASUSTek       | H81M-P PLUS                 | [e3c17dccb5](https://linux-hardware.org/?probe=e3c17dccb5) | Apr 29, 2024 |
| Gigabyte      | GA-MA785GMT-UD2H            | [b1f251b92c](https://linux-hardware.org/?probe=b1f251b92c) | Apr 29, 2024 |
| EVGA          | NF66 2                      | [ef1a49773b](https://linux-hardware.org/?probe=ef1a49773b) | Apr 29, 2024 |
| ASUSTek       | Maximus VII HERO            | [51efe9cdc9](https://linux-hardware.org/?probe=51efe9cdc9) | Apr 28, 2024 |
| MSI           | A68HM GRENADE               | [c1a1b60624](https://linux-hardware.org/?probe=c1a1b60624) | Apr 28, 2024 |
| Intel         | D945GCL AAD67193-205        | [2520d8fe1d](https://linux-hardware.org/?probe=2520d8fe1d) | Apr 28, 2024 |
| ASUSTek       | P8H61-M LE                  | [15d91ebe7c](https://linux-hardware.org/?probe=15d91ebe7c) | Apr 28, 2024 |
| ASRock        | A320M-DVS R3.0              | [3af9ef3df5](https://linux-hardware.org/?probe=3af9ef3df5) | Apr 27, 2024 |
| MSI           | G31M3-L V2                  | [0a033139d1](https://linux-hardware.org/?probe=0a033139d1) | Apr 27, 2024 |
| HP            | 3029h                       | [70cd5cbc22](https://linux-hardware.org/?probe=70cd5cbc22) | Apr 26, 2024 |
| MSI           | B250I GAMING PRO AC         | [edf573962d](https://linux-hardware.org/?probe=edf573962d) | Apr 25, 2024 |
| MAXSUN        | MS-Terminator B550M         | [4960448326](https://linux-hardware.org/?probe=4960448326) | Apr 25, 2024 |
| HP            | 2AF7                        | [dcff3bbb91](https://linux-hardware.org/?probe=dcff3bbb91) | Apr 25, 2024 |
| Gigabyte      | F2A55M-DS2                  | [8252280757](https://linux-hardware.org/?probe=8252280757) | Apr 25, 2024 |
| Gigabyte      | EX58-UD3R                   | [826b210e79](https://linux-hardware.org/?probe=826b210e79) | Apr 24, 2024 |
| Dell          | 08NPPY A00                  | [8e54a2234f](https://linux-hardware.org/?probe=8e54a2234f) | Apr 24, 2024 |
| Acer          | Veriton X2632G V:1.0        | [88daeba4af](https://linux-hardware.org/?probe=88daeba4af) | Apr 23, 2024 |
| Gigabyte      | Z390 UD                     | [36a382f0da](https://linux-hardware.org/?probe=36a382f0da) | Apr 23, 2024 |
| ASUSTek       | A68HM-PLUS                  | [c495b7e3d7](https://linux-hardware.org/?probe=c495b7e3d7) | Apr 23, 2024 |
| ASRock        | G31M-S                      | [591e58940a](https://linux-hardware.org/?probe=591e58940a) | Apr 22, 2024 |
| Dell          | 0VHXCD A01                  | [4b7a01c41a](https://linux-hardware.org/?probe=4b7a01c41a) | Apr 22, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a2b7475561](https://linux-hardware.org/?probe=a2b7475561) | Apr 21, 2024 |
| Positivo      | POS-PIG41BA POSITIVO        | [d5e1581050](https://linux-hardware.org/?probe=d5e1581050) | Apr 21, 2024 |
| Acer          | WG43M                       | [93fcdbd13d](https://linux-hardware.org/?probe=93fcdbd13d) | Apr 20, 2024 |
| HP            | 339A                        | [8cb48fe045](https://linux-hardware.org/?probe=8cb48fe045) | Apr 19, 2024 |
| MSI           | MS-7235                     | [d0b1ac0e44](https://linux-hardware.org/?probe=d0b1ac0e44) | Apr 19, 2024 |
| MSI           | B85I                        | [8751cf893f](https://linux-hardware.org/?probe=8751cf893f) | Apr 19, 2024 |
| Dell          | 0Y958C A00                  | [88a0060933](https://linux-hardware.org/?probe=88a0060933) | Apr 18, 2024 |
| ASUSTek       | P9X79                       | [3f587bf3dd](https://linux-hardware.org/?probe=3f587bf3dd) | Apr 18, 2024 |
| ASUSTek       | P8Z77-V LX                  | [686220b484](https://linux-hardware.org/?probe=686220b484) | Apr 17, 2024 |
| Pegatron      | Narra6                      | [fb336cac9b](https://linux-hardware.org/?probe=fb336cac9b) | Apr 17, 2024 |
| Intel         | H61                         | [e0bacf6b01](https://linux-hardware.org/?probe=e0bacf6b01) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [41c197d579](https://linux-hardware.org/?probe=41c197d579) | Apr 16, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4fb5756438](https://linux-hardware.org/?probe=4fb5756438) | Apr 14, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | [c6fd918c6e](https://linux-hardware.org/?probe=c6fd918c6e) | Apr 14, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [ca76c3d3ec](https://linux-hardware.org/?probe=ca76c3d3ec) | Apr 13, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2998b9027d](https://linux-hardware.org/?probe=2998b9027d) | Apr 13, 2024 |
| Dell          | OptiPlex 7050               | [e6f968f709](https://linux-hardware.org/?probe=e6f968f709) | Apr 11, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [5757303d9a](https://linux-hardware.org/?probe=5757303d9a) | Apr 11, 2024 |
| Dell          | 0NKW6Y A02                  | [fcd30b6392](https://linux-hardware.org/?probe=fcd30b6392) | Apr 11, 2024 |
| HP            | 1998                        | [4e592f29d7](https://linux-hardware.org/?probe=4e592f29d7) | Apr 11, 2024 |
| Foxconn       | 2A8C                        | [9d16faea24](https://linux-hardware.org/?probe=9d16faea24) | Apr 10, 2024 |
| ASUSTek       | H61M-C                      | [a0e36b103b](https://linux-hardware.org/?probe=a0e36b103b) | Apr 10, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1163ac6ace](https://linux-hardware.org/?probe=1163ac6ace) | Apr 09, 2024 |
| MSI           | G41M-P26                    | [c337a993c8](https://linux-hardware.org/?probe=c337a993c8) | Apr 07, 2024 |
| ASUSTek       | M4A88T-M/USB3               | [69cf49e1b1](https://linux-hardware.org/?probe=69cf49e1b1) | Apr 07, 2024 |
| Intel         | B75                         | [7ac22ca55d](https://linux-hardware.org/?probe=7ac22ca55d) | Apr 07, 2024 |
| Dell          | 0KP561                      | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| Gigabyte      | H410M S2H V2                | [2713f1fbb2](https://linux-hardware.org/?probe=2713f1fbb2) | Apr 06, 2024 |
| Unknown       | Unknown                     | [0f08ac20fe](https://linux-hardware.org/?probe=0f08ac20fe) | Apr 06, 2024 |
| HP            | 1497                        | [bc9fcab61a](https://linux-hardware.org/?probe=bc9fcab61a) | Apr 06, 2024 |
| HP            | 1790                        | [0038bf2917](https://linux-hardware.org/?probe=0038bf2917) | Apr 06, 2024 |
| Biostar       | TB250-BTC PRO               | [3fceee8ca7](https://linux-hardware.org/?probe=3fceee8ca7) | Apr 06, 2024 |
| Dell          | 02YYK5 A01                  | [e407d84cc9](https://linux-hardware.org/?probe=e407d84cc9) | Apr 06, 2024 |
| ASRock        | H87 Pro4                    | [46c9acd849](https://linux-hardware.org/?probe=46c9acd849) | Apr 05, 2024 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [2d8c4c947f](https://linux-hardware.org/?probe=2d8c4c947f) | Apr 05, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | [1750bd22db](https://linux-hardware.org/?probe=1750bd22db) | Apr 05, 2024 |
| Shenzhen M... | F7BFC                       | [4b0127a449](https://linux-hardware.org/?probe=4b0127a449) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e3541ebcf4](https://linux-hardware.org/?probe=e3541ebcf4) | Apr 03, 2024 |
| Dell          | 051FJ8 A00                  | [8f67355bed](https://linux-hardware.org/?probe=8f67355bed) | Apr 03, 2024 |
| HP            | 3396                        | [641a1891ba](https://linux-hardware.org/?probe=641a1891ba) | Apr 02, 2024 |
| Dell          | 0XFWHV A00                  | [ea24de6920](https://linux-hardware.org/?probe=ea24de6920) | Apr 02, 2024 |
| Gigabyte      | GA-770T-D3L                 | [402894f9cd](https://linux-hardware.org/?probe=402894f9cd) | Apr 01, 2024 |
| Intel         | H81                         | [b7c3224542](https://linux-hardware.org/?probe=b7c3224542) | Apr 01, 2024 |
| HP            | 2171                        | [3cd1f729a4](https://linux-hardware.org/?probe=3cd1f729a4) | Apr 01, 2024 |
| QIYIDA        | X79-M6 V1.0                 | [ab18c6c58f](https://linux-hardware.org/?probe=ab18c6c58f) | Mar 31, 2024 |
| Pegatron      | Benicia                     | [22f74ed745](https://linux-hardware.org/?probe=22f74ed745) | Mar 31, 2024 |
| Gigabyte      | B550M DS3H                  | [2ec08fd0c4](https://linux-hardware.org/?probe=2ec08fd0c4) | Mar 31, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [30575319dc](https://linux-hardware.org/?probe=30575319dc) | Mar 31, 2024 |
| ASUSTek       | P8Z77-V PREMIUM             | [3c3064e23a](https://linux-hardware.org/?probe=3c3064e23a) | Mar 31, 2024 |
| Dell          | 0H634K A00                  | [cd85e4d384](https://linux-hardware.org/?probe=cd85e4d384) | Mar 30, 2024 |
| Positivo      | POS-AG31AP                  | [606557f097](https://linux-hardware.org/?probe=606557f097) | Mar 30, 2024 |
| ASUSTek       | SABERTOOTH X99              | [9eadaaa051](https://linux-hardware.org/?probe=9eadaaa051) | Mar 29, 2024 |
| Gigabyte      | B560M DS3H V2               | [f99b737a3e](https://linux-hardware.org/?probe=f99b737a3e) | Mar 29, 2024 |
| GEEKOM        | A5                          | [c7e07714cc](https://linux-hardware.org/?probe=c7e07714cc) | Mar 28, 2024 |
| HP            | 2AE3                        | [f068c22e6c](https://linux-hardware.org/?probe=f068c22e6c) | Mar 28, 2024 |
| Dell          | 0YXT71 A03                  | [d854505a5b](https://linux-hardware.org/?probe=d854505a5b) | Mar 27, 2024 |
| HP            | 2AA6 PVT                    | [899a3e57bb](https://linux-hardware.org/?probe=899a3e57bb) | Mar 27, 2024 |
| ASRock        | H310CM-HDV                  | [b4c034c103](https://linux-hardware.org/?probe=b4c034c103) | Mar 26, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3f052410d3](https://linux-hardware.org/?probe=3f052410d3) | Mar 26, 2024 |
| Dell          | 088DT1 A01                  | [de5dac0125](https://linux-hardware.org/?probe=de5dac0125) | Mar 26, 2024 |
| ASRock        | H110M-HG4                   | [0ef9ca77ad](https://linux-hardware.org/?probe=0ef9ca77ad) | Mar 26, 2024 |
| Dell          | 07WP95 A01                  | [1c4843f354](https://linux-hardware.org/?probe=1c4843f354) | Mar 26, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [786693fab4](https://linux-hardware.org/?probe=786693fab4) | Mar 25, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [000bb993d1](https://linux-hardware.org/?probe=000bb993d1) | Mar 25, 2024 |
| MSI           | H110M PRO-VD                | [c250bda654](https://linux-hardware.org/?probe=c250bda654) | Mar 25, 2024 |
| Pegatron      | 2AB5                        | [713be0f3f0](https://linux-hardware.org/?probe=713be0f3f0) | Mar 25, 2024 |
| Dell          | 084J0R A00                  | [691f19e56c](https://linux-hardware.org/?probe=691f19e56c) | Mar 24, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [45e2102834](https://linux-hardware.org/?probe=45e2102834) | Mar 23, 2024 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [5a656756e0](https://linux-hardware.org/?probe=5a656756e0) | Mar 22, 2024 |
| ASRock        | A320M-HDV                   | [69bd8b3475](https://linux-hardware.org/?probe=69bd8b3475) | Mar 22, 2024 |
| AMI           | Intel                       | [4bb3934f7d](https://linux-hardware.org/?probe=4bb3934f7d) | Mar 21, 2024 |
| Intel         | X99                         | [c85af1f29d](https://linux-hardware.org/?probe=c85af1f29d) | Mar 21, 2024 |
| Casper        | NIRVANA DESKTOP             | [6428f854e6](https://linux-hardware.org/?probe=6428f854e6) | Mar 21, 2024 |
| HP            | 8768 A                      | [6c296786d2](https://linux-hardware.org/?probe=6c296786d2) | Mar 19, 2024 |
| Foxconn       | 2ABF                        | [cec4a4b661](https://linux-hardware.org/?probe=cec4a4b661) | Mar 19, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [345e2df2db](https://linux-hardware.org/?probe=345e2df2db) | Mar 19, 2024 |
| HP            | 0B4Ch D                     | [e85fec8591](https://linux-hardware.org/?probe=e85fec8591) | Mar 18, 2024 |
| MSI           | X99A RAIDER                 | [8d5dfb7293](https://linux-hardware.org/?probe=8d5dfb7293) | Mar 18, 2024 |
| ASRock        | X470 Taichi                 | [195c54fe84](https://linux-hardware.org/?probe=195c54fe84) | Mar 17, 2024 |
| ASUSTek       | PRIME Z790-P                | [82c42946af](https://linux-hardware.org/?probe=82c42946af) | Mar 17, 2024 |
| MSI           | B560M PRO-E                 | [2e1e84fe15](https://linux-hardware.org/?probe=2e1e84fe15) | Mar 16, 2024 |
| HP            | 097Ch                       | [23bc1b2344](https://linux-hardware.org/?probe=23bc1b2344) | Mar 15, 2024 |
| AZW           | MINI S 10                   | [843a0455d6](https://linux-hardware.org/?probe=843a0455d6) | Mar 15, 2024 |
| MSI           | Z270 PC MATE                | [87ef1a815e](https://linux-hardware.org/?probe=87ef1a815e) | Mar 15, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [708c2c7987](https://linux-hardware.org/?probe=708c2c7987) | Mar 15, 2024 |
| MSI           | B85M-G43                    | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4c8d39a7ab](https://linux-hardware.org/?probe=4c8d39a7ab) | Mar 14, 2024 |
| Gigabyte      | 945GCMX-S2                  | [fa1bce30a0](https://linux-hardware.org/?probe=fa1bce30a0) | Mar 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | [d89d81deb7](https://linux-hardware.org/?probe=d89d81deb7) | Mar 12, 2024 |
| OEM           | X79-Turbo                   | [b19889facd](https://linux-hardware.org/?probe=b19889facd) | Mar 12, 2024 |
| Intel         | B75                         | [f78757e7b2](https://linux-hardware.org/?probe=f78757e7b2) | Mar 11, 2024 |
| Dell          | 0KV62T A00                  | [fba62e6832](https://linux-hardware.org/?probe=fba62e6832) | Mar 11, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | [a32383cf3e](https://linux-hardware.org/?probe=a32383cf3e) | Mar 09, 2024 |
| ASUSTek       | PRIME H510M-E               | [2171fc67cb](https://linux-hardware.org/?probe=2171fc67cb) | Mar 07, 2024 |
| MSI           | B550-A PRO                  | [1df3b86749](https://linux-hardware.org/?probe=1df3b86749) | Mar 06, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [3a31238bd4](https://linux-hardware.org/?probe=3a31238bd4) | Mar 05, 2024 |
| Intel         | DH77EB AAG39073-304         | [b0109a5dac](https://linux-hardware.org/?probe=b0109a5dac) | Mar 05, 2024 |
| Acer          | Veriton N4630G              | [53fb2ce231](https://linux-hardware.org/?probe=53fb2ce231) | Mar 05, 2024 |
| Dell          | 0GM819                      | [82f828df2c](https://linux-hardware.org/?probe=82f828df2c) | Mar 04, 2024 |
| Dell          | 0GM819                      | [1cae3bcd28](https://linux-hardware.org/?probe=1cae3bcd28) | Mar 04, 2024 |
| HP            | 2B1B                        | [a8d024554f](https://linux-hardware.org/?probe=a8d024554f) | Mar 04, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [5e2bacbc0c](https://linux-hardware.org/?probe=5e2bacbc0c) | Mar 02, 2024 |
| ASRock        | G41C-GS R2.0                | [c57846f189](https://linux-hardware.org/?probe=c57846f189) | Mar 01, 2024 |
| ASUSTek       | VANGUARD B85                | [70712f8f34](https://linux-hardware.org/?probe=70712f8f34) | Feb 28, 2024 |
| HP            | 304Ah                       | [f01c7352de](https://linux-hardware.org/?probe=f01c7352de) | Feb 27, 2024 |
| HP            | 1497                        | [58e91b7bbc](https://linux-hardware.org/?probe=58e91b7bbc) | Feb 26, 2024 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [fc8733df5b](https://linux-hardware.org/?probe=fc8733df5b) | Feb 26, 2024 |
| Intel         | D54250WYK H13922-303        | [125932cb50](https://linux-hardware.org/?probe=125932cb50) | Feb 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [4e50b74dd4](https://linux-hardware.org/?probe=4e50b74dd4) | Feb 22, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [177b3e8210](https://linux-hardware.org/?probe=177b3e8210) | Feb 21, 2024 |
| ASUSTek       | PRIME B760M-A               | [df41ae1364](https://linux-hardware.org/?probe=df41ae1364) | Feb 20, 2024 |
| ASRock        | QC6000M                     | [c262bb8499](https://linux-hardware.org/?probe=c262bb8499) | Feb 20, 2024 |
| HP            | 8459                        | [50c9809b3f](https://linux-hardware.org/?probe=50c9809b3f) | Feb 18, 2024 |
| Gigabyte      | G41MT-S2PT                  | [dca61882f5](https://linux-hardware.org/?probe=dca61882f5) | Feb 18, 2024 |
| Dell          | 042P49 A02                  | [cae0de6242](https://linux-hardware.org/?probe=cae0de6242) | Feb 16, 2024 |
| Dell          | 0D441T A01                  | [13ad4a683c](https://linux-hardware.org/?probe=13ad4a683c) | Feb 15, 2024 |
| Positivo      | POS-MIG31AG                 | [73530ca4c9](https://linux-hardware.org/?probe=73530ca4c9) | Feb 15, 2024 |
| AMD           | A88DA                       | [89ca695711](https://linux-hardware.org/?probe=89ca695711) | Feb 14, 2024 |
| ASUSTek       | H81M-D                      | [9df4273ea0](https://linux-hardware.org/?probe=9df4273ea0) | Feb 14, 2024 |
| Acer          | Aspire TC-1660 V:1.1        | [1c0656fae9](https://linux-hardware.org/?probe=1c0656fae9) | Feb 14, 2024 |
| ECS           | G31T-M7                     | [7a7105d6d8](https://linux-hardware.org/?probe=7a7105d6d8) | Feb 14, 2024 |
| Unknown       | Unknown                     | [599636c242](https://linux-hardware.org/?probe=599636c242) | Feb 12, 2024 |
| Pegatron      | 2AC3                        | [a9575c488b](https://linux-hardware.org/?probe=a9575c488b) | Feb 11, 2024 |
| ASUSTek       | P8P67 PRO                   | [5b06c8344c](https://linux-hardware.org/?probe=5b06c8344c) | Feb 11, 2024 |
| ASUSTek       | P5B                         | [3b213fb567](https://linux-hardware.org/?probe=3b213fb567) | Feb 10, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | [9f43349b7d](https://linux-hardware.org/?probe=9f43349b7d) | Feb 10, 2024 |
| HP            | 3647h                       | [f504108ab7](https://linux-hardware.org/?probe=f504108ab7) | Feb 10, 2024 |
| MSI           | H81M-E33                    | [df8bed98ed](https://linux-hardware.org/?probe=df8bed98ed) | Feb 10, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [7fbd70f2fa](https://linux-hardware.org/?probe=7fbd70f2fa) | Feb 10, 2024 |
| Positivo      | POS-PIG41BAG                | [ad94b1b798](https://linux-hardware.org/?probe=ad94b1b798) | Feb 10, 2024 |
| HP            | 3646h                       | [711bc33a9e](https://linux-hardware.org/?probe=711bc33a9e) | Feb 10, 2024 |
| ASRock        | N68-GS                      | [06f147ad72](https://linux-hardware.org/?probe=06f147ad72) | Feb 09, 2024 |
| Gigabyte      | B75M-D3V                    | [142b258a2b](https://linux-hardware.org/?probe=142b258a2b) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [1e2d466f1b](https://linux-hardware.org/?probe=1e2d466f1b) | Feb 08, 2024 |
| ASUSTek       | PRIME Z370-A                | [a63089827b](https://linux-hardware.org/?probe=a63089827b) | Feb 08, 2024 |
| ASUSTek       | A68HM-PLUS                  | [214df7602f](https://linux-hardware.org/?probe=214df7602f) | Feb 07, 2024 |
| ASRock        | P5B-DE                      | [34550c52b4](https://linux-hardware.org/?probe=34550c52b4) | Feb 05, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c2ec630f3d](https://linux-hardware.org/?probe=c2ec630f3d) | Feb 04, 2024 |
| HP            | 339A                        | [e8e666af64](https://linux-hardware.org/?probe=e8e666af64) | Feb 02, 2024 |
| HP            | 18E7                        | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| Dell          | 0WMJ54 A00                  | [d6c3c89e3d](https://linux-hardware.org/?probe=d6c3c89e3d) | Feb 02, 2024 |
| Dell          | 0215PR A05                  | [05183a71ef](https://linux-hardware.org/?probe=05183a71ef) | Feb 01, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [c83dcb11ca](https://linux-hardware.org/?probe=c83dcb11ca) | Jan 31, 2024 |
| ASUSTek       | M5A97 R2.0                  | [bf9814808f](https://linux-hardware.org/?probe=bf9814808f) | Jan 31, 2024 |
| HP            | 8B3C A                      | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [2a526e4632](https://linux-hardware.org/?probe=2a526e4632) | Jan 30, 2024 |
| Gigabyte      | X570 GAMING X               | [3418c8d84c](https://linux-hardware.org/?probe=3418c8d84c) | Jan 30, 2024 |
| Dell          | 0GDG8Y A00                  | [9cbabba588](https://linux-hardware.org/?probe=9cbabba588) | Jan 29, 2024 |
| AZW           | MINI S 10                   | [d707319ed7](https://linux-hardware.org/?probe=d707319ed7) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c9d5d0fa7b](https://linux-hardware.org/?probe=c9d5d0fa7b) | Jan 29, 2024 |
| Dell          | 0J3C2F A00                  | [95ae5646c8](https://linux-hardware.org/?probe=95ae5646c8) | Jan 29, 2024 |
| HP            | 3396                        | [b59e0b4023](https://linux-hardware.org/?probe=b59e0b4023) | Jan 29, 2024 |
| Gigabyte      | EP45T-UD3R                  | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| ASRock        | B760M-HDV/M.2 D4            | [56ef6ba880](https://linux-hardware.org/?probe=56ef6ba880) | Jan 28, 2024 |
| ASRock        | B450 Gaming K4              | [9cee6b0a5b](https://linux-hardware.org/?probe=9cee6b0a5b) | Jan 27, 2024 |
| ASRock        | H470 Phantom Gaming 4       | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | 945GCM-S2L                  | [4490f8e838](https://linux-hardware.org/?probe=4490f8e838) | Jan 27, 2024 |
| HP            | 82F2 A01                    | [437bec28fa](https://linux-hardware.org/?probe=437bec28fa) | Jan 26, 2024 |
| Gigabyte      | B550M DS3H                  | [347b980bdf](https://linux-hardware.org/?probe=347b980bdf) | Jan 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ff7fd4d2cd](https://linux-hardware.org/?probe=ff7fd4d2cd) | Jan 24, 2024 |
| ASUSTek       | PRIME A320M-K               | [5c2e73a06a](https://linux-hardware.org/?probe=5c2e73a06a) | Jan 23, 2024 |
| Gigabyte      | H61M-S1                     | [91f61c4366](https://linux-hardware.org/?probe=91f61c4366) | Jan 23, 2024 |
| Intel         | Unknown                     | [8427ffd0dc](https://linux-hardware.org/?probe=8427ffd0dc) | Jan 23, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [97f9705158](https://linux-hardware.org/?probe=97f9705158) | Jan 22, 2024 |
| HP            | 18E5                        | [69ba380344](https://linux-hardware.org/?probe=69ba380344) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ec963a72d8](https://linux-hardware.org/?probe=ec963a72d8) | Jan 21, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [af055c48ff](https://linux-hardware.org/?probe=af055c48ff) | Jan 21, 2024 |
| Intel         | DZ77GA-70K AAG39009-500     | [cba7125977](https://linux-hardware.org/?probe=cba7125977) | Jan 20, 2024 |
| Dell          | 042P49 A02                  | [366d017089](https://linux-hardware.org/?probe=366d017089) | Jan 20, 2024 |
| ASUSTek       | PRIME A320M-K               | [58be81f7c1](https://linux-hardware.org/?probe=58be81f7c1) | Jan 20, 2024 |
| Gigabyte      | A320M-S2H-CF                | [39cd221e89](https://linux-hardware.org/?probe=39cd221e89) | Jan 20, 2024 |
| HP            | 8055                        | [5e6a445b12](https://linux-hardware.org/?probe=5e6a445b12) | Jan 19, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD           | [8d2bc7b076](https://linux-hardware.org/?probe=8d2bc7b076) | Jan 18, 2024 |
| Biostar       | A770E                       | [a149b3aeb6](https://linux-hardware.org/?probe=a149b3aeb6) | Jan 17, 2024 |
| ASUSTek       | Z97-DELUXE                  | [f414f21db4](https://linux-hardware.org/?probe=f414f21db4) | Jan 16, 2024 |
| ASUSTek       | H81M-K                      | [c1f78ee398](https://linux-hardware.org/?probe=c1f78ee398) | Jan 16, 2024 |
| MSI           | A320M-A PRO                 | [4f2655db6f](https://linux-hardware.org/?probe=4f2655db6f) | Jan 14, 2024 |
| Positivo      | POS-EINM10CB POSITIVO       | [ed11587f82](https://linux-hardware.org/?probe=ed11587f82) | Jan 14, 2024 |
| Gigabyte      | EX58-UD3R                   | [b62ae21449](https://linux-hardware.org/?probe=b62ae21449) | Jan 13, 2024 |
| Gigabyte      | H510M H V2                  | [1340d91b43](https://linux-hardware.org/?probe=1340d91b43) | Jan 13, 2024 |
| Dell          | 0W2F8G A01                  | [959d868bbf](https://linux-hardware.org/?probe=959d868bbf) | Jan 13, 2024 |
| Gigabyte      | H97M-Gaming 3               | [6230f1ef11](https://linux-hardware.org/?probe=6230f1ef11) | Jan 12, 2024 |
| MSI           | B450M-A PRO MAX             | [50ca06fa28](https://linux-hardware.org/?probe=50ca06fa28) | Jan 11, 2024 |
| ASUSTek       | PRIME Z270-P                | [bf8ac62321](https://linux-hardware.org/?probe=bf8ac62321) | Jan 11, 2024 |
| Intel         | H81                         | [1a1c6de235](https://linux-hardware.org/?probe=1a1c6de235) | Jan 10, 2024 |
| ASRock        | Q1900B-ITX                  | [610dfd5b71](https://linux-hardware.org/?probe=610dfd5b71) | Jan 10, 2024 |
| MSI           | 970A-G43                    | [00e0cf9c8d](https://linux-hardware.org/?probe=00e0cf9c8d) | Jan 09, 2024 |
| OEM           | B75 Ver:1.41                | [5466b2e4af](https://linux-hardware.org/?probe=5466b2e4af) | Jan 08, 2024 |
| Lenovo        | ThinkCentre M72e 0896A2G    | [b77ad754ae](https://linux-hardware.org/?probe=b77ad754ae) | Jan 08, 2024 |
| Gigabyte      | B450M K-CF                  | [6ffbab86cc](https://linux-hardware.org/?probe=6ffbab86cc) | Jan 07, 2024 |
| Dell          | 00V62H A01                  | [6fcf0891d9](https://linux-hardware.org/?probe=6fcf0891d9) | Jan 07, 2024 |
| Gigabyte      | MZBSWAP-00                  | [eb3700b576](https://linux-hardware.org/?probe=eb3700b576) | Jan 06, 2024 |
| Shenzhen M... | F7BFC                       | [59d6a69f30](https://linux-hardware.org/?probe=59d6a69f30) | Jan 05, 2024 |
| Shenzhen M... | F7BFC                       | [d8ed7241cb](https://linux-hardware.org/?probe=d8ed7241cb) | Jan 05, 2024 |
| Intel         | JSL MRD                     | [8b1f990d75](https://linux-hardware.org/?probe=8b1f990d75) | Jan 05, 2024 |
| Acer          | Veriton M2630G V:1.0        | [40d6bf6d97](https://linux-hardware.org/?probe=40d6bf6d97) | Jan 05, 2024 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [d53af9a54d](https://linux-hardware.org/?probe=d53af9a54d) | Jan 03, 2024 |
| ASUSTek       | Maximus V GENE              | [e62026b868](https://linux-hardware.org/?probe=e62026b868) | Jan 02, 2024 |
| ASUSTek       | M2N68-AM SE2                | [553bcade60](https://linux-hardware.org/?probe=553bcade60) | Jan 01, 2024 |
| Gigabyte      | G41M-Combo                  | [0a6df1d55f](https://linux-hardware.org/?probe=0a6df1d55f) | Dec 28, 2023 |
| Intel         | H61                         | [baec7a3074](https://linux-hardware.org/?probe=baec7a3074) | Dec 28, 2023 |
| MSI           | MS-B9311                    | [424154cf65](https://linux-hardware.org/?probe=424154cf65) | Dec 28, 2023 |
| Acer          | Predator Orion PO5-620      | [2d7731ff10](https://linux-hardware.org/?probe=2d7731ff10) | Dec 26, 2023 |
| HP            | 82F1                        | [86959f8199](https://linux-hardware.org/?probe=86959f8199) | Dec 24, 2023 |
| ASUSTek       | P5GC-MX/1333                | [a95c11e27b](https://linux-hardware.org/?probe=a95c11e27b) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a84743b247](https://linux-hardware.org/?probe=a84743b247) | Dec 23, 2023 |
| Foxconn       | 2ABF                        | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [739d4b0840](https://linux-hardware.org/?probe=739d4b0840) | Dec 23, 2023 |
| Dell          | 0X7841                      | [3757ec7f5f](https://linux-hardware.org/?probe=3757ec7f5f) | Dec 22, 2023 |
| ASUSTek       | P7H55-M LE                  | [d15476594e](https://linux-hardware.org/?probe=d15476594e) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [be8f1bf021](https://linux-hardware.org/?probe=be8f1bf021) | Dec 22, 2023 |
| HP            | 2B28                        | [a3c79770af](https://linux-hardware.org/?probe=a3c79770af) | Dec 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [2675cca8c2](https://linux-hardware.org/?probe=2675cca8c2) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| Gigabyte      | 970-GAMING                  | [403d617fdd](https://linux-hardware.org/?probe=403d617fdd) | Dec 19, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | [ee9b8f604a](https://linux-hardware.org/?probe=ee9b8f604a) | Dec 19, 2023 |
| Dell          | 0T10XW A00                  | [ffff088d9c](https://linux-hardware.org/?probe=ffff088d9c) | Dec 18, 2023 |
| Foxconn       | 2ABF                        | [907abd30c7](https://linux-hardware.org/?probe=907abd30c7) | Dec 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5c8981cf69](https://linux-hardware.org/?probe=5c8981cf69) | Dec 17, 2023 |
| ASRock        | 970M Pro3                   | [1e7fb2b8d8](https://linux-hardware.org/?probe=1e7fb2b8d8) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [41fd53bbff](https://linux-hardware.org/?probe=41fd53bbff) | Dec 16, 2023 |
| HP            | 3647h                       | [4feaf76045](https://linux-hardware.org/?probe=4feaf76045) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [72b7f2d771](https://linux-hardware.org/?probe=72b7f2d771) | Dec 16, 2023 |
| Gigabyte      | P55A-UD3                    | [485f360521](https://linux-hardware.org/?probe=485f360521) | Dec 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [a2e31b8b20](https://linux-hardware.org/?probe=a2e31b8b20) | Dec 15, 2023 |
| ASUSTek       | H81M-CS/BR                  | [39094226f9](https://linux-hardware.org/?probe=39094226f9) | Dec 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [8939c99ccb](https://linux-hardware.org/?probe=8939c99ccb) | Dec 15, 2023 |
| ASUSTek       | PRIME B460M-A               | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| HP            | 1495                        | [bd97989dd8](https://linux-hardware.org/?probe=bd97989dd8) | Dec 14, 2023 |
| ASUSTek       | PRIME H270-PRO              | [b701b34038](https://linux-hardware.org/?probe=b701b34038) | Dec 14, 2023 |
| ASRock        | G41M-VS3                    | [313b058c8c](https://linux-hardware.org/?probe=313b058c8c) | Dec 14, 2023 |
| ASRock        | AB350M-HDV                  | [945274527c](https://linux-hardware.org/?probe=945274527c) | Dec 13, 2023 |
| HP            | 18E5                        | [8195da7520](https://linux-hardware.org/?probe=8195da7520) | Dec 13, 2023 |
| Positivo      | POS-PIH81DL                 | [55cf834e17](https://linux-hardware.org/?probe=55cf834e17) | Dec 13, 2023 |
| HP            | 8169                        | [e0549dcc03](https://linux-hardware.org/?probe=e0549dcc03) | Dec 12, 2023 |
| MSI           | A88XM GAMING                | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [0e87f04695](https://linux-hardware.org/?probe=0e87f04695) | Dec 12, 2023 |
| Dell          | 0TNDVR A00                  | [4a4ab03bc7](https://linux-hardware.org/?probe=4a4ab03bc7) | Dec 11, 2023 |
| Dell          | 0GXM1W A00                  | [1b4243a8d7](https://linux-hardware.org/?probe=1b4243a8d7) | Dec 11, 2023 |
| Gigabyte      | Z77-DS3H                    | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| Gigabyte      | H310M DS2 x.x               | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [e96b9306cb](https://linux-hardware.org/?probe=e96b9306cb) | Dec 10, 2023 |
| HP            | 2B29                        | [6fb328f58e](https://linux-hardware.org/?probe=6fb328f58e) | Dec 10, 2023 |
| HP            | 3047h                       | [b4e9ee347f](https://linux-hardware.org/?probe=b4e9ee347f) | Dec 10, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | [5c1ffcfbe3](https://linux-hardware.org/?probe=5c1ffcfbe3) | Dec 09, 2023 |
| MSI           | B450-A PRO MAX              | [c576c4fbae](https://linux-hardware.org/?probe=c576c4fbae) | Dec 09, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [a4eb4e410e](https://linux-hardware.org/?probe=a4eb4e410e) | Dec 08, 2023 |
| Biostar       | A520MH                      | [de9fc0f8f2](https://linux-hardware.org/?probe=de9fc0f8f2) | Dec 07, 2023 |
| Dell          | 0HN7XN A01                  | [986d7f4d8f](https://linux-hardware.org/?probe=986d7f4d8f) | Dec 07, 2023 |
| HP            | 21B4 A01                    | [a8f5a67f32](https://linux-hardware.org/?probe=a8f5a67f32) | Dec 07, 2023 |
| Foxconn       | 2A8C                        | [2a4412d268](https://linux-hardware.org/?probe=2a4412d268) | Dec 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1f2c85d176](https://linux-hardware.org/?probe=1f2c85d176) | Dec 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f15eca360f](https://linux-hardware.org/?probe=f15eca360f) | Dec 06, 2023 |
| ASUSTek       | PRIME A520M-A II            | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| Gigabyte      | Z68XP-UD4                   | [3cdd72e242](https://linux-hardware.org/?probe=3cdd72e242) | Dec 05, 2023 |
| Foxconn       | 2ABF                        | [9478c73013](https://linux-hardware.org/?probe=9478c73013) | Dec 05, 2023 |
| Dell          | 02N3WF A03                  | [2974cc160f](https://linux-hardware.org/?probe=2974cc160f) | Dec 05, 2023 |
| Acer          | Veriton S6620G v1.0         | [34095bbfed](https://linux-hardware.org/?probe=34095bbfed) | Dec 04, 2023 |
| HP            | 1998                        | [50a48ad374](https://linux-hardware.org/?probe=50a48ad374) | Dec 04, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f013a81cbb](https://linux-hardware.org/?probe=f013a81cbb) | Dec 03, 2023 |
| ASRock        | B450 Gaming K4              | [b877f8ccda](https://linux-hardware.org/?probe=b877f8ccda) | Dec 03, 2023 |
| HP            | 3397                        | [b6c4db2738](https://linux-hardware.org/?probe=b6c4db2738) | Dec 03, 2023 |
| HP            | 8169                        | [6bdddabb7f](https://linux-hardware.org/?probe=6bdddabb7f) | Dec 03, 2023 |
| ASUSTek       | P7P55 LX                    | [0d59473ae1](https://linux-hardware.org/?probe=0d59473ae1) | Dec 02, 2023 |
| Intel         | X99                         | [e96bed5f38](https://linux-hardware.org/?probe=e96bed5f38) | Dec 02, 2023 |
| MSI           | B85M-E43 DASH               | [b9caa2d56f](https://linux-hardware.org/?probe=b9caa2d56f) | Dec 02, 2023 |
| ASUSTek       | H81M-K                      | [8f5c7fb36e](https://linux-hardware.org/?probe=8f5c7fb36e) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [5f195d4731](https://linux-hardware.org/?probe=5f195d4731) | Dec 02, 2023 |
| Dell          | 0T10XW A02                  | [ddb5b7cd64](https://linux-hardware.org/?probe=ddb5b7cd64) | Dec 01, 2023 |
| HP            | 8459                        | [b7a22ecb3f](https://linux-hardware.org/?probe=b7a22ecb3f) | Dec 01, 2023 |
| Intel         | DG41RQ AAE54511-205         | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [ed158c0464](https://linux-hardware.org/?probe=ed158c0464) | Dec 01, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [436f0406e4](https://linux-hardware.org/?probe=436f0406e4) | Dec 01, 2023 |
| Gigabyte      | B250-D3A-CF                 | [5d3de45ec6](https://linux-hardware.org/?probe=5d3de45ec6) | Dec 01, 2023 |
| Intel         | X99H                        | [147f088343](https://linux-hardware.org/?probe=147f088343) | Dec 01, 2023 |
| ASRock        | Z790 Taichi                 | [915505c787](https://linux-hardware.org/?probe=915505c787) | Nov 30, 2023 |
| Gigabyte      | H61M-S1                     | [cc54ea37ef](https://linux-hardware.org/?probe=cc54ea37ef) | Nov 30, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [3630fd2945](https://linux-hardware.org/?probe=3630fd2945) | Nov 30, 2023 |
| AZW           | U59                         | [eccee157da](https://linux-hardware.org/?probe=eccee157da) | Nov 30, 2023 |
| Gigabyte      | H81M-S2H                    | [b23f24b006](https://linux-hardware.org/?probe=b23f24b006) | Nov 30, 2023 |
| HP            | 1495                        | [9dcb53a8c2](https://linux-hardware.org/?probe=9dcb53a8c2) | Nov 30, 2023 |
| Gigabyte      | B75M-D3H                    | [6a3776da6b](https://linux-hardware.org/?probe=6a3776da6b) | Nov 29, 2023 |
| ASUSTek       | PRIME A320M-K               | [1537766927](https://linux-hardware.org/?probe=1537766927) | Nov 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [1b2c06817f](https://linux-hardware.org/?probe=1b2c06817f) | Nov 29, 2023 |
| Unknown       | Intel BayTrail Series R1... | [6ab4075642](https://linux-hardware.org/?probe=6ab4075642) | Nov 29, 2023 |
| HP            | 8053                        | [6d6877e008](https://linux-hardware.org/?probe=6d6877e008) | Nov 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [fc4e66ac12](https://linux-hardware.org/?probe=fc4e66ac12) | Nov 29, 2023 |
| MSI           | A320M-A PRO                 | [96af3871d2](https://linux-hardware.org/?probe=96af3871d2) | Nov 29, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [a06c08c462](https://linux-hardware.org/?probe=a06c08c462) | Nov 28, 2023 |
| ASUSTek       | PRIME A320M-K               | [7c53518c08](https://linux-hardware.org/?probe=7c53518c08) | Nov 28, 2023 |
| Gigabyte      | H310M DS2                   | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| HP            | 1497                        | [6cd2fea9bd](https://linux-hardware.org/?probe=6cd2fea9bd) | Nov 28, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [9e6c582721](https://linux-hardware.org/?probe=9e6c582721) | Nov 28, 2023 |
| Gigabyte      | G31-S3G                     | [895a8554b4](https://linux-hardware.org/?probe=895a8554b4) | Nov 28, 2023 |
| HP            | 18E5                        | [a9c04bd2c7](https://linux-hardware.org/?probe=a9c04bd2c7) | Nov 28, 2023 |
| Biostar       | H310MHP                     | [58282ae6c7](https://linux-hardware.org/?probe=58282ae6c7) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [7c4bb8dad1](https://linux-hardware.org/?probe=7c4bb8dad1) | Nov 28, 2023 |
| Gigabyte      | P67A-D3-B3                  | [fc4a8c9532](https://linux-hardware.org/?probe=fc4a8c9532) | Nov 27, 2023 |
| Lenovo        | ThinkCentre M58p 6137A1G    | [fafec0e338](https://linux-hardware.org/?probe=fafec0e338) | Nov 27, 2023 |
| ASRock        | H510M-HVS R2.0              | [e8867e4bb9](https://linux-hardware.org/?probe=e8867e4bb9) | Nov 27, 2023 |
| Gigabyte      | G41MT-S2P                   | [0ff86eddc6](https://linux-hardware.org/?probe=0ff86eddc6) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8885a17766](https://linux-hardware.org/?probe=8885a17766) | Nov 27, 2023 |
| Intel         | H61                         | [97a16fcd1b](https://linux-hardware.org/?probe=97a16fcd1b) | Nov 27, 2023 |
| Dell          | 0CU409                      | [328adb4fd0](https://linux-hardware.org/?probe=328adb4fd0) | Nov 27, 2023 |
| Intel         | X99H                        | [2cbd1213a8](https://linux-hardware.org/?probe=2cbd1213a8) | Nov 27, 2023 |
| HP            | 83EE                        | [4a9e67adc6](https://linux-hardware.org/?probe=4a9e67adc6) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dda972d27c](https://linux-hardware.org/?probe=dda972d27c) | Nov 26, 2023 |
| Dell          | 07KY25 A01                  | [98134987bb](https://linux-hardware.org/?probe=98134987bb) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | [8c0edc3315](https://linux-hardware.org/?probe=8c0edc3315) | Nov 26, 2023 |
| Dell          | 0WR7PY A01                  | [cceb19120f](https://linux-hardware.org/?probe=cceb19120f) | Nov 26, 2023 |
| MSI           | MS-B1711                    | [963341bb09](https://linux-hardware.org/?probe=963341bb09) | Nov 26, 2023 |
| ASRock        | 4X4-4000 Series             | [d9c6907311](https://linux-hardware.org/?probe=d9c6907311) | Nov 26, 2023 |
| ASRock        | 970A-G                      | [aabcb223d0](https://linux-hardware.org/?probe=aabcb223d0) | Nov 26, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2d09c86fa7](https://linux-hardware.org/?probe=2d09c86fa7) | Nov 26, 2023 |
| ASUSTek       | P8Z77-M                     | [2009f6493b](https://linux-hardware.org/?probe=2009f6493b) | Nov 26, 2023 |
| Foxconn       | 2ADA                        | [0f5aa8a55b](https://linux-hardware.org/?probe=0f5aa8a55b) | Nov 26, 2023 |
| Gigabyte      | B75M-D3H                    | [454b211624](https://linux-hardware.org/?probe=454b211624) | Nov 25, 2023 |
| Minix         | H61M-USB3 V1.2              | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| Dell          | 0K83V0 A00                  | [0ffd410841](https://linux-hardware.org/?probe=0ffd410841) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e8b656513](https://linux-hardware.org/?probe=4e8b656513) | Nov 24, 2023 |
| MSI           | Z87-G41 PC Mate             | [a56a424940](https://linux-hardware.org/?probe=a56a424940) | Nov 24, 2023 |
| ASUSTek       | P8H77-M LE                  | [39919b75ba](https://linux-hardware.org/?probe=39919b75ba) | Nov 24, 2023 |
| MSI           | A68HM-E33 V2                | [e257380edc](https://linux-hardware.org/?probe=e257380edc) | Nov 23, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| ASRock        | A320M-HDV R4.0              | [a67ae23c5a](https://linux-hardware.org/?probe=a67ae23c5a) | Nov 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | [eff4442629](https://linux-hardware.org/?probe=eff4442629) | Nov 22, 2023 |
| Gigabyte      | H510M H                     | [078c28606a](https://linux-hardware.org/?probe=078c28606a) | Nov 21, 2023 |
| Gigabyte      | B75M-D3H                    | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| ECS           | H61H2-M2                    | [29293282c2](https://linux-hardware.org/?probe=29293282c2) | Nov 20, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [6ed1f31ed3](https://linux-hardware.org/?probe=6ed1f31ed3) | Nov 20, 2023 |
| HP            | 89B5 A                      | [4c228a49ce](https://linux-hardware.org/?probe=4c228a49ce) | Nov 20, 2023 |
| ASRock        | B660M-STX                   | [883a70813a](https://linux-hardware.org/?probe=883a70813a) | Nov 19, 2023 |
| ASUSTek       | PRIME H510M-K               | [4243816d27](https://linux-hardware.org/?probe=4243816d27) | Nov 19, 2023 |
| ASUSTek       | M2NPV-VM                    | [be4bd9aeaf](https://linux-hardware.org/?probe=be4bd9aeaf) | Nov 18, 2023 |
| HP            | 8055                        | [1125d976fc](https://linux-hardware.org/?probe=1125d976fc) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff84b6e035](https://linux-hardware.org/?probe=ff84b6e035) | Nov 17, 2023 |
| ASUSTek       | P5SD2-VM                    | [8fa21e29e3](https://linux-hardware.org/?probe=8fa21e29e3) | Nov 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [63ba7cf0b1](https://linux-hardware.org/?probe=63ba7cf0b1) | Nov 16, 2023 |
| Inventec      | D CLASS A02                 | [e8f9a52206](https://linux-hardware.org/?probe=e8f9a52206) | Nov 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | [5b960b8464](https://linux-hardware.org/?probe=5b960b8464) | Nov 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [160e8325ba](https://linux-hardware.org/?probe=160e8325ba) | Nov 15, 2023 |
| Unknown       | T3 MRD                      | [f4a73d26e0](https://linux-hardware.org/?probe=f4a73d26e0) | Nov 15, 2023 |
| ASUSTek       | P5GC-MX/CKD/SI              | [08053c4143](https://linux-hardware.org/?probe=08053c4143) | Nov 15, 2023 |
| MSI           | Z97-G43                     | [ea16582cb2](https://linux-hardware.org/?probe=ea16582cb2) | Nov 14, 2023 |
| MSI           | A88X-G45 GAMING             | [5ab91132ea](https://linux-hardware.org/?probe=5ab91132ea) | Nov 14, 2023 |
| HP            | 09F0h                       | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [cccbd25b73](https://linux-hardware.org/?probe=cccbd25b73) | Nov 12, 2023 |
| Dell          | 0KWVT8 A03                  | [fcc17bd8a1](https://linux-hardware.org/?probe=fcc17bd8a1) | Nov 12, 2023 |
| HP            | 1850                        | [117ab7ea0d](https://linux-hardware.org/?probe=117ab7ea0d) | Nov 11, 2023 |
| Gigabyte      | Z77-D3H                     | [9c852b1f0b](https://linux-hardware.org/?probe=9c852b1f0b) | Nov 11, 2023 |
| Minix         | NEO Z83-4 V1.5              | [3623dfcb88](https://linux-hardware.org/?probe=3623dfcb88) | Nov 10, 2023 |
| Intel         | DG35EC AAE29266-210         | [fe0e055f82](https://linux-hardware.org/?probe=fe0e055f82) | Nov 10, 2023 |
| HP            | 339A                        | [7be77c764f](https://linux-hardware.org/?probe=7be77c764f) | Nov 09, 2023 |
| MSI           | A320M-A PRO                 | [9f16fd11b7](https://linux-hardware.org/?probe=9f16fd11b7) | Nov 09, 2023 |
| Gigabyte      | H110M-S2H-CF                | [10f68961cf](https://linux-hardware.org/?probe=10f68961cf) | Nov 08, 2023 |
| Gigabyte      | G41MT-S2                    | [c301ae970c](https://linux-hardware.org/?probe=c301ae970c) | Nov 08, 2023 |
| Dell          | 082WXT A01                  | [41e56ed8e4](https://linux-hardware.org/?probe=41e56ed8e4) | Nov 08, 2023 |
| HP            | 339A                        | [cdcbe8d47d](https://linux-hardware.org/?probe=cdcbe8d47d) | Nov 07, 2023 |
| Foxconn       | 2AAF                        | [fc483856a6](https://linux-hardware.org/?probe=fc483856a6) | Nov 07, 2023 |
| ASUSTek       | H81M-K                      | [3de6cf8221](https://linux-hardware.org/?probe=3de6cf8221) | Nov 07, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [c376116add](https://linux-hardware.org/?probe=c376116add) | Nov 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| HP            | 802F                        | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f070e73453](https://linux-hardware.org/?probe=f070e73453) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Acer          | Aspire M1920                | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| MSI           | H110M PRO-D                 | [da5c3ffb7e](https://linux-hardware.org/?probe=da5c3ffb7e) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| Gigabyte      | B75M-HD3                    | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| Intel         | B75                         | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| ASUSTek       | PRIME B250-PRO              | [ac060a5eb6](https://linux-hardware.org/?probe=ac060a5eb6) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [31d6b19c8d](https://linux-hardware.org/?probe=31d6b19c8d) | Oct 29, 2023 |
| Koloe         | X58                         | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| ASRock        | B450 Steel Legend           | [21beb00969](https://linux-hardware.org/?probe=21beb00969) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| Gigabyte      | Z370M D3H-CF                | [80b6c027b0](https://linux-hardware.org/?probe=80b6c027b0) | Oct 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [9d662bd187](https://linux-hardware.org/?probe=9d662bd187) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M LX3                | [d3dacafdc2](https://linux-hardware.org/?probe=d3dacafdc2) | Oct 26, 2023 |
| Dell          | 03NJH0 A01                  | [dbb152a219](https://linux-hardware.org/?probe=dbb152a219) | Oct 26, 2023 |
| MSI           | H110M PRO-VD                | [b62701c032](https://linux-hardware.org/?probe=b62701c032) | Oct 25, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| EPSON DIRE... | AT992E                      | [b61468f9c5](https://linux-hardware.org/?probe=b61468f9c5) | Oct 24, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| MSI           | PRO Z690-P DDR4             | [35e54833e8](https://linux-hardware.org/?probe=35e54833e8) | Oct 23, 2023 |
| HP            | 3397                        | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [3e46064143](https://linux-hardware.org/?probe=3e46064143) | Oct 22, 2023 |
| ASUSTek       | H170 PRO GAMING             | [859edb18bd](https://linux-hardware.org/?probe=859edb18bd) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| MSI           | G41TM-P31                   | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| Intel         | DH55HC AAE70933-505         | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| ASUSTek       | PRIME H510M-A               | [04e9833b48](https://linux-hardware.org/?probe=04e9833b48) | Oct 18, 2023 |
| Acer          | Veriton X2660G              | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| ASRock        | X470 Master SLI/ac          | [9258f94300](https://linux-hardware.org/?probe=9258f94300) | Oct 17, 2023 |
| Shenzhen M... | F7BSC                       | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| MSI           | Z97A GAMING 7               | [8af7152ba5](https://linux-hardware.org/?probe=8af7152ba5) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Gigabyte      | GA-E350N-USB3               | [62f5ab12ea](https://linux-hardware.org/?probe=62f5ab12ea) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| PCWare        | IPMH61R1                    | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| ASUSTek       | P8Q77-M                     | [ed4ca29c66](https://linux-hardware.org/?probe=ed4ca29c66) | Oct 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [babe25d4ce](https://linux-hardware.org/?probe=babe25d4ce) | Oct 14, 2023 |
| HP            | 1495                        | [e524318d58](https://linux-hardware.org/?probe=e524318d58) | Oct 13, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| ASRock        | A320M-HDV R4.0              | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K II            | [a3401cc125](https://linux-hardware.org/?probe=a3401cc125) | Oct 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| Dell          | 0M5DCD A00                  | [30d2522c95](https://linux-hardware.org/?probe=30d2522c95) | Oct 07, 2023 |
| Intel         | H61                         | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| ASRock        | N68C-GS FX                  | [cfafd2008d](https://linux-hardware.org/?probe=cfafd2008d) | Oct 07, 2023 |
| MSI           | 09AC                        | [f70ac0139f](https://linux-hardware.org/?probe=f70ac0139f) | Oct 07, 2023 |
| AZW           | Green G4 10                 | [d8fb758dec](https://linux-hardware.org/?probe=d8fb758dec) | Oct 07, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| Lenovo        | ThinkCentre xxx 7090A17     | [669bc2a016](https://linux-hardware.org/?probe=669bc2a016) | Oct 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [bc448fbb82](https://linux-hardware.org/?probe=bc448fbb82) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| HP            | 3397                        | [e77e1b6391](https://linux-hardware.org/?probe=e77e1b6391) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| HP            | 1825                        | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| ECS           | H61H2-MV                    | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| Lenovo        | NOK                         | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| HP            | 3646h                       | [f39e9c8741](https://linux-hardware.org/?probe=f39e9c8741) | Oct 04, 2023 |
| Intel         | JSL MRD                     | [5a4bfcaba3](https://linux-hardware.org/?probe=5a4bfcaba3) | Oct 03, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| Dell          | 0Y3R3K A03                  | [0675277f70](https://linux-hardware.org/?probe=0675277f70) | Oct 03, 2023 |
| Dell          | 0GXM1W A00                  | [fe83d524fb](https://linux-hardware.org/?probe=fe83d524fb) | Oct 02, 2023 |
| AZW           | MINI S 10                   | [13e3a733fd](https://linux-hardware.org/?probe=13e3a733fd) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| ASUSTek       | B85M-G                      | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| ASUSTek       | H110M-R                     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| ASUSTek       | P5B-E Plus                  | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| AZW           | MINI S 10                   | [e065b9c701](https://linux-hardware.org/?probe=e065b9c701) | Sep 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [d0fea1d86b](https://linux-hardware.org/?probe=d0fea1d86b) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| Lenovo        | H410                        | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a1ef1eb6e6](https://linux-hardware.org/?probe=a1ef1eb6e6) | Sep 28, 2023 |
| ASUSTek       | D700MD                      | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| Pegatron      | EVANS                       | [b9347254b0](https://linux-hardware.org/?probe=b9347254b0) | Sep 25, 2023 |
| ASRock        | X370 Pro4                   | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| Biostar       | B550MH                      | [4ef9bbad17](https://linux-hardware.org/?probe=4ef9bbad17) | Sep 24, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [4c6071b20c](https://linux-hardware.org/?probe=4c6071b20c) | Sep 24, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [c0e3bef058](https://linux-hardware.org/?probe=c0e3bef058) | Sep 24, 2023 |
| ASUSTek       | Z97-C                       | [e4c1f075b9](https://linux-hardware.org/?probe=e4c1f075b9) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| Shuttle       | XS36V                       | [dbcb5658e4](https://linux-hardware.org/?probe=dbcb5658e4) | Sep 23, 2023 |
| ASUSTek       | P7P55-M                     | [f5b912e122](https://linux-hardware.org/?probe=f5b912e122) | Sep 22, 2023 |
| Positivo      | POS-AG31AP                  | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| Dell          | 0KRC95 A00                  | [61ae2b85c5](https://linux-hardware.org/?probe=61ae2b85c5) | Sep 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [182384fdaa](https://linux-hardware.org/?probe=182384fdaa) | Sep 20, 2023 |
| MSI           | Indio                       | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Biostar       | B550GTQ                     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [6f4fafb23f](https://linux-hardware.org/?probe=6f4fafb23f) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [9c94944d56](https://linux-hardware.org/?probe=9c94944d56) | Sep 18, 2023 |
| ASUSTek       | P5GC-MX/1333                | [232bd09926](https://linux-hardware.org/?probe=232bd09926) | Sep 17, 2023 |
| MSI           | B450M MORTAR MAX            | [beaa4e5554](https://linux-hardware.org/?probe=beaa4e5554) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| Intel         | DX79SI AAG28808-602         | [2ccc7fc308](https://linux-hardware.org/?probe=2ccc7fc308) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [bef465f035](https://linux-hardware.org/?probe=bef465f035) | Sep 16, 2023 |
| Intel         | DH61CR AAG14064-204         | [e28e555058](https://linux-hardware.org/?probe=e28e555058) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| HP            | 339A                        | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [dd369f3c60](https://linux-hardware.org/?probe=dd369f3c60) | Sep 15, 2023 |
| Dell          | 073MMW A03                  | [b0fc15849b](https://linux-hardware.org/?probe=b0fc15849b) | Sep 15, 2023 |
| Gigabyte      | B450 AORUS M                | [9b3fc9218b](https://linux-hardware.org/?probe=9b3fc9218b) | Sep 14, 2023 |
| Intel         | H81                         | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Gigabyte      | Z97X-SOC-CF                 | [9c86fc8235](https://linux-hardware.org/?probe=9c86fc8235) | Sep 14, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [33b3749fc5](https://linux-hardware.org/?probe=33b3749fc5) | Sep 14, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| MSI           | B85M-E45                    | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| Packard Be... | MCP73                       | [b47efcac04](https://linux-hardware.org/?probe=b47efcac04) | Sep 13, 2023 |
| HP            | 339A                        | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-K               | [3b15d88a26](https://linux-hardware.org/?probe=3b15d88a26) | Sep 13, 2023 |
| MSI           | A88XM GAMING                | [0b0a88f781](https://linux-hardware.org/?probe=0b0a88f781) | Sep 13, 2023 |
| Pegatron      | 2ACF                        | [2b7e16f244](https://linux-hardware.org/?probe=2b7e16f244) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| MSI           | B450M PRO-VDH               | [c06182cc86](https://linux-hardware.org/?probe=c06182cc86) | Sep 12, 2023 |
| Intel         | H61                         | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| Dell          | 0G254H A00                  | [b41d69b7e2](https://linux-hardware.org/?probe=b41d69b7e2) | Sep 12, 2023 |
| HP            | 82A1                        | [8a68160c22](https://linux-hardware.org/?probe=8a68160c22) | Sep 12, 2023 |
| Dell          | 0G3HR7 A00                  | [ae2dfec1af](https://linux-hardware.org/?probe=ae2dfec1af) | Sep 11, 2023 |
| Unknown       | Unknown                     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Intel         | JSL MRD                     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [9c4e42b171](https://linux-hardware.org/?probe=9c4e42b171) | Sep 11, 2023 |
| HP            | 304Ah                       | [fe71b825fd](https://linux-hardware.org/?probe=fe71b825fd) | Sep 11, 2023 |
| Intel         | H81 V2.3                    | [0673e1f5ed](https://linux-hardware.org/?probe=0673e1f5ed) | Sep 11, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Philco        | DTC-A55                     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| ASUSTek       | PRIME H410M-R               | [962fd46c5c](https://linux-hardware.org/?probe=962fd46c5c) | Sep 11, 2023 |
| MSI           | PRO Z690-A                  | [2c892b26d1](https://linux-hardware.org/?probe=2c892b26d1) | Sep 11, 2023 |
| Gigabyte      | H110M-S2PT-CF               | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| ASRock        | A300M-STX                   | [923e3060e8](https://linux-hardware.org/?probe=923e3060e8) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [91b6565880](https://linux-hardware.org/?probe=91b6565880) | Sep 09, 2023 |
| HP            | 8266                        | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| ASUSTek       | P10S-C Series               | [67829cd702](https://linux-hardware.org/?probe=67829cd702) | Sep 09, 2023 |
| Lenovo        | Annapurna CRB NOK           | [dc4bc20437](https://linux-hardware.org/?probe=dc4bc20437) | Sep 09, 2023 |
| Dell          | 0YJPT1 A00                  | [b16e6f8c25](https://linux-hardware.org/?probe=b16e6f8c25) | Sep 08, 2023 |
| MSI           | H61MA-E35                   | [e64c5d24b0](https://linux-hardware.org/?probe=e64c5d24b0) | Sep 08, 2023 |
| Dell          | 0J37VM A01                  | [cfd16871a7](https://linux-hardware.org/?probe=cfd16871a7) | Sep 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c06ee9858a](https://linux-hardware.org/?probe=c06ee9858a) | Sep 08, 2023 |
| Intel         | H81                         | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| Medion        | H110H4-CM2                  | [184f133a7d](https://linux-hardware.org/?probe=184f133a7d) | Sep 07, 2023 |
| ASRock        | H310CM-HDV                  | [7aa11cd98f](https://linux-hardware.org/?probe=7aa11cd98f) | Sep 07, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| Intel         | DQ67SW AAG12527-310         | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Lenovo        | IdeaCentre K330B            | [a53977eb83](https://linux-hardware.org/?probe=a53977eb83) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Dell          | 0CU409                      | [f5ae8200cf](https://linux-hardware.org/?probe=f5ae8200cf) | Sep 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [07f51e668b](https://linux-hardware.org/?probe=07f51e668b) | Sep 06, 2023 |
| ASRock        | B550M Pro4                  | [afba6fc1eb](https://linux-hardware.org/?probe=afba6fc1eb) | Sep 06, 2023 |
| HP            | 0B54h D                     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Intel         | H61                         | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| Dell          | 0T1D10 A01                  | [97ac9f9de8](https://linux-hardware.org/?probe=97ac9f9de8) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| ASRock        | E35LM1                      | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASRock        | X570M Pro4                  | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| ASUSTek       | P5P43TD/USB3                | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| Dell          | 0J8G6F A03                  | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| ASRock        | B460M-HDV                   | [2380eeae30](https://linux-hardware.org/?probe=2380eeae30) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| OEM           | Intel H81                   | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | PRIME B250M-A               | [02160fded0](https://linux-hardware.org/?probe=02160fded0) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08a80ee482](https://linux-hardware.org/?probe=08a80ee482) | Sep 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [1cc4b106a4](https://linux-hardware.org/?probe=1cc4b106a4) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Dell          | 0D441T A03                  | [3ba5173eb2](https://linux-hardware.org/?probe=3ba5173eb2) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Gigabyte      | X79-UD3                     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| Intel         | H61                         | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| BESSTAR Te... | Cherry Trail CR             | [3ad034200f](https://linux-hardware.org/?probe=3ad034200f) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| HP            | 828A                        | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| ASRock        | B450 Gaming K4              | [96dbf56986](https://linux-hardware.org/?probe=96dbf56986) | Sep 03, 2023 |
| Intel         | H81                         | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| ASUSTek       | M2N                         | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| Gigabyte      | F2A88X-UP4                  | [37bfab5442](https://linux-hardware.org/?probe=37bfab5442) | Sep 02, 2023 |
| Intel         | DQ77KB AAG40294-401         | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | 3646h                       | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4fa68712c5](https://linux-hardware.org/?probe=4fa68712c5) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| HP            | 1497                        | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| MSI           | H81M-P33                    | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Acer          | Aspire TC-875 V:1.0         | [a25ba0bd0c](https://linux-hardware.org/?probe=a25ba0bd0c) | Sep 02, 2023 |
| ASRock        | H570 Steel Legend           | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Foxconn       | 2ABF                        | [f3655da9eb](https://linux-hardware.org/?probe=f3655da9eb) | Sep 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| HP            | 3032h                       | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| HP            | 1632                        | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Gigabyte      | B75M-D3H                    | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| AZW           | U59                         | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| ASUSTek       | H81M2                       | [55dd352412](https://linux-hardware.org/?probe=55dd352412) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Gigabyte      | B85M-D3H                    | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| AOpen         | i65HMx-D R1.04AL            | [aef1de4c53](https://linux-hardware.org/?probe=aef1de4c53) | Sep 01, 2023 |
| Medion        | B250H4-EM                   | [c2e1f2eb0b](https://linux-hardware.org/?probe=c2e1f2eb0b) | Sep 01, 2023 |
| Intel         | SHARKBAY                    | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| MSI           | MS-7390                     | [7115ad031a](https://linux-hardware.org/?probe=7115ad031a) | Sep 01, 2023 |
| Fujitsu       | D3410-B2 S26361-D3410-B2    | [924293e07f](https://linux-hardware.org/?probe=924293e07f) | Sep 01, 2023 |
| MSI           | X99A WORKSTATION            | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 1632                        | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d728ff01da](https://linux-hardware.org/?probe=d728ff01da) | Sep 01, 2023 |
| ASUSTek       | WS X299 SAGE                | [a01568da7d](https://linux-hardware.org/?probe=a01568da7d) | Aug 31, 2023 |
| HP            | 3397                        | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Positivo      | ONE500                      | [1e84a5bf44](https://linux-hardware.org/?probe=1e84a5bf44) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Shenzhen M... | F6BFC                       | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| Foxconn       | G41S/G41S-K                 | [8ad8098315](https://linux-hardware.org/?probe=8ad8098315) | Aug 31, 2023 |
| Intel         | H61                         | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| HP            | 339A                        | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| HP            | 8768 A                      | [99787646c5](https://linux-hardware.org/?probe=99787646c5) | Aug 31, 2023 |
| HP            | 2215                        | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| Intel         | HM570                       | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Acer          | Veriton N4660G              | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| MSI           | X99A RAIDER                 | [5b79d93d0a](https://linux-hardware.org/?probe=5b79d93d0a) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [19cb61cbf6](https://linux-hardware.org/?probe=19cb61cbf6) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [06860111ba](https://linux-hardware.org/?probe=06860111ba) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| Lenovo        | SDK0J40700 WIN              | [12785fd41a](https://linux-hardware.org/?probe=12785fd41a) | Aug 31, 2023 |
| HP            | 1587h                       | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| HP            | 806A                        | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| MSI           | Z370-A PRO                  | [56e3937602](https://linux-hardware.org/?probe=56e3937602) | Aug 31, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| HP            | 8768 A                      | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Gigabyte      | H110M-H-CF                  | [faf094d2ca](https://linux-hardware.org/?probe=faf094d2ca) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| MSI           | 880G-E45                    | [f10edf60fd](https://linux-hardware.org/?probe=f10edf60fd) | Aug 31, 2023 |
| MSI           | 2A78h                       | [78b5a663f2](https://linux-hardware.org/?probe=78b5a663f2) | Aug 31, 2023 |
| Dell          | 0KRC95 A02                  | [9173d00240](https://linux-hardware.org/?probe=9173d00240) | Aug 31, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [1a3fdd076f](https://linux-hardware.org/?probe=1a3fdd076f) | Aug 31, 2023 |
| MSI           | Boston                      | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| MSI           | 970 GAMING                  | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| Dell          | OptiPlex 7050               | [a35a9d7d8a](https://linux-hardware.org/?probe=a35a9d7d8a) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| ASUSTek       | A8N-E                       | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [42f87cb09b](https://linux-hardware.org/?probe=42f87cb09b) | Aug 30, 2023 |
| MSI           | H61MA-E35                   | [5eee145629](https://linux-hardware.org/?probe=5eee145629) | Aug 30, 2023 |
| Dell          | 0Y5DDC A00                  | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| ASRock        | H470M-STX                   | [8ba058add5](https://linux-hardware.org/?probe=8ba058add5) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| Acer          | Aspire XC-330               | [2e1b103708](https://linux-hardware.org/?probe=2e1b103708) | Aug 30, 2023 |
| Intel         | DH55TC AAE70932-205         | [5e3be336db](https://linux-hardware.org/?probe=5e3be336db) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| Medion        | B460H6-EM                   | [fac263bf1a](https://linux-hardware.org/?probe=fac263bf1a) | Aug 30, 2023 |
| ASUSTek       | P6T                         | [69879aca23](https://linux-hardware.org/?probe=69879aca23) | Aug 30, 2023 |
| HP            | 0B4Ch D                     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| ASUSTek       | P5Q SE PLUS                 | [311596a316](https://linux-hardware.org/?probe=311596a316) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| ASUSTek       | P8H67-V                     | [24b196c99a](https://linux-hardware.org/?probe=24b196c99a) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| ASRock        | H170M-ITX/ac                | [7921e28c6b](https://linux-hardware.org/?probe=7921e28c6b) | Aug 30, 2023 |
| OEM           | Intel H81                   | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Dell          | 0DR845                      | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f59364572a](https://linux-hardware.org/?probe=f59364572a) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [20bd10b5f4](https://linux-hardware.org/?probe=20bd10b5f4) | Aug 30, 2023 |
| Foxconn       | D180S/D190S/D290S Series... | [5f6030cb69](https://linux-hardware.org/?probe=5f6030cb69) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| HP            | 1589                        | [047e0158e8](https://linux-hardware.org/?probe=047e0158e8) | Aug 29, 2023 |
| ASUSTek       | PRIME Z270-P                | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| Pegatron      | 2A73h                       | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| MSI           | PH61-SP35                   | [590f47f3fd](https://linux-hardware.org/?probe=590f47f3fd) | Aug 29, 2023 |
| MSI           | Z97 GAMING 5                | [36cc5803b3](https://linux-hardware.org/?probe=36cc5803b3) | Aug 29, 2023 |
| Kobian        | PI945GCM ECS                | [85683b5fa3](https://linux-hardware.org/?probe=85683b5fa3) | Aug 29, 2023 |
| HP            | 885F A                      | [d665bb8939](https://linux-hardware.org/?probe=d665bb8939) | Aug 29, 2023 |
| Gigabyte      | X58A-UD7                    | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Gigabyte      | A320M-HD2-CF                | [7d9c3aa2ad](https://linux-hardware.org/?probe=7d9c3aa2ad) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | [b5ee83c5af](https://linux-hardware.org/?probe=b5ee83c5af) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M91p 4518B84    | [e2fd5511ee](https://linux-hardware.org/?probe=e2fd5511ee) | Aug 29, 2023 |
| HP            | 89B4 A                      | [e70b3a2352](https://linux-hardware.org/?probe=e70b3a2352) | Aug 29, 2023 |
| HC Technol... | HCAR5000-MI                 | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| MSI           | MAG B550 TORPEDO            | [7ac77b7bac](https://linux-hardware.org/?probe=7ac77b7bac) | Aug 28, 2023 |
| Intel         | H81                         | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [6d4609efa2](https://linux-hardware.org/?probe=6d4609efa2) | Aug 28, 2023 |
| HP            | 21D0                        | [8978dfd3bf](https://linux-hardware.org/?probe=8978dfd3bf) | Aug 28, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [409ccc747c](https://linux-hardware.org/?probe=409ccc747c) | Aug 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [844b4e4dc2](https://linux-hardware.org/?probe=844b4e4dc2) | Aug 28, 2023 |
| Gigabyte      | B550M DS3H                  | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| Dell          | 0C0YYY A00                  | [1ac938e884](https://linux-hardware.org/?probe=1ac938e884) | Aug 28, 2023 |
| ASUSTek       | PRIME B450M-A               | [b4411a9169](https://linux-hardware.org/?probe=b4411a9169) | Aug 27, 2023 |
| MSI           | B85M-G43                    | [96fd52d530](https://linux-hardware.org/?probe=96fd52d530) | Aug 27, 2023 |
| ASRock        | Z490M-ITX/ac                | [d3a4f92f62](https://linux-hardware.org/?probe=d3a4f92f62) | Aug 27, 2023 |
| ASUSTek       | P5KPL-AM                    | [a139f22d59](https://linux-hardware.org/?probe=a139f22d59) | Aug 27, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [713e62f936](https://linux-hardware.org/?probe=713e62f936) | Aug 27, 2023 |
| Foxconn       | 2ABF                        | [b0a8f65bca](https://linux-hardware.org/?probe=b0a8f65bca) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| HP            | 87D6 SMVB                   | [a2cf3918b7](https://linux-hardware.org/?probe=a2cf3918b7) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| Dell          | 0JCTF8 A00                  | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| ASUSTek       | Z77-A                       | [1aa1747b87](https://linux-hardware.org/?probe=1aa1747b87) | Aug 26, 2023 |
| Pegatron      | IPM41-D3                    | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| HP            | 1998                        | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| ASRock        | Wolfdale1333-D667           | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9bde22726b](https://linux-hardware.org/?probe=9bde22726b) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| Dell          | 00V62H A01                  | [69824bbd6d](https://linux-hardware.org/?probe=69824bbd6d) | Aug 26, 2023 |
| Dell          | 0XCR8D A02                  | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| ASUSTek       | AT5NM10-I                   | [15edd1ec31](https://linux-hardware.org/?probe=15edd1ec31) | Aug 26, 2023 |
| MSI           | H81M-P33                    | [e86c3faf2e](https://linux-hardware.org/?probe=e86c3faf2e) | Aug 26, 2023 |
| MSI           | H510M-A PRO                 | [0620b43b6a](https://linux-hardware.org/?probe=0620b43b6a) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [78df724503](https://linux-hardware.org/?probe=78df724503) | Aug 26, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5febb12d66](https://linux-hardware.org/?probe=5febb12d66) | Aug 26, 2023 |
| Biostar       | G41D3C                      | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| Gigabyte      | Z77X-UD5H                   | [98a1dbe051](https://linux-hardware.org/?probe=98a1dbe051) | Aug 25, 2023 |
| HP            | 89D8 SMVB                   | [d9898111f8](https://linux-hardware.org/?probe=d9898111f8) | Aug 25, 2023 |
| ASUSTek       | P8H77-V LE                  | [03740cd24c](https://linux-hardware.org/?probe=03740cd24c) | Aug 25, 2023 |
| ASRock        | B250M-HDV                   | [1bc8a402b3](https://linux-hardware.org/?probe=1bc8a402b3) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | [255eeb3d65](https://linux-hardware.org/?probe=255eeb3d65) | Aug 25, 2023 |
| MSI           | B450M MORTAR MAX            | [b328603445](https://linux-hardware.org/?probe=b328603445) | Aug 25, 2023 |
| ASUSTek       | M4A87TD EVO                 | [70a6d20dbf](https://linux-hardware.org/?probe=70a6d20dbf) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| Gigabyte      | H81M-H                      | [7da367fdec](https://linux-hardware.org/?probe=7da367fdec) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| MSI           | Z97S SLI Krait Edition      | [037e041959](https://linux-hardware.org/?probe=037e041959) | Aug 25, 2023 |
| HP            | 21F5 0A                     | [812718f3e7](https://linux-hardware.org/?probe=812718f3e7) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Pegatron      | EVANS                       | [1b32c5d271](https://linux-hardware.org/?probe=1b32c5d271) | Aug 24, 2023 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | [088ba21947](https://linux-hardware.org/?probe=088ba21947) | Aug 24, 2023 |
| Acer          | Aspire TC-115               | [1c22aff012](https://linux-hardware.org/?probe=1c22aff012) | Aug 24, 2023 |
| Lenovo        | ThinkCentre M72e 3597A56    | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| Acer          | EQ45LM                      | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | P8H77-M PRO                 | [4953513629](https://linux-hardware.org/?probe=4953513629) | Aug 24, 2023 |
| Acer          | Aspire TC-605               | [03cff37b1a](https://linux-hardware.org/?probe=03cff37b1a) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| Lenovo        | 312A NOK                    | [88533268cf](https://linux-hardware.org/?probe=88533268cf) | Aug 23, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Intel         | DZ77BH-55K AAG39008-400     | [30c81f585a](https://linux-hardware.org/?probe=30c81f585a) | Aug 23, 2023 |
| MSI           | A320M-A PRO                 | [c5ea9af7cd](https://linux-hardware.org/?probe=c5ea9af7cd) | Aug 23, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [aa959925b8](https://linux-hardware.org/?probe=aa959925b8) | Aug 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [796925bf51](https://linux-hardware.org/?probe=796925bf51) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Medion        | B460H6-EM                   | [7da77cb4d7](https://linux-hardware.org/?probe=7da77cb4d7) | Aug 22, 2023 |
| Intel         | H81                         | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [e99aa2e4d7](https://linux-hardware.org/?probe=e99aa2e4d7) | Aug 22, 2023 |
| MSI           | G31TM-P21                   | [c8aa8973a4](https://linux-hardware.org/?probe=c8aa8973a4) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [d39f8430ac](https://linux-hardware.org/?probe=d39f8430ac) | Aug 22, 2023 |
| HP            | 1850                        | [d9b3f59f97](https://linux-hardware.org/?probe=d9b3f59f97) | Aug 22, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [48f65a86aa](https://linux-hardware.org/?probe=48f65a86aa) | Aug 22, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [3bdb30f543](https://linux-hardware.org/?probe=3bdb30f543) | Aug 22, 2023 |
| Lenovo        | H415                        | [e6277f1ab8](https://linux-hardware.org/?probe=e6277f1ab8) | Aug 22, 2023 |
| MSI           | X470 GAMING PLUS            | [191c724d49](https://linux-hardware.org/?probe=191c724d49) | Aug 21, 2023 |
| Intel         | H61                         | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [e9c7a12d52](https://linux-hardware.org/?probe=e9c7a12d52) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [7993a53688](https://linux-hardware.org/?probe=7993a53688) | Aug 21, 2023 |
| ASUSTek       | PRIME X570-P                | [6c5abd788f](https://linux-hardware.org/?probe=6c5abd788f) | Aug 20, 2023 |
| Intel         | X99                         | [e16fe5b0f3](https://linux-hardware.org/?probe=e16fe5b0f3) | Aug 19, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [1824f3c712](https://linux-hardware.org/?probe=1824f3c712) | Aug 19, 2023 |
| Gigabyte      | G31M-S2L                    | [5768055184](https://linux-hardware.org/?probe=5768055184) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| ASRock        | Z370 Pro4                   | [9b7cf0384c](https://linux-hardware.org/?probe=9b7cf0384c) | Aug 18, 2023 |
| AZW           | EQ                          | [6fda99ad46](https://linux-hardware.org/?probe=6fda99ad46) | Aug 18, 2023 |
| ASUSTek       | H61M-E                      | [d4849fe5f4](https://linux-hardware.org/?probe=d4849fe5f4) | Aug 18, 2023 |
| ECS           | A55F-M4                     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7658411c87](https://linux-hardware.org/?probe=7658411c87) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-R               | [809590bdb0](https://linux-hardware.org/?probe=809590bdb0) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | [c956862ccd](https://linux-hardware.org/?probe=c956862ccd) | Aug 17, 2023 |
| HP            | 8768 A                      | [a2b7f6905c](https://linux-hardware.org/?probe=a2b7f6905c) | Aug 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [0a48b003bb](https://linux-hardware.org/?probe=0a48b003bb) | Aug 17, 2023 |
| Shuttle       | DS20U                       | [3a1ceb6021](https://linux-hardware.org/?probe=3a1ceb6021) | Aug 17, 2023 |
| Gigabyte      | B85M-D3H                    | [fe8d01fa26](https://linux-hardware.org/?probe=fe8d01fa26) | Aug 17, 2023 |
| Unknown       | Unknown                     | [6b82ccd639](https://linux-hardware.org/?probe=6b82ccd639) | Aug 17, 2023 |
| Gigabyte      | 965P-S3                     | [d9557da16c](https://linux-hardware.org/?probe=d9557da16c) | Aug 16, 2023 |
| ASUSTek       | H110M-R                     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Gigabyte      | P55-USB3                    | [4e25d8ef9f](https://linux-hardware.org/?probe=4e25d8ef9f) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| MSI           | A320M-A PRO MAX             | [57a2ddf4a7](https://linux-hardware.org/?probe=57a2ddf4a7) | Aug 16, 2023 |
| Acer          | EM61SM/EM61PM               | [428f134de7](https://linux-hardware.org/?probe=428f134de7) | Aug 15, 2023 |
| ASUSTek       | H97-PLUS                    | [166b18583b](https://linux-hardware.org/?probe=166b18583b) | Aug 15, 2023 |
| ASUSTek       | P5K SE                      | [8d6a3e990c](https://linux-hardware.org/?probe=8d6a3e990c) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| ASUSTek       | H170-PRO                    | [a5086e207e](https://linux-hardware.org/?probe=a5086e207e) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [ac6dd63085](https://linux-hardware.org/?probe=ac6dd63085) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| ASRock        | 970A-G                      | [5a2b77eaee](https://linux-hardware.org/?probe=5a2b77eaee) | Aug 12, 2023 |
| Biostar       | B660GTQ                     | [520d57cadc](https://linux-hardware.org/?probe=520d57cadc) | Aug 11, 2023 |
| MSI           | H410M-A PRO                 | [de3739c2a5](https://linux-hardware.org/?probe=de3739c2a5) | Aug 11, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [497623fdfd](https://linux-hardware.org/?probe=497623fdfd) | Aug 07, 2023 |
| Dell          | 0M9KCM A02                  | [a854d04706](https://linux-hardware.org/?probe=a854d04706) | Aug 07, 2023 |
| ASUSTek       | M4A77TD                     | [667b258dd5](https://linux-hardware.org/?probe=667b258dd5) | Aug 06, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.08/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 6.4.11-desktop-1omv2390      | 720      | 80.09%  |
| 6.4.8-desktop-2omv2390       | 166      | 18.46%  |
| 6.5.0-desktop-1omv2390       | 8        | 0.89%   |
| 6.6.2-desktop-1omv2390       | 1        | 0.11%   |
| 6.6.0-desktop-1omv2390       | 1        | 0.11%   |
| 6.5.1-desktop-1omv2390       | 1        | 0.11%   |
| 6.5.0-desktop-0.rc7.1omv2390 | 1        | 0.11%   |
| 6.3.5-desktop-3omv2390       | 1        | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4.11  | 720      | 80.09%  |
| 6.4.8   | 166      | 18.46%  |
| 6.5.0   | 9        | 1%      |
| 6.6.2   | 1        | 0.11%   |
| 6.6.0   | 1        | 0.11%   |
| 6.5.1   | 1        | 0.11%   |
| 6.3.5   | 1        | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4     | 884      | 98.55%  |
| 6.5     | 10       | 1.11%   |
| 6.6     | 2        | 0.22%   |
| 6.3     | 1        | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 897      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 756      | 84.09%  |
| GNOME   | 81       | 9.01%   |
| LXQt    | 58       | 6.45%   |
| Budgie  | 3        | 0.33%   |
| Unknown | 1        | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 870      | 96.88%  |
| X11     | 27       | 3.01%   |
| Unknown | 1        | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 817      | 90.98%  |
| GDM  | 81       | 9.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 417      | 46.44%  |
| de_DE | 65       | 7.24%   |
| pt_BR | 59       | 6.57%   |
| ru_RU | 58       | 6.46%   |
| fr_FR | 47       | 5.23%   |
| en_GB | 38       | 4.23%   |
| pl_PL | 34       | 3.79%   |
| it_IT | 31       | 3.45%   |
| es_ES | 26       | 2.9%    |
| en_CA | 10       | 1.11%   |
| hu_HU | 9        | 1%      |
| es_MX | 9        | 1%      |
| cs_CZ | 9        | 1%      |
| fr_BE | 8        | 0.89%   |
| es_VE | 8        | 0.89%   |
| es_AR | 7        | 0.78%   |
| pt_PT | 6        | 0.67%   |
| es_CO | 6        | 0.67%   |
| en_AU | 6        | 0.67%   |
| tr_TR | 5        | 0.56%   |
| en_IN | 5        | 0.56%   |
| nl_NL | 3        | 0.33%   |
| de_AT | 3        | 0.33%   |
| nl_BE | 2        | 0.22%   |
| fr_CA | 2        | 0.22%   |
| es_CL | 2        | 0.22%   |
| en_ZA | 2        | 0.22%   |
| en_IE | 2        | 0.22%   |
| de_CH | 2        | 0.22%   |
| ar_DZ | 2        | 0.22%   |
| uk_UA | 1        | 0.11%   |
| ro_RO | 1        | 0.11%   |
| ja_JP | 1        | 0.11%   |
| fr_CH | 1        | 0.11%   |
| es_UY | 1        | 0.11%   |
| es_PY | 1        | 0.11%   |
| es_GT | 1        | 0.11%   |
| es_CR | 1        | 0.11%   |
| es_BO | 1        | 0.11%   |
| en_SG | 1        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 480      | 53.45%  |
| BIOS | 418      | 46.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 450      | 50%     |
| Ext4     | 395      | 43.89%  |
| Btrfs    | 30       | 3.33%   |
| Xfs      | 8        | 0.89%   |
| F2fs     | 5        | 0.56%   |
| Reiserfs | 4        | 0.44%   |
| Jfs      | 3        | 0.33%   |
| Ext3     | 3        | 0.33%   |
| Udf      | 1        | 0.11%   |
| Ext2     | 1        | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 687      | 76.5%   |
| MBR  | 211      | 23.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 470      | 52.22%  |
| No        | 430      | 47.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 459      | 51.06%  |
| Yes       | 440      | 48.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 188      | 20.96%  |
| Gigabyte Technology                  | 138      | 15.38%  |
| MSI                                  | 95       | 10.59%  |
| Hewlett-Packard                      | 93       | 10.37%  |
| Dell                                 | 72       | 8.03%   |
| ASRock                               | 66       | 7.36%   |
| Intel                                | 53       | 5.91%   |
| Lenovo                               | 40       | 4.46%   |
| Fujitsu                              | 19       | 2.12%   |
| Acer                                 | 18       | 2.01%   |
| Foxconn                              | 15       | 1.67%   |
| Pegatron                             | 10       | 1.11%   |
| Biostar                              | 10       | 1.11%   |
| Shenzhen Meigao Electronic Equipment | 7        | 0.78%   |
| Positivo                             | 7        | 0.78%   |
| AZW                                  | 7        | 0.78%   |
| Unknown                              | 7        | 0.78%   |
| ECS                                  | 6        | 0.67%   |
| Medion                               | 5        | 0.56%   |
| OEM                                  | 4        | 0.45%   |
| Shuttle                              | 2        | 0.22%   |
| Red Hat                              | 2        | 0.22%   |
| PCWare                               | 2        | 0.22%   |
| Packard Bell                         | 2        | 0.22%   |
| Minix                                | 2        | 0.22%   |
| Megaware                             | 2        | 0.22%   |
| Casper                               | 2        | 0.22%   |
| BESSTAR Tech                         | 2        | 0.22%   |
| AMD                                  | 2        | 0.22%   |
| ViewSonic                            | 1        | 0.11%   |
| QIYIDA                               | 1        | 0.11%   |
| Philco                               | 1        | 0.11%   |
| NEC Computers                        | 1        | 0.11%   |
| MAXSUN                               | 1        | 0.11%   |
| MACHINIST                            | 1        | 0.11%   |
| Koloe                                | 1        | 0.11%   |
| Kobian                               | 1        | 0.11%   |
| Itautec                              | 1        | 0.11%   |
| Inventec                             | 1        | 0.11%   |
| Huanan                               | 1        | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 15       | 1.67%   |
| Intel H61                                  | 9        | 1%      |
| Unknown                                    | 8        | 0.89%   |
| Intel H81                                  | 7        | 0.78%   |
| Dell OptiPlex 7010                         | 7        | 0.78%   |
| HP Compaq Pro 6300 SFF                     | 6        | 0.67%   |
| MSI MS-7C51                                | 5        | 0.56%   |
| Intel X99                                  | 5        | 0.56%   |
| Gigabyte B75M-D3H                          | 5        | 0.56%   |
| Dell OptiPlex 9020                         | 5        | 0.56%   |
| MSI MS-7C91                                | 4        | 0.45%   |
| MSI MS-7817                                | 4        | 0.45%   |
| Intel B75                                  | 4        | 0.45%   |
| HP Z400 Workstation                        | 4        | 0.45%   |
| HP Compaq 6200 Pro SFF PC                  | 4        | 0.45%   |
| Gigabyte X299 AORUS Gaming                 | 4        | 0.45%   |
| Dell OptiPlex 9010                         | 4        | 0.45%   |
| Dell OptiPlex 3010                         | 4        | 0.45%   |
| Shenzhen Meigao Electronic Equipment UM690 | 3        | 0.33%   |
| Positivo POS-PIG41BA                       | 3        | 0.33%   |
| MSI MS-7C37                                | 3        | 0.33%   |
| MSI MS-7B89                                | 3        | 0.33%   |
| MSI MS-7B86                                | 3        | 0.33%   |
| MSI MS-7996                                | 3        | 0.33%   |
| Intel Jasper Lake Client Platform          | 3        | 0.33%   |
| HP EliteDesk 800 G1 USDT                   | 3        | 0.33%   |
| HP EliteDesk 800 G1 SFF                    | 3        | 0.33%   |
| HP Desktop M01-F1xxx                       | 3        | 0.33%   |
| HP Compaq Elite 8300 SFF                   | 3        | 0.33%   |
| HP Compaq Elite 8300 CMT                   | 3        | 0.33%   |
| HP Compaq 8000 Elite SFF PC                | 3        | 0.33%   |
| Gigabyte X570 AORUS ELITE                  | 3        | 0.33%   |
| Gigabyte B85M-D3H                          | 3        | 0.33%   |
| Gigabyte A320M-S2H                         | 3        | 0.33%   |
| Gigabyte A320M-H                           | 3        | 0.33%   |
| Foxconn Pro3500 Series                     | 3        | 0.33%   |
| Dell OptiPlex 755                          | 3        | 0.33%   |
| Biostar H310MHP                            | 3        | 0.33%   |
| AZW MINI S                                 | 3        | 0.33%   |
| ASUS TUF Gaming X570-PLUS                  | 3        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 47       | 5.24%   |
| ASUS PRIME                                 | 43       | 4.79%   |
| HP Compaq                                  | 35       | 3.9%    |
| Lenovo ThinkCentre                         | 30       | 3.34%   |
| ASUS TUF                                   | 16       | 1.78%   |
| Fujitsu ESPRIMO                            | 15       | 1.67%   |
| ASUS All                                   | 15       | 1.67%   |
| HP EliteDesk                               | 13       | 1.45%   |
| ASUS ROG                                   | 12       | 1.34%   |
| Intel H61                                  | 9        | 1%      |
| HP ProDesk                                 | 9        | 1%      |
| Dell Inspiron                              | 9        | 1%      |
| ASUS M5A78L-M                              | 9        | 1%      |
| Acer Aspire                                | 9        | 1%      |
| Intel H81                                  | 8        | 0.89%   |
| HP Slim                                    | 8        | 0.89%   |
| Acer Veriton                               | 8        | 0.89%   |
| Unknown                                    | 8        | 0.89%   |
| Gigabyte B550                              | 7        | 0.78%   |
| Gigabyte B450                              | 6        | 0.67%   |
| Dell Vostro                                | 6        | 0.67%   |
| MSI MS-7C51                                | 5        | 0.56%   |
| Intel X99                                  | 5        | 0.56%   |
| Gigabyte X570                              | 5        | 0.56%   |
| Gigabyte B75M-D3H                          | 5        | 0.56%   |
| Dell XPS                                   | 5        | 0.56%   |
| MSI MS-7C91                                | 4        | 0.45%   |
| MSI MS-7817                                | 4        | 0.45%   |
| Lenovo IdeaCentre                          | 4        | 0.45%   |
| Intel DG41RQ                               | 4        | 0.45%   |
| Intel B75                                  | 4        | 0.45%   |
| HP Z400                                    | 4        | 0.45%   |
| HP Pavilion                                | 4        | 0.45%   |
| Gigabyte X299                              | 4        | 0.45%   |
| Gigabyte H510M                             | 4        | 0.45%   |
| Gigabyte B550M                             | 4        | 0.45%   |
| Gigabyte B450M                             | 4        | 0.45%   |
| Gigabyte A320M-S2H                         | 4        | 0.45%   |
| ASRock B450                                | 4        | 0.45%   |
| Shenzhen Meigao Electronic Equipment UM690 | 3        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 101      | 11.26%  |
| 2013 | 75       | 8.36%   |
| 2014 | 69       | 7.69%   |
| 2020 | 64       | 7.13%   |
| 2018 | 61       | 6.8%    |
| 2010 | 58       | 6.47%   |
| 2011 | 56       | 6.24%   |
| 2017 | 55       | 6.13%   |
| 2019 | 54       | 6.02%   |
| 2021 | 52       | 5.8%    |
| 2022 | 48       | 5.35%   |
| 2009 | 44       | 4.91%   |
| 2016 | 40       | 4.46%   |
| 2023 | 29       | 3.23%   |
| 2015 | 27       | 3.01%   |
| 2008 | 26       | 2.9%    |
| 2007 | 23       | 2.56%   |
| 2006 | 10       | 1.11%   |
| 2005 | 3        | 0.33%   |
| 2004 | 2        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 897      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 897      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 897      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 205      | 22.85%  |
| 4.01-8.0    | 186      | 20.74%  |
| 8.01-16.0   | 184      | 20.51%  |
| 3.01-4.0    | 124      | 13.82%  |
| 32.01-64.0  | 108      | 12.04%  |
| 64.01-256.0 | 28       | 3.12%   |
| 24.01-32.0  | 25       | 2.79%   |
| 2.01-3.0    | 17       | 1.9%    |
| 1.01-2.0    | 17       | 1.9%    |
| 0.51-1.0    | 3        | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 582      | 64.45%  |
| 2.01-3.0  | 200      | 22.15%  |
| 0.51-1.0  | 70       | 7.75%   |
| 3.01-4.0  | 34       | 3.77%   |
| 4.01-8.0  | 10       | 1.11%   |
| 0.01-0.5  | 6        | 0.66%   |
| 8.01-16.0 | 1        | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 407      | 45.17%  |
| 2      | 236      | 26.19%  |
| 3      | 122      | 13.54%  |
| 4      | 67       | 7.44%   |
| 5      | 34       | 3.77%   |
| 6      | 18       | 2%      |
| 0      | 7        | 0.78%   |
| 8      | 3        | 0.33%   |
| 7      | 3        | 0.33%   |
| 10     | 2        | 0.22%   |
| 11     | 1        | 0.11%   |
| 9      | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 465      | 51.84%  |
| No        | 432      | 48.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 884      | 98.55%  |
| No        | 13       | 1.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 544      | 60.58%  |
| Yes       | 354      | 39.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 651      | 72.58%  |
| Yes       | 246      | 27.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 109      | 12.15%  |
| Germany      | 89       | 9.92%   |
| Brazil       | 89       | 9.92%   |
| Russia       | 69       | 7.69%   |
| France       | 64       | 7.13%   |
| Poland       | 49       | 5.46%   |
| Italy        | 41       | 4.57%   |
| UK           | 37       | 4.12%   |
| Spain        | 30       | 3.34%   |
| Canada       | 20       | 2.23%   |
| Australia    | 17       | 1.9%    |
| Mexico       | 15       | 1.67%   |
| Netherlands  | 14       | 1.56%   |
| Belgium      | 14       | 1.56%   |
| Hungary      | 13       | 1.45%   |
| Japan        | 11       | 1.23%   |
| India        | 10       | 1.11%   |
| Czechia      | 10       | 1.11%   |
| Turkey       | 9        | 1%      |
| Greece       | 9        | 1%      |
| Colombia     | 9        | 1%      |
| Bulgaria     | 9        | 1%      |
| Argentina    | 9        | 1%      |
| Venezuela    | 8        | 0.89%   |
| China        | 8        | 0.89%   |
| Austria      | 8        | 0.89%   |
| Portugal     | 7        | 0.78%   |
| Thailand     | 6        | 0.67%   |
| Slovakia     | 6        | 0.67%   |
| Iran         | 6        | 0.67%   |
| Finland      | 6        | 0.67%   |
| Ukraine      | 4        | 0.45%   |
| South Africa | 4        | 0.45%   |
| Serbia       | 4        | 0.45%   |
| Romania      | 4        | 0.45%   |
| Malaysia     | 4        | 0.45%   |
| Belarus      | 4        | 0.45%   |
| Tunisia      | 3        | 0.33%   |
| Switzerland  | 3        | 0.33%   |
| Slovenia     | 3        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 11       | 1.22%   |
| Warsaw         | 9        | 1%      |
| Berlin         | 9        | 1%      |
| St Petersburg  | 8        | 0.89%   |
| Krakow         | 8        | 0.89%   |
| Milan          | 7        | 0.78%   |
| Sydney         | 6        | 0.67%   |
| Vienna         | 5        | 0.56%   |
| Tehran         | 5        | 0.56%   |
| Sao Paulo      | 5        | 0.56%   |
| San Cristóbal | 5        | 0.56%   |
| Rome           | 5        | 0.56%   |
| Novosibirsk    | 5        | 0.56%   |
| Melbourne      | 5        | 0.56%   |
| Athens         | 5        | 0.56%   |
| Sao Goncalo    | 4        | 0.45%   |
| Prague         | 4        | 0.45%   |
| Porto Alegre   | 4        | 0.45%   |
| Paris          | 4        | 0.45%   |
| Munich         | 4        | 0.45%   |
| Liège         | 4        | 0.45%   |
| Istanbul       | 4        | 0.45%   |
| Hamburg        | 4        | 0.45%   |
| Sofia          | 3        | 0.33%   |
| Seville        | 3        | 0.33%   |
| Santo André   | 3        | 0.33%   |
| Rio de Janeiro | 3        | 0.33%   |
| Perth          | 3        | 0.33%   |
| Perm           | 3        | 0.33%   |
| Oak Park       | 3        | 0.33%   |
| Minsk          | 3        | 0.33%   |
| Marília       | 3        | 0.33%   |
| Leicester      | 3        | 0.33%   |
| Lajeado        | 3        | 0.33%   |
| Galveston      | 3        | 0.33%   |
| Dresden        | 3        | 0.33%   |
| Cologne        | 3        | 0.33%   |
| Chelyabinsk    | 3        | 0.33%   |
| Budapest       | 3        | 0.33%   |
| Bristol        | 3        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 262      | 327    | 16.6%   |
| Seagate                     | 234      | 287    | 14.83%  |
| Samsung Electronics         | 197      | 253    | 12.48%  |
| Kingston                    | 105      | 118    | 6.65%   |
| Toshiba                     | 92       | 105    | 5.83%   |
| Crucial                     | 78       | 97     | 4.94%   |
| SanDisk                     | 54       | 58     | 3.42%   |
| Hitachi                     | 45       | 48     | 2.85%   |
| China                       | 39       | 44     | 2.47%   |
| A-DATA Technology           | 33       | 35     | 2.09%   |
| Unknown                     | 26       | 47     | 1.65%   |
| SPCC                        | 22       | 23     | 1.39%   |
| Maxtor                      | 19       | 22     | 1.2%    |
| Intel                       | 19       | 19     | 1.2%    |
| Patriot                     | 17       | 17     | 1.08%   |
| GOODRAM                     | 16       | 20     | 1.01%   |
| Intenso                     | 14       | 16     | 0.89%   |
| Team                        | 13       | 13     | 0.82%   |
| Lexar                       | 13       | 16     | 0.82%   |
| PNY                         | 12       | 13     | 0.76%   |
| Kingston Technology Company | 12       | 15     | 0.76%   |
| Apacer                      | 11       | 12     | 0.7%    |
| JMicron Technology          | 10       | 10     | 0.63%   |
| HGST                        | 10       | 10     | 0.63%   |
| Unknown                     | 10       | 11     | 0.63%   |
| Netac                       | 9        | 9      | 0.57%   |
| Micron Technology           | 9        | 9      | 0.57%   |
| Fanxiang                    | 9        | 9      | 0.57%   |
| OCZ                         | 8        | 8      | 0.51%   |
| Hewlett-Packard             | 8        | 8      | 0.51%   |
| Silicon Motion              | 7        | 8      | 0.44%   |
| Phison                      | 7        | 8      | 0.44%   |
| KingSpec                    | 6        | 7      | 0.38%   |
| Corsair                     | 6        | 7      | 0.38%   |
| Transcend                   | 5        | 5      | 0.32%   |
| T-FORCE                     | 5        | 6      | 0.32%   |
| Plextor                     | 5        | 5      | 0.32%   |
| KingFast                    | 5        | 5      | 0.32%   |
| XPG                         | 4        | 4      | 0.25%   |
| KIOXIA-EXCERIA              | 4        | 4      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 25       | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB   | 20       | 1.12%   |
| Kingston SA400S37240G 240GB SSD  | 20       | 1.12%   |
| Kingston SA400S37480G 480GB SSD  | 18       | 1.01%   |
| Toshiba DT01ACA100 1TB           | 17       | 0.95%   |
| Crucial CT500MX500SSD1 500GB     | 16       | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB   | 14       | 0.78%   |
| Kingston SA400S37120G 120GB SSD  | 14       | 0.78%   |
| Samsung SSD 850 EVO 250GB        | 13       | 0.73%   |
| Crucial CT240BX500SSD1 240GB     | 13       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB   | 12       | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB         | 11       | 0.62%   |
| SanDisk NVMe SSD Drive 1TB       | 11       | 0.62%   |
| Toshiba DT01ACA050 500GB         | 10       | 0.56%   |
| Seagate ST3500418AS 500GB        | 10       | 0.56%   |
| Samsung SSD 860 EVO 500GB        | 10       | 0.56%   |
| Samsung SSD 850 EVO 500GB        | 10       | 0.56%   |
| Kingston SV300S37A120G 120GB SSD | 10       | 0.56%   |
| Unknown                          | 10       | 0.56%   |
| Toshiba HDWD110 1TB              | 9        | 0.5%    |
| Unknown SD/MMC 2GB               | 8        | 0.45%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 8        | 0.45%   |
| Unknown Compact Flash 977MB      | 8        | 0.45%   |
| Seagate ST1000DM003-1SB102 1TB   | 8        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB   | 8        | 0.45%   |
| Samsung SSD 870 QVO 1TB          | 8        | 0.45%   |
| Samsung HD322HJ 320GB            | 8        | 0.45%   |
| JMicron Generic 320GB            | 8        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 7        | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB      | 7        | 0.39%   |
| Seagate ST3500312CS 500GB        | 7        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB   | 7        | 0.39%   |
| SanDisk SSD PLUS 1000GB          | 7        | 0.39%   |
| SanDisk NVMe SSD Drive 500GB     | 7        | 0.39%   |
| Samsung SSD 980 500GB            | 7        | 0.39%   |
| Samsung SSD 860 EVO 250GB        | 7        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB      | 7        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 0.34%   |
| Seagate ST500LT012-1DG142 500GB  | 6        | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 233      | 285    | 32.72%  |
| WDC                 | 230      | 277    | 32.3%   |
| Toshiba             | 85       | 97     | 11.94%  |
| Samsung Electronics | 57       | 61     | 8.01%   |
| Hitachi             | 45       | 48     | 6.32%   |
| Maxtor              | 18       | 21     | 2.53%   |
| HGST                | 10       | 10     | 1.4%    |
| JMicron Technology  | 9        | 9      | 1.26%   |
| Unknown             | 8        | 8      | 1.12%   |
| Fujitsu             | 3        | 4      | 0.42%   |
| Apple               | 3        | 3      | 0.42%   |
| Min Yi U            | 2        | 2      | 0.28%   |
| ExcelStor           | 2        | 2      | 0.28%   |
| WD MediaMax         | 1        | 1      | 0.14%   |
| Intenso             | 1        | 1      | 0.14%   |
| IB-AC703            | 1        | 1      | 0.14%   |
| DAS                 | 1        | 4      | 0.14%   |
| ASMT                | 1        | 2      | 0.14%   |
| ASMedia             | 1        | 1      | 0.14%   |
| Unknown             | 1        | 2      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 99       | 122    | 15.66%  |
| Kingston            | 84       | 93     | 13.29%  |
| Crucial             | 61       | 67     | 9.65%   |
| China               | 39       | 44     | 6.17%   |
| SanDisk             | 32       | 34     | 5.06%   |
| WDC                 | 31       | 35     | 4.91%   |
| A-DATA Technology   | 25       | 26     | 3.96%   |
| SPCC                | 18       | 18     | 2.85%   |
| Patriot             | 16       | 16     | 2.53%   |
| GOODRAM             | 16       | 20     | 2.53%   |
| Intenso             | 13       | 15     | 2.06%   |
| PNY                 | 12       | 13     | 1.9%    |
| Intel               | 12       | 12     | 1.9%    |
| Team                | 8        | 8      | 1.27%   |
| OCZ                 | 8        | 8      | 1.27%   |
| Apacer              | 8        | 8      | 1.27%   |
| Micron Technology   | 7        | 7      | 1.11%   |
| Lexar               | 7        | 8      | 1.11%   |
| Unknown             | 7        | 7      | 1.11%   |
| Toshiba             | 6        | 6      | 0.95%   |
| KingSpec            | 6        | 7      | 0.95%   |
| Hewlett-Packard     | 6        | 6      | 0.95%   |
| Transcend           | 5        | 5      | 0.79%   |
| Netac               | 5        | 5      | 0.79%   |
| KingFast            | 5        | 5      | 0.79%   |
| Fanxiang            | 5        | 5      | 0.79%   |
| T-FORCE             | 4        | 5      | 0.63%   |
| Plextor             | 4        | 4      | 0.63%   |
| KIOXIA-EXCERIA      | 4        | 4      | 0.63%   |
| Verbatim            | 3        | 3      | 0.47%   |
| USB3.0              | 3        | 3      | 0.47%   |
| INNOVATION IT       | 3        | 3      | 0.47%   |
| HS-SSD-C100         | 3        | 3      | 0.47%   |
| Emtec               | 3        | 3      | 0.47%   |
| WALRAM              | 2        | 2      | 0.32%   |
| Vaseky              | 2        | 2      | 0.32%   |
| Teclast             | 2        | 2      | 0.32%   |
| LITEON              | 2        | 2      | 0.32%   |
| KINGCOMP            | 2        | 2      | 0.32%   |
| Kingchuxing         | 2        | 2      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 557      | 839    | 42.75%  |
| SSD     | 502      | 692    | 38.53%  |
| NVMe    | 221      | 291    | 16.96%  |
| Unknown | 17       | 35     | 1.3%    |
| MMC     | 6        | 7      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 810      | 1473   | 73.3%   |
| NVMe | 218      | 284    | 19.73%  |
| SAS  | 71       | 100    | 6.43%   |
| MMC  | 6        | 7      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 625      | 919    | 56.36%  |
| 0.51-1.0   | 320      | 407    | 28.85%  |
| 1.01-2.0   | 99       | 118    | 8.93%   |
| 3.01-4.0   | 26       | 34     | 2.34%   |
| 2.01-3.0   | 24       | 28     | 2.16%   |
| 4.01-10.0  | 11       | 18     | 0.99%   |
| 10.01-20.0 | 4        | 7      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 305      | 33.81%  |
| 101-250        | 167      | 18.51%  |
| 251-500        | 128      | 14.19%  |
| 501-1000       | 84       | 9.31%   |
| Unknown        | 60       | 6.65%   |
| 51-100         | 53       | 5.88%   |
| 1001-2000      | 39       | 4.32%   |
| 21-50          | 37       | 4.1%    |
| More than 3000 | 15       | 1.66%   |
| 2001-3000      | 14       | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 694      | 77.11%  |
| Unknown        | 60       | 6.67%   |
| 21-50          | 50       | 5.56%   |
| 101-250        | 26       | 2.89%   |
| 251-500        | 19       | 2.11%   |
| 51-100         | 17       | 1.89%   |
| 501-1000       | 14       | 1.56%   |
| 1001-2000      | 11       | 1.22%   |
| More than 3000 | 5        | 0.56%   |
| 2001-3000      | 4        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 9        | 9      | 2.78%   |
| Seagate ST3500418AS 500GB         | 7        | 7      | 2.16%   |
| Seagate ST1000DM010-2EP102 1TB    | 5        | 6      | 1.54%   |
| Hitachi HTS543225L9A300 250GB     | 5        | 5      | 1.54%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 4      | 1.23%   |
| Toshiba DT01ACA100 1TB            | 4        | 4      | 1.23%   |
| Seagate ST3500312CS 500GB         | 4        | 4      | 1.23%   |
| Seagate ST3160318AS 160GB         | 4        | 4      | 1.23%   |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 4      | 1.23%   |
| Samsung Electronics HD322HJ 320GB | 4        | 4      | 1.23%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 3        | 3      | 0.93%   |
| Toshiba DT01ACA050 500GB          | 3        | 3      | 0.93%   |
| Seagate ST3500413AS 500GB         | 3        | 3      | 0.93%   |
| Seagate ST2000DM001-1CH164 2TB    | 3        | 3      | 0.93%   |
| SanDisk SSD PLUS 480GB            | 3        | 3      | 0.93%   |
| Samsung Electronics HD502HJ 500GB | 3        | 3      | 0.93%   |
| Samsung Electronics HD103UJ 1TB   | 3        | 3      | 0.93%   |
| Samsung Electronics HD103SJ 1TB   | 3        | 3      | 0.93%   |
| Maxtor STM380815AS 80GB           | 3        | 4      | 0.93%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 3      | 0.93%   |
| WDC WD5000AVCS-632DY1 500GB       | 2        | 2      | 0.62%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 2        | 2      | 0.62%   |
| WDC WD3200AAJS-56M0A0 320GB       | 2        | 2      | 0.62%   |
| WDC WD3200AAJS-56B4A0 320GB       | 2        | 2      | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 0.62%   |
| WDC WD2500AAKX-001CA0 250GB       | 2        | 2      | 0.62%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 3      | 0.62%   |
| WDC WD10EZEX-60M2NA0 1TB          | 2        | 2      | 0.62%   |
| Toshiba MQ01ABD075 752GB          | 2        | 2      | 0.62%   |
| Toshiba MK3259GSXP 320GB          | 2        | 2      | 0.62%   |
| Seagate ST980811AS 80GB           | 2        | 2      | 0.62%   |
| Seagate ST500LT012-9WS142 500GB   | 2        | 2      | 0.62%   |
| Seagate ST500LT012-1DG142 500GB   | 2        | 2      | 0.62%   |
| Seagate ST250DM000-1BD141 250GB   | 2        | 2      | 0.62%   |
| Seagate ST1000DX001-1NS162 1TB    | 2        | 2      | 0.62%   |
| SanDisk SDSSDX240GG25 240GB       | 2        | 2      | 0.62%   |
| Samsung Electronics HD502HI 500GB | 2        | 2      | 0.62%   |
| Samsung Electronics HD320KJ 320GB | 2        | 3      | 0.62%   |
| Samsung Electronics HD161HJ 160GB | 2        | 2      | 0.62%   |
| Maxtor STM3250310AS 250GB         | 2        | 2      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 83       | 91     | 26.35%  |
| Seagate             | 82       | 87     | 26.03%  |
| Samsung Electronics | 36       | 37     | 11.43%  |
| Hitachi             | 28       | 28     | 8.89%   |
| Toshiba             | 22       | 23     | 6.98%   |
| Maxtor              | 13       | 14     | 4.13%   |
| SanDisk             | 7        | 7      | 2.22%   |
| Kingston            | 7        | 7      | 2.22%   |
| China               | 4        | 4      | 1.27%   |
| A-DATA Technology   | 4        | 4      | 1.27%   |
| SPCC                | 3        | 3      | 0.95%   |
| Netac               | 2        | 2      | 0.63%   |
| Micron Technology   | 2        | 2      | 0.63%   |
| Crucial             | 2        | 2      | 0.63%   |
| XPG                 | 1        | 1      | 0.32%   |
| Reeinno             | 1        | 1      | 0.32%   |
| PNY                 | 1        | 1      | 0.32%   |
| Plextor             | 1        | 1      | 0.32%   |
| OCZ                 | 1        | 1      | 0.32%   |
| KingDian            | 1        | 1      | 0.32%   |
| KINGCOMP            | 1        | 1      | 0.32%   |
| JMicron Technology  | 1        | 1      | 0.32%   |
| Intenso             | 1        | 1      | 0.32%   |
| Intel               | 1        | 1      | 0.32%   |
| INNOVATION IT       | 1        | 1      | 0.32%   |
| HGST                | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| Fujitsu             | 1        | 1      | 0.32%   |
| ExcelStor           | 1        | 1      | 0.32%   |
| EX276687RUS         | 1        | 1      | 0.32%   |
| Corsair             | 1        | 1      | 0.32%   |
| C300-CTF            | 1        | 1      | 0.32%   |
| C-S12               | 1        | 1      | 0.32%   |
| ASMT                | 1        | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 82       | 87     | 31.66%  |
| WDC                 | 78       | 86     | 30.12%  |
| Samsung Electronics | 31       | 32     | 11.97%  |
| Hitachi             | 28       | 28     | 10.81%  |
| Toshiba             | 22       | 23     | 8.49%   |
| Maxtor              | 13       | 14     | 5.02%   |
| JMicron Technology  | 1        | 1      | 0.39%   |
| HGST                | 1        | 1      | 0.39%   |
| Fujitsu             | 1        | 1      | 0.39%   |
| ExcelStor           | 1        | 1      | 0.39%   |
| ASMT                | 1        | 1      | 0.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 224      | 275    | 80.58%  |
| SSD  | 48       | 50     | 17.27%  |
| NVMe | 6        | 6      | 2.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB    | 1        | 1      | 12.5%   |
| WDC WD10EZEX-00BN5A0 1TB        | 1        | 1      | 12.5%   |
| Toshiba MQ01ABF032 320GB        | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 12.5%   |
| Seagate ST3250318AS 250GB       | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB        | 1        | 1      | 12.5%   |
| Samsung Electronics HD203WI 2TB | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 50%     |
| WDC                 | 2        | 2      | 25%     |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 743      | 1397   | 66.52%  |
| Malfunc  | 268      | 331    | 23.99%  |
| Detected | 98       | 128    | 8.77%   |
| Failed   | 8        | 8      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 606      | 50.21%  |
| AMD                              | 257      | 21.29%  |
| Samsung Electronics              | 60       | 4.97%   |
| SanDisk                          | 37       | 3.07%   |
| Kingston Technology Company      | 36       | 2.98%   |
| ASMedia Technology               | 29       | 2.4%    |
| Phison Electronics               | 26       | 2.15%   |
| Nvidia                           | 22       | 1.82%   |
| JMicron Technology               | 21       | 1.74%   |
| Micron/Crucial Technology        | 19       | 1.57%   |
| Marvell Technology Group         | 17       | 1.41%   |
| Silicon Motion                   | 16       | 1.33%   |
| MAXIO Technology (Hangzhou)      | 15       | 1.24%   |
| Realtek Semiconductor            | 8        | 0.66%   |
| ADATA Technology                 | 7        | 0.58%   |
| VIA Technologies                 | 6        | 0.5%    |
| Micron Technology                | 5        | 0.41%   |
| Shenzhen Longsys Electronics     | 4        | 0.33%   |
| Toshiba America Info Systems     | 2        | 0.17%   |
| SK hynix                         | 2        | 0.17%   |
| Netac Technology                 | 2        | 0.17%   |
| LSI Logic / Symbios Logic        | 2        | 0.17%   |
| KIOXIA                           | 2        | 0.17%   |
| Solid State Storage Technology   | 1        | 0.08%   |
| Silicon Integrated Systems [SiS] | 1        | 0.08%   |
| Seagate Technology               | 1        | 0.08%   |
| Integrated Technology Express    | 1        | 0.08%   |
| INNOGRIT                         | 1        | 0.08%   |
| Broadcom / LSI                   | 1        | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 125      | 8.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 84       | 5.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 60       | 4%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 59       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 51       | 3.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 49       | 3.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 45       | 3%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 40       | 2.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 37       | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 37       | 2.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 35       | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 34       | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 29       | 1.93%   |
| AMD FCH SATA Controller D                                                               | 29       | 1.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 27       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 26       | 1.73%   |
| Intel SATA Controller [RAID mode]                                                       | 25       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 24       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 24       | 1.6%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 20       | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 19       | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18       | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 14       | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 14       | 0.93%   |
| Nvidia MCP61 SATA Controller                                                            | 13       | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 13       | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13       | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 13       | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 12       | 0.8%    |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 12       | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 0.8%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 12       | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 11       | 0.73%   |
| Nvidia MCP61 IDE                                                                        | 11       | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11       | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 10       | 0.67%   |
| Phison E12 NVMe Controller                                                              | 10       | 0.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 8        | 0.53%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 708      | 59.1%   |
| IDE  | 223      | 18.61%  |
| NVMe | 219      | 18.28%  |
| RAID | 43       | 3.59%   |
| SAS  | 5        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 616      | 68.67%  |
| AMD    | 281      | 31.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 22       | 2.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 16       | 1.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 14       | 1.56%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 13       | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 12       | 1.34%   |
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 1.34%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 11       | 1.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 10       | 1.11%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 10       | 1.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 1%      |
| Intel Core i5-4440 CPU @ 3.10GHz            | 9        | 1%      |
| Intel Core i5-3570 CPU @ 3.40GHz            | 9        | 1%      |
| AMD Ryzen 7 5700G with Radeon Graphics      | 9        | 1%      |
| Intel Core i5-4590 CPU @ 3.30GHz            | 8        | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 0.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 0.89%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 8        | 0.89%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 8        | 0.89%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 0.89%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 8        | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 0.89%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 0.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 7        | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 7        | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.78%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 0.78%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 0.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 0.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 0.67%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 6        | 0.67%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 6        | 0.67%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 6        | 0.67%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 6        | 0.67%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 6        | 0.67%   |
| AMD Athlon II X2 250 Processor              | 6        | 0.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 0.56%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 5        | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 0.56%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 5        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 196      | 21.85%  |
| Intel Core i7           | 94       | 10.48%  |
| Intel Core i3           | 90       | 10.03%  |
| AMD Ryzen 5             | 71       | 7.92%   |
| Other                   | 44       | 4.91%   |
| AMD Ryzen 7             | 37       | 4.12%   |
| Intel Core 2 Duo        | 32       | 3.57%   |
| Intel Celeron           | 30       | 3.34%   |
| Intel Xeon              | 28       | 3.12%   |
| Intel Core 2 Quad       | 28       | 3.12%   |
| AMD FX                  | 27       | 3.01%   |
| Intel Pentium Dual-Core | 26       | 2.9%    |
| Intel Pentium           | 22       | 2.45%   |
| AMD Ryzen 3             | 22       | 2.45%   |
| AMD Ryzen 9             | 20       | 2.23%   |
| AMD Athlon II X2        | 13       | 1.45%   |
| AMD A8                  | 12       | 1.34%   |
| AMD A6                  | 10       | 1.11%   |
| AMD Phenom II X4        | 8        | 0.89%   |
| AMD A4                  | 8        | 0.89%   |
| AMD A10                 | 8        | 0.89%   |
| AMD Athlon 64 X2        | 7        | 0.78%   |
| Intel Atom              | 6        | 0.67%   |
| Intel Core 2            | 5        | 0.56%   |
| Intel Pentium Dual      | 4        | 0.45%   |
| Intel Pentium Gold      | 3        | 0.33%   |
| Intel Pentium D         | 3        | 0.33%   |
| AMD Ryzen 5 PRO         | 3        | 0.33%   |
| AMD PRO A10             | 3        | 0.33%   |
| AMD E1                  | 3        | 0.33%   |
| AMD E                   | 3        | 0.33%   |
| AMD Athlon              | 3        | 0.33%   |
| Intel Pentium 4         | 2        | 0.22%   |
| Intel Core i9           | 2        | 0.22%   |
| AMD Sempron             | 2        | 0.22%   |
| AMD Phenom II X3        | 2        | 0.22%   |
| AMD Phenom II X2        | 2        | 0.22%   |
| AMD GX                  | 2        | 0.22%   |
| AMD Athlon II X4        | 2        | 0.22%   |
| AMD Athlon Dual Core    | 2        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 387      | 43.14%  |
| 2      | 265      | 29.54%  |
| 6      | 121      | 13.49%  |
| 8      | 58       | 6.47%   |
| 1      | 20       | 2.23%   |
| 12     | 18       | 2.01%   |
| 10     | 8        | 0.89%   |
| 3      | 8        | 0.89%   |
| 16     | 6        | 0.67%   |
| 14     | 3        | 0.33%   |
| 36     | 1        | 0.11%   |
| 24     | 1        | 0.11%   |
| 5      | 1        | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 893      | 99.55%  |
| 2      | 2        | 0.22%   |
| 16     | 1        | 0.11%   |
| 14     | 1        | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 464      | 51.73%  |
| 1      | 432      | 48.16%  |
| 12     | 1        | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 897      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 634      | 70.68%  |
| 0x0a50000d | 24       | 2.68%   |
| 0x0a20120a | 19       | 2.12%   |
| 0x08701030 | 17       | 1.9%    |
| 0x08108109 | 15       | 1.67%   |
| 0x010000c8 | 15       | 1.67%   |
| 0x06001119 | 13       | 1.45%   |
| 0x06000822 | 12       | 1.34%   |
| 0x08701021 | 11       | 1.23%   |
| 0x0800820d | 10       | 1.11%   |
| 0x06003106 | 9        | 1%      |
| 0x0600611a | 7        | 0.78%   |
| 0x06000817 | 7        | 0.78%   |
| 0x0600081c | 6        | 0.67%   |
| 0x0a50000c | 5        | 0.56%   |
| 0x0a404102 | 5        | 0.56%   |
| 0x0a201025 | 5        | 0.56%   |
| 0x08101016 | 5        | 0.56%   |
| 0x08001138 | 5        | 0.56%   |
| 0x010000b6 | 5        | 0.56%   |
| 0x0a601206 | 4        | 0.45%   |
| 0x08600106 | 4        | 0.45%   |
| 0x0700010b | 4        | 0.45%   |
| 0x07030105 | 3        | 0.33%   |
| 0x06006705 | 3        | 0.33%   |
| 0x05000028 | 3        | 0.33%   |
| 0x01000086 | 3        | 0.33%   |
| 0x0a601203 | 2        | 0.22%   |
| 0x08600109 | 2        | 0.22%   |
| 0x08101013 | 2        | 0.22%   |
| 0x0810100b | 2        | 0.22%   |
| 0x0800820c | 2        | 0.22%   |
| 0x0800820b | 2        | 0.22%   |
| 0x08008206 | 2        | 0.22%   |
| 0x06003104 | 2        | 0.22%   |
| 0x05000101 | 2        | 0.22%   |
| 0x03000027 | 2        | 0.22%   |
| 0x03000014 | 2        | 0.22%   |
| 0x010000c6 | 2        | 0.22%   |
| 0x010000b7 | 2        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 114      | 12.71%  |
| IvyBridge        | 90       | 10.03%  |
| Penryn           | 72       | 8.03%   |
| SandyBridge      | 68       | 7.58%   |
| KabyLake         | 65       | 7.25%   |
| Zen 3            | 59       | 6.58%   |
| Piledriver       | 39       | 4.35%   |
| Zen 2            | 36       | 4.01%   |
| CometLake        | 36       | 4.01%   |
| Skylake          | 35       | 3.9%    |
| Zen+             | 33       | 3.68%   |
| K10              | 29       | 3.23%   |
| Alderlake Hybrid | 27       | 3.01%   |
| Core             | 26       | 2.9%    |
| Westmere         | 18       | 2.01%   |
| Zen              | 17       | 1.9%    |
| Nehalem          | 16       | 1.78%   |
| Unknown          | 15       | 1.67%   |
| K8 Hammer        | 14       | 1.56%   |
| Steamroller      | 12       | 1.34%   |
| Silvermont       | 11       | 1.23%   |
| Icelake          | 10       | 1.11%   |
| Excavator        | 10       | 1.11%   |
| Gracemont        | 8        | 0.89%   |
| Bobcat           | 6        | 0.67%   |
| Tremont          | 5        | 0.56%   |
| NetBurst         | 5        | 0.56%   |
| Puma             | 4        | 0.45%   |
| K10 Llano        | 4        | 0.45%   |
| Jaguar           | 4        | 0.45%   |
| Broadwell        | 3        | 0.33%   |
| Bonnell          | 3        | 0.33%   |
| Goldmont plus    | 2        | 0.22%   |
| Bulldozer        | 1        | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 346      | 37.32%  |
| AMD               | 289      | 31.18%  |
| Nvidia            | 287      | 30.96%  |
| Red Hat           | 2        | 0.22%   |
| ATI Technologies  | 2        | 0.22%   |
| ASPEED Technology | 1        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 56       | 5.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 39       | 4.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 39       | 4.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 26       | 2.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 24       | 2.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 22       | 2.33%   |
| Intel HD Graphics 530                                                       | 19       | 2.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 19       | 2.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17       | 1.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 1.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 16       | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 1.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 15       | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 13       | 1.38%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13       | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12       | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 12       | 1.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 12       | 1.27%   |
| Nvidia GF119 [GeForce GT 610]                                               | 11       | 1.17%   |
| Intel HD Graphics 630                                                       | 11       | 1.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 11       | 1.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 11       | 1.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 10       | 1.06%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 10       | 1.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 0.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 9        | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                         | 9        | 0.95%   |
| AMD RS780L [Radeon 3000]                                                    | 9        | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 9        | 0.95%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 9        | 0.95%   |
| Nvidia GF108 [GeForce GT 730]                                               | 8        | 0.85%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 8        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 7        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 0.64%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 6        | 0.64%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 6        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 304      | 33.89%  |
| 1 x AMD                | 271      | 30.21%  |
| 1 x Nvidia             | 258      | 28.76%  |
| Intel + Nvidia         | 19       | 2.12%   |
| 2 x Intel              | 18       | 2.01%   |
| 2 x AMD                | 11       | 1.23%   |
| AMD + Nvidia           | 5        | 0.56%   |
| Intel + AMD            | 4        | 0.45%   |
| 2 x Nvidia             | 3        | 0.33%   |
| 1 x Red Hat            | 2        | 0.22%   |
| 2 x Intel + 1 x Nvidia | 1        | 0.11%   |
| Nvidia + ASPEED        | 1        | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 866      | 96.44%  |
| Unknown     | 25       | 2.78%   |
| Proprietary | 7        | 0.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 344      | 38.31%  |
| 1.01-2.0   | 146      | 16.26%  |
| 0.51-1.0   | 115      | 12.81%  |
| 0.01-0.5   | 99       | 11.02%  |
| 3.01-4.0   | 70       | 7.8%    |
| 7.01-8.0   | 60       | 6.68%   |
| 8.01-16.0  | 29       | 3.23%   |
| 5.01-6.0   | 21       | 2.34%   |
| 2.01-3.0   | 10       | 1.11%   |
| 16.01-24.0 | 3        | 0.33%   |
| 4.01-5.0   | 1        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 148      | 16.78%  |
| Goldstar             | 101      | 11.45%  |
| Dell                 | 76       | 8.62%   |
| Acer                 | 69       | 7.82%   |
| Hewlett-Packard      | 66       | 7.48%   |
| AOC                  | 48       | 5.44%   |
| Philips              | 47       | 5.33%   |
| Ancor Communications | 35       | 3.97%   |
| BenQ                 | 33       | 3.74%   |
| ViewSonic            | 28       | 3.17%   |
| Iiyama               | 20       | 2.27%   |
| Sony                 | 14       | 1.59%   |
| MSI                  | 13       | 1.47%   |
| ASUSTek Computer     | 13       | 1.47%   |
| NEC Computers        | 12       | 1.36%   |
| Lenovo               | 11       | 1.25%   |
| Fujitsu Siemens      | 9        | 1.02%   |
| Eizo                 | 9        | 1.02%   |
| Unknown (XXX)        | 6        | 0.68%   |
| RTK                  | 6        | 0.68%   |
| Unknown              | 5        | 0.57%   |
| Sharp                | 5        | 0.57%   |
| Panasonic            | 5        | 0.57%   |
| Medion               | 5        | 0.57%   |
| Hitachi              | 5        | 0.57%   |
| Sceptre Tech         | 4        | 0.45%   |
| HKC                  | 4        | 0.45%   |
| ___                  | 3        | 0.34%   |
| Toshiba              | 3        | 0.34%   |
| Packard Bell         | 3        | 0.34%   |
| Gigabyte Technology  | 3        | 0.34%   |
| eMachines            | 3        | 0.34%   |
| CVT                  | 3        | 0.34%   |
| TCL                  | 2        | 0.23%   |
| RHT                  | 2        | 0.23%   |
| MStar                | 2        | 0.23%   |
| MiTAC                | 2        | 0.23%   |
| Mi                   | 2        | 0.23%   |
| Medion Akoya         | 2        | 0.23%   |
| HUAWEI               | 2        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 0.56%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                     | 5        | 0.56%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 5        | 0.56%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 4        | 0.45%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 3        | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.34%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 3        | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.34%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 3        | 0.34%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 3        | 0.34%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3        | 0.34%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch          | 3        | 0.34%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 3        | 0.34%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 3        | 0.34%   |
| Goldstar IPS237 GSM5901 1920x1080 510x290mm 23.1-inch                 | 3        | 0.34%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 3        | 0.34%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 3        | 0.34%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3        | 0.34%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 3        | 0.34%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 0.34%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 3        | 0.34%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 3        | 0.34%   |
| Ancor Communications BE24A ACI24AB 1920x1200 518x324mm 24.1-inch      | 3        | 0.34%   |
| Acer V226HQL ACR032D 1920x1080 480x270mm 21.7-inch                    | 3        | 0.34%   |
| Acer K222HQL ACR03E1 1920x1080 480x270mm 21.7-inch                    | 3        | 0.34%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 2        | 0.22%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 2        | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.22%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 2        | 0.22%   |
| TCL L23D2200F TCL2304 1920x1080 510x287mm 23.0-inch                   | 2        | 0.22%   |
| Sony TV SNYF301 1920x1080                                             | 2        | 0.22%   |
| Sharp HDMI SHP4192 1920x1080 708x398mm 32.0-inch                      | 2        | 0.22%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 2        | 0.22%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 2        | 0.22%   |
| Samsung Electronics T24B530 SAM0947 1920x1080 531x299mm 24.0-inch     | 2        | 0.22%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch  | 2        | 0.22%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch  | 2        | 0.22%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 2        | 0.22%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 2        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 446      | 51.32%  |
| 3840x2160 (4K)     | 68       | 7.83%   |
| 1280x1024 (SXGA)   | 58       | 6.67%   |
| 2560x1440 (QHD)    | 51       | 5.87%   |
| 1680x1050 (WSXGA+) | 44       | 5.06%   |
| 1366x768 (WXGA)    | 41       | 4.72%   |
| 1440x900 (WXGA+)   | 38       | 4.37%   |
| 1600x900 (HD+)     | 30       | 3.45%   |
| 1920x1200 (WUXGA)  | 27       | 3.11%   |
| 1360x768           | 13       | 1.5%    |
| 3440x1440          | 11       | 1.27%   |
| 2560x1080          | 8        | 0.92%   |
| 1600x1200          | 8        | 0.92%   |
| 1920x540           | 7        | 0.81%   |
| 1024x768 (XGA)     | 7        | 0.81%   |
| 1280x720 (HD)      | 3        | 0.35%   |
| 2288x1287          | 2        | 0.23%   |
| 2048x1152          | 2        | 0.23%   |
| 1280x960           | 2        | 0.23%   |
| 3840x1600          | 1        | 0.12%   |
| 1360x765           | 1        | 0.12%   |
| Unknown            | 1        | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 130      | 14.81%  |
| 24      | 122      | 13.9%   |
| 21      | 111      | 12.64%  |
| 27      | 98       | 11.16%  |
| 19      | 56       | 6.38%   |
| 31      | 53       | 6.04%   |
| 18      | 46       | 5.24%   |
| 22      | 38       | 4.33%   |
| 17      | 38       | 4.33%   |
| 20      | 36       | 4.1%    |
| Unknown | 18       | 2.05%   |
| 84      | 15       | 1.71%   |
| 72      | 15       | 1.71%   |
| 34      | 15       | 1.71%   |
| 15      | 14       | 1.59%   |
| 54      | 9        | 1.03%   |
| 32      | 7        | 0.8%    |
| 40      | 6        | 0.68%   |
| 28      | 5        | 0.57%   |
| 25      | 5        | 0.57%   |
| 52      | 4        | 0.46%   |
| 26      | 4        | 0.46%   |
| 16      | 4        | 0.46%   |
| 48      | 3        | 0.34%   |
| 37      | 3        | 0.34%   |
| 142     | 2        | 0.23%   |
| 85      | 2        | 0.23%   |
| 65      | 2        | 0.23%   |
| 46      | 2        | 0.23%   |
| 43      | 2        | 0.23%   |
| 39      | 2        | 0.23%   |
| 12      | 2        | 0.23%   |
| 74      | 1        | 0.11%   |
| 61      | 1        | 0.11%   |
| 59      | 1        | 0.11%   |
| 55      | 1        | 0.11%   |
| 42      | 1        | 0.11%   |
| 38      | 1        | 0.11%   |
| 35      | 1        | 0.11%   |
| 33      | 1        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 346      | 39.77%  |
| 401-500        | 260      | 29.89%  |
| 601-700        | 64       | 7.36%   |
| 301-350        | 49       | 5.63%   |
| 351-400        | 34       | 3.91%   |
| 1501-2000      | 33       | 3.79%   |
| 701-800        | 23       | 2.64%   |
| 1001-1500      | 23       | 2.64%   |
| Unknown        | 18       | 2.07%   |
| 801-900        | 13       | 1.49%   |
| 901-1000       | 3        | 0.34%   |
| More than 2000 | 2        | 0.23%   |
| 201-300        | 2        | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 623      | 72.95%  |
| 16/10   | 121      | 14.17%  |
| 5/4     | 61       | 7.14%   |
| 21/9    | 20       | 2.34%   |
| 4/3     | 17       | 1.99%   |
| Unknown | 6        | 0.7%    |
| 3/2     | 2        | 0.23%   |
| 1.00    | 2        | 0.23%   |
| 32/9    | 1        | 0.12%   |
| 1.96    | 1        | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 318      | 36.34%  |
| 151-200        | 133      | 15.2%   |
| 301-350        | 102      | 11.66%  |
| 351-500        | 77       | 8.8%    |
| 141-150        | 70       | 8%      |
| 251-300        | 58       | 6.63%   |
| More than 1000 | 55       | 6.29%   |
| 501-1000       | 19       | 2.17%   |
| Unknown        | 18       | 2.06%   |
| 101-110        | 12       | 1.37%   |
| 131-140        | 4        | 0.46%   |
| 111-120        | 3        | 0.34%   |
| 71-80          | 2        | 0.23%   |
| 121-130        | 2        | 0.23%   |
| 91-100         | 2        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 608      | 71.19%  |
| 101-120 | 151      | 17.68%  |
| 1-50    | 42       | 4.92%   |
| 121-160 | 22       | 2.58%   |
| Unknown | 18       | 2.11%   |
| 161-240 | 13       | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 803      | 89.42%  |
| 2     | 56       | 6.24%   |
| 0     | 34       | 3.79%   |
| 3     | 5        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 592      | 49.71%  |
| Intel                             | 326      | 27.37%  |
| Qualcomm Atheros                  | 69       | 5.79%   |
| TP-Link                           | 28       | 2.35%   |
| Broadcom                          | 26       | 2.18%   |
| Ralink Technology                 | 23       | 1.93%   |
| Nvidia                            | 20       | 1.68%   |
| Qualcomm Atheros Communications   | 14       | 1.18%   |
| Ralink                            | 11       | 0.92%   |
| MediaTek                          | 10       | 0.84%   |
| D-Link                            | 9        | 0.76%   |
| Marvell Technology Group          | 7        | 0.59%   |
| NetGear                           | 6        | 0.5%    |
| Broadcom Limited                  | 6        | 0.5%    |
| Huawei Technologies               | 5        | 0.42%   |
| Samsung Electronics               | 4        | 0.34%   |
| ASUSTek Computer                  | 4        | 0.34%   |
| ASIX Electronics                  | 3        | 0.25%   |
| VIA Technologies                  | 2        | 0.17%   |
| Qualcomm                          | 2        | 0.17%   |
| Mercucys                          | 2        | 0.17%   |
| BUFFALO                           | 2        | 0.17%   |
| AVM                               | 2        | 0.17%   |
| ZyXEL Communications              | 1        | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.08%   |
| Xiaomi                            | 1        | 0.08%   |
| U-Blox                            | 1        | 0.08%   |
| Tenda                             | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus | 1        | 0.08%   |
| Smart Link                        | 1        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.08%   |
| OPPO Electronics                  | 1        | 0.08%   |
| Motorola PCS                      | 1        | 0.08%   |
| Microsoft                         | 1        | 0.08%   |
| JMicron Technology                | 1        | 0.08%   |
| Edimax Technology                 | 1        | 0.08%   |
| CyberTAN Technology               | 1        | 0.08%   |
| Belkin Components                 | 1        | 0.08%   |
| Aquantia                          | 1        | 0.08%   |
| Apple                             | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 469      | 35.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54       | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 41       | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                      | 38       | 2.87%   |
| Intel Ethernet Connection I217-LM                                      | 28       | 2.12%   |
| Intel Wi-Fi 6 AX200                                                    | 20       | 1.51%   |
| Intel Ethernet Controller I225-V                                       | 20       | 1.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 19       | 1.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 19       | 1.44%   |
| Intel 82579V Gigabit Network Connection                                | 19       | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18       | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 16       | 1.21%   |
| Ralink MT7601U Wireless Adapter                                        | 15       | 1.13%   |
| Intel I211 Gigabit Network Connection                                  | 14       | 1.06%   |
| Realtek 802.11ac NIC                                                   | 13       | 0.98%   |
| Intel Ethernet Connection I217-V                                       | 13       | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13       | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 13       | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 11       | 0.83%   |
| Nvidia MCP61 Ethernet                                                  | 11       | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10       | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 8        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                                   | 8        | 0.6%    |
| Intel 82578DM Gigabit Network Connection                               | 8        | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7        | 0.53%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 7        | 0.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 7        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                   | 7        | 0.53%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 0.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 6        | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 6        | 0.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 6        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 0.45%   |
| Intel Wireless 7260                                                    | 6        | 0.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 5        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 5        | 0.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 5        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 109      | 30.03%  |
| Intel                           | 99       | 27.27%  |
| TP-Link                         | 28       | 7.71%   |
| Qualcomm Atheros                | 28       | 7.71%   |
| Ralink Technology               | 23       | 6.34%   |
| Qualcomm Atheros Communications | 14       | 3.86%   |
| Ralink                          | 11       | 3.03%   |
| MediaTek                        | 10       | 2.75%   |
| Broadcom                        | 10       | 2.75%   |
| D-Link                          | 9        | 2.48%   |
| NetGear                         | 6        | 1.65%   |
| ASUSTek Computer                | 4        | 1.1%    |
| Mercucys                        | 2        | 0.55%   |
| BUFFALO                         | 2        | 0.55%   |
| AVM                             | 2        | 0.55%   |
| ZyXEL Communications            | 1        | 0.28%   |
| Tenda                           | 1        | 0.28%   |
| Microsoft                       | 1        | 0.28%   |
| Edimax Technology               | 1        | 0.28%   |
| CyberTAN Technology             | 1        | 0.28%   |
| Belkin Components               | 1        | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 20       | 5.48%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 19       | 5.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 18       | 4.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 16       | 4.38%   |
| Ralink MT7601U Wireless Adapter                                                      | 15       | 4.11%   |
| Realtek 802.11ac NIC                                                                 | 13       | 3.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 11       | 3.01%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 10       | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 10       | 2.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 7        | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 7        | 1.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 7        | 1.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 6        | 1.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 6        | 1.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 6        | 1.64%   |
| Intel Wireless 7260                                                                  | 6        | 1.64%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 5        | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 5        | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 5        | 1.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 5        | 1.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 5        | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 5        | 1.37%   |
| Intel Wireless 7265                                                                  | 5        | 1.37%   |
| Intel Wireless 3165                                                                  | 5        | 1.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 4        | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 3        | 0.82%   |
| TP-Link 802.11ac NIC                                                                 | 3        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 3        | 0.82%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 3        | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 3        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 3        | 0.82%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 3        | 0.82%   |
| Ralink RT5370 Wireless Adapter                                                       | 3        | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 3        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 0.82%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 3        | 0.82%   |
| Intel Wireless 8265 / 8275                                                           | 3        | 0.82%   |
| Intel CNVi: Wi-Fi                                                                    | 3        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 552      | 59.61%  |
| Intel                             | 259      | 27.97%  |
| Qualcomm Atheros                  | 43       | 4.64%   |
| Nvidia                            | 20       | 2.16%   |
| Broadcom                          | 16       | 1.73%   |
| Marvell Technology Group          | 7        | 0.76%   |
| Broadcom Limited                  | 6        | 0.65%   |
| Huawei Technologies               | 5        | 0.54%   |
| Samsung Electronics               | 3        | 0.32%   |
| ASIX Electronics                  | 3        | 0.32%   |
| VIA Technologies                  | 2        | 0.22%   |
| Qualcomm                          | 2        | 0.22%   |
| Xiaomi                            | 1        | 0.11%   |
| Sundance Technology Inc / IC Plus | 1        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.11%   |
| OPPO Electronics                  | 1        | 0.11%   |
| JMicron Technology                | 1        | 0.11%   |
| Aquantia                          | 1        | 0.11%   |
| Apple                             | 1        | 0.11%   |
| 3Com                              | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 469      | 49.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54       | 5.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 41       | 4.31%   |
| Realtek RTL8125 2.5GbE Controller                                      | 38       | 3.99%   |
| Intel Ethernet Connection I217-LM                                      | 28       | 2.94%   |
| Intel Ethernet Controller I225-V                                       | 20       | 2.1%    |
| Intel Ethernet Connection (2) I219-V                                   | 19       | 2%      |
| Intel 82579V Gigabit Network Connection                                | 19       | 2%      |
| Intel I211 Gigabit Network Connection                                  | 14       | 1.47%   |
| Intel Ethernet Connection I217-V                                       | 13       | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13       | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 13       | 1.37%   |
| Nvidia MCP61 Ethernet                                                  | 11       | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9        | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 8        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                   | 8        | 0.84%   |
| Intel 82578DM Gigabit Network Connection                               | 8        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                   | 7        | 0.74%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.53%   |
| Intel Ethernet Connection (17) I219-V                                  | 5        | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5        | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 4        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 4        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4        | 0.42%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                  | 4        | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 0.42%   |
| Huawei E353/E3131                                                      | 4        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3        | 0.32%   |
| Nvidia MCP51 Ethernet Controller                                       | 3        | 0.32%   |
| Intel Ethernet Controller I226-V                                       | 3        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 0.32%   |
| Intel Ethernet Connection (10) I219-V                                  | 3        | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 884      | 71.06%  |
| WiFi     | 354      | 28.46%  |
| Modem    | 5        | 0.4%    |
| Unknown  | 1        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 701      | 79.39%  |
| WiFi     | 182      | 20.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 642      | 71.57%  |
| 2     | 227      | 25.31%  |
| 3     | 18       | 2.01%   |
| 0     | 8        | 0.89%   |
| 4     | 2        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 587      | 65.37%  |
| Yes  | 311      | 34.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 91       | 36.84%  |
| Cambridge Silicon Radio         | 65       | 26.32%  |
| Realtek Semiconductor           | 35       | 14.17%  |
| Broadcom                        | 11       | 4.45%   |
| MediaTek                        | 10       | 4.05%   |
| Qualcomm Atheros Communications | 7        | 2.83%   |
| ASUSTek Computer                | 7        | 2.83%   |
| IMC Networks                    | 6        | 2.43%   |
| TP-Link                         | 4        | 1.62%   |
| Lite-On Technology              | 3        | 1.21%   |
| Integrated System Solution      | 2        | 0.81%   |
| Edimax Technology               | 2        | 0.81%   |
| Foxconn / Hon Hai               | 1        | 0.4%    |
| Dynex                           | 1        | 0.4%    |
| Apple                           | 1        | 0.4%    |
| Unknown                         | 1        | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 65       | 26.32%  |
| Realtek Bluetooth Radio                                  | 24       | 9.72%   |
| Intel AX200 Bluetooth                                    | 19       | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                         | 16       | 6.48%   |
| Intel Bluetooth wireless interface                       | 15       | 6.07%   |
| Intel AX210 Bluetooth                                    | 15       | 6.07%   |
| MediaTek Wireless_Device                                 | 10       | 4.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 9        | 3.64%   |
| Realtek  Bluetooth 4.2 Adapter                           | 8        | 3.24%   |
| Intel AX201 Bluetooth                                    | 8        | 3.24%   |
| IMC Networks Bluetooth Radio                             | 6        | 2.43%   |
| TP-Link UB500 Adapter                                    | 4        | 1.62%   |
| Intel Bluetooth Device                                   | 4        | 1.62%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 1.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3        | 1.21%   |
| Realtek 802.11ac WLAN Adapter                            | 2        | 0.81%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.81%   |
| Lite-On Bluetooth Device                                 | 2        | 0.81%   |
| Edimax Edimax Bluetooth Adapter                          | 2        | 0.81%   |
| Broadcom HP Portable Bumble Bee                          | 2        | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 0.81%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 0.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 0.81%   |
| ASUS BCM20702A0                                          | 2        | 0.81%   |
| ASUS ASUS USB-BT500                                      | 2        | 0.81%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                        | 1        | 0.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1        | 0.4%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1        | 0.4%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.4%    |
| Integrated System Solution Bluetooth Device              | 1        | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 0.4%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.4%    |
| Broadcom HP Bluethunder                                  | 1        | 0.4%    |
| Broadcom Bluetooth V3.0 USB Device                       | 1        | 0.4%    |
| Broadcom Bluetooth 3.0 Device                            | 1        | 0.4%    |
| Broadcom BCM2210 Bluetooth                               | 1        | 0.4%    |
| Broadcom BCM2070 Bluetooth Device                        | 1        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 600      | 44.48%  |
| AMD                                          | 345      | 25.57%  |
| Nvidia                                       | 260      | 19.27%  |
| C-Media Electronics                          | 33       | 2.45%   |
| Creative Labs                                | 16       | 1.19%   |
| Texas Instruments                            | 7        | 0.52%   |
| ASUSTek Computer                             | 7        | 0.52%   |
| Generalplus Technology                       | 4        | 0.3%    |
| Creative Technology                          | 4        | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.22%   |
| Tenx Technology                              | 3        | 0.22%   |
| Razer USA                                    | 3        | 0.22%   |
| M-Audio                                      | 3        | 0.22%   |
| Logitech                                     | 3        | 0.22%   |
| Kingston Technology                          | 3        | 0.22%   |
| VIA Technologies                             | 2        | 0.15%   |
| SAVITECH                                     | 2        | 0.15%   |
| Realtek Semiconductor                        | 2        | 0.15%   |
| Micro Star International                     | 2        | 0.15%   |
| Lenovo                                       | 2        | 0.15%   |
| KTMicro                                      | 2        | 0.15%   |
| JMTek                                        | 2        | 0.15%   |
| GYROCOM C&C                                  | 2        | 0.15%   |
| GN Netcom                                    | 2        | 0.15%   |
| Focusrite-Novation                           | 2        | 0.15%   |
| FiiO Electronics Technology                  | 2        | 0.15%   |
| ATI Technologies                             | 2        | 0.15%   |
| Xilinx                                       | 1        | 0.07%   |
| Valve Software                               | 1        | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.07%   |
| somic                                        | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.07%   |
| Samson Technologies                          | 1        | 0.07%   |
| ONN                                          | 1        | 0.07%   |
| Native Instruments                           | 1        | 0.07%   |
| Musical Fidelity                             | 1        | 0.07%   |
| MosArt Semiconductor                         | 1        | 0.07%   |
| Microsoft                                    | 1        | 0.07%   |
| KORG                                         | 1        | 0.07%   |
| JOUNIVO                                      | 1        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 92       | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 79       | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 70       | 4.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 70       | 4.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 62       | 3.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 61       | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                          | 55       | 3.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 53       | 3.28%   |
| Intel 200 Series PCH HD Audio                                                     | 41       | 2.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 40       | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 39       | 2.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 37       | 2.29%   |
| AMD FCH Azalia Controller                                                         | 37       | 2.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 36       | 2.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 29       | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 23       | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 23       | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 23       | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 21       | 1.3%    |
| Intel Alder Lake-S HD Audio Controller                                            | 20       | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                     | 19       | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 19       | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                        | 18       | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 18       | 1.11%   |
| Nvidia High Definition Audio Controller                                           | 17       | 1.05%   |
| Intel Comet Lake PCH-V cAVS                                                       | 17       | 1.05%   |
| Nvidia GP108 High Definition Audio Controller                                     | 16       | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                | 16       | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 16       | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 14       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                     | 13       | 0.8%    |
| Intel Smart Sound Technology (SST) Audio Controller                               | 13       | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 13       | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 13       | 0.8%    |
| AMD Navi 10 HDMI Audio                                                            | 13       | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 13       | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 13       | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                                     | 12       | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 11       | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 191      | 17.87%  |
| Unknown                      | 160      | 14.97%  |
| Samsung Electronics          | 114      | 10.66%  |
| SK hynix                     | 98       | 9.17%   |
| Corsair                      | 82       | 7.67%   |
| Crucial                      | 74       | 6.92%   |
| Micron Technology            | 65       | 6.08%   |
| G.Skill                      | 53       | 4.96%   |
| Unknown                      | 25       | 2.34%   |
| A-DATA Technology            | 19       | 1.78%   |
| Patriot                      | 16       | 1.5%    |
| Team                         | 15       | 1.4%    |
| Nanya Technology             | 13       | 1.22%   |
| Ramaxel Technology           | 12       | 1.12%   |
| GOODRAM                      | 11       | 1.03%   |
| Elpida                       | 11       | 1.03%   |
| AMD                          | 8        | 0.75%   |
| Transcend                    | 7        | 0.65%   |
| Smart                        | 7        | 0.65%   |
| Apacer                       | 7        | 0.65%   |
| Atermiter                    | 6        | 0.56%   |
| Unknown (0x0E9D)             | 4        | 0.37%   |
| PNY                          | 4        | 0.37%   |
| Patriot Memory (PDP Systems) | 4        | 0.37%   |
| Kllisre                      | 3        | 0.28%   |
| Juhor                        | 3        | 0.28%   |
| ASint Technology             | 3        | 0.28%   |
| Wodposit                     | 2        | 0.19%   |
| Unknown (0x7FFF)             | 2        | 0.19%   |
| Thermaltake                  | 2        | 0.19%   |
| Teikon                       | 2        | 0.19%   |
| Silicon Power                | 2        | 0.19%   |
| Red Hat                      | 2        | 0.19%   |
| Qimonda                      | 2        | 0.19%   |
| Hikvision                    | 2        | 0.19%   |
| GeIL                         | 2        | 0.19%   |
| Wilk Elektronik              | 1        | 0.09%   |
| Wilk                         | 1        | 0.09%   |
| Walton Chaintech             | 1        | 0.09%   |
| Unknown (FFFF000000000000)   | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 25       | 2.12%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 14       | 1.18%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 11       | 0.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 10       | 0.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 8        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 8        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 8        | 0.68%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s | 8        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 7        | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 7        | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 7        | 0.59%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 7        | 0.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 7        | 0.59%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 7        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 6        | 0.51%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 6        | 0.51%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 6        | 0.51%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 6        | 0.51%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s | 6        | 0.51%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 6        | 0.51%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 6        | 0.51%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 6        | 0.51%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 5        | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 5        | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 5        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 5        | 0.42%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 5        | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 5        | 0.42%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 5        | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 5        | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 5        | 0.42%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 5        | 0.42%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 5        | 0.42%   |
| Unknown RAM Module 4GB DIMM 800MT/s                    | 4        | 0.34%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 4        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 4        | 0.34%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 4        | 0.34%   |
| Unknown RAM Module 2GB DIMM                            | 4        | 0.34%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s             | 4        | 0.34%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 350      | 38.38%  |
| DDR4    | 346      | 37.94%  |
| Unknown | 63       | 6.91%   |
| SDRAM   | 62       | 6.8%    |
| DDR2    | 53       | 5.81%   |
| DDR5    | 18       | 1.97%   |
| DDR     | 13       | 1.43%   |
| DRAM    | 3        | 0.33%   |
| RAM     | 2        | 0.22%   |
| LPDDR5  | 1        | 0.11%   |
| LPDDR4  | 1        | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 812      | 91.65%  |
| SODIMM       | 72       | 8.13%   |
| Row Of Chips | 1        | 0.11%   |
| RIMM         | 1        | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 369      | 36.79%  |
| 4096  | 271      | 27.02%  |
| 2048  | 175      | 17.45%  |
| 16384 | 102      | 10.17%  |
| 1024  | 41       | 4.09%   |
| 32768 | 36       | 3.59%   |
| 512   | 4        | 0.4%    |
| 24576 | 1        | 0.1%    |
| 15616 | 1        | 0.1%    |
| 12333 | 1        | 0.1%    |
| 3072  | 1        | 0.1%    |
| 256   | 1        | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 219      | 21.16%  |
| 1333    | 136      | 13.14%  |
| 3200    | 87       | 8.41%   |
| 2667    | 60       | 5.8%    |
| 2400    | 53       | 5.12%   |
| 3600    | 47       | 4.54%   |
| 2133    | 42       | 4.06%   |
| 800     | 36       | 3.48%   |
| Unknown | 33       | 3.19%   |
| 667     | 31       | 3%      |
| 1867    | 21       | 2.03%   |
| 1800    | 20       | 1.93%   |
| 2666    | 19       | 1.84%   |
| 3733    | 15       | 1.45%   |
| 400     | 15       | 1.45%   |
| 3800    | 12       | 1.16%   |
| 1066    | 12       | 1.16%   |
| 2933    | 11       | 1.06%   |
| 1866    | 11       | 1.06%   |
| 4800    | 10       | 0.97%   |
| 3400    | 10       | 0.97%   |
| 1067    | 9        | 0.87%   |
| 533     | 9        | 0.87%   |
| 3466    | 7        | 0.68%   |
| 3000    | 7        | 0.68%   |
| 3866    | 6        | 0.58%   |
| 1648    | 6        | 0.58%   |
| 1334    | 6        | 0.58%   |
| 2800    | 5        | 0.48%   |
| 2000    | 5        | 0.48%   |
| 333     | 5        | 0.48%   |
| 4000    | 4        | 0.39%   |
| 3534    | 4        | 0.39%   |
| 3066    | 4        | 0.39%   |
| 2132    | 4        | 0.39%   |
| 1632    | 4        | 0.39%   |
| 49926   | 3        | 0.29%   |
| 6000    | 3        | 0.29%   |
| 5600    | 3        | 0.29%   |
| 4266    | 3        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 18       | 39.13%  |
| Samsung Electronics   | 7        | 15.22%  |
| Brother Industries    | 7        | 15.22%  |
| Canon                 | 5        | 10.87%  |
| Seiko Epson           | 4        | 8.7%    |
| Prolific Technology   | 2        | 4.35%   |
| Oki Data              | 1        | 2.17%   |
| Lexmark International | 1        | 2.17%   |
| Apple                 | 1        | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 2        | 4.35%   |
| HP DeskJet 4100 series                       | 2        | 4.35%   |
| HP DeskJet 2600 series                       | 2        | 4.35%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 2.17%   |
| Seiko Epson L3210 Series                     | 1        | 2.17%   |
| Seiko Epson ET-4850 Series                   | 1        | 2.17%   |
| Seiko Epson ET-2710 Series                   | 1        | 2.17%   |
| Samsung SCX-6x55X Series                     | 1        | 2.17%   |
| Samsung ML-216x Series Laser Printer         | 1        | 2.17%   |
| Samsung ML-1865                              | 1        | 2.17%   |
| Samsung ML-1660 Series                       | 1        | 2.17%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 2.17%   |
| Samsung M2020 Series                         | 1        | 2.17%   |
| Samsung Composite Device                     | 1        | 2.17%   |
| Oki Data MC363 Multifunction Printer         | 1        | 2.17%   |
| Lexmark International MS510dn                | 1        | 2.17%   |
| HP Printing Support                          | 1        | 2.17%   |
| HP PhotoSmart 7150                           | 1        | 2.17%   |
| HP OfficeJet Pro 6960                        | 1        | 2.17%   |
| HP OfficeJet 8010 series                     | 1        | 2.17%   |
| HP OfficeJet 3830 series                     | 1        | 2.17%   |
| HP LaserJet 1020                             | 1        | 2.17%   |
| HP LaserJet 1015                             | 1        | 2.17%   |
| HP ENVY 5000 series                          | 1        | 2.17%   |
| HP DeskJet 6940 series                       | 1        | 2.17%   |
| HP DeskJet 4530 series                       | 1        | 2.17%   |
| HP DeskJet 3630 series                       | 1        | 2.17%   |
| HP DeskJet 2700 series                       | 1        | 2.17%   |
| HP DeskJet 2300 series                       | 1        | 2.17%   |
| HP Color LaserJet CP1215                     | 1        | 2.17%   |
| Canon PIXMA MG3600 Series                    | 1        | 2.17%   |
| Canon MF4010 series                          | 1        | 2.17%   |
| Canon LiDE 400                               | 1        | 2.17%   |
| Canon iP4900 series                          | 1        | 2.17%   |
| Canon G3010 series                           | 1        | 2.17%   |
| Brother QL-600 Label Printer                 | 1        | 2.17%   |
| Brother MFC-L6900DW series                   | 1        | 2.17%   |
| Brother MFC-L2690DW                          | 1        | 2.17%   |
| Brother MFC-J6530DW                          | 1        | 2.17%   |
| Brother HL-L2350DW series                    | 1        | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 66.67%  |
| Hewlett-Packard | 2        | 22.22%  |
| Seiko Epson     | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 11.11%  |
| HP Scanjet G2710                                  | 1        | 11.11%  |
| HP ScanJet 2400c                                  | 1        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20                | 1        | 11.11%  |
| Canon CanoScan N650U/N656U                        | 1        | 11.11%  |
| Canon CanoScan LIDE 25                            | 1        | 11.11%  |
| Canon CanoScan LiDE 220                           | 1        | 11.11%  |
| Canon CanoScan LiDE 110                           | 1        | 11.11%  |
| Canon CanoScan 1220U                              | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 32       | 32.65%  |
| Microsoft                     | 7        | 7.14%   |
| Microdia                      | 7        | 7.14%   |
| Z-Star Microelectronics       | 4        | 4.08%   |
| Unknown                       | 3        | 3.06%   |
| Sunplus Innovation Technology | 3        | 3.06%   |
| Hewlett-Packard               | 3        | 3.06%   |
| Chicony Electronics           | 3        | 3.06%   |
| Sunplus IT                    | 2        | 2.04%   |
| Realtek Semiconductor         | 2        | 2.04%   |
| MacroSilicon                  | 2        | 2.04%   |
| KYE Systems (Mouse Systems)   | 2        | 2.04%   |
| Generalplus Technology        | 2        | 2.04%   |
| GEMBIRD                       | 2        | 2.04%   |
| Creative Technology           | 2        | 2.04%   |
| Bison Electronics             | 2        | 2.04%   |
| ASUSTek Computer              | 2        | 2.04%   |
| Arkmicro Technologies         | 2        | 2.04%   |
| ARC International             | 2        | 2.04%   |
| WaveRider Communications      | 1        | 1.02%   |
| Valve Software                | 1        | 1.02%   |
| SunplusIT                     | 1        | 1.02%   |
| Polycom                       | 1        | 1.02%   |
| Pixart Imaging                | 1        | 1.02%   |
| Netchip Technology            | 1        | 1.02%   |
| Jieli Technology              | 1        | 1.02%   |
| IOGEAR                        | 1        | 1.02%   |
| Genesys Logic                 | 1        | 1.02%   |
| ezcap                         | 1        | 1.02%   |
| eMPIA Technology              | 1        | 1.02%   |
| Apple                         | 1        | 1.02%   |
| A4Tech                        | 1        | 1.02%   |
| 2M UVC CAMERA                 | 1        | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Logitech Webcam C270                          | 8        | 8.16%   |
| Logitech C922 Pro Stream Webcam               | 4        | 4.08%   |
| Unknown HD camera                             | 3        | 3.06%   |
| Logitech HD Webcam C615                       | 3        | 3.06%   |
| Z-Star Venus USB2.0 Camera                    | 2        | 2.04%   |
| Sunplus Full HD webcam                        | 2        | 2.04%   |
| Microsoft LifeCam VX-500 [1357]               | 2        | 2.04%   |
| Microsoft LifeCam HD-3000                     | 2        | 2.04%   |
| Microdia USB 2.0 Camera                       | 2        | 2.04%   |
| Microdia Integrated Camera                    | 2        | 2.04%   |
| Logitech Webcam C930e                         | 2        | 2.04%   |
| Logitech Webcam C170                          | 2        | 2.04%   |
| HP Webcam HD 2300                             | 2        | 2.04%   |
| Generalplus CAMERA - UVC                      | 2        | 2.04%   |
| GEMBIRD USB2.0 PC CAMERA                      | 2        | 2.04%   |
| Chicony HP High Definition 1MP Webcam         | 2        | 2.04%   |
| ASUS CU4K30 UVC UHD Video                     | 2        | 2.04%   |
| ARC International Camera                      | 2        | 2.04%   |
| Z-Star Vimicro USB Camera (Altair)            | 1        | 1.02%   |
| Z-Star Integrated Camera                      | 1        | 1.02%   |
| WaveRider USB Live camera                     | 1        | 1.02%   |
| Valve Software 3D Camera                      | 1        | 1.02%   |
| SunplusIT Depstech webcam                     | 1        | 1.02%   |
| Sunplus IT PC Camera                          | 1        | 1.02%   |
| Sunplus IT 1080P Webcam                       | 1        | 1.02%   |
| Sunplus USB 2.0 Camera                        | 1        | 1.02%   |
| Realtek Thronmax Stream Go Pro Webcam         | 1        | 1.02%   |
| Realtek FULL HD 1080P Webcam                  | 1        | 1.02%   |
| Polycom Poly Studio P5 webcam                 | 1        | 1.02%   |
| Pixart Imaging Digital_Camera                 | 1        | 1.02%   |
| Netchip Nuroum V11                            | 1        | 1.02%   |
| Microsoft LifeCam VX-700                      | 1        | 1.02%   |
| Microsoft LifeCam VX-5000                     | 1        | 1.02%   |
| Microsoft LifeCam Studio                      | 1        | 1.02%   |
| Microdia Webcam Vitade AF                     | 1        | 1.02%   |
| Microdia JOYACCESS JA-Webcam                  | 1        | 1.02%   |
| Microdia AUKEY PC-LM3                         | 1        | 1.02%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 1.02%   |
| MacroSilicon MiraBox Capture                  | 1        | 1.02%   |
| Logitech Webcam C925e                         | 1        | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Upek   | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 1        | 16.67%  |
| Gemalto (was Gemplus) | 1        | 16.67%  |
| Chicony Electronics   | 1        | 16.67%  |
| CHERRY                | 1        | 16.67%  |
| Alcor Micro           | 1        | 16.67%  |
| Advanced Card Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| OmniKey CardMan 3121 (HID Technologies)              | 1        | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 1        | 16.67%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 16.67%  |
| CHERRY SmartCard Reader Keyboard KC 1000 SC          | 1        | 16.67%  |
| Alcor Micro Watchdata W 1981                         | 1        | 16.67%  |
| Advanced Card Systems ACR38 SmartCard Reader         | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 825      | 91.87%  |
| 1     | 66       | 7.35%   |
| 2     | 7        | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 37       | 49.33%  |
| Net/wireless             | 10       | 13.33%  |
| Unassigned class         | 9        | 12%     |
| Communication controller | 6        | 8%      |
| Multimedia controller    | 5        | 6.67%   |
| Chipcard                 | 4        | 5.33%   |
| Storage/raid             | 2        | 2.67%   |
| Fingerprint reader       | 1        | 1.33%   |
| Card reader              | 1        | 1.33%   |

