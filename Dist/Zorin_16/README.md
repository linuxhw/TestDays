Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A55M-HD+                 | Desktop     | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | Notebook    | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | Notebook    | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| eMachines     | EL1850G                     | Desktop     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | Notebook    | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | Desktop     | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | Desktop     | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d998d59215](https://linux-hardware.org/?probe=d998d59215) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [0981774043](https://linux-hardware.org/?probe=0981774043) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | Notebook    | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | Notebook    | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [451f363726](https://linux-hardware.org/?probe=451f363726) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | Desktop     | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ef7d0f49e1](https://linux-hardware.org/?probe=ef7d0f49e1) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | Desktop     | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | Notebook    | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | Desktop     | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| Acer          | Spin SP513-55N              | Convertible | [8c3b4736cd](https://linux-hardware.org/?probe=8c3b4736cd) | Oct 27, 2021 |
| ASUSTek       | X750JB                      | Notebook    | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [f7e2ea06ad](https://linux-hardware.org/?probe=f7e2ea06ad) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | Notebook    | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [23d7c3ed4a](https://linux-hardware.org/?probe=23d7c3ed4a) | Oct 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [17f5a136fa](https://linux-hardware.org/?probe=17f5a136fa) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | Desktop     | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [fdb4d4b838](https://linux-hardware.org/?probe=fdb4d4b838) | Oct 25, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [cd7c995e3f](https://linux-hardware.org/?probe=cd7c995e3f) | Oct 25, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| MSI           | 2AE0                        | Desktop     | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| Schenker      | VIA 15 Pro                  | Notebook    | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | Notebook    | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | Notebook    | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | Notebook    | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [693d2a5966](https://linux-hardware.org/?probe=693d2a5966) | Oct 24, 2021 |
| Dell          | Latitude D630               | Notebook    | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | Latitude E6410              | Notebook    | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | Notebook    | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| HP            | Notebook                    | Notebook    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | Desktop     | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | Desktop     | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| Google        | Kindred                     | Notebook    | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | 1589                        | Desktop     | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | Notebook    | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | Notebook    | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| Dell          | Latitude E7470              | Notebook    | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Quanta        | XV1                         | All in one  | [c421f15879](https://linux-hardware.org/?probe=c421f15879) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| HP            | 2B38                        | Desktop     | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fa1ceccee5](https://linux-hardware.org/?probe=fa1ceccee5) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90a3d77b31](https://linux-hardware.org/?probe=90a3d77b31) | Oct 17, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | Notebook    | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| ASUSTek       | P6T                         | Desktop     | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | Notebook    | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | Notebook    | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | Notebook    | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | Notebook    | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| HP            | 15                          | Notebook    | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | Notebook    | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [95f8cd653d](https://linux-hardware.org/?probe=95f8cd653d) | Oct 12, 2021 |
| HP            | Notebook                    | Notebook    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | Notebook    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | Desktop     | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [6265908eb4](https://linux-hardware.org/?probe=6265908eb4) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | Notebook    | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Biostar       | G41-M7                      | Desktop     | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | Notebook    | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | Notebook    | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [af0bf465e5](https://linux-hardware.org/?probe=af0bf465e5) | Oct 09, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | Desktop     | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | Desktop     | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | Notebook    | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | Notebook    | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| HP            | ENVY dv6                    | Notebook    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | Desktop     | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | Notebook    | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | Desktop     | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| HP            | 8591                        | Desktop     | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Star Labs     | LabTop                      | Notebook    | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [a392dd59eb](https://linux-hardware.org/?probe=a392dd59eb) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | Notebook    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | Notebook    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | Notebook    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | Notebook    | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| HP            | Pavilion dv7                | Notebook    | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | Notebook    | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | Notebook    | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | Notebook    | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [d68bf2f2b0](https://linux-hardware.org/?probe=d68bf2f2b0) | Oct 01, 2021 |
| Dell          | Latitude E6520              | Notebook    | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | Desktop     | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | Desktop     | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | Desktop     | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | Desktop     | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [401d1460e9](https://linux-hardware.org/?probe=401d1460e9) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [8f7adb6cd3](https://linux-hardware.org/?probe=8f7adb6cd3) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [9e3d0f86c2](https://linux-hardware.org/?probe=9e3d0f86c2) | Sep 28, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [1d15930339](https://linux-hardware.org/?probe=1d15930339) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | 0TNXNR A01                  | Desktop     | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [aefac2fb50](https://linux-hardware.org/?probe=aefac2fb50) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [e0e687f0f9](https://linux-hardware.org/?probe=e0e687f0f9) | Sep 27, 2021 |
| MSI           | MS-B1061                    | All in one  | [1bc488324f](https://linux-hardware.org/?probe=1bc488324f) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| Dell          | 0TP406                      | Desktop     | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| HP            | 18E7                        | Desktop     | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | Notebook    | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | Desktop     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| HP            | 8245 001                    | All in one  | [8ea38831d5](https://linux-hardware.org/?probe=8ea38831d5) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | Notebook    | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | Desktop     | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | Notebook    | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | Notebook    | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | Notebook    | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| HP            | 18E7                        | Desktop     | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [74fe90715f](https://linux-hardware.org/?probe=74fe90715f) | Sep 22, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | Notebook    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | 213D A01                    | Desktop     | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c514cd3934](https://linux-hardware.org/?probe=c514cd3934) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [fdb65b8597](https://linux-hardware.org/?probe=fdb65b8597) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [46d07193b2](https://linux-hardware.org/?probe=46d07193b2) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | Notebook    | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [97926688ff](https://linux-hardware.org/?probe=97926688ff) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [c294748851](https://linux-hardware.org/?probe=c294748851) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [39f083f836](https://linux-hardware.org/?probe=39f083f836) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [59eb49e544](https://linux-hardware.org/?probe=59eb49e544) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | Notebook    | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | Desktop     | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| TianBei       | TB-H7                       | Notebook    | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | Desktop     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | Notebook    | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | Notebook    | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | XPS L321X                   | Notebook    | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b3a1acb0f6](https://linux-hardware.org/?probe=b3a1acb0f6) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b7fe3ed969](https://linux-hardware.org/?probe=b7fe3ed969) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | Notebook    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | Notebook    | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | Notebook    | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | Notebook    | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| Acer          | One S1003                   | Tablet      | [e021ddcbf1](https://linux-hardware.org/?probe=e021ddcbf1) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| Intel         | X99                         | Desktop     | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| NCR           | Talladega                   | Desktop     | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [68ad9fb8e9](https://linux-hardware.org/?probe=68ad9fb8e9) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| Dell          | Latitude E5470              | Notebook    | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | Notebook    | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Acer          | One S1003                   | Tablet      | [a049a2a4d3](https://linux-hardware.org/?probe=a049a2a4d3) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | Notebook    | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| HP            | 339A                        | Desktop     | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| Dell          | Latitude E6430              | Notebook    | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | Notebook    | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | Notebook    | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | Notebook    | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | Desktop     | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | XPS M1330                   | Notebook    | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | Notebook    | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | Notebook    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [15f063a517](https://linux-hardware.org/?probe=15f063a517) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5b8b652e27](https://linux-hardware.org/?probe=5b8b652e27) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e3e702ab7b](https://linux-hardware.org/?probe=e3e702ab7b) | Sep 09, 2021 |
| HP            | 2187 A01                    | Desktop     | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | Notebook    | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | Notebook    | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| RCA           | W101-CS                     | Tablet      | [7ba24072d5](https://linux-hardware.org/?probe=7ba24072d5) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Acer          | V5-171                      | Notebook    | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | Notebook    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | Notebook    | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | Notebook    | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | Notebook    | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| HP            | Pavilion dv5                | Notebook    | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | Notebook    | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [879a8ee9da](https://linux-hardware.org/?probe=879a8ee9da) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [e5d901c7a5](https://linux-hardware.org/?probe=e5d901c7a5) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [ff8f35986b](https://linux-hardware.org/?probe=ff8f35986b) | Sep 04, 2021 |
| MSI           | IONA                        | Desktop     | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| HP            | 2B4B                        | Desktop     | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | Desktop     | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| ASUSTek       | GR8                         | Notebook    | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3c88709f8a](https://linux-hardware.org/?probe=3c88709f8a) | Sep 01, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | Notebook    | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c59a1fff0d](https://linux-hardware.org/?probe=c59a1fff0d) | Aug 26, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [accc3b9ebb](https://linux-hardware.org/?probe=accc3b9ebb) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Acer          | AO722                       | Notebook    | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| TianBei       | TB-H7                       | Notebook    | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | Desktop     | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | Notebook    | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| Acer          | Aspire 8940G                | Notebook    | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | Notebook    | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8eed93b589](https://linux-hardware.org/?probe=8eed93b589) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Board                       | Desktop     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Board                       | Desktop     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | Notebook    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | Notebook    | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | Notebook    | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | Notebook    | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell          | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP            | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta        | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta        | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron      | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 149       | 28.33%  |
| 5.11.0-37-generic | 109       | 20.72%  |
| 5.11.0-34-generic | 94        | 17.87%  |
| 5.11.0-38-generic | 66        | 12.55%  |
| 5.11.0-36-generic | 39        | 7.41%   |
| 5.11.0-25-generic | 14        | 2.66%   |
| 5.8.0-53-generic  | 13        | 2.47%   |
| 5.8.0-50-generic  | 12        | 2.28%   |
| 5.8.0-55-generic  | 10        | 1.9%    |
| 5.8.0-59-generic  | 8         | 1.52%   |
| 5.8.0-63-generic  | 4         | 0.76%   |
| 5.8.0-49-generic  | 4         | 0.76%   |
| 5.8.0-45-generic  | 1         | 0.19%   |
| 5.4.0-42-generic  | 1         | 0.19%   |
| 5.13.18-xanmod1   | 1         | 0.19%   |
| 5.10.0-1044-oem   | 1         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 449       | 89.26%  |
| 5.8.0   | 51        | 10.14%  |
| 5.4.0   | 1         | 0.2%    |
| 5.13.18 | 1         | 0.2%    |
| 5.10.0  | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 449       | 89.26%  |
| 5.8     | 51        | 10.14%  |
| 5.4     | 1         | 0.2%    |
| 5.13    | 1         | 0.2%    |
| 5.10    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 496       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 486       | 97.59%  |
| Unknown  | 6         | 1.2%    |
| XFCE     | 3         | 0.6%    |
| MATE     | 1         | 0.2%    |
| Cinnamon | 1         | 0.2%    |
| Budgie   | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 490       | 98.59%  |
| Wayland | 5         | 1.01%   |
| Unknown | 2         | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 442       | 88.76%  |
| GDM     | 40        | 8.03%   |
| GDM3    | 15        | 3.01%   |
| TDM     | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 194       | 39.11%  |
| de_DE | 52        | 10.48%  |
| en_GB | 45        | 9.07%   |
| pt_BR | 28        | 5.65%   |
| en_IN | 20        | 4.03%   |
| es_ES | 16        | 3.23%   |
| en_CA | 14        | 2.82%   |
| es_MX | 12        | 2.42%   |
| it_IT | 10        | 2.02%   |
| nl_NL | 9         | 1.81%   |
| fr_FR | 9         | 1.81%   |
| en_AU | 9         | 1.81%   |
| pl_PL | 7         | 1.41%   |
| es_CL | 7         | 1.41%   |
| ru_RU | 6         | 1.21%   |
| en_ZA | 6         | 1.21%   |
| pt_PT | 5         | 1.01%   |
| cs_CZ | 5         | 1.01%   |
| sv_SE | 4         | 0.81%   |
| en_NZ | 4         | 0.81%   |
| hu_HU | 3         | 0.6%    |
| de_CH | 3         | 0.6%    |
| nl_BE | 2         | 0.4%    |
| fr_CA | 2         | 0.4%    |
| es_PE | 2         | 0.4%    |
| es_CO | 2         | 0.4%    |
| en_SG | 2         | 0.4%    |
| C     | 2         | 0.4%    |
| bg_BG | 2         | 0.4%    |
| zh_TW | 1         | 0.2%    |
| zh_CN | 1         | 0.2%    |
| tr_TR | 1         | 0.2%    |
| sk_SK | 1         | 0.2%    |
| ru_UA | 1         | 0.2%    |
| ja_JP | 1         | 0.2%    |
| fr_CH | 1         | 0.2%    |
| fr_BE | 1         | 0.2%    |
| fi_FI | 1         | 0.2%    |
| es_PA | 1         | 0.2%    |
| es_GT | 1         | 0.2%    |
| es_AR | 1         | 0.2%    |
| en_PH | 1         | 0.2%    |
| de_AT | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 306       | 61.32%  |
| BIOS | 193       | 38.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 462       | 93.15%  |
| Zfs     | 11        | 2.22%   |
| Overlay | 8         | 1.61%   |
| Btrfs   | 8         | 1.61%   |
| Ext3    | 3         | 0.6%    |
| Xfs     | 2         | 0.4%    |
| Ext2    | 2         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 452       | 90.76%  |
| GPT     | 43        | 8.63%   |
| MBR     | 3         | 0.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 487       | 97.79%  |
| Yes       | 11        | 2.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 446       | 89.56%  |
| Yes       | 52        | 10.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 84        | 16.94%  |
| Hewlett-Packard             | 74        | 14.92%  |
| Dell                        | 72        | 14.52%  |
| Lenovo                      | 69        | 13.91%  |
| Acer                        | 38        | 7.66%   |
| Gigabyte Technology         | 30        | 6.05%   |
| MSI                         | 22        | 4.44%   |
| Apple                       | 17        | 3.43%   |
| ASRock                      | 15        | 3.02%   |
| Toshiba                     | 13        | 2.62%   |
| Intel                       | 10        | 2.02%   |
| Unknown                     | 8         | 1.61%   |
| LG Electronics              | 4         | 0.81%   |
| Fujitsu                     | 4         | 0.81%   |
| Biostar                     | 4         | 0.81%   |
| Sony                        | 3         | 0.6%    |
| Samsung Electronics         | 3         | 0.6%    |
| Notebook                    | 2         | 0.4%    |
| UNOWHY                      | 1         | 0.2%    |
| TianBei                     | 1         | 0.2%    |
| Thomson                     | 1         | 0.2%    |
| Star Labs                   | 1         | 0.2%    |
| Schenker                    | 1         | 0.2%    |
| Sapphire Technology Limited | 1         | 0.2%    |
| RCA                         | 1         | 0.2%    |
| Razer                       | 1         | 0.2%    |
| Quanta                      | 1         | 0.2%    |
| Positivo                    | 1         | 0.2%    |
| Pegatron                    | 1         | 0.2%    |
| Packard Bell                | 1         | 0.2%    |
| NCR                         | 1         | 0.2%    |
| MECER                       | 1         | 0.2%    |
| KOGAN                       | 1         | 0.2%    |
| Jumper                      | 1         | 0.2%    |
| Insyde                      | 1         | 0.2%    |
| Google                      | 1         | 0.2%    |
| Giani Limited               | 1         | 0.2%    |
| Foxconn                     | 1         | 0.2%    |
| eMachines                   | 1         | 0.2%    |
| Dynabook                    | 1         | 0.2%    |
| Cube                        | 1         | 0.2%    |
| Alienware                   | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 10        | 2.02%   |
| ASUS All Series                                       | 6         | 1.21%   |
| HP Notebook                                           | 4         | 0.81%   |
| Dell OptiPlex 990                                     | 4         | 0.81%   |
| Gigabyte A320M-S2H                                    | 3         | 0.6%    |
| MSI MS-7817                                           | 2         | 0.4%    |
| Lenovo Yoga 3 Pro-1370 80HE                           | 2         | 0.4%    |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.4%    |
| Lenovo IdeaPad 3 15IIL05 81WE                         | 2         | 0.4%    |
| Intel DQ77MK-R01                                      | 2         | 0.4%    |
| HP Pavilion Notebook                                  | 2         | 0.4%    |
| HP ENVY Sleekbook 4 PC                                | 2         | 0.4%    |
| HP EliteBook 840 G1                                   | 2         | 0.4%    |
| HP 15                                                 | 2         | 0.4%    |
| Gigabyte 970A-DS3P                                    | 2         | 0.4%    |
| Dell XPS420                                           | 2         | 0.4%    |
| Dell OptiPlex 790                                     | 2         | 0.4%    |
| Dell Latitude E7470                                   | 2         | 0.4%    |
| Dell Latitude E7440                                   | 2         | 0.4%    |
| Dell Latitude E6520                                   | 2         | 0.4%    |
| Dell Latitude E6430                                   | 2         | 0.4%    |
| Dell Latitude E6420                                   | 2         | 0.4%    |
| Dell Inspiron 5566                                    | 2         | 0.4%    |
| Dell Inspiron 3542                                    | 2         | 0.4%    |
| Dell Inspiron 15 7000 Gaming                          | 2         | 0.4%    |
| ASUS X405UA                                           | 2         | 0.4%    |
| ASUS PRIME B450M-GAMING/BR                            | 2         | 0.4%    |
| ASUS M5A97 LE R2.0                                    | 2         | 0.4%    |
| ASUS M5A78L-M/USB3                                    | 2         | 0.4%    |
| Apple iMac12,2                                        | 2         | 0.4%    |
| Acer One S1003                                        | 2         | 0.4%    |
| Acer Aspire V3-571G                                   | 2         | 0.4%    |
| Acer Aspire ES1-512                                   | 2         | 0.4%    |
| UNOWHY Y13G011S4EI                                    | 1         | 0.2%    |
| Toshiba Satellite S75Dt-A                             | 1         | 0.2%    |
| Toshiba Satellite Pro T110                            | 1         | 0.2%    |
| Toshiba Satellite Pro L450D                           | 1         | 0.2%    |
| Toshiba Satellite L755                                | 1         | 0.2%    |
| Toshiba Satellite L455D                               | 1         | 0.2%    |
| Toshiba Satellite C870-1C2                            | 1         | 0.2%    |
| Toshiba Satellite C850D-11C                           | 1         | 0.2%    |
| Toshiba Satellite C850-1CP                            | 1         | 0.2%    |
| Toshiba Satellite C75D-B                              | 1         | 0.2%    |
| Toshiba Satellite C70-B                               | 1         | 0.2%    |
| Toshiba PORTEGE Z30-A                                 | 1         | 0.2%    |
| Toshiba PORTEGE Z20t-C                                | 1         | 0.2%    |
| Toshiba PORTEGE R700                                  | 1         | 0.2%    |
| TianBei TB-H7                                         | 1         | 0.2%    |
| Thomson N17C512                                       | 1         | 0.2%    |
| Star Labs LabTop                                      | 1         | 0.2%    |
| Sony VPCS135FX                                        | 1         | 0.2%    |
| Sony VPCF215FX                                        | 1         | 0.2%    |
| Sony VGN-SR5                                          | 1         | 0.2%    |
| Schenker VIA 15 Pro                                   | 1         | 0.2%    |
| Sapphire Limited PURE PLATINUM 970A-PLUS              | 1         | 0.2%    |
| Samsung 700Z3C/700Z5C                                 | 1         | 0.2%    |
| Samsung 550P5C/550P7C                                 | 1         | 0.2%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.2%    |
| RCA W101-CS                                           | 1         | 0.2%    |
| Razer Book 13 - RZ09-0357                             | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 27        | 5.44%   |
| Dell Latitude          | 21        | 4.23%   |
| Dell Inspiron          | 19        | 3.83%   |
| Lenovo IdeaPad         | 18        | 3.63%   |
| Lenovo ThinkPad        | 17        | 3.43%   |
| HP Pavilion            | 13        | 2.62%   |
| Dell OptiPlex          | 11        | 2.22%   |
| Toshiba Satellite      | 10        | 2.02%   |
| Unknown                | 10        | 2.02%   |
| Dell XPS               | 9         | 1.81%   |
| HP ENVY                | 8         | 1.61%   |
| HP EliteBook           | 8         | 1.61%   |
| ASUS PRIME             | 8         | 1.61%   |
| Lenovo Yoga            | 7         | 1.41%   |
| HP ProBook             | 7         | 1.41%   |
| ASUS ROG               | 7         | 1.41%   |
| Lenovo ThinkCentre     | 6         | 1.21%   |
| ASUS VivoBook          | 6         | 1.21%   |
| ASUS All               | 6         | 1.21%   |
| Dell Precision         | 5         | 1.01%   |
| HP Notebook            | 4         | 0.81%   |
| HP Laptop              | 4         | 0.81%   |
| HP Compaq              | 4         | 0.81%   |
| HP 255                 | 4         | 0.81%   |
| ASUS M5A97             | 4         | 0.81%   |
| Toshiba PORTEGE        | 3         | 0.6%    |
| Gigabyte A320M-S2H     | 3         | 0.6%    |
| Dell Vostro            | 3         | 0.6%    |
| ASUS TUF               | 3         | 0.6%    |
| ASUS P8H61-M           | 3         | 0.6%    |
| ASUS M5A78L-M          | 3         | 0.6%    |
| Apple MacBookPro11     | 3         | 0.6%    |
| Acer Swift             | 3         | 0.6%    |
| MSI MS-7817            | 2         | 0.4%    |
| MSI Modern             | 2         | 0.4%    |
| Lenovo MIIX            | 2         | 0.4%    |
| Lenovo Legion          | 2         | 0.4%    |
| Lenovo IdeaCentre      | 2         | 0.4%    |
| Intel DQ77MK-R01       | 2         | 0.4%    |
| HP t620                | 2         | 0.4%    |
| HP Stream              | 2         | 0.4%    |
| HP 15                  | 2         | 0.4%    |
| Gigabyte X570          | 2         | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 2         | 0.4%    |
| Gigabyte B550M         | 2         | 0.4%    |
| Gigabyte B450          | 2         | 0.4%    |
| Gigabyte 970A-DS3P     | 2         | 0.4%    |
| Fujitsu LIFEBOOK       | 2         | 0.4%    |
| Dell XPS420            | 2         | 0.4%    |
| ASUS ZenBook           | 2         | 0.4%    |
| ASUS X405UA            | 2         | 0.4%    |
| ASUS P8Z77-V           | 2         | 0.4%    |
| ASUS P5K               | 2         | 0.4%    |
| ASUS ASUS              | 2         | 0.4%    |
| ASRock B450            | 2         | 0.4%    |
| Apple iMac12           | 2         | 0.4%    |
| Acer One               | 2         | 0.4%    |
| Acer Nitro             | 2         | 0.4%    |
| UNOWHY Y13G011S4EI     | 1         | 0.2%    |
| TianBei TB-H7          | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 85        | 17.14%  |
| 2020 | 76        | 15.32%  |
| 2018 | 49        | 9.88%   |
| 2019 | 42        | 8.47%   |
| 2014 | 35        | 7.06%   |
| 2015 | 31        | 6.25%   |
| 2012 | 30        | 6.05%   |
| 2011 | 30        | 6.05%   |
| 2013 | 28        | 5.65%   |
| 2016 | 21        | 4.23%   |
| 2017 | 19        | 3.83%   |
| 2010 | 18        | 3.63%   |
| 2009 | 13        | 2.62%   |
| 2008 | 12        | 2.42%   |
| 2007 | 5         | 1.01%   |
| 2006 | 2         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 287       | 57.86%  |
| Desktop     | 174       | 35.08%  |
| All in one  | 13        | 2.62%   |
| Convertible | 10        | 2.02%   |
| Tablet      | 5         | 1.01%   |
| Mini pc     | 5         | 1.01%   |
| Server      | 2         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 430       | 86.17%  |
| Enabled  | 69        | 13.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 494       | 99.6%   |
| Yes  | 2         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 143       | 28.6%   |
| 8.01-16.0   | 103       | 20.6%   |
| 3.01-4.0    | 102       | 20.4%   |
| 16.01-24.0  | 79        | 15.8%   |
| 32.01-64.0  | 41        | 8.2%    |
| 1.01-2.0    | 18        | 3.6%    |
| 64.01-256.0 | 7         | 1.4%    |
| 24.01-32.0  | 5         | 1%      |
| 2.01-3.0    | 2         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 225       | 43.19%  |
| 2.01-3.0   | 169       | 32.44%  |
| 3.01-4.0   | 68        | 13.05%  |
| 4.01-8.0   | 47        | 9.02%   |
| 0.51-1.0   | 7         | 1.34%   |
| 8.01-16.0  | 3         | 0.58%   |
| 24.01-32.0 | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 305       | 61%     |
| 2      | 127       | 25.4%   |
| 3      | 32        | 6.4%    |
| 4      | 17        | 3.4%    |
| 5      | 11        | 2.2%    |
| 6      | 4         | 0.8%    |
| 8      | 3         | 0.6%    |
| 0      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 279       | 55.91%  |
| Yes       | 220       | 44.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 436       | 87.73%  |
| No        | 61        | 12.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 392       | 79.03%  |
| No        | 104       | 20.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 61.12%  |
| No        | 194       | 38.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 113       | 22.78%  |
| Germany      | 60        | 12.1%   |
| UK           | 38        | 7.66%   |
| Brazil       | 35        | 7.06%   |
| India        | 21        | 4.23%   |
| Spain        | 17        | 3.43%   |
| Canada       | 17        | 3.43%   |
| Mexico       | 14        | 2.82%   |
| Netherlands  | 13        | 2.62%   |
| Italy        | 13        | 2.62%   |
| Australia    | 11        | 2.22%   |
| France       | 10        | 2.02%   |
| South Africa | 9         | 1.81%   |
| Chile        | 8         | 1.61%   |
| Hungary      | 7         | 1.41%   |
| Switzerland  | 6         | 1.21%   |
| Sweden       | 6         | 1.21%   |
| Poland       | 6         | 1.21%   |
| Austria      | 6         | 1.21%   |
| Czechia      | 5         | 1.01%   |
| Russia       | 4         | 0.81%   |
| New Zealand  | 4         | 0.81%   |
| Belgium      | 4         | 0.81%   |
| Turkey       | 3         | 0.6%    |
| Romania      | 3         | 0.6%    |
| Norway       | 3         | 0.6%    |
| Malaysia     | 3         | 0.6%    |
| Japan        | 3         | 0.6%    |
| Denmark      | 3         | 0.6%    |
| Colombia     | 3         | 0.6%    |
| Argentina    | 3         | 0.6%    |
| Thailand     | 2         | 0.4%    |
| Taiwan       | 2         | 0.4%    |
| Portugal     | 2         | 0.4%    |
| Philippines  | 2         | 0.4%    |
| Morocco      | 2         | 0.4%    |
| Indonesia    | 2         | 0.4%    |
| Greece       | 2         | 0.4%    |
| El Salvador  | 2         | 0.4%    |
| Bulgaria     | 2         | 0.4%    |
| Vietnam      | 1         | 0.2%    |
| Venezuela    | 1         | 0.2%    |
| Ukraine      | 1         | 0.2%    |
| Tanzania     | 1         | 0.2%    |
| Slovakia     | 1         | 0.2%    |
| Singapore    | 1         | 0.2%    |
| Serbia       | 1         | 0.2%    |
| Qatar        | 1         | 0.2%    |
| Peru         | 1         | 0.2%    |
| Panama       | 1         | 0.2%    |
| Nigeria      | 1         | 0.2%    |
| Nepal        | 1         | 0.2%    |
| Mozambique   | 1         | 0.2%    |
| Madagascar   | 1         | 0.2%    |
| Kenya        | 1         | 0.2%    |
| Jersey       | 1         | 0.2%    |
| Jamaica      | 1         | 0.2%    |
| Israel       | 1         | 0.2%    |
| Ireland      | 1         | 0.2%    |
| Guatemala    | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vienna            | 5         | 1%      |
| Rome              | 5         | 1%      |
| Berlin            | 5         | 1%      |
| Santiago          | 4         | 0.8%    |
| Munich            | 4         | 0.8%    |
| London            | 4         | 0.8%    |
| Johannesburg      | 4         | 0.8%    |
| S??o Lu?­s        | 3         | 0.6%    |
| San Francisco     | 3         | 0.6%    |
| Rio de Janeiro    | 3         | 0.6%    |
| Paris             | 3         | 0.6%    |
| Milan             | 3         | 0.6%    |
| Hyderabad         | 3         | 0.6%    |
| Hamburg           | 3         | 0.6%    |
| Glasgow           | 3         | 0.6%    |
| Athens            | 3         | 0.6%    |
| Zurich            | 2         | 0.4%    |
| Vancouver         | 2         | 0.4%    |
| Vadodara          | 2         | 0.4%    |
| Taboao da Serra   | 2         | 0.4%    |
| Sydney            | 2         | 0.4%    |
| Stuttgart         | 2         | 0.4%    |
| Stockholm         | 2         | 0.4%    |
| S??o Paulo        | 2         | 0.4%    |
| Rochester         | 2         | 0.4%    |
| Perth             | 2         | 0.4%    |
| Oslo              | 2         | 0.4%    |
| Moscow            | 2         | 0.4%    |
| Mooresville       | 2         | 0.4%    |
| Montreal          | 2         | 0.4%    |
| Miami             | 2         | 0.4%    |
| Mentor            | 2         | 0.4%    |
| Melbourne         | 2         | 0.4%    |
| Madrid            | 2         | 0.4%    |
| Maca?©            | 2         | 0.4%    |
| Livingston        | 2         | 0.4%    |
| Kuala Lumpur      | 2         | 0.4%    |
| Kolkata           | 2         | 0.4%    |
| Kaiserslautern    | 2         | 0.4%    |
| Independence      | 2         | 0.4%    |
| Frankfurt am Main | 2         | 0.4%    |
| Ernakulam         | 2         | 0.4%    |
| Dunedin           | 2         | 0.4%    |
| Drummondville     | 2         | 0.4%    |
| Dortmund          | 2         | 0.4%    |
| Dallas            | 2         | 0.4%    |
| Contagem          | 2         | 0.4%    |
| Chicago           | 2         | 0.4%    |
| Chennai           | 2         | 0.4%    |
| Charlotte         | 2         | 0.4%    |
| Budapest          | 2         | 0.4%    |
| Brisbane          | 2         | 0.4%    |
| Bengaluru         | 2         | 0.4%    |
| Barcelona         | 2         | 0.4%    |
| Auckland          | 2         | 0.4%    |
| Amsterdam         | 2         | 0.4%    |
| Alexandria        | 2         | 0.4%    |
| Ahmedabad         | 2         | 0.4%    |
| Zionsville        | 1         | 0.2%    |
| Zephyrhills       | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 116       | 159    | 16.32%  |
| Seagate                        | 112       | 150    | 15.75%  |
| WDC                            | 89        | 106    | 12.52%  |
| Toshiba                        | 53        | 56     | 7.45%   |
| SanDisk                        | 46        | 57     | 6.47%   |
| Unknown                        | 36        | 49     | 5.06%   |
| Kingston                       | 32        | 41     | 4.5%    |
| Hitachi                        | 29        | 34     | 4.08%   |
| Crucial                        | 23        | 28     | 3.23%   |
| HGST                           | 14        | 18     | 1.97%   |
| SK Hynix                       | 13        | 18     | 1.83%   |
| A-DATA Technology              | 13        | 15     | 1.83%   |
| Phison                         | 11        | 12     | 1.55%   |
| Intel                          | 10        | 14     | 1.41%   |
| Micron Technology              | 9         | 10     | 1.27%   |
| Apple                          | 9         | 10     | 1.27%   |
| Intenso                        | 6         | 6      | 0.84%   |
| Silicon Motion                 | 5         | 9      | 0.7%    |
| JMicron                        | 5         | 7      | 0.7%    |
| SPCC                           | 4         | 5      | 0.56%   |
| LITEONIT                       | 4         | 5      | 0.56%   |
| KIOXIA                         | 4         | 4      | 0.56%   |
| China                          | 4         | 5      | 0.56%   |
| SABRENT                        | 3         | 3      | 0.42%   |
| PNY                            | 3         | 4      | 0.42%   |
| Micron/Crucial Technology      | 3         | 3      | 0.42%   |
| MAXTOR                         | 3         | 3      | 0.42%   |
| Lexar                          | 3         | 3      | 0.42%   |
| Hewlett-Packard                | 3         | 4      | 0.42%   |
| Fujitsu                        | 3         | 4      | 0.42%   |
| XPG                            | 2         | 2      | 0.28%   |
| Verbatim                       | 2         | 2      | 0.28%   |
| Team                           | 2         | 3      | 0.28%   |
| Super Talent                   | 2         | 2      | 0.28%   |
| Patriot                        | 2         | 2      | 0.28%   |
| OCZ                            | 2         | 2      | 0.28%   |
| Netac                          | 2         | 2      | 0.28%   |
| Lite-On                        | 2         | 3      | 0.28%   |
| KingSpec                       | 2         | 3      | 0.28%   |
| GOODRAM                        | 2         | 2      | 0.28%   |
| Gigabyte Technology            | 2         | 2      | 0.28%   |
| Unknown                        | 2         | 2      | 0.28%   |
| Vaseky                         | 1         | 2      | 0.14%   |
| USB30                          | 1         | 3      | 0.14%   |
| Transcend                      | 1         | 1      | 0.14%   |
| T-FORCE                        | 1         | 1      | 0.14%   |
| SuperSSpeed                    | 1         | 2      | 0.14%   |
| Star                           | 1         | 1      | 0.14%   |
| Solid State Storage Technology | 1         | 1      | 0.14%   |
| Smartbuy                       | 1         | 1      | 0.14%   |
| Realtek Semiconductor          | 1         | 1      | 0.14%   |
| OWC                            | 1         | 1      | 0.14%   |
| MyDigitalSSD                   | 1         | 1      | 0.14%   |
| Mushkin                        | 1         | 1      | 0.14%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.14%   |
| KingFast                       | 1         | 1      | 0.14%   |
| INNOVATION IT                  | 1         | 1      | 0.14%   |
| E535N                          | 1         | 1      | 0.14%   |
| Config                         | 1         | 1      | 0.14%   |
| BUFFALO                        | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 13        | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 11        | 1.38%   |
| Samsung SSD 860 EVO 500GB              | 11        | 1.38%   |
| Unknown MMC Card  64GB                 | 9         | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB         | 9         | 1.13%   |
| Samsung NVMe SSD Drive 500GB           | 9         | 1.13%   |
| Samsung NVMe SSD Drive 256GB           | 9         | 1.13%   |
| Samsung PM963 2.5" NVMe PCIe SSD 512GB | 8         | 1.01%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 1.01%   |
| Unknown SD/MMC/MS PRO 128GB            | 7         | 0.88%   |
| Seagate ST500DM002-1BD142 500GB        | 7         | 0.88%   |
| Samsung SSD 850 EVO 500GB              | 7         | 0.88%   |
| Toshiba MQ01ABF050 500GB               | 6         | 0.75%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.75%   |
| Samsung SSD 840 EVO 250GB              | 6         | 0.75%   |
| Samsung NVMe SSD Drive 1TB             | 6         | 0.75%   |
| Crucial CT240BX500SSD1 240GB           | 6         | 0.75%   |
| Seagate ST2000DM001-9YN164 2TB         | 5         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 5         | 0.63%   |
| Samsung SSD 860 EVO 1TB                | 5         | 0.63%   |
| Samsung SSD 850 EVO 250GB              | 5         | 0.63%   |
| Phison NVMe SSD Drive 1TB              | 5         | 0.63%   |
| Kingston SV300S37A120G 120GB SSD       | 5         | 0.63%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 0.63%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4         | 0.5%    |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.5%    |
| Toshiba HDWD110 1TB                    | 4         | 0.5%    |
| SK Hynix NVMe SSD Drive 256GB          | 4         | 0.5%    |
| Seagate ST9500325AS 500GB              | 4         | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB    | 4         | 0.5%    |
| Sandisk NVMe SSD Drive 512GB           | 4         | 0.5%    |
| Sandisk NVMe SSD Drive 256GB           | 4         | 0.5%    |
| Samsung SSD 870 QVO 1TB                | 4         | 0.5%    |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.5%    |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 3         | 0.38%   |
| WDC WD1600AAJS-75M0A0 160GB            | 3         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.38%   |
| WDC WD10EZEX-60WN4A0 1TB               | 3         | 0.38%   |
| WDC WD10EZEX-60M2NA0 1TB               | 3         | 0.38%   |
| Unknown MMC Card  128GB                | 3         | 0.38%   |
| Toshiba MK2555GSX 250GB                | 3         | 0.38%   |
| Toshiba DT01ACA200 2TB                 | 3         | 0.38%   |
| Seagate ST3500418AS 500GB              | 3         | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB         | 3         | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB         | 3         | 0.38%   |
| SanDisk SSD PLUS 240GB                 | 3         | 0.38%   |
| SanDisk SSD PLUS 1000GB                | 3         | 0.38%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.38%   |
| Sandisk NVMe SSD Drive 1TB             | 3         | 0.38%   |
| Samsung SSD 870 EVO 1TB                | 3         | 0.38%   |
| Samsung HD103UJ 1TB                    | 3         | 0.38%   |
| SABRENT Disk 320GB                     | 3         | 0.38%   |
| Phison NVMe SSD Drive 512GB            | 3         | 0.38%   |
| Micron NVMe SSD Drive 512GB            | 3         | 0.38%   |
| JMicron Tech 250GB                     | 3         | 0.38%   |
| Intel NVMe SSD Drive 512GB             | 3         | 0.38%   |
| Intel NVMe SSD Drive 1024GB            | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 111       | 146    | 35.92%  |
| WDC                 | 77        | 91     | 24.92%  |
| Toshiba             | 43        | 46     | 13.92%  |
| Hitachi             | 29        | 34     | 9.39%   |
| HGST                | 14        | 18     | 4.53%   |
| Samsung Electronics | 11        | 16     | 3.56%   |
| Unknown             | 7         | 9      | 2.27%   |
| Apple               | 4         | 4      | 1.29%   |
| SABRENT             | 3         | 3      | 0.97%   |
| MAXTOR              | 3         | 3      | 0.97%   |
| Fujitsu             | 3         | 4      | 0.97%   |
| Hewlett-Packard     | 2         | 3      | 0.65%   |
| JMicron             | 1         | 2      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 84     | 28.17%  |
| SanDisk             | 30        | 39     | 11.9%   |
| Kingston            | 29        | 37     | 11.51%  |
| Crucial             | 22        | 27     | 8.73%   |
| A-DATA Technology   | 11        | 13     | 4.37%   |
| WDC                 | 10        | 10     | 3.97%   |
| SK Hynix            | 6         | 6      | 2.38%   |
| Toshiba             | 5         | 5      | 1.98%   |
| Micron Technology   | 5         | 6      | 1.98%   |
| Intenso             | 5         | 5      | 1.98%   |
| SPCC                | 4         | 5      | 1.59%   |
| LITEONIT            | 4         | 5      | 1.59%   |
| China               | 4         | 5      | 1.59%   |
| Apple               | 4         | 4      | 1.59%   |
| PNY                 | 3         | 4      | 1.19%   |
| Lexar               | 3         | 3      | 1.19%   |
| Intel               | 3         | 3      | 1.19%   |
| Verbatim            | 2         | 2      | 0.79%   |
| Team                | 2         | 3      | 0.79%   |
| Super Talent        | 2         | 2      | 0.79%   |
| Patriot             | 2         | 2      | 0.79%   |
| OCZ                 | 2         | 2      | 0.79%   |
| Netac               | 2         | 2      | 0.79%   |
| KingSpec            | 2         | 3      | 0.79%   |
| GOODRAM             | 2         | 2      | 0.79%   |
| Gigabyte Technology | 2         | 2      | 0.79%   |
| USB30               | 1         | 3      | 0.4%    |
| Transcend           | 1         | 1      | 0.4%    |
| SuperSSpeed         | 1         | 2      | 0.4%    |
| Star                | 1         | 1      | 0.4%    |
| Smartbuy            | 1         | 1      | 0.4%    |
| Seagate             | 1         | 1      | 0.4%    |
| PHISON              | 1         | 1      | 0.4%    |
| OWC                 | 1         | 1      | 0.4%    |
| MyDigitalSSD        | 1         | 1      | 0.4%    |
| Mushkin             | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.4%    |
| INNOVATION IT       | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| BUFFALO             | 1         | 1      | 0.4%    |
| Apacer              | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 255       | 380    | 39.84%  |
| SSD     | 223       | 299    | 34.84%  |
| NVMe    | 121       | 157    | 18.91%  |
| MMC     | 26        | 35     | 4.06%   |
| Unknown | 15        | 21     | 2.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 407       | 656    | 69.69%  |
| NVMe | 121       | 157    | 20.72%  |
| SAS  | 30        | 44     | 5.14%   |
| MMC  | 26        | 35     | 4.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 299       | 398    | 58.97%  |
| 0.51-1.0   | 150       | 198    | 29.59%  |
| 1.01-2.0   | 39        | 54     | 7.69%   |
| 3.01-4.0   | 13        | 19     | 2.56%   |
| 4.01-10.0  | 4         | 6      | 0.79%   |
| 2.01-3.0   | 2         | 4      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 149       | 29.74%  |
| 251-500        | 128       | 25.55%  |
| 501-1000       | 79        | 15.77%  |
| 51-100         | 54        | 10.78%  |
| 1001-2000      | 27        | 5.39%   |
| More than 3000 | 17        | 3.39%   |
| 21-50          | 17        | 3.39%   |
| 2001-3000      | 12        | 2.4%    |
| 1-20           | 9         | 1.8%    |
| Unknown        | 9         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 223       | 43.64%  |
| 21-50          | 134       | 26.22%  |
| 101-250        | 48        | 9.39%   |
| 51-100         | 43        | 8.41%   |
| 251-500        | 18        | 3.52%   |
| 501-1000       | 15        | 2.94%   |
| More than 3000 | 11        | 2.15%   |
| Unknown        | 9         | 1.76%   |
| 1001-2000      | 8         | 1.57%   |
| 2001-3000      | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB        | 2         | 2      | 18.18%  |
| WDC WD10JPVX-22JC3T0 1TB       | 1         | 1      | 9.09%   |
| WDC WD10EZEX-21M2NA0 1TB       | 1         | 2      | 9.09%   |
| Toshiba MK3265GSX 320GB        | 1         | 1      | 9.09%   |
| Seagate ST9500420AS 500GB      | 1         | 1      | 9.09%   |
| Seagate ST9200420ASG 200GB     | 1         | 1      | 9.09%   |
| Seagate ST4000DM004-2CV104 4TB | 1         | 1      | 9.09%   |
| Seagate ST2000DM001-9YN164 2TB | 1         | 1      | 9.09%   |
| Seagate ST2000DL003-9VT166 2TB | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB     | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| Toshiba | 3         | 3      | 27.27%  |
| WDC     | 2         | 3      | 18.18%  |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| Toshiba | 3         | 3      | 27.27%  |
| WDC     | 2         | 3      | 18.18%  |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 12     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 454       | 814    | 88.85%  |
| Works    | 45        | 65     | 8.81%   |
| Malfunc  | 11        | 12     | 2.15%   |
| Failed   | 1         | 1      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 344       | 58.11%  |
| AMD                              | 101       | 17.06%  |
| Samsung Electronics              | 51        | 8.61%   |
| Sandisk                          | 20        | 3.38%   |
| Phison Electronics               | 11        | 1.86%   |
| SK Hynix                         | 7         | 1.18%   |
| ASMedia Technology               | 7         | 1.18%   |
| Silicon Motion                   | 5         | 0.84%   |
| KIOXIA                           | 5         | 0.84%   |
| Toshiba America Info Systems     | 4         | 0.68%   |
| Nvidia                           | 4         | 0.68%   |
| Micron Technology                | 4         | 0.68%   |
| ADATA Technology                 | 4         | 0.68%   |
| Silicon Image                    | 3         | 0.51%   |
| Micron/Crucial Technology        | 3         | 0.51%   |
| Kingston Technology Company      | 3         | 0.51%   |
| JMicron Technology               | 3         | 0.51%   |
| VIA Technologies                 | 2         | 0.34%   |
| Marvell Technology Group         | 2         | 0.34%   |
| Lite-On Technology               | 2         | 0.34%   |
| Solid State Storage Technology   | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Realtek Semiconductor            | 1         | 0.17%   |
| LSI Logic / Symbios Logic        | 1         | 0.17%   |
| Broadcom / LSI                   | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |
| Adaptec                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 66        | 9.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 31        | 4.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23        | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22        | 3.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 22        | 3.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 3.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 21        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 21        | 3.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15        | 2.22%   |
| Intel SATA Controller [RAID mode]                                                       | 13        | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 1.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11        | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9         | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 1.19%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.19%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 7         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 6         | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 0.89%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 6         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.74%   |
| Phison E12 NVMe Controller                                                              | 5         | 0.74%   |
| KIOXIA Non-Volatile memory controller                                                   | 5         | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 0.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 5         | 0.74%   |
| AMD FCH SATA Controller D                                                               | 5         | 0.74%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 0.59%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.59%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4         | 0.59%   |
| Micron Non-Volatile memory controller                                                   | 4         | 0.59%   |
| Intel SSD 660P Series                                                                   | 4         | 0.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.59%   |
| AMD FCH IDE Controller                                                                  | 4         | 0.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.44%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.44%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3         | 0.44%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3         | 0.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 374       | 61.31%  |
| NVMe | 121       | 19.84%  |
| IDE  | 68        | 11.15%  |
| RAID | 45        | 7.38%   |
| SAS  | 1         | 0.16%   |
| SCSI | 1         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 383       | 77.22%  |
| AMD    | 113       | 22.78%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 1.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.41%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 6         | 1.21%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.21%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.81%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.81%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 3         | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 3         | 0.6%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.6%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 0.6%    |
| Intel Core i5-6600K CPU @ 3.50GHz             | 3         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.6%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz              | 3         | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.6%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.6%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.6%    |
| Intel Core i3-8100 CPU @ 3.60GHz              | 3         | 0.6%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3         | 0.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.6%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.6%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 3         | 0.6%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.6%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.6%    |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 3         | 0.6%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.4%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.4%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.4%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.4%    |
| Intel Core i9-10900K CPU @ 3.70GHz            | 2         | 0.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.4%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.4%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.4%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.4%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.4%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.4%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.4%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.4%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.4%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 136       | 27.42%  |
| Intel Core i7                        | 81        | 16.33%  |
| Intel Core i3                        | 49        | 9.88%   |
| Intel Celeron                        | 26        | 5.24%   |
| AMD Ryzen 5                          | 25        | 5.04%   |
| Intel Core 2 Duo                     | 20        | 4.03%   |
| AMD Ryzen 7                          | 16        | 3.23%   |
| AMD FX                               | 16        | 3.23%   |
| Other                                | 14        | 2.82%   |
| Intel Atom                           | 12        | 2.42%   |
| Intel Xeon                           | 11        | 2.22%   |
| AMD A6                               | 11        | 2.22%   |
| Intel Pentium                        | 10        | 2.02%   |
| AMD Ryzen 3                          | 8         | 1.61%   |
| Intel Core 2 Quad                    | 7         | 1.41%   |
| Intel Pentium Dual-Core              | 5         | 1.01%   |
| AMD A10                              | 5         | 1.01%   |
| Intel Pentium Dual                   | 3         | 0.6%    |
| Intel Core i9                        | 3         | 0.6%    |
| AMD Ryzen 9                          | 3         | 0.6%    |
| AMD A8                               | 3         | 0.6%    |
| Intel Pentium Silver                 | 2         | 0.4%    |
| AMD Phenom II X4                     | 2         | 0.4%    |
| AMD GX                               | 2         | 0.4%    |
| AMD E2                               | 2         | 0.4%    |
| AMD E1                               | 2         | 0.4%    |
| AMD Athlon X4                        | 2         | 0.4%    |
| AMD A4                               | 2         | 0.4%    |
| Intel Pentium Gold                   | 1         | 0.2%    |
| Intel Pentium 4                      | 1         | 0.2%    |
| Intel Core m5                        | 1         | 0.2%    |
| Intel Core M                         | 1         | 0.2%    |
| Intel Core 2                         | 1         | 0.2%    |
| Intel Celeron M                      | 1         | 0.2%    |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.2%    |
| AMD Turion 64 Mobile                 | 1         | 0.2%    |
| AMD Sempron                          | 1         | 0.2%    |
| AMD Ryzen 7 PRO                      | 1         | 0.2%    |
| AMD Ryzen 5 PRO                      | 1         | 0.2%    |
| AMD Phenom II X6                     | 1         | 0.2%    |
| AMD Opteron                          | 1         | 0.2%    |
| AMD E                                | 1         | 0.2%    |
| AMD C-60                             | 1         | 0.2%    |
| AMD Athlon II X3                     | 1         | 0.2%    |
| AMD Athlon 64 X2                     | 1         | 0.2%    |
| AMD Athlon                           | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 219       | 44.15%  |
| 4      | 205       | 41.33%  |
| 6      | 30        | 6.05%   |
| 8      | 22        | 4.44%   |
| 1      | 7         | 1.41%   |
| 3      | 6         | 1.21%   |
| 12     | 3         | 0.6%    |
| 10     | 3         | 0.6%    |
| 16     | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 495       | 99.8%   |
| 2      | 1         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 321       | 64.72%  |
| 1      | 175       | 35.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 496       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 47        | 9.38%   |
| 0x306a9    | 39        | 7.78%   |
| Unknown    | 31        | 6.19%   |
| 0x306c3    | 26        | 5.19%   |
| 0x40651    | 22        | 4.39%   |
| 0x1067a    | 20        | 3.99%   |
| 0x806ea    | 17        | 3.39%   |
| 0x506e3    | 14        | 2.79%   |
| 0x08701021 | 12        | 2.4%    |
| 0x806ec    | 11        | 2.2%    |
| 0x406e3    | 11        | 2.2%    |
| 0x906e9    | 10        | 2%      |
| 0x806e9    | 10        | 2%      |
| 0x406c4    | 10        | 2%      |
| 0x20655    | 10        | 2%      |
| 0x06000852 | 10        | 2%      |
| 0x806c1    | 9         | 1.8%    |
| 0x6fb      | 9         | 1.8%    |
| 0x306d4    | 9         | 1.8%    |
| 0x30678    | 9         | 1.8%    |
| 0x906ea    | 8         | 1.6%    |
| 0x706e5    | 8         | 1.6%    |
| 0x08108102 | 7         | 1.4%    |
| 0xa0655    | 6         | 1.2%    |
| 0x506c9    | 6         | 1.2%    |
| 0x20652    | 6         | 1.2%    |
| 0x08108109 | 6         | 1.2%    |
| 0x07030105 | 6         | 1.2%    |
| 0x06001119 | 6         | 1.2%    |
| 0x6fd      | 5         | 1%      |
| 0x0600063e | 5         | 1%      |
| 0xa0652    | 4         | 0.8%    |
| 0x706a1    | 4         | 0.8%    |
| 0x10676    | 4         | 0.8%    |
| 0x08600106 | 4         | 0.8%    |
| 0x906eb    | 3         | 0.6%    |
| 0x806eb    | 3         | 0.6%    |
| 0x40661    | 3         | 0.6%    |
| 0x206c2    | 3         | 0.6%    |
| 0x0a201016 | 3         | 0.6%    |
| 0x08701013 | 3         | 0.6%    |
| 0x0800820d | 3         | 0.6%    |
| 0x07030106 | 3         | 0.6%    |
| 0x0700010f | 3         | 0.6%    |
| 0x06006705 | 3         | 0.6%    |
| 0x06003106 | 3         | 0.6%    |
| 0x05000119 | 3         | 0.6%    |
| 0x010000c8 | 3         | 0.6%    |
| 0xa0653    | 2         | 0.4%    |
| 0x706a8    | 2         | 0.4%    |
| 0x6f6      | 2         | 0.4%    |
| 0x08608103 | 2         | 0.4%    |
| 0x08600104 | 2         | 0.4%    |
| 0x08600103 | 2         | 0.4%    |
| 0x08101016 | 2         | 0.4%    |
| 0x06006704 | 2         | 0.4%    |
| 0x0600611a | 2         | 0.4%    |
| 0x02000057 | 2         | 0.4%    |
| 0xf43      | 1         | 0.2%    |
| 0xa0671    | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 71        | 14.31%  |
| Haswell         | 55        | 11.09%  |
| SandyBridge     | 50        | 10.08%  |
| IvyBridge       | 40        | 8.06%   |
| Skylake         | 26        | 5.24%   |
| Zen 2           | 24        | 4.84%   |
| Penryn          | 24        | 4.84%   |
| Silvermont      | 21        | 4.23%   |
| Westmere        | 20        | 4.03%   |
| Zen+            | 17        | 3.43%   |
| Core            | 17        | 3.43%   |
| Piledriver      | 16        | 3.23%   |
| CometLake       | 12        | 2.42%   |
| TigerLake       | 10        | 2.02%   |
| Puma            | 10        | 2.02%   |
| Broadwell       | 10        | 2.02%   |
| Icelake         | 9         | 1.81%   |
| Excavator       | 7         | 1.41%   |
| Zen             | 6         | 1.21%   |
| Goldmont plus   | 6         | 1.21%   |
| Goldmont        | 6         | 1.21%   |
| Zen 3           | 5         | 1.01%   |
| Jaguar          | 5         | 1.01%   |
| Bulldozer       | 5         | 1.01%   |
| K10             | 4         | 0.81%   |
| Steamroller     | 3         | 0.6%    |
| Nehalem         | 3         | 0.6%    |
| Bobcat          | 3         | 0.6%    |
| Unknown         | 3         | 0.6%    |
| K8 Hammer       | 2         | 0.4%    |
| K8 & K10 hybrid | 2         | 0.4%    |
| Tremont         | 1         | 0.2%    |
| NetBurst        | 1         | 0.2%    |
| K10 Llano       | 1         | 0.2%    |
| Bonnell         | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 286       | 50.44%  |
| Nvidia                           | 155       | 27.34%  |
| AMD                              | 122       | 21.52%  |
| Matrox Electronics Systems       | 2         | 0.35%   |
| VIA Technologies                 | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 6.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 3.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.79%   |
| Intel UHD Graphics 620                                                                   | 17        | 2.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.41%   |
| AMD Picasso                                                                              | 13        | 2.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.72%   |
| Intel HD Graphics 620                                                                    | 10        | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.55%   |
| Intel HD Graphics 630                                                                    | 9         | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.55%   |
| AMD Renoir                                                                               | 9         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 8         | 1.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.03%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 5         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.69%   |
| Intel HD Graphics 530                                                                    | 4         | 0.69%   |
| Intel HD Graphics 500                                                                    | 4         | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 0.69%   |
| Nvidia TU117M                                                                            | 3         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.52%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.52%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.52%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.52%   |
| AMD RS780L [Radeon 3000]                                                                 | 3         | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.52%   |
| AMD Lucienne                                                                             | 3         | 0.52%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.52%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.34%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.34%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.34%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 222       | 44.58%  |
| 1 x Nvidia     | 102       | 20.48%  |
| 1 x AMD        | 100       | 20.08%  |
| Intel + Nvidia | 46        | 9.24%   |
| Intel + AMD    | 9         | 1.81%   |
| 2 x AMD        | 7         | 1.41%   |
| AMD + Nvidia   | 7         | 1.41%   |
| 1 x Matrox     | 2         | 0.4%    |
| 2 x Intel      | 1         | 0.2%    |
| 1 x VIA        | 1         | 0.2%    |
| 1 x SiS        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 379       | 76.41%  |
| Proprietary | 100       | 20.16%  |
| Unknown     | 17        | 3.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 275       | 54.78%  |
| 1.01-2.0   | 62        | 12.35%  |
| 0.51-1.0   | 53        | 10.56%  |
| 0.01-0.5   | 45        | 8.96%   |
| 3.01-4.0   | 26        | 5.18%   |
| 7.01-8.0   | 17        | 3.39%   |
| 5.01-6.0   | 13        | 2.59%   |
| 2.01-3.0   | 6         | 1.2%    |
| 8.01-16.0  | 4         | 0.8%    |
| 16.01-24.0 | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 68        | 13.26%  |
| Samsung Electronics     | 67        | 13.06%  |
| Chimei Innolux          | 48        | 9.36%   |
| BOE                     | 42        | 8.19%   |
| LG Display              | 40        | 7.8%    |
| Dell                    | 24        | 4.68%   |
| Goldstar                | 21        | 4.09%   |
| Acer                    | 20        | 3.9%    |
| Apple                   | 15        | 2.92%   |
| AOC                     | 15        | 2.92%   |
| Hewlett-Packard         | 14        | 2.73%   |
| BenQ                    | 12        | 2.34%   |
| Sharp                   | 10        | 1.95%   |
| Philips                 | 10        | 1.95%   |
| Chi Mei Optoelectronics | 9         | 1.75%   |
| PANDA                   | 8         | 1.56%   |
| Lenovo                  | 8         | 1.56%   |
| Vizio                   | 7         | 1.36%   |
| Unknown                 | 6         | 1.17%   |
| LG Electronics          | 6         | 1.17%   |
| Ancor Communications    | 5         | 0.97%   |
| LGD                     | 4         | 0.78%   |
| Iiyama                  | 4         | 0.78%   |
| HPN                     | 4         | 0.78%   |
| ViewSonic               | 3         | 0.58%   |
| Sony                    | 3         | 0.58%   |
| Sceptre Tech            | 3         | 0.58%   |
| Vestel                  | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| MStar                   | 2         | 0.39%   |
| Microstep               | 2         | 0.39%   |
| InfoVision              | 2         | 0.39%   |
| HannStar                | 2         | 0.39%   |
| Gateway                 | 2         | 0.39%   |
| Fujitsu Siemens         | 2         | 0.39%   |
| AUS                     | 2         | 0.39%   |
| Unknown                 | 2         | 0.39%   |
| Xiaomi                  | 1         | 0.19%   |
| Vestel Elektronik       | 1         | 0.19%   |
| Toshiba                 | 1         | 0.19%   |
| Sceptre                 | 1         | 0.19%   |
| Sanyo                   | 1         | 0.19%   |
| PKB                     | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| ONN                     | 1         | 0.19%   |
| OEM                     | 1         | 0.19%   |
| Medion                  | 1         | 0.19%   |
| LG Philips              | 1         | 0.19%   |
| Lenovo Group Limited    | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| HCL                     | 1         | 0.19%   |
| Gigabyte Technology     | 1         | 0.19%   |
| GDH                     | 1         | 0.19%   |
| CPT                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 5         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 4         | 0.76%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 3         | 0.57%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.57%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.57%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch                | 2         | 0.38%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                                | 2         | 0.38%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch            | 2         | 0.38%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch   | 2         | 0.38%   |
| Samsung Electronics LCD Monitor LC32G7xT                                 | 2         | 0.38%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 2         | 0.38%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.38%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.38%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                      | 2         | 0.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 2         | 0.38%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch              | 2         | 0.38%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 2         | 0.38%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.38%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.38%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.38%   |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                     | 2         | 0.38%   |
| Unknown                                                                  | 2         | 0.38%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                       | 1         | 0.19%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                           | 1         | 0.19%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                     | 1         | 0.19%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                      | 1         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 203       | 40.12%  |
| 1366x768 (WXGA)    | 130       | 25.69%  |
| 3840x2160 (4K)     | 31        | 6.13%   |
| 1600x900 (HD+)     | 22        | 4.35%   |
| Unknown            | 19        | 3.75%   |
| 1680x1050 (WSXGA+) | 11        | 2.17%   |
| 1280x800 (WXGA)    | 11        | 2.17%   |
| 3840x1080          | 9         | 1.78%   |
| 2560x1440 (QHD)    | 9         | 1.78%   |
| 1440x900 (WXGA+)   | 8         | 1.58%   |
| 1920x1200 (WUXGA)  | 5         | 0.99%   |
| 3440x1440          | 4         | 0.79%   |
| 3200x1800 (QHD+)   | 4         | 0.79%   |
| 2880x1800          | 3         | 0.59%   |
| 2560x1600          | 3         | 0.59%   |
| 2256x1504          | 3         | 0.59%   |
| 1360x768           | 3         | 0.59%   |
| 1280x1024 (SXGA)   | 3         | 0.59%   |
| 5760x2160          | 2         | 0.4%    |
| 3840x2400          | 2         | 0.4%    |
| 2560x1080          | 2         | 0.4%    |
| 4480x1600          | 1         | 0.2%    |
| 4480x1440          | 1         | 0.2%    |
| 4160x1440          | 1         | 0.2%    |
| 3840x1200          | 1         | 0.2%    |
| 3600x1080          | 1         | 0.2%    |
| 3360x1080          | 1         | 0.2%    |
| 3360x1050          | 1         | 0.2%    |
| 3200x1200          | 1         | 0.2%    |
| 3120x1050          | 1         | 0.2%    |
| 2944x1080          | 1         | 0.2%    |
| 2464x900           | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1920x515           | 1         | 0.2%    |
| 1834x1031          | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |
| 1024x600           | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 135       | 27.05%  |
| 13      | 64        | 12.83%  |
| Unknown | 62        | 12.42%  |
| 27      | 31        | 6.21%   |
| 14      | 30        | 6.01%   |
| 24      | 27        | 5.41%   |
| 17      | 24        | 4.81%   |
| 21      | 20        | 4.01%   |
| 23      | 18        | 3.61%   |
| 31      | 10        | 2%      |
| 18      | 10        | 2%      |
| 11      | 9         | 1.8%    |
| 22      | 8         | 1.6%    |
| 19      | 6         | 1.2%    |
| 34      | 5         | 1%      |
| 20      | 5         | 1%      |
| 12      | 5         | 1%      |
| 84      | 4         | 0.8%    |
| 48      | 3         | 0.6%    |
| 74      | 2         | 0.4%    |
| 46      | 2         | 0.4%    |
| 41      | 2         | 0.4%    |
| 32      | 2         | 0.4%    |
| 25      | 2         | 0.4%    |
| 10      | 2         | 0.4%    |
| 72      | 1         | 0.2%    |
| 64      | 1         | 0.2%    |
| 55      | 1         | 0.2%    |
| 52      | 1         | 0.2%    |
| 49      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 40      | 1         | 0.2%    |
| 37      | 1         | 0.2%    |
| 36      | 1         | 0.2%    |
| 26      | 1         | 0.2%    |
| 16      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 194       | 39.35%  |
| 501-600     | 72        | 14.6%   |
| Unknown     | 62        | 12.58%  |
| 201-300     | 48        | 9.74%   |
| 401-500     | 45        | 9.13%   |
| 351-400     | 29        | 5.88%   |
| 601-700     | 14        | 2.84%   |
| 1001-1500   | 9         | 1.83%   |
| 701-800     | 8         | 1.62%   |
| 1501-2000   | 7         | 1.42%   |
| 901-1000    | 3         | 0.61%   |
| 801-900     | 2         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 343       | 74.4%   |
| Unknown | 59        | 12.8%   |
| 16/10   | 45        | 9.76%   |
| 21/9    | 5         | 1.08%   |
| 3/2     | 3         | 0.65%   |
| 5/4     | 2         | 0.43%   |
| 4/3     | 2         | 0.43%   |
| 32/9    | 1         | 0.22%   |
| 3.73    | 1         | 0.22%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 136       | 27.36%  |
| 81-90          | 71        | 14.29%  |
| 201-250        | 62        | 12.47%  |
| Unknown        | 62        | 12.47%  |
| 301-350        | 31        | 6.24%   |
| 71-80          | 23        | 4.63%   |
| 121-130        | 20        | 4.02%   |
| 351-500        | 17        | 3.42%   |
| 151-200        | 17        | 3.42%   |
| More than 1000 | 13        | 2.62%   |
| 51-60          | 9         | 1.81%   |
| 251-300        | 9         | 1.81%   |
| 501-1000       | 9         | 1.81%   |
| 141-150        | 8         | 1.61%   |
| 61-70          | 5         | 1.01%   |
| 41-50          | 2         | 0.4%    |
| 131-140        | 2         | 0.4%    |
| 91-100         | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 156       | 32.1%   |
| 51-100        | 116       | 23.87%  |
| 121-160       | 107       | 22.02%  |
| Unknown       | 62        | 12.76%  |
| 161-240       | 22        | 4.53%   |
| 1-50          | 12        | 2.47%   |
| More than 240 | 11        | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 411       | 82.2%   |
| 2     | 71        | 14.2%   |
| 0     | 17        | 3.4%    |
| 3     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 278       | 36.1%   |
| Intel                             | 220       | 28.57%  |
| Qualcomm Atheros                  | 96        | 12.47%  |
| Broadcom                          | 46        | 5.97%   |
| Broadcom Limited                  | 17        | 2.21%   |
| Ralink Technology                 | 13        | 1.69%   |
| Ralink                            | 10        | 1.3%    |
| TP-Link                           | 9         | 1.17%   |
| Marvell Technology Group          | 6         | 0.78%   |
| DisplayLink                       | 6         | 0.78%   |
| Huawei Technologies               | 5         | 0.65%   |
| Dell                              | 5         | 0.65%   |
| ASIX Electronics                  | 5         | 0.65%   |
| Xiaomi                            | 4         | 0.52%   |
| Samsung Electronics               | 4         | 0.52%   |
| D-Link System                     | 4         | 0.52%   |
| T & A Mobile Phones               | 3         | 0.39%   |
| Nvidia                            | 3         | 0.39%   |
| MEDIATEK                          | 3         | 0.39%   |
| Realtek                           | 2         | 0.26%   |
| Qualcomm                          | 2         | 0.26%   |
| OPPO Electronics                  | 2         | 0.26%   |
| NetGear                           | 2         | 0.26%   |
| Motorola PCS                      | 2         | 0.26%   |
| Microsoft                         | 2         | 0.26%   |
| Linksys                           | 2         | 0.26%   |
| Google                            | 2         | 0.26%   |
| Edimax Technology                 | 2         | 0.26%   |
| ZyXEL Communications              | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.13%   |
| Sierra Wireless                   | 1         | 0.13%   |
| Panasonic (Matsushita)            | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.13%   |
| Novatel Wireless                  | 1         | 0.13%   |
| Motorola BCS                      | 1         | 0.13%   |
| Lenovo                            | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Gemtek                            | 1         | 0.13%   |
| FIBOCOM                           | 1         | 0.13%   |
| Exar                              | 1         | 0.13%   |
| Ericsson Business Mobile Networks | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| ADMtek                            | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190       | 21.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 20        | 2.21%   |
| Intel Wi-Fi 6 AX200                                               | 18        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 1.66%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.22%   |
| Intel Wireless 8260                                               | 11        | 1.22%   |
| Intel Wireless 7260                                               | 11        | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1%      |
| Intel Wireless 7265                                               | 9         | 1%      |
| Intel Wireless 3165                                               | 9         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1%      |
| Intel Wi-Fi 6 AX201                                               | 8         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.77%   |
| Realtek 802.11ac NIC                                              | 7         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.77%   |
| Intel WiFi Link 5100                                              | 7         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 6         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.55%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.55%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.44%   |
| Intel Wireless 3160                                               | 4         | 0.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 0.44%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.44%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 169       | 40.43%  |
| Qualcomm Atheros       | 76        | 18.18%  |
| Realtek Semiconductor  | 75        | 17.94%  |
| Broadcom               | 30        | 7.18%   |
| Ralink Technology      | 13        | 3.11%   |
| Broadcom Limited       | 12        | 2.87%   |
| Ralink                 | 10        | 2.39%   |
| TP-Link                | 9         | 2.15%   |
| D-Link System          | 3         | 0.72%   |
| Realtek                | 2         | 0.48%   |
| NetGear                | 2         | 0.48%   |
| Microsoft              | 2         | 0.48%   |
| Linksys                | 2         | 0.48%   |
| Edimax Technology      | 2         | 0.48%   |
| Dell                   | 2         | 0.48%   |
| ZyXEL Communications   | 1         | 0.24%   |
| Sierra Wireless        | 1         | 0.24%   |
| Qualcomm               | 1         | 0.24%   |
| Panasonic (Matsushita) | 1         | 0.24%   |
| MEDIATEK               | 1         | 0.24%   |
| Gemtek                 | 1         | 0.24%   |
| FIBOCOM                | 1         | 0.24%   |
| D-Link                 | 1         | 0.24%   |
| ADMtek                 | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20        | 4.75%   |
| Intel Wi-Fi 6 AX200                                            | 18        | 4.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 3.56%   |
| Intel Wireless 8265 / 8275                                     | 12        | 2.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.61%   |
| Intel Wireless 8260                                            | 11        | 2.61%   |
| Intel Wireless 7260                                            | 11        | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.38%   |
| Intel Wireless 7265                                            | 9         | 2.14%   |
| Intel Wireless 3165                                            | 9         | 2.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.14%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.66%   |
| Realtek 802.11ac NIC                                           | 7         | 1.66%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 1.66%   |
| Intel WiFi Link 5100                                           | 7         | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.66%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.19%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.19%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.95%   |
| Intel Wireless 3160                                            | 4         | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.95%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.71%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 0.71%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 0.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.48%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 2         | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.48%   |
| Realtek 802.11n NIC                                            | 2         | 0.48%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.48%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 2         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 254       | 54.51%  |
| Intel                            | 106       | 22.75%  |
| Qualcomm Atheros                 | 30        | 6.44%   |
| Broadcom                         | 22        | 4.72%   |
| Marvell Technology Group         | 6         | 1.29%   |
| DisplayLink                      | 6         | 1.29%   |
| Broadcom Limited                 | 6         | 1.29%   |
| Huawei Technologies              | 5         | 1.07%   |
| ASIX Electronics                 | 5         | 1.07%   |
| Xiaomi                           | 4         | 0.86%   |
| Samsung Electronics              | 4         | 0.86%   |
| Nvidia                           | 3         | 0.64%   |
| OPPO Electronics                 | 2         | 0.43%   |
| Motorola PCS                     | 2         | 0.43%   |
| MediaTek                         | 2         | 0.43%   |
| Google                           | 2         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Qualcomm                         | 1         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.21%   |
| Novatel Wireless                 | 1         | 0.21%   |
| Motorola BCS                     | 1         | 0.21%   |
| ICS Advent                       | 1         | 0.21%   |
| D-Link System                    | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190       | 40.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 7.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 6.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 0.84%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.84%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.63%   |
| Huawei E353/E3131                                                 | 3         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.42%   |
| OPPO SDM712-MTP _SN:E0B69F21                                      | 2         | 0.42%   |
| Motorola PCS moto g(7)                                            | 2         | 0.42%   |
| MediaTek moto g(8) power lite                                     | 2         | 0.42%   |
| Intel Ethernet controller                                         | 2         | 0.42%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.42%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.42%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.42%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2         | 0.42%   |
| Huawei BLA-L29                                                    | 2         | 0.42%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.42%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.21%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.21%   |
| Qualcomm SDM660-MTP _SN:8F667B4D                                  | 1         | 0.21%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.21%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.21%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 436       | 52.03%  |
| WiFi     | 393       | 46.9%   |
| Modem    | 6         | 0.72%   |
| Unknown  | 3         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 400       | 52.29%  |
| WiFi     | 362       | 47.32%  |
| Unknown  | 2         | 0.26%   |
| Modem    | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 287       | 57.86%  |
| 1     | 187       | 37.7%   |
| 0     | 15        | 3.02%   |
| 3     | 7         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 348       | 69.6%   |
| Yes  | 152       | 30.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 40.84%  |
| Realtek Semiconductor           | 36        | 11.58%  |
| Qualcomm Atheros Communications | 32        | 10.29%  |
| Cambridge Silicon Radio         | 19        | 6.11%   |
| Broadcom                        | 16        | 5.14%   |
| Apple                           | 15        | 4.82%   |
| Lite-On Technology              | 13        | 4.18%   |
| IMC Networks                    | 11        | 3.54%   |
| Foxconn / Hon Hai               | 11        | 3.54%   |
| Dell                            | 7         | 2.25%   |
| ASUSTek Computer                | 5         | 1.61%   |
| Toshiba                         | 4         | 1.29%   |
| Ralink                          | 4         | 1.29%   |
| Integrated System Solution      | 2         | 0.64%   |
| Hewlett-Packard                 | 2         | 0.64%   |
| Foxconn International           | 2         | 0.64%   |
| Micro Star International        | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |
| Belkin Components               | 1         | 0.32%   |
| Askey Computer                  | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 11.9%   |
| Intel Bluetooth Device                                                              | 32        | 10.29%  |
| Realtek Bluetooth Radio                                                             | 24        | 7.72%   |
| Intel AX201 Bluetooth                                                               | 19        | 6.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 6.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 5.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 4.82%   |
| Intel AX200 Bluetooth                                                               | 13        | 4.18%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 2.57%   |
| Lite-On Bluetooth Device                                                            | 7         | 2.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.61%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 1.61%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 1.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.29%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.29%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 1.29%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.29%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.29%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.96%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 3         | 0.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.96%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.64%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.64%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.64%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.64%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.64%   |
| Dell BT Mini-Receiver                                                               | 2         | 0.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.64%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 2         | 0.64%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.32%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.32%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.32%   |
| Toshiba Askey for                                                                   | 1         | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.32%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.32%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.32%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.32%   |
| MediaTek MT7630e Bluetooth Adapter                                                  | 1         | 0.32%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.32%   |
| IMC Networks Bluetooth                                                              | 1         | 0.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.32%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.32%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.32%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.32%   |
| Broadcom Bluetooth                                                                  | 1         | 0.32%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.32%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 362       | 53.31%  |
| AMD                              | 141       | 20.77%  |
| Nvidia                           | 124       | 18.26%  |
| Texas Instruments                | 5         | 0.74%   |
| Creative Labs                    | 5         | 0.74%   |
| C-Media Electronics              | 5         | 0.74%   |
| Razer USA                        | 3         | 0.44%   |
| Logitech                         | 3         | 0.44%   |
| JMTek                            | 3         | 0.44%   |
| Corsair                          | 3         | 0.44%   |
| SteelSeries ApS                  | 2         | 0.29%   |
| GN Netcom                        | 2         | 0.29%   |
| XMOS                             | 1         | 0.15%   |
| VIA Technologies                 | 1         | 0.15%   |
| Valve Software                   | 1         | 0.15%   |
| Tenx Technology                  | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Sennheiser Communications        | 1         | 0.15%   |
| SAVITECH                         | 1         | 0.15%   |
| Samsung Electronics              | 1         | 0.15%   |
| ROCCAT                           | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| Numark                           | 1         | 0.15%   |
| Micronas                         | 1         | 0.15%   |
| Klipsch Audio                    | 1         | 0.15%   |
| Kingston Technology              | 1         | 0.15%   |
| Insignia (Best Buy)              | 1         | 0.15%   |
| iConnectivity                    | 1         | 0.15%   |
| GEMBIRD                          | 1         | 0.15%   |
| Focusrite-Novation               | 1         | 0.15%   |
| FIFINE Microphones               | 1         | 0.15%   |
| Creative Technology              | 1         | 0.15%   |
| ASUSTek Computer                 | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 45        | 5.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 44        | 5.45%   |
| Intel Sunrise Point-LP HD Audio                                                   | 43        | 5.32%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 32        | 3.96%   |
| AMD FCH Azalia Controller                                                         | 27        | 3.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 26        | 3.22%   |
| Intel Haswell-ULT HD Audio Controller                                             | 23        | 2.85%   |
| Intel 8 Series HD Audio Controller                                                | 23        | 2.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 22        | 2.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 19        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18        | 2.23%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17        | 2.1%    |
| AMD Kabini HDMI/DP Audio                                                          | 16        | 1.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 15        | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 14        | 1.73%   |
| Nvidia GF108 High Definition Audio Controller                                     | 12        | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                        | 12        | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 12        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 11        | 1.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 11        | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 10        | 1.24%   |
| Nvidia GF119 HDMI Audio Controller                                                | 9         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 9         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                         | 9         | 1.11%   |
| Intel CM238 HD Audio Controller                                                   | 9         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                | 9         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 9         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                     | 8         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 8         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 8         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 8         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 7         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                                     | 7         | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 7         | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 6         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 6         | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6         | 0.74%   |
| Intel 200 Series PCH HD Audio                                                     | 5         | 0.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5         | 0.62%   |
| AMD High Definition Audio Controller                                              | 5         | 0.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5         | 0.62%   |
| Nvidia High Definition Audio Controller                                           | 4         | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                     | 4         | 0.5%    |
| Nvidia GM204 High Definition Audio Controller                                     | 4         | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                | 4         | 0.5%    |
| Nvidia Audio device                                                               | 4         | 0.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4         | 0.5%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4         | 0.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4         | 0.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                     | 3         | 0.37%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 0.37%   |
| JMTek USB PnP Audio Device                                                        | 3         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 23.26%  |
| SK Hynix            | 16        | 18.6%   |
| Micron Technology   | 13        | 15.12%  |
| Unknown             | 9         | 10.47%  |
| Kingston            | 5         | 5.81%   |
| Crucial             | 5         | 5.81%   |
| A-DATA Technology   | 5         | 5.81%   |
| Corsair             | 4         | 4.65%   |
| Ramaxel Technology  | 3         | 3.49%   |
| G.Skill             | 2         | 2.33%   |
| Unknown (ABCD)      | 1         | 1.16%   |
| Team                | 1         | 1.16%   |
| Strontium           | 1         | 1.16%   |
| Nanya Technology    | 1         | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 3.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 3.19%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 8192MB Row Of Chips LPDDR4 4267MT/s   | 2         | 2.13%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 2.13%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 2.13%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 2         | 2.13%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 1.06%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s             | 1         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                           | 1         | 1.06%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 1.06%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 1.06%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                  | 1         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM DDR3 2400MT/s   | 1         | 1.06%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s               | 1         | 1.06%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 1.06%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.06%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.06%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.06%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1.06%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 1.06%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s            | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 1.06%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 1         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.06%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s              | 1         | 1.06%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                 | 1         | 1.06%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4096MB SODIMM DDR4 2400MT/s         | 1         | 1.06%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.06%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1024MB SODIMM DDR 667MT/s               | 1         | 1.06%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.06%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                           | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 49.33%  |
| DDR3    | 22        | 29.33%  |
| LPDDR4  | 5         | 6.67%   |
| LPDDR3  | 3         | 4%      |
| DDR2    | 3         | 4%      |
| Unknown | 3         | 4%      |
| SDRAM   | 2         | 2.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 63.51%  |
| DIMM         | 19        | 25.68%  |
| Row Of Chips | 7         | 9.46%   |
| Chip         | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 32        | 39.51%  |
| 8192  | 31        | 38.27%  |
| 2048  | 10        | 12.35%  |
| 16384 | 4         | 4.94%   |
| 32768 | 2         | 2.47%   |
| 1024  | 2         | 2.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 22.22%  |
| 2667  | 15        | 18.52%  |
| 3200  | 9         | 11.11%  |
| 2400  | 7         | 8.64%   |
| 2133  | 7         | 8.64%   |
| 1333  | 5         | 6.17%   |
| 4267  | 3         | 3.7%    |
| 3266  | 3         | 3.7%    |
| 1334  | 3         | 3.7%    |
| 4199  | 2         | 2.47%   |
| 800   | 2         | 2.47%   |
| 667   | 2         | 2.47%   |
| 3600  | 1         | 1.23%   |
| 2933  | 1         | 1.23%   |
| 2800  | 1         | 1.23%   |
| 1867  | 1         | 1.23%   |
| 1067  | 1         | 1.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 30%     |
| Canon               | 3         | 30%     |
| Seiko Epson         | 2         | 20%     |
| Samsung Electronics | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-202 203 206 Series | 1         | 10%     |
| Seiko Epson L3110 Series          | 1         | 10%     |
| Samsung SCX-3400 Series           | 1         | 10%     |
| HP OfficeJet 4650 series          | 1         | 10%     |
| HP LaserJet Professional P1102w   | 1         | 10%     |
| HP DeskJet 2700 series            | 1         | 10%     |
| Canon TR4500 series               | 1         | 10%     |
| Canon PIXMA MG2500 Series         | 1         | 10%     |
| Canon LiDE 400                    | 1         | 10%     |
| Brother DCP-L2540DW               | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| HP ScanJet 2400c     | 1         | 50%     |
| Canon CanoScan 8800F | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 19.87%  |
| Realtek Semiconductor                  | 34        | 11.45%  |
| IMC Networks                           | 26        | 8.75%   |
| Sunplus Innovation Technology          | 20        | 6.73%   |
| Microdia                               | 20        | 6.73%   |
| Acer                                   | 19        | 6.4%    |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.71%   |
| Quanta                                 | 12        | 4.04%   |
| Apple                                  | 12        | 4.04%   |
| Suyin                                  | 11        | 3.7%    |
| Syntek                                 | 9         | 3.03%   |
| Lite-On Technology                     | 8         | 2.69%   |
| Logitech                               | 7         | 2.36%   |
| Ricoh                                  | 4         | 1.35%   |
| Generalplus Technology                 | 4         | 1.35%   |
| Silicon Motion                         | 3         | 1.01%   |
| Samsung Electronics                    | 3         | 1.01%   |
| Luxvisions Innotech Limited            | 3         | 1.01%   |
| Alcor Micro                            | 3         | 1.01%   |
| Sunplus Technology                     | 2         | 0.67%   |
| Razer USA                              | 2         | 0.67%   |
| Primax Electronics                     | 2         | 0.67%   |
| Microsoft                              | 2         | 0.67%   |
| Genesys Logic                          | 2         | 0.67%   |
| YGTek                                  | 1         | 0.34%   |
| Y Media                                | 1         | 0.34%   |
| webcam vendor                          | 1         | 0.34%   |
| Teslong Camera                         | 1         | 0.34%   |
| Sonix Technology                       | 1         | 0.34%   |
| OmniVision Technologies                | 1         | 0.34%   |
| LG Electronics                         | 1         | 0.34%   |
| KYE Systems (Mouse Systems)            | 1         | 0.34%   |
| Jieli Technology                       | 1         | 0.34%   |
| Importek                               | 1         | 0.34%   |
| icSpring                               | 1         | 0.34%   |
| Huawei Technologies                    | 1         | 0.34%   |
| GEMBIRD                                | 1         | 0.34%   |
| DJKANA1RSF34LM                         | 1         | 0.34%   |
| ARC International                      | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 11        | 3.7%    |
| Chicony HD WebCam                                   | 8         | 2.69%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 2.36%   |
| IMC Networks Integrated Camera                      | 7         | 2.36%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 2.36%   |
| Microdia Integrated_Webcam_HD                       | 6         | 2.02%   |
| Apple FaceTime HD Camera (Built-in)                 | 6         | 2.02%   |
| Acer Integrated Camera                              | 6         | 2.02%   |
| Syntek Integrated Camera                            | 5         | 1.68%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 1.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.68%   |
| Chicony Integrated Camera                           | 5         | 1.68%   |
| Realtek Integrated Webcam                           | 4         | 1.35%   |
| Microdia Integrated Webcam                          | 4         | 1.35%   |
| Generalplus GENERAL WEBCAM                          | 4         | 1.35%   |
| Chicony VGA Webcam                                  | 4         | 1.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 4         | 1.35%   |
| Chicony HP TrueVision HD                            | 4         | 1.35%   |
| Chicony EasyCamera                                  | 4         | 1.35%   |
| Syntek Lenovo EasyCamera                            | 3         | 1.01%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 3         | 1.01%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.01%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 1.01%   |
| Realtek USB Camera                                  | 3         | 1.01%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.01%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.01%   |
| Chicony HD User Facing                              | 3         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 3         | 1.01%   |
| Acer Lenovo EasyCamera                              | 3         | 1.01%   |
| Suyin HP Truevision HD                              | 2         | 0.67%   |
| Sunplus HD WebCam                                   | 2         | 0.67%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 2         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.67%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.67%   |
| Realtek Integrated Webcam HD                        | 2         | 0.67%   |
| Razer USA Gaming Webcam [Kiyo]                      | 2         | 0.67%   |
| Quanta VGA WebCam                                   | 2         | 0.67%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.67%   |
| Quanta HD WebCam                                    | 2         | 0.67%   |
| Quanta HD User Facing                               | 2         | 0.67%   |
| Microdia Webcam Vitade AF                           | 2         | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.67%   |
| Logitech Webcam C270                                | 2         | 0.67%   |
| Logitech HD Pro Webcam C920                         | 2         | 0.67%   |
| Lite-On HP HD Camera                                | 2         | 0.67%   |
| IMC Networks USB Camera                             | 2         | 0.67%   |
| IMC Networks 2M Integrated Webcam                   | 2         | 0.67%   |
| Genesys Logic Camera                                | 2         | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.67%   |
| Chicony USB 2.0 Camera                              | 2         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.67%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 0.67%   |
| Apple FaceTime HD Camera                            | 2         | 0.67%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.67%   |
| Acer Lenovo EasyCamera integrated webcam            | 2         | 0.67%   |
| Acer HD Webcam                                      | 2         | 0.67%   |
| Acer EasyCamera                                     | 2         | 0.67%   |
| YGTek webcam                                        | 1         | 0.34%   |
| Y Media USB Camera                                  | 1         | 0.34%   |
| webcam vendor webcam product                        | 1         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 46.81%  |
| Upek                       | 8         | 17.02%  |
| Shenzhen Goodix Technology | 7         | 14.89%  |
| Synaptics                  | 3         | 6.38%   |
| AuthenTec                  | 3         | 6.38%   |
| LighTuning Technology      | 2         | 4.26%   |
| STMicroelectronics         | 1         | 2.13%   |
| Focal-systems.Corp         | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 14.89%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 10.64%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 8.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.38%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 4.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 4.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 4.26%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 4.26%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 4.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.13%   |
| Validity Sensors VFS491                                                    | 1         | 2.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.13%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.13%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.13%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.13%   |
| Synaptics  WBDI                                                            | 1         | 2.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.13%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.13%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.13%   |
| LighTuning Fingerprint Reader                                              | 1         | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.13%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.13%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.13%   |
| AuthenTec AES1600                                                          | 1         | 2.13%   |
| Unknown                                                                    | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 15        | 60%     |
| Alcor Micro           | 4         | 16%     |
| O2 Micro              | 2         | 8%      |
| Lenovo                | 2         | 8%      |
| Yubico.com            | 1         | 4%      |
| Advanced Card Systems | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 24%     |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 16%     |
| Broadcom 5880                                                                | 3         | 12%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4%      |
| Advanced Card Systems ACR39U                                                 | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 344       | 68.53%  |
| 1     | 128       | 25.5%   |
| 2     | 28        | 5.58%   |
| 3     | 2         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 25.54%  |
| Graphics card            | 38        | 20.65%  |
| Net/wireless             | 35        | 19.02%  |
| Chipcard                 | 22        | 11.96%  |
| Multimedia controller    | 20        | 10.87%  |
| Bluetooth                | 6         | 3.26%   |
| Storage                  | 5         | 2.72%   |
| Unassigned class         | 2         | 1.09%   |
| Sound                    | 2         | 1.09%   |
| Communication controller | 2         | 1.09%   |
| Storage/ide              | 1         | 0.54%   |
| Net/ethernet             | 1         | 0.54%   |
| Flash memory             | 1         | 0.54%   |
| Dvb card                 | 1         | 0.54%   |
| Camera                   | 1         | 0.54%   |

