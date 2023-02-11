Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 5469

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG Z590 TORPEDO            | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Acer          | FMP55                       | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| ASRock        | AD2700-ITX                  | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d1c6e3c96f](https://linux-hardware.org/?probe=d1c6e3c96f) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ASRock        | J3455B-ITX                  | [b4419e8fce](https://linux-hardware.org/?probe=b4419e8fce) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| HP            | 0AECh D                     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | Z690 PG Riptide             | [582e3e3026](https://linux-hardware.org/?probe=582e3e3026) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| MSI           | X99A RAIDER                 | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f26dbd644c](https://linux-hardware.org/?probe=f26dbd644c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [f9846c0e18](https://linux-hardware.org/?probe=f9846c0e18) | Jan 13, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [eec3fcf9ff](https://linux-hardware.org/?probe=eec3fcf9ff) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| HP            | 8459                        | [18f44a4e07](https://linux-hardware.org/?probe=18f44a4e07) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| MSI           | X99A RAIDER                 | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| MSI           | Boston                      | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [6dddb93518](https://linux-hardware.org/?probe=6dddb93518) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [172c6c1300](https://linux-hardware.org/?probe=172c6c1300) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [e89ecf8da4](https://linux-hardware.org/?probe=e89ecf8da4) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0GY6Y8 A02                  | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| HP            | 18E7                        | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| MSI           | X99A RAIDER                 | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| MSI           | 2A9C                        | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| MSI           | 2A9C                        | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Dell          | 0DR845                      | [c4d2b18dd8](https://linux-hardware.org/?probe=c4d2b18dd8) | Nov 10, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| Gigabyte      | B450M GAMING                | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 339A                        | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| MSI           | X99A RAIDER                 | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| Gigabyte      | B550 UD AC                  | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| HP            | 339A                        | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| MSI           | X99A RAIDER                 | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | X99A RAIDER                 | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASRock        | P45TS                       | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| Unknown       | X79                         | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| HP            | 8459                        | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| HP            | 8433 11                     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| NZXT          | N7 B550                     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| HP            | 8459                        | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Shuttle       | FH67H                       | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| MSI           | FM2-A55M-E33                | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| HP            | 3647h                       | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Unknown       | Intel X79                   | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| HP            | 0AECh D                     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Gigabyte      | B85M-D2V                    | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| Gigabyte      | B75M-D3H                    | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | H270M-ITX/ac                | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | Z170M Extreme4              | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASUSTek       | PRIME B365M-A               | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| MSI           | FM2-A55M-E33                | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | A88X-PRO                    | [b88a699d58](https://linux-hardware.org/?probe=b88a699d58) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| ASRock        | B550M-ITX/ac                | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| HP            | 805D                        | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b2a84cd02](https://linux-hardware.org/?probe=9b2a84cd02) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [1285ab4d66](https://linux-hardware.org/?probe=1285ab4d66) | Sep 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Dell          | 0M017G A00                  | [e040958337](https://linux-hardware.org/?probe=e040958337) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| ASUSTek       | Z97-A                       | [b23a59ba48](https://linux-hardware.org/?probe=b23a59ba48) | Sep 12, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| BESSTAR Te... | UM700                       | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [a3b824ba41](https://linux-hardware.org/?probe=a3b824ba41) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| ASUSTek       | B150 PRO GAMING             | [5e145ec2d1](https://linux-hardware.org/?probe=5e145ec2d1) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [03979fc286](https://linux-hardware.org/?probe=03979fc286) | Sep 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Biostar       | A780L3G                     | [e53730ab48](https://linux-hardware.org/?probe=e53730ab48) | Sep 09, 2022 |
| ASRock        | B550M Pro4                  | [e43ef549eb](https://linux-hardware.org/?probe=e43ef549eb) | Sep 08, 2022 |
| ASRock        | B550M Pro4                  | [ac6cb859ad](https://linux-hardware.org/?probe=ac6cb859ad) | Sep 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | [daf3e0182b](https://linux-hardware.org/?probe=daf3e0182b) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| HP            | 18E4                        | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| ASUSTek       | H110M-A                     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0f0a18c852](https://linux-hardware.org/?probe=0f0a18c852) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [e06271e233](https://linux-hardware.org/?probe=e06271e233) | Sep 08, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| ASUSTek       | Z97-A                       | [46be1ea134](https://linux-hardware.org/?probe=46be1ea134) | Sep 08, 2022 |
| MSI           | Z97 PC Mate                 | [bcf93bb718](https://linux-hardware.org/?probe=bcf93bb718) | Sep 08, 2022 |
| Biostar       | H310MHP                     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Dell          | 02YRK5 A02                  | [2395ab5aed](https://linux-hardware.org/?probe=2395ab5aed) | Sep 07, 2022 |
| ASUSTek       | H97-PRO                     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| ASRock        | EP2C602                     | [56a6980ddc](https://linux-hardware.org/?probe=56a6980ddc) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [e590a83122](https://linux-hardware.org/?probe=e590a83122) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [b4a71c0eff](https://linux-hardware.org/?probe=b4a71c0eff) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [7bb2d68f03](https://linux-hardware.org/?probe=7bb2d68f03) | Sep 04, 2022 |
| Foxconn       | 2AB1                        | [3b7dae5f40](https://linux-hardware.org/?probe=3b7dae5f40) | Sep 04, 2022 |
| Gigabyte      | F2A78M-D3H                  | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5f37e7a618](https://linux-hardware.org/?probe=5f37e7a618) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| Foxconn       | 2ADA                        | [f1ca159a19](https://linux-hardware.org/?probe=f1ca159a19) | Sep 03, 2022 |
| Acer          | Aspire M3910                | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| Dell          | 0MWYPT A02                  | [e2f98387b0](https://linux-hardware.org/?probe=e2f98387b0) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Dell          | 0KV3RP A00                  | [731a14ee10](https://linux-hardware.org/?probe=731a14ee10) | Aug 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 36 | 655      | 17.65%  |
| Fedora 33 | 564      | 15.19%  |
| Fedora 35 | 530      | 14.28%  |
| Fedora 34 | 518      | 13.95%  |
| Fedora 32 | 518      | 13.95%  |
| Fedora 37 | 343      | 9.24%   |
| Fedora 31 | 343      | 9.24%   |
| Fedora 30 | 132      | 3.56%   |
| Fedora 29 | 75       | 2.02%   |
| Fedora 28 | 14       | 0.38%   |
| Fedora 27 | 9        | 0.24%   |
| Fedora 38 | 3        | 0.08%   |
| Fedora 25 | 2        | 0.05%   |
| Fedora 24 | 2        | 0.05%   |
| Fedora 4  | 1        | 0.03%   |
| Fedora 21 | 1        | 0.03%   |
| Fedora 17 | 1        | 0.03%   |
| Fedora 14 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 3216     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.9.16-200.fc33.x86_64  | 58       | 1.36%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1.34%   |
| 5.17.5-300.fc36.x86_64  | 47       | 1.1%    |
| 6.0.15-300.fc37.x86_64  | 45       | 1.06%   |
| 6.0.12-300.fc37.x86_64  | 44       | 1.03%   |
| 5.18.13-200.fc36.x86_64 | 42       | 0.99%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.92%   |
| 5.19.16-200.fc36.x86_64 | 38       | 0.89%   |
| 5.14.10-300.fc35.x86_64 | 36       | 0.84%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.82%   |
| 5.11.12-300.fc34.x86_64 | 35       | 0.82%   |
| 5.8.4-200.fc32.x86_64   | 33       | 0.77%   |
| 5.8.15-301.fc33.x86_64  | 33       | 0.77%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.75%   |
| 6.0.11-300.fc37.x86_64  | 31       | 0.73%   |
| 5.19.9-200.fc36.x86_64  | 31       | 0.73%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.73%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.7%    |
| 5.18.5-200.fc36.x86_64  | 30       | 0.7%    |
| 5.12.13-300.fc34.x86_64 | 30       | 0.7%    |
| 5.8.18-300.fc33.x86_64  | 29       | 0.68%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.68%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.66%   |
| 6.0.8-300.fc37.x86_64   | 27       | 0.63%   |
| 6.0.9-300.fc37.x86_64   | 26       | 0.61%   |
| 5.9.11-200.fc33.x86_64  | 26       | 0.61%   |
| 5.3.16-300.fc31.x86_64  | 26       | 0.61%   |
| 6.0.7-301.fc37.x86_64   | 25       | 0.59%   |
| 5.7.10-201.fc32.x86_64  | 25       | 0.59%   |
| 5.16.16-200.fc35.x86_64 | 25       | 0.59%   |
| 5.11.11-200.fc33.x86_64 | 25       | 0.59%   |
| 5.9.8-200.fc33.x86_64   | 24       | 0.56%   |
| 5.11.16-300.fc34.x86_64 | 24       | 0.56%   |
| 5.19.6-200.fc36.x86_64  | 23       | 0.54%   |
| 5.17.6-300.fc36.x86_64  | 23       | 0.54%   |
| 5.14.9-200.fc34.x86_64  | 23       | 0.54%   |
| 5.12.8-300.fc34.x86_64  | 23       | 0.54%   |
| 5.8.11-200.fc32.x86_64  | 22       | 0.52%   |
| 5.7.15-200.fc32.x86_64  | 22       | 0.52%   |
| 5.17.4-200.fc35.x86_64  | 22       | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 67       | 1.57%   |
| 5.16.18 | 65       | 1.53%   |
| 5.17.5  | 63       | 1.48%   |
| 5.19.16 | 57       | 1.34%   |
| 5.8.15  | 53       | 1.25%   |
| 6.0.15  | 49       | 1.15%   |
| 6.0.12  | 48       | 1.13%   |
| 5.8.18  | 47       | 1.1%    |
| 5.18.13 | 43       | 1.01%   |
| 5.8.16  | 40       | 0.94%   |
| 5.13.12 | 40       | 0.94%   |
| 5.19.9  | 39       | 0.92%   |
| 6.0.8   | 38       | 0.89%   |
| 6.0.7   | 38       | 0.89%   |
| 6.0.5   | 38       | 0.89%   |
| 5.14.10 | 38       | 0.89%   |
| 5.11.12 | 37       | 0.87%   |
| 5.11.11 | 37       | 0.87%   |
| 6.0.9   | 35       | 0.82%   |
| 6.0.11  | 34       | 0.8%    |
| 5.18.5  | 34       | 0.8%    |
| 5.8.4   | 33       | 0.78%   |
| 5.18.16 | 33       | 0.78%   |
| 5.18.11 | 32       | 0.75%   |
| 5.14.18 | 32       | 0.75%   |
| 5.12.13 | 32       | 0.75%   |
| 5.6.19  | 31       | 0.73%   |
| 6.0.10  | 30       | 0.7%    |
| 5.12.8  | 30       | 0.7%    |
| 5.15.6  | 29       | 0.68%   |
| 5.9.11  | 28       | 0.66%   |
| 5.19.6  | 28       | 0.66%   |
| 5.17.6  | 28       | 0.66%   |
| 5.14.9  | 28       | 0.66%   |
| 5.6.6   | 27       | 0.63%   |
| 5.17.11 | 27       | 0.63%   |
| 5.11.16 | 27       | 0.63%   |
| 5.9.8   | 26       | 0.61%   |
| 5.7.15  | 26       | 0.61%   |
| 5.3.16  | 26       | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 334      | 8.29%   |
| 5.8     | 307      | 7.62%   |
| 5.11    | 257      | 6.38%   |
| 5.19    | 253      | 6.28%   |
| 5.18    | 249      | 6.18%   |
| 5.17    | 245      | 6.08%   |
| 5.16    | 223      | 5.53%   |
| 5.9     | 209      | 5.19%   |
| 5.10    | 206      | 5.11%   |
| 5.14    | 202      | 5.01%   |
| 5.6     | 195      | 4.84%   |
| 5.13    | 191      | 4.74%   |
| 5.15    | 177      | 4.39%   |
| 5.12    | 176      | 4.37%   |
| 5.7     | 171      | 4.24%   |
| 5.4     | 135      | 3.35%   |
| 5.5     | 121      | 3%      |
| 5.3     | 115      | 2.85%   |
| 6.1     | 56       | 1.39%   |
| 5.2     | 55       | 1.36%   |
| 5.0     | 48       | 1.19%   |
| 5.1     | 25       | 0.62%   |
| 4.19    | 22       | 0.55%   |
| 4.18    | 19       | 0.47%   |
| 4.20    | 18       | 0.45%   |
| 4.16    | 5        | 0.12%   |
| 4.15    | 3        | 0.07%   |
| 4.17    | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 4.11    | 2        | 0.05%   |
| 6.2     | 1        | 0.02%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |
| 3.17    | 1        | 0.02%   |
| 2.6.35  | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3213     | 99.88%  |
| i686    | 3        | 0.09%   |
| Unknown | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2193     | 66.15%  |
| KDE5                         | 413      | 12.46%  |
| Unknown                      | 251      | 7.57%   |
| KDE                          | 115      | 3.47%   |
| XFCE                         | 85       | 2.56%   |
| X-Cinnamon                   | 65       | 1.96%   |
| Cinnamon                     | 58       | 1.75%   |
| MATE                         | 56       | 1.69%   |
| GNOME Classic                | 22       | 0.66%   |
| LXQt                         | 10       | 0.3%    |
| LXDE                         | 10       | 0.3%    |
| Deepin                       | 10       | 0.3%    |
| i3                           | 8        | 0.24%   |
| KDE4                         | 6        | 0.18%   |
| awesome                      | 3        | 0.09%   |
| openbox                      | 2        | 0.06%   |
| DWM                          | 2        | 0.06%   |
| qtile                        | 1        | 0.03%   |
| Pantheon                     | 1        | 0.03%   |
| NsCDE                        | 1        | 0.03%   |
| GNUstep                      | 1        | 0.03%   |
| GNOME Flashback              | 1        | 0.03%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1659     | 49.07%  |
| X11     | 1472     | 43.54%  |
| Unknown | 130      | 3.85%   |
| Tty     | 115      | 3.4%    |
| Web     | 5        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1825     | 55.14%  |
| GDM     | 986      | 29.79%  |
| SDDM    | 262      | 7.92%   |
| LightDM | 147      | 4.44%   |
| TDM     | 73       | 2.21%   |
| XDM     | 7        | 0.21%   |
| KDM     | 7        | 0.21%   |
| LXDM    | 2        | 0.06%   |
| SLiM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1519     | 46.31%  |
| Unknown | 245      | 7.47%   |
| en_GB   | 234      | 7.13%   |
| pt_BR   | 163      | 4.97%   |
| ru_RU   | 149      | 4.54%   |
| de_DE   | 143      | 4.36%   |
| fr_FR   | 107      | 3.26%   |
| en_AU   | 95       | 2.9%    |
| en_CA   | 93       | 2.84%   |
| it_IT   | 69       | 2.1%    |
| pl_PL   | 53       | 1.62%   |
| es_ES   | 45       | 1.37%   |
| cs_CZ   | 24       | 0.73%   |
| en_IN   | 21       | 0.64%   |
| en_NZ   | 19       | 0.58%   |
| es_MX   | 17       | 0.52%   |
| nl_BE   | 13       | 0.4%    |
| ja_JP   | 13       | 0.4%    |
| es_AR   | 13       | 0.4%    |
| fi_FI   | 12       | 0.37%   |
| en_IE   | 12       | 0.37%   |
| es_CO   | 11       | 0.34%   |
| uk_UA   | 10       | 0.3%    |
| nl_NL   | 10       | 0.3%    |
| C       | 10       | 0.3%    |
| tr_TR   | 9        | 0.27%   |
| sv_SE   | 9        | 0.27%   |
| de_AT   | 9        | 0.27%   |
| zh_CN   | 8        | 0.24%   |
| ru_UA   | 8        | 0.24%   |
| hu_HU   | 8        | 0.24%   |
| fr_CH   | 8        | 0.24%   |
| sk_SK   | 6        | 0.18%   |
| pt_PT   | 6        | 0.18%   |
| es_CL   | 6        | 0.18%   |
| en_DK   | 6        | 0.18%   |
| el_GR   | 5        | 0.15%   |
| nb_NO   | 4        | 0.12%   |
| ko_KR   | 4        | 0.12%   |
| fr_CA   | 4        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 2045     | 62.52%  |
| BIOS | 1226     | 37.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 1658     | 50.15%  |
| Ext4                | 1336     | 40.41%  |
| Xfs                 | 165      | 4.99%   |
| Unknown             | 132      | 3.99%   |
| Overlay             | 5        | 0.15%   |
| Ext3                | 4        | 0.12%   |
| Zfs                 | 3        | 0.09%   |
| F2fs                | 2        | 0.06%   |
| Fuse.fuse-overlayfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1785     | 53.88%  |
| GPT     | 1179     | 35.59%  |
| MBR     | 349      | 10.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2785     | 84.45%  |
| Yes       | 513      | 15.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2577     | 78.71%  |
| Yes       | 697      | 21.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 952      | 29.6%   |
| Gigabyte Technology | 646      | 20.09%  |
| MSI                 | 471      | 14.65%  |
| ASRock              | 335      | 10.42%  |
| Dell                | 223      | 6.93%   |
| Hewlett-Packard     | 170      | 5.29%   |
| Lenovo              | 90       | 2.8%    |
| Intel               | 52       | 1.62%   |
| Unknown             | 39       | 1.21%   |
| Acer                | 33       | 1.03%   |
| Biostar             | 17       | 0.53%   |
| Pegatron            | 15       | 0.47%   |
| ECS                 | 15       | 0.47%   |
| BESSTAR Tech        | 13       | 0.4%    |
| Fujitsu             | 11       | 0.34%   |
| Foxconn             | 11       | 0.34%   |
| Supermicro          | 10       | 0.31%   |
| Huanan              | 10       | 0.31%   |
| Shuttle             | 8        | 0.25%   |
| Positivo            | 7        | 0.22%   |
| Apple               | 7        | 0.22%   |
| Alienware           | 7        | 0.22%   |
| PCWare              | 4        | 0.12%   |
| Medion              | 4        | 0.12%   |
| EVGA                | 4        | 0.12%   |
| System76            | 3        | 0.09%   |
| Packard Bell        | 3        | 0.09%   |
| MACHINIST           | 3        | 0.09%   |
| eMachines           | 3        | 0.09%   |
| AZW                 | 3        | 0.09%   |
| ABIT                | 3        | 0.09%   |
| ZOTAC               | 2        | 0.06%   |
| XFX                 | 2        | 0.06%   |
| OEM                 | 2        | 0.06%   |
| JINGSHA             | 2        | 0.06%   |
| Itautec             | 2        | 0.06%   |
| Google              | 2        | 0.06%   |
| Gateway             | 2        | 0.06%   |
| ASRockRack          | 2        | 0.06%   |
| AMI                 | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 98       | 3.05%   |
| Unknown                        | 42       | 1.31%   |
| MSI MS-7C37                    | 35       | 1.09%   |
| ASUS TUF Gaming X570-PLUS      | 24       | 0.75%   |
| Gigabyte B450M DS3H            | 23       | 0.72%   |
| MSI MS-7C02                    | 21       | 0.65%   |
| MSI MS-7A38                    | 20       | 0.62%   |
| MSI MS-7B86                    | 17       | 0.53%   |
| Dell OptiPlex 7010             | 17       | 0.53%   |
| MSI MS-7C91                    | 15       | 0.47%   |
| MSI MS-7C56                    | 15       | 0.47%   |
| ASUS ROG STRIX B550-F GAMING   | 15       | 0.47%   |
| ASUS PRIME X370-PRO            | 15       | 0.47%   |
| ASUS ROG STRIX B450-F GAMING   | 14       | 0.44%   |
| MSI MS-7C84                    | 13       | 0.4%    |
| MSI MS-7B79                    | 13       | 0.4%    |
| Dell OptiPlex 9020             | 13       | 0.4%    |
| Gigabyte B450 AORUS ELITE      | 12       | 0.37%   |
| Gigabyte A320M-S2H             | 12       | 0.37%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.37%   |
| ASUS ROG STRIX X570-F GAMING   | 12       | 0.37%   |
| ASUS ROG STRIX X570-E GAMING   | 12       | 0.37%   |
| ASUS ROG STRIX B550-I GAMING   | 12       | 0.37%   |
| ASUS PRIME X470-PRO            | 12       | 0.37%   |
| Gigabyte X570 I AORUS PRO WIFI | 11       | 0.34%   |
| Gigabyte B450 AORUS M          | 11       | 0.34%   |
| Gigabyte 970A-DS3P             | 11       | 0.34%   |
| ASUS ROG CROSSHAIR VII HERO    | 11       | 0.34%   |
| ASRock B450M Pro4              | 11       | 0.34%   |
| MSI MS-7B89                    | 10       | 0.31%   |
| MSI MS-7A34                    | 10       | 0.31%   |
| Gigabyte X570 AORUS MASTER     | 10       | 0.31%   |
| Gigabyte X570 AORUS ELITE      | 10       | 0.31%   |
| ASUS Z170-A                    | 10       | 0.31%   |
| ASUS TUF Gaming B550-PLUS      | 10       | 0.31%   |
| ASUS PRIME B350-PLUS           | 10       | 0.31%   |
| Dell OptiPlex 3020             | 9        | 0.28%   |
| ASUS PRIME A320M-K             | 9        | 0.28%   |
| ASRock B450M Steel Legend      | 9        | 0.28%   |
| MSI MS-7C52                    | 8        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 193      | 6%      |
| ASUS PRIME         | 187      | 5.81%   |
| Dell OptiPlex      | 114      | 3.54%   |
| ASUS TUF           | 102      | 3.17%   |
| ASUS All           | 98       | 3.05%   |
| Gigabyte X570      | 61       | 1.9%    |
| Lenovo ThinkCentre | 51       | 1.59%   |
| Dell Precision     | 43       | 1.34%   |
| HP Compaq          | 42       | 1.31%   |
| Gigabyte B450      | 42       | 1.31%   |
| Unknown            | 42       | 1.31%   |
| Gigabyte B450M     | 36       | 1.12%   |
| MSI MS-7C37        | 35       | 1.09%   |
| HP EliteDesk       | 31       | 0.96%   |
| Dell Inspiron      | 25       | 0.78%   |
| Acer Aspire        | 24       | 0.75%   |
| Dell XPS           | 23       | 0.72%   |
| ASRock X570        | 23       | 0.72%   |
| ASRock B450M       | 23       | 0.72%   |
| MSI MS-7C02        | 21       | 0.65%   |
| MSI MS-7A38        | 20       | 0.62%   |
| Gigabyte B550      | 20       | 0.62%   |
| HP ProDesk         | 18       | 0.56%   |
| ASRock B450        | 18       | 0.56%   |
| MSI MS-7B86        | 17       | 0.53%   |
| ASUS P8Z77-V       | 16       | 0.5%    |
| MSI MS-7C91        | 15       | 0.47%   |
| MSI MS-7C56        | 15       | 0.47%   |
| ASUS M5A78L-M      | 15       | 0.47%   |
| Gigabyte Z390      | 14       | 0.44%   |
| Gigabyte A320M-S2H | 14       | 0.44%   |
| ASUS SABERTOOTH    | 14       | 0.44%   |
| ASUS M5A97         | 14       | 0.44%   |
| MSI MS-7C84        | 13       | 0.4%    |
| MSI MS-7B79        | 13       | 0.4%    |
| Gigabyte B550M     | 13       | 0.4%    |
| ASUS P8Z68-V       | 13       | 0.4%    |
| ASUS Maximus       | 13       | 0.4%    |
| Gigabyte X470      | 12       | 0.37%   |
| Gigabyte 970A-DS3P | 12       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 449      | 13.96%  |
| 2019    | 394      | 12.25%  |
| 2020    | 328      | 10.2%   |
| 2017    | 280      | 8.71%   |
| 2012    | 258      | 8.02%   |
| 2013    | 228      | 7.09%   |
| 2014    | 210      | 6.53%   |
| 2021    | 180      | 5.6%    |
| 2011    | 165      | 5.13%   |
| 2015    | 153      | 4.76%   |
| 2016    | 148      | 4.6%    |
| 2009    | 114      | 3.54%   |
| 2010    | 107      | 3.33%   |
| 2008    | 81       | 2.52%   |
| 2022    | 60       | 1.87%   |
| 2007    | 37       | 1.15%   |
| 2006    | 18       | 0.56%   |
| 2005    | 4        | 0.12%   |
| Unknown | 2        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3216     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3045     | 93.87%  |
| Enabled  | 199      | 6.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3214     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 996      | 30.23%  |
| 32.01-64.0      | 751      | 22.79%  |
| 8.01-16.0       | 574      | 17.42%  |
| 4.01-8.0        | 363      | 11.02%  |
| 64.01-256.0     | 246      | 7.47%   |
| 3.01-4.0        | 212      | 6.43%   |
| 24.01-32.0      | 111      | 3.37%   |
| 1.01-2.0        | 20       | 0.61%   |
| 2.01-3.0        | 16       | 0.49%   |
| Unknown         | 4        | 0.12%   |
| More than 256.0 | 1        | 0.03%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1015     | 27.14%  |
| 2.01-3.0    | 944      | 25.24%  |
| 3.01-4.0    | 738      | 19.73%  |
| 1.01-2.0    | 519      | 13.88%  |
| 8.01-16.0   | 346      | 9.25%   |
| 16.01-24.0  | 65       | 1.74%   |
| 0.51-1.0    | 54       | 1.44%   |
| 24.01-32.0  | 25       | 0.67%   |
| 32.01-64.0  | 13       | 0.35%   |
| 0.01-0.5    | 12       | 0.32%   |
| Unknown     | 6        | 0.16%   |
| 64.01-256.0 | 3        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1047     | 30.71%  |
| 1      | 921      | 27.02%  |
| 3      | 694      | 20.36%  |
| 4      | 367      | 10.77%  |
| 5      | 175      | 5.13%   |
| 6      | 90       | 2.64%   |
| 7      | 50       | 1.47%   |
| 8      | 24       | 0.7%    |
| 9      | 11       | 0.32%   |
| 0      | 10       | 0.29%   |
| 10     | 5        | 0.15%   |
| 11     | 4        | 0.12%   |
| 12     | 3        | 0.09%   |
| 15     | 2        | 0.06%   |
| 14     | 2        | 0.06%   |
| 27     | 1        | 0.03%   |
| 24     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2077     | 63.61%  |
| Yes       | 1188     | 36.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3196     | 99.35%  |
| No        | 21       | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1730     | 52.94%  |
| Yes       | 1538     | 47.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1937     | 59.07%  |
| Yes       | 1342     | 40.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 774      | 23.93%  |
| Germany     | 251      | 7.76%   |
| Brazil      | 234      | 7.23%   |
| Russia      | 202      | 6.24%   |
| Canada      | 134      | 4.14%   |
| UK          | 132      | 4.08%   |
| France      | 128      | 3.96%   |
| Italy       | 116      | 3.59%   |
| Australia   | 105      | 3.25%   |
| Poland      | 94       | 2.91%   |
| Spain       | 78       | 2.41%   |
| Sweden      | 54       | 1.67%   |
| Netherlands | 49       | 1.51%   |
| India       | 48       | 1.48%   |
| Czechia     | 46       | 1.42%   |
| Switzerland | 45       | 1.39%   |
| Ukraine     | 38       | 1.17%   |
| Belgium     | 37       | 1.14%   |
| Finland     | 33       | 1.02%   |
| Austria     | 32       | 0.99%   |
| Romania     | 31       | 0.96%   |
| Mexico      | 31       | 0.96%   |
| Norway      | 29       | 0.9%    |
| Argentina   | 29       | 0.9%    |
| Turkey      | 27       | 0.83%   |
| Greece      | 22       | 0.68%   |
| Japan       | 21       | 0.65%   |
| Portugal    | 20       | 0.62%   |
| New Zealand | 20       | 0.62%   |
| Hungary     | 18       | 0.56%   |
| Indonesia   | 17       | 0.53%   |
| Colombia    | 14       | 0.43%   |
| Philippines | 13       | 0.4%    |
| Denmark     | 13       | 0.4%    |
| Chile       | 13       | 0.4%    |
| Slovakia    | 12       | 0.37%   |
| Belarus     | 12       | 0.37%   |
| China       | 11       | 0.34%   |
| Israel      | 10       | 0.31%   |
| Ireland     | 10       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 51       | 1.47%   |
| Sydney         | 41       | 1.18%   |
| Berlin         | 31       | 0.89%   |
| St Petersburg  | 26       | 0.75%   |
| Warsaw         | 25       | 0.72%   |
| Sao Paulo      | 23       | 0.66%   |
| Vienna         | 21       | 0.61%   |
| Brisbane       | 18       | 0.52%   |
| Paris          | 17       | 0.49%   |
| Hamburg        | 17       | 0.49%   |
| Toronto        | 16       | 0.46%   |
| Melbourne      | 16       | 0.46%   |
| Zurich         | 15       | 0.43%   |
| Prague         | 15       | 0.43%   |
| Auckland       | 15       | 0.43%   |
| Rome           | 14       | 0.4%    |
| Athens         | 14       | 0.4%    |
| Rio de Janeiro | 13       | 0.37%   |
| Porto Alegre   | 13       | 0.37%   |
| Madrid         | 13       | 0.37%   |
| London         | 13       | 0.37%   |
| Buenos Aires   | 13       | 0.37%   |
| Munich         | 12       | 0.35%   |
| Helsinki       | 12       | 0.35%   |
| Amsterdam      | 12       | 0.35%   |
| Vancouver      | 11       | 0.32%   |
| Milan          | 11       | 0.32%   |
| Krakow         | 11       | 0.32%   |
| Istanbul       | 11       | 0.32%   |
| Yekaterinburg  | 10       | 0.29%   |
| Wroclaw        | 10       | 0.29%   |
| Seattle        | 10       | 0.29%   |
| Montreal       | 10       | 0.29%   |
| Los Angeles    | 10       | 0.29%   |
| Cologne        | 10       | 0.29%   |
| Budapest       | 10       | 0.29%   |
| Bucharest      | 10       | 0.29%   |
| Belo Horizonte | 10       | 0.29%   |
| Ufa            | 9        | 0.26%   |
| Dallas         | 9        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 1222     | 2385   | 18.63%  |
| WDC                       | 1206     | 2329   | 18.38%  |
| Seagate                   | 1096     | 2018   | 16.71%  |
| Kingston                  | 450      | 679    | 6.86%   |
| Toshiba                   | 339      | 529    | 5.17%   |
| Crucial                   | 338      | 518    | 5.15%   |
| SanDisk                   | 312      | 437    | 4.76%   |
| Hitachi                   | 178      | 292    | 2.71%   |
| Intel                     | 152      | 265    | 2.32%   |
| A-DATA Technology         | 113      | 159    | 1.72%   |
| Phison                    | 107      | 150    | 1.63%   |
| HGST                      | 61       | 125    | 0.93%   |
| Unknown                   | 50       | 80     | 0.76%   |
| Corsair                   | 50       | 75     | 0.76%   |
| SPCC                      | 49       | 79     | 0.75%   |
| Micron/Crucial Technology | 46       | 62     | 0.7%    |
| China                     | 42       | 55     | 0.64%   |
| SK hynix                  | 40       | 46     | 0.61%   |
| OCZ                       | 36       | 47     | 0.55%   |
| Silicon Motion            | 35       | 47     | 0.53%   |
| PNY                       | 33       | 46     | 0.5%    |
| Patriot                   | 32       | 49     | 0.49%   |
| Micron Technology         | 32       | 46     | 0.49%   |
| Phison Electronics        | 27       | 42     | 0.41%   |
| XPG                       | 23       | 33     | 0.35%   |
| Maxtor                    | 23       | 27     | 0.35%   |
| Transcend                 | 20       | 27     | 0.3%    |
| Plextor                   | 19       | 27     | 0.29%   |
| Team                      | 18       | 28     | 0.27%   |
| Intenso                   | 18       | 26     | 0.27%   |
| Hewlett-Packard           | 18       | 22     | 0.27%   |
| Gigabyte Technology       | 18       | 32     | 0.27%   |
| GOODRAM                   | 17       | 25     | 0.26%   |
| ASMT                      | 17       | 19     | 0.26%   |
| Apacer                    | 14       | 25     | 0.21%   |
| SABRENT                   | 13       | 16     | 0.2%    |
| KingSpec                  | 13       | 20     | 0.2%    |
| Realtek Semiconductor     | 11       | 13     | 0.17%   |
| LITEON                    | 11       | 14     | 0.17%   |
| KingDian                  | 10       | 11     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 116      | 1.46%   |
| Samsung SSD 860 EVO 500GB                           | 96       | 1.21%   |
| Kingston SA400S37240G 240GB SSD                     | 96       | 1.21%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91       | 1.15%   |
| Samsung NVMe SSD Drive 500GB                        | 91       | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                      | 84       | 1.06%   |
| Samsung SSD 850 EVO 500GB                           | 83       | 1.05%   |
| Samsung SSD 860 EVO 1TB                             | 80       | 1.01%   |
| Seagate ST500DM002-1BD142 500GB                     | 70       | 0.88%   |
| Samsung NVMe SSD Drive 1TB                          | 69       | 0.87%   |
| Toshiba DT01ACA100 1TB                              | 60       | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 59       | 0.74%   |
| Kingston SA400S37120G 120GB SSD                     | 59       | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 54       | 0.68%   |
| Crucial CT500MX500SSD1 500GB                        | 48       | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 47       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                         | 46       | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB                      | 44       | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                      | 41       | 0.52%   |
| SanDisk NVMe SSD Drive 500GB                        | 38       | 0.48%   |
| SanDisk NVMe SSD Drive 1TB                          | 38       | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 38       | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                    | 38       | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB                      | 36       | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 36       | 0.45%   |
| Toshiba HDWD110 1TB                                 | 35       | 0.44%   |
| Toshiba DT01ACA200 2TB                              | 35       | 0.44%   |
| Samsung SSD 860 QVO 1TB                             | 34       | 0.43%   |
| Samsung SSD 840 EVO 250GB                           | 34       | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 33       | 0.42%   |
| Seagate ST3500418AS 500GB                           | 33       | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                      | 33       | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 33       | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 33       | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 31       | 0.39%   |
| Seagate ST31000528AS 1TB                            | 30       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 29       | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 28       | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 28       | 0.35%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 27       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1064     | 1953   | 37.03%  |
| WDC                 | 1036     | 1974   | 36.06%  |
| Toshiba             | 292      | 443    | 10.16%  |
| Hitachi             | 178      | 292    | 6.2%    |
| Samsung Electronics | 131      | 210    | 4.56%   |
| HGST                | 61       | 125    | 2.12%   |
| Maxtor              | 22       | 25     | 0.77%   |
| Unknown             | 15       | 21     | 0.52%   |
| ASMT                | 13       | 14     | 0.45%   |
| SABRENT             | 11       | 13     | 0.38%   |
| Fujitsu             | 9        | 11     | 0.31%   |
| Hewlett-Packard     | 5        | 6      | 0.17%   |
| Apple               | 4        | 4      | 0.14%   |
| MaxDigital          | 3        | 3      | 0.1%    |
| JMicron Technology  | 3        | 7      | 0.1%    |
| Intenso             | 3        | 6      | 0.1%    |
| USB3.0              | 2        | 2      | 0.07%   |
| USB                 | 2        | 2      | 0.07%   |
| LaCie               | 2        | 4      | 0.07%   |
| ASMT109x            | 2        | 2      | 0.07%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| Unknown (583)       | 1        | 1      | 0.03%   |
| Synology            | 1        | 1      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| PHD 3.0             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 735      | 1301   | 29.29%  |
| Kingston            | 373      | 570    | 14.87%  |
| Crucial             | 305      | 472    | 12.16%  |
| SanDisk             | 185      | 240    | 7.37%   |
| WDC                 | 168      | 247    | 6.7%    |
| A-DATA Technology   | 93       | 131    | 3.71%   |
| Intel               | 70       | 134    | 2.79%   |
| China               | 42       | 55     | 1.67%   |
| SPCC                | 39       | 60     | 1.55%   |
| OCZ                 | 36       | 47     | 1.43%   |
| PNY                 | 33       | 45     | 1.32%   |
| Toshiba             | 30       | 41     | 1.2%    |
| Patriot             | 29       | 45     | 1.16%   |
| Corsair             | 27       | 41     | 1.08%   |
| Micron Technology   | 25       | 36     | 1%      |
| Transcend           | 20       | 27     | 0.8%    |
| SK hynix            | 18       | 19     | 0.72%   |
| Plextor             | 17       | 24     | 0.68%   |
| GOODRAM             | 17       | 25     | 0.68%   |
| Team                | 16       | 26     | 0.64%   |
| Seagate             | 13       | 16     | 0.52%   |
| KingSpec            | 13       | 20     | 0.52%   |
| Intenso             | 12       | 17     | 0.48%   |
| Apacer              | 12       | 22     | 0.48%   |
| LITEON              | 11       | 14     | 0.44%   |
| Gigabyte Technology | 11       | 19     | 0.44%   |
| KingDian            | 10       | 11     | 0.4%    |
| Unknown             | 9        | 9      | 0.36%   |
| Hewlett-Packard     | 8        | 9      | 0.32%   |
| Verbatim            | 7        | 10     | 0.28%   |
| Mushkin             | 7        | 11     | 0.28%   |
| LITEONIT            | 7        | 8      | 0.28%   |
| Lexar               | 7        | 11     | 0.28%   |
| Leven               | 7        | 8      | 0.28%   |
| OWC                 | 4        | 6      | 0.16%   |
| KingFast            | 4        | 4      | 0.16%   |
| JMicron Technology  | 4        | 4      | 0.16%   |
| Drevo               | 4        | 4      | 0.16%   |
| Radeon              | 3        | 4      | 0.12%   |
| Inateck             | 3        | 8      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2170     | 5135   | 39.58%  |
| SSD     | 2013     | 3898   | 36.72%  |
| NVMe    | 1203     | 2079   | 21.94%  |
| Unknown | 88       | 131    | 1.61%   |
| MMC     | 8        | 9      | 0.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2878     | 8746   | 66.21%  |
| NVMe | 1202     | 2075   | 27.65%  |
| SAS  | 259      | 422    | 5.96%   |
| MMC  | 8        | 9      | 0.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2122     | 4365   | 45.1%   |
| 0.51-1.0   | 1423     | 2506   | 30.24%  |
| 1.01-2.0   | 567      | 942    | 12.05%  |
| 3.01-4.0   | 246      | 463    | 5.23%   |
| 2.01-3.0   | 160      | 316    | 3.4%    |
| 4.01-10.0  | 158      | 378    | 3.36%   |
| 10.01-20.0 | 29       | 63     | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 628      | 18.14%  |
| 1001-2000      | 615      | 17.76%  |
| 251-500        | 536      | 15.48%  |
| More than 3000 | 523      | 15.11%  |
| 101-250        | 453      | 13.08%  |
| 2001-3000      | 289      | 8.35%   |
| 1-20           | 165      | 4.77%   |
| Unknown        | 130      | 3.76%   |
| 51-100         | 89       | 2.57%   |
| 21-50          | 34       | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 632      | 17.39%  |
| 101-250        | 499      | 13.73%  |
| 21-50          | 459      | 12.63%  |
| 251-500        | 449      | 12.35%  |
| 501-1000       | 448      | 12.32%  |
| 51-100         | 394      | 10.84%  |
| 1001-2000      | 327      | 9%      |
| More than 3000 | 169      | 4.65%   |
| Unknown        | 130      | 3.58%   |
| 2001-3000      | 127      | 3.49%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 15       | 40     | 3.13%   |
| Seagate ST3500418AS 500GB           | 7        | 12     | 1.46%   |
| Seagate ST31000528AS 1TB            | 7        | 9      | 1.46%   |
| Samsung Electronics SSD 870 EVO 1TB | 7        | 7      | 1.46%   |
| Seagate ST31000524AS 1TB            | 5        | 5      | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 5      | 1.04%   |
| Samsung Electronics HD322HJ 320GB   | 5        | 7      | 1.04%   |
| Intel SSDSC2CT120A3 120GB           | 5        | 25     | 1.04%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 4      | 0.84%   |
| Toshiba MQ01ABD050 500GB            | 4        | 5      | 0.84%   |
| Seagate ST31500341AS 1TB            | 4        | 4      | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB      | 4        | 4      | 0.84%   |
| Samsung Electronics HD501LJ 500GB   | 4        | 27     | 0.84%   |
| Crucial CT275MX300SSD1 275GB        | 4        | 4      | 0.84%   |
| Crucial CT240M500SSD1 240GB         | 4        | 4      | 0.84%   |
| Crucial CT128MX100SSD1 128GB        | 4        | 6      | 0.84%   |
| WDC WD20EZRX-00D8PB0 2TB            | 3        | 4      | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 4      | 0.63%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 3        | 3      | 0.63%   |
| Toshiba DT01ACA100 1TB              | 3        | 3      | 0.63%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 3      | 0.63%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.63%   |
| Hitachi HDS721010DLE630 1TB         | 3        | 5      | 0.63%   |
| Hitachi HDS721010CLA332 1TB         | 3        | 3      | 0.63%   |
| Hitachi HDP725050GLA360 500GB       | 3        | 3      | 0.63%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 2      | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.42%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 2      | 0.42%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 2      | 0.42%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2        | 2      | 0.42%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2        | 2      | 0.42%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 6      | 0.42%   |
| WDC WD1600AVVS-63L2B0 160GB         | 2        | 5      | 0.42%   |
| WDC WD1600AABS-00H4A0 160GB         | 2        | 2      | 0.42%   |
| WDC WD10EZRX-00A8LB0 1TB            | 2        | 2      | 0.42%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 2        | 2      | 0.42%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 2      | 0.42%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 2      | 0.42%   |
| WDC WD10EZEX-00MFCA0 1TB            | 2        | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 122      | 190    | 27.05%  |
| WDC                 | 115      | 171    | 25.5%   |
| Samsung Electronics | 42       | 73     | 9.31%   |
| Hitachi             | 34       | 47     | 7.54%   |
| Toshiba             | 28       | 33     | 6.21%   |
| Intel               | 19       | 41     | 4.21%   |
| Crucial             | 18       | 20     | 3.99%   |
| SanDisk             | 12       | 12     | 2.66%   |
| Kingston            | 10       | 11     | 2.22%   |
| A-DATA Technology   | 8        | 8      | 1.77%   |
| Maxtor              | 6        | 6      | 1.33%   |
| Corsair             | 5        | 8      | 1.11%   |
| OCZ                 | 4        | 5      | 0.89%   |
| SK hynix            | 3        | 3      | 0.67%   |
| LITEON              | 3        | 3      | 0.67%   |
| HGST                | 3        | 5      | 0.67%   |
| SPCC                | 2        | 3      | 0.44%   |
| OCZ-VERTEX3         | 2        | 2      | 0.44%   |
| Fujitsu             | 2        | 2      | 0.44%   |
| Verbatim            | 1        | 1      | 0.22%   |
| Unknown             | 1        | 1      | 0.22%   |
| Team                | 1        | 4      | 0.22%   |
| PNY                 | 1        | 1      | 0.22%   |
| ORICO               | 1        | 1      | 0.22%   |
| Micron Technology   | 1        | 1      | 0.22%   |
| KingDian            | 1        | 1      | 0.22%   |
| Hewlett-Packard     | 1        | 1      | 0.22%   |
| BIWIN               | 1        | 1      | 0.22%   |
| ASMT                | 1        | 1      | 0.22%   |
| ASMedia             | 1        | 1      | 0.22%   |
| Apacer              | 1        | 1      | 0.22%   |
| AMD                 | 1        | 2      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 122      | 190    | 36.31%  |
| WDC                 | 114      | 170    | 33.93%  |
| Hitachi             | 34       | 47     | 10.12%  |
| Toshiba             | 28       | 33     | 8.33%   |
| Samsung Electronics | 25       | 54     | 7.44%   |
| Maxtor              | 6        | 6      | 1.79%   |
| HGST                | 3        | 5      | 0.89%   |
| Fujitsu             | 2        | 2      | 0.6%    |
| Hewlett-Packard     | 1        | 1      | 0.3%    |
| ASMT                | 1        | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 304      | 509    | 72.73%  |
| SSD  | 104      | 141    | 24.88%  |
| NVMe | 10       | 10     | 2.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 12.5%   |
| Toshiba HDWD130 3TB               | 1        | 1      | 12.5%   |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 12.5%   |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 12.5%   |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 12.5%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 6      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 25%     |
| Samsung Electronics | 2        | 4      | 25%     |
| WDC                 | 1        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| SPCC                | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 6      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1873     | 6268   | 50.01%  |
| Works    | 1459     | 4308   | 38.96%  |
| Malfunc  | 406      | 660    | 10.84%  |
| Failed   | 7        | 16     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1812     | 36.22%  |
| AMD                            | 1373     | 27.44%  |
| Samsung Electronics            | 552      | 11.03%  |
| ASMedia Technology             | 215      | 4.3%    |
| SanDisk                        | 198      | 3.96%   |
| Phison Electronics             | 164      | 3.28%   |
| Marvell Technology Group       | 103      | 2.06%   |
| Kingston Technology Company    | 90       | 1.8%    |
| JMicron Technology             | 79       | 1.58%   |
| Micron/Crucial Technology      | 78       | 1.56%   |
| Nvidia                         | 51       | 1.02%   |
| Silicon Motion                 | 45       | 0.9%    |
| ADATA Technology               | 41       | 0.82%   |
| Toshiba America Info Systems   | 25       | 0.5%    |
| SK hynix                       | 22       | 0.44%   |
| LSI Logic / Symbios Logic      | 20       | 0.4%    |
| Realtek Semiconductor          | 19       | 0.38%   |
| Broadcom / LSI                 | 18       | 0.36%   |
| Seagate Technology             | 14       | 0.28%   |
| Silicon Image                  | 12       | 0.24%   |
| VIA Technologies               | 10       | 0.2%    |
| Micron Technology              | 9        | 0.18%   |
| MAXIO Technology (Hangzhou)    | 9        | 0.18%   |
| Lite-On Technology             | 9        | 0.18%   |
| KIOXIA                         | 6        | 0.12%   |
| Adaptec                        | 6        | 0.12%   |
| Integrated Technology Express  | 4        | 0.08%   |
| Hewlett-Packard                | 3        | 0.06%   |
| ULi Electronics                | 2        | 0.04%   |
| Solid State Storage Technology | 2        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.04%   |
| INNOGRIT                       | 2        | 0.04%   |
| HighPoint Technologies         | 2        | 0.04%   |
| 3ware                          | 2        | 0.04%   |
| Union Memory (Shenzhen)        | 1        | 0.02%   |
| Solidigm                       | 1        | 0.02%   |
| Netac Technology               | 1        | 0.02%   |
| Biwin Storage Technology       | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 885      | 14.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 347      | 5.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 347      | 5.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 214      | 3.48%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 207      | 3.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 190      | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 183      | 2.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 176      | 2.86%   |
| Intel SATA Controller [RAID mode]                                                       | 140      | 2.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 135      | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 133      | 2.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 123      | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 123      | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 122      | 1.98%   |
| Phison E12 NVMe Controller                                                              | 95       | 1.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 93       | 1.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 93       | 1.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 89       | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 84       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 75       | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 61       | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 58       | 0.94%   |
| AMD FCH SATA Controller D                                                               | 56       | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 54       | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                                 | 51       | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 49       | 0.8%    |
| Intel SSD 660P Series                                                                   | 44       | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 44       | 0.72%   |
| Samsung NVMe SSD Controller 980                                                         | 42       | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 39       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 39       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39       | 0.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 38       | 0.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 37       | 0.6%    |
| Kingston Company A2000 NVMe SSD                                                         | 37       | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 37       | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 36       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 36       | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 31       | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2796     | 58.32%  |
| NVMe | 1205     | 25.14%  |
| IDE  | 500      | 10.43%  |
| RAID | 246      | 5.13%   |
| SAS  | 36       | 0.75%   |
| SCSI | 11       | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1794     | 55.78%  |
| AMD    | 1422     | 44.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 116      | 3.59%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 89       | 2.75%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 67       | 2.07%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 56       | 1.73%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 51       | 1.58%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 49       | 1.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 47       | 1.45%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 46       | 1.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 43       | 1.33%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 42       | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 40       | 1.24%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 37       | 1.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 34       | 1.05%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 33       | 1.02%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 33       | 1.02%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 33       | 1.02%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 33       | 1.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 33       | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 32       | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 30       | 0.93%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 30       | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 30       | 0.93%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 30       | 0.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 30       | 0.93%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 28       | 0.87%   |
| AMD FX-6300 Six-Core Processor              | 28       | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27       | 0.83%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 25       | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 24       | 0.74%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 24       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 24       | 0.74%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 23       | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 22       | 0.68%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 22       | 0.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 22       | 0.68%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 21       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 21       | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 21       | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 20       | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 550      | 17.05%  |
| Intel Core i7           | 524      | 16.25%  |
| AMD Ryzen 5             | 453      | 14.05%  |
| AMD Ryzen 7             | 322      | 9.98%   |
| AMD Ryzen 9             | 189      | 5.86%   |
| Intel Core i3           | 169      | 5.24%   |
| Intel Xeon              | 166      | 5.15%   |
| AMD FX                  | 124      | 3.84%   |
| Other                   | 90       | 2.79%   |
| Intel Core 2 Duo        | 69       | 2.14%   |
| AMD Ryzen 3             | 52       | 1.61%   |
| Intel Core 2 Quad       | 46       | 1.43%   |
| Intel Core i9           | 44       | 1.36%   |
| Intel Pentium           | 41       | 1.27%   |
| AMD Ryzen Threadripper  | 39       | 1.21%   |
| Intel Celeron           | 38       | 1.18%   |
| AMD Phenom II X4        | 31       | 0.96%   |
| AMD A10                 | 26       | 0.81%   |
| AMD A8                  | 24       | 0.74%   |
| Intel Pentium Dual-Core | 22       | 0.68%   |
| AMD Athlon II X2        | 18       | 0.56%   |
| AMD A6                  | 18       | 0.56%   |
| AMD Phenom II X6        | 16       | 0.5%    |
| AMD Athlon              | 15       | 0.47%   |
| Intel Core 2            | 13       | 0.4%    |
| AMD Phenom              | 12       | 0.37%   |
| AMD Athlon 64 X2        | 12       | 0.37%   |
| Intel Atom              | 11       | 0.34%   |
| AMD Ryzen 7 PRO         | 9        | 0.28%   |
| AMD Athlon X4           | 8        | 0.25%   |
| AMD A4                  | 8        | 0.25%   |
| AMD Ryzen 5 PRO         | 7        | 0.22%   |
| AMD Athlon II X4        | 7        | 0.22%   |
| AMD Phenom II X2        | 6        | 0.19%   |
| Intel Pentium Dual      | 4        | 0.12%   |
| Intel Genuine           | 4        | 0.12%   |
| AMD Athlon Dual Core    | 4        | 0.12%   |
| Intel Pentium Gold      | 3        | 0.09%   |
| Intel Pentium D         | 3        | 0.09%   |
| AMD Athlon 64           | 3        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1222     | 37.87%  |
| 6      | 655      | 20.3%   |
| 2      | 485      | 15.03%  |
| 8      | 462      | 14.32%  |
| 12     | 170      | 5.27%   |
| 16     | 96       | 2.97%   |
| 3      | 47       | 1.46%   |
| 10     | 34       | 1.05%   |
| 1      | 28       | 0.87%   |
| 24     | 11       | 0.34%   |
| 32     | 10       | 0.31%   |
| 14     | 5        | 0.15%   |
| 20     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3177     | 98.79%  |
| 2      | 39       | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2185     | 67.79%  |
| 1      | 1038     | 32.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3127     | 96.75%  |
| Unknown        | 105      | 3.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 306      | 9.27%   |
| 0x08701021 | 255      | 7.72%   |
| Unknown    | 185      | 5.6%    |
| 0x306a9    | 178      | 5.39%   |
| 0x506e3    | 160      | 4.85%   |
| 0x0800820d | 138      | 4.18%   |
| 0x206a7    | 131      | 3.97%   |
| 0x906ea    | 124      | 3.76%   |
| 0x906e9    | 114      | 3.45%   |
| 0x08701013 | 112      | 3.39%   |
| 0x1067a    | 86       | 2.61%   |
| 0x06000852 | 73       | 2.21%   |
| 0x0a201016 | 69       | 2.09%   |
| 0x0a201009 | 62       | 1.88%   |
| 0x906ed    | 56       | 1.7%    |
| 0x08001138 | 56       | 1.7%    |
| 0x08108109 | 46       | 1.39%   |
| 0x08001137 | 46       | 1.39%   |
| 0x90672    | 44       | 1.33%   |
| 0xa0655    | 41       | 1.24%   |
| 0x010000c8 | 40       | 1.21%   |
| 0x306f2    | 39       | 1.18%   |
| 0x0a50000c | 39       | 1.18%   |
| 0x08101016 | 36       | 1.09%   |
| 0xa0653    | 34       | 1.03%   |
| 0x06001119 | 32       | 0.97%   |
| 0x206d7    | 31       | 0.94%   |
| 0x20655    | 28       | 0.85%   |
| 0x106a5    | 27       | 0.82%   |
| 0xa0671    | 26       | 0.79%   |
| 0x6fb      | 26       | 0.79%   |
| 0x10676    | 26       | 0.79%   |
| 0x906eb    | 24       | 0.73%   |
| 0x106e5    | 23       | 0.7%    |
| 0x906ec    | 22       | 0.67%   |
| 0x0800820b | 21       | 0.64%   |
| 0x06003106 | 20       | 0.61%   |
| 0x0a50000d | 18       | 0.55%   |
| 0x0810100b | 18       | 0.55%   |
| 0x206c2    | 17       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 408      | 12.64%  |
| KabyLake         | 363      | 11.25%  |
| Haswell          | 363      | 11.25%  |
| Zen 3            | 245      | 7.59%   |
| Zen+             | 232      | 7.19%   |
| IvyBridge        | 204      | 6.32%   |
| Zen              | 188      | 5.82%   |
| Skylake          | 187      | 5.79%   |
| SandyBridge      | 174      | 5.39%   |
| Piledriver       | 136      | 4.21%   |
| Penryn           | 126      | 3.9%    |
| K10              | 95       | 2.94%   |
| CometLake        | 77       | 2.39%   |
| Nehalem          | 56       | 1.73%   |
| Alderlake Hybrid | 55       | 1.7%    |
| Westmere         | 54       | 1.67%   |
| Core             | 53       | 1.64%   |
| Steamroller      | 26       | 0.81%   |
| Icelake          | 26       | 0.81%   |
| Unknown          | 25       | 0.77%   |
| Excavator        | 21       | 0.65%   |
| Bulldozer        | 21       | 0.65%   |
| K8 Hammer        | 19       | 0.59%   |
| Silvermont       | 15       | 0.46%   |
| Broadwell        | 12       | 0.37%   |
| Bonnell          | 9        | 0.28%   |
| NetBurst         | 7        | 0.22%   |
| K10 Llano        | 7        | 0.22%   |
| Jaguar           | 6        | 0.19%   |
| Bobcat           | 5        | 0.15%   |
| Goldmont         | 4        | 0.12%   |
| Puma             | 3        | 0.09%   |
| Goldmont plus    | 3        | 0.09%   |
| Tremont          | 2        | 0.06%   |
| TigerLake        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1406     | 40.11%  |
| AMD                        | 1302     | 37.15%  |
| Intel                      | 782      | 22.31%  |
| Matrox Electronics Systems | 7        | 0.2%    |
| ASPEED Technology          | 7        | 0.2%    |
| S3 Graphics                | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 277      | 7.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 137      | 3.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 118      | 3.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 94       | 2.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 89       | 2.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 86       | 2.38%   |
| Intel HD Graphics 530                                                       | 85       | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 73       | 2.02%   |
| Intel HD Graphics 630                                                       | 62       | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 58       | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 55       | 1.52%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 53       | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 53       | 1.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 49       | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 48       | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 47       | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 46       | 1.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 43       | 1.19%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 41       | 1.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 40       | 1.11%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 39       | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 39       | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 38       | 1.05%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 38       | 1.05%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 38       | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 37       | 1.02%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 36       | 1%      |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 34       | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 34       | 0.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 33       | 0.91%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 33       | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 33       | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 0.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 29       | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 28       | 0.77%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 27       | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 26       | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 26       | 0.72%   |
| Intel AlderLake-S GT1                                                       | 23       | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1277     | 39.05%  |
| 1 x AMD                  | 1201     | 36.73%  |
| 1 x Intel                | 580      | 17.74%  |
| Intel + Nvidia           | 69       | 2.11%   |
| 2 x AMD                  | 44       | 1.35%   |
| AMD + Nvidia             | 34       | 1.04%   |
| Intel + AMD              | 22       | 0.67%   |
| 2 x Nvidia               | 20       | 0.61%   |
| 1 x ASPEED               | 5        | 0.15%   |
| 1 x Matrox               | 4        | 0.12%   |
| 2 x Intel                | 3        | 0.09%   |
| Nvidia + Matrox          | 2        | 0.06%   |
| Other                    | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.03%   |
| 1 x S3 Graphics          | 1        | 0.03%   |
| Nvidia + ASPEED          | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2396     | 73%     |
| Proprietary | 794      | 24.19%  |
| Unknown     | 92       | 2.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1121     | 33.43%  |
| 7.01-8.0   | 515      | 15.36%  |
| 1.01-2.0   | 445      | 13.27%  |
| 3.01-4.0   | 365      | 10.89%  |
| 0.51-1.0   | 322      | 9.6%    |
| 0.01-0.5   | 230      | 6.86%   |
| 5.01-6.0   | 159      | 4.74%   |
| 8.01-16.0  | 146      | 4.35%   |
| 2.01-3.0   | 45       | 1.34%   |
| 16.01-24.0 | 5        | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 566      | 14.89%  |
| Dell                 | 516      | 13.58%  |
| Goldstar             | 495      | 13.02%  |
| Acer                 | 269      | 7.08%   |
| Hewlett-Packard      | 224      | 5.89%   |
| AOC                  | 223      | 5.87%   |
| BenQ                 | 216      | 5.68%   |
| Ancor Communications | 195      | 5.13%   |
| Philips              | 152      | 4%      |
| ViewSonic            | 99       | 2.6%    |
| Iiyama               | 85       | 2.24%   |
| Lenovo               | 78       | 2.05%   |
| ASUSTek Computer     | 74       | 1.95%   |
| Sony                 | 36       | 0.95%   |
| MSI                  | 36       | 0.95%   |
| Eizo                 | 36       | 0.95%   |
| Sceptre Tech         | 34       | 0.89%   |
| Unknown              | 29       | 0.76%   |
| HannStar             | 27       | 0.71%   |
| NEC Computers        | 24       | 0.63%   |
| Gigabyte Technology  | 24       | 0.63%   |
| Vizio                | 17       | 0.45%   |
| Insignia             | 15       | 0.39%   |
| LG Electronics       | 13       | 0.34%   |
| Mi                   | 12       | 0.32%   |
| ___                  | 11       | 0.29%   |
| Panasonic            | 11       | 0.29%   |
| Pixio                | 10       | 0.26%   |
| Fujitsu Siemens      | 10       | 0.26%   |
| Gateway              | 9        | 0.24%   |
| ONN                  | 7        | 0.18%   |
| Vestel Elektronik    | 6        | 0.16%   |
| Sharp                | 6        | 0.16%   |
| RTK                  | 6        | 0.16%   |
| Hitachi              | 6        | 0.16%   |
| Apple                | 6        | 0.16%   |
| Unknown (XXX)        | 5        | 0.13%   |
| Toshiba              | 5        | 0.13%   |
| Planar               | 5        | 0.13%   |
| Packard Bell         | 5        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 32       | 0.77%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 25       | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 25       | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 21       | 0.51%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 19       | 0.46%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 18       | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 16       | 0.39%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 16       | 0.39%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16       | 0.39%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 15       | 0.36%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 15       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 14       | 0.34%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                     | 14       | 0.34%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 14       | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 13       | 0.31%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 13       | 0.31%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 13       | 0.31%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 13       | 0.31%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 11       | 0.27%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 11       | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 10       | 0.24%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 10       | 0.24%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 10       | 0.24%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 10       | 0.24%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 9        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9        | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 9        | 0.22%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.22%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 8        | 0.19%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 8        | 0.19%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 8        | 0.19%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 8        | 0.19%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 8        | 0.19%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 8        | 0.19%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 8        | 0.19%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 8        | 0.19%   |
| Ancor Communications ASUS PB278 ACI27A3 1920x1080 597x336mm 27.0-inch | 8        | 0.19%   |
| ___ LCDTV16 ___0101 1360x768                                          | 7        | 0.17%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 7        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1661     | 45.49%  |
| 2560x1440 (QHD)    | 439      | 12.02%  |
| 3840x2160 (4K)     | 418      | 11.45%  |
| 1280x1024 (SXGA)   | 153      | 4.19%   |
| 1680x1050 (WSXGA+) | 146      | 4%      |
| 1920x1200 (WUXGA)  | 134      | 3.67%   |
| 3440x1440          | 109      | 2.99%   |
| 1366x768 (WXGA)    | 100      | 2.74%   |
| 1440x900 (WXGA+)   | 97       | 2.66%   |
| 2560x1080          | 87       | 2.38%   |
| 1600x900 (HD+)     | 68       | 1.86%   |
| 1360x768           | 44       | 1.21%   |
| Unknown            | 34       | 0.93%   |
| 3840x1080          | 33       | 0.9%    |
| 1600x1200          | 19       | 0.52%   |
| 2560x1600          | 14       | 0.38%   |
| 1024x768 (XGA)     | 14       | 0.38%   |
| 1920x540           | 13       | 0.36%   |
| 2288x1287          | 12       | 0.33%   |
| 1280x720 (HD)      | 7        | 0.19%   |
| 2048x1152          | 6        | 0.16%   |
| 3840x1600          | 5        | 0.14%   |
| 1280x960           | 5        | 0.14%   |
| 2160x1200          | 3        | 0.08%   |
| 5760x2160          | 2        | 0.05%   |
| 3840x1200          | 2        | 0.05%   |
| 1280x768           | 2        | 0.05%   |
| 7680x2160          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7120x1080          | 1        | 0.03%   |
| 6784x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 6400x1080          | 1        | 0.03%   |
| 5760x1200          | 1        | 0.03%   |
| 5760x1080          | 1        | 0.03%   |
| 5120x1440          | 1        | 0.03%   |
| 4864x2160          | 1        | 0.03%   |
| 4480x1200          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 721      | 18.77%  |
| 24      | 669      | 17.42%  |
| 23      | 479      | 12.47%  |
| 21      | 446      | 11.61%  |
| 31      | 184      | 4.79%   |
| 19      | 175      | 4.56%   |
| 34      | 173      | 4.5%    |
| 22      | 127      | 3.31%   |
| 18      | 125      | 3.25%   |
| Unknown | 111      | 2.89%   |
| 20      | 89       | 2.32%   |
| 17      | 57       | 1.48%   |
| 72      | 49       | 1.28%   |
| 32      | 49       | 1.28%   |
| 25      | 44       | 1.15%   |
| 84      | 43       | 1.12%   |
| 40      | 32       | 0.83%   |
| 15      | 31       | 0.81%   |
| 54      | 24       | 0.62%   |
| 48      | 23       | 0.6%    |
| 26      | 19       | 0.49%   |
| 42      | 18       | 0.47%   |
| 29      | 13       | 0.34%   |
| 28      | 13       | 0.34%   |
| 49      | 11       | 0.29%   |
| 142     | 10       | 0.26%   |
| 46      | 10       | 0.26%   |
| 16      | 10       | 0.26%   |
| 52      | 9        | 0.23%   |
| 37      | 8        | 0.21%   |
| 13      | 8        | 0.21%   |
| 65      | 7        | 0.18%   |
| 39      | 5        | 0.13%   |
| 35      | 5        | 0.13%   |
| 30      | 5        | 0.13%   |
| 69      | 4        | 0.1%    |
| 50      | 4        | 0.1%    |
| 36      | 4        | 0.1%    |
| 33      | 4        | 0.1%    |
| 47      | 3        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1671     | 46.02%  |
| 401-500        | 818      | 22.53%  |
| 601-700        | 293      | 8.07%   |
| 701-800        | 229      | 6.31%   |
| 351-400        | 133      | 3.66%   |
| Unknown        | 111      | 3.06%   |
| 1501-2000      | 98       | 2.7%    |
| 1001-1500      | 93       | 2.56%   |
| 301-350        | 88       | 2.42%   |
| 801-900        | 50       | 1.38%   |
| 901-1000       | 25       | 0.69%   |
| More than 2000 | 12       | 0.33%   |
| 201-300        | 10       | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2424     | 71.61%  |
| 16/10   | 428      | 12.64%  |
| 21/9    | 189      | 5.58%   |
| 5/4     | 153      | 4.52%   |
| Unknown | 75       | 2.22%   |
| 4/3     | 51       | 1.51%   |
| 32/9    | 26       | 0.77%   |
| 6/5     | 13       | 0.38%   |
| 1.00    | 10       | 0.3%    |
| 3/2     | 9        | 0.27%   |
| 1.96    | 4        | 0.12%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1288     | 34.71%  |
| 301-350        | 735      | 19.81%  |
| 351-500        | 421      | 11.34%  |
| 151-200        | 412      | 11.1%   |
| 251-300        | 266      | 7.17%   |
| More than 1000 | 160      | 4.31%   |
| 141-150        | 140      | 3.77%   |
| 501-1000       | 115      | 3.1%    |
| Unknown        | 111      | 2.99%   |
| 101-110        | 27       | 0.73%   |
| 131-140        | 11       | 0.3%    |
| 91-100         | 6        | 0.16%   |
| 71-80          | 5        | 0.13%   |
| 121-130        | 5        | 0.13%   |
| 111-120        | 5        | 0.13%   |
| 81-90          | 4        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2066     | 58.88%  |
| 101-120 | 878      | 25.02%  |
| 121-160 | 195      | 5.56%   |
| 1-50    | 144      | 4.1%    |
| 161-240 | 115      | 3.28%   |
| Unknown | 111      | 3.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2307     | 69.4%   |
| 2     | 785      | 23.62%  |
| 0     | 113      | 3.4%    |
| 3     | 101      | 3.04%   |
| 4     | 14       | 0.42%   |
| 5     | 4        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1876     | 40.47%  |
| Intel                           | 1611     | 34.75%  |
| Qualcomm Atheros                | 268      | 5.78%   |
| Broadcom                        | 120      | 2.59%   |
| Ralink Technology               | 94       | 2.03%   |
| TP-Link                         | 93       | 2.01%   |
| Ralink                          | 43       | 0.93%   |
| Microsoft                       | 43       | 0.93%   |
| Nvidia                          | 42       | 0.91%   |
| Aquantia                        | 42       | 0.91%   |
| MediaTek                        | 36       | 0.78%   |
| Qualcomm Atheros Communications | 28       | 0.6%    |
| ASUSTek Computer                | 28       | 0.6%    |
| Marvell Technology Group        | 22       | 0.47%   |
| D-Link                          | 22       | 0.47%   |
| Xiaomi                          | 18       | 0.39%   |
| NetGear                         | 18       | 0.39%   |
| Samsung Electronics             | 17       | 0.37%   |
| Edimax Technology               | 15       | 0.32%   |
| ASIX Electronics                | 12       | 0.26%   |
| Huawei Technologies             | 10       | 0.22%   |
| Google                          | 10       | 0.22%   |
| Broadcom Limited                | 10       | 0.22%   |
| Mellanox Technologies           | 9        | 0.19%   |
| D-Link System                   | 9        | 0.19%   |
| Motorola PCS                    | 8        | 0.17%   |
| Linksys                         | 8        | 0.17%   |
| Arduino SA                      | 8        | 0.17%   |
| Belkin Components               | 7        | 0.15%   |
| Apple                           | 7        | 0.15%   |
| ICS Advent                      | 6        | 0.13%   |
| DisplayLink                     | 6        | 0.13%   |
| Qualcomm                        | 5        | 0.11%   |
| AVM                             | 5        | 0.11%   |
| Wilocity                        | 4        | 0.09%   |
| Microchip Technology            | 4        | 0.09%   |
| InterBiometrics                 | 4        | 0.09%   |
| HMD Global                      | 4        | 0.09%   |
| OPPO Electronics                | 3        | 0.06%   |
| OpenMoko                        | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1485     | 27.52%  |
| Intel I211 Gigabit Network Connection                             | 356      | 6.6%    |
| Intel Wi-Fi 6 AX200                                               | 317      | 5.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 198      | 3.67%   |
| Intel Ethernet Connection (2) I219-V                              | 190      | 3.52%   |
| Intel Ethernet Controller I225-V                                  | 130      | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 104      | 1.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 93       | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 82       | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 64       | 1.19%   |
| Intel Wireless-AC 9260                                            | 61       | 1.13%   |
| Intel Ethernet Connection (2) I218-V                              | 60       | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 46       | 0.85%   |
| Intel 82574L Gigabit Network Connection                           | 45       | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 44       | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 43       | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40       | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 36       | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 34       | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32       | 0.59%   |
| Intel Wireless 7260                                               | 31       | 0.57%   |
| Intel Wireless 8260                                               | 30       | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 29       | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25       | 0.46%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 25       | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 22       | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22       | 0.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 21       | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                   | 21       | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 20       | 0.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 20       | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 20       | 0.37%   |
| Intel Wireless 8265 / 8275                                        | 20       | 0.37%   |
| Intel Wireless 7265                                               | 20       | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 19       | 0.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 19       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 731      | 44.17%  |
| Realtek Semiconductor                 | 262      | 15.83%  |
| Qualcomm Atheros                      | 142      | 8.58%   |
| Ralink Technology                     | 94       | 5.68%   |
| TP-Link                               | 91       | 5.5%    |
| Broadcom                              | 60       | 3.63%   |
| Ralink                                | 43       | 2.6%    |
| Microsoft                             | 42       | 2.54%   |
| MediaTek                              | 35       | 2.11%   |
| Qualcomm Atheros Communications       | 28       | 1.69%   |
| ASUSTek Computer                      | 26       | 1.57%   |
| D-Link                                | 18       | 1.09%   |
| NetGear                               | 17       | 1.03%   |
| Edimax Technology                     | 15       | 0.91%   |
| Linksys                               | 8        | 0.48%   |
| Belkin Components                     | 7        | 0.42%   |
| D-Link System                         | 6        | 0.36%   |
| AVM                                   | 5        | 0.3%    |
| Wilocity                              | 4        | 0.24%   |
| Broadcom Limited                      | 3        | 0.18%   |
| Xiaomi                                | 2        | 0.12%   |
| IMC Networks                          | 2        | 0.12%   |
| BUFFALO                               | 2        | 0.12%   |
| AboCom Systems                        | 2        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.12%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.06%   |
| Toshiba                               | 1        | 0.06%   |
| Sitecom Europe                        | 1        | 0.06%   |
| Sierra Wireless                       | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| PLANEX                                | 1        | 0.06%   |
| Mercucys                              | 1        | 0.06%   |
| Gemtek                                | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 317      | 18.94%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 93       | 5.56%   |
| Intel Wireless-AC 9260                                         | 61       | 3.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 46       | 2.75%   |
| Ralink MT7601U Wireless Adapter                                | 36       | 2.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 35       | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32       | 1.91%   |
| Intel Wireless 7260                                            | 31       | 1.85%   |
| Intel Wireless 8260                                            | 30       | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 29       | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25       | 1.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 25       | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 21       | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                | 21       | 1.25%   |
| Ralink RT5370 Wireless Adapter                                 | 20       | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 20       | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 20       | 1.19%   |
| Intel Wireless 8265 / 8275                                     | 20       | 1.19%   |
| Intel Wireless 7265                                            | 20       | 1.19%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 19       | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 19       | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19       | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18       | 1.08%   |
| Realtek 802.11ac NIC                                           | 17       | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 17       | 1.02%   |
| Intel Wireless 3165                                            | 17       | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 16       | 0.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 0.96%   |
| Microsoft Xbox 360 Wireless Adapter                            | 16       | 0.96%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 14       | 0.84%   |
| Microsoft XBOX ACC                                             | 14       | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 14       | 0.84%   |
| Intel Wireless 3160                                            | 13       | 0.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 13       | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12       | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12       | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12       | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.66%   |
| Microsoft Wireless XBox Controller Dongle                      | 11       | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1764     | 50.13%  |
| Intel                                  | 1295     | 36.8%   |
| Qualcomm Atheros                       | 142      | 4.04%   |
| Broadcom                               | 60       | 1.71%   |
| Nvidia                                 | 42       | 1.19%   |
| Aquantia                               | 42       | 1.19%   |
| Marvell Technology Group               | 22       | 0.63%   |
| Xiaomi                                 | 16       | 0.45%   |
| Samsung Electronics                    | 16       | 0.45%   |
| ASIX Electronics                       | 12       | 0.34%   |
| Google                                 | 10       | 0.28%   |
| Motorola PCS                           | 8        | 0.23%   |
| Mellanox Technologies                  | 8        | 0.23%   |
| Broadcom Limited                       | 7        | 0.2%    |
| Apple                                  | 7        | 0.2%    |
| ICS Advent                             | 6        | 0.17%   |
| DisplayLink                            | 6        | 0.17%   |
| Qualcomm                               | 5        | 0.14%   |
| Huawei Technologies                    | 5        | 0.14%   |
| HMD Global                             | 4        | 0.11%   |
| D-Link                                 | 4        | 0.11%   |
| OPPO Electronics                       | 3        | 0.09%   |
| D-Link System                          | 3        | 0.09%   |
| ADMtek                                 | 3        | 0.09%   |
| VIA Technologies                       | 2        | 0.06%   |
| TP-Link                                | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.06%   |
| Lenovo                                 | 2        | 0.06%   |
| Davicom Semiconductor                  | 2        | 0.06%   |
| ASUSTek Computer                       | 2        | 0.06%   |
| Accton Technology                      | 2        | 0.06%   |
| 3Com                                   | 2        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| Xilinx                                 | 1        | 0.03%   |
| vivo                                   | 1        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.03%   |
| QNAP System                            | 1        | 0.03%   |
| OpenMoko                               | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1485     | 40.38%  |
| Intel I211 Gigabit Network Connection                                         | 356      | 9.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 198      | 5.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 190      | 5.17%   |
| Intel Ethernet Controller I225-V                                              | 130      | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 104      | 2.83%   |
| Intel Ethernet Connection (7) I219-V                                          | 82       | 2.23%   |
| Intel Ethernet Connection I217-LM                                             | 64       | 1.74%   |
| Intel Ethernet Connection (2) I218-V                                          | 60       | 1.63%   |
| Intel 82574L Gigabit Network Connection                                       | 45       | 1.22%   |
| Intel 82579V Gigabit Network Connection                                       | 44       | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                         | 43       | 1.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 41       | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 40       | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 40       | 1.09%   |
| Intel Ethernet Connection I217-V                                              | 34       | 0.92%   |
| Intel I210 Gigabit Network Connection                                         | 22       | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 22       | 0.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 22       | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 19       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 19       | 0.52%   |
| Nvidia MCP61 Ethernet                                                         | 19       | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 16       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 15       | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 15       | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                         | 15       | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 14       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 14       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 12       | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 11       | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.3%    |
| Intel 82578DM Gigabit Network Connection                                      | 11       | 0.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11       | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                    | 11       | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 11       | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 10       | 0.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 10       | 0.27%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 10       | 0.27%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 10       | 0.27%   |
| Intel Ethernet Connection (2) I218-LM                                         | 9        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3194     | 66.88%  |
| WiFi     | 1538     | 32.2%   |
| Modem    | 39       | 0.82%   |
| Unknown  | 5        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2580     | 75.59%  |
| WiFi     | 833      | 24.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1881     | 57.63%  |
| 2     | 1113     | 34.1%   |
| 3     | 204      | 6.25%   |
| 4     | 24       | 0.74%   |
| 0     | 19       | 0.58%   |
| 5     | 14       | 0.43%   |
| 6     | 6        | 0.18%   |
| 9     | 2        | 0.06%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 2730     | 82.85%  |
| Yes     | 562      | 17.06%  |
| Unknown | 3        | 0.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 684      | 49.32%  |
| Cambridge Silicon Radio         | 305      | 21.99%  |
| ASUSTek Computer                | 103      | 7.43%   |
| Realtek Semiconductor           | 74       | 5.34%   |
| Broadcom                        | 70       | 5.05%   |
| Qualcomm Atheros Communications | 31       | 2.24%   |
| MediaTek                        | 22       | 1.59%   |
| TP-Link                         | 21       | 1.51%   |
| IMC Networks                    | 16       | 1.15%   |
| Apple                           | 14       | 1.01%   |
| Foxconn / Hon Hai               | 7        | 0.5%    |
| Belkin Components               | 7        | 0.5%    |
| HTC (High Tech Computer)        | 6        | 0.43%   |
| Lite-On Technology              | 4        | 0.29%   |
| Edimax Technology               | 4        | 0.29%   |
| Integrated System Solution      | 3        | 0.22%   |
| Dynex                           | 3        | 0.22%   |
| Dell                            | 3        | 0.22%   |
| Toshiba                         | 2        | 0.14%   |
| SIN                             | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Kensington                      | 1        | 0.07%   |
| D-Link System                   | 1        | 0.07%   |
| Creative Technology             | 1        | 0.07%   |
| BUFFALO                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 305      | 21.91%  |
| Intel AX200 Bluetooth                                                | 298      | 21.41%  |
| Intel Bluetooth wireless interface                                   | 121      | 8.69%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 92       | 6.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 58       | 4.17%   |
| Realtek Bluetooth Radio                                              | 54       | 3.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 49       | 3.52%   |
| Intel Bluetooth Device                                               | 45       | 3.23%   |
| Intel AX210 Bluetooth                                                | 44       | 3.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 41       | 2.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 26       | 1.87%   |
| MediaTek Wireless_Device                                             | 22       | 1.58%   |
| TP-Link TPuLink UB500 Adapter                                        | 21       | 1.51%   |
| ASUS Bluetooth Radio                                                 | 18       | 1.29%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 13       | 0.93%   |
| ASUS Bluetooth Adapter                                               | 13       | 0.93%   |
| ASUS ASUS USB-BT500                                                  | 10       | 0.72%   |
| Qualcomm Atheros  Bluetooth Device                                   | 9        | 0.65%   |
| ASUS BCM20702A0                                                      | 8        | 0.57%   |
| Apple Bluetooth USB Host Controller                                  | 8        | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 7        | 0.5%    |
| IMC Networks Bluetooth Radio                                         | 7        | 0.5%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 6        | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6        | 0.43%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.43%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.43%   |
| ASUS Bluetooth Device                                                | 6        | 0.43%   |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 5        | 0.36%   |
| IMC Networks Bluetooth Device                                        | 5        | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4        | 0.29%   |
| Lite-On Bluetooth Device                                             | 4        | 0.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.29%   |
| Broadcom BCM2045 Bluetooth                                           | 4        | 0.29%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.29%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.22%   |
| Edimax Bluetooth Adapter                                             | 3        | 0.22%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 3        | 0.22%   |
| Broadcom HP Portable Bumble Bee                                      | 3        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1762     | 29.26%  |
| Intel                                | 1718     | 28.53%  |
| Nvidia                               | 1352     | 22.45%  |
| C-Media Electronics                  | 208      | 3.45%   |
| Logitech                             | 100      | 1.66%   |
| Creative Labs                        | 68       | 1.13%   |
| Kingston Technology                  | 41       | 0.68%   |
| SteelSeries ApS                      | 40       | 0.66%   |
| Texas Instruments                    | 38       | 0.63%   |
| Corsair                              | 38       | 0.63%   |
| JMTek                                | 37       | 0.61%   |
| Focusrite-Novation                   | 37       | 0.61%   |
| Razer USA                            | 36       | 0.6%    |
| Creative Technology                  | 35       | 0.58%   |
| Generalplus Technology               | 25       | 0.42%   |
| Plantronics                          | 23       | 0.38%   |
| Blue Microphones                     | 23       | 0.38%   |
| ASUSTek Computer                     | 22       | 0.37%   |
| GN Netcom                            | 20       | 0.33%   |
| GYROCOM C&C                          | 19       | 0.32%   |
| Sony                                 | 17       | 0.28%   |
| Realtek Semiconductor                | 15       | 0.25%   |
| Samson Technologies                  | 14       | 0.23%   |
| XMOS                                 | 13       | 0.22%   |
| RODE Microphones                     | 12       | 0.2%    |
| Giga-Byte Technology                 | 12       | 0.2%    |
| Tenx Technology                      | 11       | 0.18%   |
| Micro Star International             | 10       | 0.17%   |
| Cambridge Silicon Radio              | 10       | 0.17%   |
| VIA Technologies                     | 9        | 0.15%   |
| Sennheiser Communications            | 9        | 0.15%   |
| SAVITECH                             | 8        | 0.13%   |
| Dell                                 | 8        | 0.13%   |
| Schiit Audio                         | 7        | 0.12%   |
| Lenovo                               | 7        | 0.12%   |
| FiiO Electronics Technology          | 7        | 0.12%   |
| Yamaha                               | 6        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 6        | 0.1%    |
| PreSonus Audio Electronics           | 6        | 0.1%    |
| M-Audio                              | 6        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 544      | 7.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 302      | 4.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 279      | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 222      | 3.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 214      | 2.99%   |
| Intel 200 Series PCH HD Audio                                              | 198      | 2.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 189      | 2.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 184      | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 178      | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 154      | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 151      | 2.11%   |
| AMD Navi 10 HDMI Audio                                                     | 141      | 1.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 140      | 1.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 140      | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 138      | 1.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 125      | 1.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 124      | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 95       | 1.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 94       | 1.31%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 93       | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 91       | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 90       | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 89       | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 86       | 1.2%    |
| AMD FCH Azalia Controller                                                  | 77       | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 71       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 70       | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 61       | 0.85%   |
| Nvidia TU104 HD Audio Controller                                           | 60       | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 58       | 0.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 57       | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 55       | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 53       | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 53       | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 52       | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 51       | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 46       | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44       | 0.62%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 43       | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 41       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 338      | 19.33%  |
| Corsair                      | 298      | 17.04%  |
| G.Skill                      | 222      | 12.69%  |
| Unknown                      | 189      | 10.81%  |
| Crucial                      | 141      | 8.06%   |
| Samsung Electronics          | 126      | 7.2%    |
| SK hynix                     | 124      | 7.09%   |
| Micron Technology            | 74       | 4.23%   |
| A-DATA Technology            | 35       | 2%      |
| Team                         | 31       | 1.77%   |
| Patriot                      | 31       | 1.77%   |
| Ramaxel Technology           | 13       | 0.74%   |
| Nanya Technology             | 13       | 0.74%   |
| Unknown                      | 12       | 0.69%   |
| Elpida                       | 9        | 0.51%   |
| GOODRAM                      | 7        | 0.4%    |
| GeIL                         | 6        | 0.34%   |
| Transcend                    | 5        | 0.29%   |
| Smart                        | 5        | 0.29%   |
| Silicon Power                | 5        | 0.29%   |
| Qimonda                      | 4        | 0.23%   |
| PNY                          | 4        | 0.23%   |
| Avant                        | 4        | 0.23%   |
| AMD                          | 4        | 0.23%   |
| Qumo                         | 3        | 0.17%   |
| Unifosa                      | 2        | 0.11%   |
| OCZ                          | 2        | 0.11%   |
| MINPO                        | 2        | 0.11%   |
| Goldkey                      | 2        | 0.11%   |
| Gold Key                     | 2        | 0.11%   |
| CSX                          | 2        | 0.11%   |
| Apacer                       | 2        | 0.11%   |
| zApacer                      | 1        | 0.06%   |
| V-GeN                        | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (ABCD)               | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (9B)                 | 1        | 0.06%   |
| Unknown (0xF7F7F7F7F7F7E300) | 1        | 0.06%   |
| Toshiba                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 34       | 1.79%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 24       | 1.26%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 19       | 1%      |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 17       | 0.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 17       | 0.89%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3             | 14       | 0.74%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 14       | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 13       | 0.68%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 13       | 0.68%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 13       | 0.68%   |
| Unknown                                                | 12       | 0.63%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 11       | 0.58%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 11       | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 10       | 0.53%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s    | 10       | 0.53%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 10       | 0.53%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s | 10       | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 9        | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 9        | 0.47%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 9        | 0.47%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 8        | 0.42%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s | 8        | 0.42%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 8        | 0.42%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 8        | 0.42%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 8        | 0.42%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s     | 8        | 0.42%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 8        | 0.42%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 7        | 0.37%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 7        | 0.37%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s      | 7        | 0.37%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s | 7        | 0.37%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s | 7        | 0.37%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s | 7        | 0.37%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 6        | 0.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 6        | 0.32%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 6        | 0.32%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s    | 6        | 0.32%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s    | 6        | 0.32%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s  | 6        | 0.32%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s | 6        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 894      | 57.09%  |
| DDR3    | 455      | 29.05%  |
| Unknown | 86       | 5.49%   |
| DDR2    | 59       | 3.77%   |
| SDRAM   | 36       | 2.3%    |
| DDR5    | 22       | 1.4%    |
| DDR     | 10       | 0.64%   |
| LPDDR3  | 3        | 0.19%   |
| LPDDR4  | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1469     | 94.96%  |
| SODIMM       | 65       | 4.2%    |
| RIMM         | 8        | 0.52%   |
| FB-DIMM      | 3        | 0.19%   |
| Row Of Chips | 2        | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 693      | 41.27%  |
| 16384 | 350      | 20.85%  |
| 4096  | 348      | 20.73%  |
| 2048  | 158      | 9.41%   |
| 32768 | 89       | 5.3%    |
| 1024  | 36       | 2.14%   |
| 512   | 4        | 0.24%   |
| 256   | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 262      | 15.33%  |
| 3200    | 213      | 12.46%  |
| 3600    | 173      | 10.12%  |
| 1333    | 146      | 8.54%   |
| 2400    | 114      | 6.67%   |
| 2133    | 91       | 5.32%   |
| 2667    | 74       | 4.33%   |
| 800     | 56       | 3.28%   |
| 3400    | 47       | 2.75%   |
| 3000    | 47       | 2.75%   |
| 3466    | 45       | 2.63%   |
| 667     | 39       | 2.28%   |
| 1867    | 37       | 2.17%   |
| 2666    | 27       | 1.58%   |
| 3733    | 26       | 1.52%   |
| Unknown | 22       | 1.29%   |
| 3866    | 21       | 1.23%   |
| 2800    | 21       | 1.23%   |
| 1866    | 21       | 1.23%   |
| 2933    | 19       | 1.11%   |
| 3800    | 18       | 1.05%   |
| 1066    | 18       | 1.05%   |
| 1800    | 15       | 0.88%   |
| 4800    | 14       | 0.82%   |
| 3266    | 10       | 0.59%   |
| 1067    | 10       | 0.59%   |
| 3333    | 8        | 0.47%   |
| 3100    | 8        | 0.47%   |
| 1334    | 8        | 0.47%   |
| 3666    | 7        | 0.41%   |
| 533     | 6        | 0.35%   |
| 5200    | 5        | 0.29%   |
| 2733    | 5        | 0.29%   |
| 2000    | 5        | 0.29%   |
| 400     | 5        | 0.29%   |
| 3334    | 4        | 0.23%   |
| 5600    | 3        | 0.18%   |
| 4400    | 3        | 0.18%   |
| 3500    | 3        | 0.18%   |
| 3151    | 3        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 60       | 39.47%  |
| Brother Industries    | 38       | 25%     |
| Canon                 | 16       | 10.53%  |
| Samsung Electronics   | 10       | 6.58%   |
| Seiko Epson           | 9        | 5.92%   |
| Prolific Technology   | 5        | 3.29%   |
| Lexmark International | 4        | 2.63%   |
| Xerox                 | 2        | 1.32%   |
| Kyocera               | 2        | 1.32%   |
| Star Micronics        | 1        | 0.66%   |
| QinHeng Electronics   | 1        | 0.66%   |
| Graphtec America      | 1        | 0.66%   |
| Dymo-CoStar           | 1        | 0.66%   |
| Dell                  | 1        | 0.66%   |
| Boca Systems          | 1        | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 5        | 3.27%   |
| Samsung M2070 Series                         | 4        | 2.61%   |
| HP LaserJet Professional P 1102w             | 4        | 2.61%   |
| Brother HL-L2340D series                     | 4        | 2.61%   |
| HP ENVY 5000 series                          | 3        | 1.96%   |
| HP ENVY 4520 series                          | 3        | 1.96%   |
| HP DeskJet F300 series                       | 3        | 1.96%   |
| Brother Printer                              | 3        | 1.96%   |
| Brother HL-1110 series                       | 3        | 1.96%   |
| Seiko Epson Printer                          | 2        | 1.31%   |
| Samsung ML-216x Series Laser Printer         | 2        | 1.31%   |
| HP OfficeJet 6950                            | 2        | 1.31%   |
| HP DeskJet 3700 series                       | 2        | 1.31%   |
| HP DeskJet 3630 series                       | 2        | 1.31%   |
| HP DeskJet 2600 series                       | 2        | 1.31%   |
| HP DeskJet 2130 series                       | 2        | 1.31%   |
| Canon TS3300 series                          | 2        | 1.31%   |
| Canon TR4500 series                          | 2        | 1.31%   |
| Canon CanoScan LiDE 300                      | 2        | 1.31%   |
| Brother MFC-9330CDW                          | 2        | 1.31%   |
| Brother HL-2230 series                       | 2        | 1.31%   |
| Xerox Phaser 6500DN                          | 1        | 0.65%   |
| Xerox Phaser 3010                            | 1        | 0.65%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.65%   |
| Seiko Epson XP-100 Series                    | 1        | 0.65%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.65%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.65%   |
| Seiko Epson L3110 Series                     | 1        | 0.65%   |
| Seiko Epson L300 Series                      | 1        | 0.65%   |
| Seiko Epson L220 Series                      | 1        | 0.65%   |
| Seiko Epson L100 Series                      | 1        | 0.65%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1        | 0.65%   |
| Samsung ML-2855 Series                       | 1        | 0.65%   |
| Samsung ML-2010P Mono Laser Printer          | 1        | 0.65%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.65%   |
| QinHeng CH340S                               | 1        | 0.65%   |
| Lexmark International Lexmark MS521dn        | 1        | 0.65%   |
| Lexmark International Laser Printer E232     | 1        | 0.65%   |
| Lexmark International B2236dw                | 1        | 0.65%   |
| Lexmark International 2200 series            | 1        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 22       | 59.46%  |
| Seiko Epson     | 9        | 24.32%  |
| Hewlett-Packard | 4        | 10.81%  |
| UMAX            | 1        | 2.7%    |
| Mustek Systems  | 1        | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                   | 4        | 10.81%  |
| Canon CanoScan LiDE 210                                 | 4        | 10.81%  |
| Canon CanoScan LIDE 25                                  | 3        | 8.11%   |
| Canon CanoScan LiDE 220                                 | 3        | 8.11%   |
| Canon CanoScan LiDE 100                                 | 3        | 8.11%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2        | 5.41%   |
| Canon CanoScan LiDE 110                                 | 2        | 5.41%   |
| UMAX Astra 2200/2200SU                                  | 1        | 2.7%    |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 2.7%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1        | 2.7%    |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 2.7%    |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1        | 2.7%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1        | 2.7%    |
| Mustek Systems BearPaw 2448 TA Plus                     | 1        | 2.7%    |
| HP ScanJet G4050                                        | 1        | 2.7%    |
| HP ScanJet 5590                                         | 1        | 2.7%    |
| HP ScanJet 3400cse                                      | 1        | 2.7%    |
| HP ScanJet 2400c                                        | 1        | 2.7%    |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 2.7%    |
| Canon CanoScan LiDE 70                                  | 1        | 2.7%    |
| Canon CanoScan LiDE 200                                 | 1        | 2.7%    |
| Canon CanoScan LiDE 120                                 | 1        | 2.7%    |
| Canon CanoScan 4400F                                    | 1        | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 375      | 45.4%   |
| Microsoft                              | 69       | 8.35%   |
| Microdia                               | 44       | 5.33%   |
| Samsung Electronics                    | 29       | 3.51%   |
| Apple                                  | 29       | 3.51%   |
| Sunplus Innovation Technology          | 26       | 3.15%   |
| KYE Systems (Mouse Systems)            | 20       | 2.42%   |
| Realtek Semiconductor                  | 18       | 2.18%   |
| Creative Technology                    | 15       | 1.82%   |
| Chicony Electronics                    | 14       | 1.69%   |
| Generalplus Technology                 | 12       | 1.45%   |
| Cubeternet                             | 12       | 1.45%   |
| ARC International                      | 10       | 1.21%   |
| Z-Star Microelectronics                | 9        | 1.09%   |
| 2M UVC CAMERA                          | 9        | 1.09%   |
| Jieli Technology                       | 8        | 0.97%   |
| Razer USA                              | 7        | 0.85%   |
| Lenovo                                 | 7        | 0.85%   |
| Hewlett-Packard                        | 7        | 0.85%   |
| GEMBIRD                                | 7        | 0.85%   |
| Trust                                  | 6        | 0.73%   |
| MacroSilicon                           | 6        | 0.73%   |
| LG Electronics                         | 5        | 0.61%   |
| AVerMedia Technologies                 | 5        | 0.61%   |
| Arkmicro Technologies                  | 5        | 0.61%   |
| Aveo Technology                        | 4        | 0.48%   |
| Unknown                                | 3        | 0.36%   |
| SunplusIT                              | 3        | 0.36%   |
| OmniVision Technologies                | 3        | 0.36%   |
| Huawei Technologies                    | 3        | 0.36%   |
| Genesys Logic                          | 3        | 0.36%   |
| Alcor Micro                            | 3        | 0.36%   |
| A4Tech                                 | 3        | 0.36%   |
| Valve Software                         | 2        | 0.24%   |
| Sunplus IT                             | 2        | 0.24%   |
| Sonix Technology                       | 2        | 0.24%   |
| Linux Foundation                       | 2        | 0.24%   |
| Intel                                  | 2        | 0.24%   |
| HD WEBCAM                              | 2        | 0.24%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 88       | 10.49%  |
| Logitech Webcam C270                       | 83       | 9.89%   |
| Samsung Galaxy A5 (MTP)                    | 28       | 3.34%   |
| Microsoft LifeCam HD-3000                  | 25       | 2.98%   |
| Logitech HD Webcam C525                    | 25       | 2.98%   |
| Apple iPhone 5/5C/5S/6/SE                  | 24       | 2.86%   |
| Microdia Webcam Vitade AF                  | 20       | 2.38%   |
| Logitech C922 Pro Stream Webcam            | 19       | 2.26%   |
| Microsoft LifeCam Cinema                   | 17       | 2.03%   |
| Logitech Webcam C310                       | 16       | 1.91%   |
| Logitech HD Webcam C615                    | 16       | 1.91%   |
| Logitech Webcam Pro 9000                   | 14       | 1.67%   |
| Microdia USB 2.0 Camera                    | 13       | 1.55%   |
| Logitech BRIO Ultra HD Webcam              | 12       | 1.43%   |
| Logitech Webcam C925e                      | 11       | 1.31%   |
| Logitech Webcam C170                       | 11       | 1.31%   |
| Logitech Webcam C930e                      | 10       | 1.19%   |
| ARC International Camera                   | 10       | 1.19%   |
| Logitech StreamCam                         | 9        | 1.07%   |
| Logitech C920 PRO HD Webcam                | 9        | 1.07%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam       | 9        | 1.07%   |
| Logitech QuickCam Pro 9000                 | 8        | 0.95%   |
| Jieli USB PHY 2.0                          | 8        | 0.95%   |
| Sunplus HD 720P webcam                     | 7        | 0.83%   |
| Realtek Full HD webcam                     | 7        | 0.83%   |
| Realtek USB Camera                         | 6        | 0.72%   |
| Microsoft LifeCam VX-5000                  | 6        | 0.72%   |
| Logitech BRIO 4K Stream Edition            | 6        | 0.72%   |
| Razer USA Gaming Webcam [Kiyo]             | 5        | 0.6%    |
| Microsoft LifeCam Studio                   | 5        | 0.6%    |
| Microdia Camera                            | 5        | 0.6%    |
| MacroSilicon USB Video                     | 5        | 0.6%    |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 0.6%    |
| Generalplus GENERAL WEBCAM                 | 5        | 0.6%    |
| Creative Live! Cam Sync HD [VF0770]        | 5        | 0.6%    |
| Creative Live! Cam Sync 1080p              | 5        | 0.6%    |
| Sunplus ZET USB WEBCAM                     | 4        | 0.48%   |
| Realtek NexiGo N660P FHD Webcam            | 4        | 0.48%   |
| Microsoft LifeCam VX-500 [1357]            | 4        | 0.48%   |
| Logitech QuickCam E 3500                   | 4        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 20%     |
| Elan Microelectronics | 2        | 20%     |
| DigitalPersona        | 2        | 20%     |
| Synaptics             | 1        | 10%     |
| Microsoft             | 1        | 10%     |
| Dell                  | 1        | 10%     |
| AuthenTec             | 1        | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 2        | 20%     |
| DigitalPersona Fingerprint Reader              | 2        | 20%     |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 1        | 10%     |
| Microsoft Fingerprint Reader                   | 1        | 10%     |
| LighTuning Fingerprint Sensor                  | 1        | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 10%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 10%     |
| AuthenTec AES1600                              | 1        | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 5        | 15.15%  |
| Alcor Micro                       | 5        | 15.15%  |
| SCM Microsystems                  | 4        | 12.12%  |
| Realtek Semiconductor             | 4        | 12.12%  |
| VASCO Data Security International | 3        | 9.09%   |
| OmniKey                           | 3        | 9.09%   |
| Gemalto (was Gemplus)             | 2        | 6.06%   |
| Fujitsu Siemens Computers         | 1        | 3.03%   |
| Feitian Technologies              | 1        | 3.03%   |
| Clay Logic                        | 1        | 3.03%   |
| Chicony Electronics               | 1        | 3.03%   |
| Cherry                            | 1        | 3.03%   |
| Aktiv                             | 1        | 3.03%   |
| Advanced Card Systems             | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 12.12%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 3        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 3        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 9.09%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 6.06%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 2        | 6.06%   |
| Alcor Micro Watchdata W 1981                                    | 2        | 6.06%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1        | 3.03%   |
| Yubico.com Yubikey 4/5 CCID                                     | 1        | 3.03%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 3.03%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader      | 1        | 3.03%   |
| OmniKey CardMan 3121 (HID Technologies)                         | 1        | 3.03%   |
| OmniKey CardMan 3021 / 3121                                     | 1        | 3.03%   |
| OmniKey CardMan 1021                                            | 1        | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 3.03%   |
| Feitian Technologies FT SCR310                                  | 1        | 3.03%   |
| Clay Logic Nitrokey Pro                                         | 1        | 3.03%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 1        | 3.03%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 3.03%   |
| Aktiv Rutoken lite                                              | 1        | 3.03%   |
| Advanced Card Systems ACR122U                                   | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2815     | 85.51%  |
| 1     | 414      | 12.58%  |
| 2     | 43       | 1.31%   |
| 3     | 9        | 0.27%   |
| 4     | 5        | 0.15%   |
| 5     | 4        | 0.12%   |
| 8     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 156      | 29.43%  |
| Graphics card            | 146      | 27.55%  |
| Unassigned class         | 48       | 9.06%   |
| Sound                    | 31       | 5.85%   |
| Camera                   | 28       | 5.28%   |
| Multimedia controller    | 27       | 5.09%   |
| Communication controller | 27       | 5.09%   |
| Storage/raid             | 11       | 2.08%   |
| Network                  | 10       | 1.89%   |
| Fingerprint reader       | 9        | 1.7%    |
| Bluetooth                | 9        | 1.7%    |
| Net/ethernet             | 5        | 0.94%   |
| Modem                    | 5        | 0.94%   |
| Chipcard                 | 5        | 0.94%   |
| Card reader              | 5        | 0.94%   |
| Firewire controller      | 2        | 0.38%   |
| Dvb card                 | 2        | 0.38%   |
| Wireless                 | 1        | 0.19%   |
| Tv card                  | 1        | 0.19%   |
| Storage/ata              | 1        | 0.19%   |
| Storage                  | 1        | 0.19%   |

