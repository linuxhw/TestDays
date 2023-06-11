Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 5424

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Unknown       | Unknown                     | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Unknown       | Unknown                     | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [365eeba4c9](https://linux-hardware.org/?probe=365eeba4c9) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| ASRock        | H310CM-HDV                  | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| MSI           | Z390-A PRO                  | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Intel         | X99                         | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Gigabyte      | Z690 AERO G                 | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| AZW           | MINI S                      | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| ASUSTek       | H81M-C                      | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| MSI           | H110M PRO-VD                | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| ASUSTek       | E35M1-M                     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | M61PME-S2                   | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | F2A85-M                     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| HP            | 2B38                        | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| ASRock        | H470M-HVS                   | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| MSI           | 760GM-P23                   | [05c4685974](https://linux-hardware.org/?probe=05c4685974) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| HP            | 8076                        | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| ASUSTek       | P5B-VM SE                   | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Dell          | 0782GW A00                  | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Gigabyte      | H61M-DS2                    | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| ASRock        | H470M-HVS                   | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| HP            | 339A                        | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| HP            | 1632                        | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| HP            | 1998                        | [42824285c0](https://linux-hardware.org/?probe=42824285c0) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASRock        | H470M-HVS                   | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ECS           | G31T-M9                     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| ASRock        | H470M-HVS                   | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| Dell          | 0C1R19 A01                  | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Unknown       | Unknown                     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Unknown       | Unknown                     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| ASUSTek       | P8B75-V                     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [2ab6f2745c](https://linux-hardware.org/?probe=2ab6f2745c) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [55f8d9f172](https://linux-hardware.org/?probe=55f8d9f172) | Apr 14, 2023 |
| Unknown       | Unknown                     | [6925c48705](https://linux-hardware.org/?probe=6925c48705) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [158dacc1ce](https://linux-hardware.org/?probe=158dacc1ce) | Apr 13, 2023 |
| Unknown       | Unknown                     | [52aeca6f98](https://linux-hardware.org/?probe=52aeca6f98) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| Dell          | 03V7GF A02                  | [cb72d83566](https://linux-hardware.org/?probe=cb72d83566) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| Lenovo        | 32E6 NOK                    | [c1d51dba1d](https://linux-hardware.org/?probe=c1d51dba1d) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| MSI           | MAG B460 TORPEDO            | [62a628da55](https://linux-hardware.org/?probe=62a628da55) | Apr 04, 2023 |
| Unknown       | Q-790                       | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| ASUSTek       | P8Z77-M                     | [ec9901fcd5](https://linux-hardware.org/?probe=ec9901fcd5) | Apr 04, 2023 |
| Pegatron      | Benicia                     | [96ba9b6040](https://linux-hardware.org/?probe=96ba9b6040) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cdd67e12ca](https://linux-hardware.org/?probe=cdd67e12ca) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Unknown       | Unknown                     | [077bed9951](https://linux-hardware.org/?probe=077bed9951) | Apr 02, 2023 |
| Google        | Panther                     | [73f3ed3c65](https://linux-hardware.org/?probe=73f3ed3c65) | Apr 02, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2a597d7a33](https://linux-hardware.org/?probe=2a597d7a33) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [32c0716bfa](https://linux-hardware.org/?probe=32c0716bfa) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| HP            | 1495                        | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Gigabyte      | H97M-HD3                    | [ab4dce8483](https://linux-hardware.org/?probe=ab4dce8483) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Intel         | STK2M3W64CC H89289-506      | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| ASUSTek       | PRIME Z370-P                | [82e7940a77](https://linux-hardware.org/?probe=82e7940a77) | Mar 15, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| HP            | 8076 MVB,A                  | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Gigabyte      | H55M-S2H                    | [545e7119e9](https://linux-hardware.org/?probe=545e7119e9) | Mar 04, 2023 |
| HP            | 82B4                        | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| AZW           | MINI S                      | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| HP            | 8433 11                     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| Medion        | TJ4125                      | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Unknown       | Unknown                     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| HP            | 3397                        | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| ASRock        | 970M Pro3                   | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| Medion        | TJ4125                      | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| Unknown       | Unknown                     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Intel         | JSL MRD                     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Unknown       | Unknown                     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Unknown       | Unknown                     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | F2A85-M PRO                 | [c5b8952fdb](https://linux-hardware.org/?probe=c5b8952fdb) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| Unknown       | Unknown                     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| HP            | 3648h                       | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Gigabyte      | H81M-S2V                    | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| HP            | 3397                        | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| AZW           | U59                         | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Unknown       | Unknown                     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| HP            | 1589                        | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| AZW           | MINI S                      | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Dell          | 05WNJ2 A02                  | [4619f572c5](https://linux-hardware.org/?probe=4619f572c5) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Intel         | SKYBAY                      | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| ASUSTek       | PRIME B250-A                | [c686d3d123](https://linux-hardware.org/?probe=c686d3d123) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [eb551b5ec0](https://linux-hardware.org/?probe=eb551b5ec0) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| HP            | 1998                        | [81da484cc4](https://linux-hardware.org/?probe=81da484cc4) | Jan 28, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [0093f9df93](https://linux-hardware.org/?probe=0093f9df93) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| HP            | 82B4                        | [29e2d03c1a](https://linux-hardware.org/?probe=29e2d03c1a) | Jan 24, 2023 |
| HP            | 82B4                        | [3df98736a1](https://linux-hardware.org/?probe=3df98736a1) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Medion        | TJ4125                      | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| ASRock        | A300M-STX                   | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 2372     | 60.79%  |
| Debian 10               | 746      | 19.12%  |
| Debian Testing          | 231      | 5.92%   |
| Debian 12               | 180      | 4.61%   |
| Debian 9                | 146      | 3.74%   |
| Debian Unstable         | 116      | 2.97%   |
| Debian                  | 61       | 1.56%   |
| Debian 8                | 25       | 0.64%   |
| Debian 11-updates       | 16       | 0.41%   |
| Debian 7                | 5        | 0.13%   |
| Debian Testing/unstable | 2        | 0.05%   |
| Debian Sid              | 1        | 0.03%   |
| Debian 6                | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 3750     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-7-amd64        | 513      | 12.04%  |
| 5.10.0-8-amd64        | 240      | 5.63%   |
| 5.10.0-21-amd64       | 180      | 4.22%   |
| 5.10.0-9-amd64        | 123      | 2.89%   |
| 5.10.0-2-amd64        | 118      | 2.77%   |
| 5.10.0-19-amd64       | 101      | 2.37%   |
| 5.10.0-20-amd64       | 99       | 2.32%   |
| 5.10.0-13-amd64       | 86       | 2.02%   |
| 5.10.0-18-amd64       | 82       | 1.92%   |
| 6.1.0-4-amd64         | 78       | 1.83%   |
| 5.10.0-11-amd64       | 73       | 1.71%   |
| 5.10.0-10-amd64       | 72       | 1.69%   |
| 5.10.0-16-amd64       | 68       | 1.6%    |
| 4.19.0-6-amd64        | 56       | 1.31%   |
| 4.19.0-16-amd64       | 52       | 1.22%   |
| 4.19.0-14-amd64       | 52       | 1.22%   |
| 5.10.0-23-amd64       | 51       | 1.2%    |
| 5.10.0-14-amd64       | 50       | 1.17%   |
| 4.19.0-13-amd64       | 50       | 1.17%   |
| 4.19.0-9-amd64        | 48       | 1.13%   |
| 4.19.0-17-amd64       | 48       | 1.13%   |
| 4.19.0-8-amd64        | 47       | 1.1%    |
| 5.10.0-17-amd64       | 43       | 1.01%   |
| 5.10.0-15-amd64       | 42       | 0.99%   |
| 4.19.0-12-amd64       | 38       | 0.89%   |
| 5.15.0-2-amd64        | 37       | 0.87%   |
| 5.10.0-22-amd64       | 36       | 0.84%   |
| 4.19.0-10-amd64       | 34       | 0.8%    |
| 4.9.0-8-amd64         | 31       | 0.73%   |
| 6.1.0-7-amd64         | 30       | 0.7%    |
| 5.10.0-12-amd64       | 29       | 0.68%   |
| 5.6.0-2-amd64         | 28       | 0.66%   |
| 5.18.0-2-amd64        | 20       | 0.47%   |
| 6.0.0-6-amd64         | 19       | 0.45%   |
| 6.0.0-0.deb11.6-amd64 | 19       | 0.45%   |
| 5.7.0-1-amd64         | 19       | 0.45%   |
| 5.10.0-6-amd64        | 19       | 0.45%   |
| 4.9.0-9-amd64         | 19       | 0.45%   |
| 4.19.0-5-amd64        | 19       | 0.45%   |
| 5.4.0-4-amd64         | 18       | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2045     | 50.37%  |
| 4.19.0   | 516      | 12.71%  |
| 6.1.0    | 194      | 4.78%   |
| 4.9.0    | 109      | 2.68%   |
| 6.0.0    | 91       | 2.24%   |
| 5.18.0   | 79       | 1.95%   |
| 5.9.0    | 59       | 1.45%   |
| 5.15.0   | 57       | 1.4%    |
| 5.16.0   | 56       | 1.38%   |
| 5.8.0    | 55       | 1.35%   |
| 5.7.0    | 54       | 1.33%   |
| 5.6.0    | 48       | 1.18%   |
| 5.4.0    | 45       | 1.11%   |
| 5.13.19  | 44       | 1.08%   |
| 5.19.0   | 40       | 0.99%   |
| 5.14.0   | 33       | 0.81%   |
| 5.17.0   | 25       | 0.62%   |
| 5.11.22  | 19       | 0.47%   |
| 5.3.0    | 18       | 0.44%   |
| 5.15.102 | 15       | 0.37%   |
| 5.5.0    | 14       | 0.34%   |
| 5.15.83  | 14       | 0.34%   |
| 5.15.74  | 14       | 0.34%   |
| 5.15.39  | 13       | 0.32%   |
| 5.15.35  | 13       | 0.32%   |
| 5.15.107 | 13       | 0.32%   |
| 5.15.85  | 12       | 0.3%    |
| 5.15.30  | 11       | 0.27%   |
| 5.15.53  | 10       | 0.25%   |
| 3.16.0   | 10       | 0.25%   |
| 5.4.106  | 9        | 0.22%   |
| 4.18.0   | 9        | 0.22%   |
| 5.2.0    | 8        | 0.2%    |
| 5.15.104 | 8        | 0.2%    |
| 5.4.44   | 7        | 0.17%   |
| 4.15.18  | 7        | 0.17%   |
| 4.1.42   | 7        | 0.17%   |
| 5.4.65   | 6        | 0.15%   |
| 6.2.11   | 5        | 0.12%   |
| 4.17.0   | 5        | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10     | 2073     | 51.4%   |
| 4.19     | 527      | 13.07%  |
| 6.1      | 205      | 5.08%   |
| 5.15     | 187      | 4.64%   |
| 4.9      | 115      | 2.85%   |
| 6.0      | 101      | 2.5%    |
| 5.4      | 98       | 2.43%   |
| 5.18     | 84       | 2.08%   |
| 5.9      | 62       | 1.54%   |
| 5.8      | 61       | 1.51%   |
| 5.16     | 61       | 1.51%   |
| 5.7      | 58       | 1.44%   |
| 5.13     | 54       | 1.34%   |
| 5.6      | 52       | 1.29%   |
| 5.19     | 48       | 1.19%   |
| 5.14     | 36       | 0.89%   |
| 5.11     | 31       | 0.77%   |
| 5.3      | 30       | 0.74%   |
| 5.17     | 29       | 0.72%   |
| 5.5      | 17       | 0.42%   |
| 6.2      | 16       | 0.4%    |
| 4.15     | 11       | 0.27%   |
| 4.18     | 10       | 0.25%   |
| 3.16     | 10       | 0.25%   |
| 5.2      | 8        | 0.2%    |
| 5.0      | 8        | 0.2%    |
| 4.1      | 7        | 0.17%   |
| 4.17     | 5        | 0.12%   |
| 6.3      | 4        | 0.1%    |
| 5.12     | 3        | 0.07%   |
| 5.1      | 3        | 0.07%   |
| 4.16     | 3        | 0.07%   |
| 4.20     | 2        | 0.05%   |
| 4.14     | 2        | 0.05%   |
| 4.13     | 2        | 0.05%   |
| 2.6      | 2        | 0.05%   |
| 5.10.164 | 1        | 0.02%   |
| 4.6      | 1        | 0.02%   |
| 4.5      | 1        | 0.02%   |
| 4.4      | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3630     | 96.77%  |
| i686    | 92       | 2.45%   |
| ppc64   | 7        | 0.19%   |
| riscv64 | 6        | 0.16%   |
| armv7l  | 5        | 0.13%   |
| ppc64le | 2        | 0.05%   |
| mips64  | 2        | 0.05%   |
| i586    | 2        | 0.05%   |
| aarch64 | 2        | 0.05%   |
| sparc64 | 1        | 0.03%   |
| sh4a    | 1        | 0.03%   |
| armv6l  | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1410     | 36.74%  |
| GNOME             | 705      | 18.37%  |
| XFCE              | 459      | 11.96%  |
| KDE5              | 439      | 11.44%  |
| MATE              | 176      | 4.59%   |
| X-Cinnamon        | 139      | 3.62%   |
| Cinnamon          | 107      | 2.79%   |
| LXDE              | 94       | 2.45%   |
| KDE               | 78       | 2.03%   |
| LXQt              | 61       | 1.59%   |
| i3                | 34       | 0.89%   |
| Openbox           | 33       | 0.86%   |
| GNOME Flashback   | 20       | 0.52%   |
| lightdm-xsession  | 18       | 0.47%   |
| trinity           | 14       | 0.36%   |
| GNOME Classic     | 12       | 0.31%   |
| Budgie            | 12       | 0.31%   |
| awesome           | 5        | 0.13%   |
| KDE4              | 4        | 0.1%    |
| fluxbox           | 4        | 0.1%    |
| sway              | 3        | 0.08%   |
| Enlightenment     | 2        | 0.05%   |
| xmonad            | 1        | 0.03%   |
| UKUI              | 1        | 0.03%   |
| i3-with-shmlog    | 1        | 0.03%   |
| GNUstep           | 1        | 0.03%   |
| gnome-xorg        | 1        | 0.03%   |
| e16-session       | 1        | 0.03%   |
| DWM               | 1        | 0.03%   |
| default           | 1        | 0.03%   |
| /etc/X11/Xsession | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 2023     | 53.01%  |
| Unknown     | 841      | 22.04%  |
| Tty         | 585      | 15.33%  |
| Wayland     | 364      | 9.54%   |
| Web         | 2        | 0.05%   |
| Unspecified | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1948     | 50.91%  |
| LightDM | 574      | 15%     |
| GDM     | 473      | 12.36%  |
| SDDM    | 416      | 10.87%  |
| TDM     | 250      | 6.53%   |
| GDM3    | 112      | 2.93%   |
| SLiM    | 17       | 0.44%   |
| XDM     | 16       | 0.42%   |
| NODM    | 9        | 0.24%   |
| KDM     | 5        | 0.13%   |
| Ly      | 2        | 0.05%   |
| LXDM    | 2        | 0.05%   |
| WDM     | 1        | 0.03%   |
| SU      | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1275     | 33.55%  |
| ru_RU   | 795      | 20.92%  |
| Unknown | 281      | 7.39%   |
| de_DE   | 223      | 5.87%   |
| fr_FR   | 186      | 4.89%   |
| en_GB   | 170      | 4.47%   |
| pt_BR   | 114      | 3%      |
| es_ES   | 110      | 2.89%   |
| it_IT   | 76       | 2%      |
| en_CA   | 58       | 1.53%   |
| C       | 57       | 1.5%    |
| en_AU   | 55       | 1.45%   |
| pl_PL   | 36       | 0.95%   |
| en_IN   | 20       | 0.53%   |
| es_AR   | 18       | 0.47%   |
| en_IE   | 18       | 0.47%   |
| zh_CN   | 17       | 0.45%   |
| ja_JP   | 17       | 0.45%   |
| hu_HU   | 17       | 0.45%   |
| de_AT   | 16       | 0.42%   |
| es_VE   | 15       | 0.39%   |
| es_MX   | 13       | 0.34%   |
| nl_BE   | 12       | 0.32%   |
| pt_PT   | 11       | 0.29%   |
| nl_NL   | 10       | 0.26%   |
| cs_CZ   | 10       | 0.26%   |
| en_NZ   | 9        | 0.24%   |
| de_CH   | 9        | 0.24%   |
| sv_SE   | 7        | 0.18%   |
| es_CL   | 7        | 0.18%   |
| en_ZA   | 7        | 0.18%   |
| ru_UA   | 6        | 0.16%   |
| en_DK   | 6        | 0.16%   |
| uk_UA   | 5        | 0.13%   |
| fr_BE   | 5        | 0.13%   |
| en_HK   | 5        | 0.13%   |
| el_GR   | 5        | 0.13%   |
| ca_ES   | 5        | 0.13%   |
| ro_RO   | 4        | 0.11%   |
| hr_HR   | 4        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2385     | 62.65%  |
| EFI  | 1422     | 37.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 2610     | 68.85%  |
| Overlay    | 737      | 19.44%  |
| Btrfs      | 146      | 3.85%   |
| Zfs        | 93       | 2.45%   |
| Unknown    | 81       | 2.14%   |
| Xfs        | 64       | 1.69%   |
| Ext3       | 23       | 0.61%   |
| Ext2       | 10       | 0.26%   |
| Tmpfs      | 8        | 0.21%   |
| Rootfs     | 8        | 0.21%   |
| Aufs       | 4        | 0.11%   |
| XXXXXXX    | 2        | 0.05%   |
| Jfs        | 2        | 0.05%   |
| F2fs       | 2        | 0.05%   |
| Fuse.sshfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1795     | 46.87%  |
| MBR     | 1300     | 33.94%  |
| Unknown | 735      | 19.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3062     | 80.58%  |
| Yes       | 738      | 19.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2337     | 61.58%  |
| Yes       | 1458     | 38.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1035     | 27.6%   |
| Gigabyte Technology                  | 627      | 16.72%  |
| MSI                                  | 390      | 10.4%   |
| ASRock                               | 382      | 10.19%  |
| Dell                                 | 245      | 6.53%   |
| Hewlett-Packard                      | 231      | 6.16%   |
| Intel                                | 119      | 3.17%   |
| Lenovo                               | 110      | 2.93%   |
| Unknown                              | 80       | 2.13%   |
| ECS                                  | 55       | 1.47%   |
| Fujitsu                              | 39       | 1.04%   |
| Foxconn                              | 38       | 1.01%   |
| AZW                                  | 33       | 0.88%   |
| Supermicro                           | 31       | 0.83%   |
| Acer                                 | 30       | 0.8%    |
| ASRockRack                           | 28       | 0.75%   |
| Pegatron                             | 22       | 0.59%   |
| Biostar                              | 21       | 0.56%   |
| Huanan                               | 13       | 0.35%   |
| Inventec                             | 12       | 0.32%   |
| Shuttle                              | 11       | 0.29%   |
| Fujitsu Siemens                      | 11       | 0.29%   |
| Positivo                             | 10       | 0.27%   |
| Apple                                | 10       | 0.27%   |
| Medion                               | 9        | 0.24%   |
| BESSTAR Tech                         | 9        | 0.24%   |
| Google                               | 8        | 0.21%   |
| Hardkernel                           | 5        | 0.13%   |
| Techvision                           | 4        | 0.11%   |
| Packard Bell                         | 4        | 0.11%   |
| IceWhale Technology                  | 4        | 0.11%   |
| Gateway                              | 4        | 0.11%   |
| AMI                                  | 4        | 0.11%   |
| Alienware                            | 4        | 0.11%   |
| Wistron                              | 3        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.08%   |
| PCWare                               | 3        | 0.08%   |
| PC Engines                           | 3        | 0.08%   |
| Itautec                              | 3        | 0.08%   |
| HPE                                  | 3        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 124      | 3.31%   |
| Unknown                      | 85       | 2.27%   |
| ASUS S20 K29                 | 55       | 1.47%   |
| MSI MS-7996                  | 40       | 1.07%   |
| MSI MS-7817                  | 25       | 0.67%   |
| Gigabyte H81M-S2V            | 24       | 0.64%   |
| ECS G31T-M9                  | 24       | 0.64%   |
| ASRock H470M-HVS             | 20       | 0.53%   |
| Dell OptiPlex 7010           | 19       | 0.51%   |
| ASUS PRIME H510M-A           | 19       | 0.51%   |
| Gigabyte B450M DS3H          | 17       | 0.45%   |
| Gigabyte H410M S2H           | 16       | 0.43%   |
| ECS H61H2-M13                | 16       | 0.43%   |
| ASUS TUF Gaming X570-PLUS    | 15       | 0.4%    |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.4%    |
| ASUS PRIME A320M-K           | 14       | 0.37%   |
| ASRock B450M Pro4            | 14       | 0.37%   |
| ASUS PRIME B450M-A           | 13       | 0.35%   |
| MSI MS-7C56                  | 12       | 0.32%   |
| ASUS PRIME B450M-K           | 12       | 0.32%   |
| MSI MS-7C02                  | 11       | 0.29%   |
| Gigabyte B450M S2H           | 11       | 0.29%   |
| ASUS PRIME B450-PLUS         | 11       | 0.29%   |
| ASUS P8H67-M                 | 11       | 0.29%   |
| MSI MS-7B79                  | 10       | 0.27%   |
| HP Z420 Workstation          | 10       | 0.27%   |
| HP Compaq Elite 8300 SFF     | 10       | 0.27%   |
| ASUS PRIME X370-PRO          | 10       | 0.27%   |
| ASUS H110M-R                 | 10       | 0.27%   |
| ASRock H61M-VG4              | 10       | 0.27%   |
| ASRock B450 Pro4             | 10       | 0.27%   |
| MSI MS-7C91                  | 9        | 0.24%   |
| HP ProLiant MicroServer Gen8 | 9        | 0.24%   |
| HP ProLiant MicroServer      | 9        | 0.24%   |
| Gigabyte H61M-S2PV           | 9        | 0.24%   |
| Gigabyte GA-78LMT-USB3       | 9        | 0.24%   |
| Dell OptiPlex 3020           | 9        | 0.24%   |
| AZW U59                      | 9        | 0.24%   |
| AZW MINI S                   | 9        | 0.24%   |
| ASUS PRIME X570-PRO          | 9        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 220      | 5.87%   |
| Dell OptiPlex          | 133      | 3.55%   |
| ASUS All               | 124      | 3.31%   |
| Unknown                | 85       | 2.27%   |
| ASUS ROG               | 84       | 2.24%   |
| HP Compaq              | 64       | 1.71%   |
| Lenovo ThinkCentre     | 61       | 1.63%   |
| ASUS TUF               | 60       | 1.6%    |
| ASUS S20               | 55       | 1.47%   |
| Dell Precision         | 49       | 1.31%   |
| MSI MS-7996            | 40       | 1.07%   |
| Gigabyte B450M         | 38       | 1.01%   |
| ASUS P8H61-M           | 34       | 0.91%   |
| HP EliteDesk           | 30       | 0.8%    |
| HP ProLiant            | 28       | 0.75%   |
| MSI MS-7817            | 25       | 0.67%   |
| Gigabyte X570          | 25       | 0.67%   |
| Gigabyte H81M-S2V      | 24       | 0.64%   |
| ECS G31T-M9            | 24       | 0.64%   |
| ASUS PRO               | 24       | 0.64%   |
| ASRock B450M           | 24       | 0.64%   |
| Gigabyte H410M         | 20       | 0.53%   |
| ASRock H470M-HVS       | 20       | 0.53%   |
| Gigabyte B550          | 19       | 0.51%   |
| Fujitsu ESPRIMO        | 19       | 0.51%   |
| ASRock B450            | 19       | 0.51%   |
| Acer Aspire            | 19       | 0.51%   |
| Lenovo ThinkStation    | 18       | 0.48%   |
| HP ProDesk             | 18       | 0.48%   |
| ASUS M5A78L-M          | 18       | 0.48%   |
| ASUS P5G41T-M          | 17       | 0.45%   |
| Gigabyte GA-78LMT-USB3 | 16       | 0.43%   |
| ECS H61H2-M13          | 16       | 0.43%   |
| Gigabyte B450          | 15       | 0.4%    |
| Dell Vostro            | 15       | 0.4%    |
| ASUS P8H67-M           | 15       | 0.4%    |
| ASUS M5A97             | 15       | 0.4%    |
| Lenovo IdeaCentre      | 14       | 0.37%   |
| Dell XPS               | 14       | 0.37%   |
| Dell Inspiron          | 14       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 373      | 9.95%   |
| 2020    | 351      | 9.36%   |
| 2012    | 345      | 9.2%    |
| 2013    | 304      | 8.11%   |
| 2019    | 269      | 7.17%   |
| 2021    | 246      | 6.56%   |
| 2011    | 246      | 6.56%   |
| 2014    | 215      | 5.73%   |
| 2017    | 199      | 5.31%   |
| 2009    | 193      | 5.15%   |
| 2015    | 186      | 4.96%   |
| 2010    | 175      | 4.67%   |
| 2016    | 150      | 4%      |
| 2022    | 134      | 3.57%   |
| 2008    | 132      | 3.52%   |
| 2007    | 102      | 2.72%   |
| 2006    | 45       | 1.2%    |
| Unknown | 27       | 0.72%   |
| 2005    | 25       | 0.67%   |
| 2023    | 13       | 0.35%   |
| 2004    | 8        | 0.21%   |
| 2003    | 6        | 0.16%   |
| 2001    | 3        | 0.08%   |
| 2000    | 2        | 0.05%   |
| 2002    | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3750     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3694     | 98.3%   |
| Enabled  | 64       | 1.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3733     | 99.55%  |
| Yes  | 17       | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 754      | 19.81%  |
| 4.01-8.0        | 605      | 15.9%   |
| 8.01-16.0       | 593      | 15.58%  |
| 3.01-4.0        | 590      | 15.5%   |
| 32.01-64.0      | 559      | 14.69%  |
| 64.01-256.0     | 310      | 8.15%   |
| 1.01-2.0        | 156      | 4.1%    |
| 24.01-32.0      | 105      | 2.76%   |
| 2.01-3.0        | 64       | 1.68%   |
| 0.51-1.0        | 25       | 0.66%   |
| More than 256.0 | 16       | 0.42%   |
| Unknown         | 15       | 0.39%   |
| 0.01-0.5        | 13       | 0.34%   |
| 0               | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 915      | 22.55%  |
| 1.01-2.0        | 830      | 20.45%  |
| 2.01-3.0        | 665      | 16.39%  |
| 4.01-8.0        | 604      | 14.88%  |
| 3.01-4.0        | 392      | 9.66%   |
| 8.01-16.0       | 259      | 6.38%   |
| 0.01-0.5        | 164      | 4.04%   |
| 16.01-24.0      | 106      | 2.61%   |
| 32.01-64.0      | 51       | 1.26%   |
| 24.01-32.0      | 38       | 0.94%   |
| Unknown         | 18       | 0.44%   |
| 64.01-256.0     | 15       | 0.37%   |
| More than 256.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1688     | 43.7%   |
| 2       | 895      | 23.17%  |
| 3       | 507      | 13.12%  |
| 4       | 339      | 8.78%   |
| 5       | 159      | 4.12%   |
| 6       | 97       | 2.51%   |
| 7       | 51       | 1.32%   |
| 8       | 40       | 1.04%   |
| 0       | 23       | 0.6%    |
| 9       | 20       | 0.52%   |
| 10      | 13       | 0.34%   |
| 11      | 7        | 0.18%   |
| 13      | 6        | 0.16%   |
| 12      | 5        | 0.13%   |
| 14      | 2        | 0.05%   |
| Unknown | 2        | 0.05%   |
| 46      | 1        | 0.03%   |
| 29      | 1        | 0.03%   |
| 28      | 1        | 0.03%   |
| 27      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 18      | 1        | 0.03%   |
| 17      | 1        | 0.03%   |
| 16      | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2420     | 63.94%  |
| Yes       | 1365     | 36.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3720     | 99.2%   |
| No        | 30       | 0.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2610     | 69.07%  |
| Yes       | 1169     | 30.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2850     | 75.24%  |
| Yes       | 938      | 24.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 878      | 23.37%  |
| USA          | 546      | 14.53%  |
| Germany      | 374      | 9.95%   |
| France       | 238      | 6.33%   |
| Brazil       | 181      | 4.82%   |
| Spain        | 159      | 4.23%   |
| UK           | 121      | 3.22%   |
| Italy        | 120      | 3.19%   |
| Canada       | 98       | 2.61%   |
| Australia    | 76       | 2.02%   |
| Poland       | 65       | 1.73%   |
| Netherlands  | 58       | 1.54%   |
| China        | 44       | 1.17%   |
| Switzerland  | 42       | 1.12%   |
| Austria      | 40       | 1.06%   |
| Ukraine      | 37       | 0.98%   |
| Hungary      | 36       | 0.96%   |
| Belgium      | 35       | 0.93%   |
| Argentina    | 32       | 0.85%   |
| Sweden       | 31       | 0.83%   |
| Finland      | 31       | 0.83%   |
| Mexico       | 25       | 0.67%   |
| India        | 25       | 0.67%   |
| Czechia      | 24       | 0.64%   |
| Norway       | 23       | 0.61%   |
| Romania      | 22       | 0.59%   |
| Portugal     | 21       | 0.56%   |
| Japan        | 21       | 0.56%   |
| Bulgaria     | 21       | 0.56%   |
| Venezuela    | 19       | 0.51%   |
| Turkey       | 15       | 0.4%    |
| Belarus      | 15       | 0.4%    |
| Denmark      | 14       | 0.37%   |
| New Zealand  | 12       | 0.32%   |
| Taiwan       | 11       | 0.29%   |
| South Africa | 11       | 0.29%   |
| Malaysia     | 11       | 0.29%   |
| Slovakia     | 10       | 0.27%   |
| Ireland      | 10       | 0.27%   |
| Greece       | 10       | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 620      | 15.94%  |
| Moscow            | 64       | 1.65%   |
| St Petersburg     | 45       | 1.16%   |
| Paris             | 31       | 0.8%    |
| Vienna            | 30       | 0.77%   |
| Sao Paulo         | 29       | 0.75%   |
| Berlin            | 26       | 0.67%   |
| Falkenstein       | 24       | 0.62%   |
| Madrid            | 22       | 0.57%   |
| Seville           | 21       | 0.54%   |
| Barcelona         | 20       | 0.51%   |
| Amsterdam         | 18       | 0.46%   |
| Toronto           | 17       | 0.44%   |
| Rio de Janeiro    | 17       | 0.44%   |
| Melbourne         | 17       | 0.44%   |
| Sydney            | 15       | 0.39%   |
| Yekaterinburg     | 14       | 0.36%   |
| Milan             | 14       | 0.36%   |
| Brisbane          | 14       | 0.36%   |
| Munich            | 13       | 0.33%   |
| Hamburg           | 13       | 0.33%   |
| Budapest          | 13       | 0.33%   |
| Bangor            | 13       | 0.33%   |
| Warsaw            | 12       | 0.31%   |
| Kyiv              | 12       | 0.31%   |
| Zurich            | 11       | 0.28%   |
| Perm              | 11       | 0.28%   |
| New York          | 11       | 0.28%   |
| London            | 11       | 0.28%   |
| Dallas            | 11       | 0.28%   |
| Chicago           | 11       | 0.28%   |
| Valencia          | 10       | 0.26%   |
| Sofia             | 10       | 0.26%   |
| Nuremberg         | 10       | 0.26%   |
| Minsk             | 10       | 0.26%   |
| Helsinki          | 10       | 0.26%   |
| Gladbeck          | 10       | 0.26%   |
| Frankfurt am Main | 10       | 0.26%   |
| Dover-Foxcroft    | 10       | 0.26%   |
| Cologne           | 10       | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 1249     | 2305   | 18.74%  |
| Seagate                   | 1212     | 2184   | 18.18%  |
| Samsung Electronics       | 972      | 1562   | 14.58%  |
| Kingston                  | 459      | 604    | 6.89%   |
| Toshiba                   | 437      | 797    | 6.56%   |
| Crucial                   | 378      | 516    | 5.67%   |
| Hitachi                   | 229      | 337    | 3.44%   |
| SanDisk                   | 223      | 307    | 3.35%   |
| Intel                     | 125      | 175    | 1.88%   |
| A-DATA Technology         | 103      | 140    | 1.55%   |
| HGST                      | 98       | 174    | 1.47%   |
| China                     | 88       | 105    | 1.32%   |
| Unknown                   | 79       | 117    | 1.19%   |
| SPCC                      | 56       | 61     | 0.84%   |
| Phison                    | 48       | 69     | 0.72%   |
| Transcend                 | 47       | 50     | 0.71%   |
| Corsair                   | 45       | 63     | 0.68%   |
| OCZ                       | 44       | 55     | 0.66%   |
| PNY                       | 43       | 80     | 0.65%   |
| Maxtor                    | 43       | 50     | 0.65%   |
| Hewlett-Packard           | 38       | 67     | 0.57%   |
| Patriot                   | 30       | 41     | 0.45%   |
| Micron Technology         | 30       | 37     | 0.45%   |
| Netac                     | 28       | 88     | 0.42%   |
| Intenso                   | 28       | 39     | 0.42%   |
| Gigabyte Technology       | 28       | 32     | 0.42%   |
| SK hynix                  | 27       | 43     | 0.41%   |
| GOODRAM                   | 24       | 41     | 0.36%   |
| Unknown                   | 18       | 19     | 0.27%   |
| XPG                       | 16       | 27     | 0.24%   |
| Apacer                    | 16       | 18     | 0.24%   |
| Plextor                   | 14       | 20     | 0.21%   |
| JMicron Technology        | 14       | 16     | 0.21%   |
| Team                      | 13       | 19     | 0.2%    |
| LITEON                    | 13       | 17     | 0.2%    |
| Silicon Motion            | 12       | 17     | 0.18%   |
| KingDian                  | 12       | 13     | 0.18%   |
| Micron/Crucial Technology | 10       | 14     | 0.15%   |
| ASMT                      | 9        | 12     | 0.14%   |
| Phison Electronics        | 8        | 13     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 110      | 1.39%   |
| Seagate ST500DM002-1BD142 500GB  | 106      | 1.34%   |
| Seagate ST1000DM010-2EP102 1TB   | 86       | 1.09%   |
| Crucial CT480BX500SSD1 480GB     | 85       | 1.07%   |
| Toshiba DT01ACA050 500GB         | 74       | 0.93%   |
| Kingston SV300S37A120G 120GB SSD | 61       | 0.77%   |
| Kingston SA400S37480G 480GB SSD  | 58       | 0.73%   |
| Toshiba DT01ACA100 1TB           | 54       | 0.68%   |
| Samsung SSD 860 EVO 500GB        | 54       | 0.68%   |
| Samsung SSD 860 EVO 1TB          | 54       | 0.68%   |
| Samsung SSD 850 EVO 250GB        | 52       | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB         | 51       | 0.64%   |
| Samsung SSD 860 EVO 250GB        | 51       | 0.64%   |
| Kingston SA400S37120G 120GB SSD  | 51       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 49       | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB   | 48       | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB   | 48       | 0.61%   |
| Crucial CT500MX500SSD1 500GB     | 47       | 0.59%   |
| Toshiba HDWD110 1TB              | 46       | 0.58%   |
| Samsung SSD 850 EVO 500GB        | 46       | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB     | 44       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB   | 41       | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 40       | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB   | 40       | 0.51%   |
| Hitachi HDS721050CLA362 500GB    | 39       | 0.49%   |
| Crucial CT240BX500SSD1 240GB     | 39       | 0.49%   |
| Crucial CT1000MX500SSD1 1TB      | 38       | 0.48%   |
| Toshiba DT01ACA200 2TB           | 30       | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB   | 30       | 0.38%   |
| Samsung SSD 980 PRO 1TB          | 30       | 0.38%   |
| Seagate ST3500418AS 500GB        | 28       | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB         | 27       | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB   | 27       | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB         | 26       | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB         | 26       | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB         | 26       | 0.33%   |
| Samsung SSD 870 EVO 500GB        | 25       | 0.32%   |
| Crucial CT250MX500SSD1 250GB     | 25       | 0.32%   |
| Toshiba DT01ACA300 3TB           | 24       | 0.3%    |
| WDC WD20EARX-00PASB0 2TB         | 23       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1188     | 2128   | 36.13%  |
| WDC                 | 1092     | 2028   | 33.21%  |
| Toshiba             | 398      | 730    | 12.1%   |
| Hitachi             | 229      | 337    | 6.96%   |
| Samsung Electronics | 151      | 204    | 4.59%   |
| HGST                | 98       | 174    | 2.98%   |
| Maxtor              | 42       | 49     | 1.28%   |
| Unknown             | 17       | 24     | 0.52%   |
| Hewlett-Packard     | 9        | 24     | 0.27%   |
| Fujitsu             | 6        | 7      | 0.18%   |
| ASMT                | 6        | 9      | 0.18%   |
| Intenso             | 4        | 5      | 0.12%   |
| HPE                 | 4        | 9      | 0.12%   |
| External            | 4        | 6      | 0.12%   |
| Apple               | 4        | 5      | 0.12%   |
| ASMedia             | 3        | 3      | 0.09%   |
| QNAP                | 2        | 3      | 0.06%   |
| WD MediaMax         | 1        | 6      | 0.03%   |
| USB 3.0             | 1        | 2      | 0.03%   |
| USB                 | 1        | 1      | 0.03%   |
| Synology            | 1        | 1      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SD                  | 1        | 1      | 0.03%   |
| SABRENT             | 1        | 2      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| pqi                 | 1        | 1      | 0.03%   |
| Pear 2TB            | 1        | 1      | 0.03%   |
| NAS                 | 1        | 10     | 0.03%   |
| MaxDigital          | 1        | 4      | 0.03%   |
| MARSHAL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| JMicron Technology  | 1        | 2      | 0.03%   |
| Innodisk            | 1        | 1      | 0.03%   |
| Inateck             | 1        | 1      | 0.03%   |
| IBM/Hitachi         | 1        | 1      | 0.03%   |
| IBM H0              | 1        | 1      | 0.03%   |
| Hajaan              | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 544      | 794    | 22.12%  |
| Kingston            | 415      | 538    | 16.88%  |
| Crucial             | 338      | 460    | 13.75%  |
| SanDisk             | 159      | 218    | 6.47%   |
| WDC                 | 141      | 175    | 5.73%   |
| China               | 86       | 103    | 3.5%    |
| A-DATA Technology   | 79       | 104    | 3.21%   |
| Intel               | 66       | 89     | 2.68%   |
| SPCC                | 49       | 52     | 1.99%   |
| OCZ                 | 44       | 55     | 1.79%   |
| Transcend           | 41       | 44     | 1.67%   |
| Toshiba             | 33       | 42     | 1.34%   |
| PNY                 | 31       | 65     | 1.26%   |
| Netac               | 26       | 86     | 1.06%   |
| Patriot             | 22       | 27     | 0.89%   |
| Intenso             | 22       | 30     | 0.89%   |
| GOODRAM             | 21       | 29     | 0.85%   |
| Micron Technology   | 18       | 22     | 0.73%   |
| Corsair             | 18       | 23     | 0.73%   |
| Gigabyte Technology | 15       | 17     | 0.61%   |
| Hewlett-Packard     | 13       | 17     | 0.53%   |
| Apacer              | 12       | 12     | 0.49%   |
| Team                | 11       | 14     | 0.45%   |
| Plextor             | 11       | 17     | 0.45%   |
| KingDian            | 11       | 12     | 0.45%   |
| SK hynix            | 10       | 11     | 0.41%   |
| Seagate             | 10       | 12     | 0.41%   |
| Unknown             | 10       | 11     | 0.41%   |
| LITEON              | 9        | 13     | 0.37%   |
| JMicron Technology  | 9        | 10     | 0.37%   |
| Unknown             | 8        | 11     | 0.33%   |
| Mushkin             | 8        | 9      | 0.33%   |
| Hajaan              | 8        | 11     | 0.33%   |
| LITEONIT            | 7        | 12     | 0.28%   |
| SABRENT             | 6        | 6      | 0.24%   |
| Xinhaike            | 5        | 8      | 0.2%    |
| NGFF                | 5        | 5      | 0.2%    |
| Hoodisk             | 5        | 5      | 0.2%    |
| TO Exter            | 4        | 4      | 0.16%   |
| T-FORCE             | 4        | 5      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2517     | 5808   | 45.16%  |
| SSD     | 2037     | 3325   | 36.55%  |
| NVMe    | 909      | 1437   | 16.31%  |
| Unknown | 69       | 127    | 1.24%   |
| MMC     | 41       | 48     | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3404     | 8768   | 74.23%  |
| NVMe | 907      | 1432   | 19.78%  |
| SAS  | 234      | 497    | 5.1%    |
| MMC  | 41       | 48     | 0.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 2634     | 4476    | 51.38%  |
| 0.51-1.0   | 1232     | 2042    | 24.03%  |
| 1.01-2.0   | 531      | 928     | 10.36%  |
| 3.01-4.0   | 291      | 599     | 5.68%   |
| 4.01-10.0  | 209      | 548     | 4.08%   |
| 2.01-3.0   | 169      | 316     | 3.3%    |
| 10.01-20.0 | 59       | 223     | 1.15%   |
| 20.01-50.0 | 1        | 1       | 0.02%   |
| 0          | 1        | Unknown | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 818      | 21.03%  |
| 101-250        | 614      | 15.79%  |
| 251-500        | 520      | 13.37%  |
| 501-1000       | 490      | 12.6%   |
| More than 3000 | 449      | 11.55%  |
| 1001-2000      | 349      | 8.97%   |
| 51-100         | 208      | 5.35%   |
| 2001-3000      | 182      | 4.68%   |
| 1-20           | 141      | 3.63%   |
| 21-50          | 118      | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1001     | 25.19%  |
| Unknown        | 818      | 20.58%  |
| 101-250        | 385      | 9.69%   |
| 21-50          | 332      | 8.35%   |
| 251-500        | 301      | 7.57%   |
| 501-1000       | 299      | 7.52%   |
| 51-100         | 295      | 7.42%   |
| 1001-2000      | 232      | 5.84%   |
| More than 3000 | 196      | 4.93%   |
| 2001-3000      | 106      | 2.67%   |
| 0              | 9        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 26       | 40     | 2.91%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 36     | 2.24%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 20     | 2.24%   |
| Hitachi HDS721050CLA362 500GB    | 12       | 13     | 1.34%   |
| Seagate ST1000DM003-9YN162 1TB   | 9        | 10     | 1.01%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 8        | 8      | 0.89%   |
| Seagate ST31500341AS 1TB         | 8        | 14     | 0.89%   |
| Seagate ST31000528AS 1TB         | 8        | 10     | 0.89%   |
| Toshiba DT01ACA100 1TB           | 7        | 9      | 0.78%   |
| Toshiba DT01ACA050 500GB         | 7        | 8      | 0.78%   |
| Seagate ST3500418AS 500GB        | 7        | 12     | 0.78%   |
| Seagate ST3250318AS 250GB        | 7        | 8      | 0.78%   |
| Seagate ST3160815AS 160GB        | 7        | 9      | 0.78%   |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB   | 7        | 7      | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB      | 6        | 8      | 0.67%   |
| WDC WD20EARX-00PASB0 2TB         | 6        | 8      | 0.67%   |
| Seagate ST3320613AS 320GB        | 6        | 6      | 0.67%   |
| Seagate ST3250410AS 250GB        | 6        | 7      | 0.67%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.67%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 5        | 6      | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB         | 5        | 16     | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB         | 5        | 5      | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 0.56%   |
| WDC WD10EARS-00Y5B1 1TB          | 5        | 5      | 0.56%   |
| WDC WD10EADS-00M2B0 1TB          | 5        | 5      | 0.56%   |
| Seagate ST3500413AS 500GB        | 5        | 6      | 0.56%   |
| Seagate ST31000524AS 1TB         | 5        | 5      | 0.56%   |
| Samsung Electronics HD103UJ 1TB  | 5        | 6      | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 4        | 4      | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.45%   |
| WDC WD3200AAJS-00L7A0 320GB      | 4        | 4      | 0.45%   |
| Seagate ST9500325AS 500GB        | 4        | 6      | 0.45%   |
| Seagate ST3320620AS 320GB        | 4        | 6      | 0.45%   |
| Seagate ST3250310AS 250GB        | 4        | 5      | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB   | 4        | 4      | 0.45%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 5      | 0.45%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 4      | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 5      | 0.45%   |
| Samsung Electronics HD103SJ 1TB  | 4        | 4      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 259      | 369    | 30.58%  |
| WDC                 | 242      | 343    | 28.57%  |
| Samsung Electronics | 74       | 84     | 8.74%   |
| Hitachi             | 58       | 81     | 6.85%   |
| Toshiba             | 40       | 50     | 4.72%   |
| Kingston            | 40       | 46     | 4.72%   |
| Intel               | 22       | 27     | 2.6%    |
| Crucial             | 17       | 23     | 2.01%   |
| A-DATA Technology   | 16       | 23     | 1.89%   |
| Maxtor              | 14       | 15     | 1.65%   |
| SanDisk             | 9        | 12     | 1.06%   |
| HGST                | 9        | 10     | 1.06%   |
| OCZ                 | 7        | 8      | 0.83%   |
| China               | 5        | 5      | 0.59%   |
| SK hynix            | 4        | 8      | 0.47%   |
| KingDian            | 4        | 4      | 0.47%   |
| Micron Technology   | 3        | 3      | 0.35%   |
| Transcend           | 2        | 2      | 0.24%   |
| LITEONIT            | 2        | 2      | 0.24%   |
| Hewlett-Packard     | 2        | 3      | 0.24%   |
| Corsair             | 2        | 2      | 0.24%   |
| Apacer              | 2        | 2      | 0.24%   |
| Western Digital     | 1        | 2      | 0.12%   |
| Unknown             | 1        | 1      | 0.12%   |
| Teclast             | 1        | 1      | 0.12%   |
| SPCC                | 1        | 1      | 0.12%   |
| ShiJi               | 1        | 1      | 0.12%   |
| PNY                 | 1        | 1      | 0.12%   |
| Plextor             | 1        | 2      | 0.12%   |
| Patriot             | 1        | 1      | 0.12%   |
| LITEON              | 1        | 1      | 0.12%   |
| Intenso             | 1        | 1      | 0.12%   |
| Hypertec            | 1        | 1      | 0.12%   |
| HP Phison           | 1        | 1      | 0.12%   |
| Fujitsu             | 1        | 2      | 0.12%   |
| ASMT                | 1        | 2      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 259      | 369    | 39.24%  |
| WDC                 | 232      | 331    | 35.15%  |
| Hitachi             | 58       | 81     | 8.79%   |
| Samsung Electronics | 45       | 50     | 6.82%   |
| Toshiba             | 38       | 48     | 5.76%   |
| Maxtor              | 14       | 15     | 2.12%   |
| HGST                | 9        | 10     | 1.36%   |
| Hewlett-Packard     | 2        | 3      | 0.3%    |
| Unknown             | 1        | 1      | 0.15%   |
| Fujitsu             | 1        | 2      | 0.15%   |
| ASMT                | 1        | 2      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 600      | 912    | 76.43%  |
| SSD  | 162      | 197    | 20.64%  |
| NVMe | 23       | 31     | 2.93%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 3      | 10.53%  |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 5.26%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 5.26%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 5.26%   |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 5.26%   |
| Seagate ST3500630A 500GB                         | 1        | 1      | 5.26%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 5.26%   |
| Samsung Electronics SP0802N 80GB                 | 1        | 1      | 5.26%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 5.26%   |
| Samsung Electronics HD253GJ 250GB                | 1        | 1      | 5.26%   |
| Samsung Electronics HD103SJ 1TB                  | 1        | 2      | 5.26%   |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 5.26%   |
| Inland SATA SSD 128GB                            | 1        | 1      | 5.26%   |
| HGST HUH728080ALN600 8TB                         | 1        | 1      | 5.26%   |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 5.26%   |
| Hewlett-Packard SSD S700 500GB                   | 1        | 2      | 5.26%   |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 5.26%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 31.58%  |
| Seagate             | 5        | 6      | 26.32%  |
| WDC                 | 2        | 2      | 10.53%  |
| HGST                | 2        | 2      | 10.53%  |
| Intel               | 1        | 1      | 5.26%   |
| Inland              | 1        | 1      | 5.26%   |
| Hewlett-Packard     | 1        | 2      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2717     | 6865   | 61.11%  |
| Detected | 961      | 2716   | 21.61%  |
| Malfunc  | 748      | 1140   | 16.82%  |
| Failed   | 19       | 23     | 0.43%   |
| Limited  | 1        | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2499     | 47.28%  |
| AMD                              | 1094     | 20.7%   |
| Samsung Electronics              | 389      | 7.36%   |
| ASMedia Technology               | 204      | 3.86%   |
| Marvell Technology Group         | 142      | 2.69%   |
| SanDisk                          | 141      | 2.67%   |
| Phison Electronics               | 124      | 2.35%   |
| JMicron Technology               | 108      | 2.04%   |
| Nvidia                           | 91       | 1.72%   |
| Kingston Technology Company      | 59       | 1.12%   |
| Micron/Crucial Technology        | 56       | 1.06%   |
| LSI Logic / Symbios Logic        | 45       | 0.85%   |
| VIA Technologies                 | 44       | 0.83%   |
| Silicon Motion                   | 41       | 0.78%   |
| ADATA Technology                 | 39       | 0.74%   |
| Broadcom / LSI                   | 34       | 0.64%   |
| Silicon Image                    | 21       | 0.4%    |
| Toshiba America Info Systems     | 17       | 0.32%   |
| SK hynix                         | 15       | 0.28%   |
| Adaptec                          | 15       | 0.28%   |
| Micron Technology                | 13       | 0.25%   |
| Realtek Semiconductor            | 12       | 0.23%   |
| Seagate Technology               | 11       | 0.21%   |
| KIOXIA                           | 11       | 0.21%   |
| Lite-On Technology               | 9        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.15%   |
| Silicon Integrated Systems [SiS] | 5        | 0.09%   |
| IBM                              | 5        | 0.09%   |
| Hewlett-Packard                  | 5        | 0.09%   |
| Integrated Technology Express    | 4        | 0.08%   |
| INNOGRIT                         | 3        | 0.06%   |
| Transcend                        | 2        | 0.04%   |
| Netac Technology                 | 2        | 0.04%   |
| Mylex                            | 2        | 0.04%   |
| HighPoint Technologies           | 2        | 0.04%   |
| Biwin Storage Technology         | 2        | 0.04%   |
| 3ware                            | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Tekram Technology                | 1        | 0.02%   |
| Shenzhen Longsys Electronics     | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 653      | 9.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 308      | 4.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 247      | 3.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 230      | 3.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 195      | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 193      | 2.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 192      | 2.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 181      | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 180      | 2.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 151      | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 148      | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 144      | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 129      | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 123      | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 97       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 91       | 1.37%   |
| Intel SATA Controller [RAID mode]                                                       | 90       | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 90       | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 86       | 1.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 84       | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 76       | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 65       | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 63       | 0.95%   |
| Phison E12 NVMe Controller                                                              | 62       | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 57       | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 56       | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 55       | 0.83%   |
| AMD FCH SATA Controller D                                                               | 52       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 51       | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 50       | 0.75%   |
| Nvidia MCP61 SATA Controller                                                            | 49       | 0.74%   |
| AMD 300 Series Chipset SATA Controller                                                  | 47       | 0.71%   |
| Nvidia MCP61 IDE                                                                        | 43       | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 42       | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 42       | 0.63%   |
| AMD X370 Series Chipset SATA Controller                                                 | 42       | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 40       | 0.6%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 39       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 38       | 0.57%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 36       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3017     | 57.91%  |
| IDE  | 939      | 18.02%  |
| NVMe | 911      | 17.49%  |
| RAID | 232      | 4.45%   |
| SAS  | 80       | 1.54%   |
| SCSI | 31       | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2526     | 67.36%  |
| AMD                   | 1191     | 31.76%  |
| Unknown               | 7        | 0.19%   |
| CentaurHauls          | 6        | 0.16%   |
| CHRP IBM,8233-E8B     | 5        | 0.13%   |
| ARM                   | 5        | 0.13%   |
| sifive,bullet0        | 3        | 0.08%   |
| sifive,u74-mc         | 2        | 0.05%   |
| CHRP IBM,9131-52A     | 2        | 0.05%   |
| PowerNV FP5466G2      | 1        | 0.03%   |
| PowerNV C829UAG3      | 1        | 0.03%   |
| Marvell Semiconductor | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 66       | 1.76%   |
| AMD Ryzen 5 3600 6-Core Processor           | 62       | 1.65%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 42       | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 38       | 1.01%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 37       | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 37       | 0.98%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 35       | 0.93%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 35       | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 35       | 0.93%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 31       | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 31       | 0.82%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 31       | 0.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 31       | 0.82%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 30       | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 30       | 0.8%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 30       | 0.8%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 29       | 0.77%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 28       | 0.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 28       | 0.74%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 28       | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 27       | 0.72%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 27       | 0.72%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 26       | 0.69%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 24       | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 24       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.64%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 24       | 0.64%   |
| Intel Celeron N5105 @ 2.00GHz               | 23       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 23       | 0.61%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 22       | 0.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 22       | 0.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 22       | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 21       | 0.56%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 21       | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 21       | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 20       | 0.53%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 20       | 0.53%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 20       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 582      | 15.5%   |
| Intel Core i7           | 373      | 9.93%   |
| Intel Core i3           | 324      | 8.63%   |
| AMD Ryzen 5             | 268      | 7.14%   |
| Intel Xeon              | 242      | 6.44%   |
| AMD Ryzen 7             | 215      | 5.72%   |
| Intel Celeron           | 206      | 5.48%   |
| Intel Pentium           | 199      | 5.3%    |
| Other                   | 156      | 4.15%   |
| Intel Core 2 Duo        | 146      | 3.89%   |
| AMD Ryzen 9             | 121      | 3.22%   |
| AMD FX                  | 119      | 3.17%   |
| Intel Pentium Dual-Core | 73       | 1.94%   |
| Intel Core 2 Quad       | 63       | 1.68%   |
| AMD Ryzen 3             | 57       | 1.52%   |
| Intel Atom              | 39       | 1.04%   |
| AMD Ryzen Threadripper  | 37       | 0.99%   |
| Intel Core i9           | 33       | 0.88%   |
| AMD Athlon 64 X2        | 33       | 0.88%   |
| AMD Phenom II X4        | 32       | 0.85%   |
| AMD Athlon II X2        | 32       | 0.85%   |
| AMD A10                 | 29       | 0.77%   |
| AMD Athlon              | 28       | 0.75%   |
| Intel Core 2            | 27       | 0.72%   |
| Intel Pentium 4         | 26       | 0.69%   |
| Intel Pentium Gold      | 25       | 0.67%   |
| AMD A8                  | 25       | 0.67%   |
| AMD Ryzen 5 PRO         | 17       | 0.45%   |
| AMD Phenom II X6        | 17       | 0.45%   |
| AMD GX                  | 17       | 0.45%   |
| Intel Pentium Dual      | 15       | 0.4%    |
| AMD Athlon II X4        | 14       | 0.37%   |
| AMD Sempron             | 13       | 0.35%   |
| Intel Pentium D         | 11       | 0.29%   |
| AMD Phenom              | 11       | 0.29%   |
| Intel Pentium Silver    | 10       | 0.27%   |
| AMD E                   | 10       | 0.27%   |
| AMD Athlon 64           | 10       | 0.27%   |
| AMD A4                  | 10       | 0.27%   |
| AMD A6                  | 9        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1279     | 34.03%  |
| 2       | 1115     | 29.66%  |
| 6       | 535      | 14.23%  |
| 8       | 364      | 9.68%   |
| 1       | 125      | 3.33%   |
| 12      | 108      | 2.87%   |
| 16      | 104      | 2.77%   |
| 3       | 43       | 1.14%   |
| 10      | 28       | 0.74%   |
| 24      | 15       | 0.4%    |
| 32      | 13       | 0.35%   |
| Unknown | 8        | 0.21%   |
| 14      | 5        | 0.13%   |
| 18      | 4        | 0.11%   |
| 64      | 3        | 0.08%   |
| 44      | 3        | 0.08%   |
| 20      | 3        | 0.08%   |
| 22      | 2        | 0.05%   |
| 36      | 1        | 0.03%   |
| 28      | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3674     | 97.92%  |
| 2       | 68       | 1.81%   |
| Unknown | 8        | 0.21%   |
| 16      | 1        | 0.03%   |
| 0       | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2011     | 53.56%  |
| 1       | 1729     | 46.05%  |
| Unknown | 8        | 0.21%   |
| 4       | 6        | 0.16%   |
| 8       | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3638     | 96.86%  |
| Unknown        | 79       | 2.1%    |
| 32-bit         | 39       | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 829      | 21.49%  |
| 0x306c3    | 318      | 8.24%   |
| 0x206a7    | 197      | 5.11%   |
| 0x1067a    | 184      | 4.77%   |
| 0x306a9    | 176      | 4.56%   |
| 0x506e3    | 141      | 3.65%   |
| 0x906ea    | 131      | 3.4%    |
| 0x08701021 | 122      | 3.16%   |
| 0xa0653    | 86       | 2.23%   |
| 0x906e9    | 76       | 1.97%   |
| 0x0800820d | 64       | 1.66%   |
| 0x08108109 | 60       | 1.56%   |
| 0x0a201016 | 56       | 1.45%   |
| 0xa0655    | 51       | 1.32%   |
| 0xa0671    | 42       | 1.09%   |
| 0x010000c8 | 41       | 1.06%   |
| 0x906c0    | 40       | 1.04%   |
| 0x08701013 | 40       | 1.04%   |
| 0x90672    | 38       | 0.98%   |
| 0x906ed    | 35       | 0.91%   |
| 0x306f2    | 30       | 0.78%   |
| 0x206d7    | 30       | 0.78%   |
| 0x6fd      | 29       | 0.75%   |
| 0x08101016 | 29       | 0.75%   |
| 0x06000852 | 29       | 0.75%   |
| 0x08001137 | 28       | 0.73%   |
| 0x06003106 | 27       | 0.7%    |
| 0x6fb      | 26       | 0.67%   |
| 0x306e4    | 26       | 0.67%   |
| 0x906eb    | 25       | 0.65%   |
| 0x0a20120a | 22       | 0.57%   |
| 0x0a201009 | 22       | 0.57%   |
| 0x08001138 | 22       | 0.57%   |
| 0x08600106 | 21       | 0.54%   |
| 0x206c2    | 20       | 0.52%   |
| 0x10676    | 20       | 0.52%   |
| 0x0a50000c | 20       | 0.52%   |
| 0x06001119 | 19       | 0.49%   |
| 0x20655    | 18       | 0.47%   |
| 0x106a5    | 18       | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 450      | 11.97%  |
| KabyLake         | 342      | 9.1%    |
| SandyBridge      | 276      | 7.34%   |
| Penryn           | 253      | 6.73%   |
| IvyBridge        | 246      | 6.54%   |
| Zen 2            | 239      | 6.36%   |
| Skylake          | 195      | 5.19%   |
| Zen+             | 183      | 4.87%   |
| Zen 3            | 180      | 4.79%   |
| CometLake        | 154      | 4.1%    |
| K10              | 132      | 3.51%   |
| Unknown          | 130      | 3.46%   |
| Zen              | 127      | 3.38%   |
| Piledriver       | 116      | 3.09%   |
| Core             | 114      | 3.03%   |
| Westmere         | 62       | 1.65%   |
| Silvermont       | 56       | 1.49%   |
| K8 Hammer        | 56       | 1.49%   |
| NetBurst         | 47       | 1.25%   |
| Nehalem          | 47       | 1.25%   |
| Tremont          | 45       | 1.2%    |
| Alderlake Hybrid | 40       | 1.06%   |
| Steamroller      | 35       | 0.93%   |
| Goldmont plus    | 33       | 0.88%   |
| Bulldozer        | 30       | 0.8%    |
| Bonnell          | 28       | 0.74%   |
| Goldmont         | 24       | 0.64%   |
| Broadwell        | 22       | 0.59%   |
| Bobcat           | 19       | 0.51%   |
| Jaguar           | 18       | 0.48%   |
| Excavator        | 17       | 0.45%   |
| Icelake          | 13       | 0.35%   |
| Puma             | 10       | 0.27%   |
| K6               | 6        | 0.16%   |
| P6               | 5        | 0.13%   |
| K10 Llano        | 5        | 0.13%   |
| TigerLake        | 4        | 0.11%   |
| Geode            | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1528     | 38.54%  |
| Nvidia                           | 1311     | 33.06%  |
| AMD                              | 997      | 25.15%  |
| ASPEED Technology                | 69       | 1.74%   |
| Matrox Electronics Systems       | 42       | 1.06%   |
| VIA Technologies                 | 10       | 0.25%   |
| Silicon Integrated Systems [SiS] | 3        | 0.08%   |
| Silicon Motion                   | 1        | 0.03%   |
| Loongson Technology              | 1        | 0.03%   |
| Cirrus Logic                     | 1        | 0.03%   |
| ATI Technologies                 | 1        | 0.03%   |
| 3DLabs                           | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 218      | 5.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 145      | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 136      | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 129      | 3.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 97       | 2.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 88       | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 87       | 2.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 81       | 1.99%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 75       | 1.85%   |
| Intel HD Graphics 530                                                                    | 73       | 1.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 71       | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 71       | 1.75%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 69       | 1.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 64       | 1.58%   |
| Intel HD Graphics 630                                                                    | 53       | 1.31%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 48       | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 48       | 1.18%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 48       | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 46       | 1.13%   |
| Nvidia GT218 [GeForce 210]                                                               | 43       | 1.06%   |
| Intel JasperLake [UHD Graphics]                                                          | 42       | 1.03%   |
| Intel HD Graphics 510                                                                    | 39       | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37       | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 36       | 0.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 35       | 0.86%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 34       | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 32       | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 32       | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 32       | 0.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 32       | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 29       | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 29       | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 27       | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 27       | 0.66%   |
| Intel AlderLake-S GT1                                                                    | 27       | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26       | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26       | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 26       | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 24       | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 24       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1370     | 36.1%   |
| 1 x Nvidia                        | 1193     | 31.44%  |
| 1 x AMD                           | 895      | 23.58%  |
| Intel + Nvidia                    | 62       | 1.63%   |
| 1 x ASPEED                        | 52       | 1.37%   |
| 2 x AMD                           | 42       | 1.11%   |
| 1 x Matrox                        | 40       | 1.05%   |
| Other                             | 35       | 0.92%   |
| AMD + Nvidia                      | 27       | 0.71%   |
| Intel + AMD                       | 20       | 0.53%   |
| 2 x Nvidia                        | 14       | 0.37%   |
| 1 x VIA                           | 10       | 0.26%   |
| Nvidia + ASPEED                   | 10       | 0.26%   |
| AMD + ASPEED                      | 5        | 0.13%   |
| AMD + Matrox                      | 4        | 0.11%   |
| 2 x Intel                         | 3        | 0.08%   |
| 1 x SiS                           | 3        | 0.08%   |
| Intel + 2 x Nvidia                | 3        | 0.08%   |
| 3 x AMD                           | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.03%   |
| 2 x Loongson Technology           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.03%   |
| 1 x Silicon Motion                | 1        | 0.03%   |
| 1 x Cirrus Logic                  | 1        | 0.03%   |
| AMD + 3DLabs                      | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2133     | 56.19%  |
| Unknown     | 1002     | 26.4%   |
| Proprietary | 661      | 17.41%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2304     | 60.08%  |
| 1.01-2.0   | 354      | 9.23%   |
| 0.51-1.0   | 271      | 7.07%   |
| 0.01-0.5   | 240      | 6.26%   |
| 3.01-4.0   | 232      | 6.05%   |
| 7.01-8.0   | 214      | 5.58%   |
| 5.01-6.0   | 103      | 2.69%   |
| 8.01-16.0  | 59       | 1.54%   |
| 2.01-3.0   | 40       | 1.04%   |
| 16.01-24.0 | 13       | 0.34%   |
| 4.01-5.0   | 4        | 0.1%    |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 469      | 15.8%   |
| Dell                 | 347      | 11.69%  |
| Goldstar             | 289      | 9.74%   |
| Hewlett-Packard      | 190      | 6.4%    |
| BenQ                 | 187      | 6.3%    |
| Acer                 | 187      | 6.3%    |
| Philips              | 154      | 5.19%   |
| AOC                  | 148      | 4.99%   |
| Ancor Communications | 122      | 4.11%   |
| Iiyama               | 74       | 2.49%   |
| ViewSonic            | 66       | 2.22%   |
| Unknown              | 62       | 2.09%   |
| LG Electronics       | 44       | 1.48%   |
| ASUSTek Computer     | 44       | 1.48%   |
| Lenovo               | 42       | 1.42%   |
| Eizo                 | 34       | 1.15%   |
| Sony                 | 28       | 0.94%   |
| NEC Computers        | 26       | 0.88%   |
| Medion               | 18       | 0.61%   |
| Unknown              | 18       | 0.61%   |
| Fujitsu Siemens      | 17       | 0.57%   |
| Vizio                | 13       | 0.44%   |
| Vestel Elektronik    | 13       | 0.44%   |
| MSI                  | 11       | 0.37%   |
| Belinea              | 10       | 0.34%   |
| Idek Iiyama          | 9        | 0.3%    |
| HPN                  | 9        | 0.3%    |
| HannStar             | 9        | 0.3%    |
| Toshiba              | 8        | 0.27%   |
| Sceptre Tech         | 8        | 0.27%   |
| Panasonic            | 8        | 0.27%   |
| Hitachi              | 8        | 0.27%   |
| Apple                | 7        | 0.24%   |
| RTK                  | 6        | 0.2%    |
| ONN                  | 6        | 0.2%    |
| Lenovo Group Limited | 6        | 0.2%    |
| CHR                  | 6        | 0.2%    |
| AUS                  | 6        | 0.2%    |
| ___                  | 5        | 0.17%   |
| Targa Visionary      | 5        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 28       | 0.88%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 27       | 0.85%   |
| Unknown                                                               | 18       | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 13       | 0.41%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 12       | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 10       | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 10       | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 10       | 0.31%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 10       | 0.31%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 9        | 0.28%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 9        | 0.28%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 8        | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 8        | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8        | 0.25%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 8        | 0.25%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 7        | 0.22%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 7        | 0.22%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 7        | 0.22%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 7        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 7        | 0.22%   |
| Ancor Communications VE228 ACI22FA 1920x1080 531x299mm 24.0-inch      | 7        | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6        | 0.19%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 6        | 0.19%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 6        | 0.19%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 6        | 0.19%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 6        | 0.19%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 6        | 0.19%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 6        | 0.19%   |
| Ancor Communications VE248 ACI2494 1920x1080 530x300mm 24.0-inch      | 6        | 0.19%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 6        | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.19%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 5        | 0.16%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.16%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 5        | 0.16%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 5        | 0.16%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 5        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 5        | 0.16%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5        | 0.16%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                 | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1203     | 40.93%  |
| 3840x2160 (4K)     | 266      | 9.05%   |
| 1280x1024 (SXGA)   | 262      | 8.91%   |
| 2560x1440 (QHD)    | 211      | 7.18%   |
| 1680x1050 (WSXGA+) | 156      | 5.31%   |
| 1920x1200 (WUXGA)  | 111      | 3.78%   |
| Unknown            | 109      | 3.71%   |
| 1366x768 (WXGA)    | 99       | 3.37%   |
| 1600x900 (HD+)     | 76       | 2.59%   |
| 1440x900 (WXGA+)   | 76       | 2.59%   |
| 2560x1080          | 53       | 1.8%    |
| 3440x1440          | 44       | 1.5%    |
| 3840x1080          | 36       | 1.22%   |
| 1360x768           | 32       | 1.09%   |
| 1024x768 (XGA)     | 31       | 1.05%   |
| 2288x1287          | 30       | 1.02%   |
| 1600x1200          | 27       | 0.92%   |
| 1920x540           | 13       | 0.44%   |
| 2560x1600          | 9        | 0.31%   |
| 4480x1440          | 8        | 0.27%   |
| 3200x1080          | 7        | 0.24%   |
| 5760x2160          | 6        | 0.2%    |
| 5760x1080          | 6        | 0.2%    |
| 1280x720 (HD)      | 6        | 0.2%    |
| 3840x1600          | 5        | 0.17%   |
| 7680x2160          | 4        | 0.14%   |
| 3840x1200          | 3        | 0.1%    |
| 3360x1050          | 3        | 0.1%    |
| 1400x1050          | 3        | 0.1%    |
| 6400x2160          | 2        | 0.07%   |
| 5760x1200          | 2        | 0.07%   |
| 5360x1440          | 2        | 0.07%   |
| 2560x1024          | 2        | 0.07%   |
| 2048x1536          | 2        | 0.07%   |
| 2048x1152          | 2        | 0.07%   |
| 1280x800 (WXGA)    | 2        | 0.07%   |
| 7680x4320          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7280x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 418      | 14.31%  |
| 27      | 373      | 12.77%  |
| 23      | 343      | 11.74%  |
| Unknown | 320      | 10.95%  |
| 21      | 281      | 9.62%   |
| 19      | 191      | 6.54%   |
| 17      | 128      | 4.38%   |
| 18      | 111      | 3.8%    |
| 22      | 102      | 3.49%   |
| 31      | 98       | 3.35%   |
| 20      | 89       | 3.05%   |
| 34      | 74       | 2.53%   |
| 15      | 65       | 2.22%   |
| 84      | 41       | 1.4%    |
| 25      | 31       | 1.06%   |
| 142     | 28       | 0.96%   |
| 72      | 25       | 0.86%   |
| 32      | 23       | 0.79%   |
| 54      | 20       | 0.68%   |
| 26      | 19       | 0.65%   |
| 40      | 17       | 0.58%   |
| 28      | 13       | 0.44%   |
| 52      | 10       | 0.34%   |
| 29      | 10       | 0.34%   |
| 48      | 7        | 0.24%   |
| 16      | 7        | 0.24%   |
| 13      | 7        | 0.24%   |
| 65      | 6        | 0.21%   |
| 39      | 6        | 0.21%   |
| 43      | 5        | 0.17%   |
| 42      | 5        | 0.17%   |
| 37      | 5        | 0.17%   |
| 35      | 5        | 0.17%   |
| 36      | 4        | 0.14%   |
| 75      | 3        | 0.1%    |
| 38      | 3        | 0.1%    |
| 33      | 3        | 0.1%    |
| 12      | 3        | 0.1%    |
| 60      | 2        | 0.07%   |
| 55      | 2        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1051     | 37.07%  |
| 401-500        | 646      | 22.79%  |
| Unknown        | 320      | 11.29%  |
| 301-350        | 187      | 6.6%    |
| 601-700        | 173      | 6.1%    |
| 351-400        | 139      | 4.9%    |
| 701-800        | 102      | 3.6%    |
| 1501-2000      | 70       | 2.47%   |
| 1001-1500      | 57       | 2.01%   |
| 801-900        | 35       | 1.23%   |
| More than 2000 | 29       | 1.02%   |
| 201-300        | 13       | 0.46%   |
| 901-1000       | 11       | 0.39%   |
| 101-200        | 2        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1608     | 58.9%   |
| 16/10   | 350      | 12.82%  |
| Unknown | 284      | 10.4%   |
| 5/4     | 241      | 8.83%   |
| 21/9    | 91       | 3.33%   |
| 4/3     | 76       | 2.78%   |
| 1.00    | 30       | 1.1%    |
| 3/2     | 24       | 0.88%   |
| 6/5     | 13       | 0.48%   |
| 32/9    | 6        | 0.22%   |
| 2.00    | 2        | 0.07%   |
| 1.96    | 2        | 0.07%   |
| 2.65    | 1        | 0.04%   |
| 11/10   | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 912      | 31.88%  |
| 301-350        | 384      | 13.42%  |
| 151-200        | 362      | 12.65%  |
| Unknown        | 320      | 11.18%  |
| 351-500        | 220      | 7.69%   |
| 141-150        | 198      | 6.92%   |
| 251-300        | 172      | 6.01%   |
| More than 1000 | 147      | 5.14%   |
| 101-110        | 55       | 1.92%   |
| 501-1000       | 52       | 1.82%   |
| 131-140        | 10       | 0.35%   |
| 111-120        | 10       | 0.35%   |
| 71-80          | 7        | 0.24%   |
| 121-130        | 5        | 0.17%   |
| 81-90          | 3        | 0.1%    |
| 1-40           | 2        | 0.07%   |
| 41-50          | 1        | 0.03%   |
| 91-100         | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1645     | 60.26%  |
| 101-120       | 462      | 16.92%  |
| Unknown       | 321      | 11.76%  |
| 121-160       | 133      | 4.87%   |
| 1-50          | 110      | 4.03%   |
| 161-240       | 56       | 2.05%   |
| More than 240 | 3        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2072     | 54.38%  |
| 0     | 1176     | 30.87%  |
| 2     | 500      | 13.12%  |
| 3     | 58       | 1.52%   |
| 4     | 4        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2296     | 45.53%  |
| Intel                             | 1529     | 30.32%  |
| Qualcomm Atheros                  | 289      | 5.73%   |
| Broadcom                          | 138      | 2.74%   |
| Ralink Technology                 | 87       | 1.73%   |
| Nvidia                            | 77       | 1.53%   |
| TP-Link                           | 54       | 1.07%   |
| Ralink                            | 41       | 0.81%   |
| MediaTek                          | 38       | 0.75%   |
| Broadcom Limited                  | 36       | 0.71%   |
| Marvell Technology Group          | 33       | 0.65%   |
| Aquantia                          | 32       | 0.63%   |
| D-Link System                     | 23       | 0.46%   |
| ASIX Electronics                  | 21       | 0.42%   |
| Mellanox Technologies             | 20       | 0.4%    |
| Samsung Electronics               | 19       | 0.38%   |
| Qualcomm Atheros Communications   | 19       | 0.38%   |
| VIA Technologies                  | 16       | 0.32%   |
| Microsoft                         | 16       | 0.32%   |
| Huawei Technologies               | 15       | 0.3%    |
| ASUSTek Computer                  | 14       | 0.28%   |
| D-Link                            | 13       | 0.26%   |
| Edimax Technology                 | 12       | 0.24%   |
| NetGear                           | 11       | 0.22%   |
| American Megatrends               | 10       | 0.2%    |
| 3Com                              | 9        | 0.18%   |
| Gemtek                            | 8        | 0.16%   |
| Xiaomi                            | 7        | 0.14%   |
| Sigma Designs                     | 7        | 0.14%   |
| Belkin Components                 | 6        | 0.12%   |
| Sundance Technology Inc / IC Plus | 5        | 0.1%    |
| IMC Networks                      | 5        | 0.1%    |
| IBM                               | 5        | 0.1%    |
| Texas Instruments                 | 4        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 4        | 0.08%   |
| QLogic                            | 4        | 0.08%   |
| Linksys                           | 4        | 0.08%   |
| Emulex                            | 4        | 0.08%   |
| Dresden Elektronik                | 4        | 0.08%   |
| DisplayLink                       | 4        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1858     | 32.91%  |
| Intel I211 Gigabit Network Connection                             | 205      | 3.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179      | 3.17%   |
| Intel Wi-Fi 6 AX200                                               | 125      | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 117      | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109      | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 109      | 1.93%   |
| Intel Ethernet Controller I225-V                                  | 87       | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 74       | 1.31%   |
| Intel I210 Gigabit Network Connection                             | 69       | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 69       | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 59       | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 52       | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 46       | 0.81%   |
| Intel Wireless 3165                                               | 44       | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 42       | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 42       | 0.74%   |
| Intel Wireless-AC 9260                                            | 41       | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 39       | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35       | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 34       | 0.6%    |
| Intel I350 Gigabit Network Connection                             | 34       | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 34       | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33       | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 33       | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 30       | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30       | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26       | 0.46%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 26       | 0.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 24       | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 23       | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23       | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23       | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23       | 0.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 23       | 0.41%   |
| Intel Wireless 7260                                               | 23       | 0.41%   |
| Realtek 802.11ac NIC                                              | 22       | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 22       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 458      | 36.94%  |
| Realtek Semiconductor                 | 250      | 20.16%  |
| Qualcomm Atheros                      | 142      | 11.45%  |
| Ralink Technology                     | 87       | 7.02%   |
| TP-Link                               | 49       | 3.95%   |
| Ralink                                | 41       | 3.31%   |
| Broadcom                              | 41       | 3.31%   |
| MediaTek                              | 35       | 2.82%   |
| Qualcomm Atheros Communications       | 19       | 1.53%   |
| ASUSTek Computer                      | 14       | 1.13%   |
| Microsoft                             | 13       | 1.05%   |
| D-Link                                | 13       | 1.05%   |
| Edimax Technology                     | 12       | 0.97%   |
| D-Link System                         | 12       | 0.97%   |
| NetGear                               | 11       | 0.89%   |
| Gemtek                                | 6        | 0.48%   |
| Belkin Components                     | 6        | 0.48%   |
| IMC Networks                          | 5        | 0.4%    |
| Broadcom Limited                      | 5        | 0.4%    |
| Linksys                               | 4        | 0.32%   |
| Wilocity                              | 2        | 0.16%   |
| Marvell Technology Group              | 2        | 0.16%   |
| AVM                                   | 2        | 0.16%   |
| ZyDAS                                 | 1        | 0.08%   |
| TRENDnet                              | 1        | 0.08%   |
| Sitecom Europe                        | 1        | 0.08%   |
| Realtek                               | 1        | 0.08%   |
| PLANEX                                | 1        | 0.08%   |
| Micro Star International              | 1        | 0.08%   |
| Fiberline                             | 1        | 0.08%   |
| Encore Electronics                    | 1        | 0.08%   |
| CyberTAN Technology                   | 1        | 0.08%   |
| BUFFALO                               | 1        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 125      | 9.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 52       | 4.16%   |
| Intel Wireless 3165                                            | 44       | 3.52%   |
| Intel Wireless-AC 9260                                         | 41       | 3.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 34       | 2.72%   |
| Ralink MT7601U Wireless Adapter                                | 33       | 2.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 30       | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26       | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 26       | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23       | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23       | 1.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 23       | 1.84%   |
| Intel Wireless 7260                                            | 23       | 1.84%   |
| Realtek 802.11ac NIC                                           | 22       | 1.76%   |
| Ralink RT5370 Wireless Adapter                                 | 22       | 1.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 20       | 1.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 18       | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 16       | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                | 16       | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15       | 1.2%    |
| Intel Wireless 8260                                            | 15       | 1.2%    |
| Intel Wireless 7265                                            | 15       | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 15       | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 13       | 1.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 13       | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13       | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13       | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 11       | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 11       | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11       | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10       | 0.8%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 10       | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9        | 0.72%   |
| Intel Wireless 8265 / 8275                                     | 9        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8        | 0.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 7        | 0.56%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 7        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2204     | 53.57%  |
| Intel                                  | 1284     | 31.21%  |
| Qualcomm Atheros                       | 160      | 3.89%   |
| Broadcom                               | 101      | 2.46%   |
| Nvidia                                 | 77       | 1.87%   |
| Marvell Technology Group               | 32       | 0.78%   |
| Aquantia                               | 32       | 0.78%   |
| Broadcom Limited                       | 31       | 0.75%   |
| ASIX Electronics                       | 21       | 0.51%   |
| Mellanox Technologies                  | 18       | 0.44%   |
| VIA Technologies                       | 16       | 0.39%   |
| Samsung Electronics                    | 14       | 0.34%   |
| D-Link System                          | 11       | 0.27%   |
| Huawei Technologies                    | 10       | 0.24%   |
| American Megatrends                    | 10       | 0.24%   |
| 3Com                                   | 9        | 0.22%   |
| Xiaomi                                 | 7        | 0.17%   |
| TP-Link                                | 5        | 0.12%   |
| Sundance Technology Inc / IC Plus      | 5        | 0.12%   |
| IBM                                    | 5        | 0.12%   |
| Silicon Integrated Systems [SiS]       | 4        | 0.1%    |
| QLogic                                 | 4        | 0.1%    |
| Emulex                                 | 4        | 0.1%    |
| DisplayLink                            | 4        | 0.1%    |
| Qualcomm                               | 3        | 0.07%   |
| OPPO Electronics                       | 3        | 0.07%   |
| Microsoft                              | 3        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.05%   |
| SysKonnect                             | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| Motorola PCS                           | 2        | 0.05%   |
| MediaTek                               | 2        | 0.05%   |
| Lenovo                                 | 2        | 0.05%   |
| JMicron Technology                     | 2        | 0.05%   |
| Insyde Software                        | 2        | 0.05%   |
| ICS Advent                             | 2        | 0.05%   |
| Google                                 | 2        | 0.05%   |
| Gemtek                                 | 2        | 0.05%   |
| ADMtek                                 | 2        | 0.05%   |
| Tehuti Networks                        | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1858     | 43.09%  |
| Intel I211 Gigabit Network Connection                             | 205      | 4.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179      | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 117      | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109      | 2.53%   |
| Intel Ethernet Connection (2) I219-V                              | 109      | 2.53%   |
| Intel Ethernet Controller I225-V                                  | 87       | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 74       | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 69       | 1.6%    |
| Intel 82579V Gigabit Network Connection                           | 69       | 1.6%    |
| Intel 82574L Gigabit Network Connection                           | 59       | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 1.18%   |
| Nvidia MCP61 Ethernet                                             | 46       | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 42       | 0.97%   |
| Intel Ethernet Connection (14) I219-V                             | 42       | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 39       | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35       | 0.81%   |
| Intel I350 Gigabit Network Connection                             | 34       | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34       | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33       | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30       | 0.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 24       | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23       | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23       | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21       | 0.49%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 19       | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 18       | 0.42%   |
| Intel Ethernet Controller X550                                    | 17       | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15       | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 15       | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15       | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15       | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14       | 0.32%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 13       | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 11       | 0.26%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 11       | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3720     | 74.95%  |
| WiFi     | 1165     | 23.47%  |
| Modem    | 69       | 1.39%   |
| Unknown  | 9        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3259     | 86.68%  |
| WiFi     | 500      | 13.3%   |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2422     | 64.23%  |
| 2     | 988      | 26.2%   |
| 3     | 212      | 5.62%   |
| 4     | 58       | 1.54%   |
| 0     | 28       | 0.74%   |
| 6     | 23       | 0.61%   |
| 5     | 20       | 0.53%   |
| 7     | 7        | 0.19%   |
| 8     | 6        | 0.16%   |
| 9     | 3        | 0.08%   |
| 21    | 1        | 0.03%   |
| 17    | 1        | 0.03%   |
| 13    | 1        | 0.03%   |
| 12    | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3211     | 84.59%  |
| Yes     | 584      | 15.38%  |
| Unknown | 1        | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 431      | 44.34%  |
| Cambridge Silicon Radio         | 214      | 22.02%  |
| ASUSTek Computer                | 70       | 7.2%    |
| Realtek Semiconductor           | 69       | 7.1%    |
| Broadcom                        | 55       | 5.66%   |
| Qualcomm Atheros Communications | 38       | 3.91%   |
| MediaTek                        | 25       | 2.57%   |
| IMC Networks                    | 22       | 2.26%   |
| Apple                           | 9        | 0.93%   |
| TP-Link                         | 8        | 0.82%   |
| Foxconn / Hon Hai               | 6        | 0.62%   |
| Belkin Components               | 4        | 0.41%   |
| Lite-On Technology              | 3        | 0.31%   |
| Integrated System Solution      | 3        | 0.31%   |
| Micro Star International        | 2        | 0.21%   |
| Edimax Technology               | 2        | 0.21%   |
| Toshiba                         | 1        | 0.1%    |
| Sitecom Europe                  | 1        | 0.1%    |
| SINO WEALTH                     | 1        | 0.1%    |
| Realtek                         | 1        | 0.1%    |
| Qcom                            | 1        | 0.1%    |
| Microsoft                       | 1        | 0.1%    |
| Kensington                      | 1        | 0.1%    |
| Hewlett-Packard                 | 1        | 0.1%    |
| Dynex                           | 1        | 0.1%    |
| Com One                         | 1        | 0.1%    |
| Unknown                         | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 214      | 21.99%  |
| Intel AX200 Bluetooth                                 | 123      | 12.64%  |
| Intel Bluetooth wireless interface                    | 106      | 10.89%  |
| Realtek Bluetooth Radio                               | 56       | 5.76%   |
| Intel Wireless-AC 3168 Bluetooth                      | 49       | 5.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 42       | 4.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 35       | 3.6%    |
| Intel AX201 Bluetooth                                 | 33       | 3.39%   |
| Intel AX210 Bluetooth                                 | 30       | 3.08%   |
| MediaTek Wireless_Device                              | 25       | 2.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 25       | 2.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 21       | 2.16%   |
| Intel Bluetooth Device                                | 18       | 1.85%   |
| Qualcomm Atheros  Bluetooth Device                    | 15       | 1.54%   |
| IMC Networks Bluetooth Radio                          | 12       | 1.23%   |
| ASUS Bluetooth Adapter                                | 11       | 1.13%   |
| ASUS Bluetooth Radio                                  | 10       | 1.03%   |
| ASUS ASUS USB-BT500                                   | 10       | 1.03%   |
| TP-Link UB500 Adapter                                 | 8        | 0.82%   |
| Realtek  Bluetooth 4.2 Adapter                        | 7        | 0.72%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 6        | 0.62%   |
| IMC Networks Bluetooth Device                         | 6        | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 5        | 0.51%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 5        | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                           | 4        | 0.41%   |
| ASUS BCM20702A0                                       | 4        | 0.41%   |
| Apple Bluetooth Host Controller                       | 4        | 0.41%   |
| Realtek RTL8821A Bluetooth                            | 3        | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3        | 0.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3        | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.31%   |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 0.31%   |
| Broadcom Bluetooth 3.0 Dongle                         | 3        | 0.31%   |
| ASUS Bluetooth Device                                 | 3        | 0.31%   |
| Realtek Bluetooth 5.1 Radio                           | 2        | 0.21%   |
| Lite-On Bluetooth Device                              | 2        | 0.21%   |
| Integrated System Solution Bluetooth Device           | 2        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2303     | 41.04%  |
| AMD                                          | 1344     | 23.95%  |
| Nvidia                                       | 1230     | 21.92%  |
| C-Media Electronics                          | 121      | 2.16%   |
| Creative Labs                                | 63       | 1.12%   |
| Logitech                                     | 59       | 1.05%   |
| ASUSTek Computer                             | 35       | 0.62%   |
| Texas Instruments                            | 25       | 0.45%   |
| GN Netcom                                    | 22       | 0.39%   |
| Generalplus Technology                       | 21       | 0.37%   |
| Micro Star International                     | 20       | 0.36%   |
| KTMicro                                      | 20       | 0.36%   |
| Focusrite-Novation                           | 19       | 0.34%   |
| VIA Technologies                             | 18       | 0.32%   |
| Kingston Technology                          | 18       | 0.32%   |
| JMTek                                        | 17       | 0.3%    |
| Creative Technology                          | 17       | 0.3%    |
| Plantronics                                  | 14       | 0.25%   |
| SteelSeries ApS                              | 11       | 0.2%    |
| Dell                                         | 11       | 0.2%    |
| Realtek Semiconductor                        | 9        | 0.16%   |
| GYROCOM C&C                                  | 9        | 0.16%   |
| BEHRINGER International                      | 9        | 0.16%   |
| RODE Microphones                             | 8        | 0.14%   |
| Corsair                                      | 8        | 0.14%   |
| Blue Microphones                             | 8        | 0.14%   |
| Razer USA                                    | 7        | 0.12%   |
| Giga-Byte Technology                         | 7        | 0.12%   |
| Yamaha                                       | 6        | 0.11%   |
| Tenx Technology                              | 5        | 0.09%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.09%   |
| Samson Technologies                          | 5        | 0.09%   |
| Microsoft                                    | 5        | 0.09%   |
| M-Audio                                      | 5        | 0.09%   |
| DSEA A/S                                     | 5        | 0.09%   |
| Cambridge Silicon Radio                      | 5        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.07%   |
| Samsung Electronics                          | 4        | 0.07%   |
| Musical Fidelity                             | 4        | 0.07%   |
| XMOS                                         | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 323      | 4.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 323      | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 269      | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 255      | 3.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 224      | 3.42%   |
| AMD Family 17h/19h HD Audio Controller                                     | 209      | 3.19%   |
| Intel 200 Series PCH HD Audio                                              | 200      | 3.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 195      | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 176      | 2.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 171      | 2.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 150      | 2.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 141      | 2.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 116      | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 107      | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 106      | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 105      | 1.6%    |
| AMD FCH Azalia Controller                                                  | 97       | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 95       | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 80       | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 80       | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 78       | 1.19%   |
| Nvidia High Definition Audio Controller                                    | 70       | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 70       | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 66       | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 63       | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 58       | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 58       | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 58       | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 58       | 0.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 57       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 56       | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 55       | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 53       | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52       | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 50       | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                              | 48       | 0.73%   |
| Nvidia MCP61 High Definition Audio                                         | 47       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 47       | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 45       | 0.69%   |
| AMD Navi 10 HDMI Audio                                                     | 45       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 664      | 19.03%  |
| Unknown                      | 557      | 15.96%  |
| Crucial                      | 397      | 11.38%  |
| Samsung Electronics          | 353      | 10.11%  |
| Corsair                      | 316      | 9.05%   |
| SK hynix                     | 288      | 8.25%   |
| G.Skill                      | 240      | 6.88%   |
| Micron Technology            | 135      | 3.87%   |
| Patriot                      | 85       | 2.44%   |
| A-DATA Technology            | 55       | 1.58%   |
| Unknown                      | 35       | 1%      |
| Team                         | 30       | 0.86%   |
| Ramaxel Technology           | 26       | 0.74%   |
| AMD                          | 24       | 0.69%   |
| Unknown (ABCD)               | 23       | 0.66%   |
| Nanya Technology             | 22       | 0.63%   |
| Hikvision                    | 21       | 0.6%    |
| Elpida                       | 19       | 0.54%   |
| Transcend                    | 17       | 0.49%   |
| Smart                        | 13       | 0.37%   |
| Apacer                       | 10       | 0.29%   |
| Hewlett-Packard              | 9        | 0.26%   |
| GOODRAM                      | 9        | 0.26%   |
| GeIL                         | 8        | 0.23%   |
| Qimonda                      | 7        | 0.2%    |
| Timetec                      | 6        | 0.17%   |
| Toshiba                      | 4        | 0.11%   |
| PNY                          | 4        | 0.11%   |
| Patriot Memory (PDP Systems) | 4        | 0.11%   |
| Avant                        | 4        | 0.11%   |
| 48spaces                     | 4        | 0.11%   |
| Unknown (AB)                 | 3        | 0.09%   |
| Unknown (0x5846)             | 3        | 0.09%   |
| Unknown (0x0B45)             | 3        | 0.09%   |
| Unifosa                      | 3        | 0.09%   |
| Silicon Power                | 3        | 0.09%   |
| OCZ                          | 3        | 0.09%   |
| Kingmax                      | 3        | 0.09%   |
| Kimtigo                      | 3        | 0.09%   |
| Goldkey                      | 3        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 48       | 1.25%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s          | 37       | 0.96%   |
| Unknown                                                        | 35       | 0.91%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 32       | 0.83%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s          | 31       | 0.8%    |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s         | 31       | 0.8%    |
| Unknown RAM Module 1GB DIMM SDRAM                              | 28       | 0.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 24       | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 24       | 0.62%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s           | 24       | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 23       | 0.6%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 22       | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 20       | 0.52%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.52%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 18       | 0.47%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 18       | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 18       | 0.47%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s            | 16       | 0.42%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.42%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 16       | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 15       | 0.39%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 15       | 0.39%   |
| Patriot RAM PSD32G13332 2048MB DIMM DDR3 1333MT/s              | 15       | 0.39%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 15       | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 14       | 0.36%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 14       | 0.36%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 14       | 0.36%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 14       | 0.36%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 14       | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.36%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 13       | 0.34%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 13       | 0.34%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 12       | 0.31%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 12       | 0.31%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 12       | 0.31%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                 | 12       | 0.31%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 12       | 0.31%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 12       | 0.31%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 12       | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1403     | 44.9%   |
| DDR3         | 1050     | 33.6%   |
| Unknown      | 223      | 7.14%   |
| DDR2         | 170      | 5.44%   |
| SDRAM        | 167      | 5.34%   |
| DDR5         | 36       | 1.15%   |
| DDR          | 36       | 1.15%   |
| LPDDR4       | 33       | 1.06%   |
| DRAM         | 5        | 0.16%   |
| LPDDR3       | 1        | 0.03%   |
| DDR2 FB-DIMM | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2799     | 90.85%  |
| SODIMM       | 250      | 8.11%   |
| Row Of Chips | 10       | 0.32%   |
| RIMM         | 9        | 0.29%   |
| FB-DIMM      | 8        | 0.26%   |
| Unknown      | 4        | 0.13%   |
| Chip         | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 1087     | 31.98%  |
| 4096    | 774      | 22.77%  |
| 16384   | 568      | 16.71%  |
| 2048    | 547      | 16.09%  |
| 32768   | 205      | 6.03%   |
| 1024    | 167      | 4.91%   |
| 512     | 36       | 1.06%   |
| 256     | 6        | 0.18%   |
| 65536   | 4        | 0.12%   |
| 128     | 2        | 0.06%   |
| 1536    | 1        | 0.03%   |
| 64      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 623      | 18.3%   |
| 1333    | 372      | 10.93%  |
| 3200    | 283      | 8.31%   |
| 2667    | 247      | 7.25%   |
| 2400    | 208      | 6.11%   |
| 3600    | 190      | 5.58%   |
| 2133    | 186      | 5.46%   |
| 800     | 153      | 4.49%   |
| Unknown | 117      | 3.44%   |
| 667     | 94       | 2.76%   |
| 1866    | 86       | 2.53%   |
| 2666    | 77       | 2.26%   |
| 1867    | 52       | 1.53%   |
| 3400    | 51       | 1.5%    |
| 3000    | 46       | 1.35%   |
| 1066    | 46       | 1.35%   |
| 2933    | 43       | 1.26%   |
| 1800    | 35       | 1.03%   |
| 3733    | 34       | 1%      |
| 4800    | 27       | 0.79%   |
| 2866    | 27       | 0.79%   |
| 1067    | 27       | 0.79%   |
| 3800    | 25       | 0.73%   |
| 3466    | 20       | 0.59%   |
| 3266    | 20       | 0.59%   |
| 3533    | 19       | 0.56%   |
| 533     | 19       | 0.56%   |
| 400     | 19       | 0.56%   |
| 4333    | 16       | 0.47%   |
| 1334    | 15       | 0.44%   |
| 3866    | 14       | 0.41%   |
| 3100    | 13       | 0.38%   |
| 3534    | 12       | 0.35%   |
| 2048    | 12       | 0.35%   |
| 3666    | 10       | 0.29%   |
| 2800    | 10       | 0.29%   |
| 3933    | 9        | 0.26%   |
| 3500    | 9        | 0.26%   |
| 1648    | 9        | 0.26%   |
| 333     | 9        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 51       | 32.08%  |
| Brother Industries    | 34       | 21.38%  |
| Canon                 | 20       | 12.58%  |
| Samsung Electronics   | 12       | 7.55%   |
| Seiko Epson           | 7        | 4.4%    |
| Dymo-CoStar           | 5        | 3.14%   |
| Zebra                 | 4        | 2.52%   |
| Prolific Technology   | 4        | 2.52%   |
| Lexmark International | 4        | 2.52%   |
| Xerox                 | 3        | 1.89%   |
| QinHeng Electronics   | 2        | 1.26%   |
| Pantum                | 2        | 1.26%   |
| Kyocera               | 2        | 1.26%   |
| STMicroelectronics    | 1        | 0.63%   |
| Ricoh                 | 1        | 0.63%   |
| Printer               | 1        | 0.63%   |
| Oki Data              | 1        | 0.63%   |
| Konica Minolta        | 1        | 0.63%   |
| GODEX INTERNATIONAL   | 1        | 0.63%   |
| Dell                  | 1        | 0.63%   |
| Datamax-O'Neil        | 1        | 0.63%   |
| Apple                 | 1        | 0.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 3.77%   |
| HP LaserJet 1200                                          | 5        | 3.14%   |
| Prolific PL2305 Parallel Port                             | 4        | 2.52%   |
| Xerox B205                                                | 3        | 1.89%   |
| Samsung ML-1660 Series                                    | 3        | 1.89%   |
| HP LaserJet M101-M106                                     | 3        | 1.89%   |
| Brother HL-52x0 series                                    | 3        | 1.89%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.26%   |
| QinHeng CH340S                                            | 2        | 1.26%   |
| Lexmark International CS417dn                             | 2        | 1.26%   |
| HP LaserJet Pro M404-M405                                 | 2        | 1.26%   |
| HP LaserJet P1005                                         | 2        | 1.26%   |
| HP LaserJet M14-M17                                       | 2        | 1.26%   |
| HP LaserJet 400 M401a                                     | 2        | 1.26%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.26%   |
| HP ENVY 4520 series                                       | 2        | 1.26%   |
| HP DeskJet 2700 series                                    | 2        | 1.26%   |
| HP DeskJet 2130 series                                    | 2        | 1.26%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.26%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.26%   |
| Canon MF4410                                              | 2        | 1.26%   |
| Brother HL-3040CN series                                  | 2        | 1.26%   |
| Brother HL-1110 series                                    | 2        | 1.26%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.63%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.63%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.63%   |
| Zebra Printer                                             | 1        | 0.63%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.63%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.63%   |
| Seiko Epson XP-15000 Series                               | 1        | 0.63%   |
| Seiko Epson Printer                                       | 1        | 0.63%   |
| Seiko Epson L6290 Series                                  | 1        | 0.63%   |
| Seiko Epson L396 Series                                   | 1        | 0.63%   |
| Seiko Epson ET-2710 Series                                | 1        | 0.63%   |
| Seiko Epson ET-2700 Series                                | 1        | 0.63%   |
| Samsung SCX-4x26 Series                                   | 1        | 0.63%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.63%   |
| Samsung SCX-4600 Series                                   | 1        | 0.63%   |
| Samsung SCX-4200 series                                   | 1        | 0.63%   |
| Samsung SCX-3400 Series                                   | 1        | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 28       | 63.64%  |
| Seiko Epson        | 8        | 18.18%  |
| Hewlett-Packard    | 4        | 9.09%   |
| AGFA-Gevaert NV    | 2        | 4.55%   |
| Ultima Electronics | 1        | 2.27%   |
| Mustek Systems     | 1        | 2.27%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 15.91%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6        | 13.64%  |
| Canon CanoScan LiDE 220                                                               | 3        | 6.82%   |
| Canon CanoScan LiDE 210                                                               | 3        | 6.82%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 4.55%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 4.55%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2.27%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 2.27%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 2.27%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2.27%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 2.27%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 2.27%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 2.27%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 2.27%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 2.27%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 2.27%   |
| HP ScanJet Pro 2500 f1                                                                | 1        | 2.27%   |
| HP ScanJet 82x0C                                                                      | 1        | 2.27%   |
| HP ScanJet 3970c                                                                      | 1        | 2.27%   |
| HP Scanjet 300                                                                        | 1        | 2.27%   |
| Canon CanoScan LiDE 60                                                                | 1        | 2.27%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 2.27%   |
| Canon CanoScan LIDE 25                                                                | 1        | 2.27%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2.27%   |
| Canon CanoScan 8800F                                                                  | 1        | 2.27%   |
| Canon CanoScan 5600F                                                                  | 1        | 2.27%   |
| Canon CanoScan 4400F                                                                  | 1        | 2.27%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 245      | 43.29%  |
| Microdia                               | 41       | 7.24%   |
| Microsoft                              | 32       | 5.65%   |
| Generalplus Technology                 | 24       | 4.24%   |
| Samsung Electronics                    | 23       | 4.06%   |
| Sunplus Innovation Technology          | 20       | 3.53%   |
| Creative Technology                    | 15       | 2.65%   |
| Jieli Technology                       | 13       | 2.3%    |
| Apple                                  | 13       | 2.3%    |
| Z-Star Microelectronics                | 11       | 1.94%   |
| KYE Systems (Mouse Systems)            | 10       | 1.77%   |
| GEMBIRD                                | 10       | 1.77%   |
| ARC International                      | 10       | 1.77%   |
| Chicony Electronics                    | 7        | 1.24%   |
| Realtek Semiconductor                  | 5        | 0.88%   |
| MacroSilicon                           | 4        | 0.71%   |
| Huawei Technologies                    | 4        | 0.71%   |
| Hewlett-Packard                        | 4        | 0.71%   |
| Genesys Logic                          | 4        | 0.71%   |
| Cubeternet                             | 4        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.71%   |
| Novatek Microelectronics               | 3        | 0.53%   |
| Google                                 | 3        | 0.53%   |
| AVerMedia Technologies                 | 3        | 0.53%   |
| Xiongmai                               | 2        | 0.35%   |
| webcam                                 | 2        | 0.35%   |
| Valve Software                         | 2        | 0.35%   |
| ValueHD                                | 2        | 0.35%   |
| Trust                                  | 2        | 0.35%   |
| Syntek                                 | 2        | 0.35%   |
| Sunplus IT                             | 2        | 0.35%   |
| Razer USA                              | 2        | 0.35%   |
| Quanta                                 | 2        | 0.35%   |
| Nintendo                               | 2        | 0.35%   |
| Aveo Technology                        | 2        | 0.35%   |
| Arkmicro Technologies                  | 2        | 0.35%   |
| Xiaomi                                 | 1        | 0.18%   |
| WaveRider Communications               | 1        | 0.18%   |
| USB3.0 HD Audio Capture                | 1        | 0.18%   |
| Unknown                                | 1        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 66       | 11.6%   |
| Logitech HD Pro Webcam C920                       | 42       | 7.38%   |
| Samsung Galaxy series, misc. (MTP mode)           | 22       | 3.87%   |
| Logitech C922 Pro Stream Webcam                   | 21       | 3.69%   |
| Generalplus GENERAL WEBCAM                        | 18       | 3.16%   |
| Microsoft LifeCam HD-3000                         | 17       | 2.99%   |
| Logitech Webcam C170                              | 15       | 2.64%   |
| Logitech HD Webcam C525                           | 15       | 2.64%   |
| Jieli USB PHY 2.0                                 | 13       | 2.28%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 13       | 2.28%   |
| Logitech Webcam C310                              | 12       | 2.11%   |
| Microdia Webcam Vitade AF                         | 11       | 1.93%   |
| Microdia CameraA                                  | 9        | 1.58%   |
| Logitech HD Webcam C910                           | 8        | 1.41%   |
| Logitech HD Webcam C615                           | 7        | 1.23%   |
| ARC International Camera                          | 7        | 1.23%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 1.05%   |
| Logitech BRIO Ultra HD Webcam                     | 6        | 1.05%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 6        | 1.05%   |
| GEMBIRD USB2.0 PC CAMERA                          | 6        | 1.05%   |
| Sunplus Full HD webcam                            | 5        | 0.88%   |
| Microdia USB 2.0 Camera                           | 5        | 0.88%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam   | 5        | 0.88%   |
| Sunplus FHD Camera Microphone                     | 4        | 0.7%    |
| Microdia Integrated Camera                        | 4        | 0.7%    |
| Microdia Camera                                   | 4        | 0.7%    |
| Logitech Webcam C925e                             | 4        | 0.7%    |
| Logitech Webcam C210                              | 4        | 0.7%    |
| KYE Systems (Mouse Systems) PC-W3 Camera          | 4        | 0.7%    |
| Huawei UVC Camera                                 | 4        | 0.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4        | 0.7%    |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 4        | 0.7%    |
| Novatek HP High Definition 2MP Webcam             | 3        | 0.53%   |
| Microsoft LifeCam VX-500 [1357]                   | 3        | 0.53%   |
| Microsoft LifeCam HD-5000                         | 3        | 0.53%   |
| Microdia Sonix USB 2.0 Camera                     | 3        | 0.53%   |
| MacroSilicon usb video                            | 3        | 0.53%   |
| Logitech Webcam Pro 9000                          | 3        | 0.53%   |
| Logitech Webcam C930e                             | 3        | 0.53%   |
| Logitech StreamCam                                | 3        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Synaptics             | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 33.33%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 6        | 15.79%  |
| Alcor Micro                | 5        | 13.16%  |
| Realtek Semiconductor      | 4        | 10.53%  |
| Gemalto (was Gemplus)      | 4        | 10.53%  |
| Clay Logic                 | 3        | 7.89%   |
| Cherry                     | 3        | 7.89%   |
| Yubico.com                 | 2        | 5.26%   |
| Reiner SCT Kartensysteme   | 2        | 5.26%   |
| Chicony Electronics        | 2        | 5.26%   |
| Aladdin Knowledge Systems  | 2        | 5.26%   |
| Advanced Card Systems      | 2        | 5.26%   |
| Lenovo                     | 1        | 2.63%   |
| Feitian Technologies       | 1        | 2.63%   |
| Athena Smartcard Solutions | 1        | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 10.53%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 10.53%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.89%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 7.89%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 5.26%   |
| Clay Logic Nitrokey Pro                                                    | 2        | 5.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 5.26%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 5.26%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 2.63%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.63%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 2.63%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.63%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.63%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.63%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.63%   |
| Feitian Technologies SCR301                                                | 1        | 2.63%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.63%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 2.63%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.63%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 2.63%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 2.63%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.63%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.63%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2442     | 64.18%  |
| 1     | 1163     | 30.57%  |
| 2     | 170      | 4.47%   |
| 3     | 22       | 0.58%   |
| 4     | 3        | 0.08%   |
| 6     | 2        | 0.05%   |
| 5     | 2        | 0.05%   |
| 7     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1054     | 70.5%   |
| Net/wireless             | 129      | 8.63%   |
| Communication controller | 76       | 5.08%   |
| Unassigned class         | 66       | 4.41%   |
| Sound                    | 29       | 1.94%   |
| Multimedia controller    | 29       | 1.94%   |
| Chipcard                 | 18       | 1.2%    |
| Bluetooth                | 18       | 1.2%    |
| Net/ethernet             | 16       | 1.07%   |
| Camera                   | 14       | 0.94%   |
| Card reader              | 11       | 0.74%   |
| Storage/raid             | 7        | 0.47%   |
| Storage/ide              | 5        | 0.33%   |
| Network                  | 5        | 0.33%   |
| Modem                    | 4        | 0.27%   |
| Dvb card                 | 4        | 0.27%   |
| Tv card                  | 3        | 0.2%    |
| Fingerprint reader       | 3        | 0.2%    |
| Storage                  | 2        | 0.13%   |
| Wireless                 | 1        | 0.07%   |
| Storage/nvme             | 1        | 0.07%   |

