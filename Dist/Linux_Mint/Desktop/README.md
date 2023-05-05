Linux Mint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 10028

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z77A-G43                    | [02c2bfee54](https://linux-hardware.org/?probe=02c2bfee54) | May 01, 2023 |
| ASUSTek       | A55M-E                      | [ee1054dc5c](https://linux-hardware.org/?probe=ee1054dc5c) | May 01, 2023 |
| ASUSTek       | PRIME J4005I-C              | [611ed4a200](https://linux-hardware.org/?probe=611ed4a200) | May 01, 2023 |
| ASRock        | Z170 Gaming K4              | [a38bf561f7](https://linux-hardware.org/?probe=a38bf561f7) | May 01, 2023 |
| ASRock        | Z170 Gaming K4              | [b5ce5ff271](https://linux-hardware.org/?probe=b5ce5ff271) | May 01, 2023 |
| MSI           | X570-A PRO                  | [4d31b88bbf](https://linux-hardware.org/?probe=4d31b88bbf) | Apr 30, 2023 |
| MSI           | X570-A PRO                  | [47a253784a](https://linux-hardware.org/?probe=47a253784a) | Apr 30, 2023 |
| Dell          | 0YF8P5 A00                  | [4f5262d2c9](https://linux-hardware.org/?probe=4f5262d2c9) | Apr 30, 2023 |
| MSI           | 760GM-P23                   | [4ac55a6bbe](https://linux-hardware.org/?probe=4ac55a6bbe) | Apr 30, 2023 |
| Gigabyte      | P75-D3                      | [4f6987c722](https://linux-hardware.org/?probe=4f6987c722) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c83cb7e3ec](https://linux-hardware.org/?probe=c83cb7e3ec) | Apr 30, 2023 |
| MSI           | H310M PRO-VD                | [c2e2e1d130](https://linux-hardware.org/?probe=c2e2e1d130) | Apr 30, 2023 |
| ASUSTek       | PRIME H410M-E               | [44a08af32f](https://linux-hardware.org/?probe=44a08af32f) | Apr 29, 2023 |
| Gigabyte      | B450 AORUS M                | [ccc2fbf8a9](https://linux-hardware.org/?probe=ccc2fbf8a9) | Apr 29, 2023 |
| Dell          | 0WR7PY A01                  | [e585f66f17](https://linux-hardware.org/?probe=e585f66f17) | Apr 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| ASRock        | Z370 Gaming K6              | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| MSI           | B85M-E45                    | [db824980e5](https://linux-hardware.org/?probe=db824980e5) | Apr 29, 2023 |
| MSI           | B85M-E45                    | [42703e0a76](https://linux-hardware.org/?probe=42703e0a76) | Apr 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [081551c776](https://linux-hardware.org/?probe=081551c776) | Apr 29, 2023 |
| ASRock        | Z370 Extreme4               | [0f126ade53](https://linux-hardware.org/?probe=0f126ade53) | Apr 29, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [425f1a3e08](https://linux-hardware.org/?probe=425f1a3e08) | Apr 29, 2023 |
| ASUSTek       | H170I-PRO                   | [b166ca425b](https://linux-hardware.org/?probe=b166ca425b) | Apr 29, 2023 |
| Gigabyte      | H410M H V2                  | [8a23a0fef0](https://linux-hardware.org/?probe=8a23a0fef0) | Apr 28, 2023 |
| ASRock        | Z790 Steel Legend WiFi      | [36175223a5](https://linux-hardware.org/?probe=36175223a5) | Apr 28, 2023 |
| HP            | 339A                        | [4f9a0b2661](https://linux-hardware.org/?probe=4f9a0b2661) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [278ed4fdd2](https://linux-hardware.org/?probe=278ed4fdd2) | Apr 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [d472fb0a32](https://linux-hardware.org/?probe=d472fb0a32) | Apr 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [c8fe6ab042](https://linux-hardware.org/?probe=c8fe6ab042) | Apr 28, 2023 |
| MSI           | B450-A PRO                  | [9f88a0a110](https://linux-hardware.org/?probe=9f88a0a110) | Apr 28, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [968f941e2d](https://linux-hardware.org/?probe=968f941e2d) | Apr 28, 2023 |
| Dell          | 040DDP A01                  | [9d7528d062](https://linux-hardware.org/?probe=9d7528d062) | Apr 28, 2023 |
| Dell          | 051FJ8 A00                  | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | 0XCR8D A01                  | [2e228e1b38](https://linux-hardware.org/?probe=2e228e1b38) | Apr 28, 2023 |
| Dell          | 0XCR8D A01                  | [395e698d44](https://linux-hardware.org/?probe=395e698d44) | Apr 27, 2023 |
| ASUSTek       | P8H67-M                     | [7bed835979](https://linux-hardware.org/?probe=7bed835979) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [a89604dccd](https://linux-hardware.org/?probe=a89604dccd) | Apr 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [64b15b4b1d](https://linux-hardware.org/?probe=64b15b4b1d) | Apr 26, 2023 |
| ASRock        | Z690M-ITX/ax                | [76674fb178](https://linux-hardware.org/?probe=76674fb178) | Apr 26, 2023 |
| Inventec      | Z CLASS A02                 | [44b6a5142e](https://linux-hardware.org/?probe=44b6a5142e) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | [7967ed6e8f](https://linux-hardware.org/?probe=7967ed6e8f) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| Dell          | 073MMW A02                  | [890ea0fd78](https://linux-hardware.org/?probe=890ea0fd78) | Apr 25, 2023 |
| MSI           | B560M PRO-VDH               | [61cdcbbe0c](https://linux-hardware.org/?probe=61cdcbbe0c) | Apr 25, 2023 |
| Gigabyte      | H61M-S2-B3                  | [cd95f8ec71](https://linux-hardware.org/?probe=cd95f8ec71) | Apr 25, 2023 |
| ASUSTek       | B85M-E                      | [135216cc27](https://linux-hardware.org/?probe=135216cc27) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [e4c737a64d](https://linux-hardware.org/?probe=e4c737a64d) | Apr 25, 2023 |
| AMD           | Inagua CRB                  | [085d0aa051](https://linux-hardware.org/?probe=085d0aa051) | Apr 24, 2023 |
| Foxconn       | ALOE                        | [f92a9cc141](https://linux-hardware.org/?probe=f92a9cc141) | Apr 24, 2023 |
| ASUSTek       | B85M-G                      | [4819635121](https://linux-hardware.org/?probe=4819635121) | Apr 24, 2023 |
| Dell          | 0VHRW1 A03                  | [6316886f98](https://linux-hardware.org/?probe=6316886f98) | Apr 24, 2023 |
| Dell          | 0D6H9T A00                  | [fa6f088b8d](https://linux-hardware.org/?probe=fa6f088b8d) | Apr 24, 2023 |
| Huanan        | X99-8M-F V1.1               | [0621d00b73](https://linux-hardware.org/?probe=0621d00b73) | Apr 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [075afa12ed](https://linux-hardware.org/?probe=075afa12ed) | Apr 23, 2023 |
| MSI           | MEG X570S ACE MAX           | [b7ab5c207b](https://linux-hardware.org/?probe=b7ab5c207b) | Apr 23, 2023 |
| HP            | 339A                        | [aa81655af9](https://linux-hardware.org/?probe=aa81655af9) | Apr 23, 2023 |
| Dell          | 09KPNV A00                  | [0ba7a36003](https://linux-hardware.org/?probe=0ba7a36003) | Apr 23, 2023 |
| Dell          | 09KPNV A00                  | [a99600dad6](https://linux-hardware.org/?probe=a99600dad6) | Apr 23, 2023 |
| Pegatron      | IPMH61P1                    | [b71d5b1a48](https://linux-hardware.org/?probe=b71d5b1a48) | Apr 23, 2023 |
| HP            | 0AA8h                       | [071191ddf3](https://linux-hardware.org/?probe=071191ddf3) | Apr 23, 2023 |
| Gigabyte      | VM900M Rev2.0               | [284ada7211](https://linux-hardware.org/?probe=284ada7211) | Apr 23, 2023 |
| PCWare        | IPX1800G2                   | [f63cf0fe51](https://linux-hardware.org/?probe=f63cf0fe51) | Apr 23, 2023 |
| ASUSTek       | B85M-E                      | [9a0f95336c](https://linux-hardware.org/?probe=9a0f95336c) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [fb4c86b0c4](https://linux-hardware.org/?probe=fb4c86b0c4) | Apr 23, 2023 |
| HP            | 0A60h                       | [e705150840](https://linux-hardware.org/?probe=e705150840) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ea9dd842c0](https://linux-hardware.org/?probe=ea9dd842c0) | Apr 22, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [ea8fb664a3](https://linux-hardware.org/?probe=ea8fb664a3) | Apr 22, 2023 |
| ASUSTek       | H81M-K                      | [5aa26aea52](https://linux-hardware.org/?probe=5aa26aea52) | Apr 22, 2023 |
| MSI           | P55-GD65                    | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| Gigabyte      | EX58-UD5                    | [1ffb09ff2a](https://linux-hardware.org/?probe=1ffb09ff2a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bb520ff82e](https://linux-hardware.org/?probe=bb520ff82e) | Apr 21, 2023 |
| Medion        | MS-7621                     | [efb8293786](https://linux-hardware.org/?probe=efb8293786) | Apr 21, 2023 |
| ASUSTek       | P5B-MX                      | [3770e032b4](https://linux-hardware.org/?probe=3770e032b4) | Apr 21, 2023 |
| Intel         | D54250WYK H13922-305        | [a7ef0d6dad](https://linux-hardware.org/?probe=a7ef0d6dad) | Apr 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1c0e6f85fe](https://linux-hardware.org/?probe=1c0e6f85fe) | Apr 21, 2023 |
| MSI           | Z97 PC Mate                 | [f1345bd185](https://linux-hardware.org/?probe=f1345bd185) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| HP            | 2215                        | [27b339efe1](https://linux-hardware.org/?probe=27b339efe1) | Apr 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [374f586992](https://linux-hardware.org/?probe=374f586992) | Apr 20, 2023 |
| Lenovo        | ThinkCentre M90p 3282B5G    | [9741f7bd1e](https://linux-hardware.org/?probe=9741f7bd1e) | Apr 20, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [69e2175961](https://linux-hardware.org/?probe=69e2175961) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A                | [4e45f9c51f](https://linux-hardware.org/?probe=4e45f9c51f) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [adb291235a](https://linux-hardware.org/?probe=adb291235a) | Apr 20, 2023 |
| ASRock        | Z97X Killer                 | [d258d06b23](https://linux-hardware.org/?probe=d258d06b23) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [8858427eed](https://linux-hardware.org/?probe=8858427eed) | Apr 19, 2023 |
| ASUSTek       | PRIME B350M-A               | [c6cd36eaed](https://linux-hardware.org/?probe=c6cd36eaed) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8afed7ed9c](https://linux-hardware.org/?probe=8afed7ed9c) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [ff7225c921](https://linux-hardware.org/?probe=ff7225c921) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [a70cdf4848](https://linux-hardware.org/?probe=a70cdf4848) | Apr 19, 2023 |
| ASUSTek       | B85M-E                      | [748e08d7c7](https://linux-hardware.org/?probe=748e08d7c7) | Apr 19, 2023 |
| MSI           | A320M-A PRO MAX             | [630a9718a0](https://linux-hardware.org/?probe=630a9718a0) | Apr 18, 2023 |
| Dell          | 0XCR8D A01                  | [c242edb3d0](https://linux-hardware.org/?probe=c242edb3d0) | Apr 18, 2023 |
| AMD           | Inagua CRB                  | [8d2ce37fca](https://linux-hardware.org/?probe=8d2ce37fca) | Apr 18, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Gigabyte      | X570 GAMING X               | [f9f95d964c](https://linux-hardware.org/?probe=f9f95d964c) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| HP            | 0A98h                       | [db84ca1038](https://linux-hardware.org/?probe=db84ca1038) | Apr 18, 2023 |
| ASUSTek       | Z170-A                      | [622b7348d0](https://linux-hardware.org/?probe=622b7348d0) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a3f477ce4a](https://linux-hardware.org/?probe=a3f477ce4a) | Apr 18, 2023 |
| ASUSTek       | B85M-G                      | [8f5803697f](https://linux-hardware.org/?probe=8f5803697f) | Apr 17, 2023 |
| Dell          | 03NVJ6 A02                  | [2b0ef62ec7](https://linux-hardware.org/?probe=2b0ef62ec7) | Apr 17, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c5ceac2597](https://linux-hardware.org/?probe=c5ceac2597) | Apr 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9df377aaf2](https://linux-hardware.org/?probe=9df377aaf2) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| MSI           | X570-A PRO                  | [65d3714b3b](https://linux-hardware.org/?probe=65d3714b3b) | Apr 17, 2023 |
| Biostar       | TA880GU3+                   | [ee629553e7](https://linux-hardware.org/?probe=ee629553e7) | Apr 17, 2023 |
| Biostar       | TA880GU3+                   | [3553ce4185](https://linux-hardware.org/?probe=3553ce4185) | Apr 17, 2023 |
| ASUSTek       | P5Q DELUXE                  | [ebd62c0513](https://linux-hardware.org/?probe=ebd62c0513) | Apr 16, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [67ce5b3ab1](https://linux-hardware.org/?probe=67ce5b3ab1) | Apr 16, 2023 |
| Gigabyte      | Z170-Gaming K3              | [c31465c0a1](https://linux-hardware.org/?probe=c31465c0a1) | Apr 16, 2023 |
| Dell          | 0GM819                      | [b462ba5afe](https://linux-hardware.org/?probe=b462ba5afe) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [fec4fc20a6](https://linux-hardware.org/?probe=fec4fc20a6) | Apr 16, 2023 |
| AZW           | Speed S                     | [7cf5e54f5b](https://linux-hardware.org/?probe=7cf5e54f5b) | Apr 16, 2023 |
| MSI           | PRO H610M-B DDR4            | [65b2e4afa9](https://linux-hardware.org/?probe=65b2e4afa9) | Apr 16, 2023 |
| Intel         | DH61WW AAG23116-204         | [6c62f23970](https://linux-hardware.org/?probe=6c62f23970) | Apr 16, 2023 |
| ASRock        | Z270 Extreme4               | [c388675553](https://linux-hardware.org/?probe=c388675553) | Apr 16, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [41cef8b51c](https://linux-hardware.org/?probe=41cef8b51c) | Apr 16, 2023 |
| HP            | 212B                        | [343f1f5eba](https://linux-hardware.org/?probe=343f1f5eba) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [3fb8069a1b](https://linux-hardware.org/?probe=3fb8069a1b) | Apr 16, 2023 |
| HP            | 8055                        | [7e5328ded9](https://linux-hardware.org/?probe=7e5328ded9) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [76db4c685b](https://linux-hardware.org/?probe=76db4c685b) | Apr 15, 2023 |
| Gigabyte      | H97-Gaming 3                | [d7d0bcde76](https://linux-hardware.org/?probe=d7d0bcde76) | Apr 15, 2023 |
| HP            | 3048h                       | [c771c0b0a7](https://linux-hardware.org/?probe=c771c0b0a7) | Apr 15, 2023 |
| AMD           | A88F2EKS                    | [48cef621bd](https://linux-hardware.org/?probe=48cef621bd) | Apr 15, 2023 |
| ASUSTek       | PRIME Z490-A                | [17c0e1e6e4](https://linux-hardware.org/?probe=17c0e1e6e4) | Apr 15, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [dd2d3443a9](https://linux-hardware.org/?probe=dd2d3443a9) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [00ee6cd73f](https://linux-hardware.org/?probe=00ee6cd73f) | Apr 15, 2023 |
| Dell          | 0KWVT8 A01                  | [38d4552d7e](https://linux-hardware.org/?probe=38d4552d7e) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | [9d18bebcd7](https://linux-hardware.org/?probe=9d18bebcd7) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [21091d13e4](https://linux-hardware.org/?probe=21091d13e4) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | [921a57413c](https://linux-hardware.org/?probe=921a57413c) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [d78a3541af](https://linux-hardware.org/?probe=d78a3541af) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e5b11f4136](https://linux-hardware.org/?probe=e5b11f4136) | Apr 14, 2023 |
| Dell          | 00V62H A01                  | [a06e8fe70f](https://linux-hardware.org/?probe=a06e8fe70f) | Apr 14, 2023 |
| Gateway       | FX6860                      | [b3de61f1b3](https://linux-hardware.org/?probe=b3de61f1b3) | Apr 14, 2023 |
| Medion        | MS-7857                     | [5d04997966](https://linux-hardware.org/?probe=5d04997966) | Apr 14, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| PCWare        | IPMH61R3                    | [776a2824c5](https://linux-hardware.org/?probe=776a2824c5) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | [7f4d0d2d91](https://linux-hardware.org/?probe=7f4d0d2d91) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | [f3114cd0d7](https://linux-hardware.org/?probe=f3114cd0d7) | Apr 14, 2023 |
| OEM           | H110                        | [60e8c50cdd](https://linux-hardware.org/?probe=60e8c50cdd) | Apr 14, 2023 |
| ASUSTek       | PRIME B450M-K II            | [9055d69d2f](https://linux-hardware.org/?probe=9055d69d2f) | Apr 14, 2023 |
| MSI           | A320M-A PRO MAX             | [3a30c05322](https://linux-hardware.org/?probe=3a30c05322) | Apr 13, 2023 |
| Cincoze       | DX-1000.01.001              | [fa2c48478a](https://linux-hardware.org/?probe=fa2c48478a) | Apr 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3aaeeb54ca](https://linux-hardware.org/?probe=3aaeeb54ca) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| Shuttle       | FH67                        | [daa2f39981](https://linux-hardware.org/?probe=daa2f39981) | Apr 13, 2023 |
| OEM           | Intel H81                   | [1a73452d73](https://linux-hardware.org/?probe=1a73452d73) | Apr 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [eecb8d6e08](https://linux-hardware.org/?probe=eecb8d6e08) | Apr 13, 2023 |
| ASUSTek       | M2N68-AM SE2                | [e9b6076df4](https://linux-hardware.org/?probe=e9b6076df4) | Apr 13, 2023 |
| MSI           | B550M PRO-VDH               | [0d0a704eae](https://linux-hardware.org/?probe=0d0a704eae) | Apr 12, 2023 |
| ASUSTek       | M4A87TD EVO                 | [695de52123](https://linux-hardware.org/?probe=695de52123) | Apr 12, 2023 |
| HP            | 843B                        | [90de5c4ff1](https://linux-hardware.org/?probe=90de5c4ff1) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | [87d43c1f1d](https://linux-hardware.org/?probe=87d43c1f1d) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | [a291f82fe3](https://linux-hardware.org/?probe=a291f82fe3) | Apr 12, 2023 |
| ASRock        | A320M-HDV R4.0              | [8eaf410d51](https://linux-hardware.org/?probe=8eaf410d51) | Apr 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | [38d6c9f7ab](https://linux-hardware.org/?probe=38d6c9f7ab) | Apr 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [fcb884a8aa](https://linux-hardware.org/?probe=fcb884a8aa) | Apr 11, 2023 |
| Gigabyte      | B75-D3V                     | [fe025c9491](https://linux-hardware.org/?probe=fe025c9491) | Apr 11, 2023 |
| ASRock        | B550M-HDV                   | [b10bf3690e](https://linux-hardware.org/?probe=b10bf3690e) | Apr 11, 2023 |
| HP            | 2AF7                        | [e9621d5a9c](https://linux-hardware.org/?probe=e9621d5a9c) | Apr 11, 2023 |
| HP            | 2AF7                        | [b187733415](https://linux-hardware.org/?probe=b187733415) | Apr 11, 2023 |
| MSI           | MEG X570S ACE MAX           | [22e5416847](https://linux-hardware.org/?probe=22e5416847) | Apr 11, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [7ddf3af042](https://linux-hardware.org/?probe=7ddf3af042) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS M                | [e6f7aa90ab](https://linux-hardware.org/?probe=e6f7aa90ab) | Apr 11, 2023 |
| HP            | 18E4                        | [73b6760737](https://linux-hardware.org/?probe=73b6760737) | Apr 11, 2023 |
| Gigabyte      | X570 GAMING X               | [761450c579](https://linux-hardware.org/?probe=761450c579) | Apr 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [1a470a3b5a](https://linux-hardware.org/?probe=1a470a3b5a) | Apr 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [cd7d44fb7f](https://linux-hardware.org/?probe=cd7d44fb7f) | Apr 10, 2023 |
| Gigabyte      | A520I AC                    | [32867fa30e](https://linux-hardware.org/?probe=32867fa30e) | Apr 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [249b3e78ed](https://linux-hardware.org/?probe=249b3e78ed) | Apr 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [8d36d0bfeb](https://linux-hardware.org/?probe=8d36d0bfeb) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | [1f8dc6aa3d](https://linux-hardware.org/?probe=1f8dc6aa3d) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | [ff595db737](https://linux-hardware.org/?probe=ff595db737) | Apr 09, 2023 |
| AMI           | Cherry Trail CR             | [58dea5f209](https://linux-hardware.org/?probe=58dea5f209) | Apr 08, 2023 |
| ASUSTek       | P8H77-M PRO                 | [c8b30dba27](https://linux-hardware.org/?probe=c8b30dba27) | Apr 08, 2023 |
| OEM           | X99-Turbo                   | [52723223af](https://linux-hardware.org/?probe=52723223af) | Apr 08, 2023 |
| ASUSTek       | M5A78L-M LX3                | [5125228dd1](https://linux-hardware.org/?probe=5125228dd1) | Apr 08, 2023 |
| ASRock        | X79 Extreme6                | [2b3f00ac79](https://linux-hardware.org/?probe=2b3f00ac79) | Apr 08, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [269e742eb7](https://linux-hardware.org/?probe=269e742eb7) | Apr 08, 2023 |
| Acer          | Aspire XC-895 V:1.0         | [ef0fbbe0aa](https://linux-hardware.org/?probe=ef0fbbe0aa) | Apr 08, 2023 |
| Dell          | 096JG8 A01                  | [9f5a3611b8](https://linux-hardware.org/?probe=9f5a3611b8) | Apr 07, 2023 |
| Dell          | 0P01GV A03                  | [5dc44169d0](https://linux-hardware.org/?probe=5dc44169d0) | Apr 07, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11edc2be88](https://linux-hardware.org/?probe=11edc2be88) | Apr 06, 2023 |
| Acer          | Aspire M1930                | [2bc158bf57](https://linux-hardware.org/?probe=2bc158bf57) | Apr 06, 2023 |
| MSI           | B350M MORTAR                | [d066d75bd5](https://linux-hardware.org/?probe=d066d75bd5) | Apr 06, 2023 |
| MSI           | B350M MORTAR                | [6248298b60](https://linux-hardware.org/?probe=6248298b60) | Apr 06, 2023 |
| MSI           | MEG X570S ACE MAX           | [57505ad220](https://linux-hardware.org/?probe=57505ad220) | Apr 06, 2023 |
| MSI           | MEG X570S ACE MAX           | [f3703c6b73](https://linux-hardware.org/?probe=f3703c6b73) | Apr 06, 2023 |
| Lenovo        | 3111 NOK                    | [4553102bca](https://linux-hardware.org/?probe=4553102bca) | Apr 06, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [a0c75732ae](https://linux-hardware.org/?probe=a0c75732ae) | Apr 06, 2023 |
| AZW           | Green G3                    | [8e35f00a16](https://linux-hardware.org/?probe=8e35f00a16) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [d8d9dd75ba](https://linux-hardware.org/?probe=d8d9dd75ba) | Apr 05, 2023 |
| ASUSTek       | PRIME B560M-A               | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| BESSTAR Te... | UM350                       | [ccff8e1838](https://linux-hardware.org/?probe=ccff8e1838) | Apr 05, 2023 |
| ASUSTek       | B150 PRO GAMING D3          | [dd17fef419](https://linux-hardware.org/?probe=dd17fef419) | Apr 05, 2023 |
| Shenzhen M... | F7BFC                       | [41f564b960](https://linux-hardware.org/?probe=41f564b960) | Apr 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [01f2e4a69f](https://linux-hardware.org/?probe=01f2e4a69f) | Apr 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [45bcedba86](https://linux-hardware.org/?probe=45bcedba86) | Apr 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f08ea6ee04](https://linux-hardware.org/?probe=f08ea6ee04) | Apr 04, 2023 |
| HP            | 8455                        | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [3588278a4b](https://linux-hardware.org/?probe=3588278a4b) | Apr 04, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b48fc24a31](https://linux-hardware.org/?probe=b48fc24a31) | Apr 04, 2023 |
| Dell          | 0VHWTR A02                  | [64ca43bef0](https://linux-hardware.org/?probe=64ca43bef0) | Apr 04, 2023 |
| Dell          | 0VHWTR A02                  | [ac36b6f948](https://linux-hardware.org/?probe=ac36b6f948) | Apr 04, 2023 |
| Dell          | 0GX297                      | [5d1513fb01](https://linux-hardware.org/?probe=5d1513fb01) | Apr 04, 2023 |
| Dell          | 0D6H9T A00                  | [2bedb15c21](https://linux-hardware.org/?probe=2bedb15c21) | Apr 04, 2023 |
| Gateway       | SX2803                      | [63c99108ee](https://linux-hardware.org/?probe=63c99108ee) | Apr 04, 2023 |
| Dell          | 0GX297                      | [80c6b0b4f3](https://linux-hardware.org/?probe=80c6b0b4f3) | Apr 04, 2023 |
| HP            | 843B                        | [aa679005d3](https://linux-hardware.org/?probe=aa679005d3) | Apr 04, 2023 |
| HP            | 843B                        | [ba686ac542](https://linux-hardware.org/?probe=ba686ac542) | Apr 04, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [60f7987af4](https://linux-hardware.org/?probe=60f7987af4) | Apr 04, 2023 |
| ASUSTek       | H110M-C                     | [5995f1c96e](https://linux-hardware.org/?probe=5995f1c96e) | Apr 03, 2023 |
| ASUSTek       | H110M-C                     | [b9f944ed6e](https://linux-hardware.org/?probe=b9f944ed6e) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7c95c976a9](https://linux-hardware.org/?probe=7c95c976a9) | Apr 03, 2023 |
| HP            | 81B4                        | [fc738fe6b9](https://linux-hardware.org/?probe=fc738fe6b9) | Apr 03, 2023 |
| MSI           | A68HM-E33 V2                | [49b2ac9ff5](https://linux-hardware.org/?probe=49b2ac9ff5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e33abdae24](https://linux-hardware.org/?probe=e33abdae24) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9f9f72230c](https://linux-hardware.org/?probe=9f9f72230c) | Apr 03, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [73c4ac4e04](https://linux-hardware.org/?probe=73c4ac4e04) | Apr 03, 2023 |
| Intel         | DG41TY AAE47335-302         | [ecd1f451f0](https://linux-hardware.org/?probe=ecd1f451f0) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fb4f4da720](https://linux-hardware.org/?probe=fb4f4da720) | Apr 03, 2023 |
| Dell          | 055H3G A01                  | [d2f5e578ee](https://linux-hardware.org/?probe=d2f5e578ee) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a225e27910](https://linux-hardware.org/?probe=a225e27910) | Apr 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4f7c23a4ef](https://linux-hardware.org/?probe=4f7c23a4ef) | Apr 02, 2023 |
| MSI           | PRO Z690-A DDR4             | [1e43e50ed5](https://linux-hardware.org/?probe=1e43e50ed5) | Apr 02, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [6bac6aa095](https://linux-hardware.org/?probe=6bac6aa095) | Apr 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [77b1f3bc3e](https://linux-hardware.org/?probe=77b1f3bc3e) | Apr 02, 2023 |
| MSI           | A320M PRO-VD/S V2           | [5380352186](https://linux-hardware.org/?probe=5380352186) | Apr 02, 2023 |
| HP            | 843F                        | [1b656afe5b](https://linux-hardware.org/?probe=1b656afe5b) | Apr 02, 2023 |
| ASRock        | FM2A55M-DGS                 | [250384a794](https://linux-hardware.org/?probe=250384a794) | Apr 02, 2023 |
| Gigabyte      | EP45T-DS3                   | [9639c79ad5](https://linux-hardware.org/?probe=9639c79ad5) | Apr 02, 2023 |
| ASUSTek       | H110M-R                     | [589fd53791](https://linux-hardware.org/?probe=589fd53791) | Apr 02, 2023 |
| Gigabyte      | Z97-HD3                     | [eaa3b673a1](https://linux-hardware.org/?probe=eaa3b673a1) | Apr 01, 2023 |
| Unknown       | Unknown                     | [fdd5cd8cd8](https://linux-hardware.org/?probe=fdd5cd8cd8) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [c56a58c833](https://linux-hardware.org/?probe=c56a58c833) | Apr 01, 2023 |
| MSI           | 970A-G46                    | [92ee520881](https://linux-hardware.org/?probe=92ee520881) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| Biostar       | A740G M2+                   | [182d84f68a](https://linux-hardware.org/?probe=182d84f68a) | Apr 01, 2023 |
| Acer          | H11H4-AI V:1.0              | [d5337ce0e3](https://linux-hardware.org/?probe=d5337ce0e3) | Apr 01, 2023 |
| AZW           | Green G3                    | [a987d9a5c1](https://linux-hardware.org/?probe=a987d9a5c1) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [e9fe5cb307](https://linux-hardware.org/?probe=e9fe5cb307) | Apr 01, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d80d075b91](https://linux-hardware.org/?probe=d80d075b91) | Apr 01, 2023 |
| HP            | 18E7                        | [98319f4504](https://linux-hardware.org/?probe=98319f4504) | Apr 01, 2023 |
| Dell          | 0GY6Y8 A03                  | [7754565ec1](https://linux-hardware.org/?probe=7754565ec1) | Apr 01, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | [672242513c](https://linux-hardware.org/?probe=672242513c) | Mar 31, 2023 |
| ASUSTek       | A58M-A/BR                   | [90724dc86e](https://linux-hardware.org/?probe=90724dc86e) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [871b458080](https://linux-hardware.org/?probe=871b458080) | Mar 31, 2023 |
| Gigabyte      | B450 GAMING X               | [495c58a5c6](https://linux-hardware.org/?probe=495c58a5c6) | Mar 31, 2023 |
| Gigabyte      | A320M-S2H-CF                | [1c982255fa](https://linux-hardware.org/?probe=1c982255fa) | Mar 31, 2023 |
| ASRock        | FM2A55M-DGS                 | [3ab2e2c720](https://linux-hardware.org/?probe=3ab2e2c720) | Mar 31, 2023 |
| Gigabyte      | B460M AORUS ELITE           | [87145cd4b2](https://linux-hardware.org/?probe=87145cd4b2) | Mar 31, 2023 |
| ASRock        | A320M-HDV R4.0              | [f5e2675cdd](https://linux-hardware.org/?probe=f5e2675cdd) | Mar 30, 2023 |
| HP            | 339A                        | [8f484ab259](https://linux-hardware.org/?probe=8f484ab259) | Mar 30, 2023 |
| Foxconn       | ETON                        | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| ECS           | H81H3-WM                    | [cbf3d55d63](https://linux-hardware.org/?probe=cbf3d55d63) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | [1e3ec03234](https://linux-hardware.org/?probe=1e3ec03234) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | [fe068bd78d](https://linux-hardware.org/?probe=fe068bd78d) | Mar 30, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [936e8b10c5](https://linux-hardware.org/?probe=936e8b10c5) | Mar 30, 2023 |
| MSI           | B550-A PRO                  | [b4a4247459](https://linux-hardware.org/?probe=b4a4247459) | Mar 29, 2023 |
| ASUSTek       | M4A79 Deluxe                | [59c5a88b80](https://linux-hardware.org/?probe=59c5a88b80) | Mar 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7483952d78](https://linux-hardware.org/?probe=7483952d78) | Mar 29, 2023 |
| Lenovo        | 3111 NOK                    | [f6004f6817](https://linux-hardware.org/?probe=f6004f6817) | Mar 29, 2023 |
| ASUSTek       | P7P55D-E                    | [3db646f782](https://linux-hardware.org/?probe=3db646f782) | Mar 29, 2023 |
| ASRock        | B550M Pro4                  | [a78f53a6b4](https://linux-hardware.org/?probe=a78f53a6b4) | Mar 29, 2023 |
| ASRock        | B550M Pro4                  | [a4c3b109dc](https://linux-hardware.org/?probe=a4c3b109dc) | Mar 29, 2023 |
| HP            | 806A                        | [477b1e2d83](https://linux-hardware.org/?probe=477b1e2d83) | Mar 29, 2023 |
| Daten Tecn... | DQ77PRO                     | [86885bfc03](https://linux-hardware.org/?probe=86885bfc03) | Mar 29, 2023 |
| Lenovo        | 3111 NOK                    | [6ef94ade27](https://linux-hardware.org/?probe=6ef94ade27) | Mar 29, 2023 |
| HOUTER        | IPMH61R1                    | [bcabc2573c](https://linux-hardware.org/?probe=bcabc2573c) | Mar 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| Acer          | H11H4-AI V:1.0              | [4266c0287d](https://linux-hardware.org/?probe=4266c0287d) | Mar 29, 2023 |
| HP            | 3398                        | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| HP            | 0AACh                       | [43dbfddd1b](https://linux-hardware.org/?probe=43dbfddd1b) | Mar 28, 2023 |
| Gigabyte      | X58A-UD3R                   | [74d9c5e704](https://linux-hardware.org/?probe=74d9c5e704) | Mar 28, 2023 |
| ASUSTek       | A88XM-A                     | [405e95a907](https://linux-hardware.org/?probe=405e95a907) | Mar 28, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c9e155f84](https://linux-hardware.org/?probe=9c9e155f84) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [611b42e6fd](https://linux-hardware.org/?probe=611b42e6fd) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | H110-PLUS                   | [b108ebc14f](https://linux-hardware.org/?probe=b108ebc14f) | Mar 27, 2023 |
| Dell          | 0200DY A02                  | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [9f3138d8d5](https://linux-hardware.org/?probe=9f3138d8d5) | Mar 27, 2023 |
| ASRock        | AM1B-ITX                    | [e5dc5f70ac](https://linux-hardware.org/?probe=e5dc5f70ac) | Mar 27, 2023 |
| ASUSTek       | N3150I-C                    | [6c977806a1](https://linux-hardware.org/?probe=6c977806a1) | Mar 27, 2023 |
| MSI           | PRO B660-A DDR4             | [6a882b7826](https://linux-hardware.org/?probe=6a882b7826) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [922d8a7941](https://linux-hardware.org/?probe=922d8a7941) | Mar 26, 2023 |
| Gigabyte      | MRHM3AP                     | [27ac802035](https://linux-hardware.org/?probe=27ac802035) | Mar 26, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [ae3d30a042](https://linux-hardware.org/?probe=ae3d30a042) | Mar 26, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [b31a6f01f6](https://linux-hardware.org/?probe=b31a6f01f6) | Mar 26, 2023 |
| MSI           | A68HM-E33 V2                | [1531761af6](https://linux-hardware.org/?probe=1531761af6) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [9aa3215de8](https://linux-hardware.org/?probe=9aa3215de8) | Mar 26, 2023 |
| ASUSTek       | M2N68-AM Plus               | [e274c03773](https://linux-hardware.org/?probe=e274c03773) | Mar 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [74cf067852](https://linux-hardware.org/?probe=74cf067852) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [129c2be9aa](https://linux-hardware.org/?probe=129c2be9aa) | Mar 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [83fb0eaf6e](https://linux-hardware.org/?probe=83fb0eaf6e) | Mar 26, 2023 |
| HP            | 0B54h D                     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII GENE           | [71ba42d727](https://linux-hardware.org/?probe=71ba42d727) | Mar 25, 2023 |
| ASUSTek       | Maximus VIII GENE           | [33ba03aebe](https://linux-hardware.org/?probe=33ba03aebe) | Mar 25, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [8f04388ab5](https://linux-hardware.org/?probe=8f04388ab5) | Mar 25, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [cb325c06e8](https://linux-hardware.org/?probe=cb325c06e8) | Mar 25, 2023 |
| MSI           | H81M-P33                    | [0944bc82b9](https://linux-hardware.org/?probe=0944bc82b9) | Mar 25, 2023 |
| MSI           | PRO B660-A DDR4             | [ef9408ce57](https://linux-hardware.org/?probe=ef9408ce57) | Mar 25, 2023 |
| Intel         | D2700DC AAG32420-602        | [0d20e81321](https://linux-hardware.org/?probe=0d20e81321) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| MSI           | MEG X570S ACE MAX           | [3a32e79b17](https://linux-hardware.org/?probe=3a32e79b17) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [d5d190db2f](https://linux-hardware.org/?probe=d5d190db2f) | Mar 25, 2023 |
| AZW           | Green G3                    | [a0789502ab](https://linux-hardware.org/?probe=a0789502ab) | Mar 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [1cafadad17](https://linux-hardware.org/?probe=1cafadad17) | Mar 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [38cead30d5](https://linux-hardware.org/?probe=38cead30d5) | Mar 25, 2023 |
| AZW           | Green G3                    | [7dcacb9c15](https://linux-hardware.org/?probe=7dcacb9c15) | Mar 24, 2023 |
| HP            | 0AACh                       | [2a1f96ca8d](https://linux-hardware.org/?probe=2a1f96ca8d) | Mar 24, 2023 |
| ASUSTek       | M4A78T-E                    | [a820ffe411](https://linux-hardware.org/?probe=a820ffe411) | Mar 24, 2023 |
| Dell          | 040DDP A01                  | [0d62bf0ea8](https://linux-hardware.org/?probe=0d62bf0ea8) | Mar 24, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [5fccdb098d](https://linux-hardware.org/?probe=5fccdb098d) | Mar 24, 2023 |
| Gigabyte      | H170-D3H-CF                 | [0bcd7ee5e8](https://linux-hardware.org/?probe=0bcd7ee5e8) | Mar 24, 2023 |
| HP            | 304Ah                       | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| ASUSTek       | H110M-E/M.2                 | [177089e2e0](https://linux-hardware.org/?probe=177089e2e0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [81273bd2b0](https://linux-hardware.org/?probe=81273bd2b0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2db2fb4a5a](https://linux-hardware.org/?probe=2db2fb4a5a) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [79cbdbc9c1](https://linux-hardware.org/?probe=79cbdbc9c1) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [ec6fdc917b](https://linux-hardware.org/?probe=ec6fdc917b) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [9d4137f8ea](https://linux-hardware.org/?probe=9d4137f8ea) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| MSI           | A68HM-E33 V2                | [973daceeaa](https://linux-hardware.org/?probe=973daceeaa) | Mar 23, 2023 |
| Intel         | DH87RL AAG74240-401         | [3465e562e8](https://linux-hardware.org/?probe=3465e562e8) | Mar 23, 2023 |
| ASUSTek       | P5KC                        | [3c4c536325](https://linux-hardware.org/?probe=3c4c536325) | Mar 23, 2023 |
| ASUSTek       | PRIME H510M-E               | [fc5894dcb4](https://linux-hardware.org/?probe=fc5894dcb4) | Mar 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [ea6d900647](https://linux-hardware.org/?probe=ea6d900647) | Mar 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [86d12b640c](https://linux-hardware.org/?probe=86d12b640c) | Mar 23, 2023 |
| MSI           | MEG X570S ACE MAX           | [528ed2d3af](https://linux-hardware.org/?probe=528ed2d3af) | Mar 23, 2023 |
| MSI           | A68HM-E33 V2                | [2b00f56890](https://linux-hardware.org/?probe=2b00f56890) | Mar 23, 2023 |
| ASUSTek       | H110M-E/M.2                 | [78b4f9cbbd](https://linux-hardware.org/?probe=78b4f9cbbd) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0c587f1f7f](https://linux-hardware.org/?probe=0c587f1f7f) | Mar 22, 2023 |
| Acer          | Aspire M1930                | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Lenovo        | ThinkStation S20 4157E92    | [db2bde56b1](https://linux-hardware.org/?probe=db2bde56b1) | Mar 22, 2023 |
| Unknown       | Unknown                     | [de1dd4e459](https://linux-hardware.org/?probe=de1dd4e459) | Mar 22, 2023 |
| Unknown       | Unknown                     | [33ebf18165](https://linux-hardware.org/?probe=33ebf18165) | Mar 22, 2023 |
| MSI           | MEG X570 ACE                | [c2bab115eb](https://linux-hardware.org/?probe=c2bab115eb) | Mar 22, 2023 |
| Gigabyte      | B150M-D3H-CF                | [866008d461](https://linux-hardware.org/?probe=866008d461) | Mar 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2e6307252f](https://linux-hardware.org/?probe=2e6307252f) | Mar 22, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [8c50d5ae87](https://linux-hardware.org/?probe=8c50d5ae87) | Mar 21, 2023 |
| Dell          | 0XCR8D A00                  | [e86eb83730](https://linux-hardware.org/?probe=e86eb83730) | Mar 21, 2023 |
| Gigabyte      | Z77X-D3H                    | [aab84f14ed](https://linux-hardware.org/?probe=aab84f14ed) | Mar 21, 2023 |
| ASUSTek       | A68HM-K                     | [7c5033ad07](https://linux-hardware.org/?probe=7c5033ad07) | Mar 20, 2023 |
| Dell          | 03NVJ6 A01                  | [2060b57720](https://linux-hardware.org/?probe=2060b57720) | Mar 20, 2023 |
| Medion        | MS-7797                     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e897657a4e](https://linux-hardware.org/?probe=e897657a4e) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| Dell          | 0KWVT8 A00                  | [b15061e252](https://linux-hardware.org/?probe=b15061e252) | Mar 20, 2023 |
| HP            | 18E9                        | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [db7d70cd41](https://linux-hardware.org/?probe=db7d70cd41) | Mar 20, 2023 |
| ASUSTek       | Maximus Extreme             | [c6215ec2f3](https://linux-hardware.org/?probe=c6215ec2f3) | Mar 20, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [42290142fb](https://linux-hardware.org/?probe=42290142fb) | Mar 19, 2023 |
| HP            | 806A                        | [573fdc1908](https://linux-hardware.org/?probe=573fdc1908) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3500d84a8e](https://linux-hardware.org/?probe=3500d84a8e) | Mar 19, 2023 |
| ASRock        | B450M Pro4                  | [81e36f47be](https://linux-hardware.org/?probe=81e36f47be) | Mar 19, 2023 |
| MSI           | PRO B660M-A DDR4            | [149e050820](https://linux-hardware.org/?probe=149e050820) | Mar 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | [fdedfdf220](https://linux-hardware.org/?probe=fdedfdf220) | Mar 19, 2023 |
| Dell          | 0HY9JP A00                  | [3d56af3ce1](https://linux-hardware.org/?probe=3d56af3ce1) | Mar 19, 2023 |
| HP            | 0AA8h                       | [fecbec6708](https://linux-hardware.org/?probe=fecbec6708) | Mar 19, 2023 |
| Dell          | 0KWVT8 A03                  | [06cc7499e0](https://linux-hardware.org/?probe=06cc7499e0) | Mar 19, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [6e6c326058](https://linux-hardware.org/?probe=6e6c326058) | Mar 18, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [1a93d601d7](https://linux-hardware.org/?probe=1a93d601d7) | Mar 18, 2023 |
| Gigabyte      | 990FXA-UD7                  | [faab19eb56](https://linux-hardware.org/?probe=faab19eb56) | Mar 18, 2023 |
| Intel         | DP55WB AAE64798-205         | [a76d46bf92](https://linux-hardware.org/?probe=a76d46bf92) | Mar 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| Foxconn       | ALOE                        | [5b3b117c06](https://linux-hardware.org/?probe=5b3b117c06) | Mar 18, 2023 |
| Gigabyte      | GB-BRR7H-4800               | [5a70cf923e](https://linux-hardware.org/?probe=5a70cf923e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [d7d5c10d9b](https://linux-hardware.org/?probe=d7d5c10d9b) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| AZW           | U59                         | [76be282df9](https://linux-hardware.org/?probe=76be282df9) | Mar 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | [cd8dd26e2d](https://linux-hardware.org/?probe=cd8dd26e2d) | Mar 17, 2023 |
| Gigabyte      | B450 AORUS M                | [79a285d86b](https://linux-hardware.org/?probe=79a285d86b) | Mar 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [4f8bd2d95e](https://linux-hardware.org/?probe=4f8bd2d95e) | Mar 17, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Positivo      | POS-EIH61CE SIM             | [19a69ab150](https://linux-hardware.org/?probe=19a69ab150) | Mar 17, 2023 |
| AMI           | Intel                       | [491d2cca9d](https://linux-hardware.org/?probe=491d2cca9d) | Mar 17, 2023 |
| Gigabyte      | Z68A-D3H-B3                 | [dfd6e0e620](https://linux-hardware.org/?probe=dfd6e0e620) | Mar 17, 2023 |
| Dell          | 0T10XW A00                  | [ba56245418](https://linux-hardware.org/?probe=ba56245418) | Mar 17, 2023 |
| AZW           | Green G3                    | [cabe11ead0](https://linux-hardware.org/?probe=cabe11ead0) | Mar 17, 2023 |
| ASRock        | FM2A88X+ BTC                | [a9b10b44a8](https://linux-hardware.org/?probe=a9b10b44a8) | Mar 17, 2023 |
| ASRock        | FM2A88X+ BTC                | [45c8edfa30](https://linux-hardware.org/?probe=45c8edfa30) | Mar 17, 2023 |
| ASRock        | B450M Pro4                  | [a0fd9e4138](https://linux-hardware.org/?probe=a0fd9e4138) | Mar 16, 2023 |
| Inventec      | D CLASS A02                 | [6b0555ac0f](https://linux-hardware.org/?probe=6b0555ac0f) | Mar 16, 2023 |
| HP            | 805A                        | [fd97efb317](https://linux-hardware.org/?probe=fd97efb317) | Mar 16, 2023 |
| Intel         | X99 V1.0                    | [1e1b3b6542](https://linux-hardware.org/?probe=1e1b3b6542) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | [09fdb4daa2](https://linux-hardware.org/?probe=09fdb4daa2) | Mar 16, 2023 |
| Acer          | FX58M                       | [ffc55de046](https://linux-hardware.org/?probe=ffc55de046) | Mar 16, 2023 |
| Acer          | Predator PO3-630            | [07ac5c2647](https://linux-hardware.org/?probe=07ac5c2647) | Mar 16, 2023 |
| Foxconn       | 2AB1                        | [ca561adb8b](https://linux-hardware.org/?probe=ca561adb8b) | Mar 16, 2023 |
| ASRock        | N68C-S UCC                  | [9fcdcbd033](https://linux-hardware.org/?probe=9fcdcbd033) | Mar 15, 2023 |
| ASRock        | N68C-S UCC                  | [a2630bc693](https://linux-hardware.org/?probe=a2630bc693) | Mar 15, 2023 |
| Gigabyte      | Z68A-D3H-B3                 | [13234c0f6d](https://linux-hardware.org/?probe=13234c0f6d) | Mar 15, 2023 |
| Dell          | 03NVJ6 A02                  | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| Intel         | JSL MRD                     | [c381bdf142](https://linux-hardware.org/?probe=c381bdf142) | Mar 15, 2023 |
| MSI           | Z97 PC Mate                 | [5b00c07288](https://linux-hardware.org/?probe=5b00c07288) | Mar 15, 2023 |
| HP            | 21D0                        | [9b7d2f0a4f](https://linux-hardware.org/?probe=9b7d2f0a4f) | Mar 15, 2023 |
| ASRock        | X470 Master SLI             | [06141a871e](https://linux-hardware.org/?probe=06141a871e) | Mar 15, 2023 |
| BESSTAR Te... | JB9                         | [169b9f8bab](https://linux-hardware.org/?probe=169b9f8bab) | Mar 15, 2023 |
| MSI           | B550-A PRO                  | [117ca7e4ef](https://linux-hardware.org/?probe=117ca7e4ef) | Mar 15, 2023 |
| Lenovo        | ThinkCentre M58 7360C12     | [04ef67f0f8](https://linux-hardware.org/?probe=04ef67f0f8) | Mar 15, 2023 |
| Lenovo        | ThinkCentre M58 7360C12     | [82c42e8e76](https://linux-hardware.org/?probe=82c42e8e76) | Mar 15, 2023 |
| Gigabyte      | Z68XP-UD4                   | [404f1199e2](https://linux-hardware.org/?probe=404f1199e2) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [1451ae2f05](https://linux-hardware.org/?probe=1451ae2f05) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [26971576bb](https://linux-hardware.org/?probe=26971576bb) | Mar 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [867aa61b78](https://linux-hardware.org/?probe=867aa61b78) | Mar 14, 2023 |
| MSI           | B450M PRO-VDH V2            | [342fc7ec97](https://linux-hardware.org/?probe=342fc7ec97) | Mar 14, 2023 |
| ECS           | A55F-M4                     | [eaee63c0f9](https://linux-hardware.org/?probe=eaee63c0f9) | Mar 14, 2023 |
| MSI           | B450M PRO-VDH V2            | [056353c290](https://linux-hardware.org/?probe=056353c290) | Mar 14, 2023 |
| ECS           | A55F-M4                     | [667ab38865](https://linux-hardware.org/?probe=667ab38865) | Mar 14, 2023 |
| Dell          | 042P49 A00                  | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| BESSTAR Te... | JB9                         | [8e1a662f53](https://linux-hardware.org/?probe=8e1a662f53) | Mar 14, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [942d1f4c2c](https://linux-hardware.org/?probe=942d1f4c2c) | Mar 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [e836500efa](https://linux-hardware.org/?probe=e836500efa) | Mar 14, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [3222c6ea63](https://linux-hardware.org/?probe=3222c6ea63) | Mar 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4b0af487e9](https://linux-hardware.org/?probe=4b0af487e9) | Mar 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [729bfdc60d](https://linux-hardware.org/?probe=729bfdc60d) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cd389d99a0](https://linux-hardware.org/?probe=cd389d99a0) | Mar 14, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [631e225bab](https://linux-hardware.org/?probe=631e225bab) | Mar 14, 2023 |
| ASRock        | B550M-HDV                   | [2b942e22c2](https://linux-hardware.org/?probe=2b942e22c2) | Mar 13, 2023 |
| ASRock        | B550M-HDV                   | [e2379c1008](https://linux-hardware.org/?probe=e2379c1008) | Mar 13, 2023 |
| ASUSTek       | Z87-K                       | [4edc1a61c3](https://linux-hardware.org/?probe=4edc1a61c3) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| ASUSTek       | M3N-HT DELUXE               | [daa247b93e](https://linux-hardware.org/?probe=daa247b93e) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [7271007b96](https://linux-hardware.org/?probe=7271007b96) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| Gigabyte      | B450 AORUS M                | [94a2a9b97a](https://linux-hardware.org/?probe=94a2a9b97a) | Mar 13, 2023 |
| Shenzhen M... | F7BFC                       | [cf05b7a6e7](https://linux-hardware.org/?probe=cf05b7a6e7) | Mar 13, 2023 |
| Intel         | DH55TC AAE70932-302         | [1ca0e70d0e](https://linux-hardware.org/?probe=1ca0e70d0e) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| AZW           | Green G3                    | [6f19e0234a](https://linux-hardware.org/?probe=6f19e0234a) | Mar 13, 2023 |
| Gigabyte      | F2A78M-DS2                  | [659e2861d9](https://linux-hardware.org/?probe=659e2861d9) | Mar 13, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [a7105953c2](https://linux-hardware.org/?probe=a7105953c2) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [1e0274aed9](https://linux-hardware.org/?probe=1e0274aed9) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [8efb3d3950](https://linux-hardware.org/?probe=8efb3d3950) | Mar 12, 2023 |
| ASUSTek       | Maximus V FORMULA           | [9aecd96100](https://linux-hardware.org/?probe=9aecd96100) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-E               | [cf5cbabe11](https://linux-hardware.org/?probe=cf5cbabe11) | Mar 12, 2023 |
| Acer          | FX58M                       | [5974103b03](https://linux-hardware.org/?probe=5974103b03) | Mar 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [0c699c2214](https://linux-hardware.org/?probe=0c699c2214) | Mar 12, 2023 |
| ASUSTek       | P8B75-M LE                  | [cb6d3a8371](https://linux-hardware.org/?probe=cb6d3a8371) | Mar 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [17431ae177](https://linux-hardware.org/?probe=17431ae177) | Mar 12, 2023 |
| Acer          | E946GZ                      | [9b79cd2b84](https://linux-hardware.org/?probe=9b79cd2b84) | Mar 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | ThinkStation S30 056847U    | [c63ba2d1d4](https://linux-hardware.org/?probe=c63ba2d1d4) | Mar 11, 2023 |
| Intel         | DH55TC AAE70932-302         | [5c2b9bb8b7](https://linux-hardware.org/?probe=5c2b9bb8b7) | Mar 11, 2023 |
| ASUSTek       | M2N-E                       | [9e3eabb730](https://linux-hardware.org/?probe=9e3eabb730) | Mar 11, 2023 |
| MSI           | 2AE0                        | [dba335076c](https://linux-hardware.org/?probe=dba335076c) | Mar 11, 2023 |
| Intel         | H61                         | [0a38ec61cc](https://linux-hardware.org/?probe=0a38ec61cc) | Mar 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [278b9e10a7](https://linux-hardware.org/?probe=278b9e10a7) | Mar 11, 2023 |
| HP            | 18E5                        | [d94d167f13](https://linux-hardware.org/?probe=d94d167f13) | Mar 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [ca2f0853bf](https://linux-hardware.org/?probe=ca2f0853bf) | Mar 11, 2023 |
| HP            | 2215                        | [08b781f792](https://linux-hardware.org/?probe=08b781f792) | Mar 11, 2023 |
| HP            | 2215                        | [4690f4f17a](https://linux-hardware.org/?probe=4690f4f17a) | Mar 11, 2023 |
| Gigabyte      | Z590 AORUS ELITE            | [790a51e99f](https://linux-hardware.org/?probe=790a51e99f) | Mar 11, 2023 |
| HP            | 2B52                        | [c705beb5ae](https://linux-hardware.org/?probe=c705beb5ae) | Mar 11, 2023 |
| Acer          | Aspire M5400                | [39dde8de71](https://linux-hardware.org/?probe=39dde8de71) | Mar 11, 2023 |
| Intel         | X99H                        | [a89ad204c8](https://linux-hardware.org/?probe=a89ad204c8) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| Positivo      | POS-PIB150DT                | [0842fc186b](https://linux-hardware.org/?probe=0842fc186b) | Mar 10, 2023 |
| Lenovo        | ThinkStation S30 056851U    | [290eb98bed](https://linux-hardware.org/?probe=290eb98bed) | Mar 10, 2023 |
| AZW           | Green G3                    | [340a0549d8](https://linux-hardware.org/?probe=340a0549d8) | Mar 10, 2023 |
| ASRock        | 960GM-GS3 FX                | [0ff4f2d904](https://linux-hardware.org/?probe=0ff4f2d904) | Mar 10, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c59f1b8832](https://linux-hardware.org/?probe=c59f1b8832) | Mar 10, 2023 |
| Acer          | Aspire M5400                | [09984fa907](https://linux-hardware.org/?probe=09984fa907) | Mar 10, 2023 |
| ASUSTek       | P5K                         | [e936aa1681](https://linux-hardware.org/?probe=e936aa1681) | Mar 10, 2023 |
| Dell          | 0XR1GT A00                  | [c8ee51395b](https://linux-hardware.org/?probe=c8ee51395b) | Mar 10, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [0fb1309bff](https://linux-hardware.org/?probe=0fb1309bff) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [87c282ab21](https://linux-hardware.org/?probe=87c282ab21) | Mar 09, 2023 |
| Dell          | 0XR1GT A00                  | [97a24bc755](https://linux-hardware.org/?probe=97a24bc755) | Mar 09, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [ac703f5ade](https://linux-hardware.org/?probe=ac703f5ade) | Mar 09, 2023 |
| ASRock        | H87M Pro4                   | [49a012cecd](https://linux-hardware.org/?probe=49a012cecd) | Mar 09, 2023 |
| HP            | 802F                        | [8dc424549c](https://linux-hardware.org/?probe=8dc424549c) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | GTR V02                     | [06b17c5206](https://linux-hardware.org/?probe=06b17c5206) | Mar 09, 2023 |
| HP            | 3396                        | [276cd0de54](https://linux-hardware.org/?probe=276cd0de54) | Mar 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7d43250ce4](https://linux-hardware.org/?probe=7d43250ce4) | Mar 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dfc8681a45](https://linux-hardware.org/?probe=dfc8681a45) | Mar 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [b7f03a8a6d](https://linux-hardware.org/?probe=b7f03a8a6d) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6328a68180](https://linux-hardware.org/?probe=6328a68180) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Gigabyte      | 990FXA-UD7                  | [b88a423e30](https://linux-hardware.org/?probe=b88a423e30) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| HP            | 8433 11                     | [95f33803c0](https://linux-hardware.org/?probe=95f33803c0) | Mar 08, 2023 |
| Dell          | 0N826N A03                  | [b411046bb4](https://linux-hardware.org/?probe=b411046bb4) | Mar 08, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [519310d05f](https://linux-hardware.org/?probe=519310d05f) | Mar 08, 2023 |
| Dell          | 0N826N A03                  | [d4d9bac596](https://linux-hardware.org/?probe=d4d9bac596) | Mar 08, 2023 |
| ASUSTek       | H110M-K                     | [f69aaa84ed](https://linux-hardware.org/?probe=f69aaa84ed) | Mar 08, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [79459b8b4b](https://linux-hardware.org/?probe=79459b8b4b) | Mar 08, 2023 |
| AZW           | Green G3                    | [1151601daa](https://linux-hardware.org/?probe=1151601daa) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | [a56b16b410](https://linux-hardware.org/?probe=a56b16b410) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [1ef5bb11d6](https://linux-hardware.org/?probe=1ef5bb11d6) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [0bad20c48c](https://linux-hardware.org/?probe=0bad20c48c) | Mar 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [43bdb7e444](https://linux-hardware.org/?probe=43bdb7e444) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | [ed46b4c885](https://linux-hardware.org/?probe=ed46b4c885) | Mar 07, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | [87a3321cf9](https://linux-hardware.org/?probe=87a3321cf9) | Mar 07, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [781f2a13a2](https://linux-hardware.org/?probe=781f2a13a2) | Mar 07, 2023 |
| HP            | 0AA8h                       | [6552e8b371](https://linux-hardware.org/?probe=6552e8b371) | Mar 07, 2023 |
| Gigabyte      | Q87M-D2H                    | [e6a1c90404](https://linux-hardware.org/?probe=e6a1c90404) | Mar 07, 2023 |
| Dell          | 0FP406 A03                  | [66bc551d35](https://linux-hardware.org/?probe=66bc551d35) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | [1563e26ae3](https://linux-hardware.org/?probe=1563e26ae3) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | [44b690055c](https://linux-hardware.org/?probe=44b690055c) | Mar 07, 2023 |
| Gigabyte      | Z690 GAMING X               | [b8dc3dd82b](https://linux-hardware.org/?probe=b8dc3dd82b) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [ff1a57749f](https://linux-hardware.org/?probe=ff1a57749f) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [37f7cabb58](https://linux-hardware.org/?probe=37f7cabb58) | Mar 07, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [0763378218](https://linux-hardware.org/?probe=0763378218) | Mar 06, 2023 |
| ASUSTek       | Maximus V GENE              | [f06cb79be8](https://linux-hardware.org/?probe=f06cb79be8) | Mar 06, 2023 |
| ASUSTek       | Z97-A                       | [6bc7428949](https://linux-hardware.org/?probe=6bc7428949) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Dell          | 0Y2K8N A01                  | [a7a9f81898](https://linux-hardware.org/?probe=a7a9f81898) | Mar 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [f7c65531a7](https://linux-hardware.org/?probe=f7c65531a7) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [896ab1f527](https://linux-hardware.org/?probe=896ab1f527) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0328fa718e](https://linux-hardware.org/?probe=0328fa718e) | Mar 06, 2023 |
| AZW           | Green G3                    | [7c139adb84](https://linux-hardware.org/?probe=7c139adb84) | Mar 05, 2023 |
| Packard Be... | FIH57                       | [06cd872d9b](https://linux-hardware.org/?probe=06cd872d9b) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | [2728efea53](https://linux-hardware.org/?probe=2728efea53) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | [7235211822](https://linux-hardware.org/?probe=7235211822) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| Gigabyte      | P41-ES3G                    | [ae657140ba](https://linux-hardware.org/?probe=ae657140ba) | Mar 05, 2023 |
| Gigabyte      | H370M D3H GSM-CF            | [3f37f83f5a](https://linux-hardware.org/?probe=3f37f83f5a) | Mar 05, 2023 |
| Inventec      | Z CLASS A02                 | [7b5d4c040b](https://linux-hardware.org/?probe=7b5d4c040b) | Mar 05, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [984e6241f5](https://linux-hardware.org/?probe=984e6241f5) | Mar 05, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [1e09dd1123](https://linux-hardware.org/?probe=1e09dd1123) | Mar 04, 2023 |
| Dell          | 0P01GV A03                  | [b53bbf2061](https://linux-hardware.org/?probe=b53bbf2061) | Mar 04, 2023 |
| Lenovo        | MAHOBAY                     | [ce017b1c51](https://linux-hardware.org/?probe=ce017b1c51) | Mar 04, 2023 |
| Lenovo        | MAHOBAY                     | [03f1de3c62](https://linux-hardware.org/?probe=03f1de3c62) | Mar 04, 2023 |
| ASUSTek       | A8V-X                       | [f821079a04](https://linux-hardware.org/?probe=f821079a04) | Mar 04, 2023 |
| HP            | 0AA0h                       | [657f888891](https://linux-hardware.org/?probe=657f888891) | Mar 04, 2023 |
| ASRock        | G41M-GS3                    | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASRock        | B75 Pro3-M                  | [3574e6c0f8](https://linux-hardware.org/?probe=3574e6c0f8) | Mar 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [f725604d9b](https://linux-hardware.org/?probe=f725604d9b) | Mar 04, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [b00bb9faf9](https://linux-hardware.org/?probe=b00bb9faf9) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9627dbdadf](https://linux-hardware.org/?probe=9627dbdadf) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | [8c0488a140](https://linux-hardware.org/?probe=8c0488a140) | Mar 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a04a4550d5](https://linux-hardware.org/?probe=a04a4550d5) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | [6258e45123](https://linux-hardware.org/?probe=6258e45123) | Mar 04, 2023 |
| ASUSTek       | P8B75-M LE                  | [b5b5f89ca1](https://linux-hardware.org/?probe=b5b5f89ca1) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | [abb62fe86f](https://linux-hardware.org/?probe=abb62fe86f) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | [3c2ed7f053](https://linux-hardware.org/?probe=3c2ed7f053) | Mar 04, 2023 |
| Alienware     | 07W25T A00                  | [6f86fcca87](https://linux-hardware.org/?probe=6f86fcca87) | Mar 04, 2023 |
| Gigabyte      | P41-ES3G                    | [dfd94da97c](https://linux-hardware.org/?probe=dfd94da97c) | Mar 03, 2023 |
| Gigabyte      | B450 AORUS M                | [3603a535a3](https://linux-hardware.org/?probe=3603a535a3) | Mar 03, 2023 |
| Gigabyte      | B450 AORUS M                | [b43557ffd3](https://linux-hardware.org/?probe=b43557ffd3) | Mar 03, 2023 |
| Gigabyte      | Q87M-D2H                    | [d647248880](https://linux-hardware.org/?probe=d647248880) | Mar 03, 2023 |
| ASUSTek       | STRIX H270I GAMING          | [2ff7fe6634](https://linux-hardware.org/?probe=2ff7fe6634) | Mar 03, 2023 |
| Gigabyte      | Q87M-D2H                    | [d5940a6492](https://linux-hardware.org/?probe=d5940a6492) | Mar 03, 2023 |
| Gigabyte      | 970A-DS3P                   | [fc28c47011](https://linux-hardware.org/?probe=fc28c47011) | Mar 03, 2023 |
| HP            | 8265                        | [a48871b59c](https://linux-hardware.org/?probe=a48871b59c) | Mar 03, 2023 |
| Gigabyte      | Z77P-D3                     | [3cabf6cbe4](https://linux-hardware.org/?probe=3cabf6cbe4) | Mar 03, 2023 |
| NEWSMAY       | Unknown                     | [6f978c3a04](https://linux-hardware.org/?probe=6f978c3a04) | Mar 02, 2023 |
| Dell          | 018D1Y A00                  | [5af7b05e04](https://linux-hardware.org/?probe=5af7b05e04) | Mar 02, 2023 |
| MSI           | MS-7250                     | [5127fbfef5](https://linux-hardware.org/?probe=5127fbfef5) | Mar 02, 2023 |
| Dell          | 0T656F A01                  | [189bea23b3](https://linux-hardware.org/?probe=189bea23b3) | Mar 02, 2023 |
| MSI           | PRO H610M-G DDR4            | [8ecbea06f8](https://linux-hardware.org/?probe=8ecbea06f8) | Mar 02, 2023 |
| Supermicro    | X7SPA-H                     | [819c636b52](https://linux-hardware.org/?probe=819c636b52) | Mar 01, 2023 |
| ASRock        | Q1900M Pro3                 | [ef9e90045e](https://linux-hardware.org/?probe=ef9e90045e) | Mar 01, 2023 |
| BESSTAR Te... | UM700                       | [5f8e33221f](https://linux-hardware.org/?probe=5f8e33221f) | Mar 01, 2023 |
| HP            | 0AACh                       | [96cfb59fc8](https://linux-hardware.org/?probe=96cfb59fc8) | Mar 01, 2023 |
| Gigabyte      | B450M S2H                   | [37b9893751](https://linux-hardware.org/?probe=37b9893751) | Mar 01, 2023 |
| Gigabyte      | Z590 GAMING X               | [7b8fea51fd](https://linux-hardware.org/?probe=7b8fea51fd) | Mar 01, 2023 |
| Gigabyte      | GB-BRR7H-4800               | [07743ae087](https://linux-hardware.org/?probe=07743ae087) | Mar 01, 2023 |
| AZW           | Green G3                    | [a61945bed4](https://linux-hardware.org/?probe=a61945bed4) | Mar 01, 2023 |
| AZW           | Green G3                    | [594d9a8b54](https://linux-hardware.org/?probe=594d9a8b54) | Mar 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [f0134fccab](https://linux-hardware.org/?probe=f0134fccab) | Mar 01, 2023 |
| ASUSTek       | PRIME Z270-A                | [25c46b6f70](https://linux-hardware.org/?probe=25c46b6f70) | Mar 01, 2023 |
| MSI           | H110M PRO-VH                | [9b0b5b79f0](https://linux-hardware.org/?probe=9b0b5b79f0) | Mar 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [2b434f0b1d](https://linux-hardware.org/?probe=2b434f0b1d) | Feb 28, 2023 |
| AZW           | Speed S                     | [e44ff0faf0](https://linux-hardware.org/?probe=e44ff0faf0) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX                  | [5721cbc403](https://linux-hardware.org/?probe=5721cbc403) | Feb 28, 2023 |
| BESSTAR Te... | UM250 V1.0                  | [2ef76c6dff](https://linux-hardware.org/?probe=2ef76c6dff) | Feb 28, 2023 |
| Biostar       | H81MLV3                     | [ccba1a8217](https://linux-hardware.org/?probe=ccba1a8217) | Feb 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [c2eff23772](https://linux-hardware.org/?probe=c2eff23772) | Feb 28, 2023 |
| ASRock        | Z97 Pro3                    | [506d56faff](https://linux-hardware.org/?probe=506d56faff) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | [ad46fcc88d](https://linux-hardware.org/?probe=ad46fcc88d) | Feb 28, 2023 |
| Gigabyte      | H61M-S1                     | [ee8e20d95e](https://linux-hardware.org/?probe=ee8e20d95e) | Feb 27, 2023 |
| PCWare        | IPMH61R2                    | [52a17bf9c1](https://linux-hardware.org/?probe=52a17bf9c1) | Feb 27, 2023 |
| HP            | 3047h                       | [db6be92c4f](https://linux-hardware.org/?probe=db6be92c4f) | Feb 27, 2023 |
| Dell          | 0D6H9T A00                  | [70bdf485da](https://linux-hardware.org/?probe=70bdf485da) | Feb 27, 2023 |
| ASRock        | Z97 Pro3                    | [626e67df35](https://linux-hardware.org/?probe=626e67df35) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | [64496d4ab7](https://linux-hardware.org/?probe=64496d4ab7) | Feb 27, 2023 |
| Gigabyte      | H97-HD3                     | [bb2cac1486](https://linux-hardware.org/?probe=bb2cac1486) | Feb 27, 2023 |
| Dell          | 0XHGV1 A00                  | [75249be116](https://linux-hardware.org/?probe=75249be116) | Feb 27, 2023 |
| Gigabyte      | H87M-D3H                    | [3c50af5218](https://linux-hardware.org/?probe=3c50af5218) | Feb 27, 2023 |
| Gigabyte      | B650 GAMING X AX            | [c2b3e01a45](https://linux-hardware.org/?probe=c2b3e01a45) | Feb 27, 2023 |
| Gigabyte      | G41MT-S2                    | [7f72d6bba7](https://linux-hardware.org/?probe=7f72d6bba7) | Feb 26, 2023 |
| Cincoze       | DX-1000.01.001              | [7923f1dc21](https://linux-hardware.org/?probe=7923f1dc21) | Feb 26, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [310a65baea](https://linux-hardware.org/?probe=310a65baea) | Feb 26, 2023 |
| HP            | 8643 SMVB                   | [4f36e23485](https://linux-hardware.org/?probe=4f36e23485) | Feb 26, 2023 |
| HP            | 3397                        | [a1840ee53d](https://linux-hardware.org/?probe=a1840ee53d) | Feb 26, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee31b8fa71](https://linux-hardware.org/?probe=ee31b8fa71) | Feb 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a758475e11](https://linux-hardware.org/?probe=a758475e11) | Feb 26, 2023 |
| Dell          | 0NKW6Y A01                  | [62e7760c7a](https://linux-hardware.org/?probe=62e7760c7a) | Feb 26, 2023 |
| FIC           | PTM33 PCB                   | [b70b076cda](https://linux-hardware.org/?probe=b70b076cda) | Feb 26, 2023 |
| ASRock        | H61M-DGS R2.0               | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Gigabyte      | B250M-D3H-CF                | [de180bd339](https://linux-hardware.org/?probe=de180bd339) | Feb 25, 2023 |
| MSI           | X570-A PRO                  | [922ba2355e](https://linux-hardware.org/?probe=922ba2355e) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [585e02a6dc](https://linux-hardware.org/?probe=585e02a6dc) | Feb 25, 2023 |
| ASUSTek       | PRIME A520M-A II            | [8e913f4c3e](https://linux-hardware.org/?probe=8e913f4c3e) | Feb 25, 2023 |
| HP            | 3047h                       | [8f7d5acf1f](https://linux-hardware.org/?probe=8f7d5acf1f) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [3f2e38e322](https://linux-hardware.org/?probe=3f2e38e322) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| Gigabyte      | B75M-HD3                    | [29b1432f2c](https://linux-hardware.org/?probe=29b1432f2c) | Feb 25, 2023 |
| HP            | 2AA2                        | [b9411eadb7](https://linux-hardware.org/?probe=b9411eadb7) | Feb 25, 2023 |
| Gigabyte      | G41MT-S2                    | [d81c35b55b](https://linux-hardware.org/?probe=d81c35b55b) | Feb 25, 2023 |
| ASUSTek       | A88XM-A                     | [dff66700c0](https://linux-hardware.org/?probe=dff66700c0) | Feb 25, 2023 |
| ASRock        | N68-GS4 FX R2.0             | [6d03ea4905](https://linux-hardware.org/?probe=6d03ea4905) | Feb 24, 2023 |
| Dell          | 08HPGT A02                  | [69288a8011](https://linux-hardware.org/?probe=69288a8011) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| PCWare        | IPMH61R2                    | [eda674b9a5](https://linux-hardware.org/?probe=eda674b9a5) | Feb 24, 2023 |
| ASRock        | H670M Pro RS                | [91bcaa987c](https://linux-hardware.org/?probe=91bcaa987c) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | [4ed48d952c](https://linux-hardware.org/?probe=4ed48d952c) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| Gigabyte      | Q87M-D2H                    | [dde739ae8a](https://linux-hardware.org/?probe=dde739ae8a) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c34909b191](https://linux-hardware.org/?probe=c34909b191) | Feb 24, 2023 |
| HP            | 1497                        | [478a5730f6](https://linux-hardware.org/?probe=478a5730f6) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d93c7d5661](https://linux-hardware.org/?probe=d93c7d5661) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [7cdbd101a4](https://linux-hardware.org/?probe=7cdbd101a4) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [142a12ded0](https://linux-hardware.org/?probe=142a12ded0) | Feb 23, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [455b0e1401](https://linux-hardware.org/?probe=455b0e1401) | Feb 23, 2023 |
| Gigabyte      | H81M-S2H                    | [c3d9b18f7c](https://linux-hardware.org/?probe=c3d9b18f7c) | Feb 23, 2023 |
| HP            | 18E6                        | [294fa26b04](https://linux-hardware.org/?probe=294fa26b04) | Feb 23, 2023 |
| HP            | 2ADE                        | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASUSTek       | M3N78-VM                    | [246492391c](https://linux-hardware.org/?probe=246492391c) | Feb 23, 2023 |
| HP            | 0AA8h                       | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| PCWare        | IPMH61R2                    | [f02c3d5895](https://linux-hardware.org/?probe=f02c3d5895) | Feb 22, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [06138e952c](https://linux-hardware.org/?probe=06138e952c) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2993295e62](https://linux-hardware.org/?probe=2993295e62) | Feb 22, 2023 |
| Foxconn       | Lucknow                     | [3ca9a4f66e](https://linux-hardware.org/?probe=3ca9a4f66e) | Feb 22, 2023 |
| ASRock        | 970A-G                      | [80648218db](https://linux-hardware.org/?probe=80648218db) | Feb 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0d0a828b39](https://linux-hardware.org/?probe=0d0a828b39) | Feb 22, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [29673d3e8f](https://linux-hardware.org/?probe=29673d3e8f) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [c23f2f53ed](https://linux-hardware.org/?probe=c23f2f53ed) | Feb 21, 2023 |
| ASRock        | X470 Master SLI/ac          | [9c11797d60](https://linux-hardware.org/?probe=9c11797d60) | Feb 21, 2023 |
| ASUSTek       | PRIME H510M-K               | [5fb951a350](https://linux-hardware.org/?probe=5fb951a350) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ae2e7a22a0](https://linux-hardware.org/?probe=ae2e7a22a0) | Feb 21, 2023 |
| HP            | 339A                        | [d4ee04127e](https://linux-hardware.org/?probe=d4ee04127e) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [09c45a0b09](https://linux-hardware.org/?probe=09c45a0b09) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f5a22b7bb9](https://linux-hardware.org/?probe=f5a22b7bb9) | Feb 21, 2023 |
| Dell          | 0M5DCD A00                  | [9bfd5f9a7f](https://linux-hardware.org/?probe=9bfd5f9a7f) | Feb 21, 2023 |
| Dell          | 0M5DCD A00                  | [afd4e480d4](https://linux-hardware.org/?probe=afd4e480d4) | Feb 20, 2023 |
| MSI           | 970A-G43                    | [5fab82df57](https://linux-hardware.org/?probe=5fab82df57) | Feb 20, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [a37ae03564](https://linux-hardware.org/?probe=a37ae03564) | Feb 20, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [c17db0329f](https://linux-hardware.org/?probe=c17db0329f) | Feb 20, 2023 |
| HP            | 3398                        | [3ea3d01398](https://linux-hardware.org/?probe=3ea3d01398) | Feb 20, 2023 |
| HP            | 1497                        | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [2a403bdb2b](https://linux-hardware.org/?probe=2a403bdb2b) | Feb 20, 2023 |
| AMD           | A78FX VER                   | [36eb566c26](https://linux-hardware.org/?probe=36eb566c26) | Feb 20, 2023 |
| ASUSTek       | B85M-G                      | [501a95ac36](https://linux-hardware.org/?probe=501a95ac36) | Feb 20, 2023 |
| MSI           | B450M PRO-VDH V2            | [a3124367c3](https://linux-hardware.org/?probe=a3124367c3) | Feb 20, 2023 |
| HP            | 3398                        | [6b616a9a10](https://linux-hardware.org/?probe=6b616a9a10) | Feb 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a3f2825d3d](https://linux-hardware.org/?probe=a3f2825d3d) | Feb 20, 2023 |
| Gigabyte      | MRHM3AP                     | [9f4978d79f](https://linux-hardware.org/?probe=9f4978d79f) | Feb 19, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [7e45218236](https://linux-hardware.org/?probe=7e45218236) | Feb 19, 2023 |
| ASUSTek       | M3N78-VM                    | [c124cec382](https://linux-hardware.org/?probe=c124cec382) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| AZW           | GTi                         | [17bb698441](https://linux-hardware.org/?probe=17bb698441) | Feb 19, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [06c110e6f1](https://linux-hardware.org/?probe=06c110e6f1) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | [fe75bac6ce](https://linux-hardware.org/?probe=fe75bac6ce) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | [605089c66c](https://linux-hardware.org/?probe=605089c66c) | Feb 19, 2023 |
| AMD           | 970A-D3                     | [bc2f6d8481](https://linux-hardware.org/?probe=bc2f6d8481) | Feb 19, 2023 |
| ASRock        | B450 Pro4                   | [092f97e245](https://linux-hardware.org/?probe=092f97e245) | Feb 19, 2023 |
| Gigabyte      | B365M D3H-CF                | [aa49c18960](https://linux-hardware.org/?probe=aa49c18960) | Feb 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [6be03ad579](https://linux-hardware.org/?probe=6be03ad579) | Feb 19, 2023 |
| HP            | 0AACh                       | [3ff53d69b2](https://linux-hardware.org/?probe=3ff53d69b2) | Feb 19, 2023 |
| Dell          | 088DT1 A01                  | [4ecc419f83](https://linux-hardware.org/?probe=4ecc419f83) | Feb 18, 2023 |
| Inventec      | VXC Class A02               | [ddea00ed0c](https://linux-hardware.org/?probe=ddea00ed0c) | Feb 18, 2023 |
| Gigabyte      | MRHM3AP                     | [a427da167b](https://linux-hardware.org/?probe=a427da167b) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8fb0aec13d](https://linux-hardware.org/?probe=8fb0aec13d) | Feb 18, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0428793835](https://linux-hardware.org/?probe=0428793835) | Feb 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [af7c933bf3](https://linux-hardware.org/?probe=af7c933bf3) | Feb 17, 2023 |
| Dell          | 0XC7MM A01                  | [93ccca9fdd](https://linux-hardware.org/?probe=93ccca9fdd) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [667dc13294](https://linux-hardware.org/?probe=667dc13294) | Feb 17, 2023 |
| AAEON         | PICO-APL3 V1.0              | [4ef4f86a2e](https://linux-hardware.org/?probe=4ef4f86a2e) | Feb 17, 2023 |
| Acer          | Batman A01                  | [d7aaa8f1c8](https://linux-hardware.org/?probe=d7aaa8f1c8) | Feb 17, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [8da7f7cbdc](https://linux-hardware.org/?probe=8da7f7cbdc) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | [e01d812902](https://linux-hardware.org/?probe=e01d812902) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | [52b4d00a5a](https://linux-hardware.org/?probe=52b4d00a5a) | Feb 17, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0d5eded653](https://linux-hardware.org/?probe=0d5eded653) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| AZW           | Green G3                    | [ee25777882](https://linux-hardware.org/?probe=ee25777882) | Feb 17, 2023 |
| HP            | 2B36                        | [81833a42d2](https://linux-hardware.org/?probe=81833a42d2) | Feb 17, 2023 |
| MSI           | X470 GAMING PRO CARBON A... | [beec8fdf56](https://linux-hardware.org/?probe=beec8fdf56) | Feb 16, 2023 |
| ASUSTek       | P5Q-PRO                     | [f01a1d6c70](https://linux-hardware.org/?probe=f01a1d6c70) | Feb 16, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [3b0150685c](https://linux-hardware.org/?probe=3b0150685c) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | [9d197fed1d](https://linux-hardware.org/?probe=9d197fed1d) | Feb 16, 2023 |
| Inventec      | VXC Class A02               | [6e36781784](https://linux-hardware.org/?probe=6e36781784) | Feb 16, 2023 |
| Inventec      | VXC Class A02               | [f85ac5bc8a](https://linux-hardware.org/?probe=f85ac5bc8a) | Feb 16, 2023 |
| Inventec      | VXC Class A02               | [b1266a1e15](https://linux-hardware.org/?probe=b1266a1e15) | Feb 16, 2023 |
| ASRock        | B360M Xtreme                | [c10563291e](https://linux-hardware.org/?probe=c10563291e) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f0105f57bf](https://linux-hardware.org/?probe=f0105f57bf) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 18E9                        | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| Intel         | X79M-S                      | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Gigabyte      | H97M-D3H                    | [2ae439ec07](https://linux-hardware.org/?probe=2ae439ec07) | Feb 15, 2023 |
| HP            | 1497                        | [1d55830595](https://linux-hardware.org/?probe=1d55830595) | Feb 15, 2023 |
| Medion        | MS-7616                     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| ASRock        | H61M-DGS                    | [9716d5ed72](https://linux-hardware.org/?probe=9716d5ed72) | Feb 15, 2023 |
| ASUSTek       | V-P7H55E                    | [27ddce20a1](https://linux-hardware.org/?probe=27ddce20a1) | Feb 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | [8689383fea](https://linux-hardware.org/?probe=8689383fea) | Feb 15, 2023 |
| ASUSTek       | PRIME Z590-V                | [4d00371a70](https://linux-hardware.org/?probe=4d00371a70) | Feb 15, 2023 |
| Inventec      | VXC Class A02               | [52b2c70658](https://linux-hardware.org/?probe=52b2c70658) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f298c1fc7e](https://linux-hardware.org/?probe=f298c1fc7e) | Feb 14, 2023 |
| Unknown       | Unknown                     | [69c7852df8](https://linux-hardware.org/?probe=69c7852df8) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [45cfd72091](https://linux-hardware.org/?probe=45cfd72091) | Feb 14, 2023 |
| IBM           | 811328U                     | [dc9536a0f2](https://linux-hardware.org/?probe=dc9536a0f2) | Feb 14, 2023 |
| IBM           | 811328U                     | [6ad9b1f22a](https://linux-hardware.org/?probe=6ad9b1f22a) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [0b0a816ecc](https://linux-hardware.org/?probe=0b0a816ecc) | Feb 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [47f61b3037](https://linux-hardware.org/?probe=47f61b3037) | Feb 14, 2023 |
| Pegatron      | Narra6                      | [13f0acba4c](https://linux-hardware.org/?probe=13f0acba4c) | Feb 14, 2023 |
| Intel         | X99 V1.0                    | [0bfbfe2876](https://linux-hardware.org/?probe=0bfbfe2876) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [1943e44d42](https://linux-hardware.org/?probe=1943e44d42) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| DIEBOLD       | NM70-I                      | [ed4d687c32](https://linux-hardware.org/?probe=ed4d687c32) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [500a5cf614](https://linux-hardware.org/?probe=500a5cf614) | Feb 14, 2023 |
| Lenovo        | SHARKBAY NOK                | [fea9318890](https://linux-hardware.org/?probe=fea9318890) | Feb 13, 2023 |
| ASRock        | IMB-195                     | [91da0807bb](https://linux-hardware.org/?probe=91da0807bb) | Feb 13, 2023 |
| MSI           | B450M PRO-VDH V2            | [a3a21b9c18](https://linux-hardware.org/?probe=a3a21b9c18) | Feb 13, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [60ddb51b98](https://linux-hardware.org/?probe=60ddb51b98) | Feb 13, 2023 |
| MSI           | Z370 PC PRO                 | [b5744eb259](https://linux-hardware.org/?probe=b5744eb259) | Feb 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [3e54cb20fd](https://linux-hardware.org/?probe=3e54cb20fd) | Feb 13, 2023 |
| Acer          | Aspire M1930                | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | [7901a0c0ec](https://linux-hardware.org/?probe=7901a0c0ec) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | [fc5af11584](https://linux-hardware.org/?probe=fc5af11584) | Feb 13, 2023 |
| Dell          | 0YKH50 A01                  | [d2a3255f21](https://linux-hardware.org/?probe=d2a3255f21) | Feb 13, 2023 |
| ASUSTek       | H81M-K                      | [6fe888ea28](https://linux-hardware.org/?probe=6fe888ea28) | Feb 13, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [ecf4603ab4](https://linux-hardware.org/?probe=ecf4603ab4) | Feb 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b45d61318e](https://linux-hardware.org/?probe=b45d61318e) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [1788a41484](https://linux-hardware.org/?probe=1788a41484) | Feb 12, 2023 |
| Intel         | H61                         | [f220565e36](https://linux-hardware.org/?probe=f220565e36) | Feb 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4eb6264a20](https://linux-hardware.org/?probe=4eb6264a20) | Feb 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [0742700581](https://linux-hardware.org/?probe=0742700581) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09a78143b4](https://linux-hardware.org/?probe=09a78143b4) | Feb 12, 2023 |
| MSI           | Z270 GAMING M3              | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c9d3e3c1cb](https://linux-hardware.org/?probe=c9d3e3c1cb) | Feb 12, 2023 |
| Unknown       | Unknown                     | [f2f95aef80](https://linux-hardware.org/?probe=f2f95aef80) | Feb 12, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [f6ed3beac1](https://linux-hardware.org/?probe=f6ed3beac1) | Feb 12, 2023 |
| Intel         | H61                         | [7a6e4d8211](https://linux-hardware.org/?probe=7a6e4d8211) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a034121d24](https://linux-hardware.org/?probe=a034121d24) | Feb 12, 2023 |
| Pegatron      | Narra6                      | [77bed4b6f3](https://linux-hardware.org/?probe=77bed4b6f3) | Feb 12, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [2a8f60a103](https://linux-hardware.org/?probe=2a8f60a103) | Feb 11, 2023 |
| Compaq        | Presario CQ-14              | [515b629bbc](https://linux-hardware.org/?probe=515b629bbc) | Feb 11, 2023 |
| ASUSTek       | CM5571                      | [c58cb005b5](https://linux-hardware.org/?probe=c58cb005b5) | Feb 11, 2023 |
| ASRock        | B450 Pro4                   | [c9a6a6e981](https://linux-hardware.org/?probe=c9a6a6e981) | Feb 11, 2023 |
| Acer          | Aspire TC-1760              | [a0db2f09b6](https://linux-hardware.org/?probe=a0db2f09b6) | Feb 11, 2023 |
| AZW           | Green G3                    | [152433615a](https://linux-hardware.org/?probe=152433615a) | Feb 11, 2023 |
| Gigabyte      | MZBSWAP-K4                  | [325c9ef37b](https://linux-hardware.org/?probe=325c9ef37b) | Feb 11, 2023 |
| HP            | 82A2                        | [fe327d8caa](https://linux-hardware.org/?probe=fe327d8caa) | Feb 11, 2023 |
| ASRock        | 990FX Extreme4              | [4af6878800](https://linux-hardware.org/?probe=4af6878800) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d85a564e73](https://linux-hardware.org/?probe=d85a564e73) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASRock        | Z170 Extreme6+              | [9b9b84473b](https://linux-hardware.org/?probe=9b9b84473b) | Feb 10, 2023 |
| Biostar       | A68N-5100                   | [4c44b82580](https://linux-hardware.org/?probe=4c44b82580) | Feb 10, 2023 |
| HP            | 8653 A                      | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| Intel         | JSL MRD                     | [5a876c1bb0](https://linux-hardware.org/?probe=5a876c1bb0) | Feb 10, 2023 |
| Dell          | 0D28YY A00                  | [ea48b51678](https://linux-hardware.org/?probe=ea48b51678) | Feb 10, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| MSI           | PH61-SP35                   | [ffd100018d](https://linux-hardware.org/?probe=ffd100018d) | Feb 10, 2023 |
| ASUSTek       | PRIME Z270-K                | [298bbec731](https://linux-hardware.org/?probe=298bbec731) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | [756bc1fc3b](https://linux-hardware.org/?probe=756bc1fc3b) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | [769b226f8e](https://linux-hardware.org/?probe=769b226f8e) | Feb 10, 2023 |
| Gigabyte      | H410M H V3                  | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [def22e6194](https://linux-hardware.org/?probe=def22e6194) | Feb 10, 2023 |
| Dell          | 02YYK5 A00                  | [83aeaf3b0e](https://linux-hardware.org/?probe=83aeaf3b0e) | Feb 10, 2023 |
| ASUSTek       | M5A99X EVO                  | [55dd77bf13](https://linux-hardware.org/?probe=55dd77bf13) | Feb 10, 2023 |
| ASUSTek       | M5A99X EVO                  | [09bac39306](https://linux-hardware.org/?probe=09bac39306) | Feb 10, 2023 |
| MSI           | PH61-SP35                   | [579c7bc265](https://linux-hardware.org/?probe=579c7bc265) | Feb 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [b38d2821bf](https://linux-hardware.org/?probe=b38d2821bf) | Feb 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [a26baa69ab](https://linux-hardware.org/?probe=a26baa69ab) | Feb 09, 2023 |
| Medion        | MS-7797                     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| HP            | 2215                        | [68d2f417bf](https://linux-hardware.org/?probe=68d2f417bf) | Feb 09, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [46193e11d4](https://linux-hardware.org/?probe=46193e11d4) | Feb 09, 2023 |
| ASRock        | Z68 Extreme4 Gen3           | [4548de054f](https://linux-hardware.org/?probe=4548de054f) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [9523b275e8](https://linux-hardware.org/?probe=9523b275e8) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| HP            | 2215                        | [a13f0cb4d3](https://linux-hardware.org/?probe=a13f0cb4d3) | Feb 09, 2023 |
| Intel         | DH55TC AAE70932-302         | [efb8f59f69](https://linux-hardware.org/?probe=efb8f59f69) | Feb 09, 2023 |
| Intel         | DH55TC AAE70932-302         | [634fb755fa](https://linux-hardware.org/?probe=634fb755fa) | Feb 09, 2023 |
| HP            | 8459                        | [5e71f95f59](https://linux-hardware.org/?probe=5e71f95f59) | Feb 08, 2023 |
| MSI           | PRO B650M-A WIFI            | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| Lenovo        | 3853RN9                     | [0a5837a556](https://linux-hardware.org/?probe=0a5837a556) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| Lenovo        | 3741 NOK                    | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [16c72d3532](https://linux-hardware.org/?probe=16c72d3532) | Feb 08, 2023 |
| MSI           | X570-A PRO                  | [8193758f55](https://linux-hardware.org/?probe=8193758f55) | Feb 08, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b853a9ecfc](https://linux-hardware.org/?probe=b853a9ecfc) | Feb 08, 2023 |
| Dell          | 0CRH6C A00                  | [fe0e64b291](https://linux-hardware.org/?probe=fe0e64b291) | Feb 08, 2023 |
| ASRock        | B550M-C                     | [a094d92a80](https://linux-hardware.org/?probe=a094d92a80) | Feb 08, 2023 |
| ASRock        | H310M-STX                   | [faadf8b29c](https://linux-hardware.org/?probe=faadf8b29c) | Feb 08, 2023 |
| Dell          | 0DR845                      | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e88f84967d](https://linux-hardware.org/?probe=e88f84967d) | Feb 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0f4be18646](https://linux-hardware.org/?probe=0f4be18646) | Feb 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [69012dacaa](https://linux-hardware.org/?probe=69012dacaa) | Feb 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [b4b14d9d66](https://linux-hardware.org/?probe=b4b14d9d66) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cfdb3767fb](https://linux-hardware.org/?probe=cfdb3767fb) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [f0aa46956b](https://linux-hardware.org/?probe=f0aa46956b) | Feb 06, 2023 |
| Dell          | 0TTDMJ A00                  | [0bd327136a](https://linux-hardware.org/?probe=0bd327136a) | Feb 06, 2023 |
| MSI           | PRO H610M-B DDR4            | [6217fdc070](https://linux-hardware.org/?probe=6217fdc070) | Feb 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e281d5800f](https://linux-hardware.org/?probe=e281d5800f) | Feb 05, 2023 |
| ASUSTek       | M4A78T-E                    | [365f2be75e](https://linux-hardware.org/?probe=365f2be75e) | Feb 05, 2023 |
| ASUSTek       | M3A78-T                     | [fb4c0de8e9](https://linux-hardware.org/?probe=fb4c0de8e9) | Feb 05, 2023 |
| Medion        | Akoya E6240T                | [3707cf7d95](https://linux-hardware.org/?probe=3707cf7d95) | Feb 05, 2023 |
| HP            | 3397                        | [ea72001991](https://linux-hardware.org/?probe=ea72001991) | Feb 05, 2023 |
| ASRock        | 775Dual-VSTA                | [945a366595](https://linux-hardware.org/?probe=945a366595) | Feb 05, 2023 |
| ASUSTek       | M5A99X EVO                  | [2bf0bbb10a](https://linux-hardware.org/?probe=2bf0bbb10a) | Feb 05, 2023 |
| HP            | 3396                        | [96a3376aa0](https://linux-hardware.org/?probe=96a3376aa0) | Feb 05, 2023 |
| Foxconn       | 17A0                        | [1a98ed31ed](https://linux-hardware.org/?probe=1a98ed31ed) | Feb 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2b9cb5eea6](https://linux-hardware.org/?probe=2b9cb5eea6) | Feb 05, 2023 |
| HP            | 8433 11                     | [ccf76a52c8](https://linux-hardware.org/?probe=ccf76a52c8) | Feb 05, 2023 |
| ASUSTek       | H110M-K                     | [9299261af6](https://linux-hardware.org/?probe=9299261af6) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [863b642a91](https://linux-hardware.org/?probe=863b642a91) | Feb 05, 2023 |
| HP            | 84FD                        | [87bd065604](https://linux-hardware.org/?probe=87bd065604) | Feb 04, 2023 |
| Medion        | B660H7-M20                  | [90cdf106b9](https://linux-hardware.org/?probe=90cdf106b9) | Feb 04, 2023 |
| HP            | 0A98h                       | [1d3ae20ff5](https://linux-hardware.org/?probe=1d3ae20ff5) | Feb 04, 2023 |
| ASUSTek       | PRO H410M-C                 | [486f19af99](https://linux-hardware.org/?probe=486f19af99) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| Gigabyte      | Z87-HD3                     | [d214fb8d55](https://linux-hardware.org/?probe=d214fb8d55) | Feb 04, 2023 |
| Intel         | X99 V1.0                    | [b8de53522e](https://linux-hardware.org/?probe=b8de53522e) | Feb 04, 2023 |
| MSI           | PRO H610M-G DDR4            | [a7ca7dfcd9](https://linux-hardware.org/?probe=a7ca7dfcd9) | Feb 04, 2023 |
| MSI           | Z97 GAMING 7                | [f485f21128](https://linux-hardware.org/?probe=f485f21128) | Feb 04, 2023 |
| HP            | 1496                        | [4464356ef0](https://linux-hardware.org/?probe=4464356ef0) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [bb7b67d9ef](https://linux-hardware.org/?probe=bb7b67d9ef) | Feb 04, 2023 |
| HP            | 3396                        | [3d32b32b4a](https://linux-hardware.org/?probe=3d32b32b4a) | Feb 04, 2023 |
| HP            | 805D                        | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| MSI           | H270 PC MATE                | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bb6553a9c3](https://linux-hardware.org/?probe=bb6553a9c3) | Feb 03, 2023 |
| Foxconn       | 2ABF                        | [54a305f83e](https://linux-hardware.org/?probe=54a305f83e) | Feb 03, 2023 |
| HP            | 805D                        | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| HP            | 805D                        | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| HP            | 1905                        | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | Z370 Gaming K6              | [203d5736d7](https://linux-hardware.org/?probe=203d5736d7) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| ASRock        | Z97 Killer                  | [6ef63fb3ba](https://linux-hardware.org/?probe=6ef63fb3ba) | Feb 03, 2023 |
| ASUSTek       | M5A99X EVO                  | [a6035b01eb](https://linux-hardware.org/?probe=a6035b01eb) | Feb 02, 2023 |
| ASUSTek       | M5A99X EVO                  | [a84ffe2c81](https://linux-hardware.org/?probe=a84ffe2c81) | Feb 02, 2023 |
| Intel         | SKYBAY                      | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| HP            | 212B                        | [cb1e6fa666](https://linux-hardware.org/?probe=cb1e6fa666) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | [d0cf3a9d76](https://linux-hardware.org/?probe=d0cf3a9d76) | Feb 02, 2023 |
| HP            | 212B                        | [e3e8d72420](https://linux-hardware.org/?probe=e3e8d72420) | Feb 02, 2023 |
| Pegatron      | 2ACF                        | [03fada2d4c](https://linux-hardware.org/?probe=03fada2d4c) | Feb 02, 2023 |
| PCWare        | IPMH61R3                    | [e296e8530f](https://linux-hardware.org/?probe=e296e8530f) | Feb 02, 2023 |
| ASUSTek       | P5QPL-AM                    | [c8ee9be68c](https://linux-hardware.org/?probe=c8ee9be68c) | Feb 02, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [d2696b9042](https://linux-hardware.org/?probe=d2696b9042) | Feb 02, 2023 |
| ECS           | A55F-M4                     | [08af507321](https://linux-hardware.org/?probe=08af507321) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [899544eff2](https://linux-hardware.org/?probe=899544eff2) | Feb 01, 2023 |
| HP            | 2B47                        | [0e0607c1f2](https://linux-hardware.org/?probe=0e0607c1f2) | Feb 01, 2023 |
| ECS           | G31T-M7                     | [76be6a1404](https://linux-hardware.org/?probe=76be6a1404) | Feb 01, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [d44fb4f702](https://linux-hardware.org/?probe=d44fb4f702) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6aa10285fe](https://linux-hardware.org/?probe=6aa10285fe) | Feb 01, 2023 |
| Lenovo        | 3111 NOK                    | [4f7d6b345c](https://linux-hardware.org/?probe=4f7d6b345c) | Feb 01, 2023 |
| Lenovo        | 3111 NOK                    | [03df681b38](https://linux-hardware.org/?probe=03df681b38) | Feb 01, 2023 |
| ECS           | G31T-M7                     | [9b0f53b46c](https://linux-hardware.org/?probe=9b0f53b46c) | Feb 01, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [b0697611f6](https://linux-hardware.org/?probe=b0697611f6) | Feb 01, 2023 |
| Dell          | 06D7TR A02                  | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| Gigabyte      | H55M-UD2H                   | [9337f49fff](https://linux-hardware.org/?probe=9337f49fff) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | 042P49 A01                  | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| MSI           | H510M-A PRO                 | [609fc1e9bb](https://linux-hardware.org/?probe=609fc1e9bb) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| HP            | 18E4                        | [50c68be419](https://linux-hardware.org/?probe=50c68be419) | Jan 31, 2023 |
| HP            | 18E4                        | [d038da9e08](https://linux-hardware.org/?probe=d038da9e08) | Jan 31, 2023 |
| AMD           | Inagua CRB                  | [3f497311dd](https://linux-hardware.org/?probe=3f497311dd) | Jan 31, 2023 |
| Gigabyte      | B560M H                     | [65f58e4e39](https://linux-hardware.org/?probe=65f58e4e39) | Jan 31, 2023 |
| MSI           | B550-A PRO                  | [78ab25ef78](https://linux-hardware.org/?probe=78ab25ef78) | Jan 31, 2023 |
| MSI           | B550-A PRO                  | [2458455037](https://linux-hardware.org/?probe=2458455037) | Jan 31, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [9ce51b923e](https://linux-hardware.org/?probe=9ce51b923e) | Jan 31, 2023 |
| ASUSTek       | P5V800-MX                   | [a8696956aa](https://linux-hardware.org/?probe=a8696956aa) | Jan 31, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [00fcd39954](https://linux-hardware.org/?probe=00fcd39954) | Jan 31, 2023 |
| ASUSTek       | B85M-G                      | [44c2ca8150](https://linux-hardware.org/?probe=44c2ca8150) | Jan 31, 2023 |
| Acer          | MCP73VE NVIDIA MCP73        | [840102fa91](https://linux-hardware.org/?probe=840102fa91) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| Dell          | 0P01GV A03                  | [b029e941fb](https://linux-hardware.org/?probe=b029e941fb) | Jan 30, 2023 |
| Dell          | 0TP412                      | [5db177340d](https://linux-hardware.org/?probe=5db177340d) | Jan 30, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [fa81cc9dea](https://linux-hardware.org/?probe=fa81cc9dea) | Jan 30, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [78cd3f7f65](https://linux-hardware.org/?probe=78cd3f7f65) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| PCWare        | IPMH110G                    | [95fe94d9f4](https://linux-hardware.org/?probe=95fe94d9f4) | Jan 30, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell          | 0D28YY A00                  | [63b753b56e](https://linux-hardware.org/?probe=63b753b56e) | Jan 30, 2023 |
| ASUSTek       | P8Q77-M                     | [be0ebca5cc](https://linux-hardware.org/?probe=be0ebca5cc) | Jan 29, 2023 |
| MSI           | PRO H610M-G DDR4            | [358b908129](https://linux-hardware.org/?probe=358b908129) | Jan 29, 2023 |
| MSI           | X399 SLI PLUS               | [f7008e788b](https://linux-hardware.org/?probe=f7008e788b) | Jan 29, 2023 |
| HP            | 339A                        | [5bd8bab56c](https://linux-hardware.org/?probe=5bd8bab56c) | Jan 29, 2023 |
| HP            | 8643 SMVB                   | [d9047d3c7b](https://linux-hardware.org/?probe=d9047d3c7b) | Jan 29, 2023 |
| MSI           | A68HM GRENADE               | [696581b7b6](https://linux-hardware.org/?probe=696581b7b6) | Jan 28, 2023 |
| Dell          | 0PXWHK A00                  | [1866c91eb9](https://linux-hardware.org/?probe=1866c91eb9) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [2d2e42ae23](https://linux-hardware.org/?probe=2d2e42ae23) | Jan 28, 2023 |
| MSI           | B85M-E45                    | [335cebea8b](https://linux-hardware.org/?probe=335cebea8b) | Jan 28, 2023 |
| MSI           | H410M PRO                   | [d8c1dc4e25](https://linux-hardware.org/?probe=d8c1dc4e25) | Jan 28, 2023 |
| Gigabyte      | AX370-Gaming K7             | [e369c6e5b8](https://linux-hardware.org/?probe=e369c6e5b8) | Jan 28, 2023 |
| AZW           | Gemini M                    | [5534667621](https://linux-hardware.org/?probe=5534667621) | Jan 28, 2023 |
| MSI           | H410M PRO                   | [72f5a735fb](https://linux-hardware.org/?probe=72f5a735fb) | Jan 28, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [b588302693](https://linux-hardware.org/?probe=b588302693) | Jan 28, 2023 |
| MSI           | MS-7513                     | [3953f1b447](https://linux-hardware.org/?probe=3953f1b447) | Jan 28, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [493be38a2b](https://linux-hardware.org/?probe=493be38a2b) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c67c5a3cfe](https://linux-hardware.org/?probe=c67c5a3cfe) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6cdea948c5](https://linux-hardware.org/?probe=6cdea948c5) | Jan 28, 2023 |
| ASRock        | B550M-HDV                   | [29bdcc85ad](https://linux-hardware.org/?probe=29bdcc85ad) | Jan 27, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| HP            | 805A                        | [b33510966e](https://linux-hardware.org/?probe=b33510966e) | Jan 27, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | [0d9491187e](https://linux-hardware.org/?probe=0d9491187e) | Jan 27, 2023 |
| Gigabyte      | G41MT-S2                    | [774f8eb27f](https://linux-hardware.org/?probe=774f8eb27f) | Jan 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [eec3afb06e](https://linux-hardware.org/?probe=eec3afb06e) | Jan 27, 2023 |
| HP            | 3397                        | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Dell          | 0Y2MRG A00                  | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| Gigabyte      | G41MT-S2                    | [06cd0f5943](https://linux-hardware.org/?probe=06cd0f5943) | Jan 26, 2023 |
| MSI           | X99A SLI PLUS               | [931a186515](https://linux-hardware.org/?probe=931a186515) | Jan 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [90de00d686](https://linux-hardware.org/?probe=90de00d686) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3ccebf50c2](https://linux-hardware.org/?probe=3ccebf50c2) | Jan 25, 2023 |
| ASUSTek       | P8H67-M LX                  | [b8045702e2](https://linux-hardware.org/?probe=b8045702e2) | Jan 25, 2023 |
| Medion        | MS-7728                     | [76298f7282](https://linux-hardware.org/?probe=76298f7282) | Jan 25, 2023 |
| Intel         | DG31PR AAE58249-306         | [a123c38d76](https://linux-hardware.org/?probe=a123c38d76) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | [5c1d469037](https://linux-hardware.org/?probe=5c1d469037) | Jan 25, 2023 |
| Dell          | 06D7TR A02                  | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| Medion        | MS-7728                     | [5759a31d8f](https://linux-hardware.org/?probe=5759a31d8f) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [93a260a42e](https://linux-hardware.org/?probe=93a260a42e) | Jan 25, 2023 |
| MSI           | B550-A PRO                  | [0bbf395806](https://linux-hardware.org/?probe=0bbf395806) | Jan 25, 2023 |
| Dell          | 08HPGT A01                  | [d2482dec3a](https://linux-hardware.org/?probe=d2482dec3a) | Jan 25, 2023 |
| Dell          | 08HPGT A01                  | [69fdb4710d](https://linux-hardware.org/?probe=69fdb4710d) | Jan 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [68c58308b8](https://linux-hardware.org/?probe=68c58308b8) | Jan 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [610ffedb4c](https://linux-hardware.org/?probe=610ffedb4c) | Jan 24, 2023 |
| ASUSTek       | PRIME Z690-A                | [ea5c2d01c2](https://linux-hardware.org/?probe=ea5c2d01c2) | Jan 24, 2023 |
| HP            | 339A                        | [a2784a6575](https://linux-hardware.org/?probe=a2784a6575) | Jan 24, 2023 |
| ASUSTek       | H81M-K                      | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| Dell          | 0KV62T A00                  | [6c671720a9](https://linux-hardware.org/?probe=6c671720a9) | Jan 23, 2023 |
| Dell          | 0PXWHK A00                  | [d2e447ffe9](https://linux-hardware.org/?probe=d2e447ffe9) | Jan 23, 2023 |
| Dell          | 0PXWHK A00                  | [e5ea087a6b](https://linux-hardware.org/?probe=e5ea087a6b) | Jan 23, 2023 |
| Packard Be... | EG43M                       | [92810508a2](https://linux-hardware.org/?probe=92810508a2) | Jan 23, 2023 |
| ASRock        | N68-S                       | [aeadf689c9](https://linux-hardware.org/?probe=aeadf689c9) | Jan 23, 2023 |
| MSI           | B550-A PRO                  | [88c03a1f6f](https://linux-hardware.org/?probe=88c03a1f6f) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | [08f11b861b](https://linux-hardware.org/?probe=08f11b861b) | Jan 23, 2023 |
| ASUSTek       | P8H61-I R2.0                | [37c4aa5f03](https://linux-hardware.org/?probe=37c4aa5f03) | Jan 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [8b280b4152](https://linux-hardware.org/?probe=8b280b4152) | Jan 23, 2023 |
| Dell          | 0TP406                      | [e169f52d32](https://linux-hardware.org/?probe=e169f52d32) | Jan 23, 2023 |
| HP            | 8860 A                      | [ffb17b2c42](https://linux-hardware.org/?probe=ffb17b2c42) | Jan 23, 2023 |
| MSI           | B550-A PRO                  | [683938d28b](https://linux-hardware.org/?probe=683938d28b) | Jan 23, 2023 |
| ASUSTek       | P5Q SE2                     | [8618810acb](https://linux-hardware.org/?probe=8618810acb) | Jan 23, 2023 |
| ASRock        | X99 Professional Gaming ... | [04f06d8d99](https://linux-hardware.org/?probe=04f06d8d99) | Jan 23, 2023 |
| ASRock        | 970A-G                      | [ca1bdf1d74](https://linux-hardware.org/?probe=ca1bdf1d74) | Jan 23, 2023 |
| ECS           | A55F-M4                     | [db65e68855](https://linux-hardware.org/?probe=db65e68855) | Jan 23, 2023 |
| Intel         | DG31PR AAE58249-306         | [885f180987](https://linux-hardware.org/?probe=885f180987) | Jan 23, 2023 |
| HP            | 8433 11                     | [a5c598c4c5](https://linux-hardware.org/?probe=a5c598c4c5) | Jan 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [b919144e1c](https://linux-hardware.org/?probe=b919144e1c) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [eb59dcb924](https://linux-hardware.org/?probe=eb59dcb924) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| ASUSTek       | PRIME H310M-K               | [b066912bf8](https://linux-hardware.org/?probe=b066912bf8) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | [e5fff0ebe0](https://linux-hardware.org/?probe=e5fff0ebe0) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | [8a3035382a](https://linux-hardware.org/?probe=8a3035382a) | Jan 21, 2023 |
| HP            | 339A                        | [ceba4dbf16](https://linux-hardware.org/?probe=ceba4dbf16) | Jan 21, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [869df28b6b](https://linux-hardware.org/?probe=869df28b6b) | Jan 21, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [a7ed4482ca](https://linux-hardware.org/?probe=a7ed4482ca) | Jan 21, 2023 |
| MSI           | B550-A PRO                  | [54b061790b](https://linux-hardware.org/?probe=54b061790b) | Jan 21, 2023 |
| Gigabyte      | F2A88X-D3H                  | [d88f1656dd](https://linux-hardware.org/?probe=d88f1656dd) | Jan 21, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [eb57bb7cd7](https://linux-hardware.org/?probe=eb57bb7cd7) | Jan 21, 2023 |
| MSI           | B550-A PRO                  | [633a1df7d5](https://linux-hardware.org/?probe=633a1df7d5) | Jan 21, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [db131543b4](https://linux-hardware.org/?probe=db131543b4) | Jan 21, 2023 |
| Pegatron      | NARRA5                      | [f31c67dddb](https://linux-hardware.org/?probe=f31c67dddb) | Jan 21, 2023 |
| Gigabyte      | F2A88X-D3H                  | [068fa1b678](https://linux-hardware.org/?probe=068fa1b678) | Jan 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b1dd15e0d8](https://linux-hardware.org/?probe=b1dd15e0d8) | Jan 20, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [21ee6fc910](https://linux-hardware.org/?probe=21ee6fc910) | Jan 20, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Gigabyte      | H61M-S1                     | [97987f88e7](https://linux-hardware.org/?probe=97987f88e7) | Jan 20, 2023 |
| MSI           | PH61-SP35                   | [3bdfad797c](https://linux-hardware.org/?probe=3bdfad797c) | Jan 20, 2023 |
| Gigabyte      | H81M-DS2                    | [458bb94702](https://linux-hardware.org/?probe=458bb94702) | Jan 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Linux Mint 20.3 | 1157     | 17.14%  |
| Linux Mint 20.1 | 912      | 13.51%  |
| Linux Mint 20.2 | 897      | 13.29%  |
| Linux Mint 19.3 | 861      | 12.76%  |
| Linux Mint 20   | 790      | 11.71%  |
| Linux Mint 21.1 | 610      | 9.04%   |
| Linux Mint 21   | 449      | 6.65%   |
| Linux Mint 19.1 | 402      | 5.96%   |
| Linux Mint 19.2 | 322      | 4.77%   |
| Linux Mint 19   | 154      | 2.28%   |
| Linux Mint 18.3 | 134      | 1.99%   |
| Linux Mint 18.2 | 31       | 0.46%   |
| Linux Mint 18.1 | 12       | 0.18%   |
| Linux Mint 18   | 10       | 0.15%   |
| Linux Mint 17.3 | 5        | 0.07%   |
| Linux Mint 17.1 | 2        | 0.03%   |
| Linux Mint 13   | 1        | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Mint | 6225     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-91-generic  | 236      | 3.09%   |
| 5.4.0-58-generic  | 208      | 2.73%   |
| 5.15.0-56-generic | 181      | 2.37%   |
| 5.4.0-74-generic  | 149      | 1.95%   |
| 5.4.0-42-generic  | 149      | 1.95%   |
| 5.4.0-65-generic  | 148      | 1.94%   |
| 5.4.0-77-generic  | 132      | 1.73%   |
| 5.15.0-58-generic | 132      | 1.73%   |
| 5.15.0-67-generic | 127      | 1.66%   |
| 5.15.0-60-generic | 121      | 1.59%   |
| 5.4.0-81-generic  | 115      | 1.51%   |
| 5.0.0-32-generic  | 114      | 1.49%   |
| 5.4.0-72-generic  | 113      | 1.48%   |
| 5.4.0-66-generic  | 112      | 1.47%   |
| 5.4.0-88-generic  | 110      | 1.44%   |
| 4.15.0-54-generic | 107      | 1.4%    |
| 5.4.0-90-generic  | 105      | 1.38%   |
| 5.4.0-70-generic  | 105      | 1.38%   |
| 5.4.0-122-generic | 105      | 1.38%   |
| 5.4.0-107-generic | 104      | 1.36%   |
| 5.4.0-73-generic  | 102      | 1.34%   |
| 4.15.0-20-generic | 102      | 1.34%   |
| 5.4.0-80-generic  | 98       | 1.28%   |
| 5.15.0-69-generic | 97       | 1.27%   |
| 5.4.0-89-generic  | 91       | 1.19%   |
| 5.15.0-52-generic | 90       | 1.18%   |
| 5.4.0-100-generic | 89       | 1.17%   |
| 5.4.0-26-generic  | 84       | 1.1%    |
| 5.4.0-109-generic | 80       | 1.05%   |
| 5.4.0-48-generic  | 76       | 1%      |
| 5.4.0-121-generic | 75       | 0.98%   |
| 4.15.0-46-generic | 70       | 0.92%   |
| 5.15.0-41-generic | 67       | 0.88%   |
| 5.4.0-52-generic  | 63       | 0.83%   |
| 5.15.0-48-generic | 63       | 0.83%   |
| 5.4.0-96-generic  | 62       | 0.81%   |
| 5.4.0-104-generic | 58       | 0.76%   |
| 5.4.0-84-generic  | 57       | 0.75%   |
| 5.4.0-113-generic | 57       | 0.75%   |
| 5.3.0-46-generic  | 57       | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 3452     | 52.14%  |
| 5.15.0  | 1054     | 15.92%  |
| 4.15.0  | 897      | 13.55%  |
| 5.3.0   | 355      | 5.36%   |
| 5.0.0   | 190      | 2.87%   |
| 5.13.0  | 125      | 1.89%   |
| 5.8.0   | 99       | 1.5%    |
| 5.11.0  | 71       | 1.07%   |
| 5.19.0  | 47       | 0.71%   |
| 4.4.0   | 36       | 0.54%   |
| 4.10.0  | 35       | 0.53%   |
| 4.13.0  | 26       | 0.39%   |
| 4.18.0  | 23       | 0.35%   |
| 4.8.0   | 15       | 0.23%   |
| 5.14.0  | 12       | 0.18%   |
| 6.0.0   | 8        | 0.12%   |
| 5.17.0  | 6        | 0.09%   |
| 6.1.0   | 5        | 0.08%   |
| 5.9.0   | 5        | 0.08%   |
| 5.10.0  | 5        | 0.08%   |
| 5.3.6   | 4        | 0.06%   |
| 5.4.1   | 3        | 0.05%   |
| 5.16.0  | 3        | 0.05%   |
| 5.12.0  | 3        | 0.05%   |
| 5.0.9   | 3        | 0.05%   |
| 4.20.17 | 3        | 0.05%   |
| 4.11.0  | 3        | 0.05%   |
| 6.2.8   | 2        | 0.03%   |
| 6.2.12  | 2        | 0.03%   |
| 6.2.0   | 2        | 0.03%   |
| 5.8.18  | 2        | 0.03%   |
| 5.7.19  | 2        | 0.03%   |
| 5.7.0   | 2        | 0.03%   |
| 5.18.12 | 2        | 0.03%   |
| 5.17.9  | 2        | 0.03%   |
| 5.15.5  | 2        | 0.03%   |
| 5.15.10 | 2        | 0.03%   |
| 5.13.4  | 2        | 0.03%   |
| 5.12.9  | 2        | 0.03%   |
| 5.11.6  | 2        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 3458     | 52.25%  |
| 5.15    | 1065     | 16.09%  |
| 4.15    | 898      | 13.57%  |
| 5.3     | 361      | 5.45%   |
| 5.0     | 201      | 3.04%   |
| 5.13    | 128      | 1.93%   |
| 5.8     | 103      | 1.56%   |
| 5.11    | 77       | 1.16%   |
| 5.19    | 50       | 0.76%   |
| 4.4     | 36       | 0.54%   |
| 4.10    | 35       | 0.53%   |
| 4.13    | 27       | 0.41%   |
| 4.18    | 24       | 0.36%   |
| 4.8     | 15       | 0.23%   |
| 5.10    | 14       | 0.21%   |
| 5.17    | 13       | 0.2%    |
| 5.14    | 13       | 0.2%    |
| 6.2     | 11       | 0.17%   |
| 6.1     | 11       | 0.17%   |
| 6.0     | 11       | 0.17%   |
| 5.9     | 8        | 0.12%   |
| 5.7     | 8        | 0.12%   |
| 4.20    | 8        | 0.12%   |
| 5.16    | 6        | 0.09%   |
| 5.12    | 5        | 0.08%   |
| 5.18    | 4        | 0.06%   |
| 5.6     | 3        | 0.05%   |
| 5.5     | 3        | 0.05%   |
| 5.2     | 3        | 0.05%   |
| 4.14    | 3        | 0.05%   |
| 4.11    | 3        | 0.05%   |
| 4.19    | 2        | 0.03%   |
| 4.16    | 2        | 0.03%   |
| 4.12    | 2        | 0.03%   |
| 3.19    | 2        | 0.03%   |
| 3.13    | 2        | 0.03%   |
| 4.17    | 1        | 0.02%   |
| 3.2     | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 6039     | 96.92%  |
| i686   | 192      | 3.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| X-Cinnamon      | 3786     | 59.02%  |
| MATE            | 810      | 12.63%  |
| Cinnamon        | 558      | 8.7%    |
| XFCE            | 544      | 8.48%   |
| Unknown         | 531      | 8.28%   |
| GNOME           | 117      | 1.82%   |
| KDE5            | 26       | 0.41%   |
| KDE             | 21       | 0.33%   |
| LXDE            | 7        | 0.11%   |
| Pantheon        | 2        | 0.03%   |
| KDE4            | 2        | 0.03%   |
| i3              | 2        | 0.03%   |
| Budgie          | 2        | 0.03%   |
| Trinity         | 1        | 0.02%   |
| qtile           | 1        | 0.02%   |
| LXQt            | 1        | 0.02%   |
| ICEWM           | 1        | 0.02%   |
| GNOME Flashback | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| enlightenment   | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 6182     | 99.2%   |
| Tty     | 36       | 0.58%   |
| Wayland | 11       | 0.18%   |
| Unknown | 3        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4041     | 63.78%  |
| LightDM | 1437     | 22.68%  |
| TDM     | 775      | 12.23%  |
| MDM     | 42       | 0.66%   |
| SDDM    | 23       | 0.36%   |
| GDM     | 15       | 0.24%   |
| LXDM    | 2        | 0.03%   |
| GDM3    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1603     | 25.35%  |
| de_DE   | 909      | 14.38%  |
| Unknown | 683      | 10.8%   |
| pt_BR   | 488      | 7.72%   |
| ru_RU   | 274      | 4.33%   |
| fr_FR   | 272      | 4.3%    |
| en_GB   | 267      | 4.22%   |
| it_IT   | 184      | 2.91%   |
| en_CA   | 161      | 2.55%   |
| C       | 150      | 2.37%   |
| es_ES   | 145      | 2.29%   |
| en_AU   | 122      | 1.93%   |
| pl_PL   | 111      | 1.76%   |
| nl_NL   | 80       | 1.27%   |
| es_AR   | 66       | 1.04%   |
| cs_CZ   | 44       | 0.7%    |
| pt_PT   | 43       | 0.68%   |
| hu_HU   | 39       | 0.62%   |
| ru_UA   | 37       | 0.59%   |
| es_MX   | 37       | 0.59%   |
| de_AT   | 36       | 0.57%   |
| en_IN   | 33       | 0.52%   |
| en_ZA   | 31       | 0.49%   |
| fi_FI   | 30       | 0.47%   |
| sk_SK   | 28       | 0.44%   |
| de_CH   | 28       | 0.44%   |
| sv_SE   | 26       | 0.41%   |
| fr_CA   | 25       | 0.4%    |
| en_NZ   | 23       | 0.36%   |
| fr_BE   | 21       | 0.33%   |
| uk_UA   | 18       | 0.28%   |
| tr_TR   | 17       | 0.27%   |
| en_IE   | 17       | 0.27%   |
| el_GR   | 17       | 0.27%   |
| es_CO   | 16       | 0.25%   |
| nl_BE   | 15       | 0.24%   |
| es_CL   | 15       | 0.24%   |
| es_VE   | 14       | 0.22%   |
| ja_JP   | 13       | 0.21%   |
| en_PH   | 13       | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3825     | 60.46%  |
| EFI  | 2501     | 39.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 5480     | 86.67%  |
| Unknown | 512      | 8.1%    |
| Btrfs   | 129      | 2.04%   |
| Overlay | 127      | 2.01%   |
| Xfs     | 24       | 0.38%   |
| Ext2    | 18       | 0.28%   |
| Zfs     | 14       | 0.22%   |
| Ext3    | 14       | 0.22%   |
| Jfs     | 2        | 0.03%   |
| Aufs    | 2        | 0.03%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4120     | 65.21%  |
| GPT     | 1406     | 22.25%  |
| MBR     | 792      | 12.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5687     | 90.41%  |
| Yes       | 603      | 9.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5034     | 79.85%  |
| Yes       | 1270     | 20.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1513     | 24.31%  |
| Gigabyte Technology | 1064     | 17.09%  |
| MSI                 | 645      | 10.36%  |
| ASRock              | 582      | 9.35%   |
| Dell                | 522      | 8.39%   |
| Hewlett-Packard     | 479      | 7.69%   |
| Lenovo              | 212      | 3.41%   |
| Intel               | 180      | 2.89%   |
| Acer                | 118      | 1.9%    |
| Pegatron            | 98       | 1.57%   |
| Unknown             | 77       | 1.24%   |
| Foxconn             | 75       | 1.2%    |
| Biostar             | 70       | 1.12%   |
| ECS                 | 62       | 1%      |
| Fujitsu             | 59       | 0.95%   |
| Medion              | 49       | 0.79%   |
| Positivo            | 33       | 0.53%   |
| Fujitsu Siemens     | 27       | 0.43%   |
| PCWare              | 21       | 0.34%   |
| Apple               | 18       | 0.29%   |
| AZW                 | 17       | 0.27%   |
| Gateway             | 16       | 0.26%   |
| Shuttle             | 15       | 0.24%   |
| Packard Bell        | 13       | 0.21%   |
| OEM                 | 13       | 0.21%   |
| BESSTAR Tech        | 13       | 0.21%   |
| Semp Toshiba        | 12       | 0.19%   |
| eMachines           | 12       | 0.19%   |
| AMI                 | 12       | 0.19%   |
| Inventec            | 11       | 0.18%   |
| Huanan              | 11       | 0.18%   |
| AMD                 | 11       | 0.18%   |
| Alienware           | 9        | 0.14%   |
| Supermicro          | 8        | 0.13%   |
| Itautec             | 8        | 0.13%   |
| Megaware            | 5        | 0.08%   |
| ABIT                | 5        | 0.08%   |
| Wistron             | 4        | 0.06%   |
| TYAN Computer       | 4        | 0.06%   |
| PCChips             | 4        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 133      | 2.14%   |
| Unknown                      | 89       | 1.43%   |
| Dell OptiPlex 790            | 31       | 0.5%    |
| Dell OptiPlex 780            | 31       | 0.5%    |
| Dell OptiPlex 7010           | 30       | 0.48%   |
| MSI MS-7693                  | 29       | 0.47%   |
| Gigabyte B450M DS3H          | 28       | 0.45%   |
| ASUS M5A78L-M/USB3           | 28       | 0.45%   |
| ASUS TUF Gaming X570-PLUS    | 26       | 0.42%   |
| ASUS PRIME A320M-K           | 26       | 0.42%   |
| MSI MS-7C37                  | 24       | 0.39%   |
| MSI MS-7C56                  | 23       | 0.37%   |
| MSI MS-7C02                  | 23       | 0.37%   |
| MSI MS-7817                  | 22       | 0.35%   |
| Dell OptiPlex 3020           | 22       | 0.35%   |
| MSI MS-7B86                  | 21       | 0.34%   |
| MSI MS-7721                  | 21       | 0.34%   |
| Dell OptiPlex 755            | 21       | 0.34%   |
| Dell OptiPlex 9020           | 20       | 0.32%   |
| HP Compaq Elite 8300 SFF     | 19       | 0.31%   |
| Dell OptiPlex 3010           | 19       | 0.31%   |
| Dell OptiPlex 990            | 18       | 0.29%   |
| Dell OptiPlex 390            | 18       | 0.29%   |
| ASUS ROG STRIX B450-F GAMING | 18       | 0.29%   |
| ASUS M5A97 R2.0              | 18       | 0.29%   |
| Gigabyte 970A-DS3P           | 17       | 0.27%   |
| MSI MS-7641                  | 16       | 0.26%   |
| Intel H61                    | 16       | 0.26%   |
| HP EliteDesk 800 G1 SFF      | 16       | 0.26%   |
| HP Compaq 8200 Elite SFF PC  | 16       | 0.26%   |
| ASUS SABERTOOTH 990FX R2.0   | 16       | 0.26%   |
| ASUS M5A78L-M PLUS/USB3      | 16       | 0.26%   |
| MSI MS-7C91                  | 15       | 0.24%   |
| MSI MS-7B79                  | 15       | 0.24%   |
| Gigabyte A320M-S2H           | 15       | 0.24%   |
| Gigabyte GA-78LMT-USB3       | 14       | 0.22%   |
| Gigabyte G31M-ES2L           | 14       | 0.22%   |
| Dell OptiPlex 745            | 14       | 0.22%   |
| ASRock N68C-S UCC            | 14       | 0.22%   |
| ASRock B450M Pro4            | 14       | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 324      | 5.2%    |
| ASUS PRIME             | 230      | 3.69%   |
| HP Compaq              | 213      | 3.42%   |
| Lenovo ThinkCentre     | 141      | 2.27%   |
| ASUS All               | 133      | 2.14%   |
| ASUS ROG               | 107      | 1.72%   |
| ASUS TUF               | 97       | 1.56%   |
| Unknown                | 89       | 1.43%   |
| Acer Aspire            | 80       | 1.29%   |
| Dell Inspiron          | 72       | 1.16%   |
| ASUS M5A78L-M          | 71       | 1.14%   |
| HP EliteDesk           | 57       | 0.92%   |
| Dell Precision         | 55       | 0.88%   |
| Fujitsu ESPRIMO        | 42       | 0.67%   |
| ASUS P8H61-M           | 42       | 0.67%   |
| HP ProDesk             | 41       | 0.66%   |
| ASUS M5A97             | 40       | 0.64%   |
| Gigabyte B450M         | 39       | 0.63%   |
| Gigabyte B450          | 38       | 0.61%   |
| Gigabyte GA-78LMT-USB3 | 34       | 0.55%   |
| ASUS SABERTOOTH        | 33       | 0.53%   |
| ASRock B450M           | 30       | 0.48%   |
| MSI MS-7693            | 29       | 0.47%   |
| Gigabyte X570          | 28       | 0.45%   |
| HP Pavilion            | 27       | 0.43%   |
| Lenovo IdeaCentre      | 25       | 0.4%    |
| MSI MS-7C37            | 24       | 0.39%   |
| Gigabyte B550          | 24       | 0.39%   |
| Acer Veriton           | 24       | 0.39%   |
| MSI MS-7C56            | 23       | 0.37%   |
| MSI MS-7C02            | 23       | 0.37%   |
| MSI MS-7817            | 22       | 0.35%   |
| Gigabyte A320M-S2H     | 22       | 0.35%   |
| MSI MS-7B86            | 21       | 0.34%   |
| MSI MS-7721            | 21       | 0.34%   |
| Dell Vostro            | 21       | 0.34%   |
| Gigabyte Z390          | 20       | 0.32%   |
| Dell XPS               | 20       | 0.32%   |
| ASUS P5G41T-M          | 20       | 0.32%   |
| Gigabyte 970A-DS3P     | 19       | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 684      | 10.99%  |
| 2011    | 568      | 9.12%   |
| 2013    | 543      | 8.72%   |
| 2018    | 537      | 8.63%   |
| 2009    | 424      | 6.81%   |
| 2010    | 411      | 6.6%    |
| 2014    | 406      | 6.52%   |
| 2020    | 381      | 6.12%   |
| 2019    | 352      | 5.65%   |
| 2017    | 342      | 5.49%   |
| 2008    | 318      | 5.11%   |
| 2015    | 269      | 4.32%   |
| 2007    | 264      | 4.24%   |
| 2016    | 253      | 4.06%   |
| 2021    | 209      | 3.36%   |
| 2006    | 121      | 1.94%   |
| 2022    | 76       | 1.22%   |
| 2005    | 33       | 0.53%   |
| 2004    | 14       | 0.22%   |
| 2003    | 11       | 0.18%   |
| 2023    | 4        | 0.06%   |
| 2002    | 3        | 0.05%   |
| Unknown | 2        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 6225     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6037     | 96.68%  |
| Enabled  | 207      | 3.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6222     | 99.95%  |
| Yes  | 3        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1471     | 23.17%  |
| 8.01-16.0       | 1319     | 20.77%  |
| 3.01-4.0        | 1146     | 18.05%  |
| 4.01-8.0        | 1043     | 16.43%  |
| 32.01-64.0      | 696      | 10.96%  |
| 1.01-2.0        | 258      | 4.06%   |
| 64.01-256.0     | 161      | 2.54%   |
| 24.01-32.0      | 114      | 1.8%    |
| 2.01-3.0        | 106      | 1.67%   |
| 0.51-1.0        | 32       | 0.5%    |
| More than 256.0 | 2        | 0.03%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 2684     | 38.28%  |
| 2.01-3.0   | 1846     | 26.33%  |
| 4.01-8.0   | 850      | 12.12%  |
| 3.01-4.0   | 832      | 11.87%  |
| 0.51-1.0   | 528      | 7.53%   |
| 8.01-16.0  | 207      | 2.95%   |
| 16.01-24.0 | 24       | 0.34%   |
| 0.01-0.5   | 22       | 0.31%   |
| 24.01-32.0 | 12       | 0.17%   |
| 32.01-64.0 | 3        | 0.04%   |
| Unknown    | 3        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2586     | 39.84%  |
| 2       | 1917     | 29.53%  |
| 3       | 1007     | 15.51%  |
| 4       | 523      | 8.06%   |
| 5       | 237      | 3.65%   |
| 6       | 98       | 1.51%   |
| 7       | 49       | 0.75%   |
| 0       | 32       | 0.49%   |
| 8       | 23       | 0.35%   |
| 9       | 10       | 0.15%   |
| 10      | 4        | 0.06%   |
| 14      | 2        | 0.03%   |
| 28      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3572     | 56.72%  |
| No        | 2726     | 43.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6148     | 98.73%  |
| No        | 79       | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3613     | 57.19%  |
| Yes       | 2704     | 42.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4647     | 73.44%  |
| Yes       | 1681     | 26.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1098     | 17.56%  |
| Germany      | 1013     | 16.2%   |
| Brazil       | 694      | 11.1%   |
| Russia       | 402      | 6.43%   |
| France       | 292      | 4.67%   |
| UK           | 262      | 4.19%   |
| Canada       | 224      | 3.58%   |
| Italy        | 207      | 3.31%   |
| Spain        | 174      | 2.78%   |
| Netherlands  | 140      | 2.24%   |
| Australia    | 138      | 2.21%   |
| Poland       | 135      | 2.16%   |
| Ukraine      | 111      | 1.77%   |
| Argentina    | 74       | 1.18%   |
| Switzerland  | 65       | 1.04%   |
| Belgium      | 61       | 0.98%   |
| Austria      | 61       | 0.98%   |
| Sweden       | 56       | 0.9%    |
| Czechia      | 56       | 0.9%    |
| Mexico       | 52       | 0.83%   |
| Hungary      | 52       | 0.83%   |
| Portugal     | 46       | 0.74%   |
| Finland      | 42       | 0.67%   |
| India        | 40       | 0.64%   |
| Greece       | 39       | 0.62%   |
| South Africa | 38       | 0.61%   |
| Slovakia     | 32       | 0.51%   |
| Romania      | 32       | 0.51%   |
| Denmark      | 31       | 0.5%    |
| Turkey       | 30       | 0.48%   |
| Colombia     | 27       | 0.43%   |
| Belarus      | 27       | 0.43%   |
| New Zealand  | 26       | 0.42%   |
| Japan        | 24       | 0.38%   |
| Bulgaria     | 22       | 0.35%   |
| Norway       | 21       | 0.34%   |
| Serbia       | 20       | 0.32%   |
| Ireland      | 20       | 0.32%   |
| Chile        | 19       | 0.3%    |
| Israel       | 18       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sao Paulo         | 81       | 1.22%   |
| Moscow            | 77       | 1.16%   |
| Berlin            | 67       | 1.01%   |
| Hamburg           | 45       | 0.68%   |
| Rio de Janeiro    | 41       | 0.62%   |
| Vienna            | 37       | 0.56%   |
| St Petersburg     | 34       | 0.51%   |
| Paris             | 34       | 0.51%   |
| Munich            | 33       | 0.5%    |
| Sydney            | 31       | 0.47%   |
| Frankfurt am Main | 31       | 0.47%   |
| Madrid            | 30       | 0.45%   |
| Montreal          | 29       | 0.44%   |
| Amsterdam         | 29       | 0.44%   |
| London            | 28       | 0.42%   |
| Warsaw            | 26       | 0.39%   |
| Rome              | 25       | 0.38%   |
| Kyiv              | 25       | 0.38%   |
| Cologne           | 23       | 0.35%   |
| Chicago           | 23       | 0.35%   |
| Melbourne         | 22       | 0.33%   |
| Budapest          | 22       | 0.33%   |
| Brisbane          | 21       | 0.32%   |
| Brasília         | 21       | 0.32%   |
| Perth             | 20       | 0.3%    |
| Athens            | 20       | 0.3%    |
| Vancouver         | 19       | 0.29%   |
| Toronto           | 19       | 0.29%   |
| New York          | 19       | 0.29%   |
| Leipzig           | 19       | 0.29%   |
| Stockholm         | 17       | 0.26%   |
| Helsinki          | 17       | 0.26%   |
| Porto Alegre      | 16       | 0.24%   |
| Milan             | 16       | 0.24%   |
| Düsseldorf       | 16       | 0.24%   |
| Dresden           | 16       | 0.24%   |
| Barcelona         | 16       | 0.24%   |
| Zurich            | 15       | 0.23%   |
| Minsk             | 15       | 0.23%   |
| Belgrade          | 15       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 2326     | 3943   | 20.81%  |
| Seagate                   | 2267     | 3730   | 20.28%  |
| Samsung Electronics       | 1595     | 2581   | 14.27%  |
| Kingston                  | 696      | 964    | 6.23%   |
| Toshiba                   | 523      | 710    | 4.68%   |
| Crucial                   | 471      | 665    | 4.21%   |
| Hitachi                   | 459      | 612    | 4.11%   |
| SanDisk                   | 453      | 637    | 4.05%   |
| A-DATA Technology         | 160      | 215    | 1.43%   |
| Intel                     | 138      | 192    | 1.23%   |
| Maxtor                    | 131      | 180    | 1.17%   |
| China                     | 131      | 157    | 1.17%   |
| Unknown                   | 117      | 198    | 1.05%   |
| HGST                      | 111      | 161    | 0.99%   |
| Intenso                   | 95       | 130    | 0.85%   |
| Phison                    | 74       | 106    | 0.66%   |
| SPCC                      | 68       | 92     | 0.61%   |
| OCZ                       | 68       | 88     | 0.61%   |
| PNY                       | 66       | 86     | 0.59%   |
| Patriot                   | 63       | 76     | 0.56%   |
| Corsair                   | 56       | 67     | 0.5%    |
| Silicon Motion            | 54       | 82     | 0.48%   |
| Transcend                 | 48       | 73     | 0.43%   |
| Micron Technology         | 46       | 54     | 0.41%   |
| SK hynix                  | 44       | 56     | 0.39%   |
| GOODRAM                   | 39       | 51     | 0.35%   |
| Micron/Crucial Technology | 38       | 54     | 0.34%   |
| JMicron Technology        | 34       | 46     | 0.3%    |
| Apacer                    | 29       | 33     | 0.26%   |
| XPG                       | 28       | 40     | 0.25%   |
| Team                      | 27       | 38     | 0.24%   |
| Unknown                   | 27       | 39     | 0.24%   |
| Fujitsu                   | 26       | 35     | 0.23%   |
| Plextor                   | 25       | 34     | 0.22%   |
| Lexar                     | 25       | 31     | 0.22%   |
| Realtek Semiconductor     | 22       | 28     | 0.2%    |
| ASMT                      | 22       | 33     | 0.2%    |
| KingSpec                  | 21       | 34     | 0.19%   |
| Phison Electronics        | 18       | 22     | 0.16%   |
| Hewlett-Packard           | 18       | 21     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 193      | 1.49%   |
| Kingston SA400S37240G 240GB SSD                   | 171      | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB                    | 131      | 1.01%   |
| Samsung SSD 850 EVO 250GB                         | 130      | 1%      |
| Toshiba DT01ACA100 1TB                            | 126      | 0.97%   |
| Samsung SSD 860 EVO 500GB                         | 108      | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 98       | 0.76%   |
| Kingston SA400S37120G 120GB SSD                   | 94       | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                    | 91       | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB                    | 90       | 0.69%   |
| Seagate ST3500418AS 500GB                         | 89       | 0.69%   |
| Kingston SV300S37A120G 120GB SSD                  | 84       | 0.65%   |
| Samsung SSD 850 EVO 500GB                         | 82       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                    | 77       | 0.59%   |
| Samsung SSD 860 EVO 1TB                           | 75       | 0.58%   |
| Kingston SA400S37480G 480GB SSD                   | 70       | 0.54%   |
| Crucial CT240BX500SSD1 240GB                      | 69       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                       | 67       | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB                    | 66       | 0.51%   |
| Samsung SSD 860 EVO 250GB                         | 66       | 0.51%   |
| Crucial CT500MX500SSD1 500GB                      | 66       | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 64       | 0.49%   |
| Seagate ST31000528AS 1TB                          | 59       | 0.46%   |
| Seagate ST31000524AS 1TB                          | 58       | 0.45%   |
| Samsung NVMe SSD Drive 500GB                      | 57       | 0.44%   |
| Toshiba HDWD110 1TB                               | 56       | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB                    | 54       | 0.42%   |
| Seagate Expansion 4TB                             | 52       | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 49       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 49       | 0.38%   |
| Toshiba DT01ACA200 2TB                            | 49       | 0.38%   |
| Unknown SD/MMC/MS PRO 249GB                       | 48       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB                    | 48       | 0.37%   |
| Toshiba DT01ACA050 500GB                          | 47       | 0.36%   |
| Seagate ST3500413AS 500GB                         | 47       | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                    | 46       | 0.36%   |
| SanDisk SSD PLUS 240GB                            | 46       | 0.36%   |
| SanDisk SDSSDA240G 240GB                          | 43       | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB                    | 40       | 0.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 40       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2230     | 3632   | 35.95%  |
| WDC                 | 2090     | 3522   | 33.69%  |
| Toshiba             | 488      | 655    | 7.87%   |
| Samsung Electronics | 487      | 701    | 7.85%   |
| Hitachi             | 459      | 612    | 7.4%    |
| Maxtor              | 128      | 177    | 2.06%   |
| HGST                | 111      | 161    | 1.79%   |
| Unknown             | 56       | 73     | 0.9%    |
| Fujitsu             | 25       | 34     | 0.4%    |
| JMicron Technology  | 22       | 33     | 0.35%   |
| Intenso             | 13       | 16     | 0.21%   |
| ASMT                | 10       | 18     | 0.16%   |
| ASMedia             | 9        | 11     | 0.15%   |
| ExcelStor           | 7        | 9      | 0.11%   |
| WD MediaMax         | 6        | 14     | 0.1%    |
| Hewlett-Packard     | 6        | 7      | 0.1%    |
| USB3.0              | 4        | 4      | 0.06%   |
| Pioneer             | 4        | 5      | 0.06%   |
| Apple               | 4        | 4      | 0.06%   |
| HPE                 | 3        | 4      | 0.05%   |
| HGST HTS            | 3        | 4      | 0.05%   |
| ASMT109x            | 3        | 3      | 0.05%   |
| SAGE                | 2        | 2      | 0.03%   |
| SABRENT             | 2        | 2      | 0.03%   |
| RSH-319             | 2        | 2      | 0.03%   |
| PHD 3.0             | 2        | 3      | 0.03%   |
| Maxtor 6            | 2        | 3      | 0.03%   |
| Maxone              | 2        | 2      | 0.03%   |
| LaCie               | 2        | 2      | 0.03%   |
| KESU                | 2        | 3      | 0.03%   |
| Unknown             | 2        | 4      | 0.03%   |
| USB 3.0             | 1        | 4      | 0.02%   |
| USB                 | 1        | 1      | 0.02%   |
| TrueNAS             | 1        | 3      | 0.02%   |
| TANDBERG            | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| Storeva             | 1        | 1      | 0.02%   |
| Quantum             | 1        | 1      | 0.02%   |
| MaxDigital          | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 841      | 1289   | 21.93%  |
| Kingston            | 608      | 837    | 15.85%  |
| Crucial             | 436      | 616    | 11.37%  |
| SanDisk             | 362      | 504    | 9.44%   |
| WDC                 | 260      | 351    | 6.78%   |
| A-DATA Technology   | 130      | 174    | 3.39%   |
| China               | 129      | 155    | 3.36%   |
| Intel               | 77       | 100    | 2.01%   |
| Intenso             | 69       | 94     | 1.8%    |
| OCZ                 | 67       | 86     | 1.75%   |
| SPCC                | 63       | 87     | 1.64%   |
| PNY                 | 60       | 79     | 1.56%   |
| Patriot             | 60       | 73     | 1.56%   |
| Transcend           | 43       | 60     | 1.12%   |
| GOODRAM             | 38       | 50     | 0.99%   |
| Corsair             | 38       | 45     | 0.99%   |
| Toshiba             | 35       | 46     | 0.91%   |
| Micron Technology   | 32       | 39     | 0.83%   |
| Apacer              | 26       | 30     | 0.68%   |
| Team                | 25       | 36     | 0.65%   |
| Lexar               | 23       | 29     | 0.6%    |
| Plextor             | 22       | 28     | 0.57%   |
| SK hynix            | 21       | 25     | 0.55%   |
| KingSpec            | 20       | 33     | 0.52%   |
| Unknown             | 18       | 27     | 0.47%   |
| Seagate             | 15       | 26     | 0.39%   |
| LITEON              | 15       | 17     | 0.39%   |
| TO Exter            | 14       | 20     | 0.37%   |
| KingDian            | 11       | 14     | 0.29%   |
| ASMT                | 11       | 14     | 0.29%   |
| AMD                 | 11       | 12     | 0.29%   |
| LITEONIT            | 10       | 10     | 0.26%   |
| Leven               | 10       | 10     | 0.26%   |
| Verbatim            | 9        | 11     | 0.23%   |
| Hewlett-Packard     | 9        | 11     | 0.23%   |
| Smartbuy            | 8        | 12     | 0.21%   |
| Netac               | 8        | 14     | 0.21%   |
| Mushkin             | 8        | 11     | 0.21%   |
| Gigabyte Technology | 8        | 17     | 0.21%   |
| INNOVATION IT       | 6        | 8      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4671     | 9746   | 50.77%  |
| SSD     | 3207     | 5314   | 34.85%  |
| NVMe    | 1107     | 1661   | 12.03%  |
| Unknown | 183      | 276    | 1.99%   |
| MMC     | 33       | 47     | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5868     | 14542  | 78.15%  |
| NVMe | 1098     | 1642   | 14.62%  |
| SAS  | 510      | 813    | 6.79%   |
| MMC  | 33       | 47     | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 4522     | 8348   | 52.43%  |
| 0.51-1.0   | 2398     | 3835   | 27.8%   |
| 1.01-2.0   | 937      | 1583   | 10.86%  |
| 3.01-4.0   | 318      | 549    | 3.69%   |
| 2.01-3.0   | 234      | 371    | 2.71%   |
| 4.01-10.0  | 177      | 289    | 2.05%   |
| 10.01-20.0 | 37       | 83     | 0.43%   |
| 0          | 2        | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1651     | 24.92%  |
| 251-500        | 1302     | 19.66%  |
| 501-1000       | 1088     | 16.43%  |
| 1001-2000      | 822      | 12.41%  |
| More than 3000 | 656      | 9.9%    |
| 2001-3000      | 397      | 5.99%   |
| 51-100         | 378      | 5.71%   |
| 21-50          | 165      | 2.49%   |
| 1-20           | 122      | 1.84%   |
| Unknown        | 43       | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1494     | 21.6%   |
| 21-50          | 1299     | 18.78%  |
| 101-250        | 1005     | 14.53%  |
| 51-100         | 913      | 13.2%   |
| 251-500        | 649      | 9.38%   |
| 501-1000       | 637      | 9.21%   |
| 1001-2000      | 432      | 6.25%   |
| More than 3000 | 259      | 3.74%   |
| 2001-3000      | 186      | 2.69%   |
| Unknown        | 43       | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 26       | 26     | 3.38%   |
| Seagate ST3500418AS 500GB             | 17       | 19     | 2.21%   |
| Seagate ST31000528AS 1TB              | 9        | 11     | 1.17%   |
| Seagate ST1000DM003-9YN162 1TB        | 7        | 8      | 0.91%   |
| WDC WD10EARS-00Y5B1 1TB               | 6        | 6      | 0.78%   |
| Seagate ST3500320AS 500GB             | 6        | 8      | 0.78%   |
| Seagate ST31000524AS 1TB              | 6        | 7      | 0.78%   |
| Crucial CT525MX300SSD1 528GB          | 6        | 6      | 0.78%   |
| WDC WD10EZEX-00BN5A0 1TB              | 5        | 6      | 0.65%   |
| Toshiba DT01ACA100 1TB                | 5        | 6      | 0.65%   |
| Seagate ST3250318AS 250GB             | 5        | 6      | 0.65%   |
| Seagate ST2000DM001-9YN164 2TB        | 5        | 5      | 0.65%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.65%   |
| Seagate ST1500DL003-9VT16L 1TB        | 5        | 5      | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB        | 5        | 6      | 0.65%   |
| Samsung Electronics HD502HI 500GB     | 5        | 5      | 0.65%   |
| Samsung Electronics HD322HJ 320GB     | 5        | 11     | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 4        | 4      | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB           | 4        | 5      | 0.52%   |
| WDC WD5000AAKS-00A7B0 500GB           | 4        | 4      | 0.52%   |
| WDC WD3200AAJS-00L7A0 320GB           | 4        | 4      | 0.52%   |
| Seagate ST9500325AS 500GB             | 4        | 4      | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 4        | 4      | 0.52%   |
| Seagate ST3500413AS 500GB             | 4        | 6      | 0.52%   |
| Seagate ST320LT012-1DG14C 320GB       | 4        | 4      | 0.52%   |
| Seagate ST31500341AS 1TB              | 4        | 5      | 0.52%   |
| Seagate ST31000333AS 1TB              | 4        | 4      | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB        | 4        | 5      | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB        | 4        | 4      | 0.52%   |
| Seagate ST2000DL003-9VT166 2TB        | 4        | 5      | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB        | 4        | 5      | 0.52%   |
| Samsung Electronics SSD 970 EVO 500GB | 4        | 5      | 0.52%   |
| Samsung Electronics HD501LJ 500GB     | 4        | 7      | 0.52%   |
| Samsung Electronics HD161HJ 160GB     | 4        | 4      | 0.52%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 4      | 0.52%   |
| Maxtor STM3250310AS 250GB             | 4        | 5      | 0.52%   |
| Hitachi HDS721010CLA332 1TB           | 4        | 4      | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3        | 3      | 0.39%   |
| WDC WD5000AAKX-003CA0 500GB           | 3        | 3      | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB              | 3        | 6      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 230      | 277    | 31.72%  |
| WDC                 | 199      | 253    | 27.45%  |
| Samsung Electronics | 78       | 97     | 10.76%  |
| Hitachi             | 54       | 64     | 7.45%   |
| Toshiba             | 25       | 26     | 3.45%   |
| Maxtor              | 21       | 27     | 2.9%    |
| Crucial             | 17       | 18     | 2.34%   |
| SanDisk             | 16       | 17     | 2.21%   |
| Kingston            | 15       | 17     | 2.07%   |
| Intel               | 8        | 8      | 1.1%    |
| Corsair             | 6        | 9      | 0.83%   |
| OCZ                 | 5        | 6      | 0.69%   |
| HGST                | 5        | 5      | 0.69%   |
| China               | 5        | 6      | 0.69%   |
| A-DATA Technology   | 5        | 5      | 0.69%   |
| SPCC                | 3        | 4      | 0.41%   |
| Intenso             | 3        | 3      | 0.41%   |
| Transcend           | 2        | 2      | 0.28%   |
| SK hynix            | 2        | 2      | 0.28%   |
| Plextor             | 2        | 2      | 0.28%   |
| Micron Technology   | 2        | 3      | 0.28%   |
| LITEONIT            | 2        | 2      | 0.28%   |
| Leven               | 2        | 2      | 0.28%   |
| LDLC                | 2        | 2      | 0.28%   |
| Kingmax             | 2        | 2      | 0.28%   |
| XPG                 | 1        | 2      | 0.14%   |
| USB3.0              | 1        | 1      | 0.14%   |
| Unknown             | 1        | 1      | 0.14%   |
| Team                | 1        | 1      | 0.14%   |
| s60                 | 1        | 1      | 0.14%   |
| Mushkin             | 1        | 1      | 0.14%   |
| HS-SSD-E100         | 1        | 1      | 0.14%   |
| Hewlett-Packard     | 1        | 1      | 0.14%   |
| G.Skill             | 1        | 1      | 0.14%   |
| Fujitsu             | 1        | 2      | 0.14%   |
| FEASSO              | 1        | 2      | 0.14%   |
| ExcelStor           | 1        | 1      | 0.14%   |
| ASMedia             | 1        | 1      | 0.14%   |
| Unknown             | 1        | 2      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 230      | 277    | 38.53%  |
| WDC                 | 193      | 246    | 32.33%  |
| Samsung Electronics | 61       | 78     | 10.22%  |
| Hitachi             | 54       | 64     | 9.05%   |
| Toshiba             | 25       | 26     | 4.19%   |
| Maxtor              | 21       | 27     | 3.52%   |
| HGST                | 5        | 5      | 0.84%   |
| USB3.0              | 1        | 1      | 0.17%   |
| Unknown             | 1        | 1      | 0.17%   |
| Hewlett-Packard     | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 2      | 0.17%   |
| FEASSO              | 1        | 2      | 0.17%   |
| ExcelStor           | 1        | 1      | 0.17%   |
| ASMedia             | 1        | 1      | 0.17%   |
| Unknown             | 1        | 2      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 538      | 734    | 80.78%  |
| SSD  | 112      | 124    | 16.82%  |
| NVMe | 16       | 19     | 2.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 25%     |
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 12.5%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 12.5%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 12.5%   |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 50%     |
| Toshiba             | 2        | 2      | 25%     |
| Hitachi             | 2        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 4247     | 11748  | 61.41%  |
| Works    | 2014     | 4411   | 29.12%  |
| Malfunc  | 647      | 877    | 9.36%   |
| Failed   | 8        | 8      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3946     | 48.04%  |
| AMD                              | 1936     | 23.57%  |
| Samsung Electronics              | 428      | 5.21%   |
| Nvidia                           | 275      | 3.35%   |
| ASMedia Technology               | 267      | 3.25%   |
| Marvell Technology Group         | 226      | 2.75%   |
| JMicron Technology               | 224      | 2.73%   |
| SanDisk                          | 161      | 1.96%   |
| Phison Electronics               | 134      | 1.63%   |
| Kingston Technology Company      | 106      | 1.29%   |
| VIA Technologies                 | 80       | 0.97%   |
| Micron/Crucial Technology        | 78       | 0.95%   |
| Silicon Motion                   | 74       | 0.9%    |
| ADATA Technology                 | 54       | 0.66%   |
| Realtek Semiconductor            | 34       | 0.41%   |
| LSI Logic / Symbios Logic        | 22       | 0.27%   |
| SK hynix                         | 21       | 0.26%   |
| Silicon Image                    | 21       | 0.26%   |
| Micron Technology                | 15       | 0.18%   |
| Broadcom / LSI                   | 13       | 0.16%   |
| Adaptec                          | 13       | 0.16%   |
| Toshiba America Info Systems     | 10       | 0.12%   |
| Silicon Integrated Systems [SiS] | 10       | 0.12%   |
| Lite-On Technology               | 9        | 0.11%   |
| Seagate Technology               | 8        | 0.1%    |
| Integrated Technology Express    | 7        | 0.09%   |
| KIOXIA                           | 6        | 0.07%   |
| Transcend                        | 4        | 0.05%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.05%   |
| ULi Electronics                  | 3        | 0.04%   |
| Shenzhen Longsys Electronics     | 3        | 0.04%   |
| HighPoint Technologies           | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.02%   |
| OCZ Technology Group             | 2        | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.02%   |
| INNOGRIT                         | 2        | 0.02%   |
| Hewlett-Packard                  | 2        | 0.02%   |
| TenaFe                           | 1        | 0.01%   |
| Sony                             | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 938      | 8.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 453      | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 423      | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 392      | 3.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 366      | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 351      | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 346      | 3.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 290      | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 287      | 2.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 279      | 2.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 276      | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 267      | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 242      | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 230      | 2.12%   |
| Intel SATA Controller [RAID mode]                                                       | 211      | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 211      | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 211      | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 198      | 1.82%   |
| Nvidia MCP61 SATA Controller                                                            | 165      | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 144      | 1.32%   |
| Nvidia MCP61 IDE                                                                        | 132      | 1.21%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 116      | 1.07%   |
| AMD FCH SATA Controller D                                                               | 115      | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 110      | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 97       | 0.89%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 95       | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 94       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 86       | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 82       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 82       | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 76       | 0.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 76       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 76       | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 73       | 0.67%   |
| JMicron JMB368 IDE controller                                                           | 67       | 0.62%   |
| Phison E12 NVMe Controller                                                              | 66       | 0.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 66       | 0.61%   |
| AMD FCH IDE Controller                                                                  | 66       | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 64       | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 59       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4645     | 55.86%  |
| IDE  | 2141     | 25.75%  |
| NVMe | 1110     | 13.35%  |
| RAID | 357      | 4.29%   |
| SAS  | 34       | 0.41%   |
| SCSI | 29       | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 4039     | 64.88%  |
| AMD          | 2184     | 35.08%  |
| CentaurHauls | 2        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 98       | 1.57%   |
| AMD Ryzen 5 3600 6-Core Processor           | 92       | 1.47%   |
| AMD FX-8350 Eight-Core Processor            | 89       | 1.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 83       | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 74       | 1.18%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 72       | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 72       | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 70       | 1.12%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 69       | 1.1%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 67       | 1.07%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 57       | 0.91%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 54       | 0.86%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 54       | 0.86%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 54       | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 53       | 0.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 53       | 0.85%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 52       | 0.83%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 49       | 0.78%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 48       | 0.77%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 48       | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 45       | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 41       | 0.66%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 41       | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 40       | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 39       | 0.62%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 39       | 0.62%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 37       | 0.59%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 37       | 0.59%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 36       | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 34       | 0.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 33       | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 33       | 0.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 33       | 0.53%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 32       | 0.51%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 31       | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 31       | 0.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 30       | 0.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 29       | 0.46%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 29       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 29       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1127     | 18.04%  |
| Intel Core i7           | 735      | 11.77%  |
| Intel Core i3           | 462      | 7.4%    |
| AMD Ryzen 5             | 441      | 7.06%   |
| AMD FX                  | 347      | 5.56%   |
| Intel Core 2 Duo        | 281      | 4.5%    |
| AMD Ryzen 7             | 273      | 4.37%   |
| Intel Xeon              | 266      | 4.26%   |
| Intel Core 2 Quad       | 194      | 3.11%   |
| Intel Celeron           | 194      | 3.11%   |
| Intel Pentium           | 184      | 2.95%   |
| Intel Pentium Dual-Core | 150      | 2.4%    |
| Other                   | 121      | 1.94%   |
| AMD Ryzen 3             | 113      | 1.81%   |
| AMD Phenom II X4        | 103      | 1.65%   |
| AMD Athlon II X2        | 92       | 1.47%   |
| AMD Athlon 64 X2        | 92       | 1.47%   |
| AMD Ryzen 9             | 89       | 1.42%   |
| AMD A8                  | 75       | 1.2%    |
| AMD Athlon II X4        | 62       | 0.99%   |
| Intel Pentium Dual      | 61       | 0.98%   |
| AMD A10                 | 56       | 0.9%    |
| Intel Core 2            | 54       | 0.86%   |
| Intel Pentium 4         | 53       | 0.85%   |
| Intel Atom              | 53       | 0.85%   |
| AMD A4                  | 53       | 0.85%   |
| Intel Core i9           | 45       | 0.72%   |
| AMD A6                  | 45       | 0.72%   |
| Intel Pentium D         | 43       | 0.69%   |
| AMD Phenom II X6        | 39       | 0.62%   |
| AMD Athlon              | 35       | 0.56%   |
| AMD Phenom              | 28       | 0.45%   |
| AMD Sempron             | 27       | 0.43%   |
| AMD Athlon II X3        | 24       | 0.38%   |
| AMD Athlon X4           | 23       | 0.37%   |
| Intel Pentium Gold      | 21       | 0.34%   |
| AMD Ryzen 5 PRO         | 19       | 0.3%    |
| AMD Phenom II X2        | 16       | 0.26%   |
| AMD Ryzen Threadripper  | 14       | 0.22%   |
| AMD Athlon 64           | 12       | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2540     | 40.61%  |
| 2       | 1945     | 31.1%   |
| 6       | 763      | 12.2%   |
| 8       | 431      | 6.89%   |
| 1       | 215      | 3.44%   |
| 3       | 144      | 2.3%    |
| 12      | 110      | 1.76%   |
| 16      | 46       | 0.74%   |
| 10      | 34       | 0.54%   |
| Unknown | 9        | 0.14%   |
| 24      | 5        | 0.08%   |
| 14      | 4        | 0.06%   |
| 20      | 3        | 0.05%   |
| 18      | 3        | 0.05%   |
| 64      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6167     | 99.07%  |
| 2      | 58       | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3165     | 50.69%  |
| 2       | 3069     | 49.15%  |
| Unknown | 9        | 0.14%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5849     | 92.99%  |
| Unknown        | 407      | 6.47%   |
| 32-bit         | 34       | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 657      | 10.26%  |
| 0x306c3    | 568      | 8.87%   |
| 0x206a7    | 476      | 7.44%   |
| 0x306a9    | 438      | 6.84%   |
| 0x1067a    | 406      | 6.34%   |
| 0x06000852 | 247      | 3.86%   |
| 0x506e3    | 222      | 3.47%   |
| 0x08701021 | 187      | 2.92%   |
| 0x010000c8 | 187      | 2.92%   |
| 0x906e9    | 166      | 2.59%   |
| 0x906ea    | 155      | 2.42%   |
| 0x0800820d | 145      | 2.27%   |
| 0x6fb      | 104      | 1.62%   |
| 0x06001119 | 102      | 1.59%   |
| 0x6fd      | 100      | 1.56%   |
| 0x08108109 | 75       | 1.17%   |
| 0x10676    | 70       | 1.09%   |
| 0x08701013 | 70       | 1.09%   |
| 0xa0655    | 68       | 1.06%   |
| 0x106e5    | 68       | 1.06%   |
| 0x010000db | 66       | 1.03%   |
| 0x0600063e | 63       | 0.98%   |
| 0x20655    | 60       | 0.94%   |
| 0xa0653    | 50       | 0.78%   |
| 0x08001138 | 50       | 0.78%   |
| 0x06003106 | 49       | 0.77%   |
| 0x906ed    | 48       | 0.75%   |
| 0xa0671    | 47       | 0.73%   |
| 0x306f2    | 46       | 0.72%   |
| 0x20652    | 45       | 0.7%    |
| 0x08001137 | 42       | 0.66%   |
| 0x0a201016 | 39       | 0.61%   |
| 0x0a50000c | 38       | 0.59%   |
| 0x90672    | 36       | 0.56%   |
| 0x206c2    | 36       | 0.56%   |
| 0x106a5    | 36       | 0.56%   |
| 0x0600611a | 36       | 0.56%   |
| 0x03000027 | 36       | 0.56%   |
| 0x206d7    | 35       | 0.55%   |
| 0x08101016 | 35       | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 662      | 10.6%   |
| SandyBridge      | 540      | 8.65%   |
| Penryn           | 531      | 8.51%   |
| IvyBridge        | 506      | 8.11%   |
| KabyLake         | 460      | 7.37%   |
| K10              | 407      | 6.52%   |
| Piledriver       | 387      | 6.2%    |
| Zen 2            | 310      | 4.97%   |
| Core             | 291      | 4.66%   |
| Skylake          | 258      | 4.13%   |
| Zen+             | 256      | 4.1%    |
| Zen              | 205      | 3.28%   |
| Zen 3            | 187      | 3%      |
| Westmere         | 149      | 2.39%   |
| K8 Hammer        | 132      | 2.11%   |
| CometLake        | 129      | 2.07%   |
| Nehalem          | 119      | 1.91%   |
| NetBurst         | 112      | 1.79%   |
| Bulldozer        | 71       | 1.14%   |
| Unknown          | 71       | 1.14%   |
| Steamroller      | 65       | 1.04%   |
| Silvermont       | 60       | 0.96%   |
| Excavator        | 51       | 0.82%   |
| K10 Llano        | 39       | 0.62%   |
| Alderlake Hybrid | 39       | 0.62%   |
| Bonnell          | 37       | 0.59%   |
| Goldmont plus    | 35       | 0.56%   |
| Bobcat           | 35       | 0.56%   |
| Icelake          | 22       | 0.35%   |
| Jaguar           | 19       | 0.3%    |
| Goldmont         | 19       | 0.3%    |
| Broadwell        | 13       | 0.21%   |
| Tremont          | 11       | 0.18%   |
| Puma             | 8        | 0.13%   |
| K6               | 4        | 0.06%   |
| TigerLake        | 3        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2574     | 39.04%  |
| Intel                                        | 2023     | 30.68%  |
| AMD                                          | 1945     | 29.5%   |
| VIA Technologies                             | 19       | 0.29%   |
| Matrox Electronics Systems                   | 14       | 0.21%   |
| Silicon Integrated Systems [SiS]             | 7        | 0.11%   |
| ATI Technologies                             | 5        | 0.08%   |
| S3 Graphics                                  | 3        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.03%   |
| ASPEED Technology                            | 2        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 294      | 4.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 279      | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 213      | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 203      | 2.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 172      | 2.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 162      | 2.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 158      | 2.33%   |
| Intel HD Graphics 530                                                       | 135      | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 114      | 1.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 103      | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 100      | 1.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 98       | 1.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 95       | 1.4%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 95       | 1.4%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 80       | 1.18%   |
| Intel HD Graphics 630                                                       | 78       | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 75       | 1.1%    |
| AMD RS780L [Radeon 3000]                                                    | 71       | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                         | 67       | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 66       | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 63       | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 61       | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 59       | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 57       | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 55       | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 54       | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 53       | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 52       | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 51       | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                               | 51       | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 50       | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 48       | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 44       | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 43       | 0.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 43       | 0.63%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 40       | 0.59%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 38       | 0.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 37       | 0.55%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 36       | 0.53%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 36       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 2433     | 38.63%  |
| 1 x AMD             | 1789     | 28.41%  |
| 1 x Intel           | 1779     | 28.25%  |
| 2 x AMD             | 83       | 1.32%   |
| Intel + Nvidia      | 60       | 0.95%   |
| AMD + Nvidia        | 41       | 0.65%   |
| Intel + AMD         | 32       | 0.51%   |
| 2 x Nvidia          | 29       | 0.46%   |
| 1 x VIA             | 19       | 0.3%    |
| 1 x Matrox          | 14       | 0.22%   |
| 1 x SiS             | 7        | 0.11%   |
| 3 x AMD             | 4        | 0.06%   |
| 1 x S3 Graphics     | 2        | 0.03%   |
| Nvidia + XGI        | 2        | 0.03%   |
| Nvidia + ASPEED     | 2        | 0.03%   |
| Intel + 2 x Nvidia  | 1        | 0.02%   |
| Intel + S3 Graphics | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 4179     | 65.79%  |
| Proprietary | 1887     | 29.71%  |
| Unknown     | 286      | 4.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2004     | 31.2%   |
| 1.01-2.0   | 1172     | 18.24%  |
| 0.51-1.0   | 928      | 14.45%  |
| 0.01-0.5   | 882      | 13.73%  |
| 3.01-4.0   | 577      | 8.98%   |
| 7.01-8.0   | 420      | 6.54%   |
| 5.01-6.0   | 237      | 3.69%   |
| 8.01-16.0  | 105      | 1.63%   |
| 2.01-3.0   | 87       | 1.35%   |
| 16.01-24.0 | 10       | 0.16%   |
| 4.01-5.0   | 2        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1078     | 16.72%  |
| Goldstar             | 673      | 10.44%  |
| Dell                 | 578      | 8.97%   |
| Acer                 | 489      | 7.59%   |
| Hewlett-Packard      | 437      | 6.78%   |
| AOC                  | 344      | 5.34%   |
| Ancor Communications | 309      | 4.79%   |
| BenQ                 | 288      | 4.47%   |
| Philips              | 273      | 4.24%   |
| LG Electronics       | 173      | 2.68%   |
| Unknown              | 142      | 2.2%    |
| ViewSonic            | 132      | 2.05%   |
| Iiyama               | 119      | 1.85%   |
| ASUSTek Computer     | 84       | 1.3%    |
| Sony                 | 79       | 1.23%   |
| Lenovo               | 68       | 1.05%   |
| Eizo                 | 66       | 1.02%   |
| NEC Computers        | 61       | 0.95%   |
| Fujitsu Siemens      | 57       | 0.88%   |
| HannStar             | 45       | 0.7%    |
| Vizio                | 39       | 0.61%   |
| Medion               | 35       | 0.54%   |
| Unknown              | 35       | 0.54%   |
| Toshiba              | 30       | 0.47%   |
| Sceptre Tech         | 28       | 0.43%   |
| Panasonic            | 27       | 0.42%   |
| Idek Iiyama          | 23       | 0.36%   |
| MSI                  | 22       | 0.34%   |
| Vestel Elektronik    | 20       | 0.31%   |
| Sharp                | 20       | 0.31%   |
| AUS                  | 20       | 0.31%   |
| FUS                  | 17       | 0.26%   |
| Hitachi              | 16       | 0.25%   |
| Packard Bell         | 14       | 0.22%   |
| Insignia             | 14       | 0.22%   |
| HannStar Display     | 14       | 0.22%   |
| Gateway              | 14       | 0.22%   |
| Lenovo Group Limited | 13       | 0.2%    |
| VIZ                  | 12       | 0.19%   |
| Unknown (XXX)        | 12       | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 35       | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 34       | 0.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 25       | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 22       | 0.32%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 20       | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 19       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 19       | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 18       | 0.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 16       | 0.23%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 15       | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 15       | 0.22%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 13       | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 12       | 0.17%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 12       | 0.17%   |
| Unknown LCD Monitor SAMSUNG                                            | 11       | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 11       | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 11       | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 11       | 0.16%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 11       | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 11       | 0.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 11       | 0.16%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 11       | 0.16%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch    | 10       | 0.14%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 10       | 0.14%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch    | 10       | 0.14%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 10       | 0.14%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 10       | 0.14%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 10       | 0.14%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 10       | 0.14%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                           | 10       | 0.14%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 9        | 0.13%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 9        | 0.13%   |
| Philips LCD Monitor FTV 1920x1080                                      | 9        | 0.13%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch               | 9        | 0.13%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 9        | 0.13%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 9        | 0.13%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 9        | 0.13%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 9        | 0.13%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 9        | 0.13%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 8        | 0.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2738     | 42.76%  |
| 1280x1024 (SXGA)   | 527      | 8.23%   |
| 1680x1050 (WSXGA+) | 412      | 6.43%   |
| 3840x2160 (4K)     | 410      | 6.4%    |
| 1366x768 (WXGA)    | 319      | 4.98%   |
| 2560x1440 (QHD)    | 287      | 4.48%   |
| 1440x900 (WXGA+)   | 274      | 4.28%   |
| Unknown            | 252      | 3.94%   |
| 1600x900 (HD+)     | 217      | 3.39%   |
| 1920x1200 (WUXGA)  | 185      | 2.89%   |
| 1360x768           | 154      | 2.41%   |
| 3840x1080          | 87       | 1.36%   |
| 2560x1080          | 86       | 1.34%   |
| 1024x768 (XGA)     | 60       | 0.94%   |
| 3440x1440          | 55       | 0.86%   |
| 1600x1200          | 44       | 0.69%   |
| 1920x540           | 34       | 0.53%   |
| 1280x720 (HD)      | 22       | 0.34%   |
| 3200x1080          | 19       | 0.3%    |
| 3600x1080          | 15       | 0.23%   |
| 3840x1200          | 14       | 0.22%   |
| 5760x1080          | 10       | 0.16%   |
| 2560x1600          | 10       | 0.16%   |
| 4480x1440          | 9        | 0.14%   |
| 1280x960           | 8        | 0.12%   |
| 5120x1440          | 7        | 0.11%   |
| 3520x1080          | 7        | 0.11%   |
| 1152x864           | 7        | 0.11%   |
| 3360x1050          | 6        | 0.09%   |
| 3286x1080          | 6        | 0.09%   |
| 2288x1287          | 6        | 0.09%   |
| 2048x1152          | 6        | 0.09%   |
| 1280x768           | 6        | 0.09%   |
| 5120x1080          | 5        | 0.08%   |
| 3840x1600          | 5        | 0.08%   |
| 3280x1080          | 5        | 0.08%   |
| 3120x1050          | 4        | 0.06%   |
| 2960x1050          | 4        | 0.06%   |
| 2560x1024          | 4        | 0.06%   |
| 3360x1080          | 3        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1125     | 17.67%  |
| 24      | 706      | 11.09%  |
| 23      | 688      | 10.81%  |
| 21      | 626      | 9.83%   |
| 27      | 624      | 9.8%    |
| 19      | 442      | 6.94%   |
| 18      | 321      | 5.04%   |
| 22      | 270      | 4.24%   |
| 20      | 257      | 4.04%   |
| 17      | 252      | 3.96%   |
| 31      | 198      | 3.11%   |
| 15      | 114      | 1.79%   |
| 34      | 111      | 1.74%   |
| 84      | 75       | 1.18%   |
| 40      | 62       | 0.97%   |
| 32      | 62       | 0.97%   |
| 72      | 56       | 0.88%   |
| 54      | 49       | 0.77%   |
| 25      | 37       | 0.58%   |
| 26      | 24       | 0.38%   |
| 46      | 20       | 0.31%   |
| 16      | 20       | 0.31%   |
| 52      | 16       | 0.25%   |
| 28      | 14       | 0.22%   |
| 65      | 13       | 0.2%    |
| 48      | 13       | 0.2%    |
| 37      | 13       | 0.2%    |
| 36      | 12       | 0.19%   |
| 47      | 11       | 0.17%   |
| 39      | 11       | 0.17%   |
| 33      | 11       | 0.17%   |
| 12      | 11       | 0.17%   |
| 29      | 9        | 0.14%   |
| 55      | 8        | 0.13%   |
| 13      | 8        | 0.13%   |
| 74      | 7        | 0.11%   |
| 60      | 7        | 0.11%   |
| 42      | 7        | 0.11%   |
| 35      | 6        | 0.09%   |
| 38      | 5        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1904     | 30.6%   |
| 401-500        | 1624     | 26.1%   |
| Unknown        | 1125     | 18.08%  |
| 301-350        | 344      | 5.53%   |
| 351-400        | 297      | 4.77%   |
| 601-700        | 294      | 4.73%   |
| 701-800        | 195      | 3.13%   |
| 1001-1500      | 155      | 2.49%   |
| 1501-2000      | 145      | 2.33%   |
| 801-900        | 98       | 1.58%   |
| 201-300        | 24       | 0.39%   |
| 901-1000       | 14       | 0.23%   |
| More than 2000 | 3        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3415     | 56.73%  |
| Unknown | 1031     | 17.13%  |
| 16/10   | 784      | 13.02%  |
| 5/4     | 454      | 7.54%   |
| 4/3     | 137      | 2.28%   |
| 21/9    | 123      | 2.04%   |
| 3/2     | 32       | 0.53%   |
| 6/5     | 20       | 0.33%   |
| 32/9    | 13       | 0.22%   |
| 1.96    | 4        | 0.07%   |
| 1.00    | 4        | 0.07%   |
| 3.20    | 1        | 0.02%   |
| 2.00    | 1        | 0.02%   |
| 11/10   | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1851     | 29.57%  |
| Unknown        | 1125     | 17.97%  |
| 151-200        | 902      | 14.41%  |
| 301-350        | 637      | 10.18%  |
| 141-150        | 474      | 7.57%   |
| 351-500        | 406      | 6.49%   |
| 251-300        | 263      | 4.2%    |
| More than 1000 | 256      | 4.09%   |
| 501-1000       | 159      | 2.54%   |
| 101-110        | 99       | 1.58%   |
| 131-140        | 35       | 0.56%   |
| 111-120        | 23       | 0.37%   |
| 71-80          | 12       | 0.19%   |
| 121-130        | 7        | 0.11%   |
| 81-90          | 5        | 0.08%   |
| 91-100         | 5        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3546     | 58.71%  |
| Unknown | 1125     | 18.63%  |
| 101-120 | 885      | 14.65%  |
| 1-50    | 269      | 4.45%   |
| 121-160 | 150      | 2.48%   |
| 161-240 | 65       | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5108     | 80.53%  |
| 2     | 861      | 13.57%  |
| 0     | 289      | 4.56%   |
| 3     | 78       | 1.23%   |
| 4     | 7        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3946     | 44.55%  |
| Intel                                  | 2114     | 23.87%  |
| Qualcomm Atheros                       | 592      | 6.68%   |
| Ralink Technology                      | 300      | 3.39%   |
| Broadcom                               | 266      | 3%      |
| Nvidia                                 | 222      | 2.51%   |
| TP-Link                                | 195      | 2.2%    |
| Ralink                                 | 149      | 1.68%   |
| Marvell Technology Group               | 83       | 0.94%   |
| Qualcomm Atheros Communications        | 75       | 0.85%   |
| Broadcom Limited                       | 68       | 0.77%   |
| MediaTek                               | 64       | 0.72%   |
| NetGear                                | 59       | 0.67%   |
| Samsung Electronics                    | 56       | 0.63%   |
| D-Link System                          | 56       | 0.63%   |
| D-Link                                 | 49       | 0.55%   |
| ASUSTek Computer                       | 48       | 0.54%   |
| VIA Technologies                       | 44       | 0.5%    |
| Xiaomi                                 | 35       | 0.4%    |
| Microsoft                              | 29       | 0.33%   |
| ASIX Electronics                       | 27       | 0.3%    |
| Huawei Technologies                    | 25       | 0.28%   |
| IMC Networks                           | 24       | 0.27%   |
| Belkin Components                      | 23       | 0.26%   |
| Aquantia                               | 22       | 0.25%   |
| Linksys                                | 21       | 0.24%   |
| Edimax Technology                      | 20       | 0.23%   |
| Motorola PCS                           | 15       | 0.17%   |
| AVM                                    | 14       | 0.16%   |
| Qualcomm                               | 12       | 0.14%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.11%   |
| Sitecom Europe                         | 9        | 0.1%    |
| DisplayLink                            | 7        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 6        | 0.07%   |
| Silicon Integrated Systems [SiS]       | 6        | 0.07%   |
| Microchip Technology                   | 6        | 0.07%   |
| Gemtek                                 | 6        | 0.07%   |
| ZyDAS                                  | 5        | 0.06%   |
| U-Blox                                 | 5        | 0.06%   |
| Texas Instruments                      | 5        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3136     | 31.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 305      | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 207      | 2.1%    |
| Intel I211 Gigabit Network Connection                             | 199      | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 196      | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 191      | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 191      | 1.94%   |
| Nvidia MCP61 Ethernet                                             | 138      | 1.4%    |
| Ralink MT7601U Wireless Adapter                                   | 127      | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 122      | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 105      | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 99       | 1.01%   |
| Realtek 802.11ac NIC                                              | 93       | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 92       | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 92       | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 90       | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 87       | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 85       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 79       | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 77       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 64       | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                   | 59       | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58       | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 54       | 0.55%   |
| Intel Wireless-AC 9260                                            | 54       | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 52       | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 52       | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 51       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50       | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 49       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 46       | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 46       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 46       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 43       | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 43       | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 42       | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 42       | 0.43%   |
| Intel Wireless 3165                                               | 41       | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 40       | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 38       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 750      | 25.48%  |
| Intel                                 | 645      | 21.92%  |
| Ralink Technology                     | 300      | 10.19%  |
| Qualcomm Atheros                      | 291      | 9.89%   |
| TP-Link                               | 193      | 6.56%   |
| Ralink                                | 149      | 5.06%   |
| Broadcom                              | 91       | 3.09%   |
| Qualcomm Atheros Communications       | 75       | 2.55%   |
| NetGear                               | 59       | 2%      |
| MediaTek                              | 48       | 1.63%   |
| D-Link                                | 48       | 1.63%   |
| ASUSTek Computer                      | 48       | 1.63%   |
| D-Link System                         | 35       | 1.19%   |
| Microsoft                             | 29       | 0.99%   |
| IMC Networks                          | 24       | 0.82%   |
| Linksys                               | 21       | 0.71%   |
| Belkin Components                     | 21       | 0.71%   |
| Edimax Technology                     | 20       | 0.68%   |
| AVM                                   | 14       | 0.48%   |
| Broadcom Limited                      | 13       | 0.44%   |
| Sitecom Europe                        | 9        | 0.31%   |
| Gemtek                                | 6        | 0.2%    |
| ZyDAS                                 | 5        | 0.17%   |
| Texas Instruments                     | 5        | 0.17%   |
| Tenda                                 | 5        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5        | 0.17%   |
| ZyXEL Communications                  | 3        | 0.1%    |
| TRENDnet                              | 3        | 0.1%    |
| Marvell Technology Group              | 3        | 0.1%    |
| Accton Technology                     | 3        | 0.1%    |
| Wacom                                 | 2        | 0.07%   |
| VIA Technologies                      | 2        | 0.07%   |
| Samsung Electronics                   | 2        | 0.07%   |
| Mercucys                              | 2        | 0.07%   |
| Z-Com                                 | 1        | 0.03%   |
| Xiaomi                                | 1        | 0.03%   |
| Sagem                                 | 1        | 0.03%   |
| PLANEX                                | 1        | 0.03%   |
| Philips (or NXP)                      | 1        | 0.03%   |
| Netopia                               | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 191      | 6.39%   |
| Ralink MT7601U Wireless Adapter                                | 127      | 4.25%   |
| Realtek 802.11ac NIC                                           | 93       | 3.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 87       | 2.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 85       | 2.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 79       | 2.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 59       | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58       | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 54       | 1.81%   |
| Intel Wireless-AC 9260                                         | 54       | 1.81%   |
| Ralink RT5370 Wireless Adapter                                 | 52       | 1.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 52       | 1.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 49       | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 42       | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 42       | 1.4%    |
| Intel Wireless 3165                                            | 41       | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 40       | 1.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 38       | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 38       | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 37       | 1.24%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 34       | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 31       | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 30       | 1%      |
| Intel Wireless 7265                                            | 29       | 0.97%   |
| Intel Wireless 7260                                            | 29       | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 27       | 0.9%    |
| Ralink RT2561/RT61 802.11g PCI                                 | 27       | 0.9%    |
| Intel Wireless 8260                                            | 27       | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 23       | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 22       | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 22       | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 22       | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 22       | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 22       | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 22       | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 22       | 0.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 22       | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 20       | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 20       | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3662     | 55.54%  |
| Intel                                  | 1750     | 26.54%  |
| Qualcomm Atheros                       | 322      | 4.88%   |
| Nvidia                                 | 222      | 3.37%   |
| Broadcom                               | 176      | 2.67%   |
| Marvell Technology Group               | 80       | 1.21%   |
| Broadcom Limited                       | 55       | 0.83%   |
| Samsung Electronics                    | 43       | 0.65%   |
| VIA Technologies                       | 41       | 0.62%   |
| Xiaomi                                 | 34       | 0.52%   |
| ASIX Electronics                       | 27       | 0.41%   |
| Aquantia                               | 22       | 0.33%   |
| D-Link System                          | 21       | 0.32%   |
| MediaTek                               | 16       | 0.24%   |
| Huawei Technologies                    | 15       | 0.23%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.15%   |
| Qualcomm                               | 10       | 0.15%   |
| Motorola PCS                           | 10       | 0.15%   |
| DisplayLink                            | 7        | 0.11%   |
| Silicon Integrated Systems [SiS]       | 6        | 0.09%   |
| OPPO Electronics                       | 5        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.06%   |
| LG Electronics                         | 4        | 0.06%   |
| Google                                 | 4        | 0.06%   |
| Apple                                  | 3        | 0.05%   |
| 3Com                                   | 3        | 0.05%   |
| TP-Link                                | 2        | 0.03%   |
| Spreadtrum Communications              | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.03%   |
| Microchip Technology                   | 2        | 0.03%   |
| Mellanox Technologies                  | 2        | 0.03%   |
| JMicron Technology                     | 2        | 0.03%   |
| ICS Advent                             | 2        | 0.03%   |
| HTC (High Tech Computer)               | 2        | 0.03%   |
| ADMtek                                 | 2        | 0.03%   |
| vivo                                   | 1        | 0.02%   |
| ULi Electronics                        | 1        | 0.02%   |
| Trendchip Technologies                 | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3136     | 46.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 305      | 4.52%   |
| Intel Ethernet Connection (2) I219-V                              | 207      | 3.07%   |
| Intel I211 Gigabit Network Connection                             | 199      | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 196      | 2.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 191      | 2.83%   |
| Nvidia MCP61 Ethernet                                             | 138      | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 122      | 1.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 105      | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 99       | 1.47%   |
| Intel Ethernet Connection (7) I219-V                              | 92       | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 92       | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 90       | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 77       | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 64       | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 51       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50       | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 46       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 46       | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 46       | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 43       | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 43       | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 38       | 0.56%   |
| Intel 82578DM Gigabit Network Connection                          | 38       | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 36       | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 36       | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 33       | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32       | 0.47%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 30       | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 26       | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 23       | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 22       | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22       | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22       | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20       | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 20       | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19       | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19       | 0.28%   |
| Intel 82578DC Gigabit Network Connection                          | 19       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6149     | 68.74%  |
| WiFi     | 2700     | 30.18%  |
| Modem    | 69       | 0.77%   |
| Unknown  | 27       | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4813     | 74.22%  |
| WiFi     | 1663     | 25.64%  |
| Modem    | 5        | 0.08%   |
| Unknown  | 4        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4391     | 70.14%  |
| 2     | 1634     | 26.1%   |
| 3     | 149      | 2.38%   |
| 0     | 63       | 1.01%   |
| 4     | 14       | 0.22%   |
| 5     | 6        | 0.1%    |
| 7     | 2        | 0.03%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 5033     | 79.56%  |
| Yes     | 1292     | 20.42%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 579      | 33.64%  |
| Cambridge Silicon Radio         | 543      | 31.55%  |
| Realtek Semiconductor           | 138      | 8.02%   |
| Broadcom                        | 121      | 7.03%   |
| ASUSTek Computer                | 103      | 5.98%   |
| Qualcomm Atheros Communications | 55       | 3.2%    |
| IMC Networks                    | 34       | 1.98%   |
| Lite-On Technology              | 20       | 1.16%   |
| MediaTek                        | 19       | 1.1%    |
| Apple                           | 18       | 1.05%   |
| Integrated System Solution      | 17       | 0.99%   |
| TP-Link                         | 13       | 0.76%   |
| Belkin Components               | 9        | 0.52%   |
| Edimax Technology               | 6        | 0.35%   |
| Dell                            | 5        | 0.29%   |
| Conwise Technology              | 5        | 0.29%   |
| Ralink                          | 4        | 0.23%   |
| Foxconn / Hon Hai               | 4        | 0.23%   |
| Dynex                           | 4        | 0.23%   |
| Logitech                        | 3        | 0.17%   |
| Motorola PCS                    | 2        | 0.12%   |
| Micro Star International        | 2        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.12%   |
| Unknown                         | 2        | 0.12%   |
| Sitecom Europe                  | 1        | 0.06%   |
| SINO WEALTH                     | 1        | 0.06%   |
| Roper                           | 1        | 0.06%   |
| Realtek                         | 1        | 0.06%   |
| Primax Electronics              | 1        | 0.06%   |
| Plugable                        | 1        | 0.06%   |
| Microsoft                       | 1        | 0.06%   |
| Kensington                      | 1        | 0.06%   |
| HTC (High Tech Computer)        | 1        | 0.06%   |
| Fujitsu Siemens Computers       | 1        | 0.06%   |
| D-Link System                   | 1        | 0.06%   |
| D-Link                          | 1        | 0.06%   |
| Cypress Semiconductor           | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 542      | 31.38%  |
| Intel AX200 Bluetooth                                 | 169      | 9.79%   |
| Intel Bluetooth wireless interface                    | 137      | 7.93%   |
| Realtek Bluetooth Radio                               | 97       | 5.62%   |
| Intel Wireless-AC 3168 Bluetooth                      | 75       | 4.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 69       | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 53       | 3.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 45       | 2.61%   |
| Intel AX201 Bluetooth                                 | 44       | 2.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 43       | 2.49%   |
| Intel AX210 Bluetooth                                 | 40       | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                        | 30       | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 19       | 1.1%    |
| MediaTek Wireless_Device                              | 19       | 1.1%    |
| ASUS ASUS USB-BT500                                   | 19       | 1.1%    |
| Qualcomm Atheros  Bluetooth Device                    | 17       | 0.98%   |
| IMC Networks Bluetooth Radio                          | 17       | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 14       | 0.81%   |
| TP-Link UB500 Adapter                                 | 13       | 0.75%   |
| ASUS BCM20702A0                                       | 13       | 0.75%   |
| Lite-On Bluetooth Device                              | 12       | 0.69%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 11       | 0.64%   |
| Broadcom BCM2045 Bluetooth                            | 11       | 0.64%   |
| ASUS Bluetooth Radio                                  | 9        | 0.52%   |
| Realtek RTL8821A Bluetooth                            | 8        | 0.46%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 8        | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 8        | 0.46%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 7        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                           | 7        | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 6        | 0.35%   |
| Integrated System Solution Bluetooth Device           | 6        | 0.35%   |
| IMC Networks Wireless_Device                          | 6        | 0.35%   |
| IMC Networks Bluetooth Device                         | 6        | 0.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 6        | 0.35%   |
| Conwise CW6622                                        | 5        | 0.29%   |
| Broadcom HP Bluethunder                               | 5        | 0.29%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 5        | 0.29%   |
| ASUS Bluetooth Adapter                                | 5        | 0.29%   |
| Apple Bluetooth Host Controller                       | 5        | 0.29%   |
| Apple Bluetooth HCI                                   | 5        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3822     | 37.91%  |
| AMD                                             | 2590     | 25.69%  |
| Nvidia                                          | 2362     | 23.43%  |
| C-Media Electronics                             | 272      | 2.7%    |
| Creative Labs                                   | 163      | 1.62%   |
| Logitech                                        | 101      | 1%      |
| Texas Instruments                               | 59       | 0.59%   |
| VIA Technologies                                | 58       | 0.58%   |
| Generalplus Technology                          | 47       | 0.47%   |
| JMTek                                           | 43       | 0.43%   |
| Kingston Technology                             | 37       | 0.37%   |
| GN Netcom                                       | 31       | 0.31%   |
| Creative Technology                             | 31       | 0.31%   |
| Razer USA                                       | 23       | 0.23%   |
| ASUSTek Computer                                | 22       | 0.22%   |
| Focusrite-Novation                              | 20       | 0.2%    |
| Corsair                                         | 19       | 0.19%   |
| SteelSeries ApS                                 | 17       | 0.17%   |
| Plantronics                                     | 16       | 0.16%   |
| Tenx Technology                                 | 15       | 0.15%   |
| Samson Technologies                             | 14       | 0.14%   |
| Sennheiser Communications                       | 13       | 0.13%   |
| Realtek Semiconductor                           | 11       | 0.11%   |
| M-Audio                                         | 11       | 0.11%   |
| Silicon Integrated Systems [SiS]                | 10       | 0.1%    |
| XMOS                                            | 9        | 0.09%   |
| Microsoft                                       | 8        | 0.08%   |
| Micro Star International                        | 8        | 0.08%   |
| Ensoniq                                         | 8        | 0.08%   |
| Dell                                            | 8        | 0.08%   |
| Blue Microphones                                | 8        | 0.08%   |
| BEHRINGER International                         | 8        | 0.08%   |
| Yamaha                                          | 7        | 0.07%   |
| KTMicro                                         | 7        | 0.07%   |
| SAVITECH                                        | 6        | 0.06%   |
| Asahi Kasei Microsystems                        | 6        | 0.06%   |
| Trust                                           | 5        | 0.05%   |
| Syntek                                          | 5        | 0.05%   |
| Sony                                            | 5        | 0.05%   |
| Licensed by Sony Computer Entertainment America | 5        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 637      | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 615      | 5.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 486      | 4.18%   |
| AMD Starship/Matisse HD Audio Controller                                          | 381      | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 373      | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 350      | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 314      | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 290      | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 282      | 2.42%   |
| AMD Family 17h/19h HD Audio Controller                                            | 276      | 2.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 255      | 2.19%   |
| AMD FCH Azalia Controller                                                         | 249      | 2.14%   |
| Intel 200 Series PCH HD Audio                                                     | 243      | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 220      | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 204      | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 203      | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 175      | 1.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 168      | 1.44%   |
| Nvidia High Definition Audio Controller                                           | 161      | 1.38%   |
| Nvidia MCP61 High Definition Audio                                                | 160      | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                        | 157      | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 156      | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 141      | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                     | 129      | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 118      | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 118      | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                     | 116      | 1%      |
| Nvidia TU116 High Definition Audio Controller                                     | 112      | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 112      | 0.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 110      | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 110      | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                                     | 109      | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 104      | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                     | 103      | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 100      | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                | 83       | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                | 82       | 0.7%    |
| Nvidia GM206 High Definition Audio Controller                                     | 78       | 0.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 68       | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                                     | 67       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 483      | 16.89%  |
| Unknown             | 481      | 16.82%  |
| Corsair             | 334      | 11.68%  |
| Samsung Electronics | 250      | 8.74%   |
| Crucial             | 248      | 8.67%   |
| SK hynix            | 246      | 8.6%    |
| G.Skill             | 225      | 7.87%   |
| Micron Technology   | 109      | 3.81%   |
| A-DATA Technology   | 55       | 1.92%   |
| Team                | 47       | 1.64%   |
| Nanya Technology    | 44       | 1.54%   |
| Patriot             | 41       | 1.43%   |
| Ramaxel Technology  | 26       | 0.91%   |
| Unknown             | 23       | 0.8%    |
| Elpida              | 21       | 0.73%   |
| Goodram             | 18       | 0.63%   |
| AMD                 | 16       | 0.56%   |
| Transcend           | 14       | 0.49%   |
| Unknown (ABCD)      | 13       | 0.45%   |
| Unifosa             | 11       | 0.38%   |
| Kingmax             | 11       | 0.38%   |
| Smart               | 9        | 0.31%   |
| GeIL                | 8        | 0.28%   |
| Apacer              | 8        | 0.28%   |
| PNY                 | 7        | 0.24%   |
| Silicon Power       | 6        | 0.21%   |
| Teikon              | 5        | 0.17%   |
| Sesame              | 5        | 0.17%   |
| Wilk Elektronik     | 4        | 0.14%   |
| OCZ                 | 4        | 0.14%   |
| Multilaser          | 4        | 0.14%   |
| Kllisre             | 4        | 0.14%   |
| Avant               | 4        | 0.14%   |
| Atermiter           | 4        | 0.14%   |
| Unknown (0x8551)    | 3        | 0.1%    |
| TakeMS              | 3        | 0.1%    |
| Ramos Technology    | 3        | 0.1%    |
| Qumo                | 3        | 0.1%    |
| Qimonda             | 3        | 0.1%    |
| KETECH              | 3        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 32       | 1.02%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 30       | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 29       | 0.93%   |
| Unknown                                                        | 23       | 0.73%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 22       | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 21       | 0.67%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 21       | 0.67%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 20       | 0.64%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 19       | 0.61%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s       | 19       | 0.61%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 17       | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 17       | 0.54%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 17       | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 17       | 0.54%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 16       | 0.51%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s          | 16       | 0.51%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 14       | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 13       | 0.42%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 13       | 0.42%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 13       | 0.42%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 13       | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 13       | 0.42%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 13       | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 12       | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 12       | 0.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 12       | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 12       | 0.38%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 12       | 0.38%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 12       | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 11       | 0.35%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 11       | 0.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 11       | 0.35%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s            | 11       | 0.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 11       | 0.35%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s                 | 11       | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 10       | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                    | 10       | 0.32%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 10       | 0.32%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 10       | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 10       | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1018     | 40.48%  |
| DDR3         | 933      | 37.1%   |
| Unknown      | 190      | 7.55%   |
| DDR2         | 175      | 6.96%   |
| SDRAM        | 128      | 5.09%   |
| DDR          | 37       | 1.47%   |
| LPDDR4       | 16       | 0.64%   |
| DDR5         | 15       | 0.6%    |
| DRAM         | 2        | 0.08%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2306     | 93.66%  |
| SODIMM       | 145      | 5.89%   |
| FB-DIMM      | 7        | 0.28%   |
| RIMM         | 3        | 0.12%   |
| Row Of Chips | 1        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 963      | 35.5%   |
| 4096  | 705      | 25.99%  |
| 2048  | 484      | 17.84%  |
| 16384 | 320      | 11.8%   |
| 1024  | 125      | 4.61%   |
| 32768 | 92       | 3.39%   |
| 512   | 19       | 0.7%    |
| 1536  | 2        | 0.07%   |
| 256   | 2        | 0.07%   |
| 16    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 527      | 18.99%  |
| 1333    | 417      | 15.03%  |
| 3200    | 201      | 7.24%   |
| 3600    | 162      | 5.84%   |
| 2400    | 162      | 5.84%   |
| 800     | 141      | 5.08%   |
| 2133    | 134      | 4.83%   |
| 2667    | 117      | 4.22%   |
| 667     | 91       | 3.28%   |
| Unknown | 69       | 2.49%   |
| 1867    | 63       | 2.27%   |
| 3000    | 57       | 2.05%   |
| 1866    | 49       | 1.77%   |
| 2933    | 43       | 1.55%   |
| 3466    | 39       | 1.41%   |
| 3400    | 37       | 1.33%   |
| 1800    | 33       | 1.19%   |
| 1066    | 30       | 1.08%   |
| 3733    | 28       | 1.01%   |
| 2666    | 27       | 0.97%   |
| 3800    | 25       | 0.9%    |
| 3266    | 24       | 0.86%   |
| 2800    | 20       | 0.72%   |
| 3866    | 19       | 0.68%   |
| 400     | 19       | 0.68%   |
| 1067    | 16       | 0.58%   |
| 1334    | 13       | 0.47%   |
| 3666    | 11       | 0.4%    |
| 4800    | 10       | 0.36%   |
| 3534    | 10       | 0.36%   |
| 1648    | 10       | 0.36%   |
| 333     | 10       | 0.36%   |
| 2733    | 9        | 0.32%   |
| 2048    | 8        | 0.29%   |
| 2000    | 8        | 0.29%   |
| 1639    | 8        | 0.29%   |
| 3500    | 7        | 0.25%   |
| 3151    | 7        | 0.25%   |
| 533     | 7        | 0.25%   |
| 49926   | 6        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 169      | 36.98%  |
| Brother Industries       | 101      | 22.1%   |
| Canon                    | 69       | 15.1%   |
| Seiko Epson              | 39       | 8.53%   |
| Samsung Electronics      | 36       | 7.88%   |
| QinHeng Electronics      | 6        | 1.31%   |
| Prolific Technology      | 5        | 1.09%   |
| Xerox                    | 4        | 0.88%   |
| Dymo-CoStar              | 4        | 0.88%   |
| Ricoh                    | 3        | 0.66%   |
| Pantum                   | 3        | 0.66%   |
| Panasonic (Matsushita)   | 3        | 0.66%   |
| Seiko Instruments        | 2        | 0.44%   |
| Lexmark International    | 2        | 0.44%   |
| Kyocera                  | 2        | 0.44%   |
| Dell                     | 2        | 0.44%   |
| Sato                     | 1        | 0.22%   |
| Oki Data                 | 1        | 0.22%   |
| NXP Semiconductors       | 1        | 0.22%   |
| Magic Control Technology | 1        | 0.22%   |
| Fuji Xerox               | 1        | 0.22%   |
| Agere Systems (Lucent)   | 1        | 0.22%   |
| Unknown                  | 1        | 0.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP LaserJet 1020                   | 7        | 1.52%   |
| HP DeskJet 2620 All-in-One Printer | 7        | 1.52%   |
| Brother Printer                    | 7        | 1.52%   |
| Samsung M2070 Series               | 6        | 1.3%    |
| Samsung M2020 Series               | 6        | 1.3%    |
| QinHeng CH340S                     | 6        | 1.3%    |
| HP LaserJet Professional P1102w    | 6        | 1.3%    |
| Prolific PL2305 Parallel Port      | 5        | 1.09%   |
| HP OfficeJet 5200 series           | 5        | 1.09%   |
| HP Officejet 4500 G510n-z          | 5        | 1.09%   |
| HP LaserJet P1005                  | 5        | 1.09%   |
| HP LaserJet 1018                   | 5        | 1.09%   |
| Brother HL-L2360D series           | 5        | 1.09%   |
| Seiko Epson L3150 Series           | 4        | 0.87%   |
| Samsung SCX-3400 Series            | 4        | 0.87%   |
| Samsung C48x Series                | 4        | 0.87%   |
| HP Officejet 4620 series           | 4        | 0.87%   |
| HP LaserJet Professional P 1102w   | 4        | 0.87%   |
| HP ENVY 5000 series                | 4        | 0.87%   |
| HP DeskJet F4200 series            | 4        | 0.87%   |
| HP Deskjet 2050 J510               | 4        | 0.87%   |
| Canon LiDE 400                     | 4        | 0.87%   |
| Brother HL-1210W series            | 4        | 0.87%   |
| Brother DCP-7055 scanner/printer   | 4        | 0.87%   |
| Seiko Epson L210 Series            | 3        | 0.65%   |
| Panasonic (Matsushita) KX-MB1500RU | 3        | 0.65%   |
| HP OfficeJet Pro 8020 series       | 3        | 0.65%   |
| HP OfficeJet Pro 69                | 3        | 0.65%   |
| HP LaserJet P1102                  | 3        | 0.65%   |
| HP ENVY 5540 series                | 3        | 0.65%   |
| HP ENVY 4520 series                | 3        | 0.65%   |
| HP DeskJet 3630 series             | 3        | 0.65%   |
| HP Deskjet 2540 series             | 3        | 0.65%   |
| HP DeskJet 2130 series             | 3        | 0.65%   |
| Canon PIXMA MX530 Series           | 3        | 0.65%   |
| Brother MFC-L8600CDW               | 3        | 0.65%   |
| Brother MFC-J497DW                 | 3        | 0.65%   |
| Brother HL-3140CW series           | 3        | 0.65%   |
| Brother HL-2270DW Laser Printer    | 3        | 0.65%   |
| Brother HL-1110 series             | 3        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 74       | 57.81%  |
| Seiko Epson                 | 27       | 21.09%  |
| Hewlett-Packard             | 14       | 10.94%  |
| Mustek Systems              | 4        | 3.13%   |
| Ultima Electronics          | 2        | 1.56%   |
| AGFA-Gevaert NV             | 2        | 1.56%   |
| Acer Peripherals (now BenQ) | 2        | 1.56%   |
| UMAX                        | 1        | 0.78%   |
| Salix Technology            | 1        | 0.78%   |
| Microtek International      | 1        | 0.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 11       | 8.59%   |
| Canon CanoScan LIDE 25                                                                | 10       | 7.81%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 6.25%   |
| Canon CanoScan LiDE 120                                                               | 7        | 5.47%   |
| Canon CanoScan LiDE 220                                                               | 6        | 4.69%   |
| Canon CanoScan LiDE 210                                                               | 6        | 4.69%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4        | 3.13%   |
| Canon CanoScan LiDE 700F                                                              | 4        | 3.13%   |
| Canon CanoScan LiDE 60                                                                | 4        | 3.13%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3        | 2.34%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3        | 2.34%   |
| Canon CanoScan LiDE 90                                                                | 3        | 2.34%   |
| Canon CanoScan LiDE 100                                                               | 3        | 2.34%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 1.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2        | 1.56%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 2        | 1.56%   |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2        | 1.56%   |
| Mustek Systems SNAPSCAN e22                                                           | 2        | 1.56%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 2        | 1.56%   |
| HP ScanJet 3800c                                                                      | 2        | 1.56%   |
| HP Scanjet 300                                                                        | 2        | 1.56%   |
| HP ScanJet 2400c                                                                      | 2        | 1.56%   |
| Canon CanoScan N650U/N656U                                                            | 2        | 1.56%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 1.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2        | 1.56%   |
| Canon CanoScan 9000F Mark II                                                          | 2        | 1.56%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2        | 1.56%   |
| UMAX Astra 4400/4450                                                                  | 1        | 0.78%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 0.78%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 0.78%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 0.78%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 0.78%   |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1        | 0.78%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 0.78%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 0.78%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 0.78%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 0.78%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1        | 0.78%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 0.78%   |
| Salix USB Scanner.                                                                    | 1        | 0.78%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 424      | 34.39%  |
| Microdia                      | 118      | 9.57%   |
| Microsoft                     | 86       | 6.97%   |
| Samsung Electronics           | 65       | 5.27%   |
| Generalplus Technology        | 40       | 3.24%   |
| Z-Star Microelectronics       | 36       | 2.92%   |
| Sunplus Innovation Technology | 36       | 2.92%   |
| Chicony Electronics           | 36       | 2.92%   |
| KYE Systems (Mouse Systems)   | 25       | 2.03%   |
| Creative Technology           | 25       | 2.03%   |
| GEMBIRD                       | 24       | 1.95%   |
| Realtek Semiconductor         | 23       | 1.87%   |
| Apple                         | 23       | 1.87%   |
| ARC International             | 19       | 1.54%   |
| Aveo Technology               | 18       | 1.46%   |
| IMC Networks                  | 15       | 1.22%   |
| Arkmicro Technologies         | 13       | 1.05%   |
| Cubeternet                    | 12       | 0.97%   |
| MacroSilicon                  | 10       | 0.81%   |
| Jieli Technology              | 10       | 0.81%   |
| Sonix Technology              | 9        | 0.73%   |
| LG Electronics                | 9        | 0.73%   |
| Genesys Logic                 | 9        | 0.73%   |
| Alcor Micro                   | 9        | 0.73%   |
| Trust                         | 7        | 0.57%   |
| Philips (or NXP)              | 7        | 0.57%   |
| Guillemot                     | 7        | 0.57%   |
| Sunplus IT                    | 6        | 0.49%   |
| Pixart Imaging                | 6        | 0.49%   |
| Novatek Microelectronics      | 6        | 0.49%   |
| Hewlett-Packard               | 6        | 0.49%   |
| Silicon Motion                | 5        | 0.41%   |
| Huawei Technologies           | 4        | 0.32%   |
| HD USB Camera                 | 4        | 0.32%   |
| AVerMedia Technologies        | 4        | 0.32%   |
| Asuscom Network               | 4        | 0.32%   |
| Unknown                       | 3        | 0.24%   |
| Syntek                        | 3        | 0.24%   |
| Sony                          | 3        | 0.24%   |
| Razer USA                     | 3        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 103      | 8.33%   |
| Samsung Galaxy series, misc. (MTP mode) | 65       | 5.25%   |
| Logitech HD Pro Webcam C920             | 45       | 3.64%   |
| Microsoft LifeCam HD-3000               | 38       | 3.07%   |
| Microdia Webcam Vitade AF               | 32       | 2.59%   |
| Logitech HD Webcam C525                 | 27       | 2.18%   |
| Logitech Webcam C310                    | 25       | 2.02%   |
| Logitech Webcam C170                    | 25       | 2.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 23       | 1.86%   |
| Microdia USB 2.0 Camera                 | 22       | 1.78%   |
| GEMBIRD USB2.0 PC CAMERA                | 22       | 1.78%   |
| Microdia Camera                         | 21       | 1.7%    |
| Generalplus GENERAL WEBCAM              | 21       | 1.7%    |
| ARC International Camera                | 19       | 1.54%   |
| Z-Star Venus USB2.0 Camera              | 16       | 1.29%   |
| Logitech HD Webcam C615                 | 16       | 1.29%   |
| Sunplus Canyon CNS-CWC5 Webcam          | 15       | 1.21%   |
| Microdia Sonix USB 2.0 Camera           | 15       | 1.21%   |
| Logitech Webcam C210                    | 14       | 1.13%   |
| Logitech C922 Pro Stream Webcam         | 13       | 1.05%   |
| Generalplus 808 Camera                  | 13       | 1.05%   |
| Logitech C920 PRO HD Webcam             | 12       | 0.97%   |
| Chicony HP High Definition 1MP Webcam   | 11       | 0.89%   |
| Sunplus FHD Camera Microphone           | 10       | 0.81%   |
| Realtek Full HD webcam                  | 10       | 0.81%   |
| Logitech Webcam C925e                   | 10       | 0.81%   |
| Logitech QuickCam Pro 9000              | 10       | 0.81%   |
| Jieli USB PHY 2.0                       | 10       | 0.81%   |
| IMC Networks XHC Camera                 | 10       | 0.81%   |
| Microsoft LifeCam Cinema                | 9        | 0.73%   |
| Microdia Integrated Camera              | 9        | 0.73%   |
| Logitech BRIO Ultra HD Webcam           | 9        | 0.73%   |
| Arkmicro USB2.0 PC CAMERA               | 9        | 0.73%   |
| Microsoft LifeCam HD-5000               | 8        | 0.65%   |
| Logitech Webcam C930e                   | 8        | 0.65%   |
| Logitech Webcam C200                    | 8        | 0.65%   |
| Logitech HD Webcam C910                 | 8        | 0.65%   |
| Logitech HD Webcam C510                 | 8        | 0.65%   |
| Aveo UVC camera (Bresser microscope)    | 8        | 0.65%   |
| MacroSilicon USB Video                  | 7        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 4        | 30.77%  |
| LighTuning Technology      | 2        | 15.38%  |
| AuthenTec                  | 2        | 15.38%  |
| Upek                       | 1        | 7.69%   |
| Synaptics                  | 1        | 7.69%   |
| STMicroelectronics         | 1        | 7.69%   |
| Shenzhen Goodix Technology | 1        | 7.69%   |
| Microsoft                  | 1        | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 4        | 30.77%  |
| LighTuning Fingerprint Sensor                          | 2        | 15.38%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 7.69%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 7.69%   |
| STMicroelectronics Fingerprint Reader                  | 1        | 7.69%   |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 7.69%   |
| Microsoft Fingerprint Reader                           | 1        | 7.69%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1        | 7.69%   |
| AuthenTec AES1600                                      | 1        | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 11       | 26.83%  |
| OmniKey                           | 5        | 12.2%   |
| SCM Microsystems                  | 4        | 9.76%   |
| Gemalto (was Gemplus)             | 4        | 9.76%   |
| Reiner SCT Kartensysteme          | 2        | 4.88%   |
| Realtek Semiconductor             | 2        | 4.88%   |
| Chicony Electronics               | 2        | 4.88%   |
| VASCO Data Security International | 1        | 2.44%   |
| Precise Biometrics                | 1        | 2.44%   |
| In Focus Systems                  | 1        | 2.44%   |
| Hewlett-Packard                   | 1        | 2.44%   |
| Giesecke & Devrient               | 1        | 2.44%   |
| Fujitsu Siemens Computers         | 1        | 2.44%   |
| Bit4id                            | 1        | 2.44%   |
| Aladdin R.D.                      | 1        | 2.44%   |
| Aladdin Knowledge Systems         | 1        | 2.44%   |
| Aktiv                             | 1        | 2.44%   |
| Advanced Card Systems             | 1        | 2.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                                               | 6        | 14.63%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 5        | 12.2%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 9.76%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.32%   |
| OmniKey CardMan 3021 / 3121                                                | 3        | 7.32%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 2        | 4.88%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 4.88%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 2.44%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.44%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 1        | 2.44%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.44%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                 | 1        | 2.44%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.44%   |
| OmniKey CardMan 1021                                                       | 1        | 2.44%   |
| In Focus Systems EMV Smartcard Reader                                      | 1        | 2.44%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 1        | 2.44%   |
| Giesecke & Devrient StarSign CUT                                           | 1        | 2.44%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.44%   |
| Bit4id miniLector-s                                                        | 1        | 2.44%   |
| Aladdin R.D. JaCarta                                                       | 1        | 2.44%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 2.44%   |
| Aktiv Rutoken lite                                                         | 1        | 2.44%   |
| Advanced Card Systems ACR122U                                              | 1        | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 5246     | 82.26%  |
| 1     | 932      | 14.62%  |
| 2     | 156      | 2.45%   |
| 3     | 26       | 0.41%   |
| 4     | 9        | 0.14%   |
| 5     | 6        | 0.09%   |
| 6     | 2        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 423      | 32.09%  |
| Net/wireless             | 365      | 27.69%  |
| Communication controller | 139      | 10.55%  |
| Unassigned class         | 56       | 4.25%   |
| Multimedia controller    | 49       | 3.72%   |
| Sound                    | 45       | 3.41%   |
| Bluetooth                | 33       | 2.5%    |
| Network                  | 32       | 2.43%   |
| Chipcard                 | 27       | 2.05%   |
| Camera                   | 27       | 2.05%   |
| Net/ethernet             | 22       | 1.67%   |
| Storage/raid             | 21       | 1.59%   |
| Card reader              | 20       | 1.52%   |
| Storage/ide              | 17       | 1.29%   |
| Modem                    | 13       | 0.99%   |
| Fingerprint reader       | 11       | 0.83%   |
| Dvb card                 | 7        | 0.53%   |
| Firewire controller      | 3        | 0.23%   |
| Unclassified device      | 2        | 0.15%   |
| Tv card                  | 2        | 0.15%   |
| Storage/nvme             | 2        | 0.15%   |
| Storage/ata              | 2        | 0.15%   |

