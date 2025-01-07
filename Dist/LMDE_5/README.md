LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 791

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC600 v1.0           | Desktop     | [2f22befa4d](https://linux-hardware.org/?probe=2f22befa4d) | Jan 01, 2025 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [cad98a7856](https://linux-hardware.org/?probe=cad98a7856) | Jan 01, 2025 |
| PLEXHD        | X79 Turbo                   | Desktop     | [e1891a209b](https://linux-hardware.org/?probe=e1891a209b) | Nov 22, 2024 |
| PLEXHD        | X79 Turbo                   | Desktop     | [898dc2c319](https://linux-hardware.org/?probe=898dc2c319) | Nov 04, 2024 |
| eMachines     | eM350                       | Notebook    | [2e70a62535](https://linux-hardware.org/?probe=2e70a62535) | Oct 16, 2024 |
| Lenovo        | ThinkPad T460p 20FXS09D0... | Notebook    | [aff398dad9](https://linux-hardware.org/?probe=aff398dad9) | Oct 05, 2024 |
| Lenovo        | ThinkPad T460p 20FXS09D0... | Notebook    | [0ff2303573](https://linux-hardware.org/?probe=0ff2303573) | Aug 31, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [801e7f0d37](https://linux-hardware.org/?probe=801e7f0d37) | Aug 12, 2024 |
| ASRock        | Z68M-ITX/HT                 | Desktop     | [ec4ca88b8b](https://linux-hardware.org/?probe=ec4ca88b8b) | Aug 01, 2024 |
| ASUSTek       | P5K SE                      | Desktop     | [b860e6df76](https://linux-hardware.org/?probe=b860e6df76) | Jul 24, 2024 |
| ASUSTek       | P5K SE                      | Desktop     | [6f0ebdcb04](https://linux-hardware.org/?probe=6f0ebdcb04) | Jul 24, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [a0f01e0864](https://linux-hardware.org/?probe=a0f01e0864) | Jul 01, 2024 |
| Prestigio     | PSB141C03                   | Notebook    | [c7612dfd34](https://linux-hardware.org/?probe=c7612dfd34) | Jun 03, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [ab3b880704](https://linux-hardware.org/?probe=ab3b880704) | May 28, 2024 |
| ASUSTek       | 900                         | Notebook    | [9d033691b4](https://linux-hardware.org/?probe=9d033691b4) | May 19, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [4da89e5d1d](https://linux-hardware.org/?probe=4da89e5d1d) | May 05, 2024 |
| Star Labs     | StarBook                    | Notebook    | [637a8da717](https://linux-hardware.org/?probe=637a8da717) | May 02, 2024 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [9fbe4e85f5](https://linux-hardware.org/?probe=9fbe4e85f5) | May 01, 2024 |
| Intel         | DQ77MK AAG39642-302         | Desktop     | [0e7e9ec585](https://linux-hardware.org/?probe=0e7e9ec585) | Apr 26, 2024 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [741937c8be](https://linux-hardware.org/?probe=741937c8be) | Apr 23, 2024 |
| Lenovo        | 3746 WIN SDK0T76465 3422... | All in one  | [e9064cfefc](https://linux-hardware.org/?probe=e9064cfefc) | Mar 29, 2024 |
| Dell          | Latitude E6500              | Notebook    | [e623a98775](https://linux-hardware.org/?probe=e623a98775) | Mar 18, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [64e9cf77dc](https://linux-hardware.org/?probe=64e9cf77dc) | Mar 11, 2024 |
| Dell          | Latitude E6500              | Notebook    | [e03e94f299](https://linux-hardware.org/?probe=e03e94f299) | Mar 08, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [c7b2c1d469](https://linux-hardware.org/?probe=c7b2c1d469) | Mar 08, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [10852897a2](https://linux-hardware.org/?probe=10852897a2) | Mar 04, 2024 |
| Acer          | Veriton M480                | Desktop     | [c8ed2099cb](https://linux-hardware.org/?probe=c8ed2099cb) | Mar 02, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [0eb252845c](https://linux-hardware.org/?probe=0eb252845c) | Feb 24, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [70e8bb7037](https://linux-hardware.org/?probe=70e8bb7037) | Feb 23, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [373d3866b8](https://linux-hardware.org/?probe=373d3866b8) | Feb 20, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [ccf721c85c](https://linux-hardware.org/?probe=ccf721c85c) | Feb 10, 2024 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [3e0e2fd80a](https://linux-hardware.org/?probe=3e0e2fd80a) | Feb 03, 2024 |
| Lenovo        | ThinkPad T540p 20BE0060M... | Notebook    | [71296d9e0f](https://linux-hardware.org/?probe=71296d9e0f) | Feb 02, 2024 |
| Acer          | TravelMate 4220             | Notebook    | [73e17ddd6d](https://linux-hardware.org/?probe=73e17ddd6d) | Feb 01, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [ec094665df](https://linux-hardware.org/?probe=ec094665df) | Jan 09, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [e15da7350e](https://linux-hardware.org/?probe=e15da7350e) | Jan 07, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [b98b78a3df](https://linux-hardware.org/?probe=b98b78a3df) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [243e9d1b27](https://linux-hardware.org/?probe=243e9d1b27) | Jan 02, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [65ddbd761c](https://linux-hardware.org/?probe=65ddbd761c) | Jan 02, 2024 |
| Intel         | B75                         | Desktop     | [df9a51de80](https://linux-hardware.org/?probe=df9a51de80) | Dec 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9362181823](https://linux-hardware.org/?probe=9362181823) | Dec 14, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [e2c79fa4d1](https://linux-hardware.org/?probe=e2c79fa4d1) | Dec 13, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [9936eed724](https://linux-hardware.org/?probe=9936eed724) | Dec 12, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [d89c55cb89](https://linux-hardware.org/?probe=d89c55cb89) | Nov 24, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [dbce2ba706](https://linux-hardware.org/?probe=dbce2ba706) | Nov 23, 2023 |
| Pegatron      | 2ADC                        | Desktop     | [683e6fe69e](https://linux-hardware.org/?probe=683e6fe69e) | Nov 20, 2023 |
| Pegatron      | 2ADC                        | Desktop     | [ff6ee5f1e5](https://linux-hardware.org/?probe=ff6ee5f1e5) | Nov 20, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [bff17ec47d](https://linux-hardware.org/?probe=bff17ec47d) | Nov 20, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [41d4402bf3](https://linux-hardware.org/?probe=41d4402bf3) | Nov 17, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [b9f38bd221](https://linux-hardware.org/?probe=b9f38bd221) | Nov 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a2fbd58a8c](https://linux-hardware.org/?probe=a2fbd58a8c) | Nov 05, 2023 |
| Medion        | E6214                       | Notebook    | [65976063e7](https://linux-hardware.org/?probe=65976063e7) | Nov 04, 2023 |
| Multilaser    | PC13X                       | Notebook    | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [c3e7ebfd20](https://linux-hardware.org/?probe=c3e7ebfd20) | Oct 23, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [4f2229b9fa](https://linux-hardware.org/?probe=4f2229b9fa) | Oct 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3379c8b4e7](https://linux-hardware.org/?probe=3379c8b4e7) | Oct 21, 2023 |
| Alienware     | m15                         | Notebook    | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | Notebook    | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [3727598ae7](https://linux-hardware.org/?probe=3727598ae7) | Oct 09, 2023 |
| Medion        | TJ4125                      | Desktop     | [626065ec1b](https://linux-hardware.org/?probe=626065ec1b) | Oct 03, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ee49b13b77](https://linux-hardware.org/?probe=ee49b13b77) | Oct 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8008433230](https://linux-hardware.org/?probe=8008433230) | Oct 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bc2e88dd9c](https://linux-hardware.org/?probe=bc2e88dd9c) | Sep 30, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9fe3adb466](https://linux-hardware.org/?probe=9fe3adb466) | Sep 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c93318bf50](https://linux-hardware.org/?probe=c93318bf50) | Sep 28, 2023 |
| Dell          | 0H19HD A01                  | Server      | [fb5fb07ca9](https://linux-hardware.org/?probe=fb5fb07ca9) | Sep 28, 2023 |
| Dell          | 0H19HD A01                  | Server      | [643dd60247](https://linux-hardware.org/?probe=643dd60247) | Sep 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [1d749b29ad](https://linux-hardware.org/?probe=1d749b29ad) | Sep 28, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e87c0e3c00](https://linux-hardware.org/?probe=e87c0e3c00) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [b62d121676](https://linux-hardware.org/?probe=b62d121676) | Sep 26, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7e142652b2](https://linux-hardware.org/?probe=7e142652b2) | Sep 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8bdc8129ff](https://linux-hardware.org/?probe=8bdc8129ff) | Sep 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [87cba2e3a2](https://linux-hardware.org/?probe=87cba2e3a2) | Sep 24, 2023 |
| Acer          | Aspire A317-51G             | Notebook    | [16870a488b](https://linux-hardware.org/?probe=16870a488b) | Sep 24, 2023 |
| Medion        | TJ4125                      | Desktop     | [434dd057a6](https://linux-hardware.org/?probe=434dd057a6) | Sep 23, 2023 |
| Lenovo        | ThinkPad Edge E430c 3365... | Notebook    | [74351c4243](https://linux-hardware.org/?probe=74351c4243) | Sep 23, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [48a5b6b71d](https://linux-hardware.org/?probe=48a5b6b71d) | Sep 23, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [7afadf5612](https://linux-hardware.org/?probe=7afadf5612) | Sep 20, 2023 |
| HP            | 859C                        | Desktop     | [7de1553287](https://linux-hardware.org/?probe=7de1553287) | Sep 20, 2023 |
| Toshiba       | Satellite P505              | Notebook    | [2b70bd8027](https://linux-hardware.org/?probe=2b70bd8027) | Sep 19, 2023 |
| Toshiba       | Satellite P505              | Notebook    | [a18f0420ac](https://linux-hardware.org/?probe=a18f0420ac) | Sep 18, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [da930461ec](https://linux-hardware.org/?probe=da930461ec) | Sep 18, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| HP            | x2 210                      | Notebook    | [776f895eec](https://linux-hardware.org/?probe=776f895eec) | Sep 13, 2023 |
| Intel         | X79                         | Desktop     | [e9a4f4dc51](https://linux-hardware.org/?probe=e9a4f4dc51) | Sep 13, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [b0305f4ba4](https://linux-hardware.org/?probe=b0305f4ba4) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [d508e799c4](https://linux-hardware.org/?probe=d508e799c4) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [7b302f492e](https://linux-hardware.org/?probe=7b302f492e) | Sep 10, 2023 |
| Medion        | TJ4125                      | Desktop     | [80a4e5fbff](https://linux-hardware.org/?probe=80a4e5fbff) | Sep 09, 2023 |
| HP            | 859C                        | Desktop     | [c113eb162e](https://linux-hardware.org/?probe=c113eb162e) | Sep 09, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [00a11a78f5](https://linux-hardware.org/?probe=00a11a78f5) | Sep 09, 2023 |
| Dell          | Precision M4700             | Notebook    | [919035c3c7](https://linux-hardware.org/?probe=919035c3c7) | Sep 08, 2023 |
| Dell          | Precision M4700             | Notebook    | [2c666d6616](https://linux-hardware.org/?probe=2c666d6616) | Sep 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1591677e7f](https://linux-hardware.org/?probe=1591677e7f) | Sep 07, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3389baa197](https://linux-hardware.org/?probe=3389baa197) | Sep 07, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [c7bea10745](https://linux-hardware.org/?probe=c7bea10745) | Sep 07, 2023 |
| Dell          | Precision M4700             | Notebook    | [3e354770b6](https://linux-hardware.org/?probe=3e354770b6) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f73f6d9301](https://linux-hardware.org/?probe=f73f6d9301) | Sep 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [61c5e35c02](https://linux-hardware.org/?probe=61c5e35c02) | Sep 05, 2023 |
| Lenovo        | 3000 N200 0769EGG           | Notebook    | [44fd3c6e60](https://linux-hardware.org/?probe=44fd3c6e60) | Sep 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f5e7afad66](https://linux-hardware.org/?probe=f5e7afad66) | Sep 04, 2023 |
| Medion        | TJ4125                      | Desktop     | [e2e111051c](https://linux-hardware.org/?probe=e2e111051c) | Sep 03, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [d6b74ca876](https://linux-hardware.org/?probe=d6b74ca876) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e58d4f8405](https://linux-hardware.org/?probe=e58d4f8405) | Sep 03, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [17eed28ecb](https://linux-hardware.org/?probe=17eed28ecb) | Sep 02, 2023 |
| Acer          | Aspire X3400                | Desktop     | [62a78b2a16](https://linux-hardware.org/?probe=62a78b2a16) | Sep 01, 2023 |
| Lenovo        | ThinkPad L390 20NR000FUS    | Notebook    | [b4d7adfb97](https://linux-hardware.org/?probe=b4d7adfb97) | Sep 01, 2023 |
| HP            | ENVY m6                     | Notebook    | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [3d736730c7](https://linux-hardware.org/?probe=3d736730c7) | Aug 31, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| HP            | 859C                        | Desktop     | [978d715b29](https://linux-hardware.org/?probe=978d715b29) | Aug 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| eMachines     | EL1852G                     | Desktop     | [68db025f09](https://linux-hardware.org/?probe=68db025f09) | Aug 25, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [38f3df41d7](https://linux-hardware.org/?probe=38f3df41d7) | Aug 24, 2023 |
| eMachines     | EL1852G                     | Desktop     | [ea782989fd](https://linux-hardware.org/?probe=ea782989fd) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [e5c40536c3](https://linux-hardware.org/?probe=e5c40536c3) | Aug 23, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [0122f2caab](https://linux-hardware.org/?probe=0122f2caab) | Aug 23, 2023 |
| HP            | 859C                        | Desktop     | [63f9e00825](https://linux-hardware.org/?probe=63f9e00825) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [0f2259e2b8](https://linux-hardware.org/?probe=0f2259e2b8) | Aug 22, 2023 |
| Positivo      | CHT14B                      | Notebook    | [28106aa94b](https://linux-hardware.org/?probe=28106aa94b) | Aug 19, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [cce6cb2878](https://linux-hardware.org/?probe=cce6cb2878) | Aug 18, 2023 |
| Gateway       | NE71B                       | Notebook    | [ba5e9df4ec](https://linux-hardware.org/?probe=ba5e9df4ec) | Aug 18, 2023 |
| Multilaser    | PC13X                       | Notebook    | [d79767b027](https://linux-hardware.org/?probe=d79767b027) | Aug 15, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8803256d2e](https://linux-hardware.org/?probe=8803256d2e) | Aug 14, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [61edf8f5ee](https://linux-hardware.org/?probe=61edf8f5ee) | Aug 14, 2023 |
| Medion        | TJ4125                      | Desktop     | [e24dc34df5](https://linux-hardware.org/?probe=e24dc34df5) | Aug 13, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6289a9e628](https://linux-hardware.org/?probe=6289a9e628) | Aug 12, 2023 |
| HP            | 859C                        | Desktop     | [24dd090f2c](https://linux-hardware.org/?probe=24dd090f2c) | Aug 09, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c86495f999](https://linux-hardware.org/?probe=c86495f999) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7fe1ce642a](https://linux-hardware.org/?probe=7fe1ce642a) | Aug 08, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dbcb2c4a80](https://linux-hardware.org/?probe=dbcb2c4a80) | Aug 07, 2023 |
| Medion        | TJ4125                      | Desktop     | [e35dc275ce](https://linux-hardware.org/?probe=e35dc275ce) | Aug 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [0adec5cb7e](https://linux-hardware.org/?probe=0adec5cb7e) | Aug 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d3df0e8ee1](https://linux-hardware.org/?probe=d3df0e8ee1) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [499fc30d3a](https://linux-hardware.org/?probe=499fc30d3a) | Aug 03, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [37725aaff8](https://linux-hardware.org/?probe=37725aaff8) | Aug 03, 2023 |
| Intel         | X79                         | Desktop     | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [12932af713](https://linux-hardware.org/?probe=12932af713) | Jul 29, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [9d7e65fc0f](https://linux-hardware.org/?probe=9d7e65fc0f) | Jul 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [0882778c0a](https://linux-hardware.org/?probe=0882778c0a) | Jul 28, 2023 |
| Gateway       | NE71B                       | Notebook    | [341f524bc5](https://linux-hardware.org/?probe=341f524bc5) | Jul 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [374c405364](https://linux-hardware.org/?probe=374c405364) | Jul 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [199fe99179](https://linux-hardware.org/?probe=199fe99179) | Jul 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7aaa099507](https://linux-hardware.org/?probe=7aaa099507) | Jul 24, 2023 |
| Intel         | X79                         | Desktop     | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | Notebook    | [65dfd39fb4](https://linux-hardware.org/?probe=65dfd39fb4) | Jul 21, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | Notebook    | [f7fcf9f782](https://linux-hardware.org/?probe=f7fcf9f782) | Jul 21, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad W530 2447CN4       | Notebook    | [670e470556](https://linux-hardware.org/?probe=670e470556) | Jul 16, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [53b13b667d](https://linux-hardware.org/?probe=53b13b667d) | Jul 16, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [293fa24c88](https://linux-hardware.org/?probe=293fa24c88) | Jul 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d63b2efc8b](https://linux-hardware.org/?probe=d63b2efc8b) | Jul 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [88fb5ecc29](https://linux-hardware.org/?probe=88fb5ecc29) | Jul 09, 2023 |
| Medion        | TJ4125                      | Desktop     | [efa563ec1f](https://linux-hardware.org/?probe=efa563ec1f) | Jul 09, 2023 |
| Fujitsu Si... | AMILO Pa 1510               | Notebook    | [b51a760728](https://linux-hardware.org/?probe=b51a760728) | Jul 09, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d660aa6f35](https://linux-hardware.org/?probe=d660aa6f35) | Jul 09, 2023 |
| Lenovo        | ThinkPad X240 20AMS3S919    | Notebook    | [63e13bb1f2](https://linux-hardware.org/?probe=63e13bb1f2) | Jul 08, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [87872596c0](https://linux-hardware.org/?probe=87872596c0) | Jul 08, 2023 |
| Medion        | TJ4125                      | Desktop     | [38d2ffe2de](https://linux-hardware.org/?probe=38d2ffe2de) | Jul 08, 2023 |
| Medion        | TJ4125                      | Desktop     | [1de78b3365](https://linux-hardware.org/?probe=1de78b3365) | Jul 07, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [22a3b2defb](https://linux-hardware.org/?probe=22a3b2defb) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [da20e0f159](https://linux-hardware.org/?probe=da20e0f159) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d8113bbdf6](https://linux-hardware.org/?probe=d8113bbdf6) | Jul 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [8d8748e1dc](https://linux-hardware.org/?probe=8d8748e1dc) | Jul 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [89c111d3ec](https://linux-hardware.org/?probe=89c111d3ec) | Jul 02, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8090e762fe](https://linux-hardware.org/?probe=8090e762fe) | Jul 02, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [d305a15992](https://linux-hardware.org/?probe=d305a15992) | Jul 02, 2023 |
| Medion        | TJ4125                      | Desktop     | [e99bd03d75](https://linux-hardware.org/?probe=e99bd03d75) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [729fb2873e](https://linux-hardware.org/?probe=729fb2873e) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [633c55d4ba](https://linux-hardware.org/?probe=633c55d4ba) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [5cebe0a1d0](https://linux-hardware.org/?probe=5cebe0a1d0) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [327794cb1a](https://linux-hardware.org/?probe=327794cb1a) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [95e5472f48](https://linux-hardware.org/?probe=95e5472f48) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [67a44b0d84](https://linux-hardware.org/?probe=67a44b0d84) | Jun 20, 2023 |
| Intel         | X79                         | Desktop     | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0173559ed0](https://linux-hardware.org/?probe=0173559ed0) | Jun 19, 2023 |
| Medion        | TJ4125                      | Desktop     | [4c6aec7e33](https://linux-hardware.org/?probe=4c6aec7e33) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | Compaq 15                   | Notebook    | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Medion        | E6214                       | Notebook    | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | Notebook    | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [fc102c077c](https://linux-hardware.org/?probe=fc102c077c) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [59b855f1a1](https://linux-hardware.org/?probe=59b855f1a1) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3eb12fd9bc](https://linux-hardware.org/?probe=3eb12fd9bc) | Jun 10, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| AZW           | GK mini                     | Desktop     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| Google        | Lick                        | Notebook    | [d220804cab](https://linux-hardware.org/?probe=d220804cab) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| Dell          | G5 5587                     | Notebook    | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [e27deb35b8](https://linux-hardware.org/?probe=e27deb35b8) | Jun 03, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [60f94ec7f1](https://linux-hardware.org/?probe=60f94ec7f1) | Jun 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Intel         | B75                         | Desktop     | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Medion        | TJ4125                      | Desktop     | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Unknown       | X99                         | Desktop     | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [c418655a3f](https://linux-hardware.org/?probe=c418655a3f) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [309f368a92](https://linux-hardware.org/?probe=309f368a92) | Jun 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d38a3af9af](https://linux-hardware.org/?probe=d38a3af9af) | May 27, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [bca0574da6](https://linux-hardware.org/?probe=bca0574da6) | May 27, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2be29f15b4](https://linux-hardware.org/?probe=2be29f15b4) | May 27, 2023 |
| Framework     | Laptop                      | Notebook    | [cdc855ea4c](https://linux-hardware.org/?probe=cdc855ea4c) | May 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [9abb9659a8](https://linux-hardware.org/?probe=9abb9659a8) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [feb9ed8589](https://linux-hardware.org/?probe=feb9ed8589) | May 19, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [ce94bc6589](https://linux-hardware.org/?probe=ce94bc6589) | May 18, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | Desktop     | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | Desktop     | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| AZW           | MINI S                      | Desktop     | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | Desktop     | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [42d9eb5bf8](https://linux-hardware.org/?probe=42d9eb5bf8) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7c946d461d](https://linux-hardware.org/?probe=7c946d461d) | May 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | Notebook    | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| AZW           | SEi                         | Notebook    | [4cd6ab54ba](https://linux-hardware.org/?probe=4cd6ab54ba) | May 08, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| Medion        | TJ4125                      | Desktop     | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [eb82f6baa1](https://linux-hardware.org/?probe=eb82f6baa1) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd7043408f](https://linux-hardware.org/?probe=fd7043408f) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Studio 1555                 | Notebook    | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | Notebook    | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | Desktop     | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3f172b49f2](https://linux-hardware.org/?probe=3f172b49f2) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Medion        | E6214                       | Notebook    | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| Medion        | E6214                       | Notebook    | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [12cb955c6f](https://linux-hardware.org/?probe=12cb955c6f) | Apr 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [9283851416](https://linux-hardware.org/?probe=9283851416) | Apr 06, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3ebdd0188a](https://linux-hardware.org/?probe=3ebdd0188a) | Apr 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [79f326e572](https://linux-hardware.org/?probe=79f326e572) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| Medion        | E6214                       | Notebook    | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | Notebook    | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | Notebook    | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | Notebook    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | Notebook    | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | Desktop     | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | Desktop     | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | Notebook    | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Supermicro    | X10SAE                      | Server      | [fff44d7132](https://linux-hardware.org/?probe=fff44d7132) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| Supermicro    | X10SAE                      | Server      | [b968ea6172](https://linux-hardware.org/?probe=b968ea6172) | Feb 25, 2023 |
| HP            | 2000                        | Notebook    | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | Desktop     | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | Notebook    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Dell          | 0MF24N A03                  | Desktop     | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Compaq        | 420                         | Notebook    | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| Star Labs     | StarBook                    | Notebook    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| HP            | 843C                        | Desktop     | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Dell          | Precision M4800             | Notebook    | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | Notebook    | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | Notebook    | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Intel         | H61M-DS2V                   | Desktop     | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | Desktop     | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | Notebook    | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Fujitsu       | M2010                       | Notebook    | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Google        | Candy                       | Notebook    | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | Notebook    | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | Desktop     | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Google        | Ultima                      | Notebook    | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | Notebook    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | Notebook    | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [5a75bbfc48](https://linux-hardware.org/?probe=5a75bbfc48) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | 8299                        | Desktop     | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | Notebook    | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_5/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-21-amd64          | 74        | 14.02%  |
| 5.10.0-12-amd64          | 62        | 11.74%  |
| 5.10.0-23-amd64          | 52        | 9.85%   |
| 5.10.0-19-amd64          | 37        | 7.01%   |
| 5.10.0-25-amd64          | 34        | 6.44%   |
| 5.10.0-14-amd64          | 30        | 5.68%   |
| 5.10.0-20-amd64          | 29        | 5.49%   |
| 5.10.0-13-amd64          | 27        | 5.11%   |
| 5.10.0-18-amd64          | 25        | 4.73%   |
| 5.10.0-17-amd64          | 21        | 3.98%   |
| 5.10.0-15-amd64          | 19        | 3.6%    |
| 5.10.0-16-amd64          | 14        | 2.65%   |
| 5.10.0-22-amd64          | 13        | 2.46%   |
| 5.10.0-28-amd64          | 7         | 1.33%   |
| 5.10.0-26-amd64          | 6         | 1.14%   |
| 5.10.0-13-686            | 6         | 1.14%   |
| 6.1.0-0.deb11.7-amd64    | 4         | 0.76%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 0.76%   |
| 5.16.0-0.bpo.4-amd64     | 4         | 0.76%   |
| 5.10.0-24-amd64          | 4         | 0.76%   |
| 6.1.0-0.deb11.6-amd64    | 3         | 0.57%   |
| 5.19.0-0.deb11.2-amd64   | 3         | 0.57%   |
| 5.10.0-12-686            | 3         | 0.57%   |
| 6.1.0-23-amd64           | 2         | 0.38%   |
| 6.1.0-13-amd64           | 2         | 0.38%   |
| 6.1.0-0.deb11.5-amd64    | 2         | 0.38%   |
| 5.10.0-27-amd64          | 2         | 0.38%   |
| 5.10.0-27-686            | 2         | 0.38%   |
| 6.7.6-surface-1          | 1         | 0.19%   |
| 6.5.7-surface-2          | 1         | 0.19%   |
| 6.4.12-surface           | 1         | 0.19%   |
| 6.1.11-x64v1-xanmod1     | 1         | 0.19%   |
| 6.1.0-9-amd64            | 1         | 0.19%   |
| 6.1.0-28-amd64           | 1         | 0.19%   |
| 6.1.0-20-amd64           | 1         | 0.19%   |
| 6.1.0-18-amd64           | 1         | 0.19%   |
| 6.1.0-15-amd64           | 1         | 0.19%   |
| 6.1.0-12-amd64           | 1         | 0.19%   |
| 6.1.0-0.deb11.9-amd64    | 1         | 0.19%   |
| 6.1.0-0.deb11.6-rt-amd64 | 1         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 434       | 90.23%  |
| 6.1.0    | 22        | 4.57%   |
| 5.18.0   | 6         | 1.25%   |
| 5.16.0   | 4         | 0.83%   |
| 5.19.0   | 3         | 0.62%   |
| 6.7.6    | 1         | 0.21%   |
| 6.5.7    | 1         | 0.21%   |
| 6.4.12   | 1         | 0.21%   |
| 6.1.11   | 1         | 0.21%   |
| 6.0.2    | 1         | 0.21%   |
| 6.0.0    | 1         | 0.21%   |
| 5.19.10  | 1         | 0.21%   |
| 5.15.78  | 1         | 0.21%   |
| 5.15.70  | 1         | 0.21%   |
| 5.15.108 | 1         | 0.21%   |
| 5.15.0   | 1         | 0.21%   |
| 4.19.0   | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 434       | 90.42%  |
| 6.1     | 23        | 4.79%   |
| 5.18    | 6         | 1.25%   |
| 5.19    | 4         | 0.83%   |
| 5.16    | 4         | 0.83%   |
| 5.15    | 3         | 0.63%   |
| 6.0     | 2         | 0.42%   |
| 6.7     | 1         | 0.21%   |
| 6.5     | 1         | 0.21%   |
| 6.4     | 1         | 0.21%   |
| 4.19    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 451       | 95.96%  |
| i686   | 19        | 4.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 409       | 85.92%  |
| Cinnamon   | 50        | 10.5%   |
| MATE       | 7         | 1.47%   |
| XFCE       | 2         | 0.42%   |
| Unknown    | 2         | 0.42%   |
| LXDE       | 1         | 0.21%   |
| KDE5       | 1         | 0.21%   |
| KDE        | 1         | 0.21%   |
| i3         | 1         | 0.21%   |
| GNOME      | 1         | 0.21%   |
| awesome    | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 470       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 276       | 58.35%  |
| LightDM | 193       | 40.8%   |
| SDDM    | 2         | 0.42%   |
| GDM     | 2         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 164       | 34.75%  |
| de_DE | 64        | 13.56%  |
| ru_RU | 39        | 8.26%   |
| pt_BR | 33        | 6.99%   |
| en_GB | 28        | 5.93%   |
| it_IT | 21        | 4.45%   |
| fr_FR | 19        | 4.03%   |
| pl_PL | 13        | 2.75%   |
| es_ES | 10        | 2.12%   |
| en_CA | 5         | 1.06%   |
| es_MX | 4         | 0.85%   |
| en_AU | 4         | 0.85%   |
| tr_TR | 3         | 0.64%   |
| sv_SE | 3         | 0.64%   |
| ko_KR | 3         | 0.64%   |
| fr_CA | 3         | 0.64%   |
| es_BO | 3         | 0.64%   |
| en_NZ | 3         | 0.64%   |
| el_GR | 3         | 0.64%   |
| de_AT | 3         | 0.64%   |
| cs_CZ | 3         | 0.64%   |
| sk_SK | 2         | 0.42%   |
| ru_UA | 2         | 0.42%   |
| pt_PT | 2         | 0.42%   |
| hu_HU | 2         | 0.42%   |
| fr_BE | 2         | 0.42%   |
| es_EC | 2         | 0.42%   |
| es_CL | 2         | 0.42%   |
| es_AR | 2         | 0.42%   |
| en_IE | 2         | 0.42%   |
| de_CH | 2         | 0.42%   |
| da_DK | 2         | 0.42%   |
| zh_CN | 1         | 0.21%   |
| sl_SI | 1         | 0.21%   |
| nn_NO | 1         | 0.21%   |
| nl_NL | 1         | 0.21%   |
| nl_AW | 1         | 0.21%   |
| ja_JP | 1         | 0.21%   |
| it_CH | 1         | 0.21%   |
| fi_FI | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 286       | 60.72%  |
| BIOS | 185       | 39.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 431       | 91.51%  |
| Overlay | 15        | 3.18%   |
| Btrfs   | 11        | 2.34%   |
| Tmpfs   | 10        | 2.12%   |
| Xfs     | 3         | 0.64%   |
| Zfs     | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 275       | 58.14%  |
| GPT     | 143       | 30.23%  |
| MBR     | 55        | 11.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 430       | 91.1%   |
| Yes       | 42        | 8.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 407       | 86.23%  |
| Yes       | 65        | 13.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 73        | 15.53%  |
| Lenovo              | 70        | 14.89%  |
| Dell                | 60        | 12.77%  |
| ASUSTek Computer    | 49        | 10.43%  |
| Acer                | 35        | 7.45%   |
| Gigabyte Technology | 25        | 5.32%   |
| MSI                 | 21        | 4.47%   |
| Apple               | 16        | 3.4%    |
| Toshiba             | 11        | 2.34%   |
| ASRock              | 11        | 2.34%   |
| Intel               | 9         | 1.91%   |
| Samsung Electronics | 6         | 1.28%   |
| Medion              | 5         | 1.06%   |
| Fujitsu             | 5         | 1.06%   |
| AZW                 | 5         | 1.06%   |
| Google              | 4         | 0.85%   |
| Unknown             | 4         | 0.85%   |
| Sony                | 3         | 0.64%   |
| Pegatron            | 3         | 0.64%   |
| eMachines           | 3         | 0.64%   |
| Alienware           | 3         | 0.64%   |
| Star Labs           | 2         | 0.43%   |
| Packard Bell        | 2         | 0.43%   |
| Multilaser          | 2         | 0.43%   |
| Microsoft           | 2         | 0.43%   |
| GPU Company         | 2         | 0.43%   |
| Gateway             | 2         | 0.43%   |
| Fujitsu Siemens     | 2         | 0.43%   |
| Compaq              | 2         | 0.43%   |
| Wortmann AG         | 1         | 0.21%   |
| TUXEDO              | 1         | 0.21%   |
| Timi                | 1         | 0.21%   |
| Teclast             | 1         | 0.21%   |
| Supermicro          | 1         | 0.21%   |
| STONE COMPUTERS     | 1         | 0.21%   |
| SiYW                | 1         | 0.21%   |
| Sapphire            | 1         | 0.21%   |
| Prestigio           | 1         | 0.21%   |
| Positivo            | 1         | 0.21%   |
| PLEXHD              | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 6         | 1.28%   |
| HP 250 G8 Notebook PC          | 3         | 0.64%   |
| Star Labs StarBook             | 2         | 0.43%   |
| MSI MS-7C95                    | 2         | 0.43%   |
| MSI MS-7B79                    | 2         | 0.43%   |
| MSI MS-7A38                    | 2         | 0.43%   |
| Lenovo IdeaPad 3 15ITL6 82H8   | 2         | 0.43%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 2         | 0.43%   |
| Lenovo G500 20236              | 2         | 0.43%   |
| Intel B75                      | 2         | 0.43%   |
| HP ProDesk 400 G5 Desktop Mini | 2         | 0.43%   |
| HP ProBook 650 G2              | 2         | 0.43%   |
| HP Pavilion Notebook           | 2         | 0.43%   |
| HP Pavilion dv6                | 2         | 0.43%   |
| HP Notebook                    | 2         | 0.43%   |
| HP Laptop 15z-ef2xxx           | 2         | 0.43%   |
| HP Laptop 15-dw3xxx            | 2         | 0.43%   |
| HP Laptop 14-dk1xxx            | 2         | 0.43%   |
| HP 250 G7 Notebook PC          | 2         | 0.43%   |
| Gigabyte B450 AORUS M          | 2         | 0.43%   |
| Dell XPS 13 9360               | 2         | 0.43%   |
| Dell Latitude E6400            | 2         | 0.43%   |
| Dell Latitude E5540            | 2         | 0.43%   |
| Compaq 420                     | 2         | 0.43%   |
| AZW MINI S                     | 2         | 0.43%   |
| ASUS ROG STRIX B450-F GAMING   | 2         | 0.43%   |
| ASUS PRIME B350M-A             | 2         | 0.43%   |
| ASUS PRIME A320M-K             | 2         | 0.43%   |
| Apple MacBookPro9,2            | 2         | 0.43%   |
| Apple MacBookPro11,1           | 2         | 0.43%   |
| Apple iMac7,1                  | 2         | 0.43%   |
| Acer Aspire E1-570G            | 2         | 0.43%   |
| Acer Aspire 7745G              | 2         | 0.43%   |
| Acer Aspire 5930               | 2         | 0.43%   |
| Wortmann AG TERRA_MOBILE_1713A | 1         | 0.21%   |
| TUXEDO N8xxEZ                  | 1         | 0.21%   |
| Toshiba Satellite Pro A50-C    | 1         | 0.21%   |
| Toshiba Satellite P505         | 1         | 0.21%   |
| Toshiba Satellite M55          | 1         | 0.21%   |
| Toshiba Satellite L855D        | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 31        | 6.6%    |
| Acer Aspire        | 28        | 5.96%   |
| Dell Latitude      | 15        | 3.19%   |
| Lenovo IdeaPad     | 13        | 2.77%   |
| HP Laptop          | 13        | 2.77%   |
| HP Pavilion        | 12        | 2.55%   |
| Dell Inspiron      | 11        | 2.34%   |
| Toshiba Satellite  | 9         | 1.91%   |
| Dell Precision     | 9         | 1.91%   |
| ASUS PRIME         | 8         | 1.7%    |
| HP EliteBook       | 7         | 1.49%   |
| Dell OptiPlex      | 7         | 1.49%   |
| ASUS ROG           | 7         | 1.49%   |
| Dell XPS           | 6         | 1.28%   |
| ASUS VivoBook      | 6         | 1.28%   |
| Unknown            | 6         | 1.28%   |
| HP ProBook         | 5         | 1.06%   |
| HP 250             | 5         | 1.06%   |
| Dell Vostro        | 5         | 1.06%   |
| HP Compaq          | 4         | 0.85%   |
| Lenovo IdeaPadFlex | 3         | 0.64%   |
| HP ZBook           | 3         | 0.64%   |
| HP ENVY            | 3         | 0.64%   |
| Gigabyte B450M     | 3         | 0.64%   |
| Gigabyte B450      | 3         | 0.64%   |
| Toshiba PORTEGE    | 2         | 0.43%   |
| Star Labs StarBook | 2         | 0.43%   |
| MSI MS-7C95        | 2         | 0.43%   |
| MSI MS-7B79        | 2         | 0.43%   |
| MSI MS-7A38        | 2         | 0.43%   |
| Microsoft Surface  | 2         | 0.43%   |
| Lenovo Yoga        | 2         | 0.43%   |
| Lenovo ThinkCentre | 2         | 0.43%   |
| Lenovo ThinkBook   | 2         | 0.43%   |
| Lenovo Legion      | 2         | 0.43%   |
| Lenovo G500        | 2         | 0.43%   |
| Intel DQ77MK       | 2         | 0.43%   |
| Intel B75          | 2         | 0.43%   |
| HP ProDesk         | 2         | 0.43%   |
| HP Notebook        | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 43        | 9.15%   |
| 2018 | 43        | 9.15%   |
| 2012 | 41        | 8.72%   |
| 2020 | 39        | 8.3%    |
| 2013 | 35        | 7.45%   |
| 2017 | 33        | 7.02%   |
| 2016 | 33        | 7.02%   |
| 2019 | 31        | 6.6%    |
| 2010 | 27        | 5.74%   |
| 2011 | 24        | 5.11%   |
| 2022 | 22        | 4.68%   |
| 2009 | 20        | 4.26%   |
| 2008 | 20        | 4.26%   |
| 2015 | 17        | 3.62%   |
| 2014 | 15        | 3.19%   |
| 2007 | 13        | 2.77%   |
| 2006 | 10        | 2.13%   |
| 2023 | 4         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 285       | 60.64%  |
| Desktop     | 155       | 32.98%  |
| Convertible | 10        | 2.13%   |
| Tablet      | 7         | 1.49%   |
| All in one  | 7         | 1.49%   |
| Mini pc     | 4         | 0.85%   |
| Server      | 2         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 435       | 91.97%  |
| Enabled  | 38        | 8.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 463       | 98.51%  |
| Yes  | 7         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 121       | 25.42%  |
| 3.01-4.0        | 91        | 19.12%  |
| 16.01-24.0      | 83        | 17.44%  |
| 8.01-16.0       | 81        | 17.02%  |
| 32.01-64.0      | 43        | 9.03%   |
| 1.01-2.0        | 24        | 5.04%   |
| 2.01-3.0        | 15        | 3.15%   |
| 64.01-256.0     | 8         | 1.68%   |
| 24.01-32.0      | 6         | 1.26%   |
| 0.51-1.0        | 3         | 0.63%   |
| More than 256.0 | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 195       | 38.39%  |
| 2.01-3.0   | 161       | 31.69%  |
| 4.01-8.0   | 55        | 10.83%  |
| 3.01-4.0   | 53        | 10.43%  |
| 0.51-1.0   | 27        | 5.31%   |
| 8.01-16.0  | 11        | 2.17%   |
| 32.01-64.0 | 2         | 0.39%   |
| 24.01-32.0 | 2         | 0.39%   |
| 16.01-24.0 | 2         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 305       | 63.28%  |
| 2      | 107       | 22.2%   |
| 3      | 32        | 6.64%   |
| 4      | 19        | 3.94%   |
| 5      | 9         | 1.87%   |
| 6      | 5         | 1.04%   |
| 0      | 3         | 0.62%   |
| 11     | 1         | 0.21%   |
| 7      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 304       | 64.41%  |
| Yes       | 168       | 35.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 395       | 84.04%  |
| No        | 75        | 15.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 384       | 81.18%  |
| No        | 89        | 18.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 58.47%  |
| No        | 196       | 41.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 96        | 20.25%  |
| Germany      | 73        | 15.4%   |
| Russia       | 41        | 8.65%   |
| Brazil       | 34        | 7.17%   |
| Italy        | 29        | 6.12%   |
| France       | 22        | 4.64%   |
| UK           | 18        | 3.8%    |
| Poland       | 16        | 3.38%   |
| Spain        | 12        | 2.53%   |
| Canada       | 12        | 2.53%   |
| Mexico       | 7         | 1.48%   |
| Australia    | 7         | 1.48%   |
| Sweden       | 6         | 1.27%   |
| Turkey       | 4         | 0.84%   |
| Portugal     | 4         | 0.84%   |
| Netherlands  | 4         | 0.84%   |
| Chile        | 4         | 0.84%   |
| Bolivia      | 4         | 0.84%   |
| Belgium      | 4         | 0.84%   |
| Belarus      | 4         | 0.84%   |
| South Korea  | 3         | 0.63%   |
| New Zealand  | 3         | 0.63%   |
| Kazakhstan   | 3         | 0.63%   |
| Indonesia    | 3         | 0.63%   |
| Hungary      | 3         | 0.63%   |
| Greece       | 3         | 0.63%   |
| Ecuador      | 3         | 0.63%   |
| Austria      | 3         | 0.63%   |
| Vietnam      | 2         | 0.42%   |
| Venezuela    | 2         | 0.42%   |
| Ukraine      | 2         | 0.42%   |
| South Africa | 2         | 0.42%   |
| Slovenia     | 2         | 0.42%   |
| Slovakia     | 2         | 0.42%   |
| Romania      | 2         | 0.42%   |
| Peru         | 2         | 0.42%   |
| Paraguay     | 2         | 0.42%   |
| Lithuania    | 2         | 0.42%   |
| Japan        | 2         | 0.42%   |
| India        | 2         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 11        | 2.22%   |
| Moscow            | 9         | 1.81%   |
| Rome              | 5         | 1.01%   |
| Munich            | 5         | 1.01%   |
| St Petersburg     | 4         | 0.81%   |
| Rio de Janeiro    | 4         | 0.81%   |
| New York          | 4         | 0.81%   |
| Madrid            | 4         | 0.81%   |
| Krakow            | 4         | 0.81%   |
| Delligsen         | 4         | 0.81%   |
| Sydney            | 3         | 0.6%    |
| Oruro             | 3         | 0.6%    |
| Montreal          | 3         | 0.6%    |
| Milan             | 3         | 0.6%    |
| Miami             | 3         | 0.6%    |
| Lisbon            | 3         | 0.6%    |
| Frankfurt am Main | 3         | 0.6%    |
| Belém            | 3         | 0.6%    |
| Auckland          | 3         | 0.6%    |
| Wroclaw           | 2         | 0.4%    |
| Vancouver         | 2         | 0.4%    |
| Trieste           | 2         | 0.4%    |
| Toulon            | 2         | 0.4%    |
| Toronto           | 2         | 0.4%    |
| Santiago          | 2         | 0.4%    |
| San Jose          | 2         | 0.4%    |
| Potsdam           | 2         | 0.4%    |
| Porto Alegre      | 2         | 0.4%    |
| Parma             | 2         | 0.4%    |
| Paris             | 2         | 0.4%    |
| Nitra             | 2         | 0.4%    |
| Neasden           | 2         | 0.4%    |
| Natal             | 2         | 0.4%    |
| Nashville         | 2         | 0.4%    |
| Mogi das Cruzes   | 2         | 0.4%    |
| Melbourne         | 2         | 0.4%    |
| London            | 2         | 0.4%    |
| Ljubljana         | 2         | 0.4%    |
| Lima              | 2         | 0.4%    |
| Lamspringe        | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 95        | 153    | 14.24%  |
| Samsung Electronics       | 92        | 138    | 13.79%  |
| Seagate                   | 78        | 110    | 11.69%  |
| Kingston                  | 38        | 55     | 5.7%    |
| Unknown                   | 36        | 53     | 5.4%    |
| Toshiba                   | 34        | 39     | 5.1%    |
| SanDisk                   | 34        | 50     | 5.1%    |
| Crucial                   | 23        | 26     | 3.45%   |
| Hitachi                   | 21        | 28     | 3.15%   |
| SK hynix                  | 18        | 19     | 2.7%    |
| Intel                     | 14        | 15     | 2.1%    |
| A-DATA Technology         | 13        | 14     | 1.95%   |
| China                     | 12        | 14     | 1.8%    |
| Micron Technology         | 9         | 10     | 1.35%   |
| Apple                     | 8         | 13     | 1.2%    |
| HGST                      | 7         | 12     | 1.05%   |
| PNY                       | 6         | 8      | 0.9%    |
| GOODRAM                   | 6         | 6      | 0.9%    |
| Unknown                   | 6         | 10     | 0.9%    |
| SPCC                      | 5         | 6      | 0.75%   |
| Silicon Motion            | 5         | 6      | 0.75%   |
| Phison                    | 5         | 10     | 0.75%   |
| Patriot                   | 5         | 6      | 0.75%   |
| Transcend                 | 4         | 6      | 0.6%    |
| KingSpec                  | 4         | 4      | 0.6%    |
| Intenso                   | 4         | 4      | 0.6%    |
| Fujitsu                   | 4         | 4      | 0.6%    |
| ADATA Technology          | 4         | 7      | 0.6%    |
| Team                      | 3         | 3      | 0.45%   |
| Hewlett-Packard           | 3         | 3      | 0.45%   |
| Emtec                     | 3         | 3      | 0.45%   |
| ASMT                      | 3         | 4      | 0.45%   |
| WALRAM                    | 2         | 2      | 0.3%    |
| Star Drive                | 2         | 3      | 0.3%    |
| SABRENT                   | 2         | 3      | 0.3%    |
| Phison Electronics        | 2         | 2      | 0.3%    |
| OCZ                       | 2         | 2      | 0.3%    |
| Netac                     | 2         | 2      | 0.3%    |
| Micron/Crucial Technology | 2         | 4      | 0.3%    |
| LITEONIT                  | 2         | 3      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 1.08%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 1.08%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 7         | 0.95%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 0.95%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.95%   |
| Unknown SD/MMC/MS PRO 128GB                         | 6         | 0.81%   |
| Unknown MMC Card  64GB                              | 6         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB                     | 6         | 0.81%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.81%   |
| Unknown                                             | 6         | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.54%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.54%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 4         | 0.54%   |
| Samsung SSD 980 PRO 1TB                             | 4         | 0.54%   |
| Samsung SSD 970 EVO 500GB                           | 4         | 0.54%   |
| Crucial CT1000BX500SSD1 1TB                         | 4         | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 0.41%   |
| Unknown MMC Card  128GB                             | 3         | 0.41%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.41%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 3         | 0.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB   | 3         | 0.41%   |
| Seagate ST2000LX001-1RG174 2TB                      | 3         | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.41%   |
| Samsung SSD 980 1TB                                 | 3         | 0.41%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 0.41%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.41%   |
| Intenso External USB 3.0 1TB                        | 3         | 0.41%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.27%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 2         | 0.27%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 2         | 0.27%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 2         | 0.27%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 2         | 0.27%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 2         | 0.27%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 2         | 0.27%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 2         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 109    | 32.64%  |
| WDC                 | 77        | 125    | 32.22%  |
| Toshiba             | 25        | 28     | 10.46%  |
| Hitachi             | 21        | 28     | 8.79%   |
| Samsung Electronics | 11        | 17     | 4.6%    |
| HGST                | 7         | 12     | 2.93%   |
| Unknown             | 6         | 6      | 2.51%   |
| Fujitsu             | 4         | 4      | 1.67%   |
| Intenso             | 3         | 3      | 1.26%   |
| SABRENT             | 2         | 3      | 0.84%   |
| ASMT                | 2         | 3      | 0.84%   |
| Initio              | 1         | 1      | 0.42%   |
| ASMedia             | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 66     | 19.44%  |
| Kingston            | 31        | 47     | 12.3%   |
| Crucial             | 22        | 25     | 8.73%   |
| SanDisk             | 16        | 22     | 6.35%   |
| A-DATA Technology   | 13        | 14     | 5.16%   |
| WDC                 | 11        | 16     | 4.37%   |
| China               | 11        | 13     | 4.37%   |
| PNY                 | 6         | 8      | 2.38%   |
| GOODRAM             | 6         | 6      | 2.38%   |
| Apple               | 6         | 6      | 2.38%   |
| Patriot             | 5         | 6      | 1.98%   |
| Intel               | 5         | 5      | 1.98%   |
| Transcend           | 4         | 6      | 1.59%   |
| SPCC                | 4         | 5      | 1.59%   |
| KingSpec            | 4         | 4      | 1.59%   |
| Unknown             | 4         | 8      | 1.59%   |
| Toshiba             | 3         | 3      | 1.19%   |
| Team                | 3         | 3      | 1.19%   |
| SK hynix            | 3         | 3      | 1.19%   |
| OCZ                 | 2         | 2      | 0.79%   |
| Netac               | 2         | 2      | 0.79%   |
| Micron Technology   | 2         | 2      | 0.79%   |
| LITEONIT            | 2         | 3      | 0.79%   |
| Hewlett-Packard     | 2         | 2      | 0.79%   |
| Gigabyte Technology | 2         | 4      | 0.79%   |
| Emtec               | 2         | 2      | 0.79%   |
| Apacer              | 2         | 2      | 0.79%   |
| WINTEC              | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 4      | 0.4%    |
| V-GeN               | 1         | 1      | 0.4%    |
| USB30               | 1         | 1      | 0.4%    |
| TakeMS              | 1         | 1      | 0.4%    |
| T-FORCE             | 1         | 1      | 0.4%    |
| SSD PHIS            | 1         | 1      | 0.4%    |
| SD                  | 1         | 1      | 0.4%    |
| SCCTS-603-001T      | 1         | 1      | 0.4%    |
| PNY USB             | 1         | 1      | 0.4%    |
| Phison              | 1         | 6      | 0.4%    |
| ORICO               | 1         | 1      | 0.4%    |
| OCZ-VERTEX          | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 225       | 329    | 36.76%  |
| HDD     | 203       | 341    | 33.17%  |
| NVMe    | 136       | 194    | 22.22%  |
| MMC     | 32        | 47     | 5.23%   |
| Unknown | 16        | 19     | 2.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 353       | 640    | 64.07%  |
| NVMe | 135       | 193    | 24.5%   |
| MMC  | 32        | 47     | 5.81%   |
| SAS  | 31        | 50     | 5.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 267       | 415    | 61.66%  |
| 0.51-1.0   | 109       | 164    | 25.17%  |
| 1.01-2.0   | 31        | 49     | 7.16%   |
| 4.01-10.0  | 9         | 14     | 2.08%   |
| 2.01-3.0   | 8         | 16     | 1.85%   |
| 3.01-4.0   | 7         | 10     | 1.62%   |
| 10.01-20.0 | 2         | 2      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 152       | 31.34%  |
| 251-500        | 118       | 24.33%  |
| 501-1000       | 65        | 13.4%   |
| 1001-2000      | 43        | 8.87%   |
| 51-100         | 32        | 6.6%    |
| More than 3000 | 23        | 4.74%   |
| 1-20           | 22        | 4.54%   |
| 2001-3000      | 15        | 3.09%   |
| 21-50          | 13        | 2.68%   |
| Unknown        | 2         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 193       | 37.99%  |
| 21-50          | 98        | 19.29%  |
| 101-250        | 63        | 12.4%   |
| 51-100         | 61        | 12.01%  |
| 251-500        | 36        | 7.09%   |
| 501-1000       | 26        | 5.12%   |
| 1001-2000      | 14        | 2.76%   |
| More than 3000 | 8         | 1.57%   |
| 2001-3000      | 7         | 1.38%   |
| Unknown        | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 2.56%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.56%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 2.56%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 2.56%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 2.56%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 2.56%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 2.56%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 2.56%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 2.56%   |
| Toshiba MD04ACA400 4TB                | 1         | 1      | 2.56%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 2.56%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 2.56%   |
| Seagate ST98823AS 80GB                | 1         | 2      | 2.56%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 2.56%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.56%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 2.56%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 2.56%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 2.56%   |
| Seagate ST1000DM003-9YN162 1TB        | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 980 500GB     | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 2.56%   |
| Samsung Electronics SSD 870 EVO 2TB   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 2.56%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 2.56%   |
| Samsung Electronics HD153WI 1TB       | 1         | 1      | 2.56%   |
| Phison ES 512GB                       | 1         | 1      | 2.56%   |
| Intenso SSD 256GB                     | 1         | 1      | 2.56%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 2.56%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 2.56%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 2.56%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.56%   |
| Hitachi HTS541080G9AT00 80GB          | 1         | 1      | 2.56%   |
| Hitachi HDS721010KLA330 1TB           | 1         | 1      | 2.56%   |
| Hitachi HDP725050GLA360 500GB         | 1         | 1      | 2.56%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 23.68%  |
| Samsung Electronics | 8         | 9      | 21.05%  |
| WDC                 | 5         | 6      | 13.16%  |
| Hitachi             | 5         | 5      | 13.16%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Intel               | 2         | 2      | 5.26%   |
| WINTEC              | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| Phison              | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 36%     |
| WDC                 | 5         | 6      | 20%     |
| Hitachi             | 5         | 5      | 20%     |
| Toshiba             | 3         | 3      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |
| HGST                | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 63.89%  |
| SSD  | 8         | 8      | 22.22%  |
| NVMe | 5         | 6      | 13.89%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 311       | 598    | 60.98%  |
| Works    | 164       | 291    | 32.16%  |
| Malfunc  | 35        | 41     | 6.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 313       | 54.72%  |
| AMD                            | 95        | 16.61%  |
| Samsung Electronics            | 44        | 7.69%   |
| SanDisk                        | 25        | 4.37%   |
| SK hynix                       | 14        | 2.45%   |
| Phison Electronics             | 10        | 1.75%   |
| Micron Technology              | 7         | 1.22%   |
| Kingston Technology Company    | 7         | 1.22%   |
| ASMedia Technology             | 7         | 1.22%   |
| Toshiba America Info Systems   | 6         | 1.05%   |
| Silicon Motion                 | 6         | 1.05%   |
| Nvidia                         | 5         | 0.87%   |
| Marvell Technology Group       | 5         | 0.87%   |
| JMicron Technology             | 5         | 0.87%   |
| ADATA Technology               | 4         | 0.7%    |
| VIA Technologies               | 3         | 0.52%   |
| Micron/Crucial Technology      | 3         | 0.52%   |
| KIOXIA                         | 3         | 0.52%   |
| Broadcom / LSI                 | 3         | 0.52%   |
| Union Memory (Shenzhen)        | 2         | 0.35%   |
| LSI Logic / Symbios Logic      | 2         | 0.35%   |
| Solid State Storage Technology | 1         | 0.17%   |
| Biwin Storage Technology       | 1         | 0.17%   |
| Apple                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 67        | 10.03%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 27        | 4.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 23        | 3.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 3.29%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 2.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 2.54%   |
| AMD 400 Series Chipset SATA Controller                                           | 17        | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 2.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 16        | 2.4%    |
| Intel Tiger Lake-LP SATA Controller                                              | 13        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 13        | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 1.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 1.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 1.5%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 9         | 1.35%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 7         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 7         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 0.9%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 6         | 0.9%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                     | 6         | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                           | 6         | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                           | 6         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.75%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 349       | 58.07%  |
| NVMe | 136       | 22.63%  |
| IDE  | 62        | 10.32%  |
| RAID | 49        | 8.15%   |
| SAS  | 4         | 0.67%   |
| SCSI | 1         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 355       | 75.53%  |
| AMD          | 114       | 24.26%  |
| CentaurHauls | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 7         | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.06%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 1.06%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.85%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.85%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.85%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3         | 0.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.64%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 3         | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.64%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.64%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.64%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 3         | 0.64%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 2         | 0.42%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz           | 2         | 0.42%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.42%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.42%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 0.42%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 2         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.42%   |
| Intel Pentium CPU G645 @ 2.90GHz              | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 97        | 20.59%  |
| Intel Core i7           | 63        | 13.38%  |
| Intel Core i3           | 36        | 7.64%   |
| Other                   | 33        | 7.01%   |
| AMD Ryzen 5             | 33        | 7.01%   |
| Intel Celeron           | 24        | 5.1%    |
| AMD Ryzen 7             | 24        | 5.1%    |
| Intel Core 2 Duo        | 21        | 4.46%   |
| Intel Atom              | 17        | 3.61%   |
| Intel Xeon              | 16        | 3.4%    |
| Intel Pentium           | 15        | 3.18%   |
| AMD Ryzen 3             | 13        | 2.76%   |
| Intel Pentium Dual-Core | 6         | 1.27%   |
| AMD A4                  | 6         | 1.27%   |
| AMD E1                  | 5         | 1.06%   |
| Intel Core 2 Quad       | 4         | 0.85%   |
| Intel Core 2            | 4         | 0.85%   |
| Intel Pentium Silver    | 3         | 0.64%   |
| Intel Pentium Gold      | 3         | 0.64%   |
| Intel Pentium Dual      | 3         | 0.64%   |
| Intel Genuine           | 3         | 0.64%   |
| Intel Celeron M         | 3         | 0.64%   |
| AMD Ryzen 9             | 3         | 0.64%   |
| AMD FX                  | 3         | 0.64%   |
| AMD Athlon II X2        | 3         | 0.64%   |
| AMD Athlon              | 3         | 0.64%   |
| AMD A8                  | 3         | 0.64%   |
| AMD A10                 | 3         | 0.64%   |
| Intel Pentium M         | 2         | 0.42%   |
| Intel Pentium D         | 2         | 0.42%   |
| AMD Phenom II X6        | 2         | 0.42%   |
| AMD E2                  | 2         | 0.42%   |
| AMD A6                  | 2         | 0.42%   |
| Intel Core m3           | 1         | 0.21%   |
| Intel Core i9           | 1         | 0.21%   |
| Intel Core 2 Extreme    | 1         | 0.21%   |
| CentaurHauls VIA Eden   | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile | 1         | 0.21%   |
| AMD Phenom II X4        | 1         | 0.21%   |
| AMD G                   | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 209       | 44.28%  |
| 4      | 165       | 34.96%  |
| 6      | 39        | 8.26%   |
| 8      | 33        | 6.99%   |
| 1      | 14        | 2.97%   |
| 16     | 5         | 1.06%   |
| 12     | 5         | 1.06%   |
| 10     | 2         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 463       | 98.51%  |
| 2      | 7         | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 301       | 63.77%  |
| 1      | 171       | 36.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 459       | 97.66%  |
| 32-bit         | 11        | 2.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 41        | 8.56%   |
| Unknown    | 27        | 5.64%   |
| 0x206a7    | 25        | 5.22%   |
| 0x806c1    | 22        | 4.59%   |
| 0x1067a    | 20        | 4.18%   |
| 0x306c3    | 18        | 3.76%   |
| 0x08108109 | 18        | 3.76%   |
| 0x406e3    | 15        | 3.13%   |
| 0x40651    | 14        | 2.92%   |
| 0x806ec    | 12        | 2.51%   |
| 0x806e9    | 11        | 2.3%    |
| 0x406c4    | 11        | 2.3%    |
| 0x20655    | 10        | 2.09%   |
| 0x08608103 | 10        | 2.09%   |
| 0x6fd      | 9         | 1.88%   |
| 0x506e3    | 9         | 1.88%   |
| 0x906ea    | 8         | 1.67%   |
| 0x0a50000d | 8         | 1.67%   |
| 0x806ea    | 7         | 1.46%   |
| 0x706a8    | 7         | 1.46%   |
| 0x906c0    | 6         | 1.25%   |
| 0x0800820d | 6         | 1.25%   |
| 0x906e9    | 5         | 1.04%   |
| 0x706e5    | 5         | 1.04%   |
| 0x106e5    | 5         | 1.04%   |
| 0x0a50000c | 5         | 1.04%   |
| 0x08701021 | 5         | 1.04%   |
| 0x906ed    | 4         | 0.84%   |
| 0x6f6      | 4         | 0.84%   |
| 0x30661    | 4         | 0.84%   |
| 0x206d7    | 4         | 0.84%   |
| 0x20652    | 4         | 0.84%   |
| 0x106c2    | 4         | 0.84%   |
| 0x10676    | 4         | 0.84%   |
| 0x06006705 | 4         | 0.84%   |
| 0x06001119 | 4         | 0.84%   |
| 0x010000c8 | 4         | 0.84%   |
| 0xa0671    | 3         | 0.63%   |
| 0x806eb    | 3         | 0.63%   |
| 0x706a1    | 3         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 57        | 12.05%  |
| IvyBridge        | 45        | 9.51%   |
| Haswell          | 33        | 6.98%   |
| SandyBridge      | 30        | 6.34%   |
| Zen+             | 26        | 5.5%    |
| TigerLake        | 24        | 5.07%   |
| Skylake          | 24        | 5.07%   |
| Penryn           | 24        | 5.07%   |
| Unknown          | 21        | 4.44%   |
| Zen 3            | 19        | 4.02%   |
| Westmere         | 18        | 3.81%   |
| Silvermont       | 18        | 3.81%   |
| Core             | 18        | 3.81%   |
| Zen 2            | 10        | 2.11%   |
| Goldmont plus    | 10        | 2.11%   |
| Bonnell          | 10        | 2.11%   |
| Zen              | 9         | 1.9%    |
| Piledriver       | 7         | 1.48%   |
| K10              | 7         | 1.48%   |
| Excavator        | 7         | 1.48%   |
| Tremont          | 6         | 1.27%   |
| P6               | 6         | 1.27%   |
| Nehalem          | 6         | 1.27%   |
| Icelake          | 6         | 1.27%   |
| CometLake        | 5         | 1.06%   |
| Jaguar           | 4         | 0.85%   |
| Broadwell        | 4         | 0.85%   |
| Bobcat           | 4         | 0.85%   |
| Puma             | 3         | 0.63%   |
| NetBurst         | 3         | 0.63%   |
| K10 Llano        | 3         | 0.63%   |
| K8 Hammer        | 2         | 0.42%   |
| Goldmont         | 2         | 0.42%   |
| Bulldozer        | 1         | 0.21%   |
| Alderlake Hybrid | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 274       | 51.02%  |
| Nvidia                     | 142       | 26.44%  |
| AMD                        | 119       | 22.16%  |
| VIA Technologies           | 1         | 0.19%   |
| Matrox Electronics Systems | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 3.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 3.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 2.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 2.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.33%   |
| Intel HD Graphics 620                                                                    | 11        | 1.97%   |
| AMD Lucienne                                                                             | 11        | 1.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.61%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.43%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.25%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 1.08%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.9%    |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 0.72%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.72%   |
| Intel HD Graphics 530                                                                    | 4         | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.72%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.54%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.54%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 218       | 46.09%  |
| 1 x AMD        | 92        | 19.45%  |
| 1 x Nvidia     | 87        | 18.39%  |
| Intel + Nvidia | 45        | 9.51%   |
| 2 x AMD        | 10        | 2.11%   |
| Intel + AMD    | 9         | 1.9%    |
| AMD + Nvidia   | 8         | 1.69%   |
| Other          | 1         | 0.21%   |
| 2 x Nvidia     | 1         | 0.21%   |
| 1 x VIA        | 1         | 0.21%   |
| 1 x Matrox     | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 389       | 81.89%  |
| Proprietary | 59        | 12.42%  |
| Unknown     | 27        | 5.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 54.7%   |
| 0.01-0.5   | 73        | 15.24%  |
| 1.01-2.0   | 68        | 14.2%   |
| 0.51-1.0   | 30        | 6.26%   |
| 3.01-4.0   | 23        | 4.8%    |
| 7.01-8.0   | 8         | 1.67%   |
| 5.01-6.0   | 8         | 1.67%   |
| 2.01-3.0   | 3         | 0.63%   |
| 8.01-16.0  | 3         | 0.63%   |
| 16.01-24.0 | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 59        | 12.55%  |
| Samsung Electronics     | 55        | 11.7%   |
| LG Display              | 52        | 11.06%  |
| Chimei Innolux          | 44        | 9.36%   |
| BOE                     | 40        | 8.51%   |
| Goldstar                | 20        | 4.26%   |
| Acer                    | 17        | 3.62%   |
| Apple                   | 15        | 3.19%   |
| Dell                    | 14        | 2.98%   |
| Philips                 | 11        | 2.34%   |
| Hewlett-Packard         | 11        | 2.34%   |
| Chi Mei Optoelectronics | 10        | 2.13%   |
| BenQ                    | 10        | 2.13%   |
| Sharp                   | 8         | 1.7%    |
| InfoVision              | 8         | 1.7%    |
| PANDA                   | 6         | 1.28%   |
| Lenovo                  | 6         | 1.28%   |
| AOC                     | 6         | 1.28%   |
| Unknown                 | 5         | 1.06%   |
| Sony                    | 5         | 1.06%   |
| LG Philips              | 5         | 1.06%   |
| Ancor Communications    | 5         | 1.06%   |
| ViewSonic               | 4         | 0.85%   |
| HannStar                | 4         | 0.85%   |
| SLD                     | 3         | 0.64%   |
| Quanta Display          | 3         | 0.64%   |
| Sceptre Tech            | 2         | 0.43%   |
| Panasonic               | 2         | 0.43%   |
| MStar                   | 2         | 0.43%   |
| Insignia                | 2         | 0.43%   |
| Iiyama                  | 2         | 0.43%   |
| HUAWEI                  | 2         | 0.43%   |
| HPN                     | 2         | 0.43%   |
| Fujitsu Siemens         | 2         | 0.43%   |
| DENON                   | 2         | 0.43%   |
| ASUSTek Computer        | 2         | 0.43%   |
| ___                     | 1         | 0.21%   |
| Vestel Elektronik       | 1         | 0.21%   |
| Unknown (XXX)           | 1         | 0.21%   |
| TR_                     | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.83%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 3         | 0.62%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.62%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.41%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 2         | 0.41%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 2         | 0.41%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.41%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch              | 2         | 0.41%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 2         | 0.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.41%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.41%   |
| Fujitsu Siemens P27-9 TS QHD FUS08D5 2560x1440 597x336mm 27.0-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch         | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 309x174mm 14.0-inch          | 2         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 2         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.41%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                     | 2         | 0.41%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.41%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.41%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 195       | 42.76%  |
| 1366x768 (WXGA)    | 103       | 22.59%  |
| 1600x900 (HD+)     | 20        | 4.39%   |
| 3840x2160 (4K)     | 19        | 4.17%   |
| 1440x900 (WXGA+)   | 15        | 3.29%   |
| 1280x800 (WXGA)    | 14        | 3.07%   |
| 1920x1200 (WUXGA)  | 12        | 2.63%   |
| 1680x1050 (WSXGA+) | 12        | 2.63%   |
| 2560x1440 (QHD)    | 10        | 2.19%   |
| 1280x1024 (SXGA)   | 8         | 1.75%   |
| 2560x1080          | 7         | 1.54%   |
| 1024x600           | 7         | 1.54%   |
| 3440x1440          | 4         | 0.88%   |
| 1360x768           | 4         | 0.88%   |
| Unknown            | 4         | 0.88%   |
| 3840x1080          | 2         | 0.44%   |
| 2880x1800          | 2         | 0.44%   |
| 2560x1600          | 2         | 0.44%   |
| 1280x768           | 2         | 0.44%   |
| 1024x768 (XGA)     | 2         | 0.44%   |
| 4480x1440          | 1         | 0.22%   |
| 3840x2400          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 3040x1050          | 1         | 0.22%   |
| 2880x1920          | 1         | 0.22%   |
| 2256x1504          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 1920x1280          | 1         | 0.22%   |
| 1680x945           | 1         | 0.22%   |
| 1600x1200          | 1         | 0.22%   |
| 1280x720 (HD)      | 1         | 0.22%   |
| 1024x576           | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 142       | 30.02%  |
| 13      | 57        | 12.05%  |
| Unknown | 33        | 6.98%   |
| 24      | 31        | 6.55%   |
| 14      | 30        | 6.34%   |
| 23      | 23        | 4.86%   |
| 17      | 21        | 4.44%   |
| 27      | 19        | 4.02%   |
| 21      | 17        | 3.59%   |
| 31      | 12        | 2.54%   |
| 12      | 10        | 2.11%   |
| 10      | 9         | 1.9%    |
| 34      | 8         | 1.69%   |
| 20      | 8         | 1.69%   |
| 19      | 8         | 1.69%   |
| 18      | 8         | 1.69%   |
| 11      | 8         | 1.69%   |
| 22      | 6         | 1.27%   |
| 72      | 5         | 1.06%   |
| 52      | 2         | 0.42%   |
| 40      | 2         | 0.42%   |
| 32      | 2         | 0.42%   |
| 28      | 2         | 0.42%   |
| 26      | 2         | 0.42%   |
| 25      | 2         | 0.42%   |
| 84      | 1         | 0.21%   |
| 64      | 1         | 0.21%   |
| 54      | 1         | 0.21%   |
| 33      | 1         | 0.21%   |
| 16      | 1         | 0.21%   |
| 8       | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 202       | 43.63%  |
| 501-600     | 71        | 15.33%  |
| 201-300     | 53        | 11.45%  |
| 401-500     | 42        | 9.07%   |
| Unknown     | 33        | 7.13%   |
| 351-400     | 22        | 4.75%   |
| 601-700     | 17        | 3.67%   |
| 701-800     | 11        | 2.38%   |
| 1501-2000   | 6         | 1.3%    |
| 1001-1500   | 3         | 0.65%   |
| 801-900     | 2         | 0.43%   |
| 101-200     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 325       | 74.2%   |
| 16/10   | 58        | 13.24%  |
| Unknown | 29        | 6.62%   |
| 21/9    | 11        | 2.51%   |
| 5/4     | 6         | 1.37%   |
| 4/3     | 5         | 1.14%   |
| 3/2     | 4         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 141       | 30%     |
| 81-90          | 65        | 13.83%  |
| 201-250        | 62        | 13.19%  |
| Unknown        | 33        | 7.02%   |
| 351-500        | 24        | 5.11%   |
| 71-80          | 22        | 4.68%   |
| 301-350        | 21        | 4.47%   |
| 151-200        | 19        | 4.04%   |
| 251-300        | 14        | 2.98%   |
| 121-130        | 12        | 2.55%   |
| 141-150        | 11        | 2.34%   |
| 61-70          | 10        | 2.13%   |
| More than 1000 | 9         | 1.91%   |
| 41-50          | 9         | 1.91%   |
| 51-60          | 8         | 1.7%    |
| 131-140        | 5         | 1.06%   |
| 501-1000       | 2         | 0.43%   |
| 1-40           | 1         | 0.21%   |
| 111-120        | 1         | 0.21%   |
| 91-100         | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 136       | 29.69%  |
| 101-120       | 129       | 28.17%  |
| 121-160       | 127       | 27.73%  |
| Unknown       | 33        | 7.21%   |
| 161-240       | 21        | 4.59%   |
| 1-50          | 7         | 1.53%   |
| More than 240 | 5         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 397       | 82.88%  |
| 2     | 55        | 11.48%  |
| 0     | 24        | 5.01%   |
| 3     | 3         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 249       | 35.67%  |
| Intel                             | 213       | 30.52%  |
| Qualcomm Atheros                  | 79        | 11.32%  |
| Broadcom                          | 44        | 6.3%    |
| TP-Link                           | 13        | 1.86%   |
| Marvell Technology Group          | 13        | 1.86%   |
| Broadcom Limited                  | 12        | 1.72%   |
| MediaTek                          | 9         | 1.29%   |
| Ralink Technology                 | 7         | 1%      |
| Ralink                            | 5         | 0.72%   |
| Nvidia                            | 5         | 0.72%   |
| Xiaomi                            | 3         | 0.43%   |
| Samsung Electronics               | 3         | 0.43%   |
| NetGear                           | 3         | 0.43%   |
| Google                            | 3         | 0.43%   |
| VIA Technologies                  | 2         | 0.29%   |
| Tenda                             | 2         | 0.29%   |
| Spreadtrum Communications         | 2         | 0.29%   |
| Lenovo                            | 2         | 0.29%   |
| Huawei Technologies               | 2         | 0.29%   |
| Ericsson Business Mobile Networks | 2         | 0.29%   |
| Edimax Technology                 | 2         | 0.29%   |
| Dell                              | 2         | 0.29%   |
| Belkin Components                 | 2         | 0.29%   |
| ASUSTek Computer                  | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.14%   |
| Sierra Wireless                   | 1         | 0.14%   |
| Qualcomm Atheros Communications   | 1         | 0.14%   |
| Qualcomm                          | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.14%   |
| Motorola PCS                      | 1         | 0.14%   |
| Microsoft                         | 1         | 0.14%   |
| Microchip Technology              | 1         | 0.14%   |
| Mercucys                          | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| IMC Networks                      | 1         | 0.14%   |
| HTC (High Tech Computer)          | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Fibocom                           | 1         | 0.14%   |
| Davicom Semiconductor             | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 157       | 18.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 22        | 2.58%   |
| Intel Wireless 3165                                                    | 15        | 1.76%   |
| Intel Wireless 8265 / 8275                                             | 14        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                    | 14        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 1.52%   |
| Intel Wireless 8260                                                    | 13        | 1.52%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 10        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.05%   |
| Intel Wireless 7265                                                    | 9         | 1.05%   |
| Intel Wireless 7260                                                    | 9         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 0.94%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 0.94%   |
| Intel Ethernet Connection I219-V                                       | 8         | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.82%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 0.7%    |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.59%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 4         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 163       | 39.76%  |
| Realtek Semiconductor           | 96        | 23.41%  |
| Qualcomm Atheros                | 53        | 12.93%  |
| Broadcom                        | 35        | 8.54%   |
| TP-Link                         | 12        | 2.93%   |
| Broadcom Limited                | 9         | 2.2%    |
| Ralink Technology               | 7         | 1.71%   |
| MediaTek                        | 6         | 1.46%   |
| Ralink                          | 5         | 1.22%   |
| NetGear                         | 3         | 0.73%   |
| Marvell Technology Group        | 3         | 0.73%   |
| Tenda                           | 2         | 0.49%   |
| Edimax Technology               | 2         | 0.49%   |
| Belkin Components               | 2         | 0.49%   |
| ASUSTek Computer                | 2         | 0.49%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.24%   |
| Xiaomi                          | 1         | 0.24%   |
| Sierra Wireless                 | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Microsoft                       | 1         | 0.24%   |
| Mercucys                        | 1         | 0.24%   |
| IMC Networks                    | 1         | 0.24%   |
| Fibocom                         | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |
| AVM                             | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 5.21%   |
| Intel Wireless 3165                                                     | 15        | 3.55%   |
| Intel Wireless 8265 / 8275                                              | 14        | 3.32%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 3.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.08%   |
| Intel Wireless 8260                                                     | 13        | 3.08%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 2.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 10        | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.13%   |
| Intel Wireless 7265                                                     | 9         | 2.13%   |
| Intel Wireless 7260                                                     | 9         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 8         | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.95%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 4         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.95%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.95%   |
| Intel WiFi Link 5100                                                    | 4         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 4         | 0.95%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 0.95%   |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.71%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 213       | 50.71%  |
| Intel                         | 110       | 26.19%  |
| Qualcomm Atheros              | 37        | 8.81%   |
| Broadcom                      | 14        | 3.33%   |
| Marvell Technology Group      | 10        | 2.38%   |
| Nvidia                        | 5         | 1.19%   |
| Samsung Electronics           | 3         | 0.71%   |
| MediaTek                      | 3         | 0.71%   |
| Google                        | 3         | 0.71%   |
| Broadcom Limited              | 3         | 0.71%   |
| Xiaomi                        | 2         | 0.48%   |
| VIA Technologies              | 2         | 0.48%   |
| Spreadtrum Communications     | 2         | 0.48%   |
| Huawei Technologies           | 2         | 0.48%   |
| TP-Link                       | 1         | 0.24%   |
| Qualcomm                      | 1         | 0.24%   |
| OnePlus Technology (Shenzhen) | 1         | 0.24%   |
| Motorola PCS                  | 1         | 0.24%   |
| Microchip Technology          | 1         | 0.24%   |
| Lenovo                        | 1         | 0.24%   |
| JMicron Technology            | 1         | 0.24%   |
| HTC (High Tech Computer)      | 1         | 0.24%   |
| Hewlett-Packard               | 1         | 0.24%   |
| Davicom Semiconductor         | 1         | 0.24%   |
| ADMtek                        | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 157       | 36.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 7.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 5.85%   |
| Intel Ethernet Connection I219-V                                       | 8         | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 1.64%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 1.41%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.41%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 1.17%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 4         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.94%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 4         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.7%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 3         | 0.7%    |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.7%    |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.7%    |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.47%   |
| Spreadtrum Unisoc Phone                                                | 2         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.47%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.47%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.47%   |
| Nvidia MCP77 Ethernet                                                  | 2         | 0.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.47%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 393       | 50.26%  |
| WiFi     | 384       | 49.1%   |
| Modem    | 5         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 57.23%  |
| Ethernet | 210       | 42.77%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 265       | 56.26%  |
| 1     | 187       | 39.7%   |
| 0     | 13        | 2.76%   |
| 3     | 6         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 328       | 68.62%  |
| Yes  | 150       | 31.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 43.88%  |
| Realtek Semiconductor           | 43        | 15.47%  |
| Cambridge Silicon Radio         | 17        | 6.12%   |
| Broadcom                        | 16        | 5.76%   |
| Qualcomm Atheros Communications | 14        | 5.04%   |
| Lite-On Technology              | 14        | 5.04%   |
| Apple                           | 14        | 5.04%   |
| Foxconn / Hon Hai               | 12        | 4.32%   |
| Dell                            | 6         | 2.16%   |
| IMC Networks                    | 4         | 1.44%   |
| Hewlett-Packard                 | 4         | 1.44%   |
| MediaTek                        | 2         | 0.72%   |
| Marvell Semiconductor           | 2         | 0.72%   |
| Foxconn International           | 2         | 0.72%   |
| SiW                             | 1         | 0.36%   |
| Ralink                          | 1         | 0.36%   |
| Dynex                           | 1         | 0.36%   |
| Chicony Electronics             | 1         | 0.36%   |
| Askey Computer                  | 1         | 0.36%   |
| Unknown                         | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 53        | 19%     |
| Realtek Bluetooth Radio                             | 26        | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 6.81%   |
| Intel AX201 Bluetooth                               | 19        | 6.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17        | 6.09%   |
| Intel AX200 Bluetooth                               | 13        | 4.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 3.58%   |
| Intel AX210 Bluetooth                               | 7         | 2.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.79%   |
| Lite-On Bluetooth Device                            | 4         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.43%   |
| Apple Bluetooth Host Controller                     | 4         | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.08%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 1.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 1.08%   |
| Apple Bluetooth HCI                                 | 3         | 1.08%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.72%   |
| MediaTek Wireless_Device                            | 2         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.72%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.72%   |
| Foxconn / Hon Hai Acer Module                       | 2         | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.72%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.72%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.72%   |
| SiW SiW                                             | 1         | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.36%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.36%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 339       | 54.07%  |
| AMD                                  | 132       | 21.05%  |
| Nvidia                               | 109       | 17.38%  |
| C-Media Electronics                  | 11        | 1.75%   |
| Texas Instruments                    | 5         | 0.8%    |
| VIA Technologies                     | 3         | 0.48%   |
| KTMicro                              | 3         | 0.48%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.32%   |
| Realtek Semiconductor                | 2         | 0.32%   |
| Plantronics                          | 2         | 0.32%   |
| Logitech                             | 2         | 0.32%   |
| JMTek                                | 2         | 0.32%   |
| GN Netcom                            | 2         | 0.32%   |
| Yamaha                               | 1         | 0.16%   |
| Turtle Beach                         | 1         | 0.16%   |
| Sony                                 | 1         | 0.16%   |
| SAVITECH                             | 1         | 0.16%   |
| Razer USA                            | 1         | 0.16%   |
| QinHeng Electronics                  | 1         | 0.16%   |
| Native Instruments                   | 1         | 0.16%   |
| Micro Star International             | 1         | 0.16%   |
| Generalplus Technology               | 1         | 0.16%   |
| Creative Technology                  | 1         | 0.16%   |
| CMX Systems                          | 1         | 0.16%   |
| Audioengine                          | 1         | 0.16%   |
| Apple                                | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 55        | 7.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 40        | 5.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 3.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 2.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.29%   |
| AMD FCH Azalia Controller                                                                         | 16        | 2.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 1.88%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.81%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 5         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5         | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 55        | 23.81%  |
| SK hynix                     | 39        | 16.88%  |
| Unknown                      | 32        | 13.85%  |
| Micron Technology            | 21        | 9.09%   |
| Kingston                     | 19        | 8.23%   |
| Corsair                      | 12        | 5.19%   |
| Crucial                      | 9         | 3.9%    |
| G.Skill                      | 8         | 3.46%   |
| Nanya Technology             | 4         | 1.73%   |
| Elpida                       | 4         | 1.73%   |
| A-DATA Technology            | 4         | 1.73%   |
| Unknown (ABCD)               | 3         | 1.3%    |
| Team                         | 2         | 0.87%   |
| Ramaxel Technology           | 2         | 0.87%   |
| GSkill                       | 2         | 0.87%   |
| GeIL                         | 2         | 0.87%   |
| Unknown                      | 2         | 0.87%   |
| Strontium                    | 1         | 0.43%   |
| Smart                        | 1         | 0.43%   |
| PUSKILL                      | 1         | 0.43%   |
| Patriot Memory (PDP Systems) | 1         | 0.43%   |
| Patriot                      | 1         | 0.43%   |
| Lexar Co Limited             | 1         | 0.43%   |
| KLEVV                        | 1         | 0.43%   |
| CSX                          | 1         | 0.43%   |
| AVEXIR                       | 1         | 0.43%   |
| AMD                          | 1         | 0.43%   |
| 4ea5                         | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 1.18%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.79%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 2         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.79%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.79%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 0.79%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.79%   |
| Micron RAM MT40A512M16TB-062E:R 4GB Row Of Chips DDR4 3200MT/s   | 2         | 0.79%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 0.79%   |
| G.Skill RAM F4-3200C22-32GRS 32GB SODIMM DDR4 3200MT/s           | 2         | 0.79%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Unknown                                                          | 2         | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.39%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 94        | 45.85%  |
| DDR3    | 70        | 34.15%  |
| DDR2    | 16        | 7.8%    |
| LPDDR4  | 8         | 3.9%    |
| SDRAM   | 6         | 2.93%   |
| LPDDR3  | 5         | 2.44%   |
| Unknown | 4         | 1.95%   |
| DRAM    | 1         | 0.49%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 132       | 65.02%  |
| DIMM         | 54        | 26.6%   |
| Row Of Chips | 14        | 6.9%    |
| Unknown      | 2         | 0.99%   |
| Chip         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 77        | 33.92%  |
| 4096  | 59        | 25.99%  |
| 2048  | 39        | 17.18%  |
| 16384 | 31        | 13.66%  |
| 1024  | 8         | 3.52%   |
| 32768 | 7         | 3.08%   |
| 512   | 5         | 2.2%    |
| 16    | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 41        | 18.64%  |
| 1600    | 41        | 18.64%  |
| 2667    | 28        | 12.73%  |
| 2400    | 20        | 9.09%   |
| 1333    | 13        | 5.91%   |
| 2133    | 11        | 5%      |
| 1334    | 8         | 3.64%   |
| 667     | 8         | 3.64%   |
| Unknown | 8         | 3.64%   |
| 1067    | 7         | 3.18%   |
| 3600    | 6         | 2.73%   |
| 1867    | 5         | 2.27%   |
| 1066    | 3         | 1.36%   |
| 533     | 3         | 1.36%   |
| 4267    | 2         | 0.91%   |
| 4199    | 2         | 0.91%   |
| 3733    | 2         | 0.91%   |
| 1866    | 2         | 0.91%   |
| 1800    | 2         | 0.91%   |
| 3266    | 1         | 0.45%   |
| 2666    | 1         | 0.45%   |
| 2267    | 1         | 0.45%   |
| 2048    | 1         | 0.45%   |
| 1200    | 1         | 0.45%   |
| 800     | 1         | 0.45%   |
| 400     | 1         | 0.45%   |
| 266     | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Seiko Epson         | 1         | 12.5%   |
| QinHeng Electronics | 1         | 12.5%   |
| Prolific Technology | 1         | 12.5%   |
| Konica Minolta      | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ET-2820 Series    | 1         | 12.5%   |
| QinHeng CH340S                | 1         | 12.5%   |
| Prolific PL2305 Parallel Port | 1         | 12.5%   |
| Konica Minolta 185            | 1         | 12.5%   |
| HP OfficeJet Pro 8730         | 1         | 12.5%   |
| HP OfficeJet 6200             | 1         | 12.5%   |
| HP DeskJet 2130 series        | 1         | 12.5%   |
| Brother MFC-L2685DW           | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| Canon CanoScan LIDE 25                        | 1         | 25%     |
| Canon CanoScan LiDE 210                       | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 19.65%  |
| Microdia                               | 28        | 9.82%   |
| IMC Networks                           | 22        | 7.72%   |
| Bison Electronics                      | 19        | 6.67%   |
| Sunplus Innovation Technology          | 18        | 6.32%   |
| Realtek Semiconductor                  | 18        | 6.32%   |
| Suyin                                  | 16        | 5.61%   |
| Quanta                                 | 16        | 5.61%   |
| Luxvisions Innotech Limited            | 9         | 3.16%   |
| Logitech                               | 9         | 3.16%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.16%   |
| Apple                                  | 9         | 3.16%   |
| Alcor Micro                            | 9         | 3.16%   |
| Syntek                                 | 6         | 2.11%   |
| Silicon Motion                         | 4         | 1.4%    |
| Acer                                   | 4         | 1.4%    |
| Lite-On Technology                     | 3         | 1.05%   |
| Importek                               | 3         | 1.05%   |
| Z-Star Microelectronics                | 2         | 0.7%    |
| OmniVision Technologies                | 2         | 0.7%    |
| Microsoft                              | 2         | 0.7%    |
| Lenovo                                 | 2         | 0.7%    |
| Huawei Technologies                    | 2         | 0.7%    |
| Creative Technology                    | 2         | 0.7%    |
| ALi                                    | 2         | 0.7%    |
| Sunplus Technology                     | 1         | 0.35%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.35%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Razer USA                              | 1         | 0.35%   |
| Pixart Imaging                         | 1         | 0.35%   |
| MacroSilicon                           | 1         | 0.35%   |
| Intel                                  | 1         | 0.35%   |
| icSpring                               | 1         | 0.35%   |
| Genesys Logic                          | 1         | 0.35%   |
| eMPIA Technology                       | 1         | 0.35%   |
| eMeet                                  | 1         | 0.35%   |
| ARC International                      | 1         | 0.35%   |
| Alpha Imaging Technology               | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 18        | 6.21%   |
| Microdia Integrated_Webcam_HD                                  | 15        | 5.17%   |
| Bison Integrated Camera                                        | 9         | 3.1%    |
| IMC Networks Integrated Camera                                 | 6         | 2.07%   |
| Realtek USB2.0 camera                                          | 5         | 1.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 5         | 1.72%   |
| Chicony HD Webcam                                              | 5         | 1.72%   |
| Alcor Micro USB 2.0 Camera                                     | 5         | 1.72%   |
| Syntek Integrated Camera                                       | 4         | 1.38%   |
| Sunplus HD WebCam                                              | 4         | 1.38%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 4         | 1.38%   |
| Chicony HP TrueVision HD Camera                                | 4         | 1.38%   |
| Apple Built-in iSight                                          | 4         | 1.38%   |
| Suyin HP TrueVision HD                                         | 3         | 1.03%   |
| Sunplus DICOTA 4K                                              | 3         | 1.03%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.03%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 1.03%   |
| Quanta HP Webcam                                               | 3         | 1.03%   |
| Microdia USB 2.0 Camera                                        | 3         | 1.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 1.03%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 1.03%   |
| Chicony HP HD Camera                                           | 3         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.03%   |
| Suyin HD WebCam                                                | 2         | 0.69%   |
| Suyin HD Video WebCam                                          | 2         | 0.69%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 2         | 0.69%   |
| Sunplus MTD camera                                             | 2         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 0.69%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 0.69%   |
| Quanta VGA WebCam                                              | 2         | 0.69%   |
| Quanta HP HD Camera                                            | 2         | 0.69%   |
| Microdia Lenovo EasyCamera                                     | 2         | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 0.69%   |
| Logitech Webcam C270                                           | 2         | 0.69%   |
| Lite-On HP TrueVision HD Camera                                | 2         | 0.69%   |
| IMC Networks EasyCamera                                        | 2         | 0.69%   |
| Huawei HiCamera                                                | 2         | 0.69%   |
| Chicony USB2.0 Camera                                          | 2         | 0.69%   |
| Chicony TOSHIBA Web Camera - FHD                               | 2         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 44.44%  |
| Synaptics                  | 6         | 13.33%  |
| Shenzhen Goodix Technology | 4         | 8.89%   |
| AuthenTec                  | 4         | 8.89%   |
| Upek                       | 3         | 6.67%   |
| STMicroelectronics         | 2         | 4.44%   |
| Focal-systems.Corp         | 2         | 4.44%   |
| Samsung Electronics        | 1         | 2.22%   |
| Microsoft                  | 1         | 2.22%   |
| LighTuning Technology      | 1         | 2.22%   |
| Elan Microelectronics      | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 4         | 8.89%   |
| Validity Sensors Fingerprint scanner                     | 3         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 6.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 4.44%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 4.44%   |
| Validity Sensors VFS301 Fingerprint Reader               | 2         | 4.44%   |
| Validity Sensors Synaptics WBDI                          | 2         | 4.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 4.44%   |
| STMicroelectronics Fingerprint Reader                    | 2         | 4.44%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 4.44%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                | 2         | 4.44%   |
| AuthenTec AES1600                                        | 2         | 4.44%   |
| Validity Sensors VFS491                                  | 1         | 2.22%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 2.22%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 2.22%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.22%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 2.22%   |
| Synaptics WBDI                                           | 1         | 2.22%   |
| Synaptics UWP WBDI Device                                | 1         | 2.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 2.22%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                              | 1         | 2.22%   |
| Samsung Fingerprint Sensor Device - 730B                 | 1         | 2.22%   |
| Microsoft Fingerprint Reader                             | 1         | 2.22%   |
| LighTuning Fingerprint Reader                            | 1         | 2.22%   |
| Elan ELAN:Fingerprint                                    | 1         | 2.22%   |
| AuthenTec Fingerprint Sensor                             | 1         | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 57.89%  |
| Alcor Micro | 3         | 15.79%  |
| Upek        | 2         | 10.53%  |
| O2 Micro    | 2         | 10.53%  |
| Lenovo      | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 21.05%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 10.53%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10.53%  |
| Broadcom 58200                                                               | 2         | 10.53%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 316       | 65.15%  |
| 1     | 137       | 28.25%  |
| 2     | 27        | 5.57%   |
| 3     | 3         | 0.62%   |
| 4     | 2         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 52        | 25.37%  |
| Graphics card            | 49        | 23.9%   |
| Fingerprint reader       | 44        | 21.46%  |
| Multimedia controller    | 23        | 11.22%  |
| Chipcard                 | 18        | 8.78%   |
| Communication controller | 4         | 1.95%   |
| Storage                  | 3         | 1.46%   |
| Bluetooth                | 3         | 1.46%   |
| Camera                   | 2         | 0.98%   |
| Unassigned class         | 1         | 0.49%   |
| Storage/raid             | 1         | 0.49%   |
| Sound                    | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |
| Flash memory             | 1         | 0.49%   |
| Dvb card                 | 1         | 0.49%   |
| Card reader              | 1         | 0.49%   |

