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

Total: 134

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 7        | 7%      |
| Ubuntu 18.04                 | 6        | 6%      |
| Arch                         | 6        | 6%      |
| Ubuntu 21.10                 | 4        | 4%      |
| Ubuntu 19.10                 | 4        | 4%      |
| ROSA R8.1                    | 3        | 3%      |
| ROSA R11                     | 3        | 3%      |
| ROSA R10                     | 3        | 3%      |
| Pop!_OS 21.10                | 3        | 3%      |
| Pop!_OS 21.04                | 3        | 3%      |
| OpenMandriva 4.2             | 3        | 3%      |
| Manjaro 20.2.1               | 3        | 3%      |
| Manjaro                      | 3        | 3%      |
| KDE neon 20.04               | 3        | 3%      |
| Fedora 33                    | 3        | 3%      |
| Ubuntu 20.10                 | 2        | 2%      |
| ROSA 12.2                    | 2        | 2%      |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 2%      |
| Linux Mint 19.3              | 2        | 2%      |
| Fedora 32                    | 2        | 2%      |
| Debian 10                    | 2        | 2%      |
| ArcoLinux Rolling            | 2        | 2%      |
| Arch Rolling                 | 2        | 2%      |
| Zorin 16                     | 1        | 1%      |
| Xubuntu 20.04                | 1        | 1%      |
| Ubuntu 22.04                 | 1        | 1%      |
| Ubuntu 16.04                 | 1        | 1%      |
| ROSA R9                      | 1        | 1%      |
| ROSA R8                      | 1        | 1%      |
| ROSA R11.1                   | 1        | 1%      |
| RHEL 8                       | 1        | 1%      |
| Pop!_OS 22.04                | 1        | 1%      |
| Pop!_OS 20.10                | 1        | 1%      |
| Pop!_OS 20.04                | 1        | 1%      |
| Manjaro 20.0.1               | 1        | 1%      |
| Manjaro 19.0.1               | 1        | 1%      |
| Manjaro 18.0.4               | 1        | 1%      |
| Manjaro 18.0.0-rc            | 1        | 1%      |
| Linux Mint 20.3              | 1        | 1%      |
| Linux Mint 20.2              | 1        | 1%      |
| Linux Mint 20.1              | 1        | 1%      |
| Linux Mint 20                | 1        | 1%      |
| Kubuntu 20.04                | 1        | 1%      |
| Endless 3.7.6                | 1        | 1%      |
| EndeavourOS Rolling          | 1        | 1%      |
| Elementary 6.1               | 1        | 1%      |
| Deepin 20                    | 1        | 1%      |
| Deepin                       | 1        | 1%      |
| Debian Testing               | 1        | 1%      |
| CentOS 8                     | 1        | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 24       | 25.26%  |
| ROSA         | 13       | 13.68%  |
| Pop!_OS      | 9        | 9.47%   |
| Manjaro      | 9        | 9.47%   |
| Arch         | 8        | 8.42%   |
| Linux Mint   | 6        | 6.32%   |
| Fedora       | 4        | 4.21%   |
| OpenMandriva | 3        | 3.16%   |
| KDE neon     | 3        | 3.16%   |
| Debian       | 3        | 3.16%   |
| openSUSE     | 2        | 2.11%   |
| ArcoLinux    | 2        | 2.11%   |
| Zorin        | 1        | 1.05%   |
| Xubuntu      | 1        | 1.05%   |
| RHEL         | 1        | 1.05%   |
| Kubuntu      | 1        | 1.05%   |
| Endless      | 1        | 1.05%   |
| EndeavourOS  | 1        | 1.05%   |
| Elementary   | 1        | 1.05%   |
| Deepin       | 1        | 1.05%   |
| CentOS       | 1        | 1.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                   | Desktops | Percent |
|-------------------------------------------|----------|---------|
| 5.3.0-23-generic                          | 3        | 2.73%   |
| 5.10.14-desktop-1omv4002                  | 3        | 2.73%   |
| 5.9.16-1-MANJARO                          | 2        | 1.82%   |
| 5.4.0-70-generic                          | 2        | 1.82%   |
| 5.4.0-66-generic                          | 2        | 1.82%   |
| 5.4.0-48-generic                          | 2        | 1.82%   |
| 5.4.0-26-generic                          | 2        | 1.82%   |
| 5.3.0-40-generic                          | 2        | 1.82%   |
| 5.3.0-28-generic                          | 2        | 1.82%   |
| 5.3.0-24-generic                          | 2        | 1.82%   |
| 5.15.23-2-lts                             | 2        | 1.82%   |
| 5.11.0-7620-generic                       | 2        | 1.82%   |
| 4.9.60-nrj-desktop-1rosa-i586             | 2        | 1.82%   |
| 5.9.13-arch1-1                            | 1        | 0.91%   |
| 5.8.3-zen1-1-zen                          | 1        | 0.91%   |
| 5.8.17-300.fc33.x86_64                    | 1        | 0.91%   |
| 5.8.12-200.fc32.x86_64                    | 1        | 0.91%   |
| 5.8.0-7642-generic                        | 1        | 0.91%   |
| 5.8.0-48-generic                          | 1        | 0.91%   |
| 5.8.0-45-generic                          | 1        | 0.91%   |
| 5.8.0-29-generic                          | 1        | 0.91%   |
| 5.8.0-1-default                           | 1        | 0.91%   |
| 5.8.0-050800-generic                      | 1        | 0.91%   |
| 5.7.8-200.fc32.x86_64                     | 1        | 0.91%   |
| 5.7.17-050717-generic                     | 1        | 0.91%   |
| 5.7.11-arch1-1                            | 1        | 0.91%   |
| 5.6.6-1-MANJARO                           | 1        | 0.91%   |
| 5.5.3-14-tkg-pds                          | 1        | 0.91%   |
| 5.4.70-amd64-desktop                      | 1        | 0.91%   |
| 5.4.50-amd64-desktop                      | 1        | 0.91%   |
| 5.4.18-1-MANJARO                          | 1        | 0.91%   |
| 5.4.0-91-generic                          | 1        | 0.91%   |
| 5.4.0-77-generic                          | 1        | 0.91%   |
| 5.4.0-65-generic                          | 1        | 0.91%   |
| 5.4.0-42-generic                          | 1        | 0.91%   |
| 5.4.0-109-generic                         | 1        | 0.91%   |
| 5.3.0-050300-generic                      | 1        | 0.91%   |
| 5.18.3.xm1-1.klp-xanmod-rosa2021.1-x86_64 | 1        | 0.91%   |
| 5.16.19-76051619-generic                  | 1        | 0.91%   |
| 5.16.16-arch1-1                           | 1        | 0.91%   |
| 5.16.15-76051615-generic                  | 1        | 0.91%   |
| 5.16.11-76051611-generic                  | 1        | 0.91%   |
| 5.15.8-76051508-generic                   | 1        | 0.91%   |
| 5.15.3-arch1-1                            | 1        | 0.91%   |
| 5.15.15-76051515-generic                  | 1        | 0.91%   |
| 5.15.0-25-generic                         | 1        | 0.91%   |
| 5.13.12-arch1-1                           | 1        | 0.91%   |
| 5.13.0-7620-generic                       | 1        | 0.91%   |
| 5.13.0-39-generic                         | 1        | 0.91%   |
| 5.13.0-30-generic                         | 1        | 0.91%   |
| 5.13.0-28-lowlatency                      | 1        | 0.91%   |
| 5.13.0-21-generic                         | 1        | 0.91%   |
| 5.13.0-20-generic                         | 1        | 0.91%   |
| 5.13.0-12-generic                         | 1        | 0.91%   |
| 5.12.3-xanmod1-1                          | 1        | 0.91%   |
| 5.12.2-arch1-1                            | 1        | 0.91%   |
| 5.12.13-1-default                         | 1        | 0.91%   |
| 5.11.13-arch1-1                           | 1        | 0.91%   |
| 5.11.0-44-generic                         | 1        | 0.91%   |
| 5.11.0-43-generic                         | 1        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 12       | 11.76%  |
| 5.3.0    | 8        | 7.84%   |
| 4.15.0   | 8        | 7.84%   |
| 5.13.0   | 7        | 6.86%   |
| 5.8.0    | 6        | 5.88%   |
| 5.11.0   | 6        | 5.88%   |
| 5.10.14  | 3        | 2.94%   |
| 5.9.16   | 2        | 1.96%   |
| 5.15.23  | 2        | 1.96%   |
| 4.9.60   | 2        | 1.96%   |
| 4.19.0   | 2        | 1.96%   |
| 5.9.13   | 1        | 0.98%   |
| 5.8.3    | 1        | 0.98%   |
| 5.8.17   | 1        | 0.98%   |
| 5.8.12   | 1        | 0.98%   |
| 5.7.8    | 1        | 0.98%   |
| 5.7.17   | 1        | 0.98%   |
| 5.7.11   | 1        | 0.98%   |
| 5.6.6    | 1        | 0.98%   |
| 5.5.3    | 1        | 0.98%   |
| 5.4.70   | 1        | 0.98%   |
| 5.4.50   | 1        | 0.98%   |
| 5.4.18   | 1        | 0.98%   |
| 5.18.3   | 1        | 0.98%   |
| 5.16.19  | 1        | 0.98%   |
| 5.16.16  | 1        | 0.98%   |
| 5.16.15  | 1        | 0.98%   |
| 5.16.11  | 1        | 0.98%   |
| 5.15.8   | 1        | 0.98%   |
| 5.15.3   | 1        | 0.98%   |
| 5.15.15  | 1        | 0.98%   |
| 5.15.0   | 1        | 0.98%   |
| 5.13.12  | 1        | 0.98%   |
| 5.12.3   | 1        | 0.98%   |
| 5.12.2   | 1        | 0.98%   |
| 5.12.13  | 1        | 0.98%   |
| 5.11.13  | 1        | 0.98%   |
| 5.10.74  | 1        | 0.98%   |
| 5.10.7   | 1        | 0.98%   |
| 5.10.5   | 1        | 0.98%   |
| 5.10.19  | 1        | 0.98%   |
| 5.10.15  | 1        | 0.98%   |
| 5.10.12  | 1        | 0.98%   |
| 4.9.9    | 1        | 0.98%   |
| 4.9.76   | 1        | 0.98%   |
| 4.9.20   | 1        | 0.98%   |
| 4.9.124  | 1        | 0.98%   |
| 4.9.0    | 1        | 0.98%   |
| 4.19.45  | 1        | 0.98%   |
| 4.18.0   | 1        | 0.98%   |
| 4.14.78  | 1        | 0.98%   |
| 4.14.221 | 1        | 0.98%   |
| 4.14.179 | 1        | 0.98%   |
| 4.1.38   | 1        | 0.98%   |
| 4.1.34   | 1        | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 14       | 13.86%  |
| 5.8     | 9        | 8.91%   |
| 5.10    | 9        | 8.91%   |
| 5.3     | 8        | 7.92%   |
| 5.13    | 8        | 7.92%   |
| 4.15    | 8        | 7.92%   |
| 5.11    | 7        | 6.93%   |
| 4.9     | 7        | 6.93%   |
| 5.15    | 6        | 5.94%   |
| 5.16    | 4        | 3.96%   |
| 5.9     | 3        | 2.97%   |
| 5.7     | 3        | 2.97%   |
| 5.12    | 3        | 2.97%   |
| 4.19    | 3        | 2.97%   |
| 4.14    | 3        | 2.97%   |
| 4.1     | 2        | 1.98%   |
| 5.6     | 1        | 0.99%   |
| 5.5     | 1        | 0.99%   |
| 5.18    | 1        | 0.99%   |
| 4.18    | 1        | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 89       | 94.68%  |
| i686   | 5        | 5.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 36       | 37.11%  |
| KDE5          | 11       | 11.34%  |
| XFCE          | 10       | 10.31%  |
| KDE4          | 10       | 10.31%  |
| Unknown       | 10       | 10.31%  |
| KDE           | 7        | 7.22%   |
| X-Cinnamon    | 5        | 5.15%   |
| Cinnamon      | 2        | 2.06%   |
| Unity         | 1        | 1.03%   |
| Pantheon      | 1        | 1.03%   |
| MATE          | 1        | 1.03%   |
| i3            | 1        | 1.03%   |
| Enlightenment | 1        | 1.03%   |
| Deepin        | 1        | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 81       | 83.51%  |
| Wayland | 12       | 12.37%  |
| Tty     | 3        | 3.09%   |
| Unknown | 1        | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 47.37%  |
| LightDM | 12       | 12.63%  |
| KDM     | 10       | 10.53%  |
| SDDM    | 9        | 9.47%   |
| GDM     | 9        | 9.47%   |
| TDM     | 6        | 6.32%   |
| GDM3    | 4        | 4.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 50       | 52.63%  |
| Unknown | 16       | 16.84%  |
| lt_LT   | 12       | 12.63%  |
| en_GB   | 10       | 10.53%  |
| ru_RU   | 6        | 6.32%   |
| uk_UA   | 1        | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 63       | 67.02%  |
| EFI  | 31       | 32.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 73       | 76.84%  |
| Btrfs   | 7        | 7.37%   |
| Unknown | 7        | 7.37%   |
| Overlay | 5        | 5.26%   |
| Xfs     | 2        | 2.11%   |
| SAMSUNG | 1        | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 50.53%  |
| MBR     | 24       | 25.26%  |
| GPT     | 23       | 24.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 81.72%  |
| Yes       | 17       | 18.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 68.09%  |
| Yes       | 30       | 31.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 26.88%  |
| ASRock              | 18       | 19.35%  |
| Gigabyte Technology | 17       | 18.28%  |
| MSI                 | 15       | 16.13%  |
| Intel               | 6        | 6.45%   |
| Hewlett-Packard     | 6        | 6.45%   |
| Dell                | 4        | 4.3%    |
| Fujitsu Siemens     | 1        | 1.08%   |
| Fujitsu             | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7A38                        | 3        | 3.23%   |
| MSI MS-7C82                        | 2        | 2.15%   |
| MSI MS-7823                        | 2        | 2.15%   |
| MSI MS-7817                        | 2        | 2.15%   |
| ASUS PRIME Z390-A                  | 2        | 2.15%   |
| ASUS PRIME B450M-A                 | 2        | 2.15%   |
| ASUS All Series                    | 2        | 2.15%   |
| MSI MS-7C35                        | 1        | 1.08%   |
| MSI MS-7B89                        | 1        | 1.08%   |
| MSI MS-7A71                        | 1        | 1.08%   |
| MSI MS-7A34                        | 1        | 1.08%   |
| MSI MS-7977                        | 1        | 1.08%   |
| MSI MS-7788                        | 1        | 1.08%   |
| Intel DP55WB AAE64798-205          | 1        | 1.08%   |
| Intel DH67BL AAG10189-208          | 1        | 1.08%   |
| Intel DH61WW AAG23116-206          | 1        | 1.08%   |
| Intel DH55HC AAE70933-501          | 1        | 1.08%   |
| Intel DB65AL AAG12530-302          | 1        | 1.08%   |
| Intel D102GGC2 AAD42789-201        | 1        | 1.08%   |
| HP Z420 Workstation                | 1        | 1.08%   |
| HP EliteDesk 705 G2 SFF            | 1        | 1.08%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.08%   |
| HP Compaq dc5750 Small Form Factor | 1        | 1.08%   |
| HP Compaq dc5700 Microtower        | 1        | 1.08%   |
| HP Compaq 6000 Pro SFF PC          | 1        | 1.08%   |
| Gigabyte Z370M DS3H                | 1        | 1.08%   |
| Gigabyte X570 GAMING X             | 1        | 1.08%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 1.08%   |
| Gigabyte X570 AORUS ELITE          | 1        | 1.08%   |
| Gigabyte P41-ES3G                  | 1        | 1.08%   |
| Gigabyte M68MT-S2P                 | 1        | 1.08%   |
| Gigabyte M55S-S3                   | 1        | 1.08%   |
| Gigabyte H81M-D2V                  | 1        | 1.08%   |
| Gigabyte H77M-D3H                  | 1        | 1.08%   |
| Gigabyte H61M-DS2 DVI              | 1        | 1.08%   |
| Gigabyte H55M-UD2H                 | 1        | 1.08%   |
| Gigabyte GA-78LMT-USB3 R2          | 1        | 1.08%   |
| Gigabyte B85M-HD3                  | 1        | 1.08%   |
| Gigabyte B450M S2H                 | 1        | 1.08%   |
| Gigabyte B250M-DS3H                | 1        | 1.08%   |
| Gigabyte B250M-D3H                 | 1        | 1.08%   |
| Gigabyte A320M-H                   | 1        | 1.08%   |
| Fujitsu Siemens ESPRIMO E5730      | 1        | 1.08%   |
| Fujitsu S1100F                     | 1        | 1.08%   |
| Dell Vostro 270s                   | 1        | 1.08%   |
| Dell Vostro 270                    | 1        | 1.08%   |
| Dell OptiPlex 780                  | 1        | 1.08%   |
| Dell OptiPlex 7020                 | 1        | 1.08%   |
| ASUS X79-DELUXE                    | 1        | 1.08%   |
| ASUS TUF Gaming Z590-PLUS WIFI     | 1        | 1.08%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 1.08%   |
| ASUS ROG STRIX Z590-E GAMING WIFI  | 1        | 1.08%   |
| ASUS PRIME H510M-R                 | 1        | 1.08%   |
| ASUS PRIME H310M-R R2.0            | 1        | 1.08%   |
| ASUS PRIME H310M-E                 | 1        | 1.08%   |
| ASUS PRIME B450M-K                 | 1        | 1.08%   |
| ASUS PRIME B350M-A                 | 1        | 1.08%   |
| ASUS PRIME A320M-R                 | 1        | 1.08%   |
| ASUS P8Z68-V LX                    | 1        | 1.08%   |
| ASUS P5QPL-AM                      | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 10       | 10.75%  |
| HP Compaq               | 4        | 4.3%    |
| MSI MS-7A38             | 3        | 3.23%   |
| Gigabyte X570           | 3        | 3.23%   |
| MSI MS-7C82             | 2        | 2.15%   |
| MSI MS-7823             | 2        | 2.15%   |
| MSI MS-7817             | 2        | 2.15%   |
| Dell Vostro             | 2        | 2.15%   |
| Dell OptiPlex           | 2        | 2.15%   |
| ASUS TUF                | 2        | 2.15%   |
| ASUS All                | 2        | 2.15%   |
| ASRock B450             | 2        | 2.15%   |
| MSI MS-7C35             | 1        | 1.08%   |
| MSI MS-7B89             | 1        | 1.08%   |
| MSI MS-7A71             | 1        | 1.08%   |
| MSI MS-7A34             | 1        | 1.08%   |
| MSI MS-7977             | 1        | 1.08%   |
| MSI MS-7788             | 1        | 1.08%   |
| Intel DP55WB            | 1        | 1.08%   |
| Intel DH67BL            | 1        | 1.08%   |
| Intel DH61WW            | 1        | 1.08%   |
| Intel DH55HC            | 1        | 1.08%   |
| Intel DB65AL            | 1        | 1.08%   |
| Intel D102GGC2          | 1        | 1.08%   |
| HP Z420                 | 1        | 1.08%   |
| HP EliteDesk            | 1        | 1.08%   |
| Gigabyte Z370M          | 1        | 1.08%   |
| Gigabyte P41-ES3G       | 1        | 1.08%   |
| Gigabyte M68MT-S2P      | 1        | 1.08%   |
| Gigabyte M55S-S3        | 1        | 1.08%   |
| Gigabyte H81M-D2V       | 1        | 1.08%   |
| Gigabyte H77M-D3H       | 1        | 1.08%   |
| Gigabyte H61M-DS2       | 1        | 1.08%   |
| Gigabyte H55M-UD2H      | 1        | 1.08%   |
| Gigabyte GA-78LMT-USB3  | 1        | 1.08%   |
| Gigabyte B85M-HD3       | 1        | 1.08%   |
| Gigabyte B450M          | 1        | 1.08%   |
| Gigabyte B250M-DS3H     | 1        | 1.08%   |
| Gigabyte B250M-D3H      | 1        | 1.08%   |
| Gigabyte A320M-H        | 1        | 1.08%   |
| Fujitsu Siemens ESPRIMO | 1        | 1.08%   |
| Fujitsu S1100F          | 1        | 1.08%   |
| ASUS X79-DELUXE         | 1        | 1.08%   |
| ASUS ROG                | 1        | 1.08%   |
| ASUS P8Z68-V            | 1        | 1.08%   |
| ASUS P5QPL-AM           | 1        | 1.08%   |
| ASUS Maximus            | 1        | 1.08%   |
| ASUS M5A97              | 1        | 1.08%   |
| ASUS M5A78L-M           | 1        | 1.08%   |
| ASUS M4A785T-M          | 1        | 1.08%   |
| ASUS H110M-R            | 1        | 1.08%   |
| ASUS H110M-C            | 1        | 1.08%   |
| ASUS GG638AA-ABU        | 1        | 1.08%   |
| ASRock Z87              | 1        | 1.08%   |
| ASRock X570M            | 1        | 1.08%   |
| ASRock X370             | 1        | 1.08%   |
| ASRock QC5000M-ITX      | 1        | 1.08%   |
| ASRock H61M-VS          | 1        | 1.08%   |
| ASRock H61M             | 1        | 1.08%   |
| ASRock G41M-VS3         | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 18       | 19.35%  |
| 2013 | 10       | 10.75%  |
| 2009 | 10       | 10.75%  |
| 2019 | 6        | 6.45%   |
| 2017 | 6        | 6.45%   |
| 2016 | 6        | 6.45%   |
| 2015 | 6        | 6.45%   |
| 2012 | 6        | 6.45%   |
| 2010 | 5        | 5.38%   |
| 2011 | 4        | 4.3%    |
| 2006 | 4        | 4.3%    |
| 2021 | 3        | 3.23%   |
| 2020 | 3        | 3.23%   |
| 2007 | 3        | 3.23%   |
| 2014 | 1        | 1.08%   |
| 2008 | 1        | 1.08%   |
| 2005 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 92       | 97.87%  |
| Enabled  | 2        | 2.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 29.79%  |
| 3.01-4.0    | 18       | 19.15%  |
| 8.01-16.0   | 17       | 18.09%  |
| 4.01-8.0    | 12       | 12.77%  |
| 32.01-64.0  | 9        | 9.57%   |
| 64.01-256.0 | 4        | 4.26%   |
| 1.01-2.0    | 3        | 3.19%   |
| 2.01-3.0    | 2        | 2.13%   |
| 24.01-32.0  | 1        | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 32       | 29.91%  |
| 2.01-3.0   | 22       | 20.56%  |
| 4.01-8.0   | 19       | 17.76%  |
| 3.01-4.0   | 16       | 14.95%  |
| 0.51-1.0   | 11       | 10.28%  |
| 8.01-16.0  | 5        | 4.67%   |
| 24.01-32.0 | 1        | 0.93%   |
| 16.01-24.0 | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 39.8%   |
| 2      | 30       | 30.61%  |
| 3      | 18       | 18.37%  |
| 4      | 7        | 7.14%   |
| 5      | 4        | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 60%     |
| Yes       | 38       | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 93       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 72.63%  |
| Yes       | 26       | 27.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 83.87%  |
| Yes       | 15       | 16.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Lithuania | 93       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Vilnius      | 45       | 46.88%  |
| Kaunas       | 19       | 19.79%  |
| Šiauliai    | 6        | 6.25%   |
| Klaipėda    | 6        | 6.25%   |
| Telšiai     | 2        | 2.08%   |
| Mažeikiai   | 2        | 2.08%   |
| Elektrėnai  | 2        | 2.08%   |
| Alytus       | 2        | 2.08%   |
| Vainutas     | 1        | 1.04%   |
| Ukmerge      | 1        | 1.04%   |
| Tauragė     | 1        | 1.04%   |
| Šilalė     | 1        | 1.04%   |
| Raseiniai    | 1        | 1.04%   |
| Panevezys    | 1        | 1.04%   |
| Nemenčinė  | 1        | 1.04%   |
| Lentvaris    | 1        | 1.04%   |
| Kėdainiai   | 1        | 1.04%   |
| Gargždai    | 1        | 1.04%   |
| Druskininkai | 1        | 1.04%   |
| Anykščiai  | 1        | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 35       | 60     | 20.23%  |
| WDC                 | 28       | 38     | 16.18%  |
| Seagate             | 22       | 31     | 12.72%  |
| Kingston            | 15       | 25     | 8.67%   |
| A-DATA Technology   | 14       | 16     | 8.09%   |
| Toshiba             | 12       | 15     | 6.94%   |
| Crucial             | 9        | 11     | 5.2%    |
| Patriot             | 5        | 5      | 2.89%   |
| Hitachi             | 5        | 5      | 2.89%   |
| Transcend           | 2        | 2      | 1.16%   |
| SanDisk             | 2        | 2      | 1.16%   |
| JMicron Technology  | 2        | 2      | 1.16%   |
| Goodram             | 2        | 2      | 1.16%   |
| China               | 2        | 2      | 1.16%   |
| XrayDisk            | 1        | 1      | 0.58%   |
| XPG                 | 1        | 1      | 0.58%   |
| Unknown             | 1        | 1      | 0.58%   |
| StoreJet            | 1        | 1      | 0.58%   |
| PNY                 | 1        | 1      | 0.58%   |
| Plextor             | 1        | 1      | 0.58%   |
| Phison              | 1        | 1      | 0.58%   |
| OCZ                 | 1        | 2      | 0.58%   |
| Netac               | 1        | 1      | 0.58%   |
| Leven               | 1        | 3      | 0.58%   |
| Intel               | 1        | 1      | 0.58%   |
| HGST                | 1        | 1      | 0.58%   |
| Hewlett-Packard     | 1        | 1      | 0.58%   |
| Gigabyte Technology | 1        | 1      | 0.58%   |
| ExcelStor           | 1        | 1      | 0.58%   |
| Dahua               | 1        | 1      | 0.58%   |
| Colorful            | 1        | 1      | 0.58%   |
| Apacer              | 1        | 3      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 6        | 3.14%   |
| WDC WD20EFRX-68EUZN0 2TB               | 4        | 2.09%   |
| Samsung SSD 860 EVO 250GB              | 4        | 2.09%   |
| Samsung SSD 860 EVO 500GB              | 3        | 1.57%   |
| Samsung SSD 850 EVO 250GB              | 3        | 1.57%   |
| Samsung NVMe SSD Drive 1TB             | 3        | 1.57%   |
| Samsung HD501LJ 500GB                  | 3        | 1.57%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.57%   |
| A-DATA SU650 120GB SSD                 | 3        | 1.57%   |
| WDC WD800AAJS-60PSA0 80GB              | 2        | 1.05%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 1.05%   |
| Toshiba MK3261GSYN 320GB               | 2        | 1.05%   |
| Toshiba HDWE140 4TB                    | 2        | 1.05%   |
| Toshiba DT01ACA100 1TB                 | 2        | 1.05%   |
| Seagate ST3500418AS 500GB              | 2        | 1.05%   |
| SanDisk NVMe SSD Drive 500GB           | 2        | 1.05%   |
| Samsung SSD 970 EVO 500GB              | 2        | 1.05%   |
| Samsung SSD 850 EVO 500GB              | 2        | 1.05%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2        | 1.05%   |
| Patriot Burst 480GB SSD                | 2        | 1.05%   |
| Patriot Burst 120GB SSD                | 2        | 1.05%   |
| Kingston SV300S37A120G 120GB SSD       | 2        | 1.05%   |
| Kingston SUV400S37240G 240GB SSD       | 2        | 1.05%   |
| Hitachi HDS721050CLA362 500GB          | 2        | 1.05%   |
| Goodram SSD 120GB                      | 2        | 1.05%   |
| Crucial CT480BX500SSD1 480GB           | 2        | 1.05%   |
| Crucial CT120BX500SSD1 120GB           | 2        | 1.05%   |
| A-DATA SX900 128GB SSD                 | 2        | 1.05%   |
| A-DATA SX8200PNP 512GB                 | 2        | 1.05%   |
| A-DATA SP900 64GB SSD                  | 2        | 1.05%   |
| XrayDisk SSD 512GB                     | 1        | 0.52%   |
| XPG GAMMIX S5 1TB                      | 1        | 0.52%   |
| WDC WDS200T3X0C-00SJG0 2TB             | 1        | 0.52%   |
| WDC WD800JD-60LSA5 80GB                | 1        | 0.52%   |
| WDC WD7500BPKX-75HPJT0 752GB           | 1        | 0.52%   |
| WDC WD6400BPVT-80HXZT1 640GB           | 1        | 0.52%   |
| WDC WD64 00BEVT-22A0RT0 640GB          | 1        | 0.52%   |
| WDC WD5000LPVX-80V0TT0 500GB           | 1        | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 1        | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 1        | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB            | 1        | 0.52%   |
| WDC WD5000AAKS-08V0A0 500GB            | 1        | 0.52%   |
| WDC WD5000AAKS-00YGA0 500GB            | 1        | 0.52%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 1        | 0.52%   |
| WDC WD32 00BPVT-00JJ5T0 320GB          | 1        | 0.52%   |
| WDC WD30PURX-64P6ZY0 3TB               | 1        | 0.52%   |
| WDC WD2500KS-00MJB0 250GB              | 1        | 0.52%   |
| WDC WD2500AAJS-75M0A0 249GB            | 1        | 0.52%   |
| WDC WD10PURX-64E5EY0 1TB               | 1        | 0.52%   |
| WDC WD10EZEX-60ZF5A0 1TB               | 1        | 0.52%   |
| WDC WD10EZEX-60WN4A0 1TB               | 1        | 0.52%   |
| WDC WD10EZEX-08M2NA0 1TB               | 1        | 0.52%   |
| WDC WD10EZEX-07M2NA1 1TB               | 1        | 0.52%   |
| WDC WD10EZEX-00BBHA0 1TB               | 1        | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB                | 1        | 0.52%   |
| Unknown RCESSD 512GB                   | 1        | 0.52%   |
| Transcend TS64GMTS400S 64GB SSD        | 1        | 0.52%   |
| Transcend TS16GHSD370 16GB SSD         | 1        | 0.52%   |
| Toshiba RD400 256GB                    | 1        | 0.52%   |
| Toshiba MQ01ABD100 1TB                 | 1        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 37     | 34.62%  |
| Seagate             | 22       | 31     | 28.21%  |
| Toshiba             | 11       | 14     | 14.1%   |
| Samsung Electronics | 10       | 19     | 12.82%  |
| Hitachi             | 5        | 5      | 6.41%   |
| JMicron Technology  | 1        | 1      | 1.28%   |
| HGST                | 1        | 1      | 1.28%   |
| ExcelStor           | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 28     | 25%     |
| Kingston            | 13       | 22     | 17.11%  |
| A-DATA Technology   | 11       | 13     | 14.47%  |
| Crucial             | 8        | 10     | 10.53%  |
| Patriot             | 5        | 5      | 6.58%   |
| Transcend           | 2        | 2      | 2.63%   |
| Goodram             | 2        | 2      | 2.63%   |
| China               | 2        | 2      | 2.63%   |
| XrayDisk            | 1        | 1      | 1.32%   |
| Unknown             | 1        | 1      | 1.32%   |
| StoreJet            | 1        | 1      | 1.32%   |
| PNY                 | 1        | 1      | 1.32%   |
| Plextor             | 1        | 1      | 1.32%   |
| OCZ                 | 1        | 2      | 1.32%   |
| Netac               | 1        | 1      | 1.32%   |
| Leven               | 1        | 3      | 1.32%   |
| Intel               | 1        | 1      | 1.32%   |
| Hewlett-Packard     | 1        | 1      | 1.32%   |
| Gigabyte Technology | 1        | 1      | 1.32%   |
| Dahua               | 1        | 1      | 1.32%   |
| Colorful            | 1        | 1      | 1.32%   |
| Apacer              | 1        | 3      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 63       | 103    | 42.28%  |
| HDD     | 63       | 109    | 42.28%  |
| NVMe    | 22       | 26     | 14.77%  |
| Unknown | 1        | 1      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 90       | 207    | 76.27%  |
| NVMe | 22       | 26     | 18.64%  |
| SAS  | 6        | 6      | 5.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 80       | 153    | 62.5%   |
| 0.51-1.0   | 30       | 38     | 23.44%  |
| 1.01-2.0   | 11       | 13     | 8.59%   |
| 3.01-4.0   | 4        | 4      | 3.13%   |
| 2.01-3.0   | 2        | 3      | 1.56%   |
| 4.01-10.0  | 1        | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 28       | 27.45%  |
| 251-500        | 21       | 20.59%  |
| 1001-2000      | 13       | 12.75%  |
| 501-1000       | 12       | 11.76%  |
| More than 3000 | 7        | 6.86%   |
| 1-20           | 7        | 6.86%   |
| 51-100         | 6        | 5.88%   |
| 2001-3000      | 4        | 3.92%   |
| 21-50          | 2        | 1.96%   |
| Unknown        | 2        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 34.29%  |
| 101-250        | 13       | 12.38%  |
| 51-100         | 13       | 12.38%  |
| 251-500        | 12       | 11.43%  |
| 1001-2000      | 8        | 7.62%   |
| 501-1000       | 8        | 7.62%   |
| 21-50          | 7        | 6.67%   |
| More than 3000 | 5        | 4.76%   |
| Unknown        | 2        | 1.9%    |
| 2001-3000      | 1        | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD800AAJS-60PSA0 80GB         | 2        | 2      | 9.52%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 3      | 9.52%   |
| Toshiba MK3261GSYN 320GB          | 2        | 2      | 9.52%   |
| WDC WD6400BPVT-80HXZT1 640GB      | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB            | 1        | 1      | 4.76%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 4.76%   |
| Seagate ST500LX012-SSHD-8GB       | 1        | 1      | 4.76%   |
| Seagate ST3250410AS 250GB         | 1        | 1      | 4.76%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 4.76%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 4.76%   |
| Samsung Electronics HD080HJ/ 80GB | 1        | 4      | 4.76%   |
| Leven JAJS300M240C 240GB SSD      | 1        | 3      | 4.76%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 4.76%   |
| ExcelStor Technology J8160S 164GB | 1        | 1      | 4.76%   |
| Crucial CT525MX300SSD1 528GB      | 1        | 1      | 4.76%   |
| Colorful SL300 120GB SSD          | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 30%     |
| Seagate             | 3        | 3      | 15%     |
| Samsung Electronics | 3        | 6      | 15%     |
| Toshiba             | 2        | 3      | 10%     |
| Leven               | 1        | 3      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| Hitachi             | 1        | 1      | 5%      |
| ExcelStor           | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |
| Colorful            | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 37.5%   |
| Seagate             | 3        | 3      | 18.75%  |
| Samsung Electronics | 3        | 6      | 18.75%  |
| Toshiba             | 2        | 3      | 12.5%   |
| Hitachi             | 1        | 1      | 6.25%   |
| ExcelStor           | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 21     | 75%     |
| SSD  | 4        | 6      | 25%     |

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
| Detected | 53       | 129    | 49.53%  |
| Works    | 38       | 81     | 35.51%  |
| Malfunc  | 15       | 27     | 14.02%  |
| Failed   | 1        | 2      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 56       | 44.8%   |
| AMD                         | 34       | 27.2%   |
| Samsung Electronics         | 10       | 8%      |
| ASMedia Technology          | 6        | 4.8%    |
| SanDisk                     | 3        | 2.4%    |
| Nvidia                      | 3        | 2.4%    |
| Realtek Semiconductor       | 2        | 1.6%    |
| Marvell Technology Group    | 2        | 1.6%    |
| Kingston Technology Company | 2        | 1.6%    |
| JMicron Technology          | 2        | 1.6%    |
| ADATA Technology            | 2        | 1.6%    |
| Phison Electronics          | 1        | 0.8%    |
| OCZ Technology Group        | 1        | 0.8%    |
| Micron/Crucial Technology   | 1        | 0.8%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 12.87%  |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 6.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 5.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 4.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.34%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.75%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.75%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.17%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.17%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.17%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.17%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.58%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.58%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.58%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.58%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.58%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.58%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.58%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.58%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.58%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.58%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.58%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.58%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 0.58%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.58%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.58%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.58%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.58%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.58%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.58%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.58%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.58%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.58%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.58%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.58%   |
| Intel 500 Series Chipset Family SATA RAID Controller                                    | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 73       | 57.48%  |
| IDE  | 27       | 21.26%  |
| NVMe | 22       | 17.32%  |
| RAID | 4        | 3.15%   |
| SAS  | 1        | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 57       | 61.29%  |
| AMD    | 36       | 38.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 3.23%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 2.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 2.15%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 2.15%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 2.15%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.15%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.15%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 2.15%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.15%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 2.15%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.15%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 2.15%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.15%   |
| AMD Athlon II X2 260 Processor              | 2        | 2.15%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.08%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 1.08%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.08%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.08%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 1.08%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.08%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.08%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.08%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.08%   |
| Intel Core i5-9600KF CPU @ 3.70GHz          | 1        | 1.08%   |
| Intel Core i5-9600 CPU @ 3.10GHz            | 1        | 1.08%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.08%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.08%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.08%   |
| Intel Core i5 CPU 661 @ 3.33GHz             | 1        | 1.08%   |
| Intel Core i5 CPU 660 @ 3.33GHz             | 1        | 1.08%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.08%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.08%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 1        | 1.08%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.08%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.08%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.08%   |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 1        | 1.08%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.08%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 1.08%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz     | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 19.35%  |
| AMD Ryzen 5             | 17       | 18.28%  |
| Intel Core i3           | 10       | 10.75%  |
| Intel Core i7           | 8        | 8.6%    |
| Intel Pentium Dual-Core | 5        | 5.38%   |
| AMD Ryzen 7             | 4        | 4.3%    |
| Intel Core 2 Duo        | 3        | 3.23%   |
| AMD FX                  | 3        | 3.23%   |
| AMD Athlon II X2        | 3        | 3.23%   |
| Other                   | 2        | 2.15%   |
| Intel Pentium D         | 2        | 2.15%   |
| Intel Pentium 4         | 2        | 2.15%   |
| Intel Celeron           | 2        | 2.15%   |
| AMD Ryzen 9             | 2        | 2.15%   |
| AMD Athlon 64 X2        | 2        | 2.15%   |
| Intel Xeon              | 1        | 1.08%   |
| Intel Pentium           | 1        | 1.08%   |
| Intel Core i9           | 1        | 1.08%   |
| Intel Core 2 Quad       | 1        | 1.08%   |
| Intel Core 2            | 1        | 1.08%   |
| AMD Ryzen 3             | 1        | 1.08%   |
| AMD PRO A8              | 1        | 1.08%   |
| AMD Phenom II X4        | 1        | 1.08%   |
| AMD Athlon II X4        | 1        | 1.08%   |
| AMD A4                  | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 33.33%  |
| 4      | 30       | 32.26%  |
| 6      | 21       | 22.58%  |
| 8      | 7        | 7.53%   |
| 12     | 2        | 2.15%   |
| 1      | 2        | 2.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 98.94%  |
| 2      | 1        | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 52       | 55.32%  |
| 1      | 42       | 44.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 92       | 98.92%  |
| 32-bit         | 1        | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 27.66%  |
| 0x306c3    | 9        | 9.57%   |
| 0x1067a    | 6        | 6.38%   |
| 0x206a7    | 5        | 5.32%   |
| 0x08701021 | 5        | 5.32%   |
| 0x906e9    | 4        | 4.26%   |
| 0x306a9    | 4        | 4.26%   |
| 0x08001137 | 3        | 3.19%   |
| 0x010000c8 | 3        | 3.19%   |
| 0xa0653    | 2        | 2.13%   |
| 0x506e3    | 2        | 2.13%   |
| 0x0a201009 | 2        | 2.13%   |
| 0x0800820d | 2        | 2.13%   |
| 0xf65      | 1        | 1.06%   |
| 0xf47      | 1        | 1.06%   |
| 0xf43      | 1        | 1.06%   |
| 0xf34      | 1        | 1.06%   |
| 0xa0671    | 1        | 1.06%   |
| 0x906ed    | 1        | 1.06%   |
| 0x906ec    | 1        | 1.06%   |
| 0x906eb    | 1        | 1.06%   |
| 0x20652    | 1        | 1.06%   |
| 0x106e5    | 1        | 1.06%   |
| 0x0a201005 | 1        | 1.06%   |
| 0x08701013 | 1        | 1.06%   |
| 0x08108109 | 1        | 1.06%   |
| 0x0810100b | 1        | 1.06%   |
| 0x0800820b | 1        | 1.06%   |
| 0x08001129 | 1        | 1.06%   |
| 0x0700010f | 1        | 1.06%   |
| 0x06003109 | 1        | 1.06%   |
| 0x06000852 | 1        | 1.06%   |
| 0x0600081c | 1        | 1.06%   |
| 0x0100009f | 1        | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 10       | 10.75%  |
| Haswell     | 10       | 10.75%  |
| Penryn      | 9        | 9.68%   |
| IvyBridge   | 8        | 8.6%    |
| Zen         | 7        | 7.53%   |
| Zen+        | 6        | 6.45%   |
| Zen 2       | 6        | 6.45%   |
| Zen 3       | 5        | 5.38%   |
| SandyBridge | 5        | 5.38%   |
| K10         | 5        | 5.38%   |
| NetBurst    | 4        | 4.3%    |
| Piledriver  | 3        | 3.23%   |
| CometLake   | 3        | 3.23%   |
| Westmere    | 2        | 2.15%   |
| Skylake     | 2        | 2.15%   |
| K8 Hammer   | 2        | 2.15%   |
| Steamroller | 1        | 1.08%   |
| Nehalem     | 1        | 1.08%   |
| Jaguar      | 1        | 1.08%   |
| Icelake     | 1        | 1.08%   |
| Core        | 1        | 1.08%   |
| Unknown     | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 46       | 45.54%  |
| AMD    | 28       | 27.72%  |
| Intel  | 27       | 26.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 4.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 4.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 3.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 3.77%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.89%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.89%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.89%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1.89%   |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 1.89%   |
| Intel HD Graphics 630                                                       | 2        | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.89%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.89%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.89%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.94%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.94%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.94%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.94%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.94%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.94%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.94%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.94%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.94%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.94%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.94%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.94%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.94%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.94%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 0.94%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.94%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 0.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.94%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 0.94%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 0.94%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1        | 0.94%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 0.94%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 0.94%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 0.94%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 0.94%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 0.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 0.94%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 42       | 44.21%  |
| 1 x AMD        | 24       | 25.26%  |
| 1 x Intel      | 22       | 23.16%  |
| 2 x Nvidia     | 2        | 2.11%   |
| 2 x AMD        | 2        | 2.11%   |
| Intel + Nvidia | 1        | 1.05%   |
| Intel + AMD    | 1        | 1.05%   |
| AMD + Nvidia   | 1        | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 62       | 64.58%  |
| Proprietary | 30       | 31.25%  |
| Unknown     | 4        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 29.17%  |
| 1.01-2.0   | 15       | 15.63%  |
| 3.01-4.0   | 14       | 14.58%  |
| 0.51-1.0   | 12       | 12.5%   |
| 0.01-0.5   | 11       | 11.46%  |
| 5.01-6.0   | 9        | 9.38%   |
| 7.01-8.0   | 5        | 5.21%   |
| 8.01-16.0  | 2        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 25       | 25.25%  |
| Dell                 | 14       | 14.14%  |
| Philips              | 13       | 13.13%  |
| AOC                  | 11       | 11.11%  |
| Goldstar             | 10       | 10.1%   |
| BenQ                 | 7        | 7.07%   |
| Ancor Communications | 4        | 4.04%   |
| Lenovo               | 3        | 3.03%   |
| Hewlett-Packard      | 3        | 3.03%   |
| LG Electronics       | 2        | 2.02%   |
| ViewSonic            | 1        | 1.01%   |
| Sony                 | 1        | 1.01%   |
| Mi                   | 1        | 1.01%   |
| Medion               | 1        | 1.01%   |
| DENON                | 1        | 1.01%   |
| ASUSTek Computer     | 1        | 1.01%   |
| AGO                  | 1        | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                      | 3        | 2.65%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                      | 2        | 1.77%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 1.77%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                      | 2        | 1.77%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 2        | 1.77%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                         | 2        | 1.77%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                  | 1        | 0.88%   |
| Sony TV SNY2C02 1920x1080 1018x573mm 46.0-inch                         | 1        | 0.88%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.88%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.88%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch       | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch    | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01E3 1280x1024 338x270mm 17.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 1        | 0.88%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch     | 1        | 0.88%   |
| Samsung Electronics SMBX2231 SAM076C 1920x1080 477x268mm 21.5-inch     | 1        | 0.88%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch     | 1        | 0.88%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.88%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 518x324mm 24.1-inch      | 1        | 0.88%   |
| Samsung Electronics S24E450 SAM0C82 1920x1080 531x299mm 24.0-inch      | 1        | 0.88%   |
| Samsung Electronics S24E450 SAM0C81 1920x1080 531x299mm 24.0-inch      | 1        | 0.88%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.88%   |
| Samsung Electronics S23E650 SAM0CAF 1920x1080 510x287mm 23.0-inch      | 1        | 0.88%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch      | 1        | 0.88%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 0.88%   |
| Samsung Electronics S22E390 SAM0C17 1920x1080 477x268mm 21.5-inch      | 1        | 0.88%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch      | 1        | 0.88%   |
| Samsung Electronics LCD Monitor T24E390 3200x1080                      | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 950x540mm 43.0-inch  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0921 1920x1080 1120x630mm 50.6-inch | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 0.88%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch               | 1        | 0.88%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch               | 1        | 0.88%   |
| Philips PHL 272B7QPJ PHL0900 2560x1440 597x336mm 27.0-inch             | 1        | 0.88%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 1        | 0.88%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1        | 0.88%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 510x290mm 23.1-inch                | 1        | 0.88%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch                | 1        | 0.88%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 0.88%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 1        | 0.88%   |
| Philips 227ELH PHLC07B 1920x1080 480x268mm 21.6-inch                   | 1        | 0.88%   |
| Philips 227EL PHLC079 1920x1080 480x268mm 21.6-inch                    | 1        | 0.88%   |
| Philips 226CL PHLC058 1920x1080 477x268mm 21.5-inch                    | 1        | 0.88%   |
| Philips 190C PHLC037 1440x900 408x255mm 18.9-inch                      | 1        | 0.88%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                       | 1        | 0.88%   |
| Medion MD30919PO S09 MED89AD 1280x1024 376x301mm 19.0-inch             | 1        | 0.88%   |
| LG Electronics LCD Monitor LG HDR 4K 3840x2160                         | 1        | 0.88%   |
| LG Electronics LCD Monitor 22EA53 1920x1080                            | 1        | 0.88%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch               | 1        | 0.88%   |
| Lenovo LCD Monitor LEN0BD0 1920x1080 510x290mm 23.1-inch               | 1        | 0.88%   |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch             | 1        | 0.88%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch           | 1        | 0.88%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch              | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 47       | 47%     |
| 1280x1024 (SXGA)  | 14       | 14%     |
| 2560x1440 (QHD)   | 12       | 12%     |
| 3840x2160 (4K)    | 6        | 6%      |
| 1366x768 (WXGA)   | 6        | 6%      |
| 1440x900 (WXGA+)  | 3        | 3%      |
| 3440x1440         | 2        | 2%      |
| 2560x1080         | 2        | 2%      |
| 1920x1200 (WUXGA) | 2        | 2%      |
| 3840x1600         | 1        | 1%      |
| 3200x1080         | 1        | 1%      |
| 1600x900 (HD+)    | 1        | 1%      |
| 1360x768          | 1        | 1%      |
| 1280x720 (HD)     | 1        | 1%      |
| Unknown           | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 17       | 16.67%  |
| 24      | 16       | 15.69%  |
| 23      | 16       | 15.69%  |
| 21      | 10       | 9.8%    |
| Unknown | 10       | 9.8%    |
| 19      | 8        | 7.84%   |
| 18      | 7        | 6.86%   |
| 17      | 6        | 5.88%   |
| 34      | 3        | 2.94%   |
| 40      | 2        | 1.96%   |
| 20      | 2        | 1.96%   |
| 84      | 1        | 0.98%   |
| 55      | 1        | 0.98%   |
| 50      | 1        | 0.98%   |
| 25      | 1        | 0.98%   |
| 12      | 1        | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 44       | 45.36%  |
| 401-500     | 19       | 19.59%  |
| Unknown     | 10       | 10.31%  |
| 351-400     | 7        | 7.22%   |
| 301-350     | 6        | 6.19%   |
| 701-800     | 3        | 3.09%   |
| 801-900     | 2        | 2.06%   |
| 601-700     | 2        | 2.06%   |
| 1001-1500   | 2        | 2.06%   |
| 201-300     | 1        | 1.03%   |
| 1501-2000   | 1        | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 62       | 65.26%  |
| 5/4     | 13       | 13.68%  |
| Unknown | 9        | 9.47%   |
| 16/10   | 6        | 6.32%   |
| 21/9    | 3        | 3.16%   |
| 4/3     | 1        | 1.05%   |
| 3/2     | 1        | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 31.07%  |
| 301-350        | 17       | 16.5%   |
| 151-200        | 17       | 16.5%   |
| 141-150        | 12       | 11.65%  |
| Unknown        | 10       | 9.71%   |
| 251-300        | 6        | 5.83%   |
| More than 1000 | 3        | 2.91%   |
| 351-500        | 3        | 2.91%   |
| 501-1000       | 2        | 1.94%   |
| 71-80          | 1        | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 60       | 62.5%   |
| 101-120 | 20       | 20.83%  |
| Unknown | 10       | 10.42%  |
| 1-50    | 2        | 2.08%   |
| 161-240 | 2        | 2.08%   |
| 121-160 | 2        | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 73.12%  |
| 2     | 20       | 21.51%  |
| 0     | 4        | 4.3%    |
| 3     | 1        | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 60       | 52.17%  |
| Intel                    | 25       | 21.74%  |
| Qualcomm Atheros         | 10       | 8.7%    |
| Broadcom Limited         | 3        | 2.61%   |
| TP-Link                  | 2        | 1.74%   |
| Nvidia                   | 2        | 1.74%   |
| Microsoft                | 2        | 1.74%   |
| D-Link                   | 2        | 1.74%   |
| Broadcom                 | 2        | 1.74%   |
| Samsung Electronics      | 1        | 0.87%   |
| Ralink Technology        | 1        | 0.87%   |
| Ralink                   | 1        | 0.87%   |
| Marvell Technology Group | 1        | 0.87%   |
| Edimax Technology        | 1        | 0.87%   |
| D-Link System            | 1        | 0.87%   |
| 3Com                     | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 49       | 38.58%  |
| Intel I211 Gigabit Network Connection                                | 5        | 3.94%   |
| Realtek RTL8125 2.5GbE Controller                                    | 4        | 3.15%   |
| Intel 82579V Gigabit Network Connection                              | 4        | 3.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 3        | 2.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 3        | 2.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 1.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 2        | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 2        | 1.57%   |
| Microsoft XBOX ACC                                                   | 2        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 1.57%   |
| Intel Ethernet Controller I225-V                                     | 2        | 1.57%   |
| Intel Ethernet Connection (7) I219-V                                 | 2        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 1.57%   |
| Intel 82578DC Gigabit Network Connection                             | 2        | 1.57%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 2        | 1.57%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express      | 2        | 1.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1        | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 0.79%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 1        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 0.79%   |
| Nvidia MCP61 Ethernet                                                | 1        | 0.79%   |
| Nvidia MCP55 Ethernet                                                | 1        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 1        | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 0.79%   |
| Intel NM10/ICH7 Family LAN Controller                                | 1        | 0.79%   |
| Intel I210 Gigabit Network Connection                                | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                     | 1        | 0.79%   |
| Intel Ethernet Connection I217-LM                                    | 1        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                 | 1        | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1        | 0.79%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                   | 1        | 0.79%   |
| Intel 82567LF-3 Gigabit Network Connection                           | 1        | 0.79%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]    | 1        | 0.79%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1        | 0.79%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]        | 1        | 0.79%   |
| D-Link 802.11 n WLAN                                                 | 1        | 0.79%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                     | 1        | 0.79%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express      | 1        | 0.79%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1        | 0.79%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                      | 1        | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 26.92%  |
| Intel                 | 6        | 23.08%  |
| TP-Link               | 2        | 7.69%   |
| Qualcomm Atheros      | 2        | 7.69%   |
| Microsoft             | 2        | 7.69%   |
| D-Link                | 2        | 7.69%   |
| Ralink Technology     | 1        | 3.85%   |
| Ralink                | 1        | 3.85%   |
| Edimax Technology     | 1        | 3.85%   |
| D-Link System         | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 3        | 11.54%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 7.69%   |
| Microsoft XBOX ACC                                                   | 2        | 7.69%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 7.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 3.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 3.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 3.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 3.85%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 3.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 3.85%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]    | 1        | 3.85%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1        | 3.85%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]        | 1        | 3.85%   |
| D-Link 802.11 n WLAN                                                 | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 58       | 58.59%  |
| Intel                    | 24       | 24.24%  |
| Qualcomm Atheros         | 8        | 8.08%   |
| Broadcom Limited         | 3        | 3.03%   |
| Nvidia                   | 2        | 2.02%   |
| Samsung Electronics      | 1        | 1.01%   |
| Marvell Technology Group | 1        | 1.01%   |
| Broadcom                 | 1        | 1.01%   |
| 3Com                     | 1        | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 48.51%  |
| Intel I211 Gigabit Network Connection                             | 5        | 4.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.96%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 3.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.98%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.98%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.98%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 1.98%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.98%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2        | 1.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.99%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.99%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.99%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.99%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.99%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.99%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1        | 0.99%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.99%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.99%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 1        | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 78.81%  |
| WiFi     | 25       | 21.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 83.16%  |
| WiFi     | 16       | 16.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 78       | 81.25%  |
| 2     | 14       | 14.58%  |
| 3     | 4        | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 8        | 53.33%  |
| Intel                   | 6        | 40%     |
| Broadcom                | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 53.33%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 13.33%  |
| Intel AX200 Bluetooth                               | 2        | 13.33%  |
| Intel Bluetooth Device                              | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| Broadcom Bluetooth Device                           | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 56       | 33.33%  |
| Nvidia                                          | 42       | 25%     |
| AMD                                             | 41       | 24.4%   |
| JMTek                                           | 6        | 3.57%   |
| C-Media Electronics                             | 6        | 3.57%   |
| Yamaha                                          | 2        | 1.19%   |
| Logitech                                        | 2        | 1.19%   |
| SteelSeries ApS                                 | 1        | 0.6%    |
| Sony                                            | 1        | 0.6%    |
| Realtek Semiconductor                           | 1        | 0.6%    |
| Razer USA                                       | 1        | 0.6%    |
| PreSonus Audio Electronics                      | 1        | 0.6%    |
| Panasonic (Matsushita)                          | 1        | 0.6%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.6%    |
| Generalplus Technology                          | 1        | 0.6%    |
| Focusrite-Novation                              | 1        | 0.6%    |
| Creative Technology                             | 1        | 0.6%    |
| Creative Labs                                   | 1        | 0.6%    |
| ASUSTek Computer                                | 1        | 0.6%    |
| Allen&Heath                                     | 1        | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 5.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 5.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 4.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 3.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 2.58%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 2.58%   |
| JMTek USB PnP Audio Device                                                 | 5        | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.06%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.55%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.55%   |
| Yamaha AG06/AG03                                                           | 2        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.03%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.03%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 1.03%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.03%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.03%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1        | 0.52%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.52%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.52%   |
| Razer USA Razer USB Sound Card                                             | 1        | 0.52%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1        | 0.52%   |
| Panasonic (Matsushita) USB Audio 2                                         | 1        | 0.52%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.52%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.52%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.52%   |
| Nvidia MCP55 High Definition Audio                                         | 1        | 0.52%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.52%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.52%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.52%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.52%   |
| Logitech G733 Gaming Headset                                               | 1        | 0.52%   |
| Logitech G560 Gaming Speaker                                               | 1        | 0.52%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1        | 0.52%   |
| JMTek Hex                                                                  | 1        | 0.52%   |
| Intel Audio device                                                         | 1        | 0.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.52%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 24.64%  |
| Unknown             | 11       | 15.94%  |
| G.Skill             | 9        | 13.04%  |
| Crucial             | 9        | 13.04%  |
| Patriot             | 4        | 5.8%    |
| Ramaxel Technology  | 3        | 4.35%   |
| A-DATA Technology   | 3        | 4.35%   |
| Transcend           | 2        | 2.9%    |
| Team                | 2        | 2.9%    |
| Samsung Electronics | 2        | 2.9%    |
| Nanya Technology    | 2        | 2.9%    |
| Corsair             | 2        | 2.9%    |
| SK hynix            | 1        | 1.45%   |
| Elpida              | 1        | 1.45%   |
| Atermiter           | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2        | 2.53%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s      | 2        | 2.53%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s           | 2        | 2.53%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s   | 2        | 2.53%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 2.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 1.27%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 1.27%   |
| Unknown RAM Module 512MB DIMM 800MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s               | 1        | 1.27%   |
| Transcend RAM JM2400HLB-8G 8192MB DIMM DDR4 2133MT/s      | 1        | 1.27%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s       | 1        | 1.27%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.27%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s       | 1        | 1.27%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s       | 1        | 1.27%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 1.27%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Ramaxel RAM RML1520AG38D6F-667 512MB DIMM DDR2 667MT/s    | 1        | 1.27%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| Patriot RAM PSD34G13332 ...... 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| Nanya RAM M2Y51264TU88A4B-3C 512MB DIMM DDR2 667MT/s      | 1        | 1.27%   |
| Kingston RAM termiter 9.A01LF 8192MB DIMM DDR3 1067MT/s   | 1        | 1.27%   |
| Kingston RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.27%   |
| Kingston RAM Module 1024MB DIMM DDR 667MT/s               | 1        | 1.27%   |
| Kingston RAM M471B5273DH0-CK0 4096MB DIMM DDR3 1600MT/s   | 1        | 1.27%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 1.27%   |
| Kingston RAM ACR512X64D3U16C11G 4096MB DIMM DDR3 1600MT/s | 1        | 1.27%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Kingston RAM 99U5471-057.A00LF 8192MB DIMM DDR3 1333MT/s  | 1        | 1.27%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Kingston RAM 9905702-027.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 1.27%   |
| Kingston RAM 9905701-143.A00G 16384MB DIMM DDR4 2666MT/s  | 1        | 1.27%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM 2133MT/s           | 1        | 1.27%   |
| Kingston RAM 9905595-010.A00LF 2048MB DIMM DDR3 1600MT/s  | 1        | 1.27%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Kingston RAM 9905471-017.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 1.27%   |
| Kingston RAM 9905471-001.A01LF 2GB DIMM 1600MT/s          | 1        | 1.27%   |
| Kingston RAM 9905428-095.D00LF 4096MB DIMM DDR3 1600MT/s  | 1        | 1.27%   |
| Kingston RAM 9905403-156.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| G.Skill RAM F4-5333C22-8GTRS 8GB DIMM DDR4 2133MT/s       | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s     | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-8GFX 8GB DIMM DDR4 3200MT/s        | 1        | 1.27%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s        | 1        | 1.27%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 1        | 1.27%   |
| G.Skill RAM F4-2400C17-4GNT 4096MB DIMM DDR4 2400MT/s     | 1        | 1.27%   |
| G.Skill RAM F4-2400C15-8GNT 8192MB DIMM DDR4 2666MT/s     | 1        | 1.27%   |
| Elpida RAM EBJ21UE8BDF0-DJ-F 2048MB DIMM DDR3 1333MT/s    | 1        | 1.27%   |
| Crucial RAM CT8G4DFS824A.C8FHD1 8GB DIMM DDR4 2667MT/s    | 1        | 1.27%   |
| Crucial RAM CT8G4DFS824A.C8FAD1 8GB DIMM DDR4 2667MT/s    | 1        | 1.27%   |
| Crucial RAM CT8G4DFS8213.C8FBR1 8GB DIMM DDR4 2133MT/s    | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 47.54%  |
| DDR3    | 20       | 32.79%  |
| Unknown | 5        | 8.2%    |
| SDRAM   | 4        | 6.56%   |
| DDR2    | 2        | 3.28%   |
| DDR     | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 60       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 41.54%  |
| 4096  | 18       | 27.69%  |
| 2048  | 8        | 12.31%  |
| 16384 | 7        | 10.77%  |
| 1024  | 2        | 3.08%   |
| 512   | 2        | 3.08%   |
| 32768 | 1        | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 21.43%  |
| 1333    | 9        | 12.86%  |
| 3200    | 7        | 10%     |
| 2667    | 6        | 8.57%   |
| 2666    | 4        | 5.71%   |
| 2133    | 4        | 5.71%   |
| 800     | 3        | 4.29%   |
| Unknown | 3        | 4.29%   |
| 3866    | 2        | 2.86%   |
| 3533    | 2        | 2.86%   |
| 2934    | 2        | 2.86%   |
| 2400    | 2        | 2.86%   |
| 667     | 2        | 2.86%   |
| 3733    | 1        | 1.43%   |
| 3600    | 1        | 1.43%   |
| 3466    | 1        | 1.43%   |
| 3400    | 1        | 1.43%   |
| 3067    | 1        | 1.43%   |
| 2800    | 1        | 1.43%   |
| 1067    | 1        | 1.43%   |
| 1066    | 1        | 1.43%   |
| 400     | 1        | 1.43%   |

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
| Logitech                      | 6        | 33.33%  |
| Samsung Electronics           | 2        | 11.11%  |
| Microdia                      | 2        | 11.11%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Sonix Technology              | 1        | 5.56%   |
| Razer USA                     | 1        | 5.56%   |
| Pixart Imaging                | 1        | 5.56%   |
| Panasonic (Matsushita)        | 1        | 5.56%   |
| Cubeternet                    | 1        | 5.56%   |
| Arkmicro Technologies         | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)                             | 2        | 11.11%  |
| Logitech HD Webcam C615                                             | 2        | 11.11%  |
| Z-Star Venus USB2.0 Camera                                          | 1        | 5.56%   |
| Sunplus FHD Camera                                                  | 1        | 5.56%   |
| Sonix USB Camera                                                    | 1        | 5.56%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 5.56%   |
| Pixart Imaging Webcam Genius iLook 300                              | 1        | 5.56%   |
| Panasonic (Matsushita) TY-CC20W                                     | 1        | 5.56%   |
| Microdia Webcam Vitade AF                                           | 1        | 5.56%   |
| Microdia Camera                                                     | 1        | 5.56%   |
| Logitech Webcam C925e                                               | 1        | 5.56%   |
| Logitech Webcam C270                                                | 1        | 5.56%   |
| Logitech Webcam C170                                                | 1        | 5.56%   |
| Logitech HD Pro Webcam C920                                         | 1        | 5.56%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 5.56%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 5.56%   |

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
| 0     | 87       | 92.55%  |
| 1     | 6        | 6.38%   |
| 2     | 1        | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Network       | 1        | 12.5%   |
| Camera        | 1        | 12.5%   |
| Bluetooth     | 1        | 12.5%   |

