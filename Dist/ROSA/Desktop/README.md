ROSA - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for ROSA.

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

Total: 21611

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550 AORUS ELITE V2         | [0eb501cde5](https://linux-hardware.org/?probe=0eb501cde5) | Jun 30, 2023 |
| Gigabyte      | G33M-S2L                    | [99ffcc407b](https://linux-hardware.org/?probe=99ffcc407b) | Jun 30, 2023 |
| Gigabyte      | B365M DS3H                  | [0272953855](https://linux-hardware.org/?probe=0272953855) | Jun 30, 2023 |
| Gigabyte      | B450M S2H                   | [9a9ca045af](https://linux-hardware.org/?probe=9a9ca045af) | Jun 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [a366d05b2b](https://linux-hardware.org/?probe=a366d05b2b) | Jun 30, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [6a95d2096d](https://linux-hardware.org/?probe=6a95d2096d) | Jun 29, 2023 |
| MSI           | MS-7267 100                 | [3a014aae8a](https://linux-hardware.org/?probe=3a014aae8a) | Jun 29, 2023 |
| ASUSTek       | H81M-C                      | [e12c71fb39](https://linux-hardware.org/?probe=e12c71fb39) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | [d25910c419](https://linux-hardware.org/?probe=d25910c419) | Jun 28, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [6a2c4254e7](https://linux-hardware.org/?probe=6a2c4254e7) | Jun 28, 2023 |
| ASUSTek       | PRIME H510M-K               | [b96f0a3b19](https://linux-hardware.org/?probe=b96f0a3b19) | Jun 27, 2023 |
| Gigabyte      | H410M S2 V2                 | [65794907cc](https://linux-hardware.org/?probe=65794907cc) | Jun 27, 2023 |
| ASUSTek       | PRIME H510M-K               | [a0c358b2b3](https://linux-hardware.org/?probe=a0c358b2b3) | Jun 27, 2023 |
| ASUSTek       | P5P41D                      | [cd85f8d99e](https://linux-hardware.org/?probe=cd85f8d99e) | Jun 27, 2023 |
| ASUSTek       | P5P41D                      | [aaf9376be5](https://linux-hardware.org/?probe=aaf9376be5) | Jun 25, 2023 |
| ASUSTek       | PRIME H510M-K               | [3f74c8ae6f](https://linux-hardware.org/?probe=3f74c8ae6f) | Jun 25, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [02db87eec4](https://linux-hardware.org/?probe=02db87eec4) | Jun 25, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [9f48465b75](https://linux-hardware.org/?probe=9f48465b75) | Jun 24, 2023 |
| MSI           | 760GM-P21                   | [a6ab8ab499](https://linux-hardware.org/?probe=a6ab8ab499) | Jun 24, 2023 |
| ASUSTek       | PRIME H510M-K               | [6da517e892](https://linux-hardware.org/?probe=6da517e892) | Jun 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [d4f7477589](https://linux-hardware.org/?probe=d4f7477589) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | [3708ae400f](https://linux-hardware.org/?probe=3708ae400f) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | [d447bb1029](https://linux-hardware.org/?probe=d447bb1029) | Jun 23, 2023 |
| ASUSTek       | P5VD2-VM                    | [d6e01ed04d](https://linux-hardware.org/?probe=d6e01ed04d) | Jun 23, 2023 |
| ASUSTek       | P5VD2-VM                    | [ec3da2f6be](https://linux-hardware.org/?probe=ec3da2f6be) | Jun 23, 2023 |
| Gigabyte      | G41M-ES2L                   | [d2e49b65bc](https://linux-hardware.org/?probe=d2e49b65bc) | Jun 23, 2023 |
| Gigabyte      | F2A75M-D3H                  | [12fb789329](https://linux-hardware.org/?probe=12fb789329) | Jun 23, 2023 |
| Unknown       | Unknown                     | [cac503031c](https://linux-hardware.org/?probe=cac503031c) | Jun 22, 2023 |
| ASRock        | N68-GS4 FX                  | [c665b54f21](https://linux-hardware.org/?probe=c665b54f21) | Jun 22, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| ASUSTek       | PRIME B450M-K               | [fcb112b431](https://linux-hardware.org/?probe=fcb112b431) | Jun 22, 2023 |
| HP            | 3048h                       | [e4353bb3d2](https://linux-hardware.org/?probe=e4353bb3d2) | Jun 22, 2023 |
| MSI           | H510M-A PRO                 | [5d9a09395c](https://linux-hardware.org/?probe=5d9a09395c) | Jun 22, 2023 |
| HP            | ProLiant ML150 G5           | [9106155d17](https://linux-hardware.org/?probe=9106155d17) | Jun 21, 2023 |
| Gigabyte      | B360M DS3H                  | [f4894017da](https://linux-hardware.org/?probe=f4894017da) | Jun 21, 2023 |
| Gigabyte      | B360M DS3H                  | [f92fdecc78](https://linux-hardware.org/?probe=f92fdecc78) | Jun 21, 2023 |
| Huanan        | B660-D4 V1.0                | [b28fa98f7e](https://linux-hardware.org/?probe=b28fa98f7e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [07f19ac996](https://linux-hardware.org/?probe=07f19ac996) | Jun 20, 2023 |
| ASUSTek       | P8B75-M LE                  | [8e171dc32b](https://linux-hardware.org/?probe=8e171dc32b) | Jun 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [41eb54fba2](https://linux-hardware.org/?probe=41eb54fba2) | Jun 19, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [4be686b049](https://linux-hardware.org/?probe=4be686b049) | Jun 18, 2023 |
| MSI           | B75A-G43                    | [d2399f16bd](https://linux-hardware.org/?probe=d2399f16bd) | Jun 18, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e4eb86f394](https://linux-hardware.org/?probe=e4eb86f394) | Jun 18, 2023 |
| Gigabyte      | B550 GAMING X V2            | [c3b7f0c23e](https://linux-hardware.org/?probe=c3b7f0c23e) | Jun 18, 2023 |
| ASUSTek       | M2A-VM                      | [0d1a4c9975](https://linux-hardware.org/?probe=0d1a4c9975) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [2791b66594](https://linux-hardware.org/?probe=2791b66594) | Jun 17, 2023 |
| Lenovo        | H420                        | [c8d4d2fe1b](https://linux-hardware.org/?probe=c8d4d2fe1b) | Jun 17, 2023 |
| ASRock        | N68-GS4 FX                  | [10376b9b47](https://linux-hardware.org/?probe=10376b9b47) | Jun 17, 2023 |
| Gigabyte      | GA-MA770-US3                | [c7460aff4f](https://linux-hardware.org/?probe=c7460aff4f) | Jun 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [61e45982dc](https://linux-hardware.org/?probe=61e45982dc) | Jun 16, 2023 |
| NCR           | Estoril                     | [d29339575f](https://linux-hardware.org/?probe=d29339575f) | Jun 16, 2023 |
| ASUSTek       | P5QL-CM                     | [13f819c2d6](https://linux-hardware.org/?probe=13f819c2d6) | Jun 16, 2023 |
| ASUSTek       | H97M-E                      | [f3a2b5f30f](https://linux-hardware.org/?probe=f3a2b5f30f) | Jun 15, 2023 |
| MSI           | H81M-P33                    | [49cfb3fdda](https://linux-hardware.org/?probe=49cfb3fdda) | Jun 15, 2023 |
| Unknown       | Unknown                     | [377af23ae8](https://linux-hardware.org/?probe=377af23ae8) | Jun 15, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [a796ed0ed7](https://linux-hardware.org/?probe=a796ed0ed7) | Jun 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | [d7e7c84a43](https://linux-hardware.org/?probe=d7e7c84a43) | Jun 14, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [493866d0e6](https://linux-hardware.org/?probe=493866d0e6) | Jun 14, 2023 |
| Dell          | 0V8WGR A02                  | [448fd1711d](https://linux-hardware.org/?probe=448fd1711d) | Jun 12, 2023 |
| MSI           | A68HM-P33 V2                | [23097e912c](https://linux-hardware.org/?probe=23097e912c) | Jun 12, 2023 |
| Gigabyte      | G31M-ES2L                   | [887dced95a](https://linux-hardware.org/?probe=887dced95a) | Jun 12, 2023 |
| Acer          | Aspire TC-605               | [d28c61c2a7](https://linux-hardware.org/?probe=d28c61c2a7) | Jun 11, 2023 |
| Gigabyte      | 8I865GVMK-775               | [3d90d76b7b](https://linux-hardware.org/?probe=3d90d76b7b) | Jun 10, 2023 |
| Gigabyte      | H410M H                     | [dfba5357ee](https://linux-hardware.org/?probe=dfba5357ee) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [704cc1c02b](https://linux-hardware.org/?probe=704cc1c02b) | Jun 10, 2023 |
| Huanan        | X99 F8D V2.2                | [1eeaac2701](https://linux-hardware.org/?probe=1eeaac2701) | Jun 10, 2023 |
| ASRock        | H610M-ITX/ac                | [80002221f5](https://linux-hardware.org/?probe=80002221f5) | Jun 10, 2023 |
| MSI           | B250M PRO-VH                | [16b496c21d](https://linux-hardware.org/?probe=16b496c21d) | Jun 10, 2023 |
| ASRock        | A320M-DVS R4.0              | [aaf59358b7](https://linux-hardware.org/?probe=aaf59358b7) | Jun 07, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [468f6fe603](https://linux-hardware.org/?probe=468f6fe603) | Jun 06, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [c2f52c637b](https://linux-hardware.org/?probe=c2f52c637b) | Jun 06, 2023 |
| Unknown       | X79                         | [8c1de0f494](https://linux-hardware.org/?probe=8c1de0f494) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [1f07862108](https://linux-hardware.org/?probe=1f07862108) | Jun 05, 2023 |
| ASUSTek       | SABERTOOTH 55i              | [c208cb2024](https://linux-hardware.org/?probe=c208cb2024) | Jun 05, 2023 |
| Gigabyte      | G41MT-S2P                   | [aa5ed8cbc0](https://linux-hardware.org/?probe=aa5ed8cbc0) | Jun 04, 2023 |
| ASRock        | G31M-GS                     | [558dec9114](https://linux-hardware.org/?probe=558dec9114) | Jun 04, 2023 |
| ASRock        | H81M-HDS                    | [248372dd54](https://linux-hardware.org/?probe=248372dd54) | Jun 03, 2023 |
| ASUSTek       | PRIME B450M-A II            | [11e04db670](https://linux-hardware.org/?probe=11e04db670) | Jun 02, 2023 |
| ASUSTek       | B85M-E                      | [ba95473e9c](https://linux-hardware.org/?probe=ba95473e9c) | Jun 02, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [3feb5e9cb5](https://linux-hardware.org/?probe=3feb5e9cb5) | Jun 02, 2023 |
| ASRock        | J3455M                      | [ca1db2cfb9](https://linux-hardware.org/?probe=ca1db2cfb9) | Jun 01, 2023 |
| ASUSTek       | B85M-E                      | [57f47246aa](https://linux-hardware.org/?probe=57f47246aa) | Jun 01, 2023 |
| ASRock        | H81M-HDS                    | [775913e245](https://linux-hardware.org/?probe=775913e245) | Jun 01, 2023 |
| Acer          | WG43M                       | [cdd78e1cac](https://linux-hardware.org/?probe=cdd78e1cac) | May 31, 2023 |
| MSI           | X370 GAMING PLUS            | [ba0b4e2430](https://linux-hardware.org/?probe=ba0b4e2430) | May 31, 2023 |
| ASRock        | FM2A88X-ITX+                | [6a2cd16e95](https://linux-hardware.org/?probe=6a2cd16e95) | May 31, 2023 |
| ASUSTek       | B85M-E                      | [08e31c6634](https://linux-hardware.org/?probe=08e31c6634) | May 31, 2023 |
| ASRock        | A320D4-P1                   | [195945844b](https://linux-hardware.org/?probe=195945844b) | May 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [6bcba3e54d](https://linux-hardware.org/?probe=6bcba3e54d) | May 31, 2023 |
| ASUSTek       | PRIME B450M-A               | [4833d37ec3](https://linux-hardware.org/?probe=4833d37ec3) | May 30, 2023 |
| Biostar       | H610MH                      | [708df29fd6](https://linux-hardware.org/?probe=708df29fd6) | May 30, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [c23ef58095](https://linux-hardware.org/?probe=c23ef58095) | May 30, 2023 |
| ASRock        | B450 Gaming K4              | [2ef322a58d](https://linux-hardware.org/?probe=2ef322a58d) | May 29, 2023 |
| ASUSTek       | B85M-E                      | [eea74e88a5](https://linux-hardware.org/?probe=eea74e88a5) | May 29, 2023 |
| Huanan        | X99 F8D V2.2                | [b4e407cdb0](https://linux-hardware.org/?probe=b4e407cdb0) | May 29, 2023 |
| ASUSTek       | B85M-G                      | [8f51b4170e](https://linux-hardware.org/?probe=8f51b4170e) | May 29, 2023 |
| Gigabyte      | F2A68HM-S1                  | [9b21df1d8e](https://linux-hardware.org/?probe=9b21df1d8e) | May 29, 2023 |
| MSI           | 770-C45                     | [dae0d25fcc](https://linux-hardware.org/?probe=dae0d25fcc) | May 29, 2023 |
| Unknown       | X79                         | [cfda28fe65](https://linux-hardware.org/?probe=cfda28fe65) | May 28, 2023 |
| Gigabyte      | H81M-S1                     | [849ff29f29](https://linux-hardware.org/?probe=849ff29f29) | May 28, 2023 |
| Gigabyte      | H81M-S1                     | [45a2eb8526](https://linux-hardware.org/?probe=45a2eb8526) | May 28, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [ac650845ad](https://linux-hardware.org/?probe=ac650845ad) | May 27, 2023 |
| ASUSTek       | H81M-PLUS                   | [e43931a1af](https://linux-hardware.org/?probe=e43931a1af) | May 27, 2023 |
| Gigabyte      | F2A55M-DS2                  | [f1bfd18361](https://linux-hardware.org/?probe=f1bfd18361) | May 27, 2023 |
| ASRock        | B450 Gaming K4              | [985e20f0ad](https://linux-hardware.org/?probe=985e20f0ad) | May 27, 2023 |
| ASRock        | FM2A68M-DG3+                | [cd4b2a2c6e](https://linux-hardware.org/?probe=cd4b2a2c6e) | May 26, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [4fedff68f1](https://linux-hardware.org/?probe=4fedff68f1) | May 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fc02e21f13](https://linux-hardware.org/?probe=fc02e21f13) | May 25, 2023 |
| Gigabyte      | E350N WIN8                  | [3d858aac61](https://linux-hardware.org/?probe=3d858aac61) | May 25, 2023 |
| ASUSTek       | PRIME B450M-K               | [4670302b3a](https://linux-hardware.org/?probe=4670302b3a) | May 25, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [a5f7973a09](https://linux-hardware.org/?probe=a5f7973a09) | May 25, 2023 |
| Gigabyte      | GA-E240N                    | [f538fa3add](https://linux-hardware.org/?probe=f538fa3add) | May 24, 2023 |
| Gigabyte      | GA-770T-USB3                | [60e294f0e6](https://linux-hardware.org/?probe=60e294f0e6) | May 24, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [0854b7f24a](https://linux-hardware.org/?probe=0854b7f24a) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | [edfd6dd6d9](https://linux-hardware.org/?probe=edfd6dd6d9) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | [43cf78743a](https://linux-hardware.org/?probe=43cf78743a) | May 24, 2023 |
| ASUSTek       | Maximus V GENE              | [64085de9fe](https://linux-hardware.org/?probe=64085de9fe) | May 24, 2023 |
| Acer          | Aspire XC-330               | [5d462a687d](https://linux-hardware.org/?probe=5d462a687d) | May 23, 2023 |
| MSI           | MAG B560M BAZOOKA           | [712c1eecdb](https://linux-hardware.org/?probe=712c1eecdb) | May 23, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [4d067a1511](https://linux-hardware.org/?probe=4d067a1511) | May 22, 2023 |
| MSI           | 770-C45                     | [98672fa54c](https://linux-hardware.org/?probe=98672fa54c) | May 22, 2023 |
| Gigabyte      | B560 HD3                    | [5dd26df23e](https://linux-hardware.org/?probe=5dd26df23e) | May 22, 2023 |
| ASUSTek       | Z97-C                       | [e308a2d977](https://linux-hardware.org/?probe=e308a2d977) | May 22, 2023 |
| ASRock        | H61M-HVGS                   | [653f6e9a8e](https://linux-hardware.org/?probe=653f6e9a8e) | May 20, 2023 |
| Gigabyte      | 970A-DS3P                   | [c43eef4a3a](https://linux-hardware.org/?probe=c43eef4a3a) | May 20, 2023 |
| Gigabyte      | G31M-S2L                    | [927345991a](https://linux-hardware.org/?probe=927345991a) | May 20, 2023 |
| MSI           | Z170A TOMAHAWK              | [ab569c8de9](https://linux-hardware.org/?probe=ab569c8de9) | May 19, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [e1901ac344](https://linux-hardware.org/?probe=e1901ac344) | May 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [d5ffcf1bec](https://linux-hardware.org/?probe=d5ffcf1bec) | May 19, 2023 |
| Gigabyte      | GA-970A-D3                  | [52dbfc4c5a](https://linux-hardware.org/?probe=52dbfc4c5a) | May 19, 2023 |
| Gigabyte      | H510M H                     | [e7949de034](https://linux-hardware.org/?probe=e7949de034) | May 19, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [276b10e762](https://linux-hardware.org/?probe=276b10e762) | May 18, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [286c28d090](https://linux-hardware.org/?probe=286c28d090) | May 18, 2023 |
| ASUSTek       | P8H67-M LE                  | [a6bcd864f3](https://linux-hardware.org/?probe=a6bcd864f3) | May 18, 2023 |
| MSI           | B450M PRO-VDH MAX           | [6c9d197b74](https://linux-hardware.org/?probe=6c9d197b74) | May 18, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | [4651c937d1](https://linux-hardware.org/?probe=4651c937d1) | May 18, 2023 |
| OEM           | X79G                        | [08ece3d402](https://linux-hardware.org/?probe=08ece3d402) | May 18, 2023 |
| Dell          | 0Y5DDC A00                  | [86b17fb9ff](https://linux-hardware.org/?probe=86b17fb9ff) | May 17, 2023 |
| Gigabyte      | EP41-UD3L                   | [adc188c60b](https://linux-hardware.org/?probe=adc188c60b) | May 17, 2023 |
| ASUSTek       | PRIME A320M-E               | [6688a22b2b](https://linux-hardware.org/?probe=6688a22b2b) | May 17, 2023 |
| ASUSTek       | Z97M-PLUS                   | [1455e60d54](https://linux-hardware.org/?probe=1455e60d54) | May 17, 2023 |
| HP            | 1589                        | [2eb60ba617](https://linux-hardware.org/?probe=2eb60ba617) | May 17, 2023 |
| Acer          | Veriton N4680G              | [c1fc339cf0](https://linux-hardware.org/?probe=c1fc339cf0) | May 17, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e814f06497](https://linux-hardware.org/?probe=e814f06497) | May 17, 2023 |
| Gigabyte      | H55M-S2H                    | [e571fb4d7d](https://linux-hardware.org/?probe=e571fb4d7d) | May 17, 2023 |
| Intel         | DG41WV AAE90316-101         | [9bef3b952d](https://linux-hardware.org/?probe=9bef3b952d) | May 16, 2023 |
| Gigabyte      | B450M S2H                   | [03316a0819](https://linux-hardware.org/?probe=03316a0819) | May 16, 2023 |
| ASUSTek       | Z97M-PLUS                   | [930e5f69ed](https://linux-hardware.org/?probe=930e5f69ed) | May 16, 2023 |
| ASUSTek       | A88XM-E                     | [81366d4eb1](https://linux-hardware.org/?probe=81366d4eb1) | May 16, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6586d8eaed](https://linux-hardware.org/?probe=6586d8eaed) | May 15, 2023 |
| Acer          | Aspire TC-705               | [781430f6f0](https://linux-hardware.org/?probe=781430f6f0) | May 15, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [34e7782996](https://linux-hardware.org/?probe=34e7782996) | May 15, 2023 |
| ASRock        | H55M-LE                     | [8da2dc07ec](https://linux-hardware.org/?probe=8da2dc07ec) | May 15, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [08e2dca3fe](https://linux-hardware.org/?probe=08e2dca3fe) | May 14, 2023 |
| Lenovo        | ThinkCentre M71e 3176RV9    | [1f47569d44](https://linux-hardware.org/?probe=1f47569d44) | May 13, 2023 |
| OEM           | X99-Turbo                   | [31cc62203f](https://linux-hardware.org/?probe=31cc62203f) | May 13, 2023 |
| ECS           | IC55H-A                     | [82ad3504a9](https://linux-hardware.org/?probe=82ad3504a9) | May 13, 2023 |
| ASUSTek       | P5B                         | [ef0459f224](https://linux-hardware.org/?probe=ef0459f224) | May 13, 2023 |
| ASRock        | A320M-HDV R4.0              | [af60056caa](https://linux-hardware.org/?probe=af60056caa) | May 12, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [2941682016](https://linux-hardware.org/?probe=2941682016) | May 12, 2023 |
| ASUSTek       | PRIME B560M-K               | [5afcbcef75](https://linux-hardware.org/?probe=5afcbcef75) | May 12, 2023 |
| MSI           | 770-C45                     | [a2b983590a](https://linux-hardware.org/?probe=a2b983590a) | May 12, 2023 |
| MSI           | 770-C45                     | [6f2e35faa1](https://linux-hardware.org/?probe=6f2e35faa1) | May 12, 2023 |
| MSI           | H110M PRO-VD PLUS           | [3eebb3f19d](https://linux-hardware.org/?probe=3eebb3f19d) | May 11, 2023 |
| Gigabyte      | H410M H V3                  | [8726271588](https://linux-hardware.org/?probe=8726271588) | May 11, 2023 |
| Gigabyte      | H410M H V3                  | [ac70f06ddc](https://linux-hardware.org/?probe=ac70f06ddc) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | [54b185860a](https://linux-hardware.org/?probe=54b185860a) | May 10, 2023 |
| HP            | 339A                        | [f5a7934b67](https://linux-hardware.org/?probe=f5a7934b67) | May 10, 2023 |
| Gigabyte      | H97M-D3H                    | [9c9461f26c](https://linux-hardware.org/?probe=9c9461f26c) | May 09, 2023 |
| Gigabyte      | 990XA-UD3                   | [d95065a8fa](https://linux-hardware.org/?probe=d95065a8fa) | May 09, 2023 |
| Gigabyte      | H310M S2H x.x               | [7f25dc4e18](https://linux-hardware.org/?probe=7f25dc4e18) | May 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [12c2931180](https://linux-hardware.org/?probe=12c2931180) | May 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [27ec66031a](https://linux-hardware.org/?probe=27ec66031a) | May 09, 2023 |
| ASRock        | H67DE3/SI                   | [13b1131bef](https://linux-hardware.org/?probe=13b1131bef) | May 08, 2023 |
| MSI           | GF615M-P33                  | [f64f988a79](https://linux-hardware.org/?probe=f64f988a79) | May 08, 2023 |
| ASUSTek       | P8H61-M LX3                 | [9a420c42de](https://linux-hardware.org/?probe=9a420c42de) | May 07, 2023 |
| Gigabyte      | GA-MA770-US3                | [169b0a5bc0](https://linux-hardware.org/?probe=169b0a5bc0) | May 07, 2023 |
| ASUSTek       | PRIME A320M-E               | [a241837604](https://linux-hardware.org/?probe=a241837604) | May 07, 2023 |
| ASUSTek       | P5K                         | [d15b9fb438](https://linux-hardware.org/?probe=d15b9fb438) | May 07, 2023 |
| ASUSTek       | P5K                         | [230147ec2f](https://linux-hardware.org/?probe=230147ec2f) | May 07, 2023 |
| MACHINIST     | E5-RS9 V1.11                | [22b0b37a19](https://linux-hardware.org/?probe=22b0b37a19) | May 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b9d976ae11](https://linux-hardware.org/?probe=b9d976ae11) | May 07, 2023 |
| Acer          | Aspire XC-330               | [9369acb33c](https://linux-hardware.org/?probe=9369acb33c) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b979325eea](https://linux-hardware.org/?probe=b979325eea) | May 07, 2023 |
| Gigabyte      | H61M-S2PH                   | [fe207b0df1](https://linux-hardware.org/?probe=fe207b0df1) | May 07, 2023 |
| ASRock        | B365M-HDV                   | [b9482229ca](https://linux-hardware.org/?probe=b9482229ca) | May 06, 2023 |
| Gigabyte      | GA-A55M-S2HP                | [a56cc8ab0e](https://linux-hardware.org/?probe=a56cc8ab0e) | May 05, 2023 |
| MSI           | X570-A PRO                  | [e11b4303d3](https://linux-hardware.org/?probe=e11b4303d3) | May 05, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5d0bae516f](https://linux-hardware.org/?probe=5d0bae516f) | May 05, 2023 |
| Unknown       | Unknown                     | [22d1fbdeee](https://linux-hardware.org/?probe=22d1fbdeee) | May 05, 2023 |
| MSI           | PRO Z690-A                  | [c2956fd204](https://linux-hardware.org/?probe=c2956fd204) | May 05, 2023 |
| ASUSTek       | M4A785D-M PRO               | [904de435c7](https://linux-hardware.org/?probe=904de435c7) | May 05, 2023 |
| Gigabyte      | G41M-Combo                  | [082d8e2007](https://linux-hardware.org/?probe=082d8e2007) | May 05, 2023 |
| Gigabyte      | GA-970A-UD3                 | [f1dec1f586](https://linux-hardware.org/?probe=f1dec1f586) | May 05, 2023 |
| Gigabyte      | B450M S2H                   | [a79a0e564e](https://linux-hardware.org/?probe=a79a0e564e) | May 04, 2023 |
| Gigabyte      | B450M S2H                   | [831fd306fb](https://linux-hardware.org/?probe=831fd306fb) | May 04, 2023 |
| ASRock        | B450 Gaming K4              | [1a811619bf](https://linux-hardware.org/?probe=1a811619bf) | May 04, 2023 |
| ASUSTek       | H110M-K                     | [b6db5398bf](https://linux-hardware.org/?probe=b6db5398bf) | May 04, 2023 |
| Gigabyte      | GA-970A-UD3                 | [d83f1c354f](https://linux-hardware.org/?probe=d83f1c354f) | May 04, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [586e9d4fec](https://linux-hardware.org/?probe=586e9d4fec) | May 04, 2023 |
| ASUSTek       | P9X79 DELUXE                | [9e96459722](https://linux-hardware.org/?probe=9e96459722) | May 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [bae8fe38e4](https://linux-hardware.org/?probe=bae8fe38e4) | May 03, 2023 |
| MSI           | G41M-P26                    | [19fe6e1910](https://linux-hardware.org/?probe=19fe6e1910) | May 03, 2023 |
| Gigabyte      | H410M H V3                  | [343f821e8c](https://linux-hardware.org/?probe=343f821e8c) | May 03, 2023 |
| Gigabyte      | H410M H V3                  | [100acf14e5](https://linux-hardware.org/?probe=100acf14e5) | May 03, 2023 |
| ASRock        | H510M-HDV                   | [af60ddf275](https://linux-hardware.org/?probe=af60ddf275) | May 03, 2023 |
| ASUSTek       | M5A97 PRO                   | [fda9b0ae93](https://linux-hardware.org/?probe=fda9b0ae93) | May 03, 2023 |
| ASUSTek       | P9X79 DELUXE                | [22fc7d860a](https://linux-hardware.org/?probe=22fc7d860a) | May 03, 2023 |
| Biostar       | G41-M7                      | [7221b8a2f0](https://linux-hardware.org/?probe=7221b8a2f0) | May 02, 2023 |
| ASRock        | B365M-HDV                   | [35293a227b](https://linux-hardware.org/?probe=35293a227b) | May 02, 2023 |
| ASUSTek       | P8H77-V LE                  | [623ff14300](https://linux-hardware.org/?probe=623ff14300) | May 02, 2023 |
| Gigabyte      | B75M-D2V                    | [5a21b5acb8](https://linux-hardware.org/?probe=5a21b5acb8) | May 02, 2023 |
| Intel         | B75                         | [7db60d4b1e](https://linux-hardware.org/?probe=7db60d4b1e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [651d1b1a22](https://linux-hardware.org/?probe=651d1b1a22) | May 01, 2023 |
| Dell          | 0Y5DDC A00                  | [9a9a57dd2b](https://linux-hardware.org/?probe=9a9a57dd2b) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0bf0b828d4](https://linux-hardware.org/?probe=0bf0b828d4) | Apr 30, 2023 |
| ASRock        | B650M PG Riptide            | [236258bd78](https://linux-hardware.org/?probe=236258bd78) | Apr 30, 2023 |
| ASUSTek       | P5K                         | [ea70f7298c](https://linux-hardware.org/?probe=ea70f7298c) | Apr 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [4587583e6a](https://linux-hardware.org/?probe=4587583e6a) | Apr 30, 2023 |
| MSI           | P67A-C43                    | [68f0d09abd](https://linux-hardware.org/?probe=68f0d09abd) | Apr 30, 2023 |
| Gigabyte      | GA-A55M-S2HP                | [4a478780d6](https://linux-hardware.org/?probe=4a478780d6) | Apr 29, 2023 |
| Biostar       | A780L3C                     | [056ea662e6](https://linux-hardware.org/?probe=056ea662e6) | Apr 29, 2023 |
| ECS           | A740GM-M                    | [9e69523c9f](https://linux-hardware.org/?probe=9e69523c9f) | Apr 28, 2023 |
| ASRock        | Z77 Extreme3                | [b0c7bac447](https://linux-hardware.org/?probe=b0c7bac447) | Apr 28, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [93cf85eecd](https://linux-hardware.org/?probe=93cf85eecd) | Apr 28, 2023 |
| HP            | 0B54h D                     | [49c56c77af](https://linux-hardware.org/?probe=49c56c77af) | Apr 28, 2023 |
| ASRock        | N68-VS3 UCC                 | [e30ee0a621](https://linux-hardware.org/?probe=e30ee0a621) | Apr 27, 2023 |
| ASRock        | H510M-HDV/M.2               | [c11c9964fa](https://linux-hardware.org/?probe=c11c9964fa) | Apr 27, 2023 |
| Unknown       | Unknown                     | [59d18b7284](https://linux-hardware.org/?probe=59d18b7284) | Apr 27, 2023 |
| Unknown       | Unknown                     | [8599268159](https://linux-hardware.org/?probe=8599268159) | Apr 27, 2023 |
| ASUSTek       | M4A785D-M PRO               | [ac2a21023c](https://linux-hardware.org/?probe=ac2a21023c) | Apr 27, 2023 |
| Gigabyte      | P75-D3                      | [f9cf28acb8](https://linux-hardware.org/?probe=f9cf28acb8) | Apr 26, 2023 |
| MSI           | A320M PRO-VD/S              | [f147a5df1c](https://linux-hardware.org/?probe=f147a5df1c) | Apr 26, 2023 |
| MSI           | H110M PRO-VD PLUS           | [95bac1f720](https://linux-hardware.org/?probe=95bac1f720) | Apr 26, 2023 |
| Gigabyte      | A320M-H-CF                  | [a1ddcc0d4a](https://linux-hardware.org/?probe=a1ddcc0d4a) | Apr 26, 2023 |
| X79P mothe... | KLLISRE V1.0                | [a7a0059437](https://linux-hardware.org/?probe=a7a0059437) | Apr 26, 2023 |
| Acer          | Extensa M2610 V:1.0         | [4a85453666](https://linux-hardware.org/?probe=4a85453666) | Apr 26, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [8093a43498](https://linux-hardware.org/?probe=8093a43498) | Apr 25, 2023 |
| ASUSTek       | P5QL/EPU                    | [a84428c233](https://linux-hardware.org/?probe=a84428c233) | Apr 25, 2023 |
| Lenovo        | H420                        | [265f943a61](https://linux-hardware.org/?probe=265f943a61) | Apr 25, 2023 |
| HP            | 2B43                        | [aa5fb69f7e](https://linux-hardware.org/?probe=aa5fb69f7e) | Apr 25, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [b9b8640409](https://linux-hardware.org/?probe=b9b8640409) | Apr 25, 2023 |
| ASRock        | H61M-VG3                    | [3427383977](https://linux-hardware.org/?probe=3427383977) | Apr 24, 2023 |
| Gigabyte      | B365M DS3H                  | [90747b3b70](https://linux-hardware.org/?probe=90747b3b70) | Apr 24, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [cac96b2cc9](https://linux-hardware.org/?probe=cac96b2cc9) | Apr 24, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [1a7a3be03e](https://linux-hardware.org/?probe=1a7a3be03e) | Apr 23, 2023 |
| ASRock        | A320M-DVS R4.0              | [ba7ae1ec90](https://linux-hardware.org/?probe=ba7ae1ec90) | Apr 23, 2023 |
| Gigabyte      | H61M-HD2                    | [dd548a2be5](https://linux-hardware.org/?probe=dd548a2be5) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | [9f5177c657](https://linux-hardware.org/?probe=9f5177c657) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | [e263516539](https://linux-hardware.org/?probe=e263516539) | Apr 23, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2f62c287fc](https://linux-hardware.org/?probe=2f62c287fc) | Apr 22, 2023 |
| ASUSTek       | F1A75-V                     | [ac602a38ec](https://linux-hardware.org/?probe=ac602a38ec) | Apr 22, 2023 |
| ASUSTek       | M4A785D-M PRO               | [09791c0d84](https://linux-hardware.org/?probe=09791c0d84) | Apr 22, 2023 |
| ASUSTek       | M4A785D-M PRO               | [62dfd33592](https://linux-hardware.org/?probe=62dfd33592) | Apr 22, 2023 |
| Gigabyte      | P31-S3G                     | [cec5cd32e8](https://linux-hardware.org/?probe=cec5cd32e8) | Apr 21, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [ebd7a2d70a](https://linux-hardware.org/?probe=ebd7a2d70a) | Apr 21, 2023 |
| Gigabyte      | H110-D3-CF                  | [bbf67462c7](https://linux-hardware.org/?probe=bbf67462c7) | Apr 21, 2023 |
| Pegatron      | 2A73h                       | [f4578519ad](https://linux-hardware.org/?probe=f4578519ad) | Apr 21, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [ebc4b3095d](https://linux-hardware.org/?probe=ebc4b3095d) | Apr 21, 2023 |
| ASRock        | H310M-HDV                   | [ee492f099b](https://linux-hardware.org/?probe=ee492f099b) | Apr 21, 2023 |
| ASUSTek       | M4N68T-M LE                 | [4f1e6c6ce7](https://linux-hardware.org/?probe=4f1e6c6ce7) | Apr 21, 2023 |
| ASRock        | H61M-GE                     | [615c74338c](https://linux-hardware.org/?probe=615c74338c) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d3cfdb3436](https://linux-hardware.org/?probe=d3cfdb3436) | Apr 20, 2023 |
| Aquarius      | AQH410T                     | [ecb27c0ff7](https://linux-hardware.org/?probe=ecb27c0ff7) | Apr 20, 2023 |
| Huanan        | X99 F8D V2.2                | [b8c2462ada](https://linux-hardware.org/?probe=b8c2462ada) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [7ac787a4fa](https://linux-hardware.org/?probe=7ac787a4fa) | Apr 20, 2023 |
| Aquarius      | AQH410T                     | [29e8b5bd74](https://linux-hardware.org/?probe=29e8b5bd74) | Apr 20, 2023 |
| Biostar       | H61MHV                      | [7b3d591e47](https://linux-hardware.org/?probe=7b3d591e47) | Apr 20, 2023 |
| Gigabyte      | A320M-H-CF                  | [51afdddffc](https://linux-hardware.org/?probe=51afdddffc) | Apr 20, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | [ba684478b5](https://linux-hardware.org/?probe=ba684478b5) | Apr 20, 2023 |
| MACHINIST     | X99-RS9 V3.1                | [492b8bb4d0](https://linux-hardware.org/?probe=492b8bb4d0) | Apr 19, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ea69ff8c8b](https://linux-hardware.org/?probe=ea69ff8c8b) | Apr 19, 2023 |
| ASRock        | N68-GS4 FX                  | [b01bc53af9](https://linux-hardware.org/?probe=b01bc53af9) | Apr 19, 2023 |
| ASRock        | N68C-GS FX                  | [fc16ea346a](https://linux-hardware.org/?probe=fc16ea346a) | Apr 19, 2023 |
| ASUSTek       | B75M-PLUS                   | [33cd5127f2](https://linux-hardware.org/?probe=33cd5127f2) | Apr 19, 2023 |
| Dell          | 0Y5DDC A00                  | [daff249988](https://linux-hardware.org/?probe=daff249988) | Apr 19, 2023 |
| MSI           | G41M-P33 Combo              | [55ead22ec0](https://linux-hardware.org/?probe=55ead22ec0) | Apr 18, 2023 |
| MSI           | G41M-P33 Combo              | [9fc5380d7a](https://linux-hardware.org/?probe=9fc5380d7a) | Apr 18, 2023 |
| Gigabyte      | H310M S2                    | [02a81434f0](https://linux-hardware.org/?probe=02a81434f0) | Apr 18, 2023 |
| Gigabyte      | 970A-UD3P                   | [38275208cc](https://linux-hardware.org/?probe=38275208cc) | Apr 18, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [d7ebec50bf](https://linux-hardware.org/?probe=d7ebec50bf) | Apr 18, 2023 |
| Biostar       | H81MHV3                     | [384b42f2e6](https://linux-hardware.org/?probe=384b42f2e6) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | [e138e763eb](https://linux-hardware.org/?probe=e138e763eb) | Apr 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | [badd20d374](https://linux-hardware.org/?probe=badd20d374) | Apr 16, 2023 |
| Lenovo        | 367D 31900059 STD           | [e3ebbe3950](https://linux-hardware.org/?probe=e3ebbe3950) | Apr 16, 2023 |
| ASUSTek       | P5K-VM                      | [2c8298a0a8](https://linux-hardware.org/?probe=2c8298a0a8) | Apr 16, 2023 |
| Acer          | Aspire TC-705               | [80bfa42512](https://linux-hardware.org/?probe=80bfa42512) | Apr 16, 2023 |
| MSI           | B450M PRO-M2                | [05ae2ac6e6](https://linux-hardware.org/?probe=05ae2ac6e6) | Apr 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [a70cf56038](https://linux-hardware.org/?probe=a70cf56038) | Apr 15, 2023 |
| ASUSTek       | P8H61-MX                    | [4ad2b2bcdc](https://linux-hardware.org/?probe=4ad2b2bcdc) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [4f8d3b46f5](https://linux-hardware.org/?probe=4f8d3b46f5) | Apr 15, 2023 |
| ASUSTek       | P5KPL-AM                    | [f48937493d](https://linux-hardware.org/?probe=f48937493d) | Apr 15, 2023 |
| MSI           | H81M-P33                    | [e0d66aee3a](https://linux-hardware.org/?probe=e0d66aee3a) | Apr 14, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [57e42e5107](https://linux-hardware.org/?probe=57e42e5107) | Apr 14, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [9e1d9ff252](https://linux-hardware.org/?probe=9e1d9ff252) | Apr 14, 2023 |
| Gigabyte      | G31M-S2L                    | [eaccdb6a68](https://linux-hardware.org/?probe=eaccdb6a68) | Apr 14, 2023 |
| Gigabyte      | A320M-H-CF                  | [ae3ba04308](https://linux-hardware.org/?probe=ae3ba04308) | Apr 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f1f1661f59](https://linux-hardware.org/?probe=f1f1661f59) | Apr 13, 2023 |
| ASUSTek       | P5KPL-AM IN/GB              | [c7c00c395f](https://linux-hardware.org/?probe=c7c00c395f) | Apr 13, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [d05eccd5c7](https://linux-hardware.org/?probe=d05eccd5c7) | Apr 13, 2023 |
| Biostar       | G41D3C                      | [96bf9b40ac](https://linux-hardware.org/?probe=96bf9b40ac) | Apr 13, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [507f555919](https://linux-hardware.org/?probe=507f555919) | Apr 13, 2023 |
| Foxconn       | 2ABF                        | [35a1f24f18](https://linux-hardware.org/?probe=35a1f24f18) | Apr 13, 2023 |
| Gigabyte      | B550 GAMING X V2            | [67fa6790f3](https://linux-hardware.org/?probe=67fa6790f3) | Apr 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [71542ed659](https://linux-hardware.org/?probe=71542ed659) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [fe00316c95](https://linux-hardware.org/?probe=fe00316c95) | Apr 12, 2023 |
| Gigabyte      | M68MT-D3P                   | [695e9c2a36](https://linux-hardware.org/?probe=695e9c2a36) | Apr 12, 2023 |
| HP            | 3048h                       | [c16e3c4fdc](https://linux-hardware.org/?probe=c16e3c4fdc) | Apr 12, 2023 |
| Intel         | B85 V2.2A                   | [1ca186850c](https://linux-hardware.org/?probe=1ca186850c) | Apr 11, 2023 |
| Gigabyte      | GA-78LMT-S2PV               | [a2ddbc2eee](https://linux-hardware.org/?probe=a2ddbc2eee) | Apr 11, 2023 |
| ASUSTek       | Z97-K                       | [8e04d8c50e](https://linux-hardware.org/?probe=8e04d8c50e) | Apr 11, 2023 |
| MSI           | X470 GAMING PRO MAX         | [068934f572](https://linux-hardware.org/?probe=068934f572) | Apr 10, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [6cff2537ae](https://linux-hardware.org/?probe=6cff2537ae) | Apr 10, 2023 |
| Dell          | 0KC9NP A01                  | [fdb331baab](https://linux-hardware.org/?probe=fdb331baab) | Apr 10, 2023 |
| Gigabyte      | H110M-D3H R2-CF             | [4cb2e51f7d](https://linux-hardware.org/?probe=4cb2e51f7d) | Apr 10, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [d2e041bd92](https://linux-hardware.org/?probe=d2e041bd92) | Apr 10, 2023 |
| Biostar       | B250MHC                     | [4fee7821ab](https://linux-hardware.org/?probe=4fee7821ab) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | [f7435e4d65](https://linux-hardware.org/?probe=f7435e4d65) | Apr 09, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [eca06b42fa](https://linux-hardware.org/?probe=eca06b42fa) | Apr 09, 2023 |
| ECS           | H67H2-M3                    | [613fd53405](https://linux-hardware.org/?probe=613fd53405) | Apr 09, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [3af0783523](https://linux-hardware.org/?probe=3af0783523) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | [53ed0bc068](https://linux-hardware.org/?probe=53ed0bc068) | Apr 09, 2023 |
| Intel         | X79M-S                      | [3cec74aa9d](https://linux-hardware.org/?probe=3cec74aa9d) | Apr 09, 2023 |
| MSI           | 2A9C                        | [91d20791c3](https://linux-hardware.org/?probe=91d20791c3) | Apr 09, 2023 |
| HP            | 1495                        | [6a4176bb41](https://linux-hardware.org/?probe=6a4176bb41) | Apr 09, 2023 |
| MSI           | PRO H610M-E DDR4            | [64fbe95b80](https://linux-hardware.org/?probe=64fbe95b80) | Apr 08, 2023 |
| ASRock        | H87 Performance             | [bcf217db06](https://linux-hardware.org/?probe=bcf217db06) | Apr 08, 2023 |
| ASRock        | B550 Extreme4               | [26350ccd3f](https://linux-hardware.org/?probe=26350ccd3f) | Apr 08, 2023 |
| ASUSTek       | VM40B                       | [f371d84955](https://linux-hardware.org/?probe=f371d84955) | Apr 07, 2023 |
| ASRock        | N68PV-GS                    | [bd8595032e](https://linux-hardware.org/?probe=bd8595032e) | Apr 07, 2023 |
| ASRock        | N68-GS4 FX                  | [347c879912](https://linux-hardware.org/?probe=347c879912) | Apr 07, 2023 |
| ASRock        | N68C-GS4 FX                 | [71c25d2dce](https://linux-hardware.org/?probe=71c25d2dce) | Apr 07, 2023 |
| ECS           | GLKD-I2                     | [ee23104ef2](https://linux-hardware.org/?probe=ee23104ef2) | Apr 07, 2023 |
| Gigabyte      | H310M A-CF x.x              | [e37377d08b](https://linux-hardware.org/?probe=e37377d08b) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [a2423b5193](https://linux-hardware.org/?probe=a2423b5193) | Apr 07, 2023 |
| ASUSTek       | B85M-E/BR                   | [66efb7f634](https://linux-hardware.org/?probe=66efb7f634) | Apr 07, 2023 |
| Dell          | 0C2KJT A00                  | [1f006c081e](https://linux-hardware.org/?probe=1f006c081e) | Apr 06, 2023 |
| Gigabyte      | C51-MCP51                   | [64a51d5df8](https://linux-hardware.org/?probe=64a51d5df8) | Apr 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | [495ddacc93](https://linux-hardware.org/?probe=495ddacc93) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [8b89901dc6](https://linux-hardware.org/?probe=8b89901dc6) | Apr 05, 2023 |
| ASRock        | H87 Performance             | [34f591b007](https://linux-hardware.org/?probe=34f591b007) | Apr 05, 2023 |
| Dinson        | Unknown                     | [2cb920a0bd](https://linux-hardware.org/?probe=2cb920a0bd) | Apr 05, 2023 |
| Acer          | Veriton X4110G              | [0acd5d08f8](https://linux-hardware.org/?probe=0acd5d08f8) | Apr 05, 2023 |
| Gigabyte      | C51-MCP51                   | [31ee5c7a85](https://linux-hardware.org/?probe=31ee5c7a85) | Apr 05, 2023 |
| ECS           | GLKD-I2                     | [392f907879](https://linux-hardware.org/?probe=392f907879) | Apr 05, 2023 |
| Gigabyte      | H410M H V3                  | [3a3f22e8aa](https://linux-hardware.org/?probe=3a3f22e8aa) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS M                | [ed948ed552](https://linux-hardware.org/?probe=ed948ed552) | Apr 04, 2023 |
| ASUSTek       | Z97-P                       | [24d0950a77](https://linux-hardware.org/?probe=24d0950a77) | Apr 04, 2023 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [24ac3864d2](https://linux-hardware.org/?probe=24ac3864d2) | Apr 04, 2023 |
| ASRock        | N68-GS4 FX                  | [96928ca8af](https://linux-hardware.org/?probe=96928ca8af) | Apr 04, 2023 |
| ASUSTek       | M2N4-SLI                    | [870bba0c09](https://linux-hardware.org/?probe=870bba0c09) | Apr 03, 2023 |
| ASRock        | B450 Gaming K4              | [86b0411adf](https://linux-hardware.org/?probe=86b0411adf) | Apr 03, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [64fa944dfd](https://linux-hardware.org/?probe=64fa944dfd) | Apr 03, 2023 |
| ASUSTek       | P7H55-USB3                  | [e6ed8a0215](https://linux-hardware.org/?probe=e6ed8a0215) | Apr 03, 2023 |
| Huanan        | X99-BD4 V1.33               | [b11d91c675](https://linux-hardware.org/?probe=b11d91c675) | Apr 02, 2023 |
| ASRock        | H510M-HDV                   | [2cb8a6e1c5](https://linux-hardware.org/?probe=2cb8a6e1c5) | Apr 02, 2023 |
| ASUSTek       | P5KPL-AM                    | [a4e100811d](https://linux-hardware.org/?probe=a4e100811d) | Apr 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [2a898637e8](https://linux-hardware.org/?probe=2a898637e8) | Apr 02, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [c2a49fdbe4](https://linux-hardware.org/?probe=c2a49fdbe4) | Apr 02, 2023 |
| MSI           | H81M-P33                    | [cad337e1e8](https://linux-hardware.org/?probe=cad337e1e8) | Apr 02, 2023 |
| Gigabyte      | Z590M                       | [0d5e6857b8](https://linux-hardware.org/?probe=0d5e6857b8) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9c34c50ec4](https://linux-hardware.org/?probe=9c34c50ec4) | Apr 02, 2023 |
| HP            | 8906 SMVB                   | [74430f2160](https://linux-hardware.org/?probe=74430f2160) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [978a5e2579](https://linux-hardware.org/?probe=978a5e2579) | Apr 01, 2023 |
| Gigabyte      | G41M-Combo                  | [ac658bcb80](https://linux-hardware.org/?probe=ac658bcb80) | Apr 01, 2023 |
| ASUSTek       | M5A78L LE                   | [af64a32a09](https://linux-hardware.org/?probe=af64a32a09) | Apr 01, 2023 |
| MSI           | H510M-A PRO                 | [a6953d3b96](https://linux-hardware.org/?probe=a6953d3b96) | Apr 01, 2023 |
| Unknown       | X79                         | [d0592836a5](https://linux-hardware.org/?probe=d0592836a5) | Apr 01, 2023 |
| Acer          | WG43M                       | [77cb0bf517](https://linux-hardware.org/?probe=77cb0bf517) | Apr 01, 2023 |
| ASUSTek       | P8B75-V                     | [5ed3be8dbc](https://linux-hardware.org/?probe=5ed3be8dbc) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [51c601477f](https://linux-hardware.org/?probe=51c601477f) | Mar 31, 2023 |
| Gigabyte      | Z77X-UD5H                   | [323d8881a5](https://linux-hardware.org/?probe=323d8881a5) | Mar 31, 2023 |
| ASRock        | N68-GS4 FX                  | [573f5db37d](https://linux-hardware.org/?probe=573f5db37d) | Mar 31, 2023 |
| MSI           | H510M-A PRO                 | [49a4903c58](https://linux-hardware.org/?probe=49a4903c58) | Mar 30, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6bb5f276cd](https://linux-hardware.org/?probe=6bb5f276cd) | Mar 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [fecc161428](https://linux-hardware.org/?probe=fecc161428) | Mar 30, 2023 |
| Huanan        | X99-QD4 V1.0                | [d88393be26](https://linux-hardware.org/?probe=d88393be26) | Mar 30, 2023 |
| Acer          | Aspire TC-605               | [5938e606b6](https://linux-hardware.org/?probe=5938e606b6) | Mar 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [0580e11b2f](https://linux-hardware.org/?probe=0580e11b2f) | Mar 29, 2023 |
| ASRock        | B650M PG Riptide            | [f019265109](https://linux-hardware.org/?probe=f019265109) | Mar 29, 2023 |
| Unknown       | Unknown                     | [e62607df55](https://linux-hardware.org/?probe=e62607df55) | Mar 29, 2023 |
| ASRock        | N68PV-GS                    | [1c473cd5c6](https://linux-hardware.org/?probe=1c473cd5c6) | Mar 29, 2023 |
| Gigabyte      | 945P-S3                     | [8aa985b6fa](https://linux-hardware.org/?probe=8aa985b6fa) | Mar 29, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [55a22382cc](https://linux-hardware.org/?probe=55a22382cc) | Mar 29, 2023 |
| ASRock        | 990FX Extreme3              | [ca172328f1](https://linux-hardware.org/?probe=ca172328f1) | Mar 29, 2023 |
| ASRock        | H81M-HDS R2.0               | [1f333c98e1](https://linux-hardware.org/?probe=1f333c98e1) | Mar 29, 2023 |
| Gigabyte      | H410M H V3                  | [10fd7d1526](https://linux-hardware.org/?probe=10fd7d1526) | Mar 28, 2023 |
| MSI           | X370 GAMING PLUS            | [53543ce276](https://linux-hardware.org/?probe=53543ce276) | Mar 28, 2023 |
| Gigabyte      | 946GMX-S2                   | [41f98f54fd](https://linux-hardware.org/?probe=41f98f54fd) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | [b097373c25](https://linux-hardware.org/?probe=b097373c25) | Mar 28, 2023 |
| MSI           | 770-C45                     | [9b23a7e2d0](https://linux-hardware.org/?probe=9b23a7e2d0) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [23438353bb](https://linux-hardware.org/?probe=23438353bb) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [c49cc33482](https://linux-hardware.org/?probe=c49cc33482) | Mar 28, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [727f980b20](https://linux-hardware.org/?probe=727f980b20) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Intel         | X79v2.72 KD V2.0            | [7b9dfca8cc](https://linux-hardware.org/?probe=7b9dfca8cc) | Mar 27, 2023 |
| Foxconn       | 2AA9                        | [97192fc35b](https://linux-hardware.org/?probe=97192fc35b) | Mar 27, 2023 |
| Unknown       | Unknown                     | [6f77d9be36](https://linux-hardware.org/?probe=6f77d9be36) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| Gigabyte      | Z590 D                      | [095ade7803](https://linux-hardware.org/?probe=095ade7803) | Mar 26, 2023 |
| Gigabyte      | H77-DS3H                    | [36d80a146f](https://linux-hardware.org/?probe=36d80a146f) | Mar 26, 2023 |
| Foxconn       | G41MXE-V                    | [38d87a8061](https://linux-hardware.org/?probe=38d87a8061) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbfe5423c9](https://linux-hardware.org/?probe=bbfe5423c9) | Mar 26, 2023 |
| ASUSTek       | M5A78L/USB3                 | [732b7b7fab](https://linux-hardware.org/?probe=732b7b7fab) | Mar 26, 2023 |
| Gigabyte      | F2A55M-S1                   | [fff8f87d2a](https://linux-hardware.org/?probe=fff8f87d2a) | Mar 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [c33415cb2b](https://linux-hardware.org/?probe=c33415cb2b) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| Gigabyte      | B75M-D2V                    | [c98eac375f](https://linux-hardware.org/?probe=c98eac375f) | Mar 25, 2023 |
| Dell          | 01TKCC A01                  | [c250d03840](https://linux-hardware.org/?probe=c250d03840) | Mar 25, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [357a52fe14](https://linux-hardware.org/?probe=357a52fe14) | Mar 25, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f185ea819d](https://linux-hardware.org/?probe=f185ea819d) | Mar 24, 2023 |
| MACHINIST     | X99-RS9 V3.1                | [c1e2b5e7fb](https://linux-hardware.org/?probe=c1e2b5e7fb) | Mar 24, 2023 |
| ASRock        | 990FX Extreme3              | [c310b97b8d](https://linux-hardware.org/?probe=c310b97b8d) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-USB3               | [e6219dd355](https://linux-hardware.org/?probe=e6219dd355) | Mar 24, 2023 |
| HP            | 8906 SMVB                   | [ae7d4327f5](https://linux-hardware.org/?probe=ae7d4327f5) | Mar 24, 2023 |
| Unknown       | X79M2-Q                     | [f517d6c26d](https://linux-hardware.org/?probe=f517d6c26d) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| ASRock        | N68C-GS FX                  | [03da177044](https://linux-hardware.org/?probe=03da177044) | Mar 23, 2023 |
| Gigabyte      | 970-GAMING                  | [f16afa095b](https://linux-hardware.org/?probe=f16afa095b) | Mar 23, 2023 |
| HP            | 3048h                       | [8cee790d83](https://linux-hardware.org/?probe=8cee790d83) | Mar 23, 2023 |
| Gigabyte      | B450M S2H                   | [73d22216c2](https://linux-hardware.org/?probe=73d22216c2) | Mar 23, 2023 |
| MSI           | 760GM-P23                   | [f170457555](https://linux-hardware.org/?probe=f170457555) | Mar 23, 2023 |
| ASUSTek       | H97-PLUS                    | [577716237d](https://linux-hardware.org/?probe=577716237d) | Mar 22, 2023 |
| ASUSTek       | H97-PLUS                    | [32fa1d46e2](https://linux-hardware.org/?probe=32fa1d46e2) | Mar 22, 2023 |
| MACHINIST     | X99-k9 V2.0                 | [24377b0218](https://linux-hardware.org/?probe=24377b0218) | Mar 22, 2023 |
| ASUSTek       | M2N-MX                      | [7eead8bd18](https://linux-hardware.org/?probe=7eead8bd18) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [3a70b6918f](https://linux-hardware.org/?probe=3a70b6918f) | Mar 21, 2023 |
| ASRock        | H470M-HDV                   | [52b14963e3](https://linux-hardware.org/?probe=52b14963e3) | Mar 21, 2023 |
| Unknown       | X79M2-Q                     | [11e2caa120](https://linux-hardware.org/?probe=11e2caa120) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [e128423a13](https://linux-hardware.org/?probe=e128423a13) | Mar 20, 2023 |
| Gigabyte      | B360M DS3H                  | [4df457f6bb](https://linux-hardware.org/?probe=4df457f6bb) | Mar 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9a5bfcc056](https://linux-hardware.org/?probe=9a5bfcc056) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| ASRock        | H310CM-DVS                  | [2ef180bad0](https://linux-hardware.org/?probe=2ef180bad0) | Mar 20, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [e49b9e39d5](https://linux-hardware.org/?probe=e49b9e39d5) | Mar 20, 2023 |
| ASUSTek       | Z97-K                       | [a48a2fbdd0](https://linux-hardware.org/?probe=a48a2fbdd0) | Mar 19, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Dell          | 01TKCC A01                  | [fd02c2aade](https://linux-hardware.org/?probe=fd02c2aade) | Mar 19, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [4f56864a63](https://linux-hardware.org/?probe=4f56864a63) | Mar 19, 2023 |
| Soyo          | SY-Classic B660M            | [cebe1d8722](https://linux-hardware.org/?probe=cebe1d8722) | Mar 19, 2023 |
| HP            | 0A54h                       | [6ec15582a7](https://linux-hardware.org/?probe=6ec15582a7) | Mar 19, 2023 |
| ASRock        | N68C-GS FX                  | [4d50b47e95](https://linux-hardware.org/?probe=4d50b47e95) | Mar 19, 2023 |
| MB            | A320-SF110                  | [588c8f3fe5](https://linux-hardware.org/?probe=588c8f3fe5) | Mar 19, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [99096c6a78](https://linux-hardware.org/?probe=99096c6a78) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e0a2f725e3](https://linux-hardware.org/?probe=e0a2f725e3) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a77ff93d75](https://linux-hardware.org/?probe=a77ff93d75) | Mar 19, 2023 |
| ASRock        | B550 Steel Legend           | [8c50fc6c24](https://linux-hardware.org/?probe=8c50fc6c24) | Mar 19, 2023 |
| ASRock        | B550 Steel Legend           | [2283637069](https://linux-hardware.org/?probe=2283637069) | Mar 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | [1bedc9be7e](https://linux-hardware.org/?probe=1bedc9be7e) | Mar 18, 2023 |
| Gigabyte      | GA-870A-UD3                 | [caf54bddb9](https://linux-hardware.org/?probe=caf54bddb9) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | [d7d537c353](https://linux-hardware.org/?probe=d7d537c353) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | [213f4f774f](https://linux-hardware.org/?probe=213f4f774f) | Mar 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [b33066c1b7](https://linux-hardware.org/?probe=b33066c1b7) | Mar 18, 2023 |
| ASRock        | N68C-GS FX                  | [94b8c06fdd](https://linux-hardware.org/?probe=94b8c06fdd) | Mar 18, 2023 |
| Gigabyte      | G41M-Combo                  | [877608b32b](https://linux-hardware.org/?probe=877608b32b) | Mar 18, 2023 |
| Unknown       | X79M2-Q                     | [fe58227748](https://linux-hardware.org/?probe=fe58227748) | Mar 17, 2023 |
| Biostar       | G41-M7                      | [7109205ef0](https://linux-hardware.org/?probe=7109205ef0) | Mar 17, 2023 |
| ASRock        | N68C-GS FX                  | [814c2e63c6](https://linux-hardware.org/?probe=814c2e63c6) | Mar 17, 2023 |
| Biostar       | G41-M7                      | [b1fe372b7d](https://linux-hardware.org/?probe=b1fe372b7d) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [be0d148aa6](https://linux-hardware.org/?probe=be0d148aa6) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [3b591bcb12](https://linux-hardware.org/?probe=3b591bcb12) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [97ef9205b5](https://linux-hardware.org/?probe=97ef9205b5) | Mar 17, 2023 |
| ASUSTek       | PRIME B250M-K               | [244382a7f5](https://linux-hardware.org/?probe=244382a7f5) | Mar 17, 2023 |
| Dell          | 0VRWRC A00                  | [2159ca2389](https://linux-hardware.org/?probe=2159ca2389) | Mar 16, 2023 |
| ASUSTek       | P7H57D-V EVO                | [f93f85e76d](https://linux-hardware.org/?probe=f93f85e76d) | Mar 16, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [dfe927cc13](https://linux-hardware.org/?probe=dfe927cc13) | Mar 15, 2023 |
| ASRock        | Z77 Extreme3                | [e128413357](https://linux-hardware.org/?probe=e128413357) | Mar 15, 2023 |
| ECS           | K8M890M-M                   | [f38e796f51](https://linux-hardware.org/?probe=f38e796f51) | Mar 15, 2023 |
| Gigabyte      | H55-UD3H                    | [bd69e8e59c](https://linux-hardware.org/?probe=bd69e8e59c) | Mar 15, 2023 |
| ASUSTek       | P5Q SE2                     | [4f76198c2d](https://linux-hardware.org/?probe=4f76198c2d) | Mar 15, 2023 |
| ASRock        | B250M Pro4                  | [98382222cd](https://linux-hardware.org/?probe=98382222cd) | Mar 14, 2023 |
| Gigabyte      | B450M S2H                   | [31a56518c3](https://linux-hardware.org/?probe=31a56518c3) | Mar 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [25f7fa6e96](https://linux-hardware.org/?probe=25f7fa6e96) | Mar 14, 2023 |
| ASRock        | H55M Pro                    | [fe7531d450](https://linux-hardware.org/?probe=fe7531d450) | Mar 14, 2023 |
| MSI           | 770-C45                     | [ec1fc57db4](https://linux-hardware.org/?probe=ec1fc57db4) | Mar 14, 2023 |
| ASUSTek       | P5K                         | [2257feac11](https://linux-hardware.org/?probe=2257feac11) | Mar 14, 2023 |
| Gigabyte      | E350N WIN8                  | [fd71263100](https://linux-hardware.org/?probe=fd71263100) | Mar 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | [72f5663d9d](https://linux-hardware.org/?probe=72f5663d9d) | Mar 13, 2023 |
| Intel         | X79                         | [ae742c13ae](https://linux-hardware.org/?probe=ae742c13ae) | Mar 13, 2023 |
| Gigabyte      | X570 GAMING X               | [d4ebb8d458](https://linux-hardware.org/?probe=d4ebb8d458) | Mar 13, 2023 |
| ASUSTek       | H110M-K                     | [d0e82a7ba0](https://linux-hardware.org/?probe=d0e82a7ba0) | Mar 13, 2023 |
| MSI           | H61M-P32/W8                 | [9eefe8ac8e](https://linux-hardware.org/?probe=9eefe8ac8e) | Mar 13, 2023 |
| Foxconn       | nT-330i                     | [e4b99289c7](https://linux-hardware.org/?probe=e4b99289c7) | Mar 13, 2023 |
| ECS           | K8M890M-M                   | [5adfeea7d1](https://linux-hardware.org/?probe=5adfeea7d1) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [3103d0f0c2](https://linux-hardware.org/?probe=3103d0f0c2) | Mar 12, 2023 |
| Fujitsu       | D2778-D1 S26361-D2778-D1    | [092aec6abe](https://linux-hardware.org/?probe=092aec6abe) | Mar 12, 2023 |
| Gigabyte      | B365M H                     | [1f3f97f186](https://linux-hardware.org/?probe=1f3f97f186) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b1df269b3c](https://linux-hardware.org/?probe=b1df269b3c) | Mar 12, 2023 |
| Dell          | 0M859N A00                  | [4de136eea0](https://linux-hardware.org/?probe=4de136eea0) | Mar 11, 2023 |
| Gigabyte      | H55M-USB3                   | [3633c704cc](https://linux-hardware.org/?probe=3633c704cc) | Mar 11, 2023 |
| Gigabyte      | H55M-USB3                   | [c249ea9094](https://linux-hardware.org/?probe=c249ea9094) | Mar 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [70fe849438](https://linux-hardware.org/?probe=70fe849438) | Mar 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [c3c00e99aa](https://linux-hardware.org/?probe=c3c00e99aa) | Mar 11, 2023 |
| ASRock        | B550 Steel Legend           | [811704abe4](https://linux-hardware.org/?probe=811704abe4) | Mar 11, 2023 |
| ASUSTek       | P5QL/EPU                    | [ccd888c89f](https://linux-hardware.org/?probe=ccd888c89f) | Mar 10, 2023 |
| ASUSTek       | PRIME H510M-R               | [058f4d66e2](https://linux-hardware.org/?probe=058f4d66e2) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [fb2f4741e9](https://linux-hardware.org/?probe=fb2f4741e9) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [9260aaddc7](https://linux-hardware.org/?probe=9260aaddc7) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | [271d259059](https://linux-hardware.org/?probe=271d259059) | Mar 08, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | [4cb9932b91](https://linux-hardware.org/?probe=4cb9932b91) | Mar 08, 2023 |
| ASRock        | B450 Gaming K4              | [ef22a14cc5](https://linux-hardware.org/?probe=ef22a14cc5) | Mar 08, 2023 |
| Gigabyte      | H170-HD3-CF                 | [5785eede0a](https://linux-hardware.org/?probe=5785eede0a) | Mar 08, 2023 |
| Gigabyte      | 8IPE1000-G                  | [58d94793e2](https://linux-hardware.org/?probe=58d94793e2) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [38c0ccd72e](https://linux-hardware.org/?probe=38c0ccd72e) | Mar 08, 2023 |
| Gigabyte      | P35-DS3L                    | [246f8d46b3](https://linux-hardware.org/?probe=246f8d46b3) | Mar 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c4c9827316](https://linux-hardware.org/?probe=c4c9827316) | Mar 08, 2023 |
| ASUSTek       | P5Q-EM                      | [371913da58](https://linux-hardware.org/?probe=371913da58) | Mar 08, 2023 |
| MSI           | A320M-A PRO                 | [ce2373e31a](https://linux-hardware.org/?probe=ce2373e31a) | Mar 07, 2023 |
| MSI           | B450-A PRO MAX              | [55883b5a5d](https://linux-hardware.org/?probe=55883b5a5d) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [887c698c7d](https://linux-hardware.org/?probe=887c698c7d) | Mar 07, 2023 |
| Dell          | 0Y5DDC A00                  | [46fa342e07](https://linux-hardware.org/?probe=46fa342e07) | Mar 07, 2023 |
| EPoX Compu... | MCP61S DDR2: AGF6110-M S... | [537087cc72](https://linux-hardware.org/?probe=537087cc72) | Mar 06, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [2c8192e064](https://linux-hardware.org/?probe=2c8192e064) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85824345a](https://linux-hardware.org/?probe=f85824345a) | Mar 06, 2023 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | [de616ef63b](https://linux-hardware.org/?probe=de616ef63b) | Mar 06, 2023 |
| ASRock        | X470 Gaming K4              | [3884dbf23c](https://linux-hardware.org/?probe=3884dbf23c) | Mar 05, 2023 |
| ASRock        | X470 Gaming K4              | [36b6cd2a7e](https://linux-hardware.org/?probe=36b6cd2a7e) | Mar 05, 2023 |
| Shuttle       | XS35V3                      | [1f391b4852](https://linux-hardware.org/?probe=1f391b4852) | Mar 05, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [93b1720fa7](https://linux-hardware.org/?probe=93b1720fa7) | Mar 05, 2023 |
| Biostar       | A320MH                      | [f4701d1a66](https://linux-hardware.org/?probe=f4701d1a66) | Mar 05, 2023 |
| Dell          | 0T1D10 A01                  | [e42a2e580a](https://linux-hardware.org/?probe=e42a2e580a) | Mar 05, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [8555857264](https://linux-hardware.org/?probe=8555857264) | Mar 05, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [b51b70bc1a](https://linux-hardware.org/?probe=b51b70bc1a) | Mar 05, 2023 |
| Gigabyte      | H110M-D3H R2-CF             | [35866f074d](https://linux-hardware.org/?probe=35866f074d) | Mar 04, 2023 |
| ASRock        | B550 Steel Legend           | [eadfad8fc8](https://linux-hardware.org/?probe=eadfad8fc8) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | [17889079ab](https://linux-hardware.org/?probe=17889079ab) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [dd9492dd43](https://linux-hardware.org/?probe=dd9492dd43) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| Gigabyte      | B75M-HD3                    | [c76495f7b0](https://linux-hardware.org/?probe=c76495f7b0) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | [55b187db64](https://linux-hardware.org/?probe=55b187db64) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | [db674213ce](https://linux-hardware.org/?probe=db674213ce) | Mar 03, 2023 |
| ASUSTek       | PRIME Z370-P II             | [771fd25f9d](https://linux-hardware.org/?probe=771fd25f9d) | Mar 02, 2023 |
| ASUSTek       | PRIME H310M-K               | [8c7ab87113](https://linux-hardware.org/?probe=8c7ab87113) | Mar 02, 2023 |
| Intel         | H61                         | [7bc298c53d](https://linux-hardware.org/?probe=7bc298c53d) | Mar 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [ea9a7523dc](https://linux-hardware.org/?probe=ea9a7523dc) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0a096e93c1](https://linux-hardware.org/?probe=0a096e93c1) | Mar 01, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | [ee3aeec484](https://linux-hardware.org/?probe=ee3aeec484) | Mar 01, 2023 |
| Biostar       | A320MH                      | [d1f48d6cab](https://linux-hardware.org/?probe=d1f48d6cab) | Mar 01, 2023 |
| Gigabyte      | H61M-S1                     | [a37a935237](https://linux-hardware.org/?probe=a37a935237) | Mar 01, 2023 |
| HP            | ProLiant ML350 G5           | [073427bc3c](https://linux-hardware.org/?probe=073427bc3c) | Feb 28, 2023 |
| HP            | ProLiant ML350 Gen9         | [bbad31d175](https://linux-hardware.org/?probe=bbad31d175) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | [5cb2d5ea2c](https://linux-hardware.org/?probe=5cb2d5ea2c) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | [a541b48e4d](https://linux-hardware.org/?probe=a541b48e4d) | Feb 28, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [882168458c](https://linux-hardware.org/?probe=882168458c) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [e4bb117847](https://linux-hardware.org/?probe=e4bb117847) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [732f6c8c00](https://linux-hardware.org/?probe=732f6c8c00) | Feb 27, 2023 |
| ASUSTek       | P7H55                       | [394ad3d24f](https://linux-hardware.org/?probe=394ad3d24f) | Feb 27, 2023 |
| Gigabyte      | B365M D2V                   | [aa39313621](https://linux-hardware.org/?probe=aa39313621) | Feb 27, 2023 |
| Dell          | 0Y5DDC A00                  | [e3090d9725](https://linux-hardware.org/?probe=e3090d9725) | Feb 27, 2023 |
| Gigabyte      | B550M AORUS PRO             | [ffdac8fa88](https://linux-hardware.org/?probe=ffdac8fa88) | Feb 27, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e8e3f57eef](https://linux-hardware.org/?probe=e8e3f57eef) | Feb 26, 2023 |
| ASUSTek       | Z97-K                       | [77a5832b3f](https://linux-hardware.org/?probe=77a5832b3f) | Feb 26, 2023 |
| Dell          | 0UP453                      | [e45bff8252](https://linux-hardware.org/?probe=e45bff8252) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | [2fe5c30b13](https://linux-hardware.org/?probe=2fe5c30b13) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | [4b96538701](https://linux-hardware.org/?probe=4b96538701) | Feb 26, 2023 |
| ASRock        | 880GM-LE                    | [32366172e4](https://linux-hardware.org/?probe=32366172e4) | Feb 26, 2023 |
| ASRock        | AB350 Pro4                  | [887241ec59](https://linux-hardware.org/?probe=887241ec59) | Feb 26, 2023 |
| Unknown       | Intel X79                   | [0f7920afd6](https://linux-hardware.org/?probe=0f7920afd6) | Feb 26, 2023 |
| Unknown       | Unknown                     | [b4e0540b00](https://linux-hardware.org/?probe=b4e0540b00) | Feb 25, 2023 |
| HP            | 1497                        | [bd24913452](https://linux-hardware.org/?probe=bd24913452) | Feb 24, 2023 |
| HP            | 1497                        | [ebf580cb5d](https://linux-hardware.org/?probe=ebf580cb5d) | Feb 24, 2023 |
| ASUSTek       | P5Q-EM                      | [3fef9c126a](https://linux-hardware.org/?probe=3fef9c126a) | Feb 24, 2023 |
| ASRock        | 760GM-GS3                   | [5440ad3270](https://linux-hardware.org/?probe=5440ad3270) | Feb 24, 2023 |
| ASRock        | N68C-GS FX                  | [6b7b16645d](https://linux-hardware.org/?probe=6b7b16645d) | Feb 24, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [4cddc9362b](https://linux-hardware.org/?probe=4cddc9362b) | Feb 23, 2023 |
| MSI           | B450M GAMING PLUS           | [accb966ada](https://linux-hardware.org/?probe=accb966ada) | Feb 23, 2023 |
| Gigabyte      | GA-970A-D3                  | [8b1222a755](https://linux-hardware.org/?probe=8b1222a755) | Feb 23, 2023 |
| MSI           | G31TM-P21                   | [7d6e4cd766](https://linux-hardware.org/?probe=7d6e4cd766) | Feb 23, 2023 |
| ASUSTek       | PRIME H510M-K               | [3dab1052d4](https://linux-hardware.org/?probe=3dab1052d4) | Feb 22, 2023 |
| Unknown       | NF-CK804                    | [3dd6239815](https://linux-hardware.org/?probe=3dd6239815) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [feea587fef](https://linux-hardware.org/?probe=feea587fef) | Feb 22, 2023 |
| ASUSTek       | P8H61-M LX3                 | [af3c7b2459](https://linux-hardware.org/?probe=af3c7b2459) | Feb 22, 2023 |
| ASUSTek       | Z97-K                       | [132a805814](https://linux-hardware.org/?probe=132a805814) | Feb 20, 2023 |
| Huanan        | X99 F8D V2.2                | [c9d8617e08](https://linux-hardware.org/?probe=c9d8617e08) | Feb 20, 2023 |
| Intel         | X79M-S                      | [89ac8fc3ce](https://linux-hardware.org/?probe=89ac8fc3ce) | Feb 20, 2023 |
| ASUSTek       | P8H61-M LX3                 | [509f76c7ec](https://linux-hardware.org/?probe=509f76c7ec) | Feb 20, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [45e185354c](https://linux-hardware.org/?probe=45e185354c) | Feb 20, 2023 |
| Gigabyte      | 945P-S3                     | [2cdcb107ab](https://linux-hardware.org/?probe=2cdcb107ab) | Feb 20, 2023 |
| Gigabyte      | H61M-S1                     | [82ab7aabe2](https://linux-hardware.org/?probe=82ab7aabe2) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | [970f04658e](https://linux-hardware.org/?probe=970f04658e) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | [331f606733](https://linux-hardware.org/?probe=331f606733) | Feb 19, 2023 |
| Dell          | 0Y5DDC A00                  | [87c921a93a](https://linux-hardware.org/?probe=87c921a93a) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [b8b41b7a6e](https://linux-hardware.org/?probe=b8b41b7a6e) | Feb 19, 2023 |
| Gigabyte      | H410M S2H                   | [bdb8c0094b](https://linux-hardware.org/?probe=bdb8c0094b) | Feb 18, 2023 |
| OEM           | Intel H81                   | [2dc44e8ff2](https://linux-hardware.org/?probe=2dc44e8ff2) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Biostar       | H61MLB                      | [b79584c7c9](https://linux-hardware.org/?probe=b79584c7c9) | Feb 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [55a53738ee](https://linux-hardware.org/?probe=55a53738ee) | Feb 17, 2023 |
| MSI           | B460M PRO-VDH               | [38f8f579be](https://linux-hardware.org/?probe=38f8f579be) | Feb 17, 2023 |
| HP            | 3031h                       | [f3d2748999](https://linux-hardware.org/?probe=f3d2748999) | Feb 17, 2023 |
| Gigabyte      | B360M DS3H                  | [1ceaa9af7d](https://linux-hardware.org/?probe=1ceaa9af7d) | Feb 17, 2023 |
| ASRock        | 760GM-GS3                   | [88433e4e24](https://linux-hardware.org/?probe=88433e4e24) | Feb 16, 2023 |
| Intel         | DP67BA AAG10219-300         | [8fc0c69640](https://linux-hardware.org/?probe=8fc0c69640) | Feb 16, 2023 |
| MSI           | G41M-P28                    | [85efceb14b](https://linux-hardware.org/?probe=85efceb14b) | Feb 16, 2023 |
| ASRock        | N68C-GS FX                  | [bc0fe319be](https://linux-hardware.org/?probe=bc0fe319be) | Feb 15, 2023 |
| ASRock        | Z77 Pro3                    | [095671c1c9](https://linux-hardware.org/?probe=095671c1c9) | Feb 15, 2023 |
| Dell          | 0Y5DDC A00                  | [261e3ca363](https://linux-hardware.org/?probe=261e3ca363) | Feb 15, 2023 |
| Unknown       | X79A                        | [4cf2d15d70](https://linux-hardware.org/?probe=4cf2d15d70) | Feb 14, 2023 |
| Gigabyte      | Z87-HD3                     | [e856a4629d](https://linux-hardware.org/?probe=e856a4629d) | Feb 14, 2023 |
| ASRock        | AQH410T                     | [9ca03a8dcd](https://linux-hardware.org/?probe=9ca03a8dcd) | Feb 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | [da50295fcc](https://linux-hardware.org/?probe=da50295fcc) | Feb 14, 2023 |
| Gigabyte      | B450M S2H                   | [2120a2f3b5](https://linux-hardware.org/?probe=2120a2f3b5) | Feb 13, 2023 |
| Gigabyte      | B450M DS3H V2               | [6338542845](https://linux-hardware.org/?probe=6338542845) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c66b51a84d](https://linux-hardware.org/?probe=c66b51a84d) | Feb 13, 2023 |
| Gigabyte      | H510M S2H V2                | [e3580e73af](https://linux-hardware.org/?probe=e3580e73af) | Feb 13, 2023 |
| Biostar       | A320MH                      | [d51405079c](https://linux-hardware.org/?probe=d51405079c) | Feb 13, 2023 |
| ASUSTek       | M2N-E SLI                   | [8bf6aedf43](https://linux-hardware.org/?probe=8bf6aedf43) | Feb 12, 2023 |
| Huanan        | X99 F8D V2.2                | [7b98ade6b1](https://linux-hardware.org/?probe=7b98ade6b1) | Feb 12, 2023 |
| ASRock        | B450M Pro4                  | [8f60713f8a](https://linux-hardware.org/?probe=8f60713f8a) | Feb 12, 2023 |
| Gigabyte      | B550M DS3H                  | [06dc671402](https://linux-hardware.org/?probe=06dc671402) | Feb 12, 2023 |
| MSI           | MS-7369                     | [f2d9a7a428](https://linux-hardware.org/?probe=f2d9a7a428) | Feb 12, 2023 |
| MSI           | 770-C45                     | [80cd4311f5](https://linux-hardware.org/?probe=80cd4311f5) | Feb 12, 2023 |
| OEM           | Intel H81                   | [89ca7b56ce](https://linux-hardware.org/?probe=89ca7b56ce) | Feb 12, 2023 |
| Unknown       | X79A                        | [d2cdf88906](https://linux-hardware.org/?probe=d2cdf88906) | Feb 12, 2023 |
| Medion        | TJ4105                      | [b9f44d3290](https://linux-hardware.org/?probe=b9f44d3290) | Feb 11, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [0207d4f5eb](https://linux-hardware.org/?probe=0207d4f5eb) | Feb 11, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [4a3b0fd844](https://linux-hardware.org/?probe=4a3b0fd844) | Feb 11, 2023 |
| Huanan        | X99 F8D V2.2                | [226310e919](https://linux-hardware.org/?probe=226310e919) | Feb 10, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d88dcef939](https://linux-hardware.org/?probe=d88dcef939) | Feb 10, 2023 |
| ASUSTek       | PRIME H510M-K               | [ad01ef1c97](https://linux-hardware.org/?probe=ad01ef1c97) | Feb 10, 2023 |
| EPoX Compu... | nForce4 DDR: 9NPA3I / 9N... | [978c5bad53](https://linux-hardware.org/?probe=978c5bad53) | Feb 10, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [31d8a68d71](https://linux-hardware.org/?probe=31d8a68d71) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [2a366ac100](https://linux-hardware.org/?probe=2a366ac100) | Feb 09, 2023 |
| Gigabyte      | H61M-S2PV                   | [6cd301542b](https://linux-hardware.org/?probe=6cd301542b) | Feb 09, 2023 |
| Unknown       | X99H                        | [722aafff41](https://linux-hardware.org/?probe=722aafff41) | Feb 09, 2023 |
| Huanan        | B75 V10.1 376               | [f501974f04](https://linux-hardware.org/?probe=f501974f04) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| ASUSTek       | P5Q DELUXE                  | [6c056321fa](https://linux-hardware.org/?probe=6c056321fa) | Feb 08, 2023 |
| ASUSTek       | P7H55-USB3                  | [0c02735e75](https://linux-hardware.org/?probe=0c02735e75) | Feb 08, 2023 |
| ASRock        | A320M-DVS R4.0              | [8fb4060e1f](https://linux-hardware.org/?probe=8fb4060e1f) | Feb 08, 2023 |
| ASRock        | B450M Pro4-F                | [133f0c845d](https://linux-hardware.org/?probe=133f0c845d) | Feb 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| ASUSTek       | P7H55-USB3                  | [8d7cca4218](https://linux-hardware.org/?probe=8d7cca4218) | Feb 07, 2023 |
| Dell          | 0Y5DDC A00                  | [35c52844f5](https://linux-hardware.org/?probe=35c52844f5) | Feb 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [b6c83b73c5](https://linux-hardware.org/?probe=b6c83b73c5) | Feb 07, 2023 |
| Pegatron      | 2A73h                       | [6745d62f6e](https://linux-hardware.org/?probe=6745d62f6e) | Feb 07, 2023 |
| HP            | 0AA0h                       | [921b7f0d0c](https://linux-hardware.org/?probe=921b7f0d0c) | Feb 07, 2023 |
| Gigabyte      | B450M S2H V2                | [62a01ed1f1](https://linux-hardware.org/?probe=62a01ed1f1) | Feb 07, 2023 |
| ASUSTek       | P8B75-V                     | [04d1d12416](https://linux-hardware.org/?probe=04d1d12416) | Feb 07, 2023 |
| Gigabyte      | B560 HD3                    | [ab4ab47498](https://linux-hardware.org/?probe=ab4ab47498) | Feb 06, 2023 |
| ASUSTek       | P5QL/EPU                    | [32c834326a](https://linux-hardware.org/?probe=32c834326a) | Feb 06, 2023 |
| Acer          | FMCP7A-ION-LE               | [4567c6a09c](https://linux-hardware.org/?probe=4567c6a09c) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ebe7e665d6](https://linux-hardware.org/?probe=ebe7e665d6) | Feb 05, 2023 |
| ASUSTek       | PRIME Z270-P                | [8884f6f6dd](https://linux-hardware.org/?probe=8884f6f6dd) | Feb 05, 2023 |
| Huanan        | X79 VAA1                    | [62888124bd](https://linux-hardware.org/?probe=62888124bd) | Feb 05, 2023 |
| Acer          | WG43M                       | [e463181f54](https://linux-hardware.org/?probe=e463181f54) | Feb 05, 2023 |
| ASRock        | G41M-VS3                    | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| ASUSTek       | M2N                         | [cc5d457ca6](https://linux-hardware.org/?probe=cc5d457ca6) | Feb 05, 2023 |
| ASRock        | A75M-HVS                    | [74c7bde15c](https://linux-hardware.org/?probe=74c7bde15c) | Feb 05, 2023 |
| ASUSTek       | M4A785T-M                   | [5402edfed1](https://linux-hardware.org/?probe=5402edfed1) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| JGINYUE       | H97I GAMING V1.0            | [d83687e8ea](https://linux-hardware.org/?probe=d83687e8ea) | Feb 03, 2023 |
| Biostar       | A320MH                      | [61f708d874](https://linux-hardware.org/?probe=61f708d874) | Feb 03, 2023 |
| Gigabyte      | 990XA-UD3                   | [f26da18faa](https://linux-hardware.org/?probe=f26da18faa) | Feb 02, 2023 |
| MSI           | 770-C45                     | [fa06564503](https://linux-hardware.org/?probe=fa06564503) | Feb 02, 2023 |
| MSI           | Z87-GD65 GAMING             | [0021264c10](https://linux-hardware.org/?probe=0021264c10) | Feb 02, 2023 |
| Gigabyte      | X58A-UD3R                   | [e29b47f46f](https://linux-hardware.org/?probe=e29b47f46f) | Feb 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3b016839cd](https://linux-hardware.org/?probe=3b016839cd) | Feb 02, 2023 |
| Biostar       | G41-M7                      | [862afd5a70](https://linux-hardware.org/?probe=862afd5a70) | Feb 01, 2023 |
| Gigabyte      | B560 HD3                    | [477504bfc6](https://linux-hardware.org/?probe=477504bfc6) | Feb 01, 2023 |
| ASUSTek       | H110M-R                     | [c790793197](https://linux-hardware.org/?probe=c790793197) | Feb 01, 2023 |
| Unknown       | Unknown                     | [7e53e3c6e8](https://linux-hardware.org/?probe=7e53e3c6e8) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| Gigabyte      | B550 GAMING X V2            | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| ASRock        | Z77M                        | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Unknown       | X79                         | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| MSI           | 770-C45                     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| MSI           | 770-C45                     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| MSI           | 770-C45                     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| Gigabyte      | B450M S2H V2                | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| Biostar       | G41-M7                      | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Gigabyte      | F2A55M-DS2                  | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| ECS           | G41T-M7                     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| Huanan        | X99-F8D V2.4                | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| AZW           | U59                         | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Biostar       | A780LB                      | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| ASUSTek       | P4P800                      | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| Intel         | DG41MJ AAE54659-206         | [98a0ca82de](https://linux-hardware.org/?probe=98a0ca82de) | Jan 18, 2023 |
| Lenovo        | ThinkCentre M57e 6305B2U    | [fbd4306314](https://linux-hardware.org/?probe=fbd4306314) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | [a42e9dbc36](https://linux-hardware.org/?probe=a42e9dbc36) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | [d4147630a1](https://linux-hardware.org/?probe=d4147630a1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| Biostar       | A780LB                      | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| ECS           | G41T-M7                     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| ASUSTek       | P5E-VM SE                   | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASRock        | B450M Pro4                  | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| Acer          | Aspire TC-605               | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| ASRock        | Z77 Extreme3                | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| MB            | A320-SF110                  | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| MB            | A320-SF110                  | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| MSI           | H61M-P20                    | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| ASRock        | Z77M                        | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| ASUSTek       | A55BM-PLUS                  | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Unknown       | Unknown                     | [5194029152](https://linux-hardware.org/?probe=5194029152) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| ECS           | G41T-M2                     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| Lenovo        | H420                        | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | [f75b0a7e71](https://linux-hardware.org/?probe=f75b0a7e71) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | [ee31a67035](https://linux-hardware.org/?probe=ee31a67035) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| Gigabyte      | H55M-USB3                   | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| AZW           | U59                         | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| Gigabyte      | B550 GAMING X               | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| ASRock        | B450 Gaming K4              | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Dell          | 0XHGV1 A01                  | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| Gigabyte      | B365M DS3H                  | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| HP            | 0AACh                       | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| ASRock        | B365M-HDV                   | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASRock        | H510M-HDV R2.0              | [70312467b7](https://linux-hardware.org/?probe=70312467b7) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| HP            | 0AACh                       | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Gigabyte      | EP43-S3L                    | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| ASRock        | Z77M                        | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| ASUSTek       | PRIME B450M-K               | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |
| Intel         | MAHOBAY                     | [7f8c2370d4](https://linux-hardware.org/?probe=7f8c2370d4) | Dec 19, 2022 |
| Gigabyte      | GA-K8NE                     | [64adeb3e60](https://linux-hardware.org/?probe=64adeb3e60) | Dec 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [626b750c51](https://linux-hardware.org/?probe=626b750c51) | Dec 18, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [320ef20ffa](https://linux-hardware.org/?probe=320ef20ffa) | Dec 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e864dc271](https://linux-hardware.org/?probe=7e864dc271) | Dec 18, 2022 |
| Gigabyte      | P41T-D3P                    | [20f90ee21e](https://linux-hardware.org/?probe=20f90ee21e) | Dec 18, 2022 |
| MSI           | MS-B0A41                    | [3eff37d029](https://linux-hardware.org/?probe=3eff37d029) | Dec 18, 2022 |
| Gigabyte      | H110N-CF                    | [239dcc2a5c](https://linux-hardware.org/?probe=239dcc2a5c) | Dec 18, 2022 |
| ASUSTek       | A88XM-A                     | [e889711ed9](https://linux-hardware.org/?probe=e889711ed9) | Dec 17, 2022 |
| ASUSTek       | M2N-XE                      | [5cf5b3eb1b](https://linux-hardware.org/?probe=5cf5b3eb1b) | Dec 17, 2022 |
| ASRock        | X570 Pro4                   | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [74133cd0bd](https://linux-hardware.org/?probe=74133cd0bd) | Dec 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0eb4a7c919](https://linux-hardware.org/?probe=0eb4a7c919) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [d34f278afd](https://linux-hardware.org/?probe=d34f278afd) | Dec 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [f0303dc0a9](https://linux-hardware.org/?probe=f0303dc0a9) | Dec 17, 2022 |
| Gigabyte      | H81-D3                      | [547126e9e7](https://linux-hardware.org/?probe=547126e9e7) | Dec 17, 2022 |
| Gigabyte      | H110M-M2-CF                 | [11c0643905](https://linux-hardware.org/?probe=11c0643905) | Dec 16, 2022 |
| Graviton      | DMB-H510-MCA01              | [702f634fc4](https://linux-hardware.org/?probe=702f634fc4) | Dec 16, 2022 |
| Gigabyte      | P75-D3                      | [32b4b4d664](https://linux-hardware.org/?probe=32b4b4d664) | Dec 16, 2022 |
| Huanan        | X99-QD4 V1.0                | [a959e56dc8](https://linux-hardware.org/?probe=a959e56dc8) | Dec 15, 2022 |
| Intel         | SHARKBAY                    | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| MSI           | K9N6PGM2-V2                 | [c25f374572](https://linux-hardware.org/?probe=c25f374572) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [6367cb9215](https://linux-hardware.org/?probe=6367cb9215) | Dec 15, 2022 |
| ASRock        | A520M Pro4                  | [9a6fcc5f1b](https://linux-hardware.org/?probe=9a6fcc5f1b) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [766e33e4fb](https://linux-hardware.org/?probe=766e33e4fb) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [db904895cc](https://linux-hardware.org/?probe=db904895cc) | Dec 15, 2022 |
| ASUSTek       | F2A55-M LE                  | [f4c6e3c225](https://linux-hardware.org/?probe=f4c6e3c225) | Dec 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [5093772c0f](https://linux-hardware.org/?probe=5093772c0f) | Dec 14, 2022 |
| Intel         | X79v2.72 KD V2.0            | [0e58af2a59](https://linux-hardware.org/?probe=0e58af2a59) | Dec 14, 2022 |
| Gigabyte      | B85M-D3V-A                  | [22431e9b10](https://linux-hardware.org/?probe=22431e9b10) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [0e9eba0773](https://linux-hardware.org/?probe=0e9eba0773) | Dec 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [af674c6b1b](https://linux-hardware.org/?probe=af674c6b1b) | Dec 13, 2022 |
| ASUSTek       | PRIME H270-PRO              | [dc7d6ae170](https://linux-hardware.org/?probe=dc7d6ae170) | Dec 13, 2022 |
| Intel         | X79v2.72 KD V2.0            | [476f1e7cad](https://linux-hardware.org/?probe=476f1e7cad) | Dec 12, 2022 |
| MSI           | K9N6PGM2-V2                 | [f09e3c0e19](https://linux-hardware.org/?probe=f09e3c0e19) | Dec 12, 2022 |
| Gigabyte      | B450 GAMING X               | [8918608744](https://linux-hardware.org/?probe=8918608744) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [2e0158ba73](https://linux-hardware.org/?probe=2e0158ba73) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [c6e03bcd07](https://linux-hardware.org/?probe=c6e03bcd07) | Dec 12, 2022 |
| Gigabyte      | M61SME-S2                   | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f0fa1101ce](https://linux-hardware.org/?probe=f0fa1101ce) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [dcd96a2b45](https://linux-hardware.org/?probe=dcd96a2b45) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [9f9fafa75b](https://linux-hardware.org/?probe=9f9fafa75b) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [f883834ef1](https://linux-hardware.org/?probe=f883834ef1) | Dec 11, 2022 |
| HP            | 8860 A                      | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [9f72d262ef](https://linux-hardware.org/?probe=9f72d262ef) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [8bd005fd95](https://linux-hardware.org/?probe=8bd005fd95) | Dec 11, 2022 |
| ASUSTek       | PRIME B360M-K               | [aac6da2dfb](https://linux-hardware.org/?probe=aac6da2dfb) | Dec 11, 2022 |
| Gigabyte      | H77-DS3H                    | [4c52e333dd](https://linux-hardware.org/?probe=4c52e333dd) | Dec 10, 2022 |
| ASRock        | H81M-HDS R2.0               | [e3c2a2bc54](https://linux-hardware.org/?probe=e3c2a2bc54) | Dec 10, 2022 |
| Intel         | D2500HN AAG81480-500        | [0963fa0173](https://linux-hardware.org/?probe=0963fa0173) | Dec 10, 2022 |
| ASUSTek       | PRIME B350M-A               | [619a4c2f87](https://linux-hardware.org/?probe=619a4c2f87) | Dec 10, 2022 |
| ASRock        | 760GM-HDV                   | [bbd75ce275](https://linux-hardware.org/?probe=bbd75ce275) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [941668ad89](https://linux-hardware.org/?probe=941668ad89) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fc07cad186](https://linux-hardware.org/?probe=fc07cad186) | Dec 10, 2022 |
| HP            | 158A                        | [ebcf08f784](https://linux-hardware.org/?probe=ebcf08f784) | Dec 10, 2022 |
| ASRock        | H97 Anniversary             | [3f7aa1b6de](https://linux-hardware.org/?probe=3f7aa1b6de) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [f064a744ba](https://linux-hardware.org/?probe=f064a744ba) | Dec 10, 2022 |
| ASUSTek       | Z170-A                      | [c9df3386c5](https://linux-hardware.org/?probe=c9df3386c5) | Dec 10, 2022 |
| Gigabyte      | H61N-USB3                   | [9a8885a88d](https://linux-hardware.org/?probe=9a8885a88d) | Dec 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [75f1600dba](https://linux-hardware.org/?probe=75f1600dba) | Dec 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ed30003f61](https://linux-hardware.org/?probe=ed30003f61) | Dec 09, 2022 |
| Gigabyte      | D425TUD                     | [4d8c330a78](https://linux-hardware.org/?probe=4d8c330a78) | Dec 09, 2022 |
| HP            | 18E7                        | [3ae864582a](https://linux-hardware.org/?probe=3ae864582a) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [b4bd04a5a0](https://linux-hardware.org/?probe=b4bd04a5a0) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [56a6a749bb](https://linux-hardware.org/?probe=56a6a749bb) | Dec 09, 2022 |
| Gigabyte      | G31M-S2L                    | [05707c88e0](https://linux-hardware.org/?probe=05707c88e0) | Dec 08, 2022 |
| Gigabyte      | H81M-S1                     | [c2ba58af35](https://linux-hardware.org/?probe=c2ba58af35) | Dec 08, 2022 |
| Biostar       | GF8200C M2+                 | [e42ae4deef](https://linux-hardware.org/?probe=e42ae4deef) | Dec 08, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [4462cb3156](https://linux-hardware.org/?probe=4462cb3156) | Dec 08, 2022 |
| Gigabyte      | P31-ES3G                    | [21c291e1e2](https://linux-hardware.org/?probe=21c291e1e2) | Dec 08, 2022 |
| Huanan        | X99 F8D V2.2                | [d960add854](https://linux-hardware.org/?probe=d960add854) | Dec 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | [bedb81f629](https://linux-hardware.org/?probe=bedb81f629) | Dec 08, 2022 |
| Aquarius      | AQB560M                     | [3ac41202cf](https://linux-hardware.org/?probe=3ac41202cf) | Dec 08, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| ASUSTek       | PRIME B460M-K               | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| eMachines     | ET1350                      | [2d05a7a068](https://linux-hardware.org/?probe=2d05a7a068) | Dec 07, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [038581b13f](https://linux-hardware.org/?probe=038581b13f) | Dec 07, 2022 |
| ASUSTek       | M2N-XE                      | [663b3c7870](https://linux-hardware.org/?probe=663b3c7870) | Dec 06, 2022 |
| ASRock        | P67 Pro                     | [74b28c3c76](https://linux-hardware.org/?probe=74b28c3c76) | Dec 06, 2022 |
| ASRock        | B450M-HDV                   | [afeed5f423](https://linux-hardware.org/?probe=afeed5f423) | Dec 05, 2022 |
| Gigabyte      | 970A-DS3P                   | [517e06781a](https://linux-hardware.org/?probe=517e06781a) | Dec 05, 2022 |
| Gigabyte      | B450 GAMING X               | [c8b886d9bf](https://linux-hardware.org/?probe=c8b886d9bf) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [0301ad14ee](https://linux-hardware.org/?probe=0301ad14ee) | Dec 05, 2022 |
| MSI           | H97 PC Mate                 | [b8081159ab](https://linux-hardware.org/?probe=b8081159ab) | Dec 05, 2022 |
| ASUSTek       | PRIME B450M-A               | [10dd0b119a](https://linux-hardware.org/?probe=10dd0b119a) | Dec 04, 2022 |
| Unknown       | Unknown                     | [bdf0020add](https://linux-hardware.org/?probe=bdf0020add) | Dec 04, 2022 |
| HP            | 2AAC                        | [a6fb7751ed](https://linux-hardware.org/?probe=a6fb7751ed) | Dec 04, 2022 |
| Intel         | DG41CN AAE82429-102         | [8d5cd3253c](https://linux-hardware.org/?probe=8d5cd3253c) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [d3c99c8d63](https://linux-hardware.org/?probe=d3c99c8d63) | Dec 04, 2022 |
| Intel         | D2500HN AAG34776-404        | [b1ccefe421](https://linux-hardware.org/?probe=b1ccefe421) | Dec 04, 2022 |
| ASUSTek       | H81M-C                      | [0218d4ec25](https://linux-hardware.org/?probe=0218d4ec25) | Dec 03, 2022 |
| Gigabyte      | P35-DS3                     | [f4be331a61](https://linux-hardware.org/?probe=f4be331a61) | Dec 03, 2022 |
| ASUSTek       | H81M-C                      | [ea7168ab4c](https://linux-hardware.org/?probe=ea7168ab4c) | Dec 03, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [1d881e7756](https://linux-hardware.org/?probe=1d881e7756) | Dec 03, 2022 |
| ASRock        | K10N78D                     | [7d0d581c7a](https://linux-hardware.org/?probe=7d0d581c7a) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [f1e82e8a2a](https://linux-hardware.org/?probe=f1e82e8a2a) | Dec 03, 2022 |
| Gigabyte      | 970A-UD3P                   | [7bb879efed](https://linux-hardware.org/?probe=7bb879efed) | Dec 03, 2022 |
| Gigabyte      | MZBSWMP-00                  | [76ba1ef6f2](https://linux-hardware.org/?probe=76ba1ef6f2) | Dec 03, 2022 |
| MSI           | P67S-C43                    | [9674663124](https://linux-hardware.org/?probe=9674663124) | Dec 03, 2022 |
| ASUSTek       | Z170M-PLUS                  | [a39dbe7189](https://linux-hardware.org/?probe=a39dbe7189) | Dec 03, 2022 |
| Intel         | JSL MRD                     | [1a63097a67](https://linux-hardware.org/?probe=1a63097a67) | Dec 02, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5c0129ab3f](https://linux-hardware.org/?probe=5c0129ab3f) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [eaaeeb57fe](https://linux-hardware.org/?probe=eaaeeb57fe) | Dec 02, 2022 |
| HP            | 18E7                        | [37c3c7db33](https://linux-hardware.org/?probe=37c3c7db33) | Dec 02, 2022 |
| 3Q            | TD2500G-P-Q3 A01            | [46626558f6](https://linux-hardware.org/?probe=46626558f6) | Dec 01, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [16680c5211](https://linux-hardware.org/?probe=16680c5211) | Dec 01, 2022 |
| Gigabyte      | B450 GAMING X               | [ff5aef2f59](https://linux-hardware.org/?probe=ff5aef2f59) | Dec 01, 2022 |
| MSI           | H81M-E33                    | [aa874580d3](https://linux-hardware.org/?probe=aa874580d3) | Dec 01, 2022 |
| HP            | 8184 X4                     | [2b5ea5e34c](https://linux-hardware.org/?probe=2b5ea5e34c) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| ASUSTek       | P8H77-V LE                  | [d82ed03dd9](https://linux-hardware.org/?probe=d82ed03dd9) | Dec 01, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4ae619c728](https://linux-hardware.org/?probe=4ae619c728) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| ASUSTek       | H81M-C                      | [458ea4bd06](https://linux-hardware.org/?probe=458ea4bd06) | Nov 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [99c33f6741](https://linux-hardware.org/?probe=99c33f6741) | Nov 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R10           | 2140     | 13.37%  |
| ROSA R11           | 2089     | 13.05%  |
| ROSA R8            | 1892     | 11.82%  |
| ROSA R6            | 1778     | 11.11%  |
| ROSA R7            | 1692     | 10.57%  |
| ROSA R8.1          | 1459     | 9.11%   |
| ROSA R9            | 1277     | 7.98%   |
| ROSA R11.1         | 1176     | 7.35%   |
| ROSA 12.2          | 1034     | 6.46%   |
| ROSA 12.3          | 498      | 3.11%   |
| ROSA R5            | 244      | 1.52%   |
| ROSA 12.4          | 242      | 1.51%   |
| ROSA 12.1          | 189      | 1.18%   |
| ROSA 12            | 125      | 0.78%   |
| ROSA R4            | 42       | 0.26%   |
| ROSA R12           | 42       | 0.26%   |
| ROSA R3            | 26       | 0.16%   |
| ROSA 2019.05       | 14       | 0.09%   |
| ROSA R9-R11        | 12       | 0.07%   |
| ROSA Chrome 2.0    | 7        | 0.04%   |
| ROSA R2            | 6        | 0.04%   |
| ROSA 2012.0        | 5        | 0.03%   |
| ROSA 13.0          | 4        | 0.02%   |
| ROSA R4-R8         | 3        | 0.02%   |
| ROSA Nickel 2019.0 | 3        | 0.02%   |
| ROSA 2021.1        | 3        | 0.02%   |
| ROSA DX 1.0        | 2        | 0.01%   |
| ROSA R1            | 1        | 0.01%   |
| ROSA 2019.0        | 1        | 0.01%   |
| ROSA 1.0           | 1        | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| ROSA | 13204    | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 1048     | 6.06%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 950      | 5.49%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 938      | 5.42%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 922      | 5.33%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 918      | 5.31%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 862      | 4.98%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 745      | 4.31%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 500      | 2.89%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 437      | 2.53%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 399      | 2.31%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 351      | 2.03%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 330      | 1.91%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 306      | 1.77%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 291      | 1.68%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 262      | 1.51%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 256      | 1.48%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 256      | 1.48%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 244      | 1.41%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 235      | 1.36%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 232      | 1.34%   |
| 4.15.0-desktop-45.1rosa-i586        | 221      | 1.28%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 218      | 1.26%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 218      | 1.26%   |
| 5.4.32-generic-2rosa-x86_64         | 217      | 1.25%   |
| 5.4.83-generic-2rosa-x86_64         | 197      | 1.14%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 194      | 1.12%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 184      | 1.06%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 178      | 1.03%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 178      | 1.03%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 178      | 1.03%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 178      | 1.03%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 175      | 1.01%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 154      | 0.89%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 145      | 0.84%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 143      | 0.83%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 143      | 0.83%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 132      | 0.76%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 126      | 0.73%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 124      | 0.72%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 118      | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2246     | 13.24%  |
| 3.14.44  | 1381     | 8.14%   |
| 4.9.60   | 1297     | 7.65%   |
| 4.9.20   | 1167     | 6.88%   |
| 4.1.25   | 1161     | 6.85%   |
| 4.1.15   | 959      | 5.65%   |
| 5.10.74  | 937      | 5.52%   |
| 4.1.34   | 690      | 4.07%   |
| 4.1.38   | 588      | 3.47%   |
| 4.9.9    | 503      | 2.97%   |
| 4.9.124  | 475      | 2.8%    |
| 4.9.155  | 365      | 2.15%   |
| 4.1.16   | 329      | 1.94%   |
| 4.9.76   | 321      | 1.89%   |
| 5.4.32   | 292      | 1.72%   |
| 4.9.41   | 283      | 1.67%   |
| 5.4.83   | 245      | 1.44%   |
| 4.1.22   | 196      | 1.16%   |
| 3.14.53  | 195      | 1.15%   |
| 4.1.19   | 192      | 1.13%   |
| 5.15.75  | 191      | 1.13%   |
| 5.10.118 | 188      | 1.11%   |
| 6.1.20   | 184      | 1.08%   |
| 4.1.33   | 177      | 1.04%   |
| 4.9.95   | 162      | 0.96%   |
| 5.15.79  | 154      | 0.91%   |
| 4.1.13   | 148      | 0.87%   |
| 4.9.111  | 135      | 0.8%    |
| 5.10.71  | 118      | 0.7%    |
| 4.9.87   | 96       | 0.57%   |
| 3.14.33  | 91       | 0.54%   |
| 3.14.25  | 87       | 0.51%   |
| 4.9.14   | 54       | 0.32%   |
| 5.4.40   | 53       | 0.31%   |
| 3.14.39  | 52       | 0.31%   |
| 5.17.11  | 51       | 0.3%    |
| 5.10.155 | 47       | 0.28%   |
| 4.9.34   | 45       | 0.27%   |
| 5.15.77  | 40       | 0.24%   |
| 5.10.150 | 35       | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 4223     | 27.59%  |
| 4.1     | 3915     | 25.58%  |
| 4.15    | 2252     | 14.71%  |
| 3.14    | 1766     | 11.54%  |
| 5.10    | 1251     | 8.17%   |
| 5.4     | 622      | 4.06%   |
| 5.15    | 443      | 2.89%   |
| 6.1     | 203      | 1.33%   |
| 4.4     | 67       | 0.44%   |
| 5.18    | 53       | 0.35%   |
| 5.17    | 51       | 0.33%   |
| 4.8     | 38       | 0.25%   |
| 6.0     | 35       | 0.23%   |
| 3.10    | 32       | 0.21%   |
| 5.0     | 26       | 0.17%   |
| 4.7     | 26       | 0.17%   |
| 4.13    | 26       | 0.17%   |
| 4.19    | 23       | 0.15%   |
| 4.16    | 22       | 0.14%   |
| 4.6     | 20       | 0.13%   |
| 4.18    | 20       | 0.13%   |
| 3.18    | 19       | 0.12%   |
| 5.16    | 15       | 0.1%    |
| 5.5     | 13       | 0.08%   |
| 4.14    | 13       | 0.08%   |
| 4.3     | 12       | 0.08%   |
| 4.2     | 12       | 0.08%   |
| 4.17    | 12       | 0.08%   |
| 5.3     | 11       | 0.07%   |
| 4.5     | 11       | 0.07%   |
| 4.0     | 10       | 0.07%   |
| 5.2     | 8        | 0.05%   |
| 6.2     | 7        | 0.05%   |
| 4.12    | 6        | 0.04%   |
| 4.11    | 6        | 0.04%   |
| 3.0     | 6        | 0.04%   |
| 5.8     | 5        | 0.03%   |
| 5.9     | 4        | 0.03%   |
| 3.19    | 4        | 0.03%   |
| 6.3     | 3        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10526    | 77.87%  |
| i686   | 2991     | 22.13%  |
| e2k    | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE4       | 9191     | 64.64%  |
| KDE5       | 3395     | 23.88%  |
| GNOME      | 797      | 5.61%   |
| LXQt       | 412      | 2.9%    |
| MATE       | 179      | 1.26%   |
| XFCE       | 110      | 0.77%   |
| LXDE       | 73       | 0.51%   |
| Unknown    | 57       | 0.4%    |
| KDE        | 2        | 0.01%   |
| X-Cinnamon | 1        | 0.01%   |
| Cinnamon   | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 11935    | 88.3%   |
| Wayland | 1572     | 11.63%  |
| Tty     | 7        | 0.05%   |
| Unknown | 3        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 9294     | 65.75%  |
| SDDM    | 3593     | 25.42%  |
| GDM     | 1120     | 7.92%   |
| LightDM | 54       | 0.38%   |
| TDM     | 51       | 0.36%   |
| Unknown | 15       | 0.11%   |
| XDM     | 8        | 0.06%   |
| LDM     | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 10637    | 77.7%   |
| ru_RU       | 2701     | 19.73%  |
| en_US       | 87       | 0.64%   |
| de_DE       | 47       | 0.34%   |
| pl_PL       | 36       | 0.26%   |
| es_ES       | 27       | 0.2%    |
| pt_BR       | 26       | 0.19%   |
| fr_FR       | 24       | 0.18%   |
| it_IT       | 18       | 0.13%   |
| ru_UA       | 16       | 0.12%   |
| en_GB       | 14       | 0.1%    |
| pt_PT       | 7        | 0.05%   |
| ro_RO       | 6        | 0.04%   |
| hu_HU       | 4        | 0.03%   |
| es_AR       | 4        | 0.03%   |
| C           | 4        | 0.03%   |
| sk_SK       | 3        | 0.02%   |
| es_MX       | 3        | 0.02%   |
| es_CO       | 3        | 0.02%   |
| cs_CZ       | 3        | 0.02%   |
| el_GR       | 2        | 0.01%   |
| tr_TR       | 1        | 0.01%   |
| sr_RS@latin | 1        | 0.01%   |
| sr_ME       | 1        | 0.01%   |
| ru_KZ       | 1        | 0.01%   |
| ru_BY       | 1        | 0.01%   |
| lt_LT       | 1        | 0.01%   |
| ja_JP       | 1        | 0.01%   |
| fr_BE       | 1        | 0.01%   |
| es_VE       | 1        | 0.01%   |
| es_UY       | 1        | 0.01%   |
| es_PE       | 1        | 0.01%   |
| en_IN       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| de_CH       | 1        | 0.01%   |
| Default     | 1        | 0.01%   |
| bg_BG       | 1        | 0.01%   |
| be_BY       | 1        | 0.01%   |
| ar_EG       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11014    | 81.4%   |
| EFI  | 2516     | 18.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 8297     | 59.24%  |
| Ext4     | 5413     | 38.65%  |
| Btrfs    | 203      | 1.45%   |
| Ext3     | 40       | 0.29%   |
| Ext2     | 16       | 0.11%   |
| Xfs      | 13       | 0.09%   |
| F2fs     | 9        | 0.06%   |
| SAMSUNG  | 6        | 0.04%   |
| Aufs     | 3        | 0.02%   |
| Reiserfs | 2        | 0.01%   |
| Overlay  | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |
| 2G       | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 8632     | 60.69%  |
| GPT     | 3023     | 21.26%  |
| Unknown | 2567     | 18.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12031    | 87.95%  |
| Yes       | 1649     | 12.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10657    | 76.78%  |
| Yes       | 3223     | 23.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4717     | 35.72%  |
| Gigabyte Technology | 3061     | 23.18%  |
| ASRock              | 1462     | 11.07%  |
| MSI                 | 1370     | 10.38%  |
| Intel               | 342      | 2.59%   |
| ECS                 | 293      | 2.22%   |
| Hewlett-Packard     | 277      | 2.1%    |
| Dell                | 216      | 1.64%   |
| Biostar             | 212      | 1.61%   |
| Unknown             | 173      | 1.31%   |
| Foxconn             | 171      | 1.3%    |
| Acer                | 161      | 1.22%   |
| Lenovo              | 137      | 1.04%   |
| Pegatron            | 109      | 0.83%   |
| Huanan              | 39       | 0.3%    |
| Fujitsu             | 38       | 0.29%   |
| Fujitsu Siemens     | 35       | 0.27%   |
| EPoX Computer       | 35       | 0.27%   |
| WinFast             | 33       | 0.25%   |
| Nvidia              | 18       | 0.14%   |
| ABIT                | 18       | 0.14%   |
| Medion              | 16       | 0.12%   |
| Packard Bell        | 15       | 0.11%   |
| Supermicro          | 13       | 0.1%    |
| SiS Technology      | 11       | 0.08%   |
| AMD                 | 10       | 0.08%   |
| Shuttle             | 9        | 0.07%   |
| JW Technology       | 9        | 0.07%   |
| eMachines           | 9        | 0.07%   |
| OEM                 | 8        | 0.06%   |
| MACHINIST           | 8        | 0.06%   |
| IBM                 | 7        | 0.05%   |
| ZOTAC               | 6        | 0.05%   |
| PCChips             | 6        | 0.05%   |
| Lite-On             | 5        | 0.04%   |
| EVGA                | 5        | 0.04%   |
| Colorful Technology | 5        | 0.04%   |
| AMI                 | 5        | 0.04%   |
| VIA Technologies    | 4        | 0.03%   |
| Positivo            | 4        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 366      | 2.77%   |
| Unknown                    | 188      | 1.42%   |
| ASUS M5A78L-M LX3          | 78       | 0.59%   |
| MSI MS-7817                | 76       | 0.58%   |
| ASUS M5A97 R2.0            | 68       | 0.51%   |
| ASRock G31M-S              | 66       | 0.5%    |
| Gigabyte 970A-DS3P         | 63       | 0.48%   |
| ASRock N68C-S UCC          | 60       | 0.45%   |
| MSI MS-7529                | 57       | 0.43%   |
| Gigabyte H61M-S1           | 56       | 0.42%   |
| Gigabyte G31M-ES2L         | 56       | 0.42%   |
| ASUS P5K                   | 55       | 0.42%   |
| MSI MS-7592                | 54       | 0.41%   |
| ASUS P5KPL-AM              | 49       | 0.37%   |
| ASUS P5B                   | 49       | 0.37%   |
| ASUS P8H61-M LX3 R2.0      | 48       | 0.36%   |
| MSI MS-7309                | 46       | 0.35%   |
| ASUS P8Z77-V LX            | 46       | 0.35%   |
| MSI MS-7788                | 45       | 0.34%   |
| ASUS P5G41T-M LX2/GB       | 45       | 0.34%   |
| ASUS M5A97 LE R2.0         | 45       | 0.34%   |
| ASUS P5KPL-AM IN/ROEM/SI   | 43       | 0.33%   |
| ASRock G41M-VS3            | 41       | 0.31%   |
| MSI MS-7721                | 40       | 0.3%    |
| MSI MS-7693                | 40       | 0.3%    |
| Gigabyte G41M-Combo        | 40       | 0.3%    |
| ASUS SABERTOOTH 990FX R2.0 | 40       | 0.3%    |
| ASUS H110M-R               | 40       | 0.3%    |
| Gigabyte H61M-S2PV         | 38       | 0.29%   |
| MSI MS-7369                | 37       | 0.28%   |
| ASUS M5A78L-M/USB3         | 37       | 0.28%   |
| ASUS P5Q SE2               | 35       | 0.27%   |
| ASUS P5GC-MX/1333          | 35       | 0.27%   |
| MSI MS-7758                | 32       | 0.24%   |
| ASUS P8H61-M LE            | 32       | 0.24%   |
| ASUS P5G41T-M LX           | 32       | 0.24%   |
| MSI MS-7680                | 31       | 0.23%   |
| Gigabyte Z77-DS3H          | 31       | 0.23%   |
| ASUS P5KPL-AM SE           | 31       | 0.23%   |
| ASUS M2N                   | 31       | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS All            | 366      | 2.77%   |
| ASUS M5A78L-M       | 207      | 1.57%   |
| ASUS PRIME          | 202      | 1.53%   |
| ASUS P8H61-M        | 189      | 1.43%   |
| Unknown             | 188      | 1.42%   |
| ASUS P5KPL-AM       | 162      | 1.23%   |
| ASUS M5A97          | 155      | 1.17%   |
| HP Compaq           | 146      | 1.11%   |
| Dell OptiPlex       | 145      | 1.1%    |
| ASUS P5K            | 141      | 1.07%   |
| ASUS P8Z77-V        | 132      | 1%      |
| ASUS P5G41T-M       | 119      | 0.9%    |
| Acer Aspire         | 110      | 0.83%   |
| ASUS P5Q            | 107      | 0.81%   |
| MSI MS-7817         | 76       | 0.58%   |
| ASUS SABERTOOTH     | 71       | 0.54%   |
| Lenovo ThinkCentre  | 69       | 0.52%   |
| ASRock G31M-S       | 66       | 0.5%    |
| Gigabyte 970A-DS3P  | 64       | 0.48%   |
| ASRock N68C-S       | 62       | 0.47%   |
| MSI MS-7529         | 57       | 0.43%   |
| ASUS P5B            | 57       | 0.43%   |
| Gigabyte H61M-S1    | 56       | 0.42%   |
| Gigabyte G31M-ES2L  | 56       | 0.42%   |
| ASUS P5GC-MX        | 55       | 0.42%   |
| MSI MS-7592         | 54       | 0.41%   |
| ASUS P8H61-MX       | 48       | 0.36%   |
| ASUS P8B75-M        | 47       | 0.36%   |
| ASRock 970          | 47       | 0.36%   |
| MSI MS-7309         | 46       | 0.35%   |
| ASUS P8H77-V        | 46       | 0.35%   |
| MSI MS-7788         | 45       | 0.34%   |
| ASUS M2N-MX         | 44       | 0.33%   |
| ASUS M5A78L         | 43       | 0.33%   |
| ASRock G41M-VS3     | 41       | 0.31%   |
| MSI MS-7721         | 40       | 0.3%    |
| MSI MS-7693         | 40       | 0.3%    |
| Gigabyte G41M-Combo | 40       | 0.3%    |
| ASUS P8H67-M        | 40       | 0.3%    |
| ASUS P7H55-M        | 40       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1873     | 14.19%  |
| 2009    | 1442     | 10.92%  |
| 2011    | 1344     | 10.18%  |
| 2010    | 1267     | 9.6%    |
| 2008    | 1168     | 8.85%   |
| 2007    | 1140     | 8.63%   |
| 2013    | 1048     | 7.94%   |
| 2006    | 782      | 5.92%   |
| 2014    | 567      | 4.29%   |
| 2018    | 408      | 3.09%   |
| 2016    | 384      | 2.91%   |
| 2015    | 384      | 2.91%   |
| 2005    | 335      | 2.54%   |
| 2017    | 261      | 1.98%   |
| 2019    | 204      | 1.54%   |
| 2021    | 152      | 1.15%   |
| 2020    | 147      | 1.11%   |
| 2004    | 126      | 0.95%   |
| 2003    | 76       | 0.58%   |
| 2022    | 43       | 0.33%   |
| Unknown | 32       | 0.24%   |
| 2002    | 13       | 0.1%    |
| 2001    | 4        | 0.03%   |
| 2023    | 3        | 0.02%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 13204    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13204    | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13203    | 99.99%  |
| Yes  | 1        | 0.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 4256     | 30.39%  |
| 8.01-16.0   | 3017     | 21.55%  |
| 4.01-8.0    | 1860     | 13.28%  |
| 1.01-2.0    | 1491     | 10.65%  |
| 16.01-24.0  | 1312     | 9.37%   |
| 2.01-3.0    | 1187     | 8.48%   |
| 32.01-64.0  | 301      | 2.15%   |
| 0.51-1.0    | 291      | 2.08%   |
| Unknown     | 153      | 1.09%   |
| 24.01-32.0  | 81       | 0.58%   |
| 64.01-256.0 | 36       | 0.26%   |
| 0.01-0.5    | 18       | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 6938     | 45.26%  |
| 1.01-2.0   | 5991     | 39.08%  |
| 2.01-3.0   | 1154     | 7.53%   |
| 0.01-0.5   | 529      | 3.45%   |
| 3.01-4.0   | 288      | 1.88%   |
| 4.01-8.0   | 221      | 1.44%   |
| Unknown    | 178      | 1.16%   |
| 8.01-16.0  | 25       | 0.16%   |
| 16.01-24.0 | 5        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 7348     | 51.72%  |
| 2       | 3946     | 27.78%  |
| 3       | 1812     | 12.76%  |
| 4       | 633      | 4.46%   |
| 5       | 233      | 1.64%   |
| 0       | 109      | 0.77%   |
| 6       | 85       | 0.6%    |
| 7       | 20       | 0.14%   |
| 8       | 10       | 0.07%   |
| 9       | 5        | 0.04%   |
| Unknown | 4        | 0.03%   |
| 10      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8795     | 64.46%  |
| No        | 4850     | 35.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13066    | 98.95%  |
| No        | 139      | 1.05%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10273    | 76.1%   |
| Yes       | 3226     | 23.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12100    | 90.37%  |
| Yes       | 1290     | 9.63%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 7678     | 55.21%  |
| Unknown     | 4036     | 29.02%  |
| Ukraine     | 547      | 3.93%   |
| Belarus     | 173      | 1.24%   |
| Germany     | 166      | 1.19%   |
| Poland      | 147      | 1.06%   |
| Kazakhstan  | 125      | 0.9%    |
| France      | 94       | 0.68%   |
| Italy       | 93       | 0.67%   |
| USA         | 91       | 0.65%   |
| Brazil      | 76       | 0.55%   |
| Spain       | 49       | 0.35%   |
| UK          | 42       | 0.3%    |
| Moldova     | 42       | 0.3%    |
| Canada      | 38       | 0.27%   |
| Romania     | 31       | 0.22%   |
| Mexico      | 29       | 0.21%   |
| Austria     | 23       | 0.17%   |
| Israel      | 21       | 0.15%   |
| Serbia      | 20       | 0.14%   |
| Bulgaria    | 20       | 0.14%   |
| Latvia      | 18       | 0.13%   |
| Czechia     | 18       | 0.13%   |
| Netherlands | 17       | 0.12%   |
| Slovakia    | 16       | 0.12%   |
| Estonia     | 16       | 0.12%   |
| Australia   | 15       | 0.11%   |
| Lithuania   | 13       | 0.09%   |
| Argentina   | 13       | 0.09%   |
| Sweden      | 12       | 0.09%   |
| Venezuela   | 11       | 0.08%   |
| Greece      | 11       | 0.08%   |
| Switzerland | 10       | 0.07%   |
| Kyrgyzstan  | 10       | 0.07%   |
| Hungary     | 10       | 0.07%   |
| Finland     | 10       | 0.07%   |
| Colombia    | 10       | 0.07%   |
| Uzbekistan  | 9        | 0.06%   |
| Turkey      | 9        | 0.06%   |
| Belgium     | 9        | 0.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 4036     | 27.25%  |
| Moscow           | 1136     | 7.67%   |
| St Petersburg    | 462      | 3.12%   |
| Pecherskoye      | 416      | 2.81%   |
| Novosibirsk      | 282      | 1.9%    |
| Krasnodar        | 208      | 1.4%    |
| Yekaterinburg    | 204      | 1.38%   |
| Samara           | 203      | 1.37%   |
| Nizhniy Novgorod | 179      | 1.21%   |
| Rostov-on-Don    | 175      | 1.18%   |
| Chelyabinsk      | 140      | 0.95%   |
| Perm             | 136      | 0.92%   |
| Voronezh         | 125      | 0.84%   |
| Saratov          | 117      | 0.79%   |
| Krasnoyarsk      | 117      | 0.79%   |
| Omsk             | 102      | 0.69%   |
| Volgograd        | 92       | 0.62%   |
| Stavropol        | 82       | 0.55%   |
| Kazan’         | 82       | 0.55%   |
| Barnaul          | 82       | 0.55%   |
| Tyumen           | 74       | 0.5%    |
| Khabarovsk       | 72       | 0.49%   |
| Vladivostok      | 71       | 0.48%   |
| Orenburg         | 68       | 0.46%   |
| Bryansk          | 61       | 0.41%   |
| Ufa              | 60       | 0.41%   |
| Minsk            | 60       | 0.41%   |
| Irkutsk          | 59       | 0.4%    |
| Lipetsk          | 57       | 0.38%   |
| Kemerovo         | 57       | 0.38%   |
| Novokuznetsk     | 56       | 0.38%   |
| Yaroslavl        | 55       | 0.37%   |
| Tula             | 54       | 0.36%   |
| Tomsk            | 53       | 0.36%   |
| Ulyanovsk        | 52       | 0.35%   |
| Belgorod         | 52       | 0.35%   |
| Tolyatti         | 50       | 0.34%   |
| Kyiv             | 50       | 0.34%   |
| Izhevsk          | 47       | 0.32%   |
| Astrakhan        | 47       | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5917     | 9893   | 28.23%  |
| WDC                 | 5431     | 9282   | 25.91%  |
| Samsung Electronics | 1924     | 2982   | 9.18%   |
| Hitachi             | 1413     | 2026   | 6.74%   |
| Toshiba             | 1163     | 1739   | 5.55%   |
| Kingston            | 849      | 1229   | 4.05%   |
| Maxtor              | 477      | 611    | 2.28%   |
| OCZ                 | 275      | 366    | 1.31%   |
| A-DATA Technology   | 267      | 398    | 1.27%   |
| SPCC                | 262      | 363    | 1.25%   |
| China               | 229      | 316    | 1.09%   |
| SanDisk             | 226      | 337    | 1.08%   |
| Crucial             | 196      | 294    | 0.94%   |
| Plextor             | 183      | 289    | 0.87%   |
| Intel               | 182      | 318    | 0.87%   |
| HGST                | 154      | 225    | 0.73%   |
| HUAWEI              | 150      | 179    | 0.72%   |
| Apacer              | 117      | 165    | 0.56%   |
| Smartbuy            | 95       | 130    | 0.45%   |
| Corsair             | 89       | 116    | 0.42%   |
| AMD                 | 79       | 100    | 0.38%   |
| Transcend           | 78       | 110    | 0.37%   |
| GOODRAM             | 78       | 111    | 0.37%   |
| Patriot             | 76       | 98     | 0.36%   |
| KingSpec            | 67       | 82     | 0.32%   |
| Fujitsu             | 54       | 64     | 0.26%   |
| Unknown             | 51       | 93     | 0.24%   |
| Gigabyte Technology | 43       | 60     | 0.21%   |
| Silicon Motion      | 39       | 47     | 0.19%   |
| Netac               | 39       | 47     | 0.19%   |
| KingDian            | 39       | 59     | 0.19%   |
| TF CARD             | 34       | 41     | 0.16%   |
| Kingmax             | 32       | 66     | 0.15%   |
| ZTE                 | 31       | 35     | 0.15%   |
| XPG                 | 31       | 39     | 0.15%   |
| XrayDisk            | 24       | 33     | 0.11%   |
| Hewlett-Packard     | 22       | 38     | 0.1%    |
| JMicron Technology  | 20       | 23     | 0.1%    |
| Team                | 19       | 24     | 0.09%   |
| IBM/Hitachi         | 19       | 24     | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 480      | 1.99%   |
| Seagate ST3500418AS 500GB        | 338      | 1.4%    |
| Toshiba DT01ACA050 500GB         | 282      | 1.17%   |
| Seagate ST1000DM003-1CH162 1TB   | 276      | 1.15%   |
| Toshiba DT01ACA100 1TB           | 239      | 0.99%   |
| Seagate ST3250410AS 250GB        | 192      | 0.8%    |
| WDC WD5000AAKX-001CA0 500GB      | 182      | 0.76%   |
| Kingston SV300S37A120G 120GB SSD | 182      | 0.76%   |
| Seagate ST380011A 80GB           | 180      | 0.75%   |
| Seagate ST3160815AS 160GB        | 178      | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB   | 175      | 0.73%   |
| Seagate ST3250310AS 250GB        | 165      | 0.68%   |
| Toshiba HDWD110 1TB              | 164      | 0.68%   |
| Seagate ST31000528AS 1TB         | 161      | 0.67%   |
| Seagate ST380815AS 80GB          | 156      | 0.65%   |
| Seagate ST31000524AS 1TB         | 155      | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB         | 145      | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB   | 143      | 0.59%   |
| Hitachi HDS721050CLA362 500GB    | 132      | 0.55%   |
| Kingston SA400S37120G 120GB SSD  | 122      | 0.51%   |
| Seagate ST3500413AS 500GB        | 116      | 0.48%   |
| WDC WD5000AADS-00S9B0 500GB      | 114      | 0.47%   |
| Seagate ST3320620AS 320GB        | 110      | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 109      | 0.45%   |
| Seagate ST3320613AS 320GB        | 105      | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB   | 105      | 0.44%   |
| Samsung HD080HJ/ 80GB            | 105      | 0.44%   |
| Hitachi HDS721010CLA332 1TB      | 102      | 0.42%   |
| Seagate ST3250318AS 250GB        | 99       | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB   | 98       | 0.41%   |
| Hitachi HDS721616PLA380 160GB    | 98       | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB         | 96       | 0.4%    |
| Seagate ST3160811AS 160GB        | 96       | 0.4%    |
| Seagate ST340014A 40GB           | 95       | 0.39%   |
| Seagate ST250DM000-1BD141 250GB  | 95       | 0.39%   |
| Seagate ST3320418AS 320GB        | 93       | 0.39%   |
| Kingston SA400S37240G 240GB SSD  | 90       | 0.37%   |
| WDC WD10EARS-00Y5B1 1TB          | 89       | 0.37%   |
| Samsung HD502HJ 500GB            | 85       | 0.35%   |
| Toshiba HDWD105 500GB            | 83       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5905     | 9860   | 37.2%   |
| WDC                 | 5271     | 8872   | 33.21%  |
| Hitachi             | 1413     | 2026   | 8.9%    |
| Samsung Electronics | 1362     | 2003   | 8.58%   |
| Toshiba             | 1123     | 1662   | 7.07%   |
| Maxtor              | 474      | 608    | 2.99%   |
| HGST                | 154      | 225    | 0.97%   |
| Fujitsu             | 53       | 63     | 0.33%   |
| IBM/Hitachi         | 19       | 24     | 0.12%   |
| Unknown             | 16       | 24     | 0.1%    |
| ExcelStor           | 12       | 19     | 0.08%   |
| Hewlett-Packard     | 11       | 21     | 0.07%   |
| Apple               | 8        | 8      | 0.05%   |
| WD MediaMax         | 7        | 10     | 0.04%   |
| Quantum             | 6        | 6      | 0.04%   |
| IBM                 | 5        | 7      | 0.03%   |
| USB3.0              | 4        | 4      | 0.03%   |
| ASMT                | 4        | 17     | 0.03%   |
| Magnetic Data       | 3        | 3      | 0.02%   |
| Intenso             | 2        | 2      | 0.01%   |
| ASMedia             | 2        | 8      | 0.01%   |
| Unknown             | 2        | 2      | 0.01%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| TPH01204000GB       | 1        | 1      | 0.01%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| Speeding            | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| PHD 3.0             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| MARSHAL             | 1        | 1      | 0.01%   |
| Lexar               | 1        | 1      | 0.01%   |
| LaCie               | 1        | 1      | 0.01%   |
| Inateck             | 1        | 1      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| FC-1307             | 1        | 1      | 0.01%   |
| External            | 1        | 1      | 0.01%   |
| Ext Hard            | 1        | 1      | 0.01%   |
| CLOVER              | 1        | 1      | 0.01%   |
| China               | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 793      | 1146   | 17.88%  |
| Samsung Electronics | 470      | 772    | 10.6%   |
| OCZ                 | 274      | 365    | 6.18%   |
| WDC                 | 256      | 358    | 5.77%   |
| SPCC                | 255      | 353    | 5.75%   |
| China               | 227      | 314    | 5.12%   |
| A-DATA Technology   | 226      | 319    | 5.09%   |
| SanDisk             | 217      | 326    | 4.89%   |
| Crucial             | 189      | 279    | 4.26%   |
| Plextor             | 174      | 273    | 3.92%   |
| Intel               | 158      | 278    | 3.56%   |
| Apacer              | 109      | 151    | 2.46%   |
| Smartbuy            | 92       | 126    | 2.07%   |
| Corsair             | 88       | 114    | 1.98%   |
| GOODRAM             | 75       | 108    | 1.69%   |
| AMD                 | 72       | 88     | 1.62%   |
| Transcend           | 71       | 96     | 1.6%    |
| Patriot             | 68       | 90     | 1.53%   |
| KingSpec            | 67       | 82     | 1.51%   |
| Toshiba             | 42       | 70     | 0.95%   |
| KingDian            | 39       | 59     | 0.88%   |
| Gigabyte Technology | 34       | 42     | 0.77%   |
| Kingmax             | 32       | 66     | 0.72%   |
| Netac               | 29       | 34     | 0.65%   |
| XrayDisk            | 20       | 29     | 0.45%   |
| Team                | 17       | 21     | 0.38%   |
| Intenso             | 17       | 25     | 0.38%   |
| OCZ-VERTEX3         | 16       | 25     | 0.36%   |
| Foxline             | 16       | 22     | 0.36%   |
| Unknown             | 15       | 17     | 0.34%   |
| KingFast            | 13       | 19     | 0.29%   |
| PNY                 | 12       | 13     | 0.27%   |
| Qumo                | 11       | 16     | 0.25%   |
| Micron Technology   | 10       | 11     | 0.23%   |
| Zheino              | 8        | 12     | 0.18%   |
| Palit               | 8        | 12     | 0.18%   |
| Londisk             | 8        | 8      | 0.18%   |
| Seagate             | 7        | 9      | 0.16%   |
| OCZ-VERTEX          | 7        | 12     | 0.16%   |
| Hewlett-Packard     | 7        | 13     | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 12044    | 25492  | 72.35%  |
| SSD     | 3784     | 6445   | 22.73%  |
| NVMe    | 540      | 816    | 3.24%   |
| Unknown | 266      | 322    | 1.6%    |
| MMC     | 14       | 19     | 0.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13006    | 31692  | 92.93%  |
| NVMe | 526      | 796    | 3.76%   |
| SAS  | 450      | 587    | 3.22%   |
| MMC  | 14       | 19     | 0.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 11220    | 22303  | 66.69%  |
| 0.51-1.0        | 4279     | 7437   | 25.44%  |
| 1.01-2.0        | 952      | 1596   | 5.66%   |
| 2.01-3.0        | 200      | 312    | 1.19%   |
| 3.01-4.0        | 114      | 196    | 0.68%   |
| 4.01-10.0       | 48       | 81     | 0.29%   |
| More than 100.0 | 6        | 7      | 0.04%   |
| 10.01-20.0      | 4        | 5      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3806     | 24.62%  |
| 251-500        | 2846     | 18.41%  |
| 1-20           | 2000     | 12.94%  |
| 51-100         | 1928     | 12.47%  |
| 501-1000       | 1909     | 12.35%  |
| 21-50          | 1238     | 8.01%   |
| 1001-2000      | 1026     | 6.64%   |
| 2001-3000      | 306      | 1.98%   |
| More than 3000 | 218      | 1.41%   |
| Unknown        | 181      | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9453     | 61.76%  |
| 21-50          | 1394     | 9.11%   |
| 101-250        | 1190     | 7.77%   |
| 251-500        | 930      | 6.08%   |
| 51-100         | 929      | 6.07%   |
| 501-1000       | 723      | 4.72%   |
| 1001-2000      | 351      | 2.29%   |
| Unknown        | 181      | 1.18%   |
| 2001-3000      | 86       | 0.56%   |
| More than 3000 | 70       | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 195      | 254    | 2.46%   |
| Seagate ST3500418AS 500GB         | 172      | 236    | 2.17%   |
| Seagate ST3250410AS 250GB         | 121      | 155    | 1.53%   |
| Seagate ST3250310AS 250GB         | 110      | 168    | 1.39%   |
| WDC WD5000AAKX-001CA0 500GB       | 100      | 124    | 1.26%   |
| Seagate ST3320613AS 320GB         | 82       | 114    | 1.03%   |
| Seagate ST31000528AS 1TB          | 80       | 105    | 1.01%   |
| Seagate ST3160815AS 160GB         | 70       | 83     | 0.88%   |
| WDC WD5000AADS-00S9B0 500GB       | 66       | 79     | 0.83%   |
| Samsung Electronics HD080HJ/ 80GB | 66       | 81     | 0.83%   |
| Seagate ST380011A 80GB            | 65       | 74     | 0.82%   |
| Seagate ST3160811AS 160GB         | 64       | 90     | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB    | 62       | 91     | 0.78%   |
| Seagate ST31000524AS 1TB          | 59       | 86     | 0.74%   |
| Hitachi HDS721616PLA380 160GB     | 59       | 77     | 0.74%   |
| Seagate ST1000DM003-9YN162 1TB    | 56       | 68     | 0.71%   |
| Samsung Electronics HD160JJ 160GB | 55       | 85     | 0.69%   |
| Hitachi HDP725050GLA360 500GB     | 55       | 73     | 0.69%   |
| Seagate ST3250318AS 250GB         | 54       | 73     | 0.68%   |
| Hitachi HDS721050CLA362 500GB     | 53       | 68     | 0.67%   |
| WDC WD3200AAJS-00L7A0 320GB       | 50       | 59     | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB           | 50       | 82     | 0.63%   |
| Seagate ST3320620AS 320GB         | 50       | 67     | 0.63%   |
| Seagate ST31500341AS 1TB          | 50       | 71     | 0.63%   |
| Hitachi HDS721010CLA332 1TB       | 50       | 62     | 0.63%   |
| Seagate ST380815AS 80GB           | 48       | 61     | 0.61%   |
| Samsung Electronics HD321KJ 320GB | 46       | 55     | 0.58%   |
| Seagate ST3500413AS 500GB         | 45       | 50     | 0.57%   |
| Seagate ST3500320AS 500GB         | 44       | 58     | 0.56%   |
| Seagate ST3320418AS 320GB         | 42       | 53     | 0.53%   |
| Samsung Electronics HD161HJ 160GB | 42       | 52     | 0.53%   |
| Seagate ST250DM000-1BD141 250GB   | 40       | 56     | 0.5%    |
| Maxtor STM3250310AS 250GB         | 40       | 53     | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 39       | 54     | 0.49%   |
| WDC WD5000AAKS-00V1A0 500GB       | 37       | 46     | 0.47%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 36       | 42     | 0.45%   |
| Toshiba DT01ACA050 500GB          | 35       | 51     | 0.44%   |
| Toshiba DT01ACA100 1TB            | 33       | 49     | 0.42%   |
| Samsung Electronics SP2504C 250GB | 33       | 56     | 0.42%   |
| Samsung Electronics SP0802N 80GB  | 33       | 39     | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2679     | 3911   | 36.31%  |
| WDC                 | 2122     | 3017   | 28.76%  |
| Samsung Electronics | 751      | 1035   | 10.18%  |
| Hitachi             | 724      | 995    | 9.81%   |
| Maxtor              | 282      | 348    | 3.82%   |
| Toshiba             | 207      | 277    | 2.81%   |
| Kingston            | 110      | 137    | 1.49%   |
| OCZ                 | 52       | 70     | 0.7%    |
| SPCC                | 49       | 66     | 0.66%   |
| Intel               | 41       | 48     | 0.56%   |
| HGST                | 38       | 47     | 0.51%   |
| A-DATA Technology   | 33       | 48     | 0.45%   |
| SanDisk             | 32       | 41     | 0.43%   |
| Corsair             | 29       | 39     | 0.39%   |
| Kingmax             | 25       | 52     | 0.34%   |
| Fujitsu             | 25       | 29     | 0.34%   |
| IBM/Hitachi         | 16       | 21     | 0.22%   |
| Crucial             | 16       | 30     | 0.22%   |
| AMD                 | 12       | 14     | 0.16%   |
| KingSpec            | 11       | 13     | 0.15%   |
| Plextor             | 10       | 15     | 0.14%   |
| ExcelStor           | 8        | 10     | 0.11%   |
| China               | 8        | 11     | 0.11%   |
| Netac               | 7        | 7      | 0.09%   |
| OCZ-VERTEX3         | 6        | 12     | 0.08%   |
| IBM                 | 5        | 7      | 0.07%   |
| Hewlett-Packard     | 4        | 5      | 0.05%   |
| Apacer              | 4        | 7      | 0.05%   |
| Unknown             | 4        | 5      | 0.05%   |
| WD MediaMax         | 3        | 5      | 0.04%   |
| Transcend           | 3        | 3      | 0.04%   |
| Smartbuy            | 3        | 4      | 0.04%   |
| Qumo                | 3        | 7      | 0.04%   |
| Patriot             | 3        | 3      | 0.04%   |
| Neo                 | 3        | 3      | 0.04%   |
| LITEONIT            | 3        | 3      | 0.04%   |
| Intenso             | 3        | 4      | 0.04%   |
| XPG                 | 2        | 4      | 0.03%   |
| Silicon Motion      | 2        | 3      | 0.03%   |
| Quantum             | 2        | 2      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2679     | 3911   | 39.2%   |
| WDC                 | 2103     | 2978   | 30.77%  |
| Samsung Electronics | 732      | 1009   | 10.71%  |
| Hitachi             | 724      | 995    | 10.59%  |
| Maxtor              | 282      | 348    | 4.13%   |
| Toshiba             | 207      | 277    | 3.03%   |
| HGST                | 38       | 47     | 0.56%   |
| Fujitsu             | 25       | 29     | 0.37%   |
| IBM/Hitachi         | 16       | 21     | 0.23%   |
| ExcelStor           | 8        | 10     | 0.12%   |
| IBM                 | 5        | 7      | 0.07%   |
| WD MediaMax         | 3        | 5      | 0.04%   |
| Hewlett-Packard     | 3        | 4      | 0.04%   |
| Quantum             | 2        | 2      | 0.03%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| MARSHAL             | 1        | 1      | 0.01%   |
| Magnetic Data       | 1        | 1      | 0.01%   |
| LaCie               | 1        | 1      | 0.01%   |
| ASMT                | 1        | 2      | 0.01%   |
| Apple               | 1        | 1      | 0.01%   |
| Unknown             | 1        | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5955     | 9651   | 91.67%  |
| SSD  | 523      | 729    | 8.05%   |
| NVMe | 18       | 26     | 0.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 13       | 14     | 4.91%   |
| Seagate ST31000528AS 1TB          | 12       | 14     | 4.53%   |
| Seagate ST31000524AS 1TB          | 7        | 8      | 2.64%   |
| Hitachi HDS721010DLE630 1TB       | 7        | 9      | 2.64%   |
| Seagate ST3500412AS 500GB         | 6        | 8      | 2.26%   |
| Samsung Electronics HD502HJ 500GB | 5        | 5      | 1.89%   |
| Seagate ST3500410AS 500GB         | 4        | 5      | 1.51%   |
| Seagate ST31000333AS 1TB          | 4        | 4      | 1.51%   |
| Samsung Electronics SP0411N 40GB  | 4        | 5      | 1.51%   |
| Samsung Electronics HD502IJ 500GB | 4        | 4      | 1.51%   |
| Samsung Electronics HD322GJ 320GB | 4        | 5      | 1.51%   |
| HGST HTS545050A7E380 500GB        | 4        | 4      | 1.51%   |
| WDC WD5000AAKS-00V1A0 500GB       | 3        | 4      | 1.13%   |
| WDC WD3200AAJS-00L7A0 320GB       | 3        | 4      | 1.13%   |
| WDC WD15EARS-00MVWB0 1TB          | 3        | 6      | 1.13%   |
| Seagate ST3750528AS 752GB         | 3        | 3      | 1.13%   |
| Seagate ST32000542AS 2TB          | 3        | 5      | 1.13%   |
| Maxtor 6Y080L0 82GB               | 3        | 3      | 1.13%   |
| Hitachi HDS721050DLE630 500GB     | 3        | 3      | 1.13%   |
| WDC WD7501AALS-00J7B0 752GB       | 2        | 2      | 0.75%   |
| WDC WD2500JS-22NCB1 250GB         | 2        | 3      | 0.75%   |
| Toshiba DT01ACA050 500GB          | 2        | 2      | 0.75%   |
| Seagate STM3500418AS 500GB        | 2        | 2      | 0.75%   |
| Seagate ST9320325AS 320GB         | 2        | 3      | 0.75%   |
| Seagate ST9250315AS 250GB         | 2        | 2      | 0.75%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 0.75%   |
| Seagate ST3640323AS 640GB         | 2        | 2      | 0.75%   |
| Seagate ST3320613AS 320GB         | 2        | 3      | 0.75%   |
| Seagate ST3250318AS 250GB         | 2        | 6      | 0.75%   |
| Seagate ST3160318AS 160GB         | 2        | 2      | 0.75%   |
| Seagate ST31500341AS 1TB          | 2        | 3      | 0.75%   |
| Samsung Electronics HM321HI 320GB | 2        | 3      | 0.75%   |
| Samsung Electronics HM250HI 250GB | 2        | 2      | 0.75%   |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 0.75%   |
| Samsung Electronics HD252HJ 250GB | 2        | 6      | 0.75%   |
| Samsung Electronics HD251HJ 250GB | 2        | 2      | 0.75%   |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 0.75%   |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 0.75%   |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 0.75%   |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 0.75%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 95       | 115    | 36.12%  |
| WDC                 | 66       | 83     | 25.1%   |
| Samsung Electronics | 46       | 54     | 17.49%  |
| Hitachi             | 25       | 28     | 9.51%   |
| Toshiba             | 12       | 12     | 4.56%   |
| Maxtor              | 9        | 9      | 3.42%   |
| HGST                | 7        | 7      | 2.66%   |
| Hewlett-Packard     | 1        | 1      | 0.38%   |
| Corsair             | 1        | 1      | 0.38%   |
| Apple               | 1        | 1      | 0.38%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 9791     | 21277  | 57.34%  |
| Malfunc  | 6297     | 10406  | 36.88%  |
| Detected | 727      | 1100   | 4.26%   |
| Failed   | 260      | 311    | 1.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8457     | 52.6%   |
| AMD                              | 3216     | 20%     |
| Nvidia                           | 1312     | 8.16%   |
| JMicron Technology               | 1058     | 6.58%   |
| Marvell Technology Group         | 590      | 3.67%   |
| ASMedia Technology               | 370      | 2.3%    |
| VIA Technologies                 | 299      | 1.86%   |
| Samsung Electronics              | 148      | 0.92%   |
| Silicon Motion                   | 91       | 0.57%   |
| Silicon Integrated Systems [SiS] | 71       | 0.44%   |
| Kingston Technology Company      | 66       | 0.41%   |
| Silicon Image                    | 51       | 0.32%   |
| Phison Electronics               | 48       | 0.3%    |
| ADATA Technology                 | 47       | 0.29%   |
| SanDisk                          | 42       | 0.26%   |
| Integrated Technology Express    | 42       | 0.26%   |
| Realtek Semiconductor            | 27       | 0.17%   |
| Lite-On Technology               | 17       | 0.11%   |
| ULi Electronics                  | 15       | 0.09%   |
| LSI Logic / Symbios Logic        | 14       | 0.09%   |
| Micron/Crucial Technology        | 11       | 0.07%   |
| MAXIO Technology (Hangzhou)      | 10       | 0.06%   |
| Netac Technology                 | 9        | 0.06%   |
| Adaptec                          | 9        | 0.06%   |
| SK hynix                         | 8        | 0.05%   |
| Promise Technology               | 7        | 0.04%   |
| OCZ Technology Group             | 7        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 6        | 0.04%   |
| Hewlett-Packard                  | 5        | 0.03%   |
| KIOXIA                           | 4        | 0.02%   |
| Toshiba America Info Systems     | 3        | 0.02%   |
| ATI Technologies                 | 3        | 0.02%   |
| Union Memory (Shenzhen)          | 2        | 0.01%   |
| Shenzhen Longsys Electronics     | 2        | 0.01%   |
| Seagate Technology               | 2        | 0.01%   |
| Artop Electronic                 | 2        | 0.01%   |
| Transcend                        | 1        | 0.01%   |
| TenaFe                           | 1        | 0.01%   |
| Tekram Technology                | 1        | 0.01%   |
| MCST                             | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1965     | 8.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1509     | 6.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1477     | 6.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1106     | 4.59%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 900      | 3.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 785      | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 752      | 3.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 710      | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 708      | 2.94%   |
| Nvidia MCP61 SATA Controller                                                            | 667      | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 641      | 2.66%   |
| Nvidia MCP61 IDE                                                                        | 622      | 2.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 537      | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 537      | 2.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 423      | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 423      | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 411      | 1.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 400      | 1.66%   |
| JMicron JMB368 IDE controller                                                           | 378      | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 354      | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 249      | 1.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 245      | 1.02%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 235      | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 232      | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 232      | 0.96%   |
| AMD FCH IDE Controller                                                                  | 232      | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 216      | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 208      | 0.86%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 179      | 0.74%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 174      | 0.72%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 166      | 0.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 165      | 0.68%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 161      | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 161      | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 157      | 0.65%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 153      | 0.63%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 146      | 0.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 138      | 0.57%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 136      | 0.56%   |
| AMD SB600 IDE                                                                           | 136      | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 8359     | 50.91%  |
| SATA | 7127     | 43.41%  |
| NVMe | 529      | 3.22%   |
| RAID | 367      | 2.24%   |
| SCSI | 22       | 0.13%   |
| SAS  | 14       | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 8722     | 66.05%  |
| AMD      | 4482     | 33.94%  |
| MBE8C-PC | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 242      | 1.81%   |
| Intel Pentium 4 CPU 3.00GHz                 | 200      | 1.49%   |
| AMD Athlon II X2 250 Processor              | 154      | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 146      | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 133      | 0.99%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 132      | 0.99%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 130      | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 120      | 0.9%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 116      | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 116      | 0.87%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 110      | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 108      | 0.81%   |
| AMD FX-8350 Eight-Core Processor            | 105      | 0.78%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 103      | 0.77%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 100      | 0.75%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 90       | 0.67%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 85       | 0.64%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 83       | 0.62%   |
| AMD FX-8320 Eight-Core Processor            | 83       | 0.62%   |
| AMD FX-4300 Quad-Core Processor             | 81       | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 79       | 0.59%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 78       | 0.58%   |
| AMD Athlon II X2 240 Processor              | 78       | 0.58%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 77       | 0.58%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 73       | 0.55%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 72       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 71       | 0.53%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 70       | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 70       | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 70       | 0.52%   |
| AMD Phenom II X4 955 Processor              | 68       | 0.51%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 67       | 0.5%    |
| AMD Athlon 64 X2 Dual Core Processor 5600+  | 67       | 0.5%    |
| AMD Phenom II X4 965 Processor              | 66       | 0.49%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 66       | 0.49%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 66       | 0.49%   |
| AMD Athlon II X4 640 Processor              | 65       | 0.49%   |
| AMD Athlon II X2 245 Processor              | 64       | 0.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 63       | 0.47%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 63       | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1603     | 12.02%  |
| Intel Core i3           | 1095     | 8.21%   |
| Intel Core 2 Duo        | 1065     | 7.99%   |
| Intel Celeron           | 838      | 6.29%   |
| AMD FX                  | 745      | 5.59%   |
| Intel Pentium           | 688      | 5.16%   |
| AMD Athlon 64 X2        | 687      | 5.15%   |
| Intel Core i7           | 665      | 4.99%   |
| Intel Pentium Dual-Core | 534      | 4.01%   |
| AMD Athlon II X2        | 513      | 3.85%   |
| Intel Core 2 Quad       | 476      | 3.57%   |
| Intel Pentium 4         | 455      | 3.41%   |
| Intel Xeon              | 399      | 2.99%   |
| AMD Phenom II X4        | 318      | 2.39%   |
| AMD Ryzen 5             | 257      | 1.93%   |
| Intel Pentium Dual      | 238      | 1.79%   |
| Intel Core 2            | 237      | 1.78%   |
| AMD Athlon II X4        | 213      | 1.6%    |
| Intel Pentium D         | 173      | 1.3%    |
| AMD Athlon II X3        | 163      | 1.22%   |
| AMD Athlon 64           | 160      | 1.2%    |
| Intel Atom              | 159      | 1.19%   |
| AMD A4                  | 143      | 1.07%   |
| AMD A8                  | 130      | 0.98%   |
| AMD A10                 | 126      | 0.95%   |
| AMD Phenom              | 115      | 0.86%   |
| AMD Athlon X4           | 103      | 0.77%   |
| AMD Ryzen 7             | 101      | 0.76%   |
| AMD Phenom II X6        | 101      | 0.76%   |
| AMD Sempron             | 96       | 0.72%   |
| AMD Ryzen 3             | 92       | 0.69%   |
| AMD A6                  | 92       | 0.69%   |
| Other                   | 83       | 0.62%   |
| AMD Athlon              | 83       | 0.62%   |
| AMD Phenom II X2        | 61       | 0.46%   |
| Intel Pentium Gold      | 42       | 0.32%   |
| Intel Genuine           | 40       | 0.3%    |
| AMD E                   | 26       | 0.2%    |
| AMD Phenom II X3        | 25       | 0.19%   |
| Intel Celeron D         | 23       | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 6154     | 44.88%  |
| 4       | 3878     | 28.28%  |
| Unknown | 1264     | 9.22%   |
| 1       | 1071     | 7.81%   |
| 6       | 608      | 4.43%   |
| 3       | 411      | 3%      |
| 8       | 251      | 1.83%   |
| 12      | 36       | 0.26%   |
| 10      | 18       | 0.13%   |
| 16      | 11       | 0.08%   |
| 24      | 4        | 0.03%   |
| 20      | 3        | 0.02%   |
| 18      | 2        | 0.01%   |
| 14      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 13113    | 99%     |
| Unknown | 69       | 0.52%   |
| 2       | 62       | 0.47%   |
| 4       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 8476     | 62%     |
| 2       | 3930     | 28.75%  |
| Unknown | 1264     | 9.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12635    | 94.91%  |
| 32-bit         | 324      | 2.43%   |
| Unknown        | 259      | 1.95%   |
| 64-bit         | 94       | 0.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 1387     | 10.19%  |
| Unknown    | 1190     | 8.74%   |
| 0x206a7    | 1136     | 8.34%   |
| 0x306a9    | 990      | 7.27%   |
| 0x306c3    | 936      | 6.88%   |
| 0x010000c8 | 709      | 5.21%   |
| 0x6fd      | 430      | 3.16%   |
| 0x10676    | 360      | 2.64%   |
| 0x6fb      | 353      | 2.59%   |
| 0x06001119 | 303      | 2.23%   |
| 0x506e3    | 299      | 2.2%    |
| 0x906e9    | 222      | 1.63%   |
| 0x0600084f | 222      | 1.63%   |
| 0x06000852 | 194      | 1.43%   |
| 0x010000db | 162      | 1.19%   |
| 0x106e5    | 147      | 1.08%   |
| 0x20655    | 146      | 1.07%   |
| 0x6f6      | 143      | 1.05%   |
| 0xf41      | 139      | 1.02%   |
| 0x906ea    | 136      | 1%      |
| 0xf49      | 134      | 0.98%   |
| 0x010000b6 | 127      | 0.93%   |
| 0x6f2      | 126      | 0.93%   |
| 0x06003106 | 124      | 0.91%   |
| 0x010000c7 | 117      | 0.86%   |
| 0xf65      | 108      | 0.79%   |
| 0x20652    | 106      | 0.78%   |
| 0x0600063d | 98       | 0.72%   |
| 0x03000027 | 95       | 0.7%    |
| 0x10677    | 94       | 0.69%   |
| 0x0800820d | 93       | 0.68%   |
| 0x06000822 | 93       | 0.68%   |
| 0x106ca    | 79       | 0.58%   |
| 0x010000dc | 77       | 0.57%   |
| 0xf29      | 76       | 0.56%   |
| 0xa0653    | 73       | 0.54%   |
| 0x08701021 | 73       | 0.54%   |
| 0xf43      | 68       | 0.5%    |
| 0x106a5    | 67       | 0.49%   |
| 0x01000086 | 65       | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1765     | 13.22%  |
| K10              | 1533     | 11.48%  |
| Core             | 1235     | 9.25%   |
| SandyBridge      | 1202     | 9%      |
| IvyBridge        | 1041     | 7.79%   |
| Haswell          | 1007     | 7.54%   |
| K8 Hammer        | 915      | 6.85%   |
| Piledriver       | 853      | 6.39%   |
| NetBurst         | 805      | 6.03%   |
| KabyLake         | 444      | 3.32%   |
| Skylake          | 310      | 2.32%   |
| Westmere         | 280      | 2.1%    |
| Nehalem          | 222      | 1.66%   |
| Unknown          | 216      | 1.62%   |
| Zen              | 195      | 1.46%   |
| Bulldozer        | 194      | 1.45%   |
| Zen+             | 153      | 1.15%   |
| Steamroller      | 142      | 1.06%   |
| Bonnell          | 135      | 1.01%   |
| K10 Llano        | 109      | 0.82%   |
| Silvermont       | 108      | 0.81%   |
| Zen 2            | 102      | 0.76%   |
| CometLake        | 93       | 0.7%    |
| Zen 3            | 62       | 0.46%   |
| Excavator        | 41       | 0.31%   |
| Bobcat           | 36       | 0.27%   |
| Jaguar           | 32       | 0.24%   |
| K6               | 26       | 0.19%   |
| Goldmont plus    | 22       | 0.16%   |
| Icelake          | 16       | 0.12%   |
| Goldmont         | 16       | 0.12%   |
| Alderlake Hybrid | 16       | 0.12%   |
| Broadwell        | 13       | 0.1%    |
| Puma             | 7        | 0.05%   |
| Tremont          | 3        | 0.02%   |
| P6               | 3        | 0.02%   |
| K8 & K10 hybrid  | 2        | 0.01%   |
| TigerLake        | 1        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 7180     | 51.46%  |
| AMD                              | 3825     | 27.41%  |
| Intel                            | 2894     | 20.74%  |
| VIA Technologies                 | 26       | 0.19%   |
| Matrox Electronics Systems       | 8        | 0.06%   |
| Silicon Integrated Systems [SiS] | 7        | 0.05%   |
| ATI Technologies                 | 6        | 0.04%   |
| S3 Graphics                      | 5        | 0.04%   |
| ASPEED Technology                | 2        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 435      | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 379      | 2.57%   |
| Nvidia GT218 [GeForce 210]                                                  | 377      | 2.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 284      | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 277      | 1.88%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 251      | 1.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 247      | 1.67%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 234      | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                              | 223      | 1.51%   |
| Nvidia GF108 [GeForce GT 630]                                               | 223      | 1.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 221      | 1.5%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 219      | 1.48%   |
| Nvidia GF119 [GeForce GT 610]                                               | 199      | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 196      | 1.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 194      | 1.31%   |
| Nvidia GF108 [GeForce GT 440]                                               | 171      | 1.16%   |
| Nvidia GF108 [GeForce GT 430]                                               | 169      | 1.15%   |
| Nvidia G92 [GeForce GTS 250]                                                | 168      | 1.14%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 162      | 1.1%    |
| Nvidia G84 [GeForce 8600 GT]                                                | 161      | 1.09%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 157      | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 153      | 1.04%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 141      | 0.96%   |
| Nvidia GK208B [GeForce GT 730]                                              | 138      | 0.94%   |
| Nvidia GT215 [GeForce GT 240]                                               | 136      | 0.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 135      | 0.91%   |
| AMD RS780L [Radeon 3000]                                                    | 134      | 0.91%   |
| Nvidia GK107 [GeForce GT 640]                                               | 121      | 0.82%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 120      | 0.81%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 115      | 0.78%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 110      | 0.75%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 107      | 0.73%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 105      | 0.71%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 103      | 0.7%    |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 98       | 0.66%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 97       | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 96       | 0.65%   |
| Nvidia GF108 [GeForce GT 730]                                               | 96       | 0.65%   |
| Nvidia GT216 [GeForce GT 220]                                               | 94       | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 93       | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 6996     | 51.54%  |
| 1 x AMD                       | 3352     | 24.69%  |
| 1 x Intel                     | 2528     | 18.62%  |
| 2 x AMD                       | 419      | 3.09%   |
| Intel + Nvidia                | 124      | 0.91%   |
| Intel + AMD                   | 35       | 0.26%   |
| AMD + Nvidia                  | 35       | 0.26%   |
| 2 x Nvidia                    | 29       | 0.21%   |
| 1 x VIA                       | 26       | 0.19%   |
| 1 x SiS                       | 7        | 0.05%   |
| 1 x Matrox                    | 5        | 0.04%   |
| 1 x S3 Graphics               | 4        | 0.03%   |
| 3 x AMD                       | 3        | 0.02%   |
| Nvidia + Matrox               | 3        | 0.02%   |
| 3 x Nvidia                    | 2        | 0.01%   |
| 1 x ASPEED                    | 2        | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| Intel + 2 x AMD               | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10393    | 73.2%   |
| Proprietary | 2901     | 20.43%  |
| Unknown     | 904      | 6.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 3384     | 23.6%   |
| Unknown    | 3356     | 23.41%  |
| 1.01-2.0   | 3226     | 22.5%   |
| 0.51-1.0   | 3050     | 21.27%  |
| 3.01-4.0   | 792      | 5.52%   |
| 7.01-8.0   | 220      | 1.53%   |
| 2.01-3.0   | 148      | 1.03%   |
| 5.01-6.0   | 119      | 0.83%   |
| 8.01-16.0  | 41       | 0.29%   |
| 16.01-24.0 | 1        | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3393     | 25.9%   |
| Goldstar             | 2122     | 16.2%   |
| Acer                 | 1430     | 10.92%  |
| BenQ                 | 1016     | 7.76%   |
| Philips              | 851      | 6.5%    |
| ViewSonic            | 597      | 4.56%   |
| Ancor Communications | 503      | 3.84%   |
| Dell                 | 483      | 3.69%   |
| AOC                  | 459      | 3.5%    |
| Hewlett-Packard      | 374      | 2.85%   |
| NEC Computers        | 289      | 2.21%   |
| Sony                 | 135      | 1.03%   |
| Iiyama               | 132      | 1.01%   |
| Plain Tree Systems   | 77       | 0.59%   |
| Lenovo               | 61       | 0.47%   |
| Envision Peripherals | 57       | 0.44%   |
| Fujitsu Siemens      | 52       | 0.4%    |
| Unknown              | 48       | 0.37%   |
| Packard Bell         | 45       | 0.34%   |
| HannStar             | 44       | 0.34%   |
| Toshiba              | 43       | 0.33%   |
| ASUSTek Computer     | 42       | 0.32%   |
| ___                  | 36       | 0.27%   |
| MiTAC                | 36       | 0.27%   |
| Belinea              | 28       | 0.21%   |
| Panasonic            | 27       | 0.21%   |
| VIE                  | 23       | 0.18%   |
| KTC                  | 23       | 0.18%   |
| Hitachi              | 23       | 0.18%   |
| Medion               | 21       | 0.16%   |
| Eizo                 | 21       | 0.16%   |
| MStar                | 20       | 0.15%   |
| JRY                  | 20       | 0.15%   |
| HKC                  | 17       | 0.13%   |
| Haier                | 17       | 0.13%   |
| eMachines            | 15       | 0.11%   |
| Sharp                | 14       | 0.11%   |
| BBK                  | 14       | 0.11%   |
| MSI                  | 12       | 0.09%   |
| CVT                  | 12       | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 107      | 0.79%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 97       | 0.72%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 92       | 0.68%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 75       | 0.56%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                     | 72       | 0.53%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 64       | 0.47%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 55       | 0.41%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 50       | 0.37%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch   | 48       | 0.36%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 44       | 0.33%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 44       | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 43       | 0.32%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                     | 42       | 0.31%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 40       | 0.3%    |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                  | 40       | 0.3%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                 | 37       | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 34       | 0.25%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 33       | 0.24%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 33       | 0.24%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 32       | 0.24%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 32       | 0.24%   |
| Plain Tree Systems Monitor PTS06A5 1280x1024 337x270mm 17.0-inch      | 31       | 0.23%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 31       | 0.23%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 31       | 0.23%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 31       | 0.23%   |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                 | 31       | 0.23%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                 | 31       | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 29       | 0.21%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 29       | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 29       | 0.21%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 28       | 0.21%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch  | 28       | 0.21%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 28       | 0.21%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 27       | 0.2%    |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch  | 26       | 0.19%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 26       | 0.19%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                     | 26       | 0.19%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 25       | 0.19%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch | 25       | 0.19%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 25       | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5254     | 40.59%  |
| 1280x1024 (SXGA)   | 3101     | 23.96%  |
| 1680x1050 (WSXGA+) | 1000     | 7.73%   |
| 1440x900 (WXGA+)   | 831      | 6.42%   |
| 1366x768 (WXGA)    | 626      | 4.84%   |
| 1600x900 (HD+)     | 508      | 3.92%   |
| 1360x768           | 262      | 2.02%   |
| 1920x1200 (WUXGA)  | 231      | 1.78%   |
| 3840x2160 (4K)     | 230      | 1.78%   |
| 1024x768 (XGA)     | 230      | 1.78%   |
| 2560x1440 (QHD)    | 204      | 1.58%   |
| 1600x1200          | 138      | 1.07%   |
| 2560x1080          | 71       | 0.55%   |
| 1920x540           | 51       | 0.39%   |
| 1280x720 (HD)      | 40       | 0.31%   |
| 1152x864           | 35       | 0.27%   |
| 1400x1050          | 31       | 0.24%   |
| 3440x1440          | 21       | 0.16%   |
| 2048x1536          | 14       | 0.11%   |
| 2048x1152          | 12       | 0.09%   |
| 1920x1440          | 12       | 0.09%   |
| 1280x960           | 12       | 0.09%   |
| 2560x1600          | 6        | 0.05%   |
| 2288x1287          | 6        | 0.05%   |
| 1280x768           | 4        | 0.03%   |
| Unknown            | 3        | 0.02%   |
| 4093x4093          | 2        | 0.02%   |
| 832x624            | 1        | 0.01%   |
| 640x480            | 1        | 0.01%   |
| 3840x2560          | 1        | 0.01%   |
| 3840x1200          | 1        | 0.01%   |
| 3840x1080          | 1        | 0.01%   |
| 3360x1080          | 1        | 0.01%   |
| 1792x1344          | 1        | 0.01%   |
| 1280x800 (WXGA)    | 1        | 0.01%   |
| 1024x600           | 1        | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 2208     | 16.73%  |
| 21      | 2143     | 16.23%  |
| 23      | 1683     | 12.75%  |
| 17      | 1524     | 11.54%  |
| 24      | 1017     | 7.7%    |
| 18      | 882      | 6.68%   |
| 20      | 758      | 5.74%   |
| 27      | 630      | 4.77%   |
| 22      | 608      | 4.61%   |
| 15      | 468      | 3.55%   |
| Unknown | 173      | 1.31%   |
| 31      | 146      | 1.11%   |
| 72      | 116      | 0.88%   |
| 54      | 93       | 0.7%    |
| 40      | 89       | 0.67%   |
| 32      | 89       | 0.67%   |
| 34      | 83       | 0.63%   |
| 16      | 66       | 0.5%    |
| 52      | 52       | 0.39%   |
| 25      | 46       | 0.35%   |
| 84      | 41       | 0.31%   |
| 46      | 38       | 0.29%   |
| 48      | 25       | 0.19%   |
| 13      | 24       | 0.18%   |
| 14      | 20       | 0.15%   |
| 43      | 18       | 0.14%   |
| 42      | 18       | 0.14%   |
| 12      | 18       | 0.14%   |
| 28      | 15       | 0.11%   |
| 26      | 15       | 0.11%   |
| 33      | 11       | 0.08%   |
| 29      | 10       | 0.08%   |
| 65      | 9        | 0.07%   |
| 37      | 8        | 0.06%   |
| 47      | 7        | 0.05%   |
| 55      | 6        | 0.05%   |
| 39      | 6        | 0.05%   |
| 99      | 5        | 0.04%   |
| 60      | 4        | 0.03%   |
| 50      | 4        | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 5087     | 39.05%  |
| 501-600        | 3196     | 24.53%  |
| 301-350        | 1997     | 15.33%  |
| 351-400        | 1559     | 11.97%  |
| 1001-1500      | 249      | 1.91%   |
| 601-700        | 212      | 1.63%   |
| 701-800        | 184      | 1.41%   |
| Unknown        | 173      | 1.33%   |
| 1501-2000      | 160      | 1.23%   |
| 801-900        | 106      | 0.81%   |
| 201-300        | 61       | 0.47%   |
| 901-1000       | 37       | 0.28%   |
| More than 2000 | 7        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 6912     | 54.04%  |
| 5/4     | 2920     | 22.83%  |
| 16/10   | 1919     | 15%     |
| 4/3     | 706      | 5.52%   |
| 3/2     | 152      | 1.19%   |
| 21/9    | 92       | 0.72%   |
| 6/5     | 49       | 0.38%   |
| Unknown | 29       | 0.23%   |
| 32/9    | 8        | 0.06%   |
| 1.00    | 3        | 0.02%   |
| 2.00    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4709     | 36.03%  |
| 151-200        | 3565     | 27.28%  |
| 141-150        | 2150     | 16.45%  |
| 301-350        | 640      | 4.9%    |
| More than 1000 | 369      | 2.82%   |
| 351-500        | 332      | 2.54%   |
| 251-300        | 322      | 2.46%   |
| 101-110        | 262      | 2%      |
| 111-120        | 226      | 1.73%   |
| 501-1000       | 197      | 1.51%   |
| Unknown        | 173      | 1.32%   |
| 121-130        | 43       | 0.33%   |
| 131-140        | 34       | 0.26%   |
| 71-80          | 19       | 0.15%   |
| 81-90          | 15       | 0.11%   |
| 91-100         | 11       | 0.08%   |
| 61-70          | 1        | 0.01%   |
| 41-50          | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 9395     | 74.27%  |
| 101-120       | 2419     | 19.12%  |
| 1-50          | 475      | 3.75%   |
| Unknown       | 173      | 1.37%   |
| 121-160       | 149      | 1.18%   |
| 161-240       | 38       | 0.3%    |
| More than 240 | 1        | 0.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12292    | 91.25%  |
| 2     | 780      | 5.79%   |
| 0     | 375      | 2.78%   |
| 3     | 24       | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8902     | 51.44%  |
| Qualcomm Atheros                       | 1904     | 11%     |
| Intel                                  | 1534     | 8.86%   |
| Nvidia                                 | 1120     | 6.47%   |
| Ralink Technology                      | 497      | 2.87%   |
| Marvell Technology Group               | 349      | 2.02%   |
| Huawei Technologies                    | 337      | 1.95%   |
| Ralink                                 | 304      | 1.76%   |
| VIA Technologies                       | 303      | 1.75%   |
| Broadcom                               | 214      | 1.24%   |
| Qualcomm Atheros Communications        | 200      | 1.16%   |
| D-Link System                          | 200      | 1.16%   |
| TP-Link                                | 157      | 0.91%   |
| D-Link                                 | 157      | 0.91%   |
| Broadcom Limited                       | 138      | 0.8%    |
| ASUSTek Computer                       | 128      | 0.74%   |
| ZTE WCDMA Technologies MSM             | 82       | 0.47%   |
| Sundance Technology Inc / IC Plus      | 66       | 0.38%   |
| Silicon Integrated Systems [SiS]       | 52       | 0.3%    |
| MediaTek                               | 49       | 0.28%   |
| Samsung Electronics                    | 46       | 0.27%   |
| NetGear                                | 46       | 0.27%   |
| Xiaomi                                 | 45       | 0.26%   |
| 3Com                                   | 44       | 0.25%   |
| HTC (High Tech Computer)               | 36       | 0.21%   |
| IMC Networks                           | 22       | 0.13%   |
| Gemtek                                 | 21       | 0.12%   |
| Microsoft                              | 20       | 0.12%   |
| ZyXEL Communications                   | 19       | 0.11%   |
| LSI                                    | 18       | 0.1%    |
| T & A Mobile Phones                    | 15       | 0.09%   |
| Spreadtrum Communications              | 12       | 0.07%   |
| Mercucys                               | 12       | 0.07%   |
| Sony Ericsson Mobile Communications AB | 11       | 0.06%   |
| Qualcomm                               | 11       | 0.06%   |
| JMicron Technology                     | 10       | 0.06%   |
| Edimax Technology                      | 10       | 0.06%   |
| Belkin Components                      | 10       | 0.06%   |
| GCT Semiconductor                      | 9        | 0.05%   |
| ULi Electronics                        | 8        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7284     | 39.63%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 652      | 3.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 598      | 3.25%   |
| Nvidia MCP61 Ethernet                                             | 590      | 3.21%   |
| Ralink MT7601U Wireless Adapter                                   | 254      | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 254      | 1.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 252      | 1.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 204      | 1.11%   |
| Intel 82579V Gigabit Network Connection                           | 203      | 1.1%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 196      | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 191      | 1.04%   |
| Huawei Modem/Networkcard                                          | 189      | 1.03%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 163      | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                   | 158      | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 149      | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 138      | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 137      | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 125      | 0.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 123      | 0.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 121      | 0.66%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 112      | 0.61%   |
| Nvidia CK804 Ethernet Controller                                  | 111      | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 110      | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 108      | 0.59%   |
| Intel I211 Gigabit Network Connection                             | 102      | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 101      | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 94       | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 94       | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 93       | 0.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 92       | 0.5%    |
| Nvidia MCP55 Ethernet                                             | 91       | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 89       | 0.48%   |
| Nvidia MCP77 Ethernet                                             | 89       | 0.48%   |
| Nvidia MCP51 Ethernet Controller                                  | 85       | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 84       | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 78       | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 78       | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 74       | 0.4%    |
| Intel Ethernet Connection (2) I218-V                              | 73       | 0.4%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 69       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 791      | 23.09%  |
| Qualcomm Atheros                | 564      | 16.47%  |
| Ralink Technology               | 497      | 14.51%  |
| Ralink                          | 304      | 8.88%   |
| Intel                           | 220      | 6.42%   |
| Qualcomm Atheros Communications | 200      | 5.84%   |
| TP-Link                         | 156      | 4.55%   |
| D-Link                          | 155      | 4.53%   |
| ASUSTek Computer                | 118      | 3.45%   |
| D-Link System                   | 103      | 3.01%   |
| Broadcom                        | 87       | 2.54%   |
| NetGear                         | 45       | 1.31%   |
| IMC Networks                    | 22       | 0.64%   |
| Broadcom Limited                | 20       | 0.58%   |
| Microsoft                       | 19       | 0.55%   |
| ZyXEL Communications            | 15       | 0.44%   |
| Mercucys                        | 12       | 0.35%   |
| MediaTek                        | 12       | 0.35%   |
| Edimax Technology               | 10       | 0.29%   |
| Belkin Components               | 9        | 0.26%   |
| Marvell Technology Group        | 6        | 0.18%   |
| Gemtek                          | 6        | 0.18%   |
| ZyDAS                           | 5        | 0.15%   |
| Linksys                         | 5        | 0.15%   |
| TRENDnet                        | 4        | 0.12%   |
| Sitecom Europe                  | 4        | 0.12%   |
| Accton Technology               | 4        | 0.12%   |
| VIA Technologies                | 3        | 0.09%   |
| Texas Instruments               | 3        | 0.09%   |
| Sagem                           | 3        | 0.09%   |
| Realtek                         | 3        | 0.09%   |
| Micro Star International        | 3        | 0.09%   |
| BUFFALO                         | 3        | 0.09%   |
| AboCom Systems                  | 3        | 0.09%   |
| Xiaomi                          | 2        | 0.06%   |
| Z-Com                           | 1        | 0.03%   |
| Wacom                           | 1        | 0.03%   |
| Sierra Wireless                 | 1        | 0.03%   |
| Philips (or NXP)                | 1        | 0.03%   |
| Guillemot                       | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                      | 254      | 7.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 191      | 5.45%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 158      | 4.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 137      | 3.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 121      | 3.45%   |
| Ralink RT5370 Wireless Adapter                                                       | 110      | 3.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 101      | 2.88%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 69       | 1.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 66       | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 63       | 1.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 61       | 1.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 59       | 1.68%   |
| Ralink RT2561/RT61 rev B 802.11g                                                     | 56       | 1.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 54       | 1.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 52       | 1.48%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 40       | 1.14%   |
| Intel Wi-Fi 6 AX200                                                                  | 40       | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 39       | 1.11%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                 | 38       | 1.08%   |
| Realtek RTL8187 Wireless Adapter                                                     | 37       | 1.06%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 37       | 1.06%   |
| D-Link 802.11 n WLAN                                                                 | 36       | 1.03%   |
| Realtek 802.11ac NIC                                                                 | 33       | 0.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 31       | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 30       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 30       | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 28       | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 27       | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 26       | 0.74%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 26       | 0.74%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                   | 26       | 0.74%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                            | 26       | 0.74%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 25       | 0.71%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 25       | 0.71%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]        | 25       | 0.71%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 23       | 0.66%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                      | 22       | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 21       | 0.6%    |
| Intel Wireless 7260                                                                  | 21       | 0.6%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 21       | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8623     | 60.99%  |
| Qualcomm Atheros                       | 1402     | 9.92%   |
| Intel                                  | 1402     | 9.92%   |
| Nvidia                                 | 1120     | 7.92%   |
| Marvell Technology Group               | 344      | 2.43%   |
| VIA Technologies                       | 293      | 2.07%   |
| Broadcom                               | 127      | 0.9%    |
| Broadcom Limited                       | 118      | 0.83%   |
| D-Link System                          | 98       | 0.69%   |
| Huawei Technologies                    | 85       | 0.6%    |
| Sundance Technology Inc / IC Plus      | 66       | 0.47%   |
| Silicon Integrated Systems [SiS]       | 50       | 0.35%   |
| 3Com                                   | 44       | 0.31%   |
| Xiaomi                                 | 43       | 0.3%    |
| Samsung Electronics                    | 39       | 0.28%   |
| MediaTek                               | 36       | 0.25%   |
| HTC (High Tech Computer)               | 36       | 0.25%   |
| T & A Mobile Phones                    | 15       | 0.11%   |
| Gemtek                                 | 15       | 0.11%   |
| ZTE WCDMA Technologies MSM             | 13       | 0.09%   |
| Spreadtrum Communications              | 12       | 0.08%   |
| Sony Ericsson Mobile Communications AB | 11       | 0.08%   |
| Qualcomm                               | 11       | 0.08%   |
| JMicron Technology                     | 10       | 0.07%   |
| ASUSTek Computer                       | 10       | 0.07%   |
| GCT Semiconductor                      | 9        | 0.06%   |
| ULi Electronics                        | 8        | 0.06%   |
| Lenovo                                 | 8        | 0.06%   |
| ASIX Electronics                       | 8        | 0.06%   |
| Vimtron Electronics                    | 7        | 0.05%   |
| Davicom Semiconductor                  | 7        | 0.05%   |
| ADMtek                                 | 7        | 0.05%   |
| OPPO Electronics                       | 5        | 0.04%   |
| ZyXEL Communications                   | 4        | 0.03%   |
| ICS Advent                             | 4        | 0.03%   |
| Motorola PCS                           | 3        | 0.02%   |
| LG Electronics                         | 3        | 0.02%   |
| Aquantia                               | 3        | 0.02%   |
| Android                                | 3        | 0.02%   |
| TOMTOM                                 | 2        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 7284     | 50.42%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 652      | 4.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 598      | 4.14%   |
| Nvidia MCP61 Ethernet                                                      | 590      | 4.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 254      | 1.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 252      | 1.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 204      | 1.41%   |
| Intel 82579V Gigabit Network Connection                                    | 203      | 1.41%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 196      | 1.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 163      | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                       | 149      | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 138      | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 125      | 0.87%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 123      | 0.85%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 112      | 0.78%   |
| Nvidia CK804 Ethernet Controller                                           | 111      | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 108      | 0.75%   |
| Intel I211 Gigabit Network Connection                                      | 102      | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 94       | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 94       | 0.65%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 93       | 0.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 92       | 0.64%   |
| Nvidia MCP55 Ethernet                                                      | 91       | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 89       | 0.62%   |
| Nvidia MCP77 Ethernet                                                      | 89       | 0.62%   |
| Nvidia MCP51 Ethernet Controller                                           | 85       | 0.59%   |
| Intel Ethernet Connection I217-V                                           | 84       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 78       | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 78       | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 74       | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                       | 73       | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                          | 64       | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                    | 64       | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 63       | 0.44%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 60       | 0.42%   |
| Huawei E353/E3131                                                          | 50       | 0.35%   |
| Intel 82574L Gigabit Network Connection                                    | 48       | 0.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                  | 42       | 0.29%   |
| Intel Ethernet Connection I217-LM                                          | 42       | 0.29%   |
| Nvidia MCP67 Ethernet                                                      | 40       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13057    | 78.2%   |
| WiFi     | 3224     | 19.31%  |
| Modem    | 395      | 2.37%   |
| Unknown  | 20       | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10947    | 83.03%  |
| WiFi     | 2195     | 16.65%  |
| Modem    | 41       | 0.31%   |
| Unknown  | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10721    | 80.4%   |
| 2     | 2329     | 17.47%  |
| 3     | 149      | 1.12%   |
| 0     | 126      | 0.94%   |
| 4     | 8        | 0.06%   |
| 33    | 1        | 0.01%   |
| 6     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 9702     | 69.89%  |
| Unknown | 4036     | 29.07%  |
| Yes     | 144      | 1.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 610      | 46.07%  |
| Intel                           | 189      | 14.27%  |
| ASUSTek Computer                | 148      | 11.18%  |
| Broadcom                        | 89       | 6.72%   |
| Realtek Semiconductor           | 66       | 4.98%   |
| Qualcomm Atheros Communications | 55       | 4.15%   |
| Integrated System Solution      | 53       | 4%      |
| IMC Networks                    | 28       | 2.11%   |
| Lite-On Technology              | 14       | 1.06%   |
| TP-Link                         | 8        | 0.6%    |
| MediaTek                        | 8        | 0.6%    |
| ISSC                            | 8        | 0.6%    |
| Roper                           | 7        | 0.53%   |
| Ralink                          | 7        | 0.53%   |
| Conwise Technology              | 6        | 0.45%   |
| Apple                           | 6        | 0.45%   |
| Micro Star International        | 4        | 0.3%    |
| Logitech                        | 4        | 0.3%    |
| Foxconn / Hon Hai               | 3        | 0.23%   |
| Belkin Components               | 2        | 0.15%   |
| Actions                         | 2        | 0.15%   |
| Realtek                         | 1        | 0.08%   |
| Ralink Technology               | 1        | 0.08%   |
| Primax Electronics              | 1        | 0.08%   |
| Hewlett-Packard                 | 1        | 0.08%   |
| Dell                            | 1        | 0.08%   |
| D-Link                          | 1        | 0.08%   |
| Accel Semiconductor             | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 610      | 46.04%  |
| Intel Bluetooth wireless interface                    | 67       | 5.06%   |
| Realtek Bluetooth Radio                               | 58       | 4.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 52       | 3.92%   |
| Intel AX200 Bluetooth                                 | 39       | 2.94%   |
| ASUS Bluetooth Adapter                                | 36       | 2.72%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 35       | 2.64%   |
| Integrated System Solution Bluetooth Device           | 33       | 2.49%   |
| Intel Wireless-AC 3168 Bluetooth                      | 30       | 2.26%   |
| Broadcom BCM2045 Bluetooth                            | 22       | 1.66%   |
| ASUS BCM20702A0                                       | 22       | 1.66%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 20       | 1.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 19       | 1.43%   |
| Intel AX210 Bluetooth                                 | 16       | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 13       | 0.98%   |
| Lite-On Bluetooth Device                              | 12       | 0.91%   |
| ASUS Qualcomm Bluetooth 4.1                           | 11       | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 10       | 0.75%   |
| IMC Networks Bluetooth Radio                          | 10       | 0.75%   |
| ASUS Bluetooth Radio                                  | 10       | 0.75%   |
| TP-Link UB500 Adapter                                 | 8        | 0.6%    |
| MediaTek Wireless_Device                              | 8        | 0.6%    |
| ISSC Bluetooth Device                                 | 8        | 0.6%    |
| IMC Networks Bluetooth Module                         | 8        | 0.6%    |
| ASUS ASUS USB-BT500                                   | 8        | 0.6%    |
| Roper Class 1 Bluetooth Dongle                        | 7        | 0.53%   |
| Ralink RT3290 Bluetooth                               | 7        | 0.53%   |
| Intel AX201 Bluetooth                                 | 7        | 0.53%   |
| Broadcom Bluetooth 3.0 Device                         | 7        | 0.53%   |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 0.45%   |
| Conwise CW6622                                        | 6        | 0.45%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 6        | 0.45%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 6        | 0.45%   |
| Realtek  Bluetooth 4.2 Adapter                        | 5        | 0.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 0.38%   |
| Broadcom BCM2210 Bluetooth                            | 5        | 0.38%   |
| Broadcom BCM2035 Bluetooth dongle                     | 5        | 0.38%   |
| Apple Bluetooth USB Host Controller                   | 5        | 0.38%   |
| Qualcomm Atheros Bluetooth (AR3011)                   | 4        | 0.3%    |
| Micro Star International Bluetooth Device             | 4        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 8195     | 39.25%  |
| Nvidia                                          | 5969     | 28.59%  |
| AMD                                             | 4796     | 22.97%  |
| C-Media Electronics                             | 558      | 2.67%   |
| Creative Labs                                   | 459      | 2.2%    |
| VIA Technologies                                | 189      | 0.91%   |
| Silicon Integrated Systems [SiS]                | 67       | 0.32%   |
| Creative Technology                             | 64       | 0.31%   |
| Logitech                                        | 58       | 0.28%   |
| JMTek                                           | 41       | 0.2%    |
| Texas Instruments                               | 37       | 0.18%   |
| Generalplus Technology                          | 28       | 0.13%   |
| Ensoniq                                         | 24       | 0.11%   |
| Plantronics                                     | 22       | 0.11%   |
| Pixart Imaging                                  | 18       | 0.09%   |
| ASUSTek Computer                                | 18       | 0.09%   |
| Tenx Technology                                 | 17       | 0.08%   |
| ULi Electronics                                 | 15       | 0.07%   |
| Razer USA                                       | 14       | 0.07%   |
| Kingston Technology                             | 10       | 0.05%   |
| Aureal Semiconductor                            | 10       | 0.05%   |
| Yamaha                                          | 9        | 0.04%   |
| Shenzhen Rapoo Technology                       | 9        | 0.04%   |
| ESS Technology                                  | 9        | 0.04%   |
| Asahi Kasei Microsystems                        | 9        | 0.04%   |
| A4Tech                                          | 9        | 0.04%   |
| ATI Technologies                                | 8        | 0.04%   |
| Guillemot                                       | 7        | 0.03%   |
| XMOS                                            | 6        | 0.03%   |
| Sony                                            | 6        | 0.03%   |
| Philips (or NXP)                                | 6        | 0.03%   |
| M-Audio                                         | 6        | 0.03%   |
| Licensed by Sony Computer Entertainment America | 6        | 0.03%   |
| Fortemedia                                      | 6        | 0.03%   |
| Yealink Network Technology                      | 5        | 0.02%   |
| Samson Technologies                             | 5        | 0.02%   |
| Micro Star International                        | 5        | 0.02%   |
| iCreate Technologies                            | 5        | 0.02%   |
| Focusrite-Novation                              | 5        | 0.02%   |
| EGO SYStems                                     | 5        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1963     | 8.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1925     | 8.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1308     | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 782      | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 778      | 3.34%   |
| Nvidia GF108 High Definition Audio Controller                                     | 719      | 3.09%   |
| Nvidia MCP61 High Definition Audio                                                | 646      | 2.77%   |
| Nvidia High Definition Audio Controller                                           | 622      | 2.67%   |
| AMD FCH Azalia Controller                                                         | 611      | 2.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 597      | 2.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 555      | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 484      | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 424      | 1.82%   |
| Nvidia GK107 HDMI Audio Controller                                                | 418      | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 407      | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 375      | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 349      | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 311      | 1.34%   |
| Nvidia GF116 High Definition Audio Controller                                     | 310      | 1.33%   |
| Nvidia GK106 HDMI Audio Controller                                                | 298      | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 296      | 1.27%   |
| Nvidia GF119 HDMI Audio Controller                                                | 283      | 1.22%   |
| Nvidia GK104 HDMI Audio Controller                                                | 239      | 1.03%   |
| Intel 200 Series PCH HD Audio                                                     | 226      | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 210      | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 199      | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 195      | 0.84%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 194      | 0.83%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 189      | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 177      | 0.76%   |
| AMD Family 17h/19h HD Audio Controller                                            | 170      | 0.73%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 166      | 0.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 163      | 0.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 159      | 0.68%   |
| Nvidia GF114 HDMI Audio Controller                                                | 156      | 0.67%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 154      | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                     | 152      | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 152      | 0.65%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 138      | 0.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 133      | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6947     | 48.74%  |
| Kingston            | 2338     | 16.4%   |
| Samsung Electronics | 825      | 5.79%   |
| Crucial             | 721      | 5.06%   |
| SK hynix            | 609      | 4.27%   |
| Corsair             | 564      | 3.96%   |
| Micron Technology   | 230      | 1.61%   |
| AMD                 | 222      | 1.56%   |
| Patriot             | 219      | 1.54%   |
| Nanya Technology    | 134      | 0.94%   |
| GOODRAM             | 125      | 0.88%   |
| A-DATA Technology   | 112      | 0.79%   |
| G.Skill             | 101      | 0.71%   |
| Silicon Power       | 94       | 0.66%   |
| Transcend           | 86       | 0.6%    |
| Kingmax             | 83       | 0.58%   |
| Elpida              | 79       | 0.55%   |
| Qumo                | 60       | 0.42%   |
| GeIL                | 55       | 0.39%   |
| Apacer              | 54       | 0.38%   |
| Team                | 53       | 0.37%   |
| Goldkey             | 48       | 0.34%   |
| Unknown             | 36       | 0.25%   |
| Ramaxel Technology  | 35       | 0.25%   |
| Kllisre             | 34       | 0.24%   |
| KETECH              | 30       | 0.21%   |
| Unifosa             | 29       | 0.2%    |
| Foxline             | 28       | 0.2%    |
| Qimonda             | 25       | 0.18%   |
| Atermiter           | 20       | 0.14%   |
| Ramos Technology    | 18       | 0.13%   |
| TakeMS              | 14       | 0.1%    |
| Unknown (ABCD)      | 13       | 0.09%   |
| OCZ                 | 10       | 0.07%   |
| Hexon               | 10       | 0.07%   |
| Exceleram           | 10       | 0.07%   |
| TwinMOS             | 7        | 0.05%   |
| PNY                 | 6        | 0.04%   |
| ASint Technology    | 6        | 0.04%   |
| Aeneon              | 6        | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 487      | 2.91%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 468      | 2.79%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 442      | 2.64%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 415      | 2.48%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 371      | 2.21%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 352      | 2.1%    |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s           | 324      | 1.93%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 250      | 1.49%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 248      | 1.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 206      | 1.23%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 164      | 0.98%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 160      | 0.95%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 156      | 0.93%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 146      | 0.87%   |
| Unknown RAM Module 512MB DIMM SDRAM                   | 144      | 0.86%   |
| Unknown RAM Module 1024MB DIMM                        | 138      | 0.82%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 132      | 0.79%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 126      | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s          | 104      | 0.62%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 102      | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 101      | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR2                   | 98       | 0.58%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 95       | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s           | 94       | 0.56%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s               | 87       | 0.52%   |
| Unknown RAM Module 2048MB DIMM                        | 82       | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 76       | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s           | 75       | 0.45%   |
| Unknown RAM Module 512MB DIMM                         | 74       | 0.44%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 73       | 0.44%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 69       | 0.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s   | 69       | 0.41%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s | 68       | 0.41%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                | 67       | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s            | 60       | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s           | 58       | 0.35%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s            | 57       | 0.34%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s | 57       | 0.34%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                | 56       | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s               | 56       | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4532     | 34.77%  |
| Unknown | 2916     | 22.37%  |
| DDR2    | 2112     | 16.2%   |
| SDRAM   | 1504     | 11.54%  |
| DDR4    | 1445     | 11.08%  |
| DDR     | 482      | 3.7%    |
| DRAM    | 22       | 0.17%   |
| LPDDR4  | 16       | 0.12%   |
| DDR5    | 7        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 12548    | 97.82%  |
| SODIMM       | 271      | 2.11%   |
| FB-DIMM      | 8        | 0.06%   |
| Row Of Chips | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 4767     | 31.52%  |
| 4096  | 4267     | 28.21%  |
| 1024  | 2760     | 18.25%  |
| 8192  | 2163     | 14.3%   |
| 512   | 695      | 4.59%   |
| 16384 | 238      | 1.57%   |
| 256   | 165      | 1.09%   |
| 32768 | 59       | 0.39%   |
| 128   | 5        | 0.03%   |
| 32    | 4        | 0.03%   |
| 16    | 3        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 2511     | 17.83%  |
| 1333    | 2502     | 17.77%  |
| 800     | 1935     | 13.74%  |
| Unknown | 1505     | 10.69%  |
| 667     | 1125     | 7.99%   |
| 2400    | 474      | 3.37%   |
| 400     | 465      | 3.3%    |
| 2133    | 389      | 2.76%   |
| 1867    | 289      | 2.05%   |
| 1066    | 259      | 1.84%   |
| 533     | 249      | 1.77%   |
| 333     | 221      | 1.57%   |
| 2667    | 218      | 1.55%   |
| 3200    | 190      | 1.35%   |
| 1866    | 178      | 1.26%   |
| 3600    | 136      | 0.97%   |
| 1800    | 133      | 0.94%   |
| 3400    | 98       | 0.7%    |
| 266     | 96       | 0.68%   |
| 1067    | 89       | 0.63%   |
| 2933    | 71       | 0.5%    |
| 1334    | 64       | 0.45%   |
| 2666    | 53       | 0.38%   |
| 3000    | 50       | 0.36%   |
| 66      | 49       | 0.35%   |
| 3466    | 43       | 0.31%   |
| 2000    | 43       | 0.31%   |
| 2048    | 39       | 0.28%   |
| 2800    | 38       | 0.27%   |
| 1648    | 37       | 0.26%   |
| 1400    | 36       | 0.26%   |
| 1639    | 35       | 0.25%   |
| 3266    | 32       | 0.23%   |
| 2134    | 31       | 0.22%   |
| 3333    | 28       | 0.2%    |
| 200     | 28       | 0.2%    |
| 49926   | 25       | 0.18%   |
| 3334    | 15       | 0.11%   |
| 2866    | 15       | 0.11%   |
| 3066    | 14       | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 420      | 31%     |
| Canon                           | 315      | 23.25%  |
| Samsung Electronics             | 233      | 17.2%   |
| Seiko Epson                     | 133      | 9.82%   |
| Brother Industries              | 87       | 6.42%   |
| Xerox                           | 39       | 2.88%   |
| Panasonic (Matsushita)          | 25       | 1.85%   |
| Kyocera                         | 23       | 1.7%    |
| Pantum                          | 19       | 1.4%    |
| Ricoh                           | 13       | 0.96%   |
| Prolific Technology             | 10       | 0.74%   |
| Lexmark International           | 8        | 0.59%   |
| QinHeng Electronics             | 6        | 0.44%   |
| TSC Auto ID Technology          | 4        | 0.3%    |
| WinChipHead                     | 3        | 0.22%   |
| STMicroelectronics              | 2        | 0.15%   |
| Sharp                           | 2        | 0.15%   |
| Custom Engineering SPA          | 2        | 0.15%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.15%   |
| Yurex                           | 1        | 0.07%   |
| Toshiba TEC                     | 1        | 0.07%   |
| Samsung Info. Systems America   | 1        | 0.07%   |
| NXP Semiconductors              | 1        | 0.07%   |
| NCR                             | 1        | 0.07%   |
| Konica Minolta                  | 1        | 0.07%   |
| KODAK                           | 1        | 0.07%   |
| Fuji Xerox                      | 1        | 0.07%   |
| ATEN International              | 1        | 0.07%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 46       | 3.34%   |
| HP LaserJet 1018                      | 39       | 2.83%   |
| HP LaserJet P1102                     | 34       | 2.47%   |
| Samsung SCX-4200 series               | 33       | 2.4%    |
| Canon LBP2900                         | 33       | 2.4%    |
| Seiko Epson Printer                   | 28       | 2.03%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 22       | 1.6%    |
| Samsung SCX-3400 Series               | 19       | 1.38%   |
| HP LaserJet P1005                     | 19       | 1.38%   |
| HP LaserJet 1010                      | 19       | 1.38%   |
| Canon MF4410                          | 19       | 1.38%   |
| Samsung SCX-3200 Series               | 18       | 1.31%   |
| Canon MF3010                          | 18       | 1.31%   |
| Panasonic (Matsushita) KX-MB1500RU    | 17       | 1.23%   |
| Samsung ML-1640 Series Laser Printer  | 15       | 1.09%   |
| Canon MF4010 series                   | 14       | 1.02%   |
| Seiko Epson L210 Series               | 13       | 0.94%   |
| Canon LBP810                          | 12       | 0.87%   |
| Canon LBP3010/LBP3018/LBP3050         | 12       | 0.87%   |
| Xerox Phaser 3140 and 3155            | 11       | 0.8%    |
| Samsung ML-2010P Mono Laser Printer   | 11       | 0.8%    |
| Samsung ML-1210 Printer               | 11       | 0.8%    |
| HP LaserJet 1022                      | 11       | 0.8%    |
| HP Deskjet 2050 J510                  | 11       | 0.8%    |
| Canon LaserShot LBP-1120 Printer      | 11       | 0.8%    |
| Canon iP7200 series                   | 11       | 0.8%    |
| Brother DCP-7057 scanner/printer      | 11       | 0.8%    |
| Prolific PL2305 Parallel Port         | 10       | 0.73%   |
| HP LaserJet 1320                      | 10       | 0.73%   |
| HP LaserJet 1000                      | 10       | 0.73%   |
| HP DeskJet 2130 series                | 10       | 0.73%   |
| Canon PIXMA MG2500 Series             | 10       | 0.73%   |
| Canon LBP6000                         | 10       | 0.73%   |
| Brother HL-2030 Laser Printer         | 10       | 0.73%   |
| Samsung SCX-4100 Scanner              | 9        | 0.65%   |
| Samsung M2070 Series                  | 9        | 0.65%   |
| HP LaserJet P1006                     | 9        | 0.65%   |
| HP LaserJet 1200                      | 9        | 0.65%   |
| Canon PIXMA MP230                     | 9        | 0.65%   |
| Canon MG2400 series                   | 9        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 148      | 37.66%  |
| Seiko Epson                 | 93       | 23.66%  |
| Hewlett-Packard             | 67       | 17.05%  |
| Mustek Systems              | 39       | 9.92%   |
| Acer Peripherals (now BenQ) | 16       | 4.07%   |
| Ultima Electronics          | 15       | 3.82%   |
| KYE Systems (Mouse Systems) | 5        | 1.27%   |
| Fujitsu                     | 3        | 0.76%   |
| Avision                     | 2        | 0.51%   |
| AGFA-Gevaert NV             | 2        | 0.51%   |
| Plustek                     | 1        | 0.25%   |
| Microtek International      | 1        | 0.25%   |
| Canon Electronics           | 1        | 0.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                                                | 27       | 6.85%   |
| Canon CanoScan LiDE 110                                                               | 22       | 5.58%   |
| HP ScanJet 2400c                                                                      | 21       | 5.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 17       | 4.31%   |
| Canon CanoScan LiDE 120                                                               | 16       | 4.06%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 15       | 3.81%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 14       | 3.55%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 13       | 3.3%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 11       | 2.79%   |
| Canon CanoScan LiDE 210                                                               | 11       | 2.79%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 10       | 2.54%   |
| Canon CanoScan LiDE 60                                                                | 10       | 2.54%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 2.03%   |
| Canon CanoScan LiDE 100                                                               | 8        | 2.03%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 7        | 1.78%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 7        | 1.78%   |
| Canon CanoScan LiDE 220                                                               | 7        | 1.78%   |
| Seiko Epson Perfection 660                                                            | 6        | 1.52%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 6        | 1.52%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.27%   |
| Mustek Systems SNAPSCAN e22                                                           | 5        | 1.27%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5        | 1.27%   |
| Canon CanoScan                                                                        | 5        | 1.27%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 5        | 1.27%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4        | 1.02%   |
| HP ScanJet 3800c                                                                      | 4        | 1.02%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4        | 1.02%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 3        | 0.76%   |
| HP ScanJet 3970c                                                                      | 3        | 0.76%   |
| HP ScanJet 2200c                                                                      | 3        | 0.76%   |
| HP PSC 1200                                                                           | 3        | 0.76%   |
| Fujitsu ScanSnap SV600                                                                | 3        | 0.76%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3        | 0.76%   |
| Canon CanoScan LiDE 90                                                                | 3        | 0.76%   |
| Canon CanoScan LiDE 70                                                                | 3        | 0.76%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 3        | 0.76%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 2        | 0.51%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2        | 0.51%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.51%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.51%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech                        | 1021     | 32.54%  |
| Z-Star Microelectronics         | 596      | 18.99%  |
| Microdia                        | 263      | 8.38%   |
| Microsoft                       | 162      | 5.16%   |
| KYE Systems (Mouse Systems)     | 120      | 3.82%   |
| Cubeternet                      | 102      | 3.25%   |
| Pixart Imaging                  | 96       | 3.06%   |
| Aveo Technology                 | 96       | 3.06%   |
| Arkmicro Technologies           | 96       | 3.06%   |
| GEMBIRD                         | 81       | 2.58%   |
| Chicony Electronics             | 53       | 1.69%   |
| Realtek Semiconductor           | 46       | 1.47%   |
| Samsung Electronics             | 42       | 1.34%   |
| Creative Technology             | 39       | 1.24%   |
| Alcor Micro                     | 30       | 0.96%   |
| Apple                           | 29       | 0.92%   |
| Guillemot                       | 21       | 0.67%   |
| Genesys Logic                   | 18       | 0.57%   |
| Philips (or NXP)                | 17       | 0.54%   |
| Hewlett-Packard                 | 15       | 0.48%   |
| Sunplus Innovation Technology   | 14       | 0.45%   |
| Silicon Motion                  | 14       | 0.45%   |
| Nokia Mobile Phones             | 13       | 0.41%   |
| SiGma Micro                     | 10       | 0.32%   |
| IMC Networks                    | 10       | 0.32%   |
| Generalplus Technology          | 10       | 0.32%   |
| A4Tech                          | 10       | 0.32%   |
| Trust                           | 7        | 0.22%   |
| lihappe8                        | 6        | 0.19%   |
| Suyin                           | 5        | 0.16%   |
| SunplusIT                       | 5        | 0.16%   |
| Canon                           | 5        | 0.16%   |
| Unknown                         | 4        | 0.13%   |
| Sunplus IT                      | 4        | 0.13%   |
| Google                          | 4        | 0.13%   |
| Fitipower Integrated Technology | 4        | 0.13%   |
| Bison Electronics               | 4        | 0.13%   |
| Sweex                           | 3        | 0.1%    |
| Sony                            | 3        | 0.1%    |
| Panasonic (Matsushita)          | 3        | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 340      | 10.81%  |
| Z-Star Venus USB2.0 Camera                        | 272      | 8.65%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 159      | 5.06%   |
| Microdia Camera                                   | 142      | 4.52%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 117      | 3.72%   |
| Logitech Webcam C170                              | 89       | 2.83%   |
| Arkmicro USB2.0 PC CAMERA                         | 87       | 2.77%   |
| Logitech Webcam C310                              | 81       | 2.58%   |
| Logitech Webcam C210                              | 80       | 2.54%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 72       | 2.29%   |
| Logitech HD Webcam C525                           | 64       | 2.04%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 55       | 1.75%   |
| Microsoft LifeCam HD-3000                         | 51       | 1.62%   |
| Logitech Webcam C110                              | 50       | 1.59%   |
| GEMBIRD USB2.0 PC CAMERA                          | 46       | 1.46%   |
| Microdia Sonix USB 2.0 Camera                     | 45       | 1.43%   |
| Samsung Galaxy A5 (MTP)                           | 40       | 1.27%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 34       | 1.08%   |
| Logitech HD Webcam C510                           | 33       | 1.05%   |
| Aveo USB2.0 Camera                                | 33       | 1.05%   |
| Aveo Camera                                       | 33       | 1.05%   |
| Microdia USB 2.0 Camera                           | 31       | 0.99%   |
| Logitech HD Pro Webcam C920                       | 31       | 0.99%   |
| Cubeternet USB2.0 Camera                          | 29       | 0.92%   |
| Microsoft LifeCam VX-800                          | 28       | 0.89%   |
| Logitech Logitech Webcam C100                     | 28       | 0.89%   |
| Logitech Logitech Webcam C160                     | 27       | 0.86%   |
| Realtek FULL HD 1080P Webcam                      | 26       | 0.83%   |
| Aveo UVC camera (Bresser microscope)              | 26       | 0.83%   |
| Logitech Webcam C250                              | 22       | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 22       | 0.7%    |
| Alcor Micro USB 2.0 PC Camera                     | 22       | 0.7%    |
| Microsoft LifeCam VX-2000                         | 20       | 0.64%   |
| Logitech HD Webcam C910                           | 20       | 0.64%   |
| Microdia MSI Starcam Racer                        | 19       | 0.6%    |
| Logitech Webcam C120                              | 19       | 0.6%    |
| Microsoft LifeCam HD-5000                         | 18       | 0.57%   |
| Logitech Webcam C200                              | 18       | 0.57%   |
| Logitech HD Webcam C615                           | 18       | 0.57%   |
| Z-Star A4 TECH HD PC Camera                       | 15       | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 33.33%  |
| Microsoft             | 2        | 33.33%  |
| LighTuning Technology | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader            | 2        | 33.33%  |
| Microsoft Fingerprint Reader                     | 2        | 33.33%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1        | 16.67%  |
| DigitalPersona Fingerprint Scanner, U.are.U 2000 | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Aladdin Knowledge Systems               | 11       | 18.64%  |
| Alcor Micro                             | 10       | 16.95%  |
| Advanced Card Systems                   | 9        | 15.25%  |
| Aktiv                                   | 7        | 11.86%  |
| OmniKey                                 | 5        | 8.47%   |
| Realtek Semiconductor                   | 4        | 6.78%   |
| Athena Smartcard Solutions              | 4        | 6.78%   |
| Castles Technology                      | 2        | 3.39%   |
| Reiner SCT Kartensysteme                | 1        | 1.69%   |
| Gemalto (was Gemplus)                   | 1        | 1.69%   |
| Future Technology Devices International | 1        | 1.69%   |
| Cherry                                  | 1        | 1.69%   |
| BIFIT                                   | 1        | 1.69%   |
| Avtor                                   | 1        | 1.69%   |
| Aladdin R.D.                            | 1        | 1.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Aladdin Knowledge Systems Token JC                                         | 11       | 18.64%  |
| Alcor Micro Watchdata W 1981                                               | 7        | 11.86%  |
| Aktiv Rutoken lite                                                         | 6        | 10.17%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 6.78%   |
| OmniKey CardMan 1021                                                       | 4        | 6.78%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 4        | 6.78%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 5.08%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 5.08%   |
| Castles Technology EZCCID Smart Card Reader                                | 2        | 3.39%   |
| Advanced Card Systems Token USB 64K                                        | 2        | 3.39%   |
| Advanced Card Systems ACR3901U                                             | 2        | 3.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 1.69%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 1.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 1.69%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08      | 1        | 1.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 1.69%   |
| BIFIT iBank2Key                                                            | 1        | 1.69%   |
| Avtor SecureToken                                                          | 1        | 1.69%   |
| Aladdin R.D. JaCarta                                                       | 1        | 1.69%   |
| Aktiv KAZTOKEN                                                             | 1        | 1.69%   |
| Advanced Card Systems ACR39U                                               | 1        | 1.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 11833    | 86.83%  |
| 1     | 1639     | 12.03%  |
| 2     | 138      | 1.01%   |
| 3     | 15       | 0.11%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |
| 4     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1131     | 59.4%   |
| Net/wireless             | 212      | 11.13%  |
| Communication controller | 158      | 8.3%    |
| Multimedia controller    | 106      | 5.57%   |
| Camera                   | 64       | 3.36%   |
| Unassigned class         | 55       | 2.89%   |
| Chipcard                 | 52       | 2.73%   |
| Modem                    | 28       | 1.47%   |
| Sound                    | 23       | 1.21%   |
| Dvb card                 | 13       | 0.68%   |
| Network                  | 12       | 0.63%   |
| Net/ethernet             | 11       | 0.58%   |
| Bluetooth                | 10       | 0.53%   |
| Tv card                  | 5        | 0.26%   |
| Card reader              | 5        | 0.26%   |
| Storage/raid             | 4        | 0.21%   |
| Storage/ata              | 4        | 0.21%   |
| Storage                  | 4        | 0.21%   |
| Fingerprint reader       | 4        | 0.21%   |
| Video                    | 2        | 0.11%   |
| Storage/ide              | 1        | 0.05%   |

