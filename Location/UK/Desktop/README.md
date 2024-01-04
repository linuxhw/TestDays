Linux in UK - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 5264

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B550M Pro4                  | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASRock        | Z77 Professional            | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| HP            | 82A2                        | [7cc3d17916](https://linux-hardware.org/?probe=7cc3d17916) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Pegatron      | EVANS                       | [b2a67b83cd](https://linux-hardware.org/?probe=b2a67b83cd) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fb6fd51a2](https://linux-hardware.org/?probe=4fb6fd51a2) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [f45ebb1f0d](https://linux-hardware.org/?probe=f45ebb1f0d) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [eb264efa92](https://linux-hardware.org/?probe=eb264efa92) | Dec 31, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | [ba1b2a738a](https://linux-hardware.org/?probe=ba1b2a738a) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [88a9972a33](https://linux-hardware.org/?probe=88a9972a33) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [91be04698f](https://linux-hardware.org/?probe=91be04698f) | Dec 30, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [403210cab1](https://linux-hardware.org/?probe=403210cab1) | Dec 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [50eef7421d](https://linux-hardware.org/?probe=50eef7421d) | Dec 29, 2023 |
| Gigabyte      | 990FXA-UD3                  | [9104adc237](https://linux-hardware.org/?probe=9104adc237) | Dec 29, 2023 |
| ASUSTek       | X99-DELUXE                  | [2433b4bc75](https://linux-hardware.org/?probe=2433b4bc75) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | [617d953e8f](https://linux-hardware.org/?probe=617d953e8f) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | [587d9f4fcb](https://linux-hardware.org/?probe=587d9f4fcb) | Dec 29, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| Dell          | 04Y8V0 A02                  | [ba96083a55](https://linux-hardware.org/?probe=ba96083a55) | Dec 28, 2023 |
| Dell          | 0R230R A00                  | [50111db215](https://linux-hardware.org/?probe=50111db215) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee1b832527](https://linux-hardware.org/?probe=ee1b832527) | Dec 28, 2023 |
| HP            | 2AFB                        | [5279d471aa](https://linux-hardware.org/?probe=5279d471aa) | Dec 27, 2023 |
| ASUSTek       | UN42                        | [1b146f734f](https://linux-hardware.org/?probe=1b146f734f) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bfa7e572a4](https://linux-hardware.org/?probe=bfa7e572a4) | Dec 27, 2023 |
| ASRock        | X670E Steel Legend          | [fde01139b9](https://linux-hardware.org/?probe=fde01139b9) | Dec 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d661150c95](https://linux-hardware.org/?probe=d661150c95) | Dec 27, 2023 |
| Dell          | 0KWVT8 A03                  | [fae868ef79](https://linux-hardware.org/?probe=fae868ef79) | Dec 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ca94325310](https://linux-hardware.org/?probe=ca94325310) | Dec 26, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [e6cbc30aad](https://linux-hardware.org/?probe=e6cbc30aad) | Dec 25, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [915a47dab1](https://linux-hardware.org/?probe=915a47dab1) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | [2474ae00d3](https://linux-hardware.org/?probe=2474ae00d3) | Dec 24, 2023 |
| Acer          | Veriton X2631G V:1.0        | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | [bb26992a0a](https://linux-hardware.org/?probe=bb26992a0a) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| ASRock        | H610M-HVS                   | [25b5c11ccc](https://linux-hardware.org/?probe=25b5c11ccc) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [98eee633b1](https://linux-hardware.org/?probe=98eee633b1) | Dec 20, 2023 |
| MSI           | 970 GAMING                  | [cb71670ca0](https://linux-hardware.org/?probe=cb71670ca0) | Dec 20, 2023 |
| Intel         | DH55TC AAE70932-206         | [3003aeb5a9](https://linux-hardware.org/?probe=3003aeb5a9) | Dec 20, 2023 |
| Gigabyte      | Z390 UD                     | [8e6c8be806](https://linux-hardware.org/?probe=8e6c8be806) | Dec 19, 2023 |
| Gigabyte      | B550M DS3H                  | [0fd7e9086a](https://linux-hardware.org/?probe=0fd7e9086a) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASRock        | B650M Pro RS                | [df96c996dd](https://linux-hardware.org/?probe=df96c996dd) | Dec 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [38b0463b4a](https://linux-hardware.org/?probe=38b0463b4a) | Dec 18, 2023 |
| Gigabyte      | Z77-D3H                     | [8f34c208f2](https://linux-hardware.org/?probe=8f34c208f2) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [a62323f9e3](https://linux-hardware.org/?probe=a62323f9e3) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| BESSTAR Te... | UM700                       | [ac4adad071](https://linux-hardware.org/?probe=ac4adad071) | Dec 18, 2023 |
| MSI           | MAG B550M BAZOOKA           | [474668dbec](https://linux-hardware.org/?probe=474668dbec) | Dec 18, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [c0b618e2ab](https://linux-hardware.org/?probe=c0b618e2ab) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| ASRock        | X670E Taichi Carrara        | [2d0eb33a7a](https://linux-hardware.org/?probe=2d0eb33a7a) | Dec 17, 2023 |
| Gigabyte      | B550M DS3H                  | [28d755787e](https://linux-hardware.org/?probe=28d755787e) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [316b12645c](https://linux-hardware.org/?probe=316b12645c) | Dec 17, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | [0f2293e8d1](https://linux-hardware.org/?probe=0f2293e8d1) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [36f9f51f5d](https://linux-hardware.org/?probe=36f9f51f5d) | Dec 16, 2023 |
| HP            | 3397                        | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| Gigabyte      | Z77-D3H                     | [52012e39df](https://linux-hardware.org/?probe=52012e39df) | Dec 16, 2023 |
| Dell          | 02YYK5 A01                  | [0558258245](https://linux-hardware.org/?probe=0558258245) | Dec 16, 2023 |
| Dell          | 0HY9JP A00                  | [5af488fb21](https://linux-hardware.org/?probe=5af488fb21) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [ec182b1b52](https://linux-hardware.org/?probe=ec182b1b52) | Dec 16, 2023 |
| HP            | 2AFB                        | [4160a75172](https://linux-hardware.org/?probe=4160a75172) | Dec 15, 2023 |
| Dell          | 0HY9JP A00                  | [3a2a8878eb](https://linux-hardware.org/?probe=3a2a8878eb) | Dec 15, 2023 |
| HP            | 8592                        | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| HP            | 8592                        | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [39f4b40998](https://linux-hardware.org/?probe=39f4b40998) | Dec 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [7e358e1c4b](https://linux-hardware.org/?probe=7e358e1c4b) | Dec 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [01f7be08ae](https://linux-hardware.org/?probe=01f7be08ae) | Dec 13, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| Gigabyte      | H310M H x.x                 | [bcf9fba46f](https://linux-hardware.org/?probe=bcf9fba46f) | Dec 12, 2023 |
| Unknown       | Unknown                     | [c9eae3e15f](https://linux-hardware.org/?probe=c9eae3e15f) | Dec 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [39a6569b14](https://linux-hardware.org/?probe=39a6569b14) | Dec 12, 2023 |
| Dell          | 07WP95 A02                  | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| Entroware     | Poseidon                    | [88c52d72cc](https://linux-hardware.org/?probe=88c52d72cc) | Dec 11, 2023 |
| ASUSTek       | A88XM-E                     | [ef34073e18](https://linux-hardware.org/?probe=ef34073e18) | Dec 11, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [76c38ed49a](https://linux-hardware.org/?probe=76c38ed49a) | Dec 11, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [237db70b40](https://linux-hardware.org/?probe=237db70b40) | Dec 10, 2023 |
| ASUSTek       | P8H61-MX USB3               | [60d3606ca9](https://linux-hardware.org/?probe=60d3606ca9) | Dec 10, 2023 |
| Medion        | B360H4-EM V1.0              | [a0d6ba0881](https://linux-hardware.org/?probe=a0d6ba0881) | Dec 08, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [df7eb64dd1](https://linux-hardware.org/?probe=df7eb64dd1) | Dec 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [0403680fc9](https://linux-hardware.org/?probe=0403680fc9) | Dec 07, 2023 |
| Gigabyte      | 970A-DS3                    | [cad7bc7542](https://linux-hardware.org/?probe=cad7bc7542) | Dec 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [5ba88bb243](https://linux-hardware.org/?probe=5ba88bb243) | Dec 06, 2023 |
| HP            | 2AFB                        | [a91d9cd265](https://linux-hardware.org/?probe=a91d9cd265) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [38945d6d2e](https://linux-hardware.org/?probe=38945d6d2e) | Dec 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [eebdbc8611](https://linux-hardware.org/?probe=eebdbc8611) | Dec 04, 2023 |
| ASUSTek       | Z170-A                      | [8a8bfb131c](https://linux-hardware.org/?probe=8a8bfb131c) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [325091c7a2](https://linux-hardware.org/?probe=325091c7a2) | Dec 04, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f013a81cbb](https://linux-hardware.org/?probe=f013a81cbb) | Dec 03, 2023 |
| MSI           | B450M MORTAR                | [5e8bdafa0a](https://linux-hardware.org/?probe=5e8bdafa0a) | Dec 03, 2023 |
| Dell          | 0KWVT8 A02                  | [3c6a13271b](https://linux-hardware.org/?probe=3c6a13271b) | Dec 03, 2023 |
| Trigkey       | Green G4 10                 | [bade24732d](https://linux-hardware.org/?probe=bade24732d) | Dec 03, 2023 |
| Trigkey       | Green G4 10                 | [b3d175cddb](https://linux-hardware.org/?probe=b3d175cddb) | Dec 03, 2023 |
| Dell          | 03NVJ6 A02                  | [7f9b2fa7e0](https://linux-hardware.org/?probe=7f9b2fa7e0) | Dec 03, 2023 |
| Dell          | 0JP3NX A01                  | [bb746b7506](https://linux-hardware.org/?probe=bb746b7506) | Dec 02, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8fd7437767](https://linux-hardware.org/?probe=8fd7437767) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | NO DPK                      | [1ba43c09a6](https://linux-hardware.org/?probe=1ba43c09a6) | Nov 30, 2023 |
| HP            | 1495                        | [9dcb53a8c2](https://linux-hardware.org/?probe=9dcb53a8c2) | Nov 30, 2023 |
| ASRock        | X399 Taichi                 | [5e8be973c6](https://linux-hardware.org/?probe=5e8be973c6) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [2c9b3f229e](https://linux-hardware.org/?probe=2c9b3f229e) | Nov 29, 2023 |
| Unknown       | HX90                        | [54a2eb227b](https://linux-hardware.org/?probe=54a2eb227b) | Nov 29, 2023 |
| HP            | 8643 SMVB                   | [dae10e70d0](https://linux-hardware.org/?probe=dae10e70d0) | Nov 29, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a97b3bd106](https://linux-hardware.org/?probe=a97b3bd106) | Nov 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [fc4e66ac12](https://linux-hardware.org/?probe=fc4e66ac12) | Nov 29, 2023 |
| MSI           | A320M-A PRO                 | [96af3871d2](https://linux-hardware.org/?probe=96af3871d2) | Nov 29, 2023 |
| ASUSTek       | PRIME X370-A                | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7378c9d9a4](https://linux-hardware.org/?probe=7378c9d9a4) | Nov 28, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [549e026701](https://linux-hardware.org/?probe=549e026701) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | [5ab684ace6](https://linux-hardware.org/?probe=5ab684ace6) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | [d4488776c4](https://linux-hardware.org/?probe=d4488776c4) | Nov 27, 2023 |
| ASUSTek       | G11CB                       | [31f2fc857d](https://linux-hardware.org/?probe=31f2fc857d) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| HP            | 8184 X4                     | [0813228fc1](https://linux-hardware.org/?probe=0813228fc1) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dda972d27c](https://linux-hardware.org/?probe=dda972d27c) | Nov 26, 2023 |
| HP            | 8704                        | [594422dbde](https://linux-hardware.org/?probe=594422dbde) | Nov 26, 2023 |
| Gigabyte      | G41M-ES2L                   | [f2856297d6](https://linux-hardware.org/?probe=f2856297d6) | Nov 26, 2023 |
| HP            | 2820h                       | [b1659e17cb](https://linux-hardware.org/?probe=b1659e17cb) | Nov 26, 2023 |
| Dell          | 0WR7PY A01                  | [cceb19120f](https://linux-hardware.org/?probe=cceb19120f) | Nov 26, 2023 |
| ASRock        | B450M Steel Legend          | [b0f55cc692](https://linux-hardware.org/?probe=b0f55cc692) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| ASUSTek       | H97-PLUS                    | [e4c365b554](https://linux-hardware.org/?probe=e4c365b554) | Nov 26, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [44dfa50d7d](https://linux-hardware.org/?probe=44dfa50d7d) | Nov 25, 2023 |
| MSI           | MAG B760M MORTAR WIFI DD... | [b11fcf42c2](https://linux-hardware.org/?probe=b11fcf42c2) | Nov 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [5bbefae656](https://linux-hardware.org/?probe=5bbefae656) | Nov 25, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [22bbe29da3](https://linux-hardware.org/?probe=22bbe29da3) | Nov 25, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [62033adcb7](https://linux-hardware.org/?probe=62033adcb7) | Nov 25, 2023 |
| Dell          | 02M8NY A00                  | [4c874a153e](https://linux-hardware.org/?probe=4c874a153e) | Nov 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5c29cfeb41](https://linux-hardware.org/?probe=5c29cfeb41) | Nov 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [f4a77c64b0](https://linux-hardware.org/?probe=f4a77c64b0) | Nov 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [16e9af1d1a](https://linux-hardware.org/?probe=16e9af1d1a) | Nov 24, 2023 |
| Dell          | 0TP406                      | [cc0c592ca4](https://linux-hardware.org/?probe=cc0c592ca4) | Nov 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b98f204f02](https://linux-hardware.org/?probe=b98f204f02) | Nov 23, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [31b35710ab](https://linux-hardware.org/?probe=31b35710ab) | Nov 23, 2023 |
| Gigabyte      | H310M H x.x                 | [b1d5cf3254](https://linux-hardware.org/?probe=b1d5cf3254) | Nov 23, 2023 |
| HP            | 3029h                       | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [24ebfe35c8](https://linux-hardware.org/?probe=24ebfe35c8) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [b564a39ed5](https://linux-hardware.org/?probe=b564a39ed5) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [205b0b2438](https://linux-hardware.org/?probe=205b0b2438) | Nov 22, 2023 |
| Gigabyte      | H510M S2H V2                | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| Dell          | 02M8NY A00                  | [7795e6e71f](https://linux-hardware.org/?probe=7795e6e71f) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [db14a6cc67](https://linux-hardware.org/?probe=db14a6cc67) | Nov 20, 2023 |
| ASRock        | X570 Pro4                   | [9bf1dda551](https://linux-hardware.org/?probe=9bf1dda551) | Nov 19, 2023 |
| HP            | 2B47                        | [86e6bb9503](https://linux-hardware.org/?probe=86e6bb9503) | Nov 19, 2023 |
| HP            | 2B47                        | [ba5e6806fc](https://linux-hardware.org/?probe=ba5e6806fc) | Nov 19, 2023 |
| ASUSTek       | M2NPV-VM                    | [be4bd9aeaf](https://linux-hardware.org/?probe=be4bd9aeaf) | Nov 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [bfbed17470](https://linux-hardware.org/?probe=bfbed17470) | Nov 18, 2023 |
| Dell          | 0DY62R A01                  | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [0ebd3e6dd0](https://linux-hardware.org/?probe=0ebd3e6dd0) | Nov 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [6b4903cbb7](https://linux-hardware.org/?probe=6b4903cbb7) | Nov 17, 2023 |
| Dell          | 0HHV7N A00                  | [9bb04e6b68](https://linux-hardware.org/?probe=9bb04e6b68) | Nov 17, 2023 |
| Intel         | DQ77MK AAG39642-500         | [dbcccfee47](https://linux-hardware.org/?probe=dbcccfee47) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| Gigabyte      | H310M H x.x                 | [a95e23a38b](https://linux-hardware.org/?probe=a95e23a38b) | Nov 16, 2023 |
| ASRock        | X570M Pro4                  | [b166167703](https://linux-hardware.org/?probe=b166167703) | Nov 16, 2023 |
| NZXT          | N7 B650E                    | [588de38c13](https://linux-hardware.org/?probe=588de38c13) | Nov 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | [63ba7cf0b1](https://linux-hardware.org/?probe=63ba7cf0b1) | Nov 16, 2023 |
| Intel         | DQ77MK AAG39642-500         | [19d77470a5](https://linux-hardware.org/?probe=19d77470a5) | Nov 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [389f2adb17](https://linux-hardware.org/?probe=389f2adb17) | Nov 16, 2023 |
| ASUSTek       | A88XM-PLUS                  | [c951dffd5f](https://linux-hardware.org/?probe=c951dffd5f) | Nov 15, 2023 |
| ASUSTek       | A88XM-PLUS                  | [cc83fead4c](https://linux-hardware.org/?probe=cc83fead4c) | Nov 15, 2023 |
| Gigabyte      | B85M-HD3                    | [5992237ea5](https://linux-hardware.org/?probe=5992237ea5) | Nov 15, 2023 |
| Dell          | 0DFRFW A01                  | [dc42526823](https://linux-hardware.org/?probe=dc42526823) | Nov 15, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [7580fdc874](https://linux-hardware.org/?probe=7580fdc874) | Nov 15, 2023 |
| Shenzhen M... | F7BAA                       | [e91aa41101](https://linux-hardware.org/?probe=e91aa41101) | Nov 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| Alienware     | 0P0JWX A00                  | [06fd25c3b5](https://linux-hardware.org/?probe=06fd25c3b5) | Nov 14, 2023 |
| Gigabyte      | B365M DS3H                  | [23196bda4d](https://linux-hardware.org/?probe=23196bda4d) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [edc5aa4d33](https://linux-hardware.org/?probe=edc5aa4d33) | Nov 13, 2023 |
| Dell          | 0P01GV A03                  | [9ae5ddcf15](https://linux-hardware.org/?probe=9ae5ddcf15) | Nov 12, 2023 |
| Trigkey       | Green G4 10                 | [13e4a51787](https://linux-hardware.org/?probe=13e4a51787) | Nov 12, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [b310ceb608](https://linux-hardware.org/?probe=b310ceb608) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [3b4f0e52cf](https://linux-hardware.org/?probe=3b4f0e52cf) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [ea0ea2dcff](https://linux-hardware.org/?probe=ea0ea2dcff) | Nov 10, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [a6a53a60f0](https://linux-hardware.org/?probe=a6a53a60f0) | Nov 10, 2023 |
| Dell          | 0TY565                      | [9bf6328f12](https://linux-hardware.org/?probe=9bf6328f12) | Nov 09, 2023 |
| Gigabyte      | A520I AC                    | [5a4538afb3](https://linux-hardware.org/?probe=5a4538afb3) | Nov 09, 2023 |
| ASUSTek       | Z87-A                       | [669cb641ab](https://linux-hardware.org/?probe=669cb641ab) | Nov 09, 2023 |
| Lenovo        | 3106 SDK0J40700 WIN 3258... | [95cf0f4ff0](https://linux-hardware.org/?probe=95cf0f4ff0) | Nov 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [e46ed9f47e](https://linux-hardware.org/?probe=e46ed9f47e) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [978f54c17b](https://linux-hardware.org/?probe=978f54c17b) | Nov 08, 2023 |
| MSI           | H110M PRO-VD                | [6795a19ca5](https://linux-hardware.org/?probe=6795a19ca5) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| Gigabyte      | H310M H x.x                 | [5c1aced8cf](https://linux-hardware.org/?probe=5c1aced8cf) | Nov 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [c81bc71fdb](https://linux-hardware.org/?probe=c81bc71fdb) | Nov 08, 2023 |
| Dell          | 0HHV7N A00                  | [2be7c3b6d6](https://linux-hardware.org/?probe=2be7c3b6d6) | Nov 07, 2023 |
| Dell          | 0TY565                      | [1597a5eaf7](https://linux-hardware.org/?probe=1597a5eaf7) | Nov 07, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [2e09b6a2b0](https://linux-hardware.org/?probe=2e09b6a2b0) | Nov 07, 2023 |
| MSI           | PRO Z790-A WIFI             | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| HP            | 2AF3                        | [19333e743d](https://linux-hardware.org/?probe=19333e743d) | Nov 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [26332591d7](https://linux-hardware.org/?probe=26332591d7) | Nov 06, 2023 |
| GMKtec        | NucBox K2                   | [a88d491579](https://linux-hardware.org/?probe=a88d491579) | Nov 06, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [d95f04dd2c](https://linux-hardware.org/?probe=d95f04dd2c) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [f48ca40214](https://linux-hardware.org/?probe=f48ca40214) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [5196f9303d](https://linux-hardware.org/?probe=5196f9303d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| Gigabyte      | GA-970A-DS3                 | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [4e3cd50b3f](https://linux-hardware.org/?probe=4e3cd50b3f) | Nov 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | 03TJ75 A00                  | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [1ca6496a6c](https://linux-hardware.org/?probe=1ca6496a6c) | Nov 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [801d83a570](https://linux-hardware.org/?probe=801d83a570) | Nov 01, 2023 |
| HP            | 0A58h                       | [9dd3c3fdfb](https://linux-hardware.org/?probe=9dd3c3fdfb) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Unknown       | Unknown                     | [c7ce75613c](https://linux-hardware.org/?probe=c7ce75613c) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| MSI           | Z87-G45 GAMING              | [962f4ccb9e](https://linux-hardware.org/?probe=962f4ccb9e) | Oct 31, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| HP            | 0A58h                       | [f7c62b9410](https://linux-hardware.org/?probe=f7c62b9410) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| Intel         | H311 DS3 V1.0               | [2eabffe817](https://linux-hardware.org/?probe=2eabffe817) | Oct 31, 2023 |
| Gigabyte      | B365M DS3H                  | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9ca810aaa6](https://linux-hardware.org/?probe=9ca810aaa6) | Oct 29, 2023 |
| Biostar       | G31D-M7                     | [192416033b](https://linux-hardware.org/?probe=192416033b) | Oct 28, 2023 |
| ASRock        | B450 Steel Legend           | [967ed7a2b9](https://linux-hardware.org/?probe=967ed7a2b9) | Oct 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| MSI           | PRO Z790-P WIFI             | [60372b59fe](https://linux-hardware.org/?probe=60372b59fe) | Oct 28, 2023 |
| HP            | 2AF3                        | [f7c7d92cea](https://linux-hardware.org/?probe=f7c7d92cea) | Oct 28, 2023 |
| MSI           | B450M MORTAR MAX            | [ab3b2be8f5](https://linux-hardware.org/?probe=ab3b2be8f5) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | [8f83740c8d](https://linux-hardware.org/?probe=8f83740c8d) | Oct 26, 2023 |
| Foxconn       | 2AA9h                       | [dade54701d](https://linux-hardware.org/?probe=dade54701d) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [8926585836](https://linux-hardware.org/?probe=8926585836) | Oct 26, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b75faeaf8a](https://linux-hardware.org/?probe=b75faeaf8a) | Oct 25, 2023 |
| ASRock        | A520M-ITX/ac                | [8a5e0bd9d6](https://linux-hardware.org/?probe=8a5e0bd9d6) | Oct 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [f88a2686e9](https://linux-hardware.org/?probe=f88a2686e9) | Oct 25, 2023 |
| ASUSTek       | Z170-P                      | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Acer          | Aspire XC-1760              | [8a5c420847](https://linux-hardware.org/?probe=8a5c420847) | Oct 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [268b32d9bf](https://linux-hardware.org/?probe=268b32d9bf) | Oct 24, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2d6bcd74d8](https://linux-hardware.org/?probe=2d6bcd74d8) | Oct 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | [95b5ac0a0e](https://linux-hardware.org/?probe=95b5ac0a0e) | Oct 24, 2023 |
| Gigabyte      | B365M DS3H                  | [87102526a5](https://linux-hardware.org/?probe=87102526a5) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| Gigabyte      | A520I AC                    | [fc82aed364](https://linux-hardware.org/?probe=fc82aed364) | Oct 23, 2023 |
| Gigabyte      | H310M H x.x                 | [d8c12e782e](https://linux-hardware.org/?probe=d8c12e782e) | Oct 23, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [98a242f151](https://linux-hardware.org/?probe=98a242f151) | Oct 21, 2023 |
| Lenovo        | ThinkServer TS140           | [b52eba9a1b](https://linux-hardware.org/?probe=b52eba9a1b) | Oct 21, 2023 |
| ASRock        | X570 Pro4                   | [f350ad7b18](https://linux-hardware.org/?probe=f350ad7b18) | Oct 20, 2023 |
| MSI           | G41TM-P31                   | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Pegatron      | Benicia                     | [c8ec5c8db0](https://linux-hardware.org/?probe=c8ec5c8db0) | Oct 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Acer          | Aspire TC-1760              | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [534b565ca1](https://linux-hardware.org/?probe=534b565ca1) | Oct 18, 2023 |
| HP            | 3646h                       | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| HP            | 2B44                        | [9ec07b67b2](https://linux-hardware.org/?probe=9ec07b67b2) | Oct 18, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| Gigabyte      | H310M H x.x                 | [98b06c3d78](https://linux-hardware.org/?probe=98b06c3d78) | Oct 17, 2023 |
| Shenzhen M... | F7BSC                       | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| HP            | ProLiant ML350 Gen9         | [468a686a40](https://linux-hardware.org/?probe=468a686a40) | Oct 15, 2023 |
| ASRock        | B85M                        | [1712e16d1c](https://linux-hardware.org/?probe=1712e16d1c) | Oct 15, 2023 |
| Dell          | 0MWYPT A01                  | [67933e3dd7](https://linux-hardware.org/?probe=67933e3dd7) | Oct 14, 2023 |
| Dell          | 0Y2K8N A01                  | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| Gigabyte      | Z170M-D3H-CF                | [c090855f1d](https://linux-hardware.org/?probe=c090855f1d) | Oct 13, 2023 |
| Inventec      | DQ Class A02                | [675695eef9](https://linux-hardware.org/?probe=675695eef9) | Oct 12, 2023 |
| Intel         | X99-P4 V1.0                 | [afe1fd91c2](https://linux-hardware.org/?probe=afe1fd91c2) | Oct 12, 2023 |
| ASUSTek       | Q170M-C                     | [07a8a2d89f](https://linux-hardware.org/?probe=07a8a2d89f) | Oct 12, 2023 |
| Gigabyte      | A320M-H-CF                  | [a549a213f1](https://linux-hardware.org/?probe=a549a213f1) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| MSI           | X470 GAMING PLUS            | [5d9cf3ae21](https://linux-hardware.org/?probe=5d9cf3ae21) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Dell          | 03NVJ6 A02                  | [0f40b40836](https://linux-hardware.org/?probe=0f40b40836) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Gigabyte      | B550M DS3H                  | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [22d9a872fe](https://linux-hardware.org/?probe=22d9a872fe) | Oct 10, 2023 |
| Lenovo        | SHARKBAY NOK                | [b14d9fc84b](https://linux-hardware.org/?probe=b14d9fc84b) | Oct 10, 2023 |
| Dell          | 03NVJ6 A02                  | [8f7a44301e](https://linux-hardware.org/?probe=8f7a44301e) | Oct 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec66d208a0](https://linux-hardware.org/?probe=ec66d208a0) | Oct 10, 2023 |
| Gigabyte      | Z690 UD DDR4                | [8b0cd9f9f7](https://linux-hardware.org/?probe=8b0cd9f9f7) | Oct 10, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ac48da1d5c](https://linux-hardware.org/?probe=ac48da1d5c) | Oct 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [165a7d4ae1](https://linux-hardware.org/?probe=165a7d4ae1) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Acer          | Aspire TC-1760              | [c9e56d83be](https://linux-hardware.org/?probe=c9e56d83be) | Oct 08, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [7623527bdb](https://linux-hardware.org/?probe=7623527bdb) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [71ab2a6c8b](https://linux-hardware.org/?probe=71ab2a6c8b) | Oct 07, 2023 |
| MSI           | Z97 PC Mate                 | [6e2fa2dc88](https://linux-hardware.org/?probe=6e2fa2dc88) | Oct 07, 2023 |
| Dell          | 0WR7PY A02                  | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| Gigabyte      | B550 GAMING X V2            | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [b00d1d81e3](https://linux-hardware.org/?probe=b00d1d81e3) | Oct 05, 2023 |
| HP            | 8350                        | [28bfb834e4](https://linux-hardware.org/?probe=28bfb834e4) | Oct 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cbf93da8d0](https://linux-hardware.org/?probe=cbf93da8d0) | Oct 04, 2023 |
| Dell          | 0VNM11 A00                  | [127d9678c2](https://linux-hardware.org/?probe=127d9678c2) | Oct 04, 2023 |
| ECS           | GF8100VM-M5                 | [4534c53242](https://linux-hardware.org/?probe=4534c53242) | Oct 03, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab5cf455ba](https://linux-hardware.org/?probe=ab5cf455ba) | Oct 03, 2023 |
| IP3 Tech      | IB8                         | [ca4d58a353](https://linux-hardware.org/?probe=ca4d58a353) | Oct 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c5223b1e21](https://linux-hardware.org/?probe=c5223b1e21) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [06f658c722](https://linux-hardware.org/?probe=06f658c722) | Oct 02, 2023 |
| Gigabyte      | H310M H x.x                 | [3c76ca2934](https://linux-hardware.org/?probe=3c76ca2934) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| Intel         | D33217CK G76541-302         | [d1aab6a8d0](https://linux-hardware.org/?probe=d1aab6a8d0) | Sep 29, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [c602f8fba9](https://linux-hardware.org/?probe=c602f8fba9) | Sep 29, 2023 |
| ASUSTek       | P8H61-MX USB3               | [5d1175b3f3](https://linux-hardware.org/?probe=5d1175b3f3) | Sep 28, 2023 |
| HP            | 3397                        | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H61-MX USB3               | [31fe0087b8](https://linux-hardware.org/?probe=31fe0087b8) | Sep 28, 2023 |
| Lenovo        | ThinkServer TS140           | [0e08685628](https://linux-hardware.org/?probe=0e08685628) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS140           | [461eeadd52](https://linux-hardware.org/?probe=461eeadd52) | Sep 26, 2023 |
| BESSTAR Te... | UM700                       | [efd53d662d](https://linux-hardware.org/?probe=efd53d662d) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [e7a6f47b2f](https://linux-hardware.org/?probe=e7a6f47b2f) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [8b10c3ad64](https://linux-hardware.org/?probe=8b10c3ad64) | Sep 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6185e37a03](https://linux-hardware.org/?probe=6185e37a03) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| HP            | 1998                        | [f2c4af4cb6](https://linux-hardware.org/?probe=f2c4af4cb6) | Sep 22, 2023 |
| HP            | 1998                        | [ef51f7d583](https://linux-hardware.org/?probe=ef51f7d583) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [d9d063b9e8](https://linux-hardware.org/?probe=d9d063b9e8) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | GA-970A-DS3                 | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| Dell          | 0GY6Y8 A02                  | [92b6ccd3ad](https://linux-hardware.org/?probe=92b6ccd3ad) | Sep 21, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [6aae39a72b](https://linux-hardware.org/?probe=6aae39a72b) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| Unknown       | Unknown                     | [043be725eb](https://linux-hardware.org/?probe=043be725eb) | Sep 21, 2023 |
| Dell          | 0RY206                      | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| MSI           | Z270 GAMING M5              | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [85d131b5fc](https://linux-hardware.org/?probe=85d131b5fc) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Unknown       | Unknown                     | [2d2ec7d22c](https://linux-hardware.org/?probe=2d2ec7d22c) | Sep 18, 2023 |
| Gigabyte      | Z97P-D3                     | [3baa74b1a6](https://linux-hardware.org/?probe=3baa74b1a6) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| HP            | 0A9Ch                       | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| Intel         | JSL MRD                     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| HP            | 2B36                        | [ac92866980](https://linux-hardware.org/?probe=ac92866980) | Sep 11, 2023 |
| Dell          | 0GXM1W A01                  | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [dc3c32cc6a](https://linux-hardware.org/?probe=dc3c32cc6a) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| ASUSTek       | M4A87TD/USB3                | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| ASRock        | A520M-ITX/ac                | [0429117716](https://linux-hardware.org/?probe=0429117716) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| HP            | 1497                        | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| ASRock        | Z87 Pro4                    | [89b861e771](https://linux-hardware.org/?probe=89b861e771) | Sep 06, 2023 |
| HP            | 1497                        | [66bc78bedb](https://linux-hardware.org/?probe=66bc78bedb) | Sep 05, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [dcb565d513](https://linux-hardware.org/?probe=dcb565d513) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| ASUSTek       | A88XM-E                     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [15826e3d9e](https://linux-hardware.org/?probe=15826e3d9e) | Sep 04, 2023 |
| Unknown       | Unknown                     | [a0e83b70f5](https://linux-hardware.org/?probe=a0e83b70f5) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| MSI           | B560M PRO-E                 | [17eed28ecb](https://linux-hardware.org/?probe=17eed28ecb) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| MSI           | A320M-A PRO M2              | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | 0P01GV A03                  | [ef4d28f614](https://linux-hardware.org/?probe=ef4d28f614) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Dell          | 0D6H9T A00                  | [9830dce088](https://linux-hardware.org/?probe=9830dce088) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| AZW           | MINI S                      | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| ASUSTek       | PRIME Z270-P                | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d97cedcf3c](https://linux-hardware.org/?probe=d97cedcf3c) | Aug 28, 2023 |
| HC Technol... | HCAR5000-MI                 | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b217724e7](https://linux-hardware.org/?probe=2b217724e7) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [306a487e6d](https://linux-hardware.org/?probe=306a487e6d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| Dell          | 0RY206                      | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | [88e192b5f0](https://linux-hardware.org/?probe=88e192b5f0) | Aug 27, 2023 |
| HP            | 843C                        | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | [fc3a889045](https://linux-hardware.org/?probe=fc3a889045) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| MSI           | A320M-A PRO                 | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [3add2f8945](https://linux-hardware.org/?probe=3add2f8945) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [3ddae42f27](https://linux-hardware.org/?probe=3ddae42f27) | Aug 25, 2023 |
| MSI           | B550-A PRO                  | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [3a0ddb0171](https://linux-hardware.org/?probe=3a0ddb0171) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [fe7b3d01bb](https://linux-hardware.org/?probe=fe7b3d01bb) | Aug 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | [e5301a4a98](https://linux-hardware.org/?probe=e5301a4a98) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| HP            | 8054                        | [d5582dbf37](https://linux-hardware.org/?probe=d5582dbf37) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| Pegatron      | 2A94h                       | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| MSI           | Indio                       | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Dell          | 0KP561                      | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| Dell          | 0VRWRC A00                  | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| Gigabyte      | Z590 VISION G               | [0954ff78e7](https://linux-hardware.org/?probe=0954ff78e7) | Aug 16, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [c3d834a0df](https://linux-hardware.org/?probe=c3d834a0df) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| MSI           | 970A-G46                    | [d1b6347c9a](https://linux-hardware.org/?probe=d1b6347c9a) | Aug 15, 2023 |
| Dell          | 0RY206                      | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B450 GAMING X               | [d6cfe894c9](https://linux-hardware.org/?probe=d6cfe894c9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [a4f97e45f1](https://linux-hardware.org/?probe=a4f97e45f1) | Aug 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [a737674e04](https://linux-hardware.org/?probe=a737674e04) | Aug 12, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ee14fdafcf](https://linux-hardware.org/?probe=ee14fdafcf) | Aug 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [67414922e3](https://linux-hardware.org/?probe=67414922e3) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [8d27e3953f](https://linux-hardware.org/?probe=8d27e3953f) | Aug 09, 2023 |
| Dell          | 02YYK5 A00                  | [14382141e9](https://linux-hardware.org/?probe=14382141e9) | Aug 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [691838cd8c](https://linux-hardware.org/?probe=691838cd8c) | Aug 09, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| MSI           | 970A-G43                    | [68384da884](https://linux-hardware.org/?probe=68384da884) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| Gigabyte      | H81M-S2H                    | [247f361473](https://linux-hardware.org/?probe=247f361473) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Gigabyte      | H81M-S2H                    | [f74b524df1](https://linux-hardware.org/?probe=f74b524df1) | Aug 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [cc7ae6c4e9](https://linux-hardware.org/?probe=cc7ae6c4e9) | Aug 04, 2023 |
| Gigabyte      | B450 GAMING X               | [bb292f568a](https://linux-hardware.org/?probe=bb292f568a) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B760-A GAMING ... | [f629b6e16e](https://linux-hardware.org/?probe=f629b6e16e) | Aug 03, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [04f8c42dba](https://linux-hardware.org/?probe=04f8c42dba) | Aug 02, 2023 |
| Supermicro    | X9DAi                       | [d7390704d8](https://linux-hardware.org/?probe=d7390704d8) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| Gigabyte      | H81M-S2H                    | [0e5d30b504](https://linux-hardware.org/?probe=0e5d30b504) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| HP            | 3398                        | [c271d5d40e](https://linux-hardware.org/?probe=c271d5d40e) | Jul 31, 2023 |
| MSI           | H81M-P33                    | [d5cb55a484](https://linux-hardware.org/?probe=d5cb55a484) | Jul 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [07a919f178](https://linux-hardware.org/?probe=07a919f178) | Jul 31, 2023 |
| Dell          | 0CU409                      | [7b665ec8f2](https://linux-hardware.org/?probe=7b665ec8f2) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b75ad8b2c](https://linux-hardware.org/?probe=2b75ad8b2c) | Jul 30, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [2ba45b1cfa](https://linux-hardware.org/?probe=2ba45b1cfa) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [fecdf7e593](https://linux-hardware.org/?probe=fecdf7e593) | Jul 29, 2023 |
| Dell          | 0PU052                      | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [4895ec9de1](https://linux-hardware.org/?probe=4895ec9de1) | Jul 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| ASRock        | B450M Steel Legend          | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| MSI           | A68HM-E33 V2                | [858b41037e](https://linux-hardware.org/?probe=858b41037e) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [5be0e1a212](https://linux-hardware.org/?probe=5be0e1a212) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [4c4109b8f3](https://linux-hardware.org/?probe=4c4109b8f3) | Jul 23, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [d89bdeec87](https://linux-hardware.org/?probe=d89bdeec87) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [5072be5d0f](https://linux-hardware.org/?probe=5072be5d0f) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| Gigabyte      | H81M-DS2V                   | [f27670217e](https://linux-hardware.org/?probe=f27670217e) | Jul 22, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [9f52ae219f](https://linux-hardware.org/?probe=9f52ae219f) | Jul 22, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| MSI           | Z97 PC Mate                 | [a131a7a5fb](https://linux-hardware.org/?probe=a131a7a5fb) | Jul 21, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [6b8d5cb0c1](https://linux-hardware.org/?probe=6b8d5cb0c1) | Jul 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [1ee2e5b63d](https://linux-hardware.org/?probe=1ee2e5b63d) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [db1e3d03e2](https://linux-hardware.org/?probe=db1e3d03e2) | Jul 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [4dacb4cf51](https://linux-hardware.org/?probe=4dacb4cf51) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| Dell          | 073MMW A03                  | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASRock        | A320M-HDV R3.0              | [8e41b4b86d](https://linux-hardware.org/?probe=8e41b4b86d) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | [dc3bdab530](https://linux-hardware.org/?probe=dc3bdab530) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [2b9ee1f8b7](https://linux-hardware.org/?probe=2b9ee1f8b7) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | [fc3514e9a6](https://linux-hardware.org/?probe=fc3514e9a6) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| ASUSTek       | P5E-V HDMI                  | [460e520a69](https://linux-hardware.org/?probe=460e520a69) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f8ffcb4828](https://linux-hardware.org/?probe=f8ffcb4828) | Jul 12, 2023 |
| ASUSTek       | A88XM-E                     | [e951c1d4f4](https://linux-hardware.org/?probe=e951c1d4f4) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [db34bf69af](https://linux-hardware.org/?probe=db34bf69af) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [059cda8a87](https://linux-hardware.org/?probe=059cda8a87) | Jul 11, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [59c50a4a34](https://linux-hardware.org/?probe=59c50a4a34) | Jul 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [0b6dcc1ea9](https://linux-hardware.org/?probe=0b6dcc1ea9) | Jul 09, 2023 |
| Unknown       | Unknown                     | [26896deb1e](https://linux-hardware.org/?probe=26896deb1e) | Jul 09, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | [84e16d3238](https://linux-hardware.org/?probe=84e16d3238) | Jul 09, 2023 |
| Dell          | 01TKCC A01                  | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Acer          | Nitro N50-620               | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [703f0e9012](https://linux-hardware.org/?probe=703f0e9012) | Jul 08, 2023 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [53d1debf85](https://linux-hardware.org/?probe=53d1debf85) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| Lenovo        | IdeaCentre B320             | [58bb7cf40a](https://linux-hardware.org/?probe=58bb7cf40a) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [9a6e78196d](https://linux-hardware.org/?probe=9a6e78196d) | Jul 06, 2023 |
| HP            | 3398                        | [3124ceac21](https://linux-hardware.org/?probe=3124ceac21) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Gigabyte      | H110-D3A-CF                 | [bd9c7a22d6](https://linux-hardware.org/?probe=bd9c7a22d6) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [da18aba906](https://linux-hardware.org/?probe=da18aba906) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [f9688a073f](https://linux-hardware.org/?probe=f9688a073f) | Jul 04, 2023 |
| Apple         | Mac-F4208DA9 PVT            | [6c2cdc1c76](https://linux-hardware.org/?probe=6c2cdc1c76) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [ed7caf91c0](https://linux-hardware.org/?probe=ed7caf91c0) | Jul 03, 2023 |
| Acer          | Aspire M3910                | [837d0f7852](https://linux-hardware.org/?probe=837d0f7852) | Jul 03, 2023 |
| Gigabyte      | H81M-S2H                    | [cf3da29bba](https://linux-hardware.org/?probe=cf3da29bba) | Jul 03, 2023 |
| ASUSTek       | WS X299 PRO_SE              | [d31cedc2ad](https://linux-hardware.org/?probe=d31cedc2ad) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [1b82430294](https://linux-hardware.org/?probe=1b82430294) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| Gigabyte      | B85-HD3                     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d9b6645cae](https://linux-hardware.org/?probe=d9b6645cae) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dea1298c2e](https://linux-hardware.org/?probe=dea1298c2e) | Jul 01, 2023 |
| Intel         | B85 V5.56                   | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Intel         | X99H                        | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Gigabyte      | H81M-S2H                    | [fe8b1af179](https://linux-hardware.org/?probe=fe8b1af179) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | [e1ed0643fb](https://linux-hardware.org/?probe=e1ed0643fb) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | [0e98c1f04a](https://linux-hardware.org/?probe=0e98c1f04a) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [ddb283952b](https://linux-hardware.org/?probe=ddb283952b) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| Gigabyte      | H81M-S2H                    | [9cb1b45a65](https://linux-hardware.org/?probe=9cb1b45a65) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| Dell          | 0P01GV A03                  | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| HP            | 859B                        | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| Unknown       | Unknown                     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| ASRock        | A320M-HDV R3.0              | [a9cd7361e6](https://linux-hardware.org/?probe=a9cd7361e6) | Jun 23, 2023 |
| ASRock        | Z87M Pro4                   | [762b33c8e7](https://linux-hardware.org/?probe=762b33c8e7) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [184b19f00c](https://linux-hardware.org/?probe=184b19f00c) | Jun 23, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | H81M-S2H                    | [36f8057a1d](https://linux-hardware.org/?probe=36f8057a1d) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| AZW           | GTi                         | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| Dell          | 0YXT71 A01                  | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [160f6f4afb](https://linux-hardware.org/?probe=160f6f4afb) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [3d5cabad57](https://linux-hardware.org/?probe=3d5cabad57) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| ASUSTek       | A88XM-E                     | [1302a62eeb](https://linux-hardware.org/?probe=1302a62eeb) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Unknown       | Unknown                     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| Gigabyte      | H81M-S2H                    | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| Dell          | 0NNNCT A01                  | [1a1e7426a3](https://linux-hardware.org/?probe=1a1e7426a3) | Jun 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| ASRock        | H510M-HDV                   | [27ca3c6650](https://linux-hardware.org/?probe=27ca3c6650) | May 27, 2023 |
| ASUSTek       | Z170M-PLUS                  | [0577b02521](https://linux-hardware.org/?probe=0577b02521) | May 27, 2023 |
| ASRock        | H510M-HDV                   | [c6315a675c](https://linux-hardware.org/?probe=c6315a675c) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 8437                        | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | 970A-DS3P                   | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| SYWZ          | S200 Series                 | [6878838d6f](https://linux-hardware.org/?probe=6878838d6f) | May 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| Samsung       | DeskTop System              | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| ASRock        | X470 Taichi                 | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| HP            | 3398                        | [a49cbc797b](https://linux-hardware.org/?probe=a49cbc797b) | May 18, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| MSI           | A68HM-E33 V2                | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2d1acb409a](https://linux-hardware.org/?probe=2d1acb409a) | May 13, 2023 |
| ASUSTek       | M5A78L/USB3                 | [edc8069ae1](https://linux-hardware.org/?probe=edc8069ae1) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ec1f5e50b8](https://linux-hardware.org/?probe=ec1f5e50b8) | May 11, 2023 |
| Biostar       | H110MHV3                    | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| ASUSTek       | P8B75-M LE                  | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| ASUSTek       | Z170-K                      | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| MSI           | MS-7502 Fab D               | [ca5881d77e](https://linux-hardware.org/?probe=ca5881d77e) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| MSI           | B350 PC MATE                | [cabb24b0e7](https://linux-hardware.org/?probe=cabb24b0e7) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| ASUSTek       | M5A99X EVO                  | [f5499886e9](https://linux-hardware.org/?probe=f5499886e9) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [369bf3dc68](https://linux-hardware.org/?probe=369bf3dc68) | May 07, 2023 |
| Acer          | Predator PO3-620            | [9ef46f7f3e](https://linux-hardware.org/?probe=9ef46f7f3e) | May 06, 2023 |
| MSI           | MS-7502 Fab D               | [9b80139aca](https://linux-hardware.org/?probe=9b80139aca) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [64aa7fb49b](https://linux-hardware.org/?probe=64aa7fb49b) | May 05, 2023 |
| HP            | 304Ah                       | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| HP            | 21EF                        | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |
| HP            | 1589                        | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [e8c596445b](https://linux-hardware.org/?probe=e8c596445b) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [372a18076a](https://linux-hardware.org/?probe=372a18076a) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| Gigabyte      | H310M H x.x                 | [7996838ce9](https://linux-hardware.org/?probe=7996838ce9) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Apple         | Mac-F221BEC8                | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| ASRock        | B450M Pro4                  | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Acer          | Aspire M3970                | [87a55abfa7](https://linux-hardware.org/?probe=87a55abfa7) | May 01, 2023 |
| ASUSTek       | H81-PLUS                    | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| HP            | 1998                        | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| Gigabyte      | H410M H V2                  | [8a23a0fef0](https://linux-hardware.org/?probe=8a23a0fef0) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [c8fe6ab042](https://linux-hardware.org/?probe=c8fe6ab042) | Apr 28, 2023 |
| ASRock        | B450 Steel Legend           | [9130280424](https://linux-hardware.org/?probe=9130280424) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| HP            | 1589                        | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Apple         | Mac-F221BEC8                | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| Intel         | DQ67OW AAG12528-307         | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| HP            | 18E9                        | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | H61M-S2-B3                  | [cd95f8ec71](https://linux-hardware.org/?probe=cd95f8ec71) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Intel         | HM570                       | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | [70d478e2eb](https://linux-hardware.org/?probe=70d478e2eb) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | [2931b721a3](https://linux-hardware.org/?probe=2931b721a3) | Apr 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| MSI           | A88XM-E35                   | [c26812e2e1](https://linux-hardware.org/?probe=c26812e2e1) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| ASUSTek       | H81M-K                      | [5aa26aea52](https://linux-hardware.org/?probe=5aa26aea52) | Apr 22, 2023 |
| HP            | 18E5                        | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| HP            | ProLiant MicroServer        | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Acer          | Aspire M3970                | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| Unknown       | Unknown                     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [ff7225c921](https://linux-hardware.org/?probe=ff7225c921) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [a70cdf4848](https://linux-hardware.org/?probe=a70cdf4848) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c5ceac2597](https://linux-hardware.org/?probe=c5ceac2597) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| AZW           | Speed S                     | [7cf5e54f5b](https://linux-hardware.org/?probe=7cf5e54f5b) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | [44222bc590](https://linux-hardware.org/?probe=44222bc590) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | [592c412bd9](https://linux-hardware.org/?probe=592c412bd9) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [00ee6cd73f](https://linux-hardware.org/?probe=00ee6cd73f) | Apr 15, 2023 |
| Acer          | Aspire M3970                | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| Dell          | 00V62H A00                  | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Shuttle       | FH67                        | [daa2f39981](https://linux-hardware.org/?probe=daa2f39981) | Apr 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| HP            | 805F                        | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Dell          | 0PU052                      | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| ASUSTek       | A88XM-A                     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| Acer          | Aspire XC-895 V:1.0         | [ef0fbbe0aa](https://linux-hardware.org/?probe=ef0fbbe0aa) | Apr 08, 2023 |
| Dell          | 0KRC95 A01                  | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Dell          | 0P01GV A03                  | [5dc44169d0](https://linux-hardware.org/?probe=5dc44169d0) | Apr 07, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [a0584206ea](https://linux-hardware.org/?probe=a0584206ea) | Apr 06, 2023 |
| Dell          | 0HN7XN A01                  | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| HP            | 0A9Ch                       | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [b5740f3323](https://linux-hardware.org/?probe=b5740f3323) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b7068fce05](https://linux-hardware.org/?probe=b7068fce05) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS M                | [ed948ed552](https://linux-hardware.org/?probe=ed948ed552) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Pegatron      | JESSE                       | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fb4f4da720](https://linux-hardware.org/?probe=fb4f4da720) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [77b1f3bc3e](https://linux-hardware.org/?probe=77b1f3bc3e) | Apr 02, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| AZW           | U59                         | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [16e982e5cb](https://linux-hardware.org/?probe=16e982e5cb) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Acer          | Predator PO3-610            | [c5fd8fda48](https://linux-hardware.org/?probe=c5fd8fda48) | Apr 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| Acer          | H57M01                      | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [1146b0ebfc](https://linux-hardware.org/?probe=1146b0ebfc) | Apr 01, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [49917003da](https://linux-hardware.org/?probe=49917003da) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [3bf5fd0cfd](https://linux-hardware.org/?probe=3bf5fd0cfd) | Mar 30, 2023 |
| IP3 Tech      | IB8                         | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| ASRock        | X399 Taichi                 | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a37020a71d](https://linux-hardware.org/?probe=a37020a71d) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| HP            | 1998                        | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| Gigabyte      | GA-970A-DS3                 | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [d32441b2c3](https://linux-hardware.org/?probe=d32441b2c3) | Mar 21, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| HP            | 3397                        | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [06d89bd973](https://linux-hardware.org/?probe=06d89bd973) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Unknown       | Unknown                     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASUSTek       | P5W DH Deluxe               | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Google        | Teemo                       | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| Dell          | 02M8NY A02                  | [b3c31072bb](https://linux-hardware.org/?probe=b3c31072bb) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | PRIME X470-PRO              | [686fb235ce](https://linux-hardware.org/?probe=686fb235ce) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Dell          | 0DFRFW A01                  | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Gigabyte      | H170M-D3H-CF                | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | A520M H                     | [d841d9761a](https://linux-hardware.org/?probe=d841d9761a) | Mar 11, 2023 |
| Dell          | 08NPPY A00                  | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [382901fcd7](https://linux-hardware.org/?probe=382901fcd7) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [2f86f93df5](https://linux-hardware.org/?probe=2f86f93df5) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Gigabyte      | A520M H                     | [9bcfd20d80](https://linux-hardware.org/?probe=9bcfd20d80) | Mar 10, 2023 |
| Foxconn       | ETON                        | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [519310d05f](https://linux-hardware.org/?probe=519310d05f) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Foxconn       | ETON                        | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | [30b6242c17](https://linux-hardware.org/?probe=30b6242c17) | Mar 07, 2023 |
| Gigabyte      | A520M DS3H                  | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 481      | 13.25%  |
| Ubuntu 18.04                 | 279      | 7.69%   |
| Ubuntu 22.04                 | 224      | 6.17%   |
| Arch Rolling                 | 97       | 2.67%   |
| Zorin 16                     | 93       | 2.56%   |
| Debian 11                    | 73       | 2.01%   |
| ArcoLinux Rolling            | 73       | 2.01%   |
| OpenMandriva 4.2             | 68       | 1.87%   |
| Pop!_OS 22.04                | 66       | 1.82%   |
| KDE neon 20.04               | 56       | 1.54%   |
| OpenMandriva 4.3             | 54       | 1.49%   |
| Linux Mint 20.3              | 54       | 1.49%   |
| Manjaro                      | 53       | 1.46%   |
| Pop!_OS 20.04                | 48       | 1.32%   |
| Linux Mint 20.2              | 46       | 1.27%   |
| Pop!_OS 21.04                | 45       | 1.24%   |
| Linux Mint 21.1              | 43       | 1.18%   |
| Pop!_OS 20.10                | 41       | 1.13%   |
| Zorin 15                     | 37       | 1.02%   |
| Ubuntu 19.04                 | 37       | 1.02%   |
| Linux Mint 19.3              | 37       | 1.02%   |
| Arch                         | 36       | 0.99%   |
| Xubuntu 20.04                | 35       | 0.96%   |
| OpenMandriva 23.01           | 35       | 0.96%   |
| Linux Mint 20.1              | 35       | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 34       | 0.94%   |
| Linux Mint 21.2              | 34       | 0.94%   |
| Ubuntu 19.10                 | 33       | 0.91%   |
| OpenMandriva 23.03           | 33       | 0.91%   |
| Ubuntu 21.10                 | 31       | 0.85%   |
| Kubuntu 20.04                | 29       | 0.8%    |
| Debian 12                    | 29       | 0.8%    |
| Fedora 38                    | 27       | 0.74%   |
| Fedora 36                    | 27       | 0.74%   |
| Linux Mint 20                | 26       | 0.72%   |
| KDE neon 22.04               | 26       | 0.72%   |
| Ubuntu 20.10                 | 25       | 0.69%   |
| OpenMandriva 23.08           | 25       | 0.69%   |
| Debian 10                    | 25       | 0.69%   |
| Ubuntu 23.04                 | 24       | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1155     | 33.82%  |
| Linux Mint    | 313      | 9.17%   |
| OpenMandriva  | 240      | 7.03%   |
| Pop!_OS       | 212      | 6.21%   |
| Fedora        | 176      | 5.15%   |
| Debian        | 152      | 4.45%   |
| Zorin         | 134      | 3.92%   |
| Arch          | 133      | 3.89%   |
| Manjaro       | 91       | 2.66%   |
| Kubuntu       | 89       | 2.61%   |
| KDE neon      | 85       | 2.49%   |
| ArcoLinux     | 73       | 2.14%   |
| Xubuntu       | 63       | 1.84%   |
| openSUSE      | 45       | 1.32%   |
| Gentoo        | 45       | 1.32%   |
| ROSA          | 42       | 1.23%   |
| Elementary    | 23       | 0.67%   |
| Clear Linux   | 23       | 0.67%   |
| Ubuntu Unity  | 22       | 0.64%   |
| Ubuntu MATE   | 22       | 0.64%   |
| Nobara        | 22       | 0.64%   |
| Endless       | 19       | 0.56%   |
| Kali          | 16       | 0.47%   |
| Lubuntu       | 14       | 0.41%   |
| CentOS        | 14       | 0.41%   |
| BlackPanther  | 14       | 0.41%   |
| LMDE          | 12       | 0.35%   |
| Slackware     | 11       | 0.32%   |
| MX            | 10       | 0.29%   |
| EndeavourOS   | 10       | 0.29%   |
| Garuda Linux  | 9        | 0.26%   |
| SteamOS       | 8        | 0.23%   |
| RHEL          | 8        | 0.23%   |
| NixOS         | 7        | 0.2%    |
| Xero          | 5        | 0.15%   |
| Reborn OS     | 5        | 0.15%   |
| Peppermint    | 5        | 0.15%   |
| ChimeraOS     | 5        | 0.15%   |
| UbuntuDDE     | 4        | 0.12%   |
| Ubuntu Budgie | 4        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 68       | 1.64%   |
| 5.4.0-42-generic         | 65       | 1.56%   |
| 5.16.7-desktop-1omv4003  | 51       | 1.23%   |
| 5.4.0-48-generic         | 39       | 0.94%   |
| 6.1.1-desktop-1omv2290   | 33       | 0.79%   |
| 6.2.6-desktop-1omv2390   | 32       | 0.77%   |
| 5.4.0-52-generic         | 32       | 0.77%   |
| 5.4.0-29-generic         | 31       | 0.75%   |
| 5.4.0-26-generic         | 30       | 0.72%   |
| 5.15.0-56-generic        | 29       | 0.7%    |
| 5.3.0-28-generic         | 27       | 0.65%   |
| 5.4.0-37-generic         | 26       | 0.63%   |
| 5.15.0-52-generic        | 24       | 0.58%   |
| 5.15.0-46-generic        | 24       | 0.58%   |
| 5.3.0-40-generic         | 23       | 0.55%   |
| 5.4.0-66-generic         | 22       | 0.53%   |
| 5.4.0-65-generic         | 22       | 0.53%   |
| 5.15.0-58-generic        | 22       | 0.53%   |
| 6.4.11-desktop-1omv2390  | 21       | 0.51%   |
| 5.4.0-47-generic         | 21       | 0.51%   |
| 5.4.0-40-generic         | 21       | 0.51%   |
| 5.4.0-74-generic         | 20       | 0.48%   |
| 5.4.0-33-generic         | 20       | 0.48%   |
| 5.13.0-39-generic        | 20       | 0.48%   |
| 5.8.0-7630-generic       | 19       | 0.46%   |
| 5.13.0-7614-generic      | 19       | 0.46%   |
| 5.11.0-7620-generic      | 19       | 0.46%   |
| 6.2.0-36-generic         | 18       | 0.43%   |
| 5.4.0-58-generic         | 18       | 0.43%   |
| 5.4.0-54-generic         | 18       | 0.43%   |
| 5.3.0-46-generic         | 18       | 0.43%   |
| 5.11.0-40-generic        | 18       | 0.43%   |
| 5.4.0-72-generic         | 17       | 0.41%   |
| 5.15.0-48-generic        | 17       | 0.41%   |
| 5.11.0-25-generic        | 17       | 0.41%   |
| 5.4.0-91-generic         | 16       | 0.39%   |
| 5.4.0-7634-generic       | 16       | 0.39%   |
| 5.15.0-69-generic        | 16       | 0.39%   |
| 5.15.0-53-generic        | 16       | 0.39%   |
| 6.2.6-76060206-generic   | 15       | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 667      | 17.43%  |
| 5.15.0  | 325      | 8.49%   |
| 4.15.0  | 193      | 5.04%   |
| 5.11.0  | 170      | 4.44%   |
| 5.8.0   | 162      | 4.23%   |
| 5.13.0  | 157      | 4.1%    |
| 5.3.0   | 145      | 3.79%   |
| 6.2.0   | 111      | 2.9%    |
| 5.19.0  | 104      | 2.72%   |
| 5.0.0   | 90       | 2.35%   |
| 5.10.0  | 82       | 2.14%   |
| 4.18.0  | 74       | 1.93%   |
| 5.10.14 | 68       | 1.78%   |
| 5.16.7  | 51       | 1.33%   |
| 6.2.6   | 49       | 1.28%   |
| 6.1.0   | 39       | 1.02%   |
| 6.1.1   | 37       | 0.97%   |
| 4.19.0  | 26       | 0.68%   |
| 6.4.11  | 23       | 0.6%    |
| 6.5.0   | 21       | 0.55%   |
| 6.5.6   | 17       | 0.44%   |
| 5.17.5  | 16       | 0.42%   |
| 5.14.0  | 16       | 0.42%   |
| 6.5.5   | 15       | 0.39%   |
| 4.9.60  | 14       | 0.37%   |
| 6.6.2   | 12       | 0.31%   |
| 5.9.16  | 12       | 0.31%   |
| 5.18.0  | 12       | 0.31%   |
| 6.0.0   | 11       | 0.29%   |
| 4.4.0   | 11       | 0.29%   |
| 6.0.12  | 10       | 0.26%   |
| 5.18.12 | 10       | 0.26%   |
| 5.16.13 | 10       | 0.26%   |
| 4.18.16 | 10       | 0.26%   |
| 6.6.7   | 9        | 0.24%   |
| 5.19.5  | 9        | 0.24%   |
| 4.9.20  | 9        | 0.24%   |
| 6.3.9   | 8        | 0.21%   |
| 6.2.12  | 8        | 0.21%   |
| 6.0.8   | 8        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 710      | 18.91%  |
| 5.15    | 402      | 10.71%  |
| 5.10    | 215      | 5.73%   |
| 5.11    | 204      | 5.43%   |
| 6.2     | 201      | 5.35%   |
| 5.8     | 201      | 5.35%   |
| 4.15    | 194      | 5.17%   |
| 5.13    | 191      | 5.09%   |
| 5.3     | 169      | 4.5%    |
| 5.19    | 146      | 3.89%   |
| 6.1     | 133      | 3.54%   |
| 5.0     | 93       | 2.48%   |
| 5.16    | 86       | 2.29%   |
| 4.18    | 85       | 2.26%   |
| 6.5     | 75       | 2%      |
| 6.4     | 63       | 1.68%   |
| 6.0     | 57       | 1.52%   |
| 5.18    | 48       | 1.28%   |
| 6.6     | 46       | 1.23%   |
| 5.17    | 45       | 1.2%    |
| 5.14    | 45       | 1.2%    |
| 6.3     | 43       | 1.15%   |
| 5.9     | 42       | 1.12%   |
| 4.9     | 38       | 1.01%   |
| 5.12    | 37       | 0.99%   |
| 4.19    | 37       | 0.99%   |
| 5.6     | 36       | 0.96%   |
| 5.7     | 32       | 0.85%   |
| 5.5     | 19       | 0.51%   |
| 4.4     | 13       | 0.35%   |
| 5.2     | 12       | 0.32%   |
| 5.1     | 7        | 0.19%   |
| 4.1     | 7        | 0.19%   |
| 3.10    | 6        | 0.16%   |
| 4.14    | 4        | 0.11%   |
| 4.13    | 4        | 0.11%   |
| 4.20    | 2        | 0.05%   |
| 3.13    | 2        | 0.05%   |
| 4.8     | 1        | 0.03%   |
| 4.12    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3188     | 97.94%  |
| i686    | 63       | 1.94%   |
| armv7l  | 2        | 0.06%   |
| riscv64 | 1        | 0.03%   |
| aarch64 | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 1507     | 43.9%   |
| KDE5             | 614      | 17.89%  |
| Unknown          | 445      | 12.96%  |
| X-Cinnamon       | 264      | 7.69%   |
| XFCE             | 219      | 6.38%   |
| KDE              | 85       | 2.48%   |
| MATE             | 78       | 2.27%   |
| Cinnamon         | 41       | 1.19%   |
| Unity            | 23       | 0.67%   |
| Pantheon         | 22       | 0.64%   |
| KDE4             | 22       | 0.64%   |
| LXQt             | 18       | 0.52%   |
| LXDE             | 16       | 0.47%   |
| i3               | 12       | 0.35%   |
| GNOME Flashback  | 10       | 0.29%   |
| Deepin           | 9        | 0.26%   |
| sway             | 7        | 0.2%    |
| Budgie           | 6        | 0.17%   |
| openbox          | 4        | 0.12%   |
| lightdm-xsession | 4        | 0.12%   |
| Hyprland         | 4        | 0.12%   |
| GNOME Classic    | 3        | 0.09%   |
| awesome          | 3        | 0.09%   |
| xmonad           | 2        | 0.06%   |
| qtile            | 2        | 0.06%   |
| icewm            | 2        | 0.06%   |
| chadwm           | 2        | 0.06%   |
| bspwm            | 2        | 0.06%   |
| xubuntu          | 1        | 0.03%   |
| WindowMaker      | 1        | 0.03%   |
| mwm              | 1        | 0.03%   |
| LeftWM           | 1        | 0.03%   |
| enlightenment    | 1        | 0.03%   |
| DWM              | 1        | 0.03%   |
| Cutefish         | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2584     | 76.68%  |
| Wayland | 467      | 13.86%  |
| Unknown | 201      | 5.96%   |
| Tty     | 117      | 3.47%   |
| Web     | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1867     | 54.69%  |
| SDDM    | 523      | 15.32%  |
| GDM3    | 369      | 10.81%  |
| LightDM | 270      | 7.91%   |
| GDM     | 264      | 7.73%   |
| TDM     | 80       | 2.34%   |
| KDM     | 20       | 0.59%   |
| XDM     | 8        | 0.23%   |
| SLiM    | 4        | 0.12%   |
| LXDM    | 4        | 0.12%   |
| Ly      | 2        | 0.06%   |
| XINIT   | 1        | 0.03%   |
| MDM     | 1        | 0.03%   |
| GREETD  | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_GB          | 2458     | 73.37%  |
| en_US          | 395      | 11.79%  |
| Unknown        | 364      | 10.87%  |
| C              | 54       | 1.61%   |
| pl_PL          | 20       | 0.6%    |
| ru_RU          | 7        | 0.21%   |
| POSIX          | 7        | 0.21%   |
| en_IE          | 6        | 0.18%   |
| C.UTF8         | 4        | 0.12%   |
| ro_RO          | 3        | 0.09%   |
| lt_LT          | 3        | 0.09%   |
| en_CA          | 3        | 0.09%   |
| de_DE          | 3        | 0.09%   |
| nl_NL          | 2        | 0.06%   |
| hu_HU          | 2        | 0.06%   |
| en_ZA          | 2        | 0.06%   |
| zh_CN          | 1        | 0.03%   |
| wbp_AU         | 1        | 0.03%   |
| us             | 1        | 0.03%   |
| uk_UA          | 1        | 0.03%   |
| sk_SK          | 1        | 0.03%   |
| pt_PT          | 1        | 0.03%   |
| pt_BR          | 1        | 0.03%   |
| it_IT          | 1        | 0.03%   |
| fr_FR          | 1        | 0.03%   |
| fi_FI          | 1        | 0.03%   |
| et_EE          | 1        | 0.03%   |
| en_US.utf-8    | 1        | 0.03%   |
| en_SG          | 1        | 0.03%   |
| en_IN          | 1        | 0.03%   |
| en_GB.iso88591 | 1        | 0.03%   |
| cs_CZ          | 1        | 0.03%   |
| bg_BG          | 1        | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1941     | 58.17%  |
| EFI  | 1396     | 41.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 2503     | 74.12%  |
| Btrfs    | 302      | 8.94%   |
| Overlay  | 242      | 7.17%   |
| Unknown  | 111      | 3.29%   |
| Tmpfs    | 103      | 3.05%   |
| Xfs      | 56       | 1.66%   |
| Zfs      | 29       | 0.86%   |
| Ext2     | 12       | 0.36%   |
| Ext3     | 8        | 0.24%   |
| F2fs     | 5        | 0.15%   |
| Aufs     | 2        | 0.06%   |
| XXXX     | 1        | 0.03%   |
| Rootfs   | 1        | 0.03%   |
| Reiserfs | 1        | 0.03%   |
| ExX4     | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1880     | 56.07%  |
| GPT     | 1167     | 34.8%   |
| MBR     | 306      | 9.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2654     | 79.04%  |
| Yes       | 704      | 20.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2281     | 68.44%  |
| Yes       | 1052     | 31.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 860      | 26.44%  |
| Gigabyte Technology                  | 585      | 17.98%  |
| MSI                                  | 389      | 11.96%  |
| Dell                                 | 378      | 11.62%  |
| ASRock                               | 240      | 7.38%   |
| Hewlett-Packard                      | 227      | 6.98%   |
| Lenovo                               | 108      | 3.32%   |
| Intel                                | 75       | 2.31%   |
| Acer                                 | 69       | 2.12%   |
| Foxconn                              | 35       | 1.08%   |
| Unknown                              | 30       | 0.92%   |
| Fujitsu                              | 29       | 0.89%   |
| Pegatron                             | 25       | 0.77%   |
| Apple                                | 22       | 0.68%   |
| Biostar                              | 19       | 0.58%   |
| Packard Bell                         | 16       | 0.49%   |
| Medion                               | 14       | 0.43%   |
| AZW                                  | 14       | 0.43%   |
| Alienware                            | 10       | 0.31%   |
| Shuttle                              | 8        | 0.25%   |
| Fujitsu Siemens                      | 8        | 0.25%   |
| ECS                                  | 7        | 0.22%   |
| Supermicro                           | 6        | 0.18%   |
| Inventec                             | 6        | 0.18%   |
| AMI                                  | 5        | 0.15%   |
| TYAN Computer                        | 4        | 0.12%   |
| Shenzhen Meigao Electronic Equipment | 4        | 0.12%   |
| OEM_MB                               | 3        | 0.09%   |
| Huanan                               | 3        | 0.09%   |
| Wistron                              | 2        | 0.06%   |
| Trigkey                              | 2        | 0.06%   |
| SYWZ                                 | 2        | 0.06%   |
| Seeed Studio                         | 2        | 0.06%   |
| MiTAC                                | 2        | 0.06%   |
| Google                               | 2        | 0.06%   |
| EVGA                                 | 2        | 0.06%   |
| Entroware                            | 2        | 0.06%   |
| BESSTAR Tech                         | 2        | 0.06%   |
| ASRockRack                           | 2        | 0.06%   |
| Advent                               | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 83       | 2.55%   |
| Dell OptiPlex 7010               | 37       | 1.14%   |
| Unknown                          | 31       | 0.95%   |
| MSI MS-7C02                      | 30       | 0.92%   |
| ASUS M5A78L-M/USB3               | 23       | 0.71%   |
| MSI MS-7C37                      | 22       | 0.68%   |
| ASUS TUF Gaming X570-PLUS        | 22       | 0.68%   |
| Dell OptiPlex 780                | 21       | 0.65%   |
| Dell OptiPlex 755                | 21       | 0.65%   |
| ASUS ROG STRIX B450-F GAMING     | 20       | 0.61%   |
| Dell OptiPlex 790                | 18       | 0.55%   |
| ASUS PRIME A320M-K               | 17       | 0.52%   |
| Gigabyte 970A-DS3P               | 16       | 0.49%   |
| MSI MS-7C91                      | 15       | 0.46%   |
| Gigabyte X570 AORUS ELITE        | 15       | 0.46%   |
| ASUS ROG STRIX B550-F GAMING     | 15       | 0.46%   |
| MSI MS-7B79                      | 13       | 0.4%    |
| Dell OptiPlex 3020               | 13       | 0.4%    |
| Gigabyte GA-78LMT-USB3           | 12       | 0.37%   |
| Gigabyte B450M DS3H              | 12       | 0.37%   |
| ASUS PRIME B450-PLUS             | 12       | 0.37%   |
| HP ProLiant MicroServer          | 11       | 0.34%   |
| HP EliteDesk 800 G1 SFF          | 11       | 0.34%   |
| Gigabyte A320M-S2H               | 11       | 0.34%   |
| ASUS ROG CROSSHAIR VIII HERO     | 11       | 0.34%   |
| MSI MS-7B85                      | 10       | 0.31%   |
| MSI MS-7A34                      | 10       | 0.31%   |
| MSI MS-7721                      | 10       | 0.31%   |
| MSI MS-7693                      | 10       | 0.31%   |
| Gigabyte GA-78LMT-USB3 6.0       | 10       | 0.31%   |
| Dell Vostro 200                  | 10       | 0.31%   |
| Dell OptiPlex 3050               | 10       | 0.31%   |
| ASUS ROG STRIX X570-F GAMING     | 10       | 0.31%   |
| MSI MS-7B89                      | 9        | 0.28%   |
| MSI MS-7758                      | 9        | 0.28%   |
| Gigabyte H61M-DS2 DVI            | 9        | 0.28%   |
| Gigabyte B550M DS3H              | 9        | 0.28%   |
| Dell Precision WorkStation T3500 | 9        | 0.28%   |
| Dell OptiPlex 9020               | 9        | 0.28%   |
| Dell OptiPlex 7020               | 9        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 219      | 6.73%   |
| ASUS ROG               | 163      | 5.01%   |
| ASUS PRIME             | 147      | 4.52%   |
| ASUS All               | 83       | 2.55%   |
| Lenovo ThinkCentre     | 72       | 2.21%   |
| HP Compaq              | 72       | 2.21%   |
| Dell Precision         | 59       | 1.81%   |
| ASUS TUF               | 55       | 1.69%   |
| Acer Aspire            | 48       | 1.48%   |
| Gigabyte X570          | 42       | 1.29%   |
| Dell Inspiron          | 35       | 1.08%   |
| ASUS M5A78L-M          | 33       | 1.01%   |
| Unknown                | 31       | 0.95%   |
| MSI MS-7C02            | 30       | 0.92%   |
| HP EliteDesk           | 30       | 0.92%   |
| Gigabyte GA-78LMT-USB3 | 27       | 0.83%   |
| Dell Vostro            | 25       | 0.77%   |
| MSI MS-7C37            | 22       | 0.68%   |
| HP ProLiant            | 22       | 0.68%   |
| Gigabyte B450          | 22       | 0.68%   |
| Fujitsu ESPRIMO        | 21       | 0.65%   |
| HP ProDesk             | 20       | 0.61%   |
| ASUS SABERTOOTH        | 19       | 0.58%   |
| Gigabyte Z390          | 18       | 0.55%   |
| Gigabyte B550          | 17       | 0.52%   |
| Gigabyte B450M         | 17       | 0.52%   |
| Gigabyte 970A-DS3P     | 17       | 0.52%   |
| Gigabyte B550M         | 16       | 0.49%   |
| ASUS Maximus           | 16       | 0.49%   |
| MSI MS-7C91            | 15       | 0.46%   |
| Gigabyte A320M-S2H     | 15       | 0.46%   |
| ASUS P8Z77-V           | 14       | 0.43%   |
| MSI MS-7B79            | 13       | 0.4%    |
| Dell XPS               | 13       | 0.4%    |
| ASRock X570            | 13       | 0.4%    |
| Packard Bell IMEDIA    | 12       | 0.37%   |
| ASUS M5A97             | 12       | 0.37%   |
| ASRock B450M           | 12       | 0.37%   |
| MSI MS-7B85            | 10       | 0.31%   |
| MSI MS-7A34            | 10       | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 343      | 10.54%  |
| 2012    | 306      | 9.41%   |
| 2019    | 271      | 8.33%   |
| 2014    | 252      | 7.75%   |
| 2013    | 252      | 7.75%   |
| 2020    | 234      | 7.19%   |
| 2011    | 225      | 6.92%   |
| 2017    | 212      | 6.52%   |
| 2010    | 190      | 5.84%   |
| 2009    | 154      | 4.73%   |
| 2021    | 137      | 4.21%   |
| 2015    | 129      | 3.97%   |
| 2016    | 121      | 3.72%   |
| 2008    | 113      | 3.47%   |
| 2022    | 105      | 3.23%   |
| 2007    | 101      | 3.1%    |
| 2006    | 46       | 1.41%   |
| 2023    | 30       | 0.92%   |
| 2005    | 19       | 0.58%   |
| 2004    | 6        | 0.18%   |
| Unknown | 3        | 0.09%   |
| 2003    | 2        | 0.06%   |
| 2002    | 2        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3253     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3171     | 97.03%  |
| Enabled  | 97       | 2.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3251     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 895      | 26.79%  |
| 32.01-64.0      | 602      | 18.02%  |
| 8.01-16.0       | 578      | 17.3%   |
| 4.01-8.0        | 450      | 13.47%  |
| 3.01-4.0        | 395      | 11.82%  |
| 64.01-256.0     | 188      | 5.63%   |
| 24.01-32.0      | 90       | 2.69%   |
| 1.01-2.0        | 82       | 2.45%   |
| 2.01-3.0        | 38       | 1.14%   |
| 0.51-1.0        | 16       | 0.48%   |
| More than 256.0 | 6        | 0.18%   |
| 0.01-0.5        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1257     | 33.59%  |
| 2.01-3.0    | 889      | 23.76%  |
| 4.01-8.0    | 573      | 15.31%  |
| 3.01-4.0    | 485      | 12.96%  |
| 0.51-1.0    | 212      | 5.67%   |
| 8.01-16.0   | 205      | 5.48%   |
| 0.01-0.5    | 45       | 1.2%    |
| 16.01-24.0  | 40       | 1.07%   |
| 24.01-32.0  | 17       | 0.45%   |
| 32.01-64.0  | 13       | 0.35%   |
| 64.01-256.0 | 4        | 0.11%   |
| Unknown     | 2        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1166     | 33.87%  |
| 2       | 958      | 27.82%  |
| 3       | 554      | 16.09%  |
| 4       | 346      | 10.05%  |
| 5       | 201      | 5.84%   |
| 6       | 102      | 2.96%   |
| 7       | 38       | 1.1%    |
| 0       | 24       | 0.7%    |
| 8       | 19       | 0.55%   |
| 9       | 10       | 0.29%   |
| 11      | 7        | 0.2%    |
| 10      | 7        | 0.2%    |
| 12      | 5        | 0.15%   |
| 29      | 1        | 0.03%   |
| 25      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 20      | 1        | 0.03%   |
| 13      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1678     | 50.6%   |
| Yes       | 1638     | 49.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3206     | 98.52%  |
| No        | 48       | 1.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1701     | 51.17%  |
| Yes       | 1623     | 48.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2163     | 65.21%  |
| Yes       | 1154     | 34.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| UK      | 3253     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| London              | 200      | 5.48%   |
| Manchester          | 100      | 2.74%   |
| Bristol             | 59       | 1.62%   |
| Birmingham          | 56       | 1.54%   |
| Sheffield           | 51       | 1.4%    |
| Nottingham          | 47       | 1.29%   |
| Glasgow             | 43       | 1.18%   |
| Leeds               | 39       | 1.07%   |
| Edinburgh           | 38       | 1.04%   |
| Liverpool           | 36       | 0.99%   |
| Derby               | 32       | 0.88%   |
| Islington           | 31       | 0.85%   |
| Norwich             | 30       | 0.82%   |
| Reading             | 29       | 0.79%   |
| Croydon             | 29       | 0.79%   |
| Milton Keynes       | 27       | 0.74%   |
| Cardiff             | 26       | 0.71%   |
| Cambridge           | 26       | 0.71%   |
| Southampton         | 25       | 0.69%   |
| Bradford            | 23       | 0.63%   |
| Newcastle upon Tyne | 22       | 0.6%    |
| Stockport           | 20       | 0.55%   |
| Swindon             | 19       | 0.52%   |
| Hackney             | 19       | 0.52%   |
| York                | 18       | 0.49%   |
| Stoke-on-Trent      | 18       | 0.49%   |
| Leicester           | 18       | 0.49%   |
| Sunderland          | 17       | 0.47%   |
| Gloucester          | 17       | 0.47%   |
| Wolverhampton       | 16       | 0.44%   |
| Rotherham           | 16       | 0.44%   |
| Portsmouth          | 16       | 0.44%   |
| Wigan               | 15       | 0.41%   |
| Plymouth            | 15       | 0.41%   |
| Peterborough        | 15       | 0.41%   |
| Gillingham          | 15       | 0.41%   |
| Telford             | 14       | 0.38%   |
| Bolton              | 14       | 0.38%   |
| Barnsley            | 14       | 0.38%   |
| Warrington          | 13       | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1222     | 2212   | 19.23%  |
| WDC                         | 1090     | 2014   | 17.15%  |
| Samsung Electronics         | 933      | 1727   | 14.68%  |
| Crucial                     | 419      | 631    | 6.59%   |
| SanDisk                     | 393      | 593    | 6.18%   |
| Toshiba                     | 334      | 527    | 5.26%   |
| Kingston                    | 310      | 440    | 4.88%   |
| Hitachi                     | 236      | 348    | 3.71%   |
| Phison                      | 111      | 155    | 1.75%   |
| Intel                       | 91       | 155    | 1.43%   |
| China                       | 82       | 109    | 1.29%   |
| Unknown                     | 67       | 111    | 1.05%   |
| A-DATA Technology           | 64       | 92     | 1.01%   |
| OCZ                         | 60       | 70     | 0.94%   |
| Maxtor                      | 56       | 87     | 0.88%   |
| HGST                        | 52       | 77     | 0.82%   |
| Micron/Crucial Technology   | 45       | 70     | 0.71%   |
| Corsair                     | 43       | 59     | 0.68%   |
| Silicon Motion              | 39       | 53     | 0.61%   |
| Phison Electronics          | 39       | 79     | 0.61%   |
| PNY                         | 37       | 48     | 0.58%   |
| SK hynix                    | 29       | 35     | 0.46%   |
| Transcend                   | 24       | 28     | 0.38%   |
| Micron Technology           | 24       | 25     | 0.38%   |
| Integral                    | 24       | 28     | 0.38%   |
| Patriot                     | 21       | 31     | 0.33%   |
| Gigabyte Technology         | 20       | 30     | 0.31%   |
| Netac                       | 18       | 26     | 0.28%   |
| LITEON                      | 18       | 22     | 0.28%   |
| SABRENT                     | 17       | 21     | 0.27%   |
| Kingston Technology Company | 17       | 19     | 0.27%   |
| JMicron Technology          | 17       | 26     | 0.27%   |
| ASMT                        | 16       | 23     | 0.25%   |
| Apple                       | 16       | 19     | 0.25%   |
| ADATA Technology            | 16       | 21     | 0.25%   |
| SPCC                        | 15       | 24     | 0.24%   |
| KIOXIA-EXCERIA              | 14       | 22     | 0.22%   |
| Lexar                       | 12       | 13     | 0.19%   |
| Drevo                       | 12       | 23     | 0.19%   |
| Hewlett-Packard             | 11       | 17     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST3500312CS 500GB                           | 95       | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91       | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB                      | 90       | 1.18%   |
| Samsung SSD 850 EVO 250GB                           | 80       | 1.05%   |
| Kingston SA400S37240G 240GB SSD                     | 73       | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 61       | 0.8%    |
| Seagate ST500DM002-1BD142 500GB                     | 59       | 0.78%   |
| Samsung SSD 850 EVO 500GB                           | 58       | 0.76%   |
| Crucial CT1000MX500SSD1 1TB                         | 57       | 0.75%   |
| Crucial CT500MX500SSD1 500GB                        | 56       | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                      | 51       | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 51       | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 46       | 0.61%   |
| Kingston SA400S37120G 120GB SSD                     | 46       | 0.61%   |
| Toshiba DT01ACA100 1TB                              | 41       | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 41       | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB                      | 40       | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB                        | 37       | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB                      | 36       | 0.47%   |
| Toshiba HDWD130 3TB                                 | 35       | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 35       | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 34       | 0.45%   |
| Seagate ST2000DM001-1CH164 2TB                      | 34       | 0.45%   |
| Seagate ST3500418AS 500GB                           | 33       | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 33       | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 33       | 0.43%   |
| Samsung NVMe SSD Drive 1TB                          | 32       | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 32       | 0.42%   |
| SanDisk SSD PLUS 480GB                              | 31       | 0.41%   |
| Samsung SSD 840 EVO 250GB                           | 31       | 0.41%   |
| Samsung HD103SJ 1TB                                 | 31       | 0.41%   |
| Toshiba HDWD110 1TB                                 | 30       | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 30       | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 29       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 27       | 0.36%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 27       | 0.36%   |
| Samsung SSD 870 QVO 1TB                             | 27       | 0.36%   |
| Toshiba DT01ACA200 2TB                              | 26       | 0.34%   |
| SanDisk SSD PLUS 240GB                              | 26       | 0.34%   |
| Crucial CT250MX500SSD1 250GB                        | 26       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1184     | 2118   | 38.42%  |
| WDC                 | 955      | 1755   | 30.99%  |
| Toshiba             | 295      | 461    | 9.57%   |
| Hitachi             | 236      | 348    | 7.66%   |
| Samsung Electronics | 183      | 275    | 5.94%   |
| HGST                | 51       | 76     | 1.65%   |
| Maxtor              | 49       | 79     | 1.59%   |
| Unknown             | 26       | 33     | 0.84%   |
| SABRENT             | 17       | 20     | 0.55%   |
| Hewlett-Packard     | 10       | 16     | 0.32%   |
| Fujitsu             | 10       | 18     | 0.32%   |
| ASMT                | 10       | 16     | 0.32%   |
| Apple               | 9        | 11     | 0.29%   |
| TO Exter            | 7        | 8      | 0.23%   |
| WD MediaMax         | 4        | 4      | 0.13%   |
| HPE                 | 4        | 7      | 0.13%   |
| External            | 3        | 3      | 0.1%    |
| ASMT109x            | 3        | 5      | 0.1%    |
| USB3.0              | 2        | 3      | 0.06%   |
| USB                 | 2        | 2      | 0.06%   |
| SSK                 | 2        | 2      | 0.06%   |
| RSH-339             | 2        | 2      | 0.06%   |
| ExcelStor           | 2        | 4      | 0.06%   |
| TDAS                | 1        | 8      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SSI                 | 1        | 1      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| KESU                | 1        | 5      | 0.03%   |
| JMicron Technology  | 1        | 1      | 0.03%   |
| Inateck             | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Advantech           | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 537      | 878    | 23.33%  |
| Crucial             | 374      | 568    | 16.25%  |
| Kingston            | 276      | 391    | 11.99%  |
| SanDisk             | 272      | 370    | 11.82%  |
| WDC                 | 122      | 177    | 5.3%    |
| China               | 80       | 107    | 3.48%   |
| OCZ                 | 60       | 70     | 2.61%   |
| A-DATA Technology   | 50       | 71     | 2.17%   |
| Intel               | 41       | 51     | 1.78%   |
| PNY                 | 36       | 47     | 1.56%   |
| Toshiba             | 30       | 36     | 1.3%    |
| Corsair             | 26       | 35     | 1.13%   |
| Integral            | 24       | 28     | 1.04%   |
| Transcend           | 22       | 26     | 0.96%   |
| Patriot             | 20       | 30     | 0.87%   |
| LITEON              | 18       | 22     | 0.78%   |
| Gigabyte Technology | 16       | 24     | 0.7%    |
| SK hynix            | 15       | 17     | 0.65%   |
| Seagate             | 15       | 21     | 0.65%   |
| Netac               | 15       | 21     | 0.65%   |
| Micron Technology   | 15       | 15     | 0.65%   |
| SPCC                | 12       | 21     | 0.52%   |
| Drevo               | 12       | 23     | 0.52%   |
| KIOXIA-EXCERIA      | 11       | 19     | 0.48%   |
| LITEONIT            | 10       | 12     | 0.43%   |
| Vaseky              | 9        | 13     | 0.39%   |
| Lexar               | 9        | 10     | 0.39%   |
| JMicron Technology  | 9        | 14     | 0.39%   |
| Team                | 8        | 8      | 0.35%   |
| Unknown             | 8        | 9      | 0.35%   |
| ORTIAL              | 7        | 8      | 0.3%    |
| Maxtor              | 7        | 8      | 0.3%    |
| XUM                 | 6        | 6      | 0.26%   |
| Unknown             | 6        | 12     | 0.26%   |
| TCSUNBOW            | 6        | 9      | 0.26%   |
| ASMT                | 6        | 6      | 0.26%   |
| Apple               | 6        | 7      | 0.26%   |
| Plextor             | 4        | 6      | 0.17%   |
| KingSpec            | 4        | 7      | 0.17%   |
| KingDian            | 4        | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2259     | 5300   | 44.08%  |
| SSD     | 1805     | 3332   | 35.22%  |
| NVMe    | 952      | 1706   | 18.58%  |
| Unknown | 93       | 136    | 1.81%   |
| MMC     | 16       | 20     | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2968     | 8244   | 70%     |
| NVMe | 950      | 1700   | 22.41%  |
| SAS  | 306      | 530    | 7.22%   |
| MMC  | 16       | 20     | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2166     | 4188   | 46.54%  |
| 0.51-1.0        | 1229     | 2082   | 26.41%  |
| 1.01-2.0        | 658      | 1125   | 14.14%  |
| 3.01-4.0        | 217      | 441    | 4.66%   |
| 2.01-3.0        | 182      | 320    | 3.91%   |
| 4.01-10.0       | 170      | 388    | 3.65%   |
| 10.01-20.0      | 30       | 86     | 0.64%   |
| More than 100.0 | 1        | 1      | 0.02%   |
| 0               | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 750      | 21.16%  |
| 251-500        | 565      | 15.94%  |
| 501-1000       | 552      | 15.57%  |
| More than 3000 | 475      | 13.4%   |
| 1001-2000      | 429      | 12.1%   |
| 1-20           | 219      | 6.18%   |
| 2001-3000      | 209      | 5.9%    |
| 51-100         | 159      | 4.49%   |
| Unknown        | 115      | 3.24%   |
| 21-50          | 72       | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1202     | 32.67%  |
| 21-50          | 478      | 12.99%  |
| 101-250        | 415      | 11.28%  |
| 51-100         | 355      | 9.65%   |
| 251-500        | 315      | 8.56%   |
| 501-1000       | 294      | 7.99%   |
| 1001-2000      | 235      | 6.39%   |
| More than 3000 | 184      | 5%      |
| Unknown        | 115      | 3.13%   |
| 2001-3000      | 85       | 2.31%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 6        | 6      | 1.45%   |
| Seagate ST3500418AS 500GB                | 6        | 6      | 1.45%   |
| Samsung Electronics HD103UJ 1TB          | 6        | 8      | 1.45%   |
| Seagate ST3500312CS 500GB                | 5        | 7      | 1.21%   |
| Seagate ST2000DM001-1CH164 2TB           | 5        | 6      | 1.21%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 4        | 11     | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 4        | 7      | 0.97%   |
| Samsung Electronics SSD 960 EVO 250GB    | 4        | 5      | 0.97%   |
| Samsung Electronics HD103SJ 1TB          | 4        | 5      | 0.97%   |
| Hitachi HDS721010CLA332 1TB              | 4        | 4      | 0.97%   |
| WDC WD6400AAKS-22A7B2 640GB              | 3        | 3      | 0.73%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3        | 3      | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB                  | 3        | 4      | 0.73%   |
| Toshiba DT01ACA050 500GB                 | 3        | 4      | 0.73%   |
| Seagate ST500LM021-1KJ152 500GB          | 3        | 4      | 0.73%   |
| Seagate ST3500620AS 500GB                | 3        | 4      | 0.73%   |
| Seagate ST2000DM006-2DM164 2TB           | 3        | 3      | 0.73%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 3        | 4      | 0.73%   |
| Samsung Electronics SSD 840 Series 120GB | 3        | 3      | 0.73%   |
| Intel SSDPEKKW512G7 512GB                | 3        | 6      | 0.73%   |
| Hitachi HUA723030ALA640 3TB              | 3        | 4      | 0.73%   |
| Hitachi HDT721010SLA360 1TB              | 3        | 3      | 0.73%   |
| Hitachi HDP725050GLA360 500GB            | 3        | 3      | 0.73%   |
| Crucial CT480M500SSD1 480GB              | 3        | 3      | 0.73%   |
| WDC WD800JD-00HKA0 80GB                  | 2        | 2      | 0.48%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2        | 2      | 0.48%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 2        | 19     | 0.48%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 2        | 4      | 0.48%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2        | 2      | 0.48%   |
| WDC WD40EZRZ-00WN9B0 4TB                 | 2        | 2      | 0.48%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2        | 2      | 0.48%   |
| WDC WD30PURX-64P6ZY0 3TB                 | 2        | 3      | 0.48%   |
| WDC WD30EZRX-00SPEB0 3TB                 | 2        | 2      | 0.48%   |
| WDC WD30EZRX-00MMMB0 3TB                 | 2        | 2      | 0.48%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 2        | 2      | 0.48%   |
| WDC WD20EARX-00PASB0 2TB                 | 2        | 2      | 0.48%   |
| WDC WD10EZEX-60ZF5A0 1TB                 | 2        | 4      | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 2        | 2      | 0.48%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 2        | 2      | 0.48%   |
| WDC WD10EADS-00L5B1 1TB                  | 2        | 2      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 113      | 171    | 29.12%  |
| Seagate             | 96       | 129    | 24.74%  |
| Samsung Electronics | 43       | 60     | 11.08%  |
| Hitachi             | 37       | 57     | 9.54%   |
| Crucial             | 18       | 25     | 4.64%   |
| Toshiba             | 15       | 20     | 3.87%   |
| SanDisk             | 11       | 15     | 2.84%   |
| Intel               | 10       | 21     | 2.58%   |
| Kingston            | 6        | 9      | 1.55%   |
| A-DATA Technology   | 5        | 8      | 1.29%   |
| Maxtor              | 4        | 5      | 1.03%   |
| Corsair             | 3        | 7      | 0.77%   |
| WD MediaMax         | 2        | 2      | 0.52%   |
| Unknown             | 2        | 2      | 0.52%   |
| Micron Technology   | 2        | 2      | 0.52%   |
| HGST                | 2        | 2      | 0.52%   |
| Hewlett-Packard     | 2        | 2      | 0.52%   |
| Drevo               | 2        | 10     | 0.52%   |
| China               | 2        | 2      | 0.52%   |
| VENO                | 1        | 1      | 0.26%   |
| SK hynix            | 1        | 1      | 0.26%   |
| OCZ                 | 1        | 1      | 0.26%   |
| Netac               | 1        | 1      | 0.26%   |
| Mushkin             | 1        | 1      | 0.26%   |
| LITEON              | 1        | 1      | 0.26%   |
| Lexar               | 1        | 1      | 0.26%   |
| KingSpec            | 1        | 1      | 0.26%   |
| faspeed             | 1        | 1      | 0.26%   |
| BIWIN               | 1        | 1      | 0.26%   |
| BAITITON            | 1        | 4      | 0.26%   |
| AGI                 | 1        | 1      | 0.26%   |
| Unknown             | 1        | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 109      | 166    | 37.98%  |
| Seagate             | 96       | 129    | 33.45%  |
| Hitachi             | 37       | 57     | 12.89%  |
| Samsung Electronics | 19       | 28     | 6.62%   |
| Toshiba             | 14       | 19     | 4.88%   |
| Maxtor              | 4        | 5      | 1.39%   |
| WD MediaMax         | 2        | 2      | 0.7%    |
| Unknown             | 2        | 2      | 0.7%    |
| HGST                | 2        | 2      | 0.7%    |
| Hewlett-Packard     | 2        | 2      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 246      | 412    | 71.1%   |
| SSD  | 77       | 118    | 22.25%  |
| NVMe | 23       | 35     | 6.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB      | 1        | 1      | 14.29%  |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 14.29%  |
| Seagate ST3160815AS 160GB             | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1        | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 42.86%  |
| Toshiba             | 2        | 2      | 28.57%  |
| Seagate             | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2141     | 6481   | 58.12%  |
| Works    | 1208     | 3440   | 32.79%  |
| Malfunc  | 329      | 565    | 8.93%   |
| Failed   | 6        | 8      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1910     | 39.81%  |
| AMD                              | 1219     | 25.41%  |
| Samsung Electronics              | 391      | 8.15%   |
| ASMedia Technology               | 194      | 4.04%   |
| SanDisk                          | 182      | 3.79%   |
| Phison Electronics               | 169      | 3.52%   |
| Marvell Technology Group         | 112      | 2.33%   |
| Nvidia                           | 106      | 2.21%   |
| Micron/Crucial Technology        | 95       | 1.98%   |
| JMicron Technology               | 91       | 1.9%    |
| Kingston Technology Company      | 50       | 1.04%   |
| Silicon Motion                   | 43       | 0.9%    |
| ADATA Technology                 | 34       | 0.71%   |
| Seagate Technology               | 25       | 0.52%   |
| LSI Logic / Symbios Logic        | 21       | 0.44%   |
| Silicon Image                    | 20       | 0.42%   |
| Broadcom / LSI                   | 19       | 0.4%    |
| VIA Technologies                 | 18       | 0.38%   |
| Toshiba America Info Systems     | 16       | 0.33%   |
| SK hynix                         | 14       | 0.29%   |
| Realtek Semiconductor            | 11       | 0.23%   |
| Micron Technology                | 10       | 0.21%   |
| MAXIO Technology (Hangzhou)      | 10       | 0.21%   |
| Adaptec                          | 9        | 0.19%   |
| KIOXIA                           | 7        | 0.15%   |
| Shenzhen Longsys Electronics     | 4        | 0.08%   |
| Silicon Integrated Systems [SiS] | 3        | 0.06%   |
| Integrated Technology Express    | 3        | 0.06%   |
| Hewlett-Packard                  | 3        | 0.06%   |
| Solidigm                         | 2        | 0.04%   |
| INNOGRIT                         | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Initio                           | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |
| Advanced System Products         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 722      | 11.84%  |
| AMD 400 Series Chipset SATA Controller                                                  | 246      | 4.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 227      | 3.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 226      | 3.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 184      | 3.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 179      | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 160      | 2.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 149      | 2.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 141      | 2.31%   |
| AMD 500 Series Chipset SATA Controller                                                  | 141      | 2.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 138      | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 138      | 2.26%   |
| Intel SATA Controller [RAID mode]                                                       | 129      | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 125      | 2.05%   |
| Phison E12 NVMe Controller                                                              | 96       | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 95       | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 94       | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 72       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 69       | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 67       | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 62       | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 62       | 1.02%   |
| Nvidia MCP61 SATA Controller                                                            | 59       | 0.97%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 57       | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 57       | 0.93%   |
| AMD FCH SATA Controller D                                                               | 56       | 0.92%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 55       | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 54       | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 51       | 0.84%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 50       | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 49       | 0.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 49       | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 0.75%   |
| Nvidia MCP61 IDE                                                                        | 43       | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 38       | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 38       | 0.62%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 37       | 0.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 35       | 0.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 34       | 0.56%   |
| AMD FCH IDE Controller                                                                  | 34       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2638     | 56.12%  |
| NVMe | 956      | 20.34%  |
| IDE  | 825      | 17.55%  |
| RAID | 226      | 4.81%   |
| SAS  | 34       | 0.72%   |
| SCSI | 22       | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1930     | 59.33%  |
| AMD                   | 1318     | 40.52%  |
| ARM                   | 2        | 0.06%   |
| sifive,u74-mc         | 1        | 0.03%   |
| Marvell Semiconductor | 1        | 0.03%   |
| CentaurHauls          | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 86       | 2.62%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 58       | 1.77%   |
| AMD FX-8350 Eight-Core Processor            | 49       | 1.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 46       | 1.4%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 42       | 1.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 39       | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 38       | 1.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 38       | 1.16%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 37       | 1.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 36       | 1.1%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 34       | 1.04%   |
| AMD FX-6300 Six-Core Processor              | 34       | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 33       | 1.01%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 31       | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 30       | 0.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 29       | 0.88%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 28       | 0.85%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 26       | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 25       | 0.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.73%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 23       | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 23       | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.7%    |
| AMD Ryzen 9 3950X 16-Core Processor         | 23       | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 23       | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 22       | 0.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 22       | 0.67%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 22       | 0.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 22       | 0.67%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 21       | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 20       | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 19       | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 19       | 0.58%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 18       | 0.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 18       | 0.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 18       | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 17       | 0.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 17       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 505      | 15.45%  |
| Intel Core i5           | 491      | 15.02%  |
| AMD Ryzen 5             | 301      | 9.21%   |
| AMD Ryzen 7             | 236      | 7.22%   |
| Intel Core i3           | 180      | 5.51%   |
| Intel Xeon              | 165      | 5.05%   |
| AMD FX                  | 162      | 4.96%   |
| AMD Ryzen 9             | 159      | 4.86%   |
| Intel Core 2 Duo        | 112      | 3.43%   |
| Other                   | 98       | 3%      |
| Intel Pentium           | 71       | 2.17%   |
| Intel Celeron           | 69       | 2.11%   |
| Intel Core 2 Quad       | 68       | 2.08%   |
| AMD Ryzen 3             | 52       | 1.59%   |
| Intel Pentium Dual-Core | 45       | 1.38%   |
| AMD A10                 | 43       | 1.32%   |
| AMD Athlon II X2        | 42       | 1.28%   |
| AMD A8                  | 41       | 1.25%   |
| Intel Core i9           | 37       | 1.13%   |
| AMD Phenom II X4        | 34       | 1.04%   |
| AMD Ryzen Threadripper  | 30       | 0.92%   |
| AMD Athlon 64 X2        | 26       | 0.8%    |
| Intel Core 2            | 24       | 0.73%   |
| AMD A6                  | 24       | 0.73%   |
| Intel Pentium 4         | 21       | 0.64%   |
| Intel Atom              | 20       | 0.61%   |
| AMD A4                  | 18       | 0.55%   |
| Intel Pentium Dual      | 17       | 0.52%   |
| Intel Pentium D         | 17       | 0.52%   |
| AMD Athlon II X4        | 17       | 0.52%   |
| AMD Athlon              | 16       | 0.49%   |
| AMD Phenom II X6        | 15       | 0.46%   |
| AMD Phenom              | 15       | 0.46%   |
| AMD Turion II Neo       | 9        | 0.28%   |
| AMD Sempron             | 7        | 0.21%   |
| AMD Phenom II X2        | 7        | 0.21%   |
| AMD Athlon II X3        | 7        | 0.21%   |
| AMD Ryzen 7 PRO         | 6        | 0.18%   |
| AMD Athlon X4           | 6        | 0.18%   |
| AMD Athlon 64           | 6        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1185     | 36.25%  |
| 2       | 785      | 24.01%  |
| 6       | 496      | 15.17%  |
| 8       | 385      | 11.78%  |
| 12      | 114      | 3.49%   |
| 16      | 94       | 2.88%   |
| 1       | 83       | 2.54%   |
| 3       | 66       | 2.02%   |
| 10      | 25       | 0.76%   |
| 24      | 17       | 0.52%   |
| 14      | 6        | 0.18%   |
| 32      | 5        | 0.15%   |
| 28      | 2        | 0.06%   |
| 64      | 1        | 0.03%   |
| 44      | 1        | 0.03%   |
| 36      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 18      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3198     | 98.31%  |
| 2       | 54       | 1.66%   |
| Unknown | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1969     | 60.4%   |
| 1       | 1290     | 39.57%  |
| Unknown | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3196     | 97.92%  |
| Unknown        | 50       | 1.53%   |
| 32-bit         | 18       | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 942      | 27.5%   |
| 0x306c3    | 239      | 6.98%   |
| 0x206a7    | 157      | 4.58%   |
| 0x08701021 | 143      | 4.18%   |
| 0x306a9    | 137      | 4%      |
| 0x1067a    | 110      | 3.21%   |
| 0x506e3    | 101      | 2.95%   |
| 0x06000852 | 85       | 2.48%   |
| 0x0800820d | 81       | 2.36%   |
| 0x010000c8 | 73       | 2.13%   |
| 0x906ea    | 68       | 1.99%   |
| 0x08701013 | 57       | 1.66%   |
| 0x06001119 | 57       | 1.66%   |
| 0x906e9    | 53       | 1.55%   |
| 0x0a201016 | 38       | 1.11%   |
| 0x08001138 | 37       | 1.08%   |
| 0x6fb      | 36       | 1.05%   |
| 0x10676    | 31       | 0.91%   |
| 0x0a601203 | 30       | 0.88%   |
| 0x906ed    | 29       | 0.85%   |
| 0x6fd      | 29       | 0.85%   |
| 0x206c2    | 29       | 0.85%   |
| 0x06003106 | 29       | 0.85%   |
| 0x0a201009 | 28       | 0.82%   |
| 0xa0655    | 26       | 0.76%   |
| 0x0a20120a | 26       | 0.76%   |
| 0x08108109 | 26       | 0.76%   |
| 0x206d7    | 25       | 0.73%   |
| 0x106a5    | 25       | 0.73%   |
| 0x08001137 | 22       | 0.64%   |
| 0x306f2    | 20       | 0.58%   |
| 0x106e5    | 20       | 0.58%   |
| 0x010000db | 20       | 0.58%   |
| 0x20655    | 19       | 0.55%   |
| 0x0600063e | 19       | 0.55%   |
| 0x90672    | 17       | 0.5%    |
| 0x306e4    | 16       | 0.47%   |
| 0x906ec    | 15       | 0.44%   |
| 0x20652    | 15       | 0.44%   |
| 0x0a50000d | 15       | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 354      | 10.82%  |
| Zen 2            | 289      | 8.83%   |
| KabyLake         | 263      | 8.04%   |
| SandyBridge      | 235      | 7.18%   |
| IvyBridge        | 206      | 6.29%   |
| Piledriver       | 196      | 5.99%   |
| Penryn           | 189      | 5.77%   |
| Zen 3            | 183      | 5.59%   |
| Skylake          | 161      | 4.92%   |
| K10              | 160      | 4.89%   |
| Zen+             | 159      | 4.86%   |
| Zen              | 119      | 3.64%   |
| Core             | 111      | 3.39%   |
| Unknown          | 91       | 2.78%   |
| Westmere         | 77       | 2.35%   |
| Nehalem          | 62       | 1.89%   |
| CometLake        | 57       | 1.74%   |
| Steamroller      | 42       | 1.28%   |
| NetBurst         | 42       | 1.28%   |
| K8 Hammer        | 42       | 1.28%   |
| Alderlake Hybrid | 34       | 1.04%   |
| Bulldozer        | 30       | 0.92%   |
| Excavator        | 27       | 0.82%   |
| Silvermont       | 26       | 0.79%   |
| Icelake          | 17       | 0.52%   |
| Broadwell        | 16       | 0.49%   |
| Bonnell          | 15       | 0.46%   |
| Tremont          | 10       | 0.31%   |
| Jaguar           | 10       | 0.31%   |
| Goldmont plus    | 10       | 0.31%   |
| Bobcat           | 10       | 0.31%   |
| Goldmont         | 9        | 0.27%   |
| K10 Llano        | 6        | 0.18%   |
| Gracemont        | 5        | 0.15%   |
| K6               | 4        | 0.12%   |
| TigerLake        | 3        | 0.09%   |
| Puma             | 3        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1501     | 42.59%  |
| AMD                                          | 1070     | 30.36%  |
| Intel                                        | 929      | 26.36%  |
| Matrox Electronics Systems                   | 8        | 0.23%   |
| ASPEED Technology                            | 6        | 0.17%   |
| ATI Technologies                             | 4        | 0.11%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| VIA Technologies                             | 1        | 0.03%   |
| Alliance Semiconductor                       | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 168      | 4.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 154      | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 116      | 3.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 114      | 3.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 78       | 2.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 67       | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 65       | 1.77%   |
| Intel HD Graphics 530                                                       | 63       | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 61       | 1.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 60       | 1.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 52       | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 52       | 1.42%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 51       | 1.39%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 48       | 1.31%   |
| Nvidia GT218 [GeForce 210]                                                  | 47       | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 46       | 1.25%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 44       | 1.2%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 44       | 1.2%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 43       | 1.17%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 38       | 1.03%   |
| AMD Raphael                                                                 | 37       | 1.01%   |
| Intel HD Graphics 630                                                       | 36       | 0.98%   |
| Nvidia GF119 [GeForce GT 610]                                               | 34       | 0.93%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 34       | 0.93%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 32       | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 32       | 0.87%   |
| AMD RS780L [Radeon 3000]                                                    | 32       | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31       | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                              | 27       | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 26       | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 26       | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 25       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 24       | 0.65%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 24       | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 24       | 0.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 24       | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 23       | 0.63%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 23       | 0.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 23       | 0.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 22       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| 1 x Nvidia                           | 1359     | 40.93%  |
| 1 x AMD                              | 938      | 28.25%  |
| 1 x Intel                            | 750      | 22.59%  |
| Intel + Nvidia                       | 68       | 2.05%   |
| 2 x AMD                              | 63       | 1.9%    |
| AMD + Nvidia                         | 43       | 1.3%    |
| 2 x Nvidia                           | 30       | 0.9%    |
| Intel + AMD                          | 24       | 0.72%   |
| Other                                | 8        | 0.24%   |
| 1 x Matrox                           | 7        | 0.21%   |
| 2 x Intel                            | 6        | 0.18%   |
| 1 x ASPEED                           | 4        | 0.12%   |
| 2 x AMD + 1 x Nvidia                 | 3        | 0.09%   |
| Intel + AMD + 1 x Nvidia             | 3        | 0.09%   |
| 1 x SiS                              | 2        | 0.06%   |
| 3 x AMD                              | 1        | 0.03%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1        | 0.03%   |
| 1 x XGI                              | 1        | 0.03%   |
| 1 x VIA                              | 1        | 0.03%   |
| Nvidia + ASPEED                      | 1        | 0.03%   |
| 1 x Intel + 3 x Nvidia               | 1        | 0.03%   |
| Intel + 2 x Nvidia                   | 1        | 0.03%   |
| Intel + 2 x AMD                      | 1        | 0.03%   |
| Intel + AMD + 3 x Nvidia             | 1        | 0.03%   |
| AMD + SiS                            | 1        | 0.03%   |
| AMD + Matrox                         | 1        | 0.03%   |
| AMD + ASPEED                         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2247     | 66.93%  |
| Proprietary | 925      | 27.55%  |
| Unknown     | 185      | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1317     | 38.49%  |
| 1.01-2.0   | 474      | 13.85%  |
| 0.51-1.0   | 354      | 10.34%  |
| 0.01-0.5   | 354      | 10.34%  |
| 7.01-8.0   | 341      | 9.96%   |
| 3.01-4.0   | 269      | 7.86%   |
| 8.01-16.0  | 136      | 3.97%   |
| 5.01-6.0   | 116      | 3.39%   |
| 2.01-3.0   | 43       | 1.26%   |
| 16.01-24.0 | 15       | 0.44%   |
| 4.01-5.0   | 2        | 0.06%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 455      | 13.28%  |
| Samsung Electronics  | 432      | 12.61%  |
| Acer                 | 295      | 8.61%   |
| AOC                  | 231      | 6.74%   |
| Goldstar             | 221      | 6.45%   |
| BenQ                 | 220      | 6.42%   |
| Hewlett-Packard      | 213      | 6.22%   |
| Iiyama               | 149      | 4.35%   |
| Ancor Communications | 123      | 3.59%   |
| Philips              | 95       | 2.77%   |
| ViewSonic            | 73       | 2.13%   |
| Sony                 | 67       | 1.96%   |
| ASUSTek Computer     | 66       | 1.93%   |
| Unknown              | 61       | 1.78%   |
| Lenovo               | 51       | 1.49%   |
| HannStar             | 50       | 1.46%   |
| LG Electronics       | 45       | 1.31%   |
| Toshiba              | 33       | 0.96%   |
| Panasonic            | 33       | 0.96%   |
| MSI                  | 32       | 0.93%   |
| Vestel Elektronik    | 30       | 0.88%   |
| NEC Computers        | 25       | 0.73%   |
| Gigabyte Technology  | 22       | 0.64%   |
| OEM                  | 17       | 0.5%    |
| Idek Iiyama          | 16       | 0.47%   |
| Hitachi              | 15       | 0.44%   |
| CVT                  | 15       | 0.44%   |
| MiTAC                | 13       | 0.38%   |
| Eizo                 | 13       | 0.38%   |
| Pixio                | 12       | 0.35%   |
| MStar                | 11       | 0.32%   |
| HKC                  | 11       | 0.32%   |
| Fujitsu Siemens      | 11       | 0.32%   |
| Sharp                | 10       | 0.29%   |
| Unknown              | 10       | 0.29%   |
| HPN                  | 8        | 0.23%   |
| HannStar Display     | 8        | 0.23%   |
| GNR                  | 8        | 0.23%   |
| Vestel               | 7        | 0.2%    |
| Packard Bell         | 7        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 29       | 0.79%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 19       | 0.52%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 19       | 0.52%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 18       | 0.49%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 17       | 0.46%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 17       | 0.46%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 16       | 0.43%   |
| OEM 26W_LCD_TV OEM3700 1920x540                                        | 14       | 0.38%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 13       | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 12       | 0.33%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 12       | 0.33%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                      | 12       | 0.33%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 11       | 0.3%    |
| Toshiba 24W_LCD_TV TSB3700 1920x1080 706x398mm 31.9-inch               | 10       | 0.27%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                  | 10       | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 10       | 0.27%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                     | 10       | 0.27%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 10       | 0.27%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                      | 10       | 0.27%   |
| Unknown                                                                | 10       | 0.27%   |
| Sony TV SNYE903 1920x1080                                              | 9        | 0.24%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                      | 9        | 0.24%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 9        | 0.24%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                     | 9        | 0.24%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 8        | 0.22%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                       | 8        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 8        | 0.22%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 8        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 8        | 0.22%   |
| Toshiba TV TSB0108 1280x1024 708x398mm 32.0-inch                       | 7        | 0.19%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 7        | 0.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 7        | 0.19%   |
| MiTAC MTC26T42 SZM0308 1280x720 708x398mm 32.0-inch                    | 7        | 0.19%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                   | 7        | 0.19%   |
| Hitachi HDMI HEC0030 1920x1080 1150x650mm 52.0-inch                    | 7        | 0.19%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 7        | 0.19%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 7        | 0.19%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                      | 7        | 0.19%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                      | 7        | 0.19%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 7        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1471     | 44%     |
| 3840x2160 (4K)     | 383      | 11.46%  |
| 2560x1440 (QHD)    | 286      | 8.56%   |
| 1280x1024 (SXGA)   | 224      | 6.7%    |
| 1680x1050 (WSXGA+) | 155      | 4.64%   |
| 1440x900 (WXGA+)   | 107      | 3.2%    |
| Unknown            | 99       | 2.96%   |
| 1920x1200 (WUXGA)  | 98       | 2.93%   |
| 3440x1440          | 82       | 2.45%   |
| 3840x1080          | 52       | 1.56%   |
| 1600x900 (HD+)     | 49       | 1.47%   |
| 1360x768           | 49       | 1.47%   |
| 1920x540           | 41       | 1.23%   |
| 2560x1080          | 39       | 1.17%   |
| 1366x768 (WXGA)    | 35       | 1.05%   |
| 1024x768 (XGA)     | 26       | 0.78%   |
| 1600x1200          | 22       | 0.66%   |
| 1280x720 (HD)      | 18       | 0.54%   |
| 2560x1600          | 9        | 0.27%   |
| 2288x1287          | 9        | 0.27%   |
| 5120x1440          | 8        | 0.24%   |
| 5760x1080          | 7        | 0.21%   |
| 7680x2160          | 5        | 0.15%   |
| 3840x1200          | 5        | 0.15%   |
| 5760x2160          | 4        | 0.12%   |
| 3840x1600          | 4        | 0.12%   |
| 3200x1080          | 4        | 0.12%   |
| 2048x1152          | 4        | 0.12%   |
| 4480x1440          | 3        | 0.09%   |
| 6400x2160          | 2        | 0.06%   |
| 4480x1080          | 2        | 0.06%   |
| 3360x1080          | 2        | 0.06%   |
| 3360x1050          | 2        | 0.06%   |
| 3120x1050          | 2        | 0.06%   |
| 2944x1080          | 2        | 0.06%   |
| 2048x1080          | 2        | 0.06%   |
| 1280x800 (WXGA)    | 2        | 0.06%   |
| 7680x1440          | 1        | 0.03%   |
| 7280x1440          | 1        | 0.03%   |
| 6880x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 501      | 14.72%  |
| 24      | 465      | 13.66%  |
| Unknown | 439      | 12.9%   |
| 23      | 373      | 10.96%  |
| 21      | 355      | 10.43%  |
| 19      | 187      | 5.5%    |
| 31      | 144      | 4.23%   |
| 17      | 113      | 3.32%   |
| 22      | 100      | 2.94%   |
| 84      | 96       | 2.82%   |
| 34      | 87       | 2.56%   |
| 20      | 67       | 1.97%   |
| 18      | 62       | 1.82%   |
| 72      | 54       | 1.59%   |
| 32      | 41       | 1.2%    |
| 15      | 35       | 1.03%   |
| 26      | 27       | 0.79%   |
| 25      | 24       | 0.71%   |
| 40      | 20       | 0.59%   |
| 54      | 17       | 0.5%    |
| 48      | 16       | 0.47%   |
| 39      | 15       | 0.44%   |
| 33      | 15       | 0.44%   |
| 28      | 14       | 0.41%   |
| 52      | 12       | 0.35%   |
| 60      | 10       | 0.29%   |
| 46      | 10       | 0.29%   |
| 35      | 9        | 0.26%   |
| 65      | 8        | 0.24%   |
| 55      | 8        | 0.24%   |
| 42      | 7        | 0.21%   |
| 29      | 7        | 0.21%   |
| 142     | 6        | 0.18%   |
| 43      | 6        | 0.18%   |
| 37      | 6        | 0.18%   |
| 14      | 6        | 0.18%   |
| 57      | 5        | 0.15%   |
| 36      | 5        | 0.15%   |
| 12      | 5        | 0.15%   |
| 30      | 4        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1217     | 36.85%  |
| 401-500        | 666      | 20.16%  |
| Unknown        | 439      | 13.29%  |
| 601-700        | 234      | 7.08%   |
| 701-800        | 149      | 4.51%   |
| 1501-2000      | 149      | 4.51%   |
| 301-350        | 147      | 4.45%   |
| 351-400        | 121      | 3.66%   |
| 1001-1500      | 99       | 3%      |
| 801-900        | 48       | 1.45%   |
| 901-1000       | 15       | 0.45%   |
| 201-300        | 13       | 0.39%   |
| More than 2000 | 6        | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1951     | 62.13%  |
| Unknown | 388      | 12.36%  |
| 16/10   | 370      | 11.78%  |
| 5/4     | 209      | 6.66%   |
| 21/9    | 109      | 3.47%   |
| 4/3     | 53       | 1.69%   |
| 32/9    | 22       | 0.7%    |
| 3/2     | 15       | 0.48%   |
| 1.00    | 10       | 0.32%   |
| 6/5     | 9        | 0.29%   |
| 3.20    | 2        | 0.06%   |
| 2.00    | 1        | 0.03%   |
| 0.56    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1012     | 30.37%  |
| 301-350        | 517      | 15.52%  |
| Unknown        | 439      | 13.18%  |
| 151-200        | 376      | 11.28%  |
| 351-500        | 306      | 9.18%   |
| More than 1000 | 220      | 6.6%    |
| 251-300        | 177      | 5.31%   |
| 141-150        | 138      | 4.14%   |
| 501-1000       | 90       | 2.7%    |
| 101-110        | 35       | 1.05%   |
| 71-80          | 5        | 0.15%   |
| 111-120        | 5        | 0.15%   |
| 131-140        | 3        | 0.09%   |
| 81-90          | 2        | 0.06%   |
| 41-50          | 2        | 0.06%   |
| 121-130        | 2        | 0.06%   |
| 91-100         | 2        | 0.06%   |
| 51-60          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1772     | 55.71%  |
| 101-120       | 602      | 18.92%  |
| Unknown       | 439      | 13.8%   |
| 121-160       | 168      | 5.28%   |
| 1-50          | 140      | 4.4%    |
| 161-240       | 59       | 1.85%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2554     | 75.7%   |
| 2     | 520      | 15.41%  |
| 0     | 222      | 6.58%   |
| 3     | 70       | 2.07%   |
| 4     | 8        | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1892     | 39.57%  |
| Intel                            | 1476     | 30.87%  |
| Qualcomm Atheros                 | 279      | 5.84%   |
| Broadcom                         | 231      | 4.83%   |
| Ralink Technology                | 155      | 3.24%   |
| Nvidia                           | 90       | 1.88%   |
| TP-Link                          | 77       | 1.61%   |
| Ralink                           | 67       | 1.4%    |
| MediaTek                         | 66       | 1.38%   |
| Microsoft                        | 37       | 0.77%   |
| Broadcom Limited                 | 37       | 0.77%   |
| Marvell Technology Group         | 36       | 0.75%   |
| Belkin Components                | 25       | 0.52%   |
| NetGear                          | 24       | 0.5%    |
| Aquantia                         | 24       | 0.5%    |
| Qualcomm Atheros Communications  | 22       | 0.46%   |
| Samsung Electronics              | 20       | 0.42%   |
| Edimax Technology                | 16       | 0.33%   |
| Huawei Technologies              | 15       | 0.31%   |
| ASIX Electronics                 | 12       | 0.25%   |
| ASUSTek Computer                 | 11       | 0.23%   |
| Mellanox Technologies            | 8        | 0.17%   |
| D-Link System                    | 8        | 0.17%   |
| D-Link                           | 8        | 0.17%   |
| Xiaomi                           | 7        | 0.15%   |
| DisplayLink                      | 7        | 0.15%   |
| VIA Technologies                 | 6        | 0.13%   |
| IMC Networks                     | 6        | 0.13%   |
| Apple                            | 6        | 0.13%   |
| OPPO Electronics                 | 5        | 0.1%    |
| Google                           | 5        | 0.1%    |
| Gemtek                           | 5        | 0.1%    |
| ZyDAS                            | 4        | 0.08%   |
| ZTE WCDMA Technologies MSM       | 4        | 0.08%   |
| Texas Instruments                | 4        | 0.08%   |
| Silicon Integrated Systems [SiS] | 4        | 0.08%   |
| OnePlus Technology (Shenzhen)    | 4        | 0.08%   |
| Motorola PCS                     | 4        | 0.08%   |
| Microchip Technology             | 4        | 0.08%   |
| Emulex                           | 4        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1460     | 26.76%  |
| Intel I211 Gigabit Network Connection                             | 267      | 4.89%   |
| Intel Wi-Fi 6 AX200                                               | 172      | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 156      | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148      | 2.71%   |
| Intel Ethernet Connection (2) I219-V                              | 129      | 2.36%   |
| Intel Ethernet Controller I225-V                                  | 92       | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 75       | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 62       | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 61       | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 60       | 1.1%    |
| Realtek 802.11ac NIC                                              | 58       | 1.06%   |
| Ralink MT7601U Wireless Adapter                                   | 58       | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 56       | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 52       | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 50       | 0.92%   |
| Intel Wireless-AC 9260                                            | 48       | 0.88%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 0.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 42       | 0.77%   |
| Ralink RT5370 Wireless Adapter                                    | 41       | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41       | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 39       | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 39       | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 39       | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38       | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38       | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33       | 0.6%    |
| Intel Wireless 7260                                               | 32       | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 31       | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31       | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 27       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27       | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27       | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 26       | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 26       | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 25       | 0.46%   |
| Intel Wireless 3165                                               | 23       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 22       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 522      | 29.43%  |
| Realtek Semiconductor           | 424      | 23.9%   |
| Qualcomm Atheros                | 162      | 9.13%   |
| Ralink Technology               | 155      | 8.74%   |
| Broadcom                        | 107      | 6.03%   |
| TP-Link                         | 77       | 4.34%   |
| Ralink                          | 66       | 3.72%   |
| MediaTek                        | 61       | 3.44%   |
| Microsoft                       | 37       | 2.09%   |
| NetGear                         | 24       | 1.35%   |
| Belkin Components               | 24       | 1.35%   |
| Qualcomm Atheros Communications | 22       | 1.24%   |
| Broadcom Limited                | 16       | 0.9%    |
| Edimax Technology               | 15       | 0.85%   |
| ASUSTek Computer                | 11       | 0.62%   |
| D-Link                          | 8        | 0.45%   |
| D-Link System                   | 7        | 0.39%   |
| IMC Networks                    | 6        | 0.34%   |
| Gemtek                          | 5        | 0.28%   |
| ZyDAS                           | 4        | 0.23%   |
| TRENDnet                        | 3        | 0.17%   |
| Sitecom Europe                  | 3        | 0.17%   |
| Linksys                         | 3        | 0.17%   |
| Wilocity                        | 2        | 0.11%   |
| Philips (or NXP)                | 2        | 0.11%   |
| Marvell Technology Group        | 2        | 0.11%   |
| Wacom                           | 1        | 0.06%   |
| Texas Instruments               | 1        | 0.06%   |
| Micro Star International        | 1        | 0.06%   |
| Dell                            | 1        | 0.06%   |
| CyberTAN Technology             | 1        | 0.06%   |
| AboCom Systems                  | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 172      | 9.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 62       | 3.43%   |
| Realtek 802.11ac NIC                                           | 58       | 3.21%   |
| Ralink MT7601U Wireless Adapter                                | 58       | 3.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 56       | 3.1%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 50       | 2.76%   |
| Intel Wireless-AC 9260                                         | 48       | 2.65%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 42       | 2.32%   |
| Ralink RT5370 Wireless Adapter                                 | 41       | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39       | 2.16%   |
| Intel Wireless 7260                                            | 32       | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 31       | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 31       | 1.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27       | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27       | 1.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 26       | 1.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 25       | 1.38%   |
| Intel Wireless 3165                                            | 23       | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 22       | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 22       | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21       | 1.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 21       | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                | 19       | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 19       | 1.05%   |
| Intel Wireless 8260                                            | 19       | 1.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 18       | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 18       | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 17       | 0.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 16       | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16       | 0.88%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 16       | 0.88%   |
| Intel Wireless 7265                                            | 16       | 0.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 15       | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 14       | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 14       | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14       | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 13       | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                            | 13       | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                  | 12       | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1700     | 48.93%  |
| Intel                                  | 1215     | 34.97%  |
| Broadcom                               | 131      | 3.77%   |
| Qualcomm Atheros                       | 127      | 3.66%   |
| Nvidia                                 | 90       | 2.59%   |
| Marvell Technology Group               | 34       | 0.98%   |
| Aquantia                               | 24       | 0.69%   |
| Broadcom Limited                       | 21       | 0.6%    |
| Samsung Electronics                    | 16       | 0.46%   |
| Huawei Technologies                    | 13       | 0.37%   |
| ASIX Electronics                       | 12       | 0.35%   |
| Xiaomi                                 | 7        | 0.2%    |
| Mellanox Technologies                  | 7        | 0.2%    |
| DisplayLink                            | 7        | 0.2%    |
| VIA Technologies                       | 6        | 0.17%   |
| OPPO Electronics                       | 5        | 0.14%   |
| MediaTek                               | 5        | 0.14%   |
| Google                                 | 5        | 0.14%   |
| Apple                                  | 5        | 0.14%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.12%   |
| Silicon Integrated Systems [SiS]       | 4        | 0.12%   |
| Emulex                                 | 4        | 0.12%   |
| T & A Mobile Phones                    | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| Motorola PCS                           | 3        | 0.09%   |
| 3Com                                   | 3        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |
| Qualcomm                               | 2        | 0.06%   |
| Microchip Technology                   | 2        | 0.06%   |
| Lenovo                                 | 2        | 0.06%   |
| HMD Global                             | 2        | 0.06%   |
| SysKonnect                             | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Solarflare Communications              | 1        | 0.03%   |
| Research In Motion                     | 1        | 0.03%   |
| QLogic                                 | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |
| HTC (High Tech Computer)               | 1        | 0.03%   |
| Edimax Technology                      | 1        | 0.03%   |
| D-Link System                          | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1460     | 40.58%  |
| Intel I211 Gigabit Network Connection                             | 267      | 7.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 156      | 4.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148      | 4.11%   |
| Intel Ethernet Connection (2) I219-V                              | 129      | 3.59%   |
| Intel Ethernet Controller I225-V                                  | 92       | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 75       | 2.08%   |
| Intel Ethernet Connection (7) I219-V                              | 61       | 1.7%    |
| Intel 82579V Gigabit Network Connection                           | 60       | 1.67%   |
| Nvidia MCP61 Ethernet                                             | 52       | 1.45%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 1.25%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41       | 1.14%   |
| Intel Ethernet Connection I217-V                                  | 39       | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 39       | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38       | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38       | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33       | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27       | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 26       | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.64%   |
| Intel 82562V-2 10/100 Network Connection                          | 20       | 0.56%   |
| Intel 82578DM Gigabit Network Connection                          | 19       | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17       | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 17       | 0.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 17       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16       | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14       | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12       | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 12       | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12       | 0.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 12       | 0.33%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 12       | 0.33%   |
| Intel Ethernet Connection (11) I219-V                             | 11       | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10       | 0.28%   |
| Intel 82578DC Gigabit Network Connection                          | 10       | 0.28%   |
| Intel I350 Gigabit Network Connection                             | 9        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3205     | 65.74%  |
| WiFi     | 1622     | 33.27%  |
| Modem    | 38       | 0.78%   |
| Unknown  | 10       | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2507     | 73.58%  |
| WiFi     | 900      | 26.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1981     | 59.98%  |
| 2     | 1094     | 33.12%  |
| 3     | 152      | 4.6%    |
| 0     | 34       | 1.03%   |
| 4     | 22       | 0.67%   |
| 5     | 15       | 0.45%   |
| 6     | 4        | 0.12%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2833     | 85.72%  |
| Yes  | 472      | 14.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 457      | 38.21%  |
| Cambridge Silicon Radio         | 281      | 23.49%  |
| Broadcom                        | 99       | 8.28%   |
| Realtek Semiconductor           | 80       | 6.69%   |
| ASUSTek Computer                | 71       | 5.94%   |
| MediaTek                        | 36       | 3.01%   |
| Qualcomm Atheros Communications | 32       | 2.68%   |
| Apple                           | 28       | 2.34%   |
| TP-Link                         | 18       | 1.51%   |
| IMC Networks                    | 17       | 1.42%   |
| Belkin Components               | 14       | 1.17%   |
| Integrated System Solution      | 12       | 1%      |
| Foxconn / Hon Hai               | 12       | 1%      |
| Lite-On Technology              | 9        | 0.75%   |
| Logitech                        | 5        | 0.42%   |
| Dell                            | 5        | 0.42%   |
| Micro Star International        | 4        | 0.33%   |
| HTC (High Tech Computer)        | 4        | 0.33%   |
| Realtek                         | 2        | 0.17%   |
| Hewlett-Packard                 | 2        | 0.17%   |
| Unknown                         | 2        | 0.17%   |
| Taiyo Yuden                     | 1        | 0.08%   |
| SINO WEALTH                     | 1        | 0.08%   |
| Edimax Technology               | 1        | 0.08%   |
| D-Link                          | 1        | 0.08%   |
| Cypress Semiconductor           | 1        | 0.08%   |
| Creative Technology             | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 281      | 23.48%  |
| Intel AX200 Bluetooth                                                | 149      | 12.45%  |
| Intel Bluetooth wireless interface                                   | 93       | 7.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 74       | 6.18%   |
| Realtek Bluetooth Radio                                              | 63       | 5.26%   |
| Intel Bluetooth Device                                               | 52       | 4.34%   |
| Intel AX210 Bluetooth                                                | 49       | 4.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 46       | 3.84%   |
| MediaTek Wireless_Device                                             | 36       | 3.01%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 36       | 3.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 31       | 2.59%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 31       | 2.59%   |
| TP-Link UB500 Adapter                                                | 18       | 1.5%    |
| IMC Networks Bluetooth Radio                                         | 14       | 1.17%   |
| Qualcomm Atheros  Bluetooth Device                                   | 10       | 0.84%   |
| Apple Bluetooth USB Host Controller                                  | 10       | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                                    | 9        | 0.75%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 9        | 0.75%   |
| Realtek RTL8821A Bluetooth                                           | 8        | 0.67%   |
| Integrated System Solution Bluetooth Device                          | 8        | 0.67%   |
| ASUS Bluetooth Radio                                                 | 8        | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 8        | 0.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 7        | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.58%   |
| Broadcom BCM20702A0                                                  | 7        | 0.58%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.58%   |
| ASUS Bluetooth Device                                                | 7        | 0.58%   |
| Apple Bluetooth HCI                                                  | 7        | 0.58%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 6        | 0.5%    |
| Logitech BT Mini-Receiver (HCI mode)                                 | 5        | 0.42%   |
| Lite-On Bluetooth Device                                             | 5        | 0.42%   |
| Belkin Components Bluetooth Mini Dongle                              | 5        | 0.42%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 4        | 0.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.33%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 4        | 0.33%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.33%   |
| ASUS Bluetooth Adapter                                               | 4        | 0.33%   |
| ASUS BCM20702A0                                                      | 4        | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3        | 0.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1824     | 31.89%  |
| AMD                                          | 1503     | 26.28%  |
| Nvidia                                       | 1423     | 24.88%  |
| C-Media Electronics                          | 163      | 2.85%   |
| Creative Labs                                | 95       | 1.66%   |
| Logitech                                     | 62       | 1.08%   |
| Texas Instruments                            | 48       | 0.84%   |
| Razer USA                                    | 37       | 0.65%   |
| ASUSTek Computer                             | 35       | 0.61%   |
| Focusrite-Novation                           | 33       | 0.58%   |
| Micro Star International                     | 30       | 0.52%   |
| SteelSeries ApS                              | 28       | 0.49%   |
| Creative Technology                          | 28       | 0.49%   |
| JMTek                                        | 25       | 0.44%   |
| Corsair                                      | 18       | 0.31%   |
| Kingston Technology                          | 17       | 0.3%    |
| Blue Microphones                             | 17       | 0.3%    |
| VIA Technologies                             | 15       | 0.26%   |
| Realtek Semiconductor                        | 13       | 0.23%   |
| GN Netcom                                    | 12       | 0.21%   |
| BEHRINGER International                      | 12       | 0.21%   |
| Generalplus Technology                       | 11       | 0.19%   |
| Thesycon Systemsoftware & Consulting         | 10       | 0.17%   |
| Plantronics                                  | 10       | 0.17%   |
| Tenx Technology                              | 9        | 0.16%   |
| DSEA A/S                                     | 9        | 0.16%   |
| KTMicro                                      | 7        | 0.12%   |
| Dell                                         | 7        | 0.12%   |
| Valve Software                               | 6        | 0.1%    |
| Samson Technologies                          | 6        | 0.1%    |
| FiiO Electronics Technology                  | 6        | 0.1%    |
| Cambridge Silicon Radio                      | 6        | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.09%   |
| XMOS                                         | 5        | 0.09%   |
| Sony                                         | 5        | 0.09%   |
| Sennheiser Communications                    | 5        | 0.09%   |
| GYROCOM C&C                                  | 5        | 0.09%   |
| Astro Gaming                                 | 5        | 0.09%   |
| Asahi Kasei Microsystems                     | 5        | 0.09%   |
| AKAI Professional M.I.                       | 5        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 394      | 5.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 255      | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 238      | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 219      | 3.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 197      | 2.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 193      | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 159      | 2.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 157      | 2.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 155      | 2.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 153      | 2.28%   |
| Intel 200 Series PCH HD Audio                                              | 153      | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 139      | 2.07%   |
| AMD FCH Azalia Controller                                                  | 124      | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 109      | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 104      | 1.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 100      | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 96       | 1.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94       | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 92       | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 87       | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 82       | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 76       | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 74       | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 70       | 1.04%   |
| Nvidia High Definition Audio Controller                                    | 67       | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 66       | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 63       | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 63       | 0.94%   |
| Nvidia GM206 High Definition Audio Controller                              | 59       | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 59       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 58       | 0.86%   |
| Nvidia MCP61 High Definition Audio                                         | 57       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 55       | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55       | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 54       | 0.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 54       | 0.8%    |
| Nvidia TU104 HD Audio Controller                                           | 52       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 52       | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 52       | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 49       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 494      | 27.23%  |
| Kingston                     | 236      | 13.01%  |
| Unknown                      | 222      | 12.24%  |
| Crucial                      | 198      | 10.92%  |
| SK hynix                     | 151      | 8.32%   |
| Samsung Electronics          | 145      | 7.99%   |
| Micron Technology            | 96       | 5.29%   |
| G.Skill                      | 46       | 2.54%   |
| A-DATA Technology            | 36       | 1.98%   |
| Team                         | 26       | 1.43%   |
| Patriot                      | 18       | 0.99%   |
| Nanya Technology             | 16       | 0.88%   |
| Ramaxel Technology           | 15       | 0.83%   |
| Elpida                       | 13       | 0.72%   |
| Unknown                      | 12       | 0.66%   |
| Unknown (ABCD)               | 8        | 0.44%   |
| Transcend                    | 6        | 0.33%   |
| ASint Technology             | 5        | 0.28%   |
| A Force                      | 5        | 0.28%   |
| Timetec                      | 4        | 0.22%   |
| Qimonda                      | 4        | 0.22%   |
| KLEVV                        | 4        | 0.22%   |
| Hewlett-Packard              | 4        | 0.22%   |
| Apacer                       | 4        | 0.22%   |
| Lexar Co Limited             | 3        | 0.17%   |
| CSX                          | 3        | 0.17%   |
| Thermaltake                  | 2        | 0.11%   |
| Patriot Memory (PDP Systems) | 2        | 0.11%   |
| Lexar                        | 2        | 0.11%   |
| Infineon                     | 2        | 0.11%   |
| GOODRAM                      | 2        | 0.11%   |
| Axiom                        | 2        | 0.11%   |
| Wilk Elektronik              | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (9B0D)               | 1        | 0.06%   |
| Unknown (89F7)               | 1        | 0.06%   |
| Unknown (83CB)               | 1        | 0.06%   |
| Unknown (0x5846)             | 1        | 0.06%   |
| Unknown (0x4000000000000000) | 1        | 0.06%   |
| Unknown (0x0E9D)             | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 47       | 2.35%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 22       | 1.1%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 18       | 0.9%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 17       | 0.85%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 15       | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 14       | 0.7%    |
| Unknown                                                        | 12       | 0.6%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 1600MT/s         | 11       | 0.55%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s            | 11       | 0.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 10       | 0.5%    |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s         | 10       | 0.5%    |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 10       | 0.5%    |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s          | 10       | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 9        | 0.45%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s             | 9        | 0.45%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s          | 9        | 0.45%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 8        | 0.4%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 8        | 0.4%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 8        | 0.4%    |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s         | 8        | 0.4%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 8        | 0.4%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 7        | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 7        | 0.35%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 7        | 0.35%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s         | 7        | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 0.35%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s          | 7        | 0.35%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 7        | 0.35%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 7        | 0.35%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s           | 7        | 0.35%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s          | 7        | 0.35%   |
| Corsair RAM CM4X16GE2400Z16K4 16GB DIMM DDR4 2400MT/s          | 7        | 0.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 6        | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 6        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 6        | 0.3%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 6        | 0.3%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 6        | 0.3%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 765      | 48.2%   |
| DDR3    | 500      | 31.51%  |
| Unknown | 102      | 6.43%   |
| DDR2    | 90       | 5.67%   |
| SDRAM   | 58       | 3.65%   |
| DDR5    | 45       | 2.84%   |
| DDR     | 17       | 1.07%   |
| LPDDR4  | 9        | 0.57%   |
| LPDDR5  | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1447     | 93.42%  |
| SODIMM       | 88       | 5.68%   |
| RIMM         | 6        | 0.39%   |
| FB-DIMM      | 6        | 0.39%   |
| Row Of Chips | 2        | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 636      | 37.11%  |
| 4096   | 378      | 22.05%  |
| 16384  | 310      | 18.09%  |
| 2048   | 210      | 12.25%  |
| 32768  | 94       | 5.48%   |
| 1024   | 74       | 4.32%   |
| 512    | 7        | 0.41%   |
| 131072 | 1        | 0.06%   |
| 49152  | 1        | 0.06%   |
| 256    | 1        | 0.06%   |
| 16     | 1        | 0.06%   |
| 13     | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 282      | 15.81%  |
| 1333    | 192      | 10.76%  |
| 3200    | 164      | 9.19%   |
| 3600    | 140      | 7.85%   |
| 2400    | 126      | 7.06%   |
| 2133    | 81       | 4.54%   |
| 2667    | 72       | 4.04%   |
| 800     | 68       | 3.81%   |
| 667     | 55       | 3.08%   |
| 3400    | 50       | 2.8%    |
| 3000    | 46       | 2.58%   |
| 1867    | 38       | 2.13%   |
| 3733    | 36       | 2.02%   |
| 1800    | 33       | 1.85%   |
| 2933    | 28       | 1.57%   |
| 2800    | 28       | 1.57%   |
| 2666    | 24       | 1.35%   |
| 3533    | 23       | 1.29%   |
| 1866    | 23       | 1.29%   |
| 1066    | 20       | 1.12%   |
| Unknown | 20       | 1.12%   |
| 3800    | 18       | 1.01%   |
| 4800    | 17       | 0.95%   |
| 400     | 13       | 0.73%   |
| 533     | 12       | 0.67%   |
| 6000    | 10       | 0.56%   |
| 3666    | 10       | 0.56%   |
| 2048    | 10       | 0.56%   |
| 3534    | 8        | 0.45%   |
| 1067    | 8        | 0.45%   |
| 49926   | 7        | 0.39%   |
| 3266    | 6        | 0.34%   |
| 3100    | 6        | 0.34%   |
| 2000    | 6        | 0.34%   |
| 6400    | 5        | 0.28%   |
| 3007    | 5        | 0.28%   |
| 2733    | 5        | 0.28%   |
| 1648    | 5        | 0.28%   |
| 5600    | 4        | 0.22%   |
| 5200    | 4        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 70       | 46.67%  |
| Canon                 | 26       | 17.33%  |
| Seiko Epson           | 13       | 8.67%   |
| Samsung Electronics   | 13       | 8.67%   |
| Brother Industries    | 12       | 8%      |
| Prolific Technology   | 3        | 2%      |
| QinHeng Electronics   | 2        | 1.33%   |
| Lexmark International | 2        | 1.33%   |
| Dymo-CoStar           | 2        | 1.33%   |
| Seiko Instruments     | 1        | 0.67%   |
| Ricoh                 | 1        | 0.67%   |
| Pantum                | 1        | 0.67%   |
| Oki Data              | 1        | 0.67%   |
| Kyocera               | 1        | 0.67%   |
| Dell                  | 1        | 0.67%   |
| Apple                 | 1        | 0.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson Printer                  | 6        | 3.97%   |
| HP ENVY 4520 series                  | 5        | 3.31%   |
| Canon PIXMA MG2500 Series            | 5        | 3.31%   |
| HP ENVY 5000 series                  | 4        | 2.65%   |
| HP DeskJet 2600 series               | 4        | 2.65%   |
| Prolific PL2305 Parallel Port        | 3        | 1.99%   |
| HP OfficeJet 3830 series             | 3        | 1.99%   |
| HP DeskJet 2130 series               | 3        | 1.99%   |
| Canon TS3100 series                  | 3        | 1.99%   |
| Seiko Epson XP-240 Series            | 2        | 1.32%   |
| Seiko Epson XP-200 Series            | 2        | 1.32%   |
| Samsung ML-2250 Series               | 2        | 1.32%   |
| Samsung ML-216x Series Laser Printer | 2        | 1.32%   |
| Samsung M2020 Series                 | 2        | 1.32%   |
| QinHeng CH340S                       | 2        | 1.32%   |
| HP LaserJet P1005                    | 2        | 1.32%   |
| HP LaserJet 200 colorMFP M276nw      | 2        | 1.32%   |
| HP Deskjet F2280 series              | 2        | 1.32%   |
| HP DeskJet 3630 series               | 2        | 1.32%   |
| HP DeskJet 2700 series               | 2        | 1.32%   |
| HP Deskjet 1000 J110 series          | 2        | 1.32%   |
| HP Color LaserJet CP1215             | 2        | 1.32%   |
| Canon PIXMA MX920 Series             | 2        | 1.32%   |
| Canon PIXMA MP495                    | 2        | 1.32%   |
| Canon MG5700 series                  | 2        | 1.32%   |
| Canon iP7200 series                  | 2        | 1.32%   |
| Brother HL-3140CW series             | 2        | 1.32%   |
| Seiko Instruments SLP-450 Driver     | 1        | 0.66%   |
| Seiko Epson XP-211 214 216 Series    | 1        | 0.66%   |
| Seiko Epson WF-3520 Series           | 1        | 0.66%   |
| Seiko Epson WF-2010 Series           | 1        | 0.66%   |
| Seiko Epson L355 Series              | 1        | 0.66%   |
| Samsung SCX-4300 Series              | 1        | 0.66%   |
| Samsung SCX-4200 series              | 1        | 0.66%   |
| Samsung SCX-3400 Series              | 1        | 0.66%   |
| Samsung ML-1865                      | 1        | 0.66%   |
| Samsung M2070 Series                 | 1        | 0.66%   |
| Samsung C48x Series                  | 1        | 0.66%   |
| Samsung C43x Series                  | 1        | 0.66%   |
| Ricoh SP C260SFNw                    | 1        | 0.66%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 21       | 60%     |
| Seiko Epson        | 7        | 20%     |
| Ultima Electronics | 3        | 8.57%   |
| UMAX               | 1        | 2.86%   |
| Mustek Systems     | 1        | 2.86%   |
| Hewlett-Packard    | 1        | 2.86%   |
| AGFA-Gevaert NV    | 1        | 2.86%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5        | 14.29%  |
| Canon CanoScan LiDE 220                                                               | 4        | 11.43%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 8.57%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 5.71%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 5.71%   |
| Canon CanoScan LIDE 25                                                                | 2        | 5.71%   |
| Canon CanoScan LiDE 200                                                               | 2        | 5.71%   |
| UMAX Astra 2200/2200SU                                                                | 1        | 2.86%   |
| Ultima Artec E+ Pro                                                                   | 1        | 2.86%   |
| Seiko Epson Scanner                                                                   | 1        | 2.86%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 2.86%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 2.86%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 2.86%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 2.86%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1        | 2.86%   |
| HP Scanjet G2710                                                                      | 1        | 2.86%   |
| Canon CanoScan LiDE 90                                                                | 1        | 2.86%   |
| Canon CanoScan LiDE 70                                                                | 1        | 2.86%   |
| Canon CanoScan LiDE 210                                                               | 1        | 2.86%   |
| Canon CanoScan LiDE 110                                                               | 1        | 2.86%   |
| Canon CanoScan LiDE 100                                                               | 1        | 2.86%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1        | 2.86%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 253      | 35.58%  |
| Microdia                      | 62       | 8.72%   |
| Microsoft                     | 58       | 8.16%   |
| ARC International             | 27       | 3.8%    |
| Samsung Electronics           | 24       | 3.38%   |
| Apple                         | 23       | 3.23%   |
| Generalplus Technology        | 21       | 2.95%   |
| Sunplus Innovation Technology | 20       | 2.81%   |
| Realtek Semiconductor         | 19       | 2.67%   |
| GEMBIRD                       | 17       | 2.39%   |
| Creative Technology           | 16       | 2.25%   |
| Chicony Electronics           | 16       | 2.25%   |
| MacroSilicon                  | 14       | 1.97%   |
| Z-Star Microelectronics       | 12       | 1.69%   |
| Razer USA                     | 10       | 1.41%   |
| Hewlett-Packard               | 9        | 1.27%   |
| Aveo Technology               | 9        | 1.27%   |
| Huawei Technologies           | 8        | 1.13%   |
| Tobii Technology AB           | 6        | 0.84%   |
| WCM_USB                       | 5        | 0.7%    |
| Valve Software                | 4        | 0.56%   |
| SunplusIT                     | 4        | 0.56%   |
| Lenovo                        | 4        | 0.56%   |
| KYE Systems (Mouse Systems)   | 4        | 0.56%   |
| Genesys Logic                 | 4        | 0.56%   |
| Trust                         | 3        | 0.42%   |
| OmniVision Technologies       | 3        | 0.42%   |
| Arkmicro Technologies         | 3        | 0.42%   |
| YGTek                         | 2        | 0.28%   |
| ValueHD                       | 2        | 0.28%   |
| Sonix Technology              | 2        | 0.28%   |
| Quanta                        | 2        | 0.28%   |
| Oculus VR                     | 2        | 0.28%   |
| Nokia Mobile Phones           | 2        | 0.28%   |
| Linux Foundation              | 2        | 0.28%   |
| LG Electronics                | 2        | 0.28%   |
| Leap Motion                   | 2        | 0.28%   |
| HTC (High Tech Computer)      | 2        | 0.28%   |
| Google                        | 2        | 0.28%   |
| Cubeternet                    | 2        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 71       | 9.89%   |
| Logitech Webcam C270                              | 51       | 7.1%    |
| Microsoft LifeCam HD-3000                         | 28       | 3.9%    |
| ARC International Camera                          | 27       | 3.76%   |
| Samsung Galaxy series, misc. (MTP mode)           | 24       | 3.34%   |
| Microdia Webcam Vitade AF                         | 23       | 3.2%    |
| Apple iPhone 5/5C/5S/6/SE                         | 23       | 3.2%    |
| Microsoft LifeCam Cinema                          | 16       | 2.23%   |
| Logitech C922 Pro Stream Webcam                   | 16       | 2.23%   |
| Microdia USB 2.0 Camera                           | 14       | 1.95%   |
| MacroSilicon USB3. 0 capture                      | 14       | 1.95%   |
| Logitech HD Webcam C615                           | 12       | 1.67%   |
| Logitech C920 PRO HD Webcam                       | 11       | 1.53%   |
| Generalplus GENERAL WEBCAM                        | 11       | 1.53%   |
| Realtek Full HD webcam                            | 10       | 1.39%   |
| Logitech Webcam C930e                             | 10       | 1.39%   |
| Microdia USB Camera                               | 9        | 1.25%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 9        | 1.25%   |
| Logitech Webcam Pro 9000                          | 8        | 1.11%   |
| Logitech BRIO 4K Stream Edition                   | 8        | 1.11%   |
| Huawei HiCamera                                   | 8        | 1.11%   |
| GEMBIRD USB2.0 PC CAMERA                          | 8        | 1.11%   |
| Microdia Sonix USB 2.0 Camera                     | 7        | 0.97%   |
| Logitech Webcam C310                              | 7        | 0.97%   |
| Logitech B525 HD Webcam                           | 7        | 0.97%   |
| HP Webcam HD 2300                                 | 7        | 0.97%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 7        | 0.97%   |
| Tobii AB EyeChip                                  | 6        | 0.84%   |
| Sunplus WEBCAM ESSENTIELB W1                      | 6        | 0.84%   |
| Razer USA Gaming Webcam [Kiyo]                    | 6        | 0.84%   |
| Microdia Camera                                   | 6        | 0.84%   |
| Logitech Webcam C925e                             | 6        | 0.84%   |
| Logitech QuickCam Pro 9000                        | 6        | 0.84%   |
| WCM_USB WEB CAM                                   | 5        | 0.7%    |
| Logitech StreamCam                                | 5        | 0.7%    |
| Logitech HD Webcam C525                           | 5        | 0.7%    |
| Logitech BRIO Ultra HD Webcam                     | 5        | 0.7%    |
| Aveo USB2.0 Camera                                | 5        | 0.7%    |
| Z-Star Venus USB2.0 Camera                        | 4        | 0.56%   |
| Valve Software 3D Camera                          | 4        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 9        | 42.86%  |
| Synaptics                  | 5        | 23.81%  |
| STMicroelectronics         | 3        | 14.29%  |
| Shenzhen Goodix Technology | 2        | 9.52%   |
| LighTuning Technology      | 1        | 4.76%   |
| AuthenTec                  | 1        | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]  | 9        | 42.86%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 5        | 23.81%  |
| STMicroelectronics Fingerprint Reader        | 3        | 14.29%  |
| Shenzhen Goodix  Fingerprint Device          | 2        | 9.52%   |
| LighTuning ES603 Swipe Fingerprint Sensor    | 1        | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor         | 1        | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 6        | 46.15%  |
| OmniKey                   | 2        | 15.38%  |
| Yubico.com                | 1        | 7.69%   |
| Lenovo                    | 1        | 7.69%   |
| Hewlett-Packard           | 1        | 7.69%   |
| Bit4id                    | 1        | 7.69%   |
| Aladdin Knowledge Systems | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                  | 4        | 30.77%  |
| Alcor Micro AU9540 Smartcard Reader           | 2        | 15.38%  |
| Yubico.com Yubikey 4/5 CCID                   | 1        | 7.69%   |
| OmniKey CardMan 3021 / 3121                   | 1        | 7.69%   |
| OmniKey 3x21 Smart Card Reader                | 1        | 7.69%   |
| Lenovo Smartcard Keyboard                     | 1        | 7.69%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon) | 1        | 7.69%   |
| Bit4id miniLector EVO                         | 1        | 7.69%   |
| Aladdin Knowledge Systems Token JC            | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2696     | 79.88%  |
| 1     | 561      | 16.62%  |
| 2     | 86       | 2.55%   |
| 3     | 19       | 0.56%   |
| 4     | 7        | 0.21%   |
| 5     | 3        | 0.09%   |
| 7     | 2        | 0.06%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 285      | 37.16%  |
| Net/wireless             | 213      | 27.77%  |
| Communication controller | 51       | 6.65%   |
| Unassigned class         | 48       | 6.26%   |
| Sound                    | 41       | 5.35%   |
| Multimedia controller    | 31       | 4.04%   |
| Fingerprint reader       | 19       | 2.48%   |
| Camera                   | 18       | 2.35%   |
| Bluetooth                | 18       | 2.35%   |
| Chipcard                 | 10       | 1.3%    |
| Storage/raid             | 8        | 1.04%   |
| Net/ethernet             | 8        | 1.04%   |
| Network                  | 7        | 0.91%   |
| Modem                    | 3        | 0.39%   |
| Storage/ide              | 2        | 0.26%   |
| Card reader              | 2        | 0.26%   |
| Unclassified device      | 1        | 0.13%   |
| Storage                  | 1        | 0.13%   |
| Dvb card                 | 1        | 0.13%   |

