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

Total: 155

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 7        | 6.14%   |
| Ubuntu 18.04                 | 6        | 5.26%   |
| Arch                         | 6        | 5.26%   |
| Ubuntu 21.10                 | 4        | 3.51%   |
| Ubuntu 19.10                 | 4        | 3.51%   |
| Manjaro                      | 4        | 3.51%   |
| ROSA R8.1                    | 3        | 2.63%   |
| ROSA R11                     | 3        | 2.63%   |
| ROSA R10                     | 3        | 2.63%   |
| Pop!_OS 21.10                | 3        | 2.63%   |
| Pop!_OS 21.04                | 3        | 2.63%   |
| OpenMandriva 4.2             | 3        | 2.63%   |
| Manjaro 20.2.1               | 3        | 2.63%   |
| KDE neon 20.04               | 3        | 2.63%   |
| Fedora 33                    | 3        | 2.63%   |
| Zorin 16                     | 2        | 1.75%   |
| Ubuntu 22.04                 | 2        | 1.75%   |
| Ubuntu 20.10                 | 2        | 1.75%   |
| ROSA 12.2                    | 2        | 1.75%   |
| Pop!_OS 22.04                | 2        | 1.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.75%   |
| Linux Mint 19.3              | 2        | 1.75%   |
| Fedora 32                    | 2        | 1.75%   |
| Debian 11                    | 2        | 1.75%   |
| Debian 10                    | 2        | 1.75%   |
| ArcoLinux Rolling            | 2        | 1.75%   |
| Arch Rolling                 | 2        | 1.75%   |
| Xubuntu 20.04                | 1        | 0.88%   |
| Ubuntu Unity 16.04           | 1        | 0.88%   |
| ROSA R9                      | 1        | 0.88%   |
| ROSA R8                      | 1        | 0.88%   |
| ROSA R11.1                   | 1        | 0.88%   |
| RHEL 8                       | 1        | 0.88%   |
| Pop!_OS 20.10                | 1        | 0.88%   |
| Pop!_OS 20.04                | 1        | 0.88%   |
| OpenMandriva 4.3             | 1        | 0.88%   |
| Nobara 36                    | 1        | 0.88%   |
| Manjaro 20.0.1               | 1        | 0.88%   |
| Manjaro 19.0.1               | 1        | 0.88%   |
| Manjaro 18.0.4               | 1        | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 24       | 22.22%  |
| ROSA         | 13       | 12.04%  |
| Pop!_OS      | 10       | 9.26%   |
| Manjaro      | 10       | 9.26%   |
| Arch         | 8        | 7.41%   |
| Linux Mint   | 7        | 6.48%   |
| Fedora       | 5        | 4.63%   |
| OpenMandriva | 4        | 3.7%    |
| Debian       | 4        | 3.7%    |
| KDE neon     | 3        | 2.78%   |
| Zorin        | 2        | 1.85%   |
| openSUSE     | 2        | 1.85%   |
| Kubuntu      | 2        | 1.85%   |
| ArcoLinux    | 2        | 1.85%   |
| Xubuntu      | 1        | 0.93%   |
| Ubuntu Unity | 1        | 0.93%   |
| RHEL         | 1        | 0.93%   |
| Nobara       | 1        | 0.93%   |
| Lubuntu      | 1        | 0.93%   |
| Endless      | 1        | 0.93%   |
| EndeavourOS  | 1        | 0.93%   |
| Elementary   | 1        | 0.93%   |
| Deepin       | 1        | 0.93%   |
| Clear Linux  | 1        | 0.93%   |
| CentOS       | 1        | 0.93%   |
| Artix        | 1        | 0.93%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.3.0-23-generic              | 3        | 2.4%    |
| 5.10.14-desktop-1omv4002      | 3        | 2.4%    |
| 5.9.16-1-MANJARO              | 2        | 1.6%    |
| 5.4.0-70-generic              | 2        | 1.6%    |
| 5.4.0-66-generic              | 2        | 1.6%    |
| 5.4.0-48-generic              | 2        | 1.6%    |
| 5.4.0-26-generic              | 2        | 1.6%    |
| 5.3.0-40-generic              | 2        | 1.6%    |
| 5.3.0-28-generic              | 2        | 1.6%    |
| 5.3.0-24-generic              | 2        | 1.6%    |
| 5.15.23-2-lts                 | 2        | 1.6%    |
| 5.15.0-47-generic             | 2        | 1.6%    |
| 5.15.0-46-generic             | 2        | 1.6%    |
| 5.11.0-7620-generic           | 2        | 1.6%    |
| 4.9.60-nrj-desktop-1rosa-i586 | 2        | 1.6%    |
| 6.0.9-201.fc36.x86_64         | 1        | 0.8%    |
| 6.0.7-1207.native             | 1        | 0.8%    |
| 5.9.13-arch1-1                | 1        | 0.8%    |
| 5.8.3-zen1-1-zen              | 1        | 0.8%    |
| 5.8.17-300.fc33.x86_64        | 1        | 0.8%    |
| 5.8.12-200.fc32.x86_64        | 1        | 0.8%    |
| 5.8.0-7642-generic            | 1        | 0.8%    |
| 5.8.0-48-generic              | 1        | 0.8%    |
| 5.8.0-45-generic              | 1        | 0.8%    |
| 5.8.0-29-generic              | 1        | 0.8%    |
| 5.8.0-1-default               | 1        | 0.8%    |
| 5.8.0-050800-generic          | 1        | 0.8%    |
| 5.7.8-200.fc32.x86_64         | 1        | 0.8%    |
| 5.7.17-050717-generic         | 1        | 0.8%    |
| 5.7.11-arch1-1                | 1        | 0.8%    |
| 5.6.6-1-MANJARO               | 1        | 0.8%    |
| 5.5.3-14-tkg-pds              | 1        | 0.8%    |
| 5.4.70-amd64-desktop          | 1        | 0.8%    |
| 5.4.50-amd64-desktop          | 1        | 0.8%    |
| 5.4.18-1-MANJARO              | 1        | 0.8%    |
| 5.4.0-91-generic              | 1        | 0.8%    |
| 5.4.0-77-generic              | 1        | 0.8%    |
| 5.4.0-65-generic              | 1        | 0.8%    |
| 5.4.0-42-generic              | 1        | 0.8%    |
| 5.4.0-124-generic             | 1        | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 13       | 11.11%  |
| 5.3.0   | 8        | 6.84%   |
| 5.13.0  | 8        | 6.84%   |
| 4.15.0  | 8        | 6.84%   |
| 5.8.0   | 6        | 5.13%   |
| 5.11.0  | 6        | 5.13%   |
| 5.15.0  | 5        | 4.27%   |
| 5.10.14 | 3        | 2.56%   |
| 5.9.16  | 2        | 1.71%   |
| 5.15.23 | 2        | 1.71%   |
| 5.10.0  | 2        | 1.71%   |
| 4.9.60  | 2        | 1.71%   |
| 4.19.0  | 2        | 1.71%   |
| 6.0.9   | 1        | 0.85%   |
| 6.0.7   | 1        | 0.85%   |
| 5.9.13  | 1        | 0.85%   |
| 5.8.3   | 1        | 0.85%   |
| 5.8.17  | 1        | 0.85%   |
| 5.8.12  | 1        | 0.85%   |
| 5.7.8   | 1        | 0.85%   |
| 5.7.17  | 1        | 0.85%   |
| 5.7.11  | 1        | 0.85%   |
| 5.6.6   | 1        | 0.85%   |
| 5.5.3   | 1        | 0.85%   |
| 5.4.70  | 1        | 0.85%   |
| 5.4.50  | 1        | 0.85%   |
| 5.4.18  | 1        | 0.85%   |
| 5.19.15 | 1        | 0.85%   |
| 5.19.1  | 1        | 0.85%   |
| 5.19.0  | 1        | 0.85%   |
| 5.18.9  | 1        | 0.85%   |
| 5.18.3  | 1        | 0.85%   |
| 5.16.7  | 1        | 0.85%   |
| 5.16.19 | 1        | 0.85%   |
| 5.16.16 | 1        | 0.85%   |
| 5.16.15 | 1        | 0.85%   |
| 5.16.11 | 1        | 0.85%   |
| 5.15.8  | 1        | 0.85%   |
| 5.15.3  | 1        | 0.85%   |
| 5.15.15 | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 15       | 12.93%  |
| 5.10    | 11       | 9.48%   |
| 5.15    | 10       | 8.62%   |
| 5.8     | 9        | 7.76%   |
| 5.13    | 9        | 7.76%   |
| 5.3     | 8        | 6.9%    |
| 4.15    | 8        | 6.9%    |
| 5.11    | 7        | 6.03%   |
| 4.9     | 7        | 6.03%   |
| 5.16    | 5        | 4.31%   |
| 5.9     | 3        | 2.59%   |
| 5.7     | 3        | 2.59%   |
| 5.19    | 3        | 2.59%   |
| 5.12    | 3        | 2.59%   |
| 4.19    | 3        | 2.59%   |
| 4.14    | 3        | 2.59%   |
| 6.0     | 2        | 1.72%   |
| 5.18    | 2        | 1.72%   |
| 4.1     | 2        | 1.72%   |
| 5.6     | 1        | 0.86%   |
| 5.5     | 1        | 0.86%   |
| 4.18    | 1        | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 102      | 95.33%  |
| i686   | 5        | 4.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 42       | 37.5%   |
| KDE5          | 17       | 15.18%  |
| XFCE          | 11       | 9.82%   |
| KDE4          | 10       | 8.93%   |
| Unknown       | 10       | 8.93%   |
| KDE           | 7        | 6.25%   |
| X-Cinnamon    | 6        | 5.36%   |
| Cinnamon      | 2        | 1.79%   |
| Unity         | 1        | 0.89%   |
| Pantheon      | 1        | 0.89%   |
| MATE          | 1        | 0.89%   |
| LXQt          | 1        | 0.89%   |
| i3            | 1        | 0.89%   |
| Enlightenment | 1        | 0.89%   |
| Deepin        | 1        | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 90       | 81.82%  |
| Wayland | 15       | 13.64%  |
| Tty     | 4        | 3.64%   |
| Unknown | 1        | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 45.87%  |
| LightDM | 14       | 12.84%  |
| SDDM    | 13       | 11.93%  |
| GDM     | 11       | 10.09%  |
| KDM     | 10       | 9.17%   |
| TDM     | 6        | 5.5%    |
| GDM3    | 5        | 4.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 60       | 55.56%  |
| Unknown | 16       | 14.81%  |
| lt_LT   | 14       | 12.96%  |
| en_GB   | 10       | 9.26%   |
| ru_RU   | 7        | 6.48%   |
| uk_UA   | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 72       | 67.29%  |
| EFI  | 35       | 32.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 81       | 75%     |
| Btrfs   | 11       | 10.19%  |
| Unknown | 7        | 6.48%   |
| Overlay | 6        | 5.56%   |
| Xfs     | 2        | 1.85%   |
| SAMSUNG | 1        | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 54       | 50%     |
| MBR     | 27       | 25%     |
| GPT     | 27       | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 83.02%  |
| Yes       | 18       | 16.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 67.59%  |
| Yes       | 35       | 32.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 25.47%  |
| Gigabyte Technology | 21       | 19.81%  |
| ASRock              | 19       | 17.92%  |
| MSI                 | 16       | 15.09%  |
| Hewlett-Packard     | 8        | 7.55%   |
| Intel               | 6        | 5.66%   |
| Dell                | 5        | 4.72%   |
| Lenovo              | 1        | 0.94%   |
| Fujitsu Siemens     | 1        | 0.94%   |
| Fujitsu             | 1        | 0.94%   |
| BESSTAR Tech        | 1        | 0.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7A38                        | 3        | 2.83%   |
| MSI MS-7C82                        | 2        | 1.89%   |
| MSI MS-7823                        | 2        | 1.89%   |
| MSI MS-7817                        | 2        | 1.89%   |
| ASUS PRIME Z390-A                  | 2        | 1.89%   |
| ASUS PRIME B450M-K                 | 2        | 1.89%   |
| ASUS PRIME B450M-A                 | 2        | 1.89%   |
| ASUS All Series                    | 2        | 1.89%   |
| MSI MS-7C35                        | 1        | 0.94%   |
| MSI MS-7B89                        | 1        | 0.94%   |
| MSI MS-7B18                        | 1        | 0.94%   |
| MSI MS-7A71                        | 1        | 0.94%   |
| MSI MS-7A34                        | 1        | 0.94%   |
| MSI MS-7977                        | 1        | 0.94%   |
| MSI MS-7788                        | 1        | 0.94%   |
| Lenovo ThinkCentre M81 5048E2G     | 1        | 0.94%   |
| Intel DP55WB AAE64798-205          | 1        | 0.94%   |
| Intel DH67BL AAG10189-208          | 1        | 0.94%   |
| Intel DH61WW AAG23116-206          | 1        | 0.94%   |
| Intel DH55HC AAE70933-501          | 1        | 0.94%   |
| Intel DB65AL AAG12530-302          | 1        | 0.94%   |
| Intel D102GGC2 AAD42789-201        | 1        | 0.94%   |
| HP Z420 Workstation                | 1        | 0.94%   |
| HP EliteDesk 705 G2 SFF            | 1        | 0.94%   |
| HP Compaq Elite 8300 SFF           | 1        | 0.94%   |
| HP Compaq dc7600 Small Form Factor | 1        | 0.94%   |
| HP Compaq dc5750 Small Form Factor | 1        | 0.94%   |
| HP Compaq dc5700 Microtower        | 1        | 0.94%   |
| HP Compaq 6005 Pro MT PC           | 1        | 0.94%   |
| HP Compaq 6000 Pro SFF PC          | 1        | 0.94%   |
| Gigabyte Z370M DS3H                | 1        | 0.94%   |
| Gigabyte X570 GAMING X             | 1        | 0.94%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 0.94%   |
| Gigabyte X570 AORUS ELITE          | 1        | 0.94%   |
| Gigabyte P41-ES3G                  | 1        | 0.94%   |
| Gigabyte M68MT-S2P                 | 1        | 0.94%   |
| Gigabyte M55S-S3                   | 1        | 0.94%   |
| Gigabyte H81M-D2V                  | 1        | 0.94%   |
| Gigabyte H77M-D3H                  | 1        | 0.94%   |
| Gigabyte H61M-DS2 DVI              | 1        | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 11       | 10.38%  |
| HP Compaq              | 6        | 5.66%   |
| MSI MS-7A38            | 3        | 2.83%   |
| Gigabyte X570          | 3        | 2.83%   |
| ASUS TUF               | 3        | 2.83%   |
| MSI MS-7C82            | 2        | 1.89%   |
| MSI MS-7823            | 2        | 1.89%   |
| MSI MS-7817            | 2        | 1.89%   |
| Dell Vostro            | 2        | 1.89%   |
| Dell OptiPlex          | 2        | 1.89%   |
| ASUS All               | 2        | 1.89%   |
| ASRock B450            | 2        | 1.89%   |
| MSI MS-7C35            | 1        | 0.94%   |
| MSI MS-7B89            | 1        | 0.94%   |
| MSI MS-7B18            | 1        | 0.94%   |
| MSI MS-7A71            | 1        | 0.94%   |
| MSI MS-7A34            | 1        | 0.94%   |
| MSI MS-7977            | 1        | 0.94%   |
| MSI MS-7788            | 1        | 0.94%   |
| Lenovo ThinkCentre     | 1        | 0.94%   |
| Intel DP55WB           | 1        | 0.94%   |
| Intel DH67BL           | 1        | 0.94%   |
| Intel DH61WW           | 1        | 0.94%   |
| Intel DH55HC           | 1        | 0.94%   |
| Intel DB65AL           | 1        | 0.94%   |
| Intel D102GGC2         | 1        | 0.94%   |
| HP Z420                | 1        | 0.94%   |
| HP EliteDesk           | 1        | 0.94%   |
| Gigabyte Z370M         | 1        | 0.94%   |
| Gigabyte P41-ES3G      | 1        | 0.94%   |
| Gigabyte M68MT-S2P     | 1        | 0.94%   |
| Gigabyte M55S-S3       | 1        | 0.94%   |
| Gigabyte H81M-D2V      | 1        | 0.94%   |
| Gigabyte H77M-D3H      | 1        | 0.94%   |
| Gigabyte H61M-DS2      | 1        | 0.94%   |
| Gigabyte H55M-UD2H     | 1        | 0.94%   |
| Gigabyte H410M         | 1        | 0.94%   |
| Gigabyte GA-970A-D3    | 1        | 0.94%   |
| Gigabyte GA-78LMT-USB3 | 1        | 0.94%   |
| Gigabyte EX58-UD3R     | 1        | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 21       | 19.81%  |
| 2009 | 12       | 11.32%  |
| 2013 | 10       | 9.43%   |
| 2019 | 7        | 6.6%    |
| 2017 | 7        | 6.6%    |
| 2012 | 7        | 6.6%    |
| 2016 | 6        | 5.66%   |
| 2015 | 6        | 5.66%   |
| 2011 | 6        | 5.66%   |
| 2021 | 5        | 4.72%   |
| 2020 | 4        | 3.77%   |
| 2010 | 4        | 3.77%   |
| 2006 | 4        | 3.77%   |
| 2007 | 3        | 2.83%   |
| 2008 | 2        | 1.89%   |
| 2014 | 1        | 0.94%   |
| 2005 | 1        | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 106      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 105      | 98.13%  |
| Enabled  | 2        | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 28.04%  |
| 3.01-4.0    | 20       | 18.69%  |
| 8.01-16.0   | 19       | 17.76%  |
| 4.01-8.0    | 14       | 13.08%  |
| 32.01-64.0  | 11       | 10.28%  |
| 64.01-256.0 | 6        | 5.61%   |
| 1.01-2.0    | 3        | 2.8%    |
| 2.01-3.0    | 2        | 1.87%   |
| 24.01-32.0  | 1        | 0.93%   |
| 0.51-1.0    | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 34       | 27.87%  |
| 4.01-8.0   | 24       | 19.67%  |
| 2.01-3.0   | 24       | 19.67%  |
| 3.01-4.0   | 18       | 14.75%  |
| 0.51-1.0   | 11       | 9.02%   |
| 8.01-16.0  | 7        | 5.74%   |
| 16.01-24.0 | 2        | 1.64%   |
| 24.01-32.0 | 1        | 0.82%   |
| 0.01-0.5   | 1        | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 40.54%  |
| 2      | 34       | 30.63%  |
| 3      | 19       | 17.12%  |
| 4      | 8        | 7.21%   |
| 5      | 5        | 4.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 63.3%   |
| Yes       | 40       | 36.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 106      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 71.3%   |
| Yes       | 31       | 28.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 80.19%  |
| Yes       | 21       | 19.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Lithuania | 106      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Vilnius      | 54       | 49.54%  |
| Kaunas       | 20       | 18.35%  |
| Šiauliai    | 7        | 6.42%   |
| Klaipėda    | 6        | 5.5%    |
| Telšiai     | 2        | 1.83%   |
| Mažeikiai   | 2        | 1.83%   |
| Elektrėnai  | 2        | 1.83%   |
| Alytus       | 2        | 1.83%   |
| Vainutas     | 1        | 0.92%   |
| Ukmerge      | 1        | 0.92%   |
| Trakai       | 1        | 0.92%   |
| Tauragė     | 1        | 0.92%   |
| Šilalė     | 1        | 0.92%   |
| Raseiniai    | 1        | 0.92%   |
| Panevezys    | 1        | 0.92%   |
| Nemenčinė  | 1        | 0.92%   |
| Marijampolė | 1        | 0.92%   |
| Lentvaris    | 1        | 0.92%   |
| Kėdainiai   | 1        | 0.92%   |
| Gargždai    | 1        | 0.92%   |
| Druskininkai | 1        | 0.92%   |
| Anykščiai  | 1        | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 39       | 68     | 20%     |
| WDC                         | 32       | 43     | 16.41%  |
| Seagate                     | 25       | 35     | 12.82%  |
| A-DATA Technology           | 17       | 20     | 8.72%   |
| Kingston                    | 15       | 25     | 7.69%   |
| Toshiba                     | 13       | 17     | 6.67%   |
| Crucial                     | 10       | 12     | 5.13%   |
| Patriot                     | 5        | 5      | 2.56%   |
| Hitachi                     | 5        | 5      | 2.56%   |
| SanDisk                     | 3        | 4      | 1.54%   |
| Transcend                   | 2        | 2      | 1.03%   |
| JMicron Technology          | 2        | 2      | 1.03%   |
| Intel                       | 2        | 2      | 1.03%   |
| GOODRAM                     | 2        | 2      | 1.03%   |
| China                       | 2        | 2      | 1.03%   |
| XrayDisk                    | 1        | 1      | 0.51%   |
| XPG                         | 1        | 1      | 0.51%   |
| Unknown                     | 1        | 1      | 0.51%   |
| StoreJet                    | 1        | 1      | 0.51%   |
| PNY                         | 1        | 1      | 0.51%   |
| Plextor                     | 1        | 1      | 0.51%   |
| Phison                      | 1        | 1      | 0.51%   |
| OCZ                         | 1        | 2      | 0.51%   |
| Netac                       | 1        | 1      | 0.51%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.51%   |
| Lite-On Technology          | 1        | 1      | 0.51%   |
| Leven                       | 1        | 3      | 0.51%   |
| Intenso                     | 1        | 2      | 0.51%   |
| HGST                        | 1        | 1      | 0.51%   |
| Hewlett-Packard             | 1        | 1      | 0.51%   |
| Gigabyte Technology         | 1        | 1      | 0.51%   |
| ExcelStor                   | 1        | 1      | 0.51%   |
| Dahua                       | 1        | 1      | 0.51%   |
| Colorful                    | 1        | 1      | 0.51%   |
| Apacer                      | 1        | 3      | 0.51%   |
| ADATA Technology            | 1        | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 6        | 2.78%   |
| WDC WD20EFRX-68EUZN0 2TB         | 4        | 1.85%   |
| Samsung SSD 860 EVO 250GB        | 4        | 1.85%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.39%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.39%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.39%   |
| Samsung NVMe SSD Drive 1TB       | 3        | 1.39%   |
| Samsung HD501LJ 500GB            | 3        | 1.39%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 1.39%   |
| A-DATA SU650 120GB SSD           | 3        | 1.39%   |
| WDC WD800AAJS-60PSA0 80GB        | 2        | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.93%   |
| Toshiba MK3261GSYN 320GB         | 2        | 0.93%   |
| Toshiba HDWE140 4TB              | 2        | 0.93%   |
| Seagate ST3500418AS 500GB        | 2        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.93%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 0.93%   |
| Samsung SSD 970 EVO 500GB        | 2        | 0.93%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.93%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.93%   |
| Patriot Burst 480GB SSD          | 2        | 0.93%   |
| Patriot Burst 120GB SSD          | 2        | 0.93%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.93%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.93%   |
| Hitachi HDS721050CLA362 500GB    | 2        | 0.93%   |
| GOODRAM SSD 120GB                | 2        | 0.93%   |
| Crucial CT480BX500SSD1 480GB     | 2        | 0.93%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 0.93%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 0.93%   |
| A-DATA SX900 128GB SSD           | 2        | 0.93%   |
| A-DATA SX8200PNP 512GB           | 2        | 0.93%   |
| A-DATA SU650 240GB SSD           | 2        | 0.93%   |
| A-DATA SP900 64GB SSD            | 2        | 0.93%   |
| A-DATA SP550 120GB SSD           | 2        | 0.93%   |
| XrayDisk SSD 512GB               | 1        | 0.46%   |
| XPG GAMMIX S5 256GB              | 1        | 0.46%   |
| WDC WDS200T3X0C-00SJG0 2TB       | 1        | 0.46%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.46%   |
| WDC WD7500BPKX-75HPJT0 752GB     | 1        | 0.46%   |
| WDC WD6400BPVT-80HXZT1 640GB     | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 41     | 35.71%  |
| Seagate             | 25       | 35     | 29.76%  |
| Toshiba             | 12       | 16     | 14.29%  |
| Samsung Electronics | 10       | 21     | 11.9%   |
| Hitachi             | 5        | 5      | 5.95%   |
| HGST                | 1        | 1      | 1.19%   |
| ExcelStor           | 1        | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 30     | 23.81%  |
| A-DATA Technology   | 14       | 17     | 16.67%  |
| Kingston            | 13       | 22     | 15.48%  |
| Crucial             | 9        | 11     | 10.71%  |
| Patriot             | 5        | 5      | 5.95%   |
| Transcend           | 2        | 2      | 2.38%   |
| Intel               | 2        | 2      | 2.38%   |
| GOODRAM             | 2        | 2      | 2.38%   |
| China               | 2        | 2      | 2.38%   |
| XrayDisk            | 1        | 1      | 1.19%   |
| Unknown             | 1        | 1      | 1.19%   |
| StoreJet            | 1        | 1      | 1.19%   |
| PNY                 | 1        | 1      | 1.19%   |
| Plextor             | 1        | 1      | 1.19%   |
| OCZ                 | 1        | 2      | 1.19%   |
| Netac               | 1        | 1      | 1.19%   |
| Leven               | 1        | 3      | 1.19%   |
| JMicron Technology  | 1        | 1      | 1.19%   |
| Intenso             | 1        | 2      | 1.19%   |
| Hewlett-Packard     | 1        | 1      | 1.19%   |
| Gigabyte Technology | 1        | 1      | 1.19%   |
| Dahua               | 1        | 1      | 1.19%   |
| Colorful            | 1        | 1      | 1.19%   |
| Apacer              | 1        | 3      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 70       | 120    | 41.92%  |
| SSD     | 68       | 114    | 40.72%  |
| NVMe    | 27       | 36     | 16.17%  |
| Unknown | 2        | 2      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 98       | 227    | 74.24%  |
| NVMe | 27       | 36     | 20.45%  |
| SAS  | 7        | 9      | 5.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 86       | 166    | 61.43%  |
| 0.51-1.0   | 37       | 47     | 26.43%  |
| 1.01-2.0   | 10       | 12     | 7.14%   |
| 3.01-4.0   | 4        | 5      | 2.86%   |
| 2.01-3.0   | 2        | 3      | 1.43%   |
| 4.01-10.0  | 1        | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 26.96%  |
| 251-500        | 23       | 20%     |
| 501-1000       | 15       | 13.04%  |
| 1001-2000      | 14       | 12.17%  |
| More than 3000 | 8        | 6.96%   |
| 1-20           | 7        | 6.09%   |
| 51-100         | 7        | 6.09%   |
| 2001-3000      | 5        | 4.35%   |
| Unknown        | 3        | 2.61%   |
| 21-50          | 2        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 33.05%  |
| 101-250        | 15       | 12.71%  |
| 51-100         | 14       | 11.86%  |
| 251-500        | 12       | 10.17%  |
| 21-50          | 10       | 8.47%   |
| 1001-2000      | 9        | 7.63%   |
| 501-1000       | 9        | 7.63%   |
| More than 3000 | 6        | 5.08%   |
| Unknown        | 3        | 2.54%   |
| 2001-3000      | 1        | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD800AAJS-60PSA0 80GB         | 2        | 2      | 8.7%    |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 3      | 8.7%    |
| Toshiba MK3261GSYN 320GB          | 2        | 2      | 8.7%    |
| WDC WD6400BPVT-80HXZT1 640GB      | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 4.35%   |
| WDC WD1003FBYX-01Y7B0 1TB         | 1        | 2      | 4.35%   |
| Toshiba MQ01ABD100 1TB            | 1        | 1      | 4.35%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 4.35%   |
| Seagate ST500LX012-SSHD-8GB       | 1        | 1      | 4.35%   |
| Seagate ST3250410AS 250GB         | 1        | 1      | 4.35%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 4.35%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 4.35%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 4.35%   |
| Samsung Electronics HD080HJ/ 80GB | 1        | 4      | 4.35%   |
| Leven JAJS300M240C 240GB          | 1        | 3      | 4.35%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 4.35%   |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 4.35%   |
| ExcelStor Technology J8160S 164GB | 1        | 1      | 4.35%   |
| Crucial CT525MX300SSD1 528GB      | 1        | 1      | 4.35%   |
| Colorful SL300 120GB SSD          | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 31.82%  |
| Seagate             | 4        | 4      | 18.18%  |
| Samsung Electronics | 3        | 6      | 13.64%  |
| Toshiba             | 2        | 3      | 9.09%   |
| Leven               | 1        | 3      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| ExcelStor           | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |
| Colorful            | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 38.89%  |
| Seagate             | 4        | 4      | 22.22%  |
| Samsung Electronics | 3        | 6      | 16.67%  |
| Toshiba             | 2        | 3      | 11.11%  |
| Hitachi             | 1        | 1      | 5.56%   |
| ExcelStor           | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 24     | 77.78%  |
| SSD  | 4        | 6      | 22.22%  |

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
| Detected | 62       | 154    | 50.82%  |
| Works    | 42       | 86     | 34.43%  |
| Malfunc  | 17       | 30     | 13.93%  |
| Failed   | 1        | 2      | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 62       | 42.47%  |
| AMD                         | 41       | 28.08%  |
| Samsung Electronics         | 13       | 8.9%    |
| ASMedia Technology          | 6        | 4.11%   |
| SanDisk                     | 4        | 2.74%   |
| Nvidia                      | 3        | 2.05%   |
| JMicron Technology          | 3        | 2.05%   |
| ADATA Technology            | 3        | 2.05%   |
| Realtek Semiconductor       | 2        | 1.37%   |
| Marvell Technology Group    | 2        | 1.37%   |
| Kingston Technology Company | 2        | 1.37%   |
| Phison Electronics          | 1        | 0.68%   |
| OCZ Technology Group        | 1        | 0.68%   |
| Micron/Crucial Technology   | 1        | 0.68%   |
| MAXIO Technology (Hangzhou) | 1        | 0.68%   |
| Lite-On Technology          | 1        | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 13.13%  |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 5.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 3.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 2.02%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.52%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.01%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.01%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.01%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.51%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.51%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.51%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.51%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.51%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.51%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 82       | 56.55%  |
| IDE  | 30       | 20.69%  |
| NVMe | 27       | 18.62%  |
| RAID | 5        | 3.45%   |
| SAS  | 1        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 59.43%  |
| AMD    | 43       | 40.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400F CPU @ 2.90GHz          | 3        | 2.83%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 2.83%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 2.83%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.89%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.89%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.89%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.89%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.89%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.89%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.89%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.89%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.89%   |
| AMD Athlon II X2 260 Processor              | 2        | 1.89%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.94%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.94%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.94%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.94%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.94%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.94%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.94%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 0.94%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.94%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.94%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.94%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.94%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.94%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.94%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.94%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 0.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.94%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.94%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.94%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.94%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.94%   |
| Intel Core i5-9600KF CPU @ 3.70GHz          | 1        | 0.94%   |
| Intel Core i5-9600 CPU @ 3.10GHz            | 1        | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 18.87%  |
| AMD Ryzen 5             | 17       | 16.04%  |
| Intel Core i3           | 11       | 10.38%  |
| Intel Core i7           | 9        | 8.49%   |
| AMD Ryzen 7             | 7        | 6.6%    |
| Intel Pentium Dual-Core | 5        | 4.72%   |
| AMD FX                  | 4        | 3.77%   |
| Intel Core 2 Duo        | 3        | 2.83%   |
| AMD Ryzen 9             | 3        | 2.83%   |
| AMD Athlon II X2        | 3        | 2.83%   |
| Other                   | 2        | 1.89%   |
| Intel Xeon              | 2        | 1.89%   |
| Intel Pentium D         | 2        | 1.89%   |
| Intel Pentium 4         | 2        | 1.89%   |
| Intel Core i9           | 2        | 1.89%   |
| Intel Celeron           | 2        | 1.89%   |
| AMD Ryzen 3             | 2        | 1.89%   |
| AMD Phenom II X4        | 2        | 1.89%   |
| AMD Athlon 64 X2        | 2        | 1.89%   |
| Intel Pentium           | 1        | 0.94%   |
| Intel Core 2 Quad       | 1        | 0.94%   |
| Intel Core 2            | 1        | 0.94%   |
| AMD PRO A8              | 1        | 0.94%   |
| AMD Athlon II X4        | 1        | 0.94%   |
| AMD A4                  | 1        | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 37       | 34.91%  |
| 2      | 32       | 30.19%  |
| 6      | 22       | 20.75%  |
| 8      | 10       | 9.43%   |
| 12     | 2        | 1.89%   |
| 1      | 2        | 1.89%   |
| 16     | 1        | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 99.07%  |
| 2      | 1        | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 62       | 57.94%  |
| 1      | 45       | 42.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 105      | 99.06%  |
| 32-bit         | 1        | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 29.91%  |
| 0x306c3    | 9        | 8.41%   |
| 0x206a7    | 6        | 5.61%   |
| 0x1067a    | 6        | 5.61%   |
| 0x08701021 | 5        | 4.67%   |
| 0x906e9    | 4        | 3.74%   |
| 0x306a9    | 4        | 3.74%   |
| 0x010000c8 | 4        | 3.74%   |
| 0xa0653    | 3        | 2.8%    |
| 0x0800820d | 3        | 2.8%    |
| 0x08001137 | 3        | 2.8%    |
| 0x506e3    | 2        | 1.87%   |
| 0x0a201009 | 2        | 1.87%   |
| 0x08108109 | 2        | 1.87%   |
| 0xf65      | 1        | 0.93%   |
| 0xf47      | 1        | 0.93%   |
| 0xf43      | 1        | 0.93%   |
| 0xf34      | 1        | 0.93%   |
| 0xa0671    | 1        | 0.93%   |
| 0x906ed    | 1        | 0.93%   |
| 0x906ec    | 1        | 0.93%   |
| 0x906eb    | 1        | 0.93%   |
| 0x20652    | 1        | 0.93%   |
| 0x106e5    | 1        | 0.93%   |
| 0x106a5    | 1        | 0.93%   |
| 0x0a50000b | 1        | 0.93%   |
| 0x0a201005 | 1        | 0.93%   |
| 0x08701013 | 1        | 0.93%   |
| 0x0810100b | 1        | 0.93%   |
| 0x0800820b | 1        | 0.93%   |
| 0x08001129 | 1        | 0.93%   |
| 0x0700010f | 1        | 0.93%   |
| 0x06003109 | 1        | 0.93%   |
| 0x06000852 | 1        | 0.93%   |
| 0x0600081c | 1        | 0.93%   |
| 0x0100009f | 1        | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 11       | 10.38%  |
| Haswell     | 10       | 9.43%   |
| Penryn      | 9        | 8.49%   |
| IvyBridge   | 9        | 8.49%   |
| Zen+        | 8        | 7.55%   |
| Zen 3       | 7        | 6.6%    |
| Zen 2       | 7        | 6.6%    |
| Zen         | 7        | 6.6%    |
| SandyBridge | 6        | 5.66%   |
| K10         | 6        | 5.66%   |
| Piledriver  | 4        | 3.77%   |
| NetBurst    | 4        | 3.77%   |
| CometLake   | 4        | 3.77%   |
| Skylake     | 3        | 2.83%   |
| Westmere    | 2        | 1.89%   |
| Nehalem     | 2        | 1.89%   |
| K8 Hammer   | 2        | 1.89%   |
| Steamroller | 1        | 0.94%   |
| Jaguar      | 1        | 0.94%   |
| Icelake     | 1        | 0.94%   |
| Core        | 1        | 0.94%   |
| Unknown     | 1        | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 51       | 44.74%  |
| AMD    | 33       | 28.95%  |
| Intel  | 30       | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 5.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 5.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 4.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 3.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 3.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 2.52%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.68%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.68%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.68%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1.68%   |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 1.68%   |
| Intel HD Graphics 630                                                       | 2        | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.68%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.68%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.68%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.84%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.84%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.84%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.84%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.84%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.84%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.84%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.84%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.84%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 47       | 43.52%  |
| 1 x AMD        | 29       | 26.85%  |
| 1 x Intel      | 25       | 23.15%  |
| 2 x Nvidia     | 2        | 1.85%   |
| 2 x AMD        | 2        | 1.85%   |
| Intel + Nvidia | 1        | 0.93%   |
| Intel + AMD    | 1        | 0.93%   |
| AMD + Nvidia   | 1        | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 65.14%  |
| Proprietary | 34       | 31.19%  |
| Unknown     | 4        | 3.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 30.28%  |
| 1.01-2.0   | 17       | 15.6%   |
| 3.01-4.0   | 14       | 12.84%  |
| 0.51-1.0   | 13       | 11.93%  |
| 0.01-0.5   | 13       | 11.93%  |
| 5.01-6.0   | 10       | 9.17%   |
| 7.01-8.0   | 5        | 4.59%   |
| 8.01-16.0  | 3        | 2.75%   |
| 16.01-24.0 | 1        | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 23.28%  |
| Dell                 | 15       | 12.93%  |
| AOC                  | 15       | 12.93%  |
| Philips              | 13       | 11.21%  |
| Goldstar             | 12       | 10.34%  |
| BenQ                 | 8        | 6.9%    |
| Hewlett-Packard      | 6        | 5.17%   |
| Ancor Communications | 6        | 5.17%   |
| Lenovo               | 3        | 2.59%   |
| LG Electronics       | 2        | 1.72%   |
| ViewSonic            | 1        | 0.86%   |
| Unknown (XXX)        | 1        | 0.86%   |
| Sony                 | 1        | 0.86%   |
| NEC Computers        | 1        | 0.86%   |
| Mi                   | 1        | 0.86%   |
| Medion               | 1        | 0.86%   |
| DENON                | 1        | 0.86%   |
| ASUSTek Computer     | 1        | 0.86%   |
| AGO                  | 1        | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                      | 3        | 2.29%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                      | 2        | 1.53%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 1.53%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                      | 2        | 1.53%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                       | 2        | 1.53%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 2        | 1.53%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                         | 2        | 1.53%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                  | 1        | 0.76%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch         | 1        | 0.76%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                          | 1        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.76%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.76%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch       | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM01E3 1280x1024 338x270mm 17.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 1        | 0.76%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 510x290mm 23.1-inch     | 1        | 0.76%   |
| Samsung Electronics SMBX2231 SAM076C 1920x1080 477x268mm 21.5-inch     | 1        | 0.76%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch     | 1        | 0.76%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 0.76%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1        | 0.76%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 518x324mm 24.1-inch      | 1        | 0.76%   |
| Samsung Electronics S24E450 SAM0C82 1920x1080 531x299mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics S24E450 SAM0C81 1920x1080 531x299mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics S23E650 SAM0CAF 1920x1080 510x287mm 23.0-inch      | 1        | 0.76%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch      | 1        | 0.76%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 0.76%   |
| Samsung Electronics S22E390 SAM0C17 1920x1080 477x268mm 21.5-inch      | 1        | 0.76%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch      | 1        | 0.76%   |
| Samsung Electronics LCD Monitor T24E390 3200x1080                      | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 1020x570mm 46.0-inch | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0921 1280x720 950x540mm 43.0-inch   | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 52       | 44.83%  |
| 1280x1024 (SXGA)   | 16       | 13.79%  |
| 2560x1440 (QHD)    | 15       | 12.93%  |
| 3840x2160 (4K)     | 7        | 6.03%   |
| 1366x768 (WXGA)    | 6        | 5.17%   |
| 1440x900 (WXGA+)   | 3        | 2.59%   |
| Unknown            | 3        | 2.59%   |
| 3840x1080          | 2        | 1.72%   |
| 3440x1440          | 2        | 1.72%   |
| 2560x1080          | 2        | 1.72%   |
| 1920x1200 (WUXGA)  | 2        | 1.72%   |
| 3840x1600          | 1        | 0.86%   |
| 3200x1080          | 1        | 0.86%   |
| 1680x1050 (WSXGA+) | 1        | 0.86%   |
| 1600x900 (HD+)     | 1        | 0.86%   |
| 1360x768           | 1        | 0.86%   |
| 1280x720 (HD)      | 1        | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 16.24%  |
| 23      | 19       | 16.24%  |
| 24      | 17       | 14.53%  |
| Unknown | 12       | 10.26%  |
| 21      | 11       | 9.4%    |
| 19      | 9        | 7.69%   |
| 18      | 7        | 5.98%   |
| 17      | 7        | 5.98%   |
| 34      | 3        | 2.56%   |
| 40      | 2        | 1.71%   |
| 31      | 2        | 1.71%   |
| 20      | 2        | 1.71%   |
| 84      | 1        | 0.85%   |
| 55      | 1        | 0.85%   |
| 54      | 1        | 0.85%   |
| 50      | 1        | 0.85%   |
| 25      | 1        | 0.85%   |
| 22      | 1        | 0.85%   |
| 12      | 1        | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 50       | 44.64%  |
| 401-500     | 21       | 18.75%  |
| Unknown     | 12       | 10.71%  |
| 351-400     | 8        | 7.14%   |
| 301-350     | 7        | 6.25%   |
| 601-700     | 4        | 3.57%   |
| 701-800     | 3        | 2.68%   |
| 1001-1500   | 3        | 2.68%   |
| 801-900     | 2        | 1.79%   |
| 201-300     | 1        | 0.89%   |
| 1501-2000   | 1        | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 65.14%  |
| 5/4     | 15       | 13.76%  |
| Unknown | 11       | 10.09%  |
| 16/10   | 7        | 6.42%   |
| 21/9    | 3        | 2.75%   |
| 4/3     | 1        | 0.92%   |
| 3/2     | 1        | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 32.2%   |
| 301-350        | 19       | 16.1%   |
| 151-200        | 18       | 15.25%  |
| 141-150        | 13       | 11.02%  |
| Unknown        | 12       | 10.17%  |
| 251-300        | 6        | 5.08%   |
| 351-500        | 5        | 4.24%   |
| More than 1000 | 4        | 3.39%   |
| 501-1000       | 2        | 1.69%   |
| 71-80          | 1        | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 63.64%  |
| 101-120 | 21       | 19.09%  |
| Unknown | 12       | 10.91%  |
| 161-240 | 3        | 2.73%   |
| 1-50    | 2        | 1.82%   |
| 121-160 | 2        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 77       | 72.64%  |
| 2     | 24       | 22.64%  |
| 0     | 4        | 3.77%   |
| 3     | 1        | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 66       | 49.62%  |
| Intel                    | 32       | 24.06%  |
| Qualcomm Atheros         | 11       | 8.27%   |
| Broadcom                 | 4        | 3.01%   |
| TP-Link                  | 3        | 2.26%   |
| Broadcom Limited         | 3        | 2.26%   |
| Nvidia                   | 2        | 1.5%    |
| Microsoft                | 2        | 1.5%    |
| D-Link                   | 2        | 1.5%    |
| Samsung Electronics      | 1        | 0.75%   |
| Ralink Technology        | 1        | 0.75%   |
| Ralink                   | 1        | 0.75%   |
| Marvell Technology Group | 1        | 0.75%   |
| Edimax Technology        | 1        | 0.75%   |
| D-Link System            | 1        | 0.75%   |
| ASUSTek Computer         | 1        | 0.75%   |
| 3Com                     | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 55       | 37.16%  |
| Intel I211 Gigabit Network Connection                                         | 6        | 4.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 2.7%    |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 3        | 2.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 2.03%   |
| Intel Ethernet Controller I225-V                                              | 3        | 2.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.35%   |
| Microsoft XBOX ACC                                                            | 2        | 1.35%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 1.35%   |
| Intel 82578DC Gigabit Network Connection                                      | 2        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.35%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express               | 2        | 1.35%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.68%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.68%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.68%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.68%   |
| Nvidia MCP55 Ethernet                                                         | 1        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.68%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.68%   |
| Intel Wireless 7265                                                           | 1        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 25%     |
| Realtek Semiconductor | 7        | 21.88%  |
| TP-Link               | 3        | 9.38%   |
| Qualcomm Atheros      | 3        | 9.38%   |
| Microsoft             | 2        | 6.25%   |
| D-Link                | 2        | 6.25%   |
| Broadcom              | 2        | 6.25%   |
| Ralink Technology     | 1        | 3.13%   |
| Ralink                | 1        | 3.13%   |
| Edimax Technology     | 1        | 3.13%   |
| D-Link System         | 1        | 3.13%   |
| ASUSTek Computer      | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 3        | 9.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 6.25%   |
| Microsoft XBOX ACC                                                            | 2        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 6.25%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 3.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 3.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 3.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 3.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 3.13%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 3.13%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 3.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 3.13%   |
| Intel Wireless-AC 9260                                                        | 1        | 3.13%   |
| Intel Wireless 7265                                                           | 1        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 3.13%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]             | 1        | 3.13%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1        | 3.13%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 3.13%   |
| D-Link 802.11 n WLAN                                                          | 1        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 3.13%   |
| ASUS 802.11n WLAN Adapter                                                     | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 64       | 57.14%  |
| Intel                    | 30       | 26.79%  |
| Qualcomm Atheros         | 8        | 7.14%   |
| Broadcom Limited         | 3        | 2.68%   |
| Nvidia                   | 2        | 1.79%   |
| Broadcom                 | 2        | 1.79%   |
| Samsung Electronics      | 1        | 0.89%   |
| Marvell Technology Group | 1        | 0.89%   |
| 3Com                     | 1        | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55       | 47.41%  |
| Intel I211 Gigabit Network Connection                             | 6        | 5.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.45%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 3.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 2.59%   |
| Intel Ethernet Controller I225-V                                  | 3        | 2.59%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.72%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 1.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.72%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2        | 1.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.86%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.86%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.86%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.86%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.86%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.86%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1        | 0.86%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.86%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.86%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.86%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 1        | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 77.94%  |
| WiFi     | 30       | 22.06%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 82.57%  |
| WiFi     | 19       | 17.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 78.9%   |
| 2     | 18       | 16.51%  |
| 3     | 4        | 3.67%   |
| 5     | 1        | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 52.38%  |
| Intel                   | 8        | 38.1%   |
| Edimax Technology       | 1        | 4.76%   |
| Broadcom                | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 52.38%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.52%   |
| Intel AX200 Bluetooth                               | 2        | 9.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.76%   |
| Intel Bluetooth wireless interface                  | 1        | 4.76%   |
| Intel AX210 Bluetooth                               | 1        | 4.76%   |
| Intel AX201 Bluetooth                               | 1        | 4.76%   |
| Edimax Bluetooth Adapter                            | 1        | 4.76%   |
| Broadcom Bluetooth Device                           | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 62       | 32.12%  |
| AMD                                             | 49       | 25.39%  |
| Nvidia                                          | 47       | 24.35%  |
| C-Media Electronics                             | 8        | 4.15%   |
| JMTek                                           | 6        | 3.11%   |
| Logitech                                        | 4        | 2.07%   |
| Yamaha                                          | 2        | 1.04%   |
| SteelSeries ApS                                 | 2        | 1.04%   |
| Sony                                            | 1        | 0.52%   |
| Realtek Semiconductor                           | 1        | 0.52%   |
| Razer USA                                       | 1        | 0.52%   |
| PreSonus Audio Electronics                      | 1        | 0.52%   |
| Panasonic (Matsushita)                          | 1        | 0.52%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.52%   |
| Kingston Technology                             | 1        | 0.52%   |
| Generalplus Technology                          | 1        | 0.52%   |
| Focusrite-Novation                              | 1        | 0.52%   |
| Creative Technology                             | 1        | 0.52%   |
| Creative Labs                                   | 1        | 0.52%   |
| ASUSTek Computer                                | 1        | 0.52%   |
| Allen&Heath                                     | 1        | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 5.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 4.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 4.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 4.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 3.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 2.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 2.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 2.25%   |
| JMTek USB PnP Audio Device                                                 | 5        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.35%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.35%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.35%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.35%   |
| Yamaha AG06/AG03                                                           | 2        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.9%    |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.9%    |
| Intel Audio device                                                         | 2        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 25.32%  |
| Unknown             | 13       | 16.46%  |
| G.Skill             | 10       | 12.66%  |
| Crucial             | 9        | 11.39%  |
| Patriot             | 5        | 6.33%   |
| SK hynix            | 3        | 3.8%    |
| Samsung Electronics | 3        | 3.8%    |
| Ramaxel Technology  | 3        | 3.8%    |
| A-DATA Technology   | 3        | 3.8%    |
| Transcend           | 2        | 2.53%   |
| Team                | 2        | 2.53%   |
| Nanya Technology    | 2        | 2.53%   |
| Corsair             | 2        | 2.53%   |
| Elpida              | 1        | 1.27%   |
| Atermiter           | 1        | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 2.22%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s    | 2        | 2.22%   |
| Patriot RAM PSD48G266681 8192MB DIMM DDR4 2934MT/s      | 2        | 2.22%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 2        | 2.22%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 2.22%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 2        | 2.22%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.11%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 1.11%   |
| Unknown RAM Module 512MB DIMM 800MT/s                   | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.11%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 1.11%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 1.11%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 1.11%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s             | 1        | 1.11%   |
| Transcend RAM JM2400HLB-8G 8192MB DIMM DDR4 2133MT/s    | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 1        | 1.11%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.11%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s    | 1        | 1.11%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s | 1        | 1.11%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 1.11%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 1        | 1.11%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s     | 1        | 1.11%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s     | 1        | 1.11%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s  | 1        | 1.11%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.11%   |
| Ramaxel RAM RML1520AG38D6F-667 512MB DIMM DDR2 667MT/s  | 1        | 1.11%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s         | 1        | 1.11%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s         | 1        | 1.11%   |
| Patriot RAM PSD34G13332 ...... 4GB DIMM DDR3 1600MT/s   | 1        | 1.11%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s      | 1        | 1.11%   |
| Nanya RAM M2Y51264TU88A4B-3C 512MB DIMM DDR2 667MT/s    | 1        | 1.11%   |
| Kingston RAM termiter 9.A01LF 8192MB DIMM DDR3 1067MT/s | 1        | 1.11%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s     | 1        | 1.11%   |
| Kingston RAM Module 2048MB DIMM DDR3 1333MT/s           | 1        | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 34       | 48.57%  |
| DDR3    | 22       | 31.43%  |
| Unknown | 6        | 8.57%   |
| SDRAM   | 5        | 7.14%   |
| DDR2    | 2        | 2.86%   |
| DDR     | 1        | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 67       | 98.53%  |
| SODIMM | 1        | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 42.47%  |
| 4096  | 18       | 24.66%  |
| 2048  | 10       | 13.7%   |
| 16384 | 8        | 10.96%  |
| 1024  | 3        | 4.11%   |
| 512   | 2        | 2.74%   |
| 32768 | 1        | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 18.52%  |
| 1333    | 11       | 13.58%  |
| 3200    | 9        | 11.11%  |
| 2667    | 6        | 7.41%   |
| 3600    | 4        | 4.94%   |
| 2400    | 4        | 4.94%   |
| 2133    | 4        | 4.94%   |
| 2800    | 3        | 3.7%    |
| 2666    | 3        | 3.7%    |
| 800     | 3        | 3.7%    |
| Unknown | 3        | 3.7%    |
| 3866    | 2        | 2.47%   |
| 2934    | 2        | 2.47%   |
| 667     | 2        | 2.47%   |
| 400     | 2        | 2.47%   |
| 3800    | 1        | 1.23%   |
| 3733    | 1        | 1.23%   |
| 3466    | 1        | 1.23%   |
| 3400    | 1        | 1.23%   |
| 3000    | 1        | 1.23%   |
| 1867    | 1        | 1.23%   |
| 1067    | 1        | 1.23%   |
| 1066    | 1        | 1.23%   |

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
| Logitech                      | 8        | 38.1%   |
| Samsung Electronics           | 2        | 9.52%   |
| Microdia                      | 2        | 9.52%   |
| Z-Star Microelectronics       | 1        | 4.76%   |
| Sunplus Innovation Technology | 1        | 4.76%   |
| Sonix Technology              | 1        | 4.76%   |
| Razer USA                     | 1        | 4.76%   |
| Pixart Imaging                | 1        | 4.76%   |
| Panasonic (Matsushita)        | 1        | 4.76%   |
| Huawei Technologies           | 1        | 4.76%   |
| Cubeternet                    | 1        | 4.76%   |
| Arkmicro Technologies         | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 3        | 14.29%  |
| Samsung Galaxy A5 (MTP)                                             | 2        | 9.52%   |
| Logitech HD Webcam C615                                             | 2        | 9.52%   |
| Z-Star Venus USB2.0 Camera                                          | 1        | 4.76%   |
| Sunplus AUSDOM FHD Camera                                           | 1        | 4.76%   |
| Sonix USB Camera                                                    | 1        | 4.76%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 4.76%   |
| Pixart Imaging Webcam Genius iLook 300                              | 1        | 4.76%   |
| Panasonic (Matsushita) TY-CC20W                                     | 1        | 4.76%   |
| Microdia Webcam Vitade AF                                           | 1        | 4.76%   |
| Microdia Camera                                                     | 1        | 4.76%   |
| Logitech Webcam C925e                                               | 1        | 4.76%   |
| Logitech Webcam C170                                                | 1        | 4.76%   |
| Logitech HD Pro Webcam C920                                         | 1        | 4.76%   |
| Huawei UVC Camera                                                   | 1        | 4.76%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 4.76%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 4.76%   |

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
| 0     | 99       | 92.52%  |
| 1     | 7        | 6.54%   |
| 2     | 1        | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 55.56%  |
| Network       | 1        | 11.11%  |
| Net/wireless  | 1        | 11.11%  |
| Camera        | 1        | 11.11%  |
| Bluetooth     | 1        | 11.11%  |

