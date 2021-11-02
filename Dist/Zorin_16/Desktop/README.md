Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [0981774043](https://linux-hardware.org/?probe=0981774043) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| ASUSTek       | M5A78L                      | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Biostar       | G41-M7                      | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| Dell          | 0VHXCD A00                  | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| HP            | 8591                        | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| Gigabyte      | H81M-S2PV                   | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| Lenovo        | IdeaCentre K330             | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| Dell          | 0TNXNR A01                  | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0TP406                      | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| HP            | 18E7                        | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| MSI           | B75MA-P45                   | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| HP            | 18E7                        | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| MSI           | H81M-E33                    | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| ASRock        | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel         | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR           | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| ASUSTek       | Benicia                     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | 339A                        | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| HP            | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Unknown       | Unknown                     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| MSI           | B560M PRO-VDH               | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| Gigabyte      | G31M-ES2L                   | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| MSI           | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| MSI           | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| HP            | 2B4B                        | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| HP            | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Gigabyte      | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| MSI           | Z87-G43                     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell          | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte      | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Board                       | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Board                       | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel         | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte      | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte      | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell          | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP            | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock        | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock        | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek       | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell          | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron      | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer          | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-27-generic | 54       | 29.51%  |
| 5.11.0-37-generic | 33       | 18.03%  |
| 5.11.0-34-generic | 31       | 16.94%  |
| 5.11.0-38-generic | 24       | 13.11%  |
| 5.11.0-36-generic | 12       | 6.56%   |
| 5.8.0-53-generic  | 7        | 3.83%   |
| 5.8.0-55-generic  | 5        | 2.73%   |
| 5.8.0-50-generic  | 5        | 2.73%   |
| 5.8.0-59-generic  | 3        | 1.64%   |
| 5.8.0-49-generic  | 3        | 1.64%   |
| 5.11.0-25-generic | 3        | 1.64%   |
| 5.8.0-63-generic  | 2        | 1.09%   |
| 5.8.0-45-generic  | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 153      | 85.96%  |
| 5.8.0   | 25       | 14.04%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 153      | 85.96%  |
| 5.8     | 25       | 14.04%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 174      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 167      | 95.43%  |
| XFCE     | 3        | 1.71%   |
| Unknown  | 3        | 1.71%   |
| MATE     | 1        | 0.57%   |
| Cinnamon | 1        | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 174      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 162      | 93.1%   |
| GDM     | 7        | 4.02%   |
| GDM3    | 4        | 2.3%    |
| TDM     | 1        | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 75       | 43.1%   |
| de_DE | 21       | 12.07%  |
| en_GB | 16       | 9.2%    |
| pt_BR | 12       | 6.9%    |
| es_ES | 5        | 2.87%   |
| en_IN | 5        | 2.87%   |
| pl_PL | 4        | 2.3%    |
| nl_NL | 4        | 2.3%    |
| es_MX | 4        | 2.3%    |
| it_IT | 2        | 1.15%   |
| fr_CA | 2        | 1.15%   |
| en_ZA | 2        | 1.15%   |
| en_CA | 2        | 1.15%   |
| en_AU | 2        | 1.15%   |
| de_CH | 2        | 1.15%   |
| zh_CN | 1        | 0.57%   |
| tr_TR | 1        | 0.57%   |
| sv_SE | 1        | 0.57%   |
| ru_RU | 1        | 0.57%   |
| pt_PT | 1        | 0.57%   |
| nl_BE | 1        | 0.57%   |
| hu_HU | 1        | 0.57%   |
| fr_CH | 1        | 0.57%   |
| es_PE | 1        | 0.57%   |
| es_PA | 1        | 0.57%   |
| es_GT | 1        | 0.57%   |
| es_CL | 1        | 0.57%   |
| en_SG | 1        | 0.57%   |
| en_NZ | 1        | 0.57%   |
| cs_CZ | 1        | 0.57%   |
| C     | 1        | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 94       | 53.71%  |
| EFI  | 81       | 46.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 162      | 93.1%   |
| Zfs     | 3        | 1.72%   |
| Overlay | 3        | 1.72%   |
| Btrfs   | 3        | 1.72%   |
| Xfs     | 1        | 0.57%   |
| Ext3    | 1        | 0.57%   |
| Ext2    | 1        | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 163      | 93.68%  |
| GPT     | 9        | 5.17%   |
| MBR     | 2        | 1.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 96%     |
| Yes       | 7        | 4%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 153      | 87.93%  |
| Yes       | 21       | 12.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 54       | 31.03%  |
| Gigabyte Technology         | 30       | 17.24%  |
| Dell                        | 16       | 9.2%    |
| MSI                         | 15       | 8.62%   |
| ASRock                      | 15       | 8.62%   |
| Hewlett-Packard             | 13       | 7.47%   |
| Lenovo                      | 11       | 6.32%   |
| Intel                       | 5        | 2.87%   |
| Biostar                     | 4        | 2.3%    |
| Fujitsu                     | 2        | 1.15%   |
| Sapphire Technology Limited | 1        | 0.57%   |
| Positivo                    | 1        | 0.57%   |
| Pegatron                    | 1        | 0.57%   |
| NCR                         | 1        | 0.57%   |
| Foxconn                     | 1        | 0.57%   |
| eMachines                   | 1        | 0.57%   |
| Alienware                   | 1        | 0.57%   |
| Acer                        | 1        | 0.57%   |
| Unknown                     | 1        | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 6        | 3.45%   |
| Dell OptiPlex 990                        | 4        | 2.3%    |
| Gigabyte A320M-S2H                       | 3        | 1.72%   |
| MSI MS-7817                              | 2        | 1.15%   |
| Intel DQ77MK-R01                         | 2        | 1.15%   |
| Gigabyte 970A-DS3P                       | 2        | 1.15%   |
| Dell XPS420                              | 2        | 1.15%   |
| Dell OptiPlex 790                        | 2        | 1.15%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 1.15%   |
| ASUS M5A97 LE R2.0                       | 2        | 1.15%   |
| ASUS M5A78L-M/USB3                       | 2        | 1.15%   |
| Sapphire Limited PURE PLATINUM 970A-PLUS | 1        | 0.57%   |
| Positivo POS-PIH81DI                     | 1        | 0.57%   |
| Pegatron NE502AV-ABA a6750t              | 1        | 0.57%   |
| NCR xxxx-xxxx-xxxx                       | 1        | 0.57%   |
| MSI WE136AA-UUZ p6337ch                  | 1        | 0.57%   |
| MSI Pro 3515 Series                      | 1        | 0.57%   |
| MSI MS-7D18                              | 1        | 0.57%   |
| MSI MS-7C94                              | 1        | 0.57%   |
| MSI MS-7C79                              | 1        | 0.57%   |
| MSI MS-7C37                              | 1        | 0.57%   |
| MSI MS-7B89                              | 1        | 0.57%   |
| MSI MS-7B84                              | 1        | 0.57%   |
| MSI MS-7A71                              | 1        | 0.57%   |
| MSI MS-7914                              | 1        | 0.57%   |
| MSI MS-7816                              | 1        | 0.57%   |
| MSI MS-7798                              | 1        | 0.57%   |
| MSI MS-7750                              | 1        | 0.57%   |
| Lenovo ThinkStation P510 30B4S0F616      | 1        | 0.57%   |
| Lenovo ThinkCentre M93p 10AAS0ME00       | 1        | 0.57%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB  | 1        | 0.57%   |
| Lenovo ThinkCentre M81 0385AW6           | 1        | 0.57%   |
| Lenovo ThinkCentre M78 10BTA00ELM        | 1        | 0.57%   |
| Lenovo ThinkCentre M73 10B7S02L00        | 1        | 0.57%   |
| Lenovo ThinkCentre M58 3231W2Y           | 1        | 0.57%   |
| Lenovo SHARKBAY SDK0E50510 WIN           | 1        | 0.57%   |
| Lenovo IdeaCentre K330                   | 1        | 0.57%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS  | 1        | 0.57%   |
| Lenovo Board                             | 1        | 0.57%   |
| Intel X99                                | 1        | 0.57%   |
| Intel X79M-S                             | 1        | 0.57%   |
| Intel DB75EN AAG39650-303                | 1        | 0.57%   |
| HP Z420 Workstation                      | 1        | 0.57%   |
| HP Z240 SFF Workstation                  | 1        | 0.57%   |
| HP Z1 Entry Tower G5                     | 1        | 0.57%   |
| HP t620 PLUS Quad Core TC                | 1        | 0.57%   |
| HP t620 Dual Core TC                     | 1        | 0.57%   |
| HP ProDesk 600 G1 SFF                    | 1        | 0.57%   |
| HP Compaq Pro 6300 SFF                   | 1        | 0.57%   |
| HP Compaq Pro 6300 MT                    | 1        | 0.57%   |
| HP Compaq 6200 Pro SFF PC                | 1        | 0.57%   |
| HP 870-158ng                             | 1        | 0.57%   |
| HP 290 G2 MT Business PC                 | 1        | 0.57%   |
| HP 251-a123w                             | 1        | 0.57%   |
| HP 200-010                               | 1        | 0.57%   |
| Gigabyte Z77-D3H                         | 1        | 0.57%   |
| Gigabyte Z490 AORUS ELITE                | 1        | 0.57%   |
| Gigabyte X570 AORUS MASTER               | 1        | 0.57%   |
| Gigabyte X570 AORUS ELITE                | 1        | 0.57%   |
| Gigabyte Komputer                        | 1        | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 10       | 5.75%   |
| ASUS PRIME             | 8        | 4.6%    |
| Lenovo ThinkCentre     | 6        | 3.45%   |
| ASUS All               | 6        | 3.45%   |
| ASUS ROG               | 5        | 2.87%   |
| ASUS M5A97             | 4        | 2.3%    |
| HP Compaq              | 3        | 1.72%   |
| Gigabyte A320M-S2H     | 3        | 1.72%   |
| ASUS P8H61-M           | 3        | 1.72%   |
| ASUS M5A78L-M          | 3        | 1.72%   |
| MSI MS-7817            | 2        | 1.15%   |
| Lenovo IdeaCentre      | 2        | 1.15%   |
| Intel DQ77MK-R01       | 2        | 1.15%   |
| HP t620                | 2        | 1.15%   |
| Gigabyte X570          | 2        | 1.15%   |
| Gigabyte GA-78LMT-USB3 | 2        | 1.15%   |
| Gigabyte B550M         | 2        | 1.15%   |
| Gigabyte B450          | 2        | 1.15%   |
| Gigabyte 970A-DS3P     | 2        | 1.15%   |
| Dell XPS420            | 2        | 1.15%   |
| Dell Precision         | 2        | 1.15%   |
| ASUS TUF               | 2        | 1.15%   |
| ASUS P8Z77-V           | 2        | 1.15%   |
| ASUS P5K               | 2        | 1.15%   |
| ASRock B450            | 2        | 1.15%   |
| Sapphire Limited PURE  | 1        | 0.57%   |
| Positivo POS-PIH81DI   | 1        | 0.57%   |
| Pegatron NE502AV-ABA   | 1        | 0.57%   |
| NCR xxxx-xxxx-xxxx     | 1        | 0.57%   |
| MSI WE136AA-UUZ        | 1        | 0.57%   |
| MSI Pro                | 1        | 0.57%   |
| MSI MS-7D18            | 1        | 0.57%   |
| MSI MS-7C94            | 1        | 0.57%   |
| MSI MS-7C79            | 1        | 0.57%   |
| MSI MS-7C37            | 1        | 0.57%   |
| MSI MS-7B89            | 1        | 0.57%   |
| MSI MS-7B84            | 1        | 0.57%   |
| MSI MS-7A71            | 1        | 0.57%   |
| MSI MS-7914            | 1        | 0.57%   |
| MSI MS-7816            | 1        | 0.57%   |
| MSI MS-7798            | 1        | 0.57%   |
| MSI MS-7750            | 1        | 0.57%   |
| Lenovo ThinkStation    | 1        | 0.57%   |
| Lenovo SHARKBAY        | 1        | 0.57%   |
| Lenovo Board           | 1        | 0.57%   |
| Intel X99              | 1        | 0.57%   |
| Intel X79M-S           | 1        | 0.57%   |
| Intel DB75EN           | 1        | 0.57%   |
| HP Z420                | 1        | 0.57%   |
| HP Z240                | 1        | 0.57%   |
| HP Z1                  | 1        | 0.57%   |
| HP ProDesk             | 1        | 0.57%   |
| HP 870-158ng           | 1        | 0.57%   |
| HP 290                 | 1        | 0.57%   |
| HP 251-a123w           | 1        | 0.57%   |
| HP 200-010             | 1        | 0.57%   |
| Gigabyte Z77-D3H       | 1        | 0.57%   |
| Gigabyte Z490          | 1        | 0.57%   |
| Gigabyte Komputer      | 1        | 0.57%   |
| Gigabyte J4005ND2P-CF  | 1        | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 24       | 13.79%  |
| 2021 | 21       | 12.07%  |
| 2018 | 17       | 9.77%   |
| 2014 | 16       | 9.2%    |
| 2015 | 15       | 8.62%   |
| 2013 | 15       | 8.62%   |
| 2012 | 12       | 6.9%    |
| 2019 | 10       | 5.75%   |
| 2016 | 10       | 5.75%   |
| 2010 | 10       | 5.75%   |
| 2011 | 7        | 4.02%   |
| 2009 | 6        | 3.45%   |
| 2008 | 5        | 2.87%   |
| 2017 | 4        | 2.3%    |
| 2007 | 1        | 0.57%   |
| 2006 | 1        | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 174      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 163      | 92.61%  |
| Enabled  | 13       | 7.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 174      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 51       | 28.65%  |
| 16.01-24.0  | 43       | 24.16%  |
| 4.01-8.0    | 27       | 15.17%  |
| 32.01-64.0  | 26       | 14.61%  |
| 3.01-4.0    | 21       | 11.8%   |
| 1.01-2.0    | 4        | 2.25%   |
| 24.01-32.0  | 3        | 1.69%   |
| 64.01-256.0 | 3        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 79       | 43.65%  |
| 2.01-3.0   | 60       | 33.15%  |
| 3.01-4.0   | 20       | 11.05%  |
| 4.01-8.0   | 17       | 9.39%   |
| 8.01-16.0  | 2        | 1.1%    |
| 0.51-1.0   | 2        | 1.1%    |
| 16.01-24.0 | 1        | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 36.16%  |
| 2      | 57       | 32.2%   |
| 3      | 24       | 13.56%  |
| 4      | 13       | 7.34%   |
| 5      | 11       | 6.21%   |
| 6      | 4        | 2.26%   |
| 8      | 3        | 1.69%   |
| 0      | 1        | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 95       | 54.29%  |
| No        | 80       | 45.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 174      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 50.57%  |
| Yes       | 86       | 49.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 68.75%  |
| Yes       | 55       | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 47       | 27.01%  |
| Germany      | 21       | 12.07%  |
| UK           | 15       | 8.62%   |
| Brazil       | 13       | 7.47%   |
| Netherlands  | 6        | 3.45%   |
| Spain        | 5        | 2.87%   |
| India        | 5        | 2.87%   |
| Canada       | 5        | 2.87%   |
| Switzerland  | 4        | 2.3%    |
| Poland       | 4        | 2.3%    |
| Mexico       | 4        | 2.3%    |
| Italy        | 4        | 2.3%    |
| Hungary      | 4        | 2.3%    |
| Denmark      | 3        | 1.72%   |
| Australia    | 3        | 1.72%   |
| Turkey       | 2        | 1.15%   |
| Sweden       | 2        | 1.15%   |
| South Africa | 2        | 1.15%   |
| Norway       | 2        | 1.15%   |
| Malaysia     | 2        | 1.15%   |
| El Salvador  | 2        | 1.15%   |
| Chile        | 2        | 1.15%   |
| Austria      | 2        | 1.15%   |
| Taiwan       | 1        | 0.57%   |
| Serbia       | 1        | 0.57%   |
| Russia       | 1        | 0.57%   |
| Romania      | 1        | 0.57%   |
| Peru         | 1        | 0.57%   |
| Panama       | 1        | 0.57%   |
| New Zealand  | 1        | 0.57%   |
| Mozambique   | 1        | 0.57%   |
| Jamaica      | 1        | 0.57%   |
| Indonesia    | 1        | 0.57%   |
| Guatemala    | 1        | 0.57%   |
| Czechia      | 1        | 0.57%   |
| China        | 1        | 0.57%   |
| Belgium      | 1        | 0.57%   |
| Argentina    | 1        | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Vienna                 | 2        | 1.14%   |
| Vadodara               | 2        | 1.14%   |
| Santiago               | 2        | 1.14%   |
| Rio de Janeiro         | 2        | 1.14%   |
| Munich                 | 2        | 1.14%   |
| Mentor                 | 2        | 1.14%   |
| Melbourne              | 2        | 1.14%   |
| Livingston             | 2        | 1.14%   |
| Kuala Lumpur           | 2        | 1.14%   |
| Hamburg                | 2        | 1.14%   |
| Drummondville          | 2        | 1.14%   |
| Contagem               | 2        | 1.14%   |
| Berlin                 | 2        | 1.14%   |
| Zurich                 | 1        | 0.57%   |
| Zephyrhills            | 1        | 0.57%   |
| Xalapa                 | 1        | 0.57%   |
| Wylie                  | 1        | 0.57%   |
| Williamsburg           | 1        | 0.57%   |
| Warsaw                 | 1        | 0.57%   |
| Warrenton              | 1        | 0.57%   |
| Wandsworth             | 1        | 0.57%   |
| Vespasiano             | 1        | 0.57%   |
| Vancouver              | 1        | 0.57%   |
| Valley Stream          | 1        | 0.57%   |
| Utrecht                | 1        | 0.57%   |
| Tucson                 | 1        | 0.57%   |
| Trujillo               | 1        | 0.57%   |
| Titusville             | 1        | 0.57%   |
| The Hague              | 1        | 0.57%   |
| Thame                  | 1        | 0.57%   |
| Taby                   | 1        | 0.57%   |
| SÃ£o Bernardo do Campo | 1        | 0.57%   |
| Szombathely            | 1        | 0.57%   |
| Szigetvar              | 1        | 0.57%   |
| Stuttgart              | 1        | 0.57%   |
| Stockholm              | 1        | 0.57%   |
| Spartanburg            | 1        | 0.57%   |
| Spanish Town           | 1        | 0.57%   |
| Solingen               | 1        | 0.57%   |
| Shenzhen               | 1        | 0.57%   |
| Sheffield              | 1        | 0.57%   |
| Serra                  | 1        | 0.57%   |
| Sechelt                | 1        | 0.57%   |
| S??o Paulo             | 1        | 0.57%   |
| S??o Jos?© dos Campos  | 1        | 0.57%   |
| Satu Mare              | 1        | 0.57%   |
| Saratov                | 1        | 0.57%   |
| Santander              | 1        | 0.57%   |
| Santa Tecla            | 1        | 0.57%   |
| Santa Cruz de Tenerife | 1        | 0.57%   |
| Sanremo                | 1        | 0.57%   |
| San Salvador           | 1        | 0.57%   |
| San Francisco          | 1        | 0.57%   |
| Salt Lake City         | 1        | 0.57%   |
| Salem                  | 1        | 0.57%   |
| Sacramento             | 1        | 0.57%   |
| Saalfeld               | 1        | 0.57%   |
| Rotterdam              | 1        | 0.57%   |
| Richmond               | 1        | 0.57%   |
| Redruth                | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 61       | 92     | 18.65%  |
| WDC                       | 54       | 71     | 16.51%  |
| Samsung Electronics       | 48       | 74     | 14.68%  |
| Toshiba                   | 22       | 25     | 6.73%   |
| SanDisk                   | 21       | 28     | 6.42%   |
| Kingston                  | 18       | 21     | 5.5%    |
| Hitachi                   | 17       | 20     | 5.2%    |
| Phison                    | 9        | 10     | 2.75%   |
| Crucial                   | 7        | 12     | 2.14%   |
| Unknown                   | 6        | 10     | 1.83%   |
| A-DATA Technology         | 6        | 7      | 1.83%   |
| Silicon Motion            | 5        | 9      | 1.53%   |
| HGST                      | 5        | 7      | 1.53%   |
| MAXTOR                    | 3        | 3      | 0.92%   |
| Lexar                     | 3        | 3      | 0.92%   |
| JMicron                   | 3        | 4      | 0.92%   |
| Hewlett-Packard           | 3        | 4      | 0.92%   |
| China                     | 3        | 3      | 0.92%   |
| XPG                       | 2        | 2      | 0.61%   |
| Super Talent              | 2        | 2      | 0.61%   |
| OCZ                       | 2        | 2      | 0.61%   |
| Micron/Crucial Technology | 2        | 2      | 0.61%   |
| Gigabyte Technology       | 2        | 2      | 0.61%   |
| Verbatim                  | 1        | 1      | 0.31%   |
| Team                      | 1        | 2      | 0.31%   |
| SuperSSpeed               | 1        | 2      | 0.31%   |
| Smartbuy                  | 1        | 1      | 0.31%   |
| SK Hynix                  | 1        | 1      | 0.31%   |
| SABRENT                   | 1        | 1      | 0.31%   |
| Realtek Semiconductor     | 1        | 1      | 0.31%   |
| PNY                       | 1        | 1      | 0.31%   |
| Patriot                   | 1        | 1      | 0.31%   |
| OWC                       | 1        | 1      | 0.31%   |
| Netac                     | 1        | 1      | 0.31%   |
| MyDigitalSSD              | 1        | 1      | 0.31%   |
| Mushkin                   | 1        | 1      | 0.31%   |
| Micron Technology         | 1        | 1      | 0.31%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.31%   |
| KingSpec                  | 1        | 2      | 0.31%   |
| KingFast                  | 1        | 1      | 0.31%   |
| Intenso                   | 1        | 1      | 0.31%   |
| Intel                     | 1        | 1      | 0.31%   |
| INNOVATION IT             | 1        | 1      | 0.31%   |
| GOODRAM                   | 1        | 1      | 0.31%   |
| Config                    | 1        | 1      | 0.31%   |
| Apacer                    | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 7        | 1.81%   |
| Samsung SSD 860 EVO 500GB           | 7        | 1.81%   |
| Seagate ST2000DM001-9YN164 2TB      | 5        | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 1.3%    |
| Samsung NVMe SSD Drive 500GB        | 5        | 1.3%    |
| Phison NVMe SSD Drive 1TB           | 5        | 1.3%    |
| Kingston SA400S37240G 240GB SSD     | 5        | 1.3%    |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 1.04%   |
| Toshiba HDWD110 1TB                 | 4        | 1.04%   |
| Samsung SSD 840 EVO 250GB           | 4        | 1.04%   |
| Samsung NVMe SSD Drive 1TB          | 4        | 1.04%   |
| Kingston SV300S37A120G 120GB SSD    | 4        | 1.04%   |
| WDC WD1600AAJS-75M0A0 160GB         | 3        | 0.78%   |
| WDC WD10EZEX-60M2NA0 1TB            | 3        | 0.78%   |
| Unknown SD/MMC/MS PRO 128GB         | 3        | 0.78%   |
| Toshiba DT01ACA200 2TB              | 3        | 0.78%   |
| Seagate ST3500418AS 500GB           | 3        | 0.78%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 0.78%   |
| SanDisk SDSSDA240G 240GB            | 3        | 0.78%   |
| Samsung SSD 870 EVO 1TB             | 3        | 0.78%   |
| Samsung SSD 850 EVO 500GB           | 3        | 0.78%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.78%   |
| Samsung HD103UJ 1TB                 | 3        | 0.78%   |
| Phison NVMe SSD Drive 512GB         | 3        | 0.78%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 0.78%   |
| WDC WD800JD-75MSA3 80GB             | 2        | 0.52%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 2        | 0.52%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.52%   |
| Toshiba MQ01ABD032 320GB            | 2        | 0.52%   |
| Toshiba DT01ACA100 1TB              | 2        | 0.52%   |
| Toshiba DT01ACA050 500GB            | 2        | 0.52%   |
| Silicon Motion NVMe SSD Drive 128GB | 2        | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 0.52%   |
| Seagate ST4000DM000-1F2168 4TB      | 2        | 0.52%   |
| Seagate ST31500341AS 1TB            | 2        | 0.52%   |
| Seagate ST2000DX002-2DV164 2TB      | 2        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 0.52%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.52%   |
| Seagate Expansion 1TB               | 2        | 0.52%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.52%   |
| Samsung SSD 870 QVO 1TB             | 2        | 0.52%   |
| Samsung SSD 860 EVO 250GB           | 2        | 0.52%   |
| Samsung SSD 840 EVO 120GB           | 2        | 0.52%   |
| Samsung NVMe SSD Drive 256GB        | 2        | 0.52%   |
| Samsung HD103SJ 1TB                 | 2        | 0.52%   |
| Kingston SV300S37A240G 240GB SSD    | 2        | 0.52%   |
| JMicron Tech 250GB                  | 2        | 0.52%   |
| Hitachi HDT725050VLA360 500GB       | 2        | 0.52%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 0.52%   |
| Crucial CT500MX500SSD1 500GB        | 2        | 0.52%   |
| Crucial CT480BX500SSD1 480GB        | 2        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 2        | 0.52%   |
| A-DATA SU750 256GB SSD              | 2        | 0.52%   |
| XPG NVMe SSD Drive 512GB            | 1        | 0.26%   |
| XPG NVMe SSD Drive 1024GB           | 1        | 0.26%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1        | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 61       | 90     | 35.06%  |
| WDC                 | 54       | 68     | 31.03%  |
| Toshiba             | 20       | 23     | 11.49%  |
| Hitachi             | 17       | 20     | 9.77%   |
| Samsung Electronics | 8        | 13     | 4.6%    |
| HGST                | 5        | 7      | 2.87%   |
| Unknown             | 3        | 5      | 1.72%   |
| MAXTOR              | 3        | 3      | 1.72%   |
| Hewlett-Packard     | 2        | 3      | 1.15%   |
| SABRENT             | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 41     | 27.59%  |
| SanDisk             | 17       | 23     | 14.66%  |
| Kingston            | 16       | 19     | 13.79%  |
| Crucial             | 7        | 12     | 6.03%   |
| A-DATA Technology   | 6        | 7      | 5.17%   |
| WDC                 | 3        | 3      | 2.59%   |
| Lexar               | 3        | 3      | 2.59%   |
| China               | 3        | 3      | 2.59%   |
| Super Talent        | 2        | 2      | 1.72%   |
| OCZ                 | 2        | 2      | 1.72%   |
| Gigabyte Technology | 2        | 2      | 1.72%   |
| Verbatim            | 1        | 1      | 0.86%   |
| Toshiba             | 1        | 1      | 0.86%   |
| Team                | 1        | 2      | 0.86%   |
| SuperSSpeed         | 1        | 2      | 0.86%   |
| Smartbuy            | 1        | 1      | 0.86%   |
| SK Hynix            | 1        | 1      | 0.86%   |
| Seagate             | 1        | 1      | 0.86%   |
| PNY                 | 1        | 1      | 0.86%   |
| PHISON              | 1        | 1      | 0.86%   |
| Patriot             | 1        | 1      | 0.86%   |
| OWC                 | 1        | 1      | 0.86%   |
| Netac               | 1        | 1      | 0.86%   |
| MyDigitalSSD        | 1        | 1      | 0.86%   |
| Mushkin             | 1        | 1      | 0.86%   |
| Micron Technology   | 1        | 1      | 0.86%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.86%   |
| KingSpec            | 1        | 2      | 0.86%   |
| Intenso             | 1        | 1      | 0.86%   |
| Intel               | 1        | 1      | 0.86%   |
| INNOVATION IT       | 1        | 1      | 0.86%   |
| Hewlett-Packard     | 1        | 1      | 0.86%   |
| GOODRAM             | 1        | 1      | 0.86%   |
| Apacer              | 1        | 1      | 0.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 125      | 233    | 46.99%  |
| SSD     | 94       | 143    | 35.34%  |
| NVMe    | 39       | 51     | 14.66%  |
| Unknown | 8        | 12     | 3.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 167      | 366    | 75.91%  |
| NVMe | 39       | 51     | 17.73%  |
| SAS  | 14       | 22     | 6.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 129      | 196    | 52.02%  |
| 0.51-1.0   | 72       | 111    | 29.03%  |
| 1.01-2.0   | 30       | 42     | 12.1%   |
| 3.01-4.0   | 11       | 17     | 4.44%   |
| 4.01-10.0  | 4        | 6      | 1.61%   |
| 2.01-3.0   | 2        | 4      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 43       | 24.43%  |
| 251-500        | 38       | 21.59%  |
| 501-1000       | 31       | 17.61%  |
| 1001-2000      | 17       | 9.66%   |
| 51-100         | 15       | 8.52%   |
| More than 3000 | 14       | 7.95%   |
| 2001-3000      | 8        | 4.55%   |
| 1-20           | 5        | 2.84%   |
| Unknown        | 3        | 1.7%    |
| 21-50          | 2        | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 70       | 38.89%  |
| 21-50          | 38       | 21.11%  |
| 101-250        | 18       | 10%     |
| 51-100         | 17       | 9.44%   |
| More than 3000 | 10       | 5.56%   |
| 501-1000       | 9        | 5%      |
| 1001-2000      | 7        | 3.89%   |
| 251-500        | 6        | 3.33%   |
| Unknown        | 3        | 1.67%   |
| 2001-3000      | 2        | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB       | 1        | 2      | 16.67%  |
| Toshiba MK3265GSX 320GB        | 1        | 1      | 16.67%  |
| Seagate ST9500420AS 500GB      | 1        | 1      | 16.67%  |
| Seagate ST4000DM004-2CV104 4TB | 1        | 1      | 16.67%  |
| Seagate ST2000DM001-9YN164 2TB | 1        | 1      | 16.67%  |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 66.67%  |
| WDC     | 1        | 2      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 66.67%  |
| WDC     | 1        | 2      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 7      | 100%    |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 164      | 408    | 90.61%  |
| Works    | 11       | 24     | 6.08%   |
| Malfunc  | 6        | 7      | 3.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 114      | 49.14%  |
| AMD                          | 57       | 24.57%  |
| Samsung Electronics          | 15       | 6.47%   |
| Phison Electronics           | 9        | 3.88%   |
| ASMedia Technology           | 7        | 3.02%   |
| Silicon Motion               | 5        | 2.16%   |
| Sandisk                      | 4        | 1.72%   |
| Silicon Image                | 3        | 1.29%   |
| JMicron Technology           | 3        | 1.29%   |
| VIA Technologies             | 2        | 0.86%   |
| Nvidia                       | 2        | 0.86%   |
| Micron/Crucial Technology    | 2        | 0.86%   |
| Marvell Technology Group     | 2        | 0.86%   |
| Kingston Technology Company  | 2        | 0.86%   |
| ADATA Technology             | 2        | 0.86%   |
| Toshiba America Info Systems | 1        | 0.43%   |
| Realtek Semiconductor        | 1        | 0.43%   |
| Broadcom / LSI               | 1        | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 9.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 6.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 4.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 4.44%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 3.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 3.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 3.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.05%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 6        | 2.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.71%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.37%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.37%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.02%   |
| AMD FCH IDE Controller                                                                  | 3        | 1.02%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.68%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.68%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.34%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.34%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.34%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.34%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.34%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.34%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.34%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.34%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.34%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.34%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.34%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.34%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.34%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.34%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 0.34%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 134      | 56.3%   |
| IDE  | 48       | 20.17%  |
| NVMe | 39       | 16.39%  |
| RAID | 15       | 6.3%    |
| SAS  | 1        | 0.42%   |
| SCSI | 1        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 116      | 66.67%  |
| AMD    | 58       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 4.02%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 2.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.3%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.72%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 1.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 1.72%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 1.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.72%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.15%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2        | 1.15%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.15%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.15%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.15%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.15%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 2        | 1.15%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.15%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.15%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.15%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.15%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.15%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 1.15%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.15%   |
| AMD FX-6100 Six-Core Processor              | 2        | 1.15%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 1.15%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.57%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.57%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.57%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.57%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.57%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1        | 0.57%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.57%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.57%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.57%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.57%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.57%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.57%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.57%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.57%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.57%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.57%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.57%   |
| Intel Core i7-10700KF CPU @ 3.80GHz         | 1        | 0.57%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.57%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.57%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.57%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.57%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 19.54%  |
| Intel Core i7           | 22       | 12.64%  |
| Intel Core i3           | 21       | 12.07%  |
| AMD FX                  | 14       | 8.05%   |
| AMD Ryzen 5             | 13       | 7.47%   |
| Intel Xeon              | 9        | 5.17%   |
| Intel Core 2 Quad       | 7        | 4.02%   |
| AMD Ryzen 7             | 7        | 4.02%   |
| AMD Ryzen 3             | 6        | 3.45%   |
| Intel Celeron           | 5        | 2.87%   |
| Intel Pentium Dual-Core | 4        | 2.3%    |
| Intel Core 2 Duo        | 4        | 2.3%    |
| Intel Pentium Dual      | 3        | 1.72%   |
| AMD Ryzen 9             | 3        | 1.72%   |
| Intel Pentium           | 2        | 1.15%   |
| Intel Core i9           | 2        | 1.15%   |
| AMD Phenom II X4        | 2        | 1.15%   |
| AMD GX                  | 2        | 1.15%   |
| AMD Athlon X4           | 2        | 1.15%   |
| AMD A6                  | 2        | 1.15%   |
| Other                   | 1        | 0.57%   |
| Intel Pentium Gold      | 1        | 0.57%   |
| Intel Pentium 4         | 1        | 0.57%   |
| AMD Ryzen 5 PRO         | 1        | 0.57%   |
| AMD Phenom II X6        | 1        | 0.57%   |
| AMD Opteron             | 1        | 0.57%   |
| AMD Athlon II X3        | 1        | 0.57%   |
| AMD Athlon 64 X2        | 1        | 0.57%   |
| AMD A4                  | 1        | 0.57%   |
| AMD A10                 | 1        | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 82       | 47.13%  |
| 2      | 45       | 25.86%  |
| 6      | 21       | 12.07%  |
| 8      | 12       | 6.9%    |
| 3      | 6        | 3.45%   |
| 1      | 3        | 1.72%   |
| 12     | 2        | 1.15%   |
| 10     | 2        | 1.15%   |
| 16     | 1        | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 174      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 96       | 55.17%  |
| 1      | 78       | 44.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 174      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 21       | 11.93%  |
| 0x306a9    | 15       | 8.52%   |
| 0x206a7    | 15       | 8.52%   |
| 0x08701021 | 12       | 6.82%   |
| 0x1067a    | 11       | 6.25%   |
| Unknown    | 11       | 6.25%   |
| 0x06000852 | 10       | 5.68%   |
| 0x506e3    | 9        | 5.11%   |
| 0x6fb      | 6        | 3.41%   |
| 0xa0655    | 5        | 2.84%   |
| 0x0600063e | 5        | 2.84%   |
| 0x06001119 | 4        | 2.27%   |
| 0x906eb    | 3        | 1.7%    |
| 0x906e9    | 3        | 1.7%    |
| 0x6fd      | 3        | 1.7%    |
| 0x0a201016 | 3        | 1.7%    |
| 0x08701013 | 3        | 1.7%    |
| 0x0800820d | 3        | 1.7%    |
| 0x010000c8 | 3        | 1.7%    |
| 0xa0653    | 2        | 1.14%   |
| 0x906ea    | 2        | 1.14%   |
| 0x30678    | 2        | 1.14%   |
| 0x20652    | 2        | 1.14%   |
| 0x08108109 | 2        | 1.14%   |
| 0x08101016 | 2        | 1.14%   |
| 0x0700010f | 2        | 1.14%   |
| 0xf43      | 1        | 0.57%   |
| 0xa0671    | 1        | 0.57%   |
| 0x906ec    | 1        | 0.57%   |
| 0x706a1    | 1        | 0.57%   |
| 0x406f1    | 1        | 0.57%   |
| 0x40651    | 1        | 0.57%   |
| 0x306f2    | 1        | 0.57%   |
| 0x306e4    | 1        | 0.57%   |
| 0x206d7    | 1        | 0.57%   |
| 0x206c2    | 1        | 0.57%   |
| 0x106a4    | 1        | 0.57%   |
| 0x10676    | 1        | 0.57%   |
| 0x08600106 | 1        | 0.57%   |
| 0x08001138 | 1        | 0.57%   |
| 0x08001137 | 1        | 0.57%   |
| 0x06003106 | 1        | 0.57%   |
| 0x010000dc | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 25       | 14.37%  |
| SandyBridge   | 17       | 9.77%   |
| Zen 2         | 16       | 9.2%    |
| IvyBridge     | 16       | 9.2%    |
| Piledriver    | 14       | 8.05%   |
| Penryn        | 12       | 6.9%    |
| KabyLake      | 11       | 6.32%   |
| Skylake       | 9        | 5.17%   |
| Core          | 9        | 5.17%   |
| CometLake     | 7        | 4.02%   |
| Zen           | 6        | 3.45%   |
| Zen+          | 5        | 2.87%   |
| Bulldozer     | 5        | 2.87%   |
| K10           | 4        | 2.3%    |
| Zen 3         | 3        | 1.72%   |
| Westmere      | 3        | 1.72%   |
| Jaguar        | 3        | 1.72%   |
| Silvermont    | 2        | 1.15%   |
| Steamroller   | 1        | 0.57%   |
| NetBurst      | 1        | 0.57%   |
| Nehalem       | 1        | 0.57%   |
| K8 Hammer     | 1        | 0.57%   |
| Icelake       | 1        | 0.57%   |
| Goldmont plus | 1        | 0.57%   |
| Broadwell     | 1        | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 85       | 45.95%  |
| AMD              | 50       | 27.03%  |
| Intel            | 49       | 26.49%  |
| VIA Technologies | 1        | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 10       | 5.38%   |
| Nvidia GK208B [GeForce GT 710]                                                | 9        | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9        | 4.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6        | 3.23%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 5        | 2.69%   |
| Nvidia GK208B [GeForce GT 730]                                                | 4        | 2.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 4        | 2.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 4        | 2.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4        | 2.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 4        | 2.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 3        | 1.61%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3        | 1.61%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 3        | 1.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3        | 1.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3        | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3        | 1.61%   |
| AMD RS780L [Radeon 3000]                                                      | 3        | 1.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3        | 1.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 3        | 1.61%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                | 3        | 1.61%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 2        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 2        | 1.08%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2        | 1.08%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 2        | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                    | 2        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2        | 1.08%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 1.08%   |
| Nvidia GF108 [GeForce GT 730]                                                 | 2        | 1.08%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 2        | 1.08%   |
| Nvidia GA106 [GeForce RTX 3060]                                               | 2        | 1.08%   |
| Nvidia G96C [GeForce GT 120]                                                  | 2        | 1.08%   |
| Intel HD Graphics 630                                                         | 2        | 1.08%   |
| Intel HD Graphics 530                                                         | 2        | 1.08%   |
| AMD Trinity 2 [Radeon HD 7540D]                                               | 2        | 1.08%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 2        | 1.08%   |
| AMD RS880 [Radeon HD 4250]                                                    | 2        | 1.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 1.08%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                            | 2        | 1.08%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2        | 1.08%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.54%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.54%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1        | 0.54%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.54%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2060]                                               | 1        | 0.54%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1        | 0.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1        | 0.54%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1        | 0.54%   |
| Nvidia GM206GL [Quadro M2000]                                                 | 1        | 0.54%   |
| Nvidia GM204 [GeForce GTX 980]                                                | 1        | 0.54%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                             | 1        | 0.54%   |
| Nvidia GM107GL [Quadro K620]                                                  | 1        | 0.54%   |
| Nvidia GM107GL [Quadro K1200]                                                 | 1        | 0.54%   |
| Nvidia GK208 [GeForce GT 720]                                                 | 1        | 0.54%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.54%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1        | 0.54%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 1        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 83       | 47.16%  |
| 1 x AMD        | 48       | 27.27%  |
| 1 x Intel      | 39       | 22.16%  |
| Intel + Nvidia | 2        | 1.14%   |
| Intel + AMD    | 2        | 1.14%   |
| 2 x AMD        | 1        | 0.57%   |
| 1 x VIA        | 1        | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 102      | 58.62%  |
| Proprietary | 61       | 35.06%  |
| Unknown     | 11       | 6.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 35.23%  |
| 1.01-2.0   | 29       | 16.48%  |
| 0.51-1.0   | 25       | 14.2%   |
| 0.01-0.5   | 15       | 8.52%   |
| 7.01-8.0   | 14       | 7.95%   |
| 3.01-4.0   | 14       | 7.95%   |
| 5.01-6.0   | 8        | 4.55%   |
| 2.01-3.0   | 5        | 2.84%   |
| 8.01-16.0  | 3        | 1.7%    |
| 16.01-24.0 | 1        | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 15.79%  |
| Dell                 | 16       | 9.36%   |
| Goldstar             | 14       | 8.19%   |
| AOC                  | 13       | 7.6%    |
| Acer                 | 13       | 7.6%    |
| Hewlett-Packard      | 10       | 5.85%   |
| BenQ                 | 10       | 5.85%   |
| Philips              | 9        | 5.26%   |
| LG Electronics       | 6        | 3.51%   |
| Unknown              | 5        | 2.92%   |
| HPN                  | 4        | 2.34%   |
| Ancor Communications | 4        | 2.34%   |
| Vizio                | 3        | 1.75%   |
| ViewSonic            | 3        | 1.75%   |
| Lenovo               | 3        | 1.75%   |
| Vestel               | 2        | 1.17%   |
| Sony                 | 2        | 1.17%   |
| Sceptre Tech         | 2        | 1.17%   |
| NEC Computers        | 2        | 1.17%   |
| Microstep            | 2        | 1.17%   |
| Iiyama               | 2        | 1.17%   |
| AUS                  | 2        | 1.17%   |
| Xiaomi               | 1        | 0.58%   |
| Vestel Elektronik    | 1        | 0.58%   |
| Toshiba              | 1        | 0.58%   |
| Sceptre              | 1        | 0.58%   |
| Sanyo                | 1        | 0.58%   |
| PKB                  | 1        | 0.58%   |
| Panasonic            | 1        | 0.58%   |
| ONN                  | 1        | 0.58%   |
| OEM                  | 1        | 0.58%   |
| Medion               | 1        | 0.58%   |
| Lenovo Group Limited | 1        | 0.58%   |
| HCL                  | 1        | 0.58%   |
| Gigabyte Technology  | 1        | 0.58%   |
| GDH                  | 1        | 0.58%   |
| Gateway              | 1        | 0.58%   |
| Fujitsu Siemens      | 1        | 0.58%   |
| Unknown              | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 2        | 1.1%    |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 2        | 1.1%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch    | 2        | 1.1%    |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 2        | 1.1%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 2        | 1.1%    |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                      | 2        | 1.1%    |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1        | 0.55%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1        | 0.55%   |
| ViewSonic VX3258 series VSCA037 1920x1080 700x390mm 31.5-inch           | 1        | 0.55%   |
| ViewSonic LCD Monitor VA2718-FHD 1920x1080                              | 1        | 0.55%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1        | 0.55%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 0.55%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1        | 0.55%   |
| Unknown LCD Monitor RTK                                                 | 1        | 0.55%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1        | 0.55%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1        | 0.55%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1        | 0.55%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                               | 1        | 0.55%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 0.55%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1        | 0.55%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1        | 0.55%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.55%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch           | 1        | 0.55%   |
| Sceptre LCD Monitor M24 3840x1080                                       | 1        | 0.55%   |
| Sceptre LCD Monitor M24                                                 | 1        | 0.55%   |
| Sanyo LED MONITOR SAN952D 1920x1080 443x249mm 20.0-inch                 | 1        | 0.55%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 0.55%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch       | 1        | 0.55%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 0.55%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.55%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1        | 0.55%   |
| Samsung Electronics SMS27A550H SAM07CB 1680x1050 600x340mm 27.2-inch    | 1        | 0.55%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1        | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1        | 0.55%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.55%   |
| Samsung Electronics S19D300 SAM0B34 1280x720 410x230mm 18.5-inch        | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch   | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch   | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch  | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                        | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM052F 1360x768 410x256mm 19.0-inch    | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 0.55%   |
| Samsung Electronics LCD Monitor S27A950D 4480x1440                      | 1        | 0.55%   |
| Samsung Electronics LCD Monitor LC32G7xT                                | 1        | 0.55%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                       | 1        | 0.55%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                       | 1        | 0.55%   |
| Samsung Electronics LCD Monitor C24F390                                 | 1        | 0.55%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch      | 1        | 0.55%   |
| PKB LCD Monitor Viseo 190 W 1366x768                                    | 1        | 0.55%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch                | 1        | 0.55%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1        | 0.55%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1        | 0.55%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 0.55%   |
| Philips LCD Monitor PHL 328P6V 5760x2160                                | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 80       | 46.78%  |
| 3840x2160 (4K)     | 17       | 9.94%   |
| Unknown            | 15       | 8.77%   |
| 1680x1050 (WSXGA+) | 9        | 5.26%   |
| 3840x1080          | 8        | 4.68%   |
| 1366x768 (WXGA)    | 6        | 3.51%   |
| 3440x1440          | 4        | 2.34%   |
| 1440x900 (WXGA+)   | 4        | 2.34%   |
| 2560x1440 (QHD)    | 3        | 1.75%   |
| 1920x1200 (WUXGA)  | 3        | 1.75%   |
| 1360x768           | 3        | 1.75%   |
| 5760x2160          | 2        | 1.17%   |
| 1280x1024 (SXGA)   | 2        | 1.17%   |
| 4480x1440          | 1        | 0.58%   |
| 4160x1440          | 1        | 0.58%   |
| 3360x1080          | 1        | 0.58%   |
| 3360x1050          | 1        | 0.58%   |
| 3200x1200          | 1        | 0.58%   |
| 3120x1050          | 1        | 0.58%   |
| 2944x1080          | 1        | 0.58%   |
| 2560x1080          | 1        | 0.58%   |
| 2464x900           | 1        | 0.58%   |
| 1920x540           | 1        | 0.58%   |
| 1834x1031          | 1        | 0.58%   |
| 1600x900 (HD+)     | 1        | 0.58%   |
| 1600x1200          | 1        | 0.58%   |
| 1280x720 (HD)      | 1        | 0.58%   |
| 1024x768 (XGA)     | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 31.06%  |
| 24      | 17       | 10.56%  |
| 21      | 16       | 9.94%   |
| 27      | 15       | 9.32%   |
| 31      | 10       | 6.21%   |
| 23      | 9        | 5.59%   |
| 22      | 8        | 4.97%   |
| 18      | 6        | 3.73%   |
| 19      | 5        | 3.11%   |
| 34      | 4        | 2.48%   |
| 84      | 3        | 1.86%   |
| 48      | 2        | 1.24%   |
| 41      | 2        | 1.24%   |
| 32      | 2        | 1.24%   |
| 20      | 2        | 1.24%   |
| 74      | 1        | 0.62%   |
| 72      | 1        | 0.62%   |
| 46      | 1        | 0.62%   |
| 43      | 1        | 0.62%   |
| 40      | 1        | 0.62%   |
| 36      | 1        | 0.62%   |
| 26      | 1        | 0.62%   |
| 25      | 1        | 0.62%   |
| 17      | 1        | 0.62%   |
| 15      | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 50       | 32.05%  |
| 501-600     | 38       | 24.36%  |
| 401-500     | 33       | 21.15%  |
| 601-700     | 13       | 8.33%   |
| 701-800     | 7        | 4.49%   |
| 1501-2000   | 5        | 3.21%   |
| 1001-1500   | 3        | 1.92%   |
| 901-1000    | 3        | 1.92%   |
| 301-350     | 2        | 1.28%   |
| 801-900     | 1        | 0.64%   |
| 351-400     | 1        | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 74       | 49.33%  |
| Unknown | 49       | 32.67%  |
| 16/10   | 19       | 12.67%  |
| 21/9    | 4        | 2.67%   |
| 4/3     | 2        | 1.33%   |
| 5/4     | 1        | 0.67%   |
| 32/9    | 1        | 0.67%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 50       | 31.45%  |
| 201-250        | 42       | 26.42%  |
| 351-500        | 16       | 10.06%  |
| 301-350        | 15       | 9.43%   |
| 151-200        | 11       | 6.92%   |
| 251-300        | 7        | 4.4%    |
| 501-1000       | 7        | 4.4%    |
| More than 1000 | 6        | 3.77%   |
| 141-150        | 4        | 2.52%   |
| 101-110        | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 68       | 44.44%  |
| Unknown | 50       | 32.68%  |
| 101-120 | 20       | 13.07%  |
| 121-160 | 8        | 5.23%   |
| 1-50    | 6        | 3.92%   |
| 161-240 | 1        | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 133      | 75.57%  |
| 2     | 31       | 17.61%  |
| 0     | 12       | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 114      | 43.68%  |
| Intel                    | 66       | 25.29%  |
| Qualcomm Atheros         | 18       | 6.9%    |
| Ralink Technology        | 13       | 4.98%   |
| TP-Link                  | 9        | 3.45%   |
| Ralink                   | 5        | 1.92%   |
| Broadcom                 | 4        | 1.53%   |
| Samsung Electronics      | 3        | 1.15%   |
| D-Link System            | 3        | 1.15%   |
| Xiaomi                   | 2        | 0.77%   |
| Realtek                  | 2        | 0.77%   |
| Nvidia                   | 2        | 0.77%   |
| Microsoft                | 2        | 0.77%   |
| Huawei Technologies      | 2        | 0.77%   |
| Edimax Technology        | 2        | 0.77%   |
| Panasonic (Matsushita)   | 1        | 0.38%   |
| OPPO Electronics         | 1        | 0.38%   |
| NetGear                  | 1        | 0.38%   |
| Motorola PCS             | 1        | 0.38%   |
| MediaTek                 | 1        | 0.38%   |
| Marvell Technology Group | 1        | 0.38%   |
| Linksys                  | 1        | 0.38%   |
| Lenovo                   | 1        | 0.38%   |
| Google                   | 1        | 0.38%   |
| Gemtek                   | 1        | 0.38%   |
| DisplayLink              | 1        | 0.38%   |
| D-Link                   | 1        | 0.38%   |
| Broadcom Limited         | 1        | 0.38%   |
| ADMtek                   | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 91       | 30.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 15       | 5.07%   |
| Intel Wi-Fi 6 AX200                                                  | 11       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                    | 9        | 3.04%   |
| Ralink MT7601U Wireless Adapter                                      | 7        | 2.36%   |
| Intel I211 Gigabit Network Connection                                | 6        | 2.03%   |
| Intel Ethernet Connection (2) I219-V                                 | 6        | 2.03%   |
| Realtek 802.11ac NIC                                                 | 5        | 1.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4        | 1.35%   |
| Intel Ethernet Controller I225-V                                     | 4        | 1.35%   |
| Intel Ethernet Connection I217-LM                                    | 4        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                                 | 4        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4        | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 3        | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 3        | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 3        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 3        | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 3        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2        | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 2        | 0.68%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 2        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 0.68%   |
| Realtek 802.11n NIC                                                  | 2        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 2        | 0.68%   |
| Intel Wireless 7265                                                  | 2        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                 | 2        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 0.68%   |
| Intel 82579V Gigabit Network Connection                              | 2        | 0.68%   |
| Intel 82574L Gigabit Network Connection                              | 2        | 0.68%   |
| Intel 82566DC-2 Gigabit Network Connection                           | 2        | 0.68%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2        | 0.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 2        | 0.68%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 0.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1        | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.34%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 0.34%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 1        | 0.34%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 1        | 0.34%   |
| Ralink RT5592 PCIe Wireless Network Adapter                          | 1        | 0.34%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                 | 1        | 0.34%   |
| Ralink RT2600 802.11 MIMO                                            | 1        | 0.34%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1        | 0.34%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 0.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                           | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 26       | 26%     |
| Realtek Semiconductor  | 22       | 22%     |
| Ralink Technology      | 13       | 13%     |
| TP-Link                | 9        | 9%      |
| Qualcomm Atheros       | 8        | 8%      |
| Ralink                 | 5        | 5%      |
| Realtek                | 2        | 2%      |
| Microsoft              | 2        | 2%      |
| Edimax Technology      | 2        | 2%      |
| D-Link System          | 2        | 2%      |
| Broadcom               | 2        | 2%      |
| Panasonic (Matsushita) | 1        | 1%      |
| NetGear                | 1        | 1%      |
| Linksys                | 1        | 1%      |
| Gemtek                 | 1        | 1%      |
| D-Link                 | 1        | 1%      |
| Broadcom Limited       | 1        | 1%      |
| ADMtek                 | 1        | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 11       | 10.89%  |
| Ralink MT7601U Wireless Adapter                                                         | 7        | 6.93%   |
| Realtek 802.11ac NIC                                                                    | 5        | 4.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 4        | 3.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 4        | 3.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                            | 3        | 2.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                   | 3        | 2.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 3        | 2.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 3        | 2.97%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                  | 2        | 1.98%   |
| TP-Link 802.11ac WLAN Adapter                                                           | 2        | 1.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                         | 2        | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 2        | 1.98%   |
| Realtek 802.11n NIC                                                                     | 2        | 1.98%   |
| Ralink RT5370 Wireless Adapter                                                          | 2        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 2        | 1.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 2        | 1.98%   |
| Intel Wireless 7265                                                                     | 2        | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                          | 2        | 1.98%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                    | 2        | 1.98%   |
| TP-Link Archer T4U ver.3                                                                | 1        | 0.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                              | 1        | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1        | 0.99%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                 | 1        | 0.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                  | 1        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                              | 1        | 0.99%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                | 1        | 0.99%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                   | 1        | 0.99%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                             | 1        | 0.99%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                    | 1        | 0.99%   |
| Ralink RT2600 802.11 MIMO                                                               | 1        | 0.99%   |
| Ralink RT2561/RT61 802.11g PCI                                                          | 1        | 0.99%   |
| Ralink RT2500 Wireless 802.11bg                                                         | 1        | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                        | 1        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 0.99%   |
| Panasonic (Matsushita) N5HBZ0000055 802.11abgn Wireless Adapter [Atheros AR7010+AR9280] | 1        | 0.99%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                             | 1        | 0.99%   |
| Microsoft Xbox 360 Wireless Adapter                                                     | 1        | 0.99%   |
| Microsoft Wireless XBox Controller Dongle                                               | 1        | 0.99%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                  | 1        | 0.99%   |
| Intel Wireless-AC 9260                                                                  | 1        | 0.99%   |
| Intel Wireless 3165                                                                     | 1        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                         | 1        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 1        | 0.99%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                       | 1        | 0.99%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                          | 1        | 0.99%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                | 1        | 0.99%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                    | 1        | 0.99%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                               | 1        | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                                           | 1        | 0.99%   |
| ADMtek ADM8211 802.11b Wireless Interface                                               | 1        | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 108      | 57.45%  |
| Intel                    | 51       | 27.13%  |
| Qualcomm Atheros         | 11       | 5.85%   |
| Samsung Electronics      | 3        | 1.6%    |
| Xiaomi                   | 2        | 1.06%   |
| Nvidia                   | 2        | 1.06%   |
| Huawei Technologies      | 2        | 1.06%   |
| Broadcom                 | 2        | 1.06%   |
| OPPO Electronics         | 1        | 0.53%   |
| Motorola PCS             | 1        | 0.53%   |
| MediaTek                 | 1        | 0.53%   |
| Marvell Technology Group | 1        | 0.53%   |
| Google                   | 1        | 0.53%   |
| DisplayLink              | 1        | 0.53%   |
| D-Link System            | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91       | 46.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15       | 7.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 4.64%   |
| Intel I211 Gigabit Network Connection                             | 6        | 3.09%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 3.09%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.06%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.03%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.03%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.52%   |
| OPPO SDM712-MTP _SN:E0B69F21                                      | 1        | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.52%   |
| Motorola PCS moto g(7)                                            | 1        | 0.52%   |
| MediaTek moto g(8) power lite                                     | 1        | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.52%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.52%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.52%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.52%   |
| Huawei E353/E3131                                                 | 1        | 0.52%   |
| Huawei BLA-L29                                                    | 1        | 0.52%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.52%   |
| DisplayLink LAPDOCK                                               | 1        | 0.52%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 174      | 66.41%  |
| WiFi     | 87       | 33.21%  |
| Unknown  | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 69.46%  |
| WiFi     | 72       | 30.13%  |
| Unknown  | 1        | 0.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 66.67%  |
| 2     | 52       | 29.89%  |
| 3     | 4        | 2.3%    |
| 0     | 2        | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 69.32%  |
| Yes  | 54       | 30.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 34.48%  |
| Cambridge Silicon Radio         | 15       | 25.86%  |
| Realtek Semiconductor           | 7        | 12.07%  |
| Broadcom                        | 4        | 6.9%    |
| ASUSTek Computer                | 4        | 6.9%    |
| Qualcomm Atheros Communications | 2        | 3.45%   |
| Dell                            | 2        | 3.45%   |
| Micro Star International        | 1        | 1.72%   |
| Lite-On Technology              | 1        | 1.72%   |
| IMC Networks                    | 1        | 1.72%   |
| Belkin Components               | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 15       | 25.86%  |
| Realtek Bluetooth Radio                               | 7        | 12.07%  |
| Intel AX200 Bluetooth                                 | 6        | 10.34%  |
| Intel Bluetooth wireless interface                    | 4        | 6.9%    |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 5.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 3.45%   |
| Intel AX210 Bluetooth                                 | 2        | 3.45%   |
| Intel AX201 Bluetooth                                 | 2        | 3.45%   |
| Dell BT Mini-Receiver                                 | 2        | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 3.45%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 3.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.72%   |
| Micro Star International Bluetooth Device             | 1        | 1.72%   |
| Lite-On Bluetooth Device                              | 1        | 1.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.72%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 1.72%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 110      | 36.18%  |
| Nvidia              | 79       | 25.99%  |
| AMD                 | 76       | 25%     |
| Creative Labs       | 5        | 1.64%   |
| C-Media Electronics | 5        | 1.64%   |
| Texas Instruments   | 3        | 0.99%   |
| Logitech            | 3        | 0.99%   |
| Razer USA           | 2        | 0.66%   |
| JMTek               | 2        | 0.66%   |
| GN Netcom           | 2        | 0.66%   |
| XMOS                | 1        | 0.33%   |
| VIA Technologies    | 1        | 0.33%   |
| Valve Software      | 1        | 0.33%   |
| SteelSeries ApS     | 1        | 0.33%   |
| SAVITECH            | 1        | 0.33%   |
| ROCCAT              | 1        | 0.33%   |
| Numark              | 1        | 0.33%   |
| Micronas            | 1        | 0.33%   |
| Klipsch Audio       | 1        | 0.33%   |
| Kingston Technology | 1        | 0.33%   |
| Insignia (Best Buy) | 1        | 0.33%   |
| iConnectivity       | 1        | 0.33%   |
| GEMBIRD             | 1        | 0.33%   |
| Focusrite-Novation  | 1        | 0.33%   |
| FIFINE Microphones  | 1        | 0.33%   |
| Corsair             | 1        | 0.33%   |
| ASUSTek Computer    | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20       | 5.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 19       | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 5.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17       | 4.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 14       | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 12       | 3.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 2.31%   |
| AMD FCH Azalia Controller                                                         | 8        | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 2.02%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 7        | 2.02%   |
| Nvidia TU116 High Definition Audio Controller                                     | 6        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6        | 1.73%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 1.44%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 1.44%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5        | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 1.44%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.44%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.15%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 1.15%   |
| Intel Comet Lake PCH cAVS                                                         | 4        | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.15%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.86%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 3        | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.86%   |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.58%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.58%   |
| Nvidia Audio device                                                               | 2        | 0.58%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.58%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.58%   |
| Intel Audio device                                                                | 2        | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.58%   |
| GN Netcom Jabra Link 370                                                          | 2        | 0.58%   |
| C-Media Electronics USB Advanced Audio Device                                     | 2        | 0.58%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 2        | 0.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.58%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 2        | 0.58%   |
| AMD Navi 10 HDMI Audio                                                            | 2        | 0.58%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.58%   |
| XMOS Gustard USB Audio 2.0                                                        | 1        | 0.29%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1        | 0.29%   |
| Valve Software Valve VR Radio & HMD Mic                                           | 1        | 0.29%   |
| Texas Instruments PCM2904 Audio Codec                                             | 1        | 0.29%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.29%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 1        | 0.29%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                     | 1        | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 21.74%  |
| Corsair             | 4        | 17.39%  |
| Crucial             | 3        | 13.04%  |
| SK Hynix            | 2        | 8.7%    |
| Samsung Electronics | 2        | 8.7%    |
| Kingston            | 2        | 8.7%    |
| G.Skill             | 2        | 8.7%    |
| Team                | 1        | 4.35%   |
| Ramaxel Technology  | 1        | 4.35%   |
| Micron Technology   | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s  | 1        | 3.85%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 3.85%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 3.85%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s       | 1        | 3.85%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s    | 1        | 3.85%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 1        | 3.85%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 1        | 3.85%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s | 1        | 3.85%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 3.85%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 3.85%   |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 3.85%   |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 2933MT/s   | 1        | 3.85%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s       | 1        | 3.85%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM 1600MT/s         | 1        | 3.85%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 3.85%   |
| Crucial RAM BL8G32C16U4R.M8FE 8GB DIMM DDR4 2133MT/s     | 1        | 3.85%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 1        | 3.85%   |
| Corsair RAM CMK32GX4M4D3600C18 8192MB DIMM DDR4 3600MT/s | 1        | 3.85%   |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 2133MT/s   | 1        | 3.85%   |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 8        | 42.11%  |
| DDR3    | 8        | 42.11%  |
| Unknown | 3        | 15.79%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 19       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 45%     |
| 4096  | 7        | 35%     |
| 2048  | 2        | 10%     |
| 32768 | 1        | 5%      |
| 16384 | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 30%     |
| 2133  | 4        | 20%     |
| 1333  | 3        | 15%     |
| 2667  | 2        | 10%     |
| 3600  | 1        | 5%      |
| 3200  | 1        | 5%      |
| 2933  | 1        | 5%      |
| 2800  | 1        | 5%      |
| 2400  | 1        | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 33.33%  |
| Canon               | 3        | 33.33%  |
| Seiko Epson         | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Brother Industries  | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-202 203 206 Series | 1        | 11.11%  |
| Samsung SCX-3400 Series           | 1        | 11.11%  |
| HP OfficeJet 4650 series          | 1        | 11.11%  |
| HP LaserJet Professional P1102w   | 1        | 11.11%  |
| HP DeskJet 2700 series            | 1        | 11.11%  |
| Canon TR4500 series               | 1        | 11.11%  |
| Canon PIXMA MG2500 Series         | 1        | 11.11%  |
| Canon LiDE 400                    | 1        | 11.11%  |
| Brother DCP-L2540DW               | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| HP ScanJet 2400c     | 1        | 50%     |
| Canon CanoScan 8800F | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 19.23%  |
| Microdia                      | 3        | 11.54%  |
| Generalplus Technology        | 3        | 11.54%  |
| Sunplus Innovation Technology | 2        | 7.69%   |
| Razer USA                     | 2        | 7.69%   |
| Microsoft                     | 2        | 7.69%   |
| webcam vendor                 | 1        | 3.85%   |
| Teslong Camera                | 1        | 3.85%   |
| Sonix Technology              | 1        | 3.85%   |
| Samsung Electronics           | 1        | 3.85%   |
| Jieli Technology              | 1        | 3.85%   |
| Genesys Logic                 | 1        | 3.85%   |
| ARC International             | 1        | 3.85%   |
| Apple                         | 1        | 3.85%   |
| Alcor Micro                   | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Generalplus GENERAL WEBCAM           | 3        | 11.54%  |
| Razer USA Gaming Webcam [Kiyo]       | 2        | 7.69%   |
| Logitech HD Pro Webcam C920          | 2        | 7.69%   |
| webcam vendor webcam product         | 1        | 3.85%   |
| Teslong Camera Teslong Camera        | 1        | 3.85%   |
| Sunplus Integrated_Webcam_HD         | 1        | 3.85%   |
| Sunplus HD 720P webcam               | 1        | 3.85%   |
| Sonix USB 2.0 Camera                 | 1        | 3.85%   |
| Samsung Galaxy A5 (MTP)              | 1        | 3.85%   |
| Microsoft Microsoft?‚ LifeCam Cinema | 1        | 3.85%   |
| Microsoft LifeCam HD-3000            | 1        | 3.85%   |
| Microdia Webcam Vitade AF            | 1        | 3.85%   |
| Microdia PC Camera (SN9C110)         | 1        | 3.85%   |
| Microdia Camera                      | 1        | 3.85%   |
| Logitech Webcam C270                 | 1        | 3.85%   |
| Logitech HD Webcam C910              | 1        | 3.85%   |
| Logitech C922 Pro Stream Webcam      | 1        | 3.85%   |
| Jieli USB PHY 2.0                    | 1        | 3.85%   |
| Genesys Logic Camera                 | 1        | 3.85%   |
| ARC International Camera             | 1        | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE            | 1        | 3.85%   |
| Alcor Micro USB 2.0 PC Camera        | 1        | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |
| Advanced Card Systems ACR39U        | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 138      | 78.41%  |
| 1     | 34       | 19.32%  |
| 2     | 4        | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 17       | 44.74%  |
| Graphics card            | 13       | 34.21%  |
| Unassigned class         | 2        | 5.26%   |
| Chipcard                 | 2        | 5.26%   |
| Storage/ide              | 1        | 2.63%   |
| Sound                    | 1        | 2.63%   |
| Communication controller | 1        | 2.63%   |
| Camera                   | 1        | 2.63%   |

