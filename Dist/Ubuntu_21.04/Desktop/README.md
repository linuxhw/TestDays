Ubuntu 21.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.04

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B360M-A               | [af2c7a813d](https://linux-hardware.org/?probe=af2c7a813d) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | [e17f08bb61](https://linux-hardware.org/?probe=e17f08bb61) | Sep 30, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [3977fe7bd2](https://linux-hardware.org/?probe=3977fe7bd2) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [c21eff0d32](https://linux-hardware.org/?probe=c21eff0d32) | Sep 28, 2021 |
| ASRock        | Z97 Anniversary             | [c2e1c947ca](https://linux-hardware.org/?probe=c2e1c947ca) | Sep 28, 2021 |
| Dell          | 0KV62T A01                  | [3d89663ced](https://linux-hardware.org/?probe=3d89663ced) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [3538c6368a](https://linux-hardware.org/?probe=3538c6368a) | Sep 28, 2021 |
| Dell          | 0D24M8 A01                  | [f1f58938d1](https://linux-hardware.org/?probe=f1f58938d1) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [38a7a4c1d4](https://linux-hardware.org/?probe=38a7a4c1d4) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [1f148a0dc9](https://linux-hardware.org/?probe=1f148a0dc9) | Sep 27, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [37d30a84ca](https://linux-hardware.org/?probe=37d30a84ca) | Sep 27, 2021 |
| Dell          | 0KV62T A01                  | [5792f11670](https://linux-hardware.org/?probe=5792f11670) | Sep 27, 2021 |
| ASUSTek       | PRIME X370-PRO              | [6886cfc383](https://linux-hardware.org/?probe=6886cfc383) | Sep 26, 2021 |
| MSI           | X399 SLI PLUS               | [4d6c77accb](https://linux-hardware.org/?probe=4d6c77accb) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [28a3e24d5a](https://linux-hardware.org/?probe=28a3e24d5a) | Sep 26, 2021 |
| ASRock        | A320M-HDV R4.0              | [c5da6d90b3](https://linux-hardware.org/?probe=c5da6d90b3) | Sep 26, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [4a373f1855](https://linux-hardware.org/?probe=4a373f1855) | Sep 26, 2021 |
| ASUSTek       | PRIME Z590-P                | [d2aaa88c7a](https://linux-hardware.org/?probe=d2aaa88c7a) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | [7be02e74b3](https://linux-hardware.org/?probe=7be02e74b3) | Sep 25, 2021 |
| Dell          | 0KV62T A01                  | [e441d709bd](https://linux-hardware.org/?probe=e441d709bd) | Sep 25, 2021 |
| ASUSTek       | PRIME H410M-A               | [dd082afe88](https://linux-hardware.org/?probe=dd082afe88) | Sep 24, 2021 |
| Gigabyte      | H310M S2 x.x                | [3aad736b24](https://linux-hardware.org/?probe=3aad736b24) | Sep 24, 2021 |
| ASRock        | Z390M Pro4                  | [449f4436f5](https://linux-hardware.org/?probe=449f4436f5) | Sep 24, 2021 |
| Gigabyte      | H310M S2 x.x                | [f52b1c6b1b](https://linux-hardware.org/?probe=f52b1c6b1b) | Sep 24, 2021 |
| HP            | 843F                        | [2160393dde](https://linux-hardware.org/?probe=2160393dde) | Sep 24, 2021 |
| HP            | 843F                        | [be648e45cb](https://linux-hardware.org/?probe=be648e45cb) | Sep 24, 2021 |
| ASUSTek       | A55BM-K                     | [e06893df36](https://linux-hardware.org/?probe=e06893df36) | Sep 24, 2021 |
| HP            | 18E4                        | [fbd08bc910](https://linux-hardware.org/?probe=fbd08bc910) | Sep 23, 2021 |
| Acer          | EG43M                       | [e355190768](https://linux-hardware.org/?probe=e355190768) | Sep 23, 2021 |
| Acer          | EG43M                       | [e9e005a181](https://linux-hardware.org/?probe=e9e005a181) | Sep 23, 2021 |
| HP            | 0AA8h                       | [b702f1c3a2](https://linux-hardware.org/?probe=b702f1c3a2) | Sep 23, 2021 |
| MSI           | Z87 MPOWER MAX              | [9405707012](https://linux-hardware.org/?probe=9405707012) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [b4bd76d198](https://linux-hardware.org/?probe=b4bd76d198) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc776de3a8](https://linux-hardware.org/?probe=bc776de3a8) | Sep 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [46af053a8e](https://linux-hardware.org/?probe=46af053a8e) | Sep 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [67338cd31a](https://linux-hardware.org/?probe=67338cd31a) | Sep 23, 2021 |
| HP            | 18E7                        | [4c52ebef48](https://linux-hardware.org/?probe=4c52ebef48) | Sep 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [4788d011ff](https://linux-hardware.org/?probe=4788d011ff) | Sep 22, 2021 |
| Gigabyte      | Z77-D3H                     | [fd1153a7da](https://linux-hardware.org/?probe=fd1153a7da) | Sep 22, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [ad1519a144](https://linux-hardware.org/?probe=ad1519a144) | Sep 22, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fd2b87b406](https://linux-hardware.org/?probe=fd2b87b406) | Sep 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [574ad39391](https://linux-hardware.org/?probe=574ad39391) | Sep 22, 2021 |
| Acer          | EG43M                       | [48c256116d](https://linux-hardware.org/?probe=48c256116d) | Sep 21, 2021 |
| Dell          | 0KV62T A01                  | [70b115b474](https://linux-hardware.org/?probe=70b115b474) | Sep 21, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [fce5a6bf2a](https://linux-hardware.org/?probe=fce5a6bf2a) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [b44b19f051](https://linux-hardware.org/?probe=b44b19f051) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | [323169caf9](https://linux-hardware.org/?probe=323169caf9) | Sep 21, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [ef22f8090a](https://linux-hardware.org/?probe=ef22f8090a) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASRock        | X570 Taichi                 | [ab2b72b7d5](https://linux-hardware.org/?probe=ab2b72b7d5) | Sep 20, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [d922af010d](https://linux-hardware.org/?probe=d922af010d) | Sep 19, 2021 |
| MSI           | MS-7058 100                 | [e8b0580c54](https://linux-hardware.org/?probe=e8b0580c54) | Sep 19, 2021 |
| ASUSTek       | B85M-G                      | [9f31d3090b](https://linux-hardware.org/?probe=9f31d3090b) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1d86899e9a](https://linux-hardware.org/?probe=1d86899e9a) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [b9c711e311](https://linux-hardware.org/?probe=b9c711e311) | Sep 19, 2021 |
| Dell          | 0X8582                      | [9e3d318898](https://linux-hardware.org/?probe=9e3d318898) | Sep 18, 2021 |
| Dell          | 0X8582                      | [e4ea4d8c3e](https://linux-hardware.org/?probe=e4ea4d8c3e) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | [c2a88904db](https://linux-hardware.org/?probe=c2a88904db) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | [3a21f72544](https://linux-hardware.org/?probe=3a21f72544) | Sep 18, 2021 |
| MSI           | A75MA-G55                   | [2e92160434](https://linux-hardware.org/?probe=2e92160434) | Sep 18, 2021 |
| Biostar       | A68MHE                      | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Acer          | FIH57                       | [af740ea4c9](https://linux-hardware.org/?probe=af740ea4c9) | Sep 18, 2021 |
| Acer          | FIH57                       | [1f486783b8](https://linux-hardware.org/?probe=1f486783b8) | Sep 18, 2021 |
| MSI           | MS-7058 100                 | [87a56cdea2](https://linux-hardware.org/?probe=87a56cdea2) | Sep 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [6ad44dcc58](https://linux-hardware.org/?probe=6ad44dcc58) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | [4340e989f9](https://linux-hardware.org/?probe=4340e989f9) | Sep 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [6a9d330973](https://linux-hardware.org/?probe=6a9d330973) | Sep 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [76f8472281](https://linux-hardware.org/?probe=76f8472281) | Sep 16, 2021 |
| HP            | 339A                        | [973b7c1b1f](https://linux-hardware.org/?probe=973b7c1b1f) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b2b889b773](https://linux-hardware.org/?probe=b2b889b773) | Sep 16, 2021 |
| HP            | 3048h                       | [b7b670e814](https://linux-hardware.org/?probe=b7b670e814) | Sep 16, 2021 |
| ASUSTek       | P6X58D-E                    | [1c61b20dd4](https://linux-hardware.org/?probe=1c61b20dd4) | Sep 16, 2021 |
| ASUSTek       | P8H77-M                     | [1efbf10e10](https://linux-hardware.org/?probe=1efbf10e10) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | [6209c3e2c2](https://linux-hardware.org/?probe=6209c3e2c2) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | [c5f600efd8](https://linux-hardware.org/?probe=c5f600efd8) | Sep 15, 2021 |
| HP            | 212B                        | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| HP            | 212B                        | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [67361acb38](https://linux-hardware.org/?probe=67361acb38) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [f7cc010076](https://linux-hardware.org/?probe=f7cc010076) | Sep 14, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| ASRock        | 970 Pro3 R2.0               | [2c4adbe9c5](https://linux-hardware.org/?probe=2c4adbe9c5) | Sep 14, 2021 |
| ASUSTek       | P5K-VM                      | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [7e07383aa8](https://linux-hardware.org/?probe=7e07383aa8) | Sep 14, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [51a17a84a4](https://linux-hardware.org/?probe=51a17a84a4) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | [a14cd2accb](https://linux-hardware.org/?probe=a14cd2accb) | Sep 13, 2021 |
| Gigabyte      | G1.Sniper 3                 | [4f79120f74](https://linux-hardware.org/?probe=4f79120f74) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | [442dd66231](https://linux-hardware.org/?probe=442dd66231) | Sep 13, 2021 |
| Acer          | EG43M                       | [1717308694](https://linux-hardware.org/?probe=1717308694) | Sep 13, 2021 |
| Dell          | 0X8582                      | [92c5cb4a65](https://linux-hardware.org/?probe=92c5cb4a65) | Sep 13, 2021 |
| Dell          | 0X8582                      | [2c9d4b560e](https://linux-hardware.org/?probe=2c9d4b560e) | Sep 13, 2021 |
| ASRock        | FM2A58M-DG3+                | [7433bea790](https://linux-hardware.org/?probe=7433bea790) | Sep 13, 2021 |
| Gigabyte      | G1.Sniper 3                 | [3d3b3161f5](https://linux-hardware.org/?probe=3d3b3161f5) | Sep 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [edb5bc2cac](https://linux-hardware.org/?probe=edb5bc2cac) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| ASUSTek       | Leonite2                    | [be99559571](https://linux-hardware.org/?probe=be99559571) | Sep 12, 2021 |
| Intel         | DQ57TM AAE70931-403         | [fca25108b4](https://linux-hardware.org/?probe=fca25108b4) | Sep 12, 2021 |
| Acer          | Revo RN96                   | [1559422fd4](https://linux-hardware.org/?probe=1559422fd4) | Sep 12, 2021 |
| Dell          | 0X8582                      | [59e615aa4c](https://linux-hardware.org/?probe=59e615aa4c) | Sep 12, 2021 |
| Dell          | 0X8582                      | [75d86d9235](https://linux-hardware.org/?probe=75d86d9235) | Sep 12, 2021 |
| Unknown       | G41                         | [0ac983ecc1](https://linux-hardware.org/?probe=0ac983ecc1) | Sep 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a11f12a84a](https://linux-hardware.org/?probe=a11f12a84a) | Sep 12, 2021 |
| Acer          | Revo RN96                   | [9bfcad9af4](https://linux-hardware.org/?probe=9bfcad9af4) | Sep 11, 2021 |
| ASRock        | FM2A58M-HD+                 | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| ASUSTek       | P6X58D PREMIUM              | [5f2cc29efc](https://linux-hardware.org/?probe=5f2cc29efc) | Sep 11, 2021 |
| ASUSTek       | H110M-C                     | [e73e96c866](https://linux-hardware.org/?probe=e73e96c866) | Sep 11, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| ASUSTek       | P8H77-M                     | [d1c9e9e744](https://linux-hardware.org/?probe=d1c9e9e744) | Sep 10, 2021 |
| ASUSTek       | P8H77-M                     | [088a432984](https://linux-hardware.org/?probe=088a432984) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [ab69e5a8f1](https://linux-hardware.org/?probe=ab69e5a8f1) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [20664604ad](https://linux-hardware.org/?probe=20664604ad) | Sep 10, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [0e6deb049c](https://linux-hardware.org/?probe=0e6deb049c) | Sep 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [cde32dbd89](https://linux-hardware.org/?probe=cde32dbd89) | Sep 09, 2021 |
| ASUSTek       | A68HM-PLUS                  | [443986835d](https://linux-hardware.org/?probe=443986835d) | Sep 09, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [f04053a978](https://linux-hardware.org/?probe=f04053a978) | Sep 08, 2021 |
| ASRock        | 970 Extreme3                | [2d9e427f68](https://linux-hardware.org/?probe=2d9e427f68) | Sep 08, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [46f2f68684](https://linux-hardware.org/?probe=46f2f68684) | Sep 07, 2021 |
| ASUSTek       | AM1M-A                      | [4963032754](https://linux-hardware.org/?probe=4963032754) | Sep 07, 2021 |
| Intel         | DQ57TM AAE70931-403         | [6add940021](https://linux-hardware.org/?probe=6add940021) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | [ddee404146](https://linux-hardware.org/?probe=ddee404146) | Sep 07, 2021 |
| ASRock        | B75M-GL R2.0                | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [78414d4d44](https://linux-hardware.org/?probe=78414d4d44) | Sep 07, 2021 |
| Acer          | Aspire XC-830               | [859878d1b2](https://linux-hardware.org/?probe=859878d1b2) | Sep 06, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [463f501179](https://linux-hardware.org/?probe=463f501179) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | [ee58e16f17](https://linux-hardware.org/?probe=ee58e16f17) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | [c18c52cd70](https://linux-hardware.org/?probe=c18c52cd70) | Sep 06, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3259aff6f6](https://linux-hardware.org/?probe=3259aff6f6) | Sep 06, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 870C                        | [f46fa4ba94](https://linux-hardware.org/?probe=f46fa4ba94) | Sep 06, 2021 |
| HP            | 870C                        | [fcd88590bc](https://linux-hardware.org/?probe=fcd88590bc) | Sep 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [129a34a37f](https://linux-hardware.org/?probe=129a34a37f) | Sep 06, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [e72963a1b5](https://linux-hardware.org/?probe=e72963a1b5) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [28a20b5f72](https://linux-hardware.org/?probe=28a20b5f72) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c6e769829b](https://linux-hardware.org/?probe=c6e769829b) | Sep 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e52c4a231c](https://linux-hardware.org/?probe=e52c4a231c) | Sep 05, 2021 |
| ASUSTek       | P6X58D-E                    | [f1300c2d55](https://linux-hardware.org/?probe=f1300c2d55) | Sep 05, 2021 |
| ASRock        | B365M Pro4                  | [a244333b78](https://linux-hardware.org/?probe=a244333b78) | Sep 05, 2021 |
| HP            | 339A                        | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HP            | ProLiant MicroServer        | [69ca9e90ae](https://linux-hardware.org/?probe=69ca9e90ae) | Sep 05, 2021 |
| ASUSTek       | AM1M-A                      | [bbe431b15f](https://linux-hardware.org/?probe=bbe431b15f) | Sep 04, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| HP            | 1494                        | [064f4ff59f](https://linux-hardware.org/?probe=064f4ff59f) | Sep 04, 2021 |
| ASUSTek       | AM1M-A                      | [4d7a9bb2cf](https://linux-hardware.org/?probe=4d7a9bb2cf) | Sep 04, 2021 |
| ASRock        | FM2A58M-HD+                 | [5162b02b61](https://linux-hardware.org/?probe=5162b02b61) | Sep 04, 2021 |
| Pegatron      | Maureen                     | [c5ab105ead](https://linux-hardware.org/?probe=c5ab105ead) | Sep 04, 2021 |
| ASRock        | A300M-STX                   | [811f366c65](https://linux-hardware.org/?probe=811f366c65) | Sep 03, 2021 |
| ASRock        | Z370 Pro4                   | [a507f9835b](https://linux-hardware.org/?probe=a507f9835b) | Sep 03, 2021 |
| Gigabyte      | B85M-D3H                    | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| Pegatron      | Maureen                     | [8591d54048](https://linux-hardware.org/?probe=8591d54048) | Sep 03, 2021 |
| ASUSTek       | P7P55D LE                   | [8bbe7e58ae](https://linux-hardware.org/?probe=8bbe7e58ae) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | [21fd5c096a](https://linux-hardware.org/?probe=21fd5c096a) | Sep 02, 2021 |
| MSI           | TRX40 PRO WIFI              | [d337b01cb3](https://linux-hardware.org/?probe=d337b01cb3) | Sep 02, 2021 |
| Biostar       | H77MU3                      | [82f367ec4b](https://linux-hardware.org/?probe=82f367ec4b) | Sep 02, 2021 |
| ASUSTek       | Z87-EXPERT                  | [f8846969fd](https://linux-hardware.org/?probe=f8846969fd) | Sep 02, 2021 |
| ASRock        | FM2A58M-HD+                 | [5ffaa68de4](https://linux-hardware.org/?probe=5ffaa68de4) | Sep 01, 2021 |
| HP            | 18E9                        | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [796e78b6ac](https://linux-hardware.org/?probe=796e78b6ac) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [0a0d13044d](https://linux-hardware.org/?probe=0a0d13044d) | Sep 01, 2021 |
| HP            | 1998                        | [585ff46bb3](https://linux-hardware.org/?probe=585ff46bb3) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [cde0de2a3d](https://linux-hardware.org/?probe=cde0de2a3d) | Sep 01, 2021 |
| FIRICH        | J1900                       | [a682347a14](https://linux-hardware.org/?probe=a682347a14) | Sep 01, 2021 |
| Gigabyte      | F2A55M-HD2                  | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [fffa0ed19a](https://linux-hardware.org/?probe=fffa0ed19a) | Aug 31, 2021 |
| Gigabyte      | Z370 HD3P-CF                | [0f8fe06e8f](https://linux-hardware.org/?probe=0f8fe06e8f) | Aug 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [9c16c770be](https://linux-hardware.org/?probe=9c16c770be) | Aug 31, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [e689b2de7a](https://linux-hardware.org/?probe=e689b2de7a) | Aug 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [078613f010](https://linux-hardware.org/?probe=078613f010) | Aug 31, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [02cd32fbb4](https://linux-hardware.org/?probe=02cd32fbb4) | Aug 30, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [b5459f613b](https://linux-hardware.org/?probe=b5459f613b) | Aug 30, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e829df72a5](https://linux-hardware.org/?probe=e829df72a5) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | [47ba00786a](https://linux-hardware.org/?probe=47ba00786a) | Aug 30, 2021 |
| Acer          | EG43M                       | [900788bdab](https://linux-hardware.org/?probe=900788bdab) | Aug 30, 2021 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [47c72f21ae](https://linux-hardware.org/?probe=47c72f21ae) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [f4e788dce6](https://linux-hardware.org/?probe=f4e788dce6) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [8f5b776bcb](https://linux-hardware.org/?probe=8f5b776bcb) | Aug 30, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [4771af382d](https://linux-hardware.org/?probe=4771af382d) | Aug 30, 2021 |
| MSI           | P67A-C45                    | [5f5d217d7b](https://linux-hardware.org/?probe=5f5d217d7b) | Aug 30, 2021 |
| MSI           | P67A-C45                    | [8f1d2c8ca0](https://linux-hardware.org/?probe=8f1d2c8ca0) | Aug 30, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | [2ca1595715](https://linux-hardware.org/?probe=2ca1595715) | Aug 30, 2021 |
| ASUSTek       | P6X58D-E                    | [a2c8bb417d](https://linux-hardware.org/?probe=a2c8bb417d) | Aug 29, 2021 |
| Gigabyte      | H55-USB3                    | [ae6cbc8dd8](https://linux-hardware.org/?probe=ae6cbc8dd8) | Aug 29, 2021 |
| ASRock        | FM2A58M-HD+                 | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| HP            | 18E9                        | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Foxconn       | 2ABF                        | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| Gigabyte      | A320M-H-CF                  | [a089d56f43](https://linux-hardware.org/?probe=a089d56f43) | Aug 29, 2021 |
| Gigabyte      | Z77-DS3H                    | [e06775bbd6](https://linux-hardware.org/?probe=e06775bbd6) | Aug 29, 2021 |
| HP            | 3397                        | [abf1615138](https://linux-hardware.org/?probe=abf1615138) | Aug 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | [99b7f572be](https://linux-hardware.org/?probe=99b7f572be) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | [593479bed8](https://linux-hardware.org/?probe=593479bed8) | Aug 28, 2021 |
| ASUSTek       | PRIME Z270-A                | [9e81caf509](https://linux-hardware.org/?probe=9e81caf509) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [04c8ccfac4](https://linux-hardware.org/?probe=04c8ccfac4) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2ad8401f8f](https://linux-hardware.org/?probe=2ad8401f8f) | Aug 28, 2021 |
| Pegatron      | IPMSB-GS                    | [b17f032a44](https://linux-hardware.org/?probe=b17f032a44) | Aug 27, 2021 |
| HP            | 2B34                        | [9477a88acd](https://linux-hardware.org/?probe=9477a88acd) | Aug 27, 2021 |
| Gigabyte      | P41T-USB3L                  | [e234ec66f2](https://linux-hardware.org/?probe=e234ec66f2) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | [9d2bbbabf1](https://linux-hardware.org/?probe=9d2bbbabf1) | Aug 27, 2021 |
| Dell          | 0R790T A00                  | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Shuttle       | FH61V                       | [11b6744d1c](https://linux-hardware.org/?probe=11b6744d1c) | Aug 27, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7f80b632ce](https://linux-hardware.org/?probe=7f80b632ce) | Aug 26, 2021 |
| MSI           | X399 SLI PLUS               | [9efc402bb3](https://linux-hardware.org/?probe=9efc402bb3) | Aug 26, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c8198b5d21](https://linux-hardware.org/?probe=c8198b5d21) | Aug 26, 2021 |
| ASUSTek       | Z97-P                       | [1fc077ad52](https://linux-hardware.org/?probe=1fc077ad52) | Aug 26, 2021 |
| HP            | 1494                        | [29bc1c62ad](https://linux-hardware.org/?probe=29bc1c62ad) | Aug 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | [2f9e0312b5](https://linux-hardware.org/?probe=2f9e0312b5) | Aug 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [05957888bc](https://linux-hardware.org/?probe=05957888bc) | Aug 25, 2021 |
| HP            | 8768 A                      | [40e82f4d4f](https://linux-hardware.org/?probe=40e82f4d4f) | Aug 25, 2021 |
| Shuttle       | FH61V                       | [17f1c616de](https://linux-hardware.org/?probe=17f1c616de) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | [870deaf9fd](https://linux-hardware.org/?probe=870deaf9fd) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | [4b952eb1ae](https://linux-hardware.org/?probe=4b952eb1ae) | Aug 25, 2021 |
| Shuttle       | FH61V                       | [1b74c0ad1d](https://linux-hardware.org/?probe=1b74c0ad1d) | Aug 25, 2021 |
| Dell          | 03NVJ6 A02                  | [75869e33b7](https://linux-hardware.org/?probe=75869e33b7) | Aug 25, 2021 |
| Medion        | MS-7501                     | [c84fb9217e](https://linux-hardware.org/?probe=c84fb9217e) | Aug 25, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| HP            | 8054                        | [d54cd14c63](https://linux-hardware.org/?probe=d54cd14c63) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e9e6b8b426](https://linux-hardware.org/?probe=e9e6b8b426) | Aug 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [cd71732431](https://linux-hardware.org/?probe=cd71732431) | Aug 24, 2021 |
| ASRock        | Q77M vPro                   | [f53a9f288f](https://linux-hardware.org/?probe=f53a9f288f) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [8a59fff598](https://linux-hardware.org/?probe=8a59fff598) | Aug 24, 2021 |
| Gigabyte      | H510M S2H                   | [c10c8ceffe](https://linux-hardware.org/?probe=c10c8ceffe) | Aug 23, 2021 |
| Gigabyte      | F2A78M-HD2                  | [410b6b854f](https://linux-hardware.org/?probe=410b6b854f) | Aug 23, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [c5414322d8](https://linux-hardware.org/?probe=c5414322d8) | Aug 23, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [28c1656add](https://linux-hardware.org/?probe=28c1656add) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [a0805b7ffd](https://linux-hardware.org/?probe=a0805b7ffd) | Aug 23, 2021 |
| Gigabyte      | F2A55M-HD2                  | [51f33816d5](https://linux-hardware.org/?probe=51f33816d5) | Aug 22, 2021 |
| HP            | ProLiant ML350 G6           | [d89bfcf1f9](https://linux-hardware.org/?probe=d89bfcf1f9) | Aug 22, 2021 |
| HP            | 1494                        | [414b1c48e7](https://linux-hardware.org/?probe=414b1c48e7) | Aug 22, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1c910aa761](https://linux-hardware.org/?probe=1c910aa761) | Aug 22, 2021 |
| Gigabyte      | A320M-H-CF                  | [1c1434ce76](https://linux-hardware.org/?probe=1c1434ce76) | Aug 21, 2021 |
| Acer          | EG43M                       | [3c17aecee4](https://linux-hardware.org/?probe=3c17aecee4) | Aug 21, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e9b8721812](https://linux-hardware.org/?probe=e9b8721812) | Aug 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [d3340be343](https://linux-hardware.org/?probe=d3340be343) | Aug 20, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [0c8cadf01b](https://linux-hardware.org/?probe=0c8cadf01b) | Aug 20, 2021 |
| ASUSTek       | M2N-E SLI                   | [149d762d08](https://linux-hardware.org/?probe=149d762d08) | Aug 20, 2021 |
| Gigabyte      | H87M-HD3                    | [bdc2409477](https://linux-hardware.org/?probe=bdc2409477) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | [7e1f4b1620](https://linux-hardware.org/?probe=7e1f4b1620) | Aug 20, 2021 |
| MSI           | MEG X570 UNIFY              | [c4800a930a](https://linux-hardware.org/?probe=c4800a930a) | Aug 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [bffc40c965](https://linux-hardware.org/?probe=bffc40c965) | Aug 19, 2021 |
| Gigabyte      | H61M-S1                     | [0223d6864b](https://linux-hardware.org/?probe=0223d6864b) | Aug 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [0c1d976c3c](https://linux-hardware.org/?probe=0c1d976c3c) | Aug 19, 2021 |
| Dell          | 0M5DCD A00                  | [5c98a0115b](https://linux-hardware.org/?probe=5c98a0115b) | Aug 19, 2021 |
| Gigabyte      | P41T-USB3L                  | [e983759ddc](https://linux-hardware.org/?probe=e983759ddc) | Aug 19, 2021 |
| Gigabyte      | H310M S2 x.x                | [e26140d6a5](https://linux-hardware.org/?probe=e26140d6a5) | Aug 19, 2021 |
| ASRock        | 970 Extreme3                | [40aa5bc719](https://linux-hardware.org/?probe=40aa5bc719) | Aug 19, 2021 |
| MSI           | B450-A PRO MAX              | [7cf3758630](https://linux-hardware.org/?probe=7cf3758630) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [5b2b23ac97](https://linux-hardware.org/?probe=5b2b23ac97) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [4c1a100ab1](https://linux-hardware.org/?probe=4c1a100ab1) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [810f986c77](https://linux-hardware.org/?probe=810f986c77) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [a20cebc67a](https://linux-hardware.org/?probe=a20cebc67a) | Aug 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [0fb8f12bfc](https://linux-hardware.org/?probe=0fb8f12bfc) | Aug 18, 2021 |
| Gigabyte      | H310M S2 x.x                | [5b1f68ea4d](https://linux-hardware.org/?probe=5b1f68ea4d) | Aug 18, 2021 |
| ASUSTek       | M5A78L LE                   | [8e26bae3fc](https://linux-hardware.org/?probe=8e26bae3fc) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | [9bed63f2f6](https://linux-hardware.org/?probe=9bed63f2f6) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | [8885a008e0](https://linux-hardware.org/?probe=8885a008e0) | Aug 18, 2021 |
| Gigabyte      | G41M-ES2L                   | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| MSI           | B450-A PRO MAX              | [38ce4c1114](https://linux-hardware.org/?probe=38ce4c1114) | Aug 18, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [8596bc4b0e](https://linux-hardware.org/?probe=8596bc4b0e) | Aug 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [eb1e9924f7](https://linux-hardware.org/?probe=eb1e9924f7) | Aug 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [515021a70a](https://linux-hardware.org/?probe=515021a70a) | Aug 18, 2021 |
| Gigabyte      | H310M S2 x.x                | [53873c7c63](https://linux-hardware.org/?probe=53873c7c63) | Aug 17, 2021 |
| Gigabyte      | H310M S2 x.x                | [462df98aea](https://linux-hardware.org/?probe=462df98aea) | Aug 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [b446e80e0a](https://linux-hardware.org/?probe=b446e80e0a) | Aug 17, 2021 |
| Gigabyte      | H310M S2 x.x                | [3e3018cc57](https://linux-hardware.org/?probe=3e3018cc57) | Aug 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [5a4eb4b728](https://linux-hardware.org/?probe=5a4eb4b728) | Aug 17, 2021 |
| HP            | 1494                        | [df10192c5b](https://linux-hardware.org/?probe=df10192c5b) | Aug 16, 2021 |
| ASUSTek       | B150M-C                     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| Medion        | MS-7707                     | [66ace31297](https://linux-hardware.org/?probe=66ace31297) | Aug 16, 2021 |
| Unknown       | Unknown                     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| Dell          | 082WXT A01                  | [e6b9ac8959](https://linux-hardware.org/?probe=e6b9ac8959) | Aug 16, 2021 |
| Lenovo        | 0B98401 PRO                 | [537aee667d](https://linux-hardware.org/?probe=537aee667d) | Aug 16, 2021 |
| ASUSTek       | Basswood                    | [f42051fa02](https://linux-hardware.org/?probe=f42051fa02) | Aug 15, 2021 |
| Gigabyte      | X99-SLI-CF                  | [27f528f809](https://linux-hardware.org/?probe=27f528f809) | Aug 15, 2021 |
| ASUSTek       | P8H67                       | [7c1b975d25](https://linux-hardware.org/?probe=7c1b975d25) | Aug 15, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [696380b374](https://linux-hardware.org/?probe=696380b374) | Aug 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [5076334ae6](https://linux-hardware.org/?probe=5076334ae6) | Aug 15, 2021 |
| Dell          | 0NK5PH A00                  | [676c2b2a79](https://linux-hardware.org/?probe=676c2b2a79) | Aug 14, 2021 |
| ASRock        | H97M Pro4                   | [5edf7e02c8](https://linux-hardware.org/?probe=5edf7e02c8) | Aug 14, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [74d3e5803f](https://linux-hardware.org/?probe=74d3e5803f) | Aug 14, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [3d5cb99ee5](https://linux-hardware.org/?probe=3d5cb99ee5) | Aug 14, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [e2d8270403](https://linux-hardware.org/?probe=e2d8270403) | Aug 13, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [e9e0bafaee](https://linux-hardware.org/?probe=e9e0bafaee) | Aug 13, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [424787c9b9](https://linux-hardware.org/?probe=424787c9b9) | Aug 13, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [fec985ca69](https://linux-hardware.org/?probe=fec985ca69) | Aug 13, 2021 |
| Gigabyte      | Z170XP-SLI-CF               | [1174eec6c2](https://linux-hardware.org/?probe=1174eec6c2) | Aug 13, 2021 |
| Acer          | Veriton X2631G V:1.0        | [d0db0c37b0](https://linux-hardware.org/?probe=d0db0c37b0) | Aug 12, 2021 |
| Acer          | Veriton X2631G V:1.0        | [8ffd94b29c](https://linux-hardware.org/?probe=8ffd94b29c) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [adde6ef882](https://linux-hardware.org/?probe=adde6ef882) | Aug 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [02f3303081](https://linux-hardware.org/?probe=02f3303081) | Aug 12, 2021 |
| ASRock        | B550M-ITX/ac                | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| ECS           | Asterope3                   | [9255f2e941](https://linux-hardware.org/?probe=9255f2e941) | Aug 10, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [2af094f75d](https://linux-hardware.org/?probe=2af094f75d) | Aug 10, 2021 |
| ASUSTek       | M5A78L LE                   | [ae67208b0e](https://linux-hardware.org/?probe=ae67208b0e) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [8beee2f359](https://linux-hardware.org/?probe=8beee2f359) | Aug 10, 2021 |
| ASUSTek       | D642MF                      | [e50f269bc9](https://linux-hardware.org/?probe=e50f269bc9) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [d2e35c6ccb](https://linux-hardware.org/?probe=d2e35c6ccb) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [88dcb8813a](https://linux-hardware.org/?probe=88dcb8813a) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [07fad2e81c](https://linux-hardware.org/?probe=07fad2e81c) | Aug 10, 2021 |
| HP            | 87D6 SMVB                   | [7e4cda26e2](https://linux-hardware.org/?probe=7e4cda26e2) | Aug 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7979b23ea9](https://linux-hardware.org/?probe=7979b23ea9) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [aaf4f26a30](https://linux-hardware.org/?probe=aaf4f26a30) | Aug 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ea239f2f82](https://linux-hardware.org/?probe=ea239f2f82) | Aug 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [b01f2c504d](https://linux-hardware.org/?probe=b01f2c504d) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c42793eeff](https://linux-hardware.org/?probe=c42793eeff) | Aug 08, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | [a1ad011d2c](https://linux-hardware.org/?probe=a1ad011d2c) | Aug 08, 2021 |
| Foxconn       | 2A8C                        | [7123b6c779](https://linux-hardware.org/?probe=7123b6c779) | Aug 08, 2021 |
| Lenovo        | Board                       | [b4fe0907aa](https://linux-hardware.org/?probe=b4fe0907aa) | Aug 08, 2021 |
| Lenovo        | Board                       | [13d5b7a5b0](https://linux-hardware.org/?probe=13d5b7a5b0) | Aug 08, 2021 |
| HP            | 1998                        | [b0e8ef9aa2](https://linux-hardware.org/?probe=b0e8ef9aa2) | Aug 08, 2021 |
| ASRock        | 970 Extreme3                | [c08aa58f01](https://linux-hardware.org/?probe=c08aa58f01) | Aug 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [8c36ac6a56](https://linux-hardware.org/?probe=8c36ac6a56) | Aug 07, 2021 |
| MSI           | Z97 GAMING 9 AC             | [17ce8c5436](https://linux-hardware.org/?probe=17ce8c5436) | Aug 07, 2021 |
| ASUSTek       | M5A78L LE                   | [9d934a3df1](https://linux-hardware.org/?probe=9d934a3df1) | Aug 07, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [fd15e7b399](https://linux-hardware.org/?probe=fd15e7b399) | Aug 07, 2021 |
| ASUSTek       | M5A78L LE                   | [32192f4588](https://linux-hardware.org/?probe=32192f4588) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | [21e4e5c57d](https://linux-hardware.org/?probe=21e4e5c57d) | Aug 07, 2021 |
| Lenovo        | Board                       | [a053325efe](https://linux-hardware.org/?probe=a053325efe) | Aug 06, 2021 |
| Gigabyte      | A320M-S2H-CF                | [09fa4c99dc](https://linux-hardware.org/?probe=09fa4c99dc) | Aug 06, 2021 |
| Lenovo        | Board                       | [2415e3e33f](https://linux-hardware.org/?probe=2415e3e33f) | Aug 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c149c02018](https://linux-hardware.org/?probe=c149c02018) | Aug 06, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [463d805b1e](https://linux-hardware.org/?probe=463d805b1e) | Aug 06, 2021 |
| Acer          | Veriton X2631G V:1.0        | [7306d11e16](https://linux-hardware.org/?probe=7306d11e16) | Aug 06, 2021 |
| MSI           | Z370 TOMAHAWK               | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Gigabyte      | B85M-D3H                    | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [f892a56ee0](https://linux-hardware.org/?probe=f892a56ee0) | Aug 05, 2021 |
| ASUSTek       | M4A78 PRO                   | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| Dell          | 03NVJ6 A02                  | [a2a1574d81](https://linux-hardware.org/?probe=a2a1574d81) | Aug 04, 2021 |
| MSI           | 2A9C                        | [3616ca63df](https://linux-hardware.org/?probe=3616ca63df) | Aug 04, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [422b3a9c80](https://linux-hardware.org/?probe=422b3a9c80) | Aug 04, 2021 |
| Biostar       | A68MHE                      | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [88534a17b6](https://linux-hardware.org/?probe=88534a17b6) | Aug 03, 2021 |
| Gigabyte      | Z87M-D3H                    | [e679a451ab](https://linux-hardware.org/?probe=e679a451ab) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | [282ecb40ca](https://linux-hardware.org/?probe=282ecb40ca) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | [ce156e88b0](https://linux-hardware.org/?probe=ce156e88b0) | Aug 03, 2021 |
| ASUSTek       | M3N78 PRO                   | [dda6e493b7](https://linux-hardware.org/?probe=dda6e493b7) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | [d976766cee](https://linux-hardware.org/?probe=d976766cee) | Aug 03, 2021 |
| Foxconn       | 2A8C                        | [67e965bb06](https://linux-hardware.org/?probe=67e965bb06) | Aug 02, 2021 |
| MSI           | G31M3-F V2                  | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [cb617ee0fa](https://linux-hardware.org/?probe=cb617ee0fa) | Aug 02, 2021 |
| ASUSTek       | P7Q57-M DO                  | [e14cd31bf6](https://linux-hardware.org/?probe=e14cd31bf6) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | [39b2e07348](https://linux-hardware.org/?probe=39b2e07348) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | [aaece9a4d4](https://linux-hardware.org/?probe=aaece9a4d4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [2c67644e4c](https://linux-hardware.org/?probe=2c67644e4c) | Aug 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [767bc19ec8](https://linux-hardware.org/?probe=767bc19ec8) | Jul 31, 2021 |
| ASRock        | N68C-S UCC                  | [3b4a485e30](https://linux-hardware.org/?probe=3b4a485e30) | Jul 31, 2021 |
| Gigabyte      | G41M-ES2H                   | [ba0824b1c9](https://linux-hardware.org/?probe=ba0824b1c9) | Jul 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| ASRock        | H470M-HVS                   | [97dbb1b8b9](https://linux-hardware.org/?probe=97dbb1b8b9) | Jul 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [4a27442871](https://linux-hardware.org/?probe=4a27442871) | Jul 30, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [d3e4773f47](https://linux-hardware.org/?probe=d3e4773f47) | Jul 30, 2021 |
| ASRock        | Z170 OC Formula             | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| MSI           | H510M PRO                   | [6b204e25a9](https://linux-hardware.org/?probe=6b204e25a9) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | [8eba192a2d](https://linux-hardware.org/?probe=8eba192a2d) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | [d2cd2288c7](https://linux-hardware.org/?probe=d2cd2288c7) | Jul 29, 2021 |
| MSI           | H510I PRO WIFI              | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| MSI           | G31TM-P21                   | [024df6a0c1](https://linux-hardware.org/?probe=024df6a0c1) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Gigabyte      | G41M-ES2H                   | [04b060a090](https://linux-hardware.org/?probe=04b060a090) | Jul 29, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [55f86a29a2](https://linux-hardware.org/?probe=55f86a29a2) | Jul 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [41c1c2551d](https://linux-hardware.org/?probe=41c1c2551d) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASRock        | 970 Extreme3                | [4769f95bad](https://linux-hardware.org/?probe=4769f95bad) | Jul 29, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [8fe5a59e53](https://linux-hardware.org/?probe=8fe5a59e53) | Jul 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [844de3ccbf](https://linux-hardware.org/?probe=844de3ccbf) | Jul 28, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [6fcd0a6b24](https://linux-hardware.org/?probe=6fcd0a6b24) | Jul 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [67a1d9bcc9](https://linux-hardware.org/?probe=67a1d9bcc9) | Jul 27, 2021 |
| MSI           | B450M PRO-VDH MAX           | [8a24dd720f](https://linux-hardware.org/?probe=8a24dd720f) | Jul 27, 2021 |
| Intel         | BTC-T37                     | [758e5d4332](https://linux-hardware.org/?probe=758e5d4332) | Jul 27, 2021 |
| Intel         | BTC-T37                     | [000e132ac1](https://linux-hardware.org/?probe=000e132ac1) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | [588c5ca9f6](https://linux-hardware.org/?probe=588c5ca9f6) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | [d7369d7eb4](https://linux-hardware.org/?probe=d7369d7eb4) | Jul 26, 2021 |
| ASUSTek       | Z97-P                       | [ef88333344](https://linux-hardware.org/?probe=ef88333344) | Jul 26, 2021 |
| ASRock        | 970 Extreme3                | [b99b48ada3](https://linux-hardware.org/?probe=b99b48ada3) | Jul 26, 2021 |
| ASUSTek       | H110M-R                     | [87ca1f0bda](https://linux-hardware.org/?probe=87ca1f0bda) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3185d49877](https://linux-hardware.org/?probe=3185d49877) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [66e10b64e4](https://linux-hardware.org/?probe=66e10b64e4) | Jul 26, 2021 |
| Dell          | 0R790T A00                  | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Dell          | 0RY007                      | [f2cd48444a](https://linux-hardware.org/?probe=f2cd48444a) | Jul 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [527a02f609](https://linux-hardware.org/?probe=527a02f609) | Jul 25, 2021 |
| ASUSTek       | Rampage III Extreme         | [f637e33171](https://linux-hardware.org/?probe=f637e33171) | Jul 25, 2021 |
| ASUSTek       | B150M-K                     | [34e2582dc2](https://linux-hardware.org/?probe=34e2582dc2) | Jul 25, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [acc53aae10](https://linux-hardware.org/?probe=acc53aae10) | Jul 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [02dad54406](https://linux-hardware.org/?probe=02dad54406) | Jul 25, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c99742c8ed](https://linux-hardware.org/?probe=c99742c8ed) | Jul 25, 2021 |
| MSI           | Z490-A PRO                  | [740f322568](https://linux-hardware.org/?probe=740f322568) | Jul 25, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [4f7db30451](https://linux-hardware.org/?probe=4f7db30451) | Jul 24, 2021 |
| HP            | 212B                        | [2ae8fe394a](https://linux-hardware.org/?probe=2ae8fe394a) | Jul 24, 2021 |
| Dell          | 0D24M8 A01                  | [2080a71bc0](https://linux-hardware.org/?probe=2080a71bc0) | Jul 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [3d2cd06389](https://linux-hardware.org/?probe=3d2cd06389) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [aa0949f27f](https://linux-hardware.org/?probe=aa0949f27f) | Jul 24, 2021 |
| ASRock        | 970 Extreme3                | [eb85761dc0](https://linux-hardware.org/?probe=eb85761dc0) | Jul 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [61aa66455b](https://linux-hardware.org/?probe=61aa66455b) | Jul 23, 2021 |
| MSI           | H110M PRO-VH                | [42bd7fe7d2](https://linux-hardware.org/?probe=42bd7fe7d2) | Jul 23, 2021 |
| MSI           | 3664h                       | [8141885507](https://linux-hardware.org/?probe=8141885507) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | [c0e89d7f2c](https://linux-hardware.org/?probe=c0e89d7f2c) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | [53b9087fbb](https://linux-hardware.org/?probe=53b9087fbb) | Jul 23, 2021 |
| Gigabyte      | 945GCMX-S2                  | [c9d0df911e](https://linux-hardware.org/?probe=c9d0df911e) | Jul 23, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [fdd7765da0](https://linux-hardware.org/?probe=fdd7765da0) | Jul 23, 2021 |
| ASUSTek       | TUF GAMING B560M-PLUS WI... | [bc81196561](https://linux-hardware.org/?probe=bc81196561) | Jul 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [81c950f0e4](https://linux-hardware.org/?probe=81c950f0e4) | Jul 22, 2021 |
| Acer          | WMCP78M                     | [591c077e28](https://linux-hardware.org/?probe=591c077e28) | Jul 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [f00892d38b](https://linux-hardware.org/?probe=f00892d38b) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | [62eca59ba3](https://linux-hardware.org/?probe=62eca59ba3) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | [c469ee9d35](https://linux-hardware.org/?probe=c469ee9d35) | Jul 22, 2021 |
| Acer          | WMCP78M                     | [4d35606ff5](https://linux-hardware.org/?probe=4d35606ff5) | Jul 22, 2021 |
| Acer          | Aspire TC-780               | [cc39834e1d](https://linux-hardware.org/?probe=cc39834e1d) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | [900229235e](https://linux-hardware.org/?probe=900229235e) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | [c1dcbf95e4](https://linux-hardware.org/?probe=c1dcbf95e4) | Jul 21, 2021 |
| Dell          | 00FKMJ A00                  | [0b4299bc41](https://linux-hardware.org/?probe=0b4299bc41) | Jul 21, 2021 |
| Gigabyte      | Z87M-D3H                    | [382d63f2b6](https://linux-hardware.org/?probe=382d63f2b6) | Jul 21, 2021 |
| Gigabyte      | Z87M-D3H                    | [85533714a5](https://linux-hardware.org/?probe=85533714a5) | Jul 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8c093d0560](https://linux-hardware.org/?probe=8c093d0560) | Jul 20, 2021 |
| HP            | 3397                        | [7626063783](https://linux-hardware.org/?probe=7626063783) | Jul 20, 2021 |
| HP            | 3397                        | [38dfe540f7](https://linux-hardware.org/?probe=38dfe540f7) | Jul 20, 2021 |
| Gigabyte      | B250-FinTech-CF             | [58b1c1aecf](https://linux-hardware.org/?probe=58b1c1aecf) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [8e68827883](https://linux-hardware.org/?probe=8e68827883) | Jul 20, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [4788bcc4d5](https://linux-hardware.org/?probe=4788bcc4d5) | Jul 20, 2021 |
| PCWare        | IPMH61R1                    | [1212ad03e9](https://linux-hardware.org/?probe=1212ad03e9) | Jul 20, 2021 |
| ASRock        | 970 Extreme3                | [1bdc5d46a3](https://linux-hardware.org/?probe=1bdc5d46a3) | Jul 19, 2021 |
| MSI           | H110M PRO-VH                | [d324faa498](https://linux-hardware.org/?probe=d324faa498) | Jul 19, 2021 |
| MSI           | 890GXM-G65                  | [ae86741130](https://linux-hardware.org/?probe=ae86741130) | Jul 19, 2021 |
| ASUSTek       | PRIME A320M-K               | [fb9c551dd7](https://linux-hardware.org/?probe=fb9c551dd7) | Jul 19, 2021 |
| Unknown       | Unknown                     | [5faacb9f0b](https://linux-hardware.org/?probe=5faacb9f0b) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [0f6b60cc29](https://linux-hardware.org/?probe=0f6b60cc29) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [704aa27146](https://linux-hardware.org/?probe=704aa27146) | Jul 19, 2021 |
| Dell          | Board                       | [653462ebfc](https://linux-hardware.org/?probe=653462ebfc) | Jul 19, 2021 |
| Dell          | Board                       | [221fc0def9](https://linux-hardware.org/?probe=221fc0def9) | Jul 18, 2021 |
| ASUSTek       | B85M-G                      | [59a5d00285](https://linux-hardware.org/?probe=59a5d00285) | Jul 18, 2021 |
| Biostar       | NF520D3                     | [3c302b5285](https://linux-hardware.org/?probe=3c302b5285) | Jul 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [3cc44e771e](https://linux-hardware.org/?probe=3cc44e771e) | Jul 17, 2021 |
| ASRock        | Z77 Extreme3                | [79dd398eff](https://linux-hardware.org/?probe=79dd398eff) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | [f7c2e4c1ff](https://linux-hardware.org/?probe=f7c2e4c1ff) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | [279539af23](https://linux-hardware.org/?probe=279539af23) | Jul 17, 2021 |
| MSI           | H510I PRO WIFI              | [e2ee4b4177](https://linux-hardware.org/?probe=e2ee4b4177) | Jul 16, 2021 |
| MSI           | H81M-P33                    | [4a187b22eb](https://linux-hardware.org/?probe=4a187b22eb) | Jul 16, 2021 |
| MSI           | H110M PRO-VH                | [c91d217ad5](https://linux-hardware.org/?probe=c91d217ad5) | Jul 16, 2021 |
| ASUSTek       | M4A88T-M                    | [8a768d9d2e](https://linux-hardware.org/?probe=8a768d9d2e) | Jul 16, 2021 |
| MSI           | X399 SLI PLUS               | [00b0b9f630](https://linux-hardware.org/?probe=00b0b9f630) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | [15b36f53b7](https://linux-hardware.org/?probe=15b36f53b7) | Jul 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [78f6f72d78](https://linux-hardware.org/?probe=78f6f72d78) | Jul 15, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [b833818421](https://linux-hardware.org/?probe=b833818421) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | [7802550585](https://linux-hardware.org/?probe=7802550585) | Jul 15, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b7c858e62](https://linux-hardware.org/?probe=2b7c858e62) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9a7cff028c](https://linux-hardware.org/?probe=9a7cff028c) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Biostar       | TZ68K+                      | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | 0YXT71 A03                  | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5b9e8c2d22](https://linux-hardware.org/?probe=5b9e8c2d22) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | [a989b9d184](https://linux-hardware.org/?probe=a989b9d184) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | [19a34b1a62](https://linux-hardware.org/?probe=19a34b1a62) | Jul 13, 2021 |
| ASUSTek       | P8H61-MX USB3               | [4bf665fc54](https://linux-hardware.org/?probe=4bf665fc54) | Jul 13, 2021 |
| ASRock        | 980DE3/U3S3                 | [f44cd2127b](https://linux-hardware.org/?probe=f44cd2127b) | Jul 12, 2021 |
| MSI           | H61M-E22/W8                 | [6fff913666](https://linux-hardware.org/?probe=6fff913666) | Jul 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [26c9b7468a](https://linux-hardware.org/?probe=26c9b7468a) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [fe6c28a62e](https://linux-hardware.org/?probe=fe6c28a62e) | Jul 11, 2021 |
| Gigabyte      | Z77-DS3H                    | [4bb7996ee5](https://linux-hardware.org/?probe=4bb7996ee5) | Jul 11, 2021 |
| Gigabyte      | H61M-USB3H                  | [667aa68843](https://linux-hardware.org/?probe=667aa68843) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [395229874c](https://linux-hardware.org/?probe=395229874c) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [21129fefc1](https://linux-hardware.org/?probe=21129fefc1) | Jul 10, 2021 |
| Dell          | 0NK5PH A00                  | [f79af9ba9b](https://linux-hardware.org/?probe=f79af9ba9b) | Jul 10, 2021 |
| Pegatron      | Benicia                     | [ad6d42566b](https://linux-hardware.org/?probe=ad6d42566b) | Jul 10, 2021 |
| MSI           | H110M PRO-VH                | [39bbc7b6a9](https://linux-hardware.org/?probe=39bbc7b6a9) | Jul 09, 2021 |
| Gigabyte      | A320M-DS2-CF                | [ec4f4e1d9b](https://linux-hardware.org/?probe=ec4f4e1d9b) | Jul 09, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [b943914d72](https://linux-hardware.org/?probe=b943914d72) | Jul 09, 2021 |
| Dell          | 0200DY A01                  | [28c56ed28e](https://linux-hardware.org/?probe=28c56ed28e) | Jul 09, 2021 |
| Shuttle       | FH61V                       | [57e978bf7e](https://linux-hardware.org/?probe=57e978bf7e) | Jul 09, 2021 |
| ASRock        | B550M-ITX/ac                | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| ASRock        | H67M                        | [660e47da08](https://linux-hardware.org/?probe=660e47da08) | Jul 08, 2021 |
| MSI           | H81M-P33                    | [a03d8e33d2](https://linux-hardware.org/?probe=a03d8e33d2) | Jul 08, 2021 |
| Gigabyte      | A320M-S2H-CF                | [65dab5ea20](https://linux-hardware.org/?probe=65dab5ea20) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [77513a0fe5](https://linux-hardware.org/?probe=77513a0fe5) | Jul 08, 2021 |
| MSI           | CSM-H81M-P32                | [dcac2bf6e1](https://linux-hardware.org/?probe=dcac2bf6e1) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [8beba5ddf7](https://linux-hardware.org/?probe=8beba5ddf7) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | [76a98ccf8a](https://linux-hardware.org/?probe=76a98ccf8a) | Jul 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ff048cc41](https://linux-hardware.org/?probe=7ff048cc41) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e1e7fa29fb](https://linux-hardware.org/?probe=e1e7fa29fb) | Jul 08, 2021 |
| Dell          | 0WR7PY A00                  | [174989025c](https://linux-hardware.org/?probe=174989025c) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | [4c4f65a000](https://linux-hardware.org/?probe=4c4f65a000) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | [8f33247147](https://linux-hardware.org/?probe=8f33247147) | Jul 07, 2021 |
| MACHINIST     | X99-K9 V2.0                 | [11cb60efc3](https://linux-hardware.org/?probe=11cb60efc3) | Jul 07, 2021 |
| Gigabyte      | Z77-DS3H                    | [d87f176b36](https://linux-hardware.org/?probe=d87f176b36) | Jul 07, 2021 |
| MSI           | B350 TOMAHAWK               | [7b4d2e8580](https://linux-hardware.org/?probe=7b4d2e8580) | Jul 06, 2021 |
| Lenovo        | Board                       | [8adc2b3a82](https://linux-hardware.org/?probe=8adc2b3a82) | Jul 06, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [0345fe1b56](https://linux-hardware.org/?probe=0345fe1b56) | Jul 05, 2021 |
| HP            | 83E8                        | [dd469e94e9](https://linux-hardware.org/?probe=dd469e94e9) | Jul 05, 2021 |
| Gigabyte      | H110M-S2V DDR3-CF           | [9eac8917f1](https://linux-hardware.org/?probe=9eac8917f1) | Jul 04, 2021 |
| MSI           | H81M-P33                    | [5a289e338f](https://linux-hardware.org/?probe=5a289e338f) | Jul 04, 2021 |
| MSI           | G41M-P33                    | [8bc3bbf743](https://linux-hardware.org/?probe=8bc3bbf743) | Jul 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [29dc877a37](https://linux-hardware.org/?probe=29dc877a37) | Jul 03, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Biostar       | H61MLV2                     | [45f8d339a6](https://linux-hardware.org/?probe=45f8d339a6) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | [cdcbc5460d](https://linux-hardware.org/?probe=cdcbc5460d) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | [c8a5a8c476](https://linux-hardware.org/?probe=c8a5a8c476) | Jul 02, 2021 |
| ASUSTek       | PRIME A320M-K               | [f281017450](https://linux-hardware.org/?probe=f281017450) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| MSI           | 890GXM-G65                  | [f4e1c45ed2](https://linux-hardware.org/?probe=f4e1c45ed2) | Jun 30, 2021 |
| Pegatron      | 2AC2                        | [46df29e3a0](https://linux-hardware.org/?probe=46df29e3a0) | Jun 30, 2021 |
| ASUSTek       | PRIME A320M-K               | [39ce85da03](https://linux-hardware.org/?probe=39ce85da03) | Jun 30, 2021 |
| ASUSTek       | N3050I-C                    | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | Z77A-G43                    | [072048636a](https://linux-hardware.org/?probe=072048636a) | Jun 29, 2021 |
| ASUSTek       | PRIME Z390-P                | [e99b341cf4](https://linux-hardware.org/?probe=e99b341cf4) | Jun 29, 2021 |
| ASRock        | B85 Pro4                    | [f9a2e6f60c](https://linux-hardware.org/?probe=f9a2e6f60c) | Jun 29, 2021 |
| Lenovo        | Board                       | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [0a190b5aa4](https://linux-hardware.org/?probe=0a190b5aa4) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d6fb94e774](https://linux-hardware.org/?probe=d6fb94e774) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | [42238e9adc](https://linux-hardware.org/?probe=42238e9adc) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | [e86f5af473](https://linux-hardware.org/?probe=e86f5af473) | Jun 28, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [15884a55b2](https://linux-hardware.org/?probe=15884a55b2) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [921fcdf0c3](https://linux-hardware.org/?probe=921fcdf0c3) | Jun 27, 2021 |
| Dell          | 05DN3X A00                  | [d0fb4fb2ad](https://linux-hardware.org/?probe=d0fb4fb2ad) | Jun 27, 2021 |
| ASUSTek       | Basswood                    | [daf1b9da91](https://linux-hardware.org/?probe=daf1b9da91) | Jun 27, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| Pegatron      | 2AB5                        | [8fae33ceb8](https://linux-hardware.org/?probe=8fae33ceb8) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | [6a2d22eae8](https://linux-hardware.org/?probe=6a2d22eae8) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | [5b1b696b98](https://linux-hardware.org/?probe=5b1b696b98) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [d1e5fbd176](https://linux-hardware.org/?probe=d1e5fbd176) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [048336bb59](https://linux-hardware.org/?probe=048336bb59) | Jun 26, 2021 |
| Dell          | 0FPP7F A00                  | [2e2e4ab599](https://linux-hardware.org/?probe=2e2e4ab599) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b93fa99bf8](https://linux-hardware.org/?probe=b93fa99bf8) | Jun 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f9070b6d21](https://linux-hardware.org/?probe=f9070b6d21) | Jun 26, 2021 |
| Gigabyte      | Z590I AORUS ULTRA           | [3791b62c7e](https://linux-hardware.org/?probe=3791b62c7e) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [598db879ae](https://linux-hardware.org/?probe=598db879ae) | Jun 25, 2021 |
| ASUSTek       | PRIME Z270-A                | [766af89e9c](https://linux-hardware.org/?probe=766af89e9c) | Jun 25, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [dab6b0d848](https://linux-hardware.org/?probe=dab6b0d848) | Jun 25, 2021 |
| Intel         | X79 V2.72B                  | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| Gigabyte      | H61M-S2PV                   | [3da8487d5f](https://linux-hardware.org/?probe=3da8487d5f) | Jun 24, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [180890e9c8](https://linux-hardware.org/?probe=180890e9c8) | Jun 24, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | [24c93ed20a](https://linux-hardware.org/?probe=24c93ed20a) | Jun 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [1905557ab4](https://linux-hardware.org/?probe=1905557ab4) | Jun 24, 2021 |
| Dell          | 08HPGT A01                  | [7be7bba24f](https://linux-hardware.org/?probe=7be7bba24f) | Jun 24, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [39f96730d9](https://linux-hardware.org/?probe=39f96730d9) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e24031d13d](https://linux-hardware.org/?probe=e24031d13d) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | [0609479af2](https://linux-hardware.org/?probe=0609479af2) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | [bbbed29691](https://linux-hardware.org/?probe=bbbed29691) | Jun 23, 2021 |
| MSI           | H510I PRO WIFI              | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | [c13a83286a](https://linux-hardware.org/?probe=c13a83286a) | Jun 23, 2021 |
| OEM           | B250B                       | [76ea6ec5b6](https://linux-hardware.org/?probe=76ea6ec5b6) | Jun 22, 2021 |
| Packard Be... | MCP73                       | [949909da41](https://linux-hardware.org/?probe=949909da41) | Jun 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| TYAN Compu... | Toledo i3210W/i3200R S52... | [cfacd9e7ce](https://linux-hardware.org/?probe=cfacd9e7ce) | Jun 21, 2021 |
| OEM           | B250B                       | [cadd03edf3](https://linux-hardware.org/?probe=cadd03edf3) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [c40ed6f57e](https://linux-hardware.org/?probe=c40ed6f57e) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [6c5f517ffe](https://linux-hardware.org/?probe=6c5f517ffe) | Jun 21, 2021 |
| Packard Be... | MCP73                       | [e1eb07cc34](https://linux-hardware.org/?probe=e1eb07cc34) | Jun 21, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | [b23297702d](https://linux-hardware.org/?probe=b23297702d) | Jun 21, 2021 |
| ASUSTek       | PRIME Z270-A                | [5fa67b7e7e](https://linux-hardware.org/?probe=5fa67b7e7e) | Jun 21, 2021 |
| Dell          | 0GDG8Y A00                  | [5573a86f4c](https://linux-hardware.org/?probe=5573a86f4c) | Jun 21, 2021 |
| ASUSTek       | Z97-P                       | [3e013acd03](https://linux-hardware.org/?probe=3e013acd03) | Jun 21, 2021 |
| Pegatron      | Benicia                     | [40526a2b4c](https://linux-hardware.org/?probe=40526a2b4c) | Jun 20, 2021 |
| MSI           | H510I PRO WIFI              | [414b5b7cf3](https://linux-hardware.org/?probe=414b5b7cf3) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [14083d2e96](https://linux-hardware.org/?probe=14083d2e96) | Jun 20, 2021 |
| Biostar       | TB250-BTC                   | [135a42fc66](https://linux-hardware.org/?probe=135a42fc66) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | [acdf9bed0d](https://linux-hardware.org/?probe=acdf9bed0d) | Jun 19, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [c13134fc57](https://linux-hardware.org/?probe=c13134fc57) | Jun 19, 2021 |
| ASUSTek       | H81M-C                      | [8337e476da](https://linux-hardware.org/?probe=8337e476da) | Jun 19, 2021 |
| ASRock        | B85M Pro4                   | [3400ad3eb1](https://linux-hardware.org/?probe=3400ad3eb1) | Jun 19, 2021 |
| MSI           | Z77A-G43 GAMING             | [e5da744b7b](https://linux-hardware.org/?probe=e5da744b7b) | Jun 19, 2021 |
| ASRock        | B85M Pro4                   | [f1e7b8a65b](https://linux-hardware.org/?probe=f1e7b8a65b) | Jun 18, 2021 |
| MSI           | H510I PRO WIFI              | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASUSTek       | H81M-C                      | [c843908a01](https://linux-hardware.org/?probe=c843908a01) | Jun 18, 2021 |
| ASUSTek       | H81M-C                      | [d9de8b8b5b](https://linux-hardware.org/?probe=d9de8b8b5b) | Jun 17, 2021 |
| MSI           | MEG Z490 UNIFY              | [542e64b8b1](https://linux-hardware.org/?probe=542e64b8b1) | Jun 17, 2021 |
| ASUSTek       | H81M-C                      | [39e707392d](https://linux-hardware.org/?probe=39e707392d) | Jun 17, 2021 |
| ASUSTek       | P8H61-MX USB3               | [1b6fedfa86](https://linux-hardware.org/?probe=1b6fedfa86) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS M                | [061955c2a0](https://linux-hardware.org/?probe=061955c2a0) | Jun 16, 2021 |
| ASUSTek       | M2N68-AM                    | [21b5888299](https://linux-hardware.org/?probe=21b5888299) | Jun 16, 2021 |
| MSI           | B250I PRO                   | [02087ebc8a](https://linux-hardware.org/?probe=02087ebc8a) | Jun 15, 2021 |
| MSI           | B250I PRO                   | [05b0b94ace](https://linux-hardware.org/?probe=05b0b94ace) | Jun 15, 2021 |
| ASRock        | N68C-S UCC                  | [e62dd54d79](https://linux-hardware.org/?probe=e62dd54d79) | Jun 15, 2021 |
| MSI           | B75MA-P45                   | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Gigabyte      | 990FXA-UD3                  | [3d0e9bc4aa](https://linux-hardware.org/?probe=3d0e9bc4aa) | Jun 14, 2021 |
| HC            | HCAR357-MI V1.0             | [6757c0e254](https://linux-hardware.org/?probe=6757c0e254) | Jun 14, 2021 |
| ASRock        | B560M-ITX/ac                | [2284cea3c5](https://linux-hardware.org/?probe=2284cea3c5) | Jun 14, 2021 |
| ASUSTek       | PRIME Z590-A                | [ad883d60a1](https://linux-hardware.org/?probe=ad883d60a1) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| ASRock        | 970M Pro3                   | [c75be35c68](https://linux-hardware.org/?probe=c75be35c68) | Jun 14, 2021 |
| ASUSTek       | PRIME Z370-P                | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| ASUSTek       | P5WD2-Premium               | [35c95bde23](https://linux-hardware.org/?probe=35c95bde23) | Jun 13, 2021 |
| ASUSTek       | H97M-E                      | [0bc409e14c](https://linux-hardware.org/?probe=0bc409e14c) | Jun 13, 2021 |
| MSI           | 970A-G46                    | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Gigabyte      | Z77-DS3H                    | [981954c88b](https://linux-hardware.org/?probe=981954c88b) | Jun 13, 2021 |
| ASUSTek       | M2A-VM                      | [e4fdaff878](https://linux-hardware.org/?probe=e4fdaff878) | Jun 12, 2021 |
| Gigabyte      | X99M-Gaming 5               | [10d40dc417](https://linux-hardware.org/?probe=10d40dc417) | Jun 12, 2021 |
| Gigabyte      | Z590 VISION G               | [c3b20ee137](https://linux-hardware.org/?probe=c3b20ee137) | Jun 12, 2021 |
| ASUSTek       | PRIME X399-A                | [bfb3ab2f44](https://linux-hardware.org/?probe=bfb3ab2f44) | Jun 11, 2021 |
| Gigabyte      | G41MT-USB3                  | [df62a2a7e0](https://linux-hardware.org/?probe=df62a2a7e0) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | [76a7098ea9](https://linux-hardware.org/?probe=76a7098ea9) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | [f5ba57634a](https://linux-hardware.org/?probe=f5ba57634a) | Jun 11, 2021 |
| HP            | 0B4Ch D                     | [5ac932248a](https://linux-hardware.org/?probe=5ac932248a) | Jun 10, 2021 |
| HP            | 158A                        | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [bab34a6951](https://linux-hardware.org/?probe=bab34a6951) | Jun 10, 2021 |
| HP            | 843B                        | [95015678e1](https://linux-hardware.org/?probe=95015678e1) | Jun 09, 2021 |
| ASUSTek       | G11DF                       | [86408c43ff](https://linux-hardware.org/?probe=86408c43ff) | Jun 09, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [e8ea861c92](https://linux-hardware.org/?probe=e8ea861c92) | Jun 09, 2021 |
| Gigabyte      | GA-870A-UD3                 | [89462c851a](https://linux-hardware.org/?probe=89462c851a) | Jun 08, 2021 |
| Gigabyte      | P43T-ES3G                   | [ab6924723a](https://linux-hardware.org/?probe=ab6924723a) | Jun 08, 2021 |
| Acer          | EG43M                       | [4300da7d4b](https://linux-hardware.org/?probe=4300da7d4b) | Jun 08, 2021 |
| Acer          | EG43M                       | [c160d8848f](https://linux-hardware.org/?probe=c160d8848f) | Jun 08, 2021 |
| ASUSTek       | P8H61-MX USB3               | [cf5748e282](https://linux-hardware.org/?probe=cf5748e282) | Jun 07, 2021 |
| HP            | 0AA0h                       | [1231618175](https://linux-hardware.org/?probe=1231618175) | Jun 07, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [6f5aed374a](https://linux-hardware.org/?probe=6f5aed374a) | Jun 06, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| Gigabyte      | Z77X-D3H                    | [0f9baa3f5f](https://linux-hardware.org/?probe=0f9baa3f5f) | Jun 05, 2021 |
| ASUSTek       | P5WD2-Premium               | [3bf03e7263](https://linux-hardware.org/?probe=3bf03e7263) | Jun 05, 2021 |
| HP            | 1998                        | [68978259f3](https://linux-hardware.org/?probe=68978259f3) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [f55a54325f](https://linux-hardware.org/?probe=f55a54325f) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [24a4df74e1](https://linux-hardware.org/?probe=24a4df74e1) | Jun 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e7e821c4a7](https://linux-hardware.org/?probe=e7e821c4a7) | Jun 04, 2021 |
| HP            | 0AA0h                       | [ff231665d3](https://linux-hardware.org/?probe=ff231665d3) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [62a56ec749](https://linux-hardware.org/?probe=62a56ec749) | Jun 04, 2021 |
| Medion        | MS-7621                     | [29ecaf9382](https://linux-hardware.org/?probe=29ecaf9382) | Jun 04, 2021 |
| MSI           | MS-7125                     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| HP            | 1998                        | [617a033a6e](https://linux-hardware.org/?probe=617a033a6e) | Jun 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [c0e0de26cb](https://linux-hardware.org/?probe=c0e0de26cb) | Jun 04, 2021 |
| ASUSTek       | TUF H370-PRO GAMING         | [8f75ede232](https://linux-hardware.org/?probe=8f75ede232) | Jun 04, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [5de814b0ab](https://linux-hardware.org/?probe=5de814b0ab) | Jun 04, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [0126e8d357](https://linux-hardware.org/?probe=0126e8d357) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [9237a7a68b](https://linux-hardware.org/?probe=9237a7a68b) | Jun 03, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [6a9e537939](https://linux-hardware.org/?probe=6a9e537939) | Jun 03, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [adeee24676](https://linux-hardware.org/?probe=adeee24676) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| HP            | 3397                        | [73e07145f4](https://linux-hardware.org/?probe=73e07145f4) | Jun 03, 2021 |
| ASUSTek       | M2N                         | [f5537f32f6](https://linux-hardware.org/?probe=f5537f32f6) | Jun 02, 2021 |
| HP            | 3397                        | [1eba8aa1c1](https://linux-hardware.org/?probe=1eba8aa1c1) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [40545ef53f](https://linux-hardware.org/?probe=40545ef53f) | Jun 02, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5cbd925314](https://linux-hardware.org/?probe=5cbd925314) | Jun 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [8daf7e0679](https://linux-hardware.org/?probe=8daf7e0679) | Jun 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [4afad10651](https://linux-hardware.org/?probe=4afad10651) | Jun 02, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c31c1c69c6](https://linux-hardware.org/?probe=c31c1c69c6) | Jun 02, 2021 |
| ASUSTek       | PRIME Z390-P                | [75cd860063](https://linux-hardware.org/?probe=75cd860063) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | [e417b5e11e](https://linux-hardware.org/?probe=e417b5e11e) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | [ea4e7fc19e](https://linux-hardware.org/?probe=ea4e7fc19e) | Jun 01, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a133667e3c](https://linux-hardware.org/?probe=a133667e3c) | May 31, 2021 |
| Acer          | Aspire XC-230               | [4594f040e1](https://linux-hardware.org/?probe=4594f040e1) | May 31, 2021 |
| Gigabyte      | Z590 VISION G               | [ea4492aeee](https://linux-hardware.org/?probe=ea4492aeee) | May 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [aa3a28c4b3](https://linux-hardware.org/?probe=aa3a28c4b3) | May 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6dde896b4f](https://linux-hardware.org/?probe=6dde896b4f) | May 30, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [36ebf65d44](https://linux-hardware.org/?probe=36ebf65d44) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | [44a0f0e4e2](https://linux-hardware.org/?probe=44a0f0e4e2) | May 30, 2021 |
| MSI           | B350 PC MATE                | [d640900b8a](https://linux-hardware.org/?probe=d640900b8a) | May 29, 2021 |
| MSI           | B350 PC MATE                | [f7942b9c3e](https://linux-hardware.org/?probe=f7942b9c3e) | May 29, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8fd027f078](https://linux-hardware.org/?probe=8fd027f078) | May 29, 2021 |
| Foxconn       | 2ADA                        | [6e2fc02f05](https://linux-hardware.org/?probe=6e2fc02f05) | May 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [dfa6b5b067](https://linux-hardware.org/?probe=dfa6b5b067) | May 28, 2021 |
| MSI           | Z490-A PRO                  | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| MSI           | 970A-G43                    | [07a86d218e](https://linux-hardware.org/?probe=07a86d218e) | May 27, 2021 |
| ASRock        | H77 Pro4-M                  | [f0450b570d](https://linux-hardware.org/?probe=f0450b570d) | May 27, 2021 |
| HP            | 81B4                        | [41311d3164](https://linux-hardware.org/?probe=41311d3164) | May 27, 2021 |
| Biostar       | A320MD PRO                  | [02e5d996c8](https://linux-hardware.org/?probe=02e5d996c8) | May 27, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [abd5d85c0e](https://linux-hardware.org/?probe=abd5d85c0e) | May 27, 2021 |
| ASUSTek       | PRIME Z390-P                | [9f58a0f0bf](https://linux-hardware.org/?probe=9f58a0f0bf) | May 26, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [3b8ddca28e](https://linux-hardware.org/?probe=3b8ddca28e) | May 26, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [01379ec7fb](https://linux-hardware.org/?probe=01379ec7fb) | May 26, 2021 |
| MSI           | FM2-A85XMA-P33              | [0a01344d75](https://linux-hardware.org/?probe=0a01344d75) | May 26, 2021 |
| MSI           | ZH77A-G41                   | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | [0fabdb3aad](https://linux-hardware.org/?probe=0fabdb3aad) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | [eb6c059d63](https://linux-hardware.org/?probe=eb6c059d63) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | [40de3f5310](https://linux-hardware.org/?probe=40de3f5310) | May 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [2961088957](https://linux-hardware.org/?probe=2961088957) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASRock        | G41M-S3                     | [33ba80d2ae](https://linux-hardware.org/?probe=33ba80d2ae) | May 23, 2021 |
| ASRock        | B450 Pro4                   | [5be7a59bcd](https://linux-hardware.org/?probe=5be7a59bcd) | May 23, 2021 |
| ASRock        | G41M-S3                     | [d79c3e4c28](https://linux-hardware.org/?probe=d79c3e4c28) | May 23, 2021 |
| Gigabyte      | F2A78M-DS2                  | [da126fa410](https://linux-hardware.org/?probe=da126fa410) | May 23, 2021 |
| ASUSTek       | ET2700I                     | [a3edd93ada](https://linux-hardware.org/?probe=a3edd93ada) | May 23, 2021 |
| Acer          | Aspire XC-230               | [a6074abd32](https://linux-hardware.org/?probe=a6074abd32) | May 23, 2021 |
| Dell          | 0RK936                      | [27b342b50b](https://linux-hardware.org/?probe=27b342b50b) | May 22, 2021 |
| Dell          | 0RK936                      | [6c12a5edf2](https://linux-hardware.org/?probe=6c12a5edf2) | May 22, 2021 |
| ASRock        | X370 Gaming K4              | [4945bb80f6](https://linux-hardware.org/?probe=4945bb80f6) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c458b6d1ca](https://linux-hardware.org/?probe=c458b6d1ca) | May 21, 2021 |
| ASUSTek       | H81M-PLUS                   | [0e3415879f](https://linux-hardware.org/?probe=0e3415879f) | May 21, 2021 |
| MSI           | 970 GAMING                  | [eb4531374e](https://linux-hardware.org/?probe=eb4531374e) | May 21, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| Acer          | Aspire XC-230               | [31e0dabfb9](https://linux-hardware.org/?probe=31e0dabfb9) | May 20, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a42bee6110](https://linux-hardware.org/?probe=a42bee6110) | May 19, 2021 |
| HP            | 802F                        | [f01cdeed88](https://linux-hardware.org/?probe=f01cdeed88) | May 19, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [3814598db5](https://linux-hardware.org/?probe=3814598db5) | May 19, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| ASUSTek       | H81M-K                      | [d44e900d30](https://linux-hardware.org/?probe=d44e900d30) | May 18, 2021 |
| Dell          | 0RK936                      | [c3c620590f](https://linux-hardware.org/?probe=c3c620590f) | May 18, 2021 |
| ASRock        | B550 Extreme4               | [38fe00e843](https://linux-hardware.org/?probe=38fe00e843) | May 18, 2021 |
| ASUSTek       | PRIME B250M-A               | [b646c2612a](https://linux-hardware.org/?probe=b646c2612a) | May 18, 2021 |
| ASUSTek       | PRIME Z390-P                | [94f5c42214](https://linux-hardware.org/?probe=94f5c42214) | May 18, 2021 |
| ASRock        | Z97E-ITX/ac                 | [b6812b6242](https://linux-hardware.org/?probe=b6812b6242) | May 17, 2021 |
| Dell          | 0VHRW1 A03                  | [1ac850d5b7](https://linux-hardware.org/?probe=1ac850d5b7) | May 17, 2021 |
| MSI           | G41M-P25                    | [57d1c4dafa](https://linux-hardware.org/?probe=57d1c4dafa) | May 16, 2021 |
| Dell          | 0Y5DDC A00                  | [7694ca4dfd](https://linux-hardware.org/?probe=7694ca4dfd) | May 16, 2021 |
| Dell          | 051FJ8 A02                  | [dd8dc2d85a](https://linux-hardware.org/?probe=dd8dc2d85a) | May 16, 2021 |
| ASUSTek       | PRIME Z390-P                | [00a90e02e9](https://linux-hardware.org/?probe=00a90e02e9) | May 15, 2021 |
| Pegatron      | 2AB5                        | [ef62ad9c4b](https://linux-hardware.org/?probe=ef62ad9c4b) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | [637ea140ae](https://linux-hardware.org/?probe=637ea140ae) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | [0d737eab8c](https://linux-hardware.org/?probe=0d737eab8c) | May 15, 2021 |
| Medion        | MS-7621                     | [9d7d398cc1](https://linux-hardware.org/?probe=9d7d398cc1) | May 15, 2021 |
| MSI           | 970 GAMING                  | [bc393b7046](https://linux-hardware.org/?probe=bc393b7046) | May 15, 2021 |
| Gigabyte      | B460M AORUS PRO             | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| Unknown       | Unknown                     | [2c887c5d3f](https://linux-hardware.org/?probe=2c887c5d3f) | May 14, 2021 |
| Unknown       | Unknown                     | [aca4c8c6cf](https://linux-hardware.org/?probe=aca4c8c6cf) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | [b3d306266e](https://linux-hardware.org/?probe=b3d306266e) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | [5310f8c130](https://linux-hardware.org/?probe=5310f8c130) | May 14, 2021 |
| Gigabyte      | F2A55M-HD2                  | [b39ddf3718](https://linux-hardware.org/?probe=b39ddf3718) | May 14, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [a44fcb1c39](https://linux-hardware.org/?probe=a44fcb1c39) | May 13, 2021 |
| ASUSTek       | PRIME X299-A                | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Medion        | E631X Ver                   | [872b2a2dc9](https://linux-hardware.org/?probe=872b2a2dc9) | May 13, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [2efd6e26e3](https://linux-hardware.org/?probe=2efd6e26e3) | May 12, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Acer          | Aspire XC-230               | [73c9019a57](https://linux-hardware.org/?probe=73c9019a57) | May 10, 2021 |
| ASUSTek       | M2A-VM                      | [425df4a110](https://linux-hardware.org/?probe=425df4a110) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Dell          | 0YXT71 A00                  | [0b1b291060](https://linux-hardware.org/?probe=0b1b291060) | May 09, 2021 |
| MSI           | H61M-P20/W8                 | [ca302c374f](https://linux-hardware.org/?probe=ca302c374f) | May 08, 2021 |
| MSI           | H61M-P20/W8                 | [e68f90acd5](https://linux-hardware.org/?probe=e68f90acd5) | May 08, 2021 |
| HP            | 09F8h                       | [88de1576e5](https://linux-hardware.org/?probe=88de1576e5) | May 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [85058201a1](https://linux-hardware.org/?probe=85058201a1) | May 08, 2021 |
| Acer          | Veriton X490G               | [a729505133](https://linux-hardware.org/?probe=a729505133) | May 08, 2021 |
| ASRock        | X99 Extreme4                | [22b924723a](https://linux-hardware.org/?probe=22b924723a) | May 08, 2021 |
| Gigabyte      | B560M DS3H AC               | [7d79c9afb9](https://linux-hardware.org/?probe=7d79c9afb9) | May 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [77820715f4](https://linux-hardware.org/?probe=77820715f4) | May 08, 2021 |
| ASUSTek       | PRIME B460M-A               | [a65a4354b9](https://linux-hardware.org/?probe=a65a4354b9) | May 07, 2021 |
| HP            | 09F8h                       | [9d6ad317f4](https://linux-hardware.org/?probe=9d6ad317f4) | May 07, 2021 |
| MSI           | H410M PRO                   | [68104520c5](https://linux-hardware.org/?probe=68104520c5) | May 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [8219a4a9ac](https://linux-hardware.org/?probe=8219a4a9ac) | May 06, 2021 |
| MSI           | H270M BAZOOKA               | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| Gigabyte      | B75M-HD3                    | [cff51c85da](https://linux-hardware.org/?probe=cff51c85da) | May 06, 2021 |
| Gigabyte      | 970A-DS3P                   | [25ad87e22b](https://linux-hardware.org/?probe=25ad87e22b) | May 05, 2021 |
| Gigabyte      | Z390 UD                     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [dc28c67e94](https://linux-hardware.org/?probe=dc28c67e94) | May 05, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [48d1110975](https://linux-hardware.org/?probe=48d1110975) | May 05, 2021 |
| MSI           | MAG B460M MORTAR            | [9b72abe5d8](https://linux-hardware.org/?probe=9b72abe5d8) | May 05, 2021 |
| MSI           | B450 GAMING PLUS            | [45f40c1d2b](https://linux-hardware.org/?probe=45f40c1d2b) | May 04, 2021 |
| HP            | 3647h                       | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [f42aef173c](https://linux-hardware.org/?probe=f42aef173c) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [8b524de561](https://linux-hardware.org/?probe=8b524de561) | May 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [07a17b86ea](https://linux-hardware.org/?probe=07a17b86ea) | May 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [6fbe833fac](https://linux-hardware.org/?probe=6fbe833fac) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [aebf5d33a4](https://linux-hardware.org/?probe=aebf5d33a4) | May 02, 2021 |
| SYWZ          | S210H Series                | [746808e2c5](https://linux-hardware.org/?probe=746808e2c5) | May 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [315bc839ec](https://linux-hardware.org/?probe=315bc839ec) | May 01, 2021 |
| ASUSTek       | PRIME Z490-A                | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1a9b2e458a](https://linux-hardware.org/?probe=1a9b2e458a) | Apr 30, 2021 |
| Dell          | 0Y5DDC A00                  | [29206c06a9](https://linux-hardware.org/?probe=29206c06a9) | Apr 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [c3243b55ef](https://linux-hardware.org/?probe=c3243b55ef) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | [9f3fe00e5c](https://linux-hardware.org/?probe=9f3fe00e5c) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | [41fd34d001](https://linux-hardware.org/?probe=41fd34d001) | Apr 29, 2021 |
| ASUSTek       | P5Q DELUXE                  | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| Gigabyte      | H61M-S2PV                   | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| ASRock        | G41M-S3                     | [1fe4e3b8f2](https://linux-hardware.org/?probe=1fe4e3b8f2) | Apr 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| MSI           | B350 PC MATE                | [5ae67a0ac5](https://linux-hardware.org/?probe=5ae67a0ac5) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | [b4d731ce7b](https://linux-hardware.org/?probe=b4d731ce7b) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | [7a99053f1f](https://linux-hardware.org/?probe=7a99053f1f) | Apr 26, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [cc2f279890](https://linux-hardware.org/?probe=cc2f279890) | Apr 26, 2021 |
| Biostar       | A880GU3                     | [7c3cadb886](https://linux-hardware.org/?probe=7c3cadb886) | Apr 26, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [c1b51f4738](https://linux-hardware.org/?probe=c1b51f4738) | Apr 25, 2021 |
| MSI           | Z77A-GD55                   | [4ae20b53ca](https://linux-hardware.org/?probe=4ae20b53ca) | Apr 25, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [6dc9bcb3f7](https://linux-hardware.org/?probe=6dc9bcb3f7) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [80224285b6](https://linux-hardware.org/?probe=80224285b6) | Apr 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | [15f9ee179c](https://linux-hardware.org/?probe=15f9ee179c) | Apr 24, 2021 |
| ASUSTek       | VC66                        | [6158b04856](https://linux-hardware.org/?probe=6158b04856) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [a63e8e0aeb](https://linux-hardware.org/?probe=a63e8e0aeb) | Apr 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| ASUSTek       | PRIME H270-PRO              | [163211473a](https://linux-hardware.org/?probe=163211473a) | Apr 23, 2021 |
| Gigabyte      | B560M DS3H AC               | [04ecaf98a1](https://linux-hardware.org/?probe=04ecaf98a1) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| Gigabyte      | H81M-S2V                    | [6dba735784](https://linux-hardware.org/?probe=6dba735784) | Apr 20, 2021 |
| Gigabyte      | B560M DS3H AC               | [9622491640](https://linux-hardware.org/?probe=9622491640) | Apr 19, 2021 |
| ASRock        | B550 Steel Legend           | [d8db6d8577](https://linux-hardware.org/?probe=d8db6d8577) | Apr 18, 2021 |
| ASUSTek       | PRIME H410M-A               | [1a10915a97](https://linux-hardware.org/?probe=1a10915a97) | Apr 17, 2021 |
| Gigabyte      | H81M-S2V                    | [8e9d22ed4d](https://linux-hardware.org/?probe=8e9d22ed4d) | Apr 15, 2021 |
| ASRock        | X570 PG Velocita            | [20e91a55f2](https://linux-hardware.org/?probe=20e91a55f2) | Apr 15, 2021 |
| ASRock        | H570 Phantom Gaming 4       | [e89bff9fa4](https://linux-hardware.org/?probe=e89bff9fa4) | Apr 14, 2021 |
| Dell          | 0VD5HY A07                  | [28dda9b894](https://linux-hardware.org/?probe=28dda9b894) | Apr 12, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [3a69abb947](https://linux-hardware.org/?probe=3a69abb947) | Apr 05, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [63996f0452](https://linux-hardware.org/?probe=63996f0452) | Apr 04, 2021 |
| MSI           | MS-B9181                    | [7c467c7f2b](https://linux-hardware.org/?probe=7c467c7f2b) | Apr 02, 2021 |
| MSI           | MS-B9181                    | [5ed3225348](https://linux-hardware.org/?probe=5ed3225348) | Apr 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| MSI           | MS-1672 Ver                 | [c630018fea](https://linux-hardware.org/?probe=c630018fea) | Mar 31, 2021 |
| MSI           | MS-1672 Ver                 | [d72651aaf4](https://linux-hardware.org/?probe=d72651aaf4) | Mar 31, 2021 |
| AAEON         | UP-APL01 V0.4               | [9a724f738f](https://linux-hardware.org/?probe=9a724f738f) | Mar 26, 2021 |
| HP            | 3646h                       | [f870632953](https://linux-hardware.org/?probe=f870632953) | Mar 26, 2021 |
| Pegatron      | VIOLET                      | [97b60b69c9](https://linux-hardware.org/?probe=97b60b69c9) | Mar 19, 2021 |
| Biostar       | A320MD PRO                  | [cc647d652a](https://linux-hardware.org/?probe=cc647d652a) | Mar 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ee9f48a9d0](https://linux-hardware.org/?probe=ee9f48a9d0) | Mar 06, 2021 |
| ASRockRack    | X570D4U                     | [046e21b599](https://linux-hardware.org/?probe=046e21b599) | Mar 04, 2021 |
| ASRockRack    | X570D4U                     | [250918faa7](https://linux-hardware.org/?probe=250918faa7) | Mar 03, 2021 |
| ASRock        | FM2A75M-DGS                 | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [237d8d39fb](https://linux-hardware.org/?probe=237d8d39fb) | Feb 27, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ec5eb37f90](https://linux-hardware.org/?probe=ec5eb37f90) | Feb 25, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [3555575966](https://linux-hardware.org/?probe=3555575966) | Feb 21, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [190805f976](https://linux-hardware.org/?probe=190805f976) | Feb 21, 2021 |
| Gigabyte      | AB350M-D3V-CF               | [38a9e8bdd4](https://linux-hardware.org/?probe=38a9e8bdd4) | Feb 05, 2021 |
| Gigabyte      | H61M-S2-B3                  | [449cccd96f](https://linux-hardware.org/?probe=449cccd96f) | Feb 04, 2021 |
| HP            | 3032h                       | [89ff3e8a36](https://linux-hardware.org/?probe=89ff3e8a36) | Jan 25, 2021 |
| ASRock        | B75M-GL R2.0                | [79848dc213](https://linux-hardware.org/?probe=79848dc213) | Jan 17, 2021 |
| MSI           | MEG Z390 GODLIKE            | [319ddce23d](https://linux-hardware.org/?probe=319ddce23d) | Jan 11, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e081c11999](https://linux-hardware.org/?probe=e081c11999) | Jan 11, 2021 |
| MSI           | AMETHYST-M                  | [b242ecc226](https://linux-hardware.org/?probe=b242ecc226) | Jan 11, 2021 |
| MSI           | MEG Z390 GODLIKE            | [f5c9028c6a](https://linux-hardware.org/?probe=f5c9028c6a) | Dec 21, 2020 |
| ASRock        | B75M-GL R2.0                | [91c33b15fe](https://linux-hardware.org/?probe=91c33b15fe) | Dec 18, 2020 |
| HP            | 3032h                       | [aca3ed50ac](https://linux-hardware.org/?probe=aca3ed50ac) | Dec 07, 2020 |
| HP            | 3032h                       | [b061d52e66](https://linux-hardware.org/?probe=b061d52e66) | Dec 07, 2020 |
| MSI           | MEG Z390 GODLIKE            | [bb2f68b014](https://linux-hardware.org/?probe=bb2f68b014) | Nov 27, 2020 |
| MSI           | MEG Z390 GODLIKE            | [5c18dade22](https://linux-hardware.org/?probe=5c18dade22) | Nov 27, 2020 |
| Gigabyte      | Z97X-Gaming 5               | [bcc73e0b8d](https://linux-hardware.org/?probe=bcc73e0b8d) | Nov 25, 2020 |
| Colorful T... | C.H110M-K PRO V21           | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-25-generic        | 76       | 14.23%  |
| 5.11.0-22-generic        | 76       | 14.23%  |
| 5.11.0-18-generic        | 69       | 12.92%  |
| 5.11.0-16-generic        | 68       | 12.73%  |
| 5.11.0-31-generic        | 67       | 12.55%  |
| 5.11.0-34-generic        | 38       | 7.12%   |
| 5.11.0-17-generic        | 36       | 6.74%   |
| 5.11.0-36-generic        | 14       | 2.62%   |
| 5.11.0-33-generic        | 8        | 1.5%    |
| 5.11.0-26-generic        | 8        | 1.5%    |
| 5.11.0-24-generic        | 7        | 1.31%   |
| 5.11.0-37-generic        | 6        | 1.12%   |
| 5.11.0-13-generic        | 5        | 0.94%   |
| 5.10.0-14-generic        | 5        | 0.94%   |
| 5.11.0-23-generic        | 4        | 0.75%   |
| 5.11.0-14-generic        | 4        | 0.75%   |
| 5.8.0-36-generic         | 2        | 0.37%   |
| 5.12.0-051200-generic    | 2        | 0.37%   |
| 5.11.0-19-generic        | 2        | 0.37%   |
| 5.11.0-11-generic        | 2        | 0.37%   |
| 5.11.0-051100-generic    | 2        | 0.37%   |
| 5.10.0-12-generic        | 2        | 0.37%   |
| 5.10.0-051000-generic    | 2        | 0.37%   |
| 5.9.8-xanmod1-cachy      | 1        | 0.19%   |
| 5.9.10-050910-generic    | 1        | 0.19%   |
| 5.8.0-63-generic         | 1        | 0.19%   |
| 5.8.0-55-generic         | 1        | 0.19%   |
| 5.8.0-50-generic         | 1        | 0.19%   |
| 5.8.0-38-generic         | 1        | 0.19%   |
| 5.8.0-32-generic         | 1        | 0.19%   |
| 5.8.0-31-generic         | 1        | 0.19%   |
| 5.8.0-26-generic         | 1        | 0.19%   |
| 5.4.0-1038-gcp           | 1        | 0.19%   |
| 5.13.6-051306-lowlatency | 1        | 0.19%   |
| 5.13.4                   | 1        | 0.19%   |
| 5.13.0-3-generic         | 1        | 0.19%   |
| 5.13.0-16-generic        | 1        | 0.19%   |
| 5.13.0-051300rc7-generic | 1        | 0.19%   |
| 5.12.9-051209-lowlatency | 1        | 0.19%   |
| 5.12.8                   | 1        | 0.19%   |
| 5.12.10-051210-generic   | 1        | 0.19%   |
| 5.12.0-051200rc7-generic | 1        | 0.19%   |
| 5.11.12-051112-generic   | 1        | 0.19%   |
| 5.11.1-xanmod2-cacule    | 1        | 0.19%   |
| 5.11.0-7633-generic      | 1        | 0.19%   |
| 5.11.0-36-lowlatency     | 1        | 0.19%   |
| 5.11.0-35-generic        | 1        | 0.19%   |
| 5.11.0-31-lowlatency     | 1        | 0.19%   |
| 5.11.0-23-lowlatency     | 1        | 0.19%   |
| 5.11.0-20-generic        | 1        | 0.19%   |
| 5.11.0-18-lowlatency     | 1        | 0.19%   |
| 5.11.0-051100rc3-generic | 1        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 458      | 93.09%  |
| 5.8.0   | 9        | 1.83%   |
| 5.10.0  | 9        | 1.83%   |
| 5.13.0  | 3        | 0.61%   |
| 5.12.0  | 3        | 0.61%   |
| 5.9.8   | 1        | 0.2%    |
| 5.9.10  | 1        | 0.2%    |
| 5.4.0   | 1        | 0.2%    |
| 5.13.6  | 1        | 0.2%    |
| 5.13.4  | 1        | 0.2%    |
| 5.12.9  | 1        | 0.2%    |
| 5.12.8  | 1        | 0.2%    |
| 5.12.10 | 1        | 0.2%    |
| 5.11.12 | 1        | 0.2%    |
| 5.11.1  | 1        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 460      | 93.5%   |
| 5.8     | 9        | 1.83%   |
| 5.10    | 9        | 1.83%   |
| 5.12    | 6        | 1.22%   |
| 5.13    | 5        | 1.02%   |
| 5.9     | 2        | 0.41%   |
| 5.4     | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 486      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 430      | 87.58%  |
| Unknown           | 42       | 8.55%   |
| X-Cinnamon        | 5        | 1.02%   |
| Unity             | 3        | 0.61%   |
| Cinnamon          | 3        | 0.61%   |
| Yaru:ubuntu:GNOME | 2        | 0.41%   |
| Trinity           | 1        | 0.2%    |
| openbox           | 1        | 0.2%    |
| i3                | 1        | 0.2%    |
| fvwm              | 1        | 0.2%    |
| Deepin            | 1        | 0.2%    |
| awesome           | 1        | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 271      | 55.08%  |
| X11     | 194      | 39.43%  |
| Unknown | 20       | 4.07%   |
| Tty     | 7        | 1.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 376      | 76.73%  |
| GDM     | 89       | 18.16%  |
| GDM3    | 20       | 4.08%   |
| TDM     | 4        | 0.82%   |
| LightDM | 1        | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 160      | 32.79%  |
| de_DE   | 78       | 15.98%  |
| fr_FR   | 32       | 6.56%   |
| it_IT   | 20       | 4.1%    |
| en_GB   | 20       | 4.1%    |
| en_CA   | 17       | 3.48%   |
| pt_BR   | 16       | 3.28%   |
| ru_RU   | 14       | 2.87%   |
| en_AU   | 14       | 2.87%   |
| pl_PL   | 11       | 2.25%   |
| es_ES   | 11       | 2.25%   |
| zh_CN   | 6        | 1.23%   |
| es_AR   | 6        | 1.23%   |
| en_IN   | 6        | 1.23%   |
| sv_SE   | 5        | 1.02%   |
| hu_HU   | 5        | 1.02%   |
| de_CH   | 5        | 1.02%   |
| de_AT   | 5        | 1.02%   |
| ru_UA   | 4        | 0.82%   |
| ja_JP   | 4        | 0.82%   |
| en_ZA   | 4        | 0.82%   |
| el_GR   | 4        | 0.82%   |
| en_NZ   | 3        | 0.61%   |
| cs_CZ   | 3        | 0.61%   |
| bg_BG   | 3        | 0.61%   |
| ro_RO   | 2        | 0.41%   |
| nl_NL   | 2        | 0.41%   |
| nb_NO   | 2        | 0.41%   |
| fr_BE   | 2        | 0.41%   |
| es_CL   | 2        | 0.41%   |
| en_IL   | 2        | 0.41%   |
| ca_ES   | 2        | 0.41%   |
| C       | 2        | 0.41%   |
| Unknown | 2        | 0.41%   |
| zh_TW   | 1        | 0.2%    |
| zh_HK   | 1        | 0.2%    |
| uk_UA   | 1        | 0.2%    |
| tr_TR   | 1        | 0.2%    |
| sk_SK   | 1        | 0.2%    |
| pt_PT   | 1        | 0.2%    |
| id_ID   | 1        | 0.2%    |
| hr_HR   | 1        | 0.2%    |
| fr_CH   | 1        | 0.2%    |
| fi_FI   | 1        | 0.2%    |
| es_NI   | 1        | 0.2%    |
| es_MX   | 1        | 0.2%    |
| de_BE   | 1        | 0.2%    |
| ar_EG   | 1        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 384      | 78.53%  |
| EFI  | 105      | 21.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 436      | 89.34%  |
| Zfs      | 18       | 3.69%   |
| Overlay  | 12       | 2.46%   |
| Btrfs    | 12       | 2.46%   |
| Xfs      | 5        | 1.02%   |
| Ext3     | 2        | 0.41%   |
| Ext2     | 2        | 0.41%   |
| SquXshfs | 1        | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 392      | 80.33%  |
| GPT     | 85       | 17.42%  |
| MBR     | 11       | 2.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 386      | 78.14%  |
| Yes       | 108      | 21.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 272      | 54.95%  |
| Yes       | 223      | 45.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 135      | 27.78%  |
| Gigabyte Technology | 98       | 20.16%  |
| MSI                 | 66       | 13.58%  |
| ASRock              | 44       | 9.05%   |
| Hewlett-Packard     | 33       | 6.79%   |
| Dell                | 29       | 5.97%   |
| Lenovo              | 14       | 2.88%   |
| Acer                | 13       | 2.67%   |
| Biostar             | 8        | 1.65%   |
| Pegatron            | 6        | 1.23%   |
| Medion              | 4        | 0.82%   |
| Intel               | 4        | 0.82%   |
| Fujitsu             | 4        | 0.82%   |
| Unknown             | 4        | 0.82%   |
| Foxconn             | 3        | 0.62%   |
| Shuttle             | 2        | 0.41%   |
| HC                  | 2        | 0.41%   |
| TYAN Computer       | 1        | 0.21%   |
| SYWZ                | 1        | 0.21%   |
| Soyo                | 1        | 0.21%   |
| PCWare              | 1        | 0.21%   |
| Packard Bell        | 1        | 0.21%   |
| OEM                 | 1        | 0.21%   |
| MACHINIST           | 1        | 0.21%   |
| Huanan              | 1        | 0.21%   |
| Fujitsu Siemens     | 1        | 0.21%   |
| FIRICH              | 1        | 0.21%   |
| ECS                 | 1        | 0.21%   |
| Colorful Technology | 1        | 0.21%   |
| ASRockRack          | 1        | 0.21%   |
| Apple               | 1        | 0.21%   |
| AOpen               | 1        | 0.21%   |
| Alienware           | 1        | 0.21%   |
| AAEON               | 1        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 14       | 2.88%   |
| MSI MS-7B86                     | 4        | 0.82%   |
| Gigabyte B450M DS3H             | 4        | 0.82%   |
| Unknown                         | 4        | 0.82%   |
| MSI MS-7A34                     | 3        | 0.62%   |
| MSI MS-7758                     | 3        | 0.62%   |
| MSI MS-7693                     | 3        | 0.62%   |
| HP Z440 Workstation             | 3        | 0.62%   |
| Gigabyte Z77-DS3H               | 3        | 0.62%   |
| Dell OptiPlex 7010              | 3        | 0.62%   |
| ASUS ROG STRIX X570-E GAMING    | 3        | 0.62%   |
| ASUS PRIME A320M-K              | 3        | 0.62%   |
| Shuttle XH61V                   | 2        | 0.41%   |
| MSI MS-7C91                     | 2        | 0.41%   |
| MSI MS-7C75                     | 2        | 0.41%   |
| MSI MS-7C37                     | 2        | 0.41%   |
| MSI MS-7C02                     | 2        | 0.41%   |
| MSI MS-7B79                     | 2        | 0.41%   |
| MSI MS-7A38                     | 2        | 0.41%   |
| MSI MS-7817                     | 2        | 0.41%   |
| MSI MS-7592                     | 2        | 0.41%   |
| MSI MS-7529                     | 2        | 0.41%   |
| HP EliteDesk 800 G1 SFF         | 2        | 0.41%   |
| HC HCAR357-MI                   | 2        | 0.41%   |
| Gigabyte Z170X-Gaming 7         | 2        | 0.41%   |
| Gigabyte X570 AORUS MASTER      | 2        | 0.41%   |
| Gigabyte H61M-S2PV              | 2        | 0.41%   |
| Gigabyte GA-78LMT-USB3 R2       | 2        | 0.41%   |
| Gigabyte GA-78LMT-USB3 6.0      | 2        | 0.41%   |
| Gigabyte GA-78LMT-USB3          | 2        | 0.41%   |
| Gigabyte F2A55M-HD2             | 2        | 0.41%   |
| Gigabyte AB350M-DS3H V2         | 2        | 0.41%   |
| Gigabyte A320M-S2H              | 2        | 0.41%   |
| Gigabyte 990FXA-UD3             | 2        | 0.41%   |
| Dell Precision T7600            | 2        | 0.41%   |
| Dell OptiPlex 9010              | 2        | 0.41%   |
| Dell OptiPlex 780               | 2        | 0.41%   |
| Dell OptiPlex 390               | 2        | 0.41%   |
| ASUS TUF GAMING Z590-PLUS WIFI  | 2        | 0.41%   |
| ASUS ROG STRIX X570-F GAMING    | 2        | 0.41%   |
| ASUS ROG STRIX X470-F GAMING    | 2        | 0.41%   |
| ASUS ROG STRIX B550-F GAMING    | 2        | 0.41%   |
| ASUS ROG STRIX B550-E GAMING    | 2        | 0.41%   |
| ASUS ROG STRIX B450-F GAMING    | 2        | 0.41%   |
| ASUS ROG Maximus X HERO         | 2        | 0.41%   |
| ASUS PRIME Z590-P               | 2        | 0.41%   |
| ASUS PRIME Z270-A               | 2        | 0.41%   |
| ASUS PRIME H410M-A              | 2        | 0.41%   |
| ASUS P5Q DELUXE                 | 2        | 0.41%   |
| ASUS M5A97 LE R2.0              | 2        | 0.41%   |
| ASUS M2A-VM                     | 2        | 0.41%   |
| ASRock X570 Taichi              | 2        | 0.41%   |
| ASRock N68C-S UCC               | 2        | 0.41%   |
| ASRock B450 Pro4                | 2        | 0.41%   |
| TYAN Toledo i3210W/i3200R S5211 | 1        | 0.21%   |
| SYWZ S210H Series               | 1        | 0.21%   |
| Soyo SY-I5GC2-L                 | 1        | 0.21%   |
| Pegatron NQ840AA-ABD p6029de    | 1        | 0.21%   |
| Pegatron NP218AA-ABA p6142p     | 1        | 0.21%   |
| Pegatron NC062AA-ABZ IQ522it    | 1        | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 30       | 6.17%   |
| ASUS ROG               | 26       | 5.35%   |
| Dell OptiPlex          | 17       | 3.5%    |
| ASUS All               | 14       | 2.88%   |
| Acer Aspire            | 10       | 2.06%   |
| Lenovo ThinkCentre     | 9        | 1.85%   |
| HP Compaq              | 9        | 1.85%   |
| ASUS TUF               | 7        | 1.44%   |
| HP EliteDesk           | 6        | 1.23%   |
| Gigabyte X570          | 6        | 1.23%   |
| Gigabyte GA-78LMT-USB3 | 6        | 1.23%   |
| Gigabyte B450M         | 5        | 1.03%   |
| MSI MS-7B86            | 4        | 0.82%   |
| Dell Precision         | 4        | 0.82%   |
| Unknown                | 4        | 0.82%   |
| MSI MS-7A34            | 3        | 0.62%   |
| MSI MS-7758            | 3        | 0.62%   |
| MSI MS-7693            | 3        | 0.62%   |
| HP Z440                | 3        | 0.62%   |
| Gigabyte Z77-DS3H      | 3        | 0.62%   |
| Gigabyte Z390          | 3        | 0.62%   |
| Dell Inspiron          | 3        | 0.62%   |
| ASUS P8Z77-V           | 3        | 0.62%   |
| ASUS M5A97             | 3        | 0.62%   |
| ASRock X570            | 3        | 0.62%   |
| ASRock B550            | 3        | 0.62%   |
| ASRock 970             | 3        | 0.62%   |
| Shuttle XH61V          | 2        | 0.41%   |
| MSI MS-7C91            | 2        | 0.41%   |
| MSI MS-7C75            | 2        | 0.41%   |
| MSI MS-7C37            | 2        | 0.41%   |
| MSI MS-7C02            | 2        | 0.41%   |
| MSI MS-7B79            | 2        | 0.41%   |
| MSI MS-7A38            | 2        | 0.41%   |
| MSI MS-7817            | 2        | 0.41%   |
| MSI MS-7592            | 2        | 0.41%   |
| MSI MS-7529            | 2        | 0.41%   |
| Lenovo ThinkStation    | 2        | 0.41%   |
| Lenovo IdeaCentre      | 2        | 0.41%   |
| Intel X79              | 2        | 0.41%   |
| HP ProLiant            | 2        | 0.41%   |
| HP ProDesk             | 2        | 0.41%   |
| HP Pavilion            | 2        | 0.41%   |
| HC HCAR357-MI          | 2        | 0.41%   |
| Gigabyte Z590          | 2        | 0.41%   |
| Gigabyte Z170X-Gaming  | 2        | 0.41%   |
| Gigabyte H61M-S2PV     | 2        | 0.41%   |
| Gigabyte F2A55M-HD2    | 2        | 0.41%   |
| Gigabyte B450          | 2        | 0.41%   |
| Gigabyte AB350M-DS3H   | 2        | 0.41%   |
| Gigabyte A320M-S2H     | 2        | 0.41%   |
| Gigabyte 990FXA-UD3    | 2        | 0.41%   |
| Fujitsu CELSIUS        | 2        | 0.41%   |
| Dell Vostro            | 2        | 0.41%   |
| ASUS P5Q               | 2        | 0.41%   |
| ASUS M2A-VM            | 2        | 0.41%   |
| ASRock N68C-S          | 2        | 0.41%   |
| ASRock B450            | 2        | 0.41%   |
| Acer Veriton           | 2        | 0.41%   |
| TYAN Toledo            | 1        | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 81       | 16.67%  |
| 2020 | 58       | 11.93%  |
| 2019 | 53       | 10.91%  |
| 2018 | 42       | 8.64%   |
| 2011 | 33       | 6.79%   |
| 2013 | 32       | 6.58%   |
| 2012 | 28       | 5.76%   |
| 2015 | 26       | 5.35%   |
| 2010 | 26       | 5.35%   |
| 2014 | 23       | 4.73%   |
| 2009 | 23       | 4.73%   |
| 2017 | 21       | 4.32%   |
| 2016 | 16       | 3.29%   |
| 2008 | 13       | 2.67%   |
| 2007 | 5        | 1.03%   |
| 2005 | 4        | 0.82%   |
| 2006 | 2        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 486      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 478      | 98.35%  |
| Enabled  | 8        | 1.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 486      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 125      | 25.67%  |
| 8.01-16.0       | 102      | 20.94%  |
| 32.01-64.0      | 77       | 15.81%  |
| 3.01-4.0        | 66       | 13.55%  |
| 4.01-8.0        | 58       | 11.91%  |
| 64.01-256.0     | 33       | 6.78%   |
| 24.01-32.0      | 12       | 2.46%   |
| 1.01-2.0        | 11       | 2.26%   |
| 2.01-3.0        | 2        | 0.41%   |
| More than 256.0 | 1        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 194      | 37.67%  |
| 2.01-3.0    | 136      | 26.41%  |
| 4.01-8.0    | 77       | 14.95%  |
| 3.01-4.0    | 55       | 10.68%  |
| 8.01-16.0   | 27       | 5.24%   |
| 16.01-24.0  | 9        | 1.75%   |
| 0.51-1.0    | 8        | 1.55%   |
| 32.01-64.0  | 5        | 0.97%   |
| 24.01-32.0  | 3        | 0.58%   |
| 64.01-256.0 | 1        | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 182      | 36.62%  |
| 2      | 132      | 26.56%  |
| 3      | 76       | 15.29%  |
| 4      | 49       | 9.86%   |
| 5      | 27       | 5.43%   |
| 6      | 12       | 2.41%   |
| 8      | 5        | 1.01%   |
| 7      | 5        | 1.01%   |
| 0      | 4        | 0.8%    |
| 9      | 3        | 0.6%    |
| 11     | 1        | 0.2%    |
| 10     | 1        | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 258      | 52.76%  |
| Yes       | 231      | 47.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 476      | 97.94%  |
| No        | 10       | 2.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 251      | 51.33%  |
| Yes       | 238      | 48.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 304      | 62.17%  |
| Yes       | 185      | 37.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 90       | 18.48%  |
| Germany             | 85       | 17.45%  |
| France              | 32       | 6.57%   |
| Italy               | 25       | 5.13%   |
| UK                  | 19       | 3.9%    |
| Canada              | 18       | 3.7%    |
| Russia              | 17       | 3.49%   |
| Brazil              | 17       | 3.49%   |
| Spain               | 14       | 2.87%   |
| Australia           | 14       | 2.87%   |
| Poland              | 12       | 2.46%   |
| Switzerland         | 9        | 1.85%   |
| Netherlands         | 9        | 1.85%   |
| Ukraine             | 8        | 1.64%   |
| Austria             | 8        | 1.64%   |
| Argentina           | 8        | 1.64%   |
| Sweden              | 7        | 1.44%   |
| India               | 7        | 1.44%   |
| Portugal            | 6        | 1.23%   |
| Japan               | 5        | 1.03%   |
| Greece              | 5        | 1.03%   |
| China               | 5        | 1.03%   |
| South Africa        | 4        | 0.82%   |
| Serbia              | 4        | 0.82%   |
| Romania             | 4        | 0.82%   |
| New Zealand         | 4        | 0.82%   |
| Hungary             | 4        | 0.82%   |
| Finland             | 4        | 0.82%   |
| Czechia             | 4        | 0.82%   |
| Chile               | 4        | 0.82%   |
| Norway              | 3        | 0.62%   |
| Bulgaria            | 3        | 0.62%   |
| Belgium             | 3        | 0.62%   |
| Pakistan            | 2        | 0.41%   |
| Israel              | 2        | 0.41%   |
| Indonesia           | 2        | 0.41%   |
| Turkey              | 1        | 0.21%   |
| Trinidad and Tobago | 1        | 0.21%   |
| Taiwan              | 1        | 0.21%   |
| Sint Maarten        | 1        | 0.21%   |
| Singapore           | 1        | 0.21%   |
| Réunion            | 1        | 0.21%   |
| Nicaragua           | 1        | 0.21%   |
| Mexico              | 1        | 0.21%   |
| Malaysia            | 1        | 0.21%   |
| Iceland             | 1        | 0.21%   |
| Hong Kong           | 1        | 0.21%   |
| Estonia             | 1        | 0.21%   |
| Croatia             | 1        | 0.21%   |
| Colombia            | 1        | 0.21%   |
| Bermuda             | 1        | 0.21%   |
| Belarus             | 1        | 0.21%   |
| Bangladesh          | 1        | 0.21%   |
| Bahrain             | 1        | 0.21%   |
| Armenia             | 1        | 0.21%   |
| Algeria             | 1        | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 7        | 1.39%   |
| Paris          | 6        | 1.2%    |
| Milan          | 6        | 1.2%    |
| Vienna         | 5        | 1%      |
| Moscow         | 5        | 1%      |
| Sydney         | 4        | 0.8%    |
| London         | 4        | 0.8%    |
| Toronto        | 3        | 0.6%    |
| Munich         | 3        | 0.6%    |
| Krefeld        | 3        | 0.6%    |
| Hyderabad      | 3        | 0.6%    |
| Hamburg        | 3        | 0.6%    |
| Dallas         | 3        | 0.6%    |
| Budapest       | 3        | 0.6%    |
| Athens         | 3        | 0.6%    |
| Zurich         | 2        | 0.4%    |
| Warsaw         | 2        | 0.4%    |
| Ufa            | 2        | 0.4%    |
| Tucson         | 2        | 0.4%    |
| Sonneberg      | 2        | 0.4%    |
| Sofia          | 2        | 0.4%    |
| S??o Paulo     | 2        | 0.4%    |
| Rosario        | 2        | 0.4%    |
| Portland       | 2        | 0.4%    |
| Perth          | 2        | 0.4%    |
| Oslo           | 2        | 0.4%    |
| Novi Sad       | 2        | 0.4%    |
| Montreal       | 2        | 0.4%    |
| Melbourne      | 2        | 0.4%    |
| Lutisburg      | 2        | 0.4%    |
| Laberweinting  | 2        | 0.4%    |
| Kyiv           | 2        | 0.4%    |
| Krakow         | 2        | 0.4%    |
| Karachi        | 2        | 0.4%    |
| Johannesburg   | 2        | 0.4%    |
| Irkutsk        | 2        | 0.4%    |
| Haltern am See | 2        | 0.4%    |
| Graz           | 2        | 0.4%    |
| Gelsenkirchen  | 2        | 0.4%    |
| Cologne        | 2        | 0.4%    |
| Chicago        | 2        | 0.4%    |
| Calgary        | 2        | 0.4%    |
| Cahors         | 2        | 0.4%    |
| Brisbane       | 2        | 0.4%    |
| Bolzano        | 2        | 0.4%    |
| Belgrade       | 2        | 0.4%    |
| Beijing        | 2        | 0.4%    |
| Auckland       | 2        | 0.4%    |
| Zittau         | 1        | 0.2%    |
| Zeist          | 1        | 0.2%    |
| Zdanice        | 1        | 0.2%    |
| Zabrze         | 1        | 0.2%    |
| Yerevan        | 1        | 0.2%    |
| Yekaterinburg  | 1        | 0.2%    |
| Węgorzewo     | 1        | 0.2%    |
| Wylie          | 1        | 0.2%    |
| Wuxi           | 1        | 0.2%    |
| Wuhan          | 1        | 0.2%    |
| Wroclaw        | 1        | 0.2%    |
| Woodstock      | 1        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 175      | 281    | 19.02%  |
| Seagate                   | 164      | 272    | 17.83%  |
| Samsung Electronics       | 145      | 209    | 15.76%  |
| Toshiba                   | 54       | 67     | 5.87%   |
| Kingston                  | 48       | 60     | 5.22%   |
| SanDisk                   | 45       | 57     | 4.89%   |
| Crucial                   | 41       | 50     | 4.46%   |
| Hitachi                   | 34       | 43     | 3.7%    |
| A-DATA Technology         | 18       | 22     | 1.96%   |
| Silicon Motion            | 17       | 18     | 1.85%   |
| Phison                    | 16       | 21     | 1.74%   |
| Intel                     | 14       | 17     | 1.52%   |
| Unknown                   | 11       | 15     | 1.2%    |
| MAXTOR                    | 8        | 10     | 0.87%   |
| HGST                      | 7        | 10     | 0.76%   |
| China                     | 7        | 8      | 0.76%   |
| SPCC                      | 6        | 7      | 0.65%   |
| Micron Technology         | 6        | 6      | 0.65%   |
| Corsair                   | 6        | 9      | 0.65%   |
| PNY                       | 5        | 5      | 0.54%   |
| JMicron                   | 5        | 7      | 0.54%   |
| Intenso                   | 5        | 6      | 0.54%   |
| GOODRAM                   | 5        | 5      | 0.54%   |
| Gigabyte Technology       | 5        | 6      | 0.54%   |
| XPG                       | 4        | 4      | 0.43%   |
| Transcend                 | 4        | 4      | 0.43%   |
| Micron/Crucial Technology | 4        | 5      | 0.43%   |
| Patriot                   | 3        | 5      | 0.33%   |
| OCZ                       | 3        | 3      | 0.33%   |
| Mushkin                   | 3        | 6      | 0.33%   |
| LITEONIT                  | 3        | 3      | 0.33%   |
| LITEON                    | 3        | 4      | 0.33%   |
| Vaseky                    | 2        | 2      | 0.22%   |
| SK Hynix                  | 2        | 2      | 0.22%   |
| PLEXTOR                   | 2        | 2      | 0.22%   |
| LaCie                     | 2        | 2      | 0.22%   |
| Zozt                      | 1        | 3      | 0.11%   |
| Zheino                    | 1        | 2      | 0.11%   |
| WD MediaMax               | 1        | 1      | 0.11%   |
| Verbatim                  | 1        | 1      | 0.11%   |
| Teclast                   | 1        | 1      | 0.11%   |
| Team                      | 1        | 1      | 0.11%   |
| T-FORCE                   | 1        | 2      | 0.11%   |
| Synology                  | 1        | 8      | 0.11%   |
| SABRENT                   | 1        | 1      | 0.11%   |
| RX7                       | 1        | 1      | 0.11%   |
| RSH-339                   | 1        | 1      | 0.11%   |
| Realtek Semiconductor     | 1        | 3      | 0.11%   |
| Palit                     | 1        | 1      | 0.11%   |
| OCZ-VERTEX3               | 1        | 1      | 0.11%   |
| Netac                     | 1        | 1      | 0.11%   |
| Lexar                     | 1        | 1      | 0.11%   |
| LDLC                      | 1        | 1      | 0.11%   |
| KLEVV                     | 1        | 1      | 0.11%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.11%   |
| KIOXIA                    | 1        | 1      | 0.11%   |
| KingFast                  | 1        | 1      | 0.11%   |
| KingDian                  | 1        | 1      | 0.11%   |
| HPE                       | 1        | 1      | 0.11%   |
| Hewlett-Packard           | 1        | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB        | 16       | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB      | 15       | 1.39%   |
| Toshiba DT01ACA100 1TB              | 13       | 1.2%    |
| Samsung SSD 860 EVO 500GB           | 12       | 1.11%   |
| Seagate ST2000DM001-1ER164 2TB      | 11       | 1.02%   |
| Kingston SA400S37240G 240GB SSD     | 11       | 1.02%   |
| Samsung NVMe SSD Drive 1TB          | 10       | 0.93%   |
| Seagate ST500DM002-1BD142 500GB     | 9        | 0.83%   |
| Samsung SSD 850 EVO 500GB           | 9        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB      | 8        | 0.74%   |
| Samsung SSD 860 EVO 250GB           | 8        | 0.74%   |
| Toshiba DT01ACA200 2TB              | 7        | 0.65%   |
| Seagate ST31000524AS 1TB            | 7        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB      | 7        | 0.65%   |
| Seagate Expansion 5TB               | 7        | 0.65%   |
| Samsung SSD 850 EVO 250GB           | 7        | 0.65%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 6        | 0.56%   |
| Seagate ST3500418AS 500GB           | 6        | 0.56%   |
| Sandisk NVMe SSD Drive 500GB        | 6        | 0.56%   |
| Samsung SSD 840 EVO 250GB           | 6        | 0.56%   |
| Samsung NVMe SSD Drive 250GB        | 6        | 0.56%   |
| Kingston SV300S37A120G 120GB SSD    | 6        | 0.56%   |
| Kingston SA400S37480G 480GB SSD     | 6        | 0.56%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB         | 6        | 0.56%   |
| WDC WD20EZRX-00D8PB0 2TB            | 5        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5        | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB      | 5        | 0.46%   |
| SanDisk SSD PLUS 240GB              | 5        | 0.46%   |
| Sandisk NVMe SSD Drive 2TB          | 5        | 0.46%   |
| Sandisk NVMe SSD Drive 1TB          | 5        | 0.46%   |
| Crucial CT500MX500SSD1 500GB        | 5        | 0.46%   |
| WDC WD10EARS-00Y5B1 1TB             | 4        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB         | 4        | 0.37%   |
| Seagate ST9500325AS 500GB           | 4        | 0.37%   |
| Seagate ST6000DM003-2CY186 6TB      | 4        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 0.37%   |
| SanDisk SSD PLUS 1000GB             | 4        | 0.37%   |
| Samsung SSD 850 EVO 120GB           | 4        | 0.37%   |
| Samsung SSD 830 Series 128GB        | 4        | 0.37%   |
| Samsung NVMe SSD Drive 512GB        | 4        | 0.37%   |
| Crucial CT240BX500SSD1 240GB        | 4        | 0.37%   |
| XPG NVMe SSD Drive 1024GB           | 3        | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 3        | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.28%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 3        | 0.28%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 3        | 0.28%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 0.28%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 3        | 0.28%   |
| WDC WD20EFRX-68EUZN0 2TB            | 3        | 0.28%   |
| WDC WD10EZEX-75ZF5A0 1TB            | 3        | 0.28%   |
| WDC WD10EZEX-00BN5A0 1TB            | 3        | 0.28%   |
| WDC WD10EALX-009BA0 1TB             | 3        | 0.28%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 3        | 0.28%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 3        | 0.28%   |
| Toshiba MQ01ABD100 1TB              | 3        | 0.28%   |
| Toshiba HDWD130 3TB                 | 3        | 0.28%   |
| Toshiba HDWD110 1TB                 | 3        | 0.28%   |
| SPCC Solid State Disk 128GB         | 3        | 0.28%   |
| Silicon Motion NVMe SSD Drive 512GB | 3        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 161      | 267    | 35.7%   |
| WDC                 | 160      | 260    | 35.48%  |
| Toshiba             | 48       | 60     | 10.64%  |
| Hitachi             | 34       | 43     | 7.54%   |
| Samsung Electronics | 24       | 29     | 5.32%   |
| MAXTOR              | 8        | 10     | 1.77%   |
| HGST                | 7        | 10     | 1.55%   |
| Unknown             | 4        | 4      | 0.89%   |
| Synology            | 1        | 8      | 0.22%   |
| Fujitsu             | 1        | 1      | 0.22%   |
| ASMT109x            | 1        | 1      | 0.22%   |
| Asmedia             | 1        | 1      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 80       | 101    | 26.14%  |
| Kingston            | 41       | 48     | 13.4%   |
| Crucial             | 38       | 47     | 12.42%  |
| SanDisk             | 29       | 34     | 9.48%   |
| A-DATA Technology   | 16       | 18     | 5.23%   |
| WDC                 | 14       | 15     | 4.58%   |
| China               | 7        | 8      | 2.29%   |
| Toshiba             | 6        | 6      | 1.96%   |
| SPCC                | 6        | 7      | 1.96%   |
| Micron Technology   | 5        | 5      | 1.63%   |
| GOODRAM             | 5        | 5      | 1.63%   |
| Transcend           | 4        | 4      | 1.31%   |
| PNY                 | 4        | 4      | 1.31%   |
| Intenso             | 4        | 5      | 1.31%   |
| Patriot             | 3        | 5      | 0.98%   |
| OCZ                 | 3        | 3      | 0.98%   |
| Mushkin             | 3        | 6      | 0.98%   |
| LITEONIT            | 3        | 3      | 0.98%   |
| LITEON              | 3        | 4      | 0.98%   |
| Intel               | 3        | 4      | 0.98%   |
| Gigabyte Technology | 3        | 3      | 0.98%   |
| Vaseky              | 2        | 2      | 0.65%   |
| PLEXTOR             | 2        | 2      | 0.65%   |
| Zozt                | 1        | 3      | 0.33%   |
| Zheino              | 1        | 2      | 0.33%   |
| Verbatim            | 1        | 1      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |
| Teclast             | 1        | 1      | 0.33%   |
| Team                | 1        | 1      | 0.33%   |
| SABRENT             | 1        | 1      | 0.33%   |
| Palit               | 1        | 1      | 0.33%   |
| OCZ-VERTEX3         | 1        | 1      | 0.33%   |
| Lexar               | 1        | 1      | 0.33%   |
| LDLC                | 1        | 1      | 0.33%   |
| KLEVV               | 1        | 1      | 0.33%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.33%   |
| KingDian            | 1        | 1      | 0.33%   |
| JMicron             | 1        | 2      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| DREVO               | 1        | 1      | 0.33%   |
| Dogfish             | 1        | 1      | 0.33%   |
| Corsair             | 1        | 1      | 0.33%   |
| ASMT                | 1        | 1      | 0.33%   |
| AMD-RAID            | 1        | 1      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 337      | 695    | 44.58%  |
| SSD     | 252      | 365    | 33.33%  |
| NVMe    | 144      | 215    | 19.05%  |
| Unknown | 21       | 29     | 2.78%   |
| MMC     | 2        | 2      | 0.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 448      | 1034   | 71.34%  |
| NVMe | 140      | 211    | 22.29%  |
| SAS  | 38       | 59     | 6.05%   |
| MMC  | 2        | 2      | 0.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 316      | 537    | 47.73%  |
| 0.51-1.0   | 186      | 270    | 28.1%   |
| 1.01-2.0   | 87       | 140    | 13.14%  |
| 3.01-4.0   | 26       | 32     | 3.93%   |
| 4.01-10.0  | 26       | 41     | 3.93%   |
| 2.01-3.0   | 15       | 18     | 2.27%   |
| 10.01-20.0 | 6        | 22     | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 105      | 21%     |
| 251-500        | 104      | 20.8%   |
| 501-1000       | 89       | 17.8%   |
| 1001-2000      | 66       | 13.2%   |
| More than 3000 | 49       | 9.8%    |
| 2001-3000      | 24       | 4.8%    |
| 21-50          | 21       | 4.2%    |
| 51-100         | 20       | 4%      |
| 1-20           | 18       | 3.6%    |
| Unknown        | 4        | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 190      | 37.18%  |
| 21-50          | 78       | 15.26%  |
| 101-250        | 63       | 12.33%  |
| 51-100         | 49       | 9.59%   |
| 501-1000       | 36       | 7.05%   |
| 251-500        | 32       | 6.26%   |
| 1001-2000      | 30       | 5.87%   |
| More than 3000 | 20       | 3.91%   |
| 2001-3000      | 9        | 1.76%   |
| Unknown        | 4        | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                    | 2        | 2      | 4.55%   |
| Crucial CT240M500SSD1 240GB                    | 2        | 2      | 4.55%   |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1        | 1      | 2.27%   |
| WDC WD7500AADS-00M2B0 752GB                    | 1        | 1      | 2.27%   |
| WDC WD6400AAKS-65A7B0 640GB                    | 1        | 1      | 2.27%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1        | 1      | 2.27%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1        | 1      | 2.27%   |
| WDC WD5000AAKS-00UU3A0 500GB                   | 1        | 1      | 2.27%   |
| WDC WD5000AADS-00S9B0 500GB                    | 1        | 1      | 2.27%   |
| WDC WD5000AADS-00L4B1 500GB                    | 1        | 1      | 2.27%   |
| WDC WD3200AAVS-00ZTB0 320GB                    | 1        | 1      | 2.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1        | 1      | 2.27%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1        | 1      | 2.27%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 2.27%   |
| WDC WD10EADS-65M2B1 1TB                        | 1        | 1      | 2.27%   |
| WDC WD1003FZEX-00MK2A0 1TB                     | 1        | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB                       | 1        | 1      | 2.27%   |
| Toshiba DT01ACA100 1TB                         | 1        | 1      | 2.27%   |
| Seagate ST9250311CS 250GB                      | 1        | 1      | 2.27%   |
| Seagate ST500NM0011 39M4517 42C0468IBM 500GB   | 1        | 1      | 2.27%   |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 2.27%   |
| Seagate ST4000DM004-2CV104 4TB                 | 1        | 1      | 2.27%   |
| Seagate ST3750640NS 752GB                      | 1        | 1      | 2.27%   |
| Seagate ST3750330NS 752GB                      | 1        | 1      | 2.27%   |
| Seagate ST3500830AS 500GB                      | 1        | 1      | 2.27%   |
| Seagate ST3500414CS 500GB                      | 1        | 1      | 2.27%   |
| Seagate ST3320820AS 320GB                      | 1        | 1      | 2.27%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1        | 1      | 2.27%   |
| Seagate ST2000DL003-9VT166 2TB                 | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 870 EVO 4TB            | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 840 EVO 500GB          | 1        | 1      | 2.27%   |
| Samsung Electronics HD103SJ 1TB                | 1        | 1      | 2.27%   |
| PLEXTOR PX-128M5S 128GB SSD                    | 1        | 1      | 2.27%   |
| OCZ VERTEX3 120GB SSD                          | 1        | 1      | 2.27%   |
| OCZ AGITLITY3 480GB SSD                        | 1        | 1      | 2.27%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1        | 1      | 2.27%   |
| Kingston SUV400S37240G 240GB SSD               | 1        | 1      | 2.27%   |
| Kingston SH103S3120G 120GB SSD                 | 1        | 1      | 2.27%   |
| Kingston SA400S37120G 120GB SSD                | 1        | 1      | 2.27%   |
| Intel SSDSC2KW240H6 240GB                      | 1        | 1      | 2.27%   |
| Hitachi HDS5C3020ALA632 2TB                    | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 34.15%  |
| Seagate             | 10       | 11     | 24.39%  |
| Samsung Electronics | 4        | 4      | 9.76%   |
| Kingston            | 3        | 3      | 7.32%   |
| Toshiba             | 2        | 2      | 4.88%   |
| OCZ                 | 2        | 2      | 4.88%   |
| Crucial             | 2        | 2      | 4.88%   |
| PLEXTOR             | 1        | 1      | 2.44%   |
| Micron Technology   | 1        | 1      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |
| Hitachi             | 1        | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 50%     |
| Seagate             | 10       | 11     | 35.71%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 31     | 69.23%  |
| SSD  | 11       | 12     | 28.21%  |
| NVMe | 1        | 1      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 388      | 979    | 73.21%  |
| Works    | 105      | 282    | 19.81%  |
| Malfunc  | 36       | 44     | 6.79%   |
| Failed   | 1        | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 311      | 44.81%  |
| AMD                          | 164      | 23.63%  |
| Samsung Electronics          | 57       | 8.21%   |
| Sandisk                      | 23       | 3.31%   |
| Phison Electronics           | 23       | 3.31%   |
| ASMedia Technology           | 19       | 2.74%   |
| Silicon Motion               | 18       | 2.59%   |
| Nvidia                       | 15       | 2.16%   |
| Marvell Technology Group     | 13       | 1.87%   |
| JMicron Technology           | 10       | 1.44%   |
| Kingston Technology Company  | 8        | 1.15%   |
| ADATA Technology             | 8        | 1.15%   |
| Micron/Crucial Technology    | 7        | 1.01%   |
| Silicon Image                | 4        | 0.58%   |
| VIA Technologies             | 2        | 0.29%   |
| Broadcom / LSI               | 2        | 0.29%   |
| Unknown                      | 1        | 0.14%   |
| Toshiba America Info Systems | 1        | 0.14%   |
| SK Hynix                     | 1        | 0.14%   |
| Realtek Semiconductor        | 1        | 0.14%   |
| Micron Technology            | 1        | 0.14%   |
| LSI Logic / Symbios Logic    | 1        | 0.14%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.14%   |
| KIOXIA                       | 1        | 0.14%   |
| Hewlett-Packard              | 1        | 0.14%   |
| Adaptec                      | 1        | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 91       | 10.31%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34       | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32       | 3.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32       | 3.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 28       | 3.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 26       | 2.94%   |
| Intel SATA Controller [RAID mode]                                                       | 23       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 2.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21       | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 20       | 2.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 20       | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 18       | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18       | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17       | 1.93%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 15       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 1.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 12       | 1.36%   |
| Phison E12 NVMe Controller                                                              | 12       | 1.36%   |
| AMD FCH SATA Controller D                                                               | 12       | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11       | 1.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 1.13%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9        | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.02%   |
| AMD FCH IDE Controller                                                                  | 9        | 1.02%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 8        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 0.91%   |
| Intel SSD 660P Series                                                                   | 8        | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 8        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7        | 0.79%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 7        | 0.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 6        | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.68%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 6        | 0.68%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 0.57%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 5        | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 0.57%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 5        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 5        | 0.57%   |
| Sandisk WD Black SN850                                                                  | 4        | 0.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4        | 0.45%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4        | 0.45%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.45%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.45%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.45%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.45%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.45%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 0.45%   |
| Phison E7 NVMe Controller                                                               | 3        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 391      | 56.18%  |
| NVMe | 138      | 19.83%  |
| IDE  | 123      | 17.67%  |
| RAID | 36       | 5.17%   |
| SAS  | 6        | 0.86%   |
| SCSI | 2        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 310      | 63.79%  |
| AMD    | 176      | 36.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 2.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 2.26%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 8        | 1.64%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 8        | 1.64%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 1.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7        | 1.44%   |
| AMD FX-8350 Eight-Core Processor            | 7        | 1.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.23%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 6        | 1.23%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 1.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 1.23%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1.23%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 5        | 1.03%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 5        | 1.03%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 1.03%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 1.03%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 1.03%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.03%   |
| AMD FX-6300 Six-Core Processor              | 5        | 1.03%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.82%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 4        | 0.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.82%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.82%   |
| AMD A4-4000 APU with Radeon HD Graphics     | 4        | 0.82%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 3        | 0.62%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 3        | 0.62%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.62%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 3        | 0.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.62%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.62%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 3        | 0.62%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.62%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.62%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.62%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 0.62%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 3        | 0.62%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 0.62%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.62%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.62%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 0.62%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.62%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.62%   |
| AMD FX-8370 Eight-Core Processor            | 3        | 0.62%   |
| AMD Athlon II X2 245 Processor              | 3        | 0.62%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2        | 0.41%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 2        | 0.41%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2        | 0.41%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.41%   |
| Intel Pentium D CPU 3.40GHz                 | 2        | 0.41%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.41%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 2        | 0.41%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.41%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 96       | 19.71%  |
| Intel Core i7           | 64       | 13.14%  |
| AMD Ryzen 5             | 46       | 9.45%   |
| Intel Core i3           | 37       | 7.6%    |
| AMD Ryzen 7             | 27       | 5.54%   |
| Intel Xeon              | 21       | 4.31%   |
| AMD FX                  | 21       | 4.31%   |
| Intel Core i9           | 15       | 3.08%   |
| Intel Core 2 Duo        | 14       | 2.87%   |
| Intel Celeron           | 14       | 2.87%   |
| Intel Pentium Dual-Core | 13       | 2.67%   |
| AMD Ryzen 9             | 11       | 2.26%   |
| AMD Ryzen 3             | 11       | 2.26%   |
| Intel Core 2 Quad       | 8        | 1.64%   |
| AMD Athlon 64 X2        | 8        | 1.64%   |
| AMD A4                  | 8        | 1.64%   |
| Other                   | 7        | 1.44%   |
| AMD Phenom II X4        | 7        | 1.44%   |
| Intel Pentium           | 6        | 1.23%   |
| AMD Ryzen Threadripper  | 6        | 1.23%   |
| AMD Athlon II X2        | 6        | 1.23%   |
| AMD Phenom              | 4        | 0.82%   |
| Intel Pentium D         | 3        | 0.62%   |
| Intel Pentium 4         | 3        | 0.62%   |
| AMD Phenom II X6        | 3        | 0.62%   |
| AMD A6                  | 3        | 0.62%   |
| AMD A10                 | 3        | 0.62%   |
| Intel Pentium Dual      | 2        | 0.41%   |
| Intel Core 2            | 2        | 0.41%   |
| AMD A8                  | 2        | 0.41%   |
| Intel Pentium Silver    | 1        | 0.21%   |
| Intel Genuine           | 1        | 0.21%   |
| Intel Core 2 Extreme    | 1        | 0.21%   |
| Intel Celeron D         | 1        | 0.21%   |
| Intel Atom              | 1        | 0.21%   |
| AMD Turion II Neo       | 1        | 0.21%   |
| AMD Sempron             | 1        | 0.21%   |
| AMD Ryzen 5 PRO         | 1        | 0.21%   |
| AMD Phenom II X3        | 1        | 0.21%   |
| AMD Phenom II X2        | 1        | 0.21%   |
| AMD GX                  | 1        | 0.21%   |
| AMD E                   | 1        | 0.21%   |
| AMD Athlon X4           | 1        | 0.21%   |
| AMD Athlon X2           | 1        | 0.21%   |
| AMD Athlon Dual Core    | 1        | 0.21%   |
| AMD Athlon              | 1        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 192      | 39.43%  |
| 2      | 113      | 23.2%   |
| 6      | 78       | 16.02%  |
| 8      | 50       | 10.27%  |
| 1      | 13       | 2.67%   |
| 10     | 12       | 2.46%   |
| 12     | 9        | 1.85%   |
| 3      | 9        | 1.85%   |
| 16     | 5        | 1.03%   |
| 24     | 3        | 0.62%   |
| 64     | 1        | 0.21%   |
| 36     | 1        | 0.21%   |
| 14     | 1        | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 481      | 98.97%  |
| 2      | 5        | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 274      | 56.38%  |
| 1      | 212      | 43.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 486      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 337      | 68.22%  |
| 0x306c3    | 18       | 3.64%   |
| 0x08701021 | 12       | 2.43%   |
| 0x306a9    | 10       | 2.02%   |
| 0xa0655    | 9        | 1.82%   |
| 0xa0653    | 8        | 1.62%   |
| 0x906ea    | 8        | 1.62%   |
| 0x206a7    | 7        | 1.42%   |
| 0x906ed    | 6        | 1.21%   |
| 0x08108109 | 6        | 1.21%   |
| 0xa0671    | 5        | 1.01%   |
| 0x1067a    | 5        | 1.01%   |
| 0x0800820d | 5        | 1.01%   |
| 0x906e9    | 4        | 0.81%   |
| 0x0a201016 | 4        | 0.81%   |
| 0x0a201009 | 4        | 0.81%   |
| 0x06000852 | 4        | 0.81%   |
| 0x506e3    | 3        | 0.61%   |
| 0x906eb    | 2        | 0.4%    |
| 0x20655    | 2        | 0.4%    |
| 0x106a5    | 2        | 0.4%    |
| 0x08701013 | 2        | 0.4%    |
| 0x08001137 | 2        | 0.4%    |
| 0x010000dc | 2        | 0.4%    |
| 0xf64      | 1        | 0.2%    |
| 0xf43      | 1        | 0.2%    |
| 0x706a8    | 1        | 0.2%    |
| 0x6fd      | 1        | 0.2%    |
| 0x6fb      | 1        | 0.2%    |
| 0x50654    | 1        | 0.2%    |
| 0x406f1    | 1        | 0.2%    |
| 0x406c3    | 1        | 0.2%    |
| 0x306e4    | 1        | 0.2%    |
| 0x206d7    | 1        | 0.2%    |
| 0x206c2    | 1        | 0.2%    |
| 0x20652    | 1        | 0.2%    |
| 0x106e5    | 1        | 0.2%    |
| 0x10676    | 1        | 0.2%    |
| 0x0a50000c | 1        | 0.2%    |
| 0x0a201006 | 1        | 0.2%    |
| 0x08301039 | 1        | 0.2%    |
| 0x08101016 | 1        | 0.2%    |
| 0x08001138 | 1        | 0.2%    |
| 0x0800111c | 1        | 0.2%    |
| 0x06003106 | 1        | 0.2%    |
| 0x06001119 | 1        | 0.2%    |
| 0x0600063e | 1        | 0.2%    |
| 0x02000057 | 1        | 0.2%    |
| 0x010000db | 1        | 0.2%    |
| 0x010000c8 | 1        | 0.2%    |
| 0x01000083 | 1        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KabyLake        | 50       | 10.27%  |
| Haswell         | 49       | 10.06%  |
| IvyBridge       | 39       | 8.01%   |
| Zen 2           | 38       | 7.8%    |
| SandyBridge     | 38       | 7.8%    |
| Penryn          | 32       | 6.57%   |
| CometLake       | 32       | 6.57%   |
| Piledriver      | 29       | 5.95%   |
| Zen+            | 26       | 5.34%   |
| Zen             | 23       | 4.72%   |
| K10             | 23       | 4.72%   |
| Skylake         | 19       | 3.9%    |
| Zen 3           | 16       | 3.29%   |
| Core            | 11       | 2.26%   |
| Nehalem         | 10       | 2.05%   |
| K8 Hammer       | 9        | 1.85%   |
| NetBurst        | 7        | 1.44%   |
| Westmere        | 6        | 1.23%   |
| Icelake         | 4        | 0.82%   |
| Broadwell       | 4        | 0.82%   |
| Steamroller     | 3        | 0.62%   |
| K10 Llano       | 3        | 0.62%   |
| Silvermont      | 2        | 0.41%   |
| Puma            | 2        | 0.41%   |
| Goldmont plus   | 2        | 0.41%   |
| Goldmont        | 2        | 0.41%   |
| Bulldozer       | 2        | 0.41%   |
| Unknown         | 2        | 0.41%   |
| TigerLake       | 1        | 0.21%   |
| K8 & K10 hybrid | 1        | 0.21%   |
| Jaguar          | 1        | 0.21%   |
| Bobcat          | 1        | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 204      | 40.16%  |
| AMD                                          | 155      | 30.51%  |
| Intel                                        | 147      | 28.94%  |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.2%    |
| ASPEED Technology                            | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 27       | 5.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23       | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 4.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19       | 3.65%   |
| Nvidia GK208B [GeForce GT 710]                                              | 17       | 3.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14       | 2.69%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 2.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 11       | 2.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.92%   |
| AMD Picasso                                                                 | 10       | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.73%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 8        | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                              | 8        | 1.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 1.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 1.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 7        | 1.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.35%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 6        | 1.15%   |
| Intel HD Graphics 630                                                       | 6        | 1.15%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 6        | 1.15%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 6        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 0.96%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.96%   |
| Intel HD Graphics 530                                                       | 5        | 0.96%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 5        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.77%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 0.77%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.77%   |
| Intel HD Graphics 510                                                       | 4        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 0.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 0.77%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 4        | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 3        | 0.58%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 0.58%   |
| Nvidia GT215 [GeForce GT 240]                                               | 3        | 0.58%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.58%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 3        | 0.58%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 0.58%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 0.58%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 3        | 0.58%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 3        | 0.58%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.58%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.38%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.38%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.38%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.38%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 2        | 0.38%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.38%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.38%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.38%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.38%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 191      | 39.22%  |
| 1 x AMD             | 146      | 29.98%  |
| 1 x Intel           | 128      | 26.28%  |
| Intel + Nvidia      | 6        | 1.23%   |
| 2 x Nvidia          | 5        | 1.03%   |
| Intel + AMD         | 4        | 0.82%   |
| 2 x AMD             | 3        | 0.62%   |
| 1 x XGI             | 1        | 0.21%   |
| 1 x Intel + 4 x AMD | 1        | 0.21%   |
| 1 x ASPEED          | 1        | 0.21%   |
| AMD + Nvidia        | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 351      | 71.49%  |
| Proprietary | 120      | 24.44%  |
| Unknown     | 20       | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 340      | 69.25%  |
| 1.01-2.0   | 48       | 9.78%   |
| 7.01-8.0   | 29       | 5.91%   |
| 3.01-4.0   | 20       | 4.07%   |
| 0.51-1.0   | 20       | 4.07%   |
| 8.01-16.0  | 12       | 2.44%   |
| 0.01-0.5   | 10       | 2.04%   |
| 5.01-6.0   | 9        | 1.83%   |
| 2.01-3.0   | 3        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 100      | 19.84%  |
| Dell                 | 58       | 11.51%  |
| Goldstar             | 49       | 9.72%   |
| Acer                 | 46       | 9.13%   |
| Hewlett-Packard      | 29       | 5.75%   |
| Ancor Communications | 28       | 5.56%   |
| Philips              | 20       | 3.97%   |
| BenQ                 | 19       | 3.77%   |
| AOC                  | 18       | 3.57%   |
| Unknown              | 16       | 3.17%   |
| LG Electronics       | 14       | 2.78%   |
| ViewSonic            | 9        | 1.79%   |
| Sony                 | 8        | 1.59%   |
| Iiyama               | 7        | 1.39%   |
| Lenovo               | 6        | 1.19%   |
| NEC Computers        | 5        | 0.99%   |
| Fujitsu Siemens      | 5        | 0.99%   |
| ASUSTek Computer     | 5        | 0.99%   |
| Hitachi              | 4        | 0.79%   |
| HannStar             | 4        | 0.79%   |
| Medion               | 3        | 0.6%    |
| Idek Iiyama          | 3        | 0.6%    |
| Viotek               | 2        | 0.4%    |
| Vestel Elektronik    | 2        | 0.4%    |
| Toshiba              | 2        | 0.4%    |
| SKY                  | 2        | 0.4%    |
| Panasonic            | 2        | 0.4%    |
| Eizo                 | 2        | 0.4%    |
| Xiaomi               | 1        | 0.2%    |
| Vizio                | 1        | 0.2%    |
| Vestel               | 1        | 0.2%    |
| Unknown (XXX)        | 1        | 0.2%    |
| Tech Concepts        | 1        | 0.2%    |
| SVA                  | 1        | 0.2%    |
| STD                  | 1        | 0.2%    |
| Sharp                | 1        | 0.2%    |
| Sceptre Tech         | 1        | 0.2%    |
| Sceptre              | 1        | 0.2%    |
| RTK                  | 1        | 0.2%    |
| PRISM+               | 1        | 0.2%    |
| Plain Tree Systems   | 1        | 0.2%    |
| Pixio                | 1        | 0.2%    |
| Packard Bell         | 1        | 0.2%    |
| ONN                  | 1        | 0.2%    |
| OEM                  | 1        | 0.2%    |
| MTS                  | 1        | 0.2%    |
| MStar                | 1        | 0.2%    |
| MSI                  | 1        | 0.2%    |
| MLK                  | 1        | 0.2%    |
| MiTAC                | 1        | 0.2%    |
| LED                  | 1        | 0.2%    |
| Konka                | 1        | 0.2%    |
| JRY                  | 1        | 0.2%    |
| HPN                  | 1        | 0.2%    |
| HKC                  | 1        | 0.2%    |
| Gigabyte Technology  | 1        | 0.2%    |
| GDH                  | 1        | 0.2%    |
| FUS                  | 1        | 0.2%    |
| eMachines            | 1        | 0.2%    |
| DENON                | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4        | 0.74%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 3        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch  | 3        | 0.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 3        | 0.55%   |
| Hitachi HDMI HEC0030 4096x2160 1150x650mm 52.0-inch                    | 3        | 0.55%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 3        | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.55%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 3        | 0.55%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                      | 3        | 0.55%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 3        | 0.55%   |
| Viotek VIOTEKNB32C VTK3200 1920x1080 698x393mm 31.5-inch               | 2        | 0.37%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 2        | 0.37%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2        | 0.37%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                   | 2        | 0.37%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch   | 2        | 0.37%   |
| Samsung Electronics S24F350 SAM0D21 1680x1050 520x290mm 23.4-inch      | 2        | 0.37%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 2        | 0.37%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                      | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.37%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 2        | 0.37%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 2        | 0.37%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 2        | 0.37%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 2        | 0.37%   |
| Hewlett-Packard VH240a HPN349A 1920x1080 527x296mm 23.8-inch           | 2        | 0.37%   |
| Hewlett-Packard 27fw HPN354A 1920x1080 598x336mm 27.0-inch             | 2        | 0.37%   |
| Goldstar L207W GSM4E7B 1680x1050 434x270mm 20.1-inch                   | 2        | 0.37%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 0.37%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                     | 2        | 0.37%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                     | 2        | 0.37%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 2        | 0.37%   |
| Dell P2415Q DELA0BE 2048x1280 530x300mm 24.0-inch                      | 2        | 0.37%   |
| Dell LCD Monitor P2419H 1920x1080                                      | 2        | 0.37%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                       | 2        | 0.37%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                     | 2        | 0.37%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                      | 2        | 0.37%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                      | 2        | 0.37%   |
| BenQ LCD Monitor GL2450H 1920x1080                                     | 2        | 0.37%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.37%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 2        | 0.37%   |
| AOC 27G1G4 AOC2701 1920x1080 600x340mm 27.2-inch                       | 2        | 0.37%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 0.37%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 2        | 0.37%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch  | 2        | 0.37%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch   | 2        | 0.37%   |
| Acer G226HQL ACR0346 1920x1080 477x268mm 21.5-inch                     | 2        | 0.37%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                      | 1        | 0.18%   |
| Vizio VW32L HDTV20A VIZ0027 1280x720 700x390mm 31.5-inch               | 1        | 0.18%   |
| ViewSonic VX3211 SERIES VSCF534 1920x1080 698x392mm 31.5-inch          | 1        | 0.18%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch          | 1        | 0.18%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 0.18%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch          | 1        | 0.18%   |
| ViewSonic VA2456 Series VSC3236 1920x1080 527x296mm 23.8-inch          | 1        | 0.18%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                 | 1        | 0.18%   |
| ViewSonic LCD Monitor VSCB51D 1280x1024 340x270mm 17.1-inch            | 1        | 0.18%   |
| Vestel LCD Monitor 22W_LCD_TV                                          | 1        | 0.18%   |
| Unknown LCD Monitor XMI Redmi Monitor 1920x1080                        | 1        | 0.18%   |
| Unknown LCD Monitor WAM OZDSP27IPS 2560x2520                           | 1        | 0.18%   |
| Unknown LCD Monitor TSL 24MT600BF 3840x1080                            | 1        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 236      | 46.83%  |
| 3840x2160 (4K)     | 42       | 8.33%   |
| 1280x1024 (SXGA)   | 34       | 6.75%   |
| 2560x1440 (QHD)    | 33       | 6.55%   |
| 1680x1050 (WSXGA+) | 26       | 5.16%   |
| Unknown            | 23       | 4.56%   |
| 1366x768 (WXGA)    | 16       | 3.17%   |
| 1440x900 (WXGA+)   | 12       | 2.38%   |
| 1920x1200 (WUXGA)  | 11       | 2.18%   |
| 1600x900 (HD+)     | 10       | 1.98%   |
| 2560x1080          | 9        | 1.79%   |
| 1360x768           | 8        | 1.59%   |
| 3440x1440          | 6        | 1.19%   |
| 3840x1080          | 5        | 0.99%   |
| 1600x1200          | 4        | 0.79%   |
| 1280x720 (HD)      | 4        | 0.79%   |
| 5760x2160          | 2        | 0.4%    |
| 5760x1080          | 2        | 0.4%    |
| 5120x1440          | 2        | 0.4%    |
| 4480x1440          | 2        | 0.4%    |
| 2048x1152          | 2        | 0.4%    |
| 1920x540           | 2        | 0.4%    |
| 6400x2160          | 1        | 0.2%    |
| 5760x1200          | 1        | 0.2%    |
| 4608x1440          | 1        | 0.2%    |
| 4240x1440          | 1        | 0.2%    |
| 3640x1920          | 1        | 0.2%    |
| 3600x1080          | 1        | 0.2%    |
| 3520x1080          | 1        | 0.2%    |
| 2880x1200          | 1        | 0.2%    |
| 2560x2520          | 1        | 0.2%    |
| 2560x1600          | 1        | 0.2%    |
| 2048x1536          | 1        | 0.2%    |
| 1826x1027          | 1        | 0.2%    |
| 1360x765           | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 16.87%  |
| 24      | 65       | 13.05%  |
| 27      | 59       | 11.85%  |
| 23      | 58       | 11.65%  |
| 21      | 55       | 11.04%  |
| 19      | 32       | 6.43%   |
| 31      | 29       | 5.82%   |
| 22      | 15       | 3.01%   |
| 18      | 15       | 3.01%   |
| 20      | 13       | 2.61%   |
| 84      | 12       | 2.41%   |
| 17      | 11       | 2.21%   |
| 34      | 9        | 1.81%   |
| 32      | 7        | 1.41%   |
| 15      | 6        | 1.2%    |
| 40      | 4        | 0.8%    |
| 48      | 3        | 0.6%    |
| 26      | 3        | 0.6%    |
| 72      | 2        | 0.4%    |
| 54      | 2        | 0.4%    |
| 52      | 2        | 0.4%    |
| 28      | 2        | 0.4%    |
| 86      | 1        | 0.2%    |
| 69      | 1        | 0.2%    |
| 65      | 1        | 0.2%    |
| 55      | 1        | 0.2%    |
| 50      | 1        | 0.2%    |
| 46      | 1        | 0.2%    |
| 43      | 1        | 0.2%    |
| 30      | 1        | 0.2%    |
| 25      | 1        | 0.2%    |
| 10      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 171      | 34.9%   |
| 401-500     | 109      | 22.24%  |
| Unknown     | 84       | 17.14%  |
| 601-700     | 38       | 7.76%   |
| 351-400     | 24       | 4.9%    |
| 1501-2000   | 16       | 3.27%   |
| 701-800     | 15       | 3.06%   |
| 301-350     | 15       | 3.06%   |
| 1001-1500   | 11       | 2.24%   |
| 801-900     | 5        | 1.02%   |
| 201-300     | 1        | 0.2%    |
| 901-1000    | 1        | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 292      | 62.13%  |
| Unknown | 76       | 16.17%  |
| 16/10   | 52       | 11.06%  |
| 5/4     | 30       | 6.38%   |
| 21/9    | 11       | 2.34%   |
| 4/3     | 5        | 1.06%   |
| 6/5     | 3        | 0.64%   |
| 3/2     | 1        | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 159      | 32.32%  |
| Unknown        | 84       | 17.07%  |
| 151-200        | 63       | 12.8%   |
| 301-350        | 61       | 12.4%   |
| 351-500        | 43       | 8.74%   |
| More than 1000 | 26       | 5.28%   |
| 251-300        | 21       | 4.27%   |
| 141-150        | 21       | 4.27%   |
| 501-1000       | 7        | 1.42%   |
| 101-110        | 5        | 1.02%   |
| 41-50          | 1        | 0.2%    |
| 111-120        | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 266      | 56.36%  |
| Unknown | 84       | 17.8%   |
| 101-120 | 79       | 16.74%  |
| 1-50    | 21       | 4.45%   |
| 121-160 | 13       | 2.75%   |
| 161-240 | 9        | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 377      | 76.47%  |
| 2     | 76       | 15.42%  |
| 0     | 35       | 7.1%    |
| 3     | 4        | 0.81%   |
| 4     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 302      | 43.7%   |
| Intel                           | 213      | 30.82%  |
| Qualcomm Atheros                | 50       | 7.24%   |
| TP-Link                         | 16       | 2.32%   |
| Ralink Technology               | 14       | 2.03%   |
| Broadcom                        | 12       | 1.74%   |
| Nvidia                          | 11       | 1.59%   |
| Ralink                          | 6        | 0.87%   |
| Marvell Technology Group        | 6        | 0.87%   |
| ASUSTek Computer                | 5        | 0.72%   |
| Samsung Electronics             | 4        | 0.58%   |
| Qualcomm Atheros Communications | 4        | 0.58%   |
| MediaTek                        | 4        | 0.58%   |
| D-Link System                   | 4        | 0.58%   |
| D-Link                          | 4        | 0.58%   |
| Broadcom Limited                | 3        | 0.43%   |
| Aquantia                        | 3        | 0.43%   |
| NetGear                         | 2        | 0.29%   |
| Motorola PCS                    | 2        | 0.29%   |
| Microsoft                       | 2        | 0.29%   |
| IMC Networks                    | 2        | 0.29%   |
| Edimax Technology               | 2        | 0.29%   |
| BUFFALO                         | 2        | 0.29%   |
| AVM                             | 2        | 0.29%   |
| ASIX Electronics                | 2        | 0.29%   |
| Xiaomi                          | 1        | 0.14%   |
| Uniden                          | 1        | 0.14%   |
| Solarflare Communications       | 1        | 0.14%   |
| Sitecom Europe                  | 1        | 0.14%   |
| Sigma Designs                   | 1        | 0.14%   |
| Seeed Technology                | 1        | 0.14%   |
| LG Electronics                  | 1        | 0.14%   |
| Huawei Technologies             | 1        | 0.14%   |
| Belkin Components               | 1        | 0.14%   |
| Belkin                          | 1        | 0.14%   |
| Arduino SA                      | 1        | 0.14%   |
| Apple                           | 1        | 0.14%   |
| American Megatrends             | 1        | 0.14%   |
| ADMtek                          | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 236      | 29.69%  |
| Intel Wi-Fi 6 AX200                                                    | 33       | 4.15%   |
| Intel I211 Gigabit Network Connection                                  | 30       | 3.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 25       | 3.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 21       | 2.64%   |
| Realtek 802.11ac NIC                                                   | 16       | 2.01%   |
| Intel Ethernet Controller I225-V                                       | 14       | 1.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11       | 1.38%   |
| Intel Ethernet Connection I217-LM                                      | 10       | 1.26%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9        | 1.13%   |
| Ralink MT7601U Wireless Adapter                                        | 9        | 1.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 8        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 8        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 0.75%   |
| Intel Wireless 8265 / 8275                                             | 6        | 0.75%   |
| Intel Ethernet Connection I217-V                                       | 6        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                   | 6        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 6        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 6        | 0.75%   |
| TP-Link 802.11ac NIC                                                   | 5        | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5        | 0.63%   |
| Nvidia MCP77 Ethernet                                                  | 5        | 0.63%   |
| Intel Wireless-AC 9260                                                 | 5        | 0.63%   |
| Intel Wireless 7260                                                    | 5        | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5        | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 0.63%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.63%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 4        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4        | 0.5%    |
| Intel Wireless 7265                                                    | 4        | 0.5%    |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.5%    |
| Intel 82567V-2 Gigabit Network Connection                              | 4        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.38%   |
| TP-Link Archer T4U ver.3                                               | 3        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3        | 0.38%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 3        | 0.38%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 3        | 0.38%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 0.38%   |
| MediaTek Titan                                                         | 3        | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.38%   |
| Intel Wireless 8260                                                    | 3        | 0.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3        | 0.38%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                                  | 3        | 0.38%   |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 0.38%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 0.25%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2        | 0.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.25%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 91       | 36.55%  |
| Realtek Semiconductor           | 54       | 21.69%  |
| Qualcomm Atheros                | 27       | 10.84%  |
| TP-Link                         | 16       | 6.43%   |
| Ralink Technology               | 14       | 5.62%   |
| Broadcom                        | 8        | 3.21%   |
| Ralink                          | 6        | 2.41%   |
| ASUSTek Computer                | 5        | 2.01%   |
| Qualcomm Atheros Communications | 4        | 1.61%   |
| D-Link                          | 4        | 1.61%   |
| D-Link System                   | 3        | 1.2%    |
| NetGear                         | 2        | 0.8%    |
| Microsoft                       | 2        | 0.8%    |
| IMC Networks                    | 2        | 0.8%    |
| Edimax Technology               | 2        | 0.8%    |
| BUFFALO                         | 2        | 0.8%    |
| AVM                             | 2        | 0.8%    |
| Sitecom Europe                  | 1        | 0.4%    |
| MediaTek                        | 1        | 0.4%    |
| Broadcom Limited                | 1        | 0.4%    |
| Belkin Components               | 1        | 0.4%    |
| Belkin                          | 1        | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 33       | 13.1%   |
| Realtek 802.11ac NIC                                                   | 16       | 6.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11       | 4.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                        | 9        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 2.38%   |
| Intel Wireless 8265 / 8275                                             | 6        | 2.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 6        | 2.38%   |
| TP-Link 802.11ac NIC                                                   | 5        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5        | 1.98%   |
| Intel Wireless-AC 9260                                                 | 5        | 1.98%   |
| Intel Wireless 7260                                                    | 5        | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 1.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 4        | 1.59%   |
| Intel Wireless 7265                                                    | 4        | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 1.19%   |
| TP-Link Archer T4U ver.3                                               | 3        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3        | 1.19%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 3        | 1.19%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 3        | 1.19%   |
| Intel Wireless 8260                                                    | 3        | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3        | 1.19%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2        | 0.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 2        | 0.79%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                 | 2        | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2        | 0.79%   |
| Ralink RT2800 802.11n PCI                                              | 2        | 0.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 2        | 0.79%   |
| Intel Wireless 3165                                                    | 2        | 0.79%   |
| Intel Centrino Wireless-N 2230                                         | 2        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2        | 0.79%   |
| D-Link Wireless N Nano USB Adapter                                     | 2        | 0.79%   |
| D-Link 802.11ac NIC                                                    | 2        | 0.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 1        | 0.4%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                                  | 1        | 0.4%    |
| TP-Link TL-WN722N v2                                                   | 1        | 0.4%    |
| Sitecom Europe WL-608 Wireless USB Adapter 54g                         | 1        | 0.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.4%    |
| Realtek RTL8192SU 802.11n WLAN Adapter                                 | 1        | 0.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.4%    |
| Ralink RT5372 Wireless Adapter                                         | 1        | 0.4%    |
| Ralink RT3072 Wireless Adapter                                         | 1        | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1        | 0.4%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 1        | 0.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 280      | 53.85%  |
| Intel                     | 171      | 32.88%  |
| Qualcomm Atheros          | 24       | 4.62%   |
| Nvidia                    | 11       | 2.12%   |
| Marvell Technology Group  | 6        | 1.15%   |
| Samsung Electronics       | 4        | 0.77%   |
| Broadcom                  | 4        | 0.77%   |
| MediaTek                  | 3        | 0.58%   |
| Aquantia                  | 3        | 0.58%   |
| Motorola PCS              | 2        | 0.38%   |
| Broadcom Limited          | 2        | 0.38%   |
| ASIX Electronics          | 2        | 0.38%   |
| Xiaomi                    | 1        | 0.19%   |
| Solarflare Communications | 1        | 0.19%   |
| LG Electronics            | 1        | 0.19%   |
| Huawei Technologies       | 1        | 0.19%   |
| D-Link System             | 1        | 0.19%   |
| Apple                     | 1        | 0.19%   |
| American Megatrends       | 1        | 0.19%   |
| ADMtek                    | 1        | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236      | 43.78%  |
| Intel I211 Gigabit Network Connection                             | 30       | 5.57%   |
| Intel Ethernet Connection (2) I219-V                              | 25       | 4.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24       | 4.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21       | 3.9%    |
| Intel Ethernet Controller I225-V                                  | 14       | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.86%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 1.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 1.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 1.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 6        | 1.11%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 0.93%   |
| Nvidia MCP77 Ethernet                                             | 5        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.74%   |
| Intel 82567V-2 Gigabit Network Connection                         | 4        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.56%   |
| MediaTek Titan                                                    | 3        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.56%   |
| Intel Ethernet Connection (12) I219-V                             | 3        | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 0.37%   |
| Motorola PCS moto e5                                              | 2        | 0.37%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.37%   |
| Intel 82573V Gigabit Ethernet Controller (Copper)                 | 2        | 0.37%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.37%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.19%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.19%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.19%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.19%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.19%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.19%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.19%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.19%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.19%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.19%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.19%   |
| LG G2 Android Phone [tethering mode]                              | 1        | 0.19%   |
| Intel Ethernet Controller 10G X550T                               | 1        | 0.19%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.19%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 475      | 66.25%  |
| WiFi     | 238      | 33.19%  |
| Modem    | 4        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 381      | 69.65%  |
| WiFi     | 166      | 30.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 295      | 60.45%  |
| 2     | 159      | 32.58%  |
| 3     | 22       | 4.51%   |
| 0     | 8        | 1.64%   |
| 5     | 2        | 0.41%   |
| 4     | 2        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 339      | 69.47%  |
| Yes  | 149      | 30.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 82       | 43.16%  |
| Cambridge Silicon Radio         | 45       | 23.68%  |
| Realtek Semiconductor           | 19       | 10%     |
| Broadcom                        | 11       | 5.79%   |
| ASUSTek Computer                | 10       | 5.26%   |
| Qualcomm Atheros Communications | 5        | 2.63%   |
| IMC Networks                    | 4        | 2.11%   |
| Apple                           | 3        | 1.58%   |
| Hewlett-Packard                 | 2        | 1.05%   |
| Dynex                           | 2        | 1.05%   |
| Belkin Components               | 2        | 1.05%   |
| Unknown                         | 1        | 0.53%   |
| Qcom                            | 1        | 0.53%   |
| Primax Electronics              | 1        | 0.53%   |
| Logitech                        | 1        | 0.53%   |
| Conwise Technology              | 1        | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 45       | 23.68%  |
| Intel Bluetooth Device                                | 34       | 17.89%  |
| Intel AX200 Bluetooth                                 | 29       | 15.26%  |
| Realtek Bluetooth Radio                               | 16       | 8.42%   |
| Intel Bluetooth wireless interface                    | 15       | 7.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 7        | 3.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 2.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 4        | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 1.58%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 1.58%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 1.05%   |
| IMC Networks Bluetooth Radio                          | 2        | 1.05%   |
| Dynex BCM20702A0                                      | 2        | 1.05%   |
| Broadcom BCM2045 Bluetooth                            | 2        | 1.05%   |
| ASUS Bluetooth Radio                                  | 2        | 1.05%   |
| ASUS ASUS USB-BT500                                   | 2        | 1.05%   |
| Apple Bluetooth USB Host Controller                   | 2        | 1.05%   |
| Unknown Bluetooth Device                              | 1        | 0.53%   |
| Qcom Bluetooth USB                                    | 1        | 0.53%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter         | 1        | 0.53%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.53%   |
| IMC Networks Bluetooth Device                         | 1        | 0.53%   |
| IMC Networks BCM20702A0                               | 1        | 0.53%   |
| HP Bluetooth Dongle                                   | 1        | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1        | 0.53%   |
| Conwise CW6622                                        | 1        | 0.53%   |
| Broadcom BCM2210 Bluetooth                            | 1        | 0.53%   |
| Broadcom BCM20702A0                                   | 1        | 0.53%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.53%   |
| Belkin Components F8T012 Bluetooth Adapter            | 1        | 0.53%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.53%   |
| ASUS Bluetooth Device                                 | 1        | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 295      | 37.63%  |
| AMD                                             | 204      | 26.02%  |
| Nvidia                                          | 193      | 24.62%  |
| C-Media Electronics                             | 15       | 1.91%   |
| Logitech                                        | 9        | 1.15%   |
| Creative Labs                                   | 9        | 1.15%   |
| Texas Instruments                               | 5        | 0.64%   |
| Kingston Technology                             | 4        | 0.51%   |
| JMTek                                           | 4        | 0.51%   |
| ASUSTek Computer                                | 3        | 0.38%   |
| Samson Technologies                             | 2        | 0.26%   |
| RODE Microphones                                | 2        | 0.26%   |
| Razer USA                                       | 2        | 0.26%   |
| Plantronics                                     | 2        | 0.26%   |
| Micro Star International                        | 2        | 0.26%   |
| GYROCOM C&C                                     | 2        | 0.26%   |
| GN Netcom                                       | 2        | 0.26%   |
| Focusrite-Novation                              | 2        | 0.26%   |
| Yamaha                                          | 1        | 0.13%   |
| VIA Technologies                                | 1        | 0.13%   |
| USB MICROPHONE                                  | 1        | 0.13%   |
| Unknown                                         | 1        | 0.13%   |
| SteelSeries ApS                                 | 1        | 0.13%   |
| Sennheiser Communications                       | 1        | 0.13%   |
| Realtek Semiconductor                           | 1        | 0.13%   |
| Pixart Imaging                                  | 1        | 0.13%   |
| Microsoft                                       | 1        | 0.13%   |
| MAG Technology                                  | 1        | 0.13%   |
| Mad Catz                                        | 1        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.13%   |
| IK Multimedia                                   | 1        | 0.13%   |
| iConnectivity                                   | 1        | 0.13%   |
| Holtek Semiconductor                            | 1        | 0.13%   |
| Generalplus Technology                          | 1        | 0.13%   |
| Fry's Electronics                               | 1        | 0.13%   |
| Elite Silicon                                   | 1        | 0.13%   |
| Earth Computer Technologies                     | 1        | 0.13%   |
| Dell                                            | 1        | 0.13%   |
| Creative Technology                             | 1        | 0.13%   |
| Cambridge Silicon Radio                         | 1        | 0.13%   |
| Blue Microphones                                | 1        | 0.13%   |
| BEHRINGER International                         | 1        | 0.13%   |
| Astro Gaming                                    | 1        | 0.13%   |
| Asahi Kasei Microsystems                        | 1        | 0.13%   |
| AlfaPlus Semiconductor                          | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 52       | 5.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 37       | 4.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 37       | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31       | 3.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30       | 3.27%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 27       | 2.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 26       | 2.84%   |
| Intel 200 Series PCH HD Audio                                              | 24       | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 2.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 23       | 2.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 2.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21       | 2.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 21       | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20       | 2.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20       | 2.18%   |
| Nvidia High Definition Audio Controller                                    | 19       | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 2.07%   |
| AMD FCH Azalia Controller                                                  | 17       | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16       | 1.74%   |
| Intel Audio device                                                         | 14       | 1.53%   |
| AMD Navi 10 HDMI Audio                                                     | 14       | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 1.42%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 1.09%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 10       | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10       | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 0.98%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9        | 0.98%   |
| Nvidia GP102 HDMI Audio Controller                                         | 8        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 8        | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8        | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 0.87%   |
| Nvidia GM206 High Definition Audio Controller                              | 7        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 7        | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 7        | 0.76%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 6        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6        | 0.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6        | 0.65%   |
| AMD Trinity HDMI Audio Controller                                          | 6        | 0.65%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 6        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.44%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.44%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 0.44%   |
| Nvidia GF106 High Definition Audio Controller                              | 4        | 0.44%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 4        | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                              | 3        | 0.33%   |
| Nvidia Audio device                                                        | 3        | 0.33%   |
| Kingston Technology HyperX 7.1 Audio                                       | 3        | 0.33%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.33%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 38       | 19.49%  |
| Corsair                      | 35       | 17.95%  |
| G.Skill                      | 30       | 15.38%  |
| Unknown                      | 23       | 11.79%  |
| Crucial                      | 15       | 7.69%   |
| Samsung Electronics          | 14       | 7.18%   |
| SK Hynix                     | 9        | 4.62%   |
| Micron Technology            | 5        | 2.56%   |
| Team                         | 4        | 2.05%   |
| A-DATA Technology            | 4        | 2.05%   |
| Patriot                      | 3        | 1.54%   |
| Wilk Elektronik              | 1        | 0.51%   |
| Vaseky                       | 1        | 0.51%   |
| Unknown (F785)               | 1        | 0.51%   |
| Unknown (ABCD)               | 1        | 0.51%   |
| Unknown (7F7F7F0B000000)     | 1        | 0.51%   |
| Unknown (0x0702)             | 1        | 0.51%   |
| Unifosa                      | 1        | 0.51%   |
| Ramaxel Technology           | 1        | 0.51%   |
| Patriot Memory (PDP Systems) | 1        | 0.51%   |
| Neo Forza                    | 1        | 0.51%   |
| Mushkin                      | 1        | 0.51%   |
| Exceleram                    | 1        | 0.51%   |
| Elpida                       | 1        | 0.51%   |
| Avant                        | 1        | 0.51%   |
| Apacer                       | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3466MT/s             | 6        | 2.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s             | 4        | 1.82%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                 | 3        | 1.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                    | 3        | 1.36%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s               | 3        | 1.36%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s               | 3        | 1.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                 | 2        | 0.91%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                 | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                            | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                            | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                                 | 2        | 0.91%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s                          | 2        | 0.91%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s            | 2        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                    | 2        | 0.91%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s               | 2        | 0.91%   |
| Kingston RAM 99U5471-056.A00LF 8192MB DIMM DDR3 1600MT/s             | 2        | 0.91%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s            | 2        | 0.91%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s                | 2        | 0.91%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s               | 2        | 0.91%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s               | 2        | 0.91%   |
| Wilk Elektronik RAM IRP3600D4V64L17/16G 16GB DIMM DDR4 3600MT/s      | 1        | 0.45%   |
| Vaseky RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2400MT/s                | 1        | 0.45%   |
| Unknown RAM V02D4L84GB5285282400 4096MB DIMM DDR4 2400MT/s           | 1        | 0.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                 | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM DDR 266MT/s                            | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                            | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                            | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                 | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                 | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                                    | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                             | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2                                     | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                             | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM                                          | 1        | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                             | 1        | 0.45%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s            | 1        | 0.45%   |
| Unknown RAM B8P94-0060-LOGIN. 2048MB DIMM DDR3 1333MT/s              | 1        | 0.45%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                | 1        | 0.45%   |
| Unknown (F785) RAM Module 16GB DIMM DDR4 2133MT/s                    | 1        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM LPDDR4 2400MT/s    | 1        | 0.45%   |
| Unknown (7F7F7F0B000000) RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 800MT/s | 1        | 0.45%   |
| Unknown (0x0702) RAM Module 8GB DIMM DDR3 1066MT/s                   | 1        | 0.45%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM 1333MT/s                      | 1        | 0.45%   |
| Team RAM Value-667 1GB DIMM DDR 400MT/s                              | 1        | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3200MT/s                | 1        | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3200MT/s               | 1        | 0.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                   | 1        | 0.45%   |
| SK Hynix RAM HYMP564U64P8-E3 512MB DIMM DDR 400MT/s                  | 1        | 0.45%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB DIMM DDR2 333MT/s                  | 1        | 0.45%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s              | 1        | 0.45%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s                 | 1        | 0.45%   |
| SK Hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s                 | 1        | 0.45%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 1        | 0.45%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s                 | 1        | 0.45%   |
| SK Hynix RAM AARVEX TECHNOLOGY 8GB DIMM DDR4 2400MT/s                | 1        | 0.45%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                            | 1        | 0.45%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                            | 1        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s                | 1        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s             | 1        | 0.45%   |
| Samsung RAM M393B5170FH0-CH9 4GB DIMM DDR3 1333MT/s                  | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 101      | 58.05%  |
| DDR3    | 51       | 29.31%  |
| Unknown | 8        | 4.6%    |
| DDR2    | 6        | 3.45%   |
| SDRAM   | 3        | 1.72%   |
| DDR     | 3        | 1.72%   |
| LPDDR4  | 2        | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 169      | 97.13%  |
| SODIMM | 5        | 2.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 75       | 39.27%  |
| 16384 | 38       | 19.9%   |
| 4096  | 34       | 17.8%   |
| 2048  | 23       | 12.04%  |
| 32768 | 16       | 8.38%   |
| 1024  | 3        | 1.57%   |
| 512   | 2        | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 37       | 19.27%  |
| 1600    | 27       | 14.06%  |
| 1333    | 26       | 13.54%  |
| 3600    | 19       | 9.9%    |
| 2400    | 10       | 5.21%   |
| 3000    | 8        | 4.17%   |
| 2133    | 8        | 4.17%   |
| 2667    | 7        | 3.65%   |
| 3466    | 6        | 3.13%   |
| 800     | 6        | 3.13%   |
| 2666    | 5        | 2.6%    |
| 2933    | 4        | 2.08%   |
| 3733    | 3        | 1.56%   |
| 1066    | 3        | 1.56%   |
| 667     | 3        | 1.56%   |
| Unknown | 3        | 1.56%   |
| 3334    | 2        | 1.04%   |
| 333     | 2        | 1.04%   |
| 3800    | 1        | 0.52%   |
| 3533    | 1        | 0.52%   |
| 3500    | 1        | 0.52%   |
| 3100    | 1        | 0.52%   |
| 3066    | 1        | 0.52%   |
| 2934    | 1        | 0.52%   |
| 1867    | 1        | 0.52%   |
| 1866    | 1        | 0.52%   |
| 1800    | 1        | 0.52%   |
| 1400    | 1        | 0.52%   |
| 1334    | 1        | 0.52%   |
| 400     | 1        | 0.52%   |
| 266     | 1        | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 14       | 32.56%  |
| Canon                              | 8        | 18.6%   |
| Brother Industries                 | 6        | 13.95%  |
| Seiko Epson                        | 3        | 6.98%   |
| Samsung Electronics                | 3        | 6.98%   |
| Kyocera                            | 2        | 4.65%   |
| Dymo-CoStar                        | 2        | 4.65%   |
| Zhuhai Poskey Technology           | 1        | 2.33%   |
| Zebra                              | 1        | 2.33%   |
| Xerox                              | 1        | 2.33%   |
| Lexmark International              | 1        | 2.33%   |
| BeiJing LanXum Computer Technology | 1        | 2.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon PIXMA MG3600 Series                               | 2        | 4.65%   |
| Brother HL-5250DN Printer                               | 2        | 4.65%   |
| Zhuhai Poskey Printer                                   | 1        | 2.33%   |
| Zebra LP2844 Printer                                    | 1        | 2.33%   |
| Xerox WorkCentre 3119 Series                            | 1        | 2.33%   |
| Seiko Epson WF-2510 Series                              | 1        | 2.33%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F  | 1        | 2.33%   |
| Seiko Epson L395 Series                                 | 1        | 2.33%   |
| Samsung SCX-3400 Series                                 | 1        | 2.33%   |
| Samsung ML-1450                                         | 1        | 2.33%   |
| Samsung Composite Device                                | 1        | 2.33%   |
| Lexmark International Lexmark MC2425adw                 | 1        | 2.33%   |
| Kyocera FS-3920DN                                       | 1        | 2.33%   |
| Kyocera FS-1370DN                                       | 1        | 2.33%   |
| HP Officejet 4500 G510g-m                               | 1        | 2.33%   |
| HP LaserJet Professional P1102w                         | 1        | 2.33%   |
| HP LaserJet P1005                                       | 1        | 2.33%   |
| HP LaserJet M14-M17                                     | 1        | 2.33%   |
| HP LaserJet 3050                                        | 1        | 2.33%   |
| HP LaserJet 1020                                        | 1        | 2.33%   |
| HP LaserJet 1010                                        | 1        | 2.33%   |
| HP ENVY Photo 6200 series                               | 1        | 2.33%   |
| HP ENVY 5000 series                                     | 1        | 2.33%   |
| HP DeskJet Plus 4100 series                             | 1        | 2.33%   |
| HP Deskjet F4500 series                                 | 1        | 2.33%   |
| HP DeskJet 970c/970cse                                  | 1        | 2.33%   |
| HP DeskJet 3700 series                                  | 1        | 2.33%   |
| HP Deskjet 3050 J610 series                             | 1        | 2.33%   |
| Dymo-CoStar LabelWriter 400                             | 1        | 2.33%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                  | 1        | 2.33%   |
| Canon TS8000 series                                     | 1        | 2.33%   |
| Canon TR4500 series                                     | 1        | 2.33%   |
| Canon PRO-100 series                                    | 1        | 2.33%   |
| Canon PIXMA iP5300 Printer                              | 1        | 2.33%   |
| Canon LBP6030/6030B/6018L                               | 1        | 2.33%   |
| Canon iP8700 series                                     | 1        | 2.33%   |
| Brother QL-550 printer                                  | 1        | 2.33%   |
| Brother Printer                                         | 1        | 2.33%   |
| Brother MFC-J480DW                                      | 1        | 2.33%   |
| Brother DCP-L2540DW                                     | 1        | 2.33%   |
| BeiJing LanXum Technology Black and White Laser Printer | 1        | 2.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 83.33%  |
| Mustek Systems | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems BearPaw 2448 CU Pro | 1        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 16.67%  |
| Canon CanoScan N1240U/LiDE 30      | 1        | 16.67%  |
| Canon CanoScan LiDE 700F           | 1        | 16.67%  |
| Canon CanoScan LiDE 210            | 1        | 16.67%  |
| Canon CanoScan LiDE 120            | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 34       | 31.78%  |
| Microdia                      | 14       | 13.08%  |
| Microsoft                     | 7        | 6.54%   |
| Sunplus Innovation Technology | 5        | 4.67%   |
| Realtek Semiconductor         | 5        | 4.67%   |
| Generalplus Technology        | 4        | 3.74%   |
| SHENZHEN Fullhan              | 3        | 2.8%    |
| Samsung Electronics           | 3        | 2.8%    |
| GEMBIRD                       | 3        | 2.8%    |
| Cubeternet                    | 3        | 2.8%    |
| Z-Star Microelectronics       | 2        | 1.87%   |
| IMC Networks                  | 2        | 1.87%   |
| Creative Technology           | 2        | 1.87%   |
| Chicony Electronics           | 2        | 1.87%   |
| AVerMedia Technologies        | 2        | 1.87%   |
| ARC International             | 2        | 1.87%   |
| Xiongmai                      | 1        | 0.93%   |
| Trust                         | 1        | 0.93%   |
| Syntek                        | 1        | 0.93%   |
| PrehKeyTec                    | 1        | 0.93%   |
| Polycom                       | 1        | 0.93%   |
| Philips (or NXP)              | 1        | 0.93%   |
| Magic Control Technology      | 1        | 0.93%   |
| MACROSILICON                  | 1        | 0.93%   |
| Jieli Technology              | 1        | 0.93%   |
| IPEVO                         | 1        | 0.93%   |
| Huawei Technologies           | 1        | 0.93%   |
| Guillemot                     | 1        | 0.93%   |
| Etron Technology              | 1        | 0.93%   |
| Apple                         | 1        | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 10       | 9.35%   |
| Microdia USB 2.0 Camera                           | 7        | 6.54%   |
| Microdia Camera                                   | 4        | 3.74%   |
| SHENZHEN Fullhan webcam                           | 3        | 2.8%    |
| Samsung Galaxy series, misc. (MTP mode)           | 3        | 2.8%    |
| Logitech Webcam C310                              | 3        | 2.8%    |
| Logitech C922 Pro Stream Webcam                   | 3        | 2.8%    |
| Logitech BRIO                                     | 3        | 2.8%    |
| Generalplus GENERAL WEBCAM                        | 3        | 2.8%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 2.8%    |
| Sunplus Integrated_Webcam_HD                      | 2        | 1.87%   |
| Realtek NexiGo N960E FHD Webcam                   | 2        | 1.87%   |
| Realtek FULL HD 1080P Webcam                      | 2        | 1.87%   |
| Logitech Webcam Pro 9000                          | 2        | 1.87%   |
| Logitech HD Webcam C910                           | 2        | 1.87%   |
| Logitech HD Webcam C525                           | 2        | 1.87%   |
| Logitech HD Pro Webcam C920                       | 2        | 1.87%   |
| Cubeternet USB2.0 Camera                          | 2        | 1.87%   |
| AVerMedia Live Streamer CAM 313                   | 2        | 1.87%   |
| ARC International Camera                          | 2        | 1.87%   |
| Z-Star Vimicro USB2.0 UVC PC Camera               | 1        | 0.93%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 1        | 0.93%   |
| Xiongmai web camera                               | 1        | 0.93%   |
| Trust 17676 Webcam                                | 1        | 0.93%   |
| Syntek USB Video Device                           | 1        | 0.93%   |
| Sunplus NexiGo N930E FHD Webcam                   | 1        | 0.93%   |
| Sunplus FanNicao S20                              | 1        | 0.93%   |
| Sunplus Aukey-PC-LM1E Camera                      | 1        | 0.93%   |
| Realtek Web Camera                                | 1        | 0.93%   |
| PrehKeyTec MikrOkularFullHD                       | 1        | 0.93%   |
| Polycom Poly Studio P15                           | 1        | 0.93%   |
| Philips (or NXP) SPC 520/525NC PC Camera          | 1        | 0.93%   |
| Microsoft Microsoft?� LifeCam HD-5001             | 1        | 0.93%   |
| Microsoft LifeCam VX-800                          | 1        | 0.93%   |
| Microsoft LifeCam VX-7000 (UVC-compliant)         | 1        | 0.93%   |
| Microsoft LifeCam VX-5000                         | 1        | 0.93%   |
| Microsoft LifeCam Studio                          | 1        | 0.93%   |
| Microsoft LifeCam HD-3000                         | 1        | 0.93%   |
| Microsoft LifeCam Cinema                          | 1        | 0.93%   |
| Microdia USB Live camera                          | 1        | 0.93%   |
| Microdia Defender G-Lens 2577 HD720p Camera       | 1        | 0.93%   |
| Microdia ACR010 USB Webcam                        | 1        | 0.93%   |
| Magic Control j5 WebCam JVCU100                   | 1        | 0.93%   |
| MACROSILICON ShadowCast                           | 1        | 0.93%   |
| Logitech Webcam C250                              | 1        | 0.93%   |
| Logitech Webcam C210                              | 1        | 0.93%   |
| Logitech Webcam C170                              | 1        | 0.93%   |
| Logitech Webcam C110                              | 1        | 0.93%   |
| Logitech Camera                                   | 1        | 0.93%   |
| Logitech C930c                                    | 1        | 0.93%   |
| Logitech B525 HD Webcam                           | 1        | 0.93%   |
| Jieli USB PHY 2.0                                 | 1        | 0.93%   |
| IPEVO V4K                                         | 1        | 0.93%   |
| IMC Networks XHC Camera                           | 1        | 0.93%   |
| IMC Networks USB 2.0 Camera                       | 1        | 0.93%   |
| Huawei HiCamera                                   | 1        | 0.93%   |
| Guillemot Hercules HD Sunset                      | 1        | 0.93%   |
| Generalplus 808 Camera                            | 1        | 0.93%   |
| Etron SPEEDLINK SNAPPY Smart Webcam               | 1        | 0.93%   |
| Cubeternet WebCam                                 | 1        | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 75%     |
| Dell                  | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 75%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 419      | 85.34%  |
| 1     | 62       | 12.63%  |
| 2     | 9        | 1.83%   |
| 3     | 1        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 32.5%   |
| Net/wireless             | 25       | 31.25%  |
| Unassigned class         | 9        | 11.25%  |
| Sound                    | 4        | 5%      |
| Fingerprint reader       | 3        | 3.75%   |
| Camera                   | 3        | 3.75%   |
| Multimedia controller    | 2        | 2.5%    |
| Communication controller | 2        | 2.5%    |
| Card reader              | 2        | 2.5%    |
| Storage/raid             | 1        | 1.25%   |
| Dvb card                 | 1        | 1.25%   |
| Chipcard                 | 1        | 1.25%   |
| Bluetooth                | 1        | 1.25%   |

