Fedora 37 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 507

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
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
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
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
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
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
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
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
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
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Dell          | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HP            | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 6.0.15-300.fc37.x86_64                             | 45       | 12.06%  |
| 6.0.12-300.fc37.x86_64                             | 44       | 11.8%   |
| 6.0.11-300.fc37.x86_64                             | 31       | 8.31%   |
| 6.0.8-300.fc37.x86_64                              | 27       | 7.24%   |
| 6.0.9-300.fc37.x86_64                              | 26       | 6.97%   |
| 6.0.7-301.fc37.x86_64                              | 25       | 6.7%    |
| 6.0.10-300.fc37.x86_64                             | 21       | 5.63%   |
| 6.1.6-200.fc37.x86_64                              | 18       | 4.83%   |
| 6.1.7-200.fc37.x86_64                              | 14       | 3.75%   |
| 5.19.16-301.fc37.x86_64                            | 12       | 3.22%   |
| 6.1.8-200.fc37.x86_64                              | 9        | 2.41%   |
| 6.1.5-200.fc37.x86_64                              | 9        | 2.41%   |
| 6.0.17-300.fc37.x86_64                             | 9        | 2.41%   |
| 6.0.16-300.fc37.x86_64                             | 8        | 2.14%   |
| 6.0.14-300.fc37.x86_64                             | 8        | 2.14%   |
| 5.19.9-300.fc37.x86_64                             | 8        | 2.14%   |
| 5.19.13-300.fc37.x86_64                            | 8        | 2.14%   |
| 6.0.18-300.fc37.x86_64                             | 7        | 1.88%   |
| 6.0.13-300.fc37.x86_64                             | 5        | 1.34%   |
| 5.19.7-300.fc37.x86_64                             | 4        | 1.07%   |
| 6.0.5-300.fc37.x86_64                              | 3        | 0.8%    |
| 5.19.8-300.fc37.x86_64                             | 3        | 0.8%    |
| 6.0.6-300.fc37.x86_64                              | 2        | 0.54%   |
| 5.19.16-300.fc37.x86_64                            | 2        | 0.54%   |
| 5.19.12-300.fc37.x86_64                            | 2        | 0.54%   |
| 6.1.8-200.fc37.x86_64+debug                        | 1        | 0.27%   |
| 6.1.5-xm1.0.fc37.x86_64                            | 1        | 0.27%   |
| 6.1.2-200.fc37.x86_64                              | 1        | 0.27%   |
| 6.1.0-0.rc0.20221014git9c9155a3509a.11.fc38.x86_64 | 1        | 0.27%   |
| 6.0.3-300.fc37.x86_64                              | 1        | 0.27%   |
| 6.0.2-301.fc37.x86_64                              | 1        | 0.27%   |
| 6.0.13-602.inttf.fc37.x86_64                       | 1        | 0.27%   |
| 6.0.11-200.fc36.x86_64                             | 1        | 0.27%   |
| 6.0.10-602.inttf.fc37.x86_64                       | 1        | 0.27%   |
| 6.0.10-301.fsync.fc37.x86_64                       | 1        | 0.27%   |
| 6.0.0-0.rc6.20220922gitdc164f4fb00a.43.fc38.x86_64 | 1        | 0.27%   |
| 5.8.15-301.fc33.x86_64                             | 1        | 0.27%   |
| 5.19.8-501.chinfo.fc37.x86_64                      | 1        | 0.27%   |
| 5.19.16-602.inttf.fc37.x86_64                      | 1        | 0.27%   |
| 5.19.15-301.fc37.x86_64                            | 1        | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.15  | 45       | 12.06%  |
| 6.0.12  | 44       | 11.8%   |
| 6.0.11  | 32       | 8.58%   |
| 6.0.8   | 27       | 7.24%   |
| 6.0.9   | 26       | 6.97%   |
| 6.0.7   | 25       | 6.7%    |
| 6.0.10  | 23       | 6.17%   |
| 6.1.6   | 18       | 4.83%   |
| 5.19.16 | 15       | 4.02%   |
| 6.1.7   | 14       | 3.75%   |
| 6.1.8   | 10       | 2.68%   |
| 6.1.5   | 10       | 2.68%   |
| 6.0.17  | 9        | 2.41%   |
| 6.0.16  | 8        | 2.14%   |
| 6.0.14  | 8        | 2.14%   |
| 5.19.9  | 8        | 2.14%   |
| 5.19.13 | 8        | 2.14%   |
| 6.0.18  | 7        | 1.88%   |
| 6.0.13  | 6        | 1.61%   |
| 5.19.8  | 4        | 1.07%   |
| 5.19.7  | 4        | 1.07%   |
| 6.0.5   | 3        | 0.8%    |
| 6.0.6   | 2        | 0.54%   |
| 5.19.14 | 2        | 0.54%   |
| 5.19.12 | 2        | 0.54%   |
| 5.19.10 | 2        | 0.54%   |
| 5.19.0  | 2        | 0.54%   |
| 6.1.2   | 1        | 0.27%   |
| 6.1.0   | 1        | 0.27%   |
| 6.0.3   | 1        | 0.27%   |
| 6.0.2   | 1        | 0.27%   |
| 6.0.0   | 1        | 0.27%   |
| 5.8.15  | 1        | 0.27%   |
| 5.19.15 | 1        | 0.27%   |
| 5.18.0  | 1        | 0.27%   |
| 5.17.0  | 1        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 254      | 71.95%  |
| 6.1     | 51       | 14.45%  |
| 5.19    | 45       | 12.75%  |
| 5.8     | 1        | 0.28%   |
| 5.18    | 1        | 0.28%   |
| 5.17    | 1        | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 343      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 252      | 73.26%  |
| KDE5                         | 64       | 18.6%   |
| XFCE                         | 7        | 2.03%   |
| Unknown                      | 6        | 1.74%   |
| Cinnamon                     | 5        | 1.45%   |
| X-Cinnamon                   | 4        | 1.16%   |
| MATE                         | 3        | 0.87%   |
| LXDE                         | 1        | 0.29%   |
| i3                           | 1        | 0.29%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 221      | 63.87%  |
| X11     | 112      | 32.37%  |
| Tty     | 8        | 2.31%   |
| Unknown | 5        | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 191      | 55.52%  |
| GDM     | 99       | 28.78%  |
| SDDM    | 32       | 9.3%    |
| LightDM | 21       | 6.1%    |
| LXDM    | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 179      | 52.19%  |
| en_GB          | 30       | 8.75%   |
| pt_BR          | 21       | 6.12%   |
| ru_RU          | 20       | 5.83%   |
| pl_PL          | 12       | 3.5%    |
| en_AU          | 11       | 3.21%   |
| de_DE          | 11       | 3.21%   |
| fr_FR          | 9        | 2.62%   |
| en_CA          | 9        | 2.62%   |
| es_ES          | 8        | 2.33%   |
| it_IT          | 7        | 2.04%   |
| hu_HU          | 3        | 0.87%   |
| fi_FI          | 3        | 0.87%   |
| cs_CZ          | 3        | 0.87%   |
| en_NZ          | 2        | 0.58%   |
| C              | 2        | 0.58%   |
| tr_TR          | 1        | 0.29%   |
| sv_SE          | 1        | 0.29%   |
| ru_UA          | 1        | 0.29%   |
| pt_PT          | 1        | 0.29%   |
| nl_NL          | 1        | 0.29%   |
| es_UY          | 1        | 0.29%   |
| es_PE          | 1        | 0.29%   |
| en_IE          | 1        | 0.29%   |
| de_CH          | 1        | 0.29%   |
| de_AT          | 1        | 0.29%   |
| ca_ES@valencia | 1        | 0.29%   |
| ca_ES          | 1        | 0.29%   |
| Unknown        | 1        | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 246      | 71.3%   |
| BIOS | 99       | 28.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 265      | 77.26%  |
| Ext4  | 64       | 18.66%  |
| Xfs   | 12       | 3.5%    |
| F2fs  | 2        | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 186      | 53.76%  |
| GPT     | 139      | 40.17%  |
| MBR     | 21       | 6.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 298      | 86.38%  |
| Yes       | 47       | 13.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 276      | 80%     |
| Yes       | 69       | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 117      | 34.11%  |
| Gigabyte Technology                  | 61       | 17.78%  |
| MSI                                  | 57       | 16.62%  |
| ASRock                               | 33       | 9.62%   |
| Dell                                 | 26       | 7.58%   |
| Hewlett-Packard                      | 15       | 4.37%   |
| Lenovo                               | 8        | 2.33%   |
| Intel                                | 5        | 1.46%   |
| Acer                                 | 4        | 1.17%   |
| Positivo                             | 3        | 0.87%   |
| AZW                                  | 2        | 0.58%   |
| Unknown                              | 2        | 0.58%   |
| Shuttle                              | 1        | 0.29%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.29%   |
| Pegatron                             | 1        | 0.29%   |
| MACHINIST                            | 1        | 0.29%   |
| Itautec                              | 1        | 0.29%   |
| Huanan                               | 1        | 0.29%   |
| GALAX                                | 1        | 0.29%   |
| Fujitsu                              | 1        | 0.29%   |
| ECS                                  | 1        | 0.29%   |
| Apple                                | 1        | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 10       | 2.92%   |
| Dell OptiPlex 7010                 | 6        | 1.75%   |
| MSI MS-7C02                        | 4        | 1.17%   |
| ASUS TUF Gaming B550M-PLUS         | 4        | 1.17%   |
| ASUS ROG STRIX B450-F GAMING       | 4        | 1.17%   |
| MSI MS-7C84                        | 3        | 0.87%   |
| MSI MS-7C56                        | 3        | 0.87%   |
| MSI MS-7C37                        | 3        | 0.87%   |
| MSI MS-7A38                        | 3        | 0.87%   |
| Gigabyte B550M DS3H                | 3        | 0.87%   |
| ASUS TUF Gaming X570-PLUS          | 3        | 0.87%   |
| ASUS ROG STRIX X670E-F GAMING WIFI | 3        | 0.87%   |
| ASUS ROG STRIX X570-E GAMING       | 3        | 0.87%   |
| ASUS ProArt Z690-CREATOR WIFI      | 3        | 0.87%   |
| ASUS ProArt X670E-CREATOR WIFI     | 3        | 0.87%   |
| ASUS PRIME X370-PRO                | 3        | 0.87%   |
| ASUS PRIME B550-PLUS               | 3        | 0.87%   |
| ASUS PRIME B450M-A II              | 3        | 0.87%   |
| Positivo POS-PIQ57BQ               | 2        | 0.58%   |
| MSI MS-7D25                        | 2        | 0.58%   |
| MSI MS-7D22                        | 2        | 0.58%   |
| MSI MS-7C91                        | 2        | 0.58%   |
| MSI MS-7B98                        | 2        | 0.58%   |
| MSI MS-7B78                        | 2        | 0.58%   |
| Gigabyte X570 AORUS MASTER         | 2        | 0.58%   |
| Gigabyte J1900M-D2P                | 2        | 0.58%   |
| Gigabyte GA-78LMT-USB3 6.0         | 2        | 0.58%   |
| Dell OptiPlex 790                  | 2        | 0.58%   |
| ASUS TUF Gaming B550-PLUS          | 2        | 0.58%   |
| ASUS ROG Strix GA15DH_G15DH        | 2        | 0.58%   |
| ASUS ROG STRIX B550-F GAMING       | 2        | 0.58%   |
| ASUS ROG STRIX B450-F GAMING II    | 2        | 0.58%   |
| ASUS ROG CROSSHAIR VIII IMPACT     | 2        | 0.58%   |
| ASUS ROG CROSSHAIR VII HERO        | 2        | 0.58%   |
| ASUS PRIME Z270-A                  | 2        | 0.58%   |
| ASUS PRIME X670E-PRO WIFI          | 2        | 0.58%   |
| ASUS PRIME B550M-A                 | 2        | 0.58%   |
| ASUS PRIME B450M-GAMING/BR         | 2        | 0.58%   |
| ASRock X79 Extreme6                | 2        | 0.58%   |
| ASRock X670E Steel Legend          | 2        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 33       | 9.62%   |
| ASUS ROG               | 29       | 8.45%   |
| ASUS TUF               | 19       | 5.54%   |
| Dell OptiPlex          | 15       | 4.37%   |
| ASUS All               | 10       | 2.92%   |
| ASUS ProArt            | 6        | 1.75%   |
| Gigabyte X570          | 5        | 1.46%   |
| Dell Precision         | 5        | 1.46%   |
| Dell Inspiron          | 5        | 1.46%   |
| MSI MS-7C02            | 4        | 1.17%   |
| Lenovo ThinkCentre     | 4        | 1.17%   |
| HP Compaq              | 4        | 1.17%   |
| Gigabyte B550M         | 4        | 1.17%   |
| Acer Aspire            | 4        | 1.17%   |
| MSI MS-7C84            | 3        | 0.87%   |
| MSI MS-7C56            | 3        | 0.87%   |
| MSI MS-7C37            | 3        | 0.87%   |
| MSI MS-7A38            | 3        | 0.87%   |
| HP Pavilion            | 3        | 0.87%   |
| Gigabyte B550          | 3        | 0.87%   |
| Gigabyte B450M         | 3        | 0.87%   |
| ASRock X670E           | 3        | 0.87%   |
| Positivo POS-PIQ57BQ   | 2        | 0.58%   |
| MSI MS-7D25            | 2        | 0.58%   |
| MSI MS-7D22            | 2        | 0.58%   |
| MSI MS-7C91            | 2        | 0.58%   |
| MSI MS-7B98            | 2        | 0.58%   |
| MSI MS-7B78            | 2        | 0.58%   |
| HP EliteDesk           | 2        | 0.58%   |
| Gigabyte Z690          | 2        | 0.58%   |
| Gigabyte J1900M-D2P    | 2        | 0.58%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.58%   |
| Gigabyte B365M         | 2        | 0.58%   |
| ASUS SABERTOOTH        | 2        | 0.58%   |
| ASUS P8Z77-V           | 2        | 0.58%   |
| ASUS P8Z68-V           | 2        | 0.58%   |
| ASRock X79             | 2        | 0.58%   |
| ASRock X570            | 2        | 0.58%   |
| ASRock X300-ITX        | 2        | 0.58%   |
| ASRock FM2A88X         | 2        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 52       | 15.16%  |
| 2019 | 46       | 13.41%  |
| 2018 | 39       | 11.37%  |
| 2022 | 34       | 9.91%   |
| 2021 | 31       | 9.04%   |
| 2013 | 24       | 7%      |
| 2012 | 24       | 7%      |
| 2017 | 21       | 6.12%   |
| 2014 | 19       | 5.54%   |
| 2015 | 11       | 3.21%   |
| 2010 | 11       | 3.21%   |
| 2009 | 11       | 3.21%   |
| 2011 | 10       | 2.92%   |
| 2016 | 5        | 1.46%   |
| 2008 | 3        | 0.87%   |
| 2007 | 1        | 0.29%   |
| 2006 | 1        | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 343      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 312      | 90.7%   |
| Enabled  | 32       | 9.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 343      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 105      | 30.43%  |
| 32.01-64.0      | 95       | 27.54%  |
| 8.01-16.0       | 49       | 14.2%   |
| 64.01-256.0     | 32       | 9.28%   |
| 4.01-8.0        | 22       | 6.38%   |
| 24.01-32.0      | 22       | 6.38%   |
| 3.01-4.0        | 17       | 4.93%   |
| 1.01-2.0        | 2        | 0.58%   |
| More than 256.0 | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 110      | 30.56%  |
| 3.01-4.0   | 89       | 24.72%  |
| 2.01-3.0   | 76       | 21.11%  |
| 8.01-16.0  | 43       | 11.94%  |
| 1.01-2.0   | 31       | 8.61%   |
| 0.51-1.0   | 6        | 1.67%   |
| 16.01-24.0 | 2        | 0.56%   |
| 32.01-64.0 | 1        | 0.28%   |
| 24.01-32.0 | 1        | 0.28%   |
| 0.01-0.5   | 1        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 105      | 30.26%  |
| 1      | 97       | 27.95%  |
| 3      | 75       | 21.61%  |
| 4      | 39       | 11.24%  |
| 5      | 13       | 3.75%   |
| 6      | 7        | 2.02%   |
| 7      | 4        | 1.15%   |
| 8      | 2        | 0.58%   |
| 18     | 1        | 0.29%   |
| 15     | 1        | 0.29%   |
| 12     | 1        | 0.29%   |
| 9      | 1        | 0.29%   |
| 0      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 250      | 72.67%  |
| Yes       | 94       | 27.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 341      | 99.42%  |
| No        | 2        | 0.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 174      | 50.58%  |
| No        | 170      | 49.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 175      | 50.58%  |
| No        | 171      | 49.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 86       | 24.86%  |
| Brazil       | 27       | 7.8%    |
| Germany      | 23       | 6.65%   |
| Russia       | 19       | 5.49%   |
| UK           | 16       | 4.62%   |
| Poland       | 16       | 4.62%   |
| France       | 13       | 3.76%   |
| Italy        | 12       | 3.47%   |
| Australia    | 12       | 3.47%   |
| Spain        | 11       | 3.18%   |
| Netherlands  | 9        | 2.6%    |
| Canada       | 9        | 2.6%    |
| Sweden       | 7        | 2.02%   |
| Austria      | 6        | 1.73%   |
| Romania      | 5        | 1.45%   |
| Hungary      | 5        | 1.45%   |
| Czechia      | 5        | 1.45%   |
| Switzerland  | 4        | 1.16%   |
| Turkey       | 3        | 0.87%   |
| Portugal     | 3        | 0.87%   |
| Indonesia    | 3        | 0.87%   |
| Greece       | 3        | 0.87%   |
| Finland      | 3        | 0.87%   |
| Belgium      | 3        | 0.87%   |
| Vietnam      | 2        | 0.58%   |
| Thailand     | 2        | 0.58%   |
| Singapore    | 2        | 0.58%   |
| Saudi Arabia | 2        | 0.58%   |
| Norway       | 2        | 0.58%   |
| New Zealand  | 2        | 0.58%   |
| Malaysia     | 2        | 0.58%   |
| Latvia       | 2        | 0.58%   |
| Belarus      | 2        | 0.58%   |
| Uruguay      | 1        | 0.29%   |
| Ukraine      | 1        | 0.29%   |
| Uganda       | 1        | 0.29%   |
| UAE          | 1        | 0.29%   |
| Taiwan       | 1        | 0.29%   |
| South Korea  | 1        | 0.29%   |
| South Africa | 1        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sydney           | 7        | 1.98%   |
| Warsaw           | 6        | 1.69%   |
| Moscow           | 5        | 1.41%   |
| Berlin           | 5        | 1.41%   |
| Palmas           | 4        | 1.13%   |
| London           | 4        | 1.13%   |
| Budapest         | 4        | 1.13%   |
| Vienna           | 3        | 0.85%   |
| Sao Paulo        | 3        | 0.85%   |
| Hamburg          | 3        | 0.85%   |
| Yekaterinburg    | 2        | 0.56%   |
| Vancouver        | 2        | 0.56%   |
| Singapore        | 2        | 0.56%   |
| Seattle          | 2        | 0.56%   |
| Saratov          | 2        | 0.56%   |
| Santa Clara      | 2        | 0.56%   |
| Rochester        | 2        | 0.56%   |
| Riga             | 2        | 0.56%   |
| Prague           | 2        | 0.56%   |
| Porto Alegre     | 2        | 0.56%   |
| Minsk            | 2        | 0.56%   |
| Melbourne        | 2        | 0.56%   |
| Krasnodar        | 2        | 0.56%   |
| Ho Chi Minh City | 2        | 0.56%   |
| Helsinki         | 2        | 0.56%   |
| Goiânia         | 2        | 0.56%   |
| Bucharest        | 2        | 0.56%   |
| Bristol          | 2        | 0.56%   |
| Antwerp          | 2        | 0.56%   |
| Ankara           | 2        | 0.56%   |
| Amsterdam        | 2        | 0.56%   |
| Zurich           | 1        | 0.28%   |
| Zierikzee        | 1        | 0.28%   |
| York             | 1        | 0.28%   |
| Yogyakarta       | 1        | 0.28%   |
| Willowbrook      | 1        | 0.28%   |
| Westlake         | 1        | 0.28%   |
| Westford         | 1        | 0.28%   |
| Waterville       | 1        | 0.28%   |
| Waterbury        | 1        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Samsung Electronics            | 157      | 240    | 22.4%   |
| WDC                            | 111      | 181    | 15.83%  |
| Seagate                        | 109      | 150    | 15.55%  |
| Kingston                       | 51       | 61     | 7.28%   |
| SanDisk                        | 49       | 58     | 6.99%   |
| Crucial                        | 39       | 46     | 5.56%   |
| Toshiba                        | 33       | 44     | 4.71%   |
| Phison Electronics             | 16       | 18     | 2.28%   |
| Intel                          | 14       | 19     | 2%      |
| Hitachi                        | 13       | 17     | 1.85%   |
| Micron/Crucial Technology      | 10       | 12     | 1.43%   |
| China                          | 8        | 10     | 1.14%   |
| Unknown                        | 6        | 8      | 0.86%   |
| SPCC                           | 6        | 9      | 0.86%   |
| HGST                           | 6        | 17     | 0.86%   |
| Apacer                         | 6        | 8      | 0.86%   |
| A-DATA Technology              | 6        | 6      | 0.86%   |
| Corsair                        | 4        | 6      | 0.57%   |
| Silicon Motion                 | 3        | 4      | 0.43%   |
| Realtek Semiconductor          | 3        | 3      | 0.43%   |
| ADATA Technology               | 3        | 3      | 0.43%   |
| SK hynix                       | 2        | 2      | 0.29%   |
| PNY                            | 2        | 2      | 0.29%   |
| Plextor                        | 2        | 2      | 0.29%   |
| Micron Technology              | 2        | 2      | 0.29%   |
| Lite-On Technology             | 2        | 2      | 0.29%   |
| Lexar                          | 2        | 3      | 0.29%   |
| GOODRAM                        | 2        | 3      | 0.29%   |
| ASMT                           | 2        | 3      | 0.29%   |
| XSTAR                          | 1        | 1      | 0.14%   |
| USB3.0                         | 1        | 1      | 0.14%   |
| Transcend                      | 1        | 1      | 0.14%   |
| Team                           | 1        | 1      | 0.14%   |
| Super Talent                   | 1        | 1      | 0.14%   |
| Solid State Storage Technology | 1        | 2      | 0.14%   |
| Seagate Technology             | 1        | 1      | 0.14%   |
| SABRENT                        | 1        | 1      | 0.14%   |
| Phison                         | 1        | 1      | 0.14%   |
| Patriot                        | 1        | 1      | 0.14%   |
| OWC                            | 1        | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 31       | 3.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 17       | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB                       | 15       | 1.84%   |
| Kingston SA400S37240G 240GB SSD                      | 15       | 1.84%   |
| Samsung SSD 850 EVO 250GB                            | 10       | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB                       | 9        | 1.1%    |
| Samsung SSD 870 EVO 500GB                            | 9        | 1.1%    |
| Crucial CT1000MX500SSD1 1TB                          | 9        | 1.1%    |
| Seagate ST500DM002-1BD142 500GB                      | 8        | 0.98%   |
| Phison E12 NVMe Controller 1TB                       | 8        | 0.98%   |
| Samsung SSD 860 EVO 500GB                            | 7        | 0.86%   |
| Samsung SSD 850 EVO 500GB                            | 7        | 0.86%   |
| Kingston SA400S37120G 120GB SSD                      | 7        | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 6        | 0.73%   |
| Toshiba DT01ACA200 2TB                               | 6        | 0.73%   |
| Seagate ST2000DM008-2UB102 2TB                       | 6        | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB                       | 6        | 0.73%   |
| Samsung SSD 870 EVO 1TB                              | 6        | 0.73%   |
| Samsung SSD 860 EVO 1TB                              | 6        | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 6        | 0.73%   |
| Toshiba DT01ACA100 1TB                               | 5        | 0.61%   |
| Seagate ST31000528AS 1TB                             | 5        | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB                       | 5        | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB                       | 5        | 0.61%   |
| Samsung SSD 970 EVO Plus 2TB                         | 5        | 0.61%   |
| Samsung SSD 870 QVO 2TB                              | 5        | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 5        | 0.61%   |
| Phison E16 PCIe4 NVMe Controller 2TB                 | 5        | 0.61%   |
| Kingston SA400S37480G 480GB SSD                      | 5        | 0.61%   |
| Intel SSD 660P Series 512GB                          | 5        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 4        | 0.49%   |
| WDC WD30EFRX-68EUZN0 3TB                             | 4        | 0.49%   |
| WDC WD10EZEX-60WN4A0 1TB                             | 4        | 0.49%   |
| Toshiba DT01ACA300 3TB                               | 4        | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4        | 0.49%   |
| Samsung SSD 980 PRO 1TB                              | 4        | 0.49%   |
| Samsung SSD 980 1TB                                  | 4        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                         | 4        | 0.49%   |
| Samsung SSD 960 EVO 250GB                            | 4        | 0.49%   |
| Samsung SSD 860 EVO 250GB                            | 4        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 107      | 148    | 41.47%  |
| WDC                 | 92       | 147    | 35.66%  |
| Toshiba             | 26       | 35     | 10.08%  |
| Hitachi             | 13       | 17     | 5.04%   |
| Samsung Electronics | 8        | 10     | 3.1%    |
| HGST                | 6        | 17     | 2.33%   |
| Unknown             | 2        | 2      | 0.78%   |
| USB3.0              | 1        | 1      | 0.39%   |
| SABRENT             | 1        | 1      | 0.39%   |
| Maxtor              | 1        | 1      | 0.39%   |
| ASMT                | 1        | 2      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 76       | 106    | 31.4%   |
| Kingston            | 38       | 46     | 15.7%   |
| Crucial             | 37       | 42     | 15.29%  |
| SanDisk             | 20       | 20     | 8.26%   |
| WDC                 | 14       | 18     | 5.79%   |
| China               | 8        | 10     | 3.31%   |
| Intel               | 6        | 8      | 2.48%   |
| Toshiba             | 4        | 4      | 1.65%   |
| SPCC                | 4        | 6      | 1.65%   |
| Apacer              | 4        | 5      | 1.65%   |
| Unknown             | 2        | 2      | 0.83%   |
| PNY                 | 2        | 2      | 0.83%   |
| Plextor             | 2        | 2      | 0.83%   |
| Lexar               | 2        | 3      | 0.83%   |
| GOODRAM             | 2        | 3      | 0.83%   |
| Corsair             | 2        | 3      | 0.83%   |
| A-DATA Technology   | 2        | 2      | 0.83%   |
| XSTAR               | 1        | 1      | 0.41%   |
| Transcend           | 1        | 1      | 0.41%   |
| Super Talent        | 1        | 1      | 0.41%   |
| SK hynix            | 1        | 1      | 0.41%   |
| Patriot             | 1        | 1      | 0.41%   |
| OWC                 | 1        | 1      | 0.41%   |
| OCZ                 | 1        | 1      | 0.41%   |
| Netac               | 1        | 1      | 0.41%   |
| Mushkin             | 1        | 1      | 0.41%   |
| Mercury             | 1        | 1      | 0.41%   |
| LITEON              | 1        | 1      | 0.41%   |
| KingSpec            | 1        | 1      | 0.41%   |
| KingFast            | 1        | 1      | 0.41%   |
| KingDian            | 1        | 1      | 0.41%   |
| BIWIN               | 1        | 1      | 0.41%   |
| AMD                 | 1        | 2      | 0.41%   |
| Acer                | 1        | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 198      | 300    | 33.11%  |
| HDD     | 197      | 381    | 32.94%  |
| NVMe    | 194      | 281    | 32.44%  |
| Unknown | 9        | 11     | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 277      | 654    | 55.73%  |
| NVMe | 194      | 281    | 39.03%  |
| SAS  | 26       | 38     | 5.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 185      | 285    | 42.33%  |
| 0.51-1.0   | 131      | 195    | 29.98%  |
| 1.01-2.0   | 60       | 81     | 13.73%  |
| 3.01-4.0   | 23       | 36     | 5.26%   |
| 4.01-10.0  | 19       | 31     | 4.35%   |
| 2.01-3.0   | 17       | 35     | 3.89%   |
| 10.01-20.0 | 2        | 18     | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 66       | 19.02%  |
| 501-1000       | 63       | 18.16%  |
| More than 3000 | 58       | 16.71%  |
| 251-500        | 41       | 11.82%  |
| 2001-3000      | 39       | 11.24%  |
| 101-250        | 28       | 8.07%   |
| 1-20           | 22       | 6.34%   |
| Unknown        | 18       | 5.19%   |
| 51-100         | 10       | 2.88%   |
| 21-50          | 2        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 68       | 19.32%  |
| 501-1000       | 59       | 16.76%  |
| 101-250        | 40       | 11.36%  |
| 251-500        | 39       | 11.08%  |
| 1001-2000      | 38       | 10.8%   |
| 21-50          | 36       | 10.23%  |
| 51-100         | 25       | 7.1%    |
| Unknown        | 18       | 5.11%   |
| More than 3000 | 17       | 4.83%   |
| 2001-3000      | 12       | 3.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 5.17%   |
| Intel SSDSC2CT120A3 120GB             | 2        | 4      | 3.45%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-603CA0 500GB           | 1        | 1      | 1.72%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 1      | 1.72%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1        | 1      | 1.72%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 1.72%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 1.72%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 1      | 1.72%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1        | 1      | 1.72%   |
| WDC WD20EZRX-22D8PB0 2TB              | 1        | 1      | 1.72%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 1.72%   |
| WDC WD15EARS-00MVWB0 1TB              | 1        | 1      | 1.72%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1        | 2      | 1.72%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 2      | 1.72%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.72%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 1      | 1.72%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 1.72%   |
| Toshiba MK7559GSXP 752GB              | 1        | 1      | 1.72%   |
| Toshiba MK3263GSX 320GB               | 1        | 1      | 1.72%   |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1        | 1      | 1.72%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 1.72%   |
| Seagate ST8000NE001-2M7101 8TB        | 1        | 1      | 1.72%   |
| Seagate ST6000DM003-2CY186 6TB        | 1        | 1      | 1.72%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 1.72%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.72%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 1.72%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 1.72%   |
| Seagate ST32000641AS 2TB              | 1        | 1      | 1.72%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.72%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 1.72%   |
| Seagate ST31000340NS 1TB              | 1        | 1      | 1.72%   |
| Seagate ST3000DM001-1ER166 3TB        | 1        | 1      | 1.72%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 3      | 1.72%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 1.72%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 1.72%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.72%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 20     | 30.19%  |
| WDC                 | 15       | 19     | 28.3%   |
| Samsung Electronics | 7        | 10     | 13.21%  |
| Intel               | 3        | 5      | 5.66%   |
| Crucial             | 3        | 3      | 5.66%   |
| Toshiba             | 2        | 2      | 3.77%   |
| SPCC                | 1        | 1      | 1.89%   |
| SK hynix            | 1        | 1      | 1.89%   |
| Maxtor              | 1        | 1      | 1.89%   |
| Kingston            | 1        | 1      | 1.89%   |
| Hitachi             | 1        | 1      | 1.89%   |
| Corsair             | 1        | 1      | 1.89%   |
| AMD                 | 1        | 2      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 20     | 41.03%  |
| WDC                 | 15       | 19     | 38.46%  |
| Samsung Electronics | 4        | 6      | 10.26%  |
| Toshiba             | 2        | 2      | 5.13%   |
| Maxtor              | 1        | 1      | 2.56%   |
| Hitachi             | 1        | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 49     | 70.83%  |
| SSD  | 14       | 18     | 29.17%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB    | 1        | 1      | 50%     |
| Seagate ST31000528AS 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SPCC    | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 207      | 541    | 52.67%  |
| Works    | 139      | 363    | 35.37%  |
| Malfunc  | 45       | 67     | 11.45%  |
| Failed   | 2        | 2      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 182      | 30.74%  |
| AMD                            | 157      | 26.52%  |
| Samsung Electronics            | 92       | 15.54%  |
| SanDisk                        | 40       | 6.76%   |
| Phison Electronics             | 22       | 3.72%   |
| ASMedia Technology             | 20       | 3.38%   |
| Kingston Technology Company    | 15       | 2.53%   |
| Micron/Crucial Technology      | 12       | 2.03%   |
| Marvell Technology Group       | 9        | 1.52%   |
| Silicon Motion                 | 6        | 1.01%   |
| ADATA Technology               | 6        | 1.01%   |
| Realtek Semiconductor          | 4        | 0.68%   |
| Toshiba America Info Systems   | 3        | 0.51%   |
| Nvidia                         | 3        | 0.51%   |
| JMicron Technology             | 3        | 0.51%   |
| Broadcom / LSI                 | 3        | 0.51%   |
| VIA Technologies               | 2        | 0.34%   |
| Micron Technology              | 2        | 0.34%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.34%   |
| LSI Logic / Symbios Logic      | 2        | 0.34%   |
| Lite-On Technology             | 2        | 0.34%   |
| Solidigm                       | 1        | 0.17%   |
| Solid State Storage Technology | 1        | 0.17%   |
| SK hynix                       | 1        | 0.17%   |
| Seagate Technology             | 1        | 0.17%   |
| Biwin Storage Technology       | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 71       | 10.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 53       | 7.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 39       | 5.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 30       | 4.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 28       | 4.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 20       | 2.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 19       | 2.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19       | 2.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19       | 2.77%   |
| AMD SATA controller                                                            | 17       | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 15       | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15       | 2.19%   |
| Intel SATA Controller [RAID mode]                                              | 13       | 1.9%    |
| SanDisk Non-Volatile memory controller                                         | 12       | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12       | 1.75%   |
| Phison E12 NVMe Controller                                                     | 11       | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10       | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10       | 1.46%   |
| Kingston Company Company Non-Volatile memory controller                        | 9        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8        | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 8        | 1.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7        | 1.02%   |
| Samsung NVMe SSD Controller 980                                                | 7        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7        | 1.02%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6        | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6        | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 0.88%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5        | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                               | 5        | 0.73%   |
| Intel SSD 660P Series                                                          | 5        | 0.73%   |
| AMD X370 Series Chipset SATA Controller                                        | 5        | 0.73%   |
| AMD FCH SATA Controller D                                                      | 5        | 0.73%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4        | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4        | 0.58%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 300      | 52.36%  |
| NVMe | 193      | 33.68%  |
| IDE  | 42       | 7.33%   |
| RAID | 32       | 5.58%   |
| SAS  | 5        | 0.87%   |
| SCSI | 1        | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 179      | 52.19%  |
| AMD    | 164      | 47.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 16       | 4.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 12       | 3.5%    |
| AMD Ryzen 5 5600X 6-Core Processor     | 10       | 2.92%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 9        | 2.62%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 9        | 2.62%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 8        | 2.33%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 7        | 2.04%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 7        | 2.04%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 7        | 2.04%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 7        | 2.04%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 5        | 1.46%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 5        | 1.46%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 5        | 1.46%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 5        | 1.46%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 5        | 1.46%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 5        | 1.46%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 4        | 1.17%   |
| Intel 12th Gen Core i9-12900K          | 4        | 1.17%   |
| Intel 12th Gen Core i7-12700           | 4        | 1.17%   |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 4        | 1.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 4        | 1.17%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3        | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 3        | 0.87%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 3        | 0.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 3        | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 0.87%   |
| Intel 12th Gen Core i5-12600K          | 3        | 0.87%   |
| Intel 12th Gen Core i3-12100F          | 3        | 0.87%   |
| AMD Ryzen 5 3500X 6-Core Processor     | 3        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 0.87%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 2        | 0.58%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 2        | 0.58%   |
| Intel Core i7-9700F CPU @ 3.00GHz      | 2        | 0.58%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 0.58%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 2        | 0.58%   |
| Intel Core i7-3770S CPU @ 3.10GHz      | 2        | 0.58%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 2        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 62       | 18.08%  |
| Intel Core i7           | 61       | 17.78%  |
| AMD Ryzen 7             | 39       | 11.37%  |
| Intel Core i5           | 38       | 11.08%  |
| AMD Ryzen 9             | 30       | 8.75%   |
| Other                   | 26       | 7.58%   |
| Intel Xeon              | 14       | 4.08%   |
| Intel Core i3           | 13       | 3.79%   |
| AMD FX                  | 10       | 2.92%   |
| Intel Core i9           | 5        | 1.46%   |
| Intel Core 2 Quad       | 5        | 1.46%   |
| Intel Pentium           | 4        | 1.17%   |
| Intel Pentium Dual-Core | 3        | 0.87%   |
| Intel Core 2 Duo        | 3        | 0.87%   |
| Intel Celeron           | 3        | 0.87%   |
| AMD Ryzen 3             | 3        | 0.87%   |
| AMD Phenom II X6        | 3        | 0.87%   |
| AMD A10                 | 3        | 0.87%   |
| Intel Atom              | 2        | 0.58%   |
| AMD Ryzen Threadripper  | 2        | 0.58%   |
| AMD Phenom II X4        | 2        | 0.58%   |
| AMD A8                  | 2        | 0.58%   |
| AMD A4                  | 2        | 0.58%   |
| Intel Pentium Gold      | 1        | 0.29%   |
| Intel Pentium Dual      | 1        | 0.29%   |
| AMD Ryzen 5 PRO         | 1        | 0.29%   |
| AMD Ryzen 3 PRO         | 1        | 0.29%   |
| AMD PRO A10             | 1        | 0.29%   |
| AMD Athlon II X4        | 1        | 0.29%   |
| AMD Athlon II X2        | 1        | 0.29%   |
| AMD A6                  | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 104      | 30.32%  |
| 6      | 84       | 24.49%  |
| 8      | 63       | 18.37%  |
| 2      | 33       | 9.62%   |
| 12     | 22       | 6.41%   |
| 16     | 21       | 6.12%   |
| 10     | 7        | 2.04%   |
| 3      | 4        | 1.17%   |
| 24     | 2        | 0.58%   |
| 32     | 1        | 0.29%   |
| 14     | 1        | 0.29%   |
| 1      | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 338      | 98.54%  |
| 2      | 5        | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 255      | 74.34%  |
| 1      | 88       | 25.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 343      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 36       | 10.43%  |
| 0x306a9    | 24       | 6.96%   |
| 0x306c3    | 22       | 6.38%   |
| 0x90672    | 14       | 4.06%   |
| 0x0a601203 | 13       | 3.77%   |
| 0x0a201016 | 13       | 3.77%   |
| 0x906ea    | 12       | 3.48%   |
| 0x506e3    | 12       | 3.48%   |
| 0x906ed    | 11       | 3.19%   |
| Unknown    | 11       | 3.19%   |
| 0x206a7    | 10       | 2.9%    |
| 0x0a50000d | 10       | 2.9%    |
| 0x0a20120a | 9        | 2.61%   |
| 0x08701013 | 8        | 2.32%   |
| 0x906e9    | 7        | 2.03%   |
| 0x206d7    | 7        | 2.03%   |
| 0x1067a    | 7        | 2.03%   |
| 0xa0655    | 6        | 1.74%   |
| 0x0800820d | 6        | 1.74%   |
| 0x06000822 | 6        | 1.74%   |
| 0xa0671    | 5        | 1.45%   |
| 0x0a50000c | 5        | 1.45%   |
| 0x0a50000b | 5        | 1.45%   |
| 0x0a201009 | 5        | 1.45%   |
| 0x90675    | 4        | 1.16%   |
| 0x0a601201 | 4        | 1.16%   |
| 0x0a201205 | 4        | 1.16%   |
| 0x08001138 | 4        | 1.16%   |
| 0xa0653    | 3        | 0.87%   |
| 0x906ec    | 3        | 0.87%   |
| 0x6fb      | 3        | 0.87%   |
| 0x08108109 | 3        | 0.87%   |
| 0x06001119 | 3        | 0.87%   |
| 0xb0671    | 2        | 0.58%   |
| 0x906eb    | 2        | 0.58%   |
| 0x6fd      | 2        | 0.58%   |
| 0x50657    | 2        | 0.58%   |
| 0x306f2    | 2        | 0.58%   |
| 0x30678    | 2        | 0.58%   |
| 0x206c2    | 2        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 53       | 15.45%  |
| Zen 2            | 48       | 13.99%  |
| KabyLake         | 36       | 10.5%   |
| Haswell          | 25       | 7.29%   |
| IvyBridge        | 24       | 7%      |
| Alderlake Hybrid | 20       | 5.83%   |
| Unknown          | 19       | 5.54%   |
| SandyBridge      | 17       | 4.96%   |
| Skylake          | 15       | 4.37%   |
| Piledriver       | 11       | 3.21%   |
| Zen+             | 10       | 2.92%   |
| Zen              | 9        | 2.62%   |
| Penryn           | 9        | 2.62%   |
| CometLake        | 9        | 2.62%   |
| K10              | 6        | 1.75%   |
| Westmere         | 5        | 1.46%   |
| Icelake          | 5        | 1.46%   |
| Core             | 5        | 1.46%   |
| Nehalem          | 3        | 0.87%   |
| Excavator        | 3        | 0.87%   |
| Steamroller      | 2        | 0.58%   |
| Silvermont       | 2        | 0.58%   |
| Bulldozer        | 2        | 0.58%   |
| Bonnell          | 2        | 0.58%   |
| Tremont          | 1        | 0.29%   |
| K10 Llano        | 1        | 0.29%   |
| Jaguar           | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 153      | 41.46%  |
| AMD               | 153      | 41.46%  |
| Intel             | 62       | 16.8%   |
| ASPEED Technology | 1        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 32       | 8.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 17       | 4.39%   |
| AMD Raphael                                                                 | 16       | 4.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 15       | 3.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13       | 3.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 2.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 2.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 2.07%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 7        | 1.81%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 7        | 1.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 7        | 1.81%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.81%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 1.55%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 1.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.29%   |
| Intel HD Graphics 530                                                       | 5        | 1.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1.29%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.03%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.03%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 1.03%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.03%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 1.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.03%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.78%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 0.78%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.78%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 3        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 0.78%   |
| Intel HD Graphics 630                                                       | 3        | 0.78%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 134      | 38.95%  |
| 1 x AMD                 | 132      | 38.37%  |
| 1 x Intel               | 43       | 12.5%   |
| 2 x AMD                 | 13       | 3.78%   |
| Intel + Nvidia          | 8        | 2.33%   |
| AMD + Nvidia            | 7        | 2.03%   |
| 2 x Intel               | 3        | 0.87%   |
| 2 x Nvidia              | 2        | 0.58%   |
| 2 x Nvidia + 1 x ASPEED | 1        | 0.29%   |
| Intel + AMD             | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 246      | 71.3%   |
| Proprietary | 87       | 25.22%  |
| Unknown     | 12       | 3.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 27.09%  |
| 7.01-8.0   | 82       | 23.63%  |
| 1.01-2.0   | 39       | 11.24%  |
| 3.01-4.0   | 34       | 9.8%    |
| 8.01-16.0  | 30       | 8.65%   |
| 0.51-1.0   | 24       | 6.92%   |
| 0.01-0.5   | 23       | 6.63%   |
| 5.01-6.0   | 16       | 4.61%   |
| 2.01-3.0   | 3        | 0.86%   |
| 16.01-24.0 | 2        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 63       | 16.03%  |
| Samsung Electronics  | 55       | 13.99%  |
| Goldstar             | 49       | 12.47%  |
| Hewlett-Packard      | 33       | 8.4%    |
| AOC                  | 22       | 5.6%    |
| Acer                 | 21       | 5.34%   |
| BenQ                 | 20       | 5.09%   |
| ASUSTek Computer     | 14       | 3.56%   |
| Ancor Communications | 14       | 3.56%   |
| Philips              | 12       | 3.05%   |
| Lenovo               | 11       | 2.8%    |
| Sceptre Tech         | 8        | 2.04%   |
| MSI                  | 7        | 1.78%   |
| Gigabyte Technology  | 7        | 1.78%   |
| Iiyama               | 6        | 1.53%   |
| Eizo                 | 5        | 1.27%   |
| NEC Computers        | 4        | 1.02%   |
| Mi                   | 4        | 1.02%   |
| Sony                 | 3        | 0.76%   |
| Pixio                | 3        | 0.76%   |
| ViewSonic            | 2        | 0.51%   |
| Unknown              | 2        | 0.51%   |
| ONN                  | 2        | 0.51%   |
| HannStar             | 2        | 0.51%   |
| Belinea              | 2        | 0.51%   |
| Westinghouse         | 1        | 0.25%   |
| Vizio                | 1        | 0.25%   |
| USR                  | 1        | 0.25%   |
| Panasonic            | 1        | 0.25%   |
| MStar                | 1        | 0.25%   |
| Medion Akoya         | 1        | 0.25%   |
| KTC                  | 1        | 0.25%   |
| JRY                  | 1        | 0.25%   |
| InnoView             | 1        | 0.25%   |
| HVR                  | 1        | 0.25%   |
| HUAWEI               | 1        | 0.25%   |
| Hitachi              | 1        | 0.25%   |
| HGC                  | 1        | 0.25%   |
| Haier                | 1        | 0.25%   |
| GMX                  | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4        | 0.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.71%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 3        | 0.71%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 3        | 0.71%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 3        | 0.71%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.71%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                     | 3        | 0.71%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 3        | 0.71%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.47%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch         | 2        | 0.47%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                 | 2        | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2        | 0.47%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch | 2        | 0.47%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.47%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                   | 2        | 0.47%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch               | 2        | 0.47%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch               | 2        | 0.47%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch          | 2        | 0.47%   |
| Hewlett-Packard LA2006 HWP2944 1600x900 443x249mm 20.0-inch            | 2        | 0.47%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 550x310mm 24.9-inch             | 2        | 0.47%   |
| Hewlett-Packard 2311 HWP293B 1920x1080 509x286mm 23.0-inch             | 2        | 0.47%   |
| Goldstar ULTRAGEAR GSM774B 3440x1440 800x335mm 34.1-inch               | 2        | 0.47%   |
| Goldstar UltraFine GSM5B74 3840x2160 600x340mm 27.2-inch               | 2        | 0.47%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                   | 2        | 0.47%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2        | 0.47%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                  | 2        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.47%   |
| Gigabyte Technology AORUS FV43U GBT4300 3840x2160 941x529mm 42.5-inch  | 2        | 0.47%   |
| Dell U2713HM DEL407F 1920x1080 597x336mm 27.0-inch                     | 2        | 0.47%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.47%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 2        | 0.47%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 2        | 0.47%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.47%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                    | 2        | 0.47%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 2        | 0.47%   |
| Dell S2721DS DELA19C 2560x1440 590x330mm 26.6-inch                     | 2        | 0.47%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2        | 0.47%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                      | 2        | 0.47%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 170      | 44.97%  |
| 3840x2160 (4K)     | 58       | 15.34%  |
| 2560x1440 (QHD)    | 55       | 14.55%  |
| 3440x1440          | 23       | 6.08%   |
| 1280x1024 (SXGA)   | 13       | 3.44%   |
| 1680x1050 (WSXGA+) | 10       | 2.65%   |
| 2560x1080          | 8        | 2.12%   |
| 1920x1200 (WUXGA)  | 8        | 2.12%   |
| 1366x768 (WXGA)    | 6        | 1.59%   |
| 1600x900 (HD+)     | 5        | 1.32%   |
| 1440x900 (WXGA+)   | 5        | 1.32%   |
| 1360x768           | 4        | 1.06%   |
| 2560x1600          | 3        | 0.79%   |
| 2288x1287          | 2        | 0.53%   |
| 1600x1200          | 2        | 0.53%   |
| 3840x1600          | 1        | 0.26%   |
| 3840x1080          | 1        | 0.26%   |
| 3120x1600          | 1        | 0.26%   |
| 2560x2880          | 1        | 0.26%   |
| 2160x1200          | 1        | 0.26%   |
| Unknown            | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 88       | 21.84%  |
| 24      | 67       | 16.63%  |
| 23      | 53       | 13.15%  |
| 21      | 34       | 8.44%   |
| 31      | 31       | 7.69%   |
| 34      | 27       | 6.7%    |
| 19      | 12       | 2.98%   |
| 25      | 8        | 1.99%   |
| 22      | 8        | 1.99%   |
| 20      | 8        | 1.99%   |
| Unknown | 8        | 1.99%   |
| 32      | 7        | 1.74%   |
| 18      | 6        | 1.49%   |
| 84      | 5        | 1.24%   |
| 26      | 5        | 1.24%   |
| 40      | 4        | 0.99%   |
| 29      | 4        | 0.99%   |
| 28      | 3        | 0.74%   |
| 142     | 2        | 0.5%    |
| 72      | 2        | 0.5%    |
| 54      | 2        | 0.5%    |
| 52      | 2        | 0.5%    |
| 48      | 2        | 0.5%    |
| 42      | 2        | 0.5%    |
| 39      | 2        | 0.5%    |
| 36      | 2        | 0.5%    |
| 17      | 2        | 0.5%    |
| 15      | 2        | 0.5%    |
| 65      | 1        | 0.25%   |
| 44      | 1        | 0.25%   |
| 37      | 1        | 0.25%   |
| 35      | 1        | 0.25%   |
| 33      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 191      | 50%     |
| 401-500        | 57       | 14.92%  |
| 601-700        | 48       | 12.57%  |
| 701-800        | 36       | 9.42%   |
| 351-400        | 10       | 2.62%   |
| 801-900        | 8        | 2.09%   |
| Unknown        | 8        | 2.09%   |
| 1501-2000      | 7        | 1.83%   |
| 1001-1500      | 7        | 1.83%   |
| 301-350        | 4        | 1.05%   |
| 901-1000       | 4        | 1.05%   |
| More than 2000 | 2        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 264      | 76.3%   |
| 21/9    | 31       | 8.96%   |
| 16/10   | 28       | 8.09%   |
| 5/4     | 12       | 3.47%   |
| Unknown | 4        | 1.16%   |
| 4/3     | 3        | 0.87%   |
| 1.00    | 2        | 0.58%   |
| 32/9    | 1        | 0.29%   |
| 0.89    | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 123      | 31.06%  |
| 301-350        | 90       | 22.73%  |
| 351-500        | 70       | 17.68%  |
| 151-200        | 35       | 8.84%   |
| 251-300        | 34       | 8.59%   |
| More than 1000 | 15       | 3.79%   |
| 501-1000       | 13       | 3.28%   |
| Unknown        | 8        | 2.02%   |
| 141-150        | 6        | 1.52%   |
| 101-110        | 2        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 197      | 54.42%  |
| 101-120 | 95       | 26.24%  |
| 121-160 | 30       | 8.29%   |
| 161-240 | 18       | 4.97%   |
| 1-50    | 14       | 3.87%   |
| Unknown | 8        | 2.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 230      | 66.47%  |
| 2     | 91       | 26.3%   |
| 0     | 13       | 3.76%   |
| 3     | 11       | 3.18%   |
| 4     | 1        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 199      | 39.25%  |
| Intel                         | 186      | 36.69%  |
| MediaTek                      | 20       | 3.94%   |
| Qualcomm Atheros              | 19       | 3.75%   |
| Broadcom                      | 15       | 2.96%   |
| TP-Link                       | 14       | 2.76%   |
| Aquantia                      | 8        | 1.58%   |
| Ralink Technology             | 7        | 1.38%   |
| Ralink                        | 6        | 1.18%   |
| Microsoft                     | 4        | 0.79%   |
| Google                        | 4        | 0.79%   |
| D-Link                        | 4        | 0.79%   |
| Samsung Electronics           | 2        | 0.39%   |
| Nvidia                        | 2        | 0.39%   |
| Xiaomi                        | 1        | 0.2%    |
| Qualcomm                      | 1        | 0.2%    |
| OPPO Electronics              | 1        | 0.2%    |
| OnePlus Technology (Shenzhen) | 1        | 0.2%    |
| NetGear                       | 1        | 0.2%    |
| Motorola PCS                  | 1        | 0.2%    |
| Microchip Technology          | 1        | 0.2%    |
| Mellanox Technologies         | 1        | 0.2%    |
| Marvell Technology Group      | 1        | 0.2%    |
| InterBiometrics               | 1        | 0.2%    |
| ICS Advent                    | 1        | 0.2%    |
| Huawei Technologies           | 1        | 0.2%    |
| Conexant Systems              | 1        | 0.2%    |
| Broadcom Limited              | 1        | 0.2%    |
| Bose                          | 1        | 0.2%    |
| Arduino SA                    | 1        | 0.2%    |
| AboCom Systems                | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 149      | 25.51%  |
| Realtek RTL8125 2.5GbE Controller                                   | 39       | 6.68%   |
| Intel Wi-Fi 6 AX200                                                 | 38       | 6.51%   |
| Intel I211 Gigabit Network Connection                               | 34       | 5.82%   |
| Intel Ethernet Controller I225-V                                    | 29       | 4.97%   |
| Intel Ethernet Connection (2) I219-V                                | 18       | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 15       | 2.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 14       | 2.4%    |
| Intel Ethernet Connection (7) I219-V                                | 10       | 1.71%   |
| Intel Wireless-AC 9260                                              | 9        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 9        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 8        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 7        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 1.03%   |
| Intel 82574L Gigabit Network Connection                             | 6        | 1.03%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 1.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                | 4        | 0.68%   |
| TP-Link 802.11ac NIC                                                | 3        | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                               | 3        | 0.51%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2        | 0.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 0.34%   |
| TP-Link Archer T4U ver.3                                            | 2        | 0.34%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 2        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.34%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 2        | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 0.34%   |
| Realtek 802.11ac NIC                                                | 2        | 0.34%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 2        | 0.34%   |
| Ralink MT7601U Wireless Adapter                                     | 2        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 83       | 45.6%   |
| Realtek Semiconductor | 26       | 14.29%  |
| MediaTek              | 20       | 10.99%  |
| TP-Link               | 13       | 7.14%   |
| Qualcomm Atheros      | 11       | 6.04%   |
| Ralink Technology     | 7        | 3.85%   |
| Ralink                | 6        | 3.3%    |
| Broadcom              | 6        | 3.3%    |
| Microsoft             | 4        | 2.2%    |
| D-Link                | 3        | 1.65%   |
| NetGear               | 1        | 0.55%   |
| Broadcom Limited      | 1        | 0.55%   |
| AboCom Systems        | 1        | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 38       | 20.65%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 14       | 7.61%   |
| Intel Wireless-AC 9260                                        | 9        | 4.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9        | 4.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 8        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 7        | 3.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 6        | 3.26%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 4        | 2.17%   |
| TP-Link 802.11ac NIC                                          | 3        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3        | 1.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2        | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 1.09%   |
| TP-Link Archer T4U ver.3                                      | 2        | 1.09%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 2        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2        | 1.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 2        | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 1.09%   |
| Realtek 802.11ac NIC                                          | 2        | 1.09%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 2        | 1.09%   |
| Ralink MT7601U Wireless Adapter                               | 2        | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2        | 1.09%   |
| Microsoft Wireless XBox Controller Dongle                     | 2        | 1.09%   |
| Intel Wireless 8260                                           | 2        | 1.09%   |
| Intel Wireless 3165                                           | 2        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2        | 1.09%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2        | 1.09%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                         | 1        | 0.54%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1        | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter           | 1        | 0.54%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1        | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 1        | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 190      | 50.13%  |
| Intel                         | 145      | 38.26%  |
| Qualcomm Atheros              | 9        | 2.37%   |
| Broadcom                      | 9        | 2.37%   |
| Aquantia                      | 8        | 2.11%   |
| Google                        | 4        | 1.06%   |
| Samsung Electronics           | 2        | 0.53%   |
| Nvidia                        | 2        | 0.53%   |
| Xiaomi                        | 1        | 0.26%   |
| TP-Link                       | 1        | 0.26%   |
| Qualcomm                      | 1        | 0.26%   |
| OPPO Electronics              | 1        | 0.26%   |
| OnePlus Technology (Shenzhen) | 1        | 0.26%   |
| Motorola PCS                  | 1        | 0.26%   |
| Mellanox Technologies         | 1        | 0.26%   |
| Marvell Technology Group      | 1        | 0.26%   |
| ICS Advent                    | 1        | 0.26%   |
| D-Link                        | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 149      | 37.82%  |
| Realtek RTL8125 2.5GbE Controller                                   | 39       | 9.9%    |
| Intel I211 Gigabit Network Connection                               | 34       | 8.63%   |
| Intel Ethernet Controller I225-V                                    | 29       | 7.36%   |
| Intel Ethernet Connection (2) I219-V                                | 18       | 4.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 15       | 3.81%   |
| Intel Ethernet Connection (7) I219-V                                | 10       | 2.54%   |
| Intel 82574L Gigabit Network Connection                             | 6        | 1.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                                | 4        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.76%   |
| Intel Ethernet Connection (10) I219-V                               | 3        | 0.76%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.51%   |
| Intel Ethernet Connection I217-V                                    | 2        | 0.51%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                               | 2        | 0.51%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                            | 2        | 0.51%   |
| Intel 82575EB Gigabit Network Connection                            | 2        | 0.51%   |
| Google Pixel 6 Pro                                                  | 2        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 2        | 0.51%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 2        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.25%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.25%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 1        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.25%   |
| Qualcomm Android                                                    | 1        | 0.25%   |
| OPPO SDM710-MTP _SN:2396E2D4                                        | 1        | 0.25%   |
| OnePlus (Shenzhen) OnePlus                                          | 1        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 341      | 65.58%  |
| WiFi     | 173      | 33.27%  |
| Modem    | 5        | 0.96%   |
| Unknown  | 1        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 274      | 74.05%  |
| WiFi     | 96       | 25.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 187      | 54.2%   |
| 2     | 125      | 36.23%  |
| 3     | 27       | 7.83%   |
| 4     | 3        | 0.87%   |
| 9     | 1        | 0.29%   |
| 5     | 1        | 0.29%   |
| 0     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 235      | 68.12%  |
| Yes  | 110      | 31.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 80       | 43.96%  |
| Cambridge Silicon Radio         | 38       | 20.88%  |
| TP-Link                         | 13       | 7.14%   |
| Realtek Semiconductor           | 13       | 7.14%   |
| MediaTek                        | 11       | 6.04%   |
| Broadcom                        | 7        | 3.85%   |
| Foxconn / Hon Hai               | 6        | 3.3%    |
| ASUSTek Computer                | 4        | 2.2%    |
| IMC Networks                    | 3        | 1.65%   |
| Qualcomm Atheros Communications | 2        | 1.1%    |
| Belkin Components               | 2        | 1.1%    |
| SIN                             | 1        | 0.55%   |
| HTC (High Tech Computer)        | 1        | 0.55%   |
| Apple                           | 1        | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 38       | 20.65%  |
| Intel AX200 Bluetooth                                                | 36       | 19.57%  |
| TP-Link TPuLink UB500 Adapter                                        | 13       | 7.07%   |
| MediaTek Wireless_Device                                             | 11       | 5.98%   |
| Intel Bluetooth Device                                               | 11       | 5.98%   |
| Realtek Bluetooth Radio                                              | 10       | 5.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9        | 4.89%   |
| Intel AX210 Bluetooth                                                | 9        | 4.89%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 3.8%    |
| Intel Bluetooth wireless interface                                   | 6        | 3.26%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6        | 3.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 2.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 1.63%   |
| IMC Networks Bluetooth Radio                                         | 3        | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.09%   |
| SIN Bluetooth Keyboard                                               | 1        | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1        | 0.54%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.54%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.54%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.54%   |
| Broadcom BCM20702A0 Bluetooth                                        | 1        | 0.54%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.54%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.54%   |
| ASUS Bluetooth Device                                                | 1        | 0.54%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.54%   |
| ASUS ASUS USB-BT500                                                  | 1        | 0.54%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 201      | 29.65%  |
| Intel                                | 171      | 25.22%  |
| Nvidia                               | 149      | 21.98%  |
| C-Media Electronics                  | 21       | 3.1%    |
| Logitech                             | 11       | 1.62%   |
| Creative Labs                        | 9        | 1.33%   |
| Razer USA                            | 8        | 1.18%   |
| Kingston Technology                  | 7        | 1.03%   |
| ASUSTek Computer                     | 7        | 1.03%   |
| SteelSeries ApS                      | 5        | 0.74%   |
| Generalplus Technology               | 5        | 0.74%   |
| Focusrite-Novation                   | 5        | 0.74%   |
| Sony                                 | 4        | 0.59%   |
| VIA Technologies                     | 3        | 0.44%   |
| Texas Instruments                    | 3        | 0.44%   |
| Samson Technologies                  | 3        | 0.44%   |
| RODE Microphones                     | 3        | 0.44%   |
| Micro Star International             | 3        | 0.44%   |
| JMTek                                | 3        | 0.44%   |
| GN Netcom                            | 3        | 0.44%   |
| Giga-Byte Technology                 | 3        | 0.44%   |
| Corsair                              | 3        | 0.44%   |
| XMOS                                 | 2        | 0.29%   |
| Trust                                | 2        | 0.29%   |
| Realtek Semiconductor                | 2        | 0.29%   |
| Plantronics                          | 2        | 0.29%   |
| Medeli Electronics                   | 2        | 0.29%   |
| LG Electronics                       | 2        | 0.29%   |
| FiiO Electronics Technology          | 2        | 0.29%   |
| Dell                                 | 2        | 0.29%   |
| Creative Technology                  | 2        | 0.29%   |
| Antlion Audio                        | 2        | 0.29%   |
| ZOOM                                 | 1        | 0.15%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.15%   |
| Tenx Technology                      | 1        | 0.15%   |
| Studiologic                          | 1        | 0.15%   |
| Shure                                | 1        | 0.15%   |
| Schiit Audio                         | 1        | 0.15%   |
| Samsung Electronics                  | 1        | 0.15%   |
| RME                                  | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 80       | 9.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 44       | 5.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 41       | 5.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33       | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21       | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21       | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 2.45%   |
| Intel Alder Lake-S HD Audio Controller                                     | 19       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 17       | 2.09%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 17       | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 1.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 1.6%    |
| AMD Navi 10 HDMI Audio                                                     | 13       | 1.6%    |
| Nvidia TU104 HD Audio Controller                                           | 12       | 1.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 12       | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 1.23%   |
| Nvidia GM206 High Definition Audio Controller                              | 10       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 8        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 8        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 0.86%   |
| AMD FCH Azalia Controller                                                  | 7        | 0.86%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 0.74%   |
| Intel Audio device                                                         | 6        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 5        | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.61%   |
| Generalplus Technology USB Audio Device                                    | 5        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 40       | 23.12%  |
| G.Skill             | 29       | 16.76%  |
| Corsair             | 25       | 14.45%  |
| Unknown             | 12       | 6.94%   |
| Crucial             | 11       | 6.36%   |
| Samsung Electronics | 10       | 5.78%   |
| SK hynix            | 6        | 3.47%   |
| A-DATA Technology   | 6        | 3.47%   |
| Micron Technology   | 5        | 2.89%   |
| Team                | 4        | 2.31%   |
| Unknown             | 4        | 2.31%   |
| Ramaxel Technology  | 3        | 1.73%   |
| Unifosa             | 2        | 1.16%   |
| Smart               | 2        | 1.16%   |
| Patriot             | 2        | 1.16%   |
| Nanya Technology    | 2        | 1.16%   |
| Gold Key            | 2        | 1.16%   |
| Apacer              | 2        | 1.16%   |
| Silicon Power       | 1        | 0.58%   |
| Qimonda             | 1        | 0.58%   |
| GOODRAM             | 1        | 0.58%   |
| Elpida              | 1        | 0.58%   |
| Avant               | 1        | 0.58%   |
| AMD                 | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 4        | 2.16%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 4        | 2.16%   |
| Unknown                                                     | 4        | 2.16%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 3        | 1.62%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 3        | 1.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s       | 3        | 1.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 1.08%   |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 2        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 1.08%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s          | 2        | 1.08%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s         | 2        | 1.08%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s         | 2        | 1.08%   |
| Kingston RAM KF560C40-16 16GB DIMM DDR5 4800MT/s            | 2        | 1.08%   |
| Kingston RAM KF552C40-32 32GB DIMM DDR5 5200MT/s            | 2        | 1.08%   |
| Kingston RAM KF552C40-16 16GB DIMM 5200MT/s                 | 2        | 1.08%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.08%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s      | 2        | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                    | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 800MT/s                         | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 667MT/s                         | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1        | 0.54%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.54%   |
| Unifosa RAM GU332G0ALEPR8H2C6F 2GB SODIMM DDR2 800MT/s      | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD3-1333 4GB DIMM DDR3 1333MT/s          | 1        | 0.54%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.54%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s         | 1        | 0.54%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                  | 1        | 0.54%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1        | 0.54%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.54%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.54%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.54%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s        | 1        | 0.54%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s     | 1        | 0.54%   |
| Silicon Power RAM Module 8GB DIMM DDR4 3200MT/s             | 1        | 0.54%   |
| Samsung RAM M395T5750GZ4-CE66 2GB FB-DIMM DDR2 667MT/s      | 1        | 0.54%   |
| Samsung RAM M395T5160QZ4-CE65 4GB FB-DIMM DDR2 667MT/s      | 1        | 0.54%   |
| Samsung RAM M395T5160DZ4-CE66 4GB FB-DIMM DDR2 667MT/s      | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 80       | 52.63%  |
| DDR3    | 40       | 26.32%  |
| DDR5    | 19       | 12.5%   |
| DDR2    | 7        | 4.61%   |
| Unknown | 4        | 2.63%   |
| SDRAM   | 2        | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 146      | 97.33%  |
| SODIMM  | 2        | 1.33%   |
| FB-DIMM | 2        | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 60       | 38.46%  |
| 16384 | 36       | 23.08%  |
| 4096  | 31       | 19.87%  |
| 32768 | 14       | 8.97%   |
| 2048  | 12       | 7.69%   |
| 1024  | 3        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 21       | 12.65%  |
| 3600  | 20       | 12.05%  |
| 3200  | 17       | 10.24%  |
| 1333  | 12       | 7.23%   |
| 4800  | 10       | 6.02%   |
| 2400  | 10       | 6.02%   |
| 3466  | 9        | 5.42%   |
| 2133  | 6        | 3.61%   |
| 2667  | 5        | 3.01%   |
| 800   | 5        | 3.01%   |
| 5200  | 4        | 2.41%   |
| 3866  | 4        | 2.41%   |
| 1800  | 4        | 2.41%   |
| 667   | 4        | 2.41%   |
| 5600  | 3        | 1.81%   |
| 3000  | 3        | 1.81%   |
| 2666  | 3        | 1.81%   |
| 1866  | 3        | 1.81%   |
| 3733  | 2        | 1.2%    |
| 3400  | 2        | 1.2%    |
| 3333  | 2        | 1.2%    |
| 533   | 2        | 1.2%    |
| 400   | 2        | 1.2%    |
| 6400  | 1        | 0.6%    |
| 5808  | 1        | 0.6%    |
| 4133  | 1        | 0.6%    |
| 3800  | 1        | 0.6%    |
| 3666  | 1        | 0.6%    |
| 3266  | 1        | 0.6%    |
| 3100  | 1        | 0.6%    |
| 2800  | 1        | 0.6%    |
| 2200  | 1        | 0.6%    |
| 2132  | 1        | 0.6%    |
| 1867  | 1        | 0.6%    |
| 1334  | 1        | 0.6%    |
| 1066  | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 4        | 28.57%  |
| Brother Industries    | 4        | 28.57%  |
| Seiko Epson           | 2        | 14.29%  |
| Samsung Electronics   | 1        | 7.14%   |
| Prolific Technology   | 1        | 7.14%   |
| Lexmark International | 1        | 7.14%   |
| Canon                 | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson Printer           | 1        | 7.14%   |
| Seiko Epson L300 Series       | 1        | 7.14%   |
| Samsung ML-2855 Series        | 1        | 7.14%   |
| Prolific PL2305 Parallel Port | 1        | 7.14%   |
| Lexmark International B2236dw | 1        | 7.14%   |
| HP LaserJet 1010              | 1        | 7.14%   |
| HP ENVY Photo 7800 series     | 1        | 7.14%   |
| HP DeskJet F300 series        | 1        | 7.14%   |
| HP DeskJet 3630 series        | 1        | 7.14%   |
| Canon LiDE 400                | 1        | 7.14%   |
| Brother MFC-7460DN            | 1        | 7.14%   |
| Brother HL-L2350DW series     | 1        | 7.14%   |
| Brother HL-L2300D series      | 1        | 7.14%   |
| Brother DCP-L2510D series     | 1        | 7.14%   |

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


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 38       | 42.22%  |
| Microdia                      | 7        | 7.78%   |
| Microsoft                     | 6        | 6.67%   |
| Samsung Electronics           | 5        | 5.56%   |
| Apple                         | 5        | 5.56%   |
| KYE Systems (Mouse Systems)   | 4        | 4.44%   |
| LG Electronics                | 3        | 3.33%   |
| Trust                         | 2        | 2.22%   |
| Chicony Electronics           | 2        | 2.22%   |
| WCM_USB                       | 1        | 1.11%   |
| SunplusIT                     | 1        | 1.11%   |
| Sunplus Innovation Technology | 1        | 1.11%   |
| Sonix Technology              | 1        | 1.11%   |
| SN0002                        | 1        | 1.11%   |
| Smartronix                    | 1        | 1.11%   |
| Realtek Semiconductor         | 1        | 1.11%   |
| Nikon                         | 1        | 1.11%   |
| MacroSilicon                  | 1        | 1.11%   |
| Integrated Technology Express | 1        | 1.11%   |
| Hewlett-Packard               | 1        | 1.11%   |
| Cubeternet                    | 1        | 1.11%   |
| ASUSTek Computer              | 1        | 1.11%   |
| Arkmicro Technologies         | 1        | 1.11%   |
| ARC International             | 1        | 1.11%   |
| Anker PowerConf C200          | 1        | 1.11%   |
| A4Tech                        | 1        | 1.11%   |
| 2M UVC CAMERA                 | 1        | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 8        | 8.89%   |
| Logitech Webcam C270                  | 6        | 6.67%   |
| Samsung Galaxy A5 (MTP)               | 5        | 5.56%   |
| Logitech HD Webcam C525               | 5        | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE             | 5        | 5.56%   |
| Microdia Webcam Vitade AF             | 4        | 4.44%   |
| Logitech C922 Pro Stream Webcam       | 3        | 3.33%   |
| Logitech C920 PRO HD Webcam           | 3        | 3.33%   |
| Microdia USB 2.0 Camera               | 2        | 2.22%   |
| Logitech Webcam C930e                 | 2        | 2.22%   |
| Logitech Webcam C925e                 | 2        | 2.22%   |
| Logitech Logi Webcam C920e            | 2        | 2.22%   |
| LG LG UltraFine Display Camera        | 2        | 2.22%   |
| WCM_USB WEB CAM                       | 1        | 1.11%   |
| Trust WB-6250X Webcam                 | 1        | 1.11%   |
| Trust FHD Webcam                      | 1        | 1.11%   |
| SunplusIT USB 2.0 Camera              | 1        | 1.11%   |
| Sunplus FHD Camera Microphone         | 1        | 1.11%   |
| Sonix USB Camera                      | 1        | 1.11%   |
| SN0002 1080P Web Camera               | 1        | 1.11%   |
| Smartronix webcam                     | 1        | 1.11%   |
| Realtek NexiGo N660P FHD Webcam       | 1        | 1.11%   |
| Nikon DSC D3200                       | 1        | 1.11%   |
| Microsoft Xbox NUI Camera             | 1        | 1.11%   |
| Microsoft MicrosoftÂ LifeCam Cinema  | 1        | 1.11%   |
| Microsoft LifeCam VX-5000             | 1        | 1.11%   |
| Microsoft LifeCam VX-2000             | 1        | 1.11%   |
| Microsoft LifeCam Studio              | 1        | 1.11%   |
| Microsoft LifeCam Cinema              | 1        | 1.11%   |
| Microdia JOYACCESS JA-Webcam          | 1        | 1.11%   |
| MacroSilicon USB Video                | 1        | 1.11%   |
| Logitech Webcam C250                  | 1        | 1.11%   |
| Logitech Webcam C110                  | 1        | 1.11%   |
| Logitech HD Webcam C615               | 1        | 1.11%   |
| Logitech HD Webcam C510               | 1        | 1.11%   |
| Logitech C930c                        | 1        | 1.11%   |
| Logitech BRIO Ultra HD Webcam         | 1        | 1.11%   |
| Logitech Brio 500                     | 1        | 1.11%   |
| LG Optimus (Various Models) MTP Mode  | 1        | 1.11%   |
| KYE Systems (Mouse Systems) iSlim 320 | 1        | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Microsoft             | 1        | 25%     |
| LighTuning Technology | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microsoft Fingerprint Reader                | 1        | 25%     |
| LighTuning Fingerprint Sensor               | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 25%     |
| AuthenTec AES1600                           | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 290      | 83.57%  |
| 1     | 46       | 13.26%  |
| 4     | 4        | 1.15%   |
| 3     | 3        | 0.86%   |
| 2     | 2        | 0.58%   |
| 8     | 1        | 0.29%   |
| 5     | 1        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 26.39%  |
| Net/wireless             | 15       | 20.83%  |
| Sound                    | 10       | 13.89%  |
| Camera                   | 6        | 8.33%   |
| Multimedia controller    | 5        | 6.94%   |
| Fingerprint reader       | 4        | 5.56%   |
| Storage/raid             | 3        | 4.17%   |
| Communication controller | 3        | 4.17%   |
| Network                  | 2        | 2.78%   |
| Net/ethernet             | 2        | 2.78%   |
| Unassigned class         | 1        | 1.39%   |
| Modem                    | 1        | 1.39%   |
| Bluetooth                | 1        | 1.39%   |

