Fedora 39 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 39.

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

Total: 1422

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P6T6 WS REVOLUTION          | [fcd38b29d8](https://linux-hardware.org/?probe=fcd38b29d8) | Aug 27, 2025 |
| AFOX          | IH81-MA5                    | [e4daf0dc75](https://linux-hardware.org/?probe=e4daf0dc75) | May 28, 2025 |
| MSI           | PRO B760-P DDR4 II          | [c594811a71](https://linux-hardware.org/?probe=c594811a71) | May 04, 2025 |
| Intel         | X79G-A V2.0                 | [0626c24cd5](https://linux-hardware.org/?probe=0626c24cd5) | May 02, 2025 |
| MSI           | PRO H610M-E DDR4            | [68ba6ae421](https://linux-hardware.org/?probe=68ba6ae421) | Apr 23, 2025 |
| MSI           | MS-7142                     | [67b96b40ba](https://linux-hardware.org/?probe=67b96b40ba) | Apr 18, 2025 |
| Intel         | H55                         | [7d725788f7](https://linux-hardware.org/?probe=7d725788f7) | Apr 11, 2025 |
| Intel         | X79G-A V2.0                 | [bf696cb803](https://linux-hardware.org/?probe=bf696cb803) | Apr 11, 2025 |
| Intel         | X79G-A V2.0                 | [548a0a77bd](https://linux-hardware.org/?probe=548a0a77bd) | Apr 06, 2025 |
| Intel         | X79G-A V2.0                 | [de5d11cf3a](https://linux-hardware.org/?probe=de5d11cf3a) | Mar 21, 2025 |
| Intel         | X79G-A V2.0                 | [dd1c77debf](https://linux-hardware.org/?probe=dd1c77debf) | Mar 18, 2025 |
| BESSTAR Te... | TH50                        | [fdd2e91625](https://linux-hardware.org/?probe=fdd2e91625) | Feb 26, 2025 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [88cc810a2d](https://linux-hardware.org/?probe=88cc810a2d) | Feb 10, 2025 |
| ASRock        | H81M-HDS                    | [7cfa1348bd](https://linux-hardware.org/?probe=7cfa1348bd) | Jan 28, 2025 |
| HP            | 8643 SMVB                   | [ca9f4fb194](https://linux-hardware.org/?probe=ca9f4fb194) | Jan 25, 2025 |
| ASRock        | Z77 Extreme4                | [797fa65c73](https://linux-hardware.org/?probe=797fa65c73) | Jan 23, 2025 |
| ASUSTek       | CG8480                      | [7b1431a800](https://linux-hardware.org/?probe=7b1431a800) | Jan 22, 2025 |
| Dell          | 0KWVT8 A00                  | [e160f659f6](https://linux-hardware.org/?probe=e160f659f6) | Jan 19, 2025 |
| Gigabyte      | Z97N-WIFI                   | [2b49fe98b3](https://linux-hardware.org/?probe=2b49fe98b3) | Jan 12, 2025 |
| ASUSTek       | P5Q SE/R                    | [a2d7cfe0a0](https://linux-hardware.org/?probe=a2d7cfe0a0) | Jan 09, 2025 |
| Gigabyte      | Z97N-WIFI                   | [94525b433d](https://linux-hardware.org/?probe=94525b433d) | Jan 04, 2025 |
| Pegatron      | Benicia                     | [e061c1cadc](https://linux-hardware.org/?probe=e061c1cadc) | Dec 28, 2024 |
| Dell          | 0Y9655                      | [02dddf8f3b](https://linux-hardware.org/?probe=02dddf8f3b) | Dec 10, 2024 |
| ASRock        | B360M Pro4                  | [110b5c92b3](https://linux-hardware.org/?probe=110b5c92b3) | Dec 05, 2024 |
| ASRock        | B360M Pro4                  | [51ed30ad3f](https://linux-hardware.org/?probe=51ed30ad3f) | Dec 05, 2024 |
| Dell          | 09KPNV A00                  | [3071efb367](https://linux-hardware.org/?probe=3071efb367) | Nov 23, 2024 |
| MSI           | X99A RAIDER                 | [e18f89ceee](https://linux-hardware.org/?probe=e18f89ceee) | Nov 14, 2024 |
| ASUSTek       | Leonite2                    | [0811b000fc](https://linux-hardware.org/?probe=0811b000fc) | Nov 12, 2024 |
| Dell          | 08NPPY A00                  | [55c68fb44b](https://linux-hardware.org/?probe=55c68fb44b) | Nov 11, 2024 |
| ASUSTek       | Leonite2                    | [1eccc2d680](https://linux-hardware.org/?probe=1eccc2d680) | Nov 10, 2024 |
| ASUSTek       | PRIME A520M-K               | [0ee75416e7](https://linux-hardware.org/?probe=0ee75416e7) | Nov 08, 2024 |
| Dell          | 09KPNV A00                  | [c93191fdb6](https://linux-hardware.org/?probe=c93191fdb6) | Nov 08, 2024 |
| ASRock        | B650 LiveMixer              | [644424949e](https://linux-hardware.org/?probe=644424949e) | Nov 05, 2024 |
| ASUSTek       | P5Q SE/R                    | [e2902f3cdb](https://linux-hardware.org/?probe=e2902f3cdb) | Nov 04, 2024 |
| ASRock        | 990FX Killer                | [f8fbe6083a](https://linux-hardware.org/?probe=f8fbe6083a) | Oct 25, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [a2e03265d9](https://linux-hardware.org/?probe=a2e03265d9) | Oct 19, 2024 |
| MSI           | B550 GAMING GEN3            | [6862f6eee9](https://linux-hardware.org/?probe=6862f6eee9) | Oct 18, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5372e4c323](https://linux-hardware.org/?probe=5372e4c323) | Oct 13, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [7e908345aa](https://linux-hardware.org/?probe=7e908345aa) | Oct 07, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [55d1e16a84](https://linux-hardware.org/?probe=55d1e16a84) | Sep 28, 2024 |
| MSI           | 880GM-E41                   | [337e4c377f](https://linux-hardware.org/?probe=337e4c377f) | Sep 27, 2024 |
| BESSTAR Te... | UM350                       | [57738b8c5e](https://linux-hardware.org/?probe=57738b8c5e) | Sep 25, 2024 |
| ASUSTek       | PRIME X470-PRO              | [ede9d3b2eb](https://linux-hardware.org/?probe=ede9d3b2eb) | Sep 13, 2024 |
| BESSTAR Te... | UM250 V1.0                  | [e53f27a41d](https://linux-hardware.org/?probe=e53f27a41d) | Sep 10, 2024 |
| ASRock        | B550M-ITX/ac                | [569f106b52](https://linux-hardware.org/?probe=569f106b52) | Sep 04, 2024 |
| MSI           | 880GM-E41                   | [6644af397b](https://linux-hardware.org/?probe=6644af397b) | Sep 01, 2024 |
| ASRock        | 760GM-HDV                   | [5f7ac7c626](https://linux-hardware.org/?probe=5f7ac7c626) | Aug 31, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [c88853eed3](https://linux-hardware.org/?probe=c88853eed3) | Aug 21, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [0b9a036c20](https://linux-hardware.org/?probe=0b9a036c20) | Aug 17, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [f8e212a6a6](https://linux-hardware.org/?probe=f8e212a6a6) | Aug 17, 2024 |
| Dell          | 0215PR A03                  | [4709910f60](https://linux-hardware.org/?probe=4709910f60) | Aug 12, 2024 |
| Dell          | 0215PR A03                  | [ba8b885367](https://linux-hardware.org/?probe=ba8b885367) | Aug 12, 2024 |
| ASRock        | Z170 Extreme7+              | [64c270cc1d](https://linux-hardware.org/?probe=64c270cc1d) | Aug 12, 2024 |
| HP            | 2129                        | [d2ae5dc64d](https://linux-hardware.org/?probe=d2ae5dc64d) | Aug 11, 2024 |
| ASRock        | B560M-ITX/ac                | [a6f4b3ba0b](https://linux-hardware.org/?probe=a6f4b3ba0b) | Aug 10, 2024 |
| ASRock        | B560M-ITX/ac                | [52ca97fd84](https://linux-hardware.org/?probe=52ca97fd84) | Aug 10, 2024 |
| ASRock        | X300M-STX                   | [4468e82d99](https://linux-hardware.org/?probe=4468e82d99) | Aug 05, 2024 |
| ASUSTek       | P5Q SE2                     | [8805319545](https://linux-hardware.org/?probe=8805319545) | Aug 04, 2024 |
| HP            | 8056                        | [2e64830df3](https://linux-hardware.org/?probe=2e64830df3) | Aug 01, 2024 |
| HP            | 8056                        | [d38465aac1](https://linux-hardware.org/?probe=d38465aac1) | Aug 01, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [c59904f021](https://linux-hardware.org/?probe=c59904f021) | Aug 01, 2024 |
| ASUSTek       | P8H61-MX USB3               | [bb161d55df](https://linux-hardware.org/?probe=bb161d55df) | Jul 29, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [7858b227f7](https://linux-hardware.org/?probe=7858b227f7) | Jul 23, 2024 |
| ASRock        | Z170 Extreme7+              | [09c4b3a35e](https://linux-hardware.org/?probe=09c4b3a35e) | Jul 17, 2024 |
| HP            | 2ADC                        | [bbb526fb8b](https://linux-hardware.org/?probe=bbb526fb8b) | Jul 17, 2024 |
| ASRock        | N100DC-ITX                  | [c94f86230a](https://linux-hardware.org/?probe=c94f86230a) | Jul 16, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [e6b145c630](https://linux-hardware.org/?probe=e6b145c630) | Jul 16, 2024 |
| HP            | 3048h                       | [4e0b68d2c5](https://linux-hardware.org/?probe=4e0b68d2c5) | Jul 15, 2024 |
| ASUSTek       | Z170-A                      | [448a362678](https://linux-hardware.org/?probe=448a362678) | Jul 05, 2024 |
| Dell          | 00V62H A01                  | [b2a92269b5](https://linux-hardware.org/?probe=b2a92269b5) | Jul 05, 2024 |
| ASRock        | B650 PG Lightning           | [69f46fe2a1](https://linux-hardware.org/?probe=69f46fe2a1) | Jul 04, 2024 |
| ASUSTek       | Z97-DELUXE/USB              | [493d6359d2](https://linux-hardware.org/?probe=493d6359d2) | Jul 03, 2024 |
| Dell          | 0KYJ8C A00                  | [05a3087fd1](https://linux-hardware.org/?probe=05a3087fd1) | Jul 02, 2024 |
| ASUSTek       | G20AJ                       | [9b564a9f2f](https://linux-hardware.org/?probe=9b564a9f2f) | Jun 29, 2024 |
| ASUSTek       | P8Z68-V LX                  | [6aaf1f5ee3](https://linux-hardware.org/?probe=6aaf1f5ee3) | Jun 26, 2024 |
| ASUSTek       | PRIME Z390-P                | [1b0549fd0b](https://linux-hardware.org/?probe=1b0549fd0b) | Jun 26, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [b37aa6322d](https://linux-hardware.org/?probe=b37aa6322d) | Jun 24, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [43bdcb8bff](https://linux-hardware.org/?probe=43bdcb8bff) | Jun 23, 2024 |
| AMD           | A520                        | [4cf100d9b8](https://linux-hardware.org/?probe=4cf100d9b8) | Jun 23, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [a20ee9e228](https://linux-hardware.org/?probe=a20ee9e228) | Jun 22, 2024 |
| Apple         | Mac-F221BEC8                | [6e268a171b](https://linux-hardware.org/?probe=6e268a171b) | Jun 19, 2024 |
| MSI           | X370 GAMING PRO CARBON      | [c6a3ecc9f1](https://linux-hardware.org/?probe=c6a3ecc9f1) | Jun 18, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [61aa75d0c5](https://linux-hardware.org/?probe=61aa75d0c5) | Jun 15, 2024 |
| Gigabyte      | F2A88XM-D3H                 | [6f371f483d](https://linux-hardware.org/?probe=6f371f483d) | Jun 11, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [c0e41508e0](https://linux-hardware.org/?probe=c0e41508e0) | Jun 11, 2024 |
| System76      | Thelio Major thelio-majo... | [4e35bc3849](https://linux-hardware.org/?probe=4e35bc3849) | Jun 10, 2024 |
| System76      | Thelio Major thelio-majo... | [f8c8acc689](https://linux-hardware.org/?probe=f8c8acc689) | Jun 10, 2024 |
| Gigabyte      | Z77N-WIFI                   | [482f64e89f](https://linux-hardware.org/?probe=482f64e89f) | Jun 10, 2024 |
| HP            | 8917                        | [051b3cf905](https://linux-hardware.org/?probe=051b3cf905) | Jun 08, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [7b4a89be4f](https://linux-hardware.org/?probe=7b4a89be4f) | Jun 05, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [58135f78e5](https://linux-hardware.org/?probe=58135f78e5) | Jun 05, 2024 |
| ASUSTek       | PRIME B350M-A               | [31b9558caf](https://linux-hardware.org/?probe=31b9558caf) | Jun 05, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [d7ef7b9c36](https://linux-hardware.org/?probe=d7ef7b9c36) | Jun 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [208fd714ad](https://linux-hardware.org/?probe=208fd714ad) | Jun 04, 2024 |
| HP            | 1495                        | [c7979accd3](https://linux-hardware.org/?probe=c7979accd3) | May 31, 2024 |
| HP            | 1495                        | [088f6c2bc6](https://linux-hardware.org/?probe=088f6c2bc6) | May 31, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | [e696e99eeb](https://linux-hardware.org/?probe=e696e99eeb) | May 28, 2024 |
| ASUSTek       | Maximus IX EXTREME          | [1bb674726e](https://linux-hardware.org/?probe=1bb674726e) | May 28, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [8144ad4580](https://linux-hardware.org/?probe=8144ad4580) | May 27, 2024 |
| ASRock        | B650 LiveMixer              | [e80e27799c](https://linux-hardware.org/?probe=e80e27799c) | May 25, 2024 |
| ASUSTek       | PRIME H370M-PLUS            | [5676eb00c8](https://linux-hardware.org/?probe=5676eb00c8) | May 25, 2024 |
| Gigabyte      | 970A-DS3P                   | [0d3b74e4c6](https://linux-hardware.org/?probe=0d3b74e4c6) | May 21, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | [71a450cd04](https://linux-hardware.org/?probe=71a450cd04) | May 20, 2024 |
| Dell          | 02YYK5 A01                  | [414b05c91f](https://linux-hardware.org/?probe=414b05c91f) | May 19, 2024 |
| ASRock        | B560M-ITX/ac                | [b68d9ac21d](https://linux-hardware.org/?probe=b68d9ac21d) | May 18, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [d949bd1fbc](https://linux-hardware.org/?probe=d949bd1fbc) | May 18, 2024 |
| Lenovo        | ThinkStation D20 4155CTO    | [c9d30be181](https://linux-hardware.org/?probe=c9d30be181) | May 18, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [472ce85160](https://linux-hardware.org/?probe=472ce85160) | May 16, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [ae8bcfd05d](https://linux-hardware.org/?probe=ae8bcfd05d) | May 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ab6a57393a](https://linux-hardware.org/?probe=ab6a57393a) | May 13, 2024 |
| Gigabyte      | B660M GAMING X AX DDR4      | [76e26350ae](https://linux-hardware.org/?probe=76e26350ae) | May 13, 2024 |
| ASRock        | B560M-ITX/ac                | [aa1981e8c1](https://linux-hardware.org/?probe=aa1981e8c1) | May 12, 2024 |
| Erying        | tgl                         | [f16c3082ce](https://linux-hardware.org/?probe=f16c3082ce) | May 11, 2024 |
| ASUSTek       | PRIME Z690-P D4             | [8b42c49814](https://linux-hardware.org/?probe=8b42c49814) | May 10, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [48be6a2dbb](https://linux-hardware.org/?probe=48be6a2dbb) | May 07, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [b7c53048d5](https://linux-hardware.org/?probe=b7c53048d5) | May 04, 2024 |
| Gigabyte      | Z77MX-D3H                   | [7faebd43a1](https://linux-hardware.org/?probe=7faebd43a1) | May 01, 2024 |
| ASUSTek       | PRIME H610I-PLUS D4         | [1c4e390f2d](https://linux-hardware.org/?probe=1c4e390f2d) | Apr 30, 2024 |
| ASUSTek       | CG8480                      | [7567b12c01](https://linux-hardware.org/?probe=7567b12c01) | Apr 30, 2024 |
| ASUSTek       | G20AJ                       | [d314388bb1](https://linux-hardware.org/?probe=d314388bb1) | Apr 28, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [1af94235a9](https://linux-hardware.org/?probe=1af94235a9) | Apr 28, 2024 |
| Biostar       | Hi-Fi Z87X 3D               | [09d7331f2b](https://linux-hardware.org/?probe=09d7331f2b) | Apr 27, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | [29c763baa8](https://linux-hardware.org/?probe=29c763baa8) | Apr 27, 2024 |
| Lenovo        | ThinkStation D20 4155CTO    | [54cae1f375](https://linux-hardware.org/?probe=54cae1f375) | Apr 27, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [14dee832b2](https://linux-hardware.org/?probe=14dee832b2) | Apr 26, 2024 |
| Gigabyte      | X399 AORUS PRO-CF           | [ae667fce92](https://linux-hardware.org/?probe=ae667fce92) | Apr 25, 2024 |
| Gigabyte      | 970A-UD3P                   | [e4237a07f0](https://linux-hardware.org/?probe=e4237a07f0) | Apr 24, 2024 |
| ASUSTek       | M2N-SLI DELUXE              | [e74da3b338](https://linux-hardware.org/?probe=e74da3b338) | Apr 24, 2024 |
| ASRock        | B450 Pro4                   | [a43f744651](https://linux-hardware.org/?probe=a43f744651) | Apr 24, 2024 |
| ASUSTek       | A88X-PLUS                   | [758736ef94](https://linux-hardware.org/?probe=758736ef94) | Apr 24, 2024 |
| Gigabyte      | GA-A55M-S2V                 | [cc1a7f7fef](https://linux-hardware.org/?probe=cc1a7f7fef) | Apr 24, 2024 |
| Gigabyte      | B75M-D3V                    | [719891e7c2](https://linux-hardware.org/?probe=719891e7c2) | Apr 24, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [7e76ea0f76](https://linux-hardware.org/?probe=7e76ea0f76) | Apr 24, 2024 |
| Digiboard     | MPxx                        | [e277b1a1d5](https://linux-hardware.org/?probe=e277b1a1d5) | Apr 24, 2024 |
| HP            | 21D0                        | [fe5b1a679c](https://linux-hardware.org/?probe=fe5b1a679c) | Apr 24, 2024 |
| Dell          | 0YGYJY A01                  | [c922a511fd](https://linux-hardware.org/?probe=c922a511fd) | Apr 23, 2024 |
| Dell          | 0HHV7N A00                  | [328456d99c](https://linux-hardware.org/?probe=328456d99c) | Apr 23, 2024 |
| Dell          | 0HHV7N A00                  | [dbe31bb448](https://linux-hardware.org/?probe=dbe31bb448) | Apr 23, 2024 |
| HP            | 8299                        | [e2ee3223fd](https://linux-hardware.org/?probe=e2ee3223fd) | Apr 23, 2024 |
| Gigabyte      | X570S AORUS MASTER          | [864cdaee54](https://linux-hardware.org/?probe=864cdaee54) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [a06e5411c0](https://linux-hardware.org/?probe=a06e5411c0) | Apr 23, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [4626c1b15a](https://linux-hardware.org/?probe=4626c1b15a) | Apr 23, 2024 |
| ASUSTek       | PRIME Z590-A                | [ab2310f0d6](https://linux-hardware.org/?probe=ab2310f0d6) | Apr 22, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [90e696166f](https://linux-hardware.org/?probe=90e696166f) | Apr 22, 2024 |
| MSI           | CSM-H81M-P32                | [056face9de](https://linux-hardware.org/?probe=056face9de) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a671f5391b](https://linux-hardware.org/?probe=a671f5391b) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | [f1d18ed809](https://linux-hardware.org/?probe=f1d18ed809) | Apr 22, 2024 |
| Intel         | X99H                        | [cca155cf13](https://linux-hardware.org/?probe=cca155cf13) | Apr 22, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [68d6575b15](https://linux-hardware.org/?probe=68d6575b15) | Apr 22, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [0cac32bd87](https://linux-hardware.org/?probe=0cac32bd87) | Apr 22, 2024 |
| Biostar       | Hi-Fi Z87X 3D               | [8c77d98a43](https://linux-hardware.org/?probe=8c77d98a43) | Apr 21, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | [6c6b1a2edd](https://linux-hardware.org/?probe=6c6b1a2edd) | Apr 21, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | [7f5ce15d32](https://linux-hardware.org/?probe=7f5ce15d32) | Apr 21, 2024 |
| ASRock        | B450M-HDV R4.0              | [c5eedce567](https://linux-hardware.org/?probe=c5eedce567) | Apr 21, 2024 |
| Acer          | RS780DV                     | [2fd4cf8e84](https://linux-hardware.org/?probe=2fd4cf8e84) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2c617e212d](https://linux-hardware.org/?probe=2c617e212d) | Apr 21, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [9287fd48fd](https://linux-hardware.org/?probe=9287fd48fd) | Apr 21, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [40c04cd535](https://linux-hardware.org/?probe=40c04cd535) | Apr 21, 2024 |
| ASUSTek       | PRIME A520M-E               | [fa784dad84](https://linux-hardware.org/?probe=fa784dad84) | Apr 21, 2024 |
| ASUSTek       | PRIME X370-PRO              | [a4e68832be](https://linux-hardware.org/?probe=a4e68832be) | Apr 21, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [dc0120c1ae](https://linux-hardware.org/?probe=dc0120c1ae) | Apr 21, 2024 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [34da91dacf](https://linux-hardware.org/?probe=34da91dacf) | Apr 21, 2024 |
| HP            | 805B                        | [06e17f3461](https://linux-hardware.org/?probe=06e17f3461) | Apr 21, 2024 |
| HP            | 87D6 SMVB                   | [b3862648a1](https://linux-hardware.org/?probe=b3862648a1) | Apr 21, 2024 |
| ASUSTek       | P6T                         | [d2206947bb](https://linux-hardware.org/?probe=d2206947bb) | Apr 21, 2024 |
| ASUSTek       | G20AJ                       | [0b3321dc98](https://linux-hardware.org/?probe=0b3321dc98) | Apr 21, 2024 |
| Colorful T... | CVN Z690 GAMING FROZEN V... | [09cbde09ca](https://linux-hardware.org/?probe=09cbde09ca) | Apr 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a343ca7f17](https://linux-hardware.org/?probe=a343ca7f17) | Apr 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [9836019d80](https://linux-hardware.org/?probe=9836019d80) | Apr 20, 2024 |
| ASUSTek       | H110M-PLUS                  | [98eba50e5b](https://linux-hardware.org/?probe=98eba50e5b) | Apr 20, 2024 |
| Lenovo        | SDK0E50510 WIN              | [bc958fb0e5](https://linux-hardware.org/?probe=bc958fb0e5) | Apr 19, 2024 |
| Dell          | 08NPPY A00                  | [dad92afe76](https://linux-hardware.org/?probe=dad92afe76) | Apr 19, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | [6b0dd29862](https://linux-hardware.org/?probe=6b0dd29862) | Apr 19, 2024 |
| Dell          | 0Y2MRG A00                  | [6abe6d21fc](https://linux-hardware.org/?probe=6abe6d21fc) | Apr 19, 2024 |
| Pegatron      | 2AB5                        | [36f9f1b443](https://linux-hardware.org/?probe=36f9f1b443) | Apr 18, 2024 |
| Unknown       | T100                        | [cbe8f3e9af](https://linux-hardware.org/?probe=cbe8f3e9af) | Apr 18, 2024 |
| Unknown       | T100                        | [03f07534d1](https://linux-hardware.org/?probe=03f07534d1) | Apr 18, 2024 |
| MSI           | B450 GAMING PLUS            | [7f84bae081](https://linux-hardware.org/?probe=7f84bae081) | Apr 18, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [a344875df9](https://linux-hardware.org/?probe=a344875df9) | Apr 18, 2024 |
| MSI           | Z270 GAMING PLUS            | [4e997cc9d3](https://linux-hardware.org/?probe=4e997cc9d3) | Apr 18, 2024 |
| ASUSTek       | PRIME N100I-D D4            | [1b1bec34e3](https://linux-hardware.org/?probe=1b1bec34e3) | Apr 17, 2024 |
| ASRock        | B550 Extreme4               | [6ee8d62842](https://linux-hardware.org/?probe=6ee8d62842) | Apr 17, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | [344e87c2a8](https://linux-hardware.org/?probe=344e87c2a8) | Apr 17, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [eb6c0896d5](https://linux-hardware.org/?probe=eb6c0896d5) | Apr 17, 2024 |
| MSI           | MPG B550I GAMING EDGE WI... | [ddf96b058d](https://linux-hardware.org/?probe=ddf96b058d) | Apr 17, 2024 |
| ASRock        | B550M Pro4                  | [2a69ec7381](https://linux-hardware.org/?probe=2a69ec7381) | Apr 17, 2024 |
| Dell          | 0P99M4 A01                  | [77e4450298](https://linux-hardware.org/?probe=77e4450298) | Apr 16, 2024 |
| ASUSTek       | P8Z68 DELUXE                | [f77a3ef205](https://linux-hardware.org/?probe=f77a3ef205) | Apr 16, 2024 |
| Dell          | 0MWYPT A01                  | [1dcea45437](https://linux-hardware.org/?probe=1dcea45437) | Apr 16, 2024 |
| Gigabyte      | Z690 GAMING X DDR4          | [4bc71ebee3](https://linux-hardware.org/?probe=4bc71ebee3) | Apr 16, 2024 |
| HP            | 8617                        | [4f55f454d0](https://linux-hardware.org/?probe=4f55f454d0) | Apr 16, 2024 |
| Dell          | 0Y2MRG A00                  | [693ad9a009](https://linux-hardware.org/?probe=693ad9a009) | Apr 16, 2024 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | [3370e4360d](https://linux-hardware.org/?probe=3370e4360d) | Apr 16, 2024 |
| Dell          | 0KV62T A00                  | [13b11b28fc](https://linux-hardware.org/?probe=13b11b28fc) | Apr 16, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | [5be1a4715b](https://linux-hardware.org/?probe=5be1a4715b) | Apr 16, 2024 |
| ASUSTek       | H87-PLUS                    | [7da05aaadf](https://linux-hardware.org/?probe=7da05aaadf) | Apr 16, 2024 |
| ASRock        | B650M Pro RS WiFi           | [eb9f0768cf](https://linux-hardware.org/?probe=eb9f0768cf) | Apr 16, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [d74cf44500](https://linux-hardware.org/?probe=d74cf44500) | Apr 16, 2024 |
| ASUSTek       | H110M-A                     | [fcc681df4b](https://linux-hardware.org/?probe=fcc681df4b) | Apr 15, 2024 |
| ASUSTek       | H110M-A                     | [d46d720322](https://linux-hardware.org/?probe=d46d720322) | Apr 15, 2024 |
| Dell          | 0KJCC5 A00                  | [688001e950](https://linux-hardware.org/?probe=688001e950) | Apr 15, 2024 |
| MSI           | Z270M MORTAR                | [2d81483fa4](https://linux-hardware.org/?probe=2d81483fa4) | Apr 15, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | [583357f85f](https://linux-hardware.org/?probe=583357f85f) | Apr 15, 2024 |
| ASUSTek       | PRIME H510M-K               | [8ae1401a90](https://linux-hardware.org/?probe=8ae1401a90) | Apr 14, 2024 |
| Gigabyte      | B450M K-CF                  | [b2bcb4464b](https://linux-hardware.org/?probe=b2bcb4464b) | Apr 14, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [c7a6c2d6ed](https://linux-hardware.org/?probe=c7a6c2d6ed) | Apr 14, 2024 |
| ASUSTek       | PRIME Z270-P                | [aaed2b7478](https://linux-hardware.org/?probe=aaed2b7478) | Apr 14, 2024 |
| ASUSTek       | P10S-I Series               | [c0afefe9bc](https://linux-hardware.org/?probe=c0afefe9bc) | Apr 14, 2024 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [5de5178742](https://linux-hardware.org/?probe=5de5178742) | Apr 14, 2024 |
| ASRock        | B650M-HDV/M.2               | [8ed3523f0a](https://linux-hardware.org/?probe=8ed3523f0a) | Apr 14, 2024 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e96012759d](https://linux-hardware.org/?probe=e96012759d) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5bb8884eee](https://linux-hardware.org/?probe=5bb8884eee) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [841b3d5f2e](https://linux-hardware.org/?probe=841b3d5f2e) | Apr 14, 2024 |
| Gigabyte      | H61M-S2-B3                  | [5e533a401e](https://linux-hardware.org/?probe=5e533a401e) | Apr 14, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [776d567b36](https://linux-hardware.org/?probe=776d567b36) | Apr 14, 2024 |
| ASUSTek       | H81M-E                      | [7af65eace4](https://linux-hardware.org/?probe=7af65eace4) | Apr 13, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [2bb2f2f042](https://linux-hardware.org/?probe=2bb2f2f042) | Apr 13, 2024 |
| ASUSTek       | PRIME B650M-K               | [702273a412](https://linux-hardware.org/?probe=702273a412) | Apr 13, 2024 |
| ASUSTek       | PRIME H610I-PLUS D4         | [cf8e423d4c](https://linux-hardware.org/?probe=cf8e423d4c) | Apr 13, 2024 |
| HP            | 1905                        | [85c5b91f0d](https://linux-hardware.org/?probe=85c5b91f0d) | Apr 13, 2024 |
| MSI           | B450 GAMING PLUS            | [fe95b1e7e7](https://linux-hardware.org/?probe=fe95b1e7e7) | Apr 13, 2024 |
| MSI           | B450M MORTAR MAX            | [bebccc0dd1](https://linux-hardware.org/?probe=bebccc0dd1) | Apr 13, 2024 |
| Shenzhen M... | F7BAA                       | [1015688c75](https://linux-hardware.org/?probe=1015688c75) | Apr 13, 2024 |
| MSI           | X99A RAIDER                 | [84a01ab668](https://linux-hardware.org/?probe=84a01ab668) | Apr 13, 2024 |
| Gigabyte      | H81M-DS2                    | [b8407eb44d](https://linux-hardware.org/?probe=b8407eb44d) | Apr 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [aa96253b80](https://linux-hardware.org/?probe=aa96253b80) | Apr 12, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [f0de46fc9a](https://linux-hardware.org/?probe=f0de46fc9a) | Apr 12, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | [4f51073d9c](https://linux-hardware.org/?probe=4f51073d9c) | Apr 12, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [16f0af2047](https://linux-hardware.org/?probe=16f0af2047) | Apr 12, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [2ee7ec3b1f](https://linux-hardware.org/?probe=2ee7ec3b1f) | Apr 12, 2024 |
| Pegatron      | H81-M1                      | [ad6b67560b](https://linux-hardware.org/?probe=ad6b67560b) | Apr 12, 2024 |
| MSI           | B350M GAMING PRO            | [448a1d81fb](https://linux-hardware.org/?probe=448a1d81fb) | Apr 12, 2024 |
| ASUSTek       | PRIME Z270-A                | [6a4269d6d1](https://linux-hardware.org/?probe=6a4269d6d1) | Apr 12, 2024 |
| MSI           | B350M GAMING PRO            | [25ed2372d0](https://linux-hardware.org/?probe=25ed2372d0) | Apr 12, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | [d81a8d46ed](https://linux-hardware.org/?probe=d81a8d46ed) | Apr 12, 2024 |
| ASUSTek       | Z170-DELUXE                 | [8efe50aabf](https://linux-hardware.org/?probe=8efe50aabf) | Apr 11, 2024 |
| ASRock        | H77 Pro4-M                  | [7b10a71ade](https://linux-hardware.org/?probe=7b10a71ade) | Apr 11, 2024 |
| Gigabyte      | Z77MX-D3H                   | [1234bcb2a4](https://linux-hardware.org/?probe=1234bcb2a4) | Apr 11, 2024 |
| SZQFTX        | MI2-SC                      | [be8172007e](https://linux-hardware.org/?probe=be8172007e) | Apr 11, 2024 |
| Intel         | B365                        | [7abeea79f6](https://linux-hardware.org/?probe=7abeea79f6) | Apr 11, 2024 |
| Gigabyte      | GA-870A-UD3                 | [ef8d387984](https://linux-hardware.org/?probe=ef8d387984) | Apr 10, 2024 |
| Gigabyte      | G41MT-D3                    | [4ec86b2e5d](https://linux-hardware.org/?probe=4ec86b2e5d) | Apr 10, 2024 |
| Gigabyte      | B550M GAMING                | [d85fa6cbe3](https://linux-hardware.org/?probe=d85fa6cbe3) | Apr 10, 2024 |
| ASUSTek       | M5A97 R2.0                  | [eadf15884b](https://linux-hardware.org/?probe=eadf15884b) | Apr 10, 2024 |
| Gigabyte      | TRX40 DESIGNARE             | [e86ef24429](https://linux-hardware.org/?probe=e86ef24429) | Apr 10, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [be0f54854d](https://linux-hardware.org/?probe=be0f54854d) | Apr 10, 2024 |
| Dell          | 030VXY A01                  | [793be088c2](https://linux-hardware.org/?probe=793be088c2) | Apr 09, 2024 |
| Dell          | 030VXY A01                  | [64ed2bb4d3](https://linux-hardware.org/?probe=64ed2bb4d3) | Apr 09, 2024 |
| Digiboard     | MPxx                        | [fe1ed8d822](https://linux-hardware.org/?probe=fe1ed8d822) | Apr 09, 2024 |
| Gigabyte      | B450M GAMING                | [e033d32271](https://linux-hardware.org/?probe=e033d32271) | Apr 09, 2024 |
| Gigabyte      | Z390 M GAMING-CF            | [cb1ab91477](https://linux-hardware.org/?probe=cb1ab91477) | Apr 09, 2024 |
| Gigabyte      | B650M DS3H                  | [2c7e501a12](https://linux-hardware.org/?probe=2c7e501a12) | Apr 09, 2024 |
| Foxconn       | H55MX-S Series              | [e659b4546f](https://linux-hardware.org/?probe=e659b4546f) | Apr 09, 2024 |
| Alienware     | 0XJKKD A01                  | [891952c62d](https://linux-hardware.org/?probe=891952c62d) | Apr 09, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [7e40bc4b0a](https://linux-hardware.org/?probe=7e40bc4b0a) | Apr 09, 2024 |
| Foxconn       | H55MX-S Series              | [93deba6ce5](https://linux-hardware.org/?probe=93deba6ce5) | Apr 09, 2024 |
| ASRock        | B550M-C                     | [dd5090a053](https://linux-hardware.org/?probe=dd5090a053) | Apr 09, 2024 |
| Alienware     | 07HV66 A01                  | [5557c9197d](https://linux-hardware.org/?probe=5557c9197d) | Apr 09, 2024 |
| Itautec       | ST 4265                     | [256c04b1e3](https://linux-hardware.org/?probe=256c04b1e3) | Apr 09, 2024 |
| Itautec       | ST 4265                     | [052c74a17d](https://linux-hardware.org/?probe=052c74a17d) | Apr 08, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [cc080ae6d6](https://linux-hardware.org/?probe=cc080ae6d6) | Apr 08, 2024 |
| HP            | 8595                        | [75999844ff](https://linux-hardware.org/?probe=75999844ff) | Apr 08, 2024 |
| HP            | 8595                        | [78e64097d4](https://linux-hardware.org/?probe=78e64097d4) | Apr 08, 2024 |
| MSI           | X99A RAIDER                 | [8ebbe74fff](https://linux-hardware.org/?probe=8ebbe74fff) | Apr 08, 2024 |
| HP            | 2B38                        | [db7129fcde](https://linux-hardware.org/?probe=db7129fcde) | Apr 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [0553161eac](https://linux-hardware.org/?probe=0553161eac) | Apr 07, 2024 |
| HP            | 2B38                        | [44386f0027](https://linux-hardware.org/?probe=44386f0027) | Apr 07, 2024 |
| ASUSTek       | PRIME B350M-A               | [57145c3161](https://linux-hardware.org/?probe=57145c3161) | Apr 07, 2024 |
| Shenzhen M... | F7BSC                       | [5a07da097a](https://linux-hardware.org/?probe=5a07da097a) | Apr 07, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | [e499150ab3](https://linux-hardware.org/?probe=e499150ab3) | Apr 07, 2024 |
| ASRock        | B450M-HDV                   | [a06329df00](https://linux-hardware.org/?probe=a06329df00) | Apr 07, 2024 |
| MSI           | X99A RAIDER                 | [b35623df85](https://linux-hardware.org/?probe=b35623df85) | Apr 07, 2024 |
| MSI           | B450M MORTAR MAX            | [67dad6a68c](https://linux-hardware.org/?probe=67dad6a68c) | Apr 07, 2024 |
| Intel         | X99                         | [7dca188f3d](https://linux-hardware.org/?probe=7dca188f3d) | Apr 07, 2024 |
| Intel         | X99                         | [8821705436](https://linux-hardware.org/?probe=8821705436) | Apr 07, 2024 |
| Gigabyte      | A520M K V2                  | [d0dc207772](https://linux-hardware.org/?probe=d0dc207772) | Apr 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [4a15d1a355](https://linux-hardware.org/?probe=4a15d1a355) | Apr 06, 2024 |
| HP            | 870C                        | [eb08ffa35d](https://linux-hardware.org/?probe=eb08ffa35d) | Apr 06, 2024 |
| ASUSTek       | Maximus IX FORMULA          | [0bb98b6d5d](https://linux-hardware.org/?probe=0bb98b6d5d) | Apr 06, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [f675a67959](https://linux-hardware.org/?probe=f675a67959) | Apr 06, 2024 |
| ASUSTek       | H61M-A/BR                   | [4c0e6e4b31](https://linux-hardware.org/?probe=4c0e6e4b31) | Apr 06, 2024 |
| MSI           | X99A RAIDER                 | [bae1a9abd7](https://linux-hardware.org/?probe=bae1a9abd7) | Apr 06, 2024 |
| Gigabyte      | GA-870A-UD3                 | [b99319c775](https://linux-hardware.org/?probe=b99319c775) | Apr 06, 2024 |
| Foxconn       | H55MX-S Series              | [57dab83b95](https://linux-hardware.org/?probe=57dab83b95) | Apr 06, 2024 |
| Foxconn       | H55MX-S Series              | [111eb94f46](https://linux-hardware.org/?probe=111eb94f46) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5bc8966967](https://linux-hardware.org/?probe=5bc8966967) | Apr 06, 2024 |
| Gigabyte      | G41MT-D3                    | [ae8d66a693](https://linux-hardware.org/?probe=ae8d66a693) | Apr 06, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [68d2448180](https://linux-hardware.org/?probe=68d2448180) | Apr 05, 2024 |
| Win elemen... | M600                        | [9f4d0b35c6](https://linux-hardware.org/?probe=9f4d0b35c6) | Apr 05, 2024 |
| Win elemen... | M600                        | [bed5926e13](https://linux-hardware.org/?probe=bed5926e13) | Apr 05, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6496d4176b](https://linux-hardware.org/?probe=6496d4176b) | Apr 05, 2024 |
| ASUSTek       | Maximus IX FORMULA          | [a7245399da](https://linux-hardware.org/?probe=a7245399da) | Apr 05, 2024 |
| MSI           | PRO B760-VC WIFI            | [f6466041c0](https://linux-hardware.org/?probe=f6466041c0) | Apr 05, 2024 |
| Gigabyte      | B650 GAMING X AX            | [490811d61a](https://linux-hardware.org/?probe=490811d61a) | Apr 05, 2024 |
| OEM           | X99-Turbo                   | [ad20e3f989](https://linux-hardware.org/?probe=ad20e3f989) | Apr 05, 2024 |
| MSI           | PRO B760-VC WIFI            | [2847b39ae3](https://linux-hardware.org/?probe=2847b39ae3) | Apr 05, 2024 |
| MSI           | A320M PRO-VH PLUS           | [943c2e486a](https://linux-hardware.org/?probe=943c2e486a) | Apr 05, 2024 |
| MSI           | A320M PRO-VH PLUS           | [15b41ef5b3](https://linux-hardware.org/?probe=15b41ef5b3) | Apr 04, 2024 |
| Dell          | 07N90W A02                  | [4d11f26d4c](https://linux-hardware.org/?probe=4d11f26d4c) | Apr 04, 2024 |
| ASRock        | B550M-C                     | [7601b80b80](https://linux-hardware.org/?probe=7601b80b80) | Apr 04, 2024 |
| Dell          | 0P99M4 A01                  | [7a869aaf6e](https://linux-hardware.org/?probe=7a869aaf6e) | Apr 04, 2024 |
| HP            | 2175                        | [d21c1aaf46](https://linux-hardware.org/?probe=d21c1aaf46) | Apr 04, 2024 |
| MSI           | PRO B650-P WIFI             | [8856db4940](https://linux-hardware.org/?probe=8856db4940) | Apr 04, 2024 |
| Intel         | B75 V124A                   | [df800a1252](https://linux-hardware.org/?probe=df800a1252) | Apr 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [071d177bf5](https://linux-hardware.org/?probe=071d177bf5) | Apr 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8946117fdf](https://linux-hardware.org/?probe=8946117fdf) | Apr 04, 2024 |
| HP            | 1497                        | [86bbef8ff3](https://linux-hardware.org/?probe=86bbef8ff3) | Apr 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4eb39c2cf0](https://linux-hardware.org/?probe=4eb39c2cf0) | Apr 03, 2024 |
| ASRock        | B650M Pro RS WiFi           | [e0b3cba959](https://linux-hardware.org/?probe=e0b3cba959) | Apr 03, 2024 |
| HP            | 8434 11                     | [a1a62e20a4](https://linux-hardware.org/?probe=a1a62e20a4) | Apr 03, 2024 |
| HP            | 1495                        | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| ASRock        | B650M Pro RS WiFi           | [60c648fc52](https://linux-hardware.org/?probe=60c648fc52) | Apr 03, 2024 |
| Lenovo        | 3709 SDK0J40700 WIN 3258... | [1e11e401a4](https://linux-hardware.org/?probe=1e11e401a4) | Apr 03, 2024 |
| ASRock        | B650M-H/M.2+                | [2e3ed0f79c](https://linux-hardware.org/?probe=2e3ed0f79c) | Apr 02, 2024 |
| ASUSTek       | PRIME B650M-K               | [5f3337af59](https://linux-hardware.org/?probe=5f3337af59) | Apr 02, 2024 |
| Gigabyte      | H510M S2H V3                | [860e8667e1](https://linux-hardware.org/?probe=860e8667e1) | Apr 02, 2024 |
| Dell          | 0GY6Y8 A01                  | [ae35aaa6fe](https://linux-hardware.org/?probe=ae35aaa6fe) | Apr 02, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [aedfa9ff53](https://linux-hardware.org/?probe=aedfa9ff53) | Apr 02, 2024 |
| MSI           | B365M PRO-VH                | [3b94bbe5fe](https://linux-hardware.org/?probe=3b94bbe5fe) | Apr 02, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [3bf4dbf87e](https://linux-hardware.org/?probe=3bf4dbf87e) | Apr 02, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9c151ab347](https://linux-hardware.org/?probe=9c151ab347) | Apr 01, 2024 |
| HP            | 1632                        | [09e29cc1bb](https://linux-hardware.org/?probe=09e29cc1bb) | Apr 01, 2024 |
| HP            | 1632                        | [746200a8d4](https://linux-hardware.org/?probe=746200a8d4) | Apr 01, 2024 |
| ASUSTek       | PRIME B360-PLUS             | [1fd384a408](https://linux-hardware.org/?probe=1fd384a408) | Apr 01, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | [f0329002c8](https://linux-hardware.org/?probe=f0329002c8) | Apr 01, 2024 |
| Lenovo        | 3769 NO DPK                 | [c532b6c4ed](https://linux-hardware.org/?probe=c532b6c4ed) | Apr 01, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e9b930b832](https://linux-hardware.org/?probe=e9b930b832) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | [48dfdf4137](https://linux-hardware.org/?probe=48dfdf4137) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | [d209d00332](https://linux-hardware.org/?probe=d209d00332) | Apr 01, 2024 |
| Huanan        | X79 V2.47                   | [46ef932a9f](https://linux-hardware.org/?probe=46ef932a9f) | Mar 31, 2024 |
| Gigabyte      | H81M-S                      | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Gigabyte      | B450 AORUS M                | [e3f1b781a2](https://linux-hardware.org/?probe=e3f1b781a2) | Mar 31, 2024 |
| Gigabyte      | H61M-S2-B3                  | [a7615a9986](https://linux-hardware.org/?probe=a7615a9986) | Mar 31, 2024 |
| Gigabyte      | B450 AORUS M                | [145a13951d](https://linux-hardware.org/?probe=145a13951d) | Mar 31, 2024 |
| Gigabyte      | H61M-S2-B3                  | [00de19b7af](https://linux-hardware.org/?probe=00de19b7af) | Mar 31, 2024 |
| ASUSTek       | H87-PLUS                    | [a32a6e5814](https://linux-hardware.org/?probe=a32a6e5814) | Mar 31, 2024 |
| Gigabyte      | B85-HD3                     | [bd45787501](https://linux-hardware.org/?probe=bd45787501) | Mar 31, 2024 |
| GEEKOM        | A5                          | [da516126ba](https://linux-hardware.org/?probe=da516126ba) | Mar 31, 2024 |
| MSI           | B560M-A PRO                 | [e365e673d0](https://linux-hardware.org/?probe=e365e673d0) | Mar 31, 2024 |
| MSI           | Z390-A PRO                  | [bbd24ce2a1](https://linux-hardware.org/?probe=bbd24ce2a1) | Mar 31, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [7f3b57dade](https://linux-hardware.org/?probe=7f3b57dade) | Mar 30, 2024 |
| Foxconn       | H61MXL-K                    | [967587e883](https://linux-hardware.org/?probe=967587e883) | Mar 30, 2024 |
| ASRock        | B365M IB-R                  | [870917e4e8](https://linux-hardware.org/?probe=870917e4e8) | Mar 30, 2024 |
| MSI           | MS-B9181                    | [1ae3e9b8ba](https://linux-hardware.org/?probe=1ae3e9b8ba) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [c8e50aef4c](https://linux-hardware.org/?probe=c8e50aef4c) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [dc808b758c](https://linux-hardware.org/?probe=dc808b758c) | Mar 30, 2024 |
| HP            | 886C                        | [c36efe4b45](https://linux-hardware.org/?probe=c36efe4b45) | Mar 30, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | [6edb48c733](https://linux-hardware.org/?probe=6edb48c733) | Mar 29, 2024 |
| Gigabyte      | B450 AORUS M                | [ba62c18a47](https://linux-hardware.org/?probe=ba62c18a47) | Mar 29, 2024 |
| Gigabyte      | B450 AORUS M                | [d58ea5ec2c](https://linux-hardware.org/?probe=d58ea5ec2c) | Mar 29, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [b8f102aaac](https://linux-hardware.org/?probe=b8f102aaac) | Mar 29, 2024 |
| ASUSTek       | PRIME B560M-K               | [75a6f1b690](https://linux-hardware.org/?probe=75a6f1b690) | Mar 29, 2024 |
| ASRock        | B550M Pro4                  | [4190d386b3](https://linux-hardware.org/?probe=4190d386b3) | Mar 29, 2024 |
| ASUSTek       | GA35DX                      | [9f86bc906c](https://linux-hardware.org/?probe=9f86bc906c) | Mar 29, 2024 |
| ASRock        | AD2700-ITX                  | [52eb0a99d1](https://linux-hardware.org/?probe=52eb0a99d1) | Mar 29, 2024 |
| Apple         | Mac-F221BEC8                | [eadd458a1d](https://linux-hardware.org/?probe=eadd458a1d) | Mar 29, 2024 |
| Gigabyte      | Z87X-OC-CF                  | [ef8f367c13](https://linux-hardware.org/?probe=ef8f367c13) | Mar 29, 2024 |
| Dell          | 0K837J A02                  | [d4e979b93a](https://linux-hardware.org/?probe=d4e979b93a) | Mar 29, 2024 |
| Dell          | 0K837J A02                  | [86c44e64e6](https://linux-hardware.org/?probe=86c44e64e6) | Mar 29, 2024 |
| Intel         | X99                         | [f0dc0b1cf7](https://linux-hardware.org/?probe=f0dc0b1cf7) | Mar 28, 2024 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [208d350948](https://linux-hardware.org/?probe=208d350948) | Mar 28, 2024 |
| Lenovo        | 1066 NOK                    | [43b1e20967](https://linux-hardware.org/?probe=43b1e20967) | Mar 28, 2024 |
| ASUSTek       | PRIME B660M-K D4            | [ec561b98c0](https://linux-hardware.org/?probe=ec561b98c0) | Mar 28, 2024 |
| Intel         | X99                         | [9770a63f27](https://linux-hardware.org/?probe=9770a63f27) | Mar 28, 2024 |
| MSI           | MPG Z790 CARBON WIFI        | [2854efe003](https://linux-hardware.org/?probe=2854efe003) | Mar 28, 2024 |
| Gigabyte      | 990FXA-UD3                  | [ef4427b153](https://linux-hardware.org/?probe=ef4427b153) | Mar 28, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1248f2ac01](https://linux-hardware.org/?probe=1248f2ac01) | Mar 27, 2024 |
| Gigabyte      | B560M DS3H                  | [483f5486da](https://linux-hardware.org/?probe=483f5486da) | Mar 27, 2024 |
| Gigabyte      | Z77MX-D3H                   | [6d24bca5f3](https://linux-hardware.org/?probe=6d24bca5f3) | Mar 27, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [56d77f445e](https://linux-hardware.org/?probe=56d77f445e) | Mar 27, 2024 |
| HP            | 18E7                        | [ff6a9328f3](https://linux-hardware.org/?probe=ff6a9328f3) | Mar 27, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b46c9ec4ab](https://linux-hardware.org/?probe=b46c9ec4ab) | Mar 27, 2024 |
| ASRock        | B550M Pro4                  | [d8557bf301](https://linux-hardware.org/?probe=d8557bf301) | Mar 26, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [fed078783d](https://linux-hardware.org/?probe=fed078783d) | Mar 26, 2024 |
| HP            | 8767 A                      | [ad38b06d7e](https://linux-hardware.org/?probe=ad38b06d7e) | Mar 26, 2024 |
| SZQFTX        | MI2-SC                      | [4364c74d90](https://linux-hardware.org/?probe=4364c74d90) | Mar 26, 2024 |
| Gigabyte      | B450M DS3H V2               | [e506b0242a](https://linux-hardware.org/?probe=e506b0242a) | Mar 26, 2024 |
| HP            | 8643 SMVB                   | [752af4f00b](https://linux-hardware.org/?probe=752af4f00b) | Mar 26, 2024 |
| ASUSTek       | PRIME X570-P                | [e347c5c90a](https://linux-hardware.org/?probe=e347c5c90a) | Mar 26, 2024 |
| ASRock        | B550 PG Velocita            | [b81f82d351](https://linux-hardware.org/?probe=b81f82d351) | Mar 25, 2024 |
| ASUSTek       | PRIME X570-P                | [90bb672c8b](https://linux-hardware.org/?probe=90bb672c8b) | Mar 25, 2024 |
| ASUSTek       | P6X58D-E                    | [079fb4b5bc](https://linux-hardware.org/?probe=079fb4b5bc) | Mar 25, 2024 |
| Lenovo        | 1036 NO DPK                 | [2eceb99d09](https://linux-hardware.org/?probe=2eceb99d09) | Mar 25, 2024 |
| HP            | 3646h                       | [94d980596e](https://linux-hardware.org/?probe=94d980596e) | Mar 25, 2024 |
| MSI           | H61M-P20/W8                 | [24a58b5cc3](https://linux-hardware.org/?probe=24a58b5cc3) | Mar 25, 2024 |
| Lenovo        | 30C0 SBB0M45864 WIN 3305... | [c49adde538](https://linux-hardware.org/?probe=c49adde538) | Mar 25, 2024 |
| ASRock        | B550 PG Velocita            | [ae39da586e](https://linux-hardware.org/?probe=ae39da586e) | Mar 25, 2024 |
| MSI           | PRO H610M-E DDR4            | [cf6f76433e](https://linux-hardware.org/?probe=cf6f76433e) | Mar 25, 2024 |
| ASRock        | B550M Pro4                  | [6bfc2f7f08](https://linux-hardware.org/?probe=6bfc2f7f08) | Mar 25, 2024 |
| MSI           | H61M-P20/W8                 | [733e7093b1](https://linux-hardware.org/?probe=733e7093b1) | Mar 25, 2024 |
| ASUSTek       | Maximus IV Extreme          | [0eb022bd57](https://linux-hardware.org/?probe=0eb022bd57) | Mar 25, 2024 |
| ASUSTek       | PRIME H610M-D D4            | [68bda24263](https://linux-hardware.org/?probe=68bda24263) | Mar 24, 2024 |
| Intel         | DH55TC AAE70932-302         | [67b164f712](https://linux-hardware.org/?probe=67b164f712) | Mar 24, 2024 |
| Dell          | 0XD433 A00                  | [dd7aca8bce](https://linux-hardware.org/?probe=dd7aca8bce) | Mar 24, 2024 |
| ASRock        | M3N78D FX                   | [ac75a8caa6](https://linux-hardware.org/?probe=ac75a8caa6) | Mar 24, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [c3b5853d94](https://linux-hardware.org/?probe=c3b5853d94) | Mar 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [ef64fb9837](https://linux-hardware.org/?probe=ef64fb9837) | Mar 24, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [a3bda8f86d](https://linux-hardware.org/?probe=a3bda8f86d) | Mar 24, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [aa71eb1fea](https://linux-hardware.org/?probe=aa71eb1fea) | Mar 24, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [0defdbcedd](https://linux-hardware.org/?probe=0defdbcedd) | Mar 24, 2024 |
| Gigabyte      | B550M K                     | [bfc7e96b9c](https://linux-hardware.org/?probe=bfc7e96b9c) | Mar 24, 2024 |
| Gigabyte      | B450M DS3H-CF               | [58ff9b49c3](https://linux-hardware.org/?probe=58ff9b49c3) | Mar 23, 2024 |
| HP            | 8767 A                      | [5149a8ba78](https://linux-hardware.org/?probe=5149a8ba78) | Mar 23, 2024 |
| ASRock        | AB350 Pro4                  | [98053d03fb](https://linux-hardware.org/?probe=98053d03fb) | Mar 23, 2024 |
| ASRock        | AB350 Pro4                  | [6a4491e402](https://linux-hardware.org/?probe=6a4491e402) | Mar 23, 2024 |
| Biostar       | H61MLV                      | [c4a166928e](https://linux-hardware.org/?probe=c4a166928e) | Mar 23, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [810fea77aa](https://linux-hardware.org/?probe=810fea77aa) | Mar 23, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b4b14726e3](https://linux-hardware.org/?probe=b4b14726e3) | Mar 23, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [2b17261b3a](https://linux-hardware.org/?probe=2b17261b3a) | Mar 23, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e37fef15e](https://linux-hardware.org/?probe=2e37fef15e) | Mar 23, 2024 |
| Gigabyte      | J1900M-D2P                  | [2c072e707c](https://linux-hardware.org/?probe=2c072e707c) | Mar 23, 2024 |
| ASUSTek       | PRIME B650M-K               | [c554279c73](https://linux-hardware.org/?probe=c554279c73) | Mar 23, 2024 |
| Dell          | 0XD433 A00                  | [7493f7d748](https://linux-hardware.org/?probe=7493f7d748) | Mar 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [2441f80f98](https://linux-hardware.org/?probe=2441f80f98) | Mar 23, 2024 |
| ASRock        | X300M-STX                   | [41f3f09405](https://linux-hardware.org/?probe=41f3f09405) | Mar 23, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d402ccab08](https://linux-hardware.org/?probe=d402ccab08) | Mar 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a0d5a96cf4](https://linux-hardware.org/?probe=a0d5a96cf4) | Mar 23, 2024 |
| ASRock        | Z77 Extreme6                | [72c7021b55](https://linux-hardware.org/?probe=72c7021b55) | Mar 22, 2024 |
| HP            | 212B                        | [c2e77d634d](https://linux-hardware.org/?probe=c2e77d634d) | Mar 22, 2024 |
| HP            | 212B                        | [6862acf2e2](https://linux-hardware.org/?probe=6862acf2e2) | Mar 22, 2024 |
| MSI           | PRO B660M-E DDR4            | [083addc44d](https://linux-hardware.org/?probe=083addc44d) | Mar 22, 2024 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [08adc47cd0](https://linux-hardware.org/?probe=08adc47cd0) | Mar 22, 2024 |
| NCR           | Misano                      | [d31ebf4987](https://linux-hardware.org/?probe=d31ebf4987) | Mar 22, 2024 |
| Biostar       | H61MLV                      | [8f05e7d694](https://linux-hardware.org/?probe=8f05e7d694) | Mar 22, 2024 |
| MSI           | B450M BAZOOKA               | [a4ff7791f6](https://linux-hardware.org/?probe=a4ff7791f6) | Mar 22, 2024 |
| Dell          | 07WP95 A01                  | [91d3a8ab75](https://linux-hardware.org/?probe=91d3a8ab75) | Mar 21, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [1c26aa3298](https://linux-hardware.org/?probe=1c26aa3298) | Mar 21, 2024 |
| ASUSTek       | PRIME A320M-K               | [73769f6724](https://linux-hardware.org/?probe=73769f6724) | Mar 21, 2024 |
| Gigabyte      | H97M-HD3                    | [e80f6ad755](https://linux-hardware.org/?probe=e80f6ad755) | Mar 21, 2024 |
| HP            | 8054                        | [269251e535](https://linux-hardware.org/?probe=269251e535) | Mar 21, 2024 |
| ECS           | H61H2-MV                    | [2ab5b82fb2](https://linux-hardware.org/?probe=2ab5b82fb2) | Mar 21, 2024 |
| Dell          | 07WP95 A01                  | [8d213c1708](https://linux-hardware.org/?probe=8d213c1708) | Mar 21, 2024 |
| Acer          | Aspire TC-1660 V:1.1        | [c0dfdce31b](https://linux-hardware.org/?probe=c0dfdce31b) | Mar 21, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [fc00eb107c](https://linux-hardware.org/?probe=fc00eb107c) | Mar 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a3211374f](https://linux-hardware.org/?probe=5a3211374f) | Mar 20, 2024 |
| Lenovo        | ThinkCentre M58p 7220A72    | [9d5723ac83](https://linux-hardware.org/?probe=9d5723ac83) | Mar 20, 2024 |
| MSI           | B450M-A PRO MAX II          | [81d81323e9](https://linux-hardware.org/?probe=81d81323e9) | Mar 20, 2024 |
| ASUSTek       | Z87-A                       | [82226d4eeb](https://linux-hardware.org/?probe=82226d4eeb) | Mar 20, 2024 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | [aef062b601](https://linux-hardware.org/?probe=aef062b601) | Mar 20, 2024 |
| Foxconn       | 2ADA                        | [cbc6b7f4f8](https://linux-hardware.org/?probe=cbc6b7f4f8) | Mar 20, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [59f4fda949](https://linux-hardware.org/?probe=59f4fda949) | Mar 19, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [a5aa554570](https://linux-hardware.org/?probe=a5aa554570) | Mar 19, 2024 |
| Intel         | X99H                        | [d2bcb78b08](https://linux-hardware.org/?probe=d2bcb78b08) | Mar 19, 2024 |
| Dell          | 0K2NWM A00                  | [c74bd3823a](https://linux-hardware.org/?probe=c74bd3823a) | Mar 19, 2024 |
| MSI           | B450M BAZOOKA               | [8acd0b4f67](https://linux-hardware.org/?probe=8acd0b4f67) | Mar 19, 2024 |
| ASUSTek       | PRIME Z270-P                | [12f62966ac](https://linux-hardware.org/?probe=12f62966ac) | Mar 19, 2024 |
| ASRock        | B450M Pro4 R2.0             | [09cc580df1](https://linux-hardware.org/?probe=09cc580df1) | Mar 19, 2024 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [868c239b34](https://linux-hardware.org/?probe=868c239b34) | Mar 19, 2024 |
| ASUSTek       | PRIME A320M-K               | [2559083db4](https://linux-hardware.org/?probe=2559083db4) | Mar 19, 2024 |
| MSI           | B450M PRO-VDH MAX           | [d2157076ae](https://linux-hardware.org/?probe=d2157076ae) | Mar 18, 2024 |
| MSI           | B350M MORTAR                | [8d5526d959](https://linux-hardware.org/?probe=8d5526d959) | Mar 18, 2024 |
| Dell          | 02YYK5 A01                  | [ea80b38e6e](https://linux-hardware.org/?probe=ea80b38e6e) | Mar 18, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | [72fa1a6cd1](https://linux-hardware.org/?probe=72fa1a6cd1) | Mar 18, 2024 |
| MSI           | B560M-A PRO                 | [5e5b0f7c8e](https://linux-hardware.org/?probe=5e5b0f7c8e) | Mar 18, 2024 |
| Intel         | H81                         | [36c10e3626](https://linux-hardware.org/?probe=36c10e3626) | Mar 18, 2024 |
| Intel         | H81                         | [1bdef11f1d](https://linux-hardware.org/?probe=1bdef11f1d) | Mar 18, 2024 |
| ASUSTek       | PB50                        | [48a3c760f1](https://linux-hardware.org/?probe=48a3c760f1) | Mar 17, 2024 |
| MSI           | Z390 PLUS                   | [8aabf6b948](https://linux-hardware.org/?probe=8aabf6b948) | Mar 17, 2024 |
| MSI           | Z390 PLUS                   | [d2c68bfc8c](https://linux-hardware.org/?probe=d2c68bfc8c) | Mar 17, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [6cc40f1ab5](https://linux-hardware.org/?probe=6cc40f1ab5) | Mar 17, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [fcf4a969ac](https://linux-hardware.org/?probe=fcf4a969ac) | Mar 17, 2024 |
| Dell          | 0VRWRC A00                  | [858ec63e4e](https://linux-hardware.org/?probe=858ec63e4e) | Mar 17, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7347a50168](https://linux-hardware.org/?probe=7347a50168) | Mar 17, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [9a74259cf6](https://linux-hardware.org/?probe=9a74259cf6) | Mar 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [e1d8b9713d](https://linux-hardware.org/?probe=e1d8b9713d) | Mar 16, 2024 |
| MSI           | B350M BAZOOKA               | [e8c63c54a8](https://linux-hardware.org/?probe=e8c63c54a8) | Mar 16, 2024 |
| ASUSTek       | PRIME B550M-A               | [e7849fe0ba](https://linux-hardware.org/?probe=e7849fe0ba) | Mar 16, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [598011953e](https://linux-hardware.org/?probe=598011953e) | Mar 16, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [a60433b2f9](https://linux-hardware.org/?probe=a60433b2f9) | Mar 16, 2024 |
| MSI           | MEG Z390 GODLIKE            | [86b5c5939b](https://linux-hardware.org/?probe=86b5c5939b) | Mar 16, 2024 |
| Dell          | 0GK1K2 A00                  | [8b61a57322](https://linux-hardware.org/?probe=8b61a57322) | Mar 16, 2024 |
| MSI           | PRO Z690-A DDR4             | [8a0b5bf53d](https://linux-hardware.org/?probe=8a0b5bf53d) | Mar 16, 2024 |
| ASUSTek       | PRIME H310M-A               | [972b9375c7](https://linux-hardware.org/?probe=972b9375c7) | Mar 16, 2024 |
| Dell          | 0C2KJT A00                  | [b049e2f049](https://linux-hardware.org/?probe=b049e2f049) | Mar 15, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [10889b5773](https://linux-hardware.org/?probe=10889b5773) | Mar 15, 2024 |
| MSI           | B450-A PRO                  | [fbea84b6b4](https://linux-hardware.org/?probe=fbea84b6b4) | Mar 15, 2024 |
| ASUSTek       | P8Z68-V LX                  | [3573b604cc](https://linux-hardware.org/?probe=3573b604cc) | Mar 15, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [fd9e14f869](https://linux-hardware.org/?probe=fd9e14f869) | Mar 15, 2024 |
| ASRock        | B450 Pro4                   | [723f208e9b](https://linux-hardware.org/?probe=723f208e9b) | Mar 14, 2024 |
| ASRock        | B450 Pro4                   | [a3a7dd03fc](https://linux-hardware.org/?probe=a3a7dd03fc) | Mar 14, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [dbc28d0198](https://linux-hardware.org/?probe=dbc28d0198) | Mar 14, 2024 |
| MSI           | MPG Z790I EDGE WIFI         | [6933f4969f](https://linux-hardware.org/?probe=6933f4969f) | Mar 14, 2024 |
| GEEKOM        | A7                          | [41bbc04266](https://linux-hardware.org/?probe=41bbc04266) | Mar 13, 2024 |
| Gigabyte      | B85M-D3V-A                  | [dd00485e27](https://linux-hardware.org/?probe=dd00485e27) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [da89580342](https://linux-hardware.org/?probe=da89580342) | Mar 13, 2024 |
| Dell          | 00V62H A01                  | [d0b41424bf](https://linux-hardware.org/?probe=d0b41424bf) | Mar 12, 2024 |
| Dell          | 0M5DCD A00                  | [6a7520951e](https://linux-hardware.org/?probe=6a7520951e) | Mar 12, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [37790d3110](https://linux-hardware.org/?probe=37790d3110) | Mar 12, 2024 |
| Lenovo        | 1052 NOK                    | [a07900782f](https://linux-hardware.org/?probe=a07900782f) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [86024c45ed](https://linux-hardware.org/?probe=86024c45ed) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [a65a82b4d4](https://linux-hardware.org/?probe=a65a82b4d4) | Mar 12, 2024 |
| NZXT          | N7 B650E                    | [66453a8f80](https://linux-hardware.org/?probe=66453a8f80) | Mar 12, 2024 |
| Gigabyte      | H81M-DS2                    | [dde5a90821](https://linux-hardware.org/?probe=dde5a90821) | Mar 12, 2024 |
| NZXT          | N7 B650E                    | [b788fa656b](https://linux-hardware.org/?probe=b788fa656b) | Mar 12, 2024 |
| Intel         | X99-P4 V5.0                 | [d15a83afa0](https://linux-hardware.org/?probe=d15a83afa0) | Mar 12, 2024 |
| ASRock        | P45TS                       | [34e6cab182](https://linux-hardware.org/?probe=34e6cab182) | Mar 12, 2024 |
| GALAX         | B365M G10b                  | [728ae3d168](https://linux-hardware.org/?probe=728ae3d168) | Mar 12, 2024 |
| ASRock        | H55M-LE                     | [43f3ef8fd5](https://linux-hardware.org/?probe=43f3ef8fd5) | Mar 11, 2024 |
| ASUSTek       | P8Z77-M PRO                 | [3aaabd554f](https://linux-hardware.org/?probe=3aaabd554f) | Mar 10, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [45963ebb10](https://linux-hardware.org/?probe=45963ebb10) | Mar 10, 2024 |
| Dell          | 040DDP A01                  | [61d64de417](https://linux-hardware.org/?probe=61d64de417) | Mar 10, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [014ec83828](https://linux-hardware.org/?probe=014ec83828) | Mar 10, 2024 |
| MSI           | 760GM-P34                   | [cef041a8ee](https://linux-hardware.org/?probe=cef041a8ee) | Mar 10, 2024 |
| Dell          | 0X501H A00                  | [b65adc134f](https://linux-hardware.org/?probe=b65adc134f) | Mar 10, 2024 |
| Gigabyte      | J1900M-D2P                  | [f638c5db6a](https://linux-hardware.org/?probe=f638c5db6a) | Mar 10, 2024 |
| AZW           | SER V1                      | [03fbf37ce1](https://linux-hardware.org/?probe=03fbf37ce1) | Mar 10, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [001f42acad](https://linux-hardware.org/?probe=001f42acad) | Mar 10, 2024 |
| Gigabyte      | B450M GAMING                | [d7a9a275ed](https://linux-hardware.org/?probe=d7a9a275ed) | Mar 10, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [5e7d500ce9](https://linux-hardware.org/?probe=5e7d500ce9) | Mar 10, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e2818e065c](https://linux-hardware.org/?probe=e2818e065c) | Mar 09, 2024 |
| MSI           | B450M MORTAR MAX            | [e1ab158ccf](https://linux-hardware.org/?probe=e1ab158ccf) | Mar 09, 2024 |
| Dell          | 0V8WGR A01                  | [addd0c2871](https://linux-hardware.org/?probe=addd0c2871) | Mar 09, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [2a6047cea9](https://linux-hardware.org/?probe=2a6047cea9) | Mar 09, 2024 |
| Google        | Panther                     | [9fee846e7c](https://linux-hardware.org/?probe=9fee846e7c) | Mar 09, 2024 |
| Google        | Panther                     | [9b94bb7555](https://linux-hardware.org/?probe=9b94bb7555) | Mar 09, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [c02282268e](https://linux-hardware.org/?probe=c02282268e) | Mar 09, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [94f8b9a5ec](https://linux-hardware.org/?probe=94f8b9a5ec) | Mar 08, 2024 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [6e9090d743](https://linux-hardware.org/?probe=6e9090d743) | Mar 08, 2024 |
| HP            | 83EE                        | [0129a70225](https://linux-hardware.org/?probe=0129a70225) | Mar 08, 2024 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [103c096047](https://linux-hardware.org/?probe=103c096047) | Mar 07, 2024 |
| Gigabyte      | AB350M-HD3-CF se1           | [6f60e3f76e](https://linux-hardware.org/?probe=6f60e3f76e) | Mar 07, 2024 |
| Gigabyte      | B550M DS3H AC               | [203f82333d](https://linux-hardware.org/?probe=203f82333d) | Mar 07, 2024 |
| Gigabyte      | H97M-HD3                    | [1b028e3789](https://linux-hardware.org/?probe=1b028e3789) | Mar 07, 2024 |
| Intel         | DG33BU AAD79951-405         | [2cdebaa501](https://linux-hardware.org/?probe=2cdebaa501) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [1719342e74](https://linux-hardware.org/?probe=1719342e74) | Mar 07, 2024 |
| MSI           | MEG X570 UNIFY              | [c3ecdc1d99](https://linux-hardware.org/?probe=c3ecdc1d99) | Mar 06, 2024 |
| ASRock        | H61M-VG3                    | [717618a9c6](https://linux-hardware.org/?probe=717618a9c6) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ab740da693](https://linux-hardware.org/?probe=ab740da693) | Mar 06, 2024 |
| ASUSTek       | P8Z68-V PRO                 | [cd72ba8c02](https://linux-hardware.org/?probe=cd72ba8c02) | Mar 06, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [92ee6b2bfe](https://linux-hardware.org/?probe=92ee6b2bfe) | Mar 06, 2024 |
| MSI           | B350 TOMAHAWK PLUS          | [a17b71b49d](https://linux-hardware.org/?probe=a17b71b49d) | Mar 05, 2024 |
| AMD           | A520                        | [bf763dfa9d](https://linux-hardware.org/?probe=bf763dfa9d) | Mar 05, 2024 |
| Digiboard     | MPxx                        | [9551902d2d](https://linux-hardware.org/?probe=9551902d2d) | Mar 05, 2024 |
| Unknown       | Unknown                     | [7709b92d0a](https://linux-hardware.org/?probe=7709b92d0a) | Mar 05, 2024 |
| Gigabyte      | B550M DS3H                  | [c3069142cb](https://linux-hardware.org/?probe=c3069142cb) | Mar 05, 2024 |
| ASRock        | B660-ITX                    | [4e2d037487](https://linux-hardware.org/?probe=4e2d037487) | Mar 05, 2024 |
| Pegatron      | 2AC2A                       | [ae3cc4af6d](https://linux-hardware.org/?probe=ae3cc4af6d) | Mar 04, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7da52267ed](https://linux-hardware.org/?probe=7da52267ed) | Mar 04, 2024 |
| Dell          | 0Y2MRG A01                  | [e86dfdef50](https://linux-hardware.org/?probe=e86dfdef50) | Mar 04, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [29b34c19d3](https://linux-hardware.org/?probe=29b34c19d3) | Mar 04, 2024 |
| HP            | 87D6 SMVB                   | [ddea20ce6c](https://linux-hardware.org/?probe=ddea20ce6c) | Mar 03, 2024 |
| Dell          | 0V8WGR A01                  | [7365a2624f](https://linux-hardware.org/?probe=7365a2624f) | Mar 03, 2024 |
| ASRock        | B550M-ITX/ac                | [52ee74e340](https://linux-hardware.org/?probe=52ee74e340) | Mar 03, 2024 |
| Gigabyte      | H61M-S2V-B3                 | [eaa7dc4743](https://linux-hardware.org/?probe=eaa7dc4743) | Mar 03, 2024 |
| MSI           | MEG X570 UNIFY              | [46fef61e9e](https://linux-hardware.org/?probe=46fef61e9e) | Mar 03, 2024 |
| Gigabyte      | AX370-Gaming K5-CF          | [03ffd1aa1b](https://linux-hardware.org/?probe=03ffd1aa1b) | Mar 03, 2024 |
| Dell          | 088DT1 A01                  | [52c4382ecc](https://linux-hardware.org/?probe=52c4382ecc) | Mar 03, 2024 |
| MSI           | MS-B9201                    | [11682d05a0](https://linux-hardware.org/?probe=11682d05a0) | Mar 03, 2024 |
| MSI           | MS-B9201                    | [a6baa17c48](https://linux-hardware.org/?probe=a6baa17c48) | Mar 03, 2024 |
| HP            | 1905                        | [e98cd386ed](https://linux-hardware.org/?probe=e98cd386ed) | Mar 03, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [109efd5c05](https://linux-hardware.org/?probe=109efd5c05) | Mar 03, 2024 |
| ASRock        | B660M-HDV                   | [427836e454](https://linux-hardware.org/?probe=427836e454) | Mar 02, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [87afd5cfa6](https://linux-hardware.org/?probe=87afd5cfa6) | Mar 02, 2024 |
| Dell          | 042P49 A02                  | [a707d0b8f6](https://linux-hardware.org/?probe=a707d0b8f6) | Mar 02, 2024 |
| ASRock        | B660M-HDV                   | [68b50166f3](https://linux-hardware.org/?probe=68b50166f3) | Mar 02, 2024 |
| Fujitsu       | D3231-S1 S26361-D3231-S1    | [3445498936](https://linux-hardware.org/?probe=3445498936) | Mar 02, 2024 |
| ASUSTek       | D500TC                      | [78a01397ae](https://linux-hardware.org/?probe=78a01397ae) | Mar 02, 2024 |
| ASUSTek       | D500TC                      | [06e510f9b4](https://linux-hardware.org/?probe=06e510f9b4) | Mar 02, 2024 |
| ASRock        | B450M Pro4-F R2.0           | [97b861c12b](https://linux-hardware.org/?probe=97b861c12b) | Mar 01, 2024 |
| ASUSTek       | P5G41T-M LX                 | [e0de46817d](https://linux-hardware.org/?probe=e0de46817d) | Mar 01, 2024 |
| ASRock        | 990FX Killer                | [0e0a9543b3](https://linux-hardware.org/?probe=0e0a9543b3) | Mar 01, 2024 |
| Gigabyte      | A620M GAMING X AX           | [bcf877e80c](https://linux-hardware.org/?probe=bcf877e80c) | Mar 01, 2024 |
| ASUSTek       | P8H61-M LE/CSM              | [41206d8b5d](https://linux-hardware.org/?probe=41206d8b5d) | Mar 01, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c886c83137](https://linux-hardware.org/?probe=c886c83137) | Feb 29, 2024 |
| Apple         | Mac-F221BEC8                | [263d7989cb](https://linux-hardware.org/?probe=263d7989cb) | Feb 29, 2024 |
| ASRock        | B650E Taichi Lite           | [45d4f1a6c1](https://linux-hardware.org/?probe=45d4f1a6c1) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [6fe990a29c](https://linux-hardware.org/?probe=6fe990a29c) | Feb 29, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | [fa61c6c7a1](https://linux-hardware.org/?probe=fa61c6c7a1) | Feb 29, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | [8fa6673f0c](https://linux-hardware.org/?probe=8fa6673f0c) | Feb 29, 2024 |
| HP            | 1998                        | [de124e0aad](https://linux-hardware.org/?probe=de124e0aad) | Feb 29, 2024 |
| Dell          | 0DFRFW A01                  | [0f4cb380d0](https://linux-hardware.org/?probe=0f4cb380d0) | Feb 28, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [7039330487](https://linux-hardware.org/?probe=7039330487) | Feb 28, 2024 |
| MSI           | PRO B660M-E DDR4            | [6d9ef71e3b](https://linux-hardware.org/?probe=6d9ef71e3b) | Feb 28, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [4bb4a14245](https://linux-hardware.org/?probe=4bb4a14245) | Feb 28, 2024 |
| Gigabyte      | B450M DS3H-CF               | [b379aba175](https://linux-hardware.org/?probe=b379aba175) | Feb 28, 2024 |
| ASRock        | FM2A68M-HD+                 | [4869de3185](https://linux-hardware.org/?probe=4869de3185) | Feb 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [ca82540f11](https://linux-hardware.org/?probe=ca82540f11) | Feb 28, 2024 |
| Gigabyte      | H310M S2H                   | [482a7100d8](https://linux-hardware.org/?probe=482a7100d8) | Feb 27, 2024 |
| ASRock        | B550M-ITX/ac                | [c3ea9f352f](https://linux-hardware.org/?probe=c3ea9f352f) | Feb 27, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d5d958e5d9](https://linux-hardware.org/?probe=d5d958e5d9) | Feb 27, 2024 |
| HP            | 805D                        | [a4e341ef12](https://linux-hardware.org/?probe=a4e341ef12) | Feb 27, 2024 |
| Unknown       | Unknown                     | [5f88523016](https://linux-hardware.org/?probe=5f88523016) | Feb 27, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [056d94a05f](https://linux-hardware.org/?probe=056d94a05f) | Feb 27, 2024 |
| AMD           | A520                        | [606f339d84](https://linux-hardware.org/?probe=606f339d84) | Feb 27, 2024 |
| Gigabyte      | B550 GAMING X V2            | [2810a78cf4](https://linux-hardware.org/?probe=2810a78cf4) | Feb 27, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [fdf2db398f](https://linux-hardware.org/?probe=fdf2db398f) | Feb 27, 2024 |
| Gigabyte      | B550 GAMING X V2            | [81c23b536b](https://linux-hardware.org/?probe=81c23b536b) | Feb 27, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [a4fa28e88f](https://linux-hardware.org/?probe=a4fa28e88f) | Feb 26, 2024 |
| Shenzhen M... | F7BAA                       | [d261d09b18](https://linux-hardware.org/?probe=d261d09b18) | Feb 26, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [ebdfb428a7](https://linux-hardware.org/?probe=ebdfb428a7) | Feb 26, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a98b039841](https://linux-hardware.org/?probe=a98b039841) | Feb 26, 2024 |
| Gigabyte      | B550M DS3H AC               | [86575e9e0c](https://linux-hardware.org/?probe=86575e9e0c) | Feb 26, 2024 |
| Gigabyte      | GA-970A-UD3                 | [1be2150566](https://linux-hardware.org/?probe=1be2150566) | Feb 26, 2024 |
| Gigabyte      | Z77MX-D3H                   | [e2f7db70cc](https://linux-hardware.org/?probe=e2f7db70cc) | Feb 26, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a99365833b](https://linux-hardware.org/?probe=a99365833b) | Feb 26, 2024 |
| Shenzhen M... | F7BAA                       | [67da95b542](https://linux-hardware.org/?probe=67da95b542) | Feb 25, 2024 |
| ASRock        | B550M-ITX/ac                | [70921daf0d](https://linux-hardware.org/?probe=70921daf0d) | Feb 25, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [fe14f1d35b](https://linux-hardware.org/?probe=fe14f1d35b) | Feb 25, 2024 |
| ASRock        | N68C-S UCC                  | [4aff653920](https://linux-hardware.org/?probe=4aff653920) | Feb 25, 2024 |
| ASUSTek       | PRIME B450M-A II            | [ad4c84d385](https://linux-hardware.org/?probe=ad4c84d385) | Feb 25, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | [4bc9aa7d3a](https://linux-hardware.org/?probe=4bc9aa7d3a) | Feb 25, 2024 |
| ASRock        | FM2A68M-HD+                 | [daafafcf94](https://linux-hardware.org/?probe=daafafcf94) | Feb 25, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [075f3b55c8](https://linux-hardware.org/?probe=075f3b55c8) | Feb 25, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [8231c10128](https://linux-hardware.org/?probe=8231c10128) | Feb 25, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [9455775381](https://linux-hardware.org/?probe=9455775381) | Feb 25, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a6f08967ca](https://linux-hardware.org/?probe=a6f08967ca) | Feb 24, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [2b1b229936](https://linux-hardware.org/?probe=2b1b229936) | Feb 24, 2024 |
| ASUSTek       | P9X79 LE                    | [9fc143e2b9](https://linux-hardware.org/?probe=9fc143e2b9) | Feb 24, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [8784f6d9f3](https://linux-hardware.org/?probe=8784f6d9f3) | Feb 24, 2024 |
| ASUSTek       | PRIME Z390-A                | [b3e5fe0754](https://linux-hardware.org/?probe=b3e5fe0754) | Feb 24, 2024 |
| Gigabyte      | Z370M DS3H-CF               | [e290f43bee](https://linux-hardware.org/?probe=e290f43bee) | Feb 24, 2024 |
| Gigabyte      | Z370M DS3H-CF               | [b7a3d79295](https://linux-hardware.org/?probe=b7a3d79295) | Feb 24, 2024 |
| Biostar       | A320MH                      | [4480fb658b](https://linux-hardware.org/?probe=4480fb658b) | Feb 24, 2024 |
| Gigabyte      | 970A-DS3P                   | [a62c77eb85](https://linux-hardware.org/?probe=a62c77eb85) | Feb 24, 2024 |
| Dell          | 00V62H A01                  | [3db9227dda](https://linux-hardware.org/?probe=3db9227dda) | Feb 24, 2024 |
| MSI           | MS-7388                     | [2429edf24b](https://linux-hardware.org/?probe=2429edf24b) | Feb 24, 2024 |
| Gigabyte      | G41MT-D3                    | [dd00b434af](https://linux-hardware.org/?probe=dd00b434af) | Feb 24, 2024 |
| Gigabyte      | GA-870A-UD3                 | [e6acbeff7e](https://linux-hardware.org/?probe=e6acbeff7e) | Feb 24, 2024 |
| Gigabyte      | J1900M-D2P                  | [5339633565](https://linux-hardware.org/?probe=5339633565) | Feb 24, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8bb9b8a42a](https://linux-hardware.org/?probe=8bb9b8a42a) | Feb 24, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b72538d4d2](https://linux-hardware.org/?probe=b72538d4d2) | Feb 24, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [949f1cd85d](https://linux-hardware.org/?probe=949f1cd85d) | Feb 23, 2024 |
| Dell          | 0KJCC5 A00                  | [5d71445a1c](https://linux-hardware.org/?probe=5d71445a1c) | Feb 23, 2024 |
| ASUSTek       | PRIME B450M-A II            | [d9780d8472](https://linux-hardware.org/?probe=d9780d8472) | Feb 23, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | [b1897a476e](https://linux-hardware.org/?probe=b1897a476e) | Feb 23, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4ad6003e14](https://linux-hardware.org/?probe=4ad6003e14) | Feb 23, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [11c7902587](https://linux-hardware.org/?probe=11c7902587) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | [244cd38058](https://linux-hardware.org/?probe=244cd38058) | Feb 23, 2024 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [51148df849](https://linux-hardware.org/?probe=51148df849) | Feb 23, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [9470ab96b2](https://linux-hardware.org/?probe=9470ab96b2) | Feb 23, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [d32fba0e96](https://linux-hardware.org/?probe=d32fba0e96) | Feb 23, 2024 |
| ASRock        | B650M-HDV/M.2               | [23c90ffd3a](https://linux-hardware.org/?probe=23c90ffd3a) | Feb 22, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a1083e09fa](https://linux-hardware.org/?probe=a1083e09fa) | Feb 22, 2024 |
| HP            | 805D                        | [bfe43c8f6f](https://linux-hardware.org/?probe=bfe43c8f6f) | Feb 22, 2024 |
| MSI           | MAG B660M BAZOOKA DDR4      | [b870f14a33](https://linux-hardware.org/?probe=b870f14a33) | Feb 22, 2024 |
| Gigabyte      | Z170X-Gaming 5              | [4199cffa4f](https://linux-hardware.org/?probe=4199cffa4f) | Feb 21, 2024 |
| ASRock        | Z97E-ITX/ac                 | [0b4dc072fe](https://linux-hardware.org/?probe=0b4dc072fe) | Feb 21, 2024 |
| ASRock        | G41C-GS                     | [afd3704033](https://linux-hardware.org/?probe=afd3704033) | Feb 21, 2024 |
| Dell          | 0VRWRC A00                  | [e5e91a26f8](https://linux-hardware.org/?probe=e5e91a26f8) | Feb 21, 2024 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [d63458f668](https://linux-hardware.org/?probe=d63458f668) | Feb 21, 2024 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [ede6bceec9](https://linux-hardware.org/?probe=ede6bceec9) | Feb 21, 2024 |
| Gigabyte      | Z390 M-CF                   | [da7b2aabc9](https://linux-hardware.org/?probe=da7b2aabc9) | Feb 21, 2024 |
| HP            | 2215                        | [3333f97016](https://linux-hardware.org/?probe=3333f97016) | Feb 21, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [cc456069d3](https://linux-hardware.org/?probe=cc456069d3) | Feb 21, 2024 |
| MSI           | MAG B660M BAZOOKA DDR4      | [a655bdeb74](https://linux-hardware.org/?probe=a655bdeb74) | Feb 20, 2024 |
| Dell          | 0HN7XN A00                  | [49c1c6a80a](https://linux-hardware.org/?probe=49c1c6a80a) | Feb 20, 2024 |
| ASUSTek       | PRIME Z270-P                | [03c4445d03](https://linux-hardware.org/?probe=03c4445d03) | Feb 20, 2024 |
| Acer          | Veriton X4110G              | [85c69e6034](https://linux-hardware.org/?probe=85c69e6034) | Feb 20, 2024 |
| Unknown       | Unknown                     | [13504f6300](https://linux-hardware.org/?probe=13504f6300) | Feb 20, 2024 |
| Pegatron      | IPMH61P1                    | [438f1fc09d](https://linux-hardware.org/?probe=438f1fc09d) | Feb 20, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [219f9cb0cb](https://linux-hardware.org/?probe=219f9cb0cb) | Feb 20, 2024 |
| MSI           | A320M-A PRO                 | [088d4b8a65](https://linux-hardware.org/?probe=088d4b8a65) | Feb 20, 2024 |
| HP            | 2215                        | [8fec3e792a](https://linux-hardware.org/?probe=8fec3e792a) | Feb 19, 2024 |
| MSI           | H510I PRO WIFI              | [52e9a0e485](https://linux-hardware.org/?probe=52e9a0e485) | Feb 19, 2024 |
| HP            | 83E9                        | [5c64b48b20](https://linux-hardware.org/?probe=5c64b48b20) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b667bc9122](https://linux-hardware.org/?probe=b667bc9122) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f562021a9](https://linux-hardware.org/?probe=3f562021a9) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8c09f036b](https://linux-hardware.org/?probe=b8c09f036b) | Feb 19, 2024 |
| ASRock        | G41C-GS                     | [b28c13684a](https://linux-hardware.org/?probe=b28c13684a) | Feb 19, 2024 |
| ASUSTek       | M2N-TE                      | [e1931b720e](https://linux-hardware.org/?probe=e1931b720e) | Feb 19, 2024 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [6ebb084fa0](https://linux-hardware.org/?probe=6ebb084fa0) | Feb 19, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [6eb913e53f](https://linux-hardware.org/?probe=6eb913e53f) | Feb 19, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [f10a5d0844](https://linux-hardware.org/?probe=f10a5d0844) | Feb 19, 2024 |
| HP            | 8A96 11                     | [6f03ec0a38](https://linux-hardware.org/?probe=6f03ec0a38) | Feb 19, 2024 |
| Gigabyte      | P35C-DS3R                   | [a573f2f068](https://linux-hardware.org/?probe=a573f2f068) | Feb 19, 2024 |
| MSI           | X99A RAIDER                 | [2a1f27fe39](https://linux-hardware.org/?probe=2a1f27fe39) | Feb 19, 2024 |
| ASRock        | X99 Taichi                  | [98640d2d16](https://linux-hardware.org/?probe=98640d2d16) | Feb 19, 2024 |
| ASRock        | B365M Pro4                  | [420e3cc35b](https://linux-hardware.org/?probe=420e3cc35b) | Feb 18, 2024 |
| ASRock        | B365M Pro4                  | [cd216bb151](https://linux-hardware.org/?probe=cd216bb151) | Feb 18, 2024 |
| Intel         | X99 V1.0                    | [53be939fd4](https://linux-hardware.org/?probe=53be939fd4) | Feb 18, 2024 |
| MSI           | A520M-A PRO                 | [dd37fb4492](https://linux-hardware.org/?probe=dd37fb4492) | Feb 18, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [92a3da7b06](https://linux-hardware.org/?probe=92a3da7b06) | Feb 18, 2024 |
| Gigabyte      | X570 AORUS PRO              | [c71d21d3c2](https://linux-hardware.org/?probe=c71d21d3c2) | Feb 18, 2024 |
| Dell          | 0KJCC5 A00                  | [fab0a7953d](https://linux-hardware.org/?probe=fab0a7953d) | Feb 18, 2024 |
| ASRock        | A320M Pro4-F                | [d4007897b9](https://linux-hardware.org/?probe=d4007897b9) | Feb 18, 2024 |
| ASRock        | X570 Phantom Gaming 4S      | [56e7d1d3ea](https://linux-hardware.org/?probe=56e7d1d3ea) | Feb 18, 2024 |
| MSI           | X99A RAIDER                 | [20ae1292c5](https://linux-hardware.org/?probe=20ae1292c5) | Feb 18, 2024 |
| MSI           | PRO B650-P WIFI             | [753b761dd6](https://linux-hardware.org/?probe=753b761dd6) | Feb 18, 2024 |
| ASUSTek       | PRIME H270-PLUS             | [ae5261f6af](https://linux-hardware.org/?probe=ae5261f6af) | Feb 17, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [2df79d1eff](https://linux-hardware.org/?probe=2df79d1eff) | Feb 17, 2024 |
| BESSTAR Te... | TH50                        | [ee4866df27](https://linux-hardware.org/?probe=ee4866df27) | Feb 17, 2024 |
| Gigabyte      | H110M-H DDR3-CF             | [03bf287af9](https://linux-hardware.org/?probe=03bf287af9) | Feb 17, 2024 |
| Gigabyte      | G41MT-D3                    | [1478dc157c](https://linux-hardware.org/?probe=1478dc157c) | Feb 17, 2024 |
| MSI           | AMETHYST-M                  | [ca908328d9](https://linux-hardware.org/?probe=ca908328d9) | Feb 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [195ccec5ac](https://linux-hardware.org/?probe=195ccec5ac) | Feb 16, 2024 |
| MSI           | AMETHYST-M                  | [1701f5e6a9](https://linux-hardware.org/?probe=1701f5e6a9) | Feb 16, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [5e676dc488](https://linux-hardware.org/?probe=5e676dc488) | Feb 16, 2024 |
| MSI           | PRO B660M-E DDR4            | [40d28adbd5](https://linux-hardware.org/?probe=40d28adbd5) | Feb 15, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [317a98ac74](https://linux-hardware.org/?probe=317a98ac74) | Feb 15, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [f3dad0af31](https://linux-hardware.org/?probe=f3dad0af31) | Feb 15, 2024 |
| ASUSTek       | PRIME B450M-A II            | [58dc65db56](https://linux-hardware.org/?probe=58dc65db56) | Feb 15, 2024 |
| HP            | 0AECh D                     | [f542fee953](https://linux-hardware.org/?probe=f542fee953) | Feb 15, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [a62bdc7719](https://linux-hardware.org/?probe=a62bdc7719) | Feb 15, 2024 |
| ASUSTek       | PRIME B450M-A II            | [e0715ac544](https://linux-hardware.org/?probe=e0715ac544) | Feb 15, 2024 |
| Unknown       | Unknown                     | [d4ffec2f30](https://linux-hardware.org/?probe=d4ffec2f30) | Feb 15, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [526c74c210](https://linux-hardware.org/?probe=526c74c210) | Feb 15, 2024 |
| Dell          | 0HHV7N A00                  | [809cfa76c6](https://linux-hardware.org/?probe=809cfa76c6) | Feb 15, 2024 |
| Dell          | 0HHV7N A00                  | [f975ea14f6](https://linux-hardware.org/?probe=f975ea14f6) | Feb 14, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [6637baf0a5](https://linux-hardware.org/?probe=6637baf0a5) | Feb 14, 2024 |
| MSI           | H110M PRO-VD PLUS           | [3c66be1385](https://linux-hardware.org/?probe=3c66be1385) | Feb 14, 2024 |
| Acer          | Predator PO3-630            | [45ef053c68](https://linux-hardware.org/?probe=45ef053c68) | Feb 14, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [bfbd5c6295](https://linux-hardware.org/?probe=bfbd5c6295) | Feb 14, 2024 |
| ASRock        | X570 Phantom Gaming 4S      | [01e9c9ed92](https://linux-hardware.org/?probe=01e9c9ed92) | Feb 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [1c7c2e02cb](https://linux-hardware.org/?probe=1c7c2e02cb) | Feb 13, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [fda923c904](https://linux-hardware.org/?probe=fda923c904) | Feb 13, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [fd550d37e4](https://linux-hardware.org/?probe=fd550d37e4) | Feb 12, 2024 |
| Gigabyte      | A320M-H-CF                  | [76b99bc559](https://linux-hardware.org/?probe=76b99bc559) | Feb 12, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [6486a2883f](https://linux-hardware.org/?probe=6486a2883f) | Feb 12, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [a81e54d797](https://linux-hardware.org/?probe=a81e54d797) | Feb 12, 2024 |
| HP            | 1495                        | [047dcce2b9](https://linux-hardware.org/?probe=047dcce2b9) | Feb 12, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [01b810943e](https://linux-hardware.org/?probe=01b810943e) | Feb 12, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [58bd1f7aed](https://linux-hardware.org/?probe=58bd1f7aed) | Feb 12, 2024 |
| Biostar       | A68MHE                      | [adf7cb9274](https://linux-hardware.org/?probe=adf7cb9274) | Feb 12, 2024 |
| Dell          | 0KRC95 A02                  | [5f2be5fefa](https://linux-hardware.org/?probe=5f2be5fefa) | Feb 11, 2024 |
| Dell          | 0YNVJG A02                  | [c979ee9419](https://linux-hardware.org/?probe=c979ee9419) | Feb 11, 2024 |
| MACHINIST     | X99-RS9 V3.1                | [f77f3320c0](https://linux-hardware.org/?probe=f77f3320c0) | Feb 11, 2024 |
| MACHINIST     | X99-RS9 V3.1                | [86e543bb4c](https://linux-hardware.org/?probe=86e543bb4c) | Feb 11, 2024 |
| HP            | 8055                        | [5814a9f75b](https://linux-hardware.org/?probe=5814a9f75b) | Feb 11, 2024 |
| Gigabyte      | Z77MX-D3H                   | [e3d87c07aa](https://linux-hardware.org/?probe=e3d87c07aa) | Feb 11, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0d347a5da4](https://linux-hardware.org/?probe=0d347a5da4) | Feb 11, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [d0a7bef49e](https://linux-hardware.org/?probe=d0a7bef49e) | Feb 11, 2024 |
| Dell          | 004FN1 A01                  | [832b78549b](https://linux-hardware.org/?probe=832b78549b) | Feb 11, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [633fc33096](https://linux-hardware.org/?probe=633fc33096) | Feb 10, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6d6b8b6d7d](https://linux-hardware.org/?probe=6d6b8b6d7d) | Feb 10, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [0c36321ae6](https://linux-hardware.org/?probe=0c36321ae6) | Feb 10, 2024 |
| ASUSTek       | H110M-R                     | [9df19beabd](https://linux-hardware.org/?probe=9df19beabd) | Feb 10, 2024 |
| ASUSTek       | H110M-R                     | [4d0e061568](https://linux-hardware.org/?probe=4d0e061568) | Feb 10, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [179f28f8e3](https://linux-hardware.org/?probe=179f28f8e3) | Feb 10, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [662e5df955](https://linux-hardware.org/?probe=662e5df955) | Feb 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [e85583dafa](https://linux-hardware.org/?probe=e85583dafa) | Feb 10, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [1a9fd9bdbd](https://linux-hardware.org/?probe=1a9fd9bdbd) | Feb 10, 2024 |
| Gigabyte      | GA-870A-UD3                 | [b69eecd28e](https://linux-hardware.org/?probe=b69eecd28e) | Feb 10, 2024 |
| ASUSTek       | PRIME B760-PLUS             | [4c75dbf3e4](https://linux-hardware.org/?probe=4c75dbf3e4) | Feb 10, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [dbd67f16dc](https://linux-hardware.org/?probe=dbd67f16dc) | Feb 09, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [37d98b4cbf](https://linux-hardware.org/?probe=37d98b4cbf) | Feb 09, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [982dc2cfb4](https://linux-hardware.org/?probe=982dc2cfb4) | Feb 09, 2024 |
| ASUSTek       | PRIME Z590-P                | [697011e701](https://linux-hardware.org/?probe=697011e701) | Feb 09, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [308b87d845](https://linux-hardware.org/?probe=308b87d845) | Feb 09, 2024 |
| Gigabyte      | B85M-D3V-A                  | [f4251d37e2](https://linux-hardware.org/?probe=f4251d37e2) | Feb 09, 2024 |
| Gigabyte      | H310M S2H                   | [87512d7e7e](https://linux-hardware.org/?probe=87512d7e7e) | Feb 09, 2024 |
| Gigabyte      | J1900M-D2P                  | [86467d10dc](https://linux-hardware.org/?probe=86467d10dc) | Feb 09, 2024 |
| Dell          | 0HHV7N A00                  | [6cc19e9f8a](https://linux-hardware.org/?probe=6cc19e9f8a) | Feb 09, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8234b16b6a](https://linux-hardware.org/?probe=8234b16b6a) | Feb 08, 2024 |
| ASUSTek       | PRIME A320M-A               | [f85fa50f25](https://linux-hardware.org/?probe=f85fa50f25) | Feb 08, 2024 |
| Acer          | Predator PO3-630            | [c0f6de019d](https://linux-hardware.org/?probe=c0f6de019d) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [bc288692b8](https://linux-hardware.org/?probe=bc288692b8) | Feb 08, 2024 |
| MSI           | B450M MORTAR MAX            | [7d93273d71](https://linux-hardware.org/?probe=7d93273d71) | Feb 08, 2024 |
| Dell          | 0TDG4V A01                  | [aae07824f6](https://linux-hardware.org/?probe=aae07824f6) | Feb 08, 2024 |
| Danuri        | B550M-PX                    | [2e639c4202](https://linux-hardware.org/?probe=2e639c4202) | Feb 07, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [894a9128d0](https://linux-hardware.org/?probe=894a9128d0) | Feb 07, 2024 |
| ASUSTek       | P9X79 LE                    | [d718121ccc](https://linux-hardware.org/?probe=d718121ccc) | Feb 07, 2024 |
| Lenovo        | SDK0E50510 WIN              | [f8b45adf06](https://linux-hardware.org/?probe=f8b45adf06) | Feb 07, 2024 |
| MSI           | Z370-A PRO                  | [1bb42a007e](https://linux-hardware.org/?probe=1bb42a007e) | Feb 07, 2024 |
| Intel         | H55                         | [cadc3711e0](https://linux-hardware.org/?probe=cadc3711e0) | Feb 07, 2024 |
| Lenovo        | ThinkCentre M58p 7220A72    | [3fda097acd](https://linux-hardware.org/?probe=3fda097acd) | Feb 07, 2024 |
| Shenzhen M... | DRFXI                       | [0f6bdc262a](https://linux-hardware.org/?probe=0f6bdc262a) | Feb 07, 2024 |
| Shenzhen M... | DRFXI                       | [e30d161f24](https://linux-hardware.org/?probe=e30d161f24) | Feb 07, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [4f4a731909](https://linux-hardware.org/?probe=4f4a731909) | Feb 07, 2024 |
| HP            | 0B54h D                     | [95d93c776d](https://linux-hardware.org/?probe=95d93c776d) | Feb 06, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [48146cfed7](https://linux-hardware.org/?probe=48146cfed7) | Feb 06, 2024 |
| ASUSTek       | X99-DELUXE II               | [cde1b607e4](https://linux-hardware.org/?probe=cde1b607e4) | Feb 06, 2024 |
| Gigabyte      | B550M DS3H                  | [a50feca5c5](https://linux-hardware.org/?probe=a50feca5c5) | Feb 05, 2024 |
| Gigabyte      | H77M-D3H                    | [cccac82c9f](https://linux-hardware.org/?probe=cccac82c9f) | Feb 05, 2024 |
| MSI           | MAG B760M MORTAR MAX WIF... | [c82d881aee](https://linux-hardware.org/?probe=c82d881aee) | Feb 05, 2024 |
| ASRock        | 970 Extreme3                | [06dc9ae1ab](https://linux-hardware.org/?probe=06dc9ae1ab) | Feb 05, 2024 |
| ASUSTek       | H97M-E                      | [80a217fc53](https://linux-hardware.org/?probe=80a217fc53) | Feb 05, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [72838f01dc](https://linux-hardware.org/?probe=72838f01dc) | Feb 05, 2024 |
| ASRock        | AB350 Gaming-ITX/ac         | [5051c554ea](https://linux-hardware.org/?probe=5051c554ea) | Feb 05, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [ab931f7c26](https://linux-hardware.org/?probe=ab931f7c26) | Feb 05, 2024 |
| ASUSTek       | STRIX B250F GAMING          | [c54da6844e](https://linux-hardware.org/?probe=c54da6844e) | Feb 05, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [15012c2832](https://linux-hardware.org/?probe=15012c2832) | Feb 05, 2024 |
| HP            | 0AECh D                     | [8e34a7f2b3](https://linux-hardware.org/?probe=8e34a7f2b3) | Feb 04, 2024 |
| Gigabyte      | H77M-D3H                    | [4e70174dd5](https://linux-hardware.org/?probe=4e70174dd5) | Feb 04, 2024 |
| HP            | 8618                        | [df55ae931a](https://linux-hardware.org/?probe=df55ae931a) | Feb 04, 2024 |
| Dell          | 0KJCC5 A00                  | [da239f62cb](https://linux-hardware.org/?probe=da239f62cb) | Feb 04, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [d7207d9c77](https://linux-hardware.org/?probe=d7207d9c77) | Feb 04, 2024 |
| MSI           | Z490M-S01                   | [49a63046bd](https://linux-hardware.org/?probe=49a63046bd) | Feb 04, 2024 |
| AZW           | EQ                          | [8923cbe776](https://linux-hardware.org/?probe=8923cbe776) | Feb 04, 2024 |
| ASRock        | Z170 Pro4                   | [8a577144aa](https://linux-hardware.org/?probe=8a577144aa) | Feb 04, 2024 |
| ASRock        | A320M-HDV R4.0              | [a15632e04c](https://linux-hardware.org/?probe=a15632e04c) | Feb 04, 2024 |
| ASRock        | X670E Pro RS                | [b5f16b7125](https://linux-hardware.org/?probe=b5f16b7125) | Feb 03, 2024 |
| ASUSTek       | Z170-DELUXE                 | [ae245dd993](https://linux-hardware.org/?probe=ae245dd993) | Feb 03, 2024 |
| Gigabyte      | H410M S2 V2                 | [05931d928d](https://linux-hardware.org/?probe=05931d928d) | Feb 03, 2024 |
| ASUSTek       | PRIME A320M-K               | [63e5f0957e](https://linux-hardware.org/?probe=63e5f0957e) | Feb 03, 2024 |
| ASRock        | Z170 Pro4                   | [a5eafa5e5f](https://linux-hardware.org/?probe=a5eafa5e5f) | Feb 03, 2024 |
| MSI           | X99A RAIDER                 | [4e9d6930c7](https://linux-hardware.org/?probe=4e9d6930c7) | Feb 03, 2024 |
| Gigabyte      | G41MT-D3                    | [966b04c0cc](https://linux-hardware.org/?probe=966b04c0cc) | Feb 03, 2024 |
| ASUSTek       | X99-E WS                    | [03ddf903a2](https://linux-hardware.org/?probe=03ddf903a2) | Feb 02, 2024 |
| ASRock        | X670E Pro RS                | [fd02477c14](https://linux-hardware.org/?probe=fd02477c14) | Feb 02, 2024 |
| HP            | 83E9                        | [a140a989be](https://linux-hardware.org/?probe=a140a989be) | Feb 02, 2024 |
| ASUSTek       | H110M-R                     | [2902d23de2](https://linux-hardware.org/?probe=2902d23de2) | Feb 02, 2024 |
| Pegatron      | IPM41-D3                    | [5884d40085](https://linux-hardware.org/?probe=5884d40085) | Feb 02, 2024 |
| MSI           | X99A RAIDER                 | [158530e4dc](https://linux-hardware.org/?probe=158530e4dc) | Feb 02, 2024 |
| ASRock        | A320M-ITX                   | [7c3ebbb23c](https://linux-hardware.org/?probe=7c3ebbb23c) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [654e691a5d](https://linux-hardware.org/?probe=654e691a5d) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [279e68de12](https://linux-hardware.org/?probe=279e68de12) | Feb 02, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [e8554aab57](https://linux-hardware.org/?probe=e8554aab57) | Feb 02, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [73e32179ef](https://linux-hardware.org/?probe=73e32179ef) | Feb 02, 2024 |
| ASUSTek       | PRIME B560M-K               | [007e574396](https://linux-hardware.org/?probe=007e574396) | Feb 01, 2024 |
| ASUSTek       | PRIME B560M-K               | [9d4315d3e3](https://linux-hardware.org/?probe=9d4315d3e3) | Feb 01, 2024 |
| Pegatron      | IPM41-D3                    | [7969244295](https://linux-hardware.org/?probe=7969244295) | Feb 01, 2024 |
| HP            | 870C                        | [14801c4f80](https://linux-hardware.org/?probe=14801c4f80) | Feb 01, 2024 |
| Gigabyte      | G41MT-D3                    | [88c563b03e](https://linux-hardware.org/?probe=88c563b03e) | Feb 01, 2024 |
| MSI           | X99A RAIDER                 | [3953592045](https://linux-hardware.org/?probe=3953592045) | Feb 01, 2024 |
| Unknown       | Unknown                     | [66102cc055](https://linux-hardware.org/?probe=66102cc055) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0b234564e9](https://linux-hardware.org/?probe=0b234564e9) | Jan 31, 2024 |
| MSI           | X99A RAIDER                 | [ffaf5dab37](https://linux-hardware.org/?probe=ffaf5dab37) | Jan 31, 2024 |
| ASUSTek       | M4N68T-M LE                 | [31e2d90ef4](https://linux-hardware.org/?probe=31e2d90ef4) | Jan 31, 2024 |
| Dell          | 00V62H A01                  | [4a42c319b4](https://linux-hardware.org/?probe=4a42c319b4) | Jan 30, 2024 |
| MSI           | AMETHYST-M                  | [865d868008](https://linux-hardware.org/?probe=865d868008) | Jan 30, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [fac7cfcfce](https://linux-hardware.org/?probe=fac7cfcfce) | Jan 30, 2024 |
| MSI           | AMETHYST-M                  | [da16f0848e](https://linux-hardware.org/?probe=da16f0848e) | Jan 30, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [9d98a77586](https://linux-hardware.org/?probe=9d98a77586) | Jan 30, 2024 |
| ASUSTek       | X99-DELUXE                  | [482b1946f4](https://linux-hardware.org/?probe=482b1946f4) | Jan 30, 2024 |
| ASRock        | B550 Pro4                   | [9617266ebe](https://linux-hardware.org/?probe=9617266ebe) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0a68bb3157](https://linux-hardware.org/?probe=0a68bb3157) | Jan 30, 2024 |
| Dell          | 0U880P A01                  | [d3d4142e1e](https://linux-hardware.org/?probe=d3d4142e1e) | Jan 30, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [193e9e6c74](https://linux-hardware.org/?probe=193e9e6c74) | Jan 30, 2024 |
| ASRock        | B450M Pro4                  | [c0f87d75df](https://linux-hardware.org/?probe=c0f87d75df) | Jan 29, 2024 |
| MSI           | Z490M-S01                   | [ed7f213619](https://linux-hardware.org/?probe=ed7f213619) | Jan 29, 2024 |
| ASRock        | A320M-HD                    | [5c0864b392](https://linux-hardware.org/?probe=5c0864b392) | Jan 29, 2024 |
| MSI           | MAG B550M BAZOOKA           | [c0d98503dd](https://linux-hardware.org/?probe=c0d98503dd) | Jan 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | [99e90d2b89](https://linux-hardware.org/?probe=99e90d2b89) | Jan 29, 2024 |
| Intel         | DB75EN AAG39650-302         | [dcc6332a8e](https://linux-hardware.org/?probe=dcc6332a8e) | Jan 29, 2024 |
| MSI           | Z790 GAMING PRO WIFI        | [3e946efe3c](https://linux-hardware.org/?probe=3e946efe3c) | Jan 29, 2024 |
| Huanan        | X99-QD4 V1.0                | [2194293ede](https://linux-hardware.org/?probe=2194293ede) | Jan 28, 2024 |
| MSI           | 880GMS-E35                  | [0216fb4b4f](https://linux-hardware.org/?probe=0216fb4b4f) | Jan 28, 2024 |
| Gigabyte      | AX370-Gaming 5              | [c3f740ce88](https://linux-hardware.org/?probe=c3f740ce88) | Jan 28, 2024 |
| MSI           | H81M-E34                    | [9aec3e7a36](https://linux-hardware.org/?probe=9aec3e7a36) | Jan 28, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [35b6b0dd05](https://linux-hardware.org/?probe=35b6b0dd05) | Jan 28, 2024 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [cfc0d0a745](https://linux-hardware.org/?probe=cfc0d0a745) | Jan 28, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [59ce08f802](https://linux-hardware.org/?probe=59ce08f802) | Jan 28, 2024 |
| MSI           | X470 GAMING PLUS            | [a896c739ca](https://linux-hardware.org/?probe=a896c739ca) | Jan 28, 2024 |
| Gigabyte      | B650 GAMING X AX            | [f728617f20](https://linux-hardware.org/?probe=f728617f20) | Jan 28, 2024 |
| ASUSTek       | PRIME B450M-A II            | [1d4239bc71](https://linux-hardware.org/?probe=1d4239bc71) | Jan 27, 2024 |
| ASUSTek       | PRIME X370-A                | [e3c045bb8c](https://linux-hardware.org/?probe=e3c045bb8c) | Jan 27, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [26c552f089](https://linux-hardware.org/?probe=26c552f089) | Jan 27, 2024 |
| Gigabyte      | Z77MX-D3H                   | [618155f762](https://linux-hardware.org/?probe=618155f762) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [9d4827b4a5](https://linux-hardware.org/?probe=9d4827b4a5) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [57f2a52748](https://linux-hardware.org/?probe=57f2a52748) | Jan 27, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [85fd42ad4d](https://linux-hardware.org/?probe=85fd42ad4d) | Jan 27, 2024 |
| Gigabyte      | TRX40 AORUS XTREME          | [cdf9d5dadb](https://linux-hardware.org/?probe=cdf9d5dadb) | Jan 27, 2024 |
| Gigabyte      | G41MT-D3                    | [327217e107](https://linux-hardware.org/?probe=327217e107) | Jan 27, 2024 |
| MSI           | MEG Z690I UNIFY             | [42f4602ff3](https://linux-hardware.org/?probe=42f4602ff3) | Jan 27, 2024 |
| ASUSTek       | PRIME X670-P                | [1d4943457c](https://linux-hardware.org/?probe=1d4943457c) | Jan 26, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8ac63955c7](https://linux-hardware.org/?probe=8ac63955c7) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [9b55015259](https://linux-hardware.org/?probe=9b55015259) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [3cecdef02f](https://linux-hardware.org/?probe=3cecdef02f) | Jan 26, 2024 |
| HP            | 843B                        | [9a021639c5](https://linux-hardware.org/?probe=9a021639c5) | Jan 26, 2024 |
| ASUSTek       | PRIME X670-P                | [75379edae7](https://linux-hardware.org/?probe=75379edae7) | Jan 26, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | [f59710809d](https://linux-hardware.org/?probe=f59710809d) | Jan 26, 2024 |
| MSI           | H81M-E34                    | [c53fb2b81b](https://linux-hardware.org/?probe=c53fb2b81b) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [813ed73797](https://linux-hardware.org/?probe=813ed73797) | Jan 25, 2024 |
| ASUSTek       | Z97-P                       | [0803e06982](https://linux-hardware.org/?probe=0803e06982) | Jan 25, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [ac31169eb1](https://linux-hardware.org/?probe=ac31169eb1) | Jan 25, 2024 |
| ASUSTek       | H110M-D                     | [7f2b907eb8](https://linux-hardware.org/?probe=7f2b907eb8) | Jan 25, 2024 |
| MSI           | B450M BAZOOKA V2            | [3f0ed24a76](https://linux-hardware.org/?probe=3f0ed24a76) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [869af9b5c0](https://linux-hardware.org/?probe=869af9b5c0) | Jan 25, 2024 |
| ASUSTek       | G20AJ                       | [4dd87f5aeb](https://linux-hardware.org/?probe=4dd87f5aeb) | Jan 24, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [0786b58816](https://linux-hardware.org/?probe=0786b58816) | Jan 24, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [f38d7bb62a](https://linux-hardware.org/?probe=f38d7bb62a) | Jan 24, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [9bf161df69](https://linux-hardware.org/?probe=9bf161df69) | Jan 24, 2024 |
| MSI           | FM2-A75MA-E35               | [78cddbe37f](https://linux-hardware.org/?probe=78cddbe37f) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d6b0dcab0](https://linux-hardware.org/?probe=8d6b0dcab0) | Jan 24, 2024 |
| ASRock        | Z690-C/D5                   | [534911d3a7](https://linux-hardware.org/?probe=534911d3a7) | Jan 24, 2024 |
| ASRock        | B660-ITX                    | [c82f95d7de](https://linux-hardware.org/?probe=c82f95d7de) | Jan 24, 2024 |
| Gigabyte      | H61M-S2V-B3                 | [74874054dd](https://linux-hardware.org/?probe=74874054dd) | Jan 24, 2024 |
| Gigabyte      | H110M-S2H-CF                | [81f34fc65a](https://linux-hardware.org/?probe=81f34fc65a) | Jan 23, 2024 |
| Dell          | 0KN5W4 A03                  | [4665315883](https://linux-hardware.org/?probe=4665315883) | Jan 23, 2024 |
| ASUSTek       | P5Q SE2                     | [06fae6b7bf](https://linux-hardware.org/?probe=06fae6b7bf) | Jan 23, 2024 |
| MSI           | PRO B660M-E DDR4            | [7357312922](https://linux-hardware.org/?probe=7357312922) | Jan 23, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [1eeda8c8f1](https://linux-hardware.org/?probe=1eeda8c8f1) | Jan 23, 2024 |
| Lenovo        | ThinkCentre M90p 5536AN5    | [8305fcdce9](https://linux-hardware.org/?probe=8305fcdce9) | Jan 23, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | [9f48506578](https://linux-hardware.org/?probe=9f48506578) | Jan 23, 2024 |
| ASUSTek       | P5Q PRO TURBO               | [93762ed6a5](https://linux-hardware.org/?probe=93762ed6a5) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6dbdc40268](https://linux-hardware.org/?probe=6dbdc40268) | Jan 22, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [2c38517137](https://linux-hardware.org/?probe=2c38517137) | Jan 22, 2024 |
| Biostar       | A68MHE                      | [bd1cb81b9d](https://linux-hardware.org/?probe=bd1cb81b9d) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [bc06fb13b6](https://linux-hardware.org/?probe=bc06fb13b6) | Jan 22, 2024 |
| ASUSTek       | P7P55D                      | [8d8fab9b27](https://linux-hardware.org/?probe=8d8fab9b27) | Jan 21, 2024 |
| MSI           | X370 SLI PLUS               | [c4729b1c7c](https://linux-hardware.org/?probe=c4729b1c7c) | Jan 21, 2024 |
| ASUSTek       | M5A97 R2.0                  | [de6fb94ac8](https://linux-hardware.org/?probe=de6fb94ac8) | Jan 21, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [d67daf2078](https://linux-hardware.org/?probe=d67daf2078) | Jan 21, 2024 |
| HP            | 8618                        | [d1bd70f41d](https://linux-hardware.org/?probe=d1bd70f41d) | Jan 21, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [f313b1c112](https://linux-hardware.org/?probe=f313b1c112) | Jan 21, 2024 |
| Pegatron      | 2AB6                        | [57a1fef3f7](https://linux-hardware.org/?probe=57a1fef3f7) | Jan 21, 2024 |
| ASUSTek       | PRIME B550M-A               | [7069f9af65](https://linux-hardware.org/?probe=7069f9af65) | Jan 21, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [fbc836a9ff](https://linux-hardware.org/?probe=fbc836a9ff) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5c9deadb93](https://linux-hardware.org/?probe=5c9deadb93) | Jan 20, 2024 |
| MSI           | Z790 GAMING PRO WIFI        | [bdcd287661](https://linux-hardware.org/?probe=bdcd287661) | Jan 20, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [a535d51ede](https://linux-hardware.org/?probe=a535d51ede) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [1db270091f](https://linux-hardware.org/?probe=1db270091f) | Jan 20, 2024 |
| MSI           | MS-7388                     | [e151be731a](https://linux-hardware.org/?probe=e151be731a) | Jan 20, 2024 |
| Dell          | 04Y8V0 A02                  | [c7ac75fb19](https://linux-hardware.org/?probe=c7ac75fb19) | Jan 20, 2024 |
| HP            | 8A96 11                     | [8b913e22cd](https://linux-hardware.org/?probe=8b913e22cd) | Jan 20, 2024 |
| HP            | 8A96 11                     | [3fa20439d9](https://linux-hardware.org/?probe=3fa20439d9) | Jan 20, 2024 |
| Gigabyte      | GA-870A-UD3                 | [7c13b83bff](https://linux-hardware.org/?probe=7c13b83bff) | Jan 20, 2024 |
| ASRock        | B760M PG SONIC WiFi         | [987717796a](https://linux-hardware.org/?probe=987717796a) | Jan 20, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [5ab5b74cfa](https://linux-hardware.org/?probe=5ab5b74cfa) | Jan 20, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d166663637](https://linux-hardware.org/?probe=d166663637) | Jan 19, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [97f56eac35](https://linux-hardware.org/?probe=97f56eac35) | Jan 19, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [0eb94b3491](https://linux-hardware.org/?probe=0eb94b3491) | Jan 19, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [b6dfff4b78](https://linux-hardware.org/?probe=b6dfff4b78) | Jan 19, 2024 |
| Foxconn       | 2ABF                        | [9a5efc4dd3](https://linux-hardware.org/?probe=9a5efc4dd3) | Jan 19, 2024 |
| Gigabyte      | EP45-DS3L                   | [c3a9225062](https://linux-hardware.org/?probe=c3a9225062) | Jan 19, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [008c387c2b](https://linux-hardware.org/?probe=008c387c2b) | Jan 19, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | [9e1182e93f](https://linux-hardware.org/?probe=9e1182e93f) | Jan 19, 2024 |
| ASUSTek       | CG8480                      | [4610686acc](https://linux-hardware.org/?probe=4610686acc) | Jan 19, 2024 |
| Pegatron      | 2AB6                        | [9a9b3ef258](https://linux-hardware.org/?probe=9a9b3ef258) | Jan 19, 2024 |
| MSI           | MS-B9181                    | [503f0edf6a](https://linux-hardware.org/?probe=503f0edf6a) | Jan 19, 2024 |
| ASRock        | X370 Pro4                   | [9dfd5fe2cb](https://linux-hardware.org/?probe=9dfd5fe2cb) | Jan 19, 2024 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [89d65b315c](https://linux-hardware.org/?probe=89d65b315c) | Jan 19, 2024 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [27b2376cad](https://linux-hardware.org/?probe=27b2376cad) | Jan 18, 2024 |
| MSI           | MEG X570 UNIFY              | [01d5509c12](https://linux-hardware.org/?probe=01d5509c12) | Jan 18, 2024 |
| ASRock        | H310M-STX                   | [8e7c70643c](https://linux-hardware.org/?probe=8e7c70643c) | Jan 18, 2024 |
| Dell          | 0KN5W4 A03                  | [64f7b3272e](https://linux-hardware.org/?probe=64f7b3272e) | Jan 18, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [16f764cb39](https://linux-hardware.org/?probe=16f764cb39) | Jan 18, 2024 |
| ASUSTek       | PRIME B360-PLUS             | [7f55ddb513](https://linux-hardware.org/?probe=7f55ddb513) | Jan 18, 2024 |
| Gigabyte      | B85-HD3                     | [66b0dbb818](https://linux-hardware.org/?probe=66b0dbb818) | Jan 18, 2024 |
| HP            | 3048h                       | [e24f1cffa1](https://linux-hardware.org/?probe=e24f1cffa1) | Jan 18, 2024 |
| HP            | 2B0F                        | [ce5907f486](https://linux-hardware.org/?probe=ce5907f486) | Jan 18, 2024 |
| ASRock        | AD2700-ITX                  | [93eee675be](https://linux-hardware.org/?probe=93eee675be) | Jan 18, 2024 |
| Gigabyte      | J1900M-D2P                  | [3c5d80f1e7](https://linux-hardware.org/?probe=3c5d80f1e7) | Jan 18, 2024 |
| ASUSTek       | P8Z77-V                     | [cc154717f4](https://linux-hardware.org/?probe=cc154717f4) | Jan 18, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [04707ec04e](https://linux-hardware.org/?probe=04707ec04e) | Jan 17, 2024 |
| Gigabyte      | F2A55M-DS2                  | [972e4192b6](https://linux-hardware.org/?probe=972e4192b6) | Jan 17, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [842faed623](https://linux-hardware.org/?probe=842faed623) | Jan 17, 2024 |
| Lenovo        | ThinkCentre M58p 7220A72    | [9d8436f707](https://linux-hardware.org/?probe=9d8436f707) | Jan 17, 2024 |
| ASRock        | X670E Pro RS                | [08a25334a9](https://linux-hardware.org/?probe=08a25334a9) | Jan 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [6b8df5e5f8](https://linux-hardware.org/?probe=6b8df5e5f8) | Jan 16, 2024 |
| HP            | 802F                        | [891f0c3076](https://linux-hardware.org/?probe=891f0c3076) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ad209d60d3](https://linux-hardware.org/?probe=ad209d60d3) | Jan 15, 2024 |
| ECS           | H61H2-MV                    | [09c20c7740](https://linux-hardware.org/?probe=09c20c7740) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3d6f9a4f65](https://linux-hardware.org/?probe=3d6f9a4f65) | Jan 15, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b81d575e86](https://linux-hardware.org/?probe=b81d575e86) | Jan 15, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [2be91db1f9](https://linux-hardware.org/?probe=2be91db1f9) | Jan 15, 2024 |
| MSI           | PRO H610M-G DDR4            | [9dc779fa6c](https://linux-hardware.org/?probe=9dc779fa6c) | Jan 15, 2024 |
| ASUSTek       | Z97M-PLUS                   | [6565fd5500](https://linux-hardware.org/?probe=6565fd5500) | Jan 15, 2024 |
| MSI           | Z370-OC PRO                 | [4ffb04a6df](https://linux-hardware.org/?probe=4ffb04a6df) | Jan 15, 2024 |
| Dell          | 00V62H A01                  | [77fa76ca79](https://linux-hardware.org/?probe=77fa76ca79) | Jan 15, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [29d93a66fe](https://linux-hardware.org/?probe=29d93a66fe) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5ba2479207](https://linux-hardware.org/?probe=5ba2479207) | Jan 15, 2024 |
| Dell          | 0GM819                      | [b55d9b9a52](https://linux-hardware.org/?probe=b55d9b9a52) | Jan 14, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4edc08fb7](https://linux-hardware.org/?probe=c4edc08fb7) | Jan 14, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [721d114c58](https://linux-hardware.org/?probe=721d114c58) | Jan 14, 2024 |
| MSI           | A320M-A PRO                 | [0c48e7148e](https://linux-hardware.org/?probe=0c48e7148e) | Jan 14, 2024 |
| MSI           | B450M BAZOOKA V2            | [016db84158](https://linux-hardware.org/?probe=016db84158) | Jan 14, 2024 |
| AMI           | Intel                       | [8cea24270b](https://linux-hardware.org/?probe=8cea24270b) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [90337c194c](https://linux-hardware.org/?probe=90337c194c) | Jan 14, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [6443f8b7e5](https://linux-hardware.org/?probe=6443f8b7e5) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | [6be6b20963](https://linux-hardware.org/?probe=6be6b20963) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dba611325e](https://linux-hardware.org/?probe=dba611325e) | Jan 13, 2024 |
| ASUSTek       | PRIME B660M-A D4            | [cd57f74a31](https://linux-hardware.org/?probe=cd57f74a31) | Jan 13, 2024 |
| MSI           | H310M PRO-VH PLUS           | [7b76b0de4f](https://linux-hardware.org/?probe=7b76b0de4f) | Jan 13, 2024 |
| Gigabyte      | Z590 UD AC                  | [17dc5fdc19](https://linux-hardware.org/?probe=17dc5fdc19) | Jan 13, 2024 |
| MSI           | GF615M-P33                  | [7d32db9104](https://linux-hardware.org/?probe=7d32db9104) | Jan 12, 2024 |
| MSI           | H77MA-G43                   | [51882b379d](https://linux-hardware.org/?probe=51882b379d) | Jan 12, 2024 |
| Apple         | Mac-F221BEC8                | [79039b79e4](https://linux-hardware.org/?probe=79039b79e4) | Jan 12, 2024 |
| ASRock        | X670E Pro RS                | [2f899514f8](https://linux-hardware.org/?probe=2f899514f8) | Jan 12, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [b47717df63](https://linux-hardware.org/?probe=b47717df63) | Jan 12, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [c8b80fe147](https://linux-hardware.org/?probe=c8b80fe147) | Jan 12, 2024 |
| ASRock        | Z370 IB-R                   | [60d0873a83](https://linux-hardware.org/?probe=60d0873a83) | Jan 11, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6f2ff7e922](https://linux-hardware.org/?probe=6f2ff7e922) | Jan 11, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [537c95bdae](https://linux-hardware.org/?probe=537c95bdae) | Jan 11, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [2e480c8e36](https://linux-hardware.org/?probe=2e480c8e36) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0b4b01f1aa](https://linux-hardware.org/?probe=0b4b01f1aa) | Jan 11, 2024 |
| ASUSTek       | PRIME B450M-A               | [4bfba10e3f](https://linux-hardware.org/?probe=4bfba10e3f) | Jan 11, 2024 |
| ASUSTek       | H81M-A/BR                   | [9d4a2ac12b](https://linux-hardware.org/?probe=9d4a2ac12b) | Jan 11, 2024 |
| HP            | 8459                        | [1d15c6aed7](https://linux-hardware.org/?probe=1d15c6aed7) | Jan 10, 2024 |
| HP            | 8618                        | [0abc5ffc81](https://linux-hardware.org/?probe=0abc5ffc81) | Jan 10, 2024 |
| MSI           | H310M PRO-VH PLUS           | [8431e0e3d7](https://linux-hardware.org/?probe=8431e0e3d7) | Jan 10, 2024 |
| Dell          | OptiPlex 5050               | [ad6a14b4dc](https://linux-hardware.org/?probe=ad6a14b4dc) | Jan 10, 2024 |
| Gigabyte      | J1900M-D2P                  | [b48b4a8698](https://linux-hardware.org/?probe=b48b4a8698) | Jan 10, 2024 |
| Dell          | 0XC7MM A01                  | [d2cc3e306e](https://linux-hardware.org/?probe=d2cc3e306e) | Jan 10, 2024 |
| MSI           | PRO B650M-A WIFI            | [245ccd0eb9](https://linux-hardware.org/?probe=245ccd0eb9) | Jan 09, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8a25bf8215](https://linux-hardware.org/?probe=8a25bf8215) | Jan 09, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [ad3bd18e36](https://linux-hardware.org/?probe=ad3bd18e36) | Jan 09, 2024 |
| Shenzhen M... | F7BRC                       | [f40f768b40](https://linux-hardware.org/?probe=f40f768b40) | Jan 09, 2024 |
| Intel         | B75                         | [cc1767546e](https://linux-hardware.org/?probe=cc1767546e) | Jan 09, 2024 |
| ASUSTek       | PRIME B550M-A               | [9f2c754db2](https://linux-hardware.org/?probe=9f2c754db2) | Jan 08, 2024 |
| ASUSTek       | H81M-E                      | [4fc71cdf2e](https://linux-hardware.org/?probe=4fc71cdf2e) | Jan 08, 2024 |
| HP            | 8906 SMVB                   | [fd4b6e8840](https://linux-hardware.org/?probe=fd4b6e8840) | Jan 08, 2024 |
| ASUSTek       | X99-DELUXE II               | [8362692262](https://linux-hardware.org/?probe=8362692262) | Jan 08, 2024 |
| GEEKOM        | A5                          | [a46bf9499e](https://linux-hardware.org/?probe=a46bf9499e) | Jan 07, 2024 |
| Biostar       | A68MHE                      | [ed7007dc1f](https://linux-hardware.org/?probe=ed7007dc1f) | Jan 07, 2024 |
| Gigabyte      | B650 GAMING X               | [33c147e1f3](https://linux-hardware.org/?probe=33c147e1f3) | Jan 07, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [46a12dff06](https://linux-hardware.org/?probe=46a12dff06) | Jan 07, 2024 |
| MSI           | A320M PRO-VH PLUS           | [3ff7f414fe](https://linux-hardware.org/?probe=3ff7f414fe) | Jan 07, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [96907e78c1](https://linux-hardware.org/?probe=96907e78c1) | Jan 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [d7bd0a9659](https://linux-hardware.org/?probe=d7bd0a9659) | Jan 07, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [a642b9a382](https://linux-hardware.org/?probe=a642b9a382) | Jan 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [c1203b6f85](https://linux-hardware.org/?probe=c1203b6f85) | Jan 06, 2024 |
| AMD           | A520                        | [844129c6ba](https://linux-hardware.org/?probe=844129c6ba) | Jan 06, 2024 |
| Intel         | B75                         | [b2190f0cff](https://linux-hardware.org/?probe=b2190f0cff) | Jan 06, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [41582699c7](https://linux-hardware.org/?probe=41582699c7) | Jan 06, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [dda07da31a](https://linux-hardware.org/?probe=dda07da31a) | Jan 06, 2024 |
| Gigabyte      | GA-870A-UD3                 | [d273ae013f](https://linux-hardware.org/?probe=d273ae013f) | Jan 06, 2024 |
| AMD           | A520                        | [ab02db5a08](https://linux-hardware.org/?probe=ab02db5a08) | Jan 06, 2024 |
| Gigabyte      | G41MT-D3                    | [a78a3d75b9](https://linux-hardware.org/?probe=a78a3d75b9) | Jan 06, 2024 |
| Foxconn       | 2ABF                        | [d7443c3161](https://linux-hardware.org/?probe=d7443c3161) | Jan 05, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_39/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 6.5.6-300.fc39.x86_64        | 115      | 10.21%  |
| 6.7.9-200.fc39.x86_64        | 86       | 7.64%   |
| 6.6.9-200.fc39.x86_64        | 64       | 5.68%   |
| 6.7.4-200.fc39.x86_64        | 59       | 5.24%   |
| 6.6.8-200.fc39.x86_64        | 49       | 4.35%   |
| 6.5.11-300.fc39.x86_64       | 49       | 4.35%   |
| 6.7.7-200.fc39.x86_64        | 40       | 3.55%   |
| 6.6.11-200.fc39.x86_64       | 36       | 3.2%    |
| 6.6.13-200.fc39.x86_64       | 35       | 3.11%   |
| 6.5.12-300.fc39.x86_64       | 35       | 3.11%   |
| 6.6.2-201.fc39.x86_64        | 34       | 3.02%   |
| 6.6.7-200.fc39.x86_64        | 32       | 2.84%   |
| 6.7.10-200.fc39.x86_64       | 30       | 2.66%   |
| 6.8.6-200.fc39.x86_64        | 28       | 2.49%   |
| 6.8.4-200.fc39.x86_64        | 28       | 2.49%   |
| 6.7.5-200.fc39.x86_64        | 28       | 2.49%   |
| 6.7.11-200.fc39.x86_64       | 28       | 2.49%   |
| 6.6.6-200.fc39.x86_64        | 28       | 2.49%   |
| 6.6.4-200.fc39.x86_64        | 28       | 2.49%   |
| 6.7.3-200.fc39.x86_64        | 27       | 2.4%    |
| 6.7.6-200.fc39.x86_64        | 23       | 2.04%   |
| 6.8.5-201.fc39.x86_64        | 22       | 1.95%   |
| 6.6.12-200.fc39.x86_64       | 21       | 1.87%   |
| 6.6.14-200.fc39.x86_64       | 19       | 1.69%   |
| 6.8.7-200.fc39.x86_64        | 16       | 1.42%   |
| 6.5.10-300.fc39.x86_64       | 14       | 1.24%   |
| 6.8.11-200.fc39.x86_64       | 13       | 1.15%   |
| 6.11.9-100.fc39.x86_64       | 11       | 0.98%   |
| 6.8.9-200.fc39.x86_64        | 9        | 0.8%    |
| 6.6.3-200.fc39.x86_64        | 9        | 0.8%    |
| 6.7.9-207.fsync.fc39.x86_64  | 6        | 0.53%   |
| 6.7.9-204.fsync.fc39.x86_64  | 6        | 0.53%   |
| 6.5.9-300.fc39.x86_64        | 6        | 0.53%   |
| 6.5.5-300.fc39.x86_64        | 6        | 0.53%   |
| 6.8.10-200.fc39.x86_64       | 5        | 0.44%   |
| 6.9.7-100.fc39.x86_64        | 4        | 0.36%   |
| 6.6.12-201.fsync.fc39.x86_64 | 4        | 0.36%   |
| 6.9.4-100.fc39.x86_64        | 3        | 0.27%   |
| 6.9.12-100.fc39.x86_64       | 3        | 0.27%   |
| 6.11.5-100.fc39.x86_64       | 3        | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5.6   | 115      | 10.21%  |
| 6.7.9   | 100      | 8.88%   |
| 6.6.9   | 64       | 5.68%   |
| 6.7.4   | 59       | 5.24%   |
| 6.6.8   | 49       | 4.35%   |
| 6.5.11  | 49       | 4.35%   |
| 6.7.7   | 41       | 3.64%   |
| 6.6.13  | 36       | 3.2%    |
| 6.6.11  | 36       | 3.2%    |
| 6.5.12  | 35       | 3.11%   |
| 6.6.2   | 34       | 3.02%   |
| 6.6.7   | 33       | 2.93%   |
| 6.7.10  | 30       | 2.66%   |
| 6.8.4   | 29       | 2.58%   |
| 6.7.5   | 29       | 2.58%   |
| 6.6.6   | 29       | 2.58%   |
| 6.8.6   | 28       | 2.49%   |
| 6.7.3   | 28       | 2.49%   |
| 6.7.11  | 28       | 2.49%   |
| 6.6.4   | 28       | 2.49%   |
| 6.6.12  | 25       | 2.22%   |
| 6.7.6   | 24       | 2.13%   |
| 6.8.5   | 22       | 1.95%   |
| 6.6.14  | 20       | 1.78%   |
| 6.5.10  | 17       | 1.51%   |
| 6.8.7   | 16       | 1.42%   |
| 6.8.11  | 13       | 1.15%   |
| 6.11.9  | 11       | 0.98%   |
| 6.8.9   | 9        | 0.8%    |
| 6.6.3   | 9        | 0.8%    |
| 6.5.9   | 6        | 0.53%   |
| 6.5.5   | 6        | 0.53%   |
| 6.9.7   | 5        | 0.44%   |
| 6.8.10  | 5        | 0.44%   |
| 6.5.0   | 4        | 0.36%   |
| 6.9.4   | 3        | 0.27%   |
| 6.9.12  | 3        | 0.27%   |
| 6.7.0   | 3        | 0.27%   |
| 6.4.0   | 3        | 0.27%   |
| 6.11.5  | 3        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 334      | 31.16%  |
| 6.7     | 328      | 30.6%   |
| 6.5     | 239      | 22.29%  |
| 6.8     | 122      | 11.38%  |
| 6.11    | 17       | 1.59%   |
| 6.9     | 16       | 1.49%   |
| 6.10    | 9        | 0.84%   |
| 6.4     | 5        | 0.47%   |
| 6.3     | 1        | 0.09%   |
| 6.2     | 1        | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 991      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 721      | 72.54%  |
| KDE5            | 165      | 16.6%   |
| X-Cinnamon      | 19       | 1.91%   |
| Cinnamon        | 18       | 1.81%   |
| Unknown         | 17       | 1.71%   |
| XFCE            | 13       | 1.31%   |
| Budgie          | 12       | 1.21%   |
| GNOME Classic   | 8        | 0.8%    |
| MATE            | 6        | 0.6%    |
| KDE6            | 3        | 0.3%    |
| KDE             | 2        | 0.2%    |
| Hyprland        | 2        | 0.2%    |
| WindowMaker     | 1        | 0.1%    |
| sway            | 1        | 0.1%    |
| LXQt            | 1        | 0.1%    |
| i3              | 1        | 0.1%    |
| GNOME-Classic   | 1        | 0.1%    |
| GNOME Flashback | 1        | 0.1%    |
| Deepin          | 1        | 0.1%    |
| bspwm           | 1        | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 730      | 72.42%  |
| X11     | 239      | 23.71%  |
| Tty     | 32       | 3.17%   |
| Unknown | 7        | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 692      | 69.62%  |
| GDM     | 179      | 18.01%  |
| SDDM    | 75       | 7.55%   |
| LightDM | 48       | 4.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 479      | 48.19%  |
| en_GB | 68       | 6.84%   |
| pt_BR | 65       | 6.54%   |
| ru_RU | 64       | 6.44%   |
| de_DE | 44       | 4.43%   |
| en_AU | 41       | 4.12%   |
| fr_FR | 30       | 3.02%   |
| en_CA | 24       | 2.41%   |
| it_IT | 21       | 2.11%   |
| es_MX | 16       | 1.61%   |
| es_ES | 16       | 1.61%   |
| pl_PL | 14       | 1.41%   |
| cs_CZ | 13       | 1.31%   |
| de_AT | 9        | 0.91%   |
| hu_HU | 7        | 0.7%    |
| zh_CN | 6        | 0.6%    |
| nl_NL | 6        | 0.6%    |
| en_NZ | 6        | 0.6%    |
| tr_TR | 5        | 0.5%    |
| fr_CA | 5        | 0.5%    |
| fr_BE | 5        | 0.5%    |
| pt_PT | 4        | 0.4%    |
| ko_KR | 4        | 0.4%    |
| es_AR | 4        | 0.4%    |
| ja_JP | 3        | 0.3%    |
| en_IN | 3        | 0.3%    |
| en_IE | 3        | 0.3%    |
| en_DK | 3        | 0.3%    |
| sv_SE | 2        | 0.2%    |
| sr_RS | 2        | 0.2%    |
| en_BW | 2        | 0.2%    |
| zh_SG | 1        | 0.1%    |
| zh_HK | 1        | 0.1%    |
| ro_RO | 1        | 0.1%    |
| nl_BE | 1        | 0.1%    |
| nb_NO | 1        | 0.1%    |
| lv_LV | 1        | 0.1%    |
| hr_HR | 1        | 0.1%    |
| he_IL | 1        | 0.1%    |
| fr_CH | 1        | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 534      | 52.51%  |
| EFI  | 483      | 47.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 807      | 81.02%  |
| Ext4    | 150      | 15.06%  |
| Xfs     | 29       | 2.91%   |
| Tmpfs   | 6        | 0.6%    |
| Overlay | 2        | 0.2%    |
| XXXXX   | 1        | 0.1%    |
| Unknown | 1        | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 675      | 67.84%  |
| GPT     | 297      | 29.85%  |
| MBR     | 23       | 2.31%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 907      | 91.06%  |
| Yes       | 89       | 8.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 841      | 84.78%  |
| Yes       | 151      | 15.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 294      | 29.67%  |
| MSI                                  | 161      | 16.25%  |
| Gigabyte Technology                  | 158      | 15.94%  |
| ASRock                               | 93       | 9.38%   |
| Dell                                 | 72       | 7.27%   |
| Hewlett-Packard                      | 60       | 6.05%   |
| Lenovo                               | 26       | 2.62%   |
| Intel                                | 21       | 2.12%   |
| Apple                                | 12       | 1.21%   |
| Pegatron                             | 9        | 0.91%   |
| Fujitsu                              | 9        | 0.91%   |
| Biostar                              | 6        | 0.61%   |
| Acer                                 | 6        | 0.61%   |
| Unknown                              | 6        | 0.61%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.5%    |
| Foxconn                              | 5        | 0.5%    |
| BESSTAR Tech                         | 4        | 0.4%    |
| AZW                                  | 4        | 0.4%    |
| Huanan                               | 3        | 0.3%    |
| GEEKOM                               | 3        | 0.3%    |
| AMI                                  | 3        | 0.3%    |
| Alienware                            | 3        | 0.3%    |
| OEM                                  | 2        | 0.2%    |
| EVGA                                 | 2        | 0.2%    |
| Colorful Technology                  | 2        | 0.2%    |
| ZOTAC                                | 1        | 0.1%    |
| SZQFTX                               | 1        | 0.1%    |
| System76                             | 1        | 0.1%    |
| Positivo                             | 1        | 0.1%    |
| PCWare                               | 1        | 0.1%    |
| NZXT                                 | 1        | 0.1%    |
| NCR                                  | 1        | 0.1%    |
| MAXSUN                               | 1        | 0.1%    |
| MACHINIST                            | 1        | 0.1%    |
| LattePanda                           | 1        | 0.1%    |
| Itautec                              | 1        | 0.1%    |
| Google                               | 1        | 0.1%    |
| GALAX                                | 1        | 0.1%    |
| Erying                               | 1        | 0.1%    |
| eMachines                            | 1        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 16       | 1.61%   |
| MSI MS-7C95                        | 8        | 0.81%   |
| MSI MS-7C37                        | 7        | 0.71%   |
| ASUS ROG STRIX B550-F GAMING       | 7        | 0.71%   |
| Apple MacPro5,1                    | 7        | 0.71%   |
| MSI MS-7B89                        | 6        | 0.61%   |
| ASUS TUF Gaming X570-PLUS          | 6        | 0.61%   |
| ASUS ROG STRIX X570-E GAMING       | 6        | 0.61%   |
| ASUS PRIME A320M-K                 | 6        | 0.61%   |
| Unknown                            | 6        | 0.61%   |
| MSI MS-7C56                        | 5        | 0.5%    |
| MSI MS-7C02                        | 5        | 0.5%    |
| MSI MS-7B86                        | 5        | 0.5%    |
| Intel X99                          | 5        | 0.5%    |
| Gigabyte X570 I AORUS PRO WIFI     | 5        | 0.5%    |
| Dell OptiPlex 9020                 | 5        | 0.5%    |
| ASUS TUF Gaming X570-PRO           | 5        | 0.5%    |
| ASUS TUF Gaming B550-PLUS          | 5        | 0.5%    |
| MSI MS-7D78                        | 4        | 0.4%    |
| MSI MS-7D54                        | 4        | 0.4%    |
| MSI MS-7C91                        | 4        | 0.4%    |
| MSI MS-7A38                        | 4        | 0.4%    |
| Gigabyte B550 AORUS ELITE V2       | 4        | 0.4%    |
| Gigabyte 970A-DS3P                 | 4        | 0.4%    |
| Dell Precision Tower 5810          | 4        | 0.4%    |
| Dell OptiPlex 7010                 | 4        | 0.4%    |
| ASUS ROG STRIX X670E-E GAMING WIFI | 4        | 0.4%    |
| ASUS PRIME X570-PRO                | 4        | 0.4%    |
| ASUS PRIME B550-PLUS               | 4        | 0.4%    |
| ASUS PRIME B450M-A II              | 4        | 0.4%    |
| ASRock B550M Pro4                  | 4        | 0.4%    |
| Apple MacPro6,1                    | 4        | 0.4%    |
| MSI MS-7D76                        | 3        | 0.3%    |
| MSI MS-7D75                        | 3        | 0.3%    |
| MSI MS-7D43                        | 3        | 0.3%    |
| MSI MS-7D25                        | 3        | 0.3%    |
| MSI MS-7C84                        | 3        | 0.3%    |
| MSI MS-7B79                        | 3        | 0.3%    |
| MSI MS-7885                        | 3        | 0.3%    |
| MSI MS-7641                        | 3        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 82       | 8.27%   |
| ASUS ROG            | 66       | 6.66%   |
| ASUS TUF            | 47       | 4.74%   |
| Dell OptiPlex       | 40       | 4.04%   |
| ASUS All            | 16       | 1.61%   |
| HP EliteDesk        | 15       | 1.51%   |
| Gigabyte X570       | 15       | 1.51%   |
| Dell Precision      | 13       | 1.31%   |
| Gigabyte B550M      | 11       | 1.11%   |
| Gigabyte B550       | 11       | 1.11%   |
| Lenovo ThinkStation | 10       | 1.01%   |
| Lenovo ThinkCentre  | 10       | 1.01%   |
| Gigabyte B450M      | 9        | 0.91%   |
| MSI MS-7C95         | 8        | 0.81%   |
| HP Compaq           | 8        | 0.81%   |
| MSI MS-7C37         | 7        | 0.71%   |
| HP ProDesk          | 7        | 0.71%   |
| Gigabyte B650       | 7        | 0.71%   |
| Fujitsu ESPRIMO     | 7        | 0.71%   |
| ASRock B550         | 7        | 0.71%   |
| Apple MacPro5       | 7        | 0.71%   |
| MSI MS-7B89         | 6        | 0.61%   |
| Intel X99           | 6        | 0.61%   |
| Dell XPS            | 6        | 0.61%   |
| Dell Inspiron       | 6        | 0.61%   |
| ASUS Pro            | 6        | 0.61%   |
| ASRock X570         | 6        | 0.61%   |
| Unknown             | 6        | 0.61%   |
| MSI MS-7C56         | 5        | 0.5%    |
| MSI MS-7C02         | 5        | 0.5%    |
| MSI MS-7B86         | 5        | 0.5%    |
| HP Pavilion         | 5        | 0.5%    |
| ASUS Maximus        | 5        | 0.5%    |
| ASRock B450M        | 5        | 0.5%    |
| MSI MS-7D78         | 4        | 0.4%    |
| MSI MS-7D54         | 4        | 0.4%    |
| MSI MS-7C91         | 4        | 0.4%    |
| MSI MS-7A38         | 4        | 0.4%    |
| Gigabyte B650M      | 4        | 0.4%    |
| Gigabyte B450       | 4        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 125      | 12.61%  |
| 2022 | 124      | 12.51%  |
| 2019 | 91       | 9.18%   |
| 2021 | 85       | 8.58%   |
| 2018 | 84       | 8.48%   |
| 2023 | 73       | 7.37%   |
| 2017 | 59       | 5.95%   |
| 2012 | 50       | 5.05%   |
| 2013 | 48       | 4.84%   |
| 2014 | 45       | 4.54%   |
| 2015 | 41       | 4.14%   |
| 2010 | 38       | 3.83%   |
| 2011 | 33       | 3.33%   |
| 2016 | 30       | 3.03%   |
| 2009 | 23       | 2.32%   |
| 2008 | 18       | 1.82%   |
| 2007 | 10       | 1.01%   |
| 2024 | 8        | 0.81%   |
| 2006 | 4        | 0.4%    |
| 2005 | 2        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 991      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 905      | 91.05%  |
| Enabled  | 89       | 8.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 989      | 99.8%   |
| Yes  | 2        | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 289      | 28.81%  |
| 16.01-24.0      | 249      | 24.83%  |
| 8.01-16.0       | 129      | 12.86%  |
| 64.01-256.0     | 125      | 12.46%  |
| 4.01-8.0        | 95       | 9.47%   |
| 24.01-32.0      | 69       | 6.88%   |
| 3.01-4.0        | 36       | 3.59%   |
| 1.01-2.0        | 7        | 0.7%    |
| More than 256.0 | 2        | 0.2%    |
| 2.01-3.0        | 2        | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 341      | 31.81%  |
| 2.01-3.0    | 237      | 22.11%  |
| 3.01-4.0    | 228      | 21.27%  |
| 1.01-2.0    | 105      | 9.79%   |
| 8.01-16.0   | 100      | 9.33%   |
| 16.01-24.0  | 30       | 2.8%    |
| 0.51-1.0    | 21       | 1.96%   |
| 24.01-32.0  | 5        | 0.47%   |
| 32.01-64.0  | 4        | 0.37%   |
| 64.01-256.0 | 1        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 317      | 31.2%   |
| 2      | 276      | 27.17%  |
| 3      | 220      | 21.65%  |
| 4      | 99       | 9.74%   |
| 5      | 55       | 5.41%   |
| 6      | 27       | 2.66%   |
| 8      | 9        | 0.89%   |
| 7      | 6        | 0.59%   |
| 9      | 3        | 0.3%    |
| 12     | 2        | 0.2%    |
| 11     | 1        | 0.1%    |
| 10     | 1        | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 724      | 72.62%  |
| Yes       | 273      | 27.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 978      | 98.69%  |
| No        | 13       | 1.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 567      | 56.76%  |
| No        | 432      | 43.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 540      | 54.16%  |
| No        | 457      | 45.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 250      | 25.18%  |
| Brazil      | 80       | 8.06%   |
| Russia      | 65       | 6.55%   |
| Germany     | 64       | 6.45%   |
| UK          | 44       | 4.43%   |
| Australia   | 44       | 4.43%   |
| France      | 40       | 4.03%   |
| Canada      | 37       | 3.73%   |
| Italy       | 31       | 3.12%   |
| Netherlands | 22       | 2.22%   |
| Poland      | 21       | 2.11%   |
| Mexico      | 21       | 2.11%   |
| Spain       | 20       | 2.01%   |
| Czechia     | 19       | 1.91%   |
| Austria     | 14       | 1.41%   |
| Sweden      | 13       | 1.31%   |
| Belgium     | 13       | 1.31%   |
| Portugal    | 12       | 1.21%   |
| Argentina   | 12       | 1.21%   |
| Hungary     | 11       | 1.11%   |
| Turkey      | 10       | 1.01%   |
| Switzerland | 10       | 1.01%   |
| Romania     | 8        | 0.81%   |
| Egypt       | 8        | 0.81%   |
| Norway      | 7        | 0.7%    |
| New Zealand | 7        | 0.7%    |
| India       | 7        | 0.7%    |
| Finland     | 7        | 0.7%    |
| Bulgaria    | 7        | 0.7%    |
| Taiwan      | 5        | 0.5%    |
| Colombia    | 5        | 0.5%    |
| China       | 5        | 0.5%    |
| Thailand    | 4        | 0.4%    |
| South Korea | 4        | 0.4%    |
| Kazakhstan  | 4        | 0.4%    |
| Japan       | 4        | 0.4%    |
| Belarus     | 4        | 0.4%    |
| Serbia      | 3        | 0.3%    |
| Puerto Rico | 3        | 0.3%    |
| Malaysia    | 3        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 22       | 2.19%   |
| Moscow         | 15       | 1.49%   |
| Seattle        | 9        | 0.9%    |
| Warsaw         | 7        | 0.7%    |
| Sao Paulo      | 7        | 0.7%    |
| Rio de Janeiro | 7        | 0.7%    |
| Prague         | 7        | 0.7%    |
| Brisbane       | 7        | 0.7%    |
| Berlin         | 7        | 0.7%    |
| St Petersburg  | 6        | 0.6%    |
| Mexico City    | 6        | 0.6%    |
| Melbourne      | 6        | 0.6%    |
| Vienna         | 5        | 0.5%    |
| Chicago        | 5        | 0.5%    |
| Ankara         | 5        | 0.5%    |
| Alexandria     | 5        | 0.5%    |
| Toronto        | 4        | 0.4%    |
| Scarborough    | 4        | 0.4%    |
| Rome           | 4        | 0.4%    |
| Porto Alegre   | 4        | 0.4%    |
| Palmas         | 4        | 0.4%    |
| Charlotte      | 4        | 0.4%    |
| Brussels       | 4        | 0.4%    |
| Austin         | 4        | 0.4%    |
| Auckland       | 4        | 0.4%    |
| Yekaterinburg  | 3        | 0.3%    |
| Yaroslavl      | 3        | 0.3%    |
| Valencia       | 3        | 0.3%    |
| Timișoara     | 3        | 0.3%    |
| Taipei         | 3        | 0.3%    |
| Stuttgart      | 3        | 0.3%    |
| Sofia          | 3        | 0.3%    |
| Roswell        | 3        | 0.3%    |
| Riga           | 3        | 0.3%    |
| Reading        | 3        | 0.3%    |
| Perth          | 3        | 0.3%    |
| Paris          | 3        | 0.3%    |
| Montreal       | 3        | 0.3%    |
| Minsk          | 3        | 0.3%    |
| Milano         | 3        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 341      | 600    | 17.13%  |
| WDC                          | 278      | 468    | 13.96%  |
| Seagate                      | 254      | 392    | 12.76%  |
| Sandisk                      | 138      | 179    | 6.93%   |
| Kingston                     | 121      | 167    | 6.08%   |
| Crucial                      | 89       | 117    | 4.47%   |
| Toshiba                      | 74       | 95     | 3.72%   |
| Micron/Crucial Technology    | 61       | 83     | 3.06%   |
| Phison Electronics           | 55       | 71     | 2.76%   |
| Intel                        | 52       | 70     | 2.61%   |
| Hitachi                      | 38       | 47     | 1.91%   |
| MAXIO Technology (Hangzhou)  | 36       | 40     | 1.81%   |
| SK hynix                     | 31       | 35     | 1.56%   |
| ADATA Technology             | 30       | 40     | 1.51%   |
| Kingston Technology Company  | 24       | 27     | 1.21%   |
| China                        | 24       | 33     | 1.21%   |
| Silicon Motion               | 22       | 34     | 1.1%    |
| HGST                         | 21       | 32     | 1.05%   |
| A-DATA Technology            | 21       | 24     | 1.05%   |
| Micron Technology            | 17       | 21     | 0.85%   |
| Realtek Semiconductor        | 14       | 16     | 0.7%    |
| Unknown                      | 13       | 18     | 0.65%   |
| SPCC                         | 12       | 15     | 0.6%    |
| Intenso                      | 11       | 12     | 0.55%   |
| PNY                          | 10       | 12     | 0.5%    |
| Patriot                      | 10       | 15     | 0.5%    |
| Shenzhen Longsys Electronics | 9        | 14     | 0.45%   |
| Apacer                       | 9        | 12     | 0.45%   |
| Team                         | 8        | 10     | 0.4%    |
| Unknown                      | 8        | 10     | 0.4%    |
| OCZ                          | 7        | 8      | 0.35%   |
| Netac                        | 7        | 10     | 0.35%   |
| JMicron Technology           | 7        | 7      | 0.35%   |
| Fanxiang                     | 7        | 10     | 0.35%   |
| Transcend                    | 5        | 6      | 0.25%   |
| Maxtor                       | 5        | 6      | 0.25%   |
| KIOXIA                       | 5        | 6      | 0.25%   |
| KingSpec                     | 5        | 6      | 0.25%   |
| GOODRAM                      | 5        | 7      | 0.25%   |
| Apple                        | 5        | 5      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 103      | 4.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 53       | 2.28%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                                | 41       | 1.77%   |
| Kingston SA400S37480G 480GB SSD                                    | 29       | 1.25%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB                   | 25       | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 24       | 1.03%   |
| Samsung SSD 860 EVO 500GB                                          | 23       | 0.99%   |
| Phison E12 NVMe Controller 1TB                                     | 23       | 0.99%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 21       | 0.9%    |
| Samsung SSD 860 EVO 1TB                                            | 21       | 0.9%    |
| Samsung SSD 850 EVO 250GB                                          | 20       | 0.86%   |
| Kingston SA400S37240G 240GB SSD                                    | 20       | 0.86%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 19       | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB              | 17       | 0.73%   |
| Seagate ST500DM002-1BD142 500GB                                    | 16       | 0.69%   |
| Samsung SSD 980 1TB                                                | 16       | 0.69%   |
| Samsung SSD 850 EVO 500GB                                          | 16       | 0.69%   |
| Intel SSD 660P Series 512GB                                        | 16       | 0.69%   |
| Toshiba DT01ACA100 1TB                                             | 15       | 0.65%   |
| Samsung SSD 990 PRO 2TB                                            | 14       | 0.6%    |
| Kingston Company SNV2S1000G 1TB                                    | 14       | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                                        | 14       | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB               | 13       | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                                     | 12       | 0.52%   |
| Seagate ST2000DM008-2UB102 2TB                                     | 12       | 0.52%   |
| Samsung SSD 870 QVO 1TB                                            | 12       | 0.52%   |
| Samsung SSD 870 EVO 1TB                                            | 12       | 0.52%   |
| Phison E16 PCIe4 NVMe Controller 1TB                               | 12       | 0.52%   |
| Kingston SA400S37120G 120GB SSD                                    | 12       | 0.52%   |
| Crucial CT500MX500SSD1 500GB                                       | 12       | 0.52%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 12       | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 11       | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                                     | 11       | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB                                       | 10       | 0.43%   |
| Sandisk WD_BLACK SN850X 1000GB                                     | 10       | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB                   | 10       | 0.43%   |
| Crucial CT480BX500SSD1 480GB                                       | 10       | 0.43%   |
| Toshiba HDWD110 1TB                                                | 9        | 0.39%   |
| Samsung SSD 980 500GB                                              | 9        | 0.39%   |
| Samsung SSD 860 EVO 250GB                                          | 9        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 250      | 383    | 37.09%  |
| WDC                 | 239      | 403    | 35.46%  |
| Toshiba             | 63       | 83     | 9.35%   |
| Hitachi             | 38       | 47     | 5.64%   |
| Samsung Electronics | 26       | 41     | 3.86%   |
| HGST                | 20       | 31     | 2.97%   |
| JMicron Technology  | 6        | 6      | 0.89%   |
| Unknown             | 5        | 5      | 0.74%   |
| Maxtor              | 4        | 5      | 0.59%   |
| External            | 4        | 7      | 0.59%   |
| USB3.0              | 2        | 2      | 0.3%    |
| Fujitsu             | 2        | 3      | 0.3%    |
| ASMT                | 2        | 6      | 0.3%    |
| USB                 | 1        | 1      | 0.15%   |
| TO Exter            | 1        | 2      | 0.15%   |
| TerraMas            | 1        | 2      | 0.15%   |
| T-FORCE             | 1        | 1      | 0.15%   |
| SAGE                | 1        | 1      | 0.15%   |
| SABRENT             | 1        | 1      | 0.15%   |
| Lenovo              | 1        | 1      | 0.15%   |
| KINGWIN             | 1        | 1      | 0.15%   |
| Intenso             | 1        | 1      | 0.15%   |
| ICY BOX             | 1        | 1      | 0.15%   |
| IB-377U3            | 1        | 1      | 0.15%   |
| FC-1307             | 1        | 1      | 0.15%   |
| Apple               | 1        | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 173      | 278    | 24.82%  |
| Kingston            | 95       | 125    | 13.63%  |
| Crucial             | 89       | 117    | 12.77%  |
| WDC                 | 53       | 65     | 7.6%    |
| SanDisk             | 44       | 54     | 6.31%   |
| China               | 24       | 33     | 3.44%   |
| Intel               | 21       | 34     | 3.01%   |
| A-DATA Technology   | 21       | 24     | 3.01%   |
| SPCC                | 11       | 14     | 1.58%   |
| SK hynix            | 11       | 12     | 1.58%   |
| PNY                 | 10       | 12     | 1.43%   |
| Patriot             | 10       | 15     | 1.43%   |
| Intenso             | 10       | 11     | 1.43%   |
| Apacer              | 9        | 12     | 1.29%   |
| Team                | 8        | 10     | 1.15%   |
| OCZ                 | 7        | 8      | 1%      |
| Toshiba             | 6        | 7      | 0.86%   |
| Micron Technology   | 6        | 8      | 0.86%   |
| Fanxiang            | 6        | 8      | 0.86%   |
| Transcend           | 5        | 6      | 0.72%   |
| KingSpec            | 5        | 6      | 0.72%   |
| GOODRAM             | 5        | 7      | 0.72%   |
| Unknown             | 5        | 7      | 0.72%   |
| Smartbuy            | 4        | 5      | 0.57%   |
| Netac               | 4        | 5      | 0.57%   |
| Corsair             | 4        | 5      | 0.57%   |
| Apple               | 4        | 4      | 0.57%   |
| Hewlett-Packard     | 3        | 4      | 0.43%   |
| Seagate             | 2        | 2      | 0.29%   |
| Mushkin             | 2        | 2      | 0.29%   |
| Lexar               | 2        | 4      | 0.29%   |
| Emtec               | 2        | 2      | 0.29%   |
| Acer                | 2        | 2      | 0.29%   |
| XrayDisk            | 1        | 1      | 0.14%   |
| V7                  | 1        | 1      | 0.14%   |
| TECH                | 1        | 1      | 0.14%   |
| T-FORCE             | 1        | 1      | 0.14%   |
| sobetter            | 1        | 1      | 0.14%   |
| SD                  | 1        | 2      | 0.14%   |
| SABRENT             | 1        | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 566      | 887    | 33.67%  |
| SSD     | 554      | 948    | 32.96%  |
| HDD     | 533      | 1037   | 31.71%  |
| Unknown | 27       | 35     | 1.61%   |
| MMC     | 1        | 1      | 0.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 777      | 1919   | 54.99%  |
| NVMe | 563      | 880    | 39.84%  |
| SAS  | 72       | 108    | 5.1%    |
| MMC  | 1        | 1      | 0.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 503      | 901    | 41.64%  |
| 0.51-1.0   | 365      | 549    | 30.22%  |
| 1.01-2.0   | 168      | 241    | 13.91%  |
| 3.01-4.0   | 79       | 120    | 6.54%   |
| 4.01-10.0  | 53       | 111    | 4.39%   |
| 2.01-3.0   | 25       | 37     | 2.07%   |
| 10.01-20.0 | 13       | 24     | 1.08%   |
| 20.01-50.0 | 2        | 2      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 236      | 23.02%  |
| More than 3000 | 196      | 19.12%  |
| 501-1000       | 188      | 18.34%  |
| 251-500        | 119      | 11.61%  |
| 101-250        | 84       | 8.2%    |
| 2001-3000      | 72       | 7.02%   |
| Unknown        | 53       | 5.17%   |
| 1-20           | 37       | 3.61%   |
| 51-100         | 30       | 2.93%   |
| 21-50          | 10       | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 226      | 21.67%  |
| 21-50          | 165      | 15.82%  |
| 101-250        | 128      | 12.27%  |
| 51-100         | 111      | 10.64%  |
| 251-500        | 93       | 8.92%   |
| 501-1000       | 83       | 7.96%   |
| 1001-2000      | 82       | 7.86%   |
| More than 3000 | 66       | 6.33%   |
| Unknown        | 53       | 5.08%   |
| 2001-3000      | 36       | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                                      | 3        | 3      | 4.48%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 4      | 4.48%   |
| Seagate ST2000DM001-1ER164 2TB                                | 2        | 2      | 2.99%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB     | 2        | 2      | 2.99%   |
| Intel SSDSC2CT120A3 120GB                                     | 2        | 8      | 2.99%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                              | 1        | 1      | 1.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                              | 1        | 1      | 1.49%   |
| WDC WD7500BPKX-00HPJT0 752GB                                  | 1        | 1      | 1.49%   |
| WDC WD6400AAKS-65A7B2 640GB                                   | 1        | 1      | 1.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                                  | 1        | 1      | 1.49%   |
| WDC WD5000AVDS-63U7B1 500GB                                   | 1        | 2      | 1.49%   |
| WDC WD5000AVCS-632DY1 500GB                                   | 1        | 3      | 1.49%   |
| WDC WD5000AAKX-00ERMA0 500GB                                  | 1        | 2      | 1.49%   |
| WDC WD5000AAKS-00UU3A0 500GB                                  | 1        | 1      | 1.49%   |
| WDC WD40EFRX-68WT0N0 4TB                                      | 1        | 1      | 1.49%   |
| WDC WD3200AAKS-22B3A0 320GB                                   | 1        | 1      | 1.49%   |
| WDC WD30EZRX-00SPEB0 3TB                                      | 1        | 1      | 1.49%   |
| WDC WD30 EZRX-00SPEB0 3TB                                     | 1        | 1      | 1.49%   |
| WDC WD20EADS-00S2B0 2TB                                       | 1        | 1      | 1.49%   |
| WDC WD2003FZEX-00SRLA0 2TB                                    | 1        | 1      | 1.49%   |
| WDC WD20 EZRX-00D8PB0 2TB                                     | 1        | 1      | 1.49%   |
| WDC WD1600AVVS-63L2B0 160GB                                   | 1        | 1      | 1.49%   |
| WDC WD15EARS-00MVWB0 1TB                                      | 1        | 1      | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB                                      | 1        | 1      | 1.49%   |
| WDC WD10EARS-22Y5B1 1TB                                       | 1        | 1      | 1.49%   |
| WDC WD10EADS-11M2B2 1TB                                       | 1        | 1      | 1.49%   |
| WDC WD10EADS-00L5B1 1TB                                       | 1        | 1      | 1.49%   |
| Toshiba MQ01ABD050 500GB                                      | 1        | 4      | 1.49%   |
| Toshiba DT01ACA100 1TB                                        | 1        | 1      | 1.49%   |
| Seagate ST500LM034-2GH17A 500GB                               | 1        | 1      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB                               | 1        | 1      | 1.49%   |
| Seagate ST5000LM000-2AN170 5TB                                | 1        | 1      | 1.49%   |
| Seagate ST4000DM000-1F2168 4TB                                | 1        | 1      | 1.49%   |
| Seagate ST3500320AS 500GB                                     | 1        | 1      | 1.49%   |
| Seagate ST31000524AS 1TB                                      | 1        | 3      | 1.49%   |
| Seagate ST31000333AS 1TB                                      | 1        | 2      | 1.49%   |
| Seagate ST2000DX002-2DV164 2TB                                | 1        | 1      | 1.49%   |
| Seagate ST1000DX001-1NS162 1TB                                | 1        | 2      | 1.49%   |
| Seagate ST1000DM003-1SB102 1TB                                | 1        | 1      | 1.49%   |
| SanDisk SSD PLUS 480GB                                        | 1        | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 22       | 29     | 34.92%  |
| Seagate               | 11       | 16     | 17.46%  |
| Samsung Electronics   | 6        | 17     | 9.52%   |
| Hitachi               | 6        | 6      | 9.52%   |
| SanDisk               | 4        | 4      | 6.35%   |
| Toshiba               | 2        | 5      | 3.17%   |
| Realtek Semiconductor | 2        | 2      | 3.17%   |
| Intel                 | 2        | 8      | 3.17%   |
| Crucial               | 2        | 5      | 3.17%   |
| Neo                   | 1        | 1      | 1.59%   |
| Mushkin               | 1        | 1      | 1.59%   |
| Micron Technology     | 1        | 1      | 1.59%   |
| Maxtor                | 1        | 2      | 1.59%   |
| Kingston              | 1        | 1      | 1.59%   |
| HGST                  | 1        | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 27     | 47.73%  |
| Seagate             | 11       | 16     | 25%     |
| Hitachi             | 6        | 6      | 13.64%  |
| Toshiba             | 2        | 5      | 4.55%   |
| Samsung Electronics | 2        | 12     | 4.55%   |
| Maxtor              | 1        | 2      | 2.27%   |
| HGST                | 1        | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 39       | 69     | 66.1%   |
| SSD  | 14       | 23     | 23.73%  |
| NVMe | 6        | 7      | 10.17%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD30 EZRS-00J99B0 3TB   | 1        | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Hitachi | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 716      | 2001   | 67.17%  |
| Works    | 294      | 805    | 27.58%  |
| Malfunc  | 54       | 99     | 5.07%   |
| Failed   | 2        | 3      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 504      | 28.69%  |
| AMD                          | 467      | 26.58%  |
| Samsung Electronics          | 206      | 11.72%  |
| SanDisk                      | 96       | 5.46%   |
| ASMedia Technology           | 75       | 4.27%   |
| Micron/Crucial Technology    | 61       | 3.47%   |
| Phison Electronics           | 56       | 3.19%   |
| Kingston Technology Company  | 55       | 3.13%   |
| MAXIO Technology (Hangzhou)  | 36       | 2.05%   |
| ADATA Technology             | 30       | 1.71%   |
| Silicon Motion               | 22       | 1.25%   |
| JMicron Technology           | 22       | 1.25%   |
| SK hynix                     | 20       | 1.14%   |
| Marvell Technology Group     | 20       | 1.14%   |
| Realtek Semiconductor        | 14       | 0.8%    |
| Micron Technology            | 11       | 0.63%   |
| Nvidia                       | 10       | 0.57%   |
| Shenzhen Longsys Electronics | 9        | 0.51%   |
| Toshiba America Info Systems | 5        | 0.28%   |
| KIOXIA                       | 5        | 0.28%   |
| Broadcom / LSI               | 5        | 0.28%   |
| Solidigm                     | 4        | 0.23%   |
| Netac Technology             | 3        | 0.17%   |
| Adaptec                      | 3        | 0.17%   |
| VIA Technologies             | 2        | 0.11%   |
| LSI Logic / Symbios Logic    | 2        | 0.11%   |
| Lite-On Technology           | 2        | 0.11%   |
| INNOGRIT                     | 2        | 0.11%   |
| Yangtze Memory Technologies  | 1        | 0.06%   |
| Union Memory (Shenzhen)      | 1        | 0.06%   |
| ULi Electronics              | 1        | 0.06%   |
| TenaFe                       | 1        | 0.06%   |
| Silicon Image                | 1        | 0.06%   |
| Promise Technology           | 1        | 0.06%   |
| OCZ Technology Group         | 1        | 0.06%   |
| HighPoint Technologies       | 1        | 0.06%   |
| HGST                         | 1        | 0.06%   |
| Biwin Storage Technology     | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 182      | 8.89%   |
| AMD 500 Series Chipset SATA Controller                                         | 110      | 5.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 103      | 5.03%   |
| AMD 600 Series Chipset SATA Controller                                         | 83       | 4.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 79       | 3.86%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 64       | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52       | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 51       | 2.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 49       | 2.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 41       | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 40       | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 35       | 1.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35       | 1.71%   |
| Intel SATA Controller [RAID mode]                                              | 34       | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 33       | 1.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 29       | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 28       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 28       | 1.37%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 26       | 1.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 25       | 1.22%   |
| Phison E12 NVMe Controller                                                     | 23       | 1.12%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 23       | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 23       | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 22       | 1.07%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 22       | 1.07%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 20       | 0.98%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 19       | 0.93%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 19       | 0.93%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 19       | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                         | 18       | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 17       | 0.83%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 16       | 0.78%   |
| Intel SSD 660P Series                                                          | 16       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                             | 15       | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 15       | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 14       | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 13       | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13       | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 13       | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 13       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 883      | 53.68%  |
| NVMe | 561      | 34.1%   |
| IDE  | 114      | 6.93%   |
| RAID | 79       | 4.8%    |
| SAS  | 6        | 0.36%   |
| SCSI | 2        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 502      | 50.66%  |
| AMD    | 489      | 49.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 33       | 3.32%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 27       | 2.71%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 23       | 2.31%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 20       | 2.01%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 20       | 2.01%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 19       | 1.91%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 17       | 1.71%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 17       | 1.71%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 15       | 1.51%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 13       | 1.31%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 13       | 1.31%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 11       | 1.11%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 11       | 1.11%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 10       | 1.01%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 1.01%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 9        | 0.9%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.9%    |
| Intel 12th Gen Core i5-12400F               | 9        | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 9        | 0.9%    |
| AMD Ryzen 5 5500                            | 9        | 0.9%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 8        | 0.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 0.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 8        | 0.8%    |
| AMD Ryzen 5 5600 6-Core Processor           | 8        | 0.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 0.7%    |
| AMD Ryzen 5 7600X 6-Core Processor          | 7        | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 0.6%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 6        | 0.6%    |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 0.6%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 6        | 0.6%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 6        | 0.6%    |
| AMD Ryzen 9 7950X3D 16-Core Processor       | 6        | 0.6%    |
| AMD Ryzen 7 7700X 8-Core Processor          | 6        | 0.6%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 6        | 0.6%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 6        | 0.6%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 0.6%    |
| AMD FX-8320 Eight-Core Processor            | 6        | 0.6%    |
| Intel N100                                  | 5        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 153      | 15.38%  |
| AMD Ryzen 7             | 143      | 14.37%  |
| Intel Core i5           | 140      | 14.07%  |
| Intel Core i7           | 105      | 10.55%  |
| Other                   | 91       | 9.15%   |
| AMD Ryzen 9             | 87       | 8.74%   |
| Intel Xeon              | 57       | 5.73%   |
| Intel Core i3           | 43       | 4.32%   |
| AMD FX                  | 21       | 2.11%   |
| AMD Ryzen 3             | 18       | 1.81%   |
| Intel Core 2 Quad       | 17       | 1.71%   |
| Intel Core 2 Duo        | 12       | 1.21%   |
| AMD Ryzen Threadripper  | 12       | 1.21%   |
| Intel Core i9           | 11       | 1.11%   |
| Intel Celeron           | 11       | 1.11%   |
| Intel Pentium           | 7        | 0.7%    |
| AMD Phenom II X6        | 7        | 0.7%    |
| AMD A10                 | 6        | 0.6%    |
| AMD Phenom II X4        | 5        | 0.5%    |
| AMD Athlon 64 X2        | 5        | 0.5%    |
| AMD A8                  | 5        | 0.5%    |
| Intel Genuine           | 4        | 0.4%    |
| AMD Ryzen 5 PRO         | 4        | 0.4%    |
| AMD A4                  | 4        | 0.4%    |
| AMD A6                  | 3        | 0.3%    |
| Intel Core 2            | 2        | 0.2%    |
| Intel Atom              | 2        | 0.2%    |
| AMD Phenom II X2        | 2        | 0.2%    |
| AMD Athlon II X4        | 2        | 0.2%    |
| AMD Athlon II X3        | 2        | 0.2%    |
| Intel Pentium Gold      | 1        | 0.1%    |
| Intel Pentium Dual-Core | 1        | 0.1%    |
| Intel Core 2 Extreme    | 1        | 0.1%    |
| AMD Turion 64 X2 Mobile | 1        | 0.1%    |
| AMD Sempron             | 1        | 0.1%    |
| AMD Ryzen Embedded      | 1        | 0.1%    |
| AMD Ryzen 7 PRO         | 1        | 0.1%    |
| AMD Ryzen 3 PRO         | 1        | 0.1%    |
| AMD PRO A10             | 1        | 0.1%    |
| AMD Phenom              | 1        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 290      | 29.15%  |
| 6      | 229      | 23.02%  |
| 8      | 189      | 18.99%  |
| 2      | 95       | 9.55%   |
| 12     | 75       | 7.54%   |
| 16     | 54       | 5.43%   |
| 24     | 14       | 1.41%   |
| 10     | 13       | 1.31%   |
| 14     | 9        | 0.9%    |
| 1      | 7        | 0.7%    |
| 3      | 6        | 0.6%    |
| 32     | 4        | 0.4%    |
| 28     | 4        | 0.4%    |
| 18     | 3        | 0.3%    |
| 64     | 1        | 0.1%    |
| 20     | 1        | 0.1%    |
| 5      | 1        | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 978      | 98.69%  |
| 2      | 13       | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 735      | 73.94%  |
| 1      | 259      | 26.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 991      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 746      | 73.57%  |
| 0x08701021 | 28       | 2.76%   |
| 0x0a601206 | 25       | 2.47%   |
| 0x0a601203 | 21       | 2.07%   |
| 0x0a20120a | 19       | 1.87%   |
| 0x08701030 | 17       | 1.68%   |
| 0x0a50000d | 15       | 1.48%   |
| 0x0a201016 | 14       | 1.38%   |
| 0x0800820d | 10       | 0.99%   |
| 0x0a20120e | 9        | 0.89%   |
| 0x010000c8 | 8        | 0.79%   |
| 0x0a50000f | 7        | 0.69%   |
| 0x08701013 | 7        | 0.69%   |
| 0x08101016 | 6        | 0.59%   |
| 0x06000852 | 6        | 0.59%   |
| 0x0a50000c | 5        | 0.49%   |
| 0x08108109 | 5        | 0.49%   |
| 0x08001138 | 5        | 0.49%   |
| 0x08001137 | 5        | 0.49%   |
| 0x06001119 | 5        | 0.49%   |
| 0x0a20102b | 3        | 0.3%    |
| 0x08600109 | 3        | 0.3%    |
| 0x010000dc | 3        | 0.3%    |
| 0x0a601201 | 2        | 0.2%    |
| 0x0a50000b | 2        | 0.2%    |
| 0x0a201205 | 2        | 0.2%    |
| 0x0a201025 | 2        | 0.2%    |
| 0x08600106 | 2        | 0.2%    |
| 0x0830107b | 2        | 0.2%    |
| 0x0800111c | 2        | 0.2%    |
| 0x06003106 | 2        | 0.2%    |
| 0x0600081c | 2        | 0.2%    |
| 0x010000bf | 2        | 0.2%    |
| 0x01000086 | 2        | 0.2%    |
| 0x0a705203 | 1        | 0.1%    |
| 0x0a404102 | 1        | 0.1%    |
| 0x0a201204 | 1        | 0.1%    |
| 0x0a201009 | 1        | 0.1%    |
| 0x0a201006 | 1        | 0.1%    |
| 0x08001129 | 1        | 0.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 165      | 16.55%  |
| Unknown          | 126      | 12.64%  |
| Zen 2            | 91       | 9.13%   |
| KabyLake         | 83       | 8.32%   |
| Haswell          | 80       | 8.02%   |
| Alderlake Hybrid | 51       | 5.12%   |
| IvyBridge        | 47       | 4.71%   |
| Skylake          | 41       | 4.11%   |
| SandyBridge      | 36       | 3.61%   |
| Zen              | 35       | 3.51%   |
| Zen+             | 34       | 3.41%   |
| Piledriver       | 27       | 2.71%   |
| Penryn           | 27       | 2.71%   |
| CometLake        | 27       | 2.71%   |
| K10              | 21       | 2.11%   |
| Nehalem          | 16       | 1.6%    |
| Westmere         | 13       | 1.3%    |
| Broadwell        | 13       | 1.3%    |
| Icelake          | 11       | 1.1%    |
| Core             | 11       | 1.1%    |
| Steamroller      | 8        | 0.8%    |
| K8 Hammer        | 8        | 0.8%    |
| Excavator        | 5        | 0.5%    |
| Silvermont       | 4        | 0.4%    |
| Gracemont        | 4        | 0.4%    |
| Bonnell          | 3        | 0.3%    |
| Tremont          | 2        | 0.2%    |
| TigerLake        | 2        | 0.2%    |
| Goldmont plus    | 2        | 0.2%    |
| NetBurst         | 1        | 0.1%    |
| K10 Llano        | 1        | 0.1%    |
| Jaguar           | 1        | 0.1%    |
| Bobcat           | 1        | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 448      | 40.62%  |
| AMD                        | 421      | 38.17%  |
| Intel                      | 231      | 20.94%  |
| VIA Technologies           | 1        | 0.09%   |
| Matrox Electronics Systems | 1        | 0.09%   |
| ASPEED Technology          | 1        | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Raphael                                                                 | 63       | 5.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 38       | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35       | 3.02%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 29       | 2.5%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 29       | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 28       | 2.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 28       | 2.42%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 26       | 2.24%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 26       | 2.24%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 25       | 2.16%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 24       | 2.07%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 20       | 1.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 18       | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 1.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 15       | 1.29%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 15       | 1.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 13       | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 13       | 1.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 1.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 12       | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 12       | 1.04%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 12       | 1.04%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 12       | 1.04%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 12       | 1.04%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 12       | 1.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 11       | 0.95%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 11       | 0.95%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 10       | 0.86%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 10       | 0.86%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 10       | 0.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 0.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 10       | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                               | 9        | 0.78%   |
| Nvidia AD104 [GeForce RTX 4070]                                             | 9        | 0.78%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 9        | 0.78%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 9        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 384      | 38.4%   |
| 1 x AMD        | 321      | 32.1%   |
| 1 x Intel      | 160      | 16%     |
| 2 x AMD        | 48       | 4.8%    |
| AMD + Nvidia   | 34       | 3.4%    |
| Intel + Nvidia | 27       | 2.7%    |
| Intel + AMD    | 14       | 1.4%    |
| 2 x Intel      | 4        | 0.4%    |
| 2 x Nvidia     | 3        | 0.3%    |
| Other          | 2        | 0.2%    |
| 1 x VIA        | 1        | 0.1%    |
| 1 x Matrox     | 1        | 0.1%    |
| 1 x ASPEED     | 1        | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 766      | 76.14%  |
| Proprietary | 176      | 17.5%   |
| Unknown     | 64       | 6.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 529      | 52.02%  |
| 7.01-8.0   | 109      | 10.72%  |
| 8.01-16.0  | 92       | 9.05%   |
| 3.01-4.0   | 72       | 7.08%   |
| 1.01-2.0   | 61       | 6%      |
| 0.51-1.0   | 49       | 4.82%   |
| 0.01-0.5   | 47       | 4.62%   |
| 5.01-6.0   | 30       | 2.95%   |
| 16.01-24.0 | 22       | 2.16%   |
| 2.01-3.0   | 5        | 0.49%   |
| 4.01-5.0   | 1        | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 157      | 14.11%  |
| Dell                 | 153      | 13.75%  |
| Goldstar             | 152      | 13.66%  |
| Acer                 | 77       | 6.92%   |
| Hewlett-Packard      | 58       | 5.21%   |
| AOC                  | 55       | 4.94%   |
| Philips              | 53       | 4.76%   |
| Ancor Communications | 41       | 3.68%   |
| ASUSTek Computer     | 39       | 3.5%    |
| BenQ                 | 38       | 3.41%   |
| MSI                  | 27       | 2.43%   |
| Lenovo               | 27       | 2.43%   |
| Iiyama               | 20       | 1.8%    |
| ViewSonic            | 17       | 1.53%   |
| Gigabyte Technology  | 17       | 1.53%   |
| Sony                 | 9        | 0.81%   |
| Sceptre Tech         | 8        | 0.72%   |
| Panasonic            | 8        | 0.72%   |
| Mi                   | 8        | 0.72%   |
| Vizio                | 7        | 0.63%   |
| Unknown              | 7        | 0.63%   |
| NEC Computers        | 7        | 0.63%   |
| Insignia             | 7        | 0.63%   |
| Fujitsu Siemens      | 7        | 0.63%   |
| HKC                  | 5        | 0.45%   |
| Eizo                 | 5        | 0.45%   |
| Apple                | 5        | 0.45%   |
| SAC                  | 4        | 0.36%   |
| HUAWEI               | 4        | 0.36%   |
| HannStar             | 4        | 0.36%   |
| VIE                  | 3        | 0.27%   |
| Unknown (XXX)        | 3        | 0.27%   |
| Toshiba              | 3        | 0.27%   |
| RTK                  | 3        | 0.27%   |
| Huion                | 3        | 0.27%   |
| Westinghouse         | 2        | 0.18%   |
| UGD                  | 2        | 0.18%   |
| SKG                  | 2        | 0.18%   |
| Pixio                | 2        | 0.18%   |
| Medion               | 2        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 13       | 1.09%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 8        | 0.67%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 7        | 0.58%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6        | 0.5%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.5%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 6        | 0.5%    |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 6        | 0.5%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6        | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 0.5%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 5        | 0.42%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5        | 0.42%   |
| Dell S2719DGF DELD0E6 2560x1440 597x336mm 27.0-inch                   | 5        | 0.42%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 5        | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4        | 0.33%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 4        | 0.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 0.33%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 4        | 0.33%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 4        | 0.33%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 338x270mm 17.0-inch              | 4        | 0.33%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 4        | 0.33%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 4        | 0.33%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch        | 4        | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4        | 0.33%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                   | 4        | 0.33%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4        | 0.33%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 4        | 0.33%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 4        | 0.33%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 3        | 0.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.25%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3        | 0.25%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.25%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3        | 0.25%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 3        | 0.25%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 3        | 0.25%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 3        | 0.25%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 3        | 0.25%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                  | 3        | 0.25%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 3        | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3        | 0.25%   |
| Goldstar E2011 GSM4ED3 1600x900 443x249mm 20.0-inch                   | 3        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 463      | 42.67%  |
| 3840x2160 (4K)     | 171      | 15.76%  |
| 2560x1440 (QHD)    | 153      | 14.1%   |
| 1280x1024 (SXGA)   | 43       | 3.96%   |
| 3440x1440          | 39       | 3.59%   |
| 1680x1050 (WSXGA+) | 36       | 3.32%   |
| 1366x768 (WXGA)    | 25       | 2.3%    |
| 2560x1080          | 23       | 2.12%   |
| 1920x1200 (WUXGA)  | 23       | 2.12%   |
| 1600x900 (HD+)     | 23       | 2.12%   |
| 1440x900 (WXGA+)   | 21       | 1.94%   |
| 3840x1080          | 13       | 1.2%    |
| 1920x540           | 9        | 0.83%   |
| 1360x768           | 7        | 0.65%   |
| 2288x1287          | 6        | 0.55%   |
| 2560x1600          | 5        | 0.46%   |
| 1600x1200          | 5        | 0.46%   |
| Unknown            | 4        | 0.37%   |
| 1280x720 (HD)      | 3        | 0.28%   |
| 640x480            | 2        | 0.18%   |
| 3840x1600          | 2        | 0.18%   |
| 5520x1080          | 1        | 0.09%   |
| 5120x2880          | 1        | 0.09%   |
| 2880x1440          | 1        | 0.09%   |
| 2560x2880          | 1        | 0.09%   |
| 2200x1650          | 1        | 0.09%   |
| 1360x765           | 1        | 0.09%   |
| 1280x960           | 1        | 0.09%   |
| 1280x800 (WXGA)    | 1        | 0.09%   |
| 1280x768           | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 249      | 22.25%  |
| 24      | 160      | 14.3%   |
| 23      | 131      | 11.71%  |
| 31      | 104      | 9.29%   |
| 21      | 94       | 8.4%    |
| 34      | 56       | 5%      |
| 19      | 45       | 4.02%   |
| 20      | 30       | 2.68%   |
| 18      | 29       | 2.59%   |
| Unknown | 26       | 2.32%   |
| 22      | 23       | 2.06%   |
| 84      | 18       | 1.61%   |
| 32      | 17       | 1.52%   |
| 48      | 14       | 1.25%   |
| 17      | 13       | 1.16%   |
| 54      | 12       | 1.07%   |
| 72      | 8        | 0.71%   |
| 26      | 8        | 0.71%   |
| 28      | 7        | 0.63%   |
| 15      | 7        | 0.63%   |
| 142     | 6        | 0.54%   |
| 40      | 6        | 0.54%   |
| 25      | 6        | 0.54%   |
| 42      | 5        | 0.45%   |
| 37      | 5        | 0.45%   |
| 29      | 5        | 0.45%   |
| 36      | 4        | 0.36%   |
| 63      | 3        | 0.27%   |
| 39      | 3        | 0.27%   |
| 33      | 3        | 0.27%   |
| 59      | 2        | 0.18%   |
| 47      | 2        | 0.18%   |
| 46      | 2        | 0.18%   |
| 35      | 2        | 0.18%   |
| 16      | 2        | 0.18%   |
| 86      | 1        | 0.09%   |
| 85      | 1        | 0.09%   |
| 74      | 1        | 0.09%   |
| 65      | 1        | 0.09%   |
| 60      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 482      | 44.8%   |
| 401-500        | 189      | 17.57%  |
| 601-700        | 145      | 13.48%  |
| 701-800        | 80       | 7.43%   |
| 1001-1500      | 40       | 3.72%   |
| 351-400        | 34       | 3.16%   |
| 1501-2000      | 28       | 2.6%    |
| Unknown        | 26       | 2.42%   |
| 301-350        | 19       | 1.77%   |
| 801-900        | 17       | 1.58%   |
| 901-1000       | 8        | 0.74%   |
| More than 2000 | 6        | 0.56%   |
| 201-300        | 2        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 735      | 73.94%  |
| 16/10   | 102      | 10.26%  |
| 21/9    | 65       | 6.54%   |
| 5/4     | 39       | 3.92%   |
| Unknown | 15       | 1.51%   |
| 32/9    | 12       | 1.21%   |
| 4/3     | 7        | 0.7%    |
| 1.00    | 6        | 0.6%    |
| 6/5     | 5        | 0.5%    |
| 3/2     | 2        | 0.2%    |
| 1.96    | 2        | 0.2%    |
| 2.12    | 1        | 0.1%    |
| 2.00    | 1        | 0.1%    |
| 0.89    | 1        | 0.1%    |
| 0.56    | 1        | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 321      | 29.16%  |
| 301-350        | 254      | 23.07%  |
| 351-500        | 188      | 17.08%  |
| 151-200        | 107      | 9.72%   |
| 251-300        | 63       | 5.72%   |
| More than 1000 | 57       | 5.18%   |
| 501-1000       | 44       | 4%      |
| 141-150        | 29       | 2.63%   |
| Unknown        | 26       | 2.36%   |
| 101-110        | 8        | 0.73%   |
| 71-80          | 1        | 0.09%   |
| 131-140        | 1        | 0.09%   |
| 121-130        | 1        | 0.09%   |
| 91-100         | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 616      | 60.57%  |
| 101-120 | 221      | 21.73%  |
| 121-160 | 75       | 7.37%   |
| 1-50    | 41       | 4.03%   |
| 161-240 | 38       | 3.74%   |
| Unknown | 26       | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 697      | 69.35%  |
| 2     | 215      | 21.39%  |
| 0     | 60       | 5.97%   |
| 3     | 25       | 2.49%   |
| 4     | 6        | 0.6%    |
| 6     | 2        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 644      | 42.79%  |
| Intel                           | 495      | 32.89%  |
| MediaTek                        | 75       | 4.98%   |
| Broadcom                        | 53       | 3.52%   |
| Qualcomm Atheros                | 45       | 2.99%   |
| TP-Link                         | 24       | 1.59%   |
| Ralink Technology               | 17       | 1.13%   |
| Microsoft                       | 17       | 1.13%   |
| Ralink                          | 12       | 0.8%    |
| Aquantia                        | 12       | 0.8%    |
| Qualcomm Atheros Communications | 9        | 0.6%    |
| ASIX Electronics                | 9        | 0.6%    |
| Nvidia                          | 8        | 0.53%   |
| NetGear                         | 7        | 0.47%   |
| Samsung Electronics             | 5        | 0.33%   |
| D-Link                          | 5        | 0.33%   |
| ASUSTek Computer                | 5        | 0.33%   |
| Xiaomi                          | 4        | 0.27%   |
| Motorola PCS                    | 4        | 0.27%   |
| Marvell Technology Group        | 4        | 0.27%   |
| Google                          | 4        | 0.27%   |
| Mellanox Technologies           | 3        | 0.2%    |
| AVM                             | 3        | 0.2%    |
| Qualcomm Technologies           | 2        | 0.13%   |
| Oculus VR                       | 2        | 0.13%   |
| Mercucys                        | 2        | 0.13%   |
| Linksys                         | 2        | 0.13%   |
| DisplayLink                     | 2        | 0.13%   |
| Broadcom Limited                | 2        | 0.13%   |
| ZyXEL Communications            | 1        | 0.07%   |
| ZyDAS                           | 1        | 0.07%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.07%   |
| VIA Technologies                | 1        | 0.07%   |
| Tehuti Networks                 | 1        | 0.07%   |
| Sharp                           | 1        | 0.07%   |
| Sagem                           | 1        | 0.07%   |
| ROCCAT                          | 1        | 0.07%   |
| Raspberry Pi                    | 1        | 0.07%   |
| Qualcomm                        | 1        | 0.07%   |
| Polar Electro Oy                | 1        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 430      | 24.49%  |
| Realtek RTL8125 2.5GbE Controller                                      | 152      | 8.66%   |
| Intel Wi-Fi 6 AX200                                                    | 84       | 4.78%   |
| Intel I211 Gigabit Network Connection                                  | 74       | 4.21%   |
| Intel Ethernet Controller I225-V                                       | 67       | 3.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 54       | 3.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 36       | 2.05%   |
| Intel Ethernet Connection (2) I219-V                                   | 32       | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 27       | 1.54%   |
| Intel Ethernet Connection I217-LM                                      | 24       | 1.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 21       | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 20       | 1.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 20       | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 17       | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15       | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15       | 0.85%   |
| Intel 82574L Gigabit Network Connection                                | 15       | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 14       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 14       | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14       | 0.8%    |
| Intel 700 Series Chipset CNVi WiFi                                     | 13       | 0.74%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 12       | 0.68%   |
| Intel I210 Gigabit Network Connection                                  | 11       | 0.63%   |
| Intel Ethernet Connection (17) I219-V                                  | 11       | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 10       | 0.57%   |
| Ralink MT7601U Wireless Adapter                                        | 10       | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9        | 0.51%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 9        | 0.51%   |
| Intel Wireless 7265                                                    | 9        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                   | 9        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 8        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8        | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 8        | 0.46%   |
| Realtek 802.11ac NIC                                                   | 8        | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                        | 8        | 0.46%   |
| Intel Wireless 7260                                                    | 8        | 0.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 8        | 0.46%   |
| Intel Ethernet Controller I226-V                                       | 8        | 0.46%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 7        | 0.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 7        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 257      | 43.12%  |
| Realtek Semiconductor           | 112      | 18.79%  |
| MediaTek                        | 68       | 11.41%  |
| Broadcom                        | 34       | 5.7%    |
| TP-Link                         | 24       | 4.03%   |
| Qualcomm Atheros                | 20       | 3.36%   |
| Ralink Technology               | 17       | 2.85%   |
| Microsoft                       | 17       | 2.85%   |
| Ralink                          | 12       | 2.01%   |
| Qualcomm Atheros Communications | 9        | 1.51%   |
| NetGear                         | 7        | 1.17%   |
| ASUSTek Computer                | 5        | 0.84%   |
| D-Link                          | 4        | 0.67%   |
| AVM                             | 3        | 0.5%    |
| Mercucys                        | 2        | 0.34%   |
| Linksys                         | 2        | 0.34%   |
| ZyDAS                           | 1        | 0.17%   |
| Sagem                           | 1        | 0.17%   |
| Qualcomm Technologies           | 1        | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 84       | 14%     |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 54       | 9%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 34       | 5.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 27       | 4.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 20       | 3.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 20       | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 15       | 2.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 14       | 2.33%   |
| Intel 700 Series Chipset CNVi WiFi                                                            | 13       | 2.17%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 12       | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 12       | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 10       | 1.67%   |
| Ralink MT7601U Wireless Adapter                                                               | 10       | 1.67%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                          | 9        | 1.5%    |
| Intel Wireless 7265                                                                           | 9        | 1.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 8        | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 8        | 1.33%   |
| Realtek 802.11ac NIC                                                                          | 8        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 8        | 1.33%   |
| Intel Wireless 7260                                                                           | 8        | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 8        | 1.33%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                                   | 7        | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 7        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 6        | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 6        | 1%      |
| TP-Link 802.11ac WLAN Adapter                                                                 | 5        | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 5        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 0.83%   |
| Intel Wireless 8260                                                                           | 5        | 0.83%   |
| Intel Wireless 3165                                                                           | 5        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 5        | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 4        | 0.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 4        | 0.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 4        | 0.67%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 4        | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 4        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4        | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 607      | 55.74%  |
| Intel                    | 357      | 32.78%  |
| Qualcomm Atheros         | 25       | 2.3%    |
| Broadcom                 | 24       | 2.2%    |
| Aquantia                 | 12       | 1.1%    |
| ASIX Electronics         | 9        | 0.83%   |
| Nvidia                   | 8        | 0.73%   |
| Samsung Electronics      | 5        | 0.46%   |
| MediaTek                 | 5        | 0.46%   |
| Xiaomi                   | 4        | 0.37%   |
| Motorola PCS             | 4        | 0.37%   |
| Marvell Technology Group | 4        | 0.37%   |
| Google                   | 4        | 0.37%   |
| Mellanox Technologies    | 3        | 0.28%   |
| DisplayLink              | 2        | 0.18%   |
| Broadcom Limited         | 2        | 0.18%   |
| ZyXEL Communications     | 1        | 0.09%   |
| VIA Technologies         | 1        | 0.09%   |
| Tehuti Networks          | 1        | 0.09%   |
| Sharp                    | 1        | 0.09%   |
| Qualcomm Technologies    | 1        | 0.09%   |
| Qualcomm                 | 1        | 0.09%   |
| OPPO Electronics         | 1        | 0.09%   |
| Lenovo                   | 1        | 0.09%   |
| JMicron Technology       | 1        | 0.09%   |
| Davicom Semiconductor    | 1        | 0.09%   |
| D-Link System            | 1        | 0.09%   |
| D-Link                   | 1        | 0.09%   |
| Apple                    | 1        | 0.09%   |
| 3Com                     | 1        | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 430      | 37.82%  |
| Realtek RTL8125 2.5GbE Controller                                              | 152      | 13.37%  |
| Intel I211 Gigabit Network Connection                                          | 74       | 6.51%   |
| Intel Ethernet Controller I225-V                                               | 67       | 5.89%   |
| Intel Ethernet Connection (2) I219-V                                           | 32       | 2.81%   |
| Intel Ethernet Connection I217-LM                                              | 24       | 2.11%   |
| Intel Ethernet Connection (7) I219-V                                           | 17       | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 15       | 1.32%   |
| Intel 82574L Gigabit Network Connection                                        | 15       | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                          | 14       | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14       | 1.23%   |
| Intel I210 Gigabit Network Connection                                          | 11       | 0.97%   |
| Intel Ethernet Connection (17) I219-V                                          | 11       | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                           | 9        | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 9        | 0.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8        | 0.7%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 8        | 0.7%    |
| Intel Ethernet Controller I226-V                                               | 8        | 0.7%    |
| Intel 82579V Gigabit Network Connection                                        | 7        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6        | 0.53%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 6        | 0.53%   |
| Intel Ethernet Connection I217-V                                               | 5        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                                          | 5        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4        | 0.35%   |
| Motorola PCS motorola one 5G ace                                               | 4        | 0.35%   |
| Intel Ethernet Controller X550                                                 | 4        | 0.35%   |
| Intel Ethernet Connection (2) I218-LM                                          | 4        | 0.35%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 4        | 0.35%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 4        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3        | 0.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.26%   |
| Nvidia MCP55 Ethernet                                                          | 3        | 0.26%   |
| Intel Ethernet Connection (11) I219-V                                          | 3        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 978      | 62.49%  |
| WiFi     | 569      | 36.36%  |
| Modem    | 13       | 0.83%   |
| Unknown  | 5        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 729      | 68.77%  |
| WiFi     | 331      | 31.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 466      | 46.74%  |
| 2     | 446      | 44.73%  |
| 3     | 67       | 6.72%   |
| 4     | 8        | 0.8%    |
| 0     | 6        | 0.6%    |
| 5     | 2        | 0.2%    |
| 11    | 1        | 0.1%    |
| 6     | 1        | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 668      | 66.93%  |
| Yes  | 330      | 33.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 247      | 44.58%  |
| Cambridge Silicon Radio         | 58       | 10.47%  |
| Realtek Semiconductor           | 54       | 9.75%   |
| MediaTek                        | 47       | 8.48%   |
| IMC Networks                    | 31       | 5.6%    |
| ASUSTek Computer                | 29       | 5.23%   |
| TP-Link                         | 22       | 3.97%   |
| Apple                           | 14       | 2.53%   |
| Broadcom                        | 13       | 2.35%   |
| Foxconn / Hon Hai               | 11       | 1.99%   |
| Realtek                         | 6        | 1.08%   |
| Qualcomm Atheros Communications | 5        | 0.9%    |
| Integrated System Solution      | 3        | 0.54%   |
| Actions                         | 3        | 0.54%   |
| Edimax Technology               | 2        | 0.36%   |
| Dynex                           | 2        | 0.36%   |
| Belkin Components               | 2        | 0.36%   |
| Unknown                         | 2        | 0.36%   |
| Ralink                          | 1        | 0.18%   |
| Lite-On Technology              | 1        | 0.18%   |
| Hewlett-Packard                 | 1        | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 75       | 13.51%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 58       | 10.45%  |
| Intel AX210 Bluetooth                                    | 50       | 9.01%   |
| MediaTek Wireless_Device                                 | 47       | 8.47%   |
| Realtek Bluetooth Radio                                  | 40       | 7.21%   |
| Intel Wireless-AC 3168 Bluetooth                         | 27       | 4.86%   |
| Intel Bluetooth wireless interface                       | 24       | 4.32%   |
| Intel Bluetooth Device                                   | 24       | 4.32%   |
| Intel AX201 Bluetooth                                    | 23       | 4.14%   |
| TP-Link TP-T@- UB500 Adapter                             | 22       | 3.96%   |
| IMC Networks Bluetooth Radio                             | 15       | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 14       | 2.52%   |
| IMC Networks Wireless_Device                             | 14       | 2.52%   |
| Foxconn / Hon Hai Wireless_Device                        | 9        | 1.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 9        | 1.62%   |
| ASUS ASUS USB-BT500                                      | 9        | 1.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 1.44%   |
| Realtek Bluetooth 5.3 Radio                              | 6        | 1.08%   |
| Realtek Bluetooth Radio                                  | 6        | 1.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 6        | 1.08%   |
| Apple Bluetooth Host Controller                          | 6        | 1.08%   |
| Realtek  Bluetooth 4.2 Adapter                           | 5        | 0.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 5        | 0.9%    |
| ASUS Qualcomm Bluetooth 4.1                              | 4        | 0.72%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 4        | 0.72%   |
| ASUS Bluetooth Radio                                     | 4        | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3        | 0.54%   |
| Actions general adapter                                  | 3        | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 2        | 0.36%   |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 0.36%   |
| Integrated System Solution Bluetooth Device              | 2        | 0.36%   |
| Foxconn / Hon Hai Bluetooth Device                       | 2        | 0.36%   |
| Edimax Bluetooth Device                                  | 2        | 0.36%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 2        | 0.36%   |
| Broadcom BCM2070B0                                       | 2        | 0.36%   |
| ASUS Bluetooth Adapter                                   | 2        | 0.36%   |
| Unknown                                                  | 2        | 0.36%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.18%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 579      | 30.08%  |
| Intel                                | 493      | 25.61%  |
| Nvidia                               | 435      | 22.6%   |
| C-Media Electronics                  | 44       | 2.29%   |
| Logitech                             | 36       | 1.87%   |
| Micro Star International             | 22       | 1.14%   |
| ASUSTek Computer                     | 22       | 1.14%   |
| JMTek                                | 19       | 0.99%   |
| SteelSeries ApS                      | 17       | 0.88%   |
| Razer USA                            | 16       | 0.83%   |
| Creative Labs                        | 16       | 0.83%   |
| Generalplus Technology               | 14       | 0.73%   |
| Kingston Technology                  | 13       | 0.68%   |
| Hewlett-Packard                      | 12       | 0.62%   |
| Texas Instruments                    | 10       | 0.52%   |
| GN Netcom                            | 10       | 0.52%   |
| Corsair                              | 10       | 0.52%   |
| Thesycon Systemsoftware & Consulting | 7        | 0.36%   |
| Realtek Semiconductor                | 7        | 0.36%   |
| Focusrite-Novation                   | 7        | 0.36%   |
| Plantronics                          | 6        | 0.31%   |
| RODE Microphones                     | 5        | 0.26%   |
| FIFINE Microphones                   | 5        | 0.26%   |
| Blue Microphones                     | 5        | 0.26%   |
| Jieli Technology                     | 4        | 0.21%   |
| BEHRINGER International              | 4        | 0.21%   |
| VIA Technologies                     | 3        | 0.16%   |
| TTGK Technology                      | 3        | 0.16%   |
| Trust                                | 3        | 0.16%   |
| Sony                                 | 3        | 0.16%   |
| Schiit Audio                         | 3        | 0.16%   |
| Samson Technologies                  | 3        | 0.16%   |
| Giga-Byte Technology                 | 3        | 0.16%   |
| Elgato Systems                       | 3        | 0.16%   |
| Audient                              | 3        | 0.16%   |
| ASRock                               | 3        | 0.16%   |
| Arturia                              | 3        | 0.16%   |
| Tenx Technology                      | 2        | 0.1%    |
| Solid State Logic                    | 2        | 0.1%    |
| Shure                                | 2        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 189      | 8.1%    |
| AMD Ryzen HD Audio Controller                                              | 155      | 6.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 97       | 4.16%   |
| AMD Radeon High Definition Audio Controller                                | 75       | 3.21%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 58       | 2.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 57       | 2.44%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 56       | 2.4%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 54       | 2.31%   |
| Intel Alder Lake-S HD Audio Controller                                     | 48       | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 46       | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 45       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 43       | 1.84%   |
| Nvidia GA106 High Definition Audio Controller                              | 42       | 1.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 42       | 1.8%    |
| Intel 200 Series PCH HD Audio                                              | 41       | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 39       | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 38       | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 38       | 1.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30       | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 28       | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 28       | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 28       | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 26       | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 25       | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 23       | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 23       | 0.99%   |
| Micro Star International USB Audio                                         | 22       | 0.94%   |
| ASUSTek Computer USB Audio                                                 | 22       | 0.94%   |
| Nvidia GA102 High Definition Audio Controller                              | 21       | 0.9%    |
| Intel Raptor Lake High Definition Audio Controller                         | 21       | 0.9%    |
| AMD Navi 10 HDMI Audio                                                     | 21       | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20       | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 18       | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 18       | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18       | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 17       | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                         | 16       | 0.69%   |
| JMTek USB PnP Audio Device                                                 | 15       | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 0.64%   |
| AMD FCH Azalia Controller                                                  | 15       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Corsair                              | 61       | 18.15%  |
| Kingston                             | 57       | 16.96%  |
| G.Skill                              | 51       | 15.18%  |
| Unknown                              | 27       | 8.04%   |
| Crucial                              | 26       | 7.74%   |
| Samsung Electronics                  | 25       | 7.44%   |
| SK hynix                             | 15       | 4.46%   |
| Micron Technology                    | 11       | 3.27%   |
| A-DATA Technology                    | 9        | 2.68%   |
| Team                                 | 8        | 2.38%   |
| Unknown                              | 8        | 2.38%   |
| Smart                                | 4        | 1.19%   |
| Patriot                              | 4        | 1.19%   |
| Nanya Technology                     | 3        | 0.89%   |
| Ramaxel Technology                   | 2        | 0.6%    |
| Patriot Memory                       | 2        | 0.6%    |
| Lexar                                | 2        | 0.6%    |
| Atermiter                            | 2        | 0.6%    |
| AMD                                  | 2        | 0.6%    |
| Wodposit                             | 1        | 0.3%    |
| V-GeN                                | 1        | 0.3%    |
| Unknown (ABCD)                       | 1        | 0.3%    |
| Unknown (09D5)                       | 1        | 0.3%    |
| Transcend                            | 1        | 0.3%    |
| TakeMS                               | 1        | 0.3%    |
| Super Talent                         | 1        | 0.3%    |
| Silicon Power                        | 1        | 0.3%    |
| Shenzhen Jinge Information           | 1        | 0.3%    |
| Kllisre                              | 1        | 0.3%    |
| Kingmax                              | 1        | 0.3%    |
| Hikvision                            | 1        | 0.3%    |
| CUSO                                 | 1        | 0.3%    |
| Chun Well Technology Holding Limited | 1        | 0.3%    |
| Chun Well                            | 1        | 0.3%    |
| Avant                                | 1        | 0.3%    |
| Apacer                               | 1        | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown                                                    | 8        | 2.2%    |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3466MT/s      | 4        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 3        | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 3        | 0.83%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s         | 3        | 0.83%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s      | 3        | 0.83%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6200MT/s       | 3        | 0.83%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 3        | 0.83%   |
| Corsair RAM CMK64GX5M2B5600C40 32GB DIMM DDR5 5600MT/s     | 3        | 0.83%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s     | 3        | 0.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 3        | 0.83%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 2        | 0.55%   |
| Unknown RAM Module 4GB DIMM SDRAM                          | 2        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 0.55%   |
| Unknown RAM Module 2GB DIMM 667MT/s                        | 2        | 0.55%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 4000MT/s        | 2        | 0.55%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                 | 2        | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2        | 0.55%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s        | 2        | 0.55%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s        | 2        | 0.55%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2400MT/s        | 2        | 0.55%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3400MT/s | 2        | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s       | 2        | 0.55%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2        | 0.55%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s        | 2        | 0.55%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 2        | 0.55%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 6200MT/s           | 2        | 0.55%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s      | 2        | 0.55%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s       | 2        | 0.55%   |
| G.Skill RAM F5-6400J3239F48G 48GB DIMM DDR5 6400MT/s       | 2        | 0.55%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s       | 2        | 0.55%   |
| G.Skill RAM F5-6000J3040F16G 16GB DIMM DDR5 6000MT/s       | 2        | 0.55%   |
| G.Skill RAM F5-6000J3038F16G 16GB DIMM DDR5 6000MT/s       | 2        | 0.55%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s      | 2        | 0.55%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s        | 2        | 0.55%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3800MT/s         | 2        | 0.55%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 2        | 0.55%   |
| Crucial RAM CT32G4SFD8266.C16FB 32GB SODIMM DDR4 2667MT/s  | 2        | 0.55%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s    | 2        | 0.55%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3600MT/s      | 2        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 177      | 55.66%  |
| DDR5    | 55       | 17.3%   |
| DDR3    | 54       | 16.98%  |
| Unknown | 11       | 3.46%   |
| DDR2    | 8        | 2.52%   |
| SDRAM   | 7        | 2.2%    |
| LPDDR4  | 3        | 0.94%   |
| DDR     | 2        | 0.63%   |
| DRAM    | 1        | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 287      | 90.82%  |
| SODIMM       | 25       | 7.91%   |
| Row Of Chips | 2        | 0.63%   |
| RIMM         | 2        | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 124      | 37.13%  |
| 16384 | 97       | 29.04%  |
| 32768 | 49       | 14.67%  |
| 4096  | 36       | 10.78%  |
| 2048  | 23       | 6.89%   |
| 49152 | 2        | 0.6%    |
| 1024  | 2        | 0.6%    |
| 65536 | 1        | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 42       | 12.35%  |
| 3200    | 37       | 10.88%  |
| 1600    | 33       | 9.71%   |
| 2133    | 19       | 5.59%   |
| 2400    | 18       | 5.29%   |
| 1333    | 18       | 5.29%   |
| 6000    | 13       | 3.82%   |
| 4800    | 13       | 3.82%   |
| 3733    | 12       | 3.53%   |
| 2667    | 12       | 3.53%   |
| 5600    | 9        | 2.65%   |
| 3800    | 9        | 2.65%   |
| 3400    | 8        | 2.35%   |
| 3000    | 8        | 2.35%   |
| 4000    | 7        | 2.06%   |
| 800     | 7        | 2.06%   |
| 3466    | 6        | 1.76%   |
| 6400    | 5        | 1.47%   |
| 6200    | 5        | 1.47%   |
| 5200    | 5        | 1.47%   |
| 1866    | 5        | 1.47%   |
| Unknown | 5        | 1.47%   |
| 3866    | 4        | 1.18%   |
| 1066    | 4        | 1.18%   |
| 1867    | 3        | 0.88%   |
| 667     | 3        | 0.88%   |
| 5800    | 2        | 0.59%   |
| 3467    | 2        | 0.59%   |
| 3266    | 2        | 0.59%   |
| 3066    | 2        | 0.59%   |
| 2933    | 2        | 0.59%   |
| 2666    | 2        | 0.59%   |
| 400     | 2        | 0.59%   |
| 12800   | 1        | 0.29%   |
| 7000    | 1        | 0.29%   |
| 5000    | 1        | 0.29%   |
| 4266    | 1        | 0.29%   |
| 3933    | 1        | 0.29%   |
| 3533    | 1        | 0.29%   |
| 3334    | 1        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 19       | 40.43%  |
| Brother Industries  | 12       | 25.53%  |
| Canon               | 5        | 10.64%  |
| Seiko Epson         | 4        | 8.51%   |
| Dymo-CoStar         | 3        | 6.38%   |
| Samsung Electronics | 2        | 4.26%   |
| iDPRT               | 1        | 2.13%   |
| Dell                | 1        | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Brother Printer                        | 2        | 4.26%   |
| Brother MFC-L2710DW series             | 2        | 4.26%   |
| Seiko Epson XP-4100 Series             | 1        | 2.13%   |
| Seiko Epson ET-2710 Series             | 1        | 2.13%   |
| Seiko Epson EPSON L300 Series          | 1        | 2.13%   |
| Seiko Epson AL-M310DN                  | 1        | 2.13%   |
| Samsung ML-216x Series Laser Printer   | 1        | 2.13%   |
| Samsung M203x Series                   | 1        | 2.13%   |
| iDPRT SP410                            | 1        | 2.13%   |
| HP Smart Tank 7300 series              | 1        | 2.13%   |
| HP PSC-1315/PSC-1317                   | 1        | 2.13%   |
| HP LaserJet P2015 series               | 1        | 2.13%   |
| HP LaserJet P1006                      | 1        | 2.13%   |
| HP LaserJet P1005                      | 1        | 2.13%   |
| HP LaserJet M14-M17                    | 1        | 2.13%   |
| HP LaserJet 400 color M451dn           | 1        | 2.13%   |
| HP LaserJet 2200                       | 1        | 2.13%   |
| HP LaserJet 1020                       | 1        | 2.13%   |
| HP LaserJet 1010                       | 1        | 2.13%   |
| HP HP LaserJet Pro M404-M405           | 1        | 2.13%   |
| HP ENVY Photo 7800 series              | 1        | 2.13%   |
| HP ENVY Photo 6200 series              | 1        | 2.13%   |
| HP ENVY 5000 series                    | 1        | 2.13%   |
| HP ENVY 4500 series                    | 1        | 2.13%   |
| HP DeskJet 4100 series                 | 1        | 2.13%   |
| HP DeskJet 3940                        | 1        | 2.13%   |
| HP DeskJet 2700 series                 | 1        | 2.13%   |
| HP DeskJet 2600 series                 | 1        | 2.13%   |
| Dymo-CoStar LabelWriter 450            | 1        | 2.13%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 2.13%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO   | 1        | 2.13%   |
| Dell C1660w Color Printer              | 1        | 2.13%   |
| Canon TS3100 series                    | 1        | 2.13%   |
| Canon TR4700 series                    | 1        | 2.13%   |
| Canon PIXMA MX470 Series               | 1        | 2.13%   |
| Canon MF3010                           | 1        | 2.13%   |
| Canon LBP3010/LBP3018/LBP3050          | 1        | 2.13%   |
| Brother MFC-L8690CDW series            | 1        | 2.13%   |
| Brother MFC-L2740DW                    | 1        | 2.13%   |
| Brother HL-L2340D series               | 1        | 2.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 5        | 55.56%  |
| Seiko Epson        | 3        | 33.33%  |
| Ultima Electronics | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 2        | 22.22%  |
| Canon CanoScan LiDE 220                     | 2        | 22.22%  |
| Ultima Artec E+ Pro                         | 1        | 11.11%  |
| Seiko Epson GT-X770 [Perfection V500]       | 1        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 11.11%  |
| Canon CanoScan LiDE 210                     | 1        | 11.11%  |
| Canon CanoScan LiDE 110                     | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 87       | 39.19%  |
| Microdia                      | 19       | 8.56%   |
| Sunplus Innovation Technology | 11       | 4.95%   |
| Microsoft                     | 10       | 4.5%    |
| Realtek Semiconductor         | 7        | 3.15%   |
| Generalplus Technology        | 7        | 3.15%   |
| ARC International             | 6        | 2.7%    |
| Apple                         | 6        | 2.7%    |
| Razer USA                     | 4        | 1.8%    |
| AVerMedia Technologies        | 4        | 1.8%    |
| Z-Star Microelectronics       | 3        | 1.35%   |
| webcam                        | 3        | 1.35%   |
| Trust                         | 3        | 1.35%   |
| Samsung Electronics           | 3        | 1.35%   |
| MacroSilicon                  | 3        | 1.35%   |
| KYE Systems (Mouse Systems)   | 3        | 1.35%   |
| GEMBIRD                       | 3        | 1.35%   |
| Owon                          | 2        | 0.9%    |
| Linux Foundation              | 2        | 0.9%    |
| eMeet                         | 2        | 0.9%    |
| Chicony Electronics           | 2        | 0.9%    |
| Anker PowerConf C200          | 2        | 0.9%    |
| Alpha Imaging Technology      | 2        | 0.9%    |
| A4Tech                        | 2        | 0.9%    |
| YGTek                         | 1        | 0.45%   |
| webcamvendor                  | 1        | 0.45%   |
| WCM_USB                       | 1        | 0.45%   |
| WaveRider Communications      | 1        | 0.45%   |
| Valve Software                | 1        | 0.45%   |
| Spreadtrum Communications     | 1        | 0.45%   |
| Sonix Technology              | 1        | 0.45%   |
| Sculpfun CAM500               | 1        | 0.45%   |
| Remo Tech                     | 1        | 0.45%   |
| Quanta                        | 1        | 0.45%   |
| Pixart Imaging                | 1        | 0.45%   |
| Motorola PCS                  | 1        | 0.45%   |
| Leap Motion                   | 1        | 0.45%   |
| Jieli Technology              | 1        | 0.45%   |
| Huawei Technologies           | 1        | 0.45%   |
| Hopewin Electronic Material   | 1        | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 13       | 5.83%   |
| Logitech Webcam C270                     | 11       | 4.93%   |
| Microdia USB 2.0 Camera                  | 10       | 4.48%   |
| Logitech C922 Pro Stream Webcam          | 8        | 3.59%   |
| Logitech BRIO Ultra HD Webcam            | 7        | 3.14%   |
| Logitech C920 PRO HD Webcam              | 6        | 2.69%   |
| ARC International Camera                 | 6        | 2.69%   |
| Logitech Webcam C930e                    | 5        | 2.24%   |
| Logitech HD Webcam C615                  | 5        | 2.24%   |
| Razer USA Razer Kiyo Pro                 | 4        | 1.79%   |
| Logitech QuickCam E 3500                 | 4        | 1.79%   |
| Logitech HD Webcam C525                  | 4        | 1.79%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 4        | 1.79%   |
| webcam webcam                            | 3        | 1.35%   |
| Sunplus USB 2.0 Camera                   | 3        | 1.35%   |
| Sunplus Integrated Camera                | 3        | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)  | 3        | 1.35%   |
| Microsoft LifeCam Studio                 | 3        | 1.35%   |
| Logitech Webcam C310                     | 3        | 1.35%   |
| Generalplus GENERAL WEBCAM               | 3        | 1.35%   |
| AVerMedia Live Streamer CAM 313          | 3        | 1.35%   |
| Trust Full HD Webcam                     | 2        | 0.9%    |
| Sunplus Full HD webcam                   | 2        | 0.9%    |
| Realtek USB Camera                       | 2        | 0.9%    |
| Owon USB CAMERA                          | 2        | 0.9%    |
| Microsoft LifeCam HD-3000                | 2        | 0.9%    |
| Microsoft LifeCam Cinema                 | 2        | 0.9%    |
| Microdia USB Live camera                 | 2        | 0.9%    |
| Microdia Sonix USB 2.0 Camera            | 2        | 0.9%    |
| Microdia Integrated Camera               | 2        | 0.9%    |
| Microdia Camera                          | 2        | 0.9%    |
| MacroSilicon USB Video                   | 2        | 0.9%    |
| Logitech Webcam C170                     | 2        | 0.9%    |
| Logitech StreamCam                       | 2        | 0.9%    |
| Logitech Logitech Webcam C925e           | 2        | 0.9%    |
| Logitech HD Webcam C910                  | 2        | 0.9%    |
| Logitech HD Webcam C510                  | 2        | 0.9%    |
| Logitech B525 HD Webcam                  | 2        | 0.9%    |
| Linux Foundation EEM Gadget              | 2        | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Upek   | 1        | 50%     |
| Dell   | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Upek TCS1C EIM/STM32 Fingerprint sensor        | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 3        | 50%     |
| Realtek Semiconductor     | 1        | 16.67%  |
| Chicony Electronics       | 1        | 16.67%  |
| Aladdin Knowledge Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface    | 1        | 16.67%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 16.67%  |
| Aladdin Knowledge Systems Token JC                   | 1        | 16.67%  |
| Advanced Card Systems ACR1281 1S Dual Reader         | 1        | 16.67%  |
| Advanced Card Systems ACR1252 Dual Reader            | 1        | 16.67%  |
| Advanced Card Systems ACR1252 CL Reader PICC         | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 828      | 82.97%  |
| 1     | 145      | 14.53%  |
| 2     | 17       | 1.7%    |
| 3     | 4        | 0.4%    |
| 5     | 2        | 0.2%    |
| 4     | 2        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 92       | 47.42%  |
| Net/wireless             | 41       | 21.13%  |
| Unassigned class         | 22       | 11.34%  |
| Sound                    | 12       | 6.19%   |
| Bluetooth                | 6        | 3.09%   |
| Storage/raid             | 4        | 2.06%   |
| Net/ethernet             | 4        | 2.06%   |
| Multimedia controller    | 4        | 2.06%   |
| Camera                   | 4        | 2.06%   |
| Communication controller | 2        | 1.03%   |
| Network                  | 1        | 0.52%   |
| Fingerprint reader       | 1        | 0.52%   |
| Chipcard                 | 1        | 0.52%   |

