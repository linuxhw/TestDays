Linux in Lithuania - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 191

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X470 Taichi Ultimate        | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | H81M-P33                    | [f59a3c2021](https://linux-hardware.org/?probe=f59a3c2021) | Oct 25, 2023 |
| MSI           | H81M-P33                    | [04b9d686b6](https://linux-hardware.org/?probe=04b9d686b6) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| ASRock        | B450M Pro4                  | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| ASRock        | B450M Pro4                  | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| Intel         | D915GAV AAC64134-400        | [c7cad9e093](https://linux-hardware.org/?probe=c7cad9e093) | Aug 20, 2023 |
| ASRock        | B450M-HDV R4.0              | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| ASUSTek       | PRIME H410M-K               | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | P5KPL-VM                    | [e2919326cd](https://linux-hardware.org/?probe=e2919326cd) | Jun 16, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| ASRock        | QC5000M-ITX/PH              | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| HP            | 0B4Ch D                     | [0f593c947e](https://linux-hardware.org/?probe=0f593c947e) | May 27, 2023 |
| HP            | 0B4Ch D                     | [e7a8d68439](https://linux-hardware.org/?probe=e7a8d68439) | May 27, 2023 |
| Unknown       | Unknown                     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [db7e2a1d87](https://linux-hardware.org/?probe=db7e2a1d87) | Apr 29, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| ASUSTek       | P8B75-V                     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| HP            | 1850                        | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| ASRock        | H67M-GE/HT                  | [3410887193](https://linux-hardware.org/?probe=3410887193) | Feb 25, 2023 |
| Gigabyte      | GB-BSi5-1135G7              | [93002e901f](https://linux-hardware.org/?probe=93002e901f) | Feb 10, 2023 |
| MSI           | H61M-P23                    | [86404b5b68](https://linux-hardware.org/?probe=86404b5b68) | Feb 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Gigabyte      | B550M DS3H                  | [10ae4cbb25](https://linux-hardware.org/?probe=10ae4cbb25) | Jan 08, 2023 |
| Gigabyte      | H410M H V3                  | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| HP            | 3397                        | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| HP            | 3047h                       | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASUSTek       | M5A97 R2.0                  | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| MSI           | MAG B460M MORTAR            | [258d99cc9e](https://linux-hardware.org/?probe=258d99cc9e) | Sep 06, 2022 |
| Gigabyte      | GA-970A-D3                  | [5ee4e3aec0](https://linux-hardware.org/?probe=5ee4e3aec0) | Sep 02, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| Dell          | 07T4MC A11                  | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| MSI           | Z270-A PRO                  | [0d78267c59](https://linux-hardware.org/?probe=0d78267c59) | Jun 16, 2022 |
| Dell          | 02YYK5 A01                  | [bd3336efcb](https://linux-hardware.org/?probe=bd3336efcb) | Jun 14, 2022 |
| Dell          | 02YYK5 A01                  | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| Dell          | 02YYK5 A01                  | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| Dell          | 03NVJ6 A02                  | [9e90322621](https://linux-hardware.org/?probe=9e90322621) | May 06, 2022 |
| Dell          | 03NVJ6 A02                  | [08e665f8bf](https://linux-hardware.org/?probe=08e665f8bf) | May 04, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| Dell          | 02YYK5 A01                  | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Gigabyte      | B450M S2H                   | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| MSI           | B350 PC MATE                | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASRock        | QC5000M-ITX/PH              | [573ff5a0d0](https://linux-hardware.org/?probe=573ff5a0d0) | Feb 16, 2022 |
| MSI           | B450M MORTAR MAX            | [54f55cc209](https://linux-hardware.org/?probe=54f55cc209) | Feb 16, 2022 |
| ASUSTek       | Maximus Formula             | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| ASRock        | B450 Pro4                   | [cc0c8de988](https://linux-hardware.org/?probe=cc0c8de988) | Nov 27, 2021 |
| Dell          | 084J0R A00                  | [2f5b5e4c72](https://linux-hardware.org/?probe=2f5b5e4c72) | Nov 19, 2021 |
| Dell          | 084J0R A00                  | [1907e644a0](https://linux-hardware.org/?probe=1907e644a0) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| MSI           | MEG X570 UNIFY              | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| MSI           | B85M GAMING                 | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | X79-DELUXE                  | [c49552f889](https://linux-hardware.org/?probe=c49552f889) | Oct 14, 2021 |
| ASUSTek       | X79-DELUXE                  | [d606b23e02](https://linux-hardware.org/?probe=d606b23e02) | Oct 14, 2021 |
| ASUSTek       | Maximus Formula             | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| HP            | 09F8h                       | [60e1a81b56](https://linux-hardware.org/?probe=60e1a81b56) | Sep 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [057cfec49e](https://linux-hardware.org/?probe=057cfec49e) | Sep 01, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [523f5ca193](https://linux-hardware.org/?probe=523f5ca193) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [90e24e0335](https://linux-hardware.org/?probe=90e24e0335) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI           | MAG B460M MORTAR            | [652f1a31e9](https://linux-hardware.org/?probe=652f1a31e9) | Aug 10, 2021 |
| MSI           | MAG B460M MORTAR            | [80648f256b](https://linux-hardware.org/?probe=80648f256b) | Aug 10, 2021 |
| ASRock        | G31M-VS2                    | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | Z87 Extreme4                | [ee3189a7be](https://linux-hardware.org/?probe=ee3189a7be) | Jul 11, 2021 |
| ASRock        | X570M Pro4                  | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| Gigabyte      | P41-ES3G                    | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ASUSTek       | PRIME B450M-K               | [e78af672d3](https://linux-hardware.org/?probe=e78af672d3) | Jun 18, 2021 |
| MSI           | H81M-P33                    | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| Gigabyte      | M55S-S3                     | [7114f9857a](https://linux-hardware.org/?probe=7114f9857a) | Apr 29, 2021 |
| ASUSTek       | PRIME B450M-K               | [dc665ba00d](https://linux-hardware.org/?probe=dc665ba00d) | Apr 14, 2021 |
| Gigabyte      | B85M-HD3                    | [499ccddfc2](https://linux-hardware.org/?probe=499ccddfc2) | Apr 09, 2021 |
| MSI           | MAG B460M MORTAR            | [f7341fd5b2](https://linux-hardware.org/?probe=f7341fd5b2) | Apr 01, 2021 |
| Gigabyte      | H81M-D2V                    | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| HP            | 805A                        | [76ad927d3b](https://linux-hardware.org/?probe=76ad927d3b) | Mar 18, 2021 |
| Gigabyte      | B85M-HD3                    | [ad58858e33](https://linux-hardware.org/?probe=ad58858e33) | Mar 17, 2021 |
| Intel         | DH67BL AAG10189-208         | [391c72b961](https://linux-hardware.org/?probe=391c72b961) | Mar 17, 2021 |
| Intel         | DH55HC AAE70933-501         | [6a44f69309](https://linux-hardware.org/?probe=6a44f69309) | Mar 17, 2021 |
| Gigabyte      | H55M-UD2H                   | [e671743616](https://linux-hardware.org/?probe=e671743616) | Mar 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [d4e62a32a8](https://linux-hardware.org/?probe=d4e62a32a8) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Gigabyte      | Z370M DS3H-CF               | [e4702a62a8](https://linux-hardware.org/?probe=e4702a62a8) | Feb 19, 2021 |
| Gigabyte      | A320M-H-CF                  | [ceffe7a79e](https://linux-hardware.org/?probe=ceffe7a79e) | Feb 16, 2021 |
| Intel         | DH61WW AAG23116-206         | [446351d845](https://linux-hardware.org/?probe=446351d845) | Feb 15, 2021 |
| ASUSTek       | Maximus Formula             | [b5e1004909](https://linux-hardware.org/?probe=b5e1004909) | Feb 12, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [504106eb2c](https://linux-hardware.org/?probe=504106eb2c) | Feb 12, 2021 |
| ASUSTek       | H87M-PLUS                   | [c951026b91](https://linux-hardware.org/?probe=c951026b91) | Feb 07, 2021 |
| ASUSTek       | Maximus Formula             | [80724d2ba1](https://linux-hardware.org/?probe=80724d2ba1) | Jan 31, 2021 |
| ASRock        | H61M/U3S3                   | [2d831a72bb](https://linux-hardware.org/?probe=2d831a72bb) | Jan 27, 2021 |
| Gigabyte      | B250M-D3H-CF                | [a38c700d1b](https://linux-hardware.org/?probe=a38c700d1b) | Jan 16, 2021 |
| ASUSTek       | H87M-PLUS                   | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASUSTek       | Leonite2                    | [9867e750d0](https://linux-hardware.org/?probe=9867e750d0) | Jan 01, 2021 |
| ASRock        | B450M Pro4                  | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [5c89245f08](https://linux-hardware.org/?probe=5c89245f08) | Dec 02, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| Gigabyte      | H81M-D2V                    | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| ASRock        | 880GM-LE FX                 | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| Gigabyte      | H77M-D3H                    | [2788cb02ed](https://linux-hardware.org/?probe=2788cb02ed) | Nov 08, 2020 |
| HP            | 3048h                       | [96c9bd0ab6](https://linux-hardware.org/?probe=96c9bd0ab6) | Nov 05, 2020 |
| MSI           | Z87M-G43                    | [9de0cc7bbf](https://linux-hardware.org/?probe=9de0cc7bbf) | Nov 03, 2020 |
| HP            | 0A64h                       | [88899b775b](https://linux-hardware.org/?probe=88899b775b) | Oct 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [a5e1c0e5f3](https://linux-hardware.org/?probe=a5e1c0e5f3) | Oct 03, 2020 |
| ASUSTek       | H87M-PLUS                   | [0362c406d8](https://linux-hardware.org/?probe=0362c406d8) | Oct 03, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [b765d71b82](https://linux-hardware.org/?probe=b765d71b82) | Sep 28, 2020 |
| Gigabyte      | H81M-D2V                    | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-R               | [0097d71249](https://linux-hardware.org/?probe=0097d71249) | Sep 04, 2020 |
| ASUSTek       | PRIME Z390-A                | [4bd12a2bcc](https://linux-hardware.org/?probe=4bd12a2bcc) | Aug 25, 2020 |
| ASRock        | AB350M Pro4                 | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| Gigabyte      | M68MT-S2P                   | [f6a94becbf](https://linux-hardware.org/?probe=f6a94becbf) | Aug 13, 2020 |
| MSI           | H81M-P33                    | [5d7abb7a5b](https://linux-hardware.org/?probe=5d7abb7a5b) | Jul 31, 2020 |
| ASUSTek       | PRIME H310M-E               | [f31ba594be](https://linux-hardware.org/?probe=f31ba594be) | Jul 19, 2020 |
| ASUSTek       | PRIME H310M-E               | [90f3c751dc](https://linux-hardware.org/?probe=90f3c751dc) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [ab2ec330ab](https://linux-hardware.org/?probe=ab2ec330ab) | Jun 24, 2020 |
| ASUSTek       | M5A97 R2.0                  | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| Intel         | DP55WB AAE64798-205         | [cbc58485b8](https://linux-hardware.org/?probe=cbc58485b8) | Apr 23, 2020 |
| MSI           | H61M-P20                    | [bd9fc44d34](https://linux-hardware.org/?probe=bd9fc44d34) | Mar 17, 2020 |
| MSI           | H61M-P20                    | [9111061475](https://linux-hardware.org/?probe=9111061475) | Mar 10, 2020 |
| MSI           | Z170A GAMING M5             | [f1eb3e7e12](https://linux-hardware.org/?probe=f1eb3e7e12) | Mar 01, 2020 |
| MSI           | Z170A GAMING M5             | [7058bdb7d6](https://linux-hardware.org/?probe=7058bdb7d6) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | [816d9c42da](https://linux-hardware.org/?probe=816d9c42da) | Feb 28, 2020 |
| HP            | 1589                        | [0c9be85544](https://linux-hardware.org/?probe=0c9be85544) | Feb 21, 2020 |
| ASUSTek       | P8Z68-V LX                  | [2d24c5a932](https://linux-hardware.org/?probe=2d24c5a932) | Feb 15, 2020 |
| ASUSTek       | PRIME B350M-A               | [c95a831b3c](https://linux-hardware.org/?probe=c95a831b3c) | Feb 11, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| MSI           | B450M PRO-VDH               | [5b95761a5d](https://linux-hardware.org/?probe=5b95761a5d) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH V2            | [660da3e630](https://linux-hardware.org/?probe=660da3e630) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH               | [f45d7203c0](https://linux-hardware.org/?probe=f45d7203c0) | Jan 03, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b0c00423bd](https://linux-hardware.org/?probe=b0c00423bd) | Dec 31, 2019 |
| MSI           | B450M PRO-VDH               | [924e886e1f](https://linux-hardware.org/?probe=924e886e1f) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | [4a5d98c236](https://linux-hardware.org/?probe=4a5d98c236) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | [b919c0cb27](https://linux-hardware.org/?probe=b919c0cb27) | Dec 13, 2019 |
| ASRock        | H61M-VS                     | [6d7e3aa70a](https://linux-hardware.org/?probe=6d7e3aa70a) | Dec 11, 2019 |
| ASUSTek       | H110M-R                     | [3068ae6e29](https://linux-hardware.org/?probe=3068ae6e29) | Nov 05, 2019 |
| ASUSTek       | H110M-R                     | [dc23169db8](https://linux-hardware.org/?probe=dc23169db8) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | [ec4b0c74d2](https://linux-hardware.org/?probe=ec4b0c74d2) | Sep 27, 2019 |
| HP            | 0A60h                       | [e587b4122a](https://linux-hardware.org/?probe=e587b4122a) | Sep 22, 2019 |
| Gigabyte      | B250M-DS3H-CF               | [fd394cc113](https://linux-hardware.org/?probe=fd394cc113) | Jun 05, 2019 |
| ASRock        | X370 Taichi                 | [283ce85ac6](https://linux-hardware.org/?probe=283ce85ac6) | Feb 20, 2019 |
| Dell          | 0XFWHV A00                  | [f9e47efc1f](https://linux-hardware.org/?probe=f9e47efc1f) | Jan 12, 2019 |
| MSI           | Z170A GAMING M5             | [68365011c2](https://linux-hardware.org/?probe=68365011c2) | Oct 26, 2018 |
| Intel         | DB65AL AAG12530-302         | [be0b280760](https://linux-hardware.org/?probe=be0b280760) | Oct 25, 2018 |
| HP            | 0A60h                       | [887d9e063a](https://linux-hardware.org/?probe=887d9e063a) | Sep 24, 2018 |
| HP            | 0A60h                       | [180ad06c55](https://linux-hardware.org/?probe=180ad06c55) | Aug 21, 2018 |
| HP            | 0A60h                       | [4ed0a42e5c](https://linux-hardware.org/?probe=4ed0a42e5c) | Jun 30, 2018 |
| ASUSTek       | M4A785T-M                   | [0f2664d3b1](https://linux-hardware.org/?probe=0f2664d3b1) | Mar 29, 2018 |
| ASUSTek       | M4A785T-M                   | [1a91c5f47f](https://linux-hardware.org/?probe=1a91c5f47f) | Mar 05, 2018 |
| Intel         | D102GGC2 AAD42789-201       | [d52ebc3540](https://linux-hardware.org/?probe=d52ebc3540) | Jan 09, 2018 |
| Intel         | D102GGC2 AAD42789-201       | [16d64740e8](https://linux-hardware.org/?probe=16d64740e8) | Jan 09, 2018 |
| ASRock        | ALiveDual-eSATA2            | [7330a7e461](https://linux-hardware.org/?probe=7330a7e461) | Sep 27, 2017 |
| ASRock        | 980DE3/U3S3 R2.0            | [ce9b629fa0](https://linux-hardware.org/?probe=ce9b629fa0) | Apr 21, 2017 |
| ASRock        | G41M-VS3                    | [8915ed904a](https://linux-hardware.org/?probe=8915ed904a) | Mar 14, 2017 |
| ASRock        | G41C-VS                     | [3688013a36](https://linux-hardware.org/?probe=3688013a36) | Dec 02, 2016 |
| ASRock        | G41C-VS                     | [9f9c0116cd](https://linux-hardware.org/?probe=9f9c0116cd) | Nov 30, 2016 |
| ASRock        | G41C-VS                     | [a1993f9fc4](https://linux-hardware.org/?probe=a1993f9fc4) | Nov 28, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 7        | 4.93%   |
| Ubuntu 18.04                 | 6        | 4.23%   |
| Arch                         | 6        | 4.23%   |
| Ubuntu 22.04                 | 5        | 3.52%   |
| Arch Rolling                 | 5        | 3.52%   |
| Ubuntu 21.10                 | 4        | 2.82%   |
| Ubuntu 19.10                 | 4        | 2.82%   |
| OpenMandriva 23.01           | 4        | 2.82%   |
| Manjaro                      | 4        | 2.82%   |
| Debian 11                    | 4        | 2.82%   |
| ROSA R8.1                    | 3        | 2.11%   |
| ROSA R11                     | 3        | 2.11%   |
| ROSA R10                     | 3        | 2.11%   |
| Pop!_OS 22.04                | 3        | 2.11%   |
| Pop!_OS 21.10                | 3        | 2.11%   |
| Pop!_OS 21.04                | 3        | 2.11%   |
| OpenMandriva 4.2             | 3        | 2.11%   |
| Manjaro 20.2.1               | 3        | 2.11%   |
| KDE neon 20.04               | 3        | 2.11%   |
| Fedora 33                    | 3        | 2.11%   |
| Zorin 16                     | 2        | 1.41%   |
| Ubuntu 23.04                 | 2        | 1.41%   |
| Ubuntu 20.10                 | 2        | 1.41%   |
| ROSA 12.2                    | 2        | 1.41%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.41%   |
| OpenMandriva 23.03           | 2        | 1.41%   |
| Linux Mint 19.3              | 2        | 1.41%   |
| Kubuntu 20.04                | 2        | 1.41%   |
| Fedora 32                    | 2        | 1.41%   |
| Debian 10                    | 2        | 1.41%   |
| ArcoLinux Rolling            | 2        | 1.41%   |
| Xubuntu 20.04                | 1        | 0.7%    |
| Ubuntu Unity 16.04           | 1        | 0.7%    |
| ROSA R9                      | 1        | 0.7%    |
| ROSA R8                      | 1        | 0.7%    |
| ROSA R11.1                   | 1        | 0.7%    |
| RHEL 8                       | 1        | 0.7%    |
| Pop!_OS 20.10                | 1        | 0.7%    |
| Pop!_OS 20.04                | 1        | 0.7%    |
| OpenMandriva 4.3             | 1        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 29       | 21.8%   |
| ROSA         | 13       | 9.77%   |
| Pop!_OS      | 11       | 8.27%   |
| OpenMandriva | 11       | 8.27%   |
| Manjaro      | 11       | 8.27%   |
| Linux Mint   | 9        | 6.77%   |
| Arch         | 9        | 6.77%   |
| Fedora       | 6        | 4.51%   |
| Debian       | 6        | 4.51%   |
| Kubuntu      | 4        | 3.01%   |
| KDE neon     | 4        | 3.01%   |
| Zorin        | 2        | 1.5%    |
| openSUSE     | 2        | 1.5%    |
| Nobara       | 2        | 1.5%    |
| ArcoLinux    | 2        | 1.5%    |
| Xubuntu      | 1        | 0.75%   |
| Ubuntu Unity | 1        | 0.75%   |
| RHEL         | 1        | 0.75%   |
| Lubuntu      | 1        | 0.75%   |
| Garuda Linux | 1        | 0.75%   |
| Endless      | 1        | 0.75%   |
| EndeavourOS  | 1        | 0.75%   |
| Elementary   | 1        | 0.75%   |
| Deepin       | 1        | 0.75%   |
| Clear Linux  | 1        | 0.75%   |
| CentOS       | 1        | 0.75%   |
| Artix        | 1        | 0.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.1.1-desktop-1omv2290        | 4        | 2.58%   |
| 5.3.0-23-generic              | 3        | 1.94%   |
| 5.10.14-desktop-1omv4002      | 3        | 1.94%   |
| 6.2.6-desktop-1omv2390        | 2        | 1.29%   |
| 6.2.0-20-generic              | 2        | 1.29%   |
| 6.1.31-1-lts                  | 2        | 1.29%   |
| 5.9.16-1-MANJARO              | 2        | 1.29%   |
| 5.4.0-70-generic              | 2        | 1.29%   |
| 5.4.0-66-generic              | 2        | 1.29%   |
| 5.4.0-48-generic              | 2        | 1.29%   |
| 5.4.0-26-generic              | 2        | 1.29%   |
| 5.3.0-40-generic              | 2        | 1.29%   |
| 5.3.0-28-generic              | 2        | 1.29%   |
| 5.3.0-24-generic              | 2        | 1.29%   |
| 5.19.0-41-generic             | 2        | 1.29%   |
| 5.15.23-2-lts                 | 2        | 1.29%   |
| 5.15.0-47-generic             | 2        | 1.29%   |
| 5.15.0-46-generic             | 2        | 1.29%   |
| 5.11.0-7620-generic           | 2        | 1.29%   |
| 4.9.60-nrj-desktop-1rosa-i586 | 2        | 1.29%   |
| 6.4.9-zen1-1-zen              | 1        | 0.65%   |
| 6.4.12-arch1-1                | 1        | 0.65%   |
| 6.4.10-202.fsync.fc38.x86_64  | 1        | 0.65%   |
| 6.3.8-200.fc38.x86_64         | 1        | 0.65%   |
| 6.3.5-desktop-3omv2390        | 1        | 0.65%   |
| 6.3.5-arch1-1                 | 1        | 0.65%   |
| 6.2.6-76060206-generic        | 1        | 0.65%   |
| 6.2.0-35-generic              | 1        | 0.65%   |
| 6.1.0-6-amd64                 | 1        | 0.65%   |
| 6.1.0-13-amd64                | 1        | 0.65%   |
| 6.0.9-201.fc36.x86_64         | 1        | 0.65%   |
| 6.0.7-1207.native             | 1        | 0.65%   |
| 5.9.13-arch1-1                | 1        | 0.65%   |
| 5.8.3-zen1-1-zen              | 1        | 0.65%   |
| 5.8.17-300.fc33.x86_64        | 1        | 0.65%   |
| 5.8.12-200.fc32.x86_64        | 1        | 0.65%   |
| 5.8.0-7642-generic            | 1        | 0.65%   |
| 5.8.0-48-generic              | 1        | 0.65%   |
| 5.8.0-45-generic              | 1        | 0.65%   |
| 5.8.0-29-generic              | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 13       | 8.9%    |
| 5.15.0  | 10       | 6.85%   |
| 5.3.0   | 8        | 5.48%   |
| 5.13.0  | 8        | 5.48%   |
| 4.15.0  | 8        | 5.48%   |
| 5.8.0   | 6        | 4.11%   |
| 5.11.0  | 6        | 4.11%   |
| 6.1.1   | 4        | 2.74%   |
| 6.2.6   | 3        | 2.05%   |
| 6.2.0   | 3        | 2.05%   |
| 5.19.0  | 3        | 2.05%   |
| 5.10.14 | 3        | 2.05%   |
| 5.10.0  | 3        | 2.05%   |
| 6.3.5   | 2        | 1.37%   |
| 6.1.31  | 2        | 1.37%   |
| 6.1.0   | 2        | 1.37%   |
| 5.9.16  | 2        | 1.37%   |
| 5.15.23 | 2        | 1.37%   |
| 4.9.60  | 2        | 1.37%   |
| 4.19.0  | 2        | 1.37%   |
| 6.4.9   | 1        | 0.68%   |
| 6.4.12  | 1        | 0.68%   |
| 6.4.10  | 1        | 0.68%   |
| 6.3.8   | 1        | 0.68%   |
| 6.0.9   | 1        | 0.68%   |
| 6.0.7   | 1        | 0.68%   |
| 5.9.13  | 1        | 0.68%   |
| 5.8.3   | 1        | 0.68%   |
| 5.8.17  | 1        | 0.68%   |
| 5.8.12  | 1        | 0.68%   |
| 5.7.8   | 1        | 0.68%   |
| 5.7.17  | 1        | 0.68%   |
| 5.7.11  | 1        | 0.68%   |
| 5.6.6   | 1        | 0.68%   |
| 5.5.3   | 1        | 0.68%   |
| 5.4.70  | 1        | 0.68%   |
| 5.4.50  | 1        | 0.68%   |
| 5.4.18  | 1        | 0.68%   |
| 5.19.15 | 1        | 0.68%   |
| 5.19.1  | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 11.03%  |
| 5.4     | 15       | 10.34%  |
| 5.10    | 12       | 8.28%   |
| 5.8     | 9        | 6.21%   |
| 5.13    | 9        | 6.21%   |
| 6.1     | 8        | 5.52%   |
| 5.3     | 8        | 5.52%   |
| 4.15    | 8        | 5.52%   |
| 5.11    | 7        | 4.83%   |
| 4.9     | 7        | 4.83%   |
| 6.2     | 6        | 4.14%   |
| 5.19    | 5        | 3.45%   |
| 5.16    | 5        | 3.45%   |
| 6.4     | 3        | 2.07%   |
| 6.3     | 3        | 2.07%   |
| 5.9     | 3        | 2.07%   |
| 5.7     | 3        | 2.07%   |
| 5.12    | 3        | 2.07%   |
| 4.19    | 3        | 2.07%   |
| 4.14    | 3        | 2.07%   |
| 6.0     | 2        | 1.38%   |
| 5.18    | 2        | 1.38%   |
| 4.1     | 2        | 1.38%   |
| 5.6     | 1        | 0.69%   |
| 5.5     | 1        | 0.69%   |
| 4.18    | 1        | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 126      | 96.18%  |
| i686   | 5        | 3.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 51       | 36.96%  |
| KDE5          | 27       | 19.57%  |
| XFCE          | 12       | 8.7%    |
| Unknown       | 12       | 8.7%    |
| KDE4          | 10       | 7.25%   |
| X-Cinnamon    | 7        | 5.07%   |
| KDE           | 7        | 5.07%   |
| Cinnamon      | 3        | 2.17%   |
| MATE          | 2        | 1.45%   |
| Unity         | 1        | 0.72%   |
| qtile         | 1        | 0.72%   |
| Pantheon      | 1        | 0.72%   |
| LXQt          | 1        | 0.72%   |
| i3            | 1        | 0.72%   |
| Enlightenment | 1        | 0.72%   |
| Deepin        | 1        | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 110      | 80.88%  |
| Wayland | 20       | 14.71%  |
| Tty     | 5        | 3.68%   |
| Unknown | 1        | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 42.22%  |
| SDDM    | 23       | 17.04%  |
| GDM     | 16       | 11.85%  |
| LightDM | 14       | 10.37%  |
| KDM     | 10       | 7.41%   |
| GDM3    | 9        | 6.67%   |
| TDM     | 6        | 4.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 81       | 61.36%  |
| lt_LT   | 16       | 12.12%  |
| Unknown | 16       | 12.12%  |
| en_GB   | 10       | 7.58%   |
| ru_RU   | 7        | 5.3%    |
| uk_UA   | 1        | 0.76%   |
| C       | 1        | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 87       | 65.91%  |
| EFI  | 45       | 34.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 94       | 70.68%  |
| Btrfs   | 13       | 9.77%   |
| Overlay | 12       | 9.02%   |
| Unknown | 7        | 5.26%   |
| Xfs     | 3        | 2.26%   |
| Tmpfs   | 3        | 2.26%   |
| SAMSUNG | 1        | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 44.03%  |
| GPT     | 45       | 33.58%  |
| MBR     | 30       | 22.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 82.31%  |
| Yes       | 23       | 17.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 67.67%  |
| Yes       | 43       | 32.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 36       | 27.69%  |
| ASRock              | 24       | 18.46%  |
| Gigabyte Technology | 23       | 17.69%  |
| MSI                 | 19       | 14.62%  |
| Hewlett-Packard     | 11       | 8.46%   |
| Intel               | 7        | 5.38%   |
| Dell                | 5        | 3.85%   |
| Lenovo              | 1        | 0.77%   |
| Fujitsu Siemens     | 1        | 0.77%   |
| Fujitsu             | 1        | 0.77%   |
| BESSTAR Tech        | 1        | 0.77%   |
| Unknown             | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7A38                        | 3        | 2.31%   |
| MSI MS-7817                        | 3        | 2.31%   |
| ASUS All Series                    | 3        | 2.31%   |
| MSI MS-7C82                        | 2        | 1.54%   |
| MSI MS-7A34                        | 2        | 1.54%   |
| MSI MS-7823                        | 2        | 1.54%   |
| ASUS TUF Gaming X570-PLUS          | 2        | 1.54%   |
| ASUS TUF Gaming B550-PLUS          | 2        | 1.54%   |
| ASUS PRIME Z390-A                  | 2        | 1.54%   |
| ASUS PRIME B450M-K                 | 2        | 1.54%   |
| ASUS PRIME B450M-A                 | 2        | 1.54%   |
| ASRock B450 Pro4                   | 2        | 1.54%   |
| MSI MS-7C35                        | 1        | 0.77%   |
| MSI MS-7B89                        | 1        | 0.77%   |
| MSI MS-7B18                        | 1        | 0.77%   |
| MSI MS-7A71                        | 1        | 0.77%   |
| MSI MS-7977                        | 1        | 0.77%   |
| MSI MS-7788                        | 1        | 0.77%   |
| MSI MS-7680                        | 1        | 0.77%   |
| Lenovo ThinkCentre M81 5048E2G     | 1        | 0.77%   |
| Intel DP55WB AAE64798-205          | 1        | 0.77%   |
| Intel DH67BL AAG10189-208          | 1        | 0.77%   |
| Intel DH61WW AAG23116-206          | 1        | 0.77%   |
| Intel DH55HC AAE70933-501          | 1        | 0.77%   |
| Intel DB65AL AAG12530-302          | 1        | 0.77%   |
| Intel D915GAV AAC64134-400         | 1        | 0.77%   |
| Intel D102GGC2 AAD42789-201        | 1        | 0.77%   |
| HP Z420 Workstation                | 1        | 0.77%   |
| HP Z400 Workstation                | 1        | 0.77%   |
| HP EliteDesk 800 G1 DM             | 1        | 0.77%   |
| HP EliteDesk 705 G2 SFF            | 1        | 0.77%   |
| HP Compaq Pro 6305 MT              | 1        | 0.77%   |
| HP Compaq Elite 8300 SFF           | 1        | 0.77%   |
| HP Compaq dc7600 Small Form Factor | 1        | 0.77%   |
| HP Compaq dc5750 Small Form Factor | 1        | 0.77%   |
| HP Compaq dc5700 Microtower        | 1        | 0.77%   |
| HP Compaq 6005 Pro MT PC           | 1        | 0.77%   |
| HP Compaq 6000 Pro SFF PC          | 1        | 0.77%   |
| Gigabyte Z370M DS3H                | 1        | 0.77%   |
| Gigabyte X570 GAMING X             | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 13       | 10%     |
| HP Compaq          | 7        | 5.38%   |
| ASUS TUF           | 5        | 3.85%   |
| MSI MS-7A38        | 3        | 2.31%   |
| MSI MS-7817        | 3        | 2.31%   |
| Gigabyte X570      | 3        | 2.31%   |
| ASUS All           | 3        | 2.31%   |
| ASRock B450        | 3        | 2.31%   |
| MSI MS-7C82        | 2        | 1.54%   |
| MSI MS-7A34        | 2        | 1.54%   |
| MSI MS-7823        | 2        | 1.54%   |
| HP EliteDesk       | 2        | 1.54%   |
| Dell Vostro        | 2        | 1.54%   |
| Dell OptiPlex      | 2        | 1.54%   |
| ASUS ROG           | 2        | 1.54%   |
| ASRock B550M       | 2        | 1.54%   |
| MSI MS-7C35        | 1        | 0.77%   |
| MSI MS-7B89        | 1        | 0.77%   |
| MSI MS-7B18        | 1        | 0.77%   |
| MSI MS-7A71        | 1        | 0.77%   |
| MSI MS-7977        | 1        | 0.77%   |
| MSI MS-7788        | 1        | 0.77%   |
| MSI MS-7680        | 1        | 0.77%   |
| Lenovo ThinkCentre | 1        | 0.77%   |
| Intel DP55WB       | 1        | 0.77%   |
| Intel DH67BL       | 1        | 0.77%   |
| Intel DH61WW       | 1        | 0.77%   |
| Intel DH55HC       | 1        | 0.77%   |
| Intel DB65AL       | 1        | 0.77%   |
| Intel D915GAV      | 1        | 0.77%   |
| Intel D102GGC2     | 1        | 0.77%   |
| HP Z420            | 1        | 0.77%   |
| HP Z400            | 1        | 0.77%   |
| Gigabyte Z370M     | 1        | 0.77%   |
| Gigabyte P41-ES3G  | 1        | 0.77%   |
| Gigabyte M68MT-S2P | 1        | 0.77%   |
| Gigabyte M55S-S3   | 1        | 0.77%   |
| Gigabyte H81M-D2V  | 1        | 0.77%   |
| Gigabyte H77M-D3H  | 1        | 0.77%   |
| Gigabyte H61M-DS2  | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 18.46%  |
| 2009 | 12       | 9.23%   |
| 2013 | 11       | 8.46%   |
| 2012 | 10       | 7.69%   |
| 2020 | 9        | 6.92%   |
| 2011 | 9        | 6.92%   |
| 2017 | 8        | 6.15%   |
| 2021 | 7        | 5.38%   |
| 2019 | 7        | 5.38%   |
| 2016 | 6        | 4.62%   |
| 2015 | 6        | 4.62%   |
| 2010 | 5        | 3.85%   |
| 2007 | 4        | 3.08%   |
| 2006 | 4        | 3.08%   |
| 2014 | 3        | 2.31%   |
| 2008 | 2        | 1.54%   |
| 2022 | 1        | 0.77%   |
| 2005 | 1        | 0.77%   |
| 2004 | 1        | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 130      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 129      | 98.47%  |
| Enabled  | 2        | 1.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 28.24%  |
| 8.01-16.0   | 24       | 18.32%  |
| 3.01-4.0    | 22       | 16.79%  |
| 32.01-64.0  | 17       | 12.98%  |
| 4.01-8.0    | 16       | 12.21%  |
| 64.01-256.0 | 7        | 5.34%   |
| 1.01-2.0    | 4        | 3.05%   |
| 2.01-3.0    | 2        | 1.53%   |
| 24.01-32.0  | 1        | 0.76%   |
| 0.51-1.0    | 1        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 42       | 28.19%  |
| 2.01-3.0   | 31       | 20.81%  |
| 4.01-8.0   | 29       | 19.46%  |
| 3.01-4.0   | 21       | 14.09%  |
| 0.51-1.0   | 12       | 8.05%   |
| 8.01-16.0  | 9        | 6.04%   |
| 24.01-32.0 | 2        | 1.34%   |
| 16.01-24.0 | 2        | 1.34%   |
| 0.01-0.5   | 1        | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 38.69%  |
| 2      | 44       | 32.12%  |
| 3      | 25       | 18.25%  |
| 4      | 8        | 5.84%   |
| 5      | 6        | 4.38%   |
| 6      | 1        | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 64.93%  |
| Yes       | 47       | 35.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 130      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 69.92%  |
| Yes       | 40       | 30.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 77.69%  |
| Yes       | 29       | 22.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Lithuania | 130      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Vilnius      | 65       | 48.87%  |
| Kaunas       | 24       | 18.05%  |
| Šiauliai    | 9        | 6.77%   |
| Klaipėda    | 9        | 6.77%   |
| Alytus       | 3        | 2.26%   |
| Telšiai     | 2        | 1.5%    |
| Panevezys    | 2        | 1.5%    |
| Mažeikiai   | 2        | 1.5%    |
| Elektrėnai  | 2        | 1.5%    |
| Vainutas     | 1        | 0.75%   |
| Ukmerge      | 1        | 0.75%   |
| Trakai       | 1        | 0.75%   |
| Tauragė     | 1        | 0.75%   |
| Šilalė     | 1        | 0.75%   |
| Raseiniai    | 1        | 0.75%   |
| Nemenčinė  | 1        | 0.75%   |
| Marijampolė | 1        | 0.75%   |
| Lentvaris    | 1        | 0.75%   |
| Kėdainiai   | 1        | 0.75%   |
| Garliava     | 1        | 0.75%   |
| Gargždai    | 1        | 0.75%   |
| Druskininkai | 1        | 0.75%   |
| Anykščiai  | 1        | 0.75%   |
| Agluonenai   | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 46       | 81     | 19.01%  |
| WDC                         | 40       | 55     | 16.53%  |
| Seagate                     | 32       | 44     | 13.22%  |
| A-DATA Technology           | 21       | 25     | 8.68%   |
| Kingston                    | 18       | 29     | 7.44%   |
| Toshiba                     | 17       | 23     | 7.02%   |
| Crucial                     | 12       | 14     | 4.96%   |
| Hitachi                     | 7        | 7      | 2.89%   |
| Patriot                     | 6        | 6      | 2.48%   |
| SanDisk                     | 3        | 4      | 1.24%   |
| XPG                         | 2        | 2      | 0.83%   |
| Transcend                   | 2        | 2      | 0.83%   |
| JMicron Technology          | 2        | 2      | 0.83%   |
| Intel                       | 2        | 2      | 0.83%   |
| HGST                        | 2        | 3      | 0.83%   |
| GOODRAM                     | 2        | 2      | 0.83%   |
| Gigabyte Technology         | 2        | 2      | 0.83%   |
| China                       | 2        | 2      | 0.83%   |
| Apacer                      | 2        | 4      | 0.83%   |
| ADATA Technology            | 2        | 3      | 0.83%   |
| XrayDisk                    | 1        | 1      | 0.41%   |
| Unknown                     | 1        | 1      | 0.41%   |
| StoreJet                    | 1        | 1      | 0.41%   |
| SPCC                        | 1        | 1      | 0.41%   |
| PNY                         | 1        | 1      | 0.41%   |
| Plextor                     | 1        | 1      | 0.41%   |
| Phison                      | 1        | 1      | 0.41%   |
| OCZ                         | 1        | 2      | 0.41%   |
| Netac                       | 1        | 1      | 0.41%   |
| Micron/Crucial Technology   | 1        | 1      | 0.41%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.41%   |
| Lite-On Technology          | 1        | 1      | 0.41%   |
| Leven                       | 1        | 3      | 0.41%   |
| KIOXIA                      | 1        | 1      | 0.41%   |
| Intenso                     | 1        | 2      | 0.41%   |
| Hewlett-Packard             | 1        | 1      | 0.41%   |
| ExcelStor                   | 1        | 1      | 0.41%   |
| Dahua                       | 1        | 1      | 0.41%   |
| Corsair                     | 1        | 1      | 0.41%   |
| Colorful                    | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 6        | 2.23%   |
| A-DATA SU650 120GB SSD                            | 5        | 1.86%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 4        | 1.49%   |
| Samsung SSD 860 EVO 250GB                         | 4        | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 1.49%   |
| Toshiba DT01ACA100 1TB                            | 3        | 1.12%   |
| Samsung SSD 860 EVO 500GB                         | 3        | 1.12%   |
| Samsung SSD 860 EVO 1TB                           | 3        | 1.12%   |
| Samsung SSD 850 EVO 250GB                         | 3        | 1.12%   |
| Samsung NVMe SSD Drive 1TB                        | 3        | 1.12%   |
| Samsung HD501LJ 500GB                             | 3        | 1.12%   |
| Patriot Burst 480GB SSD                           | 3        | 1.12%   |
| Kingston SA400S37240G 240GB SSD                   | 3        | 1.12%   |
| Kingston SA400S37120G 120GB SSD                   | 3        | 1.12%   |
| Crucial CT1000MX500SSD1 1TB                       | 3        | 1.12%   |
| WDC WD800AAJS-60PSA0 80GB                         | 2        | 0.74%   |
| WDC WD5000AAKX-001CA0 500GB                       | 2        | 0.74%   |
| WDC WD10PURX-64E5EY0 1TB                          | 2        | 0.74%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 2        | 0.74%   |
| Toshiba MQ01ABD100 1TB                            | 2        | 0.74%   |
| Toshiba MK3261GSYN 320GB                          | 2        | 0.74%   |
| Toshiba HDWE140 4TB                               | 2        | 0.74%   |
| Toshiba HDWD120 2TB                               | 2        | 0.74%   |
| Toshiba HDWD110 1TB                               | 2        | 0.74%   |
| Seagate ST3500418AS 500GB                         | 2        | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2        | 0.74%   |
| SanDisk NVMe SSD Drive 500GB                      | 2        | 0.74%   |
| Samsung SSD 970 EVO 500GB                         | 2        | 0.74%   |
| Samsung SSD 850 EVO 500GB                         | 2        | 0.74%   |
| Samsung SSD 850 EVO 120GB                         | 2        | 0.74%   |
| Samsung NVMe SSD Drive 500GB                      | 2        | 0.74%   |
| Patriot Burst 120GB SSD                           | 2        | 0.74%   |
| Kingston SV300S37A120G 120GB SSD                  | 2        | 0.74%   |
| Kingston SUV400S37240G 240GB SSD                  | 2        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 0.74%   |
| Hitachi HDS721680PLA380 82GB                      | 2        | 0.74%   |
| Hitachi HDS721050CLA362 500GB                     | 2        | 0.74%   |
| GOODRAM SSD 120GB                                 | 2        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 51     | 34.62%  |
| Seagate             | 32       | 44     | 30.77%  |
| Toshiba             | 16       | 22     | 15.38%  |
| Samsung Electronics | 10       | 25     | 9.62%   |
| Hitachi             | 7        | 7      | 6.73%   |
| HGST                | 2        | 3      | 1.92%   |
| ExcelStor           | 1        | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 34     | 23.76%  |
| A-DATA Technology   | 17       | 21     | 16.83%  |
| Kingston            | 16       | 26     | 15.84%  |
| Crucial             | 11       | 13     | 10.89%  |
| Patriot             | 6        | 6      | 5.94%   |
| WDC                 | 2        | 2      | 1.98%   |
| Transcend           | 2        | 2      | 1.98%   |
| Intel               | 2        | 2      | 1.98%   |
| GOODRAM             | 2        | 2      | 1.98%   |
| Gigabyte Technology | 2        | 2      | 1.98%   |
| China               | 2        | 2      | 1.98%   |
| Apacer              | 2        | 4      | 1.98%   |
| XrayDisk            | 1        | 1      | 0.99%   |
| Unknown             | 1        | 1      | 0.99%   |
| StoreJet            | 1        | 1      | 0.99%   |
| SPCC                | 1        | 1      | 0.99%   |
| PNY                 | 1        | 1      | 0.99%   |
| Plextor             | 1        | 1      | 0.99%   |
| OCZ                 | 1        | 2      | 0.99%   |
| Netac               | 1        | 1      | 0.99%   |
| Leven               | 1        | 3      | 0.99%   |
| Intenso             | 1        | 2      | 0.99%   |
| Hewlett-Packard     | 1        | 1      | 0.99%   |
| Dahua               | 1        | 1      | 0.99%   |
| Colorful            | 1        | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 87       | 153    | 41.23%  |
| SSD     | 84       | 133    | 39.81%  |
| NVMe    | 38       | 49     | 18.01%  |
| Unknown | 2        | 2      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 119      | 279    | 72.56%  |
| NVMe | 37       | 48     | 22.56%  |
| SAS  | 8        | 10     | 4.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 192    | 58.48%  |
| 0.51-1.0   | 46       | 61     | 26.9%   |
| 1.01-2.0   | 17       | 23     | 9.94%   |
| 3.01-4.0   | 4        | 5      | 2.34%   |
| 2.01-3.0   | 2        | 3      | 1.17%   |
| 4.01-10.0  | 2        | 2      | 1.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 35       | 24.65%  |
| 251-500        | 29       | 20.42%  |
| 501-1000       | 18       | 12.68%  |
| 1001-2000      | 16       | 11.27%  |
| 1-20           | 11       | 7.75%   |
| More than 3000 | 10       | 7.04%   |
| 2001-3000      | 8        | 5.63%   |
| 51-100         | 8        | 5.63%   |
| Unknown        | 4        | 2.82%   |
| 21-50          | 3        | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 47       | 32.64%  |
| 101-250        | 23       | 15.97%  |
| 251-500        | 14       | 9.72%   |
| 51-100         | 14       | 9.72%   |
| 21-50          | 12       | 8.33%   |
| 1001-2000      | 12       | 8.33%   |
| 501-1000       | 11       | 7.64%   |
| More than 3000 | 6        | 4.17%   |
| Unknown        | 4        | 2.78%   |
| 2001-3000      | 1        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD800AAJS-60PSA0 80GB         | 2        | 2      | 8%      |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 5      | 8%      |
| Toshiba MK3261GSYN 320GB          | 2        | 2      | 8%      |
| WDC WD6400BPVT-80HXZT1 640GB      | 1        | 1      | 4%      |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 4%      |
| WDC WD1003FBYX-01Y7B0 1TB         | 1        | 2      | 4%      |
| Toshiba MQ01ABD100 1TB            | 1        | 1      | 4%      |
| Seagate ST9500325AS 500GB         | 1        | 1      | 4%      |
| Seagate ST500LX012-SSHD-8GB       | 1        | 1      | 4%      |
| Seagate ST3250410AS 250GB         | 1        | 1      | 4%      |
| Seagate ST3250318AS 250GB         | 1        | 1      | 4%      |
| Seagate ST2000VX000-1CU164 2TB    | 1        | 1      | 4%      |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 4%      |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 4%      |
| Samsung Electronics HD080HJ 80GB  | 1        | 4      | 4%      |
| Leven JAJS300M240C 240GB          | 1        | 3      | 4%      |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 4%      |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 4%      |
| ExcelStor Technology J8160S 165GB | 1        | 1      | 4%      |
| Crucial CT525MX300SSD1 528GB      | 1        | 1      | 4%      |
| Colorful SL300 120GB SSD          | 1        | 1      | 4%      |
| A-DATA Technology SX900 256GB SSD | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 11     | 29.17%  |
| Seagate             | 5        | 5      | 20.83%  |
| Samsung Electronics | 3        | 6      | 12.5%   |
| Toshiba             | 2        | 3      | 8.33%   |
| Leven               | 1        | 3      | 4.17%   |
| Kingston            | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 1      | 4.17%   |
| ExcelStor           | 1        | 1      | 4.17%   |
| Crucial             | 1        | 1      | 4.17%   |
| Colorful            | 1        | 1      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 11     | 36.84%  |
| Seagate             | 5        | 5      | 26.32%  |
| Samsung Electronics | 3        | 6      | 15.79%  |
| Toshiba             | 2        | 3      | 10.53%  |
| Hitachi             | 1        | 1      | 5.26%   |
| ExcelStor           | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 27     | 75%     |
| SSD  | 5        | 7      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST3160812A 160GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 70       | 185    | 47.95%  |
| Works    | 57       | 116    | 39.04%  |
| Malfunc  | 18       | 34     | 12.33%  |
| Failed   | 1        | 2      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 75       | 41.21%  |
| AMD                         | 52       | 28.57%  |
| Samsung Electronics         | 17       | 9.34%   |
| ASMedia Technology          | 8        | 4.4%    |
| ADATA Technology            | 6        | 3.3%    |
| SanDisk                     | 4        | 2.2%    |
| Nvidia                      | 3        | 1.65%   |
| JMicron Technology          | 3        | 1.65%   |
| Realtek Semiconductor       | 2        | 1.1%    |
| Phison Electronics          | 2        | 1.1%    |
| Micron/Crucial Technology   | 2        | 1.1%    |
| Marvell Technology Group    | 2        | 1.1%    |
| Kingston Technology Company | 2        | 1.1%    |
| OCZ Technology Group        | 1        | 0.55%   |
| MAXIO Technology (Hangzhou) | 1        | 0.55%   |
| Lite-On Technology          | 1        | 0.55%   |
| KIOXIA                      | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 13.28%  |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 6.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 4.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.07%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 2.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 1.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.24%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.24%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.24%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.83%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.83%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.83%   |
| ADATA FALCON NVMe SSD                                                                   | 2        | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.41%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1        | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.41%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.41%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 100      | 55.87%  |
| NVMe | 37       | 20.67%  |
| IDE  | 34       | 18.99%  |
| RAID | 7        | 3.91%   |
| SAS  | 1        | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 58.46%  |
| AMD    | 54       | 41.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 3.08%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 2.31%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 2.31%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 2.31%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 2.31%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 2.31%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.54%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.54%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.54%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.54%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.54%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.54%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.54%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.54%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.54%   |
| AMD Athlon II X2 260 Processor              | 2        | 1.54%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.77%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.77%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 0.77%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.77%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.77%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.77%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.77%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 17.69%  |
| AMD Ryzen 5             | 23       | 17.69%  |
| Intel Core i7           | 12       | 9.23%   |
| Intel Core i3           | 12       | 9.23%   |
| AMD Ryzen 7             | 8        | 6.15%   |
| AMD Ryzen 9             | 6        | 4.62%   |
| Intel Pentium Dual-Core | 5        | 3.85%   |
| Intel Core 2 Duo        | 4        | 3.08%   |
| AMD FX                  | 4        | 3.08%   |
| Other                   | 3        | 2.31%   |
| Intel Xeon              | 3        | 2.31%   |
| Intel Pentium 4         | 3        | 2.31%   |
| Intel Pentium           | 3        | 2.31%   |
| AMD Athlon II X2        | 3        | 2.31%   |
| Intel Pentium D         | 2        | 1.54%   |
| Intel Core i9           | 2        | 1.54%   |
| Intel Celeron           | 2        | 1.54%   |
| AMD Ryzen 3             | 2        | 1.54%   |
| AMD Phenom II X4        | 2        | 1.54%   |
| AMD Athlon 64 X2        | 2        | 1.54%   |
| Intel Core 2 Quad       | 1        | 0.77%   |
| Intel Core 2            | 1        | 0.77%   |
| AMD PRO A8              | 1        | 0.77%   |
| AMD Athlon II X4        | 1        | 0.77%   |
| AMD A8                  | 1        | 0.77%   |
| AMD A4                  | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 41       | 31.54%  |
| 2      | 38       | 29.23%  |
| 6      | 31       | 23.85%  |
| 8      | 12       | 9.23%   |
| 12     | 3        | 2.31%   |
| 1      | 3        | 2.31%   |
| 16     | 2        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 99.24%  |
| 2      | 1        | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 81       | 61.83%  |
| 1      | 50       | 38.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 129      | 99.23%  |
| 32-bit         | 1        | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 31.82%  |
| 0x306c3    | 11       | 8.33%   |
| 0x206a7    | 7        | 5.3%    |
| 0x1067a    | 6        | 4.55%   |
| 0x306a9    | 5        | 3.79%   |
| 0x08701021 | 5        | 3.79%   |
| 0x906e9    | 4        | 3.03%   |
| 0x08001137 | 4        | 3.03%   |
| 0x010000c8 | 4        | 3.03%   |
| 0xa0653    | 3        | 2.27%   |
| 0x0800820d | 3        | 2.27%   |
| 0xf43      | 2        | 1.52%   |
| 0x506e3    | 2        | 1.52%   |
| 0x0a50000c | 2        | 1.52%   |
| 0x0a201009 | 2        | 1.52%   |
| 0x08108109 | 2        | 1.52%   |
| 0xf65      | 1        | 0.76%   |
| 0xf47      | 1        | 0.76%   |
| 0xf34      | 1        | 0.76%   |
| 0xa0671    | 1        | 0.76%   |
| 0x906ed    | 1        | 0.76%   |
| 0x906ec    | 1        | 0.76%   |
| 0x906eb    | 1        | 0.76%   |
| 0x806c1    | 1        | 0.76%   |
| 0x206c2    | 1        | 0.76%   |
| 0x20652    | 1        | 0.76%   |
| 0x106e5    | 1        | 0.76%   |
| 0x106a5    | 1        | 0.76%   |
| 0x0a50000d | 1        | 0.76%   |
| 0x0a50000b | 1        | 0.76%   |
| 0x0a20120a | 1        | 0.76%   |
| 0x0a201204 | 1        | 0.76%   |
| 0x0a201016 | 1        | 0.76%   |
| 0x0a201005 | 1        | 0.76%   |
| 0x08701013 | 1        | 0.76%   |
| 0x0810100b | 1        | 0.76%   |
| 0x0800820b | 1        | 0.76%   |
| 0x08001129 | 1        | 0.76%   |
| 0x0700010f | 1        | 0.76%   |
| 0x06003109 | 1        | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 14       | 10.77%  |
| Haswell     | 13       | 10%     |
| KabyLake    | 12       | 9.23%   |
| IvyBridge   | 11       | 8.46%   |
| Zen+        | 9        | 6.92%   |
| Penryn      | 9        | 6.92%   |
| Zen 2       | 8        | 6.15%   |
| Zen         | 8        | 6.15%   |
| SandyBridge | 8        | 6.15%   |
| K10         | 6        | 4.62%   |
| Piledriver  | 5        | 3.85%   |
| NetBurst    | 5        | 3.85%   |
| CometLake   | 5        | 3.85%   |
| Westmere    | 3        | 2.31%   |
| Skylake     | 3        | 2.31%   |
| Nehalem     | 2        | 1.54%   |
| K8 Hammer   | 2        | 1.54%   |
| Core        | 2        | 1.54%   |
| TigerLake   | 1        | 0.77%   |
| Steamroller | 1        | 0.77%   |
| Jaguar      | 1        | 0.77%   |
| Icelake     | 1        | 0.77%   |
| Unknown     | 1        | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 60       | 42.86%  |
| AMD    | 44       | 31.43%  |
| Intel  | 36       | 25.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 4.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 2.04%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 2.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.04%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 2.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.36%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 1.36%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.36%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.36%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.36%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1.36%   |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 1.36%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.36%   |
| Intel HD Graphics 630                                                       | 2        | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.36%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1.36%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.36%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.36%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.36%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.68%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.68%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.68%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.68%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 56       | 42.11%  |
| 1 x AMD        | 39       | 29.32%  |
| 1 x Intel      | 30       | 22.56%  |
| 2 x AMD        | 3        | 2.26%   |
| 2 x Nvidia     | 2        | 1.5%    |
| Intel + Nvidia | 1        | 0.75%   |
| Intel + AMD    | 1        | 0.75%   |
| AMD + Nvidia   | 1        | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 94       | 69.63%  |
| Proprietary | 37       | 27.41%  |
| Unknown     | 4        | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 33.82%  |
| 1.01-2.0   | 19       | 13.97%  |
| 0.51-1.0   | 15       | 11.03%  |
| 0.01-0.5   | 15       | 11.03%  |
| 3.01-4.0   | 14       | 10.29%  |
| 7.01-8.0   | 13       | 9.56%   |
| 5.01-6.0   | 10       | 7.35%   |
| 8.01-16.0  | 3        | 2.21%   |
| 16.01-24.0 | 1        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 32       | 22.86%  |
| Dell                 | 17       | 12.14%  |
| AOC                  | 17       | 12.14%  |
| Philips              | 16       | 11.43%  |
| Goldstar             | 15       | 10.71%  |
| BenQ                 | 8        | 5.71%   |
| Ancor Communications | 8        | 5.71%   |
| Hewlett-Packard      | 6        | 4.29%   |
| Lenovo               | 5        | 3.57%   |
| ViewSonic            | 2        | 1.43%   |
| LG Electronics       | 2        | 1.43%   |
| Unknown (XXX)        | 1        | 0.71%   |
| Sony                 | 1        | 0.71%   |
| NEC Computers        | 1        | 0.71%   |
| Mi                   | 1        | 0.71%   |
| Medion               | 1        | 0.71%   |
| Iiyama               | 1        | 0.71%   |
| Hitachi              | 1        | 0.71%   |
| Eizo                 | 1        | 0.71%   |
| DENON                | 1        | 0.71%   |
| ASUSTek Computer     | 1        | 0.71%   |
| AGO                  | 1        | 0.71%   |
| Acer                 | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3        | 1.91%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 3        | 1.91%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch     | 2        | 1.27%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 2        | 1.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 1.27%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                     | 2        | 1.27%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2        | 1.27%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                     | 2        | 1.27%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2        | 1.27%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 2        | 1.27%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 1.27%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                        | 2        | 1.27%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 1.27%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.64%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.64%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 0.64%   |
| Sony TV SNY2C02 1920x1080 1218x685mm 55.0-inch                        | 1        | 0.64%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.64%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch      | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch   | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01E3 1280x1024 338x270mm 17.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch  | 1        | 0.64%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch    | 1        | 0.64%   |
| Samsung Electronics SMBX2231 SAM076C 1920x1080 477x268mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 0.64%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 518x324mm 24.1-inch     | 1        | 0.64%   |
| Samsung Electronics S24E450 SAM0C82 1920x1080 531x299mm 24.0-inch     | 1        | 0.64%   |
| Samsung Electronics S24E450 SAM0C81 1920x1080 531x299mm 24.0-inch     | 1        | 0.64%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 1        | 0.64%   |
| Samsung Electronics S23E650 SAM0CAF 1920x1080 510x287mm 23.0-inch     | 1        | 0.64%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch     | 1        | 0.64%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1        | 0.64%   |
| Samsung Electronics S22E390 SAM0C17 1920x1080 477x268mm 21.5-inch     | 1        | 0.64%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch     | 1        | 0.64%   |
| Samsung Electronics LS32A70 SAM7164 3840x2160 698x393mm 31.5-inch     | 1        | 0.64%   |
| Samsung Electronics LCD Monitor T24E390 3200x1080                     | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 64       | 45.07%  |
| 2560x1440 (QHD)    | 20       | 14.08%  |
| 1280x1024 (SXGA)   | 19       | 13.38%  |
| 3840x2160 (4K)     | 11       | 7.75%   |
| 1366x768 (WXGA)    | 6        | 4.23%   |
| 1440x900 (WXGA+)   | 4        | 2.82%   |
| 3440x1440          | 3        | 2.11%   |
| Unknown            | 3        | 2.11%   |
| 3840x1600          | 2        | 1.41%   |
| 3840x1080          | 2        | 1.41%   |
| 2560x1080          | 2        | 1.41%   |
| 3200x1080          | 1        | 0.7%    |
| 1920x1200 (WUXGA)  | 1        | 0.7%    |
| 1680x1050 (WSXGA+) | 1        | 0.7%    |
| 1600x900 (HD+)     | 1        | 0.7%    |
| 1360x768           | 1        | 0.7%    |
| 1280x720 (HD)      | 1        | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 24       | 16.78%  |
| 27      | 20       | 13.99%  |
| 24      | 20       | 13.99%  |
| 21      | 15       | 10.49%  |
| Unknown | 12       | 8.39%   |
| 19      | 11       | 7.69%   |
| 17      | 9        | 6.29%   |
| 18      | 7        | 4.9%    |
| 31      | 5        | 3.5%    |
| 40      | 4        | 2.8%    |
| 34      | 4        | 2.8%    |
| 84      | 2        | 1.4%    |
| 20      | 2        | 1.4%    |
| 55      | 1        | 0.7%    |
| 54      | 1        | 0.7%    |
| 50      | 1        | 0.7%    |
| 37      | 1        | 0.7%    |
| 33      | 1        | 0.7%    |
| 25      | 1        | 0.7%    |
| 22      | 1        | 0.7%    |
| 12      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 59       | 42.75%  |
| 401-500     | 26       | 18.84%  |
| Unknown     | 12       | 8.7%    |
| 351-400     | 9        | 6.52%   |
| 301-350     | 9        | 6.52%   |
| 601-700     | 7        | 5.07%   |
| 801-900     | 5        | 3.62%   |
| 701-800     | 5        | 3.62%   |
| 1001-1500   | 3        | 2.17%   |
| 1501-2000   | 2        | 1.45%   |
| 201-300     | 1        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 90       | 67.16%  |
| 5/4     | 18       | 13.43%  |
| Unknown | 11       | 8.21%   |
| 16/10   | 7        | 5.22%   |
| 21/9    | 5        | 3.73%   |
| 3/2     | 2        | 1.49%   |
| 4/3     | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 35.42%  |
| 301-350        | 20       | 13.89%  |
| 151-200        | 20       | 13.89%  |
| 141-150        | 15       | 10.42%  |
| Unknown        | 12       | 8.33%   |
| 351-500        | 10       | 6.94%   |
| More than 1000 | 5        | 3.47%   |
| 251-300        | 5        | 3.47%   |
| 501-1000       | 5        | 3.47%   |
| 71-80          | 1        | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 89       | 65.93%  |
| 101-120 | 26       | 19.26%  |
| Unknown | 12       | 8.89%   |
| 121-160 | 4        | 2.96%   |
| 1-50    | 2        | 1.48%   |
| 161-240 | 2        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 99       | 75.57%  |
| 2     | 26       | 19.85%  |
| 0     | 5        | 3.82%   |
| 3     | 1        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 82       | 49.4%   |
| Intel                           | 40       | 24.1%   |
| Qualcomm Atheros                | 13       | 7.83%   |
| Broadcom                        | 5        | 3.01%   |
| Broadcom Limited                | 4        | 2.41%   |
| TP-Link                         | 3        | 1.81%   |
| Ralink                          | 2        | 1.2%    |
| Nvidia                          | 2        | 1.2%    |
| Microsoft                       | 2        | 1.2%    |
| D-Link                          | 2        | 1.2%    |
| U-Blox                          | 1        | 0.6%    |
| Samsung Electronics             | 1        | 0.6%    |
| Ralink Technology               | 1        | 0.6%    |
| Qualcomm Atheros Communications | 1        | 0.6%    |
| Marvell Technology Group        | 1        | 0.6%    |
| Huawei Technologies             | 1        | 0.6%    |
| Edimax Technology               | 1        | 0.6%    |
| D-Link System                   | 1        | 0.6%    |
| ASUSTek Computer                | 1        | 0.6%    |
| Aquantia                        | 1        | 0.6%    |
| 3Com                            | 1        | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68       | 36.56%  |
| Intel I211 Gigabit Network Connection                             | 7        | 3.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.69%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 2.15%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.15%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.08%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.08%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 2        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.08%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.08%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2        | 1.08%   |
| U-Blox [u-blox 7]                                                 | 1        | 0.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.54%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 31.71%  |
| Realtek Semiconductor           | 9        | 21.95%  |
| TP-Link                         | 3        | 7.32%   |
| Qualcomm Atheros                | 3        | 7.32%   |
| Ralink                          | 2        | 4.88%   |
| Microsoft                       | 2        | 4.88%   |
| D-Link                          | 2        | 4.88%   |
| Broadcom                        | 2        | 4.88%   |
| Ralink Technology               | 1        | 2.44%   |
| Qualcomm Atheros Communications | 1        | 2.44%   |
| Edimax Technology               | 1        | 2.44%   |
| D-Link System                   | 1        | 2.44%   |
| ASUSTek Computer                | 1        | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 4        | 9.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 3        | 7.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 7.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 4.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 4.88%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 4.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 4.88%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 2        | 4.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 2.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 2.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 2.44%   |
| Realtek 802.11ac WLAN Adapter                                                 | 1        | 2.44%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.44%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2.44%   |
| Intel Wireless-AC 9260                                                        | 1        | 2.44%   |
| Intel Wireless 7265                                                           | 1        | 2.44%   |
| Intel Wireless 7260                                                           | 1        | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.44%   |
| Intel Wi-Fi 6 AX201                                                           | 1        | 2.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.44%   |
| Edimax 802.11n WLAN Adapter                                                   | 1        | 2.44%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1        | 2.44%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 2.44%   |
| D-Link 802.11 n WLAN                                                          | 1        | 2.44%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.44%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.44%   |
| ASUS 802.11n WLAN Adapter                                                     | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 79       | 56.83%  |
| Intel                    | 36       | 25.9%   |
| Qualcomm Atheros         | 10       | 7.19%   |
| Broadcom Limited         | 4        | 2.88%   |
| Broadcom                 | 3        | 2.16%   |
| Nvidia                   | 2        | 1.44%   |
| Samsung Electronics      | 1        | 0.72%   |
| Marvell Technology Group | 1        | 0.72%   |
| Huawei Technologies      | 1        | 0.72%   |
| Aquantia                 | 1        | 0.72%   |
| 3Com                     | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68       | 47.22%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 4.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 3.47%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.78%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 2.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2        | 1.39%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.39%   |
| Intel 82578DC Gigabit Network Connection                                      | 2        | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.39%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express               | 2        | 1.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.69%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.69%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.69%   |
| Nvidia MCP55 Ethernet                                                         | 1        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.69%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.69%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.69%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.69%   |
| Intel Ethernet Connection (13) I219-V                                         | 1        | 0.69%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.69%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 0.69%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller                 | 1        | 0.69%   |
| Huawei E353/E3131                                                             | 1        | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 76.47%  |
| WiFi     | 39       | 22.94%  |
| Modem    | 1        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 82.09%  |
| WiFi     | 24       | 17.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 75.94%  |
| 2     | 25       | 18.8%   |
| 3     | 6        | 4.51%   |
| 5     | 1        | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 14       | 48.28%  |
| Intel                   | 12       | 41.38%  |
| Edimax Technology       | 2        | 6.9%    |
| Broadcom                | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 48.28%  |
| Intel AX200 Bluetooth                               | 4        | 13.79%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 10.34%  |
| Intel AX201 Bluetooth                               | 2        | 6.9%    |
| Edimax Bluetooth Adapter                            | 2        | 6.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.45%   |
| Intel Bluetooth wireless interface                  | 1        | 3.45%   |
| Intel AX210 Bluetooth                               | 1        | 3.45%   |
| Broadcom Bluetooth Device                           | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 74       | 31.9%   |
| AMD                                             | 63       | 27.16%  |
| Nvidia                                          | 55       | 23.71%  |
| C-Media Electronics                             | 8        | 3.45%   |
| JMTek                                           | 6        | 2.59%   |
| Logitech                                        | 4        | 1.72%   |
| Yamaha                                          | 2        | 0.86%   |
| SteelSeries ApS                                 | 2        | 0.86%   |
| PreSonus Audio Electronics                      | 2        | 0.86%   |
| XMOS                                            | 1        | 0.43%   |
| Sony                                            | 1        | 0.43%   |
| Sennheiser Communications                       | 1        | 0.43%   |
| Realtek Semiconductor                           | 1        | 0.43%   |
| Razer USA                                       | 1        | 0.43%   |
| Panasonic (Matsushita)                          | 1        | 0.43%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.43%   |
| Kingston Technology                             | 1        | 0.43%   |
| GN Netcom                                       | 1        | 0.43%   |
| Generalplus Technology                          | 1        | 0.43%   |
| Focusrite-Novation                              | 1        | 0.43%   |
| Creative Technology                             | 1        | 0.43%   |
| Creative Labs                                   | 1        | 0.43%   |
| Audio-Technica                                  | 1        | 0.43%   |
| ASUSTek Computer                                | 1        | 0.43%   |
| Allen&Heath                                     | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 6.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 4.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 4.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 3.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.55%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 2.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.82%   |
| JMTek USB PnP Audio Device                                                 | 5        | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.46%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.09%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.09%   |
| Yamaha AG06/AG03                                                           | 2        | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.73%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 23.71%  |
| Unknown             | 16       | 16.49%  |
| G.Skill             | 14       | 14.43%  |
| Crucial             | 11       | 11.34%  |
| Patriot             | 8        | 8.25%   |
| Samsung Electronics | 4        | 4.12%   |
| SK hynix            | 3        | 3.09%   |
| Ramaxel Technology  | 3        | 3.09%   |
| A-DATA Technology   | 3        | 3.09%   |
| Transcend           | 2        | 2.06%   |
| Team                | 2        | 2.06%   |
| Nanya Technology    | 2        | 2.06%   |
| GOODRAM             | 2        | 2.06%   |
| Corsair             | 2        | 2.06%   |
| Elpida              | 1        | 1.03%   |
| Atermiter           | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s     | 3        | 2.75%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 3        | 2.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 1.83%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s   | 2        | 1.83%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s        | 2        | 1.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 2        | 1.83%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 2        | 1.83%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 2        | 1.83%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 1        | 0.92%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.92%   |
| Unknown RAM Module 512MB DIMM 800MT/s                  | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 1        | 0.92%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 1        | 0.92%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s            | 1        | 0.92%   |
| Transcend RAM JM2400HLB-8G 8192MB DIMM DDR4 2133MT/s   | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 1        | 0.92%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.92%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s   | 1        | 0.92%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 0.92%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 0.92%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 1        | 0.92%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s    | 1        | 0.92%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s    | 1        | 0.92%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s | 1        | 0.92%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3           | 1        | 0.92%   |
| Ramaxel RAM RML1520AG38D6F-667 512MB DIMM DDR2 667MT/s | 1        | 0.92%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s        | 1        | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 43       | 49.43%  |
| DDR3    | 28       | 32.18%  |
| Unknown | 6        | 6.9%    |
| SDRAM   | 5        | 5.75%   |
| DDR2    | 3        | 3.45%   |
| DDR     | 2        | 2.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 81       | 95.29%  |
| SODIMM | 4        | 4.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 35       | 38.89%  |
| 4096  | 22       | 24.44%  |
| 16384 | 11       | 12.22%  |
| 2048  | 11       | 12.22%  |
| 32768 | 5        | 5.56%   |
| 1024  | 3        | 3.33%   |
| 512   | 3        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 19%     |
| 3200    | 13       | 13%     |
| 1333    | 13       | 13%     |
| 2667    | 7        | 7%      |
| 2400    | 6        | 6%      |
| 2133    | 4        | 4%      |
| 3733    | 3        | 3%      |
| 3266    | 3        | 3%      |
| 2800    | 3        | 3%      |
| 2666    | 3        | 3%      |
| 800     | 3        | 3%      |
| 667     | 3        | 3%      |
| Unknown | 3        | 3%      |
| 3866    | 2        | 2%      |
| 3600    | 2        | 2%      |
| 2934    | 2        | 2%      |
| 400     | 2        | 2%      |
| 3800    | 1        | 1%      |
| 3533    | 1        | 1%      |
| 3400    | 1        | 1%      |
| 3066    | 1        | 1%      |
| 3000    | 1        | 1%      |
| 1867    | 1        | 1%      |
| 1067    | 1        | 1%      |
| 1066    | 1        | 1%      |
| 333     | 1        | 1%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 60%     |
| Hewlett-Packard     | 2        | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 20%     |
| Samsung ML-1670 Series  | 1        | 20%     |
| Samsung M2070 Series    | 1        | 20%     |
| HP PSC-1315/PSC-1317    | 1        | 20%     |
| HP LaserJet 1020        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 45.16%  |
| Microdia                      | 3        | 9.68%   |
| Samsung Electronics           | 2        | 6.45%   |
| Panasonic (Matsushita)        | 2        | 6.45%   |
| Z-Star Microelectronics       | 1        | 3.23%   |
| Sunplus Innovation Technology | 1        | 3.23%   |
| Sonix Technology              | 1        | 3.23%   |
| Razer USA                     | 1        | 3.23%   |
| Pixart Imaging                | 1        | 3.23%   |
| Lenovo                        | 1        | 3.23%   |
| Huawei Technologies           | 1        | 3.23%   |
| Genesys Logic                 | 1        | 3.23%   |
| Cubeternet                    | 1        | 3.23%   |
| Arkmicro Technologies         | 1        | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 3        | 9.68%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 2        | 6.45%   |
| Panasonic (Matsushita) TY-CC20W                                     | 2        | 6.45%   |
| Microdia Webcam Vitade AF                                           | 2        | 6.45%   |
| Logitech HD Webcam C615                                             | 2        | 6.45%   |
| Logitech HD Pro Webcam C920                                         | 2        | 6.45%   |
| Z-Star Venus USB2.0 Camera                                          | 1        | 3.23%   |
| Sunplus AUSDOM FHD Camera                                           | 1        | 3.23%   |
| Sonix USB Camera                                                    | 1        | 3.23%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 3.23%   |
| Pixart Imaging Webcam Genius iLook 300                              | 1        | 3.23%   |
| Microdia Camera                                                     | 1        | 3.23%   |
| Logitech Webcam C930e                                               | 1        | 3.23%   |
| Logitech Webcam C925e                                               | 1        | 3.23%   |
| Logitech Webcam C170                                                | 1        | 3.23%   |
| Logitech Logitech Webcam C160                                       | 1        | 3.23%   |
| Logitech HD Webcam C525                                             | 1        | 3.23%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 3.23%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 3.23%   |
| Lenovo FHD Webcam Audio                                             | 1        | 3.23%   |
| Huawei UVC Camera                                                   | 1        | 3.23%   |
| Genesys Logic USB 2.0 Camera                                        | 1        | 3.23%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 3.23%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 120      | 91.6%   |
| 1     | 10       | 7.63%   |
| 2     | 1        | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 6        | 50%     |
| Net/wireless          | 2        | 16.67%  |
| Network               | 1        | 8.33%   |
| Multimedia controller | 1        | 8.33%   |
| Camera                | 1        | 8.33%   |
| Bluetooth             | 1        | 8.33%   |

