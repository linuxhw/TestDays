Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 5548

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | P67A-GD65                   | [1024e95ca9](https://linux-hardware.org/?probe=1024e95ca9) | Aug 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [ae7ae594f1](https://linux-hardware.org/?probe=ae7ae594f1) | Aug 12, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [7298d533c9](https://linux-hardware.org/?probe=7298d533c9) | Aug 12, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [13e0e622f3](https://linux-hardware.org/?probe=13e0e622f3) | Aug 12, 2023 |
| HP            | 0A04h                       | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| Fujitsu       | JIQ87Y                      | [b11d99014e](https://linux-hardware.org/?probe=b11d99014e) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | [af419fe003](https://linux-hardware.org/?probe=af419fe003) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | [16cd37e4fe](https://linux-hardware.org/?probe=16cd37e4fe) | Aug 12, 2023 |
| Dell          | 0Y2MRG A00                  | [04ce264a3e](https://linux-hardware.org/?probe=04ce264a3e) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [28bc891b6d](https://linux-hardware.org/?probe=28bc891b6d) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [3050db3fbf](https://linux-hardware.org/?probe=3050db3fbf) | Aug 12, 2023 |
| MSI           | Boston                      | [62ad275a7d](https://linux-hardware.org/?probe=62ad275a7d) | Aug 11, 2023 |
| MSI           | Boston                      | [a34a89c083](https://linux-hardware.org/?probe=a34a89c083) | Aug 11, 2023 |
| Intel         | B75                         | [17641de345](https://linux-hardware.org/?probe=17641de345) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Unknown       | Unknown                     | [62ef56dbab](https://linux-hardware.org/?probe=62ef56dbab) | Aug 11, 2023 |
| ASRock        | B450M Pro4                  | [65d55091fa](https://linux-hardware.org/?probe=65d55091fa) | Aug 11, 2023 |
| Intel         | D915GEV AAC63667-501        | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| Gigabyte      | B85M-D2V                    | [d8d7d7bad7](https://linux-hardware.org/?probe=d8d7d7bad7) | Aug 11, 2023 |
| ASRock        | B550M-ITX/ac                | [e6624cc619](https://linux-hardware.org/?probe=e6624cc619) | Aug 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [7d31344218](https://linux-hardware.org/?probe=7d31344218) | Aug 11, 2023 |
| Dell          | 0HY9JP A01                  | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| Acer          | Aspire G7713                | [cb79bdce06](https://linux-hardware.org/?probe=cb79bdce06) | Aug 11, 2023 |
| Gigabyte      | Z77-D3H                     | [e71fc09944](https://linux-hardware.org/?probe=e71fc09944) | Aug 11, 2023 |
| ASUSTek       | PRIME H510M-K               | [3c239efc46](https://linux-hardware.org/?probe=3c239efc46) | Aug 11, 2023 |
| AZW           | Green G4 10                 | [a574280172](https://linux-hardware.org/?probe=a574280172) | Aug 11, 2023 |
| MSI           | MS-7380                     | [584074ca03](https://linux-hardware.org/?probe=584074ca03) | Aug 11, 2023 |
| Alienware     | Area-51 R2                  | [07a6f57292](https://linux-hardware.org/?probe=07a6f57292) | Aug 11, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6a1d87f2aa](https://linux-hardware.org/?probe=6a1d87f2aa) | Aug 10, 2023 |
| ASUSTek       | P8P67 PRO                   | [c0d6900ba3](https://linux-hardware.org/?probe=c0d6900ba3) | Aug 10, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | [1c32da7aed](https://linux-hardware.org/?probe=1c32da7aed) | Aug 10, 2023 |
| Lenovo        | ThinkStation S30 056848U    | [e6bc23d815](https://linux-hardware.org/?probe=e6bc23d815) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [6bf6a38fba](https://linux-hardware.org/?probe=6bf6a38fba) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Dell          | 04YP6J A02                  | [5d5ce952b3](https://linux-hardware.org/?probe=5d5ce952b3) | Aug 10, 2023 |
| Gigabyte      | B560M DS3H                  | [96d3419a5f](https://linux-hardware.org/?probe=96d3419a5f) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [5264c46571](https://linux-hardware.org/?probe=5264c46571) | Aug 10, 2023 |
| YANYU         | EPIC-C57                    | [6d42c0f9af](https://linux-hardware.org/?probe=6d42c0f9af) | Aug 10, 2023 |
| MSI           | A320M PRO-VD/S              | [7f7c988470](https://linux-hardware.org/?probe=7f7c988470) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [307c7bbe9c](https://linux-hardware.org/?probe=307c7bbe9c) | Aug 10, 2023 |
| Dell          | 0JP3NX A01                  | [a9c4812d66](https://linux-hardware.org/?probe=a9c4812d66) | Aug 09, 2023 |
| ASUSTek       | PRIME Z270-A                | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| MSI           | 970 GAMING                  | [a499728742](https://linux-hardware.org/?probe=a499728742) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| ASRock        | H77M-ITX                    | [01dc3bfc4b](https://linux-hardware.org/?probe=01dc3bfc4b) | Aug 09, 2023 |
| HP            | 894D                        | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| MSI           | A78M-E45                    | [d39f224497](https://linux-hardware.org/?probe=d39f224497) | Aug 09, 2023 |
| MSI           | 970 GAMING                  | [4751920c96](https://linux-hardware.org/?probe=4751920c96) | Aug 09, 2023 |
| Lenovo        | 30C1                        | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Dell          | 02YYK5 A00                  | [14382141e9](https://linux-hardware.org/?probe=14382141e9) | Aug 09, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [64fbeeca5e](https://linux-hardware.org/?probe=64fbeeca5e) | Aug 08, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [c48e0220d8](https://linux-hardware.org/?probe=c48e0220d8) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [fa0fbda262](https://linux-hardware.org/?probe=fa0fbda262) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f75916b7c7](https://linux-hardware.org/?probe=f75916b7c7) | Aug 08, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [6ffda81a5e](https://linux-hardware.org/?probe=6ffda81a5e) | Aug 08, 2023 |
| HP            | 2129                        | [f005bdb494](https://linux-hardware.org/?probe=f005bdb494) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2335e10b59](https://linux-hardware.org/?probe=2335e10b59) | Aug 08, 2023 |
| Pegatron      | 2AB5                        | [9579022e6f](https://linux-hardware.org/?probe=9579022e6f) | Aug 07, 2023 |
| ASRock        | H610M-ITX/ac                | [205fab2707](https://linux-hardware.org/?probe=205fab2707) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [40b0ea74b1](https://linux-hardware.org/?probe=40b0ea74b1) | Aug 07, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [873825c261](https://linux-hardware.org/?probe=873825c261) | Aug 07, 2023 |
| HP            | 8055                        | [5124119ce1](https://linux-hardware.org/?probe=5124119ce1) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [002014034b](https://linux-hardware.org/?probe=002014034b) | Aug 07, 2023 |
| ASUSTek       | P5N-E SLI                   | [d552e347f5](https://linux-hardware.org/?probe=d552e347f5) | Aug 07, 2023 |
| AZW           | SEi                         | [b38e4eec2e](https://linux-hardware.org/?probe=b38e4eec2e) | Aug 07, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [fbfc0c60bd](https://linux-hardware.org/?probe=fbfc0c60bd) | Aug 07, 2023 |
| MSI           | Z97 GAMING 5                | [d076b394d9](https://linux-hardware.org/?probe=d076b394d9) | Aug 06, 2023 |
| Dell          | 0WMJ54 A01                  | [7f6aa0ed0c](https://linux-hardware.org/?probe=7f6aa0ed0c) | Aug 06, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [80c705f1a7](https://linux-hardware.org/?probe=80c705f1a7) | Aug 06, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [28ee020bed](https://linux-hardware.org/?probe=28ee020bed) | Aug 06, 2023 |
| HP            | 805D                        | [672e431e69](https://linux-hardware.org/?probe=672e431e69) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| Lenovo        | 110536U ThinkServer TS13... | [5084897812](https://linux-hardware.org/?probe=5084897812) | Aug 05, 2023 |
| HP            | 1791                        | [4a89aab3d6](https://linux-hardware.org/?probe=4a89aab3d6) | Aug 05, 2023 |
| HP            | 198E                        | [34023c0d62](https://linux-hardware.org/?probe=34023c0d62) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [8cc106746a](https://linux-hardware.org/?probe=8cc106746a) | Aug 05, 2023 |
| MSI           | A78M-E45                    | [988c1f5878](https://linux-hardware.org/?probe=988c1f5878) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [4f2449c578](https://linux-hardware.org/?probe=4f2449c578) | Aug 05, 2023 |
| Gigabyte      | G31M-S2C                    | [9cda5ca576](https://linux-hardware.org/?probe=9cda5ca576) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [f5ebaad3b1](https://linux-hardware.org/?probe=f5ebaad3b1) | Aug 05, 2023 |
| Gigabyte      | H110M-H-CF                  | [17ea53b0c6](https://linux-hardware.org/?probe=17ea53b0c6) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [af4ef366cf](https://linux-hardware.org/?probe=af4ef366cf) | Aug 04, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| MSI           | MS-7380                     | [98aa00b9e1](https://linux-hardware.org/?probe=98aa00b9e1) | Aug 03, 2023 |
| Medion        | MS-7616                     | [7b9dae91ad](https://linux-hardware.org/?probe=7b9dae91ad) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | [79d26043a0](https://linux-hardware.org/?probe=79d26043a0) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [beddea6e34](https://linux-hardware.org/?probe=beddea6e34) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [92bf3762f2](https://linux-hardware.org/?probe=92bf3762f2) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [37ebe498c2](https://linux-hardware.org/?probe=37ebe498c2) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [53edc778db](https://linux-hardware.org/?probe=53edc778db) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [dc1c75a471](https://linux-hardware.org/?probe=dc1c75a471) | Aug 03, 2023 |
| MSI           | PRO Z790-P WIFI             | [8f3eaca764](https://linux-hardware.org/?probe=8f3eaca764) | Aug 03, 2023 |
| Dell          | 0GTK4K A10                  | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| HP            | 843E                        | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [6b22568f3f](https://linux-hardware.org/?probe=6b22568f3f) | Aug 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dcbf7b10c](https://linux-hardware.org/?probe=9dcbf7b10c) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B760-A GAMING ... | [f629b6e16e](https://linux-hardware.org/?probe=f629b6e16e) | Aug 03, 2023 |
| Win elemen... | M600                        | [b9537c621c](https://linux-hardware.org/?probe=b9537c621c) | Aug 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0e28c2aae2](https://linux-hardware.org/?probe=0e28c2aae2) | Aug 02, 2023 |
| Intel         | DH67BL AAG10189-211         | [db043e1572](https://linux-hardware.org/?probe=db043e1572) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| Supermicro    | X9DAi                       | [d7390704d8](https://linux-hardware.org/?probe=d7390704d8) | Aug 02, 2023 |
| Dell          | 0FR6WH A01                  | [38feb4d1f7](https://linux-hardware.org/?probe=38feb4d1f7) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [69cd0aae71](https://linux-hardware.org/?probe=69cd0aae71) | Aug 02, 2023 |
| Dell          | 0GRJJ9 A01                  | [dca7ee3fdc](https://linux-hardware.org/?probe=dca7ee3fdc) | Aug 02, 2023 |
| Pegatron      | Benicia                     | [5db4c563c6](https://linux-hardware.org/?probe=5db4c563c6) | Aug 01, 2023 |
| MSI           | MS-7380                     | [6f3e83e5a2](https://linux-hardware.org/?probe=6f3e83e5a2) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [9b314ec48b](https://linux-hardware.org/?probe=9b314ec48b) | Aug 01, 2023 |
| Gigabyte      | P35-DS4                     | [9116e4042c](https://linux-hardware.org/?probe=9116e4042c) | Aug 01, 2023 |
| HP            | 18E4                        | [20ebffd9a8](https://linux-hardware.org/?probe=20ebffd9a8) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| HP            | 2B2C                        | [3f0b3f8811](https://linux-hardware.org/?probe=3f0b3f8811) | Aug 01, 2023 |
| Dell          | 06NWYK A00                  | [1c3a3db0ec](https://linux-hardware.org/?probe=1c3a3db0ec) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [668eb36a4a](https://linux-hardware.org/?probe=668eb36a4a) | Aug 01, 2023 |
| Dell          | 09KPNV A01                  | [1768a6834a](https://linux-hardware.org/?probe=1768a6834a) | Aug 01, 2023 |
| Dell          | OptiPlex 980                | [7ec85c3865](https://linux-hardware.org/?probe=7ec85c3865) | Aug 01, 2023 |
| HP            | 3048h                       | [02df08e8ab](https://linux-hardware.org/?probe=02df08e8ab) | Jul 31, 2023 |
| HP            | 3398                        | [c271d5d40e](https://linux-hardware.org/?probe=c271d5d40e) | Jul 31, 2023 |
| Gigabyte      | B85M-D3H                    | [9ddb5c2ea3](https://linux-hardware.org/?probe=9ddb5c2ea3) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4e4e6cd3eb](https://linux-hardware.org/?probe=4e4e6cd3eb) | Jul 31, 2023 |
| Dell          | 08NPPY A00                  | [26acefc1b8](https://linux-hardware.org/?probe=26acefc1b8) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [aead9f82b2](https://linux-hardware.org/?probe=aead9f82b2) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [9e8f131101](https://linux-hardware.org/?probe=9e8f131101) | Jul 31, 2023 |
| HP            | 212A                        | [4f81f09718](https://linux-hardware.org/?probe=4f81f09718) | Jul 30, 2023 |
| HP            | 3398                        | [444f9d27d5](https://linux-hardware.org/?probe=444f9d27d5) | Jul 30, 2023 |
| Intel         | DH67BL AAG10189-211         | [33ac97b0c6](https://linux-hardware.org/?probe=33ac97b0c6) | Jul 30, 2023 |
| Gigabyte      | X58A-UD7                    | [98759e7a12](https://linux-hardware.org/?probe=98759e7a12) | Jul 30, 2023 |
| Acer          | Aspire G7713                | [e0624d410e](https://linux-hardware.org/?probe=e0624d410e) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [de6e904009](https://linux-hardware.org/?probe=de6e904009) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [6928788f05](https://linux-hardware.org/?probe=6928788f05) | Jul 30, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [4ff0e84129](https://linux-hardware.org/?probe=4ff0e84129) | Jul 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe48f2b4d4](https://linux-hardware.org/?probe=fe48f2b4d4) | Jul 30, 2023 |
| ASUSTek       | PRIME Z270-A                | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| Dell          | 0RF705                      | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d788283742](https://linux-hardware.org/?probe=d788283742) | Jul 30, 2023 |
| Lenovo        | 0C48431 WIN                 | [4e0d5538b2](https://linux-hardware.org/?probe=4e0d5538b2) | Jul 30, 2023 |
| Gigabyte      | B460M DS3H V2               | [42b35cd473](https://linux-hardware.org/?probe=42b35cd473) | Jul 30, 2023 |
| Dell          | 0RF705                      | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [a4d7919584](https://linux-hardware.org/?probe=a4d7919584) | Jul 29, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| Intel         | D33217GKE G76540-203        | [d551e6904d](https://linux-hardware.org/?probe=d551e6904d) | Jul 29, 2023 |
| Medion        | H110H4-EM                   | [7c2b005f92](https://linux-hardware.org/?probe=7c2b005f92) | Jul 29, 2023 |
| Lenovo        | SHARKBAY NOK                | [6e89d2949a](https://linux-hardware.org/?probe=6e89d2949a) | Jul 29, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | [bee5e6175b](https://linux-hardware.org/?probe=bee5e6175b) | Jul 29, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a69e475106](https://linux-hardware.org/?probe=a69e475106) | Jul 29, 2023 |
| HP            | 2B1B                        | [8454c98fbb](https://linux-hardware.org/?probe=8454c98fbb) | Jul 29, 2023 |
| Gigabyte      | X570S AERO G                | [d500093891](https://linux-hardware.org/?probe=d500093891) | Jul 28, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [099c883745](https://linux-hardware.org/?probe=099c883745) | Jul 28, 2023 |
| Lenovo        | NO DPK                      | [15d3803dcc](https://linux-hardware.org/?probe=15d3803dcc) | Jul 28, 2023 |
| ASRock        | H81 Pro BTC R2.0            | [b322ef8e74](https://linux-hardware.org/?probe=b322ef8e74) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [d4774401e3](https://linux-hardware.org/?probe=d4774401e3) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [45c79840cc](https://linux-hardware.org/?probe=45c79840cc) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [735d4f8f84](https://linux-hardware.org/?probe=735d4f8f84) | Jul 28, 2023 |
| Dell          | 0FR6WH A01                  | [d20434fd50](https://linux-hardware.org/?probe=d20434fd50) | Jul 28, 2023 |
| HP            | 2B0B 100                    | [586d94bacc](https://linux-hardware.org/?probe=586d94bacc) | Jul 28, 2023 |
| HP            | 2B0B 100                    | [da33776470](https://linux-hardware.org/?probe=da33776470) | Jul 28, 2023 |
| HP            | 0A04h                       | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f689c31a17](https://linux-hardware.org/?probe=f689c31a17) | Jul 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [ccfe4b2234](https://linux-hardware.org/?probe=ccfe4b2234) | Jul 27, 2023 |
| ASRock        | X670E Pro RS                | [27a13f80b2](https://linux-hardware.org/?probe=27a13f80b2) | Jul 27, 2023 |
| Medion        | MS-7616                     | [349360bcba](https://linux-hardware.org/?probe=349360bcba) | Jul 27, 2023 |
| MSI           | MS-B1831                    | [35f0e625f1](https://linux-hardware.org/?probe=35f0e625f1) | Jul 27, 2023 |
| Pegatron      | 2A99                        | [068f8c77fd](https://linux-hardware.org/?probe=068f8c77fd) | Jul 27, 2023 |
| Medion        | H110H4-EM                   | [080a30ad72](https://linux-hardware.org/?probe=080a30ad72) | Jul 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [0a84eeb8e2](https://linux-hardware.org/?probe=0a84eeb8e2) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [d54ad601d0](https://linux-hardware.org/?probe=d54ad601d0) | Jul 26, 2023 |
| Alienware     | 04VWF2 A02                  | [e6c2096ce5](https://linux-hardware.org/?probe=e6c2096ce5) | Jul 26, 2023 |
| Intel         | D33217GKE G76540-203        | [b4089ed499](https://linux-hardware.org/?probe=b4089ed499) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [e359107d20](https://linux-hardware.org/?probe=e359107d20) | Jul 26, 2023 |
| Gigabyte      | Z490 UD                     | [29aa67256f](https://linux-hardware.org/?probe=29aa67256f) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [01309bf370](https://linux-hardware.org/?probe=01309bf370) | Jul 26, 2023 |
| AZW           | SEi                         | [115142c288](https://linux-hardware.org/?probe=115142c288) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [88dd1326f2](https://linux-hardware.org/?probe=88dd1326f2) | Jul 26, 2023 |
| HP            | 8169                        | [f2885ba2de](https://linux-hardware.org/?probe=f2885ba2de) | Jul 26, 2023 |
| Intel         | X79                         | [46434d0a2c](https://linux-hardware.org/?probe=46434d0a2c) | Jul 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [ded7cda68f](https://linux-hardware.org/?probe=ded7cda68f) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [94a5fdec96](https://linux-hardware.org/?probe=94a5fdec96) | Jul 26, 2023 |
| ASUSTek       | Rampage II GENE             | [c3df12e6ea](https://linux-hardware.org/?probe=c3df12e6ea) | Jul 25, 2023 |
| MSI           | A68HM-E33 V2                | [858b41037e](https://linux-hardware.org/?probe=858b41037e) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [5e77384bb8](https://linux-hardware.org/?probe=5e77384bb8) | Jul 25, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [a08da8df65](https://linux-hardware.org/?probe=a08da8df65) | Jul 25, 2023 |
| Intel         | X79                         | [520788cdc8](https://linux-hardware.org/?probe=520788cdc8) | Jul 25, 2023 |
| Intel         | DQ965GF AAD41676-601        | [384577dee3](https://linux-hardware.org/?probe=384577dee3) | Jul 25, 2023 |
| Dell          | 0M5DCD A00                  | [f03fba3891](https://linux-hardware.org/?probe=f03fba3891) | Jul 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [b5380c8836](https://linux-hardware.org/?probe=b5380c8836) | Jul 25, 2023 |
| ASRock        | B450M Pro4                  | [ab5995e72d](https://linux-hardware.org/?probe=ab5995e72d) | Jul 25, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [9b3ed16747](https://linux-hardware.org/?probe=9b3ed16747) | Jul 25, 2023 |
| ASUSTek       | UN45                        | [ea2bebc887](https://linux-hardware.org/?probe=ea2bebc887) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| Dell          | 0U880P A01                  | [91d0931125](https://linux-hardware.org/?probe=91d0931125) | Jul 24, 2023 |
| Pegatron      | Benicia                     | [ad8b67f72e](https://linux-hardware.org/?probe=ad8b67f72e) | Jul 24, 2023 |
| ASRock        | Z690 Phantom Gaming 4       | [0a334297a5](https://linux-hardware.org/?probe=0a334297a5) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ce1c4f4026](https://linux-hardware.org/?probe=ce1c4f4026) | Jul 24, 2023 |
| Dell          | 088DT1 A01                  | [f796a78d27](https://linux-hardware.org/?probe=f796a78d27) | Jul 24, 2023 |
| Dell          | 088DT1 A01                  | [e130e8c0f2](https://linux-hardware.org/?probe=e130e8c0f2) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| Intel         | X79                         | [c0c619638e](https://linux-hardware.org/?probe=c0c619638e) | Jul 24, 2023 |
| Lenovo        | MAHOBAY NOK                 | [e391e5bca6](https://linux-hardware.org/?probe=e391e5bca6) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [955c69d2b2](https://linux-hardware.org/?probe=955c69d2b2) | Jul 24, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [96e8002856](https://linux-hardware.org/?probe=96e8002856) | Jul 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [f6c6668305](https://linux-hardware.org/?probe=f6c6668305) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [4c4109b8f3](https://linux-hardware.org/?probe=4c4109b8f3) | Jul 23, 2023 |
| Gigabyte      | Z370P D3-CF                 | [5b4c2db6cf](https://linux-hardware.org/?probe=5b4c2db6cf) | Jul 23, 2023 |
| HP            | 81BB                        | [75973dea3f](https://linux-hardware.org/?probe=75973dea3f) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [d89bdeec87](https://linux-hardware.org/?probe=d89bdeec87) | Jul 23, 2023 |
| Gigabyte      | X570S AERO G                | [8e3dbf7ff9](https://linux-hardware.org/?probe=8e3dbf7ff9) | Jul 23, 2023 |
| ASRock        | 960GM-GS3 FX                | [3ddda4afa3](https://linux-hardware.org/?probe=3ddda4afa3) | Jul 23, 2023 |
| ASRock        | 4X4-4000 Series             | [d95040e760](https://linux-hardware.org/?probe=d95040e760) | Jul 23, 2023 |
| CWWK          | CW-AD4L-N V1                | [8d9ea8214d](https://linux-hardware.org/?probe=8d9ea8214d) | Jul 23, 2023 |
| Dell          | 02YYK5 A01                  | [13da37735a](https://linux-hardware.org/?probe=13da37735a) | Jul 23, 2023 |
| BESSTAR Te... | JB9                         | [ea014bad4f](https://linux-hardware.org/?probe=ea014bad4f) | Jul 22, 2023 |
| MSI           | MEG Z490I UNIFY             | [9a414330bf](https://linux-hardware.org/?probe=9a414330bf) | Jul 22, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [9f52ae219f](https://linux-hardware.org/?probe=9f52ae219f) | Jul 22, 2023 |
| Shenzhen M... | F7BFC                       | [a9639fb963](https://linux-hardware.org/?probe=a9639fb963) | Jul 22, 2023 |
| ASUSTek       | SABERTOOTH X58              | [8841163f3b](https://linux-hardware.org/?probe=8841163f3b) | Jul 22, 2023 |
| ASRock        | J3355B-ITX                  | [3edbf4710e](https://linux-hardware.org/?probe=3edbf4710e) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [50641feb57](https://linux-hardware.org/?probe=50641feb57) | Jul 22, 2023 |
| Intel         | DH61WW AAG23116-206         | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | 2B0B 100                    | [42df5ab3e8](https://linux-hardware.org/?probe=42df5ab3e8) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Dell          | 00010C A00                  | [40543af7a5](https://linux-hardware.org/?probe=40543af7a5) | Jul 21, 2023 |
| Intel         | DP67BG AAG10491-400         | [084b222fa7](https://linux-hardware.org/?probe=084b222fa7) | Jul 21, 2023 |
| MSI           | Z170A GAMING M7             | [0e79ff628d](https://linux-hardware.org/?probe=0e79ff628d) | Jul 21, 2023 |
| MW            | NAS-N5105                   | [1a5c7ab436](https://linux-hardware.org/?probe=1a5c7ab436) | Jul 20, 2023 |
| Intel         | DP67BG AAG10491-400         | [e0ff2f40fa](https://linux-hardware.org/?probe=e0ff2f40fa) | Jul 20, 2023 |
| ECS           | H61H2-MV                    | [69a0cd41e0](https://linux-hardware.org/?probe=69a0cd41e0) | Jul 20, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a77eda6cc3](https://linux-hardware.org/?probe=a77eda6cc3) | Jul 20, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [ad0df808cb](https://linux-hardware.org/?probe=ad0df808cb) | Jul 20, 2023 |
| Dell          | 0D28YY A01                  | [6b01835487](https://linux-hardware.org/?probe=6b01835487) | Jul 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | [044cf93e31](https://linux-hardware.org/?probe=044cf93e31) | Jul 20, 2023 |
| ASRock        | X99M Extreme4               | [caf88d9f9d](https://linux-hardware.org/?probe=caf88d9f9d) | Jul 20, 2023 |
| Dell          | 0HN7XN A01                  | [567369da67](https://linux-hardware.org/?probe=567369da67) | Jul 20, 2023 |
| Gigabyte      | 990FXA-UD3                  | [8be5de827d](https://linux-hardware.org/?probe=8be5de827d) | Jul 20, 2023 |
| Dell          | 0HD5W2 A01                  | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| ASUSTek       | H97I-PLUS                   | [d244fb3ef9](https://linux-hardware.org/?probe=d244fb3ef9) | Jul 19, 2023 |
| Unknown       | Unknown                     | [39d3820e1a](https://linux-hardware.org/?probe=39d3820e1a) | Jul 19, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [ececa8856a](https://linux-hardware.org/?probe=ececa8856a) | Jul 19, 2023 |
| Dell          | 0XC7MM A00                  | [8d7dd80fa4](https://linux-hardware.org/?probe=8d7dd80fa4) | Jul 19, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [0f7fea54eb](https://linux-hardware.org/?probe=0f7fea54eb) | Jul 19, 2023 |
| MSI           | PRO B660M-E DDR4            | [62aa29ec8e](https://linux-hardware.org/?probe=62aa29ec8e) | Jul 19, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [290f64f841](https://linux-hardware.org/?probe=290f64f841) | Jul 19, 2023 |
| Dell          | 0HN7XN A01                  | [a7c167f16f](https://linux-hardware.org/?probe=a7c167f16f) | Jul 19, 2023 |
| MSI           | H81M-E33                    | [dc821e7080](https://linux-hardware.org/?probe=dc821e7080) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | [06e511f834](https://linux-hardware.org/?probe=06e511f834) | Jul 19, 2023 |
| ASUSTek       | H97M-E                      | [7171de16ea](https://linux-hardware.org/?probe=7171de16ea) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | [0c537839b2](https://linux-hardware.org/?probe=0c537839b2) | Jul 19, 2023 |
| ASUSTek       | PRIME Z390-A                | [94856d413f](https://linux-hardware.org/?probe=94856d413f) | Jul 19, 2023 |
| Gigabyte      | B450M DS3H V2               | [67db76ffed](https://linux-hardware.org/?probe=67db76ffed) | Jul 19, 2023 |
| Alienware     | 0VDT73 A00                  | [dfdf19c0f1](https://linux-hardware.org/?probe=dfdf19c0f1) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [140d426127](https://linux-hardware.org/?probe=140d426127) | Jul 18, 2023 |
| Dell          | 02YRK5 A02                  | [a09aa96e91](https://linux-hardware.org/?probe=a09aa96e91) | Jul 18, 2023 |
| HP            | 18E7                        | [bddd22fb18](https://linux-hardware.org/?probe=bddd22fb18) | Jul 18, 2023 |
| ASUSTek       | PRIME Z370-A II             | [6ca4720242](https://linux-hardware.org/?probe=6ca4720242) | Jul 18, 2023 |
| HP            | 889C                        | [3124074b5a](https://linux-hardware.org/?probe=3124074b5a) | Jul 18, 2023 |
| AMI           | Intel                       | [fb562a8b94](https://linux-hardware.org/?probe=fb562a8b94) | Jul 18, 2023 |
| AMI           | Intel                       | [52cb51f3c6](https://linux-hardware.org/?probe=52cb51f3c6) | Jul 18, 2023 |
| HP            | 304Ah                       | [649b673c7e](https://linux-hardware.org/?probe=649b673c7e) | Jul 18, 2023 |
| HP            | 304Ah                       | [8cd2a48010](https://linux-hardware.org/?probe=8cd2a48010) | Jul 18, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [0d9c612141](https://linux-hardware.org/?probe=0d9c612141) | Jul 17, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [a58b13cf37](https://linux-hardware.org/?probe=a58b13cf37) | Jul 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [0f497ef7f8](https://linux-hardware.org/?probe=0f497ef7f8) | Jul 17, 2023 |
| Dell          | 0GXM1W A00                  | [692ba8a4af](https://linux-hardware.org/?probe=692ba8a4af) | Jul 17, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [e7e1588ebf](https://linux-hardware.org/?probe=e7e1588ebf) | Jul 17, 2023 |
| ASRock Ind... | NUC-1220P                   | [3b1cedb39d](https://linux-hardware.org/?probe=3b1cedb39d) | Jul 17, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [b729a884f0](https://linux-hardware.org/?probe=b729a884f0) | Jul 17, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [d4b5c25500](https://linux-hardware.org/?probe=d4b5c25500) | Jul 17, 2023 |
| ASUSTek       | SABERTOOTH X58              | [d206dfdfed](https://linux-hardware.org/?probe=d206dfdfed) | Jul 17, 2023 |
| Dell          | 0PC5F7 A02                  | [b6fe9245e4](https://linux-hardware.org/?probe=b6fe9245e4) | Jul 17, 2023 |
| ASRock Ind... | NUC-1220P                   | [8094cfcbe6](https://linux-hardware.org/?probe=8094cfcbe6) | Jul 16, 2023 |
| HP            | 82F2 A01                    | [d4033cf114](https://linux-hardware.org/?probe=d4033cf114) | Jul 16, 2023 |
| MSI           | Z97 GAMING 7                | [28c6cd48b8](https://linux-hardware.org/?probe=28c6cd48b8) | Jul 16, 2023 |
| MSI           | Z97 GAMING 7                | [9ef499d31f](https://linux-hardware.org/?probe=9ef499d31f) | Jul 16, 2023 |
| MSI           | MAG Z690 TORPEDO            | [8f4a9f7202](https://linux-hardware.org/?probe=8f4a9f7202) | Jul 16, 2023 |
| Dell          | 0CRH6C A02                  | [abf1be3307](https://linux-hardware.org/?probe=abf1be3307) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [20ee7f8016](https://linux-hardware.org/?probe=20ee7f8016) | Jul 16, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [08d99231a6](https://linux-hardware.org/?probe=08d99231a6) | Jul 16, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [7fe3a6b5b2](https://linux-hardware.org/?probe=7fe3a6b5b2) | Jul 16, 2023 |
| HP            | ProLiant MicroServer Gen... | [ec8fee15ed](https://linux-hardware.org/?probe=ec8fee15ed) | Jul 16, 2023 |
| Shenzhen M... | F7BFC                       | [a6bcd9758f](https://linux-hardware.org/?probe=a6bcd9758f) | Jul 15, 2023 |
| Shenzhen M... | F7BFC                       | [c7eadb3912](https://linux-hardware.org/?probe=c7eadb3912) | Jul 15, 2023 |
| MSI           | MS-7369                     | [7cd5c6d6f0](https://linux-hardware.org/?probe=7cd5c6d6f0) | Jul 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [8296b2914a](https://linux-hardware.org/?probe=8296b2914a) | Jul 15, 2023 |
| Pegatron      | 2AB5                        | [f625288322](https://linux-hardware.org/?probe=f625288322) | Jul 15, 2023 |
| Dell          | 0D24M8 A01                  | [9e82c71281](https://linux-hardware.org/?probe=9e82c71281) | Jul 15, 2023 |
| MSI           | Z590-A PRO                  | [8c4fe85b51](https://linux-hardware.org/?probe=8c4fe85b51) | Jul 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [7d3eea9c76](https://linux-hardware.org/?probe=7d3eea9c76) | Jul 15, 2023 |
| HP            | 212A                        | [5ed0059210](https://linux-hardware.org/?probe=5ed0059210) | Jul 15, 2023 |
| ASUSTek       | H81M-V3                     | [017671472c](https://linux-hardware.org/?probe=017671472c) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | [f1a7e1dbb3](https://linux-hardware.org/?probe=f1a7e1dbb3) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-P                | [9eff556aca](https://linux-hardware.org/?probe=9eff556aca) | Jul 15, 2023 |
| ASRock        | G41M-VS3                    | [f472934f38](https://linux-hardware.org/?probe=f472934f38) | Jul 15, 2023 |
| Intel         | DH67BL AAG10189-211         | [3ac8b2e91d](https://linux-hardware.org/?probe=3ac8b2e91d) | Jul 14, 2023 |
| Gigabyte      | H510M H                     | [8771f0ddd0](https://linux-hardware.org/?probe=8771f0ddd0) | Jul 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Dell          | 0GXM1W A00                  | [cbdd93f7d6](https://linux-hardware.org/?probe=cbdd93f7d6) | Jul 14, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [62890116b3](https://linux-hardware.org/?probe=62890116b3) | Jul 14, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [476c241a58](https://linux-hardware.org/?probe=476c241a58) | Jul 14, 2023 |
| Huanan        | X99-F8 V5.0 JX              | [a45c6e5f27](https://linux-hardware.org/?probe=a45c6e5f27) | Jul 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [6776e11ac9](https://linux-hardware.org/?probe=6776e11ac9) | Jul 14, 2023 |
| Unknown       | Unknown                     | [cdf60a9582](https://linux-hardware.org/?probe=cdf60a9582) | Jul 14, 2023 |
| ASUSTek       | J1800I-A                    | [ce7f031b0a](https://linux-hardware.org/?probe=ce7f031b0a) | Jul 14, 2023 |
| ASUSTek       | P5E-V HDMI                  | [460e520a69](https://linux-hardware.org/?probe=460e520a69) | Jul 13, 2023 |
| Shenzhen M... | F7BFC                       | [a0c045bcd6](https://linux-hardware.org/?probe=a0c045bcd6) | Jul 13, 2023 |
| Shenzhen M... | F7BFC                       | [c0c4f2abb6](https://linux-hardware.org/?probe=c0c4f2abb6) | Jul 13, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME H410M-K               | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7c9bb65c6a](https://linux-hardware.org/?probe=7c9bb65c6a) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [3795772e96](https://linux-hardware.org/?probe=3795772e96) | Jul 13, 2023 |
| Unknown       | Unknown                     | [beea313884](https://linux-hardware.org/?probe=beea313884) | Jul 13, 2023 |
| ASUSTek       | AT3IONT-I                   | [773d5ee9aa](https://linux-hardware.org/?probe=773d5ee9aa) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [3428c47b0c](https://linux-hardware.org/?probe=3428c47b0c) | Jul 13, 2023 |
| Dell          | 00V62H A01                  | [7462f134fc](https://linux-hardware.org/?probe=7462f134fc) | Jul 13, 2023 |
| HP            | 1495                        | [fdbc0b7f33](https://linux-hardware.org/?probe=fdbc0b7f33) | Jul 13, 2023 |
| Dell          | 00V62H A01                  | [f2878312b2](https://linux-hardware.org/?probe=f2878312b2) | Jul 12, 2023 |
| Biostar       | H61MGV                      | [4fadeeb5bd](https://linux-hardware.org/?probe=4fadeeb5bd) | Jul 12, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f8ffcb4828](https://linux-hardware.org/?probe=f8ffcb4828) | Jul 12, 2023 |
| HP            | 1495                        | [8fa2ff9487](https://linux-hardware.org/?probe=8fa2ff9487) | Jul 12, 2023 |
| Gigabyte      | Z270X-Gaming 5              | [949ca22bb2](https://linux-hardware.org/?probe=949ca22bb2) | Jul 12, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [40281279ab](https://linux-hardware.org/?probe=40281279ab) | Jul 12, 2023 |
| HP            | 81BB                        | [ae0ad9c6fb](https://linux-hardware.org/?probe=ae0ad9c6fb) | Jul 12, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [077367f0bd](https://linux-hardware.org/?probe=077367f0bd) | Jul 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [58c9a4c19c](https://linux-hardware.org/?probe=58c9a4c19c) | Jul 12, 2023 |
| Dell          | 0CRH6C A02                  | [333813fa10](https://linux-hardware.org/?probe=333813fa10) | Jul 11, 2023 |
| Dell          | 0CRH6C A02                  | [66fb93438f](https://linux-hardware.org/?probe=66fb93438f) | Jul 11, 2023 |
| Gigabyte      | B450 AORUS M                | [500fee1ce5](https://linux-hardware.org/?probe=500fee1ce5) | Jul 11, 2023 |
| ASUSTek       | PRIME B450M-A               | [6c541c67b9](https://linux-hardware.org/?probe=6c541c67b9) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | [7a6bfcf1a9](https://linux-hardware.org/?probe=7a6bfcf1a9) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | [2397913be3](https://linux-hardware.org/?probe=2397913be3) | Jul 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [6481c63fee](https://linux-hardware.org/?probe=6481c63fee) | Jul 11, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [9b3b477b44](https://linux-hardware.org/?probe=9b3b477b44) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [bad8c925e6](https://linux-hardware.org/?probe=bad8c925e6) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [f754f1e59b](https://linux-hardware.org/?probe=f754f1e59b) | Jul 11, 2023 |
| ASRock        | H81M                        | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [7dc652ae30](https://linux-hardware.org/?probe=7dc652ae30) | Jul 11, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [8131ccf070](https://linux-hardware.org/?probe=8131ccf070) | Jul 11, 2023 |
| HP            | 212A                        | [65b433407e](https://linux-hardware.org/?probe=65b433407e) | Jul 11, 2023 |
| HP            | 3047h                       | [1a4c2d4702](https://linux-hardware.org/?probe=1a4c2d4702) | Jul 11, 2023 |
| ASUSTek       | H110M-A                     | [b2de29a3db](https://linux-hardware.org/?probe=b2de29a3db) | Jul 10, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [00e22b8fa7](https://linux-hardware.org/?probe=00e22b8fa7) | Jul 10, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [3aae868be2](https://linux-hardware.org/?probe=3aae868be2) | Jul 10, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [08c3b18c08](https://linux-hardware.org/?probe=08c3b18c08) | Jul 10, 2023 |
| WeiBu         | ADL-N Prod                  | [23746411d7](https://linux-hardware.org/?probe=23746411d7) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | [8e289dc3f9](https://linux-hardware.org/?probe=8e289dc3f9) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | [8f7a02d8b5](https://linux-hardware.org/?probe=8f7a02d8b5) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7c9b47b69f](https://linux-hardware.org/?probe=7c9b47b69f) | Jul 10, 2023 |
| Dell          | 02YRK5 A02                  | [113d7e1853](https://linux-hardware.org/?probe=113d7e1853) | Jul 10, 2023 |
| Dell          | 0JP3NX A01                  | [fb5723d423](https://linux-hardware.org/?probe=fb5723d423) | Jul 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [7c3e56e08a](https://linux-hardware.org/?probe=7c3e56e08a) | Jul 10, 2023 |
| MSI           | B550-A PRO                  | [483109bdd9](https://linux-hardware.org/?probe=483109bdd9) | Jul 09, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [08ae4ea22e](https://linux-hardware.org/?probe=08ae4ea22e) | Jul 09, 2023 |
| ASUSTek       | P8Z77-V                     | [13ece994a6](https://linux-hardware.org/?probe=13ece994a6) | Jul 09, 2023 |
| Gigabyte      | P55-USB3L                   | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| Unknown       | CoffeeLake                  | [b3f96a87d5](https://linux-hardware.org/?probe=b3f96a87d5) | Jul 09, 2023 |
| ASRock        | E3C224D4I-14S               | [bd2d074d07](https://linux-hardware.org/?probe=bd2d074d07) | Jul 09, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [549875a866](https://linux-hardware.org/?probe=549875a866) | Jul 09, 2023 |
| MSI           | MS-B9181                    | [4702ba374d](https://linux-hardware.org/?probe=4702ba374d) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| Unknown       | X99-GT                      | [34c4fadab5](https://linux-hardware.org/?probe=34c4fadab5) | Jul 08, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [8590628d0a](https://linux-hardware.org/?probe=8590628d0a) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| HP            | 3399                        | [432d638098](https://linux-hardware.org/?probe=432d638098) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [de745928b7](https://linux-hardware.org/?probe=de745928b7) | Jul 08, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [2ef97a52b8](https://linux-hardware.org/?probe=2ef97a52b8) | Jul 08, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [391ec4c6a8](https://linux-hardware.org/?probe=391ec4c6a8) | Jul 08, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [e07a2eb978](https://linux-hardware.org/?probe=e07a2eb978) | Jul 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [703f0e9012](https://linux-hardware.org/?probe=703f0e9012) | Jul 08, 2023 |
| MSI           | B550-A PRO                  | [9c6ce21357](https://linux-hardware.org/?probe=9c6ce21357) | Jul 07, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [4b952291ac](https://linux-hardware.org/?probe=4b952291ac) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [901c7b45c2](https://linux-hardware.org/?probe=901c7b45c2) | Jul 07, 2023 |
| Unknown       | Unknown                     | [690678e4bd](https://linux-hardware.org/?probe=690678e4bd) | Jul 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c816d8f1b](https://linux-hardware.org/?probe=8c816d8f1b) | Jul 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [ab73e6cc7f](https://linux-hardware.org/?probe=ab73e6cc7f) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3401b425ae](https://linux-hardware.org/?probe=3401b425ae) | Jul 07, 2023 |
| HP            | 2129                        | [12a66801ad](https://linux-hardware.org/?probe=12a66801ad) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | [23c5c27995](https://linux-hardware.org/?probe=23c5c27995) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| ASRock        | A320M-HD                    | [7eb9d089cf](https://linux-hardware.org/?probe=7eb9d089cf) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [2d20ffc659](https://linux-hardware.org/?probe=2d20ffc659) | Jul 06, 2023 |
| HP            | 2B2C                        | [3989b4f642](https://linux-hardware.org/?probe=3989b4f642) | Jul 06, 2023 |
| ASUSTek       | Z170-A                      | [87a26e01e6](https://linux-hardware.org/?probe=87a26e01e6) | Jul 06, 2023 |
| HP            | 3398                        | [3124ceac21](https://linux-hardware.org/?probe=3124ceac21) | Jul 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [04d7534d9e](https://linux-hardware.org/?probe=04d7534d9e) | Jul 06, 2023 |
| Gigabyte      | F2A68HM-H                   | [e9b7499b4d](https://linux-hardware.org/?probe=e9b7499b4d) | Jul 06, 2023 |
| Dell          | 0N4YC8 A00                  | [b6c778034c](https://linux-hardware.org/?probe=b6c778034c) | Jul 06, 2023 |
| ASUSTek       | A88X-PRO                    | [6a20985072](https://linux-hardware.org/?probe=6a20985072) | Jul 05, 2023 |
| ASRock        | H81M-HDS                    | [80074bc9c4](https://linux-hardware.org/?probe=80074bc9c4) | Jul 05, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [a9f169ce16](https://linux-hardware.org/?probe=a9f169ce16) | Jul 05, 2023 |
| ASUSTek       | WS X299 SAGE                | [f97dafae6f](https://linux-hardware.org/?probe=f97dafae6f) | Jul 05, 2023 |
| Gateway       | SX2110GA                    | [1698b8292d](https://linux-hardware.org/?probe=1698b8292d) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3ec7b573fc](https://linux-hardware.org/?probe=3ec7b573fc) | Jul 05, 2023 |
| HP            | 18E4                        | [6d3964fd1b](https://linux-hardware.org/?probe=6d3964fd1b) | Jul 05, 2023 |
| HP            | 18E4                        | [8a382f8911](https://linux-hardware.org/?probe=8a382f8911) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [497e454852](https://linux-hardware.org/?probe=497e454852) | Jul 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [44140c28bb](https://linux-hardware.org/?probe=44140c28bb) | Jul 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [a89cd340ff](https://linux-hardware.org/?probe=a89cd340ff) | Jul 05, 2023 |
| MSI           | Indio                       | [b61c090b7e](https://linux-hardware.org/?probe=b61c090b7e) | Jul 05, 2023 |
| ASUSTek       | H81M-PLUS                   | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| Gigabyte      | H110-D3A-CF                 | [bd9c7a22d6](https://linux-hardware.org/?probe=bd9c7a22d6) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [f9688a073f](https://linux-hardware.org/?probe=f9688a073f) | Jul 04, 2023 |
| Intel         | DH61WW AAG23116-206         | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| Apple         | Mac-F4208DA9 PVT            | [6c2cdc1c76](https://linux-hardware.org/?probe=6c2cdc1c76) | Jul 04, 2023 |
| HP            | 83EF                        | [5f850e2bc1](https://linux-hardware.org/?probe=5f850e2bc1) | Jul 04, 2023 |
| HP            | 212A                        | [f936acf506](https://linux-hardware.org/?probe=f936acf506) | Jul 04, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [db376a9857](https://linux-hardware.org/?probe=db376a9857) | Jul 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [5f1c0efa6b](https://linux-hardware.org/?probe=5f1c0efa6b) | Jul 04, 2023 |
| MSI           | PRO X670-P WIFI             | [a6658d55ff](https://linux-hardware.org/?probe=a6658d55ff) | Jul 04, 2023 |
| Dell          | 0TNDVR A00                  | [050573aef7](https://linux-hardware.org/?probe=050573aef7) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [ed7caf91c0](https://linux-hardware.org/?probe=ed7caf91c0) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [7002d2d6a8](https://linux-hardware.org/?probe=7002d2d6a8) | Jul 03, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [4b9e57acb0](https://linux-hardware.org/?probe=4b9e57acb0) | Jul 03, 2023 |
| HP            | 1791                        | [64fdea845b](https://linux-hardware.org/?probe=64fdea845b) | Jul 03, 2023 |
| ASUSTek       | H170M-PLUS                  | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [46dbe425b5](https://linux-hardware.org/?probe=46dbe425b5) | Jul 03, 2023 |
| Medion        | BTDD-LT                     | [6c22cd4728](https://linux-hardware.org/?probe=6c22cd4728) | Jul 03, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [231af0c684](https://linux-hardware.org/?probe=231af0c684) | Jul 03, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [5509c9dd07](https://linux-hardware.org/?probe=5509c9dd07) | Jul 03, 2023 |
| ASUSTek       | WS X299 PRO_SE              | [d31cedc2ad](https://linux-hardware.org/?probe=d31cedc2ad) | Jul 03, 2023 |
| HP            | 2129                        | [cc9462c976](https://linux-hardware.org/?probe=cc9462c976) | Jul 02, 2023 |
| Gigabyte      | B460M DS3H AC               | [71aa2fd160](https://linux-hardware.org/?probe=71aa2fd160) | Jul 02, 2023 |
| Medion        | BTDD-LT                     | [fb1c5c941c](https://linux-hardware.org/?probe=fb1c5c941c) | Jul 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8712050b69](https://linux-hardware.org/?probe=8712050b69) | Jul 02, 2023 |
| Lenovo        | ThinkStation E30 782497U    | [f9376fd059](https://linux-hardware.org/?probe=f9376fd059) | Jul 02, 2023 |
| Lenovo        | ThinkStation E30 782497U    | [6dcf0eeb55](https://linux-hardware.org/?probe=6dcf0eeb55) | Jul 02, 2023 |
| ASUSTek       | PRIME B450M-A II            | [24b39db7e7](https://linux-hardware.org/?probe=24b39db7e7) | Jul 02, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b010348549](https://linux-hardware.org/?probe=b010348549) | Jul 02, 2023 |
| MSI           | Boston                      | [39a458d562](https://linux-hardware.org/?probe=39a458d562) | Jul 01, 2023 |
| Unknown       | Unknown                     | [1b8105097a](https://linux-hardware.org/?probe=1b8105097a) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [46c52eedc1](https://linux-hardware.org/?probe=46c52eedc1) | Jul 01, 2023 |
| Intel         | X99                         | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Acer          | TDPS05                      | [71cf03e3a2](https://linux-hardware.org/?probe=71cf03e3a2) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dea1298c2e](https://linux-hardware.org/?probe=dea1298c2e) | Jul 01, 2023 |
| Gigabyte      | H61M-USB3V                  | [cebfe5c301](https://linux-hardware.org/?probe=cebfe5c301) | Jul 01, 2023 |
| Gigabyte      | H61M-USB3V                  | [715907e0c3](https://linux-hardware.org/?probe=715907e0c3) | Jul 01, 2023 |
| Unknown       | Unknown                     | [53eedfaac9](https://linux-hardware.org/?probe=53eedfaac9) | Jul 01, 2023 |
| Dell          | 09KPNV A01                  | [ca6243303f](https://linux-hardware.org/?probe=ca6243303f) | Jul 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [9564e74fb6](https://linux-hardware.org/?probe=9564e74fb6) | Jul 01, 2023 |
| ASRock        | H510M-HDV/M.2               | [ec9ab3662c](https://linux-hardware.org/?probe=ec9ab3662c) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| Supermicro    | X10DDW-i                    | [c43e65f1ae](https://linux-hardware.org/?probe=c43e65f1ae) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Pegatron      | 2AB5                        | [f23fa01e43](https://linux-hardware.org/?probe=f23fa01e43) | Jun 30, 2023 |
| AZW           | SEi                         | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Intel         | X99H                        | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Supermicro    | X9DRW                       | [cb955d7a58](https://linux-hardware.org/?probe=cb955d7a58) | Jun 30, 2023 |
| HP            | 1497                        | [4dd582d288](https://linux-hardware.org/?probe=4dd582d288) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [f4fff60df3](https://linux-hardware.org/?probe=f4fff60df3) | Jun 30, 2023 |
| ASUSTek       | M51AC                       | [d32d060e9c](https://linux-hardware.org/?probe=d32d060e9c) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [c860545122](https://linux-hardware.org/?probe=c860545122) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [5a6b149eb4](https://linux-hardware.org/?probe=5a6b149eb4) | Jun 29, 2023 |
| Dell          | 0T568R A00                  | [cf98a8a69b](https://linux-hardware.org/?probe=cf98a8a69b) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6cb722f64](https://linux-hardware.org/?probe=d6cb722f64) | Jun 29, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [304ff06fc0](https://linux-hardware.org/?probe=304ff06fc0) | Jun 29, 2023 |
| MSI           | Z87 MPOWER                  | [e34420b76e](https://linux-hardware.org/?probe=e34420b76e) | Jun 29, 2023 |
| ASUSTek       | F2A85-M PRO                 | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| ZR            | A320M-F 1005                | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e29021ab76](https://linux-hardware.org/?probe=e29021ab76) | Jun 28, 2023 |
| ASRock        | X570 Taichi                 | [75cb221d91](https://linux-hardware.org/?probe=75cb221d91) | Jun 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [1f5a11092b](https://linux-hardware.org/?probe=1f5a11092b) | Jun 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [607da926f3](https://linux-hardware.org/?probe=607da926f3) | Jun 28, 2023 |
| ASUSTek       | F2A55-M LK                  | [0fcac8a0af](https://linux-hardware.org/?probe=0fcac8a0af) | Jun 28, 2023 |
| MSI           | Z390-A PRO                  | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| ASRock        | AB350M-HDV                  | [a055db3af3](https://linux-hardware.org/?probe=a055db3af3) | Jun 27, 2023 |
| Dell          | 0KWVT8 A03                  | [8dcd3c3200](https://linux-hardware.org/?probe=8dcd3c3200) | Jun 27, 2023 |
| Gigabyte      | H310M M.2 x.x               | [6f9c836bb4](https://linux-hardware.org/?probe=6f9c836bb4) | Jun 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [708131b231](https://linux-hardware.org/?probe=708131b231) | Jun 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [ef8f76e9e1](https://linux-hardware.org/?probe=ef8f76e9e1) | Jun 27, 2023 |
| Dell          | 0FXD80 A00                  | [4427c2159c](https://linux-hardware.org/?probe=4427c2159c) | Jun 27, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Dell          | 00010C A00                  | [f965b0f028](https://linux-hardware.org/?probe=f965b0f028) | Jun 27, 2023 |
| HP            | 0A9Ch                       | [08eccac462](https://linux-hardware.org/?probe=08eccac462) | Jun 27, 2023 |
| ASRock        | 960GM-VGS3 FX               | [2cd4ef0e5d](https://linux-hardware.org/?probe=2cd4ef0e5d) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [962cd7b905](https://linux-hardware.org/?probe=962cd7b905) | Jun 27, 2023 |
| Gigabyte      | AB350M-D3H-CF               | [c73458700f](https://linux-hardware.org/?probe=c73458700f) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [91b5e02477](https://linux-hardware.org/?probe=91b5e02477) | Jun 26, 2023 |
| Biostar       | B550T-SILVER                | [bae0c9a5b0](https://linux-hardware.org/?probe=bae0c9a5b0) | Jun 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [309cb87000](https://linux-hardware.org/?probe=309cb87000) | Jun 26, 2023 |
| Intel         | DH55TC AAE70932-206         | [9ff872e2a3](https://linux-hardware.org/?probe=9ff872e2a3) | Jun 26, 2023 |
| HP            | 21F5 0A                     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| ASUSTek       | B85M-G                      | [5a9f85740e](https://linux-hardware.org/?probe=5a9f85740e) | Jun 26, 2023 |
| Unknown       | Unknown                     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [baeab145a2](https://linux-hardware.org/?probe=baeab145a2) | Jun 26, 2023 |
| Lenovo        | 3102 NOK                    | [6277771b08](https://linux-hardware.org/?probe=6277771b08) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 7033A1G    | [a3ca410b6a](https://linux-hardware.org/?probe=a3ca410b6a) | Jun 26, 2023 |
| ASRock        | H61M-VG4                    | [7fbf9c4e53](https://linux-hardware.org/?probe=7fbf9c4e53) | Jun 25, 2023 |
| Intel         | B75                         | [2456289bbd](https://linux-hardware.org/?probe=2456289bbd) | Jun 25, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [9aa214f70a](https://linux-hardware.org/?probe=9aa214f70a) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | [dc2911bfae](https://linux-hardware.org/?probe=dc2911bfae) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | [273bec93a4](https://linux-hardware.org/?probe=273bec93a4) | Jun 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac084eba06](https://linux-hardware.org/?probe=ac084eba06) | Jun 24, 2023 |
| Intel         | DH55HC AAE70933-503         | [8dab0b7f0d](https://linux-hardware.org/?probe=8dab0b7f0d) | Jun 24, 2023 |
| ASUSTek       | P5K                         | [c33ff02489](https://linux-hardware.org/?probe=c33ff02489) | Jun 24, 2023 |
| ASUSTek       | P5K                         | [c87e87b883](https://linux-hardware.org/?probe=c87e87b883) | Jun 24, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a19fc9dde8](https://linux-hardware.org/?probe=a19fc9dde8) | Jun 24, 2023 |
| HP            | 0A9Ch                       | [4bd59bd633](https://linux-hardware.org/?probe=4bd59bd633) | Jun 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 CJ41GV2... | [79a2c321e8](https://linux-hardware.org/?probe=79a2c321e8) | Jun 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [0f64e88f33](https://linux-hardware.org/?probe=0f64e88f33) | Jun 23, 2023 |
| HP            | 304Bh                       | [234bedfab1](https://linux-hardware.org/?probe=234bedfab1) | Jun 23, 2023 |
| ASUSTek       | Q87M-E                      | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Dell          | 0CRH6C A02                  | [7ce8bcbc26](https://linux-hardware.org/?probe=7ce8bcbc26) | Jun 23, 2023 |
| ASRock        | B365M Pro4-F                | [16a5102512](https://linux-hardware.org/?probe=16a5102512) | Jun 23, 2023 |
| HP            | 3047h                       | [e60df0b6d1](https://linux-hardware.org/?probe=e60df0b6d1) | Jun 23, 2023 |
| ASUSTek       | PRIME B550M-A               | [3789bc7deb](https://linux-hardware.org/?probe=3789bc7deb) | Jun 23, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c202144225](https://linux-hardware.org/?probe=c202144225) | Jun 23, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [83eb8cda4a](https://linux-hardware.org/?probe=83eb8cda4a) | Jun 23, 2023 |
| HP            | 0A9Ch                       | [2f48843246](https://linux-hardware.org/?probe=2f48843246) | Jun 23, 2023 |
| Foxconn       | ALOE X3                     | [ec9afb2155](https://linux-hardware.org/?probe=ec9afb2155) | Jun 23, 2023 |
| MSI           | 760GM-E51                   | [078c1805bd](https://linux-hardware.org/?probe=078c1805bd) | Jun 22, 2023 |
| Supermicro    | X9DRW                       | [3b2f007f67](https://linux-hardware.org/?probe=3b2f007f67) | Jun 22, 2023 |
| Unknown       | Unknown                     | [3e25fc74a7](https://linux-hardware.org/?probe=3e25fc74a7) | Jun 22, 2023 |
| Unknown       | Unknown                     | [c2e0154437](https://linux-hardware.org/?probe=c2e0154437) | Jun 22, 2023 |
| ASRock        | X399 Taichi                 | [d9ca7c4369](https://linux-hardware.org/?probe=d9ca7c4369) | Jun 22, 2023 |
| ASRock        | H61M-VG3                    | [955228e9e5](https://linux-hardware.org/?probe=955228e9e5) | Jun 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d3a63bb6aa](https://linux-hardware.org/?probe=d3a63bb6aa) | Jun 22, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6c43b99ec8](https://linux-hardware.org/?probe=6c43b99ec8) | Jun 22, 2023 |
| ASRock        | B365 Pro4                   | [46dc8e10a8](https://linux-hardware.org/?probe=46dc8e10a8) | Jun 21, 2023 |
| Dell          | 0NKW6Y A01                  | [def5a35ba4](https://linux-hardware.org/?probe=def5a35ba4) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| MSI           | B450-A PRO MAX              | [589e702758](https://linux-hardware.org/?probe=589e702758) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | [c3961b2aa5](https://linux-hardware.org/?probe=c3961b2aa5) | Jun 21, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [8c4bd347a7](https://linux-hardware.org/?probe=8c4bd347a7) | Jun 21, 2023 |
| Gigabyte      | Z97M-D3H                    | [66e2a42098](https://linux-hardware.org/?probe=66e2a42098) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [ff224b2f9d](https://linux-hardware.org/?probe=ff224b2f9d) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [acbd33c5c8](https://linux-hardware.org/?probe=acbd33c5c8) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [f76394a58a](https://linux-hardware.org/?probe=f76394a58a) | Jun 21, 2023 |
| HP            | 339A                        | [960fd64baa](https://linux-hardware.org/?probe=960fd64baa) | Jun 21, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [63f5506bc3](https://linux-hardware.org/?probe=63f5506bc3) | Jun 21, 2023 |
| HP            | 339A                        | [60b0bff872](https://linux-hardware.org/?probe=60b0bff872) | Jun 21, 2023 |
| Dell          | 0GM819                      | [5823b51b38](https://linux-hardware.org/?probe=5823b51b38) | Jun 20, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6f0b6969bf](https://linux-hardware.org/?probe=6f0b6969bf) | Jun 20, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [92f6324f8a](https://linux-hardware.org/?probe=92f6324f8a) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f1acdd3081](https://linux-hardware.org/?probe=f1acdd3081) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| HP            | 18E4                        | [9e2ad40fc3](https://linux-hardware.org/?probe=9e2ad40fc3) | Jun 20, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [19c5a44099](https://linux-hardware.org/?probe=19c5a44099) | Jun 20, 2023 |
| ASRock        | X370 Killer SLI             | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| ASRock        | H270 Pro4                   | [e3b13a5c7f](https://linux-hardware.org/?probe=e3b13a5c7f) | Jun 20, 2023 |
| AMI           | Intel                       | [94c1b63cc6](https://linux-hardware.org/?probe=94c1b63cc6) | Jun 20, 2023 |
| Acer          | Veriton X490G               | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [d9d8f74eca](https://linux-hardware.org/?probe=d9d8f74eca) | Jun 19, 2023 |
| Lenovo        | ThinkServer TS140           | [9210e713ff](https://linux-hardware.org/?probe=9210e713ff) | Jun 19, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| Dell          | 0CRH6C A02                  | [6ae5e917b4](https://linux-hardware.org/?probe=6ae5e917b4) | Jun 19, 2023 |
| Dell          | 0DF42J A00                  | [c1db29329c](https://linux-hardware.org/?probe=c1db29329c) | Jun 19, 2023 |
| Shuttle       | SA76 V10                    | [fbcf156e7e](https://linux-hardware.org/?probe=fbcf156e7e) | Jun 19, 2023 |
| Gigabyte      | Z77MX-D3H                   | [c1aac2f0a4](https://linux-hardware.org/?probe=c1aac2f0a4) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [257c60290f](https://linux-hardware.org/?probe=257c60290f) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| Alienware     | 0CPDXD A00                  | [3e1923b97a](https://linux-hardware.org/?probe=3e1923b97a) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [fcec0ed2a4](https://linux-hardware.org/?probe=fcec0ed2a4) | Jun 19, 2023 |
| ASUSTek       | H110M-A                     | [22fc172f71](https://linux-hardware.org/?probe=22fc172f71) | Jun 18, 2023 |
| Dell          | 0CRH6C A02                  | [3dc796f9d3](https://linux-hardware.org/?probe=3dc796f9d3) | Jun 18, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [68e00c1869](https://linux-hardware.org/?probe=68e00c1869) | Jun 18, 2023 |
| ZR            | A320M-F 1005                | [e3c749da2a](https://linux-hardware.org/?probe=e3c749da2a) | Jun 18, 2023 |
| ASUSTek       | PRIME H510M-K               | [6ce49c3f6f](https://linux-hardware.org/?probe=6ce49c3f6f) | Jun 18, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [02de076b1c](https://linux-hardware.org/?probe=02de076b1c) | Jun 18, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [c409de5ebd](https://linux-hardware.org/?probe=c409de5ebd) | Jun 18, 2023 |
| Dell          | 06NWYK A00                  | [5e065b17cf](https://linux-hardware.org/?probe=5e065b17cf) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [176bffae78](https://linux-hardware.org/?probe=176bffae78) | Jun 18, 2023 |
| ASUSTek       | F2A55-M LK                  | [961b50409f](https://linux-hardware.org/?probe=961b50409f) | Jun 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7cefb01373](https://linux-hardware.org/?probe=7cefb01373) | Jun 18, 2023 |
| PCWare        | IPX1800E1                   | [59b9fa6ff9](https://linux-hardware.org/?probe=59b9fa6ff9) | Jun 17, 2023 |
| Gigabyte      | B450M DS3H V2               | [434d06d1ea](https://linux-hardware.org/?probe=434d06d1ea) | Jun 17, 2023 |
| AZW           | GTi                         | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | [bebc7de8d4](https://linux-hardware.org/?probe=bebc7de8d4) | Jun 17, 2023 |
| ASUSTek       | A55BM-E                     | [98b3d14b06](https://linux-hardware.org/?probe=98b3d14b06) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | [0a02c36bd6](https://linux-hardware.org/?probe=0a02c36bd6) | Jun 17, 2023 |
| Medion        | H110H4-EM                   | [d1cae28722](https://linux-hardware.org/?probe=d1cae28722) | Jun 17, 2023 |
| ZR            | A320M-F 1005                | [c190f4fcff](https://linux-hardware.org/?probe=c190f4fcff) | Jun 17, 2023 |
| HP            | 3397                        | [b9fa9f9e43](https://linux-hardware.org/?probe=b9fa9f9e43) | Jun 17, 2023 |
| Dell          | 0PU052                      | [93bd9e7b0b](https://linux-hardware.org/?probe=93bd9e7b0b) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [a585caa218](https://linux-hardware.org/?probe=a585caa218) | Jun 17, 2023 |
| MSI           | Boston                      | [8bc41737a5](https://linux-hardware.org/?probe=8bc41737a5) | Jun 17, 2023 |
| Dell          | 0PU052                      | [36b0b1204f](https://linux-hardware.org/?probe=36b0b1204f) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| Dell          | 0PU052                      | [d5d7c6ec90](https://linux-hardware.org/?probe=d5d7c6ec90) | Jun 16, 2023 |
| MSI           | X58 Pro-E                   | [abd2765191](https://linux-hardware.org/?probe=abd2765191) | Jun 16, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [c5cea5f197](https://linux-hardware.org/?probe=c5cea5f197) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [2543c7b4c9](https://linux-hardware.org/?probe=2543c7b4c9) | Jun 16, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [c47a9a7bb8](https://linux-hardware.org/?probe=c47a9a7bb8) | Jun 16, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [6a93f8d5d8](https://linux-hardware.org/?probe=6a93f8d5d8) | Jun 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5844f8b39b](https://linux-hardware.org/?probe=5844f8b39b) | Jun 16, 2023 |
| OEM           | ALDER LAKE JHS64S           | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Biostar       | A880GZ                      | [0ab2ec8924](https://linux-hardware.org/?probe=0ab2ec8924) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a3068b835](https://linux-hardware.org/?probe=2a3068b835) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [96be22e98f](https://linux-hardware.org/?probe=96be22e98f) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f94cf27a96](https://linux-hardware.org/?probe=f94cf27a96) | Jun 15, 2023 |
| Gateway       | SX2110GA                    | [e47130d966](https://linux-hardware.org/?probe=e47130d966) | Jun 15, 2023 |
| ASUSTek       | F2A55-M LK                  | [68965d8ed9](https://linux-hardware.org/?probe=68965d8ed9) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [05923edc6b](https://linux-hardware.org/?probe=05923edc6b) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [95a5739eda](https://linux-hardware.org/?probe=95a5739eda) | Jun 14, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [7ee7ee0f67](https://linux-hardware.org/?probe=7ee7ee0f67) | Jun 14, 2023 |
| Unknown       | Unknown                     | [e6ac28ac73](https://linux-hardware.org/?probe=e6ac28ac73) | Jun 14, 2023 |
| Unknown       | Unknown                     | [ca27fe4c19](https://linux-hardware.org/?probe=ca27fe4c19) | Jun 14, 2023 |
| ASUSTek       | M5A99X EVO                  | [5732495ae1](https://linux-hardware.org/?probe=5732495ae1) | Jun 14, 2023 |
| Unknown       | Unknown                     | [613aa12940](https://linux-hardware.org/?probe=613aa12940) | Jun 14, 2023 |
| Shenzhen M... | F7BFC                       | [7ae905703c](https://linux-hardware.org/?probe=7ae905703c) | Jun 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [2bc004d4b4](https://linux-hardware.org/?probe=2bc004d4b4) | Jun 14, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [993f00eca6](https://linux-hardware.org/?probe=993f00eca6) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [3bf8d20351](https://linux-hardware.org/?probe=3bf8d20351) | Jun 14, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [bc10401eda](https://linux-hardware.org/?probe=bc10401eda) | Jun 14, 2023 |
| ASUSTek       | P9X79 PRO                   | [4bab6db53f](https://linux-hardware.org/?probe=4bab6db53f) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| Chuwi         | RZBOX                       | [11bb40ef32](https://linux-hardware.org/?probe=11bb40ef32) | Jun 13, 2023 |
| Foxconn       | 2ABF                        | [61a0229bdd](https://linux-hardware.org/?probe=61a0229bdd) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS M                | [aaef0bda82](https://linux-hardware.org/?probe=aaef0bda82) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [0f19266aaf](https://linux-hardware.org/?probe=0f19266aaf) | Jun 13, 2023 |
| HP            | 18E7                        | [1be1b42bb4](https://linux-hardware.org/?probe=1be1b42bb4) | Jun 13, 2023 |
| HP            | 18E7                        | [cbf4019da2](https://linux-hardware.org/?probe=cbf4019da2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [7689518326](https://linux-hardware.org/?probe=7689518326) | Jun 13, 2023 |
| ASUSTek       | P9X79 PRO                   | [9e6d8db2d3](https://linux-hardware.org/?probe=9e6d8db2d3) | Jun 13, 2023 |
| ASUSTek       | P7P55D LE                   | [285303d1a0](https://linux-hardware.org/?probe=285303d1a0) | Jun 13, 2023 |
| Seco          | C40 C                       | [37b8e950d0](https://linux-hardware.org/?probe=37b8e950d0) | Jun 12, 2023 |
| ASRockRack    | B565D4-V1L                  | [34df85cbb3](https://linux-hardware.org/?probe=34df85cbb3) | Jun 12, 2023 |
| MSI           | X470 GAMING PRO             | [5f60b4bbac](https://linux-hardware.org/?probe=5f60b4bbac) | Jun 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [e68b78c037](https://linux-hardware.org/?probe=e68b78c037) | Jun 12, 2023 |
| MSI           | 760GM-P23                   | [9abb16943e](https://linux-hardware.org/?probe=9abb16943e) | Jun 12, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [b870560cb8](https://linux-hardware.org/?probe=b870560cb8) | Jun 12, 2023 |
| Dell          | 0YF8P5 A00                  | [5ac4a46c16](https://linux-hardware.org/?probe=5ac4a46c16) | Jun 12, 2023 |
| Dell          | 0XCR8D A02                  | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| Dell          | 0M5DCD A00                  | [ae7b392070](https://linux-hardware.org/?probe=ae7b392070) | Jun 12, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [1364983b69](https://linux-hardware.org/?probe=1364983b69) | Jun 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [7480d3ed9c](https://linux-hardware.org/?probe=7480d3ed9c) | Jun 11, 2023 |
| Gigabyte      | P55-USB3                    | [33915148d2](https://linux-hardware.org/?probe=33915148d2) | Jun 11, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8363538b57](https://linux-hardware.org/?probe=8363538b57) | Jun 11, 2023 |
| ASUSTek       | H110M-PLUS                  | [c544318b46](https://linux-hardware.org/?probe=c544318b46) | Jun 11, 2023 |
| Dell          | 0FDY5C A00                  | [21ad2d85dc](https://linux-hardware.org/?probe=21ad2d85dc) | Jun 11, 2023 |
| HP            | 3398                        | [7523eb041f](https://linux-hardware.org/?probe=7523eb041f) | Jun 11, 2023 |
| ASUSTek       | V-P5G43 R1.04G              | [e2400bfebe](https://linux-hardware.org/?probe=e2400bfebe) | Jun 11, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [e2673cf04e](https://linux-hardware.org/?probe=e2673cf04e) | Jun 11, 2023 |
| Unknown       | Unknown                     | [fae1758e76](https://linux-hardware.org/?probe=fae1758e76) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [baf1f44dc8](https://linux-hardware.org/?probe=baf1f44dc8) | Jun 11, 2023 |
| ASRock        | B650M PG Riptide            | [0f8fc0513f](https://linux-hardware.org/?probe=0f8fc0513f) | Jun 11, 2023 |
| Dell          | 0WMJ54 A01                  | [a6fb35a2d8](https://linux-hardware.org/?probe=a6fb35a2d8) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Chuwi         | RZBOX                       | [e31b33ae5e](https://linux-hardware.org/?probe=e31b33ae5e) | Jun 11, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [2cd4d2c377](https://linux-hardware.org/?probe=2cd4d2c377) | Jun 11, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [3544b34815](https://linux-hardware.org/?probe=3544b34815) | Jun 11, 2023 |
| Dell          | 0FDY5C A00                  | [100d556664](https://linux-hardware.org/?probe=100d556664) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | M5A78L/USB3                 | [81e4b3fe5c](https://linux-hardware.org/?probe=81e4b3fe5c) | Jun 10, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b5aee5a0a1](https://linux-hardware.org/?probe=b5aee5a0a1) | Jun 10, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| ASUSTek       | F2A85-V PRO                 | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| Gigabyte      | B650M GAMING X AX           | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Pegatron      | Benicia                     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| Dell          | 0PU052                      | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | 0WMJ54 A01                  | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [a1877cb5b3](https://linux-hardware.org/?probe=a1877cb5b3) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| MSI           | H81I                        | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [5833483fe2](https://linux-hardware.org/?probe=5833483fe2) | Jun 09, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [40f18ae1f4](https://linux-hardware.org/?probe=40f18ae1f4) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| HP            | 2B35                        | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| Dell          | 0KRC95 A02                  | [585c31e8d3](https://linux-hardware.org/?probe=585c31e8d3) | Jun 08, 2023 |
| Dell          | 0K83V0 A00                  | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [8c84a543bf](https://linux-hardware.org/?probe=8c84a543bf) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| HJS           | OPSH110D4                   | [bfb0ead991](https://linux-hardware.org/?probe=bfb0ead991) | Jun 08, 2023 |
| AZW           | SEi                         | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Dell          | 0GDG8Y A00                  | [4789561d79](https://linux-hardware.org/?probe=4789561d79) | Jun 08, 2023 |
| Dell          | 088DT1 A01                  | [173e9a0e0c](https://linux-hardware.org/?probe=173e9a0e0c) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [a91f24af7a](https://linux-hardware.org/?probe=a91f24af7a) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [96e1e7ea7e](https://linux-hardware.org/?probe=96e1e7ea7e) | Jun 08, 2023 |
| ASRock        | B85M-HDS                    | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b18ffc5311](https://linux-hardware.org/?probe=b18ffc5311) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| ASRock        | G41C-GS R2.0                | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| HP            | 2820h                       | [eb7322ad95](https://linux-hardware.org/?probe=eb7322ad95) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| HP            | 3397                        | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| Gigabyte      | H310M M.2 x.x               | [602e1c8875](https://linux-hardware.org/?probe=602e1c8875) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Gigabyte      | Z590 VISION G               | [ee1abb360e](https://linux-hardware.org/?probe=ee1abb360e) | Jun 06, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [de614b2bc7](https://linux-hardware.org/?probe=de614b2bc7) | Jun 05, 2023 |
| HP            | 3397                        | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| HP            | 83E2                        | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [0cf4dfc5e4](https://linux-hardware.org/?probe=0cf4dfc5e4) | Jun 05, 2023 |
| HP            | 3397                        | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| Pegatron      | 2AC2                        | [6182103d25](https://linux-hardware.org/?probe=6182103d25) | Jun 05, 2023 |
| MSI           | Boston                      | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| ASRock        | A75M-HVS                    | [69bc52dc4f](https://linux-hardware.org/?probe=69bc52dc4f) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| HP            | 83E2                        | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| Unknown       | Unknown                     | [8c2d7ce6e2](https://linux-hardware.org/?probe=8c2d7ce6e2) | Jun 04, 2023 |
| Dell          | 0N4NF7 A00                  | [e1348eb2c2](https://linux-hardware.org/?probe=e1348eb2c2) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | [6ff177257b](https://linux-hardware.org/?probe=6ff177257b) | Jun 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [2745284306](https://linux-hardware.org/?probe=2745284306) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [1ebbe353ba](https://linux-hardware.org/?probe=1ebbe353ba) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [0bb2080b31](https://linux-hardware.org/?probe=0bb2080b31) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| Biostar       | TA970XE                     | [11936a0f0f](https://linux-hardware.org/?probe=11936a0f0f) | Jun 02, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [c8fca2b92d](https://linux-hardware.org/?probe=c8fca2b92d) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [6c86bd69e0](https://linux-hardware.org/?probe=6c86bd69e0) | Jun 01, 2023 |
| ASRock        | Z77M                        | [eae1adee21](https://linux-hardware.org/?probe=eae1adee21) | Jun 01, 2023 |
| HP            | 18E5                        | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| HP            | 1906                        | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| HP            | 18E7                        | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Pegatron      | 2ACB                        | [cfd38fc71a](https://linux-hardware.org/?probe=cfd38fc71a) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | G10DK                       | [75cde40262](https://linux-hardware.org/?probe=75cde40262) | May 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c6c547437](https://linux-hardware.org/?probe=2c6c547437) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| System76      | Thelio Mira                 | [d5fe3a3749](https://linux-hardware.org/?probe=d5fe3a3749) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [a7e599b1f5](https://linux-hardware.org/?probe=a7e599b1f5) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [a29a16d74c](https://linux-hardware.org/?probe=a29a16d74c) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [c471536b99](https://linux-hardware.org/?probe=c471536b99) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [05e7ed23f3](https://linux-hardware.org/?probe=05e7ed23f3) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Pegatron      | 2AC2                        | [a8873fdeab](https://linux-hardware.org/?probe=a8873fdeab) | May 30, 2023 |
| ASUSTek       | PRIME Z370-P                | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [d98102f69a](https://linux-hardware.org/?probe=d98102f69a) | May 29, 2023 |
| Gigabyte      | H410M H                     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | [0ae3ea958a](https://linux-hardware.org/?probe=0ae3ea958a) | May 29, 2023 |
| HP            | 1497                        | [5f1886622a](https://linux-hardware.org/?probe=5f1886622a) | May 29, 2023 |
| HP            | 2B43                        | [fb2841cfa4](https://linux-hardware.org/?probe=fb2841cfa4) | May 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| ASRock        | 970 Pro3 R2.0               | [4ae997cf6b](https://linux-hardware.org/?probe=4ae997cf6b) | May 28, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [7467436de2](https://linux-hardware.org/?probe=7467436de2) | May 28, 2023 |
| HP            | 1495                        | [15b94cba50](https://linux-hardware.org/?probe=15b94cba50) | May 28, 2023 |
| ECS           | H81H3-M4                    | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Dell          | 048DY8 A01                  | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| HP            | 0B54h D                     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [dbb348e8bf](https://linux-hardware.org/?probe=dbb348e8bf) | May 28, 2023 |
| Pegatron      | 2ACB                        | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb842bc2d8](https://linux-hardware.org/?probe=bb842bc2d8) | May 28, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [ccf71ca66c](https://linux-hardware.org/?probe=ccf71ca66c) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [1a3a921775](https://linux-hardware.org/?probe=1a3a921775) | May 27, 2023 |
| MSI           | A55M-E33                    | [c25cb7cbb6](https://linux-hardware.org/?probe=c25cb7cbb6) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| Lenovo        | 31900058 STD                | [d09ae4f1a2](https://linux-hardware.org/?probe=d09ae4f1a2) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b82f4b77f4](https://linux-hardware.org/?probe=b82f4b77f4) | May 26, 2023 |
| ASUSTek       | X99-DELUXE                  | [ebc73bb225](https://linux-hardware.org/?probe=ebc73bb225) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| ASUSTek       | Z77-A                       | [0c22362cc0](https://linux-hardware.org/?probe=0c22362cc0) | May 26, 2023 |
| Dell          | 0XCR8D A03                  | [25867f7c36](https://linux-hardware.org/?probe=25867f7c36) | May 26, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Gigabyte      | P43-ES3G                    | [b9af05a16f](https://linux-hardware.org/?probe=b9af05a16f) | May 25, 2023 |
| ASUSTek       | M4A78LT-M                   | [7080c87654](https://linux-hardware.org/?probe=7080c87654) | May 25, 2023 |
| PCWare        | IPMH110G                    | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| ASUSTek       | F2A85-V                     | [c166f91030](https://linux-hardware.org/?probe=c166f91030) | May 25, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [6e9287cc5c](https://linux-hardware.org/?probe=6e9287cc5c) | May 25, 2023 |
| Dell          | 0654JC A01                  | [d3a2957b45](https://linux-hardware.org/?probe=d3a2957b45) | May 24, 2023 |
| AZW           | SEi                         | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| EPSON DIRE... | MR7200E-L                   | [a436b49a11](https://linux-hardware.org/?probe=a436b49a11) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| AZW           | SEi                         | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Gigabyte      | H77N-WIFI                   | [9e96bcdbef](https://linux-hardware.org/?probe=9e96bcdbef) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| Medion        | H110H4-EM                   | [218e19be02](https://linux-hardware.org/?probe=218e19be02) | May 23, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| Dell          | 0JC6JH A00                  | [91d6d0d2da](https://linux-hardware.org/?probe=91d6d0d2da) | May 23, 2023 |
| Pegatron      | 2ACB                        | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| Gigabyte      | B75M-D3H                    | [00a6f60d75](https://linux-hardware.org/?probe=00a6f60d75) | May 23, 2023 |
| ASRock        | X399 Professional Gaming    | [72cd126fc6](https://linux-hardware.org/?probe=72cd126fc6) | May 23, 2023 |
| HP            | 0AECh D                     | [06f56df636](https://linux-hardware.org/?probe=06f56df636) | May 23, 2023 |
| eMachines     | EL1360                      | [0821a0d29b](https://linux-hardware.org/?probe=0821a0d29b) | May 22, 2023 |
| Biostar       | A880GZ                      | [097e118b3a](https://linux-hardware.org/?probe=097e118b3a) | May 22, 2023 |
| HP            | 1791                        | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | [59ede76205](https://linux-hardware.org/?probe=59ede76205) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | [a5c1b4eecd](https://linux-hardware.org/?probe=a5c1b4eecd) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| ASUSTek       | F2A85-V PRO                 | [dc846ba2e5](https://linux-hardware.org/?probe=dc846ba2e5) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| MSI           | Z87-G43                     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| Gigabyte      | B550M DS3H                  | [7db2aa27dc](https://linux-hardware.org/?probe=7db2aa27dc) | May 21, 2023 |
| Dell          | 033FF6 A00                  | [086dd9367e](https://linux-hardware.org/?probe=086dd9367e) | May 21, 2023 |
| Gigabyte      | B450M S2H                   | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| ASUSTek       | P8B75-M                     | [313fb9c88a](https://linux-hardware.org/?probe=313fb9c88a) | May 21, 2023 |
| Gigabyte      | Z390 UD                     | [867806192a](https://linux-hardware.org/?probe=867806192a) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [62b86acadc](https://linux-hardware.org/?probe=62b86acadc) | May 21, 2023 |
| Dell          | 0VNP2H A00                  | [298317e388](https://linux-hardware.org/?probe=298317e388) | May 21, 2023 |
| ASUSTek       | P8Z68-V LX                  | [27c48503ad](https://linux-hardware.org/?probe=27c48503ad) | May 21, 2023 |
| Unknown       | GSUO H61V10C                | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | [a547a22c01](https://linux-hardware.org/?probe=a547a22c01) | May 20, 2023 |
| Medion        | BTDD-LT                     | [3b5eac782c](https://linux-hardware.org/?probe=3b5eac782c) | May 20, 2023 |
| MSI           | H97M-G43                    | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Dell          | 0JP3NX A01                  | [a4a766a9e1](https://linux-hardware.org/?probe=a4a766a9e1) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [6f6b65d0ed](https://linux-hardware.org/?probe=6f6b65d0ed) | May 19, 2023 |
| Pegatron      | Benicia                     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| Gigabyte      | B360M DS3H                  | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Acer          | TDPS05                      | [ed5384ee4d](https://linux-hardware.org/?probe=ed5384ee4d) | May 19, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [665ac2defe](https://linux-hardware.org/?probe=665ac2defe) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | [b208edbf01](https://linux-hardware.org/?probe=b208edbf01) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | [c90642a42c](https://linux-hardware.org/?probe=c90642a42c) | May 19, 2023 |
| ASUSTek       | PRIME H410M-R               | [09cc939f04](https://linux-hardware.org/?probe=09cc939f04) | May 19, 2023 |
| Gigabyte      | H310M S2                    | [61f60c8a7d](https://linux-hardware.org/?probe=61f60c8a7d) | May 19, 2023 |
| Gigabyte      | B460M DS3H V2               | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| Dell          | 0MGK50 A02                  | [7b98244b73](https://linux-hardware.org/?probe=7b98244b73) | May 19, 2023 |
| Pegatron      | Benicia                     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASRock        | B365M Pro4                  | [0df5d6f44e](https://linux-hardware.org/?probe=0df5d6f44e) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| MSI           | Z97-G55 SLI                 | [a17ed55b13](https://linux-hardware.org/?probe=a17ed55b13) | May 19, 2023 |
| Dell          | 0D881F A06                  | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [75ca7ed17e](https://linux-hardware.org/?probe=75ca7ed17e) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [839536ab43](https://linux-hardware.org/?probe=839536ab43) | May 18, 2023 |
| MSI           | Z97-G55 SLI                 | [0883ceb18c](https://linux-hardware.org/?probe=0883ceb18c) | May 18, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [afd85b3621](https://linux-hardware.org/?probe=afd85b3621) | May 18, 2023 |
| Dell          | 0VRWRC A00                  | [c7f7f8758b](https://linux-hardware.org/?probe=c7f7f8758b) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| ASUSTek       | PRIME B560M-A               | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| Gigabyte      | H310M S2                    | [b8a04e73b8](https://linux-hardware.org/?probe=b8a04e73b8) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| Dell          | 0VNP2H A00                  | [85da02478a](https://linux-hardware.org/?probe=85da02478a) | May 17, 2023 |
| Dell          | 0RY007                      | [c2b8174064](https://linux-hardware.org/?probe=c2b8174064) | May 17, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [ad477b9698](https://linux-hardware.org/?probe=ad477b9698) | May 17, 2023 |
| ASUSTek       | H81M-A/BR                   | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | [d17610915a](https://linux-hardware.org/?probe=d17610915a) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| ASRock        | Z97 Professional            | [7d0ecd3359](https://linux-hardware.org/?probe=7d0ecd3359) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [fed1ba2b90](https://linux-hardware.org/?probe=fed1ba2b90) | May 17, 2023 |
| ASUSTek       | P5E WS Pro                  | [97a221407d](https://linux-hardware.org/?probe=97a221407d) | May 17, 2023 |
| Acer          | TDPS05                      | [2cfc303d36](https://linux-hardware.org/?probe=2cfc303d36) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [b0710623f7](https://linux-hardware.org/?probe=b0710623f7) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | [777f8ccab0](https://linux-hardware.org/?probe=777f8ccab0) | May 17, 2023 |
| ZOTAC         | Unknown                     | [5ae0ed6f5a](https://linux-hardware.org/?probe=5ae0ed6f5a) | May 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [c7c487333a](https://linux-hardware.org/?probe=c7c487333a) | May 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [afbef25815](https://linux-hardware.org/?probe=afbef25815) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | [b77555d36f](https://linux-hardware.org/?probe=b77555d36f) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| ASUSTek       | X99-DELUXE                  | [d2fbc01926](https://linux-hardware.org/?probe=d2fbc01926) | May 15, 2023 |
| Supermicro    | H12DSU-iN                   | [05b2b86f35](https://linux-hardware.org/?probe=05b2b86f35) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Fujitsu       | JIB75Y3                     | [31146fe86e](https://linux-hardware.org/?probe=31146fe86e) | May 15, 2023 |
| MSI           | Z87-G45 GAMING              | [06e1ef84b3](https://linux-hardware.org/?probe=06e1ef84b3) | May 15, 2023 |
| ASUSTek       | F2A85-V PRO                 | [b21029ef65](https://linux-hardware.org/?probe=b21029ef65) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6e8f0dd2b9](https://linux-hardware.org/?probe=6e8f0dd2b9) | May 15, 2023 |
| Dell          | 0N4YC8 A00                  | [61eeca9cec](https://linux-hardware.org/?probe=61eeca9cec) | May 15, 2023 |
| Dell          | 0J3C2F A00                  | [17b9d54da0](https://linux-hardware.org/?probe=17b9d54da0) | May 15, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | [6e21010553](https://linux-hardware.org/?probe=6e21010553) | May 15, 2023 |
| HP            | 0B4Ch D                     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [94d901f023](https://linux-hardware.org/?probe=94d901f023) | May 14, 2023 |
| Pegatron      | IPXSB-H61                   | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| Pegatron      | 2AC2                        | [510047e597](https://linux-hardware.org/?probe=510047e597) | May 14, 2023 |
| Lenovo        | Dory CRB                    | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| eMachines     | EL1360                      | [74745ea02b](https://linux-hardware.org/?probe=74745ea02b) | May 14, 2023 |
| Biostar       | N61PB-M2S                   | [4ac75a003b](https://linux-hardware.org/?probe=4ac75a003b) | May 14, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | [f35c753afd](https://linux-hardware.org/?probe=f35c753afd) | May 14, 2023 |
| Pegatron      | 2AB5                        | [2381fb0c55](https://linux-hardware.org/?probe=2381fb0c55) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | [65ad7c5ad5](https://linux-hardware.org/?probe=65ad7c5ad5) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| MSI           | A68HM-E33 V2                | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| Gateway       | DX4840                      | [b96adf8863](https://linux-hardware.org/?probe=b96adf8863) | May 13, 2023 |
| Intel         | B75                         | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Toshiba       | STI 007567                  | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Dell          | 0NC2VH A01                  | [48c5ff757c](https://linux-hardware.org/?probe=48c5ff757c) | May 13, 2023 |
| ASUSTek       | M5A78L-M LX                 | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [62aab97f35](https://linux-hardware.org/?probe=62aab97f35) | May 12, 2023 |
| ASUSTek       | X99-DELUXE                  | [2acd6e02ea](https://linux-hardware.org/?probe=2acd6e02ea) | May 12, 2023 |
| ASRock        | H510M-ITX/ac                | [9a8da03c1e](https://linux-hardware.org/?probe=9a8da03c1e) | May 12, 2023 |
| Medion        | BTDD-LT                     | [86a5697c9c](https://linux-hardware.org/?probe=86a5697c9c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [01b1668378](https://linux-hardware.org/?probe=01b1668378) | May 12, 2023 |
| Biostar       | A68N-5600E                  | [55db0c720e](https://linux-hardware.org/?probe=55db0c720e) | May 12, 2023 |
| Intel         | DH87RL AAG74240-403         | [888f0a2923](https://linux-hardware.org/?probe=888f0a2923) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [40d2790e0a](https://linux-hardware.org/?probe=40d2790e0a) | May 12, 2023 |
| ASUSTek       | P8P67 LE                    | [cae9bea146](https://linux-hardware.org/?probe=cae9bea146) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Biostar       | B450MH                      | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| ZOTAC         | Unknown                     | [9495c6ca84](https://linux-hardware.org/?probe=9495c6ca84) | May 11, 2023 |
| Biostar       | B450MH                      | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Gigabyte      | Z270N-Gaming 5              | [c056fdd9a8](https://linux-hardware.org/?probe=c056fdd9a8) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Dell          | 0T10XW A02                  | [a488bed661](https://linux-hardware.org/?probe=a488bed661) | May 11, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [53d9e318f6](https://linux-hardware.org/?probe=53d9e318f6) | May 11, 2023 |
| Biostar       | H110MHV3                    | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3df5f7ec7e](https://linux-hardware.org/?probe=3df5f7ec7e) | May 11, 2023 |
| Dell          | 0Y958C A00                  | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [1b20151b4c](https://linux-hardware.org/?probe=1b20151b4c) | May 10, 2023 |
| Dell          | 076VHM A02                  | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [554b258b3c](https://linux-hardware.org/?probe=554b258b3c) | May 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| Dell          | 0GM819                      | [ccd99ab6c3](https://linux-hardware.org/?probe=ccd99ab6c3) | May 10, 2023 |
| ASUSTek       | P8Z68-M PRO                 | [37b88384a5](https://linux-hardware.org/?probe=37b88384a5) | May 10, 2023 |
| AZW           | MINI S 10                   | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [02c4a35621](https://linux-hardware.org/?probe=02c4a35621) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [a9df4bc7fb](https://linux-hardware.org/?probe=a9df4bc7fb) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6fd3dea188](https://linux-hardware.org/?probe=6fd3dea188) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [e55b8813e3](https://linux-hardware.org/?probe=e55b8813e3) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | H170-PRO                    | [8f41b17a9b](https://linux-hardware.org/?probe=8f41b17a9b) | May 10, 2023 |
| ASUSTek       | X99-DELUXE II               | [966821ec0d](https://linux-hardware.org/?probe=966821ec0d) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| Dell          | 0D883F A06                  | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| Intel         | DQ57TM AAE70931-402         | [df02c1cce7](https://linux-hardware.org/?probe=df02c1cce7) | May 09, 2023 |
| HP            | 18E5                        | [09eb27d0c5](https://linux-hardware.org/?probe=09eb27d0c5) | May 09, 2023 |
| Dell          | 0KC9NP A01                  | [575bffc7a9](https://linux-hardware.org/?probe=575bffc7a9) | May 09, 2023 |
| HP            | 3398                        | [360aa1ac89](https://linux-hardware.org/?probe=360aa1ac89) | May 09, 2023 |
| Lenovo        | Dory CRB                    | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [58a9b45939](https://linux-hardware.org/?probe=58a9b45939) | May 09, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [bcccbb24de](https://linux-hardware.org/?probe=bcccbb24de) | May 09, 2023 |
| Dell          | 0KYJ8C A02                  | [ce4726c253](https://linux-hardware.org/?probe=ce4726c253) | May 09, 2023 |
| Lenovo        | ThinkCentre M71z 1782W14    | [f5a1b23281](https://linux-hardware.org/?probe=f5a1b23281) | May 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 290      | 6.85%   |
| 5.15.0-52-generic | 250      | 5.91%   |
| 5.15.0-58-generic | 243      | 5.74%   |
| 5.19.0-35-generic | 211      | 4.98%   |
| 5.15.0-48-generic | 202      | 4.77%   |
| 5.15.0-47-generic | 196      | 4.63%   |
| 5.15.0-43-generic | 192      | 4.54%   |
| 5.19.0-32-generic | 180      | 4.25%   |
| 5.19.0-41-generic | 165      | 3.9%    |
| 5.19.0-46-generic | 150      | 3.54%   |
| 5.15.0-53-generic | 150      | 3.54%   |
| 5.19.0-38-generic | 145      | 3.43%   |
| 5.15.0-46-generic | 137      | 3.24%   |
| 5.15.0-25-generic | 111      | 2.62%   |
| 5.19.0-43-generic | 104      | 2.46%   |
| 5.15.0-27-generic | 102      | 2.41%   |
| 5.15.0-60-generic | 95       | 2.24%   |
| 5.15.0-41-generic | 93       | 2.2%    |
| 5.15.0-40-generic | 91       | 2.15%   |
| 5.15.0-57-generic | 83       | 1.96%   |
| 5.15.0-50-generic | 80       | 1.89%   |
| 5.19.0-45-generic | 73       | 1.72%   |
| 5.19.0-40-generic | 68       | 1.61%   |
| 5.15.0-67-generic | 63       | 1.49%   |
| 5.15.0-33-generic | 60       | 1.42%   |
| 5.15.0-30-generic | 53       | 1.25%   |
| 5.19.0-42-generic | 48       | 1.13%   |
| 5.19.0-50-generic | 47       | 1.11%   |
| 5.15.0-39-generic | 46       | 1.09%   |
| 5.15.0-69-generic | 45       | 1.06%   |
| 5.15.0-35-generic | 44       | 1.04%   |
| 6.2.0-26-generic  | 43       | 1.02%   |
| 5.15.0-37-generic | 41       | 0.97%   |
| 5.15.0-76-generic | 26       | 0.61%   |
| 5.15.0-71-generic | 26       | 0.61%   |
| 5.15.0-78-generic | 18       | 0.43%   |
| 5.15.0-73-generic | 17       | 0.4%    |
| 5.15.0-72-generic | 14       | 0.33%   |
| 5.15.0-75-generic | 12       | 0.28%   |
| 5.15.0-23-generic | 12       | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2570     | 67.28%  |
| 5.19.0  | 1088     | 28.48%  |
| 6.2.0   | 45       | 1.18%   |
| 5.17.0  | 19       | 0.5%    |
| 5.13.0  | 15       | 0.39%   |
| 6.1.0   | 7        | 0.18%   |
| 6.0.0   | 5        | 0.13%   |
| 5.18.0  | 5        | 0.13%   |
| 6.0.1   | 3        | 0.08%   |
| 5.19.5  | 3        | 0.08%   |
| 5.18.10 | 3        | 0.08%   |
| 5.10.60 | 3        | 0.08%   |
| 6.4.3   | 2        | 0.05%   |
| 6.4.0   | 2        | 0.05%   |
| 6.2.11  | 2        | 0.05%   |
| 6.1.11  | 2        | 0.05%   |
| 6.0.9   | 2        | 0.05%   |
| 5.8.0   | 2        | 0.05%   |
| 5.19.17 | 2        | 0.05%   |
| 5.17.9  | 2        | 0.05%   |
| 5.17.15 | 2        | 0.05%   |
| 5.15.13 | 2        | 0.05%   |
| 5.14.0  | 2        | 0.05%   |
| 6.3.7   | 1        | 0.03%   |
| 6.3.4   | 1        | 0.03%   |
| 6.3.2   | 1        | 0.03%   |
| 6.2.9   | 1        | 0.03%   |
| 6.2.6   | 1        | 0.03%   |
| 6.2.3   | 1        | 0.03%   |
| 6.2.16  | 1        | 0.03%   |
| 6.2.10  | 1        | 0.03%   |
| 6.2.1   | 1        | 0.03%   |
| 6.1.8   | 1        | 0.03%   |
| 6.1.6   | 1        | 0.03%   |
| 6.1.4   | 1        | 0.03%   |
| 6.1.32  | 1        | 0.03%   |
| 6.1.10  | 1        | 0.03%   |
| 6.0.8   | 1        | 0.03%   |
| 6.0.3   | 1        | 0.03%   |
| 5.4.0   | 1        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2572     | 67.37%  |
| 5.19    | 1094     | 28.65%  |
| 6.2     | 53       | 1.39%   |
| 5.17    | 28       | 0.73%   |
| 5.13    | 15       | 0.39%   |
| 6.1     | 14       | 0.37%   |
| 5.18    | 13       | 0.34%   |
| 6.0     | 12       | 0.31%   |
| 6.4     | 4        | 0.1%    |
| 6.3     | 3        | 0.08%   |
| 5.10    | 3        | 0.08%   |
| 5.8     | 2        | 0.05%   |
| 5.14    | 2        | 0.05%   |
| 5.4     | 1        | 0.03%   |
| 5.16    | 1        | 0.03%   |
| 5.11    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3697     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3368     | 91%     |
| Unknown         | 196      | 5.3%    |
| GNUstep         | 66       | 1.78%   |
| X-Cinnamon      | 39       | 1.05%   |
| GNOME Flashback | 14       | 0.38%   |
| GNOME Classic   | 9        | 0.24%   |
| i3              | 4        | 0.11%   |
| ubuntu=GNOME    | 1        | 0.03%   |
| ubuntu          | 1        | 0.03%   |
| INPT            | 1        | 0.03%   |
| i3-with-shmlog  | 1        | 0.03%   |
| awesome         | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2011     | 53.34%  |
| X11     | 1453     | 38.54%  |
| Tty     | 214      | 5.68%   |
| Unknown | 91       | 2.41%   |
| Web     | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 3227     | 87.05%  |
| Unknown | 327      | 8.82%   |
| LightDM | 119      | 3.21%   |
| GDM     | 16       | 0.43%   |
| SDDM    | 13       | 0.35%   |
| SLiM    | 4        | 0.11%   |
| LXDM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1637     | 44.15%  |
| de_DE   | 357      | 9.63%   |
| fr_FR   | 240      | 6.47%   |
| en_GB   | 181      | 4.88%   |
| pt_BR   | 143      | 3.86%   |
| it_IT   | 119      | 3.21%   |
| en_CA   | 108      | 2.91%   |
| ru_RU   | 94       | 2.54%   |
| es_ES   | 78       | 2.1%    |
| en_AU   | 70       | 1.89%   |
| en_IN   | 57       | 1.54%   |
| C       | 50       | 1.35%   |
| pl_PL   | 48       | 1.29%   |
| nl_NL   | 37       | 1%      |
| Unknown | 34       | 0.92%   |
| cs_CZ   | 33       | 0.89%   |
| ja_JP   | 31       | 0.84%   |
| de_AT   | 29       | 0.78%   |
| es_MX   | 26       | 0.7%    |
| es_AR   | 24       | 0.65%   |
| sv_SE   | 22       | 0.59%   |
| zh_CN   | 21       | 0.57%   |
| fi_FI   | 17       | 0.46%   |
| en_ZA   | 17       | 0.46%   |
| hu_HU   | 16       | 0.43%   |
| pt_PT   | 14       | 0.38%   |
| fr_BE   | 13       | 0.35%   |
| el_GR   | 13       | 0.35%   |
| en_NZ   | 11       | 0.3%    |
| tr_TR   | 10       | 0.27%   |
| nl_BE   | 10       | 0.27%   |
| en_PH   | 10       | 0.27%   |
| de_CH   | 10       | 0.27%   |
| ko_KR   | 8        | 0.22%   |
| fr_CA   | 8        | 0.22%   |
| es_CO   | 8        | 0.22%   |
| sk_SK   | 7        | 0.19%   |
| zh_TW   | 5        | 0.13%   |
| nb_NO   | 5        | 0.13%   |
| es_VE   | 5        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2575     | 68.98%  |
| EFI  | 1158     | 31.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 3067     | 80.88%  |
| Tmpfs         | 457      | 12.05%  |
| Overlay       | 111      | 2.93%   |
| Zfs           | 80       | 2.11%   |
| Btrfs         | 40       | 1.05%   |
| Xfs           | 22       | 0.58%   |
| Ext2          | 7        | 0.18%   |
| Unknown       | 4        | 0.11%   |
| XXXX          | 1        | 0.03%   |
| Jfs           | 1        | 0.03%   |
| Fuse.snapfuse | 1        | 0.03%   |
| Ext3          | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 2520     | 65.83%  |
| Unknown | 912      | 23.82%  |
| MBR     | 396      | 10.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3080     | 82.18%  |
| Yes       | 668      | 17.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2150     | 57.52%  |
| Yes       | 1588     | 42.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 936      | 25.32%  |
| Gigabyte Technology                  | 548      | 14.82%  |
| MSI                                  | 442      | 11.96%  |
| Dell                                 | 398      | 10.77%  |
| Hewlett-Packard                      | 282      | 7.63%   |
| ASRock                               | 280      | 7.57%   |
| Lenovo                               | 152      | 4.11%   |
| Intel                                | 105      | 2.84%   |
| Acer                                 | 70       | 1.89%   |
| Fujitsu                              | 61       | 1.65%   |
| Unknown                              | 50       | 1.35%   |
| Pegatron                             | 33       | 0.89%   |
| Medion                               | 30       | 0.81%   |
| Foxconn                              | 28       | 0.76%   |
| Biostar                              | 27       | 0.73%   |
| ECS                                  | 20       | 0.54%   |
| Apple                                | 19       | 0.51%   |
| Supermicro                           | 18       | 0.49%   |
| Shuttle                              | 17       | 0.46%   |
| Alienware                            | 16       | 0.43%   |
| AZW                                  | 12       | 0.32%   |
| Huanan                               | 11       | 0.3%    |
| Gateway                              | 9        | 0.24%   |
| Positivo                             | 8        | 0.22%   |
| Packard Bell                         | 8        | 0.22%   |
| BESSTAR Tech                         | 8        | 0.22%   |
| ASRockRack                           | 6        | 0.16%   |
| OEM                                  | 5        | 0.14%   |
| eMachines                            | 5        | 0.14%   |
| AMI                                  | 4        | 0.11%   |
| YANYU                                | 3        | 0.08%   |
| Wistron                              | 3        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.08%   |
| PCWare                               | 3        | 0.08%   |
| Google                               | 3        | 0.08%   |
| Fujitsu Siemens                      | 3        | 0.08%   |
| ZOTAC                                | 2        | 0.05%   |
| System76                             | 2        | 0.05%   |
| Protectli                            | 2        | 0.05%   |
| NCR                                  | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 92       | 2.49%   |
| Unknown                         | 56       | 1.51%   |
| Dell OptiPlex 7010              | 31       | 0.84%   |
| Dell OptiPlex 9020              | 26       | 0.7%    |
| ASUS PRIME A320M-K              | 25       | 0.68%   |
| ASUS TUF Gaming X570-PLUS       | 23       | 0.62%   |
| MSI MS-7C37                     | 19       | 0.51%   |
| MSI MS-7721                     | 19       | 0.51%   |
| Dell OptiPlex 3020              | 19       | 0.51%   |
| ASUS PRIME Z590-P               | 18       | 0.49%   |
| Dell OptiPlex 790               | 16       | 0.43%   |
| MSI MS-7C91                     | 15       | 0.41%   |
| ASUS ROG STRIX B550-F GAMING    | 15       | 0.41%   |
| Dell OptiPlex 3050              | 14       | 0.38%   |
| ASUS PRIME X570-PRO             | 14       | 0.38%   |
| ASUS PRIME B550M-A              | 14       | 0.38%   |
| HP Compaq 8200 Elite SFF PC     | 13       | 0.35%   |
| Dell OptiPlex 7050              | 12       | 0.32%   |
| ASRock B450M Pro4               | 12       | 0.32%   |
| MSI MS-7C52                     | 11       | 0.3%    |
| Dell OptiPlex 990               | 11       | 0.3%    |
| ASUS M5A78L-M/USB3              | 11       | 0.3%    |
| MSI MS-7C56                     | 10       | 0.27%   |
| MSI MS-7C02                     | 10       | 0.27%   |
| MSI MS-7B79                     | 10       | 0.27%   |
| Intel H61                       | 10       | 0.27%   |
| HP ProDesk 600 G1 SFF           | 10       | 0.27%   |
| Gigabyte B450M DS3H             | 10       | 0.27%   |
| Dell OptiPlex 780               | 10       | 0.27%   |
| Dell OptiPlex 7040              | 10       | 0.27%   |
| MSI MS-7B86                     | 9        | 0.24%   |
| MSI MS-7817                     | 9        | 0.24%   |
| MSI MS-7693                     | 9        | 0.24%   |
| Gigabyte A320M-S2H              | 9        | 0.24%   |
| ASUS ROG STRIX B450-F GAMING    | 9        | 0.24%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI | 9        | 0.24%   |
| ASUS H110M-A                    | 9        | 0.24%   |
| ASRock A320M-HDV R4.0           | 9        | 0.24%   |
| HP EliteDesk 800 G1 SFF         | 8        | 0.22%   |
| HP Compaq Pro 6300 SFF          | 8        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 247      | 6.68%   |
| ASUS PRIME          | 214      | 5.79%   |
| ASUS ROG            | 124      | 3.35%   |
| ASUS All            | 92       | 2.49%   |
| ASUS TUF            | 91       | 2.46%   |
| HP Compaq           | 90       | 2.43%   |
| Lenovo ThinkCentre  | 79       | 2.14%   |
| Dell Precision      | 61       | 1.65%   |
| Unknown             | 56       | 1.51%   |
| HP EliteDesk        | 44       | 1.19%   |
| Acer Aspire         | 44       | 1.19%   |
| Dell Inspiron       | 40       | 1.08%   |
| Fujitsu ESPRIMO     | 35       | 0.95%   |
| HP ProDesk          | 34       | 0.92%   |
| Lenovo ThinkStation | 24       | 0.65%   |
| Gigabyte B450M      | 23       | 0.62%   |
| ASUS M5A78L-M       | 22       | 0.6%    |
| Gigabyte X570       | 21       | 0.57%   |
| Gigabyte Z390       | 20       | 0.54%   |
| MSI MS-7C37         | 19       | 0.51%   |
| MSI MS-7721         | 19       | 0.51%   |
| Lenovo IdeaCentre   | 19       | 0.51%   |
| Fujitsu CELSIUS     | 19       | 0.51%   |
| Dell XPS            | 19       | 0.51%   |
| ASUS M5A97          | 18       | 0.49%   |
| ASRock B450M        | 18       | 0.49%   |
| Gigabyte B550M      | 17       | 0.46%   |
| Gigabyte B450       | 16       | 0.43%   |
| ASUS P8H61-M        | 16       | 0.43%   |
| MSI MS-7C91         | 15       | 0.41%   |
| Gigabyte B550       | 15       | 0.41%   |
| ASUS Pro            | 15       | 0.41%   |
| Dell Vostro         | 14       | 0.38%   |
| ASUS CROSSHAIR      | 14       | 0.38%   |
| HP Pavilion         | 12       | 0.32%   |
| ASRock X570         | 12       | 0.32%   |
| Acer Veriton        | 12       | 0.32%   |
| MSI MS-7C52         | 11       | 0.3%    |
| HP ProLiant         | 11       | 0.3%    |
| Gigabyte A320M-S2H  | 11       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 341      | 9.22%   |
| 2013    | 327      | 8.85%   |
| 2012    | 315      | 8.52%   |
| 2021    | 291      | 7.87%   |
| 2020    | 291      | 7.87%   |
| 2019    | 271      | 7.33%   |
| 2011    | 269      | 7.28%   |
| 2014    | 254      | 6.87%   |
| 2017    | 232      | 6.28%   |
| 2015    | 213      | 5.76%   |
| 2022    | 184      | 4.98%   |
| 2010    | 179      | 4.84%   |
| 2009    | 151      | 4.08%   |
| 2016    | 141      | 3.81%   |
| 2008    | 107      | 2.89%   |
| 2007    | 67       | 1.81%   |
| 2023    | 32       | 0.87%   |
| 2006    | 21       | 0.57%   |
| 2005    | 6        | 0.16%   |
| Unknown | 5        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3697     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3570     | 96.38%  |
| Enabled  | 134      | 3.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3691     | 99.84%  |
| Yes  | 6        | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 968      | 25.91%  |
| 32.01-64.0      | 643      | 17.21%  |
| 8.01-16.0       | 627      | 16.78%  |
| 4.01-8.0        | 607      | 16.25%  |
| 3.01-4.0        | 424      | 11.35%  |
| 64.01-256.0     | 277      | 7.41%   |
| 24.01-32.0      | 107      | 2.86%   |
| 1.01-2.0        | 45       | 1.2%    |
| 2.01-3.0        | 20       | 0.54%   |
| More than 256.0 | 16       | 0.43%   |
| 0.51-1.0        | 2        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1230     | 31.1%   |
| 2.01-3.0    | 1197     | 30.27%  |
| 4.01-8.0    | 606      | 15.32%  |
| 3.01-4.0    | 565      | 14.29%  |
| 8.01-16.0   | 202      | 5.11%   |
| 0.51-1.0    | 80       | 2.02%   |
| 16.01-24.0  | 33       | 0.83%   |
| 0.01-0.5    | 15       | 0.38%   |
| 24.01-32.0  | 14       | 0.35%   |
| 32.01-64.0  | 12       | 0.3%    |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1514     | 39.88%  |
| 2      | 1116     | 29.4%   |
| 3      | 560      | 14.75%  |
| 4      | 277      | 7.3%    |
| 5      | 134      | 3.53%   |
| 6      | 65       | 1.71%   |
| 0      | 44       | 1.16%   |
| 7      | 34       | 0.9%    |
| 8      | 15       | 0.4%    |
| 9      | 13       | 0.34%   |
| 11     | 6        | 0.16%   |
| 10     | 6        | 0.16%   |
| 13     | 3        | 0.08%   |
| 12     | 3        | 0.08%   |
| 25     | 2        | 0.05%   |
| 38     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 17     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2085     | 56%     |
| Yes       | 1638     | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3665     | 99.11%  |
| No        | 33       | 0.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2047     | 54.95%  |
| Yes       | 1678     | 45.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2517     | 67.55%  |
| Yes       | 1209     | 32.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 813      | 21.96%  |
| Germany      | 424      | 11.45%  |
| France       | 259      | 7%      |
| Brazil       | 200      | 5.4%    |
| UK           | 176      | 4.75%   |
| Russia       | 143      | 3.86%   |
| Canada       | 142      | 3.84%   |
| Italy        | 140      | 3.78%   |
| Switzerland  | 133      | 3.59%   |
| Spain        | 87       | 2.35%   |
| Australia    | 79       | 2.13%   |
| Netherlands  | 70       | 1.89%   |
| Poland       | 64       | 1.73%   |
| India        | 62       | 1.67%   |
| Austria      | 52       | 1.4%    |
| Sweden       | 44       | 1.19%   |
| Mexico       | 43       | 1.16%   |
| Japan        | 40       | 1.08%   |
| Belgium      | 40       | 1.08%   |
| Argentina    | 40       | 1.08%   |
| Czechia      | 39       | 1.05%   |
| Finland      | 38       | 1.03%   |
| Greece       | 32       | 0.86%   |
| Hungary      | 25       | 0.68%   |
| Turkey       | 24       | 0.65%   |
| China        | 24       | 0.65%   |
| South Africa | 21       | 0.57%   |
| Romania      | 21       | 0.57%   |
| Bulgaria     | 20       | 0.54%   |
| Portugal     | 19       | 0.51%   |
| Slovakia     | 18       | 0.49%   |
| South Korea  | 15       | 0.41%   |
| Norway       | 14       | 0.38%   |
| Denmark      | 14       | 0.38%   |
| New Zealand  | 13       | 0.35%   |
| Serbia       | 12       | 0.32%   |
| Indonesia    | 12       | 0.32%   |
| Colombia     | 12       | 0.32%   |
| Taiwan       | 11       | 0.3%    |
| Hong Kong    | 11       | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 81       | 2.1%    |
| Berlin            | 37       | 0.96%   |
| Vienna            | 33       | 0.86%   |
| Paris             | 31       | 0.8%    |
| Moscow            | 29       | 0.75%   |
| Sydney            | 28       | 0.73%   |
| Cheboksary        | 24       | 0.62%   |
| Milan             | 23       | 0.6%    |
| Sao Paulo         | 21       | 0.54%   |
| Madrid            | 20       | 0.52%   |
| Helsinki          | 20       | 0.52%   |
| New York          | 19       | 0.49%   |
| Hamburg           | 19       | 0.49%   |
| St Petersburg     | 18       | 0.47%   |
| Rio de Janeiro    | 18       | 0.47%   |
| Lucerne           | 18       | 0.47%   |
| Athens            | 18       | 0.47%   |
| Seattle           | 17       | 0.44%   |
| Prague            | 17       | 0.44%   |
| Munich            | 16       | 0.42%   |
| San Jose          | 15       | 0.39%   |
| Toronto           | 14       | 0.36%   |
| Istanbul          | 14       | 0.36%   |
| Warsaw            | 13       | 0.34%   |
| Melbourne         | 13       | 0.34%   |
| London            | 13       | 0.34%   |
| Budapest          | 13       | 0.34%   |
| Rome              | 12       | 0.31%   |
| Manchester        | 12       | 0.31%   |
| Los Angeles       | 12       | 0.31%   |
| Dallas            | 12       | 0.31%   |
| Brisbane          | 12       | 0.31%   |
| Sofia             | 11       | 0.29%   |
| Frankfurt am Main | 11       | 0.29%   |
| Amsterdam         | 11       | 0.29%   |
| Vancouver         | 10       | 0.26%   |
| Stockholm         | 10       | 0.26%   |
| Buenos Aires      | 10       | 0.26%   |
| Bucharest         | 10       | 0.26%   |
| Bengaluru         | 10       | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1209     | 1920   | 18.55%  |
| WDC                         | 1169     | 1947   | 17.93%  |
| Samsung Electronics         | 991      | 1538   | 15.2%   |
| Kingston                    | 409      | 508    | 6.27%   |
| Toshiba                     | 316      | 414    | 4.85%   |
| SanDisk                     | 314      | 443    | 4.82%   |
| Crucial                     | 288      | 430    | 4.42%   |
| Hitachi                     | 206      | 263    | 3.16%   |
| A-DATA Technology           | 102      | 125    | 1.56%   |
| Intel                       | 93       | 108    | 1.43%   |
| China                       | 80       | 91     | 1.23%   |
| Unknown                     | 77       | 121    | 1.18%   |
| HGST                        | 70       | 105    | 1.07%   |
| SK hynix                    | 60       | 75     | 0.92%   |
| Phison Electronics          | 56       | 77     | 0.86%   |
| Intenso                     | 54       | 65     | 0.83%   |
| PNY                         | 53       | 60     | 0.81%   |
| Micron/Crucial Technology   | 50       | 68     | 0.77%   |
| Silicon Motion              | 49       | 64     | 0.75%   |
| Kingston Technology Company | 46       | 55     | 0.71%   |
| SPCC                        | 41       | 68     | 0.63%   |
| Phison                      | 35       | 48     | 0.54%   |
| Micron Technology           | 33       | 46     | 0.51%   |
| OCZ                         | 30       | 48     | 0.46%   |
| Patriot                     | 27       | 32     | 0.41%   |
| Maxtor                      | 27       | 37     | 0.41%   |
| Gigabyte Technology         | 25       | 34     | 0.38%   |
| Corsair                     | 24       | 27     | 0.37%   |
| Transcend                   | 23       | 23     | 0.35%   |
| Team                        | 22       | 33     | 0.34%   |
| Lexar                       | 22       | 23     | 0.34%   |
| Unknown                     | 22       | 25     | 0.34%   |
| ADATA Technology            | 17       | 24     | 0.26%   |
| JMicron Technology          | 16       | 17     | 0.25%   |
| Hewlett-Packard             | 16       | 47     | 0.25%   |
| ASMT                        | 16       | 28     | 0.25%   |
| Realtek Semiconductor       | 14       | 16     | 0.21%   |
| KIOXIA                      | 14       | 27     | 0.21%   |
| Apacer                      | 14       | 14     | 0.21%   |
| SABRENT                     | 13       | 17     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB                        | 98       | 1.29%   |
| Seagate ST500DM002-1BD142 500GB                       | 94       | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 94       | 1.24%   |
| Kingston SA400S37240G 240GB SSD                       | 87       | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                        | 83       | 1.1%    |
| Samsung SSD 850 EVO 250GB                             | 63       | 0.83%   |
| Samsung SSD 850 EVO 500GB                             | 61       | 0.81%   |
| Kingston SA400S37480G 480GB SSD                       | 60       | 0.79%   |
| Samsung SSD 980 PRO 1TB                               | 56       | 0.74%   |
| Samsung SSD 860 EVO 500GB                             | 56       | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB                        | 49       | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                        | 48       | 0.63%   |
| Toshiba DT01ACA100 1TB                                | 47       | 0.62%   |
| Toshiba DT01ACA050 500GB                              | 44       | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 43       | 0.57%   |
| Crucial CT500MX500SSD1 500GB                          | 43       | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB                        | 38       | 0.5%    |
| Kingston SA400S37120G 120GB SSD                       | 38       | 0.5%    |
| Crucial CT240BX500SSD1 240GB                          | 38       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                           | 36       | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 35       | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                            | 34       | 0.45%   |
| Unknown SD/MMC/MS PRO 128GB                           | 32       | 0.42%   |
| Toshiba HDWD110 1TB                                   | 32       | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 32       | 0.42%   |
| Samsung SSD 980 1TB                                   | 31       | 0.41%   |
| Samsung NVMe SSD Drive 1TB                            | 31       | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB                        | 29       | 0.38%   |
| Toshiba DT01ACA200 2TB                                | 28       | 0.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 28       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 28       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB                        | 27       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                        | 27       | 0.36%   |
| Samsung SSD 860 EVO 1TB                               | 27       | 0.36%   |
| Seagate ST3500418AS 500GB                             | 25       | 0.33%   |
| Samsung SSD 870 EVO 500GB                             | 25       | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                      | 24       | 0.32%   |
| Toshiba VT180 240GB SSD                               | 23       | 0.3%    |
| Seagate ST31000528AS 1TB                              | 23       | 0.3%    |
| Samsung SSD 870 QVO 1TB                               | 23       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1182     | 1866   | 38.61%  |
| WDC                 | 1032     | 1714   | 33.71%  |
| Toshiba             | 271      | 348    | 8.85%   |
| Hitachi             | 205      | 262    | 6.7%    |
| Samsung Electronics | 156      | 226    | 5.1%    |
| HGST                | 70       | 101    | 2.29%   |
| Unknown             | 35       | 45     | 1.14%   |
| Maxtor              | 25       | 33     | 0.82%   |
| Intenso             | 16       | 17     | 0.52%   |
| JMicron Technology  | 13       | 14     | 0.42%   |
| ASMT                | 11       | 16     | 0.36%   |
| Fujitsu             | 8        | 9      | 0.26%   |
| Apple               | 7        | 8      | 0.23%   |
| WD MediaMax         | 4        | 4      | 0.13%   |
| SABRENT             | 3        | 4      | 0.1%    |
| Hewlett-Packard     | 3        | 11     | 0.1%    |
| ASMedia             | 3        | 3      | 0.1%    |
| USB3.0              | 2        | 3      | 0.07%   |
| LaCie               | 2        | 3      | 0.07%   |
| Inateck             | 2        | 2      | 0.07%   |
| HPE                 | 2        | 3      | 0.07%   |
| External            | 2        | 2      | 0.07%   |
| RSH-339             | 1        | 1      | 0.03%   |
| QUANTUM             | 1        | 1      | 0.03%   |
| Min Yi U            | 1        | 2      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| DAS                 | 1        | 3      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 508      | 685    | 22.6%   |
| Kingston            | 339      | 422    | 15.08%  |
| Crucial             | 260      | 389    | 11.57%  |
| SanDisk             | 171      | 242    | 7.61%   |
| WDC                 | 130      | 166    | 5.78%   |
| A-DATA Technology   | 87       | 109    | 3.87%   |
| China               | 79       | 89     | 3.51%   |
| Intel               | 55       | 61     | 2.45%   |
| Toshiba             | 50       | 56     | 2.22%   |
| PNY                 | 48       | 55     | 2.14%   |
| SPCC                | 38       | 64     | 1.69%   |
| Intenso             | 30       | 39     | 1.33%   |
| OCZ                 | 28       | 34     | 1.25%   |
| Patriot             | 26       | 31     | 1.16%   |
| Transcend           | 22       | 22     | 0.98%   |
| Team                | 21       | 32     | 0.93%   |
| Micron Technology   | 21       | 33     | 0.93%   |
| SK hynix            | 19       | 25     | 0.85%   |
| Gigabyte Technology | 17       | 26     | 0.76%   |
| Lexar               | 16       | 17     | 0.71%   |
| KingSpec            | 13       | 13     | 0.58%   |
| Corsair             | 13       | 15     | 0.58%   |
| Unknown             | 13       | 14     | 0.58%   |
| Apacer              | 12       | 12     | 0.53%   |
| Hewlett-Packard     | 11       | 11     | 0.49%   |
| GOODRAM             | 11       | 17     | 0.49%   |
| LITEON              | 9        | 11     | 0.4%    |
| LITEONIT            | 8        | 8      | 0.36%   |
| Emtec               | 7        | 7      | 0.31%   |
| Seagate             | 6        | 8      | 0.27%   |
| Netac               | 6        | 7      | 0.27%   |
| Fanxiang            | 6        | 9      | 0.27%   |
| Dogfish             | 6        | 10     | 0.27%   |
| ASMT                | 6        | 12     | 0.27%   |
| Plextor             | 5        | 5      | 0.22%   |
| Mushkin             | 5        | 5      | 0.22%   |
| Leven               | 5        | 8      | 0.22%   |
| FORESEE             | 5        | 5      | 0.22%   |
| MidasForce          | 4        | 4      | 0.18%   |
| LDLC                | 4        | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2376     | 4704   | 42.87%  |
| SSD     | 1912     | 2926   | 34.5%   |
| NVMe    | 1101     | 1676   | 19.87%  |
| Unknown | 130      | 222    | 2.35%   |
| MMC     | 23       | 32     | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3215     | 7358   | 69.39%  |
| NVMe | 1093     | 1660   | 23.59%  |
| SAS  | 302      | 510    | 6.52%   |
| MMC  | 23       | 32     | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2237     | 3627   | 47.55%  |
| 0.51-1.0   | 1355     | 2108   | 28.8%   |
| 1.01-2.0   | 571      | 872    | 12.14%  |
| 3.01-4.0   | 232      | 365    | 4.93%   |
| 4.01-10.0  | 145      | 358    | 3.08%   |
| 2.01-3.0   | 119      | 173    | 2.53%   |
| 10.01-20.0 | 45       | 126    | 0.96%   |
| 0          | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 923      | 24.04%  |
| 251-500        | 721      | 18.78%  |
| 501-1000       | 699      | 18.2%   |
| 1001-2000      | 450      | 11.72%  |
| More than 3000 | 377      | 9.82%   |
| 2001-3000      | 193      | 5.03%   |
| 51-100         | 180      | 4.69%   |
| 1-20           | 150      | 3.91%   |
| Unknown        | 75       | 1.95%   |
| 21-50          | 72       | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1230     | 31.26%  |
| 21-50          | 718      | 18.25%  |
| 101-250        | 468      | 11.89%  |
| 51-100         | 463      | 11.77%  |
| 251-500        | 320      | 8.13%   |
| 501-1000       | 267      | 6.79%   |
| 1001-2000      | 163      | 4.14%   |
| More than 3000 | 160      | 4.07%   |
| Unknown        | 75       | 1.91%   |
| 2001-3000      | 70       | 1.78%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB              | 8        | 10     | 2.39%   |
| Seagate ST500DM002-1BD142 500GB       | 6        | 6      | 1.79%   |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 5      | 1.19%   |
| SanDisk SSD PLUS 480GB                | 4        | 4      | 1.19%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3        | 3      | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 4      | 0.9%    |
| Toshiba DT01ACA050 500GB              | 3        | 3      | 0.9%    |
| Seagate ST3500418AS 500GB             | 3        | 4      | 0.9%    |
| Seagate ST3250310AS 250GB             | 3        | 3      | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB        | 3        | 3      | 0.9%    |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.9%    |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.9%    |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.9%    |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2        | 4      | 0.6%    |
| WDC WD30EZRX-00MMMB0 3TB              | 2        | 6      | 0.6%    |
| WDC WD10EZEX-60ZF5A0 1TB              | 2        | 2      | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.6%    |
| WDC WD10EZEX-21WN4A0 1TB              | 2        | 2      | 0.6%    |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.6%    |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.6%    |
| Seagate ST3750528AS 752GB             | 2        | 2      | 0.6%    |
| Seagate ST3320620AS 320GB             | 2        | 2      | 0.6%    |
| Seagate ST31000528AS 1TB              | 2        | 2      | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.6%    |
| Seagate ST1000DX001-1CM162 1TB        | 2        | 2      | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.6%    |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.6%    |
| SanDisk SSD PLUS 1000GB               | 2        | 2      | 0.6%    |
| Samsung Electronics SSD 980 PRO 1TB   | 2        | 3      | 0.6%    |
| Samsung Electronics SSD 970 EVO 500GB | 2        | 2      | 0.6%    |
| Samsung Electronics SSD 970 EVO 1TB   | 2        | 2      | 0.6%    |
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 0.6%    |
| Samsung Electronics SSD 850 EVO 1TB   | 2        | 2      | 0.6%    |
| Samsung Electronics HD322GJ 320GB     | 2        | 2      | 0.6%    |
| Samsung Electronics HD103UJ 1TB       | 2        | 2      | 0.6%    |
| LITEONIT LCT-128M3S 128GB SSD         | 2        | 2      | 0.6%    |
| Intel SSDSC2CW120A3 120GB             | 2        | 2      | 0.6%    |
| Hitachi HUA722010CLA330 1TB           | 2        | 2      | 0.6%    |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 99       | 123    | 30.28%  |
| Seagate             | 81       | 98     | 24.77%  |
| Samsung Electronics | 40       | 45     | 12.23%  |
| Hitachi             | 20       | 20     | 6.12%   |
| Toshiba             | 14       | 14     | 4.28%   |
| Kingston            | 11       | 11     | 3.36%   |
| Intel               | 8        | 8      | 2.45%   |
| SanDisk             | 7        | 8      | 2.14%   |
| Crucial             | 7        | 9      | 2.14%   |
| Maxtor              | 5        | 6      | 1.53%   |
| A-DATA Technology   | 5        | 5      | 1.53%   |
| China               | 4        | 4      | 1.22%   |
| LITEONIT            | 3        | 3      | 0.92%   |
| HGST                | 3        | 4      | 0.92%   |
| Micron Technology   | 2        | 8      | 0.61%   |
| LDLC                | 2        | 2      | 0.61%   |
| Intenso             | 2        | 2      | 0.61%   |
| YS                  | 1        | 1      | 0.31%   |
| XPG                 | 1        | 1      | 0.31%   |
| WD MediaMax         | 1        | 1      | 0.31%   |
| SK hynix            | 1        | 1      | 0.31%   |
| Silicon Motion      | 1        | 1      | 0.31%   |
| PNY                 | 1        | 1      | 0.31%   |
| Patriot             | 1        | 1      | 0.31%   |
| OCZ                 | 1        | 1      | 0.31%   |
| Netac               | 1        | 1      | 0.31%   |
| Mushkin             | 1        | 1      | 0.31%   |
| KingSpec            | 1        | 1      | 0.31%   |
| Gigabyte Technology | 1        | 1      | 0.31%   |
| ASMedia             | 1        | 1      | 0.31%   |
| Unknown             | 1        | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 96       | 120    | 40.17%  |
| Seagate             | 81       | 98     | 33.89%  |
| Hitachi             | 20       | 20     | 8.37%   |
| Samsung Electronics | 19       | 21     | 7.95%   |
| Toshiba             | 13       | 13     | 5.44%   |
| Maxtor              | 5        | 6      | 2.09%   |
| HGST                | 3        | 4      | 1.26%   |
| WD MediaMax         | 1        | 1      | 0.42%   |
| ASMedia             | 1        | 1      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 221      | 284    | 71.52%  |
| SSD  | 70       | 80     | 22.65%  |
| NVMe | 18       | 20     | 5.83%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB     | 2        | 2      | 25%     |
| WDC WD800BB-00FJA0 80GB               | 1        | 1      | 12.5%   |
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 12.5%   |
| Seagate ST3500630AS 500GB             | 1        | 1      | 12.5%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 12.5%   |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 12.5%   |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 37.5%   |
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 1        | 1      | 12.5%   |
| Intel               | 1        | 1      | 12.5%   |
| Hewlett-Packard     | 1        | 4      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2500     | 6536   | 62.22%  |
| Works    | 1222     | 2629   | 30.41%  |
| Malfunc  | 288      | 384    | 7.17%   |
| Failed   | 8        | 11     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 2470     | 45.85%  |
| AMD                           | 1112     | 20.64%  |
| Samsung Electronics           | 428      | 7.95%   |
| ASMedia Technology            | 211      | 3.92%   |
| SanDisk                       | 205      | 3.81%   |
| Kingston Technology Company   | 120      | 2.23%   |
| Marvell Technology Group      | 113      | 2.1%    |
| Phison Electronics            | 109      | 2.02%   |
| JMicron Technology            | 102      | 1.89%   |
| Nvidia                        | 82       | 1.52%   |
| Micron/Crucial Technology     | 81       | 1.5%    |
| Silicon Motion                | 57       | 1.06%   |
| SK hynix                      | 43       | 0.8%    |
| ADATA Technology              | 34       | 0.63%   |
| LSI Logic / Symbios Logic     | 23       | 0.43%   |
| Broadcom / LSI                | 23       | 0.43%   |
| Realtek Semiconductor         | 21       | 0.39%   |
| KIOXIA                        | 19       | 0.35%   |
| Silicon Image                 | 17       | 0.32%   |
| VIA Technologies              | 15       | 0.28%   |
| MAXIO Technology (Hangzhou)   | 15       | 0.28%   |
| Seagate Technology            | 13       | 0.24%   |
| Micron Technology             | 13       | 0.24%   |
| Adaptec                       | 12       | 0.22%   |
| Toshiba America Info Systems  | 6        | 0.11%   |
| Shenzhen Longsys Electronics  | 6        | 0.11%   |
| INNOGRIT                      | 4        | 0.07%   |
| Solidigm                      | 3        | 0.06%   |
| Lite-On Technology            | 3        | 0.06%   |
| Hewlett-Packard               | 3        | 0.06%   |
| Union Memory (Shenzhen)       | 2        | 0.04%   |
| OCZ Technology Group          | 2        | 0.04%   |
| Integrated Technology Express | 2        | 0.04%   |
| Chelsio Communications        | 2        | 0.04%   |
| Apple                         | 2        | 0.04%   |
| 3ware                         | 2        | 0.04%   |
| Western Digital               | 1        | 0.02%   |
| Transcend                     | 1        | 0.02%   |
| Toshiba                       | 1        | 0.02%   |
| TenaFe                        | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 614      | 9.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 313      | 4.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 214      | 3.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 199      | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 199      | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 198      | 3.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 192      | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 188      | 2.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 171      | 2.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 166      | 2.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 160      | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 144      | 2.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 126      | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 122      | 1.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 112      | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 110      | 1.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 101      | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 99       | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 89       | 1.36%   |
| AMD FCH SATA Controller D                                                               | 79       | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 78       | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 77       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 70       | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 63       | 0.97%   |
| Samsung NVMe SSD Controller 980                                                         | 62       | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 55       | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 55       | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 49       | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 48       | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 46       | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 45       | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 44       | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 44       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 42       | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 39       | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 39       | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 39       | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 37       | 0.57%   |
| Nvidia MCP61 SATA Controller                                                            | 37       | 0.57%   |
| AMD 300 Series Chipset SATA Controller                                                  | 37       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3031     | 57.8%   |
| NVMe | 1096     | 20.9%   |
| IDE  | 698      | 13.31%  |
| RAID | 357      | 6.81%   |
| SAS  | 45       | 0.86%   |
| SCSI | 17       | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2520     | 68.16%  |
| AMD    | 1177     | 31.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 64       | 1.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 56       | 1.51%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 45       | 1.21%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 43       | 1.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 42       | 1.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 42       | 1.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 41       | 1.11%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 40       | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 39       | 1.05%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 37       | 1%      |
| Intel Core i7-4770 CPU @ 3.40GHz            | 36       | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 36       | 0.97%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 36       | 0.97%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 35       | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 35       | 0.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 33       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 32       | 0.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 31       | 0.84%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 29       | 0.78%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 29       | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 29       | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 27       | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 26       | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 25       | 0.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 25       | 0.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 25       | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 23       | 0.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 23       | 0.62%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 22       | 0.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21       | 0.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 20       | 0.54%   |
| Intel 12th Gen Core i9-12900K               | 20       | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 20       | 0.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 20       | 0.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 19       | 0.51%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.51%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 19       | 0.51%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.49%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.49%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 18       | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 729      | 19.68%  |
| Intel Core i7           | 546      | 14.74%  |
| Intel Core i3           | 297      | 8.02%   |
| AMD Ryzen 5             | 285      | 7.69%   |
| Intel Xeon              | 237      | 6.4%    |
| Other                   | 228      | 6.16%   |
| AMD Ryzen 7             | 197      | 5.32%   |
| AMD Ryzen 9             | 136      | 3.67%   |
| AMD FX                  | 121      | 3.27%   |
| Intel Celeron           | 112      | 3.02%   |
| Intel Core 2 Duo        | 84       | 2.27%   |
| Intel Pentium           | 81       | 2.19%   |
| Intel Core 2 Quad       | 80       | 2.16%   |
| AMD Ryzen 3             | 57       | 1.54%   |
| AMD A10                 | 46       | 1.24%   |
| Intel Core i9           | 39       | 1.05%   |
| Intel Pentium Dual-Core | 36       | 0.97%   |
| AMD Phenom II X4        | 34       | 0.92%   |
| AMD A8                  | 32       | 0.86%   |
| AMD Ryzen Threadripper  | 30       | 0.81%   |
| AMD Athlon II X2        | 30       | 0.81%   |
| AMD A6                  | 25       | 0.67%   |
| AMD A4                  | 18       | 0.49%   |
| AMD Phenom II X6        | 17       | 0.46%   |
| AMD Athlon 64 X2        | 17       | 0.46%   |
| Intel Core 2            | 16       | 0.43%   |
| AMD Athlon II X4        | 16       | 0.43%   |
| Intel Atom              | 14       | 0.38%   |
| AMD Athlon              | 14       | 0.38%   |
| AMD Ryzen 5 PRO         | 11       | 0.3%    |
| Intel Pentium Dual      | 10       | 0.27%   |
| AMD Phenom II X2        | 10       | 0.27%   |
| AMD Athlon II X3        | 10       | 0.27%   |
| AMD Sempron             | 8        | 0.22%   |
| AMD Athlon X4           | 7        | 0.19%   |
| Intel Pentium Gold      | 6        | 0.16%   |
| Intel Pentium 4         | 6        | 0.16%   |
| AMD Ryzen 3 PRO         | 6        | 0.16%   |
| AMD Phenom              | 5        | 0.13%   |
| AMD E1                  | 5        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1503     | 40.58%  |
| 2      | 793      | 21.41%  |
| 6      | 558      | 15.06%  |
| 8      | 407      | 10.99%  |
| 12     | 140      | 3.78%   |
| 16     | 104      | 2.81%   |
| 1      | 56       | 1.51%   |
| 3      | 49       | 1.32%   |
| 10     | 35       | 0.94%   |
| 24     | 18       | 0.49%   |
| 14     | 11       | 0.3%    |
| 32     | 10       | 0.27%   |
| 28     | 6        | 0.16%   |
| 20     | 5        | 0.13%   |
| 18     | 4        | 0.11%   |
| 64     | 2        | 0.05%   |
| 128    | 1        | 0.03%   |
| 44     | 1        | 0.03%   |
| 40     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3624     | 98.03%  |
| 2      | 73       | 1.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2176     | 58.76%  |
| 1      | 1525     | 41.18%  |
| 6      | 1        | 0.03%   |
| 4      | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3695     | 99.92%  |
| Unknown        | 3        | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2258     | 59.66%  |
| 0x306c3    | 158      | 4.17%   |
| 0x306a9    | 105      | 2.77%   |
| 0x506e3    | 91       | 2.4%    |
| 0x206a7    | 83       | 2.19%   |
| 0x08701021 | 64       | 1.69%   |
| 0x906ea    | 60       | 1.59%   |
| 0x906e9    | 55       | 1.45%   |
| 0x90672    | 40       | 1.06%   |
| 0x0a201016 | 37       | 0.98%   |
| 0xa0671    | 35       | 0.92%   |
| 0xa0653    | 35       | 0.92%   |
| 0x06000852 | 34       | 0.9%    |
| 0x0a20120a | 33       | 0.87%   |
| 0x0800820d | 33       | 0.87%   |
| 0x306f2    | 32       | 0.85%   |
| 0x1067a    | 31       | 0.82%   |
| 0xa0655    | 29       | 0.77%   |
| 0x906ed    | 28       | 0.74%   |
| 0x010000c8 | 28       | 0.74%   |
| 0x08108109 | 23       | 0.61%   |
| 0x0a601203 | 22       | 0.58%   |
| 0xb0671    | 20       | 0.53%   |
| 0x08701013 | 20       | 0.53%   |
| 0x06003106 | 16       | 0.42%   |
| 0x906ec    | 14       | 0.37%   |
| 0x0a50000c | 13       | 0.34%   |
| 0x0a201205 | 13       | 0.34%   |
| 0x06001119 | 13       | 0.34%   |
| 0x906eb    | 11       | 0.29%   |
| 0x406f1    | 11       | 0.29%   |
| 0x106e5    | 11       | 0.29%   |
| 0x106a5    | 11       | 0.29%   |
| 0x0a50000d | 11       | 0.29%   |
| 0x20655    | 10       | 0.26%   |
| 0x0a201009 | 10       | 0.26%   |
| 0x0810100b | 10       | 0.26%   |
| 0x08001138 | 10       | 0.26%   |
| 0x90675    | 9        | 0.24%   |
| 0x206d7    | 9        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 492      | 13.29%  |
| KabyLake         | 343      | 9.26%   |
| IvyBridge        | 298      | 8.05%   |
| SandyBridge      | 254      | 6.86%   |
| Zen 3            | 245      | 6.62%   |
| Skylake          | 227      | 6.13%   |
| Zen 2            | 220      | 5.94%   |
| Penryn           | 175      | 4.73%   |
| Unknown          | 158      | 4.27%   |
| Piledriver       | 155      | 4.19%   |
| K10              | 135      | 3.65%   |
| Zen+             | 132      | 3.56%   |
| CometLake        | 119      | 3.21%   |
| Westmere         | 108      | 2.92%   |
| Zen              | 98       | 2.65%   |
| Core             | 84       | 2.27%   |
| Alderlake Hybrid | 68       | 1.84%   |
| Nehalem          | 65       | 1.76%   |
| Steamroller      | 41       | 1.11%   |
| Icelake          | 40       | 1.08%   |
| Silvermont       | 36       | 0.97%   |
| Broadwell        | 31       | 0.84%   |
| K8 Hammer        | 27       | 0.73%   |
| Bulldozer        | 25       | 0.68%   |
| Excavator        | 24       | 0.65%   |
| Goldmont plus    | 23       | 0.62%   |
| Goldmont         | 15       | 0.41%   |
| NetBurst         | 11       | 0.3%    |
| K10 Llano        | 11       | 0.3%    |
| Tremont          | 9        | 0.24%   |
| TigerLake        | 7        | 0.19%   |
| Jaguar           | 7        | 0.19%   |
| Bobcat           | 7        | 0.19%   |
| Puma             | 6        | 0.16%   |
| Bonnell          | 6        | 0.16%   |
| Gracemont        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1632     | 40.93%  |
| Intel                                        | 1298     | 32.56%  |
| AMD                                          | 1019     | 25.56%  |
| Matrox Electronics Systems                   | 17       | 0.43%   |
| ASPEED Technology                            | 17       | 0.43%   |
| ATI Technologies                             | 2        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| VIA Technologies                             | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 229      | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 129      | 3.17%   |
| Intel HD Graphics 530                                                       | 120      | 2.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 118      | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 112      | 2.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 97       | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 81       | 1.99%   |
| Intel HD Graphics 630                                                       | 63       | 1.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 63       | 1.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 60       | 1.47%   |
| Nvidia GT218 [GeForce 210]                                                  | 57       | 1.4%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 54       | 1.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 54       | 1.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 49       | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 48       | 1.18%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 47       | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 46       | 1.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 44       | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 41       | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 40       | 0.98%   |
| Intel AlderLake-S GT1                                                       | 39       | 0.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 37       | 0.91%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 32       | 0.79%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 32       | 0.79%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 32       | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                               | 31       | 0.76%   |
| AMD Raphael                                                                 | 31       | 0.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 30       | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30       | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 29       | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 29       | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 28       | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 28       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 27       | 0.66%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 26       | 0.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 26       | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 25       | 0.61%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 25       | 0.61%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 24       | 0.59%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 24       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1476     | 39.62%  |
| 1 x Intel                | 1101     | 29.56%  |
| 1 x AMD                  | 905      | 24.3%   |
| Intel + Nvidia           | 65       | 1.74%   |
| AMD + Nvidia             | 50       | 1.34%   |
| 2 x AMD                  | 37       | 0.99%   |
| 2 x Nvidia               | 23       | 0.62%   |
| Intel + AMD              | 22       | 0.59%   |
| 1 x Matrox               | 13       | 0.35%   |
| 1 x ASPEED               | 11       | 0.3%    |
| Nvidia + ASPEED          | 5        | 0.13%   |
| Nvidia + Matrox          | 3        | 0.08%   |
| Other                    | 2        | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.05%   |
| 3 x AMD                  | 1        | 0.03%   |
| 1 x XGI                  | 1        | 0.03%   |
| 1 x VIA                  | 1        | 0.03%   |
| 1 x Intel + 3 x Nvidia   | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| Intel + AMD + 3 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |
| AMD + ASPEED             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2560     | 68.19%  |
| Proprietary | 1003     | 26.72%  |
| Unknown     | 191      | 5.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2717     | 72.4%   |
| 1.01-2.0   | 230      | 6.13%   |
| 7.01-8.0   | 178      | 4.74%   |
| 0.51-1.0   | 172      | 4.58%   |
| 3.01-4.0   | 146      | 3.89%   |
| 0.01-0.5   | 111      | 2.96%   |
| 8.01-16.0  | 88       | 2.34%   |
| 5.01-6.0   | 57       | 1.52%   |
| 16.01-24.0 | 25       | 0.67%   |
| 2.01-3.0   | 24       | 0.64%   |
| 4.01-5.0   | 5        | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 628      | 16.95%  |
| Dell                 | 441      | 11.91%  |
| Goldstar             | 336      | 9.07%   |
| Hewlett-Packard      | 259      | 6.99%   |
| Acer                 | 254      | 6.86%   |
| BenQ                 | 182      | 4.91%   |
| AOC                  | 179      | 4.83%   |
| Philips              | 170      | 4.59%   |
| Ancor Communications | 145      | 3.91%   |
| Iiyama               | 85       | 2.29%   |
| Lenovo               | 77       | 2.08%   |
| ASUSTek Computer     | 72       | 1.94%   |
| ViewSonic            | 71       | 1.92%   |
| Sony                 | 49       | 1.32%   |
| Vizio                | 35       | 0.94%   |
| Fujitsu Siemens      | 31       | 0.84%   |
| LG Electronics       | 30       | 0.81%   |
| Panasonic            | 27       | 0.73%   |
| Unknown              | 26       | 0.7%    |
| Sceptre Tech         | 25       | 0.67%   |
| NEC Computers        | 25       | 0.67%   |
| MSI                  | 25       | 0.67%   |
| Eizo                 | 25       | 0.67%   |
| Unknown              | 19       | 0.51%   |
| Medion               | 18       | 0.49%   |
| HannStar             | 18       | 0.49%   |
| Toshiba              | 15       | 0.4%    |
| HKC                  | 12       | 0.32%   |
| Vestel Elektronik    | 11       | 0.3%    |
| Sharp                | 11       | 0.3%    |
| Gigabyte Technology  | 11       | 0.3%    |
| Apple                | 11       | 0.3%    |
| Hitachi              | 10       | 0.27%   |
| Gericom              | 10       | 0.27%   |
| RTK                  | 9        | 0.24%   |
| Mi                   | 9        | 0.24%   |
| Unknown (XXX)        | 8        | 0.22%   |
| Plain Tree Systems   | 8        | 0.22%   |
| MStar                | 8        | 0.22%   |
| Onkyo                | 7        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 21       | 0.53%   |
| Unknown                                                               | 19       | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 17       | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17       | 0.43%   |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15       | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 15       | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 15       | 0.38%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 14       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 13       | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 13       | 0.33%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 11       | 0.28%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 10       | 0.25%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 10       | 0.25%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 10       | 0.25%   |
| Sony TV SNY3102 1920x1080 708x398mm 32.0-inch                         | 9        | 0.23%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 9        | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 9        | 0.23%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 9        | 0.23%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9        | 0.23%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                     | 9        | 0.23%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch     | 8        | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 8        | 0.2%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7        | 0.18%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 7        | 0.18%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 7        | 0.18%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 7        | 0.18%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 7        | 0.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7        | 0.18%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 7        | 0.18%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                        | 7        | 0.18%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6        | 0.15%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 6        | 0.15%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 6        | 0.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 6        | 0.15%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 6        | 0.15%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 6        | 0.15%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 6        | 0.15%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 6        | 0.15%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 6        | 0.15%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1692     | 46.65%  |
| 3840x2160 (4K)     | 414      | 11.41%  |
| 2560x1440 (QHD)    | 256      | 7.06%   |
| 1280x1024 (SXGA)   | 205      | 5.65%   |
| 1680x1050 (WSXGA+) | 177      | 4.88%   |
| 1366x768 (WXGA)    | 129      | 3.56%   |
| 1920x1200 (WUXGA)  | 116      | 3.2%    |
| 1600x900 (HD+)     | 112      | 3.09%   |
| 1440x900 (WXGA+)   | 109      | 3.01%   |
| 3440x1440          | 56       | 1.54%   |
| 2560x1080          | 50       | 1.38%   |
| Unknown            | 48       | 1.32%   |
| 1360x768           | 46       | 1.27%   |
| 1920x540           | 37       | 1.02%   |
| 3840x1080          | 28       | 0.77%   |
| 1024x768 (XGA)     | 26       | 0.72%   |
| 1280x720 (HD)      | 20       | 0.55%   |
| 1600x1200          | 18       | 0.5%    |
| 2560x1600          | 12       | 0.33%   |
| 2288x1287          | 11       | 0.3%    |
| 3840x1600          | 10       | 0.28%   |
| 3840x1200          | 5        | 0.14%   |
| 2048x1152          | 5        | 0.14%   |
| 1280x960           | 5        | 0.14%   |
| 1400x1050          | 4        | 0.11%   |
| 4480x1440          | 3        | 0.08%   |
| 3600x1080          | 3        | 0.08%   |
| 5760x1080          | 2        | 0.06%   |
| 5120x1440          | 2        | 0.06%   |
| 3360x1080          | 2        | 0.06%   |
| 1280x768           | 2        | 0.06%   |
| 7680x2160          | 1        | 0.03%   |
| 720x480            | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 5760x2160          | 1        | 0.03%   |
| 5520x1080          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |
| 4080x2058          | 1        | 0.03%   |
| 3840x2560          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 520      | 14.06%  |
| 24      | 518      | 14%     |
| 23      | 459      | 12.41%  |
| 21      | 391      | 10.57%  |
| Unknown | 260      | 7.03%   |
| 19      | 228      | 6.16%   |
| 31      | 197      | 5.33%   |
| 20      | 123      | 3.33%   |
| 22      | 119      | 3.22%   |
| 18      | 116      | 3.14%   |
| 17      | 106      | 2.87%   |
| 34      | 83       | 2.24%   |
| 84      | 71       | 1.92%   |
| 32      | 55       | 1.49%   |
| 15      | 52       | 1.41%   |
| 72      | 41       | 1.11%   |
| 40      | 41       | 1.11%   |
| 25      | 36       | 0.97%   |
| 54      | 25       | 0.68%   |
| 28      | 19       | 0.51%   |
| 37      | 16       | 0.43%   |
| 65      | 15       | 0.41%   |
| 46      | 15       | 0.41%   |
| 42      | 15       | 0.41%   |
| 29      | 14       | 0.38%   |
| 26      | 14       | 0.38%   |
| 52      | 12       | 0.32%   |
| 43      | 12       | 0.32%   |
| 36      | 12       | 0.32%   |
| 48      | 9        | 0.24%   |
| 49      | 8        | 0.22%   |
| 47      | 8        | 0.22%   |
| 35      | 7        | 0.19%   |
| 142     | 6        | 0.16%   |
| 64      | 6        | 0.16%   |
| 14      | 6        | 0.16%   |
| 60      | 5        | 0.14%   |
| 57      | 5        | 0.14%   |
| 39      | 5        | 0.14%   |
| 33      | 5        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1410     | 39.2%   |
| 401-500        | 852      | 23.69%  |
| 601-700        | 283      | 7.87%   |
| Unknown        | 260      | 7.23%   |
| 701-800        | 156      | 4.34%   |
| 301-350        | 150      | 4.17%   |
| 351-400        | 128      | 3.56%   |
| 1501-2000      | 121      | 3.36%   |
| 1001-1500      | 118      | 3.28%   |
| 801-900        | 72       | 2%      |
| 901-1000       | 27       | 0.75%   |
| 201-300        | 13       | 0.36%   |
| More than 2000 | 7        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2371     | 68.7%   |
| 16/10   | 435      | 12.61%  |
| Unknown | 210      | 6.09%   |
| 5/4     | 204      | 5.91%   |
| 21/9    | 113      | 3.27%   |
| 4/3     | 56       | 1.62%   |
| 32/9    | 19       | 0.55%   |
| 3/2     | 17       | 0.49%   |
| 6/5     | 8        | 0.23%   |
| 1.00    | 8        | 0.23%   |
| 2.12    | 2        | 0.06%   |
| 2.00    | 2        | 0.06%   |
| 1.96    | 2        | 0.06%   |
| 0.56    | 2        | 0.06%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1174     | 32.26%  |
| 301-350        | 531      | 14.59%  |
| 151-200        | 471      | 12.94%  |
| 351-500        | 367      | 10.09%  |
| Unknown        | 260      | 7.14%   |
| 251-300        | 214      | 5.88%   |
| More than 1000 | 212      | 5.83%   |
| 141-150        | 191      | 5.25%   |
| 501-1000       | 140      | 3.85%   |
| 101-110        | 45       | 1.24%   |
| 131-140        | 9        | 0.25%   |
| 111-120        | 9        | 0.25%   |
| 71-80          | 8        | 0.22%   |
| 81-90          | 3        | 0.08%   |
| 121-130        | 2        | 0.05%   |
| 91-100         | 2        | 0.05%   |
| 41-50          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2182     | 62.63%  |
| 101-120       | 601      | 17.25%  |
| Unknown       | 260      | 7.46%   |
| 1-50          | 187      | 5.37%   |
| 121-160       | 170      | 4.88%   |
| 161-240       | 83       | 2.38%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2782     | 73.91%  |
| 2     | 594      | 15.78%  |
| 0     | 314      | 8.34%   |
| 3     | 64       | 1.7%    |
| 4     | 8        | 0.21%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2187     | 41.86%  |
| Intel                           | 1729     | 33.1%   |
| Qualcomm Atheros                | 264      | 5.05%   |
| Broadcom                        | 154      | 2.95%   |
| TP-Link                         | 108      | 2.07%   |
| Ralink Technology               | 106      | 2.03%   |
| Nvidia                          | 68       | 1.3%    |
| MediaTek                        | 65       | 1.24%   |
| Ralink                          | 57       | 1.09%   |
| NetGear                         | 36       | 0.69%   |
| Aquantia                        | 36       | 0.69%   |
| Broadcom Limited                | 32       | 0.61%   |
| Marvell Technology Group        | 31       | 0.59%   |
| Microsoft                       | 25       | 0.48%   |
| ASIX Electronics                | 25       | 0.48%   |
| Samsung Electronics             | 24       | 0.46%   |
| Qualcomm Atheros Communications | 22       | 0.42%   |
| D-Link System                   | 22       | 0.42%   |
| Xiaomi                          | 17       | 0.33%   |
| D-Link                          | 17       | 0.33%   |
| ASUSTek Computer                | 15       | 0.29%   |
| Edimax Technology               | 13       | 0.25%   |
| Linksys                         | 12       | 0.23%   |
| IMC Networks                    | 10       | 0.19%   |
| DisplayLink                     | 10       | 0.19%   |
| Qualcomm                        | 7        | 0.13%   |
| Sitecom Europe                  | 6        | 0.11%   |
| Belkin Components               | 6        | 0.11%   |
| AVM                             | 5        | 0.1%    |
| ZyDAS                           | 4        | 0.08%   |
| Wilocity                        | 4        | 0.08%   |
| VIA Technologies                | 4        | 0.08%   |
| Sigma Designs                   | 4        | 0.08%   |
| OPPO Electronics                | 4        | 0.08%   |
| JMicron Technology              | 4        | 0.08%   |
| ICS Advent                      | 4        | 0.08%   |
| Huawei Technologies             | 4        | 0.08%   |
| ZTE WCDMA Technologies MSM      | 3        | 0.06%   |
| Texas Instruments               | 3        | 0.06%   |
| Micro Star International        | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1696     | 28.34%  |
| Realtek RTL8125 2.5GbE Controller                                 | 245      | 4.09%   |
| Intel I211 Gigabit Network Connection                             | 189      | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 178      | 2.97%   |
| Intel Wi-Fi 6 AX200                                               | 166      | 2.77%   |
| Intel Ethernet Controller I225-V                                  | 132      | 2.21%   |
| Intel Ethernet Connection I217-LM                                 | 130      | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 130      | 2.17%   |
| Intel 82579V Gigabit Network Connection                           | 75       | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 73       | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 61       | 1.02%   |
| Realtek 802.11ac NIC                                              | 61       | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60       | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 58       | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 58       | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 51       | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 48       | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 46       | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 41       | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 41       | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 40       | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 37       | 0.62%   |
| Intel Wireless-AC 9260                                            | 36       | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.58%   |
| Nvidia MCP61 Ethernet                                             | 33       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33       | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 30       | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29       | 0.48%   |
| Intel Wireless 7265                                               | 28       | 0.47%   |
| Intel Wireless 7260                                               | 27       | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 27       | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 26       | 0.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 25       | 0.42%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 25       | 0.42%   |
| Intel Wireless 3165                                               | 24       | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 24       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 618      | 34.26%  |
| Realtek Semiconductor                 | 424      | 23.5%   |
| Qualcomm Atheros                      | 149      | 8.26%   |
| TP-Link                               | 106      | 5.88%   |
| Ralink Technology                     | 106      | 5.88%   |
| MediaTek                              | 60       | 3.33%   |
| Broadcom                              | 60       | 3.33%   |
| Ralink                                | 57       | 3.16%   |
| NetGear                               | 36       | 2%      |
| Microsoft                             | 25       | 1.39%   |
| Qualcomm Atheros Communications       | 22       | 1.22%   |
| D-Link System                         | 17       | 0.94%   |
| D-Link                                | 17       | 0.94%   |
| Broadcom Limited                      | 15       | 0.83%   |
| ASUSTek Computer                      | 15       | 0.83%   |
| Edimax Technology                     | 13       | 0.72%   |
| Linksys                               | 10       | 0.55%   |
| IMC Networks                          | 10       | 0.55%   |
| Sitecom Europe                        | 6        | 0.33%   |
| Belkin Components                     | 6        | 0.33%   |
| AVM                                   | 5        | 0.28%   |
| ZyDAS                                 | 4        | 0.22%   |
| Wilocity                              | 4        | 0.22%   |
| Micro Star International              | 3        | 0.17%   |
| Mercucys                              | 3        | 0.17%   |
| Encore Electronics                    | 2        | 0.11%   |
| BUFFALO                               | 2        | 0.11%   |
| TRENDnet                              | 1        | 0.06%   |
| Sierra Wireless                       | 1        | 0.06%   |
| Sagem                                 | 1        | 0.06%   |
| Philips (or NXP)                      | 1        | 0.06%   |
| LSI                                   | 1        | 0.06%   |
| Guillemot                             | 1        | 0.06%   |
| Gemtek                                | 1        | 0.06%   |
| Dell                                  | 1        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 166      | 9.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 73       | 3.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 61       | 3.34%   |
| Realtek 802.11ac NIC                                          | 61       | 3.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 58       | 3.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 51       | 2.79%   |
| Ralink MT7601U Wireless Adapter                               | 41       | 2.24%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 41       | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 37       | 2.02%   |
| Intel Wireless-AC 9260                                        | 36       | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 29       | 1.59%   |
| Intel Wireless 7265                                           | 28       | 1.53%   |
| Intel Wireless 7260                                           | 27       | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 27       | 1.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 25       | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                | 25       | 1.37%   |
| Intel Wireless 3165                                           | 24       | 1.31%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 23       | 1.26%   |
| Ralink RT5370 Wireless Adapter                                | 22       | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 22       | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 21       | 1.15%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 20       | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 19       | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                               | 19       | 1.04%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 19       | 1.04%   |
| Intel Wireless 8260                                           | 19       | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 18       | 0.98%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 18       | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 18       | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 18       | 0.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 17       | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 17       | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 17       | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 16       | 0.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 14       | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 14       | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 14       | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 14       | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 14       | 0.77%   |
| TP-Link 802.11ac WLAN Adapter                                 | 13       | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2037     | 51.36%  |
| Intel                                  | 1413     | 35.63%  |
| Qualcomm Atheros                       | 130      | 3.28%   |
| Broadcom                               | 97       | 2.45%   |
| Nvidia                                 | 68       | 1.71%   |
| Aquantia                               | 36       | 0.91%   |
| Marvell Technology Group               | 31       | 0.78%   |
| ASIX Electronics                       | 25       | 0.63%   |
| Xiaomi                                 | 17       | 0.43%   |
| Samsung Electronics                    | 17       | 0.43%   |
| Broadcom Limited                       | 17       | 0.43%   |
| DisplayLink                            | 10       | 0.25%   |
| Qualcomm                               | 7        | 0.18%   |
| D-Link System                          | 5        | 0.13%   |
| VIA Technologies                       | 4        | 0.1%    |
| OPPO Electronics                       | 4        | 0.1%    |
| MediaTek                               | 4        | 0.1%    |
| JMicron Technology                     | 4        | 0.1%    |
| ICS Advent                             | 4        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 3        | 0.08%   |
| Huawei Technologies                    | 3        | 0.08%   |
| Chelsio Communications                 | 3        | 0.08%   |
| TP-Link                                | 2        | 0.05%   |
| Tehuti Networks                        | 2        | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| Mellanox Technologies                  | 2        | 0.05%   |
| Linksys                                | 2        | 0.05%   |
| Google                                 | 2        | 0.05%   |
| Apple                                  | 2        | 0.05%   |
| American Megatrends                    | 2        | 0.05%   |
| 3Com                                   | 2        | 0.05%   |
| Vimtron Electronics                    | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Prolific Technology                    | 1        | 0.03%   |
| Motorola PCS                           | 1        | 0.03%   |
| MosChip Semiconductor                  | 1        | 0.03%   |
| LG Electronics                         | 1        | 0.03%   |
| Compal Electronics                     | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1696     | 41.28%  |
| Realtek RTL8125 2.5GbE Controller                                 | 245      | 5.96%   |
| Intel I211 Gigabit Network Connection                             | 189      | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 178      | 4.33%   |
| Intel Ethernet Controller I225-V                                  | 132      | 3.21%   |
| Intel Ethernet Connection I217-LM                                 | 130      | 3.16%   |
| Intel Ethernet Connection (2) I219-V                              | 130      | 3.16%   |
| Intel 82579V Gigabit Network Connection                           | 75       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 1.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60       | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 58       | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 48       | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 46       | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 40       | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 33       | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 33       | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.73%   |
| Intel I210 Gigabit Network Connection                             | 30       | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 26       | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 25       | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                             | 24       | 0.58%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24       | 0.58%   |
| Intel Ethernet Connection (14) I219-V                             | 20       | 0.49%   |
| Intel 82578DC Gigabit Network Connection                          | 20       | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20       | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 18       | 0.44%   |
| Intel Ethernet Connection (2) I218-LM                             | 18       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17       | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.41%   |
| Intel 82578DM Gigabit Network Connection                          | 16       | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15       | 0.37%   |
| Intel Ethernet Controller X550                                    | 15       | 0.37%   |
| Intel Ethernet Connection (17) I219-V                             | 15       | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14       | 0.34%   |
| Intel Ethernet Connection (11) I219-V                             | 14       | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13       | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12       | 0.29%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 12       | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3665     | 67.96%  |
| WiFi     | 1681     | 31.17%  |
| Modem    | 42       | 0.78%   |
| Unknown  | 5        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2934     | 75.97%  |
| WiFi     | 927      | 24%     |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2305     | 62.03%  |
| 2     | 1174     | 31.59%  |
| 3     | 170      | 4.57%   |
| 4     | 29       | 0.78%   |
| 0     | 23       | 0.62%   |
| 5     | 9        | 0.24%   |
| 8     | 2        | 0.05%   |
| 7     | 2        | 0.05%   |
| 9     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2504     | 67.29%  |
| Yes  | 1217     | 32.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 570      | 45.67%  |
| Cambridge Silicon Radio         | 242      | 19.39%  |
| Realtek Semiconductor           | 86       | 6.89%   |
| ASUSTek Computer                | 77       | 6.17%   |
| Qualcomm Atheros Communications | 54       | 4.33%   |
| Broadcom                        | 50       | 4.01%   |
| MediaTek                        | 31       | 2.48%   |
| IMC Networks                    | 28       | 2.24%   |
| Apple                           | 22       | 1.76%   |
| TP-Link                         | 19       | 1.52%   |
| Lite-On Technology              | 16       | 1.28%   |
| Foxconn / Hon Hai               | 9        | 0.72%   |
| Belkin Components               | 6        | 0.48%   |
| Micro Star International        | 4        | 0.32%   |
| Logitech                        | 4        | 0.32%   |
| Edimax Technology               | 4        | 0.32%   |
| Dell                            | 4        | 0.32%   |
| Realtek                         | 3        | 0.24%   |
| Integrated System Solution      | 2        | 0.16%   |
| Hewlett-Packard                 | 2        | 0.16%   |
| D-Link System                   | 2        | 0.16%   |
| Conwise Technology              | 2        | 0.16%   |
| Unknown                         | 2        | 0.16%   |
| TRENDnet                        | 1        | 0.08%   |
| Toshiba                         | 1        | 0.08%   |
| Ralink                          | 1        | 0.08%   |
| Primax Electronics              | 1        | 0.08%   |
| Mobile Action Technology        | 1        | 0.08%   |
| ISSC                            | 1        | 0.08%   |
| HTC (High Tech Computer)        | 1        | 0.08%   |
| Dynex                           | 1        | 0.08%   |
| Actions                         | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 242      | 19.36%  |
| Intel AX200 Bluetooth                                 | 142      | 11.36%  |
| Intel Bluetooth wireless interface                    | 110      | 8.8%    |
| Intel AX201 Bluetooth                                 | 73       | 5.84%   |
| Intel AX210 Bluetooth                                 | 72       | 5.76%   |
| Realtek Bluetooth Radio                               | 62       | 4.96%   |
| Intel Wireless-AC 3168 Bluetooth                      | 56       | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 43       | 3.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 36       | 2.88%   |
| MediaTek Wireless_Device                              | 31       | 2.48%   |
| Intel Bluetooth Device                                | 29       | 2.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 28       | 2.24%   |
| ASUS ASUS USB-BT500                                   | 26       | 2.08%   |
| Qualcomm Atheros  Bluetooth Device                    | 21       | 1.68%   |
| TP-Link UB500 Adapter                                 | 19       | 1.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 17       | 1.36%   |
| IMC Networks Bluetooth Radio                          | 15       | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 14       | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                        | 13       | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 11       | 0.88%   |
| ASUS Bluetooth Radio                                  | 11       | 0.88%   |
| Apple Bluetooth USB Host Controller                   | 10       | 0.8%    |
| Lite-On Bluetooth Device                              | 9        | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 8        | 0.64%   |
| IMC Networks Wireless_Device                          | 8        | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 8        | 0.64%   |
| Realtek RTL8821A Bluetooth                            | 7        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                     | 7        | 0.56%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.4%    |
| ASUS Qualcomm Bluetooth 4.1                           | 5        | 0.4%    |
| ASUS Bluetooth Device                                 | 5        | 0.4%    |
| ASUS BCM20702A0                                       | 5        | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.32%   |
| Micro Star International Bluetooth Device             | 4        | 0.32%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 4        | 0.32%   |
| Broadcom BCM2045 Bluetooth                            | 4        | 0.32%   |
| Broadcom BCM2035 Bluetooth dongle                     | 4        | 0.32%   |
| Apple Bluetooth HCI                                   | 4        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2408     | 39.14%  |
| Nvidia                                       | 1550     | 25.2%   |
| AMD                                          | 1456     | 23.67%  |
| C-Media Electronics                          | 122      | 1.98%   |
| Logitech                                     | 65       | 1.06%   |
| Creative Labs                                | 60       | 0.98%   |
| ASUSTek Computer                             | 45       | 0.73%   |
| GN Netcom                                    | 32       | 0.52%   |
| Micro Star International                     | 29       | 0.47%   |
| Texas Instruments                            | 25       | 0.41%   |
| Kingston Technology                          | 22       | 0.36%   |
| JMTek                                        | 20       | 0.33%   |
| SteelSeries ApS                              | 17       | 0.28%   |
| Razer USA                                    | 17       | 0.28%   |
| Creative Technology                          | 16       | 0.26%   |
| Corsair                                      | 15       | 0.24%   |
| Generalplus Technology                       | 14       | 0.23%   |
| Focusrite-Novation                           | 11       | 0.18%   |
| Plantronics                                  | 9        | 0.15%   |
| Tenx Technology                              | 8        | 0.13%   |
| Giga-Byte Technology                         | 8        | 0.13%   |
| Blue Microphones                             | 8        | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 7        | 0.11%   |
| VIA Technologies                             | 7        | 0.11%   |
| M-Audio                                      | 6        | 0.1%    |
| Hewlett-Packard                              | 6        | 0.1%    |
| Sennheiser Communications                    | 5        | 0.08%   |
| Realtek Semiconductor                        | 5        | 0.08%   |
| KTMicro                                      | 5        | 0.08%   |
| Jieli Technology                             | 5        | 0.08%   |
| Dell                                         | 5        | 0.08%   |
| Astro Gaming                                 | 5        | 0.08%   |
| Apple                                        | 5        | 0.08%   |
| Sony                                         | 4        | 0.07%   |
| Samson Technologies                          | 4        | 0.07%   |
| Yamaha                                       | 3        | 0.05%   |
| Xilinx                                       | 3        | 0.05%   |
| Scarlett                                     | 3        | 0.05%   |
| SAVITECH                                     | 3        | 0.05%   |
| RODE Microphones                             | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 379      | 5.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 353      | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 273      | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 254      | 3.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 224      | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 214      | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 211      | 2.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 195      | 2.75%   |
| Intel 200 Series PCH HD Audio                                              | 191      | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 140      | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 135      | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 134      | 1.89%   |
| AMD FCH Azalia Controller                                                  | 124      | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 121      | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 106      | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                     | 99       | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 96       | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 95       | 1.34%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 93       | 1.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 89       | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 88       | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 86       | 1.21%   |
| Nvidia High Definition Audio Controller                                    | 85       | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 83       | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                              | 79       | 1.12%   |
| Nvidia GA102 High Definition Audio Controller                              | 77       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 74       | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 74       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 72       | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 71       | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 70       | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 69       | 0.97%   |
| Nvidia GK107 HDMI Audio Controller                                         | 61       | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 60       | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 58       | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 57       | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 56       | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 55       | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 53       | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 48       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 354      | 18.11%  |
| Corsair                      | 295      | 15.09%  |
| Samsung Electronics          | 213      | 10.9%   |
| SK hynix                     | 197      | 10.08%  |
| G.Skill                      | 159      | 8.13%   |
| Crucial                      | 155      | 7.93%   |
| Unknown                      | 151      | 7.72%   |
| Micron Technology            | 103      | 5.27%   |
| A-DATA Technology            | 51       | 2.61%   |
| Team                         | 36       | 1.84%   |
| Unknown                      | 32       | 1.64%   |
| Patriot                      | 22       | 1.13%   |
| Ramaxel Technology           | 16       | 0.82%   |
| Nanya Technology             | 16       | 0.82%   |
| Unknown (ABCD)               | 12       | 0.61%   |
| Elpida                       | 9        | 0.46%   |
| Transcend                    | 8        | 0.41%   |
| Smart                        | 8        | 0.41%   |
| Apacer                       | 8        | 0.41%   |
| AMD                          | 8        | 0.41%   |
| PNY                          | 7        | 0.36%   |
| GOODRAM                      | 6        | 0.31%   |
| Silicon Power                | 5        | 0.26%   |
| Hewlett-Packard              | 5        | 0.26%   |
| Timetec                      | 4        | 0.2%    |
| KETECH                       | 4        | 0.2%    |
| GeIL                         | 4        | 0.2%    |
| Avant                        | 4        | 0.2%    |
| ASint Technology             | 4        | 0.2%    |
| Asgard                       | 4        | 0.2%    |
| Patriot Memory (PDP Systems) | 3        | 0.15%   |
| KLEVV                        | 3        | 0.15%   |
| Kingmax                      | 3        | 0.15%   |
| Innodisk                     | 3        | 0.15%   |
| Atermiter                    | 3        | 0.15%   |
| Unknown (0x0C97)             | 2        | 0.1%    |
| Super Talent                 | 2        | 0.1%    |
| Qumo                         | 2        | 0.1%    |
| Netac                        | 2        | 0.1%    |
| Neo Forza                    | 2        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 32       | 1.52%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 21       | 1%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 20       | 0.95%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 15       | 0.71%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 13       | 0.62%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s              | 13       | 0.62%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 13       | 0.62%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                      | 13       | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 12       | 0.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 12       | 0.57%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s             | 12       | 0.57%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 12       | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                | 11       | 0.52%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 11       | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 10       | 0.47%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 10       | 0.47%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s             | 10       | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 9        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 9        | 0.43%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s              | 9        | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 9        | 0.43%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s             | 9        | 0.43%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s               | 8        | 0.38%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s               | 8        | 0.38%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s            | 8        | 0.38%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s            | 8        | 0.38%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 7        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 7        | 0.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s               | 7        | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 7        | 0.33%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 7        | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 6        | 0.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 6        | 0.28%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s                | 6        | 0.28%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 6        | 0.28%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s              | 6        | 0.28%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 6        | 0.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 6        | 0.28%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s              | 6        | 0.28%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 6        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 923      | 53.23%  |
| DDR3         | 542      | 31.26%  |
| DDR5         | 69       | 3.98%   |
| Unknown      | 64       | 3.69%   |
| SDRAM        | 55       | 3.17%   |
| DDR2         | 40       | 2.31%   |
| LPDDR4       | 22       | 1.27%   |
| DDR          | 11       | 0.63%   |
| LPDDR3       | 4        | 0.23%   |
| DRAM         | 2        | 0.12%   |
| LPDDR5       | 1        | 0.06%   |
| DDR2 FB-DIMM | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1545     | 90.78%  |
| SODIMM       | 135      | 7.93%   |
| Row Of Chips | 9        | 0.53%   |
| RIMM         | 9        | 0.53%   |
| FB-DIMM      | 3        | 0.18%   |
| Unknown      | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 679      | 36.92%  |
| 16384  | 400      | 21.75%  |
| 4096   | 392      | 21.32%  |
| 2048   | 179      | 9.73%   |
| 32768  | 154      | 8.37%   |
| 1024   | 29       | 1.58%   |
| 65536  | 4        | 0.22%   |
| 131072 | 1        | 0.05%   |
| 512    | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 328      | 17.15%  |
| 3200    | 245      | 12.81%  |
| 1333    | 178      | 9.31%   |
| 2400    | 149      | 7.79%   |
| 3600    | 136      | 7.11%   |
| 2667    | 126      | 6.59%   |
| 2133    | 83       | 4.34%   |
| 3000    | 49       | 2.56%   |
| 1867    | 49       | 2.56%   |
| 800     | 41       | 2.14%   |
| 2666    | 35       | 1.83%   |
| 4800    | 33       | 1.73%   |
| 2933    | 27       | 1.41%   |
| 1800    | 27       | 1.41%   |
| 667     | 26       | 1.36%   |
| 3800    | 25       | 1.31%   |
| 3400    | 25       | 1.31%   |
| 3533    | 22       | 1.15%   |
| 3733    | 21       | 1.1%    |
| 1866    | 18       | 0.94%   |
| 1066    | 18       | 0.94%   |
| Unknown | 15       | 0.78%   |
| 3534    | 13       | 0.68%   |
| 3266    | 13       | 0.68%   |
| 1067    | 12       | 0.63%   |
| 3466    | 11       | 0.58%   |
| 2800    | 10       | 0.52%   |
| 5600    | 9        | 0.47%   |
| 5200    | 9        | 0.47%   |
| 3666    | 9        | 0.47%   |
| 3866    | 8        | 0.42%   |
| 3500    | 8        | 0.42%   |
| 2000    | 8        | 0.42%   |
| 400     | 8        | 0.42%   |
| 6400    | 7        | 0.37%   |
| 1648    | 7        | 0.37%   |
| 5808    | 6        | 0.31%   |
| 3933    | 6        | 0.31%   |
| 2465    | 6        | 0.31%   |
| 1334    | 6        | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 60       | 32.61%  |
| Brother Industries     | 42       | 22.83%  |
| Canon                  | 22       | 11.96%  |
| Samsung Electronics    | 20       | 10.87%  |
| Seiko Epson            | 19       | 10.33%  |
| Prolific Technology    | 3        | 1.63%   |
| Lexmark International  | 3        | 1.63%   |
| Dymo-CoStar            | 3        | 1.63%   |
| STMicroelectronics     | 2        | 1.09%   |
| QinHeng Electronics    | 2        | 1.09%   |
| Zebra                  | 1        | 0.54%   |
| Pantum                 | 1        | 0.54%   |
| Oki Data               | 1        | 0.54%   |
| Kyocera                | 1        | 0.54%   |
| Fuji Xerox             | 1        | 0.54%   |
| Custom Engineering SPA | 1        | 0.54%   |
| BESTEASY               | 1        | 0.54%   |
| Apple                  | 1        | 0.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2130 series                                    | 5        | 2.66%   |
| Seiko Epson L360 Series                                   | 3        | 1.6%    |
| Seiko Epson ET-2720 Series                                | 3        | 1.6%    |
| Samsung Composite Device                                  | 3        | 1.6%    |
| Prolific PL2305 Parallel Port                             | 3        | 1.6%    |
| HP OfficeJet 3830 series                                  | 3        | 1.6%    |
| Brother Printer                                           | 3        | 1.6%    |
| Brother HL-1440 Laser Printer                             | 3        | 1.6%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 1.06%   |
| Seiko Epson XP-2100 Series                                | 2        | 1.06%   |
| Seiko Epson L3250 Series                                  | 2        | 1.06%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.06%   |
| Samsung M2070 Series                                      | 2        | 1.06%   |
| Samsung C460 Series                                       | 2        | 1.06%   |
| QinHeng CH340S                                            | 2        | 1.06%   |
| HP OfficeJet Pro 8020 series                              | 2        | 1.06%   |
| HP OfficeJet 5600 (USBHUB)                                | 2        | 1.06%   |
| HP Officejet 4500 G510n-z                                 | 2        | 1.06%   |
| HP LaserJet P1005                                         | 2        | 1.06%   |
| HP LaserJet M203-M206                                     | 2        | 1.06%   |
| HP LaserJet M14-M17                                       | 2        | 1.06%   |
| HP LaserJet 4250                                          | 2        | 1.06%   |
| HP LaserJet 3015                                          | 2        | 1.06%   |
| HP DeskJet 4100 series                                    | 2        | 1.06%   |
| HP DeskJet 3700 series                                    | 2        | 1.06%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.06%   |
| HP DeskJet 2300 series                                    | 2        | 1.06%   |
| HP DeskJet 1110 series                                    | 2        | 1.06%   |
| Dymo-CoStar LabelWriter 400                               | 2        | 1.06%   |
| Canon TS3100 series                                       | 2        | 1.06%   |
| Canon LBP2900                                             | 2        | 1.06%   |
| Brother HL-L2375DW series                                 | 2        | 1.06%   |
| Brother HL-L2350DW series                                 | 2        | 1.06%   |
| Brother HL-2270DW Laser Printer                           | 2        | 1.06%   |
| Brother DCP-J105                                          | 2        | 1.06%   |
| Brother DCP-7055 scanner/printer                          | 2        | 1.06%   |
| Brother DCP-1610W                                         | 2        | 1.06%   |
| Zebra ZP 450 Printer                                      | 1        | 0.53%   |
| Seiko Epson WF-3520 Series                                | 1        | 0.53%   |
| Seiko Epson WF-2840 Series                                | 1        | 0.53%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 19       | 57.58%  |
| Seiko Epson                 | 7        | 21.21%  |
| Hewlett-Packard             | 6        | 18.18%  |
| Acer Peripherals (now BenQ) | 1        | 3.03%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                                  | 5        | 15.15%  |
| Canon CanoScan LiDE 100                                  | 3        | 9.09%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 2        | 6.06%   |
| Canon CanoScan LiDE 220                                  | 2        | 6.06%   |
| Canon CanoScan LiDE 110                                  | 2        | 6.06%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 3.03%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 3.03%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 3.03%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 1        | 3.03%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1        | 3.03%   |
| HP Scanjet N6010                                         | 1        | 3.03%   |
| HP ScanJet G4010                                         | 1        | 3.03%   |
| HP Scanjet G2710                                         | 1        | 3.03%   |
| HP ScanJet 4850C/4890C                                   | 1        | 3.03%   |
| HP ScanJet 3970c                                         | 1        | 3.03%   |
| HP ScanJet 3400cse                                       | 1        | 3.03%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 3.03%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 3.03%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1        | 3.03%   |
| Canon CanoScan LIDE 25                                   | 1        | 3.03%   |
| Canon CanoScan LiDE 200                                  | 1        | 3.03%   |
| Canon CanoScan 9000F Mark II                             | 1        | 3.03%   |
| Canon CanoScan 4200F                                     | 1        | 3.03%   |
| Acer Peripherals (now BenQ) Benq 5000                    | 1        | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 244      | 35.36%  |
| Microdia                      | 61       | 8.84%   |
| Microsoft                     | 48       | 6.96%   |
| Sunplus Innovation Technology | 30       | 4.35%   |
| Apple                         | 26       | 3.77%   |
| Samsung Electronics           | 22       | 3.19%   |
| Generalplus Technology        | 19       | 2.75%   |
| Realtek Semiconductor         | 18       | 2.61%   |
| ARC International             | 18       | 2.61%   |
| Z-Star Microelectronics       | 16       | 2.32%   |
| Chicony Electronics           | 16       | 2.32%   |
| 2M UVC CAMERA                 | 9        | 1.3%    |
| Trust                         | 8        | 1.16%   |
| Creative Technology           | 8        | 1.16%   |
| MacroSilicon                  | 7        | 1.01%   |
| Razer USA                     | 6        | 0.87%   |
| KYE Systems (Mouse Systems)   | 6        | 0.87%   |
| GEMBIRD                       | 6        | 0.87%   |
| Cubeternet                    | 6        | 0.87%   |
| Jieli Technology              | 5        | 0.72%   |
| WaveRider Communications      | 4        | 0.58%   |
| Sonix Technology              | 4        | 0.58%   |
| Philips (or NXP)              | 4        | 0.58%   |
| Linux Foundation              | 4        | 0.58%   |
| Hewlett-Packard               | 4        | 0.58%   |
| AVerMedia Technologies        | 4        | 0.58%   |
| YGTek                         | 3        | 0.43%   |
| OPPO Electronics              | 3        | 0.43%   |
| IMC Networks                  | 3        | 0.43%   |
| Genesys Logic                 | 3        | 0.43%   |
| Aveo Technology               | 3        | 0.43%   |
| Asuscom Network               | 3        | 0.43%   |
| Arkmicro Technologies         | 3        | 0.43%   |
| Alcor Micro                   | 3        | 0.43%   |
| Sunplus IT                    | 2        | 0.29%   |
| Quanta                        | 2        | 0.29%   |
| Pixart Imaging                | 2        | 0.29%   |
| OmniVision Technologies       | 2        | 0.29%   |
| Magic Control Technology      | 2        | 0.29%   |
| Lenovo                        | 2        | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 59       | 8.53%   |
| Logitech HD Pro Webcam C920              | 36       | 5.2%    |
| Logitech C922 Pro Stream Webcam          | 24       | 3.47%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 24       | 3.47%   |
| Samsung Galaxy series, misc. (MTP mode)  | 21       | 3.03%   |
| Microdia Webcam Vitade AF                | 19       | 2.75%   |
| ARC International Camera                 | 18       | 2.6%    |
| Logitech HD Webcam C615                  | 13       | 1.88%   |
| Logitech C920 PRO HD Webcam              | 13       | 1.88%   |
| Microsoft LifeCam HD-3000                | 12       | 1.73%   |
| Microdia USB 2.0 Camera                  | 12       | 1.73%   |
| Generalplus GENERAL WEBCAM               | 10       | 1.45%   |
| Microsoft LifeCam Cinema                 | 9        | 1.3%    |
| Logitech Webcam C170                     | 9        | 1.3%    |
| Logitech BRIO Ultra HD Webcam            | 9        | 1.3%    |
| 2M UVC CAMERA Web Camera                 | 9        | 1.3%    |
| Sunplus 1080P Webcam                     | 8        | 1.16%   |
| Microdia Camera                          | 8        | 1.16%   |
| Logitech Webcam C310                     | 8        | 1.16%   |
| Logitech HD Webcam C525                  | 8        | 1.16%   |
| Microdia Integrated Camera               | 7        | 1.01%   |
| Sunplus papalook AF 925                  | 6        | 0.87%   |
| Microdia Sonix USB 2.0 Camera            | 6        | 0.87%   |
| MacroSilicon USB Video                   | 6        | 0.87%   |
| Chicony HP High Definition 1MP Webcam    | 6        | 0.87%   |
| Z-Star Venus USB2.0 Camera               | 5        | 0.72%   |
| Realtek USB Camera                       | 5        | 0.72%   |
| Realtek FULL HD 1080P Webcam             | 5        | 0.72%   |
| Logitech Webcam C925e                    | 5        | 0.72%   |
| Logitech StreamCam                       | 5        | 0.72%   |
| Jieli USB PHY 2.0                        | 5        | 0.72%   |
| Generalplus 808 Camera #9 (web-cam mode) | 5        | 0.72%   |
| WaveRider USB 2.0 Camera                 | 4        | 0.58%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 0.58%   |
| Microsoft LifeCam VX-500 [1357]          | 4        | 0.58%   |
| Microsoft LifeCam Studio                 | 4        | 0.58%   |
| Logitech Webcam C930e                    | 4        | 0.58%   |
| Logitech Webcam C250                     | 4        | 0.58%   |
| Logitech QuickCam Pro 9000               | 4        | 0.58%   |
| Logitech QuickCam Communicate MP/S5500   | 4        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 40%     |
| Microsoft             | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| DigitalPersona        | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 40%     |
| Microsoft Fingerprint Reader                   | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 20%     |
| DigitalPersona Fingerprint Reader              | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 7        | 21.88%  |
| Realtek Semiconductor     | 4        | 12.5%   |
| Gemalto (was Gemplus)     | 4        | 12.5%   |
| Alcor Micro               | 4        | 12.5%   |
| SCM Microsystems          | 3        | 9.38%   |
| Chicony Electronics       | 3        | 9.38%   |
| Reiner SCT Kartensysteme  | 1        | 3.13%   |
| Lenovo                    | 1        | 3.13%   |
| Giesecke & Devrient       | 1        | 3.13%   |
| Fujitsu Siemens Computers | 1        | 3.13%   |
| Cherry                    | 1        | 3.13%   |
| BIT4ID                    | 1        | 3.13%   |
| Aladdin Knowledge Systems | 1        | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 12.5%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 12.5%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 9.38%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 9.38%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 9.38%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 9.38%   |
| Advanced Card Systems ACR122U                                              | 2        | 6.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 3.13%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 3.13%   |
| Giesecke & Devrient StarSign CUT S                                         | 1        | 3.13%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.13%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 3.13%   |
| BIT4ID miniLector EVO                                                      | 1        | 3.13%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 3.13%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 3.13%   |
| Advanced Card Systems ACR39U                                               | 1        | 3.13%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3096     | 82.45%  |
| 1     | 547      | 14.57%  |
| 2     | 65       | 1.73%   |
| 3     | 22       | 0.59%   |
| 5     | 10       | 0.27%   |
| 4     | 10       | 0.27%   |
| 8     | 2        | 0.05%   |
| 6     | 2        | 0.05%   |
| 7     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 288      | 36.09%  |
| Net/wireless             | 181      | 22.68%  |
| Unassigned class         | 82       | 10.28%  |
| Communication controller | 58       | 7.27%   |
| Sound                    | 51       | 6.39%   |
| Chipcard                 | 21       | 2.63%   |
| Camera                   | 19       | 2.38%   |
| Bluetooth                | 17       | 2.13%   |
| Multimedia controller    | 16       | 2.01%   |
| Storage/raid             | 15       | 1.88%   |
| Net/ethernet             | 15       | 1.88%   |
| Network                  | 9        | 1.13%   |
| Card reader              | 6        | 0.75%   |
| Dvb card                 | 4        | 0.5%    |
| Storage/nvme             | 3        | 0.38%   |
| Storage/ata              | 3        | 0.38%   |
| Modem                    | 3        | 0.38%   |
| Fingerprint reader       | 3        | 0.38%   |
| Tv card                  | 2        | 0.25%   |
| Wireless                 | 1        | 0.13%   |
| Firewire controller      | 1        | 0.13%   |

